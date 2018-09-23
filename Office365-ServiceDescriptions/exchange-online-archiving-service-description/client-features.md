---
title: Exchange Online Archiving의 클라이언트 기능
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- clients-and-devices-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c8d5f97a-607f-4949-a4f7-0b9e3b246851
description: Microsoft Exchange Online 보관 사용자가 다양 한 장치 및 플랫폼에서에서 보관 사서함에 연결할 수 있습니다. 인터넷을 통해 사용자의 보관을 모든 네트워크 연결에 발생 하 고 가상 사설망 (VPN) 연결이 필요 하지 않습니다. 조직에서는 사용자가 VPN 연결을 요구 하지 않고 사용 하면 외부에서 Outlook 사용을 통해 기본 사서함에 액세스할 수 있도록 온-프레미스 클라이언트 액세스 서버를 게시할 수 있습니다. VPN 액세스 온-프레미스 서버에 있는 사용자의 기본 사서함에 액세스 해야하는 경우에이 요구 사항이 변경 되지 않습니다.
ms.openlocfilehash: 90f384e990363294c8972a79e8b500d97ca4a839
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036443"
---
# <a name="client-features-in-exchange-online-archiving"></a><span data-ttu-id="8d38b-106">Exchange Online Archiving의 클라이언트 기능</span><span class="sxs-lookup"><span data-stu-id="8d38b-106">Client Features in Exchange Online Archiving</span></span>

<span data-ttu-id="8d38b-p102">Microsoft Exchange Online 보관 사용자가 다양 한 장치 및 플랫폼에서에서 보관 사서함에 연결할 수 있습니다. 인터넷을 통해 사용자의 보관을 모든 네트워크 연결에 발생 하 고 가상 사설망 (VPN) 연결이 필요 하지 않습니다. 조직에서는 사용자가 VPN 연결을 요구 하지 않고 사용 하면 외부에서 Outlook 사용을 통해 기본 사서함에 액세스할 수 있도록 온-프레미스 클라이언트 액세스 서버를 게시할 수 있습니다. VPN 액세스 온-프레미스 서버에 있는 사용자의 기본 사서함에 액세스 해야하는 경우에이 요구 사항이 변경 되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="8d38b-p102">Microsoft Exchange Online Archiving enables users to connect to their archive mailboxes from a variety of devices and platforms. All network connectivity to the user's archive occurs over the Internet, and virtual private network (VPN) connections are not required. Organizations can publish an on-premises Client Access server to allow users to access their primary mailbox using Outlook Anywhere, without requiring a VPN connection. If VPN access is required to access the user's primary mailbox located on an on-premises server, this requirement does not change.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="8d38b-111">Microsoft는 Exchange Online Archiving 서비스 상태를 악화시키는 모든 클라이언트 소프트웨어로부터의 연결을 차단하거나 제한할 수 있는 권한을 보유합니다.</span><span class="sxs-lookup"><span data-stu-id="8d38b-111">Microsoft reserves the right to block or throttle connections from any client software that negatively impacts the health of the Exchange Online Archiving service.</span></span> 
  
## <a name="microsoft-outlook"></a><span data-ttu-id="8d38b-112">Microsoft Outlook</span><span class="sxs-lookup"><span data-stu-id="8d38b-112">Microsoft Outlook</span></span>

<span data-ttu-id="8d38b-p103">Microsoft Outlook은 일정, 연락처 및 작업을 지원하는 기능이 포함된 유용한 전자 메일 프로그램입니다. Exchange Online Archiving에서는 Outlook 2013, Outlook 2010 및 Outlook 2007을 지원합니다. 주요 기능은 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="8d38b-p103">Microsoft Outlook is a rich email program that includes support for calendaring, contacts, and tasks. Exchange Online Archiving supports Outlook 2013, Outlook 2010, and Outlook 2007. Key features include:</span></span>
  
