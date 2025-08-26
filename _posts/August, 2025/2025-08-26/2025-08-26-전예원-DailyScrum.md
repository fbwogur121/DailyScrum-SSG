---
layout: scrum
title: "DailyScrum"
date: 2025-08-26 # YYYY-MM-DD 형식 (파일명과 일치해야 함)
author: "전예원" # 본인 이름으로 변경 (신민혁, 고윤아, 김병곤, 김선민, 최문규)
categories: [scrum]
---

## 📝 오늘 한 일

- 혼자 공부하는 네트워크 1-3 끝내기
- 운영체제 ch1(ppt) 절반

### 혼자 공부하는 네트워크
- packet은 송신할 때 encapsulation, 수신할 때 decapsulation이 이루어짐
- capsulation 과정: application layer -> physical layer으로 상위 계층에서의 packet을 payload 삼아
 해당 계층의 protocol에 맞는 header를 덧붙여 하위 계층으로 전달
- decapsulation 과정: physical layer -> application layer : 메시지를 수신할 때, header를 각 계층에서 확인한 뒤 
 제거하고 상위 계층으로 전달
- PDU(Protocol Data Unit): 상위 계층에서 전달받은 payload + 현재 계층의 protocol header
- data, segment/datagram, packet(IP datagram), frame, bit (상위 -> 하위 계층)
- 네트워크 참조 모델은 가이드라인, 프로토콜 혹은 네트워크 장비가 네트워크를 작동시키는 주체
- 트래픽(traffic): 네트워크 내 정보량 -> throughput, bandwidth, packet loss
- 처리율(throughput): 단위 시간당 네트워크를 통해 실제 전송되는 정보량 bps, Mbps, Gbps, pps
- 대역폭(bandwidth): 단위 시간당 송수신 할 수 있는 최대 정보량(네트워크 성능 영역)

## 🎯 내일 할 일

- 운영체제 ch1 남은 부분 (아마 내일 약속 때문에...)

## 💭 한줄평
네트워크 부분은 작년에 배운 내용을 복습하고 있는데 확실히 정리가 잘 되는걸 보면 복습 효과가 
대단한 것 같다... 백준 풀어야하는데 문제 읽고 생각하기가 너무 오래걸려서 주말마다 한문제씩
푸는걸 도전해봐야집

## 🔗 공유하고 싶은 것
- 공부하고 있는 운영체제 자료를 조만간 공유해보겟슴니다...
- 11시까지 하는 카페는 24시간 카페가 아닐까요....? 제가 사는 왕십리에는 탐앤탐스가 24시간임니다


