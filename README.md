# XuckAD Android

광고·추적 요청과 HTTPS 본문·화면 요소를 필터링하는 Android 앱의 배포 저장소입니다.

**[Obtainium으로 설치·업데이트 등록](https://apps.obtainium.imranr.dev/redirect?r=obtainium%3A%2F%2Fapp%2F%257B%2522id%2522%253A%2522app.xuckad.android%2522%252C%2522url%2522%253A%2522https%253A%252F%252Fgithub.com%252Fssfssd%252FXuckAD%2522%252C%2522author%2522%253A%2522ssfssd%2522%252C%2522name%2522%253A%2522XuckAD%2522%252C%2522additionalSettings%2522%253A%2522%257B%255C%2522includePrereleases%255C%2522%253Atrue%252C%255C%2522verifyLatestTag%255C%2522%253Afalse%252C%255C%2522filterReleaseTitlesByRegEx%255C%2522%253A%255C%2522%255EXuckAD%2520Android%2520%255C%2522%257D%2522%257D)**

- [Android 0.4.0 사전 릴리스](https://github.com/ssfssd/XuckAD/releases/tag/android-v0.4.0)
- [APK 직접 다운로드](https://github.com/ssfssd/XuckAD/releases/download/android-v0.4.0/XuckAD-0.4.0-debug.apk)
- [휴대폰 간편 설정 안내](https://github.com/ssfssd/XuckAD/releases/download/android-v0.4.0/INSTALL.md)
- [Obtainium 공식 설치](https://obtainium.imranr.dev/)

이미 등록했다면 Obtainium에서 업데이트를 확인하세요. 기존 앱은 제거하지 마세요. Android 11 이상에서는 XuckAD의 **처음 설정 · 휴대폰만으로 간편 설정**으로 진행하며, 별도 앱·PC·명령어는 필요하지 않습니다. Android의 무선 디버깅 페어링과 CA 설치 승인은 최초 한 번 직접 진행합니다.

기존 Tailscale 앱을 유지하는 로컬 프록시 방식입니다. 설정 후 Wi-Fi·LTE/5G에서 사용하도록 구현했습니다. Android 8~10의 기존 모드는 유지되지만 휴대폰 단독 권한 설정은 Android 11 이상이 필요합니다.

자동 검증 및 Android 15 에뮬레이터 검증을 통과한 사전 릴리스입니다. 실제 휴대폰·Tailscale 계정·tailnet·LTE/5G·모바일 Chrome 성능은 미검증입니다.

수동 Obtainium 등록: 소스 `https://github.com/ssfssd/XuckAD`, **사전 릴리스 포함** 켜기, **최신 태그 확인** 끄기, 릴리스 제목 필터 `^XuckAD Android `.

패키지 `app.xuckad.android`, versionName `0.4.0`, versionCode `4`. 같은 서명의 테스트 APK를 제공합니다. 차후 업데이트도 같은 패키지·서명과 증가한 versionCode로 게시합니다.
