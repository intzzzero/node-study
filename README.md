## NODE STUDY

- [Node.js 교과서 개정2판](http://www.yes24.com/Product/Goods/91213376?OzSrank=1)을 보며 공부함

---

## Node.js의 핵심 개념

- 자바스크립트로 서버를 실행할 수 있도록 하는 **자바스크립트 실행환경(runtime)**
- 크롬 브라우저와 동일한 V8 자바스크립트 엔진 기반
- libuv 라이브러리를 통한 비동기/IO 구현
- 이벤트 기반(event-driven)
  - 특정 이벤트(클릭, 스크롤 등)가 발생했을 때 미리 등록한 콜백을 통한 동작 실행
- 이벤트 루프(event-loop)
  - 이벤트의 실행 순서는 [이벤트 루프](https://meetup.toast.com/posts/89)가 판단
