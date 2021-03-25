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
description: Microsoft는 다음과 같은 네트워킹 기능을 지원합니다.
ms.openlocfilehash: 318437ce65c5ced55d42e798bf76774cda6708f9
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173023"
---
# <a name="networking"></a><span data-ttu-id="f1c90-103">네트워킹</span><span class="sxs-lookup"><span data-stu-id="f1c90-103">Networking</span></span>

<span data-ttu-id="f1c90-104">Microsoft는 다음과 같은 네트워킹 기능을 지원합니다.</span><span class="sxs-lookup"><span data-stu-id="f1c90-104">Microsoft supports the following networking features.</span></span>
  
## <a name="ports-protocols-and-ip-addresses"></a><span data-ttu-id="f1c90-105">포트, 프로토콜 및 IP 주소</span><span class="sxs-lookup"><span data-stu-id="f1c90-105">Ports, protocols, and IP addresses</span></span>

<span data-ttu-id="f1c90-106">Microsoft는 IPv4 및 IPv6 주소를 사용합니다.</span><span class="sxs-lookup"><span data-stu-id="f1c90-106">Microsoft uses IPv4 and IPv6 addresses.</span></span> <span data-ttu-id="f1c90-107">Office 365에서 IPv6 주소는 연결 시 선택 사항이며 반드시 사용해야 하는 것은 아닙니다.</span><span class="sxs-lookup"><span data-stu-id="f1c90-107">Use of IPv6 addressing is optional and not required for connectivity with Office 365.</span></span> <span data-ttu-id="f1c90-108">일부 Microsoft 365 기능은 IPv6을 사용하여 완전히 사용하도록 설정되지는 않습니다.</span><span class="sxs-lookup"><span data-stu-id="f1c90-108">Not all Microsoft 365 features are fully enabled using IPv6.</span></span> <span data-ttu-id="f1c90-109">Ipv6 지원에 대한 자세한 내용은 Microsoft 서비스의 [IPv6 지원을 참조하세요.](/office365/enterprise/ipv6-support)</span><span class="sxs-lookup"><span data-stu-id="f1c90-109">For more information about Ipv6 support, see [IPv6 support in Microsoft services](/office365/enterprise/ipv6-support).</span></span>
  
