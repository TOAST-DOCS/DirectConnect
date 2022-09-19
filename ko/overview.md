# Network > Direct Connect > 개요

Direct Connect 서비스는 NHN Cloud의 IaaS 자원과 외부 네트워크(ex. 고객사 On-premise) 구간을 통신사에서 제공하는 전용 회선으로 연결하기 위한 접점입니다. 전용 회선을 이용하면 보다 안정적인 속도를 유지하고 외부 보안에도 안전한 통신을 이용할 수 있습니다.

## 주요 기능
Direct Connect는 다음과 같은 다양한 기능을 제공합니다.
> [참고사항] 현재 한국리전(판교,평촌)에서만 제공되며, 점차 다른 리전도 지원할 예정입니다.
* 다양한 속도 : 최소 10Mbps부터 최대 10Gbps까지 대역폭을 제공합니다.
* 이중화 지원 : 전용회선 연결 접점의 이중화를 지원합니다.
* 우수한 보안성 : NHN Cloud가 취득한 여러 보안 인증과 기술을 통해 전용 회선 연결시 동일 데이터 센터 수준의 보안성을 제공합니다.
* 중립적 데이터센터 : 고객이 선호하는 통신사 전용회선 인입이 가능합니다.
* 다양한 통신 설정 : L2,L3 기반 Vlan, BGP 등 다양한 통신 프로토콜을 지원합니다.

## 구성 환경 
Direct Connect가 지원하는 클라우드 구성 환경은 다음과 같습니다.
| 항목지원 | 사양 |
| --- | --- |
| 리전 | 한국리전(판교, 평촌) |
| 대역폭 | 10Mbps ~ 10Mbps |
| 회선 타입 | Ethernet 방식 |
| 통신 방식 | L2(Vlan), L3(BGP, Static, IPsec) |
| 연결 방식 | 전용 연결* : 전용회선 사업자 |
| - | 호스팅 연결 ** : 제공 파트너(LGU, KINX) |

> [참고]*전용 연결은 NHN Cloud 위치 내 Direct connect 네트워크 포트 및 사용자의 네트워크 포트 간 물리적 연결입니다. 고객이 선호하는 통신사업자의 회선을 직접 연동하실 수 있습니다.

> [참고]**호스팅 연결은 Direct Connect 제공 파트너의 네트워크 환경을 통해 프로비저닝하는 논리적(VLAN) 연결입니다. 호스팅 연결을 사용하는 경우 파트너 포트 중 하나를 사용하여 NHN Cloud 네트워크에 연결합니다.