---
title : 유용한 언리얼 엔진 코드 플러그인
date: 2023-02-06 19:14:00 +0900
categories: [언리얼]
tags: [언리얼, 플러그인]
---


직접 사용해본 플러그인 중에 유용했던 플러그인들을 모아보았다.

선정 기준은 내가 새 프로젝트를 시작할 때 설치하고 싶은 플러그인들이다.

UE5 기준이며, UE4까지만 지원하는 플러그인은 소개하지 않았다.

언리얼 엔진 마켓플레이스 관련 유용한 사이트

[Orbital Market](https://orbital-market.com/)

플러그인은 아니지만 모르는 사람이 있다면 소개하고 싶은 유용한 사이트.

인기순, 리뷰순 정렬 등을 지원한다.

---

# 생산성 관련

### 모듈 생성 도구 (New C++ Module Tool, C++ Module Generator)

[New C++ Module tool, 카테고리 코드 플러그인 - UE 마켓플레이스](https://www.unrealengine.com/marketplace/ko/product/new-c-module-tool/reviews)

[C++ Module Generator, 카테고리 코드 플러그인 - UE 마켓플레이스](https://www.unrealengine.com/marketplace/ko/product/c-module-generator)

에디터에서 클래스를 생성하는 것처럼 GUI로 모듈을 생성할 수 있게 해준다.

둘 다 써봤는데 위쪽의 New C++ Module Tool이 좀 더 좋다. 

하지만 나는 아래쪽의 C++ Module Generator를 사용한다. 이유는 별 거 없다. New C++ Module Tool은 매크로 부분 때문에 IDE의 솔루션 탐색기에 빨간 줄이 그어지기 때문이다.

이 기능은 에디터에 들어가야 한다고 생각하는 필수 플러그인이다. 

강력히 추천함.

### 콘텐츠 브라우저 북마크 (Easy Bookmarks)

[Easy Bookmarks, 카테고리 코드 플러그인 - UE 마켓플레이스](https://www.unrealengine.com/marketplace/ko/product/easy-bookmarks)

콘텐츠 브라우저의 특정 위치/에셋을 북마크로 만들어 별도의 창에 표시한다.

클릭하면 해당 북마크된 에셋을 편집할 수 있다.

단순하면서도 매우 편리한 도구. 

강력히 추천함.

---

# 최적화 관련

### 벤치마크 도구 (Micro Benchmark)

[Micro Benchmark - Profiler Tool for Blueprint and Code Performance Timing, 카테고리 코드 플러그인 - UE 마켓플레이스](https://www.unrealengine.com/marketplace/ko/product/micro-benchmark-profiler-tool-for-blueprint-and-code-performance-timing)

블루프린트에서 사용하기 편한 벤치마크 도구.

Tic과 Toc 두 개의 함수를 제공하는 단순한 플러그인이다.

반드시 필요하지는 않지만 편하게 쓸 수 있다.

---

# 아트 에셋 관련

### 메시 피벗 도구 (Pivot tool)

[Pivot Tool, 카테고리 코드 플러그인 - UE 마켓플레이스](https://www.unrealengine.com/marketplace/ko/product/pivot-tool)

메시의 피벗을 변경할 수 있다.

이게 기능의 전부이지만 DCC에서 피벗을 바꾸고 가져오는 수고를 덜 수 있어서 편리하다.

### 텍스쳐 리사이즈 (RMA Texture Resizer)

[RMA Texture Resizer, 카테고리 코드 플러그인 - UE 마켓플레이스](https://www.unrealengine.com/marketplace/ko/product/rmatextureresizer)

언리얼 에디터에서 대량의 텍스쳐 에셋들을 찾아서 리사이징할 수 있는 도구.

간단한 기능이지만 매우 유용하고 편하다. 여기저기서 사다모은 에셋들을 최적화할 때 사용했었다.

무료 툴도 써보았지만 별로였고, 유료인 만큼 편하고 좋았다.

내가 구매했던 때보다 가격이 오른 것 같은 느낌이 들긴 하는데, 직접 에디터 도구를 만들어서 쓸 게 아니라면 이걸 쓰자.

---

# 애니메이션 관련

### IK (Dragon.IK)

[Dragon.IK - Universal IK System, 카테고리 코드 플러그인 - UE 마켓플레이스](https://www.unrealengine.com/marketplace/ko/product/dragon-ik-animal-inverse-kinematics)

매우 편리한 IK 솔루션.

강력히 추천함.

---

# 버전 관리

### Project Version From Git

[ProjectVersionFromGit, 카테고리 코드 플러그인 - UE 마켓플레이스](https://www.unrealengine.com/marketplace/ko/product/projectversionfromgit)

[https://github.com/mrbindraw/ProjectVersionFromGit](https://github.com/mrbindraw/ProjectVersionFromGit)

깃에서 브랜치 이름, 커밋 해시, 빌드 시간 등을 가져올 수 있는 함수 라이브러리.

개발 및 테스트용 패키지를 특정하는 데에 아주 유용하다.

---

# 설정 관리

### 콜리전 프리셋 매트릭스 (Smart Collision Profiles)

[Smart Collision Profiles, 카테고리 코드 플러그인 - UE 마켓플레이스](https://www.unrealengine.com/marketplace/ko/product/smart-collision-profiles)

언리얼 엔진의 콜리전 설정을 처음 만질 때 너무나도 비직관적이어서 놀랐던 적이 있다.

이 플러그인은 그런 불편함을 어느정도 해소해준다. 

강력히 추천함.

---

# 온라인 서브시스템 관련

### Online Subsystem Blueprints

[Online Subsystem Blueprints, 카테고리 코드 플러그인 - UE 마켓플레이스](https://www.unrealengine.com/marketplace/ko/product/online-subsystem-blueprints)

온라인 서브시스템 기능들을 블루프린트에서 편하게 사용할 수 있도록 해주는 플러그인.

AdvancedSession, SteamCore 등의 플러그인들을 사용해봤는데 이 플러그인이 가장 좋았다. 

플러그인 문서는 API 참조만 있어서 스팀 등의 플랫폼과 통합하기 위해서는 언리얼 공식 문서를 참조할 것. 문서는 빈약하지만 예제 프로젝트가 잘 되어 있어서 보고 따라하면 된다.

나는 주로 같은 제작자의 EOS Online Subsystem과 함께 사용했다.

마켓에서 다운받은 플러그인에 바이너리만 있고, 코드 접근을 위해서 제작자의 웹사이트에 따로 인증을 하고 깃을 통해 소스 코드를 받아야 하는 것은 매우 불편했다. 

다른 플러그인들은 그냥 플러그인에 소스 코드가 포함되어 있는데 말이다.

### EOS Online Subsystem

[EOS Online Subsystem, 카테고리 코드 플러그인 - UE 마켓플레이스](https://www.unrealengine.com/marketplace/ko/product/eos-online-subsystem)

에픽 온라인 서비스(EOS)와 통합하기 위한 플러그인.

사용하기 매우 편하고 코드가 잘 구성되어 있다. 

대부분의 EOS 관련 설정을 플러그인을 적용시키기만 해도 자동으로 설정해주어서 매우 편하다. 하지만 공식 문서를 보고 직접 설정해두었던 온갖 설정들을 날려버리고 플러그인에서 자동으로 생성한 설정들로 덮어써버려서, 해당 기능을 비활성화하고 기존 설정을 복구했어야 했다.

사용하면서 AntiCheat와 관련해서 특정 상황에 크래시가 발생했었다. 제작자에게 문의했을 때 답변은 빨랐지만, 바로 처리해주지 않아서 해당 상황을 회피하는 식으로 문제를 해결했었다.

이 플러그인 역시 바이너리만 포함하고 있으며, 소스 코드 접근을 위해서는 따로 제작자에게 인증을 받아야 한다는 점은 불편하다.

일개 플러그인이 너무 많은 것을 하려고 드는 것이 단점. 좀 더 간단하고 미니멀했으면 좋았을 것 같다.

[다른 EOS 플러그인인 EOSCore와의 비교]

SteamCore 제작자의 EOSCore도 사용해봤지만 이 플러그인이 낫다. 

비교해보자면 이 플러그인은 코드가 더 잘 구성되어 있고, EOSCore는 더 단순하고 직설적인 방식으로 코드가 짜여 있다. EOSCore는 코드가 단순하단 점은 좋았으나 공식 EOS 문서와 다른 방법으로 뭔가를 하게 되어있는 부분이 있었다. 정확히 기억나지는 않지만 인증 부분에서 구현을 편히 하기 위해 편법을 썼던 것 같다. 거기에 더해 제작자에 대한 불신 때문에 EOSCore 대신 이 플러그인을 선택했었다.

---

# 그 외

## 써보진 않았지만 유용해보이는 플러그인

### 절차적 회전 애니메이션 (Procedural Turn In Place System)

[Procedural Turn in Place System, 카테고리 블루프린트 - UE 마켓플레이스](https://www.unrealengine.com/marketplace/ko/product/procedural-turn-in-place-system)

Control Rig을 이용해 절차적 애니메이션을 만들어주는 플러그인.

이전 프로젝트가 UE4를 사용했는데 이 플러그인은 UE5만 지원하기 때문에 써보진 않았다.

그럼에도 매우 좋은 플러그인처럼 보여서 소개한다.

---

## 비추천

개인적인 의견일 뿐이므로 판단에 참고만 하세요.

### Easy Multi Save

[Easy Multi Save, 카테고리 코드 플러그인 - UE 마켓플레이스](https://www.unrealengine.com/marketplace/ko/product/easy-multi-save)

세이브 시스템 중 최다 리뷰를 기록하고 있는 플러그인이지만 비추천한다.

주된 이유는 많은 크래시와 게임 틱에 의존하는 구조 때문.

이 플러그인을 사용한 프로젝트를 출시했던 적이 있는데, 출시 초기에 이 플러그인 때문에 수많은 크래시 리포트와 메일을 받았었다.

직렬화 및 압축 코드 어딘가에 널 포인터 익셉션을 유발하는 코드가 숨어있었던 걸로 기억한다.

해당 부분을 직접 수정해서 사용했지만, 그 버그는 한동안 고쳐지지 않았었다. 어쩌면 아직도 안 고쳐졌을지도 모른다.

내가 게임을 출시한 지 몇 달 이후, 다른 게임을 출시한 게임 개발자가 나에게 개인적으로 이메일을 보내온 적이 있었다. 

내용은 이랬다. "네 게임에서 EasyMultiSave 관련 크래시가 발생했었다는 것을 아는데, 지금 나도 게임을 출시했더니 똑같은 크래시가 난다. 대체 어떻게 해결했었냐?"

그래서 버그를 수정하는 법을 알려줬던 기억이 있다. 아마도 제작자에게 문의해보고 해결이 안 되서 나한테까지 연락했던 것 같다. 

대체 어떻게 알았는지는 모르겠다. 아마도 크래시 로그로 검색했다가 내 게임의 스팀커뮤니티에 들어왔던 게 아닐까 싶다.

그 외에도 게임을 일시정지하면 게임 틱에 등록한 타이머에 의해 실행되는 세이브 동작이 멈춘다든지 하는 몇몇 문제점이 있었다.

그래서 이걸 왜 쓰나 해서 인터페이스만 유지한 채로 자체 개발한 세이브 로드 시스템으로 바꿨다.

### SteamCore

[SteamCore, 카테고리 코드 플러그인 - UE 마켓플레이스](https://www.unrealengine.com/marketplace/ko/product/steamcore)

이것도 스팀 온라인 서브시스템 블루프린트 통합 중에서 인기가 상당히 많은 플러그인이다.

비추천하는 이유는 간단한데, 크래시가 많았다.

상당히 편리하고 좋은 플러그인이었지만, 이 플러그인 코드에서 비롯한 크래시 리포트를 많이 받았다.

나는 2022년 3월까지 이 플러그인을 사용했는데, 지금까지 업데이트를 계속해오면서 버그들을 수정했다면 쓸만할지도 모르겠다. 하지만 위에 소개한 Online Subsystem Blueprints를 더 추천한다.