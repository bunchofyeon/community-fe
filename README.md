# 🌲 Piney Community
Spring Boot 3.5 · Express.js · MySQL · Docker · GitHub Actions · AWS(EC2, S3, API Gateway, Lambda)

실제 운영 환경을 목표로 설계된 **풀스택 커뮤니티 웹 서비스**입니다.  
프론트엔드부터 백엔드, Reverse Proxy, CI/CD, AWS 인프라까지 모든 구성 요소를 직접 구축했습니다.

게시글·댓글 CRUD, JWT 인증, 파일 업로드(S3 Presigned URL), Soft Delete, 좋아요 기능, Nginx Reverse Proxy 등  
실제 서비스에 필요한 기능과 운영 환경을 반영한 프로젝트입니다.

---

# 📘 프로젝트 개요

**Piney Community**는 개인적인 고민 공유 + 개발 소통 기능을 제공하는 커뮤니티 서비스입니다.  
아키텍처는 다음과 같이 구성되어 있습니다.

- **Frontend**: Express.js 기반 SPA  
- **Backend**: Spring Boot REST API  
- **Infrastructure**: AWS EC2, S3, API Gateway, Lambda, Route53  
- **Deployment**: Docker, Docker Compose, Private Registry, GitHub Actions CI/CD  
- **Networking**: Nginx Reverse Proxy + HTTPS 

---

## 👩🏻‍💻 개발기간 및 역할
2025.10 ~ 2025.12

## 🎨 Frontend
개인적인 고민과 개발을 주제로 서로 소통하는 커뮤니티 프로젝트의 프론트엔드 버전입니다.

## 🔧 기술스택
	•	Express.js
	•	JavaScript (Vanilla)
	•	HTML/CSS
	•	Docker / Docker Compose
	•	GitHub Actions
	•	Nginx Reverse Proxy


# 🖼 전체 아키텍처 이미지

<img width="2093" height="1525" alt="piney_community" src="https://github.com/user-attachments/assets/b6905518-3950-4d5b-9bab-69bc54f20913" />

---

## 🖼️ 주요 화면

- 로그인
<img width="1579" height="1060" alt="스크린샷 2025-12-06 오후 4 29 20" src="https://github.com/user-attachments/assets/5c6cded8-2686-4f88-9fd0-55c7e4240655" />

- 회원가입
<img width="1579" height="1060" alt="스크린샷 2025-12-06 오후 4 29 26" src="https://github.com/user-attachments/assets/2f235c1e-d1c6-42a1-bd42-4efc32f67b88" />
<img width="1579" height="1060" alt="스크린샷 2025-12-06 오후 4 30 38" src="https://github.com/user-attachments/assets/5c333183-6ba1-4669-a8dd-877ec06ffefa" />


- 게시글 목록
<img width="1579" height="1060" alt="스크린샷 2025-12-06 오후 4 30 54" src="https://github.com/user-attachments/assets/fce94c69-d9ae-4a82-b6b1-0bbfeea74681" />

<img width="1579" height="1060" alt="스크린샷 2025-12-06 오후 4 32 59" src="https://github.com/user-attachments/assets/f4c35164-67d4-4c96-bae9-5035eca06ce3" />

- 게시글 생성
<img width="1579" height="1060" alt="스크린샷 2025-12-06 오후 4 30 59" src="https://github.com/user-attachments/assets/988ddad1-8d99-4982-9932-78428c912913" />
<img width="1579" height="1060" alt="스크린샷 2025-12-06 오후 4 31 22" src="https://github.com/user-attachments/assets/70ee0175-08cd-4487-8df6-8bcff3ddd1d4" />

<img width="1579" height="1060" alt="스크린샷 2025-12-06 오후 4 32 29" src="https://github.com/user-attachments/assets/04616abd-e974-4307-90c1-c550ac03e808" />

- 게시글 수정
<img width="1579" height="1060" alt="스크린샷 2025-12-06 오후 4 32 04" src="https://github.com/user-attachments/assets/ab6f9536-cb6c-43d1-8957-6ad1698983f2" />

- 게시글 삭제
- 게시글 파일 삭제
<img width="1579" height="1060" alt="스크린샷 2025-12-06 오후 4 32 08" src="https://github.com/user-attachments/assets/108185d5-708b-4e2b-b011-03b099d3d796" />
<img width="1579" height="1060" alt="스크린샷 2025-12-06 오후 4 32 08 1" src="https://github.com/user-attachments/assets/76c9385c-b90e-45c7-aeb0-0cf61c0bd093" />


- 댓글 등록
<img width="1579" height="1060" alt="스크린샷 2025-12-06 오후 4 32 34" src="https://github.com/user-attachments/assets/ea59dd27-7533-4b4a-ab2e-8d85d5960e7b" />

- 댓글 수정
<img width="1579" height="1060" alt="스크린샷 2025-12-06 오후 4 32 25" src="https://github.com/user-attachments/assets/a1e41ec8-cdbf-48b9-bc56-91c7251b8548" />

- 댓글 삭제
<img width="1579" height="1060" alt="스크린샷 2025-12-06 오후 4 32 32" src="https://github.com/user-attachments/assets/154da98e-27a9-4034-875f-5bf8eca1ed85" />

- 마이페이지
<img width="1579" height="1060" alt="스크린샷 2025-12-06 오후 5 08 03" src="https://github.com/user-attachments/assets/2875907f-8269-4a46-8ef7-0c456a56c0b5" />
<img width="1579" height="1060" alt="스크린샷 2025-12-06 오후 4 33 59" src="https://github.com/user-attachments/assets/a122350a-2441-47ad-a1fc-3573a91095d9" />

- 프로필 이미지 수정
<img width="1579" height="1060" alt="스크린샷 2025-12-06 오후 4 35 33" src="https://github.com/user-attachments/assets/5b02e4be-37bc-4dd2-a383-0e8e781f7385" />
<img width="1579" height="1060" alt="스크린샷 2025-12-06 오후 5 07 32" src="https://github.com/user-attachments/assets/63bef513-4926-48c6-9360-d6db6e630b57" />

  
- 닉네임 수정
<img width="1579" height="1060" alt="스크린샷 2025-12-06 오후 5 07 57" src="https://github.com/user-attachments/assets/c5f35bc9-8ea8-495b-ba86-23e184abfc96" />

- 비밀번호 수정


- 회원 탈퇴
<img width="1579" height="1060" alt="스크린샷 2025-12-06 오후 5 08 10" src="https://github.com/user-attachments/assets/65bb10bd-dc85-4cd3-9796-79b52db6aa2b" />


## 🙌 프론트엔드 후기

Vanilla 기반으로 React 없는 환경에서 SPA 느낌을 구현하는 과정에서
JS 동작 방식과 렌더링 구조를 깊이 이해할 수 있었던 프로젝트였습니다.
