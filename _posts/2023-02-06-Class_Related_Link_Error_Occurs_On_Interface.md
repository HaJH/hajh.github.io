---
title : 인터페이스에서 클래스 관련 링크 에러가 날 때
date: 2023-02-06 16:35:00 +0900
categories: [언리얼, 프로그래밍]
tags: [언리얼, 프로그래밍, 라이더]
---

요약 : `UINTERFACE(MinimalAPI)`  선언을 확인할 것. `UINTERFACE()` 일 경우 PrivateStaticClass() 등의 엔진 함수를 이용하지 못한다.

---

```cpp
const UClass* ClassType = T::UClassType::StaticClass();
```

위와 같이 인터페이스를 사용하던 중 원인불명의 링크 에러가 발생했다.

에러 메시지는 다음과 같았다.

- unresolved external symbol "private: static class UClass * __cdecl UMyInterface::GetPrivateStaticClass(void)" (?GetPrivateStaticClass@UMyInterface@@CAPEAVUClass@@XZ) referenced in function "class IMyInterface * __cdecl MyUtil::GetActorInterface<class IMyInterface>(class AActor *)" (??$GetActorInterface@VIMyInterface@@@MyUtil@@YAPEAVIMyInterface@@PEAVAActor@@@Z)

다른 모듈에 있는 인터페이스를 참조하던 중이라 모듈 간의 종속성 문제인가 싶었는데, 아니었다.

UMyInterface::GetPrivateStaticClass(void) 외부 심볼을 확인하지 못했다는 데서 문제의 원인을 찾을 수 있었다.

해당 함수는 언리얼 헤더 툴(UHT)에 의해 생성되는 함수 StaticClass()의 내부 함수이다.

즉, 내 모듈에서의 종속성 문제가 아니라 엔진 모듈과의 종속성 문제였다.

문제의 원인은 클래스를 생성할 때 에디터를 켜기가 싫어서 IDE(라이더)의 UnrealClass 생성 도구로 클래스를 생성했던 것이었다.

엔진을 통해서 생성한 인터페이스와 거의 동일한 보일러플레이트 코드가 생성되었지만 한 군데가 달랐다.

바로 UINTERFACE 매크로 부분이었다.

정상작동하는 다른 인터페이스 클래스와 비교해 본 결과, UINTERFACE() 매크로의 지정자가 잘못되어 있던 것을 확인할 수 있었다.

UINTERFACE() → UINTERFACE(MinimalAPI)로 수정하고 나니 링크 에러 없이 정상 동작했다.