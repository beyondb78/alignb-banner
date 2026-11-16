# 얼라인비 GIF 메인 배너 — GitHub Pages 배포 패키지

## 포함 파일
- `index.html`: GIF 표시 테스트 페이지
- `cafe24-banner.html`: 카페24 HTML 삽입 코드
- `main-banner.gif`: **미포함**. 실제 움직이는 GIF를 직접 업로드해야 합니다. (전달받은 GIF가 정지 1프레임이었으므로 임의로 대체하지 않았습니다.)

## 1. GitHub 저장소 만들기
1. GitHub 로그인 → New repository.
2. 이름: `alignb-banner`, 공개 범위: **Public**, Create repository.
3. 이 ZIP을 압축 해제한 뒤 `index.html`과 `README.md`를 저장소 최상위에 업로드합니다. `cafe24-banner.html`도 함께 업로드해도 됩니다.
4. 본인의 **움직이는 GIF**를 `main-banner.gif`로 이름 변경해 저장소 최상위에 업로드합니다. GIF 자체가 무한 반복으로 저장되어 있어야 합니다.
5. Commit changes를 누릅니다.

## 2. GitHub Pages 켜기
Settings → Pages → Build and deployment → Deploy from a branch → Branch: `main`, Folder: `/(root)` → Save.
배포가 끝나면 다음 주소로 접속합니다.
- 테스트 페이지: `https://YOUR-USERNAME.github.io/alignb-banner/`
- GIF 직접 주소: `https://YOUR-USERNAME.github.io/alignb-banner/main-banner.gif`

`YOUR-USERNAME`을 GitHub 사용자명으로 바꾸세요. 실제 저장소명이 다르면 URL의 `alignb-banner`도 바꾸세요.

## 3. 카페24 연결
1. 카페24 현재 사용 중인 디자인을 먼저 백업합니다.
2. 메인 배너 슬라이더를 비활성화합니다. 스킨에 따라 편집 위치가 다릅니다.
3. `cafe24-banner.html`을 열고 `YOUR-USERNAME`을 교체합니다.
4. 코드를 메인 배너 위치의 HTML에 붙여 넣고 저장합니다.
5. PC·모바일에서 이미지 크기, 자동 반복, 클릭 링크, 로딩을 확인합니다.

## 주의사항
- HTML은 GIF 업로드 자체를 대신하지 않습니다. GIF는 GitHub 저장소에 직접 올려야 합니다.
- GIF가 1프레임이면 움직이지 않습니다.
- GitHub Pages 공개 저장소에 올린 GIF는 누구나 볼 수 있습니다.
- GIF 파일이 너무 크면 첫 화면 로딩이 느려질 수 있습니다. 트래픽이 큰 상업 사이트라면 전용 CDN/이미지 호스팅이 더 적합할 수 있습니다.
- `index.html`은 GIF가 없는 경우 안내 문구를 보여줍니다.
