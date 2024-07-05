## MSA 스터디 개요

당근 마켓, Amazon, Netflix, 네이버, 여기어때, 야놀자, 컬리 등등 많은 서비스들이 MSA를 도입하고 관리하고 있습니다.

요즘 이름을 들어봤다 하는 서비스들은 거의 MSA를 도입하고, 업계 표준이 된 상황입니다.

하지만, 개인 사이드 프로젝트에서 이를 적용하기에는 너무 오버엔지니어링이기 때문에 좀 어려운 상황입니다.

따라서, 스터디를 통해 대규모 시스템 설계 이론에 대해서 공부해보고 시스템을 직접 구축해보고자 하는 스터디입니다.

최근 백엔드로서 아주 중요한 역량인 대규모 시스템 설계, 고가용성, 대규모 트래픽처리, 동시성 처리 등에 대한 이해를 높이고, 더 나은 백엔드 개발자로서 성장하고자 합니다...!

## 스터디에서 다룰 내용

- 여러 기업들의 MSA 아키텍처에 대해 탐구
- 대규모 트래픽이 들어왔을때 대처에 대한 고민 (비동기처리, API Rate Limiter, 캐싱, Message Queue, 로드밸런싱 등)
- MSA 아키텍처에서 각 서버간 Coupling을 줄이기
- MSA 아키텍처 설계를 위한 요소들 탐구 (서킷브레이커 패턴, 서비스매쉬, 컨테이너 오케스트레제이션, 분산추적, API Gateway 등)
- MSA 아키텍처에서 많이 쓰이는 기술들 탐구 (Kafka, Istio, Kubernetus, Docker, Promethus, Grafana, Jaeger, ELK Stack, argoCD, Harbor 등..)
- 클라우드 설계 (ELB, VPC, EKS, ECR 등)
- MSA 환경에서의 분산 DB 설계 (티켓서버, 트위터 스노플레이크 접근법, CAP 정리, DB Replication, Master-Slave, 안정적인 해시 설계, Orchestration based SAGA 패턴 같은 분산 트랜잭션, 이기종 DB 트랜잭션, Transaction Outbox pattern 등)

