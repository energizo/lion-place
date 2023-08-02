# 🦁 [ 멋사 6기 JavaScript project]

_프로젝트 14조 / energizo_

> **주제**: Lion-Place
>
> <img alt="JavaScript" src ="https://img.shields.io/badge/JavaScriipt-F7DF1E.svg?&style=for-the-badge&logo=JavaScript&logoColor=black"/>

---

# \*️⃣ 구현 이미지

## ❖ 김성재 / 로그인, 회원가입 기능 구현

![나](https://github.com/energizo/lion-place/assets/134567486/813a29bc-9893-4ecc-883c-b0a2a6290c6f)

---

## ❖ 윤선영 / 리뷰 기능 구현

![리뷰기능구현](https://github.com/energizo/lion-place/assets/134567486/92c831af-b1c1-4f26-ae0c-06b1627a5a0b)

## ❖ 이현주 / 지도 API를 활용한 지도 및 네비게이션 구현

## ![swiper 기능](https://github.com/energizo/lion-place/assets/134567486/e0fe6c2a-4438-45c5-9c47-bc3b71f2d7b1)

## ❖ 장현주 / Swiper 기능 구현

![지도](https://github.com/energizo/lion-place/assets/134567486/996605a1-a458-49a4-b57f-636b9ebabcf3)

---

# \*️⃣ 프로젝트 진행 시 준수사항

## ❖ 라이언 플레이스(Lion-Place)

### 요구사항

- 슬라이드가 필요한 ui에서는 [**swiper.js**](https://swiperjs.com/)를 사용해주세요.
  - 각 슬라이드를 데이터로 받아 동적으로 렌더링 되도록 만들어주세요.
  - 슬라이드의 `prev`, `next` 버튼도 구현해주세요.
  - 키보드 키로도 작동되도록 구현해주세요.
- “마이크로 애니메이션”이 필요하다면 추가해주세요.
- “회원가입 기능”을 구현해주세요.
  - 아이디, 이메일, 비밀번호의 모든 항목을 필수로 받았을 경우 로그인 버튼이 활성화 됩니다.
- 인증 번호의 유효성을 검사합니다.
  - 아이디 조건 : 최소 영문 3자 이상
  - 비밀번호 조건 : 특수문자 포함 최소 8자
  - 이메일과 비밀번호가 모두 입력되어 있고, 조건을 만족해야 제출 버튼이 활성화 되도록 구현해주세요.
- 회원가입을 통해 사용자(user)를 생성하고 관리합니다.
  - 랜덤 한 문자값 (10자 이상) 을 생성 후 사용자의 Unique ID 값으로 넣어주세요.
  - 해당 유저의 Unique ID를 확인 후 로그인합니다.
  - 응답받은 Unique ID는 `localStorage`에 저장해주세요
  - 다음 번에 로그인 시 Unique ID가 존재한다면 루트 경로로 리디렉션 시켜주세요
  - 어떤 경우든 Unique ID가 유효하지 않다면 사용자에게 알리고 로그인 페이지로 리디렉션 시켜주세요
  - 로그아웃은 클라이언트 단에서 `localStorage`에 저장된 Unique ID를 삭제하는 방식으로 구현합니다.
- 지도 API를 사용해 주세요
  - 지도 API를 사용해 실제 화면에 지도로 탐색이 가능할 수 있도록 구현해주세요.
- 리뷰 기능을 만들어 주세요
  - 데이터 스키마를 통해 리뷰 데이터를 설계 후 리뷰 화면에 랜더링 해 주세요.
  - 리뷰 작성을 통해 데이터를 생성 후 화면에 리랜더링이 될 수 있도록 설계해 주세요.

---

## ❖ 웹 표준 마크업 & 스타일링

- 적절한 헤딩 사용 및 시맨틱 마크업에 신경써 주세요.
- 예) 버튼 기능을 하는 UI를 마크업 할 때 <div> 등 의미없는 요소를 사용하지 마세요.
  다만 <div> 요소를 사용하지 말라는 의미가 아닙니다.
- 유효성 검증을 통해 문법 오류가 발생하지 않도록 구현해야 합니다.
- 페이지 단위로 구현해주세요. (컴포넌트 단위 구현은 React 프로젝트에서 진행됩니다)
- 스타일 작성 시, Tailwind CSS 기술을 사용해 스타일링 해주세요. (강제)
- 네이밍 컨벤션은 [BEM](https://getbem.com/) 방식을 사용해 주세요. (선택사항)

---

## ❖ 웹 접근성

- 이미지의 경우, 대체 텍스트 제공이 필요합니다.
- 마우스로 조작할 수 있는 기능은 키보드로도 접근 및 조작이 가능해야 합니다.
- 폼 컨트롤은 식별 가능한 레이블이 필요합니다.
  (시각적으로 표현되지 않더라도 스크린 리더가 읽을 수 있게 처리해야 합니다)
- 명도대비는 최소 4.5대 1을 준수해야 합니다. (`24px`, `18px Bold`인 경우, 최소 3대 1까지 허용 → [참고](https://www.w3.org/TR/WCAG22/#contrast-minimum))
- 좀 더 상세한 웹접근성 가이드 라인 및 [체크리스트](https://www.notion.so/32d50962016c4c90a04c8447298434fc?pvs=21)는 사람인에서 공개한 정보를 참고해 주세요.

  [소개 | 사람인 웹 접근성 교육](https://saramin.github.io/a11y)

  ***

## ❖ 웹 프로그래밍

- 처음 제공해드린 `data.json`에 추가적으로 데이터를 모델링하여 주세요.
- 코드의 일관성, 가독성, 함수 분리, 폴더 구조 설계, 코드 품질 등을 기준으로 세부적인 평가가 이루어 집니다.
- [json-server](https://github.com/typicode/json-server)를 사용하여 서버를 구동 하며 해당 사이트에서 제공된 API 명세서를 따릅니다.
  [GitHub - typicode/json-server: Get a full fake REST API with zero coding in less than 30 seconds (seriously)](https://github.com/typicode/json-server)
- `README.md` 파일은 꼭 작성해주세요. 팀원 소개와 프로젝트의 소개 등 자유롭게 작성해주시면 됩니다.
- 가능하다면 함수 중심으로 프로그래밍 하여 개발해주세요.

---

## ❖ git commit 규칙

1. 주제 (작업내용 한줄 요약)
2. 내용 (추가 된 내용 상세하게 기재)
3. 푸터 (이슈 번호 및 참고사항 기재)

---

## ❖ git flow branch 전략

![캡처](https://github.com/energizo/lion-place/assets/134567486/9330e33a-7d66-4881-b986-caf60a30c1a1)

---

## ❖ 코딩 컨벤션

- ASI를 이용하지 않고 세미콜론을 필수적으로 써준다. (prettier로 관리)
- 함수 작성시 일반함수를 기본규칙으로 하되, 코드 길이가 짧은 함수는 화살표 함수로 작성한다.
- var를 쓰지 않고, const와 let으로 구성한다.(단, const를 주로 쓰되 변수의 값 변경이 필요할 경우 let을 쓴다.)
- image, svg는 단어와 단어사이 -를 사용해 네이밍한다. (ex. erase-check.svg).
- 변수명은 camelCase로 작성한다. (issueLabel).
- webpack alias를 이용해서 파일 절대 경로로 import, export 사용한다.
- 코딩시 단락 구분이 쉽도록 주석을 잘 작성한다. 수정한 내용이 있을 경우 날짜와 함께 작업한 내용을 적어준다.
- 이벤트 핸들러는 on + 메소드명 + Handler로 정의한다. (ex. onClickHandler).
- 액션 크리에이터 함수는 함수명 뒤에 무조건 Action을 붙혀줍니다. (ex. signAction).
- sign in sign up 단어는 두개의 단어로 생각하여 카멜케이스를 사용할 때 signIn signUp으로 사용해준다.
- 서버요청 관련 코드에서는 무조건 status 값을 받아 체크해주고 try catch문으로 묶어준다.









