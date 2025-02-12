# **Cobra09**

## **소개**

**Cobra09**는 유저들이 공동구매를 등록하고 판매를 신청할 수 있는 플랫폼입니다.\
이 플랫폼은 쉽고 간편한 구매/판매 프로세스를 제공하며, 보다 저렴한 가격에 제품을 구매할 수 있도록 지원합니다.

---

## **팀원 소개**

| 이름   | 역할       | GitHub                                            | 이메일                                                    |
| ------ | ---------- | ------------------------------------------------- | --------------------------------------------------------- |
| 최원정 | 팀 리더    | [CWJ1222](https://github.com/CWJ1222)             | [qadzcwsx@gmail.com](mailto:qadzcwsx@gmail.com)           |
| 이수진 | 백엔드     | [Soojin-Lee-01](https://github.com/Soojin-Lee-01) | [sojinlee1004@naver.com](mailto:sojinlee1004@naver.com)   |
| 오성환 | 백엔드     | [gogigogigogi](https://github.com/gogigogigogi)   | [tlsrb101@gmail.com](mailto:tlsrb101@gmail.com)           |
| 최수연 | 프론트엔드 | [suyeon-dev](https://github.com/suyeon-dev)       | [choilynne.dev@gmail.com](mailto:choilynne.dev@gmail.com) |
| 오태원 | 프론트엔드 | [oh2815](https://github.com/oh2815)               | [oh2815@naver.com](mailto:oh2815@naver.com)               |

---

## 🚀 데모 링크👉 [Cobra09 공동구매 마켓](http://175.121.178.197:8081/)

## 🔥 주요 기능 한눈에 보기

| 기능명            | 설명                                             |
| ----------------- | ------------------------------------------------ |
| 회원가입 / 로그인 | 이메일 및 소셜 로그인(카카오) 지원               |
| 공동구매 등록     | 판매자가 공동구매 상품을 등록하고 가격 설정 가능 |
| 공동구매 참여     | 구매자가 공동구매에 참여하고 주문 가능           |
| 찜 기능           | 관심 있는 상품을 저장하여 쉽게 찾아볼 수 있음    |
| 댓글 및 리뷰      | 상품에 대한 리뷰 및 댓글 작성 가능               |
| 마이페이지        | 구매 및 판매 내역 확인, 회원정보 수정 가능       |

## 🛠 사용 기술 스택

### **프론트엔드**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![EJS](https://img.shields.io/badge/EJS-8BC34A?style=for-the-badge&logo=javascript&logoColor=white)

- HTML, CSS, JavaScript 기반의 프론트엔드
- **EJS** 템플릿 엔진을 활용한 서버 사이드 렌더링
- Vanilla JS로 동적인 UI 요소 구현 (찜 기능, 댓글 작성, 상품 슬라이드 등)

---

### **백엔드**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=for-the-badge&logo=sequelize&logoColor=white)
![Multer](https://img.shields.io/badge/Multer-FF6F00?style=for-the-badge&logo=javascript&logoColor=white)
![bcrypt](https://img.shields.io/badge/bcrypt-4A90E2?style=for-the-badge&logo=security&logoColor=white)

- **Node.js & Express.js** 기반 REST API 개발
- **Sequelize ORM**을 활용한 MySQL 연동 및 모델링
- **Multer**를 사용한 이미지 업로드 기능 구현
- **bcrypt**를 활용한 비밀번호 암호화 및 인증
- **express-session**을 이용한 사용자 인증 및 세션 관리
- **dotenv**로 환경 변수 관리

---

### **데이터베이스**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)

- **MySQL (MariaDB)** 사용
- Sequelize ORM을 통한 관계형 데이터 모델링
- **주요 테이블**: Users, Products, Orders, Comments, Wishlists

---

### **배포 및 인프라**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![PM2](https://img.shields.io/badge/PM2-2B037A?style=for-the-badge&logo=pm2&logoColor=white)

- **AWS EC2**에서 서버 호스팅
- **AWS RDS**를 활용한 MySQL 데이터베이스 관리
- **Nginx** 리버스 프록시 설정 및 HTTPS 적용
- **PM2**를 사용한 Node.js 프로세스 매니지먼트

---

### **기타 라이브러리 & 툴**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=javascript&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)

- **Git & GitHub**를 활용한 버전 관리 및 협업
- **Postman**으로 API 테스트 및 문서화
- **Axios**를 사용한 API 요청 및 데이터 처리

---

## 📌 프로젝트 히스토리

### 🏁 Early Stage (~24.12.16)

- 📝 **팀명 및 주제 선정** (아이디어 취합 후 다수결 결정)
- 📄 **기획서 제출**
- ⚙ **팀 규칙 설정** (CamelCase 등 코딩 컨벤션 확립)
- 🛠 **협업 환경 구축** (Notion, GitHub 초대 및 설정)
- 📂 **폴더 구조 설계 및 GitHub 초기 Push**

---

### 🚀 Mid Stage 1 (~24.12.23)

- 🏗 **ERD 설계 및 데이터베이스 구축**
- ✅ **핵심 기능 구현 & 1차 배포**
  - 회원가입 / 탈퇴
  - 로그인 / 정보 수정
  - 판매 등록 / 구매 등록

---

### 🎨 Mid Stage 2 (~24.12.27)

- 🎭 **프론트엔드 UI 개선 및 추가 기능 구현**
  - 판매 페이지, 홈 화면, 마이페이지 UI 수정
  - 댓글 기능 / 찜 기능 등 고급 기능 추가
- 📢 **PT 발표 플랫폼 선정 및 준비**

---

### 🎯 Late Stage (~24.12.30)

- 📝 **PT 자료 제작 및 발표 준비**
- 🔍 **코드 정리 및 리팩토링**
- 📦 **더미 데이터 생성 & 기능 점검**
- 🚀 **최종 배포 (2차 배포) 및 발표 진행**

---

## **기능 소개**

### **1. 회원가입 및 로그인**

- 이메일을 통한 회원가입 및 로그인 지원
- 카카오 계정을 활용한 소셜 로그인 기능 제공

### **2. 공동구매 등록 및 참여**

- 판매자는 공동구매를 등록할 수 있으며, 제품 상세 정보 입력 가능
- 구매자는 공동구매에 참여하여 할인된 가격으로 제품을 구매 가능
- 구매 마감 기한 설정 및 최대 구매 가능 수량 조정 가능

### **3. 상품 검색 및 카테고리 필터**

- 카테고리별 상품 검색 기능 제공 (예: 식품, 전자기기, 의류 등)
- 찜하기(위시리스트) 기능 지원으로 관심 있는 상품 저장 가능

### **4. 주문 및 결제 관리**

- 구매자는 주문 정보를 입력하여 구매 신청 가능
- 판매자는 주문 목록을 확인하고, 처리 상태를 관리 가능

### **5. 마이페이지**

- 유저는 자신의 구매 및 판매 내역을 확인 가능
- 닉네임 및 비밀번호 변경 가능
- 찜한 상품 목록 확인 가능

### **6. 댓글 및 리뷰 시스템**

- 상품 상세 페이지에서 댓글 및 답글 기능 제공
- 최대 4단계까지 대댓글 지원
- 불필요한 댓글은 "삭제 처리된 댓글입니다."로 변경 가능

---

## **기술 스택**

### **프론트엔드**

- HTML, CSS, JavaScript
- EJS 템플릿 엔진

### **백엔드**

- Node.js (Express.js)
- Sequelize ORM (MySQL 연동)
- Multer (파일 업로드 처리)
- express-session (사용자 인증 및 세션 관리)
- dotenv (환경 변수 관리)
- axios (API 요청 및 응답 처리)

### **데이터베이스**

- MySQL (MariaDB)
- Sequelize ORM을 활용한 데이터 모델링

### **배포 환경**

- AWS EC2 (서버 호스팅)
- AWS RDS (MySQL 데이터베이스)

---

## **프로젝트 구조**

```
Cobra-09market/
├── controller/       # 비즈니스 로직 (API)
│   ├── Cauth.js      # 인증 관련 컨트롤러
│   ├── Ccomment.js   # 댓글 관련 컨트롤러
│   ├── Chost.js      # 판매 등록 컨트롤러
│   ├── Cmain.js      # 메인 페이지 관련 컨트롤러
│   ├── Cmember.js    # 회원 관련 컨트롤러
│   ├── Cproduct.js   # 상품 관련 컨트롤러
│   ├── Cpurchase.js  # 구매 관련 컨트롤러
│   └── ...
│
├── models/           # 데이터베이스 모델 (Sequelize 사용)
│   ├── Category.js   # 카테고리 모델
│   ├── Comment.js    # 댓글 모델
│   ├── Order.js      # 주문 모델
│   ├── Product.js    # 상품 모델
│   ├── User.js       # 사용자 모델
│   ├── Wishlists.js  # 찜 목록 모델
│   └── index.js      # Sequelize 초기화 및 모델 관계 설정
│
├── routes/           # API 라우팅 설정
│   ├── auth.js       # 인증 관련 라우터
│   ├── comment.js    # 댓글 관련 라우터
│   ├── host.js       # 판매 등록 라우터
│   ├── index.js      # 메인 페이지 라우터
│   ├── member.js     # 회원 관련 라우터
│   ├── product.js    # 상품 관련 라우터
│   ├── purchase.js   # 구매 관련 라우터
│   └── ...
│
├── views/            # EJS 뷰 파일 (프론트엔드)
│   ├── 404.ejs       # 404 페이지
│   ├── buyForm.ejs   # 구매 신청 페이지
│   ├── commentTest.ejs # 댓글 테스트 페이지
│   ├── hostTest.ejs  # 판매 등록 페이지
│   ├── index.ejs     # 메인 페이지
│   ├── login.ejs     # 로그인 페이지
│   ├── mybuypage.ejs # 나의 구매 내역 페이지
│   ├── mypage.ejs    # 마이페이지
│   ├── mysellpage.ejs # 나의 판매 내역 페이지
│   ├── purchase.ejs  # 구매 페이지
│   ├── signup.ejs    # 회원가입 페이지
│   ├── wishlist.ejs  # 찜 목록 페이지
│   └── ...
│
├── utils/            # 공통 유틸리티 함수
│   ├── common.js     # 공통 함수 (비밀번호 해싱, 댓글 정렬 등)
│   ├── constant.js   # 프로젝트에서 사용되는 상수
│
├── config/           # 환경 설정 파일
│   ├── config.js     # MySQL 연결 설정
│
├── public/           # 정적 파일 (CSS, 이미지, JS)
│   ├── css/          # 스타일시트
│   ├── img/          # 이미지 파일
│   ├── js/           # 프론트엔드 스크립트
│
├── .gitignore        # Git에서 제외할 파일 목록
├── package.json      # 프로젝트 종속성 및 스크립트
├── app.js            # 메인 서버 실행 파일
├── README.md         # 프로젝트 설명 파일
└── sql.sql           # MySQL 초기 데이터 스크립트
```

---

## **설치 및 실행 방법**

1. **레포지토리 클론**

   ```sh
   git clone https://github.com/CWJ1222/Cobra-09market.git
   ```

2. **환경 변수 설정**

   - 프로젝트 루트에 `.env` 파일을 생성 후, 필요한 환경 변수 추가

3. **패키지 설치**

   ```sh
   npm install
   ```

4. **서버 실행**

   ```sh
   npm run dev
   ```

---
