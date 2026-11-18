# STARFOLIO

이한별 포트폴리오 웹사이트.

## 폴더 구성

```
index.html          페이지 (모든 텍스트·도형은 원본 디자인의 윤곽선 그대로)
css/style.css       스타일
js/main.js          인터랙션 (점→선→면 인트로, 가루 호버, 별 해체·조립, 펼침 목록, 스크롤 등장)
assets/profile.jpg  프로필 사진
.nojekyll           GitHub Pages가 파일을 그대로 쓰도록 하는 빈 파일
```

외부 폰트나 라이브러리를 불러오지 않아서 이 파일들만 있으면 됩니다.

## GitHub Pages로 올리기

1. GitHub에서 새 저장소를 만듭니다 (예: `starfolio`, Public).
2. 저장소 화면에서 **Add file → Upload files**를 누르고, 이 폴더 **안의 내용물**(index.html, css, js, assets, .nojekyll)을 끌어다 놓은 뒤 **Commit changes**.
   - `.nojekyll`처럼 점으로 시작하는 파일은 숨김 파일이라 안 보일 수 있어요. 빠져도 사이트는 잘 열립니다.
3. **Settings → Pages**에서 Source를 **Deploy from a branch**, Branch를 **main / (root)**로 두고 **Save**.
4. 1~2분 뒤 `https://<깃허브아이디>.github.io/starfolio/` 에서 열립니다.

저장소 이름을 `<깃허브아이디>.github.io`로 만들면 주소가 `https://<깃허브아이디>.github.io/` 가 됩니다.

## 내 컴퓨터에서 미리 보기

`index.html`을 더블클릭해서 브라우저로 열면 됩니다.
