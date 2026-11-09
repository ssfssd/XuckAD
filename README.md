# XuckAD Android

광고·추적 요청과 HTTPS 본문·화면 요소를 필터링하는 Android 앱의 배포 저장소입니다.

## 설치·업데이트

**[Obtainium으로 등록하기](https://apps.obtainium.imranr.dev/redirect?r=obtainium%3A%2F%2Fapp%2F%257B%2522id%2522%253A%2522app.xuckad.android%2522%252C%2522url%2522%253A%2522https%253A%252F%252Fgithub.com%252Fssfssd%252FXuckAD%2522%252C%2522author%2522%253A%2522ssfssd%2522%252C%2522name%2522%253A%2522XuckAD%2522%252C%2522additionalSettings%2522%253A%2522%257B%255C%2522includePrereleases%255C%2522%253Atrue%252C%255C%2522verifyLatestTag%255C%2522%253Afalse%252C%255C%2522filterReleaseTitlesByRegEx%255C%2522%253A%255C%2522%255EXuckAD%2520Android%2520%255C%2522%257D%2522%257D)**

휴대폰에서 링크를 열어 Obtainium에 추가한 다음 설치를 누르세요. 이 링크는 Android 릴리스와 사전 릴리스 수신 설정을 포함합니다. 이후 같은 저장소에 게시되는 버전을 Obtainium에서 확인·업데이트할 수 있습니다.

- [Android 0.3.0 사전 릴리스](https://github.com/ssfssd/XuckAD/releases/tag/android-v0.3.0)
- [APK 직접 다운로드](https://github.com/ssfssd/XuckAD/releases/download/android-v0.3.0/XuckAD-0.3.0-debug.apk)
- [최초 설정·복구 안내](https://github.com/ssfssd/XuckAD/releases/download/android-v0.3.0/INSTALL.md)
- [Obtainium 공식 설치](https://obtainium.imranr.dev/)

수동으로 추가할 때 소스는 `https://github.com/ssfssd/XuckAD`, **사전 릴리스 포함**은 켜고, **최신 태그 확인**은 끄세요. 릴리스 제목 필터는 `^XuckAD Android `입니다.

## 현재 배포 범위

Android 8 이상, 패키지 `app.xuckad.android`, 버전 `0.3.0` / versionCode `3`. 기존 0.2.0과 같은 서명의 디버그 테스트 빌드입니다. 업데이트 시 기존 앱을 먼저 제거하지 마세요.

Tailscale 공존 모드는 별도 VPN 없이 휴대폰의 로컬 프록시를 사용하도록 구현했습니다. **최초 ADB 권한 부여와 CA 인증서 설치는 Obtainium 설치와 별개**이며, 이후 상시 PC는 필요하지 않습니다. 시스템 프록시와 사용자 CA를 따르는 앱만 대상입니다.

**실제 Android 기기에서 설치·Chrome·Tailscale·Wi-Fi/LTE/5G 동작은 아직 검증하지 못했습니다.** 자동 검증과 APK 검증을 통과한 사전 릴리스이며 모바일 차단율·속도·배터리 우위를 주장하지 않습니다.

## 업데이트 유지

이 저장소의 Android 릴리스 제목은 `XuckAD Android `로 시작합니다. 다음 APK도 같은 패키지·서명 키와 증가한 versionCode를 사용해야 기존 설치를 업데이트할 수 있습니다. 서명 개인 키와 사용자 데이터는 배포하지 않습니다.
