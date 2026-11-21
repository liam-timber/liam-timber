<!-- liamgeni/liamgeni 저장소의 README.md 초안. [ ] 표시된 곳을 채워 넣으세요. -->

# 안녕하세요, [이름]입니다 👋

데이터를 모으고, 쌓고, 의미 있게 꺼내 쓰는 시스템을 만드는 백엔드 개발자입니다.
요즘은 **금융 데이터 수집 파이프라인**과 **퀀트 리서치 플랫폼**을 직접 만들고 있습니다.

- 🔭 진행 중: **finminer** — 국내 주식 데이터 수집·퀀트 리서치 플랫폼
- 🌱 공부 중: 데이터 정합성 설계, 대량 수집 파이프라인, 퀀트 백테스트
- 💬 관심 분야: 금융 데이터, 백엔드 아키텍처, 데이터 엔지니어링
- 📫 연락: [블로그 / 링크드인 / 공개용 이메일]

## 🛠 Tech Stack

**Backend**

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![JPA](https://img.shields.io/badge/JPA_/_Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=gradle&logoColor=white)

**Data**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)

**Tools**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000?style=flat-square&logo=intellijidea&logoColor=white)

## 📈 Featured Project

### finminer — 국내 주식 데이터 수집 · 퀀트 리서치 플랫폼

KOSPI·KOSDAQ 전 종목의 시세·재무·배당·공시를 여러 출처에서 수집해, 종목 정보 서비스와 백테스트에 쓸 수 있는 데이터로 쌓는 플랫폼입니다.

- **다중 출처 수집:** KRX, DART, 증권사 Open API를 출처별 어댑터로 묶고, 호출 제한을 Redis 토큰 버킷으로 분산
- **백테스트 수준의 정확도:** 상장폐지 종목 포함(생존자 편향 방지), 정정공시 버전 보관(point-in-time), 원주가·수정주가 분리
- **실시간 + 배치:** Redis Streams 작업 큐, WebSocket 실시간 시세, 1분봉 기반 다중 주기 차트
- **Stack:** Kotlin · Spring Boot · Python · MySQL · Redis

> 비공개로 진행 중입니다.

<!--
## 📊 GitHub Stats (선택)
외부 서비스(github-readme-stats)라 가끔 이미지가 안 뜰 수 있습니다. 쓰려면 주석을 해제하세요.

![stats](https://github-readme-stats.vercel.app/api?username=liamgeni&show_icons=true&count_private=true)
![top langs](https://github-readme-stats.vercel.app/api/top-langs/?username=liamgeni&layout=compact)
-->
