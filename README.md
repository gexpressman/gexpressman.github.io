# G-Express 서비스란?

G-Express 서비스는 고객이 운영하는 인터넷 어플리케이션 서비스의 글로벌 이용자에게 전용망 기반 고품질 가속서비스를 제공하는 글로벌 가속 서비스 입니다. 이를 통해 인터넷 어플리케이션 서비스의 패킷 손실과 서비스 전송 지연을 최소화 하고 사용자 경험을 향상 시킵니다.

[![G-Express Service Concept](https://gexpressman.github.io/images/Intro_gex_concept.png)](https://gexpress.solbox.com)<br>
[G-Express Service Pages](https://gexpress.solbox.com)

## 시스템 구성
고객은 글로벌 가속 서비스를 이용하기 위해서 글로벌 가속기(Accelerator)를 생성해야 합니다. 글로벌 가속기는 리스너와 엔드포인트로 구성되며, 고객의 인터넷 어플리케이션 서비스 이용자가 요청한 데이터는 글로벌 가속기(Accelerator)를 통해 가속 전송됩니다.  

### Listener
Accelerator를 구성하는 SW 모듈로 Listener는  사용자가 오리진 서버로 요청하는 데이터를 직접 수신하여, Backend Server 가 위치한 region의 Endpoint로 사용자 데이터를 가속 전송하는 역할을 합니다. 고객은 글로벌 어플리케이션 가속이 필요한  사용자가 위치한 region에 Listener를 생성해야 합니다. 

### Endpoint
Accelerator를 구성하는 SW 모듈로 Listener로 부터 수신한 사용자의 요청 데이터를 Backend Server로 가속 전송하는 역할을 수행합니다. 고객은 글로벌 어플리케이션 가속이 필요한 Backend Server가 위치한 region에 Endpoint를 생성해야 합니다.

## 활용분야
### 글로벌 게임 가속 서비스
글로벌 게임 서비스 이용자가 원격의 게임서버에 접속할때, 이용자가 접속하는 지역에 따라 서비스 품질의 편차가 발생할 수 있습니다. 이러한, 글로벌 서비스 이용자의 지역별 서비스 품질 차이는 게임 이용자간 불공정한 서비스 환경을 만듭니다. G-Express가 제공하는 글로벌 가속 서비스는 글로벌 서비스 이용자 접속지역과 게임서버 간 전용망을 통한 가속 서비스로 글로벌 게임 이용자간 균등한 서비스를 보장해 줍니다. 

![Global Game service](https://gexpressman.github.io/images/Intro_usage_gameservice.png)

### 스마트 오피스 가속 서비스
글로벌 기업에서 운영하고 있는 온프로미스 오피스를 클라우드 기반의 스마트 오피스로 변경할 경우 글로벌 지역 사무소는 여전히 본사와의 전용망을 통한 스마트 오피스 서비스 접속으로 인한 서비스 품질저하가 빈번하게 일어나고 있습니다. 이 경우 글로벌 지역 사무소와 스마트 오피스 서비스 지역간 글로벌 가속 서비스를 개설하여 글로벌 지역 사무소의 스마트 오피스 서비스 품질을 대폭 개선할 수 있습니다. 

![Smart Office service](https://gexpressman.github.io/images/Intro_usage_smartoffice.png)

