# 서동준 (Seo Dong-jun)

**Backend Developer**

📧 [vj174566@gmail.com](mailto:vj174566@gmail.com) | 📱 010-5009-2170

🔗 [Blog](https://9osari.netlify.app/) | 💻 [GitHub](https://github.com/9osari)

---

## 👋 소개

레거시에서 모던으로, 실무와 학습을 병행하며 성장하는 백엔드 개발자 서동준 입니다.

제약회사 LIMS/QMS 운영하며 슬로우 쿼리 7배 개선, 레거시 리팩토링으로 
유지보수 시간 50% 단축 등 실질적인 성과를 달성했습니다.

퇴근 후 Spring Boot/JPA/AWS로 경매 플랫폼을 개발하며 동시 입찰 처리,
실시간 통신 등을 구현했고, 문제 해결 과정과 학습내용을 [기술 블로그](https://9osari.netlify.app/)에 20개+ 포스트로 공유 중입니다.
---

## 🛠 기술 스택

### Backend
- **Java, Spring Framework, MyBatis, Oracle** ⭐⭐⭐
- **Spring Boot, JPA, MySQL** ⭐⭐⭐
- **REST API** ⭐⭐⭐

### Frontend
- **HTML5, CSS3, JavaScript** ⭐⭐

### Infrastructure & Tools
- **AWS** (S3, CloudFront) ⭐⭐
- **Git, SVN** ⭐⭐⭐

**현재 학습 중**: JWT, Redis

---

## 💼 경력

### **백엔드 개발자** | 인터페이스정보기술

*2024.03 - 현재 | 서울*

> LIMS(실험실 정보 관리 시스템), QMS(품질 관리 시스템) 운영 및 유지보수   
> Java, Spring Framework, MyBatis, Oracle

**삼진제약 QMS 7.1** | 2025.10 - 현재
- [고객사, 관리자도 모르는 L7 스위치 찾기](https://9osari.netlify.app/posts/%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC%EC%9E%A5%EC%95%A0-%EB%8C%80%EC%9D%91%EA%B8%B0/)
- 공급업체 관리 및 승인 워크플로우 구현

**하나제약 LIMS 7.1** | 2024.12 - 2025.10
- [슬로우 쿼리 **7배** 성능 개선](https://9osari.netlify.app/posts/%EA%B3%B5%ED%86%B5%EC%BF%BC%EB%A6%AC-%EA%B0%9C%EC%84%A0/)
- 시스템 버전업에 따른 신규 기능 개발 및 기존 기능 호환성 확보
- CHRONIX 리포트 개발: 30종 이상의 분석 성적서 및 라벨 양식 개발

**현대약품 LIMS 7.0** | 2024.03 - 2025.03
- [레거시 소스에 OOP 리펙토링 적용기](https://9osari.netlify.app/posts/%EB%A0%88%EA%B1%B0%EC%8B%9C%EC%BD%94%EB%93%9C-%EB%A6%AC%ED%8E%99%ED%86%A0%EB%A7%81/): 단일 책임 원칙에 따라 클래스 분리, 유지보수성 확보
- 승인 프로세스 동시성 이슈 해결: synchronized 블록과 트랜잭션 격리 수준 조정으로 중복 승인 방지, 데이터 정합성 100% 확보


---

## 🚀 주요 프로젝트

### DevBid - 중고 물품 경매 플랫폼

*2025.08 - 현재 | [GitHub](https://github.com/9osari/DevBid)*

> Spring Boot / JPA / MySQL / AWS

**주요 성과 및 구현 내용**
- **도메인 설계**: [DDD 기반](https://9osari.netlify.app/posts/%EB%8F%84%EB%A9%94%EC%9D%B8%EC%A3%BC%EB%8F%84%EC%84%A4%EA%B3%84/) Aggregate Root 설계
  - [도메인 간 책임 분리](https://9osari.netlify.app/posts/srp-dip-%EC%9C%84%EB%B0%98%EA%B3%BC%ED%95%B4%EA%B2%B0/),
  - [RESTful한 설계 적용](https://9osari.netlify.app/posts/http-from-%ED%99%98%EA%B2%BD%EC%97%90%EC%84%9C-restful/)
- **동시성 제어**: [낙관적 락과 데드락 원인 분석과 해결](https://9osari.netlify.app/posts/%EB%82%99%EA%B4%80%EC%A0%81-%EB%9D%BD-%EC%A0%81%EC%9A%A9%EA%B3%BC-%EB%8D%B0%EB%93%9C%EB%9D%BD/)
- **성능 최적화**:
    - Querydsl을 활용한 동적 쿼리 작성
    - [N+1 문제 해결](https://9osari.netlify.app/posts/%EC%B9%B4%ED%85%8C%EA%B3%A0%EB%A6%AC-%ED%8A%B8%EB%A6%AC-n+1-%EC%B5%9C%EC%A0%81%ED%99%94/) (fetch join, @EntityGraph 활용)
- **클라우드 인프라**: [S3 Presigned URL](https://9osari.netlify.app/posts/aws-s3-presignedurl/) 방식으로 클라이언트 직접 업로드 구현 **(서버 부하 80% 감소)**   
  CloudFront CDN 적용으로 이미지 로딩 속도 **3배 향상**
- **인증/인가**: Spring Security 기반 사용자 인증 및 세션 관리

---

## 🎓 교육

**이젠컴퓨터아카데미** | 풀스택 개발 전문가 과정   
*2022.12 - 2023.05*

**학점은행제** | 컴퓨터공학과   
*2022.02 - 2022.08*

**일학습병행** | 원제로소프트   
C# / Oracle 기반 사내 시스템 유지보수 참여 (산학연계 실무형 교육)   
2021.03 - 2022.02

**장안대학교** | 소프트웨어융합과   
*2017.03 - 2022.02*

---

## 🏆 자격증 & 수상

**정보처리기사** | 한국산업인력공단   
*2024.12*

**네트워크관리사 2급** | 한국정보통신자격협회   
*2022.04*

**우수논문상** | 한국컴퓨터정보학회   
[TTS를 이용한 E-Book 및 News 웹 개발](https://www.youtube.com/watch?v=MVG5kzbo_q0)   
*2022.01*

---
