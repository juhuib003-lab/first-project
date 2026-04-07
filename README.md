# 💻 Soramarket (소라마켓)

> 피부 진정과 휴식에 집중한 청정 뷰티 플랫폼

---

## 📖 프로젝트 소개

미세먼지와 잦은 마스크 착용으로 인해 피부가 민감해진 현대인을 위해,  
자극적인 제품 중심의 기존 뷰티 시장에서 벗어나  
피부 본연의 건강과 휴식에 집중한 제품만을 선별하여 제공하는  
**청정 뷰티 플랫폼 '소라마켓'**을 기획하고 개발한 팀 프로젝트입니다.

---

## 👥 프로젝트 유형

- 팀 프로젝트 (협업 개발)

---

## 👥 팀 구성 및 역할

- 👑 **김강산 (팀장)**
  - 상품 리스트 및 상세 페이지 개발
  - React Router 기반 SPA 구현
  - 장바구니 및 재고 관리 기능

- 🙋‍♀️ **박주희 (본인)**
  - 상품 및 리뷰 DB 테이블 설계
  - 관리자 페이지 (상품 등록 / 수정 / 삭제) 구현
  - 상품 검색 기능 및 데이터 연동 처리

- 🙋 **박도예**
  - 장바구니 및 주문 / 결제 기능 구현
  - 카카오 주소 API 및 결제 API 연동

- 🙋 **이연우**
  - 회원 및 주문 DB 설계
  - 로그인 / 회원 관리 기능 구현
  - 관리자 및 사용자 권한 관리 기능

---

## 🛠️ 사용 기술

### 💻 Language & Frontend
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### ⚙️ Backend
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![MyBatis](https://img.shields.io/badge/MyBatis-000000?style=for-the-badge)

### 🗄️ Database
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)

### 🛠️ Tools
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![SQL Developer](https://img.shields.io/badge/SQL_Developer-4479A1?style=for-the-badge)

---

## 🎯 주요 기능

- 🔍 상품 검색 기능 (부분 검색 및 필터링)
- 🛒 관리자 상품 등록 기능 (이미지 업로드 및 유효성 검사)
- 🗑️ 상품 수정 및 삭제 기능 (실시간 UI 반영)
- 🗂️ 상품 및 리뷰 데이터베이스 설계

---

## 🙋‍♀️ 담당 역할

- 상품 및 리뷰 관련 **DB 테이블 설계**
- 관리자 페이지의 **상품 CRUD 기능 구현**
- 사용자 **상품 검색 기능 구현**

---

## 📸 기능 시연

### 🔍 검색 기능

- 상품명을 기준으로 검색어가 포함된 데이터 필터링
- 대소문자 구분 없이 검색 가능
- 일부 키워드만 입력해도 결과가 출력되는 부분 검색 구현

<img width="885" src="https://github.com/user-attachments/assets/a01e8cef-5c0f-4f87-9eaf-9d81dc52196c" />
<img width="440" src="https://github.com/user-attachments/assets/db540f2a-82a0-42d0-ac60-87478ddbc83d" />

---

### 🛒 상품 등록 기능 (관리자)

- 관리자 페이지에서 상품 정보 등록 (상품명, 브랜드, 가격, 설명, 카테고리, 재고)
- 이미지 파일 업로드 기능 구현
- 입력값 유효성 검사로 잘못된 데이터 입력 방지
- 등록 완료 시 메인 페이지로 이동

<img width="432" src="https://github.com/user-attachments/assets/62ec27e8-6f06-4396-b1c5-26220c9b1908" />
<img width="494" src="https://github.com/user-attachments/assets/b0919593-15b3-47e7-9bcb-0f2f6fa98e12" />
<img width="219" src="https://github.com/user-attachments/assets/bdc35fbc-1a7e-4130-bde7-b7149ef93d83" />

---

### 🗑️ 상품 수정 / 삭제 기능 (관리자)

- 관리자 페이지에서 상품 정보 수정 및 삭제 기능 구현
- 삭제 시 확인 알림창을 통해 실수 방지
- 삭제 완료 후 페이지 새로고침 없이 즉시 목록 반영
- 관리자 관점에서 효율적인 상품 관리 가능

<img width="567" src="https://github.com/user-attachments/assets/abfe7bc0-82dd-414f-bbd4-79d1159f747d" />
<img width="416" src="https://github.com/user-attachments/assets/b6f71782-9c6f-497c-a6d6-ae4313db5f5a" />
<img width="158" src="https://github.com/user-attachments/assets/0b80de56-a410-44a9-9bd4-9998f4e248d1" />

---

## 💡 트러블 슈팅 & 개선

- 프로젝트 통합 과정에서 기능 충돌 및 오류 발생  
  → 사전 설계 및 협업 기준 정립의 중요성을 경험

- 각자 구현 방식이 달라 기능 통합이 어려웠던 문제  
  → 코드 규칙 및 구조 통일의 필요성 인식

---

## 🚀 배운 점

- 협업 프로젝트에서 **사전 기획과 커뮤니케이션의 중요성**을 체감
- 데이터베이스 설계 및 백엔드 로직 구현 경험
- 다양한 구현 방식을 공유하며 문제 해결 능력 향상

---

## 🔗 프로젝트 특징

- 퍼블리싱을 넘어 **풀스택 기반 웹 프로젝트 경험**
- 관리자 기능 중심의 실무형 CRUD 구현
- 데이터베이스 설계부터 기능 구현까지 직접 수행
