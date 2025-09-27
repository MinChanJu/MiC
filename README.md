# MiC (Mathematics in Coding)

온라인 프로그래밍 대회 및 문제 관리 시스템

## 🌐 Live Demo

**접속 주소:** https://minchanju.github.io/MiC/

## 🔍 프로젝트 소개

MiC는 아주대학교 수학과 소학회입니다. 이 소학회는 프로그래밍에 대한 멘토링과 프로젝트 및 프로그래밍 대회를 주최하는 소학회입니다. 2024년 저는 이 소학회의 회장을 맡았습니다. 이 프로젝트는 프로그래밍 대회를 주최하고 관리할 수 있는 웹 플랫폼입니다. 사용자는 대회를 생성하고, 문제를 출제하며, 참가자들의 점수를 확인할 수 있습니다.

### 주요 기능

- 📝 **대회 관리**: 대회 생성, 수정, 삭제 및 관리
- 🧮 **문제 관리**: 프로그래밍 문제 작성 및 편집 (MathJax 수식 지원)
- 👥 **사용자 관리**: 로그인, 회원가입, 프로필 관리
- 🏆 **점수판**: 실시간 대회 순위 확인
- 📢 **공지사항**: 대회 관련 공지사항 관리

## 🛠️ 기술 스택

### Frontend
- **React 18** - UI 라이브러리
- **TypeScript** - 타입 안전성
- **React Router DOM** - 클라이언트 사이드 라우팅
- **Vite** - 빌드 도구
- **Axios** - HTTP 클라이언트
- **MathJax** - 수학 수식 렌더링

### Development Tools
- **ESLint** - 코드 품질 관리
- **GitHub Pages** - 배포 플랫폼

## 📂 프로젝트 구조

```
src/
├── api/              # API 호출 관련 모듈
├── assets/           # 정적 자원 (이미지, CSS)
├── components/       # 재사용 가능한 컴포넌트
├── constants/        # 상수 정의
├── context/          # React Context
├── hooks/            # 커스텀 훅
├── pages/            # 페이지 컴포넌트
├── styles/           # 전역 스타일
├── types/            # TypeScript 타입 정의
└── utils/            # 유틸리티 함수
```

## 🚀 시작하기

### 필수 조건
- Node.js 18.0.0 이상
- npm 또는 yarn

### 설치 및 실행

1. **저장소 클론**
   ```bash
   git clone https://github.com/MinChanJu/MiC.git
   cd MiC
   ```

2. **의존성 설치**
   ```bash
   npm install
   ```

3. **개발 서버 실행**
   ```bash
   npm run dev
   ```

4. **빌드**
   ```bash
   npm run build
   ```

5. **배포**
   ```bash
   npm run deploy
   ```

## 📱 주요 페이지

- **홈 (`/`)** - 메인 대시보드
- **대회 목록 (`/contest`)** - 전체 대회 목록
- **대회 상세 (`/contest/:id`)** - 특정 대회 정보 및 문제 목록
- **문제 보기 (`/problem/:id`)** - 문제 상세 페이지
- **점수판 (`/score/:id`)** - 대회별 순위표
- **사용자 프로필 (`/user/:id`)** - 사용자 정보 및 제출 기록
- **관리 페이지** - 대회 및 문제 생성/편집

## 🎯 주요 특징

### 수식 지원
Better React MathJax를 통해 LaTeX 형식의 수학 수식을 완벽하게 렌더링합니다.

### 반응형 디자인
모든 기기에서 최적화된 사용자 경험을 제공합니다.

### 실시간 업데이트
대회 진행 상황과 점수판이 실시간으로 업데이트됩니다.

## 👨‍💻 개발자

**MinChanJu** - [GitHub](https://github.com/MinChanJu)