# 배프 카페 키오스크 연습장

배포 사이트의 소스 커밋 `906a64f`에서 가져온 정적 웹앱입니다. HTML, CSS, JavaScript와 메뉴 이미지가 포함되어 있습니다.

## React/Vite 프로젝트에 넣기

1. 이 ZIP 안의 `public/baep-cafe` 폴더를 기존 프로젝트의 `public` 아래에 복사합니다.
2. 연습장 버튼이나 링크에서 아래 URL을 사용합니다. Vite의 배포 경로를 적용하므로 프로젝트가 GitHub Pages의 하위 경로에 배포되어도 링크가 그 경로를 따릅니다.

```tsx
<a href={`${import.meta.env.BASE_URL}baep-cafe/index.html`}>
  카페 키오스크 연습하기
</a>
```

3. 기존 프로젝트의 개발 서버에서 링크를 열어 확인한 후, `public/baep-cafe` 폴더와 링크를 추가한 파일을 GitHub에 커밋합니다.

기존 화면 안에서 열려면 같은 URL을 `iframe`의 `src`로 사용하세요. 카페 연습장 자체에는 별도의 npm 설치나 빌드가 필요 없습니다.