- <span data-ttu-id="8d38b-p104">**외부에서 Outlook 사용** Outlook 사용자는 외부에서 Outlook 사용 를 통해 VPN 연결을 사용하지 않고도 인터넷에서 Exchange Server와 Exchange Online Archiving에 연결할 수 있습니다. Outlook과 Exchange Online Archiving 간의 통신은 RPC-over-HTTP Windows 네트워킹 구성 요소를 사용하여 SSL 보안 터널을 통해 수행됩니다.</span><span class="sxs-lookup"><span data-stu-id="8d38b-p104">**Outlook Anywhere** Outlook Anywhere lets Outlook users connect to Exchange Server and Exchange Online Archiving over the Internet with no need for a VPN connection. Communication between Outlook and Exchange Online Archiving occurs via an SSL-secured tunnel, using the RPC-over-HTTP Windows networking component.</span></span> 
    
- <span data-ttu-id="8d38b-p105">**자동 검색** Exchange 자동 검색 서비스는 Outlook을 Exchange Online Archiving과 함께 자동으로 작동하도록 구성합니다. Outlook 사용자는 자동 검색을 통해 전자 메일 주소와 암호로 처음 로그인할 때, 필요한 프로필 설정을 Exchange에서 직접 받을 수 있습니다. 첫 로그인 이후에는 설정이 일정한 간격으로 수신됩니다.</span><span class="sxs-lookup"><span data-stu-id="8d38b-p105">**Autodiscover** The Exchange Autodiscover service automatically configures Outlook to work with Exchange Online Archiving. Autodiscover enables Outlook users to receive their required profile settings directly from Exchange the first time (and at fixed intervals thereafter) that they sign in with their email address and password.</span></span> 
    
<span data-ttu-id="8d38b-120">Outlook 2010 이상 버전과 Outlook Web App에서는 사용자에게 보관 사서함의 모든 기능은 물론 보존 및 보관 정책과 같은 관련 기능도 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="8d38b-120">Outlook 2010 and later and Outlook Web App provide users with the full features of the archive, as well as related features like retention and archive policies.</span></span>
  
<span data-ttu-id="8d38b-p106">Outlook 2007은 보관 사서함을 기본적으로 지원하지만 일부 보관 및 규정 준수 기능은 Outlook 2007에서 사용할 수 없습니다. 예를 들어 Outlook 2007에서는 사용자가 사서함의 항목에 보존 또는 보관 정책을 적용할 수 없습니다. 그 대신에 관리자가 프로비저닝한 정책을 사용해야 합니다. Outlook 2007 사용자의 경우 보관 사서함에 액세스하려면 2011년 2월 Office 2007 누적 업데이트가 필요합니다.</span><span class="sxs-lookup"><span data-stu-id="8d38b-p106">Outlook 2007 provides basic support for the archive, but not all archiving and compliance features are available in Outlook 2007. For example, with Outlook 2007, users cannot apply retention or archive policies to items in their mailboxes. They must rely on administrator-provisioned policies instead. Outlook 2007 users require the Office 2007 Cumulative Update for February 2011 to access the archive.</span></span>
  
> [!NOTE]
> <span data-ttu-id="8d38b-p107">Exchange Online Archiving에서는 Outlook이 제공되지 않습니다. 일부 Office 365 계획에는 Microsoft Office 365 ProPlus(Microsoft Outlook 포함)가 포함되어 있고, 별도의 구독을 구입할 수도 있습니다. 자세한 내용은 [Office 365 계획 옵션](../office-365-platform-service-description/office-365-plan-options.md)을 참조하세요. Office 365 ProPlus에 대한 자세한 내용은 [Office 응용 프로그램 서비스 설명](../office-applications-service-description/office-applications-service-description.md)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="8d38b-p107">Outlook is not provided with Exchange Online Archiving. Microsoft Office 365 ProPlus (which includes Microsoft Outlook) is included in some Office 365 plans and can be purchased as a separate subscription. For more information, see [Office 365 Plan Options](../office-365-platform-service-description/office-365-plan-options.md). For more information about Office 365 ProPlus, see the [Office Applications Service Description](../office-applications-service-description/office-applications-service-description.md).</span></span> 
  
### <a name="clients-supported-by-exchange-online-archiving"></a><span data-ttu-id="8d38b-129">Exchange Online Archiving에서 지원하는 클라이언트</span><span class="sxs-lookup"><span data-stu-id="8d38b-129">Clients supported by Exchange Online Archiving</span></span>

