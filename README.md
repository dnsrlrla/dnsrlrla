## Hi there 👋

📝 Language

![Java.](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python.](	https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C#.](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)

🖥 Front-End

![HTML.](https://img.shields.io/badge/HTML-239120?style=for-the-badge&logo=html5&logoColor=white)
![CSS.](	https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white)
![Javascript.](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white)
![Bootstrap.](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)

⚙️ Back-End

![Spring Boot.](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=Spring%20Boot&logoColor=white)
![Elasticsearch.](https://img.shields.io/badge/-ElasticSearch-005571?style=for-the-badge&logo=elasticsearch)

📚 DBMS

![MySQL.](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL.](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

##
[![Solved.ac 프로필](http://mazassumnida.wtf/api/v2/generate_badge?boj=kku123)](https://solved.ac/kku123)
[![GitHub Stats](https://github-stats-extended.vercel.app/api/top-langs?username=dnsrlrla&layout=compact&langs_count=4&theme=graywhite)](https://github-stats-extended.vercel.app/api/top-langs?username=dnsrlrla&layout=compact&langs_count=4&theme=graywhite)
##


# 🎫 클리어티켓 (ClearTicket)

> **공연 예매가 어려운 입문자를 위해 복잡한 탐색을 줄여주는 AI 맞춤형 공연 추천 & 예매 플랫폼**

[![GitHub](https://img.shields.io/badge/GitHub-ClearTicket-181717?style=flat-square&logo=github)](https://github.com/ClearTiket/ClearTiket)

---

## 📌 프로젝트 개요

* **수행 기간**: 2026.06 ~ 2026.07 (2개월)
* **수행 인원**: 3명
* **기획 배경**: 공연 예매가 생소하거나 취향에 맞는 공연을 선택하기 힘들어하는 사용자를 위해 진입장벽을 낮추고 탐색 과정을 단축하는 플랫폼을 기획했습니다.
* **프로젝트 목표**:
  * Spring Boot 기반 풀스택 백엔드 개발 역량 내실화
  * Python을 활용한 공공 데이터 수집 및 전처리 파이프라인 자동화
  * AI 임베딩 모델과 Elasticsearch를 결합한 개인화 추천 엔진 구현

---

## 🛠 Tech Stack

### Backend & Database
![Java 21](https://img.shields.io/badge/Java_21-007396?style=flat-square&logo=java&logoColor=white)
![Spring Boot 4](https://img.shields.io/badge/Spring_Boot_4-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

### Data & AI / Infrastructure
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

## 👤 담당 역할 및 주요 성과

**담당 영역**: 백엔드 전반 설계, 데이터 수집·전처리 파이프라인 구축, 메인페이지, 검색 기능, AI 공연 추천 기능

### 1. 🔄 자동화 데이터 수집 파이프라인 구축
* **공공 데이터 수집**: Python `requests`를 사용해 KOPIS(공연예술통합전산망) API 데이터를 수집
* **전처리 및 DB 적재**: `Pandas`로 서비스 스키마 규격에 맞춰 가공 후 `Psycopg`로 PostgreSQL 연동
* **One-Step 파이프라인**: 수집부터 가공, DB 삽입까지 단 한 번의 실행으로 처리되도록 데이터 파이프라인 연결

### 2. 🔍 Elasticsearch 기반 검색 시스템 개발
* **데이터 인덱싱**: PostgreSQL 데이터를 Elasticsearch에 동기화/인덱싱하여 빠르게 검색 처리
* **다중 조건 검색**: `Bool`, `Must`, `Should` 쿼리를 조합해 정교하고 유연한 태그 필터링 검색 구현

### 3. 🤖 AI 임베딩 모델 활용 추천 엔진 개발
* **태그 벡터화**: `ko-SRoBERTa` 모델로 사전 정의된 태그 텍스트 임베딩 진행
* **유사도 매핑**: 공연 설명 텍스트와 태그 벡터 간 **코사인 유사도(Cosine Similarity)**를 계산하여 정교한 태그 자동 할당
* **개인화 추천**: Elasticsearch의 **가중치 검색(Weight Search)**을 적용하여 사용자의 선호 태그와 일치도가 높은 공연을 상위 노출

<!--
**dnsrlrla/dnsrlrla** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
