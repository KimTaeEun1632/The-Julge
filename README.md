<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=250&section=header&text=The%20Julge&fontSize=50&fontAlignY=40" />

# The Julge
> 팀프로젝트 <br>
> 개발기간: 2024.04.15 ~ 2024.05.01

# 배포주소
> https://the-julge-dusky.vercel.app/

# 팀원소개
| <img src="https://avatars.githubusercontent.com/u/84865501?v=4,naeun14,naeun_,https://github.com/naeun14" width="150" height="150"/> | <img src="https://avatars.githubusercontent.com/u/59686080?v=4,jinhok96,,https://github.com/jinhok96" width="150" height="150"/> | <img src="https://avatars.githubusercontent.com/u/155213331?v=4,KimTaeEun1632,,https://github.com/KimTaeEun1632" width="150" height="150"/> | <img src="https://avatars.githubusercontent.com/u/96658105?v=4,kong33,,https://github.com/kong33" width="150" height="150"/> | <img src="https://avatars.githubusercontent.com/u/110177217?v=4,min3eo,,https://github.com/min3eo" width="150" height="150"/> |
| :----------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------: |
|                                                [@naeun14](https://github.com/naeun14)                                                |                                             [@jinhok96](https://github.com/jinhok96)                                             |                                             [@KimTaeEun1632](https://github.com/KimTaeEun1632)                                              |                                             [@kong33](https://github.com/kong33)                                             |                                             [@min3eo](https://github.com/min3eo)                                              |


# 프로젝트 소개 
'The-julge'는 구인구직 매칭 플래폼의 기본 기능을 중심으로 한 웹 애플리케이션입니다. <br>
조건을 입력해 일자리를 검색하는 기능과 사용자는 원하는 일자리에 지원하고, 근무 승인을 받는 기능을 제공합니다. 고용인이 더 높은 시급을 제공할 경우, 시급 인상률을 기준으로 일자리를 정렬하는 기능을 제공합니다. 

# 시작 가이드

### 1. 저장소 클론
```bash
git clone https://github.com/KimTaeEun1632/The-Julge.git
cd The-Julge
```

### 2.Node.js 버전 설정 (nvm 사용 시)
```bash
nvm use 20.12.1
```

### 3. 의존성 설치 및 실행
```bash
npm install
npm run dev
```
---
# 📚 STACKS
<p>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=Next.js&logoColor=white">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=TypeScript&logoColor=white">
  <img src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white">
  <img src="https://img.shields.io/badge/TanStack%20Query-FF4154?style=for-the-badge&logo=react%20query&logoColor=white">
  <img src="https://img.shields.io/badge/Styled%20Components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white">
</p>

# 🤲협업 툴
<p>
  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
  <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/discord-5865F2?style=for-the-badge&logo=discord&logoColor=white">
  <img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white">
  <img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white">
</p>

# 🔎 미리보기

| 메인 페이지 | 회원가입 페이지 | 내 가게(사장님) |
|-------------|--------------|----------------|
| ![메인 페이지](https://github.com/user-attachments/assets/7ecc260d-6ef7-4136-bc64-9376f723fa51) | ![로그인 페이지](https://github.com/user-attachments/assets/86d8ad19-3b5f-403a-9cdf-78cde89cc24b) | ![내 가게](https://github.com/user-attachments/assets/60446087-df18-4c03-a155-6ee4703f1f1d) | ![공고등록](https://github.com/user-attachments/assets/870f6a3b-f249-4331-9dde-e30169b6e81e) |


| 공고등록(사장님) | 근무신청(알바생) | 신청자 목록(사장님) |
|----------------|-------------|-------------|
|![공고등록](https://github.com/user-attachments/assets/870f6a3b-f249-4331-9dde-e30169b6e81e) | ![근무 신청](https://github.com/user-attachments/assets/c909ad69-f266-4b6b-a24b-b829b881f7e0) | ![신청자 목록](https://github.com/user-attachments/assets/bc5f0154-5d09-4842-afcd-24a1b6233c19) |

> **Tip**  
> 클릭하면 원본 크기로 크게 볼 수 있어요!  


- **프로젝트 내용**
  - 사용자는 사장님, 알바생 2유형으로 회원가입이 가능하면 유형에 따라 다른 기능을 제공합니다.
  - 사장님은 내 가게를 등록하고 공고를 올릴 수 있으며, 공고 현황에서 신청자 목록을 확인, 승인, 거절을 할 수 있습니다.
  - 공고는 최저임금을 기준으로 하며, 최저임금보다 높을 경우 몇 퍼센트가 높은지 표시가 됩니다.
  - 알바생은 내 프로필 등록후 공고 지원이 가능하며 임금순, 최신순, 마감순으로 공고 확인을 통해 신청을 할 수 있습니다.


# 파일 구조
```
The-Julge
├── pages
│   ├── notice
│   │   └── [shopId]
│   │       └── [noticeId]
│   │           ├── index.module.scss
│   │           └── index.tsx
│   ├── search
│   │   └── index.tsx
│   ├── shop
│   │   ├── register
│   │   │   ├── index.module.scss
│   │   │   └── index.tsx
│   │   └── [shopId]
│   │       ├── edit
│   │       │   ├── index.module.scss
│   │       │   └── index.tsx
│   │       ├── register
│   │       │   ├── index.module.scss
│   │       │   └── index.tsx
│   │       ├── [noticeId]
│   │       │   ├── index.module.scss
│   │       │   └── index.tsx
│   │       ├── index.module.scss
│   │       └── index.tsx
│   ├── user
│   │   ├── edit
│   │   │   ├── index.module.scss
│   │   │   └── index.tsx
│   │   ├── register
│   │   │   ├── index.module.scss
│   │   │   └── index.tsx
│   │   ├── index.module.scss
│   │   └── index.tsx
│   ├── 404.tsx
│   ├── index.module.scss
│   ├── index.tsx
│   ├── login.tsx
│   ├── signup.tsx
│   ├── _app.tsx
│   └── _document.tsx
├── public
│   ├── images
│   └── svgs
└── src
    ├── apis
    │   ├── alert
    │   ├── application
    │   ├── authentication
    │   ├── image
    │   ├── notice
    │   ├── shop
    │   ├── user
    │   ├── common.type.ts
    │   ├── interceptors.ts
    │   ├── requestor.ts
    │   └── utils.ts
    ├── components
    │   ├── common
    │   ├── Employer
    │   ├── feature
    │   └── layout
    ├── layouts
    ├── libs
    │   ├── constants
    │   ├── contexts
    │   ├── hooks
    │   └── utils
    └── styles
 ```
