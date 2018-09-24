---
title: 클라이언트 및 모바일 장치
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-clients-and-mobile-devices
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: fce4ac03-f30a-4152-9145-4a9ce564c966
ms.openlocfilehash: ad19845f7a06cfb01a74507fdb794813091c1c2b
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036590"
---
# <a name="clients-and-mobile-devices"></a><span data-ttu-id="2d4a1-102">클라이언트 및 모바일 장치</span><span class="sxs-lookup"><span data-stu-id="2d4a1-102">Clients and Mobile Devices</span></span>

## <a name="microsoft-outlook"></a><span data-ttu-id="2d4a1-103">Microsoft Outlook</span><span class="sxs-lookup"><span data-stu-id="2d4a1-103">Microsoft Outlook</span></span>

<span data-ttu-id="2d4a1-104">Microsoft Outlook 일정, 연락처, 작업 및 다음과 같은 주요 기능에 대 한 지원을 포함 하는 전자 메일 프로그램은:</span><span class="sxs-lookup"><span data-stu-id="2d4a1-104">Microsoft Outlook is an email program that includes support for calendar, contacts, tasks, and the following key features:</span></span>
  
- <span data-ttu-id="2d4a1-p101">**HTTP 통한 MAPI** 응용 프로그램 인터페이스) MAPI (messaging HTTP를 통한 Outlook 사용자가 조직의 방화벽 외부에서 인터넷을 통해 Exchange Online 사서함에 연결할 수 있습니다. MAPI over HTTP 외부에서 Outlook 사용에 대 한 장기 대체 합니다. 이 연결 방법은 제공 향상 된 연결 복구, 보안을 강화 로그인, 확장성, 향상과 함께 대 한 IT 및 지원 합니다. 자세한 내용은, [RPC over HTTP에는 Office 365의 지원의 끝에 도달](https://go.microsoft.com/fwlink/?linkid=863890) 하 고 [HTTP 통한 MAPI](https://go.microsoft.com/fwlink/?linkid=393041)를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="2d4a1-p101">**MAPI over HTTP** Messaging Application Program Interface (MAPI) over HTTP allows Outlook users to connect to Exchange Online mailboxes over the Internet from outside their organization's firewall. MAPI over HTTP, the long term replacement for Outlook Anywhere. This connectivity method offers improved connection resiliency, more secure sign-in, extensibility, as well as enhancements for IT and support. To learn more, see [RPC over HTTP reaches end of support in Office 365](https://go.microsoft.com/fwlink/?linkid=863890) and [MAPI over HTTP](https://go.microsoft.com/fwlink/?linkid=393041).</span></span>
    
- <span data-ttu-id="2d4a1-p102">**자동 검색** 자동 검색 서비스 기능은 자동으로 Outlook을 Exchange Online과 함께 작동하도록 구성합니다. Outlook 사용자는 처음 전자 메일 주소와 암호를 통해 로그인했을 때 Exchange Online에서 바로 필요한 프로필 설정을 받을 수 있습니다. 이러한 설정은 사용자의 프로필을 만들고 유지하는 데 필요한 정보를 가지고 Outlook 클라이언트를 자동으로 업데이트합니다. 자동 검색 서비스를 사용하려면 SSL 인증서를 필요합니다. 이 SSL 인증서는 하나의 기본 SSL 도메인으로 제한됩니다.</span><span class="sxs-lookup"><span data-stu-id="2d4a1-p102">**Autodiscover** The Autodiscover service feature automatically configures Outlook to work with Exchange Online. Outlook users can receive their required profile settings directly from Exchange Online the first time they sign in with their email address and password. These settings automatically update the Outlook client with the information necessary to create and maintain the user's profile. An SSL certificate is required to use the Autodiscover service. This SSL certificate is limited to a single primary SSL domain.</span></span> 
    
- <span data-ttu-id="2d4a1-p103">**캐시된 Exchange 모드** 캐시된 Exchange 모드 기능을 통해 Outlook 사용자는 인터넷에 연결되지 않은 상태일 경우 Exchange Online 사서함의 로컬 사본에 액세스할 수 있습니다. 캐시된 Exchange 모드는 Outlook에 사용자 Exchange 사서함의 클라이언트 쪽 사본을 유지하여 자동으로 이 사본을 전자 메일 서버와 동기화합니다. 캐시된 Exchange 모드는 오프라인 액세스를 제공하고 클라이언트와 서버 간 네트워크 환경이 좋지 않은 경우에도 응답성이 좋은 사용자 환경을 제공합니다. 따라서 Outlook은 캐시된 Exchange 모드에서 사용하는 것이 좋습니다.</span><span class="sxs-lookup"><span data-stu-id="2d4a1-p103">**Cached Exchange Mode** The Cached Exchange Mode feature allows Outlook users to access local copies of their Exchange Online mailboxes when they are not connected to the Internet. Cached Exchange Mode retains a client-side copy of users' Exchange mailboxes in Outlook and automatically synchronizes this copy with the email server. We recommend using Outlook in Cached Exchange Mode because it provides offline access and helps to provide a responsive user experience even when network conditions between the client and the server are not ideal.</span></span> 
    
<span data-ttu-id="2d4a1-p104">기본적으로 Outlook 액세스는 모든 사용자에 대해 사용하도록 설정되어 있습니다. 관리자는 Windows Powershell을 통해 특정 사용자 또는 그룹의 액세스를 사용하지 않도록 설정할 수 있습니다. Exchange Online에 액세스하려면 최신 서비스 팩이 설치된 Outlook 최신 버전을 사용하는 것이 좋습니다.</span><span class="sxs-lookup"><span data-stu-id="2d4a1-p104">By default, Outlook access is enabled for all users. Administrators can disable access for specific users or groups through Windows PowerShell. We recommend using the latest version of Outlook—with the latest service pack installed—to access Exchange Online.</span></span> 
  
<span data-ttu-id="2d4a1-120">Exchange 2016 및 Exchange Online에서 지원되는 Outlook 클라이언트에 대한 자세한 내용은 [Exchange 2016 시스템 요구 사항](https://go.microsoft.com/fwlink/?LinkID=828972)에서 "지원되는 클라이언트"를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="2d4a1-120">For information about which Outlook clients are supported by Exchange 2016 and Exchange Online, see "Supported clients" in [Exchange 2016 system requirements](https://go.microsoft.com/fwlink/?LinkID=828972).</span></span>
  
> [!IMPORTANT]
>  <span data-ttu-id="2d4a1-p105">Outlook은 Exchange Online 구독 가격에 포함되어 제공되지 않습니다. 일부 Office 365 계획에는 Microsoft Office Pro Plus(Microsoft Outlook 포함)가 포함되어 있으며, 별도의 구독을 구매할 수도 있습니다. >  POP을 사용해서 Exchange Online 전자 메일 계정에 연결하면 다음 제한 사항이 표시됩니다. >  일정 정보 없음 >  약속 있음/없음 정보 없음 >  전체 주소 목록 없음 >  전자 메일 푸시 없음 >  POP를 통해 연결하면 모든 메시지가 클라이언트로 다운로드되며, 여러 컴퓨터 또는 장치 간에 동기화가 수행되지 않습니다(예: 랩톱과 전화 간).</span><span class="sxs-lookup"><span data-stu-id="2d4a1-p105">Outlook is not provided as part of the Exchange Online subscription price. Microsoft Office Pro Plus (which includes Microsoft Outlook) is included in some Office 365 plans and can be purchased as a separate subscription. >  You will see the following limitations if you use POP to connect to an Exchange Online email account: >  No calendar information >  No free/busy information >  No Global Address List >  No push email >  When connecting through POP, all messages will be downloaded to the client and there will be no synchronization between multiple computers or devices (such as between a laptop and a phone).</span></span> 
  
## <a name="outlook-on-the-web"></a><span data-ttu-id="2d4a1-124">웹에서 Outlook</span><span class="sxs-lookup"><span data-stu-id="2d4a1-124">Outlook on the web</span></span>

<span data-ttu-id="2d4a1-p106">웹상의 Outlook은 웹 기반 버전의 Outlook 전자 메일 프로그램으로 Exchange Online과 함께 사용됩니다. 사용자는 인터넷이 연결된 곳이라면 어디서나 웹 브라우저를 통해 전자 메일, 일정, 연락처에 액세스할 수 있습니다. 지원되는 브라우저에 대한 자세한 내용은 [비즈니스용 웹상의 Outlook에 대해 지원되는 브라우저](https://go.microsoft.com/fwlink/p/?LinkId=287032)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="2d4a1-p106">Outlook on the web is a web-based version of the Outlook email program that is used with Exchange Online. It enables users to access their email, calendar, and contacts through a web browser from wherever they connect to the Internet. For information about supported browsers, see [Supported browsers for Outlook on the web for business](https://go.microsoft.com/fwlink/p/?LinkId=287032).</span></span>
  
<span data-ttu-id="2d4a1-128">웹상의 Outlook에는 2가지 클라이언트 버전이 있으며, 모두 Exchange Online과 함께 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2d4a1-128">Outlook on the web comes in two client versions, both of which can be used with Exchange Online:</span></span>
  
- <span data-ttu-id="2d4a1-p107">**웹상의 Outlook** 웹상의 Outlook 표준 버전으로 Exchange Online 사용자에게 Outlook 사용자와 가장 유사한 메시지 환경을 제공합니다. 대부분의 최신 웹 브라우저를 지원하며 데스크톱 및 랩톱 뿐만 아니라 태블릿 및 스마트폰 사용에 최적화되어 있습니다. 사용자는 메시지 읽기 및 보내기, 연락처 구성, 약속 및 모임 예약 등의 작업을 수행할 수 있습니다. 기본 작업 기반 시간 제한은 6시간으로 설정되지만 [Windows PowerShell에서 관리자가 5분에서 8시간 사이로 구성](https://go.microsoft.com/fwlink/p/?LinkId=399155)할 수 있습니다. 이 시간 제한은 단추 클릭이나 메시지 선택 등 웹 응용 프로그램 내 사용자 상호 작용에 따라 달라집니다. 또한 구성할 수 없으며 사용자 작업에 상관없이 발생하는 별도의 보안 기반 시간 제한도 있습니다. 사용자가 8시간 동안 로그인되어 있는 경우 OWA는 사용자를 자동으로 로그아웃하고 다시 인증하라는 메시지를 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="2d4a1-p107">**Outlook on the web** The standard version of Outlook on the web provides Exchange Online users with a messaging experience most similar to that of Outlook users. It supports most newer web browsers and is optimized for use on tablets and smartphones as well as desktops and laptops. Users can read and send messages, organize contacts, and schedule appointments and meetings. The default activity-based time-out is set at six hours, but it can be [configured by an administrator in Windows PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=399155) from 5 minutes to 8 hours. This time-out depends on user interactions within the web app, such as clicking a button or selecting a message. There is also a separate security-driven time-out, which is not configurable and will occur regardless of user activity. If a user is logged in for 8 hours, OWA will automatically log the user out and ask for re-authentication.</span></span> 
    
- <span data-ttu-id="2d4a1-p108">**웹상의 Outlook 라이트 버전** 웹상의 Outlook 라이트 버전은 Exchange Online 사용자에게 거의 모든 웹 브라우저를 통한 사서함 액세스를 제공합니다. 사용자는 메시지 읽기 및 보내기, 연락처 구성, 약속 및 모임 예약 등의 작업을 수행할 수 있습니다. 기본 작업 기반 시간 제한은 6시간으로 설정되지만 [Windows PowerShell에서 관리자가 5분에서 8시간 사이로 구성](https://go.microsoft.com/fwlink/p/?LinkId=399155)할 수 있습니다. 이 시간 제한은 단추 클릭이나 메시지 선택 등 웹 응용 프로그램 내 사용자 상호 작용에 따라 달라집니다. 또한 구성할 수 없으며 사용자 작업에 상관없이 발생하는 별도의 보안 기반 시간 제한도 있습니다. 사용자가 8시간 동안 로그인되어 있는 경우 라이트 버전의 OWA는 사용자를 자동으로 로그아웃하고 다시 인증하라는 메시지를 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="2d4a1-p108">**The light version of Outlook on the web** The light version of Outlook on the web provides Exchange Online users access to the mailbox using almost any web browser. Users can read and send messages, organize contacts, and schedule appointments and meetings. The default activity-based time-out is set at six hours, but it can be [configured by an administrator in Windows PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=399155) from 5 minutes to 8 hours. This time-out depends on user interactions within the web app, such as clicking a button or selecting a message. There is also a separate security-driven time-out, which is not configurable and will occur regardless of user activity. If a user is logged in for 8 hours, the light version of OWA will automatically log the user out and ask for re-authentication.</span></span> 
    
<span data-ttu-id="2d4a1-p109">웹상의 Outlook은 모바일 버전으로도 사용할 수 있습니다. 자세한 내용은 [이 페이지](http://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="2d4a1-p109">Outlook on the web also is available in mobile versions. For more information, see [this page](http://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409).</span></span>
  
## <a name="outlook-for-mac"></a><span data-ttu-id="2d4a1-144">Outlook for Mac</span><span class="sxs-lookup"><span data-stu-id="2d4a1-144">Outlook for Mac</span></span>

<span data-ttu-id="2d4a1-145">Exchange Online 전자 메일, 일정, 주소록, 작업 목록 및 메모 목록을 제공 하는 Mac 용 Microsoft Outlook을 지원 합니다.</span><span class="sxs-lookup"><span data-stu-id="2d4a1-145">Exchange Online supports Microsoft Outlook for Mac, which provides email, calendar, an address book, a task list, and a note list.</span></span>
  
## <a name="outlook-for-ios-android-and-windows-phone"></a><span data-ttu-id="2d4a1-146">IOS, Android, 및 Windows Phone 대 한 outlook</span><span class="sxs-lookup"><span data-stu-id="2d4a1-146">Outlook for iOS, Android, and Windows Phone</span></span>

<span data-ttu-id="2d4a1-p110">Exchange Online iOS, Android, 및 Windows Phone 사용할 수 있는 Outlook apps 작동합니다. 이러한 장치에서 응용 프로그램 저장소를 사용 하 여 Outlook app 파악 합니다. 모바일 운영 체제 하 여 분석 하는 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="2d4a1-p110">Exchange Online works with Outlook apps available for iOS, Android, and Windows Phone. On any of these devices, use the app store to find the Outlook app. Here's a breakdown by mobile OS.</span></span>
  
|||||
|:-----|:-----|:-----|:-----|
|<span data-ttu-id="2d4a1-150">장치</span><span class="sxs-lookup"><span data-stu-id="2d4a1-150">Device</span></span>  <br/> |<span data-ttu-id="2d4a1-151">Android</span><span class="sxs-lookup"><span data-stu-id="2d4a1-151">Android</span></span>  <br/> |<span data-ttu-id="2d4a1-152">iOS</span><span class="sxs-lookup"><span data-stu-id="2d4a1-152">iOS</span></span>  <br/> |<span data-ttu-id="2d4a1-153">Windows Phone</span><span class="sxs-lookup"><span data-stu-id="2d4a1-153">Windows Phone</span></span>  <br/> |
|<span data-ttu-id="2d4a1-154">Outlook 모바일 응용 프로그램 가용성</span><span class="sxs-lookup"><span data-stu-id="2d4a1-154">Outlook mobile app availability</span></span>  <br/> |<span data-ttu-id="2d4a1-155">예</span><span class="sxs-lookup"><span data-stu-id="2d4a1-155">Yes</span></span>  <br/> [<span data-ttu-id="2d4a1-156">Android 용 Outlook 가져오기</span><span class="sxs-lookup"><span data-stu-id="2d4a1-156">Get Outlook for Android</span></span>](https://go.microsoft.com/fwlink/?linkid=863380) <br/> |<span data-ttu-id="2d4a1-157">예</span><span class="sxs-lookup"><span data-stu-id="2d4a1-157">Yes</span></span>  <br/> [<span data-ttu-id="2d4a1-158">IOS에 대 한 Outlook 가져오기</span><span class="sxs-lookup"><span data-stu-id="2d4a1-158">Get Outlook for iOS</span></span>](https://go.microsoft.com/fwlink/?linkid=863382) <br/> |<span data-ttu-id="2d4a1-159">기본 제공</span><span class="sxs-lookup"><span data-stu-id="2d4a1-159">Built-in</span></span>  <br/> |
|<span data-ttu-id="2d4a1-160">Exchange Online과 호환 되는 기본 제공 전자 메일 앱</span><span class="sxs-lookup"><span data-stu-id="2d4a1-160">Built-in email apps compatible with Exchange Online</span></span>  <br/> |<span data-ttu-id="2d4a1-161">Gmail app/삼성 전자 메일 응용 프로그램</span><span class="sxs-lookup"><span data-stu-id="2d4a1-161">Gmail app/Samsung Email app</span></span>  <br/> |<span data-ttu-id="2d4a1-162">iOS 메일 앱</span><span class="sxs-lookup"><span data-stu-id="2d4a1-162">iOS Mail app</span></span>  <br/> |<span data-ttu-id="2d4a1-163">Outlook 메일, 일정, 연락처</span><span class="sxs-lookup"><span data-stu-id="2d4a1-163">Outlook Mail, calendar, contacts</span></span>  <br/> |
|<span data-ttu-id="2d4a1-164">추가 정보</span><span class="sxs-lookup"><span data-stu-id="2d4a1-164">More information</span></span>  <br/> |[<span data-ttu-id="2d4a1-165">Android 모바일 설치</span><span class="sxs-lookup"><span data-stu-id="2d4a1-165">Android mobile setup</span></span>](https://go.microsoft.com/fwlink/?linkid=525632) <br/> |[<span data-ttu-id="2d4a1-166">iPhone 또는 iPad 설치</span><span class="sxs-lookup"><span data-stu-id="2d4a1-166">iPhone or iPad setup</span></span>](https://go.microsoft.com/fwlink/?linkid=396655) <br/> |[<span data-ttu-id="2d4a1-167">Windows Phone 설치</span><span class="sxs-lookup"><span data-stu-id="2d4a1-167">Windows Phone setup</span></span>](https://go.microsoft.com/fwlink/?linkid=831342) <br/> |
   
<span data-ttu-id="2d4a1-168">Exchange Online Blackberry를 포함 한 장치를 함께 사용 하 여 옵션이 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2d4a1-168">There are also options for using Exchange Online with devices, including Blackberry.</span></span>
  
### <a name="feature-availability"></a><span data-ttu-id="2d4a1-169">기능 가용성</span><span class="sxs-lookup"><span data-stu-id="2d4a1-169">Feature availability</span></span>

<span data-ttu-id="2d4a1-p111">Outlook의 신속 하 고 직관적인 전자 메일 및 일정 환경을 유일한 응용 프로그램에서 Office 365의 최상의 기능에 대 한 지원을 제공 되는 동안 현대 모바일 응용 프로그램에서 제공 되는 자신이 사용자에 게 제공 합니다. 사용자에 게 일관 된 경험의 데스크톱에서 모바일을 Office 365 환경에서 전체를 지원 하기 위해 특별히 설계 된 유일한 전자 메일 응용 프로그램은 것입니다. Outlook은 Intune, 엔터프라이즈 모바일 기능 및 보안 및 Exchange 컨트롤 및 사용자 데이터를 안전 하 게 유지 하려면와 통합 됩니다.</span><span class="sxs-lookup"><span data-stu-id="2d4a1-p111">Outlook gives users the fast, intuitive email and calendar experience that they expect from a modern mobile app, while being the only app to provide support for the best features of Office 365. It is the only email app specifically designed to support the full Office 365 experience, giving users a coherent experience from desktop to mobile. Outlook is integrated with Intune, enterprise mobility and security, and Exchange controls to keep data and users safe.</span></span>
  
<span data-ttu-id="2d4a1-173">Outlook에서는 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2d4a1-173">Outlook enables users to:</span></span>
  
- <span data-ttu-id="2d4a1-174">모바일 장치에서 자신의 전체 하루를 관리 합니다.</span><span class="sxs-lookup"><span data-stu-id="2d4a1-174">Manage their entire day from a mobile device.</span></span>
    
- <span data-ttu-id="2d4a1-175">응용 프로그램 및 별도 및 보안 자신의 작업 및 개인 정보를 유지 하는 동안, 생산성을 높일 수에 필요한 서비스에 연결 합니다.</span><span class="sxs-lookup"><span data-stu-id="2d4a1-175">Connect to the apps and services they need to be productive, while keeping their work and personal information separate and secure.</span></span>
    
<span data-ttu-id="2d4a1-176">IOS, Android에 대 한 Outlook 또는 Windows Phone 용 Outlook에 대 한 Outlook과 함께 사용자가 다음을 수행할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2d4a1-176">With Outlook for iOS, Outlook for Android, or Outlook for Windows Phone, users can:</span></span> 
  
- <span data-ttu-id="2d4a1-177">포커스가 받은 편지함에서 해당 우선순위 중요 한 전자 메일을 활용</span><span class="sxs-lookup"><span data-stu-id="2d4a1-177">Benefit from a focused inbox that priorities important email</span></span>
    
- <span data-ttu-id="2d4a1-178">자신의 고유한 전자 메일 환경에 맞도록 살짝 제스처를 사용자 지정</span><span class="sxs-lookup"><span data-stu-id="2d4a1-178">Customize swipe gestures to match their unique email habits</span></span>
    
- <span data-ttu-id="2d4a1-179">주요 정보를 한눈에 사용할 수 있는 일정에 직접 추가할 수 있는 여행 일정 만들기</span><span class="sxs-lookup"><span data-stu-id="2d4a1-179">Create travel itineraries that can be added directly to the calendar, with key information available at a glance</span></span>
    
- <span data-ttu-id="2d4a1-180">받은 편지함에서 모임 회신 번호입니다.</span><span class="sxs-lookup"><span data-stu-id="2d4a1-180">RSVP to meetings from the inbox.</span></span>
    
- <span data-ttu-id="2d4a1-181">직관적인 아이콘을 사용 하 여 정보를 신속 하 게 처리 하는 데 도움이 되는 전자 메일 및 일정 약속에</span><span class="sxs-lookup"><span data-stu-id="2d4a1-181">Use intuitive icons in email and calendar appointments that help them process information quickly</span></span>
    
- <span data-ttu-id="2d4a1-182">모든 장치에 대해 일관성 있고 친숙 한 Outlook 환경 사용</span><span class="sxs-lookup"><span data-stu-id="2d4a1-182">Use a consistent and familiar Outlook experience across all devices</span></span>
    
- <span data-ttu-id="2d4a1-183">쉽게 실행 하 고 일정에서 Skype 모임에 참가</span><span class="sxs-lookup"><span data-stu-id="2d4a1-183">Easily launch and join Skype meetings from the calendar</span></span>
    
- <span data-ttu-id="2d4a1-184">암호화 된 전자 메일을 제한 된 읽기 및 IRM에 응답</span><span class="sxs-lookup"><span data-stu-id="2d4a1-184">Read and respond to IRM encrypted and protected emails</span></span>
    
- <span data-ttu-id="2d4a1-185">비즈니스용 OneDrive에 저장 된 파일 공유</span><span class="sxs-lookup"><span data-stu-id="2d4a1-185">Share files stored in OneDrive for Business</span></span>
    
- <span data-ttu-id="2d4a1-186">누르는 자동 회신을 설정 합니다.</span><span class="sxs-lookup"><span data-stu-id="2d4a1-186">Set Automatic Replies with a tap</span></span>
    
- <span data-ttu-id="2d4a1-187">보기 및 공유 및 위임 된 일정 관리</span><span class="sxs-lookup"><span data-stu-id="2d4a1-187">View and manage shared and delegated calendars</span></span>
    
- <span data-ttu-id="2d4a1-188">몇 번 누르기를 사용 하 여 자신의 회사의 전체 주소 목록 검색</span><span class="sxs-lookup"><span data-stu-id="2d4a1-188">Search their company's global address list with a few taps</span></span>
    
- <span data-ttu-id="2d4a1-189">동료의 가용성을 확인 하 고 작동 하는 모든 사용자에 대 한 모임 시간을 예약</span><span class="sxs-lookup"><span data-stu-id="2d4a1-189">View coworker's availability and schedule a meeting time that works for everyone</span></span>
    
- <span data-ttu-id="2d4a1-190">초대 수락, 미정 및 상태를 거절를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="2d4a1-190">See invitees accept, tentative, and decline status</span></span>
    
- <span data-ttu-id="2d4a1-191">휴대폰에서 바로 일정 공유</span><span class="sxs-lookup"><span data-stu-id="2d4a1-191">Share calendars right from their phones</span></span>
    
- <span data-ttu-id="2d4a1-192">시작 하 고 일정에서 Skype 모임 오른쪽에 참가</span><span class="sxs-lookup"><span data-stu-id="2d4a1-192">Start and join Skype meetings right from a calendar</span></span>
    
- <span data-ttu-id="2d4a1-193">Access 작업 및 응용 프로그램을 전환 하지 않고도 한곳에서 개인 일정</span><span class="sxs-lookup"><span data-stu-id="2d4a1-193">Access work and personal calendars in one place, without switching apps</span></span>
    
## <a name="exchange-activesync"></a><span data-ttu-id="2d4a1-194">Exchange ActiveSync</span><span class="sxs-lookup"><span data-stu-id="2d4a1-194">Exchange ActiveSync</span></span>

<span data-ttu-id="2d4a1-195">Exchange Online은 모바일 장치와 Exchange Online 간에 사서함 데이터를 동기화하는 Microsoft Exchange ActiveSync 프로토콜을 지원합니다. 따라서 사용자는 자신의 전자 메일, 연락처 및 작업을 이동 중에도 액세스할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2d4a1-195">Exchange Online supports the Microsoft Exchange ActiveSync protocol, which synchronizes mailbox data between mobile devices and Exchange Online, so users can access their email, calendar, contacts, and tasks on the go.</span></span>
  
<span data-ttu-id="2d4a1-p112">다양 한 모바일 장치 Microsoft Windows Phone, Apple iPhone 및 iPad 및 Android 전화 및 태블릿을 비롯 한 Exchange ActiveSync를 사용 합니다. 휴대폰 및 장치 외에도 Windows Phone 메일 응용 프로그램은 Exchange Online에 연결 하려면 Exchange ActiveSync를 사용 합니다. 현재 Exchange ActiveSync 정식 사용자의 전체 목록은 Exchange ActiveSync 라이선스 사이트에서 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2d4a1-p112">A wide range of mobile devices work with Exchange ActiveSync, including Microsoft Windows Phone, Apple iPhone and iPad, and Android phones and tablets. In addition to mobile phones and devices, the Mail application in Windows Phone uses Exchange ActiveSync to connect to Exchange Online. A complete list of current Exchange ActiveSync licensees is available at the Exchange ActiveSync Licensing site.</span></span>
  
<span data-ttu-id="2d4a1-199">Exchange ActiveSync에 대 한 자세한 내용은 [Exchange ActiveSync](https://go.microsoft.com/fwlink/p/?LinkId=271792)를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="2d4a1-199">For more information about Exchange ActiveSync, see [Exchange ActiveSync](https://go.microsoft.com/fwlink/p/?LinkId=271792).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="2d4a1-200">사서함당 Exchange ActiveSync 장치 수는 최대 100개입니다.</span><span class="sxs-lookup"><span data-stu-id="2d4a1-200">The maximum number of Exchange ActiveSync devices per mailbox is 100.</span></span> 
  
## <a name="applications-developed-with-exchange-web-services-ews"></a><span data-ttu-id="2d4a1-201">Exchange 웹 서비스(EWS)로 개발된 응용 프로그램</span><span class="sxs-lookup"><span data-stu-id="2d4a1-201">Applications developed with Exchange Web Services (EWS)</span></span>

 <span data-ttu-id="2d4a1-202">EWS(Exchange 웹 서비스) 또는 EWS Managed API로 개발된 응용 프로그램을 사용하여 관리자는 온-프레미스, Azure 또는 기타 호스트된 서비스에서 실행되는 응용 프로그램에서 Exchange Online에 저장된 데이터에 액세스할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2d4a1-202">Applications developed using Exchange Web Services (EWS) or the EWS Managed API let administrators access data stored with Exchange Online from applications that are running on-premises, in Azure, or in other hosted services.</span></span> 
  
<span data-ttu-id="2d4a1-203">Exchange 웹 서비스로 개발된 응용 프로그램에 대한 자세한 내용은 [Exchange의 웹 서비스](https://go.microsoft.com/fwlink/?LinkId=325346)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="2d4a1-203">For more information on applications developed with Exchange Web Services, see [Web Services in Exchange](https://go.microsoft.com/fwlink/?LinkId=325346).</span></span>
  
## <a name="pop-and-imap"></a><span data-ttu-id="2d4a1-204">POP 및 IMAP</span><span class="sxs-lookup"><span data-stu-id="2d4a1-204">POP and IMAP</span></span>

<span data-ttu-id="2d4a1-p113">Exchange Online은 POP3 및 IMAP4 프로토콜을 통해 사서함 액세스를 지원합니다. POP 및 IMAP 액세스에는 SSL를 사용한 암호화가 필요합니다. POP는 기본적으로 모든 사용자에 대해 사용하도록 설정되어 있습니다. 사용자는 자신의 POP 및 IMAP 연결 설정을 웹상의 Outlook에서 볼 수 있습니다. 관리자는 POP 및 IMAP 액세스를 각 사용자별로 사용하지 않도록 설정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2d4a1-p113">Exchange Online supports mailbox access through both POP3 and IMAP4 protocols. POP and IMAP access requires encryption using SSL. POP is enabled by default for all users. Users can view their POP and IMAP connection settings in Outlook on the web. Administrators can disable POP and IMAP access on a per-user basis.</span></span>
  
<span data-ttu-id="2d4a1-210">POP3 및 IMAP4 연결에 대한 자세한 내용은 [POP3 및 IMAP4](https://go.microsoft.com/fwlink/p/?LinkId=272070)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="2d4a1-210">For more information about POP3 and IMAP4 connectivity, see [POP3 and IMAP4](https://go.microsoft.com/fwlink/p/?LinkId=272070).</span></span>
  
## <a name="smtp"></a><span data-ttu-id="2d4a1-211">SMTP</span><span class="sxs-lookup"><span data-stu-id="2d4a1-211">SMTP</span></span>

<span data-ttu-id="2d4a1-p114">SMTP(Simple Mail Transfer Protocol)은 IMAP 또는 POP를 통해 Exchange Online에 연결하는 클라이언트의 아웃바운드 메일을 보내는 데 사용됩니다. Exchange Server를 통한 배달 및 라우팅의 기본 프로토콜입니다. Exchange Online은 SMTP 메일 전송에 필요한 승인된 내부 고객 응용 프로그램에 대해 2가지 유형의 SMTP 릴레이 서비스를 지원합니다.</span><span class="sxs-lookup"><span data-stu-id="2d4a1-p114">Simple Mail Transfer Protocol (SMTP) is used to send outbound mail for clients that connect to Exchange Online through IMAP or POP. It is the primary protocol for routing and delivery through Exchange Server. Exchange Online supports two types of SMTP relay services for authorized internal customer applications that require SMTP mail submission:</span></span>
  
- <span data-ttu-id="2d4a1-215">관리 환경 내부 사용자에 대한 SMTP 메시지 전송.</span><span class="sxs-lookup"><span data-stu-id="2d4a1-215">SMTP message submission to users inside the managed environment.</span></span>
    
- <span data-ttu-id="2d4a1-216">관리 환경 외부의 주소에 대한 인증된 SMTP 메시지 릴레이.</span><span class="sxs-lookup"><span data-stu-id="2d4a1-216">Authenticated SMTP message relay to addresses outside the managed environment.</span></span>
    
> [!IMPORTANT]
> <span data-ttu-id="2d4a1-p115">SMTP 릴레이를 허용하려면 승인된 원본 서버에 대한 IP 주소가 필요합니다. SMTP를 사용해 전자 메일을 보낼 때는 전송 계층 보안(TLS) 암호화 및 인증이 필요합니다.</span><span class="sxs-lookup"><span data-stu-id="2d4a1-p115">IP addresses for authorized source servers are required to allow SMTP relay. Transport Layer Security (TLS) encryption and authentication is required when using SMTP to send email.</span></span> 
  
## <a name="blackberry-devices"></a><span data-ttu-id="2d4a1-219">BlackBerry® 장치</span><span class="sxs-lookup"><span data-stu-id="2d4a1-219">BlackBerry® devices</span></span>

<span data-ttu-id="2d4a1-p116">Office 365 전자 메일은 Exchange ActiveSync를 통해 BlackBerry® 장치에서 사용할 수 있습니다. 옵션 이란를 찾으려면 다음이 항목을 참조 합니다.</span><span class="sxs-lookup"><span data-stu-id="2d4a1-p116">Office 365 email is available on BlackBerry® devices via Exchange ActiveSync. To find out what your options are, see these topics:</span></span>
  
- [<span data-ttu-id="2d4a1-222">BlackBerry 장치에서 전자 메일 설정</span><span class="sxs-lookup"><span data-stu-id="2d4a1-222">Set up email on a BlackBerry device</span></span>](https://go.microsoft.com/fwlink/?linkid=863394)
    
- [<span data-ttu-id="2d4a1-223">BlackBerry 장치 7.1에서 전자 메일 설정 운영 체제 및 이전 버전</span><span class="sxs-lookup"><span data-stu-id="2d4a1-223">Set up email on a BlackBerry device 7.1 OS and earlier</span></span>](https://go.microsoft.com/fwlink/?linkid=863403)
    
<span data-ttu-id="2d4a1-224">자세한 내용은 [BlackBerry](../office-365-platform-service-description/blackberry.md)를 참고하세요.</span><span class="sxs-lookup"><span data-stu-id="2d4a1-224">For more information, see [BlackBerry](../office-365-platform-service-description/blackberry.md).</span></span>
  
> [!NOTE]
> <span data-ttu-id="2d4a1-p117">중국의 21Vianet에서 운영하는 Office 365를 사용하는 경우 BlackBerry Business Cloud Services를 사용할 수 없지만 Exchange ActiveSync 장치 또는 RIM(Research in Motion, BlackBerry 무선 전자 메일 솔루션)의 기능을 사용하여 BES(Blackberry Enterprise Server)를 실행할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2d4a1-p117">If you are using Office 365 operated by 21Vianet in China, BlackBerry Business Cloud Services is not available. However, you can use Exchange ActiveSync devices or an offering from Research in Motion (RIM, the BlackBerry wireless email solution) to run Blackberry Enterprise Server (BES).</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="2d4a1-227">기능 가용성</span><span class="sxs-lookup"><span data-stu-id="2d4a1-227">Feature Availability</span></span>

<span data-ttu-id="2d4a1-228">Office 365 계획, 독립 실행형 옵션 및 온-프레미스 솔루션별로 기능 가용성을 확인하려면 [Exchange Online 서비스 설명](exchange-online-service-description.md)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="2d4a1-228">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  
