# XuckAD Android
광고·추적 요청과 HTTPS 본문·화면 요소를 필터링하는 Android 앱의 배포 저장소입니다.

**[Obtainium으로 설치·업데이트 등록](https://apps.obtainium.imranr.dev/redirect?r=obtainium%3A%2F%2Fapp%2F%257B%2522id%2522%253A%2522app.xuckad.android%2522%252C%2522url%2522%253A%2522https%253A%252F%252Fgithub.com%252Fssfssd%252FXuckAD%2522%252C%2522author%2522%253A%2522ssfssd%2522%252C%2522name%2522%253A%2522XuckAD%2522%252C%2522additionalSettings%2522%253A%2522%257B%255C%2522includePrereleases%255C%2522%253Atrue%252C%255C%2522verifyLatestTag%255C%2522%253Afalse%252C%255C%2522filterReleaseTitlesByRegEx%255C%2522%253A%255C%2522%255EXuckAD%2520Android%2520%255C%2522%257D%2522%257D)**

- [Android 0.5.0 사전 릴리스](https://github.com/ssfssd/XuckAD/releases/tag/android-v0.5.0)
- [APK 다운로드](https://github.com/ssfssd/XuckAD/releases/download/android-v0.5.0/XuckAD-0.5.0-debug.apk)
- [휴대폰 간편 설정·작동 확인 안내](https://github.com/ssfssd/XuckAD/releases/download/android-v0.5.0/INSTALL.md)

기존 앱을 제거하지 말고 Obtainium에서 업데이트하세요. 업데이트 후 **현황 → 작동 확인**을 누르면 됩니다. 최초 설정은 **처음 설정 · 휴대폰만으로 간편 설정**에서 진행하며 Android 11 이상과 최초 Wi-Fi, 시스템 페어링·CA 승인이 필요합니다.

기존 Tailscale 공존 프록시 방식과 HTTPS·화면 요소 차단을 유지합니다. 작동 확인은 실제 HTTPS 시험 요청과 앱 안의 화면 숨김을 검사합니다. Tailscale은 VPN 감지와 공식 시험 서버 통신을 구분하며, 실제 접속 성공 때만 통신 확인이라고 표시합니다.

JVM 123개와 Android 15 에뮬레이터 19개 검증이 통과했습니다. 물리 휴대폰·Tailscale 계정·LTE/5G·모바일 Chrome 실사이트 성능은 미검증입니다. 검사 결과도 그 범위를 넘어 보장하지 않습니다.

수동 Obtainium 등록: 소스 `https://github.com/ssfssd/XuckAD`, 사전 릴리스 포함 켜기, 최신 태그 확인 끄기, 릴리스 제목 필터 `^XuckAD Android `.

패키지 `app.xuckad.android`, versionName `0.5.0`, versionCode `5`. 같은 서명의 테스트 APK입니다.
