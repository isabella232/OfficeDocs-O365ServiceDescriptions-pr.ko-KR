---
title: Exchange Online 설치 및 관리
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-administration-and-management
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 80c07748-ac57-4b90-97dd-a2d1115009a6
description: 이 섹션에서는 관리 컨트롤 및 Exchange Online 설정 사용자 지정 하 고 환경을 유지 하는 조직의 Exchange Online을 실행 하 고 사용할 수 있고 현재 수 있는 지원에 설명 합니다. 셀프서비스 관리 도구 및 조직;를 사용할 수 있는 기능에 대 한 정보 포함 Microsoft 관리 업무 및 성능 확정; 및 서비스 및 제품 업그레이드 합니다.
ms.openlocfilehash: 6b7bb1d68e6d676c39e9ebb254305b2799cc0931
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036462"
---
# <a name="exchange-online-setup-and-administration"></a><span data-ttu-id="404f3-104">Exchange Online 설치 및 관리</span><span class="sxs-lookup"><span data-stu-id="404f3-104">Exchange Online Setup and Administration</span></span>

<span data-ttu-id="404f3-p102">이 섹션에서는 관리 컨트롤 및 Exchange Online 설정 사용자 지정 하 고 환경을 유지 하는 조직의 Exchange Online을 실행 하 고 사용할 수 있고 현재 수 있는 지원에 설명 합니다. 셀프서비스 관리 도구 및 조직;를 사용할 수 있는 기능에 대 한 정보 포함 Microsoft 관리 업무 및 성능 확정; 및 서비스 및 제품 업그레이드 합니다.</span><span class="sxs-lookup"><span data-stu-id="404f3-p102">This section describes the administration controls and support that are available to customize Exchange Online settings and keep an organization's Exchange Online environment up, running, and current. It includes information about self-service administration tools and capabilities available to organizations; Microsoft administration responsibilities and performance commitments; and service and product upgrades.</span></span>
  
## <a name="self-service-administration-tools"></a><span data-ttu-id="404f3-107">셀프 서비스 관리 도구</span><span class="sxs-lookup"><span data-stu-id="404f3-107">Self-service administration tools</span></span>

<span data-ttu-id="404f3-p103">Microsoft에서 모든 Exchange Online 데이터 센터를 직접 제어하고 전체 시스템 성능을 책임지고는 있지만, Office 365 사용자의 전체 환경을 제공하기 위한 구성 요소의 일부만 관리할 수 있습니다. 조직은 자체적으로 데이터 센터, 고객의 WAN(광역 네트워크) 및 고객의 LAN(Local Area Network)에 대한 연결을 담당합니다. 또한 조직은 사용자 장치 및 구성을 책임지며, 사용자가 해당 기능에 액세스해야 하는 경우, 원하는 기능을 관리하는 능력을 포함하여 이에 국한되지 않는 기능 제공을 위해 사용자 기준 라이선스를 유지 관리해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="404f3-p103">Although Microsoft directly controls all Exchange Online data centers and is responsible for overall system performance, it can control only a portion of the elements that combine to provide the total experience for Office 365 users. Organizations themselves are responsible for the network connections to the data centers, the customer's wide area network (WAN), and the customer's local area networks (LANs). Additionally, they are in charge of user devices and their configuration.  They are also responsible for maintaining the required licensing per user for any desired feature, including, but not limited to, the ability to manage these features, for as long as the user needs access to the feature.</span></span>
  
<span data-ttu-id="404f3-112">따라서 Exchange Online은 고객 관리자에게 다양한 메시징 관련 작업을 관리할 수 있는 다음 도구를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="404f3-112">Exchange Online therefore provides customer administrators with the following tools, described below, to manage a variety of messaging-related tasks:</span></span>
  
