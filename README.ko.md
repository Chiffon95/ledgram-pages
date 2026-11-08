# LEDgram

[English](README.md)

LEDgram은 Android 스마트폰, 태블릿, 폴더블 기기를 밝고 자유롭게 꾸밀 수 있는 LED 전광판으로 바꾸는 앱입니다. Editor에서 문구를 만들고 즉시 미리 본 뒤, 행사·응원·안내 또는 일상적인 소통을 위해 전체 화면으로 표시할 수 있습니다.

## 주요 기능

- 단색 글자·배경 색상과 6가지 고정 및 4가지 애니메이션 글자 그라데이션, 굵게, 기울임, 밑줄 설정
- Text + Glow 및 Dot Matrix 표현 방식
- 고정 문구 또는 양방향 전광판 이동
- Blink, Pulse, Fade 효과와 독립적인 이동·효과 속도 조절
- 소프트 줄바꿈 없이 한글을 포함한 명시적 여러 줄 입력
- 스마트폰, 태블릿, 폴더블 기기에서 부드러운 화면 방향 추적과 Lock/Unlock을 지원하는 몰입형 전체 화면 Display
- 앱을 다시 실행해도 유지되는 Editor 설정
- 저장된 미리보기와 상세 정보, 생성, 불러오기, 이름 변경, 명시적 덮어쓰기, 삭제, 불러오기 실행 취소 및 편집 가능한 초기 Default를 지원하는 로컬 프리셋 라이브러리
- 새로 설치하면 Brand Amber에서 Pink로 이어지는 고정 가로 그라데이션으로 시작하며, 기존에 저장된 Editor 설정과 프리셋은 변경되지 않음
- Settings, 개인정보 처리방침, 법적 고지를 제공하는 한국어 및 영어 인터페이스
- 필요한 지역에서 UMP 동의 및 개인정보 보호 옵션을 제공하는 Google Mobile Ads

## 스크린샷

### Editor와 실시간 미리보기

<img src="docs/play-store/screenshots/ko/01-editor-overview.png" alt="실시간 미리보기와 꾸미기 설정이 표시된 LEDgram Editor" width="320">

### Dot Matrix Display

<img src="docs/play-store/screenshots/ko/03-dot-matrix.png" alt="LEDgram Dot Matrix 전체 화면 Display" width="720">

### 여러 줄 Display

<img src="docs/play-store/screenshots/ko/06-multiline.png" alt="LEDgram 여러 줄 전체 화면 Display" width="720">

## 기술 구성

- Kotlin 2.4.21
- Jetpack Compose(BOM 2025.11.00) 및 Material 3
- AndroidX DataStore 1.2.1 및 Android SDK 24–36
- Google Mobile Ads 25.5.0 및 UMP 4.0.0
- Kotlin DSL 기반 Android Gradle Plugin 9.4.1 및 Gradle 9.8.0

## 출시 상태

- **게시된 버전:** 1.1.0 (22), Google Play에서 제공 중

## 개발자

LEDgram은 **Gwol Labs**에서 개발합니다.

## 링크

- [공개 웹사이트](https://chiffon95.github.io/ledgram-pages/)
- [개인정보 처리방침 — 영어](https://chiffon95.github.io/ledgram-pages/privacy/)
- [개인정보 처리방침 — 한국어](https://chiffon95.github.io/ledgram-pages/privacy/ko.html)

## 라이선스

이 프로젝트에는 오픈 소스 라이선스가 공개되어 있지 않습니다. 모든 권리는 Gwol Labs에 있습니다.

LEDgram에는 Lee Minseo가 제작하고 SIL Open Font License 1.1로 배포한 [Galmuri11](https://github.com/quiple/galmuri)이 포함됩니다. OFL은 번들 글꼴에만 적용되며 LEDgram 애플리케이션 소스 코드에는 적용되지 않습니다.
