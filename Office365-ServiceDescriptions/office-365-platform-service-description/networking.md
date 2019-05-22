---
title: 네트워킹
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-networking
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 073dea34-7fd8-4c1d-9a31-6bee87924a81
description: Microsoft Office 365에서는 다음과 같은 네트워킹 기능을 지원 합니다.
ms.openlocfilehash: 0a7956b5d59082f2f04f71ee2e349c2c3b238c83
ms.sourcegitcommit: 15e92292209454f6778bfef26ecab96bfc71ef5f
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/22/2019
ms.locfileid: "34343627"
---
# <a name="networking"></a><span data-ttu-id="d99cc-103">네트워킹</span><span class="sxs-lookup"><span data-stu-id="d99cc-103">Networking</span></span>

<span data-ttu-id="d99cc-104">Microsoft Office 365에서는 다음과 같은 네트워킹 기능을 지원 합니다.</span><span class="sxs-lookup"><span data-stu-id="d99cc-104">Microsoft Office 365 supports the following networking features.</span></span>
  
## <a name="ports-protocols-and-ip-addresses"></a><span data-ttu-id="d99cc-105">포트, 프로토콜 및 IP 주소</span><span class="sxs-lookup"><span data-stu-id="d99cc-105">Ports, protocols, and IP addresses</span></span>

