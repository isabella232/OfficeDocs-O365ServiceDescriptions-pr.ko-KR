---
title: Exchange Online 설치 및 관리
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-administration-and-management
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 80c07748-ac57-4b90-97dd-a2d1115009a6
description: 이 문서에서는 Exchange Online 설정을 사용자 지정 하 고 조직의 Exchange Online 환경을 최신, 실행 및 최신 상태로 유지 하는 데 사용할 수 있는 관리 제어 및 지원에 대해 설명 합니다. 내용에는 Microsoft 관리 책임 및 성능 약정, 서비스 및 제품 업그레이드와 같이 조직에서 사용할 수 있는 셀프 서비스 관리 도구 및 기능에 대한 정보가 포함되어 있습니다.
ms.openlocfilehash: 19ec50b3f502ee111de05e1a115d17f16fec3569
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45133003"
---
# <a name="exchange-online-setup-and-administration"></a><span data-ttu-id="ae036-104">Exchange Online 설치 및 관리</span><span class="sxs-lookup"><span data-stu-id="ae036-104">Exchange Online setup and administration</span></span>

<span data-ttu-id="ae036-105">이 문서에서는 Exchange Online 설정을 사용자 지정 하 고 조직의 Exchange Online 환경을 최신, 실행 및 최신 상태로 유지 하는 데 사용할 수 있는 관리 제어 및 지원에 대해 설명 합니다.</span><span class="sxs-lookup"><span data-stu-id="ae036-105">This article describes the administration controls and support that are available to customize Exchange Online settings and keep an organization's Exchange Online environment up, running, and current.</span></span> <span data-ttu-id="ae036-106">내용에는 Microsoft 관리 책임 및 성능 약정, 서비스 및 제품 업그레이드와 같이 조직에서 사용할 수 있는 셀프 서비스 관리 도구 및 기능에 대한 정보가 포함되어 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ae036-106">It includes information about self-service administration tools and capabilities available to organizations; Microsoft administration responsibilities and performance commitments; and service and product upgrades.</span></span>
  
## <a name="self-service-administration-tools"></a><span data-ttu-id="ae036-107">셀프 서비스 관리 도구</span><span class="sxs-lookup"><span data-stu-id="ae036-107">Self-service administration tools</span></span>

<span data-ttu-id="ae036-108">Microsoft는 모든 Exchange Online 데이터 센터를 직접 제어 하 고 전반적인 시스템 성능을 담당 하지만 전체 사용자 환경을 제공 하기 위해 결합 되는 요소의 일부만 제어할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ae036-108">Although Microsoft directly controls all Exchange Online data centers and is responsible for overall system performance, it can control only a portion of the elements that combine to provide the total experience for users.</span></span> <span data-ttu-id="ae036-109">조직은 데이터 센터, 고객의 WAN (광역 네트워크) 및 고객 Lan (local area networks)에 대 한 네트워크 연결을 담당 합니다.</span><span class="sxs-lookup"><span data-stu-id="ae036-109">Organizations themselves are responsible for the network connections to the data centers, the customer's wide area network (WAN), and the customer's local area networks (LANs).</span></span> <span data-ttu-id="ae036-110">또한 사용자 장치 및 해당 구성에 대 한 비용이 청구 됩니다.</span><span class="sxs-lookup"><span data-stu-id="ae036-110">Additionally, they are in charge of user devices and their configuration.</span></span><span data-ttu-id="ae036-111">또한 사용자가 기능에 액세스 해야 하는 경우에는 이러한 기능을 관리 하는 기능을 비롯 하 여 원하는 기능에 대해 사용자 당 필요한 라이선스를 유지 관리 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="ae036-111">  They are also responsible for maintaining the required licensing per user for any desired feature, including, but not limited to, the ability to manage these features, for as long as the user needs access to the feature.</span></span>
  
