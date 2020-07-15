---
title: 네트워킹
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-networking
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 073dea34-7fd8-4c1d-9a31-6bee87924a81
description: Microsoft는 다음과 같은 네트워킹 기능을 지원 합니다.
ms.openlocfilehash: 0f0554bdd907a6f0a37299dc3e38e5f778e7187e
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132332"
---
# <a name="networking"></a>네트워킹

Microsoft는 다음과 같은 네트워킹 기능을 지원 합니다.
  
## <a name="ports-protocols-and-ip-addresses"></a>포트, 프로토콜 및 IP 주소

Microsoft는 IPv4 및 IPv6 주소를 사용 합니다. Office 365에서 IPv6 주소는 연결 시 선택 사항이며 반드시 사용해야 하는 것은 아닙니다. 일부 Microsoft 365 기능은 i p v 6을 사용 하 여 완전히 사용 하도록 설정 되지 않습니다. Ipv6 지원에 대 한 자세한 내용은 [Microsoft 서비스의 ipv6 지원](https://docs.microsoft.com/office365/enterprise/ipv6-support)를 참조 하세요.
  
Microsoft는 Microsoft 도움말에서 허용 되는 IP 주소 목록을 유지 관리 합니다. 자세한 내용은 [url 및 IP 주소 범위](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)를 참조 하세요. 21Vianet에서 운영하는 Office 365의 경우 [21Vianet에서 운영하는 Office 365용 URL 및 IP 주소](https://docs.microsoft.com/office365/enterprise/managing-office-365-endpoints)를 참조하세요. Office 365 Germany의 경우 [Office 365 Germany 끝점](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8)을 참조하세요.
  
> [!IMPORTANT]
> We strongly recommend that you enable routing to the root domain names listed in the articles above (such as \*.Outlook.com, \*.MicrosoftOnline.com and \*.SharePoint.com) instead of routing to specific IP address subnets. Relying on IP address subnets runs the risk of outages for your users as changes are made. 
  
## <a name="bandwidth-requirements"></a>대역폭 요구 사항

대역폭 요구 사항에 대한 자세한 내용은 [인터넷 대역폭 계획](https://docs.microsoft.com/office365/enterprise/network-planning-and-performance)을 참조하세요.
  
## <a name="connecting-to-microsoft"></a>Microsoft에 연결

Microsoft에 대 한 모든 연결은 공용 인터넷 또는 개인 Azure Express 사용자 연결을 통해 수행 되며 SSL에 따라 적절 하 게 보호 됩니다. Azure Express를 사용 하면 인터넷을 우회 하 여 전역 Microsoft 네트워크에 직접 연결할 수 있습니다. Microsoft 네트워킹 파트너는 전역 Microsoft 네트워크에 대한 연결을 제공합니다.
  
Azure Express 경로에 대한 자세한 내용은 [Office 365용 Azure Express 경로](https://aka.ms/expressrouteoffice365)를 참조하세요.
  
### <a name="wan-accelerators"></a>WAN 가속기

Microsoft does not provide support for customer-owned WAN acceleration and caching devices with Office 365. If you decide to use a WAN optimization controller to improve performance under conditions of high latency or low bandwidth, you'll need to disable it while troubleshooting service requests with Microsoft, and work with your device vendor for device support. For more information, see [WAN Acceleration and caching devices with Office 365](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365).
  
## <a name="the-global-microsoft-network"></a>세계적인 Microsoft 네트워크

Microsoft 네트워킹 인프라는 데이터 센터, 서버, 콘텐츠 배포 네트워크, edge 컴퓨팅 노드 및 파이버 네트워크의 대규모 전역 포트폴리오로 구성 되어 있으며, 서비스의 전역 배포를 제공 합니다. 복잡한 서비스 계측 및 모니터링 기능이 각 구성 요소의 가장 기본적인 수준에 통합되어 데이터 센터, 네트워크 백본, 인터넷 교환 등을 파악할 수 있으므로 중단 발생의 원인을 발견, 진단 및 관리하는 데 도움이 됩니다. 네트워크는 성능 저하 없이 대규모 네트워크 중단에 대해서도 충분한 용량을 유지하도록 빌드됩니다. 자세한 내용은 [Microsoft 글로벌 네트워크](https://docs.microsoft.com/azure/networking/microsoft-global-network)를 참조 하세요. 
  
Microsoft는 고객 데이터의 기밀성과 무결성을 유지 하기 위해 microsoft 네트워크와는 별도로 소비자 서비스 네트워크를 유지 합니다. (이에 제한되지 않음) 정보 흐름을 제어하기 위해 다음과 같은 다양한 방법이 사용됩니다.
  
- Physical separation. Network segments are physically separated by routers that are configured to prevent specific communication patterns.
    
- Logical separation. Virtual LAN (VLAN) technology is used to further separate communications.
    
- 방화벽. 방화벽 및 기타 네트워크 보안 적용 지점은 인터넷에 노출 되는 시스템과의 데이터 교환을 제한 하 고 Microsoft에서 관리 하는 백 엔드 시스템에서 시스템을 격리 하는 데 사용 됩니다. 
    
- 프로토콜 제한.
    
자세한 내용은 [Office 365 보안 센터](https://www.microsoft.com/trust-center)를 참조하세요. 
  
## <a name="feature-availability"></a>기능 가용성

계획 간의 기능 가용성을 확인 하려면 [Microsoft 365 및 Office 365 platform service description](office-365-platform-service-description.md)을 참조 하세요.
  

