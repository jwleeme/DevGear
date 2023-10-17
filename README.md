<img src="https://kdt-gitlab.elice.io/sw_track/class_06/web_project/team05/teamtotal/uploads/97350ef12d03f8e73cd93123958c4452/%EB%B0%B0%EB%84%88.png" alt="쇼핑몰 배너 이미지" style="width:600px"/>
- 배포 URL : https://kdt-sw-6-team05.elicecoding.com/
<br/> => 사전에 회원가입/로그인 시 회원쪽에서 JWT token 값을 localStorage에 담고있어 로그아웃(=비회원) 상태에서 구매하기/장바구니 버튼을 눌렀을때 로그인하라는 alert가 뜨지않고 바로 주문/장바구니 페이지로 이동합니다.

## 🛒 프로젝트 명

- DevGears

## 🖥️ 프로젝트 소개

- 컴퓨터 장비에 관심있는 개발자들을 위해 만들어진 쇼핑몰입니다.

## 🕰️ 개발 기간

- 23.10.02(월) ~ 23.10.13(금) (2주간)

## 🧑‍🤝‍🧑 멤버 구성

- 팀장 : 이민섭(BE)
- 팀원1 : 김효인(BE)
- 팀원2 : 최정윤(FE)
- 팀원3 : 이성민(FE)
- 팀원4 : 이지원(FE)

## ⚙️ 환경 및 기술 스택

### Run-time env & Manage
<img src="https://img.shields.io/badge/Node.js-339933.svg?&style=for-the-badge&logo=Node.js&logoColor=white">
<img src="https://img.shields.io/badge/PM2-2B037A.svg?&style=for-the-badge&logo=PM2&logoColor=white">

### Front-end
<img src="https://img.shields.io/badge/HTML5-E34F26.svg?&style=for-the-badge&logo=HTML5&logoColor=white">
<img src="https://img.shields.io/badge/CSS3-1572B6.svg?&style=for-the-badge&logo=CSS3&logoColor=white">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?&style=for-the-badge&logo=JavaScript&logoColor=white">
<img src="https://img.shields.io/badge/bulma-00D1B2.svg?&style=for-the-badge&logo=bulma&logoColor=white">

### Back-end
<img src="https://img.shields.io/badge/Express-000000.svg?&style=for-the-badge&logo=Express&logoColor=white">
<img src="https://img.shields.io/badge/MongoDB-47A248.svg?&style=for-the-badge&logo=MongoDB&logoColor=white">
<img src="https://img.shields.io/badge/Mongoose-880000.svg?&style=for-the-badge&logo=Mongoose&logoColor=white">
<img src="https://img.shields.io/badge/Nginx-009639.svg?&style=for-the-badge&logo=Nginx&logoColor=white">

## 📌 주요 기능

- 네비게이션 바를 통해 카테고리, 로그인, 검색 제공
- 로그인은 JWT를 통해 암호화
- 카테고리는 2계층으로 구성
- 상품 리스트는 페이징 및 정렬 가능
- 상품 장바구니 추가 및 주문 가능
- 관리자를 통해 상품, 카테고리, 유저, 주문 데이터에 대해 CRUD
- Nginx를 통해 프록시 설정
- HTTPS (SSL) 설정

## 💾 프로젝트 구조

├─ .gitignore <br>
├─ .gitlab-ci.yml<br>
├─ .prettierrc<br>
├─ API명세 팁.txt<br>
├─ README.md<br>
├─ api specs<br>
├─ gitlab-ci.yml<br>
├─ index.js<br>
├─ middlewares<br>
├─ models<br>
├─ package-lock.json<br>
├─ package.json<br>
├─ services<br>
├─ utils<br>
└─ views<br>
│  ├─ admin<br>
│  ├─ cart<br>
│  ├─ common<br>
│  ├─ login<br>
│  ├─ mainPage<br>
│ ├─ mypage<br>
│  ├─ paymentPage<br>
│  ├─ product<br>
│  ├─ productList<br>
│  ├─ signUp<br>
│  └─ utils
