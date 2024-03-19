# Drawer 

## 소개

북마크를 저장 및 관리할 수 있는 간단한 서비스입니다. 본 프로젝트는 현재 개발 단계이며 지속적으로 개선해 나아갈 예정입니다.

## 동기 

여러 프로젝트를 진행하면서 소프트웨어 프로젝트 라이프사이클의 각 단계를 경험하는 것이 중요하다는 깨달음을 얻게 되어, 설계 단계부터 배포 및 운영까지의 모든 단계를 혼자서 경험하고자 했습니다. 이러한 경험이 부족하다는 인식으로부터 출발하여, 실제로 프로젝트를 기획하고 진행하는 과정에서의 도전과 성장을 경험하기 위해 프로젝트를 진행하였습니다.

## 링크

###

- 배포 주소 : http://drawertools.com

### 프로젝트 저장소

- Drawer-Client : https://github.com/Drawer-Project/drawer-client
- Drawer-Server : https://github.com/Drawer-Project/drawer-server

### 문서 

- Api-Spec : https://docs.google.com/spreadsheets/d/1907sB0XZEPogwbIbYd10ziAG2_7jMj6iBDJkEIAr-TY/edit?usp=sharing

## 주요 기술 스택

- Front-End : React, Typescript, Tanstack-Query, React-Hook-Form, Tailwind, Zod,
- Back-End : Java, SpringBoot, Hibernate, SpringDataJpa, QueryDsl, SpringSecurity, H2

## DB 설계

![image](https://github.com/Drawer-Project/.github/assets/64501757/6374c569-77a4-4026-9221-93743afed4d7)

## 주요 기능

### 유저

- [x] 회원가입
- [x] 회원탈퇴
- [x] 로그인
- [x] 로그아웃
- [x] 회원 정보 수정
  - [ ] 이메일
  - [x] 프로필 사진
  - [ ] 비밀번호

### 북마크

- [x] 북마크 생성
- [x] 북마크 조회
- [x] 북마크 삭제

### 컬렉션

- [x] 컬렉션 생성
- [x] 컬렉션 조회
- [x] 컬렉션 수정
- [x] 컬렉션 삭제
- [x] 북마크를 컬렉션에 추가
- [x] 북마크를 컬렉션에서 제거
