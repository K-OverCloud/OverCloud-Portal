# K-OverCloud
![Alt Text](https://raw.githubusercontent.com/K-OverCloud/Portal/master/main.jpg)

K-OverCloud는 이종 다수 클라우드 간의 자동화된 SaaS 호환성 기술 개발을 위하여 위의 그림과 같은 SaaS OverCloud의 관련 기술에 대한 연구/개발을 진행합니다.


# SaaS OverCloud

SaaS OverCloud란, 다양한 SaaS 응용들이 이종 하이브리드/멀티사이트 클라우드 인프라/플랫폼 환경에 독립적으로 설치와 운용되도록 보장하는 호환성 지원을 자동화된 실행 환경을 통해 동적으로 제공함으로써 SaaS 응용의 호환성을 제고하기 위해 클라우드 인프라/플랫폼/서비스를 통합적으로 아우르는 소프트웨어 기반 자동화 기술을 의미합니다.


# OverCloud & UnderCloud

SaaS 호환성 해결을 위해 SaaS OverCloud를 OverCloud와 UnderCloud로 구분합니다.
UnderCloud는 SaaS 응용을 위해 융합형(hyper-converged) 박스 중심의 실제 ICT 자원들로 구축/운영되는 하이브리드/멀티사이트 클라우드 인프라/플랫폼을 넘어서서 사용자 별로 자원집합을 제공하도록 구분된 자원집합의 조각들의 묶음을 의미합니다.
SaaS OverCloud는 SaaS 응용 개발자의 요구사항에 따라 SaaS UnderCloud가 제공하는 자원집합의 조각 (실제로는 가상/컨테이너/물리 머신)들을 부분적으로 선택하고 엮어 개발자에게 논리적인 클러스터 형태로 제공되는 오버레이 기반의 클라우드를 의미합니다.
즉, SaaS OverCloud는 하나 또는 복수의 논리적인 클러스터 형태로 추상화되어 개발자가 필요한 SaaS 환경 호환성 제공을 위한 요소기술들을 기본적으로 내포하면서 제공합니다.

따라서, 개발자는 SaaS 운용이 실제 동작하는 하부의 UnderCloud와 호환상에 대해 고민할  필요 없이 추상화된 SaaS OverCloud 만을 고려하여 원하는 SaaS 응용을 개발/운영할 수 있습니다.


# Plan

SaaS 응용 호환성/고도화를 위해 다양한 SaaS의 호환성/고도화 기술을 실증적으로 개발합니다. 이를 위해 여러 SaaS 응용을 개발/서비스할 수 있는 공용개발환경이 필요하고, 이종 하이브리드/멀티사이트 클라우드 환경의 제공도 필요합니다.
따라서 초고속/고성능 확장을 감당할 수 있는 다양한 구성의 클라우드 인프라/플랫폼들이 모두 엮어 있는 형태로 구성해 공용개발환경 인프라를 구축합니다. 세부적으로 하이브리드/멀티사이트 클라우드 인프라에 대응하는 Private 클라우드는 GIST, KISTI에서 운영하는 OpenStack 클라우드와 이노그리드의 Cloudit 클라우드를 활용하고, Public 클라우드로는 일차적으로 아마존 AWS를, 그리고 향후 진행에 따라 마이크로소프트 Azure로 대상을 확장할 계획입니다.


이에 대한 자세한 내용 및 질문이나 피드백은 언제나 환영합니다. 아래의 메일 주소를 통해 소중한 의견 부탁드립니다. 감사합니다.

문의 : overcloud@smartx.kr
