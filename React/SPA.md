## SPA란?

SPA(Single Page Application) - 하나의 파일로 전체 사이트를 구현한다.
주객전도. 동적인 기능이 주가 되버림. → 자바스크립트가 주가 되고 그 안에 일부 HTML, CSS 가 포함

- html 파일이 한 개.
- npm run build ⇒ html 파일 하나 생김 (ex. AWS 배포할 때)
- 페이지를 이동하려고 하면 자바스크립트 내의 특정 함수를 타서 `<div id="root" />` 의 내용을 싹 교체하는 것.
- 서버로부터 html 자체를 받아서 페이지를 바꾸는게 아니다.

