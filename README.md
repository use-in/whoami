# whoami

박유진의 자기소개 페이지. 의존성 없는 단일 HTML 파일입니다.

**→ https://use-in.github.io/whoami**

## 구성

- `index.html` — 페이지 전체 (마크업 + CSS 인라인)

폰트는 Google Fonts에서 Gowun Batang(이름), IBM Plex Sans KR(본문),
IBM Plex Mono(라벨)를 불러옵니다. 그 외 외부 의존성은 없습니다.

## 로컬에서 보기

`index.html`을 브라우저로 열면 끝입니다. 빌드 과정이 없습니다.

## 수정하기

`index.html` 하나만 고치면 됩니다. `main` 브랜치에 푸시하면
GitHub Pages가 자동으로 다시 배포합니다.

- 색·글꼴은 파일 상단 `:root` 의 CSS 변수에서 한 번에 바꿉니다
  (다크 모드 값은 바로 아래 두 블록에 같은 이름으로 정의돼 있습니다)
- 관심 분야와 연락처는 아직 비워 둔 상태입니다. `.blank` 로 표시된 자리에
  내용을 넣으면 됩니다 (연락처는 `.links` 안의 각 항목)
