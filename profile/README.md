## MSA 스터디 개요

당근 마켓, Amazon, Netflix, 네이버, 여기어때, 야놀자, 컬리 등등 많은 서비스들이 MSA를 도입하고 관리하고 있습니다.

요즘 이름을 들어봤다 하는 서비스들은 거의 MSA를 도입하고, 업계 표준이 된 상황입니다.

하지만, 개인 사이드 프로젝트에서 이를 적용하기에는 너무 오버엔지니어링이기 때문에 좀 어려운 상황입니다.

따라서, 스터디를 통해 대규모 시스템 설계 이론에 대해서 공부해보고 시스템을 직접 구축해보고자 하는 스터디입니다.

최근 백엔드로서 아주 중요한 역량인 대규모 시스템 설계, 고가용성, 대규모 트래픽처리, 동시성 처리 등에 대한 이해를 높이고, 더 나은 백엔드 개발자로서 성장하고자 합니다...!

<br>

## 스터디에서 다룰 내용

- [스터디 주차별 실습 세부 일정](https://github.com/kookmin-msa-study/.github/wiki/%EC%A3%BC%EC%B0%A8%EB%B3%84-%EC%8A%A4%ED%84%B0%EB%94%94-%EC%A7%84%ED%96%89-%EC%9D%BC%EC%A0%95)은 해당 문서를 참고해주세요!!
- 백엔드에 관련된 기술 탐구
- 여러 기업들의 MSA 아키텍처에 대해 탐구
- 대규모 트래픽이 들어왔을때 대처에 대한 고민 (비동기처리, API Rate Limiter, 캐싱, Message Queue, 로드밸런싱 등)
- MSA 아키텍처에서 각 서버간 Coupling을 줄이기
- MSA 아키텍처 설계를 위한 요소들 탐구 (서킷브레이커 패턴, 서비스매쉬, 컨테이너 오케스트레제이션, 분산추적, API Gateway 등)
- MSA 아키텍처에서 많이 쓰이는 기술들 탐구 (Kafka, Istio, Kubernetus, Docker, Promethus, Grafana, Jaeger, ELK Stack, argoCD, Harbor 등..)
- 클라우드 설계 (ELB, VPC, EKS, ECR 등)
- MSA 환경에서의 분산 DB 설계 (티켓서버, 트위터 스노플레이크 접근법, CAP 정리, DB Replication, Master-Slave, 안정적인 해시 설계, Orchestration based SAGA 패턴 같은 분산 트랜잭션, 이기종 DB 트랜잭션, Transaction Outbox pattern 등)

<br>

## 스터디 진행 과정

스터디는 크게 이론과 실습 2가지로 나누어 진행할 예정입니다. 스터디는 매주 금요일 오후 2시에 Discord로 진행됩니다.

1. 백엔드 개발론에 대한 주제로 각자 돌아가면서 발표를 진행합니다.

   - 각자 자유롭게 발표할 주제를 선정합니다. 이때 주제는 정통 CS이 아닌 되도록 백엔드와 밀접한 관련이 있는 주제를 선정합니다. (ex : 실제 기업에서 쓰는 기술이나 아키텍처에 대한 소개, 백엔드와 관련된 최신 IT 소식 및 기술, Transaction Outbox Pattern이나 안정 해시 설계 등 대규모 시스템 구축에 관련된 이론, Jaeger나 Istio 등 기술 스택에 대한 소개, 뉴스 피드 시스템이나 검색어 자동완성 시스템이나 결제 시스템 등 시스템 구현 방법에 대한 소개 등)
   - 주제 선정이 어려운 스터디원을 위해 참고자료를 첨부할 계획입니다. 이에 대해선 [해당 Repo의 Wiki](https://github.com/kookmin-msa-study/.github/wiki)를 참고해주시길 바랍니다.
   - 발표 자료는 자유로운 형식으로 진행하시면 됩니다. (ex : 블로그 글, ppt, Notion 등)
   - 발표 스타일은 우아한 형제들 유튜브의 "10분 테코톡" 스타일을 지향하고 있습니다.
   - 발표 분량은 10분 ~ 20분 이내로 준비하시길 바랍니다.

2. 각자 다음 스터디 날짜까지 해당 주차별로 정한 시스템을 구축해옵니다.

   - 기본적으로 실습은 "[스프링으로 하는 마이크로 서비스 구축](https://www.yes24.com/Product/Goods/95593443)" 책을 바탕으로 진행합니다.
   - [해당 책의 샘플 레포](https://github.com/PacktPublishing/Hands-On-Microservices-with-Spring-Boot-and-Spring-Cloud)를 참고하여 각자 주차별로 해당 주제의 시스템을 직접 구축해봅니다.
   - 발표가 끝난 후, 각자 1주동안 구축한 시스템에 대해서 이야기를 나눕니다. (어떤 점에서 고난을 겪었는지, 어떤식으로 커스텀을 해봤는지, 어떻게 더 개선할 수 있을지 등)
   - 반드시 해당 책의 챕터대로 진행하지는 않을 계획입니다. Kubernetus 같은 내용은 한주에 하기 어렵기도 하며, 해당 책에서는 argoCD, Kafka, GRPC 등 MSA에서 필수적인 기술 스택에 대해서는 다루고 있지 않아 추가할 수도 있기 때문입니다.
   - DB 분산 설계는 개인적으로 진행하기 어려워서 이론으로만 다룰 계획입니다. 원한다면 DB 분산 설계까지 진행하셔도 무방합니다!
   - 시스템 구축은 기본적으로 On-Promise 환경에서 구축하고자 합니다. 클라우드 환경에서 MSA를 구축하기에는 비용적인 문제가 많기 때문입니다. 원한다면 클라우드 기술까지 접목해서 개발해도 좋습니다!

3. 참고자료 작성

   - 스터디에 도움이 될 만한 자료나, 참고자료는 [해당 레포의 Wiki](https://github.com/kookmin-msa-study/.github/wiki)에 작성해주시길 바랍니다.
    
<br>

## 스터디 진행에 사용할 책

- [스프링으로 하는 마이크로 서비스 구축](https://www.yes24.com/Product/Goods/95593443)
- [가상 면접 사례로 배우는 대규모 시스템 설계 기초](https://www.yes24.com/Product/Goods/102819435)

<br>

## 스터디원 정보

- [조현진](https://github.com/mclub4)(스터디장) : [개인 블로그](https://mclub4.tistory.com/)
- [홍석주](https://github.com/sukjuhong) : [개인 블로그](https://velog.io/@sukjuhong/posts)
- [채원찬](https://github.com/BlueBerrySoda)
- [이은선] (https://github.com/Eun-sun-Lee) : [개인 블로그] (https://esssun.tistory.com/)

<br>

**해당 스터디에 관련해서 관심 있으신분은 (mclub4@kookmin.ac.kr)으로 연락주시길 바랍니다. 국민대 출신 학생으로만 한정해서 받습니다!**
