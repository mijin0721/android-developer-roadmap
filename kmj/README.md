# Android 개발 학습 로드맵

이 문서는 저장소의 Android Developer Roadmap에 나온 주제를 학습 순서에 맞춰 정리한 체크리스트입니다. 모든 항목을 한 번에 깊게 공부하기보다, 작은 앱을 만들면서 필요한 내용을 차례로 익혀 보세요.

## 1. Android 플랫폼 기초

- [ ] **Application Fundamentals**: 앱이 Android에서 설치되고 실행되는 기본 흐름
- [ ] **Android Operating System**: Android OS가 앱과 기기를 관리하는 방식
- [ ] **Android Platform Architecture**: Linux 커널, Android Runtime, 프레임워크 등 플랫폼 계층
- [ ] **Native Libraries**: 그래픽, 미디어, 데이터베이스 등 플랫폼 라이브러리의 역할
- [ ] **System Apps**: 시스템 앱과 일반 앱의 역할 및 차이

## 2. 앱 구성 요소와 실행

- [ ] **App Manifest**: `AndroidManifest.xml`에서 앱 구성 요소, 권한, 설정 선언하기
- [ ] **App Components**: Activity, Service, Broadcast Receiver, Content Provider의 역할
- [ ] **Activity**: 화면 구성 단위와 생명주기
- [ ] **Intent Filters**: 구성 요소가 처리할 수 있는 요청 선언하기
- [ ] **Explicit Intents**: 대상 구성 요소를 지정해 기능이나 화면 실행하기
- [ ] **Implicit Intents**: 수행할 작업을 요청하고 시스템이 처리 앱을 찾게 하기
- [ ] **App Entry Points**: 런처, 딥링크, 알림 등 앱이 시작되는 경로

## 3. 화면 이동과 상태 전달

- [ ] **Task and Back Stack**: 화면 이동 기록과 뒤로 가기 동작 이해하기
- [ ] **Parcelables and Bundles**: 구성 요소 사이에 데이터를 전달하고 상태 저장하기
- [ ] **App Navigation**: 앱 내부 화면 이동 설계하기
- [ ] **Navigation Graph**: 목적지와 이동 경로를 그래프로 구성하기
- [ ] **Destinations**: 앱에서 이동 가능한 화면이나 목적지 정의하기
- [ ] **Global Actions**: 여러 화면에서 공유하는 이동 동작 구성하기

## 4. 앱 구조와 데이터 처리

- [ ] **App Architecture**: UI, 데이터, 비즈니스 로직을 나누는 방법
- [ ] **Architecture Components**: 생명주기, 상태, 데이터 관리를 돕는 Android Jetpack 구성 요소
- [ ] **Dependency Injection**: 객체가 필요한 의존성을 외부에서 제공받도록 구성하기
- [ ] **Design Patterns**: 반복되는 설계 문제에 적용하는 패턴 이해하기
- [ ] **Builder Pattern**: 복잡한 객체를 단계적으로 생성하기
- [ ] **Local Storage**: 앱 데이터를 기기에 저장하고 불러오기
- [ ] **Asynchronous / Coroutines**: 네트워크·파일 작업을 비동기로 처리하기
- [ ] **Image Loading**: 이미지 로딩, 캐싱, 화면 표시 이해하기

## 5. UI와 앱 완성

- [ ] **User Interface**: 사용자가 보고 조작하는 화면 구성하기
- [ ] **Compose UI**: Jetpack Compose로 UI를 선언하고 상태에 따라 갱신하기
- [ ] **Service**: 화면 밖에서 수행되는 작업과 실행 제약 이해하기
- [ ] **Code Analysis & Test**: 코드 검사와 단위·UI 테스트로 품질 확인하기
- [ ] **CI/CD**: 빌드, 검사, 배포 자동화하기
- [ ] **QA & App Publishing**: 앱 검증 및 스토어 출시 과정 익히기
- [ ] **App Startup**: 초기화 작업과 앱 시작 성능 관리하기

## 추천 학습 순서

Kotlin 기초 → Android 플랫폼 기초 → Activity와 Intent → 화면 이동 → Compose UI → 로컬 저장과 비동기 처리 → 테스트와 출시 순서로 진행합니다. 나머지 항목은 앱을 만들며 필요할 때 보충합니다.

## 참고 자료

- [저장소 로드맵 README](../README.md)
- [Android Developers 문서](https://developer.android.com/)
- [Part 1: Android Platform](https://getstream.io/blog/android-developer-roadmap/)
- [Part 2: App Components](https://getstream.io/blog/android-developer-roadmap-part-2/)
- [Part 3: App Navigation and Jetpack](https://getstream.io/blog/android-developer-roadmap-part-3/)
- [Part 4: Design Patterns and Architecture](https://getstream.io/blog/design-patterns-and-architecture-the-android-developer-roadmap-part-4/)
- [Part 5: Jetpack Compose](https://getstream.io/blog/android-developer-roadmap-part-5/)

> 이 저장소의 로드맵은 2022년판입니다. 개념 학습의 지도로 활용하고, 실제 API 사용법과 최신 권장 사항은 Android Developers 문서에서 확인하세요.
