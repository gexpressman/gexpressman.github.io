---
sort: 5
---

# Usage Report

고객이 생성한 글로벌 가속 서비스를 통해 사용한 트래픽량을 기간별로 조회하고, 리포트를 생성할 수 있습니다. 조회 시점으로부터 최대 60일 동안의 사용 트래픽량을 조회할 수 있습니다. 

![Usage Report 화면](/images/UsageReport.png)

Usage Report 설정항목은 다음과 같습니다.

| 설정항목  | 설명  |
|---|---|
| Accelerator  | 고객이 조회하고자하는 Accelerator를 선택합니다.   |
| Search period  | 트래픽 사용량 조회 기간을 설정합니다.<br> 조회 시점으로부터 최대 60일까지 조회가 가능합니다.  |
| ![View Detail Icon](/images/Icon_ViewDetail.png): view detail  | 조회기간 동안 트래픽 사용량을 표 형태의 리포트로 표시 합니다.  |

Usage Report에서 제공하는 그래프 제공항목은 다음과 같습니다.

| 그래프 제공항목  | 설명  |
|---|---|
| Listener Traffic  | Listener를 통해 제공된 Inbound, Outbound 트래픽량을 표시합니다.  |
| Endpoint Traffic  | Endpoint를 통해 제공된 Inbound, Outbound 트래픽량을 표시합니다.  |
| In(bound)  | End user에서 Origin Server 방향으로 전송한 트래픽량을 표시합니다.<br> - 시간단위 조회 시: 5분 평균 트래픽을 표시합니다.<br> - 기간단위 조회 시: 1시간 최고 트래픽(5분 평균에서 최고값)을 표시합니다.  |
| Out(bound)  | Origin Server에서 End user 방향으로 전송한 트래픽량을 표시합니다.<br> - 시간단위 조회 시: 5분 평균 트래픽을 표시합니다.<br> - 기간단위 조회 시: 1시간 최고 트래픽(5분 평균에서 최고값)을 표시합니다.  |

Usage Report 그래프 아래 표에서 제공하는 항목은 다음과 같습니다.

| 표 제공항목  | 설명  |
|---|---|
| Minimal Traffic  | 조회기간 내에서 최소 트래픽량을 표시합니다.<br> - 시간단위 조회 시: 5분 평균 트래픽 기준.<br> - 기간단위 조회 시: 1시간 최고 트래픽(5분 평균에서 최고값) 기준.  |
| Maximum Traffic  | 조회기간 내에서 최대 트래픽량을 표시합니다.<br> - 시간단위 조회 시: 5분 평균 트래픽 기준.<br> - 기간단위 조회 시: 1시간 최고 트래픽(5분 평균에서 최고값) 기준.  |
| Average Traffic  | 조회기간 내에서 평균 트래픽량을 표시합니다.<br> - 시간단위 조회 시: 5분 평균 트래픽 기준.<br> - 기간단위 조회 시: 1시간 최고 트래픽(5분 평균에서 최고값) 기준.  |
