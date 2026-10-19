# 킹글로그 배포본

이 폴더는 정적 호스팅에 올릴 최소 파일로 구성되어 있습니다. 게임은 `index.html` 한 파일로 실행되며 서버나 빌드 단계가 필요하지 않습니다.

## GitHub Pages 무료 배포

GitHub Free에서는 Pages를 쓰려면 저장소를 공개로 만들어야 합니다. 저장소 내용과 게임 주소가 공개됩니다.

1. GitHub 계정으로 로그인하고 새 공개 저장소를 만듭니다. 예: `kingle-rogue`
2. 이 폴더 안의 `index.html`과 `THIRD_PARTY_NOTICES.md`를 저장소 최상위에 올리고 커밋합니다.
3. 저장소의 **Settings → Pages**에서 **Deploy from a branch**를 선택합니다.
4. Branch는 `main`, 폴더는 `/(root)`로 지정하고 저장합니다.
5. Pages 설정 화면에 표시되는 주소를 엽니다. 주소 형식은 `https://계정명.github.io/kingle-rogue/`입니다.

게임을 갱신할 때는 새 `index.html`을 같은 위치에 올려 커밋하면 됩니다.
