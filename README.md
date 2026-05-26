<div align="center">

# 👋 안녕하세요, 서준범입니다

**"목표를 세우면 끝까지 해내는 백엔드 개발자"**

[![Portfolio](https://img.shields.io/badge/Portfolio-junbeom--coding.org-FFC03C?style=for-the-badge&logo=google-chrome&logoColor=black)](https://junbeom-coding.org)
[![Email](https://img.shields.io/badge/Email-tjwnsqja12@naver.com-03C75A?style=for-the-badge&logo=naver&logoColor=white)](mailto:tjwnsqja12@naver.com)
[![Notion](https://img.shields.io/badge/Notion-개발상세보기-000000?style=for-the-badge&logo=notion&logoColor=white)](https://lilac-hide-2c7.notion.site/Final-Project-3a4b0a555650826686c081487fb228d2)

</div>

---

## 🙋 About Me

- 전공 초기 방황을 계기로 학습 방식을 바꿔 **2학년부터 졸업까지 전공 4점대를 유지**, 최종 **학점 3.75**로 졸업했습니다.
- 여러 기술을 빠르게 훑기보다, **왜 그렇게 동작하는지 이해하고 직접 구현**할 수 있는 수준까지 익히는 것을 중요하게 생각합니다.
- 졸업 후 **정보처리기사**를 취득하고, **7개월간 Java 기반 풀스택 국비교육**을 수료하며 백엔드 전반을 학습했습니다.

---

## 🛠 Tech Stack

### Backend
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/Spring_Framework-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot_3-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![JSP](https://img.shields.io/badge/JSP%2FServlet-007396?style=flat-square&logo=openjdk&logoColor=white)
![MyBatis](https://img.shields.io/badge/MyBatis-000000?style=flat-square&logo=mybatis&logoColor=white)

### Frontend
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)
![Thymeleaf](https://img.shields.io/badge/Thymeleaf-005F0F?style=flat-square&logo=thymeleaf&logoColor=white)

### Database
![Oracle](https://img.shields.io/badge/Oracle_XE-F80000?style=flat-square&logo=oracle&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

### Tools & Infra
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Apache Tomcat](https://img.shields.io/badge/Apache_Tomcat-F8DC75?style=flat-square&logo=apachetomcat&logoColor=black)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)

---

## 📂 Projects

### 그룹웨어 시스템
> **2025.11.19 ~ 2025.12.09 | 팀장 | 팀 4명**

사내 업무 효율화를 위한 그룹웨어 시스템. 팀장으로서 일정 조율과 개발 방향을 주도하며 핵심 기능을 직접 구현했습니다.

`Java` `JSP/Servlet` `Oracle DB` `HTML/CSS/JS` `Model1`

| 담당 기능 | 내용 |
|---|---|
| 로그인 & 세션 | 순수 JSP Model1 방식으로 세션 처리 구현 |
| 전체 레이아웃 | 서비스 전체 UI 설계 및 구현 |
| 내부 메일 | 받은/보낸 메일함 분리, status 컬럼으로 독립 삭제 처리 |
| 자유게시판 | CRUD 구현 |

> 💡 **트러블슈팅:** 받은 메일 삭제 시 상대방 보낸 메일함까지 삭제되는 문제 → `DELETE` 대신 `status` 컬럼 추가 후 `UPDATE`로 변경하여 각 사용자 기준 독립 삭제 구현

[![GitHub](https://img.shields.io/badge/GitHub-SemiProject2-181717?style=flat-square&logo=github)](https://github.com/JunBeomSeo/SemiProject2)

---

### 스터디 매칭 & 학습관리 플랫폼 (Hi, Study)
> **2026.01.19 ~ 2026.02.25 | 팀원 | 팀 6명**

스터디를 개설하고 참여 신청할 수 있는 매칭 플랫폼과, 역할 기반 학습 관리 시스템(LMS)을 함께 구현한 서비스입니다.

`Java` `Spring Framework` `MyBatis` `Oracle DB` `AJAX` `동적 SQL`

| 담당 기능 | 내용 |
|---|---|
| 메인 레이아웃 | 전체 서비스 UI 설계 및 구현 |
| 스터디 조회 & 검색 | MyBatis 동적 SQL + AJAX 실시간 자동완성 + Oracle ROWNUM 페이징 |
| 스터디 개설 | 유효성 검사 포함 개설 기능 구현 |
| 스터디 상세 & 참여 신청 | 상세 페이지 및 참여 신청 플로우 구현 |
| LMS | DB 역할 컬럼 기반 개설자/참여자 권한 분리, 과제 등록·제출 구현 |

> 💡 **트러블슈팅:** 카테고리 선택 후 페이지 이동 시 필터 초기화 문제 → 페이징 쿼리스트링에 `sc_idx` 포함하여 해결

[![GitHub](https://img.shields.io/badge/GitHub-Realhistudy-181717?style=flat-square&logo=github)](https://github.com/ljh1901/Realhistudy)
[![Notion](https://img.shields.io/badge/Notion-개발상세보기-000000?style=flat-square&logo=notion)](https://lilac-hide-2c7.notion.site/Final-Project-3a4b0a555650826686c081487fb228d2)

---

## Education & Certificate

| 구분 | 내용 | 기간 |
|---|---|---|
| 🎓 학력 | 세명대학교 정보통신학부 졸업 (학점 3.75) | 2020.03 ~ 2026.02 |
| 🏫 교육 | 쌍용교육센터 AWS & CI/CD 기반 Java Full-Stack 개발자 양성 | 2025.07 ~ 2026.02 |
| 📄 자격증 | 정보처리기사 | 2025.09 |
| 📄 자격증 | COS Pro Python 2급 | 2024.12 |
| 📄 자격증 | MOS Expert | 2025.06 |
| 📄 자격증 | 운전면허 2종보통 | 2020.03 |

---

