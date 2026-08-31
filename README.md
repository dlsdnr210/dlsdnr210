# 👋 안녕하세요, 백인욱입니다.

> **에러가 사라져도 원인을 모르면 해결됐다고 생각하지 않는 개발자입니다.**

Java·Spring 기반 웹 개발과 Python 기반 데이터 처리 경험을 바탕으로  
**데이터가 들어오고, 처리되고, 저장되어 서비스 기능으로 연결되는 흐름**을 이해하는 개발자를 목표로 하고 있습니다.

단순히 "동작하는 코드"에서 끝내기보다  
문제가 발생한 위치를 나누고, 원인을 추적하고, 다음 사람이 이해할 수 있도록 기록하는 과정을 중요하게 생각합니다.

---

## 👨‍💻 About Me

- Java · Spring 기반 백엔드 개발
- Python 기반 웹 크롤링 및 데이터 처리
- MySQL · Oracle 기반 데이터 저장 및 조회
- REST API 및 Controller-Service-Repository 구조 구현
- Git · GitHub 기반 버전 관리 및 협업
- Elasticsearch · Kibana 기반 데이터 검색 및 시각화 경험
- 데이터 수집 → 전처리 → 저장 → 서비스 연결 구조에 관심

---

## 🛠 Tech Stack

### Backend
`Java` `Spring` `Spring Boot` `REST API`

### Data
`Python` `Pandas` `Web Crawling`

### Database
`MySQL` `Oracle` `H2`

### Frontend
`HTML` `CSS` `JavaScript`

### Search & Visualization
`Elasticsearch` `Kibana`

### Collaboration
`Git` `GitHub`

---

## 📌 Projects

### 01. 데이터 수집 파이프라인

웹에서 데이터를 수집하고 필요한 정보를 추출한 뒤  
전처리하여 데이터베이스에 적재하는 흐름을 구현했습니다.

**주요 작업**

- Python 기반 웹 크롤링
- 필요한 데이터 필드 추출
- 결측값 및 데이터 형식 전처리
- MySQL 데이터 적재
- 수집 / 추출 / 전처리 / 저장 기능 분리
- GitHub 기반 버전 관리

```text
Crawling
   ↓
Extract
   ↓
Preprocess
   ↓
Load
   ↓
Database
```

초기에는 여러 기능이 하나의 코드에 섞여 있어  
오류가 발생했을 때 원인을 찾기 어려웠습니다.

이를 기능별로 분리해 **수정 범위를 줄이고 문제 발생 지점을 추적하기 쉬운 구조**로 개선했습니다.

---

### 02. Java · Spring 웹 애플리케이션

Spring MVC 구조를 기반으로  
사용자의 요청이 서버 로직을 거쳐 데이터베이스에 저장되고 다시 응답되는 흐름을 구현했습니다.

**주요 작업**

- Controller / Service / Repository 역할 분리
- REST API 구현
- 데이터 저장 및 조회
- MySQL · H2 연동
- 사용자 입력값 및 비즈니스 조건 검증

화면에서 값이 정상적으로 보이더라도  
서버에서 비즈니스 조건을 검증하지 않으면 데이터 정합성이 깨질 수 있다는 점을 경험했습니다.

이를 통해 **화면 구현과 서버 검증은 별개의 책임**이라는 기준을 갖게 됐습니다.

---

## 🔍 How I Solve Problems

문제가 발생하면 눈에 보이는 코드부터 수정하지 않습니다.

먼저 실행 흐름을 나눕니다.

```text
입력값
   ↓
처리 로직
   ↓
출력값
   ↓
Database
```

크롤링 문제라면 더 세분화합니다.

```text
페이지 이동
   ↓
Element 탐색
   ↓
이벤트 실행
   ↓
데이터 로딩
   ↓
중복 제거
   ↓
종료 조건
```

그리고 다음 기준으로 확인합니다.

1. 문제가 재현되는 조건을 확인합니다.
2. 정상 동작하는 구간과 실패하는 구간을 나눕니다.
3. 한 번에 하나의 원인만 검증합니다.
4. 수정 후 같은 조건으로 다시 실행합니다.
5. 변경 이유를 Git 기록으로 남깁니다.

> **“일단 돌아가니까 됐지”보다 “왜 돌아가는지 설명할 수 있는가”를 더 중요하게 생각합니다.**

---

## 🤝 How I Work

협업에서는 코드를 작성하기 전에  
**서로 같은 작업 상태를 보고 있는지 확인하는 것**이 중요하다고 생각합니다.

GitHub 협업 과정에서 개인 저장소와 기준 저장소의 역할이 섞여  
원격 저장소 설정 문제가 발생한 경험이 있습니다.

이후에는 다음 기준을 적용하고 있습니다.

- 작업 전 원격 저장소 및 브랜치 상태 확인
- 기능 단위 커밋
- 변경 내용을 확인할 수 있는 커밋 메시지 작성
- 기능별 책임을 분리한 코드 구조
- 다른 사람이 이어서 수정할 수 있는 기록 유지

---

## 🌱 Currently Learning

현재 개발 실무 역량을 높이기 위해 다음 영역을 학습하고 있습니다.

- Java / Spring Boot
- REST API
- SQL / Database
- Python Data Processing
- Data Pipeline
- Test Code
- CI / CD
- Git / GitHub
- AI / Machine Learning / Deep Learning

---

## 🎯 Career Goal

### 1~2년
기존 서비스의 코드와 데이터 흐름을 정확히 이해하고  
작은 기능부터 안정적으로 완성할 수 있는 개발자가 되는 것이 목표입니다.

### 3~5년
단순 기능 구현을 넘어 반복되는 오류와 비효율을 발견하고  
테스트, 예외 처리, 데이터 구조 개선을 통해 서비스 품질 향상에 기여하고 싶습니다.

### 5년 이후
특정 기술 하나에만 의존하지 않고  
서비스의 요구사항을 데이터 구조와 로직으로 변환하고  
복잡한 문제를 맡겼을 때 팀이 신뢰할 수 있는 개발자로 성장하고 싶습니다.

---

## 📫 Contact

- GitHub : https://github.com/dlsdnr210)
- Email : dlsdnr1210@gmail.com