<span data-ttu-id="ae036-112">따라서 Exchange Online은 고객 관리자에게 다양한 메시징 관련 작업을 관리할 수 있는 다음 도구를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="ae036-112">Exchange Online therefore provides customer administrators with the following tools, described below, to manage a variety of messaging-related tasks:</span></span>
  
- [<span data-ttu-id="ae036-113">Microsoft Office 365 포털</span><span class="sxs-lookup"><span data-stu-id="ae036-113">Microsoft Office 365 portal</span></span>](exchange-online-setup-and-administration.md#microsoft-office-365-portal)
    
- [<span data-ttu-id="ae036-114">Microsoft 365 관리 센터</span><span class="sxs-lookup"><span data-stu-id="ae036-114">Microsoft 365 admin center</span></span>](#microsoft-365-admin-center)
    
- [<span data-ttu-id="ae036-115">Exchange 관리 센터</span><span class="sxs-lookup"><span data-stu-id="ae036-115">Exchange admin center</span></span>](exchange-online-setup-and-administration.md#exchange-admin-center)
    
- [<span data-ttu-id="ae036-116">Exchange Online용 원격 Windows PowerShell</span><span class="sxs-lookup"><span data-stu-id="ae036-116">Remote Windows PowerShell for Exchange Online</span></span>](exchange-online-setup-and-administration.md#remote-windows-powershell-for-exchange-online)
    
### <a name="microsoft-office-365-portal"></a><span data-ttu-id="ae036-117">Microsoft Office 365 포털</span><span class="sxs-lookup"><span data-stu-id="ae036-117">Microsoft Office 365 portal</span></span>

<span data-ttu-id="ae036-118">[https://portal.office.com](https://portal.office.com)의 Microsoft Office 365 포털은 관리자와 파트너가 Office 365 서비스를 구입 및 관리하고, 사용자가 Office 365 공동 작업 도구에 액세스하여 사용할 수 있는 웹 사이트입니다.</span><span class="sxs-lookup"><span data-stu-id="ae036-118">The Microsoft Office 365 portal, at [https://portal.office.com](https://portal.office.com), is the website through which administrators and partners purchase and manage Office 365 services and where users access and use Office 365 collaborative tools.</span></span>
  
### <a name="microsoft-365-admin-center"></a><span data-ttu-id="ae036-119">Microsoft 365 관리 센터</span><span class="sxs-lookup"><span data-stu-id="ae036-119">Microsoft 365 admin center</span></span>

<span data-ttu-id="ae036-120">Microsoft 365 관리 센터는 각 회사의 서비스 관리자가 구독 하는 각 Microsoft 서비스에 대 한 사용자 계정 및 설정을 관리할 수 있는 웹 포털입니다.</span><span class="sxs-lookup"><span data-stu-id="ae036-120">The Microsoft 365 admin center is the web portal from which each company's service administrator can manage user accounts and settings for each of the Microsoft services to which they subscribe.</span></span> <span data-ttu-id="ae036-121">Microsoft 365 관리 센터에서 관리자는 EAC (Exchange 관리 센터)에 대 한 링크를 팔 로우 하 여 Exchange Online과 관련 된 설정을 관리할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ae036-121">From within the Microsoft 365 admin center, administrators can follow links to the Exchange admin center (EAC), where they can manage settings specific to Exchange Online.</span></span> <span data-ttu-id="ae036-122">Microsoft 365 관리 센터를 사용 하 여 작업을 수행 하 고 실행 하는 방법에 대 한 자세한 내용은 [Office 365 Enterprise 소개](https://go.microsoft.com/fwlink/p/?LinkId=271806)비디오를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="ae036-122">For more information about getting up and running using the Microsoft 365 admin center, see the following video: [Introducing Office 365 Enterprise](https://go.microsoft.com/fwlink/p/?LinkId=271806).</span></span>
  
### <a name="exchange-admin-center"></a><span data-ttu-id="ae036-123">Exchange 관리 센터</span><span class="sxs-lookup"><span data-stu-id="ae036-123">Exchange admin center</span></span>

<span data-ttu-id="ae036-124">Exchange Online provides a single unified management console that allows for ease of use and is optimized for management of on-premises, online, or hybrid deployments.</span><span class="sxs-lookup"><span data-stu-id="ae036-124">Exchange Online provides a single unified management console that allows for ease of use and is optimized for management of on-premises, online, or hybrid deployments.</span></span> <span data-ttu-id="ae036-125">The Exchange admin center (EAC) is where administrators can manage Exchange-specific settings.</span><span class="sxs-lookup"><span data-stu-id="ae036-125">The Exchange admin center (EAC) is where administrators can manage Exchange-specific settings.</span></span>
  
<span data-ttu-id="ae036-126">EAC를 사용하여 Exchange Online을 관리하는 방법에 대한 자세한 내용은 [Exchange 관리 센터](https://go.microsoft.com/fwlink/p/?LinkId=271807)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="ae036-126">For more information about how to use the EAC to manage Exchange Online, see [Exchange admin center](https://go.microsoft.com/fwlink/p/?LinkId=271807).</span></span>
  
### <a name="remote-windows-powershell-for-exchange-online"></a><span data-ttu-id="ae036-127">Exchange Online용 원격 Windows PowerShell</span><span class="sxs-lookup"><span data-stu-id="ae036-127">Remote Windows PowerShell for Exchange Online</span></span>

<span data-ttu-id="ae036-128">Using remote Windows PowerShell, administrators can connect to Exchange Online to perform management tasks that are not available or practical using the EAC.</span><span class="sxs-lookup"><span data-stu-id="ae036-128">Using remote Windows PowerShell, administrators can connect to Exchange Online to perform management tasks that are not available or practical using the EAC.</span></span> <span data-ttu-id="ae036-129">These include the ability to automate repetitive tasks, extract data for custom reports, customize policies, and connect Exchange Online to existing infrastructure and processes.</span><span class="sxs-lookup"><span data-stu-id="ae036-129">These include the ability to automate repetitive tasks, extract data for custom reports, customize policies, and connect Exchange Online to existing infrastructure and processes.</span></span> <span data-ttu-id="ae036-130">For more information, see [Connect to Exchange Online Using Remote PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=308994).</span><span class="sxs-lookup"><span data-stu-id="ae036-130">For more information, see [Connect to Exchange Online Using Remote PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=308994).</span></span>
  
<span data-ttu-id="ae036-131">Exchange Online uses the same Windows PowerShell cmdlets as Exchange Server 2013, with certain commands and parameters unavailable because these features do not apply in Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="ae036-131">Exchange Online uses the same Windows PowerShell cmdlets as Exchange Server 2013, with certain commands and parameters unavailable because these features do not apply in Exchange Online.</span></span> <span data-ttu-id="ae036-132">For a list of cmdlets for use with Exchange Online, see [Exchange Online cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).</span><span class="sxs-lookup"><span data-stu-id="ae036-132">For a list of cmdlets for use with Exchange Online, see [Exchange Online cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).</span></span>
  
<span data-ttu-id="ae036-133">Administrators do not need to install any Exchange Server management or migration tools to use remote Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="ae036-133">Administrators do not need to install any Exchange Server management or migration tools to use remote Windows PowerShell.</span></span> <span data-ttu-id="ae036-134">However, administrators' computers must be running the Windows Management Framework 3.0, which contains Windows PowerShell v3 and WinRM 3.0; and Windows .NET Framework 4.5.</span><span class="sxs-lookup"><span data-stu-id="ae036-134">However, administrators' computers must be running the Windows Management Framework 3.0, which contains Windows PowerShell v3 and WinRM 3.0; and Windows .NET Framework 4.5.</span></span> <span data-ttu-id="ae036-135">These components are already installed on computers running Windows 8 or Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="ae036-135">These components are already installed on computers running Windows 8 or Windows Server 2012.</span></span> <span data-ttu-id="ae036-136">Administrators can manually download these components for computers that are running Windows 7 or Windows Server 2008 R2.</span><span class="sxs-lookup"><span data-stu-id="ae036-136">Administrators can manually download these components for computers that are running Windows 7 or Windows Server 2008 R2.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="ae036-137">DoS(서비스 거부) 공격을 방지하려면 Exchange Online 조직에 대해 세 가지 개방형 Windows PowerShell 연결만을 사용해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="ae036-137">To help prevent denial of service (DoS) attacks, you're limited to three open Windows PowerShell connections to your Exchange Online organization.</span></span> 
  
## <a name="self-service-capabilities-for-exchange-online"></a><span data-ttu-id="ae036-138">Exchange Online에 대한 셀프 서비스 기능</span><span class="sxs-lookup"><span data-stu-id="ae036-138">Self-service capabilities for Exchange Online</span></span>

<span data-ttu-id="ae036-139">Below are important capabilities that are available for managing Exchange Online by using the EAC, remote Windows PowerShell, and other tools.</span><span class="sxs-lookup"><span data-stu-id="ae036-139">Below are important capabilities that are available for managing Exchange Online by using the EAC, remote Windows PowerShell, and other tools.</span></span> <span data-ttu-id="ae036-140">Many other settings can also be controlled with these tools, as described throughout this document.</span><span class="sxs-lookup"><span data-stu-id="ae036-140">Many other settings can also be controlled with these tools, as described throughout this document.</span></span>
  
### <a name="mobile-device-security-policies-for-exchange-online"></a><span data-ttu-id="ae036-141">Exchange Online에 대한 모바일 장치 보안 정책</span><span class="sxs-lookup"><span data-stu-id="ae036-141">Mobile device security policies for Exchange Online</span></span>

<span data-ttu-id="ae036-142">Exchange Online supports the same ActiveSync policies for mobile devices as Exchange Server 2013.</span><span class="sxs-lookup"><span data-stu-id="ae036-142">Exchange Online supports the same ActiveSync policies for mobile devices as Exchange Server 2013.</span></span> <span data-ttu-id="ae036-143">Administrators can enforce and customize these security policies for specific users and groups by using the EAC or remote Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="ae036-143">Administrators can enforce and customize these security policies for specific users and groups by using the EAC or remote Windows PowerShell.</span></span>
  
### <a name="message-tracking-for-exchange-online"></a><span data-ttu-id="ae036-144">Exchange Online에 대한 메시지 추적</span><span class="sxs-lookup"><span data-stu-id="ae036-144">Message tracking for Exchange Online</span></span>

<span data-ttu-id="ae036-145">배달 보고서 기능을 통한 메시지 추적은 [보고 기능 및 문제 해결 도구](reporting-features-and-troubleshooting-tools.md)항목에 설명 되어 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ae036-145">Message tracking via the Delivery Reports feature is described in the following topic: [Reporting features and troubleshooting tools](reporting-features-and-troubleshooting-tools.md).</span></span>
  
### <a name="usage-reporting-for-exchange-online"></a><span data-ttu-id="ae036-146">Exchange Online에 대한 사용 현황 보고</span><span class="sxs-lookup"><span data-stu-id="ae036-146">Usage reporting for Exchange Online</span></span>

<span data-ttu-id="ae036-147">Administrators can use remote Windows PowerShell to retrieve information about how people in their organizations use the Exchange Online service.</span><span class="sxs-lookup"><span data-stu-id="ae036-147">Administrators can use remote Windows PowerShell to retrieve information about how people in their organizations use the Exchange Online service.</span></span> <span data-ttu-id="ae036-148">Available information includes:</span><span class="sxs-lookup"><span data-stu-id="ae036-148">Available information includes:</span></span>
  
- <span data-ttu-id="ae036-149">조직 내 각 사용자에 대한 사서함 크기 표시.</span><span class="sxs-lookup"><span data-stu-id="ae036-149">Showing the mailbox size for each user in the organization.</span></span>
    
- <span data-ttu-id="ae036-150">사서함에 설정되는 사용자 지정 사용 권한(예: 대리인 액세스 권한) 표시.</span><span class="sxs-lookup"><span data-stu-id="ae036-150">Displaying custom permissions that are set on mailboxes, such as delegate access.</span></span>
    
- <span data-ttu-id="ae036-151">Exchange ActiveSync를 통해 연결 중인 사용자, 이러한 사용자가 사용 중인 장치 및 마지막으로 연결한 시간과 같은 모바일 장치 액세스에 대한 데이터 추출.</span><span class="sxs-lookup"><span data-stu-id="ae036-151">Extracting data about mobile device access, such as which users are connecting through Exchange ActiveSync, what devices they are using, and when they last connected.</span></span>
    
<span data-ttu-id="ae036-152">Remote Windows PowerShell cmdlets that start with "get-" can fetch data from the Exchange Online system.</span><span class="sxs-lookup"><span data-stu-id="ae036-152">Remote Windows PowerShell cmdlets that start with "get-" can fetch data from the Exchange Online system.</span></span> <span data-ttu-id="ae036-153">Administrators can export this information from Windows PowerShell in .csv format for advanced analysis or reporting.</span><span class="sxs-lookup"><span data-stu-id="ae036-153">Administrators can export this information from Windows PowerShell in .csv format for advanced analysis or reporting.</span></span>
  
<span data-ttu-id="ae036-154">Exchange Online에서 사용할 수 있는 Windows PowerShell cmdlet에 대한 자세한 내용은 [Exchange Online cmdlet](https://go.microsoft.com/fwlink/p/?LinkId=271808)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="ae036-154">For more information about Windows PowerShell cmdlets for use with Exchange Online, see [Exchange Online cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).</span></span>
  
### <a name="auditing-for-exchange-online"></a><span data-ttu-id="ae036-155">Exchange Online에 대한 감사</span><span class="sxs-lookup"><span data-stu-id="ae036-155">Auditing for Exchange Online</span></span>

<span data-ttu-id="ae036-156">감사 로깅 기능은 [보고 기능 및 문제 해결 도구](reporting-features-and-troubleshooting-tools.md)항목에 설명 되어 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ae036-156">The audit logging feature is described in the following topic: [Reporting features and troubleshooting tools](reporting-features-and-troubleshooting-tools.md).</span></span>
  
## <a name="service-and-product-upgrades-for-exchange-online"></a><span data-ttu-id="ae036-157">Exchange Online에 대한 서비스 및 제품 업그레이드</span><span class="sxs-lookup"><span data-stu-id="ae036-157">Service and product upgrades for Exchange Online</span></span>

<span data-ttu-id="ae036-158">Exchange Online customers benefit from periodic upgrades to the latest Exchange technology, including new releases of Exchange Server.</span><span class="sxs-lookup"><span data-stu-id="ae036-158">Exchange Online customers benefit from periodic upgrades to the latest Exchange technology, including new releases of Exchange Server.</span></span> <span data-ttu-id="ae036-159">These upgrades are made available at no additional charge, and ensure that customers are always using the latest Exchange software.</span><span class="sxs-lookup"><span data-stu-id="ae036-159">These upgrades are made available at no additional charge, and ensure that customers are always using the latest Exchange software.</span></span>
  
<span data-ttu-id="ae036-160">고객은 Microsoft에서 주요 Exchange 버전을 릴리스한 후 12개월 이내에 서비스를 새 릴리스로 업그레이드할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ae036-160">After a major version of Exchange is released by Microsoft, customers have up to 12 months to upgrade their service to the new release.</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="ae036-161">기능 가용성</span><span class="sxs-lookup"><span data-stu-id="ae036-161">Feature availability</span></span>

<span data-ttu-id="ae036-162">계획, 독립 실행형 옵션 및 온-프레미스 솔루션 별로 기능 가용성을 확인 하려면 [Exchange Online 서비스 설명을](exchange-online-service-description.md)참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="ae036-162">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online service description](exchange-online-service-description.md).</span></span>
  