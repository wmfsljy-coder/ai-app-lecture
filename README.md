# AI로 학교 앱 만들기 · 2시간 강의안

선생님 대상 강의안(초보자 2시간 / 중급자 2시간). 이정용 선생님(웅천고)이 실제로 만들고 운영한 업무·수업 앱 경험을 바탕으로, 단계별 진행·강사 멘트·실습(바로 써 보는 도구, 복사용 주문서와 코드, 퀴즈, 체크리스트)과 강의 시계를 담았다.

- 주소: https://wmfsljy-coder.github.io/ai-app-lecture/
  - 초보자: `#beginner`, 중급자: `#intermediate`, 자료·명령어: `#res`
- 방식: HTML 한 장(빌드 없음) + GitHub Pages. 저장할 데이터 없음. 실습 메모·체크는 그 기기 localStorage(`lec-*`)에만.
- 고치는 곳: `index.html` 아래 `<script>`의 `TRACKS`(단계·시간·할 말·실습), `WEBAPP`(앱스스크립트 예제 두 가지), `METHOD`·`SAFE`·`BUGS`(퀴즈), `MIGRATE`(체크리스트).
- 배포: 빌드 없음. `index.html` 을 고쳐 `main` 에 push 하면 GitHub Pages(가지 `main`, 폴더 `/`)가 1~2분 뒤 위 주소에 반영한다.
- 공개 저장소: 학생 이름, 시트·드라이브 주소, 열쇠·비밀번호, 관리 화면 주소를 넣지 않는다.
