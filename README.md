# reactjs-example
React JS repository for running



## Setup & Setting

- React JS 개발에 필요한 프로그램 및 IDE 설치
- 현재 개발하는 PC의 OS는 Window 10 

###

### Node.js (NPM)

- Download
  - https://nodejs.org/ko/
  - Stable 버젼 다운로드
- Node JS
  - Chrome V8 JavaScript엔진 기반의 JavaScript Server
- NPM(Node Package Manager)
  - Java의 Maven / Ant 같은 역할을 하는 패키지 매니저이다.
  - 중요 역할은 모듈의 설치 및 버젼관리
  - 최근엔 yarn이 많이 사용되고 있다.
  - CMD / Terminal 에서 "npm {option}" 으로 필요 라이브러리를 직접 설치하기도 하고 패키지를 말기도 한다.
- 노드 JS 기반 개발도구
  - babel
    - ECMAScript 6를 Target Browser 환경에 맞게 호환을 돕는 개발 도구
  - webpack
    - 코드 수정 시, 자동 페이지 로딩처리를 해주는 도구



###yarn & create-react-app 설치

- Download
  - https://yarnpkg.com/en/docs/install#windows-stable
- 사용법
  - https://yarnpkg.com/en/docs/usage
- create-react-app
  - React JS 프로젝트 초기생성 시 필요한 설정 / 도구 등을 미리 생성해주는 간편 명령어(도구)
  - 프로젝트에서만 사용할 수도 있고(local), 모든 프로젝트에서 사용할 수 있게 전역(global)로 설정할 수도 있다.
  - 설정
    - yarn global add create-react-app
    - npm install -g create-react-app



### Visual Studio Code

- Download
  - https://code.visualstudio.com/
- Extention (Recommend)
  - ESLint : JavaScript 문법 체크
  - Reactjs Code Snippets (by Charalampos Karypidis): 리액트 관련 스니펫 모음
- Extention (Optional)
  - RelativePath :  상대경로 작성을 돕는 도구
  - Guides : 들여쓰기 가이드라인
  - React-beautify : React JS 코드 정리



### Git

- Download
  - https://git-scm.com/downloads



### create-react-app 를 통해 프로젝트 생성 및 실행

- 명령어
  - create-react-app {project_name}
  - cd {project_name}
  - yarn start 또는 npm start