<span data-ttu-id="d99cc-p101">Office 365는 IPv4 및 IPv6 주소를 사용합니다. Office 365에서 IPv6 주소는 연결 시 선택 사항이며 반드시 사용해야 하는 것은 아닙니다. IPv6을 사용할 경우 Office 365 기능 중 일부를 사용할 수 없습니다. Office 365의 Ipv6 지원에 대한 자세한 내용은 [Office 365 서비스의 IPv6 지원](https://go.microsoft.com/fwlink/?LinkID=785121&amp;clcid=0x409)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="d99cc-p101">Office 365 uses IPv4 and IPv6 addresses. Use of IPv6 addressing is optional and not required for connectivity with Office 365. Not all Office 365 features are fully enabled using IPv6. For more information about Ipv6 support in Office 365, see [IPv6 support in Office 365 services](https://go.microsoft.com/fwlink/?LinkID=785121&amp;clcid=0x409).</span></span>
  
<span data-ttu-id="d99cc-p102">Office 365의 Office 365 도움말에는 허용된 IP 주소 목록이 유지됩니다. 자세한 내용은 [Office 365 URL 및 IP 주소 범위](https://go.microsoft.com/fwlink/p/?LinkID=243567)를 참조하세요. 21Vianet에서 운영하는 Office 365의 경우 [21Vianet에서 운영하는 Office 365용 URL 및 IP 주소](https://go.microsoft.com/fwlink/?LinkID=733351&amp;clcid=0x409)를 참조하세요. Office 365 Germany의 경우 [Office 365 Germany 끝점](https://support.office.com/en-us/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="d99cc-p102">Office 365 maintains a list of allowed IP addresses in the Office 365 help. For more information, see [Office 365 URLs and IP address ranges](https://go.microsoft.com/fwlink/p/?LinkID=243567). For Office 365 operated by 21Vianet, see [URLs and IP Addresses for Office 365 operated by 21Vianet](https://go.microsoft.com/fwlink/?LinkID=733351&amp;clcid=0x409). For Office 365 Germany, see [Office 365 Germany endpoints](https://support.office.com/en-us/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="d99cc-p103">특정 IP 주소 서브넷으로 라우팅하는 대신 위 문서에 나열된 루트 도메인 이름(예: \*.Outlook.com, \*.MicrosoftOnline.com and \*.SharePoint.com)으로 라우팅하는 것이 좋습니다. IP 주소 서브넷에 의존하면 변경 사항이 발생하는 경우 사용자의 서비스가 중단될 위험이 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d99cc-p103">We strongly recommend that you enable routing to the root domain names listed in the articles above (such as \*.Outlook.com, \*.MicrosoftOnline.com and \*.SharePoint.com) instead of routing to specific IP address subnets. Relying on IP address subnets runs the risk of outages for your users as changes are made.</span></span> 
  
## <a name="bandwidth-requirements"></a><span data-ttu-id="d99cc-116">대역폭 요구 사항</span><span class="sxs-lookup"><span data-stu-id="d99cc-116">Bandwidth requirements</span></span>

<span data-ttu-id="d99cc-117">대역폭 요구 사항에 대한 자세한 내용은 [인터넷 대역폭 계획](https://go.microsoft.com/fwlink/p/?LinkID=282467)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="d99cc-117">For information on bandwidth requirements, see [Internet bandwidth planning](https://go.microsoft.com/fwlink/p/?LinkID=282467).</span></span>
  
## <a name="connecting-to-office-365"></a><span data-ttu-id="d99cc-118">Office 365에 연결</span><span class="sxs-lookup"><span data-stu-id="d99cc-118">Connecting to Office 365</span></span>

<span data-ttu-id="d99cc-p104">Office 365에 대한 모든 연결은 공용 인터넷 또는 개인 Azure Express 경로 연결을 통해 수행되고 SSL로 적절히 보호됩니다. Azure Express 경로를 사용하여 인터넷을 무시하고 전역 Microsoft 네트워크에 직접 연결할 수 있습니다. Microsoft 네트워킹 파트너는 전역 Microsoft 네트워크에 대한 연결을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="d99cc-p104">All Connections to Office 365 are done over the public Internet or over a private Azure ExpressRoute connection, and are secured by SSL as appropriate. Azure ExpressRoute allows connecting directly to the global Microsoft network, bypassing the Internet. A Microsoft networking partner provides the connectivity to the global Microsoft network.</span></span>
  
<span data-ttu-id="d99cc-122">Azure Express 경로에 대한 자세한 내용은 [Office 365용 Azure Express 경로](https://aka.ms/expressrouteoffice365)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="d99cc-122">For more information about Azure ExpressRoute, see [Azure ExpressRoute for Office 365.](https://aka.ms/expressrouteoffice365)</span></span>
  
### <a name="wan-accelerators"></a><span data-ttu-id="d99cc-123">WAN 가속기</span><span class="sxs-lookup"><span data-stu-id="d99cc-123">WAN accelerators</span></span>

<span data-ttu-id="d99cc-p105">Microsoft에서는 Office 365를 통한 고객 소유 WAN 바로 연결 및 캐싱 장치를 지원하지 않습니다. 대기 시간이 길거나 대역폭이 낮은 환경에서 WAN 최적화 컨트롤러를 사용하여 성능을 향상시키려면 Microsoft에서 서비스 요청 문제를 해결하는 동안 사용자가 컨트롤러를 사용하지 않도록 설정하고 장치 공급업체에 장치 지원을 요청해야 합니다. 자세한 내용은 [Office 365를 통한 WAN 바로 연결 및 캐싱 장치](https://go.microsoft.com/fwlink/p/?LinkID=282468)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="d99cc-p105">Microsoft does not provide support for customer-owned WAN acceleration and caching devices with Office 365. If you decide to use a WAN optimization controller to improve performance under conditions of high latency or low bandwidth, you'll need to disable it while troubleshooting service requests with Microsoft, and work with your device vendor for device support. For more information, see [WAN Acceleration and caching devices with Office 365](https://go.microsoft.com/fwlink/p/?LinkID=282468).</span></span>
  
## <a name="the-global-microsoft-network"></a><span data-ttu-id="d99cc-127">세계적인 Microsoft 네트워크</span><span class="sxs-lookup"><span data-stu-id="d99cc-127">The global Microsoft network</span></span>

<span data-ttu-id="d99cc-p106">Office 365 네트워킹 인프라는 서비스를 세계적으로 배포하기 위한 데이터 센터, 서버, 콘텐츠 배포 네트워크, 에지 컴퓨팅 노드 및 광섬유 네트워크의 세계적인 대규모 포트폴리오로 구성됩니다. 복잡한 서비스 계측 및 모니터링 기능이 각 구성 요소의 가장 기본적인 수준에 통합되어 데이터 센터, 네트워크 백본, 인터넷 교환 등을 파악할 수 있으므로 중단 발생의 원인을 발견, 진단 및 관리하는 데 도움이 됩니다. 네트워크는 성능 저하 없이 대규모 네트워크 중단에 대해서도 충분한 용량을 유지하도록 빌드됩니다. 자세한 내용은 [Global Foundation Services](https://go.microsoft.com/fwlink/p/?LinkID=282622)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="d99cc-p106">The Office 365 networking infrastructure is comprised of a large global portfolio of data centers, servers, content distribution networks, edge computing nodes, and fiber optic networks to provide global distribution of services. Sophisticated service instrumentation and monitoring integrates at the deepest levels with each component, giving visibility into the data center, network backbone, internet exchanges and beyond, to help spot, diagnose and manage the cause of disruptions that arise. The network is built to maintain sufficient capacity even for large scale network interruptions without degradation of performance. For more information, see [Global Foundation Services](https://go.microsoft.com/fwlink/p/?LinkID=282622).</span></span> 
  
<span data-ttu-id="d99cc-p107">고객 데이터의 신뢰성과 무결성을 유지하기 위해 Microsoft에서는 Office 365 네트워크와 별도로 소비자 서비스 네트워크를 유지합니다. (이에 제한되지 않음) 정보 흐름을 제어하기 위해 다음과 같은 다양한 방법이 사용됩니다.</span><span class="sxs-lookup"><span data-stu-id="d99cc-p107">To maintain the confidentiality and integrity of customer data, Microsoft keeps consumer services networks separate from Office 365 networks. Multiple techniques are used to control information flows, including but not limited to:</span></span>
  
- <span data-ttu-id="d99cc-p108">물리적 분리. 네트워크 세그먼트는 특정 통신 패턴을 차단하도록 구성된 라우터별로 물리적으로 분리됩니다.</span><span class="sxs-lookup"><span data-stu-id="d99cc-p108">Physical separation. Network segments are physically separated by routers that are configured to prevent specific communication patterns.</span></span>
    
- <span data-ttu-id="d99cc-p109">논리적 분리. VLAN(가상 사설망) 기술은 통신을 추가로 분리하는 데 사용됩니다.</span><span class="sxs-lookup"><span data-stu-id="d99cc-p109">Logical separation. Virtual LAN (VLAN) technology is used to further separate communications.</span></span>
    
- <span data-ttu-id="d99cc-p110">방화벽. 방화벽과 기타 네트워크 보안 강화 지점은 인터넷에 노출된 시스템과의 데이터 교환을 제한하고 Microsoft에서 관리하는 백엔드 시스템에서 시스템을 격리하는 데 사용됩니다.</span><span class="sxs-lookup"><span data-stu-id="d99cc-p110">Firewalls. Firewalls and other network security enforcement points are used to limit data exchanges with systems that are exposed to the Internet, and to isolate systems from back-end systems managed by Microsoft.</span></span> 
    
- <span data-ttu-id="d99cc-140">프로토콜 제한.</span><span class="sxs-lookup"><span data-stu-id="d99cc-140">Protocol restrictions.</span></span>
    
<span data-ttu-id="d99cc-141">자세한 내용은 [Office 365 보안 센터](https://go.microsoft.com/fwlink/p/?LinkID=282621)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="d99cc-141">For more information, see the [Office 365 Trust Center](https://go.microsoft.com/fwlink/p/?LinkID=282621).</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="d99cc-142">기능 가용성</span><span class="sxs-lookup"><span data-stu-id="d99cc-142">Feature availability</span></span>

<span data-ttu-id="d99cc-143">Office 365 계획 간의 기능 가용성을 확인하려면 [Office 365 플랫폼 서비스 설명](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="d99cc-143">To view feature availability across Office 365 plans, see [Office 365 Platform Service Description](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx).</span></span>
  