<span data-ttu-id="8d38b-130">아래 표에는 Exchange Online Archiving에서 지원하는 클라이언트가 나와 있습니다.</span><span class="sxs-lookup"><span data-stu-id="8d38b-130">The table below lists the clients supported by Exchange Online Archiving:</span></span>
  
|<span data-ttu-id="8d38b-131">**클라이언트**</span><span class="sxs-lookup"><span data-stu-id="8d38b-131">**Client**</span></span>|<span data-ttu-id="8d38b-132">**EOA 지원**</span><span class="sxs-lookup"><span data-stu-id="8d38b-132">**EOA Support**</span></span>|
|:-----|:-----|
|<span data-ttu-id="8d38b-133">Outlook 2010 이상</span><span class="sxs-lookup"><span data-stu-id="8d38b-133">Outlook 2010 and later</span></span>  <br/> |<span data-ttu-id="8d38b-134">Exchange Online Archiving의 최신 기능 지원<sup>1</sup></span><span class="sxs-lookup"><span data-stu-id="8d38b-134">Supports the latest features in Exchange Online Archiving.<sup>1</sup></span></span> <br/> |
|<span data-ttu-id="8d38b-135">Outlook 2007</span><span class="sxs-lookup"><span data-stu-id="8d38b-135">Outlook 2007</span></span>  <br/> |<span data-ttu-id="8d38b-136">Exchange Online Archiving과 함께 사용할 수 있도록 지원<sup>1,2</sup></span><span class="sxs-lookup"><span data-stu-id="8d38b-136">Supported for use with Exchange Online Archiving.<sup>1,2</sup></span></span> <br/> |
|<span data-ttu-id="8d38b-137">Outlook 2003</span><span class="sxs-lookup"><span data-stu-id="8d38b-137">Outlook 2003</span></span>  <br/> |<span data-ttu-id="8d38b-138">지원되지 않음</span><span class="sxs-lookup"><span data-stu-id="8d38b-138">Not supported</span></span>  <br/> |
|<span data-ttu-id="8d38b-139">Outlook for Mac 2011</span><span class="sxs-lookup"><span data-stu-id="8d38b-139">Outlook for Mac 2011</span></span>  <br/> |<span data-ttu-id="8d38b-140">지원되지 않음</span><span class="sxs-lookup"><span data-stu-id="8d38b-140">Not supported</span></span>  <br/> |
|<span data-ttu-id="8d38b-141">Outlook for Mac</span><span class="sxs-lookup"><span data-stu-id="8d38b-141">Outlook for Mac</span></span>  <br/> |<span data-ttu-id="8d38b-142">Exchange Online 보관에 사용 하기 위한 지원 합니다. <sup>3</sup></span><span class="sxs-lookup"><span data-stu-id="8d38b-142">Supported for use with Exchange Online Archiving.<sup>3</sup></span></span> <br/> |
|<span data-ttu-id="8d38b-143">Microsoft Office Entourage 2008 Web Services Edition</span><span class="sxs-lookup"><span data-stu-id="8d38b-143">Microsoft Office Entourage 2008 Web Services Edition</span></span>  <br/> |<span data-ttu-id="8d38b-144">지원되지 않음</span><span class="sxs-lookup"><span data-stu-id="8d38b-144">Not supported</span></span>  <br/> |
|<span data-ttu-id="8d38b-145">IMAP 및 POP</span><span class="sxs-lookup"><span data-stu-id="8d38b-145">IMAP and POP</span></span>  <br/> |<span data-ttu-id="8d38b-146">지원되지 않음</span><span class="sxs-lookup"><span data-stu-id="8d38b-146">Not supported</span></span>  <br/> |
|<span data-ttu-id="8d38b-147">Exchange ActiveSync(모바일 장치)</span><span class="sxs-lookup"><span data-stu-id="8d38b-147">Exchange ActiveSync (Mobile devices)</span></span>  <br/> |<span data-ttu-id="8d38b-148">지원되지 않음</span><span class="sxs-lookup"><span data-stu-id="8d38b-148">Not supported</span></span>  <br/> |
   
