# Quizly: 3D 상호작용 기반의 몰입형 퀴즈 풀이 서비스

<!-- <img src="path/to/quizly_logo.png" alt="Quizly Logo" width="200"/> -->

## 프로젝트 개요

Quizly는 3D 환경에서 실시간 상호작용을 통해 즐겁고 효과적인 학습 경험을 제공하는 혁신적인 퀴즈 플랫폼입니다.

## 시스템 아키텍처

Quizly는 다음 네 개의 주요 컴포넌트로 구성되어 있습니다:

1. **API 서버** (Spring Boot)

   - 사용자 관리, 퀴즈 CRUD, 결과 분석 등 핵심 비즈니스 로직 처리
   - 기술 스택: Java, Spring Boot, JPA, MySQL

2. **프론트엔드** (React, Three.js)

   - 사용자 인터페이스 및 3D 퀴즈 환경 구현
   - 기술 스택: React, Three.js, React Three Fiber

3. **실시간 통신 서버** (Nest.js)

   - 실시간 퀴즈 진행, 사용자 간 상호작용 처리
   - 기술 스택: Node.js, Nest.js, Socket.io

4. **화상 통화 서버** (OpenVidu)
   - WebRTC 기반 실시간 화상 통화 기능 제공
   - 기술 스택: OpenVidu, LiveKit

### 시스템 아키텍쳐

<img src="./img/아키텍쳐.png" alt="Quizly 아키텍쳐"/>

## 레포지토리 구조

- [quizly-frontend](https://github.com/Quizly-Project/quizly-frontend) - React & Three.js 프론트엔드
- [quizly-spring](https://github.com/Quizly-Project/quizly-Spring) - Spring Boot API 서버
- [quizly-nest](https://github.com/Quizly-Project/quizly-Nest) - Nest.js 실시간 통신 서버
<!-- - [quizly-openvidu](https://github.com/Quizly-Project/quizly-multiCam) - OpenVidu 기반 화상 통화 서버 -->

## 설치 및 실행 방법

각 레포지토리의 README를 참조하세요.

## 팀 정보

이 프로젝트는 크래프톤 정글 5기 '나만의 무기 만들기' 최종 팀 프로젝트로 개발되었습니다.

- **프로젝트명**: Quizly - 3D 상호작용 기반의 몰입형 퀴즈 풀이 서비스
- **개발 기간**: 2024.06.21 - 2024.07.27 (5주)
- **팀명**: 크래프톤 정글 5기 1교육장 2팀

### 팀원 소개

| 이름   | 역할               | GitHub                                         |
| ------ | ------------------ | ---------------------------------------------- |
| 김현수 | Frontend Developer | [@hyunS00](https://github.com/hyunS00)         |
| 신동우 | Backend Developer  | [@NoNoise2022](https://github.com/NoNoise2022) |
| 유영우 | Backend Developer  | [@yoo20370](https://github.com/yoo20370)       |
| 조재룡 | Backend Developer  | [@jjr7181](https://github.com/jjr7181)         |
| 황연경 | Frontend Developer | [@yunnn426](https://github.com/yunnn426)       |
