---
title: 네트워킹
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-networking
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 073dea34-7fd8-4c1d-9a31-6bee87924a81
description: Microsoft Office 365에서는 다음과 같은 네트워킹 기능을 지원 합니다.
ms.openlocfilehash: 2245e2e60333d0f1eb85e1243c49c0a04a4f62ec
ms.sourcegitcommit: 830694c729ab53fcc8518b0cdd5322b322514431
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/25/2019
ms.locfileid: "33247264"
---
# <a name="networking"></a>네트워킹

Microsoft Office 365에서는 다음과 같은 네트워킹 기능을 지원 합니다.
  
## <a name="ports-protocols-and-ip-addresses"></a>포트, 프로토콜 및 IP 주소

Office 365는 IPv4 및 IPv6 주소를 사용합니다. Office 365에서 IPv6 주소는 연결 시 선택 사항이며 반드시 사용해야 하는 것은 아닙니다. IPv6을 사용할 경우 Office 365 기능 중 일부를 사용할 수 없습니다. Office 365의 Ipv6 지원에 대한 자세한 내용은 [Office 365 서비스의 IPv6 지원](https://go.microsoft.com/fwlink/?LinkID=785121&amp;clcid=0x409)을 참조하세요.
  
Office 365의 Office 365 도움말에는 허용된 IP 주소 목록이 유지됩니다. 자세한 내용은 [Office 365 URL 및 IP 주소 범위](https://go.microsoft.com/fwlink/p/?LinkID=243567)를 참조하세요. 21Vianet에서 운영하는 Office 365의 경우 [21Vianet에서 운영하는 Office 365용 URL 및 IP 주소](https://go.microsoft.com/fwlink/?LinkID=733351&amp;clcid=0x409)를 참조하세요. Office 365 Germany의 경우 [Office 365 Germany 끝점](https://support.office.com/en-us/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8)을 참조하세요.
  
> [!IMPORTANT]
> 특정 IP 주소 서브넷으로 라우팅하는 대신 위 문서에 나열된 루트 도메인 이름(예: \*.Outlook.com, \*.MicrosoftOnline.com and \*.SharePoint.com)으로 라우팅하는 것이 좋습니다. IP 주소 서브넷에 의존하면 변경 사항이 발생하는 경우 사용자의 서비스가 중단될 위험이 있습니다. 
  
## <a name="bandwidth-requirements"></a>대역폭 요구 사항

대역폭 요구 사항에 대한 자세한 내용은 [인터넷 대역폭 계획](https://go.microsoft.com/fwlink/p/?LinkID=282467)을 참조하세요.
  
## <a name="connecting-to-office-365"></a>Office 365에 연결

Office 365에 대한 모든 연결은 공용 인터넷 또는 개인 Azure Express 경로 연결을 통해 수행되고 SSL로 적절히 보호됩니다. Azure Express 경로를 사용하여 인터넷을 무시하고 전역 Microsoft 네트워크에 직접 연결할 수 있습니다. Microsoft 네트워킹 파트너는 전역 Microsoft 네트워크에 대한 연결을 제공합니다.
  
Azure Express 경로에 대한 자세한 내용은 [Office 365용 Azure Express 경로](https://aka.ms/expressrouteoffice365)를 참조하세요.
  
### <a name="wan-accelerators"></a>WAN 가속기

Microsoft에서는 Office 365를 통한 고객 소유 WAN 바로 연결 및 캐싱 장치를 지원하지 않습니다. 대기 시간이 길거나 대역폭이 낮은 환경에서 WAN 최적화 컨트롤러를 사용하여 성능을 향상시키려면 Microsoft에서 서비스 요청 문제를 해결하는 동안 사용자가 컨트롤러를 사용하지 않도록 설정하고 장치 공급업체에 장치 지원을 요청해야 합니다. 자세한 내용은 [Office 365를 통한 WAN 바로 연결 및 캐싱 장치](https://go.microsoft.com/fwlink/p/?LinkID=282468)를 참조하세요.
  
## <a name="the-global-microsoft-network"></a>세계적인 Microsoft 네트워크

Office 365 네트워킹 인프라는 서비스를 세계적으로 배포하기 위한 데이터 센터, 서버, 콘텐츠 배포 네트워크, 에지 컴퓨팅 노드 및 광섬유 네트워크의 세계적인 대규모 포트폴리오로 구성됩니다. 복잡한 서비스 계측 및 모니터링 기능이 각 구성 요소의 가장 기본적인 수준에 통합되어 데이터 센터, 네트워크 백본, 인터넷 교환 등을 파악할 수 있으므로 중단 발생의 원인을 발견, 진단 및 관리하는 데 도움이 됩니다. 네트워크는 성능 저하 없이 대규모 네트워크 중단에 대해서도 충분한 용량을 유지하도록 빌드됩니다. 자세한 내용은 [Global Foundation Services](https://go.microsoft.com/fwlink/p/?LinkID=282622)를 참조하세요. 
  
고객 데이터의 신뢰성과 무결성을 유지하기 위해 Microsoft에서는 Office 365 네트워크와 별도로 소비자 서비스 네트워크를 유지합니다. (이에 제한되지 않음) 정보 흐름을 제어하기 위해 다음과 같은 다양한 방법이 사용됩니다.
  
- 물리적 분리. 네트워크 세그먼트는 특정 통신 패턴을 차단하도록 구성된 라우터별로 물리적으로 분리됩니다.
    
- 논리적 분리. VLAN(가상 사설망) 기술은 통신을 추가로 분리하는 데 사용됩니다.
    
- 방화벽. 방화벽과 기타 네트워크 보안 강화 지점은 인터넷에 노출된 시스템과의 데이터 교환을 제한하고 Microsoft에서 관리하는 백엔드 시스템에서 시스템을 격리하는 데 사용됩니다. 
    
- 프로토콜 제한.
    
자세한 내용은 [Office 365 보안 센터](https://go.microsoft.com/fwlink/p/?LinkID=282621)를 참조하세요. 
  
## <a name="feature-availability"></a>기능 가용성

Office 365 계획 간의 기능 가용성을 확인하려면 [Office 365 플랫폼 서비스 설명](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx)을 참조하세요.
  