> [!NOTE]
> <span data-ttu-id="8d38b-p108"><sup>1</sup> 에 포함 된 Microsoft Office 표준 outlook 지원 되지 않습니다. 자세한 내용을 보려면, [개인 보관 함 및 보존 정책에 대 한 라이선스 요구 사항](https://go.microsoft.com/fwlink/?LinkId=389396)을 참조 하십시오. > <sup>2</sup> 보관 지원을 활성화 하려면 업데이트를 설치 해야 합니다. Outlook 2007 사용자 수는 없습니다 보기 또는 보존을 적용 또는 보관 보관 사서함;의 항목에 대 한 정책 관리자가 프로 비전 정책에 의존 합니다. 또한 Outlook 2007 사용자는 온-프레미스 사서함과 동시에 보관 파일을 검색할 수 없습니다. > <sup>3</sup> 를 사용 하 여 Outlook 2016 Mac 또는 Mac에 대 한 Outlook에 대 한 이동 또는 복사 폴더, 일정 항목, 연락처, 작업 또는 슬라이드 노트에서 보관을 또는 항목은 Outlook (다른 버전을 사용 하 여 이전에 이동 된 경우 보관 사서함에서 볼 수는 없습니다 같은 Outlook 2016 Windows 용). 자세한 내용은 [Mac 용 Outlook 2016와 온라인 보관 사용](https://support.office.com/en-us/article/Use-your-online-archive-with-Outlook-2016-for-Mac-45b8439c-2982-4b6b-9097-eed71dbfe238)을 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="8d38b-p108"><sup>1</sup> Outlook included with Microsoft Office Standard is not supported. To learn more, see [License requirements for Personal Archive and retention policies](https://go.microsoft.com/fwlink/?LinkId=389396). > <sup>2</sup> Requires update to enable archiving support. Outlook 2007 users cannot view or apply retention or archive policies to items in their archive mailboxes; they must rely on administrator-provisioned policies. Additionally, Outlook 2007 users cannot search the on-premises mailbox and the archive at the same time. > <sup>3</sup> You can't use Outlook 2016 for Mac or Outlook for Mac to move or copy folders, calendar items, contacts, tasks, or notes to your archive, or view them in the archive mailbox, if the items were previously moved there by using any other version of Outlook (such as Outlook 2016 for Windows). For more information, see [Use your online archive with Outlook 2016 for Mac](https://support.office.com/en-us/article/Use-your-online-archive-with-Outlook-2016-for-Mac-45b8439c-2982-4b6b-9097-eed71dbfe238).</span></span> 
  
## <a name="outlook-web-app"></a><span data-ttu-id="8d38b-156">Outlook Web App</span><span class="sxs-lookup"><span data-stu-id="8d38b-156">Outlook Web App</span></span>

<span data-ttu-id="8d38b-p109">Outlook Web App은 Exchange Online과 함께 사용되는 웹 기반 버전의 Outlook 전자 메일 프로그램입니다. 사용자는 인터넷에 연결하는 위치(집, 사무실, 외부)에 관계없이 어디서나 Outlook Web App을 통해 전자 메일에 액세스할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="8d38b-p109">Outlook Web App is a web-based version of the Outlook email program that is used with Exchange Online. Wherever users are connected to the Internet—at home, at the office, or on the road—they can access their email through Outlook Web App.</span></span>
  
<span data-ttu-id="8d38b-p110">사용자는 온-프레미스에서 같은 URL을 사용하여 Outlook Web App에 로그인해 보관 사서함에 액세스할 수 있습니다. 보관 사서함은 Outlook Web App에서 기본 사서함 옆에 표시됩니다. Outlook Web App에서 보관 사서함에 직접 액세스하는 명시적인 방법은 없습니다.</span><span class="sxs-lookup"><span data-stu-id="8d38b-p110">Users can access their archive by signing in to Outlook Web App on-premises (using the same URL). The archive appears alongside their primary mailbox in Outlook Web App. There is no explicit way to access the archive directly from Outlook Web App.</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="8d38b-162">기능 가용성</span><span class="sxs-lookup"><span data-stu-id="8d38b-162">Feature Availability</span></span>

<span data-ttu-id="8d38b-163">Office 365 계획, 독립 실행형 옵션 및 온-프레미스 솔루션별로 기능 가용성을 확인하려면 [Exchange Online Archiving 서비스 설명](exchange-online-archiving-service-description.md)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="8d38b-163">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Archiving Service Description](exchange-online-archiving-service-description.md).</span></span>
  

