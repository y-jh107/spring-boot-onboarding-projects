# Spring Boot Onboarding Projects

이 레포지토리는  
**「스프링 부트 개발자 온보딩 가이드」** 책을 기반으로  
실습 프로젝트를 진행하며 그 과정을 관리한 **meta repository**입니다.

각 프로젝트는 개별 GitHub 레포지토리에서 구현되며,  
본 레포지토리는 전체 실습 흐름과 진행 상태를 한눈에 정리하는 허브 역할을 합니다.

---

## 🎯 목표

- 「스프링 부트 개발자 온보딩 가이드」에 소개된 실습 프로젝트를 순차적으로 진행
- 단순 구현이 아닌 **이슈 기반 프로젝트 관리 방식**으로 실습 수행
- 각 프로젝트를 **구현 → 테스트 → 검증 → 정리 → PR** 흐름으로 완주
- 여러 개의 작은 프로젝트를 하나의 학습 스토리로 체계적으로 관리

---

## 📦 프로젝트 목록

### 1. 인메모리 기반 To-Do 리스트 REST API 서버
- **Status:** ✅ Completed
- **설명:**  
  데이터베이스 없이 메모리를 사용해 To-Do 리스트를 관리하는 REST API 서버
- **주요 학습 포인트:**
  - 계층별 역할 분리 (Domain / Repository / Service / Controller)
  - GitHub 이슈 및 서브 이슈 기반 작업 관리
  - Controller / Service 유닛 테스트 작성
  - Swagger(OpenAPI)를 통한 API 문서화
- **Repository**: https://github.com/y-jh107/todo-in-memory

---

### 2. JPA 기반의 To-Do 리스트 API 서버
- **Status:** ✅ Completed
- **설명:**  
  JPA를 활용해 영속성을 가지는 To-Do 리스트 REST API 서버 개발
- **주요 학습 포인트:**
  - JPA 이해
  - 도커를 이용한 MySQL
  - DTO 패턴 이애하기
- **Repository**: https://github.com/y-jh107/todo-mysql

---

### 3. 고급 JPA 기반의 마이크로블로그 REST API 서버
- **Status:** ✅ Completed
- **설명:**  
  고급 JPA 기능을 활용해 마이크로블로그 REST API 서버를 개발
- **주요 학습 포인트:**
  - 스프링 전역 에러 처리기
  - 성능을 고려한 JPA 설계
  - 복잡한 도메인 모델링
- **Repository**: https://github.com/y-jh107/minilog-jpa

---

### 4. Minilog 인증 기능 추가 (JWT)
- **Status:** 🚧 In Progress
- **설명:**  
  기존 Minilog API에 JWT 기반 인증 기능을 추가
- **주요 학습 포인트:**
  - JWT 인증 이해
  - 인증/인가 처리 구조
  - 보안 설정
- **Repository:** (예정)

---

### 5. GraphQL 기반 마이크로블로그 API 서버
- **Status:** 📝 Planned
- **설명:**  
  REST가 아닌 GraphQL 기반 API 서버 구현
- **주요 학습 포인트:**
  - GraphQL 이해
  - Query / Mutation 구성
  - REST API와 GraphQL의 차이 비교
- **Repository:** (예정)

---

### 6. Docker를 이용한 애플리케이션 패키징 및 배포
- **Status:** 📝 Planned
- **설명:**  
  Spring Boot 애플리케이션을 Docker로 패키징하고 실행
- **주요 학습 포인트:**
  - Dockerfile 기본 개념
  - 이미지 빌드 및 컨테이너 실행
  - 로컬 환경에서의 배포 흐름 이해
- **Repository:** (예정)

---

## 🗂 프로젝트 관리 방식

- 프로젝트별로 **부모 이슈 + 서브 이슈 구조**를 사용
- 작업 단위별 이슈 생성 및 완료 시 close
- 구현, 테스트, 검증 단계를 이슈 단위로 분리
- 모든 작업 완료 후 PR 생성 및 병합
- 프로젝트 종료 후 개념 정리 이슈 작성

---

## 📌 참고 도서
- **스프링 부트 개발자 온보딩 가이드**
