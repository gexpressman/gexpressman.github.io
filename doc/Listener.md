---
sort: 3
---

# Listener

## Listener 상세보기

![Listener 상세보기](/images/Listener_Details.png)

**Listener**

| 제공항목  | 설명  |
|---|---|
| Listener Name  | 설정하신 Listener 이름입니다.  |
| Listener SEQ  | Listener를 구분할 수 있는 고유번호입니다.  |
| Listener Region  | Listener가 생성된 물리적 위치 정보입니다.  |
| IP Address  | Listener에 할당된 IP입니다.  |
| Port  | 가속 서비스를 수행할 고객의 인터넷 어플리케이션 서비스가 사용하는 프로토콜 정보입니다.  |
| Protocol  | 가속 서비스를 수행할 고객의 인터넷 어플리케이션 서비스가 사용하는 포트 정보입니다.  |
| Created  | Listener 생성일입니다.  |
| Edited  | Listener 마지막 수정일입니다.   |

**Endpoint List**

| 제공항목  | 설명  |
|---|---|
| Endpoint Name  | 설정하신 Endpoint 이름입니다.  |
| Endpoint SEQ  | Endpoint 를 구분할 수 있는 고유번호입니다.  |
| Endpoint Region  | Endpoint 가 생성된 물리적 위치 정보입니다. |

## Listener 수정

![Listener 수정화면](/images/Listener_Edit.png)

| 설정항목  | 설명  |
|---  |---|
| Listener Name  | Listener의 이름을 수정할 수 있습니다.<br> 대/소문자, 숫자 조합으로 중간에 공백없이 입력하시길 바랍니다. 최소 4자부터 최대 50자까지 입력 가능합니다.    |
| Listener Region  | Listener Region은 수정할 수 없습니다.   |
| Listener Protocol  | 사용자(User)가 요청하는 데이터를 수신할 프로토콜을 수정할 수 있습니다.<br> 현재, UDP와 TCP를 지원합니다.  |
| Listener Ports  | 사용자(User)가 요청하는 데이터를 수신할 서비스 포트를 수정할 수 있습니다.<br> ','를 사용하여 여러개의 서비스 포트를 지정하거나  '-'를 사용하여 범위로 서비스 포트를 지정할 수 있습니다.<br> 유효한 서비스 포트 범위는 1-65535 입니다.  최대 1000개의 포트를 입력할 수 있습니다. 단, TCP의 경우 1001, 1002, 8181 포트는 설정할 수 없습니다.<br> 예) 8080, 80, 90 혹은 9000-10000<br> *주의) 서비스 포트는 중복하여 설정할 수는 없습니다. 예) 90, 80, 90  → 90이 중복 되므로 설정 불가함.* |