<span data-ttu-id="f1c90-110">Microsoft는 Microsoft 도움말에서 허용된 IP 주소 목록을 유지 관리합니다.</span><span class="sxs-lookup"><span data-stu-id="f1c90-110">Microsoft maintains a list of allowed IP addresses in the Microsoft help.</span></span> <span data-ttu-id="f1c90-111">자세한 내용은 URL 및 [IP 주소 범위를 참조하세요.](/office365/enterprise/urls-and-ip-address-ranges)</span><span class="sxs-lookup"><span data-stu-id="f1c90-111">For more information, see [URLs and IP address ranges](/office365/enterprise/urls-and-ip-address-ranges).</span></span> <span data-ttu-id="f1c90-112">21Vianet에서 운영하는 Office 365의 경우 [21Vianet에서 운영하는 Office 365용 URL 및 IP 주소](/office365/enterprise/managing-office-365-endpoints)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="f1c90-112">For Office 365 operated by 21Vianet, see [URLs and IP Addresses for Office 365 operated by 21Vianet](/office365/enterprise/managing-office-365-endpoints).</span></span> <span data-ttu-id="f1c90-113">Office 365 Germany의 경우 [Office 365 Germany 끝점](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="f1c90-113">For Office 365 Germany, see [Office 365 Germany endpoints](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="f1c90-p103">특정 IP 주소 서브넷으로 라우팅하는 대신 위 문서에 나열된 루트 도메인 이름(예: \*.Outlook.com, \*.MicrosoftOnline.com and \*.SharePoint.com)으로 라우팅하는 것이 좋습니다. IP 주소 서브넷에 의존하면 변경 사항이 발생하는 경우 사용자의 서비스가 중단될 위험이 있습니다.</span><span class="sxs-lookup"><span data-stu-id="f1c90-p103">We strongly recommend that you enable routing to the root domain names listed in the articles above (such as \*.Outlook.com, \*.MicrosoftOnline.com and \*.SharePoint.com) instead of routing to specific IP address subnets. Relying on IP address subnets runs the risk of outages for your users as changes are made.</span></span> 
  
## <a name="bandwidth-requirements"></a><span data-ttu-id="f1c90-116">대역폭 요구 사항</span><span class="sxs-lookup"><span data-stu-id="f1c90-116">Bandwidth requirements</span></span>

<span data-ttu-id="f1c90-117">대역폭 요구 사항에 대한 자세한 내용은 [인터넷 대역폭 계획](/office365/enterprise/network-planning-and-performance)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="f1c90-117">For information on bandwidth requirements, see [Internet bandwidth planning](/office365/enterprise/network-planning-and-performance).</span></span>
  
## <a name="connecting-to-microsoft"></a><span data-ttu-id="f1c90-118">Microsoft에 연결</span><span class="sxs-lookup"><span data-stu-id="f1c90-118">Connecting to Microsoft</span></span>

<span data-ttu-id="f1c90-119">Microsoft에 대한 모든 연결은 공용 인터넷 또는 개인 Azure ExpressRoute 연결을 통해 수행하며 SSL을 통해 적절하게 보호됩니다.</span><span class="sxs-lookup"><span data-stu-id="f1c90-119">All Connections to Microsoft are done over the public internet or over a private Azure ExpressRoute connection, and are secured by SSL as appropriate.</span></span> <span data-ttu-id="f1c90-120">Azure ExpressRoute를 사용하면 인터넷을 우회하여 전역 Microsoft 네트워크에 직접 연결할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="f1c90-120">Azure ExpressRoute allows connecting directly to the global Microsoft network, bypassing the internet.</span></span> <span data-ttu-id="f1c90-121">Microsoft 네트워킹 파트너는 전역 Microsoft 네트워크에 대한 연결을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="f1c90-121">A Microsoft networking partner provides the connectivity to the global Microsoft network.</span></span>
  
<span data-ttu-id="f1c90-122">Azure Express 경로에 대한 자세한 내용은 [Office 365용 Azure Express 경로](/microsoft-365/enterprise/azure-expressroute)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="f1c90-122">For more information about Azure ExpressRoute, see [Azure ExpressRoute for Office 365.](/microsoft-365/enterprise/azure-expressroute)</span></span>
  
### <a name="wan-accelerators"></a><span data-ttu-id="f1c90-123">WAN 가속기</span><span class="sxs-lookup"><span data-stu-id="f1c90-123">WAN accelerators</span></span>

<span data-ttu-id="f1c90-p105">Microsoft에서는 Office 365를 통한 고객 소유 WAN 바로 연결 및 캐싱 장치를 지원하지 않습니다. 대기 시간이 길거나 대역폭이 낮은 환경에서 WAN 최적화 컨트롤러를 사용하여 성능을 향상시키려면 Microsoft에서 서비스 요청 문제를 해결하는 동안 사용자가 컨트롤러를 사용하지 않도록 설정하고 장치 공급업체에 장치 지원을 요청해야 합니다. 자세한 내용은 [Office 365를 통한 WAN 바로 연결 및 캐싱 장치](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="f1c90-p105">Microsoft does not provide support for customer-owned WAN acceleration and caching devices with Office 365. If you decide to use a WAN optimization controller to improve performance under conditions of high latency or low bandwidth, you'll need to disable it while troubleshooting service requests with Microsoft, and work with your device vendor for device support. For more information, see [WAN Acceleration and caching devices with Office 365](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365).</span></span>
  
## <a name="the-global-microsoft-network"></a><span data-ttu-id="f1c90-127">세계적인 Microsoft 네트워크</span><span class="sxs-lookup"><span data-stu-id="f1c90-127">The global Microsoft network</span></span>

<span data-ttu-id="f1c90-128">Microsoft 네트워킹 인프라는 서비스의 전역 배포를 제공하기 위해 데이터 센터, 서버, 콘텐츠 배포 네트워크, 에지 컴퓨팅 노드 및 광섬유 네트워크의 대규모 글로벌 포트폴리오로 구성됩니다.</span><span class="sxs-lookup"><span data-stu-id="f1c90-128">The Microsoft networking infrastructure is comprised of a large global portfolio of data centers, servers, content distribution networks, edge computing nodes, and fiber optic networks to provide global distribution of services.</span></span> <span data-ttu-id="f1c90-129">복잡한 서비스 계측 및 모니터링 기능이 각 구성 요소의 가장 기본적인 수준에 통합되어 데이터 센터, 네트워크 백본, 인터넷 교환 등을 파악할 수 있으므로 중단 발생의 원인을 발견, 진단 및 관리하는 데 도움이 됩니다.</span><span class="sxs-lookup"><span data-stu-id="f1c90-129">Sophisticated service instrumentation and monitoring integrates at the deepest levels with each component, giving visibility into the data center, network backbone, internet exchanges and beyond, to help spot, diagnose and manage the cause of disruptions that arise.</span></span> <span data-ttu-id="f1c90-130">네트워크는 성능 저하 없이 대규모 네트워크 중단에 대해서도 충분한 용량을 유지하도록 빌드됩니다.</span><span class="sxs-lookup"><span data-stu-id="f1c90-130">The network is built to maintain sufficient capacity even for large scale network interruptions without degradation of performance.</span></span> <span data-ttu-id="f1c90-131">자세한 내용은 [Microsoft 전역 네트워크를 참조하세요.](/azure/networking/microsoft-global-network)</span><span class="sxs-lookup"><span data-stu-id="f1c90-131">For more information, see [Microsoft Global Network](/azure/networking/microsoft-global-network).</span></span> 
  
<span data-ttu-id="f1c90-132">고객 데이터의 기밀성 및 무결성을 유지하기 위해 Microsoft는 소비자 서비스 네트워크를 Microsoft 네트워크와 분리합니다.</span><span class="sxs-lookup"><span data-stu-id="f1c90-132">To maintain the confidentiality and integrity of customer data, Microsoft keeps consumer services networks separate from Microsoft networks.</span></span> <span data-ttu-id="f1c90-133">(이에 제한되지 않음) 정보 흐름을 제어하기 위해 다음과 같은 다양한 방법이 사용됩니다.</span><span class="sxs-lookup"><span data-stu-id="f1c90-133">Multiple techniques are used to control information flows, including but not limited to:</span></span>
  
- <span data-ttu-id="f1c90-p108">물리적 분리. 네트워크 세그먼트는 특정 통신 패턴을 차단하도록 구성된 라우터별로 물리적으로 분리됩니다.</span><span class="sxs-lookup"><span data-stu-id="f1c90-p108">Physical separation. Network segments are physically separated by routers that are configured to prevent specific communication patterns.</span></span>
    
- <span data-ttu-id="f1c90-p109">논리적 분리. VLAN(가상 사설망) 기술은 통신을 추가로 분리하는 데 사용됩니다.</span><span class="sxs-lookup"><span data-stu-id="f1c90-p109">Logical separation. Virtual LAN (VLAN) technology is used to further separate communications.</span></span>
    
- <span data-ttu-id="f1c90-138">방화벽.</span><span class="sxs-lookup"><span data-stu-id="f1c90-138">Firewalls.</span></span> <span data-ttu-id="f1c90-139">방화벽 및 기타 네트워크 보안 적용 지점은 인터넷에 노출되는 시스템과의 데이터 교환을 제한하고 Microsoft에서 관리하는 백 엔드 시스템에서 시스템을 격리하는 데 사용됩니다.</span><span class="sxs-lookup"><span data-stu-id="f1c90-139">Firewalls and other network security enforcement points are used to limit data exchanges with systems that are exposed to the internet, and to isolate systems from back-end systems managed by Microsoft.</span></span> 
    
- <span data-ttu-id="f1c90-140">프로토콜 제한.</span><span class="sxs-lookup"><span data-stu-id="f1c90-140">Protocol restrictions.</span></span>
    
<span data-ttu-id="f1c90-141">자세한 내용은 [Office 365 보안 센터](https://www.microsoft.com/trust-center)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="f1c90-141">For more information, see the [Office 365 Trust Center](https://www.microsoft.com/trust-center).</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="f1c90-142">기능 가용성</span><span class="sxs-lookup"><span data-stu-id="f1c90-142">Feature availability</span></span>

<span data-ttu-id="f1c90-143">계획 간 기능 가용성을 확인 내용은 [Microsoft 365 및 Office 365 플랫폼 서비스 설명을 참조하세요.](office-365-platform-service-description.md)</span><span class="sxs-lookup"><span data-stu-id="f1c90-143">To view feature availability across plans, see [Microsoft 365 and Office 365 platform service description](office-365-platform-service-description.md).</span></span>
