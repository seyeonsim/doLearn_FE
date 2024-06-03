# <img src="https://github.com/seyeonsim/doLearn_FE/blob/f3a27f32e6953326e73b27fbd2b2002ceccbb157/public/favicon.png" width="50"> 두런두런
캐릭터와 재미있게 대화하며 영어 공부를 할 수 있는 웹 서비스

<br />

> 📅 개발 기간 : 2024.02.29 ~ 2024.04.02
> 
> 🔗 배포 주소 : https://43.203.227.36.sslip.io/

<br /><br /><br />

## 개발 팀 소개

| 이름 | 역할 |  |
| --- | --- | --- |
| [한우리](https://github.com/Hanwoori00) | Back-end | - Chat AI 선정 <br /> - 캐릭터 AI와 대화 기능 구현 <br /> - 학습하기 예문 생성 구현 |
| [이정원](https://github.com/symbicort) | Back-end | - 서버 구축 및 배포 <br /> - SSL 인증서 발급 및 https 연결 설정 <br /> - TTS API 기능 구현 <br /> - User 기능 API 구현 |
| [심세연](https://github.com/seyeonsim) | Back-end | - Chat AI 선정 <br /> - STT 기능 <br /> - 미션 표현 데이터 생성  <br /> - 캐릭터와의 대화에서 미션 표현 사용 여부 판단 |
| [김상호](https://github.com/roo2bos) | Front-end | - 대화하기 <br /> - 대화목록|
| [손호성](https://github.com/ghtjd1358) | Front-end | - Redux-toolkit을 이용한 상태관리 <br /> - 로그인, 마이페이지 구현 <br /> - 마이페이지 생성, 수정, 삭제 기능 구현 <br /> - React-hook-form을 이용한 유효성 검사 <br /> - 랜딩 페이지, error 페이지 구현 <br /> - 퀴즈 기능 구현 |
| [한지혜](https://github.com/jihyehan91) | Front-end | - CSS 전반 <br /> - 메인 페이지 |

<br /><br /><br />

## 기술 스택

### Front-end
<div>
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=white">
  <img src="https://img.shields.io/badge/TYPESCRIPT-3178C6?style=for-the-badge&logo=TYPESCRIPT&logoColor=white">
  
  #### - BUILD
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=Vite&logoColor=white">
  
  #### - LIBRARY
  <img src="https://img.shields.io/badge/reacthookform-EC5990?style=for-the-badge&logo=reacthookform&logoColor=white">
  
  #### - NPM
  <div>
    <img src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=Axios&logoColor=white">
    <img src="https://img.shields.io/badge/Tailwind CSS-06B6D4?style=for-the-badge&logo=Tailwind CSS&logoColor=white">
    <img src="https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=Redux&logoColor=white">
  </div>
</div>

<br />

### Back-end
<div>
  ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
  <img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white">
  <img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
  <img src="https://img.shields.io/badge/googlecloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white">    <img src="https://img.shields.io/badge/caddy-1F88C0?style=for-the-badge&logo=caddy&logoColor=white">
  
   #### - DevOps
  <div>
    <img src="https://img.shields.io/badge/nginx-009639?style=for-the-badge&logo=nginx&logoColor=white">
    <img src="https://img.shields.io/badge/amazonec2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white">
  </div>
  
  #### - DataBase
  <div>
    <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysqly&logoColor=white">
    <img src="https://img.shields.io/badge/mongodb-47A248?style=for-the-badge&logo=mongodb&logoColor=white">
  </div>
</div>

<br />

### Cooperation Tools
<div>
    <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
    <img src="https://img.shields.io/badge/figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white">
    <img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white">
</div>

<br /><br /><br />

## 주요 기능

### 💬 대화하기
| 기능 | |
| --- | --- |
| 🔊 <br /> Speech-to-Text | <video src="https://github.com/seyeonsim/doLearn_FE/assets/148730784/b0812ec3-f12f-4300-8a77-b12a24e2abec" /> |
| 🔊 <br /> 캐릭터 AI와 대화, <br /> 답변 Text-to-Speech | <video src="https://github.com/seyeonsim/doLearn_FE/assets/148730784/8e5fd450-36ed-44f4-b2e6-ec2ed55a320b" /> |
| 대화의 감정에 따라 바뀌는 캐릭터 | ![감정](https://github.com/seyeonsim/doLearn_FE/assets/148730784/6887e5b8-f811-4022-bb5a-500a2626a88b) |
| 미션(학습하기 - 학습 완료) 표현 사용 여부 판단 | ![대화 미션](https://github.com/seyeonsim/doLearn_FE/assets/148730784/cbf9ffe5-66e6-4aaa-b389-a50bc5a44b6e) |
| 대화 종료 버튼 클릭 <br /> : 대화 종료(저장) 및 문법 교정 | ![대화종료, 교정](https://github.com/seyeonsim/doLearn_FE/assets/148730784/34ebca06-b5eb-4dc1-a8a9-1df5c55a2afc) <br /> <img src="https://github.com/seyeonsim/doLearn_FE/assets/148730784/d755ba9e-5c37-4fd1-8f41-a67f50341c9e" width="1200" />|

<br /><br />

### 📖 학습하기
| 기능 | |
| --- | --- |
| 수준별 표현 | <img width="1209" alt="수준별" src="https://github.com/seyeonsim/doLearn_FE/assets/148730784/6140b36f-e66e-4f4d-ae95-0e792201b2a9"> |
| AI 활용 예문 생성 | ![예문](https://github.com/seyeonsim/doLearn_FE/assets/148730784/6a2f84f7-5739-42d6-808c-ac7b3bf07b98) |
| 학습 완료, 해당 표현은 대화하기 미션으로 할당됨 | ![학습 완료](https://github.com/seyeonsim/doLearn_FE/assets/148730784/eda0dd34-9377-4bc0-a0d7-b610e1af6d22) |
| 퀴즈 | ![퀴즈](https://github.com/seyeonsim/doLearn_FE/assets/148730784/8b6b2e86-f6b6-42ec-89ed-2ebdca6f7b22) |