- [<span data-ttu-id="404f3-113">Microsoft Office 365 포털</span><span class="sxs-lookup"><span data-stu-id="404f3-113">Microsoft Office 365 portal</span></span>](exchange-online-setup-and-administration.md#microsoft-office-365-portal)
    
- [<span data-ttu-id="404f3-114">Microsoft Office 365 관리 센터</span><span class="sxs-lookup"><span data-stu-id="404f3-114">Microsoft Office 365 admin center</span></span>](exchange-online-setup-and-administration.md#microsoft-office-365-admin-center)
    
- [<span data-ttu-id="404f3-115">Exchange 관리 센터</span><span class="sxs-lookup"><span data-stu-id="404f3-115">Exchange admin center</span></span>](exchange-online-setup-and-administration.md#exchange-admin-center)
    
- [<span data-ttu-id="404f3-116">Exchange Online용 원격 Windows PowerShell</span><span class="sxs-lookup"><span data-stu-id="404f3-116">Remote Windows PowerShell for Exchange Online</span></span>](exchange-online-setup-and-administration.md#remote-windows-powershell-for-exchange-online)
    
### <a name="microsoft-office-365-portal"></a><span data-ttu-id="404f3-117">Microsoft Office 365 포털</span><span class="sxs-lookup"><span data-stu-id="404f3-117">Microsoft Office 365 portal</span></span>
<span data-ttu-id="404f3-118"><a name="BKMK_MicrosoftOnlineServicesPortal"> </a></span><span class="sxs-lookup"><span data-stu-id="404f3-118"></span></span>

<span data-ttu-id="404f3-119">[https://portal.office.com](https://portal.office.com)의 Microsoft Office 365 포털은 관리자와 파트너가 Office 365 서비스를 구입 및 관리하고, 사용자가 Office 365 공동 작업 도구에 액세스하여 사용할 수 있는 웹 사이트입니다.</span><span class="sxs-lookup"><span data-stu-id="404f3-119">The Microsoft Office 365 portal, at [https://portal.office.com](https://portal.office.com), is the website through which administrators and partners purchase and manage Office 365 services and where users access and use Office 365 collaborative tools.</span></span>
  
### <a name="microsoft-office-365-admin-center"></a><span data-ttu-id="404f3-120">Microsoft Office 365 관리 센터</span><span class="sxs-lookup"><span data-stu-id="404f3-120">Microsoft Office 365 admin center</span></span>
<span data-ttu-id="404f3-121"><a name="BKMK_Office365admincenterl"> </a></span><span class="sxs-lookup"><span data-stu-id="404f3-121"></span></span>

<span data-ttu-id="404f3-p104">Microsoft Office 365 관리 센터는 각 기업의 서비스 관리자가 기업이 구독한 각 Office 365 서비스의 사용자 계정 및 설정을 관리할 수 있는 웹 포털입니다. Office 365 관리 센터에서 관리자는 EAC(Exchange 관리 센터)의 링크를 따라 이동하여 Exchange Online 관련 설정을 관리할 수 있습니다. Office 365 관리 센터를 사용한 준비 및 실행에 대한 자세한 내용은 다음 동영상을 참조하세요. [Office 365 Enterprise 소개](https://go.microsoft.com/fwlink/p/?LinkId=271806).</span><span class="sxs-lookup"><span data-stu-id="404f3-p104">The Microsoft Office 365 admin center is the web portal from which each company's service administrator can manage user accounts and settings for each of the Office 365 services to which they subscribe. From within the Office 365 admin center, administrators can follow links to the Exchange admin center (EAC), where they can manage settings specific to Exchange Online. For more information about getting up and running using the Office 365 admin center, see the following video: [Introducing Office 365 Enterprise](https://go.microsoft.com/fwlink/p/?LinkId=271806).</span></span>
  
### <a name="exchange-admin-center"></a><span data-ttu-id="404f3-125">Exchange 관리 센터</span><span class="sxs-lookup"><span data-stu-id="404f3-125">Exchange admin center</span></span>
<span data-ttu-id="404f3-126"><a name="BKMK_ExchangeAdministrationCenter"> </a></span><span class="sxs-lookup"><span data-stu-id="404f3-126"></span></span>

<span data-ttu-id="404f3-p105">Exchange Online은 온-프레미스, 온라인 또는 하이브리드 배포의 관리에 최적화된 편리한 단일 통합 관리 콘솔을 제공합니다. EAC(Exchange 관리 센터)를 통해 관리자는 Exchange 관련 설정을 관리할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="404f3-p105">Exchange Online provides a single unified management console that allows for ease of use and is optimized for management of on-premises, online, or hybrid deployments. The Exchange admin center (EAC) is where administrators can manage Exchange-specific settings.</span></span>
  
<span data-ttu-id="404f3-129">EAC를 사용하여 Exchange Online을 관리하는 방법에 대한 자세한 내용은 [Exchange 관리 센터](https://go.microsoft.com/fwlink/p/?LinkId=271807)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="404f3-129">For more information about how to use the EAC to manage Exchange Online, see [Exchange admin center](https://go.microsoft.com/fwlink/p/?LinkId=271807).</span></span>
  
### <a name="remote-windows-powershell-for-exchange-online"></a><span data-ttu-id="404f3-130">Exchange Online용 원격 Windows PowerShell</span><span class="sxs-lookup"><span data-stu-id="404f3-130">Remote Windows PowerShell for Exchange Online</span></span>
<span data-ttu-id="404f3-131"><a name="BKMK_RemoteWindowsPowerShell"> </a></span><span class="sxs-lookup"><span data-stu-id="404f3-131"></span></span>

<span data-ttu-id="404f3-p106">원격 Windows PowerShell을 사용하면 관리자는 Exchange Online에 연결하여 EAC에서는 사용할 수 없거나 타당하지 않은 관리 작업을 수행할 수 없습니다. 여기에는 반복 작업 자동화, 사용자 지정 보고서용 데이터 추출, 정책 사용자 지정 및 기존 인프라와 프로세스에 Exchange Online 연결 기능이 포함됩니다. 자세한 내용은 [원격 PowerShell을 사용하여 Exchange Online에 연결](https://go.microsoft.com/fwlink/p/?LinkId=308994)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="404f3-p106">Using remote Windows PowerShell, administrators can connect to Exchange Online to perform management tasks that are not available or practical using the EAC. These include the ability to automate repetitive tasks, extract data for custom reports, customize policies, and connect Exchange Online to existing infrastructure and processes. For more information, see [Connect to Exchange Online Using Remote PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=308994).</span></span>
  
<span data-ttu-id="404f3-p107">Exchange Online에서는 Exchange Server 2013과 동일한 Windows PowerShell cmdlet을 사용합니다. 그러나 Exchange Online에 적용되지 않는 특정 명령과 매개 변수는 사용할 수 없습니다. Exchange Online에서 사용할 수 있는 cmdlet 목록은 [Exchange Online cmdlet](https://go.microsoft.com/fwlink/p/?LinkId=271808)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="404f3-p107">Exchange Online uses the same Windows PowerShell cmdlets as Exchange Server 2013, with certain commands and parameters unavailable because these features do not apply in Exchange Online. For a list of cmdlets for use with Exchange Online, see [Exchange Online cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).</span></span>
  
<span data-ttu-id="404f3-p108">원격 Windows PowerShell을 사용하기 위해 관리자가 Exchange Server 관리 또는 마이그레이션 도구를 설치할 필요가 없습니다. 그러나 관리자의 컴퓨터는 Windows PowerShell v3 및 WinRM 3.0, Windows .NET Framework 4.5가 포함된 Windows Management Framework 3.0을 실행 중이어야 합니다. 이러한 구성 요소는 Windows 8 또는 Windows Server 2012를 실행 중인 컴퓨터에 이미 설치되어 있습니다. Windows 7 또는 Windows Server 2008 R2를 실행 중인 컴퓨터에 대해서는 관리자가 이러한 구성 요소를 수동으로 다운로드할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="404f3-p108">Administrators do not need to install any Exchange Server management or migration tools to use remote Windows PowerShell. However, administrators' computers must be running the Windows Management Framework 3.0, which contains Windows PowerShell v3 and WinRM 3.0; and Windows .NET Framework 4.5. These components are already installed on computers running Windows 8 or Windows Server 2012. Administrators can manually download these components for computers that are running Windows 7 or Windows Server 2008 R2.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="404f3-141">DoS(서비스 거부) 공격을 방지하려면 Exchange Online 조직에 대해 세 가지 개방형 Windows PowerShell 연결만을 사용해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="404f3-141">To help prevent denial of service (DoS) attacks, you're limited to three open Windows PowerShell connections to your Exchange Online organization.</span></span> 
  
## <a name="self-service-capabilities-for-exchange-online"></a><span data-ttu-id="404f3-142">Exchange Online에 대한 셀프 서비스 기능</span><span class="sxs-lookup"><span data-stu-id="404f3-142">Self-service capabilities for Exchange Online</span></span>

<span data-ttu-id="404f3-p109">EAC, 원격 Windows PowerShell 및 기타 도구를 통해 Exchange Online을 관리하는 데 사용할 수 있는 다음 기능은 중요한 기능입니다. 이 문서에서 설명하는 다른 많은 설정 또한 이러한 도구로 제어할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="404f3-p109">Below are important capabilities that are available for managing Exchange Online by using the EAC, remote Windows PowerShell, and other tools. Many other settings can also be controlled with these tools, as described throughout this document.</span></span>
  
### <a name="mobile-device-security-policies-for-exchange-online"></a><span data-ttu-id="404f3-145">Exchange Online에 대한 모바일 장치 보안 정책</span><span class="sxs-lookup"><span data-stu-id="404f3-145">Mobile device security policies for Exchange Online</span></span>

<span data-ttu-id="404f3-p110">Exchange Online에서는 모바일 장치에 대해 Exchange Server 2013과 동일한 ActiveSync 정책을 지원합니다. 관리자는 EAC 또는 원격 Windows PowerShell을 통해 이러한 보안 정책을 특정 사용자 및 그룹에 대해 적용하고 사용자 지정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="404f3-p110">Exchange Online supports the same ActiveSync policies for mobile devices as Exchange Server 2013. Administrators can enforce and customize these security policies for specific users and groups by using the EAC or remote Windows PowerShell.</span></span>
  
### <a name="message-tracking-for-exchange-online"></a><span data-ttu-id="404f3-148">Exchange Online에 대한 메시지 추적</span><span class="sxs-lookup"><span data-stu-id="404f3-148">Message tracking for Exchange Online</span></span>

<span data-ttu-id="404f3-149">배달 보고서를 통한 메시지 추적은 다음 항목에서 설명합니다. [보고 기능 및 문제 해결 도구](reporting-features-and-troubleshooting-tools.md).</span><span class="sxs-lookup"><span data-stu-id="404f3-149">Message tracking via the Delivery Reports feature is described in the following topic: [Reporting Features and Troubleshooting Tools](reporting-features-and-troubleshooting-tools.md).</span></span>
  
### <a name="usage-reporting-for-exchange-online"></a><span data-ttu-id="404f3-150">Exchange Online에 대한 사용 현황 보고</span><span class="sxs-lookup"><span data-stu-id="404f3-150">Usage reporting for Exchange Online</span></span>

<span data-ttu-id="404f3-p111">관리자는 원격 Windows PowerShell을 사용하여 조직 내 사람들이 Exchange Online 서비스를 사용하는 방식에 대한 정보를 검색할 수 있습니다. 사용할 수 있는 정보는 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="404f3-p111">Administrators can use remote Windows PowerShell to retrieve information about how people in their organizations use the Exchange Online service. Available information includes:</span></span>
  
- <span data-ttu-id="404f3-153">조직 내 각 사용자에 대한 사서함 크기 표시.</span><span class="sxs-lookup"><span data-stu-id="404f3-153">Showing the mailbox size for each user in the organization.</span></span>
    
- <span data-ttu-id="404f3-154">사서함에 설정되는 사용자 지정 사용 권한(예: 대리인 액세스 권한) 표시.</span><span class="sxs-lookup"><span data-stu-id="404f3-154">Displaying custom permissions that are set on mailboxes, such as delegate access.</span></span>
    
- <span data-ttu-id="404f3-155">Exchange ActiveSync를 통해 연결 중인 사용자, 이러한 사용자가 사용 중인 장치 및 마지막으로 연결한 시간과 같은 모바일 장치 액세스에 대한 데이터 추출.</span><span class="sxs-lookup"><span data-stu-id="404f3-155">Extracting data about mobile device access, such as which users are connecting through Exchange ActiveSync, what devices they are using, and when they last connected.</span></span>
    
<span data-ttu-id="404f3-p112">"get-"으로 시작하는 원격 Windows PowerShell cmdlet은 Exchange Online 시스템에서 데이터를 가져올 수 있습니다. 관리자는 고급 분석 또는 보고를 위해 Windows PowerShell에서 이 정보를 .csv 형식으로 내보낼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="404f3-p112">Remote Windows PowerShell cmdlets that start with "get-" can fetch data from the Exchange Online system. Administrators can export this information from Windows PowerShell in .csv format for advanced analysis or reporting.</span></span>
  
<span data-ttu-id="404f3-158">Exchange Online에서 사용할 수 있는 Windows PowerShell cmdlet에 대한 자세한 내용은 [Exchange Online cmdlet](https://go.microsoft.com/fwlink/p/?LinkId=271808)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="404f3-158">For more information about Windows PowerShell cmdlets for use with Exchange Online, see [Exchange Online cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).</span></span>
  
### <a name="auditing-for-exchange-online"></a><span data-ttu-id="404f3-159">Exchange Online에 대한 감사</span><span class="sxs-lookup"><span data-stu-id="404f3-159">Auditing for Exchange Online</span></span>

<span data-ttu-id="404f3-160">감사 로깅 기능은 다음 항목에서 설명합니다. [보고 기능 및 문제 해결 도구](reporting-features-and-troubleshooting-tools.md).</span><span class="sxs-lookup"><span data-stu-id="404f3-160">The audit logging feature is described in the following topic: [Reporting Features and Troubleshooting Tools](reporting-features-and-troubleshooting-tools.md).</span></span>
  
## <a name="service-and-product-upgrades-for-exchange-online"></a><span data-ttu-id="404f3-161">Exchange Online에 대한 서비스 및 제품 업그레이드</span><span class="sxs-lookup"><span data-stu-id="404f3-161">Service and product upgrades for Exchange Online</span></span>

<span data-ttu-id="404f3-p113">Exchange Online 고객은 Exchange Server의 새 릴리스를 비롯하여 최신 Exchange 기술에 대한 정기 업그레이드를 통해 혜택을 얻을 수 있습니다. 이러한 업그레이드는 추가 비용 없이 가능하며, 고객은 항상 최신 Exchange 소프트웨어를 사용하고 있는지 확인해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="404f3-p113">Exchange Online customers benefit from periodic upgrades to the latest Exchange technology, including new releases of Exchange Server. These upgrades are made available at no additional charge, and ensure that customers are always using the latest Exchange software.</span></span>
  
<span data-ttu-id="404f3-164">고객은 Microsoft에서 주요 Exchange 버전을 릴리스한 후 12개월 이내에 서비스를 새 릴리스로 업그레이드할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="404f3-164">After a major version of Exchange is released by Microsoft, customers have up to 12 months to upgrade their service to the new release.</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="404f3-165">기능 가용성</span><span class="sxs-lookup"><span data-stu-id="404f3-165">Feature Availability</span></span>

<span data-ttu-id="404f3-166">Office 365 계획, 독립 실행형 옵션 및 온-프레미스 솔루션별로 기능 가용성을 확인하려면 [Exchange Online 서비스 설명](exchange-online-service-description.md)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="404f3-166">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  
