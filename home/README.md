# 홈페이지 문제 목록 관리

홈페이지는 `problem-list.js`의 목록을 읽어 문제 카드를 표시합니다. GitHub Pages는 정적 사이트이므로 새 폴더를 실시간으로 검색하지 않습니다.

새 문제를 만들 때는 문제 페이지를 생성한 뒤 `problem-list.js`에 다음과 같은 항목을 추가합니다.

```js
{
  number: 36,
  title: '지문 주제',
  href: '../problems/problem-36/index.html'
}
```

문제-33처럼 루트 `index.html`을 사용하는 경우에만 `href`를 `../index.html`로 지정합니다. 이후 문제 페이지와 목록 파일을 함께 커밋하고 push하면 GitHub Pages에 반영됩니다.
