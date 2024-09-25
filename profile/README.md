# TEAM4 - 사이클링홈런⚾️

## ⭐️ About Team
> 유데미 X 스나이퍼팩토리 React 2기 4팀
- 팀명: 사이클링홈런
- 팀소개: 완봉과 퍼펙트게임을 모두 이루며, 최고의 성과를 만들어가자💥
- 팀목표: 최고의 UI/UX/DX를 위하여 런앤히트 ⚾
- 프로젝트 기업: KT

## 🚀 Project

- (24.09.02~24.09.27) React로 KTwiz 정보제공 페이지 만들기
  - 기존 KT wiz 홈페이지의 UI를 전면 개편하였습니다.
      - 딱딱하고 불편했던 기존 UX를 대폭 개선하였습니다.
      - 사용자 경험을 향상시키기 위해 흥미를 유발하는 애니메이션을 추가하였습니다.

&nbsp;

## 🔧 Tech

<div align="center">

|      Type       |                                                                                                                  Tool                                                                                                                   |
| :-------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|     Library     |                   ![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=black) ![VITE](https://img.shields.io/badge/VITE-646CFF?style=for-the-badge&logo=Vite&logoColor=white)                    |
|    Language     |                                                          ![TyoeScript](https://img.shields.io/badge/TypeScript-3178C6.svg?style=for-the-badge&logo=TypeScript&logoColor=black)                                                          |
|     Styling     |                                                          ![TailwindCSS](https://img.shields.io/badge/tailwindcss-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)                                                           |
|  Data Fetching  |          ![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=Axios&logoColor=white) ![ReactQuery](https://img.shields.io/badge/reactquery-FF4154?style=for-the-badge&logo=reactquery&logoColor=white)           |
|   Formatting    |           ![ESLint](https://img.shields.io/badge/ESLint-4B3263?style=for-the-badge&logo=eslint&logoColor=white) ![Prettier](https://img.shields.io/badge/prettier-1A2C34?style=for-the-badge&logo=prettier&logoColor=F7BA3E)            |
| Package Manager |                                                                      ![Npm](https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white)                                                                       |
| Version Control |            ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)             |
|   Deployment    | ![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=Vercel&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=GitHub%20Actions&logoColor=white) |
|  Collaboration  |             ![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white) ![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)              |

</div>

&nbsp;

## 🔩 프로젝트 설정 및 실행 방법

### 1. 프로젝트 클론하기

먼저, Git 저장소에서 프로젝트를 로컬로 클론해야 합니다. 터미널(또는 명령 프롬프트)을 열고 아래 명령어를 입력합니다.

```bash
git clone https://github.com/Team-4yclingHomerun/4yclinghomerun-client.git
```

해당 명령어는 지정된 Git 저장소에서 프로젝트를 로컬 컴퓨터로 복사해옵니다.

### 2. 의존성 설치

프로젝트가 로컬에 클론된 후, 프로젝트 폴더로 이동한 다음, 필요한 패키지들을 설치해야 합니다. 
Node.js 기반 프로젝트인 경우, `npm` 명령어를 사용하여 의존성을 설치할 수 있습니다.

```bash
npm install
```

이 명령어는 `package.json` 파일에 정의된 모든 의존성(dependencies)을 자동으로 설치해 줍니다.

### 3. 개발 서버 실행

모든 의존성이 설치되면, 개발 서버를 실행하여 프로젝트를 로컬에서 테스트할 수 있습니다.

```bash
npm run dev
```

이 명령어를 통해 개발 모드에서 서버를 시작하며, 변경 사항이 있을 때 자동으로 갱신됩니다.
이후, 브라우저에서 `http://localhost:5173` 주소로 접속하여 애플리케이션을 확인할 수 있습니다.

&nbsp;

## ✉️ Conventions

### 커밋 컨벤션

- `feat`: 새로운 기능 추가
- `style`: css 수정 및 코드의 의미에 영향을 미치지 않는 변경사항
- `fix`: 버그 수정
- `refactor`: 리팩토링, 기능 변화 없이 코드 구조 개선
- `chore`: 코드 수정 외 잡다한 작업 (빌드 과정이나 설정 변경 등)
- `docs`: 문서 변경 
- `perf`: 성능을 향상시키는 코드 변경
- `test`: 테스트 코드 추가 또는 수정 
- `build`: 빌드 시스템 또는 외부 종속성 관련 변경
- `ci`: CI 구성 파일 및 스크립트 변경 
- `revert`: 이전 커밋을 되돌림

### 파일 컨벤션

- 폴더명: LowerCase || kebab-case
- 파일명: PascalCase

### 코드 컨벤션

- 함수: const Component = () => {} / export default Component
- `export` 구문: 하단
- 타입명: `type PlayerProps` (PascalCase)
- 타입 내부 키 값: `playerName: string` (camelCase)
- 상수: `UPPER_SNAKE_CASE`

&nbsp;

## 🐹 Members

|[![hdayeon](https://avatars.githubusercontent.com/u/147478174?v=4)](https://github.com/hdayeon)|[![jungkyuYang](https://avatars.githubusercontent.com/u/67031524?v=4)](https://github.com/jungkyuYang)|[![HyoKyoungLee](https://avatars.githubusercontent.com/u/43572462?v=4)](https://github.com/HyoKyoungLee)|[![bbjbc](https://avatars.githubusercontent.com/u/102457140?v=4)](http://github.com/bbjbc)|
|:---:|:---:|:---:|:---:|
|**🐔 [하다연](https://github.com/hdayeon)**|**🐤 [양정규](https://github.com/jungkyuYang)**|**🐤 [이효경](https://github.com/HyoKyoungLee)**|**🐤 [조병찬](http://github.com/bbjbc)**|

