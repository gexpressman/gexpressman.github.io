---
sort: 1
---

# Glossary

### Global Acceleration Service(글로벌 가속 서비스)
G-Express가 제공하는 글로벌 가속 서비스는 클라우드 사업자의 전용망을 이용하여 전송 구간을 최적화하고, 패킷손실, 지터, 패킷지연, 혼잡 등을 최소화하여 인터넷 어플리케이션 서비스를 가속합니다. 이를 통해 글로벌 어플리케이션 서비스의 사용자 경험을 극대화 합니다

### Accelerator(글로벌 가속기)
고객의 인터넷 어플리케이션의 품질 향상을 위해 특정 지역간의 글로벌 가속서비스를 수행하는 소프트웨어 시스템입니다 . Solbox의 Accelerator는 고객이 웹 포털을 통해 직접 서비스를 개설, 관리할 수 있고, 별도의 물리적 시스템 구성없이 신속하게 확장할 수 있는 탄력성을 제공합니다.<br>
 Global Accelerator는 Listener와 Endpoint로 구성됩니다.  

### Listener
Accelerator를 구성하는 SW 모듈로 Listener는  사용자가 오리진 서버로 요청하는 데이터를 직접 수신하여, Backend Server 가 위치한 region의 Endpoint로 사용자 데이터를 가속 전송하는 역할을 합니다. 고객은 글로벌 어플리케이션 가속이 필요한  사용자가 위치한 region에 Listener를 생성해야 합니다.

### Endpoint
Accelerator를 구성하는 SW 모듈로 Listener로 부터 수신한 사용자의 요청 데이터를 Backend Server로 가속 전송하는 역할을 수행합니다. 고객은 글로벌 어플리케이션 가속이 필요한 Backend Server가 위치한 region에 Endpoint를 생성해야 합니다.

### Backend Server(=Origin Server)
인터넷 어플리케이션 서비스를 사용자에게 제공하는 고객의 서버를 일컫습니다. 

### Client(고객)
G-Express가 제공하는 글로벌 가속 서비스를 사용하는 인터넷 어플리케이션 서비스 사업자를 일컫습니다.

### Region(지역)
글로벌 가속 서비스를 생성할 수 있는 지역을 의미합니다. G-Express가 제공하는 글로벌 가속 서비스는 다양한 클라우드 서비스 플랫폼과 전용망을 이용하여 구성하고 있으며, 글로벌 가속 서비스를 수행하는 Accelerator의 구성요소인 Listener와 Endpoint를 생성할 수 있는 물리적 위치를 의미합니다.

### Listener Region
글로벌 가속 서비스를 수행하는 Accelerator의 구성요소인 Listener를 생성할 수 있는 물리적 위치를 의미합니다.  

### Endpoint Region
글로벌 가속 서비스를 수행하는 Accelerator의 구성요소인 Endpoint를 생성할 수 있는 물리적 위치를 의미합니다.
