<p align="center">
  <a href="https://github.com/devxb/gitanimals">
    <img src="https://render.gitanimals.org/farms/piwoori" width="800" />
  </a>
</p>

<br/>

<p align="center">
  <img src="https://raw.githubusercontent.com/piwoori/piwoori/output/github-contribution-grid-snake.svg" />
</p>

<br/>

## 👋 About Me

Backend developer focused on **AI-powered services, system architecture, and security-aware backend design**.

I enjoy designing **API-driven services**, integrating **AI models into real applications**,  
and building systems that are **scalable, secure, and maintainable**.

- 🧩 Backend-focused Computer Science student (Senior)
- 🛡️ Interested in **Security Architecture & system design**
- 🤖 Experience building **AI-powered service architectures**
- 🎓 B.S. in Computer Science

<br/>

## 🧱 Tech Stack

<table>
  <tr>
    <td width="140"><b>Language</b></td>
    <td>
      <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=Java&logoColor=white"/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/>
      <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=MySQL&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td><b>Backend</b></td>
    <td>
      <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=SpringBoot&logoColor=white"/>
      <img src="https://img.shields.io/badge/Spring%20Data%20JPA-59666C?style=flat-square"/>
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=MySQL&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td><b>AI / Data</b></td>
    <td>
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=PyTorch&logoColor=white"/>
      <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square"/>
    </td>
  </tr>
  <tr>
    <td><b>Infra / Tools</b></td>
    <td>
      <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=AmazonAWS&logoColor=white"/>
      <img src="https://img.shields.io/badge/Git-181717?style=flat-square&logo=Git&logoColor=white"/>
      <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/>
    </td>
  </tr>
</table>

<br/>

## 🏆 Awards

- 🥈 **우수논문상 (은상)**  
  2024 한국정보기술학회 학술대회 — AI 기반 재활용 분리수거 보조 시스템  

- 🥉 **우수논문상 (동상)**  
  2025 한국정보기술학회 하계종합학술대회 — 특별 구역 불법 주차 대응 AI 시스템  

- 🥉 **캡스톤 디자인 경진대회 (동상)**  
  AI 융합 백엔드 시스템 프로젝트

<br/>

## 📜 Certifications & Scores

- 📜 **정보처리기사** (Engineer Information Processing)  
- 🧠 **TOPCIT Level 3**

<br/>

## 🚀 Projects
### 🛡️ Re-트리버  
AI 기반 재활용 분리수거 보조 시스템 (시각장애인 보조 서비스)

시각장애인이 쓰레기 사진을 촬영하면 AI가 객체를 인식하고  
재활용 분류 정보를 **음성 안내(TTS)**로 제공하는 접근성 중심 서비스입니다.

- **Role:** 서버 아키텍처 기획 및 시스템 설계, 논문 작성
- **AI Model:** YOLOv5 기반 이미지 객체 인식
- **Data:** AI Hub 재활용품 분류 데이터셋 활용
- **System Flow:**  
  사용자 촬영 이미지 → 서버 AI 분석 → 재활용 분류 결과 생성 → TTS 음성 안내 제공
- **Focus:** AI 모델을 활용한 접근성 중심 서비스 아키텍처 설계
- **Achievement:** 🥈 한국정보기술학회 우수논문상 (은상)

<br/>

### 🚗 불법주차 감지 AI 시스템  
스마트폰 기반 객체 탐지 + 서버 연동 자동 신고 시스템

특별 주차 구역(장애인 구역, 소화전, 어린이 보호구역 등)의  
불법 주차 차량을 **스마트폰 기반 AI 객체 탐지 모델로 실시간 감지**하고  
관리자에게 알림 및 신고 기능을 제공하는 시스템입니다.

- **Role:** 팀장 (PM)
- **Responsibility:** AI 모델 학습, 서버 API 설계, 전체 시스템 아키텍처 설계
- **AI Model:** YOLOv8 객체 탐지 모델
- **Dataset:** 약 10,000장의 특별 구역 이미지 데이터 학습
- **Detection Target**
  - 특별 주차 구역 (장애인 구역, 소화전, 어린이 보호구역)
  - 차량 객체
- **System Architecture**
  - Mobile App → Backend API → AI Server → 관리자 알림
- **Infra:** AWS Cloud
- **Security:** Hyperledger Fabric 기반 신고 데이터 로그 관리
- **Stack:** Python, YOLOv8, FastAPI, MySQL
- **Achievement**
  - 🥉 캡스톤 디자인 경진대회 동상
  - 🥉 한국정보기술학회 우수논문상 (동상)

<br/>

### 🌱 Growlog  
AI 기반 감정 기록 및 자기관리 서비스

사용자의 **할 일, 감정 기록, 회고 데이터를 통합 관리**하고  
AI 감정 분석을 통해 자기 관리 패턴을 시각화하는 서비스입니다.

- **Role:** 서비스 기획, DB 설계, Backend API 개발
- **Stack:** Spring Boot, JPA, MySQL
- **Focus**
  - 사용자 활동 데이터를 통합 관리하는 서비스 API 설계
  - 감정 분석 AI 서버와 연동하는 데이터 흐름 설계
  - 감정 기록 및 회고 데이터를 기반으로 한 자기관리 서비스 구조 구현
- **System Architecture**
  - Frontend → Backend API → Database → AI Server
- **Repos**

<a href="https://github.com/piwoori/growlog-frontend"><img src="https://img.shields.io/badge/Frontend-github-181717?style=flat-square&logo=github&logoColor=white"/></a>
<a href="https://github.com/piwoori/growlog-backend"><img src="https://img.shields.io/badge/Backend-github-181717?style=flat-square&logo=github&logoColor=white"/></a>
<a href="https://github.com/piwoori/growlog-ai"><img src="https://img.shields.io/badge/AI-github-181717?style=flat-square&logo=github&logoColor=white"/></a>
