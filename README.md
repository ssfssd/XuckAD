# 고요 (Goyo) Android
광고·추적 요청과 HTTPS 본문·화면 요소를 필터링하는 Android 앱입니다. XuckAD에서 **고요**로 이름을 바꿨습니다.

**[Obtainium으로 설치·업데이트 등록](https://apps.obtainium.imranr.dev/redirect?r=obtainium%3A%2F%2Fapp%2F%257B%2522id%2522%253A%2522app.xuckad.android%2522%252C%2522url%2522%253A%2522https%253A%252F%252Fgithub.com%252Fssfssd%252FXuckAD%2522%252C%2522author%2522%253A%2522ssfssd%2522%252C%2522name%2522%253A%2522%25EA%25B3%25A0%25EC%259A%2594%2522%252C%2522additionalSettings%2522%253A%2522%257B%255C%2522includePrereleases%255C%2522%253Atrue%252C%255C%2522verifyLatestTag%255C%2522%253Afalse%252C%255C%2522filterReleaseTitlesByRegEx%255C%2522%253A%255C%2522%255EXuckAD%2520Android%2520%255C%2522%257D%2522%257D)**

- [Android 0.6.0 사전 릴리스](https://github.com/ssfssd/XuckAD/releases/tag/android-v0.6.0)
- [APK 다운로드](https://github.com/ssfssd/XuckAD/releases/download/android-v0.6.0/Goyo-0.6.0-debug.apk)
- [간편 설정·작동 확인 안내](https://github.com/ssfssd/XuckAD/releases/download/android-v0.6.0/INSTALL.md)

기존 앱을 제거하지 말고 Obtainium의 기존 XuckAD 항목에서 업데이트하세요. Android 앱 이름·아이콘은 고요로 바뀝니다. 기존 CA 인증서·설정 권한·규칙을 그대로 사용하므로 다시 설정하지 않아도 됩니다. Obtainium에 표시되는 사용자 지정 이름은 그대로일 수 있습니다.

업데이트 후 **고요 → 현황 → 작동 확인**을 누르세요. 기존 Tailscale 공존 프록시와 HTTPS·화면 요소 차단을 유지합니다. 최초 설정이 필요한 새 기기는 **처음 설정 · 휴대폰만으로 간편 설정**을 사용합니다.

JVM 123개, Android 15 에뮬레이터 업데이트/브랜딩 10개 및 작동 확인 19개 통과. 실제 홈·알림을 확인했습니다. 실물 휴대폰·Tailscale 계정·LTE/5G·모바일 Chrome 실사이트 성능은 미검증입니다.

수동 Obtainium 등록: 소스 `https://github.com/ssfssd/XuckAD`, 사전 릴리스 포함 켜기, 최신 태그 확인 끄기, 릴리스 제목 필터 `^XuckAD Android `. 기존 업데이트 호환을 위해 저장소 주소와 제목 접두어를 유지합니다.

패키지 `app.xuckad.android`, versionName `0.6.0`, versionCode `6`. 기존과 동일한 서명의 테스트 APK입니다.
