---
title: 엄준서
permalink: /about/
---


![스크린샷 2022-08-29 22.46.46.png](%E1%84%8B%E1%85%A5%E1%86%B7%E1%84%8C%E1%85%AE%E1%86%AB%E1%84%89%E1%85%A5%20ee66f58c661042a3843438c00bed6652/%25E1%2584%2589%25E1%2585%25B3%25E1%2584%258F%25E1%2585%25B3%25E1%2584%2585%25E1%2585%25B5%25E1%2586%25AB%25E1%2584%2589%25E1%2585%25A3%25E1%2586%25BA_2022-08-29_22.46.46.png)

### **Contracts**

**Email.** djawnstj44@gmail.com

**Phone.** 010-7577-1018

### Link

**Blog.** [https://velog.io/@djawnstj🔗](https://velog.io/@djawnstj)

**Github.** [https://github.com/djawnstj🔗](https://github.com/djawnstj)

---

# Introduce

### 나눔을 중요시하는 개발자입니다.

평소 다른 사람에게 배푸는 것을 중요하게 생각합니다. 대학 시절 학회장 활동을 하며 학우들의 학교생활에 도움을 주었고 개발자로 취업하고 난 후에는 학부생, 취업 준비생, 비전공자를 대상으로 기초적인 프로그래밍 지식과 개발자 마인드, 공부해야 할 로드맵 등을 나누며 도움을 주고 있습니다. 앞으로는 많은 오픈소스 활동으로 개발환경에 기여하는 개발자가 되고 싶습니다.

### 문제점을 파악하고 개선하기위해 노력하는 개발자입니다.

첫 직장을 다니며 10년 동안 이어져 오던 XML 방식의 앱 버전 관리의 비효율을 느끼고 RDB로 관리할 수 있는 시스템을 건의, 개발하였습니다. 이 시스템 개선으로 XML 파일을 응답받아 정보를 읽기 위해 필요한 parser 코드 등 불필요한 작업을 줄이고 JSON 형식으로 응답받아 개발 생산성을 높일 수 있었습니다.

---

# **Work Experience**

## UNS 네트웍스(2021.12. ~)

헬스케어 SI기업. 국내 3대 병원 모바일 개발/운영 전담

### RobotT

2022.08 ~

- Kotlin/Android, express.js, redis(pub/sub), WebRTC
- 병원의 자율주행 로봇에 설치되어 화상회의 형태의 원격 회진을 돕는 애플리케이션
- redis pub/sub을 통해 WebRTC 커넥션을 만들어 화상회의 기능 구현
- 화상채팅 품질 개선
    - 동시에 3개 이상의 단말기 화상채팅시 화면공유가 원활히 연결되지 않는 문제 발생
    - WebRTC 특성상 모든 단말기가 영상정보를 통신하기 때문에 네트워크 지연이 발생된다 판단.
    - 실제 운영시 5대 이상의 단말기가 연결되므로 1:N 방식의 영상 통신이 가능한 SFU서버 도입 필요성 주장.

### e-PIMS

2022.08 ~ 2022.12

- Kotlin/Android, express.js
- 약제부의 Paper-less 처방을 위한 약제부 애플리케이션
- node api를 개발하여 안드로이드 rerofit을 이용해 통신

### DarwinT

2021.12 ~ 2022.07

- Kotlin/Android, express.js
- 의사 업무중 하나인 회진에 필요한 종이를 없애는 Paper-less 회진을 위한 회진 애플리케이션
- node api를 개발하여 안드로이드 rerofit을 이용해 통신
- express-session 모듈 없이 세션 기능 구현
    - 기존 프로젝트들에서 쓰던 자바 레거시 백엔드와 연동 필요
    - 30분단위로 로그아웃 처리를 하기 위한 HashMap, settimeout을 이용한 독립적 세션 모듈 구현

---

# **Other Experience**

### [Spring Boot/AWS 스터디🔗](https://velog.io/@djawnstj/series/AWS-Spring-Boot-%EC%98%81%ED%99%94-%ED%8E%98%EC%9D%B4%EC%A7%80-%EC%A0%9C%EC%9E%91)

2022.09 ~

- Kotlin, Spring boot, JPA, MariaDB, AWS, thymeleaf
- 13년차, 5년차 시니어 개발자와 영화 정보 페이지 개발 스터디 진행

### **[트래블릿🔗](https://github.com/team-travelit)**

2022.09 ~

- React Native, Spring boot, JPA, mariaDB
- 사용자의 여행 경험을 바탕으로 여행 계획을 짜고 다시 환원하는 커뮤니티 (기획 1명, FE 3명, BE 3명)
- MVP 모델을 준비중이며 12월 런칭 계획
- 참여 후, Node+FireBase를 사용하던 기존 시스템을 Spring boot + MariaDB로 변경

### [Scroll Pager🔗](https://github.com/djawnstj/ScrollPager)

- Android/Kotlin 라이브러리
- ScrollView를 이용한 세로 페이징 기능 적용

### 재능기부(무료 과외)

2022.01 ~ 

- Kotlin, Java, Java Script, Android, React, Spring boot
- 총 네명의 학부생, 취업 준비생, 비전공자와 함께 프로그래밍 기초를 도와주며 함께 배우는 재능기부 과외 진행

### [LX 공간정보아카데미🔗](https://lxsiedu.or.kr/)

2021.06 ~ 2021.11

- Spring+tomcat/Node 백엔드와 JSP/Android 개발 교육 과정
- 한국국토정보공사에서 진행하는 ‘공간정보 응용소프트웨어 전문가 양성과정’ 8기 수료
- 프로젝트 기획부터 발표까지 총 5개의 프로젝트 진행
- 프로젝트 - [lxtagram🔗](https://github.com/djawnstj/lxtagram)
    - tomcat, Spring, JSP, 카카오맵
    - 인스타그램 클론코딩
    - 템플릿을 제외한 설계부터 기능 구현까지 직접 개발
    - 해시태그, 위치기반 게시글 작성, 스크롤 페이징 구현
- 프로젝트 - [든든카🔗](https://youtu.be/aE4IptNcTVM?t=7410)
    - 교통난 극복과 잉여 자가용을 활용한 차세대 카쉐어링 플랫폼
    - tomcat, Spring, Node, Android, JSP

---

# **Skill**

### Back End

- Kotlin, Java
- Spring Boot, MyBatis, JPA

### Front End

- HTML, Java Script
- Vue, React

### Android

- Kotlin, Java
- Retrofit2, Okhttp3, Glide, RoomDB
- MVP, MVVP

### DB

- MySQL, MariaDB, Oracle

---

## License

### 정보처리기사

2022.09
