# 안녕하세요. 백엔드 개발자 유성호입니다.

> "로그와 SQL 실행계획을 근거로 병목의 원인을 추적하고 시스템을 개선합니다."

Contact: [shyu6370@gmail.com](mailto:shyu6370@gmail.com)

---

## About Me
- **"왜?"라는 질문을 던지며 근본적인 원인을 찾습니다.** 단순히 기능 구현에 그치지 않고, 쿼리 실행 계획과 로그를 집요하게 분석하여 시스템의 진짜 병목 지점을 찾아내고 개선하는 과정을 즐깁니다.
- **데이터베이스 엔지니어링과 분산 시스템에 관심이 많습니다.** 대용량 트래픽 환경에서의 인덱스 튜닝, 캐시 최적화, 그리고 데이터 정합성을 보장하는 아키텍처 설계에 깊게 파고듭니다.
- **주도적으로 인프라 환경을 개척합니다.** 클라우드 환경 운영에 머물지 않고, 비용 절감과 효율성을 위해 직접 로컬 VM 기반 K8s 클러스터를 구축하고 CI/CD를 고도화하는 등 백엔드와 인프라의 경계를 넓혀가며 성장 중입니다.

---

## Tech Stack

### Backend
<img src="https://img.shields.io/badge/Java%2017-007396?style=for-the-badge&logo=java&logoColor=white"> <img src="https://img.shields.io/badge/Spring%20Boot%203-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"> <img src="https://img.shields.io/badge/Spring%20Data%20JPA-6DB33F?style=for-the-badge&logo=spring&logoColor=white"> <img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white"> <img src="https://img.shields.io/badge/Spring%20Cloud-6DB33F?style=for-the-badge&logo=spring&logoColor=white"> <img src="https://img.shields.io/badge/QueryDSL-007396?style=for-the-badge&logo=java&logoColor=white"> 

### Database & Search
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"> <img src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white"> <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"> <img src="https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white"> <img src="https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white"> <img src="https://img.shields.io/badge/Debezium-000000?style=for-the-badge&logo=apachekafka&logoColor=white">

### Infra, Monitoring & DevOps
<img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"> <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"> <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"> <img src="https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white"> <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"> <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white"> <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white">

### Tools & Testing
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"> <img src="https://img.shields.io/badge/IntelliJ%20IDEA-000000?style=for-the-badge&logo=intellijidea&logoColor=white"> <img src="https://img.shields.io/badge/JUnit%205-25A162?style=for-the-badge&logo=junit5&logoColor=white"> <img src="https://img.shields.io/badge/Mockito-000000?style=for-the-badge&logo=java&logoColor=white"> 

---

## Core Competencies
- **Performance Optimization**: 500만 건 데이터 환경에서 복합 인덱스 재설계로 조회 속도를 14초에서 60ms로 단축하고, Redis 캐싱을 적용해 최종 20ms까지 성능을 극대화한 경험이 있습니다.
- **Infrastructure & CI/CD**: AWS EC2 분산 환경을 로컬 VM 3-Node Kubernetes 클러스터로 직접 마이그레이션하여 비용을 절감하고 서비스를 운영한 경험이 있습니다.
- **System Resilience**: Circuit Breaker 및 Event-Driven 아키텍처를 적용해 단일 실패 지점(SPOF) 리스크를 줄이고 외부 장애 전파를 차단합니다.

---

## Key Projects

### PawBridge (유기동물 보호 및 입양 플랫폼)
*8개의 마이크로서비스로 구성된 K8s 환경 기반의 통합 플랫폼*
- **MSA & Infra**: 로컬 VM 3-Node K8s 클러스터 구축, Helm 기반 선언적 배포 및 Cloudflare Tunnel 적용
- **Data Sync**: Transactional Outbox 패턴과 Debezium CDC를 도입해 이중 쓰기 방지 및 비동기 데이터 동기화 파이프라인 구축
- **Concurrency**: 주문 폭주 시나리오를 대비해 비관적 락(Pessimistic Lock)을 적용하여 재고 차감 경쟁 상태(Race Condition) 제어

### 샛별 (개발자 커리어 플랫폼)
*고가용성 확보 및 대용량 트래픽 성능 최적화에 집중한 플랫폼*
- **Performance**: 500만 건 데이터 대상 다중 스칼라 서브쿼리 병목을 복합 인덱스로 해결(14초 ➔ 60ms)하고, Redis 적용으로 최종 20ms 달성
- **Resilience**: Resilience4j Circuit Breaker를 도입해 외부 API 지연 시 연쇄 실패(Cascading Failure)를 차단하는 Dual LLM Fallback 아키텍처 구현
- **Architecture**: 트랜잭션과 부가 기능(검열/알림)의 강결합을 Spring Event로 분리하고, `@TransactionalEventListener`로 데이터 가시성 확보

### OTT-Moa (OTT 구독 공유 플랫폼)
*실시간 통신 및 안전한 파티 매칭을 위한 중개 서비스*
- **Real-time Chat**: 단일 서버 WebSocket의 한계를 극복하기 위해 Redis Pub/Sub을 도입하여 다중 서버(Scale-out) 환경의 채팅 아키텍처 구축
- **Query Tuning**: 채팅방 목록 조회 시 발생하는 N+1 문제를 Fetch Join으로 해결하여 쿼리 발생 횟수 93% 감소 (28회 ➔ 2회)

---

## GitHub Stats
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Dorosiya&show_icons=true&theme=transparent&hide_border=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Dorosiya&layout=compact&theme=transparent&hide_border=true)
