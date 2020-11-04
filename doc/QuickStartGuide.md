---
sort: 1
---

# Quick Start Guide

![Quick Start Guide](/images/QuickStart_guide.png)

고객이 목적 서비스 지역에서 인터넷 어플리케이션 서비스의 품질을 개선하기 위한 글로벌 가속 서비스 개설 절차는 다음과 같습니다.


> 1. Accelerator 생성을 위해 이름을 정의하고 서비스 제공 최대 데이터량을 정의합니다.
> 2. End user가 접속하는 목적 서비스 지역에 Accelerator의 Listener를 설정합니다. 
> 3. 인터넷 어플리케이션 서비스를 제공하는 Backend Server가 있는 지역에 Endpoint를 설정합니다.
> 4. 인터넷 어플리케이션 서비스를 제공하는 Backend Server(오리진서버) 정보를 설정합니다.    

상기 글로벌 가속 서비스를 제공하는 Accelerator를 생성하기 위한 서비스 개설 Wizard를 제공하며 설정 방법은 아래와 같습니다.

---
## Accelerator 설정 Wizard 시작

* Global Accelerator 메뉴에서 'Create Accelerator'를 클릭하여 Accelerator 생성 Wizard를 실행 시킵니다.

![Accelerator 설정시작](/images/QuickStart_Wizard_exec.png)

## Accelerator 설정.

* Accelerator 생성을 위해 이름을 정의하고 서비스 제공 최대 데이터량을 정의합니다.

> a. Accelerator의 이름을 설정합니다.<br>
> b. 글로벌 가속 서비스를 이용하여 서비스할 한달간 최대 데이터 사용량을 설정합니다. 고객은 설정한 데이터 사용량을 초과하여 사용할 수 없으며, 사용량 변경이 필요할 경우 데이터 사용량을 수정할 수 있습니다.<br>
> c. 'Next' 버튼을 클릭합니다.<br>


![Accelerator 설정화면](/images/QuickStart_Wizard_Accelerator.png)
  
## Listener 설정.

* End user가 접속하는 목적 서비스 지역에 Accelerator의 Listener를 설정합니다. ( Listener 설정 참조. )

> a. Listener의 이름을 설정합니다.<br>
> b. Listener를 생성할 물리적 위치인 Listener region을 선택합니다.<br>
> c. 가속 서비스를 수행할 고객의 인터넷 어플리케이션 서비스가 사용하는 프로토콜을 설정합니다. 현재, 글로벌 가속 서비스는 TCP와 UDP 프로토콜을 지원합니다.<br>
> d. 고객의 인터넷 어플리케이션 서비스를 위해 사용하는 서비스 포트를 설정합니다. 예) HTTP 웹서비스 포트: 80<br>
> e. 'Next' 버튼을 클릭합니다.<br> 

![Listener 설정화면](/images/QuickStart_Wizard_Listener.png)

## Endpoint 및 Backend Server 설정.

* 인터넷 어플리케이션 서비스를 제공하는 Backend Server가 있는 지역에 Endpoint와 Backend Server(오리진서버) 정보를 설정합니다. ( Endpoint 설정 및 Backend Server 설정 참조.  )

> a. Endpoint의 이름을 설정합니다.<br>
> b. Endpoint를 생성할 물리적 위치인 Endpoint region을 선택합니다.<br>
>
> c. 고객의 인터넷 어플리케이션 서비스를 제공하고 있는 Backend Server(Origin Server)의 IP정보를 입력합니다.<br>
> d. 고객의 인터넷 어플리케이션 서비스를 제공하고 있는 Backend Server(Origin Server)의 서비스 포트 정보를 입력합니다. 예) HTTP 웹서비스 포트: 80<br>
> e. 'Creater Accelerator' 버튼을 클릭하여 Accelerator 생성을 완료합니다.<br>

![Endpoint 및 Backend Server 설정화면](/images/QuickStart_Wizard_Endpoint.png)

## 고객의 Accelerator IP 등록

* End user가 인터넷 어플리케이션 서비스 접속 시 Accelerator의 Static IP address로 접속할 수 있도록 고객의 DNS 등을 설정 합니다. 고객의 인터넷 어플리케이션 서비스 제공 방법에 따라 사용자의 요청을 Accelerator로 보낼 수 있도록 설정이 필요합니다.

![Accelerator IP 확인 화면](/images/QuickStart_Wizard_Last.png)


