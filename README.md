# Zeta Kakao 북마크릿 URL 배포

1. 공개 GitHub 저장소 `hllim-svg/kakao-theme`의 최상위에 이 폴더의 `index.html`, `zeta-kakao.js`를 올립니다.
2. 저장소 Settings → Pages에서 Deploy from a branch, main, /(root)를 선택합니다.
3. `https://hllim-svg.github.io/kakao-theme/zeta-kakao.js`에 접속해 스크립트가 열리는지 확인합니다.
4. 로더 TXT 안의 한 줄(`https://hllim-svg.github.io/kakao-theme/zeta-kakao.js`을 불러오도록 이미 설정됨)을 Safari 북마크 주소에 저장합니다.
5. 이후 업데이트는 저장소의 `zeta-kakao.js`만 교체합니다. 로더는 실행 때마다 최신 파일을 요청합니다.

스크립트는 공개 저장소에 올라가므로 코드에 개인 키나 비밀번호를 넣지 마세요. 제타 페이지의 CSP가 외부 스크립트를 막으면 로더의 실패 안내가 나타날 수 있습니다.
