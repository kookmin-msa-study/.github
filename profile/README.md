## MSA 스터디 개요

해당 스터디는 대규모 시스템 설계, 고가용성, 대규모 트래픽 처리, 동시성 처리 등 백엔드에서 중요한 역량을 탐구하는 데 있습니다. 

백엔드 개발은 개인적으로 해결하기 어려운 부분이 많기 때문에, 스터디에서는 여러 기업들의 아키텍처를 분석하고, 비동기 처리, API Rate Limiter, 캐싱, Message Queue, 로드밸런싱 등 백엔드에 관련된 이론을 심도있게 학습하는 스터디입니다. 

<br>

## 스터디에서 다룰 내용

- [스터디 주차별 실습 세부 일정](https://github.com/kookmin-msa-study/.github/wiki/%EC%A3%BC%EC%B0%A8%EB%B3%84-%EC%8A%A4%ED%84%B0%EB%94%94-%EC%A7%84%ED%96%89-%EC%9D%BC%EC%A0%95)은 해당 문서를 참고해주세요!!
- 백엔드에 관련된 기술 탐구
- 여러 기업들의 MSA 아키텍처에 대해 탐구
- 대규모 트래픽이 들어왔을때 대처에 대한 고민 (비동기처리, API Rate Limiter, 캐싱, Message Queue, 로드밸런싱 등)
- 아키텍처 설계를 위한 요소들 탐구 (서킷브레이커 패턴, 서비스매쉬, 컨테이너 오케스트레제이션, 분산추적, API Gateway 등)
- 여러 기술 스택들 탐구 (Kafka, Istio, Kubernetus, Docker, Promethus, Grafana, Jaeger, ELK Stack, argoCD, Harbor 등..)
- 클라우드 설계 (ELB, VPC, EKS, ECR 등)
- 분산 DB 설계 (티켓서버, 트위터 스노플레이크 접근법, CAP 정리, DB Replication, Master-Slave, 안정적인 해시 설계, Orchestration based SAGA 패턴 같은 분산 트랜잭션, 이기종 DB 트랜잭션, Transaction Outbox pattern 등)

<br>

## 스터디에서 진행할 활동

스터디는 매주 금요일 오후 2시에 Discord로 진행됩니다. (시간 조정 가능)

1. 백엔드 개발론에 대한 주제로 각자 돌아가면서 발표를 진행합니다.

   - 각자 자유롭게 발표할 주제를 선정합니다. 이때 주제는 정통 CS이 아닌 되도록 백엔드와 밀접한 관련이 있는 주제를 선정합니다. (ex : 실제 기업에서 쓰는 기술이나 아키텍처에 대한 소개, 백엔드와 관련된 최신 IT 소식 및 기술, Transaction Outbox Pattern이나 안정 해시 설계 등 대규모 시스템 구축에 관련된 이론, Jaeger나 Istio 등 기술 스택에 대한 소개, 뉴스 피드 시스템이나 검색어 자동완성 시스템이나 결제 시스템 등 시스템 구현 방법에 대한 소개 등)
   - 주제 선정이 어려운 스터디원을 위해 참고자료를 첨부할 계획입니다. 이에 대해선 [해당 Repo의 Wiki](https://github.com/kookmin-msa-study/.github/wiki)를 참고해주시길 바랍니다.
   - 발표 자료는 자유로운 형식으로 진행하시면 됩니다. (ex : 블로그 글, ppt, Notion 등)
   - 발표 스타일은 우아한 형제들 유튜브의 "10분 테코톡" 스타일을 지향하고 있습니다.
   - 발표 분량은 10분 ~ 20분 이내로 준비하시길 바랍니다.

2. 발표가 끝난후, 면접 대비를 위해 백엔드에 관련된 주제의 질문에 답해봅니다.

  - [주차별 백엔드 면접 질문 모음 (질문만 있는 버젼)](https://github.com/kookmin-msa-study/.github/wiki/%EC%A3%BC%EC%B0%A8%EB%B3%84-%EB%A9%B4%EC%A0%91-%EC%97%B0%EC%8A%B5-%EC%A7%88%EB%AC%B8-%EB%AA%A8%EC%9D%8C-(Ver.-Question))를 바탕으로 백엔드 면접에서 물어볼 수 있는 질문들에 대해 다같이 답해보는 시간을 가집니다.
  - [답 있는 버젼](https://github.com/kookmin-msa-study/.github/wiki/%EC%A3%BC%EC%B0%A8%EB%B3%84-%EB%A9%B4%EC%A0%91-%EC%97%B0%EC%8A%B5-%EC%A7%88%EB%AC%B8-%EB%AA%A8%EC%9D%8C-(Ver.-Answer))에서 해당 면접 질문에 대한 답까지 볼 수 있습니다. 해당 답은 스터디장이 키워드를 넣어서 예쁘게 답변을 받아낸 것입니다.
  - 면접 질문 난이도는 어려운 질문을 대비하여 난이도가 높게 선정되어 있습니다.

3. 참고자료 작성

   - 스터디에 도움이 될 만한 자료나, 참고자료는 [해당 레포의 Wiki](https://github.com/kookmin-msa-study/.github/wiki)에 작성해주시길 바랍니다.
    
<br>

## 스터디 진행에 사용할 책

- [가상 면접 사례로 배우는 대규모 시스템 설계 기초](https://www.yes24.com/Product/Goods/102819435)

<br>

## 스터디원 정보

- [조현진](https://github.com/mclub4)(스터디장) : [개인 블로그](https://mclub4.tistory.com/)
- [채원찬](https://github.com/BlueBerrySoda)
- [정수환](https://github.com/su-hwani)
<br>

**해당 스터디에 관련해서 관심 있으신분은 (mclub4@kookmin.ac.kr)으로 연락주시길 바랍니다. 국민대 출신 학생으로만 한정해서 받습니다!**
