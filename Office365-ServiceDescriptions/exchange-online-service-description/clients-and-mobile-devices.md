---
title: 클라이언트 및 모바일 장치
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-clients-and-mobile-devices
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: fce4ac03-f30a-4152-9145-4a9ce564c966
description: Exchange Online은 데스크톱 및 모바일 버전의 Outlook 및 웹용 Outlook 에서도 작동 합니다.
ms.openlocfilehash: 32fb8ee9124a805233daaab2968158825cb46ca4
ms.sourcegitcommit: 8d17d5df1427a817df15d45eae5f2f3e48d7b12d
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/23/2020
ms.locfileid: "48214357"
---
# <a name="clients-and-mobile-devices"></a><span data-ttu-id="220d0-103">클라이언트 및 모바일 장치</span><span class="sxs-lookup"><span data-stu-id="220d0-103">Clients and mobile devices</span></span>

## <a name="microsoft-outlook"></a><span data-ttu-id="220d0-104">Microsoft Outlook</span><span class="sxs-lookup"><span data-stu-id="220d0-104">Microsoft Outlook</span></span>

<span data-ttu-id="220d0-105">Microsoft Outlook은 일정, 연락처, 작업 및 다음 주요 기능에 대 한 지원을 포함 하는 전자 메일 프로그램입니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-105">Microsoft Outlook is an email program that includes support for calendar, contacts, tasks, and the following key features:</span></span>
  
- <span data-ttu-id="220d0-106">Http를 통한 **mapi (http** 를 통한 mapi)를 사용 하면 Outlook 사용자가 조직의 방화벽 외부에서 인터넷을 통해 Exchange Online 사서함에 연결할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-106">**MAPI over HTTP** - Messaging Application Program Interface (MAPI) over HTTP allows Outlook users to connect to Exchange Online mailboxes over the internet from outside their organization's firewall.</span></span> <span data-ttu-id="220d0-107">HTTP를 통한 MAPI, 외부에서 Outlook 사용에 대 한 장기간 교체</span><span class="sxs-lookup"><span data-stu-id="220d0-107">MAPI over HTTP, the long term replacement for Outlook Anywhere.</span></span> <span data-ttu-id="220d0-108">이 연결 방법은 향상 된 연결 복구, 보다 안전한 로그인, 확장성 및 IT 및 지원에 대 한 향상을 제공 합니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-108">This connectivity method offers improved connection resiliency, more secure sign-in, extensibility, as well as enhancements for IT and support.</span></span> <span data-ttu-id="220d0-109">자세한 내용은 Office 365 및 [MAPI OVER http](https://go.microsoft.com/fwlink/?linkid=393041) [에서 RPC over http 지원의 끝에 도달 하는 방법에 대](https://go.microsoft.com/fwlink/?linkid=863890) 한 자세한 내용을 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="220d0-109">To learn more, see [RPC over HTTP reaches end of support in Office 365](https://go.microsoft.com/fwlink/?linkid=863890) and [MAPI over HTTP](https://go.microsoft.com/fwlink/?linkid=393041).</span></span>

- <span data-ttu-id="220d0-110">**자동 검색** -자동 검색 서비스 기능은 Outlook에서 Exchange Online과 함께 작동 하도록 구성 합니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-110">**Autodiscover** - The Autodiscover service feature automatically configures Outlook to work with Exchange Online.</span></span> <span data-ttu-id="220d0-111">Outlook 사용자는 처음 전자 메일 주소와 암호를 통해 로그인했을 때 Exchange Online에서 바로 필요한 프로필 설정을 받을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-111">Outlook users can receive their required profile settings directly from Exchange Online the first time they sign in with their email address and password.</span></span> <span data-ttu-id="220d0-112">이러한 설정은 사용자의 프로필을 만들고 유지하는 데 필요한 정보를 가지고 Outlook 클라이언트를 자동으로 업데이트합니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-112">These settings automatically update the Outlook client with the information necessary to create and maintain the user's profile.</span></span> <span data-ttu-id="220d0-113">자동 검색 서비스를 사용하려면 SSL 인증서를 필요합니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-113">An SSL certificate is required to use the Autodiscover service.</span></span> <span data-ttu-id="220d0-114">이 SSL 인증서는 하나의 기본 SSL 도메인으로 제한됩니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-114">This SSL certificate is limited to a single primary SSL domain.</span></span> 

- <span data-ttu-id="220d0-115">**캐시** 된 exchange 모드-캐시 된 exchange 모드 기능을 사용 하면 Outlook 사용자가 인터넷에 연결 되어 있지 않을 때 exchange Online 사서함의 로컬 복사본에 액세스할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-115">**Cached Exchange Mode** - The Cached Exchange Mode feature allows Outlook users to access local copies of their Exchange Online mailboxes when they are not connected to the internet.</span></span> <span data-ttu-id="220d0-116">캐시 된 Exchange 모드는 Outlook에서 사용자 Exchange 사서함의 클라이언트 쪽 복사본을 유지 하며이 복사본을 전자 메일 서버와 자동으로 동기화 합니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-116">Cached Exchange Mode retains a client-side copy of users' Exchange mailboxes in Outlook and automatically synchronizes this copy with the email server.</span></span> <span data-ttu-id="220d0-117">Outlook은 캐시 된 Exchange 모드에서 오프 라인 액세스를 제공 하 고 클라이언트와 서버 간의 네트워크 조건이 적합 하지 않은 경우에도 응답성이 뛰어난 사용자 환경을 제공 하는 것이 좋습니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-117">We recommend using Outlook in Cached Exchange Mode because it provides offline access and helps to provide a responsive user experience even when network conditions between the client and the server are not ideal.</span></span> 

<span data-ttu-id="220d0-p104">기본적으로 Outlook 액세스는 모든 사용자에 대해 사용하도록 설정되어 있습니다. 관리자는 Windows Powershell을 통해 특정 사용자 또는 그룹의 액세스를 사용하지 않도록 설정할 수 있습니다. Exchange Online에 액세스하려면 최신 서비스 팩이 설치된 Outlook 최신 버전을 사용하는 것이 좋습니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-p104">By default, Outlook access is enabled for all users. Administrators can disable access for specific users or groups through Windows PowerShell. We recommend using the latest version of Outlook—with the latest service pack installed—to access Exchange Online.</span></span> 
  
<span data-ttu-id="220d0-121">Exchange 2016 및 Exchange Online에서 지 원하는 Outlook 클라이언트에 대 한 자세한 내용은 [시스템 요구 사항 Office](https://products.office.com/office-system-requirements)를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="220d0-121">For information about which Outlook clients are supported by Exchange 2016 and Exchange Online, see [System Requirements for Office](https://products.office.com/office-system-requirements).</span></span> 

<span data-ttu-id="220d0-122">Microsoft 365는 최신 브라우저 및 Office 버전에서 작동 하도록 설계 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-122">Microsoft 365 is designed to work with the latest browsers and versions of Office.</span></span> <span data-ttu-id="220d0-123">기본 지원 센터에 없는 이전 버전의 Office를 사용 하는 경우:</span><span class="sxs-lookup"><span data-stu-id="220d0-123">If you use older browsers and versions of Office that aren't in mainstream support:</span></span>

- <span data-ttu-id="220d0-124">Microsoft는 의도적으로 서비스에 연결 하지 못하도록 하지만, 시간이 지남에 따라 환경의 품질이 떨어질 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-124">Microsoft won't deliberately prevent you from connecting to the service, but the quality of your experience may diminish over time.</span></span>
- <span data-ttu-id="220d0-125">Microsoft는 비보안 관련 문제를 해결 하기 위한 소프트웨어 업데이트를 제공 하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-125">Microsoft won't provide software updates to resolve non-security related problems.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="220d0-126">Outlook은 Exchange Online 구독 가격에 포함되어 제공되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-126">Outlook is not provided as part of the Exchange Online subscription price.</span></span> <span data-ttu-id="220d0-127">Microsoft 365 for enterprise (Microsoft Outlook 포함)는 일부 계획에 포함 되어 있으며 별도의 구독으로 구매할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-127">Microsoft 365 Apps for enterprise (which includes Microsoft Outlook) is included in some plans and can be purchased as a separate subscription.</span></span> <span data-ttu-id="220d0-128">POP을 사용해서 Exchange Online 전자 메일 계정에 연결하면 다음 제한 사항이 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-128">You will see the following limitations if you use POP to connect to an Exchange Online email account:</span></span>
> - <span data-ttu-id="220d0-129">일정 정보 없음</span><span class="sxs-lookup"><span data-stu-id="220d0-129">No calendar information</span></span>
>- <span data-ttu-id="220d0-130">약속 있음/없음 정보 없음</span><span class="sxs-lookup"><span data-stu-id="220d0-130">No free/busy information</span></span>
>- <span data-ttu-id="220d0-131">전체 주소 목록 없음</span><span class="sxs-lookup"><span data-stu-id="220d0-131">No Global Address List</span></span>
>- <span data-ttu-id="220d0-132">전자 메일 푸시 없음</span><span class="sxs-lookup"><span data-stu-id="220d0-132">No push email</span></span>
>- <span data-ttu-id="220d0-133">POP를 통해 연결하면 모든 메시지가 클라이언트로 다운로드되며, 여러 컴퓨터 또는 장치 간에 동기화가 수행되지 않습니다(예: 랩톱과 전화 간).</span><span class="sxs-lookup"><span data-stu-id="220d0-133">When connecting through POP, all messages will be downloaded to the client and there will be no synchronization between multiple computers or devices (such as between a laptop and a phone).</span></span> 
  
## <a name="outlook-on-the-web"></a><span data-ttu-id="220d0-134">웹에서 Outlook</span><span class="sxs-lookup"><span data-stu-id="220d0-134">Outlook on the web</span></span>

<span data-ttu-id="220d0-135">웹상의 Outlook은 웹 기반 버전의 Outlook 전자 메일 프로그램으로 Exchange Online과 함께 사용됩니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-135">Outlook on the web is a web-based version of the Outlook email program that is used with Exchange Online.</span></span> <span data-ttu-id="220d0-136">이를 통해 사용자는 인터넷에 연결 된 모든 위치에서 웹 브라우저를 통해 전자 메일, 일정 및 연락처에 액세스할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-136">It lets users access their email, calendar, and contacts through a web browser from wherever they connect to the internet.</span></span> <span data-ttu-id="220d0-137">지원되는 브라우저에 대한 자세한 내용은 [비즈니스용 웹상의 Outlook에 대해 지원되는 브라우저](https://support.office.com/article/Supported-browsers-for-Outlook-Web-App-c89774d6-0722-4c93-a547-ef45e693e006)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="220d0-137">For information about supported browsers, see [Supported browsers for Outlook on the web for business](https://support.office.com/article/Supported-browsers-for-Outlook-Web-App-c89774d6-0722-4c93-a547-ef45e693e006).</span></span>
  
<span data-ttu-id="220d0-138">웹상의 Outlook에는 2가지 클라이언트 버전이 있으며, 모두 Exchange Online과 함께 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-138">Outlook on the web comes in two client versions, both of which can be used with Exchange Online:</span></span>
  
- <span data-ttu-id="220d0-139">**웹용 outlook** -웹용 outlook standard 버전은 Exchange Online 사용자에 게 outlook 사용자와 가장 유사한 메시징 환경을 제공 합니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-139">**Outlook on the web** - The standard version of Outlook on the web provides Exchange Online users with a messaging experience most similar to that of Outlook users.</span></span> <span data-ttu-id="220d0-140">대부분의 최신 웹 브라우저를 지원하며 데스크톱 및 랩톱 뿐만 아니라 태블릿 및 스마트폰 사용에 최적화되어 있습니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-140">It supports most newer web browsers and is optimized for use on tablets and smartphones as well as desktops and laptops.</span></span> <span data-ttu-id="220d0-141">사용자는 메시지 읽기 및 보내기, 연락처 구성, 약속 및 모임 예약 등의 작업을 수행할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-141">Users can read and send messages, organize contacts, and schedule appointments and meetings.</span></span> <span data-ttu-id="220d0-142">기본 작업 기반 시간 제한은 6시간으로 설정되지만 [Windows PowerShell에서 관리자가 5분에서 8시간 사이로 구성](https://go.microsoft.com/fwlink/p/?LinkId=399155)할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-142">The default activity-based time-out is set at six hours, but it can be [configured by an administrator in Windows PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=399155) from 5 minutes to 8 hours.</span></span> <span data-ttu-id="220d0-143">이 시간 제한은 단추를 선택 하거나 메시지를 선택 하는 것과 같은 웹 응용 프로그램 내의 사용자 상호 작용에 따라 달라 집니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-143">This time-out depends on user interactions within the web app, such as selecting a button or selecting a message.</span></span> <span data-ttu-id="220d0-144">또한 구성할 수 없으며 사용자 작업에 상관없이 발생하는 별도의 보안 기반 시간 제한도 있습니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-144">There is also a separate security-driven time-out, which is not configurable and will occur regardless of user activity.</span></span> <span data-ttu-id="220d0-145">사용자가 8시간 동안 로그인되어 있는 경우 OWA는 사용자를 자동으로 로그아웃하고 다시 인증하라는 메시지를 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-145">If a user is logged in for 8 hours, OWA will automatically log the user out and ask for re-authentication.</span></span> 

- <span data-ttu-id="220d0-146">**웹용 outlook의 라이트 버전** -웹용 outlook의 light 버전은 Exchange Online 사용자에 게 거의 모든 웹 브라우저를 사용 하 여 사서함에 대 한 액세스를 제공 합니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-146">**The light version of Outlook on the web** - The light version of Outlook on the web provides Exchange Online users access to the mailbox using almost any web browser.</span></span> <span data-ttu-id="220d0-147">사용자는 메시지 읽기 및 보내기, 연락처 구성, 약속 및 모임 예약 등의 작업을 수행할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-147">Users can read and send messages, organize contacts, and schedule appointments and meetings.</span></span> <span data-ttu-id="220d0-148">기본 작업 기반 시간 제한은 6시간으로 설정되지만 [Windows PowerShell에서 관리자가 5분에서 8시간 사이로 구성](https://go.microsoft.com/fwlink/p/?LinkId=399155)할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-148">The default activity-based time-out is set at six hours, but it can be [configured by an administrator in Windows PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=399155) from 5 minutes to 8 hours.</span></span> <span data-ttu-id="220d0-149">이 시간 제한은 단추를 선택 하거나 메시지를 선택 하는 것과 같은 웹 응용 프로그램 내의 사용자 상호 작용에 따라 달라 집니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-149">This time-out depends on user interactions within the web app, such as selecting a button or selecting a message.</span></span> <span data-ttu-id="220d0-150">또한 구성할 수 없으며 사용자 작업에 상관없이 발생하는 별도의 보안 기반 시간 제한도 있습니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-150">There is also a separate security-driven time-out, which is not configurable and will occur regardless of user activity.</span></span> <span data-ttu-id="220d0-151">사용자가 8시간 동안 로그인되어 있는 경우 라이트 버전의 OWA는 사용자를 자동으로 로그아웃하고 다시 인증하라는 메시지를 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-151">If a user is logged in for 8 hours, the light version of OWA will automatically log the user out and ask for re-authentication.</span></span> 

<span data-ttu-id="220d0-152">웹상의 Outlook은 모바일 버전으로도 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-152">Outlook on the web also is available in mobile versions.</span></span> <span data-ttu-id="220d0-153">자세한 내용은 [이 페이지](https://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="220d0-153">For more information, see [this page](https://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409).</span></span>
  
## <a name="outlook-for-mac"></a><span data-ttu-id="220d0-154">Outlook for Mac</span><span class="sxs-lookup"><span data-stu-id="220d0-154">Outlook for Mac</span></span>

<span data-ttu-id="220d0-155">Exchange Online은 전자 메일, 일정, 주소록, 작업 목록 및 메모 목록을 제공 하는 Mac 용 Microsoft Outlook을 지원 합니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-155">Exchange Online supports Microsoft Outlook for Mac, which provides email, calendar, an address book, a task list, and a note list.</span></span>
  
## <a name="outlook-for-ios-android-and-windows-phone"></a><span data-ttu-id="220d0-156">IOS, Android 및 Windows Phone 용 Outlook</span><span class="sxs-lookup"><span data-stu-id="220d0-156">Outlook for iOS, Android, and Windows Phone</span></span>

<span data-ttu-id="220d0-157">Exchange Online은 iOS, Android 및 Windows Phone에 사용할 수 있는 Outlook 앱과 함께 작동 합니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-157">Exchange Online works with Outlook apps available for iOS, Android, and Windows Phone.</span></span> <span data-ttu-id="220d0-158">이러한 장치에서 앱 스토어를 사용 하 여 Outlook 앱을 찾습니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-158">On any of these devices, use the app store to find the Outlook app.</span></span> <span data-ttu-id="220d0-159">다음은 모바일 OS에서 분석 한 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-159">Here's a breakdown by mobile OS.</span></span><br><br>
  
| <span data-ttu-id="220d0-160">디바이스</span><span class="sxs-lookup"><span data-stu-id="220d0-160">Device</span></span> | <span data-ttu-id="220d0-161">Android</span><span class="sxs-lookup"><span data-stu-id="220d0-161">Android</span></span> | <span data-ttu-id="220d0-162">iOS</span><span class="sxs-lookup"><span data-stu-id="220d0-162">iOS</span></span> | <span data-ttu-id="220d0-163">Windows Phone</span><span class="sxs-lookup"><span data-stu-id="220d0-163">Windows Phone</span></span> |
|:-----|:-----|:-----|:-----|
|<span data-ttu-id="220d0-164">Outlook 모바일 앱 가용성</span><span class="sxs-lookup"><span data-stu-id="220d0-164">Outlook mobile app availability</span></span>  <br/> |<span data-ttu-id="220d0-165">예</span><span class="sxs-lookup"><span data-stu-id="220d0-165">Yes</span></span>  <br/> [<span data-ttu-id="220d0-166">Android 용 Outlook 받기</span><span class="sxs-lookup"><span data-stu-id="220d0-166">Get Outlook for Android</span></span>](https://go.microsoft.com/fwlink/?linkid=863380) <br/> |<span data-ttu-id="220d0-167">예</span><span class="sxs-lookup"><span data-stu-id="220d0-167">Yes</span></span>  <br/> [<span data-ttu-id="220d0-168">IOS 용 Outlook 받기</span><span class="sxs-lookup"><span data-stu-id="220d0-168">Get Outlook for iOS</span></span>](https://go.microsoft.com/fwlink/?linkid=863382) <br/> |<span data-ttu-id="220d0-169">기본 제공</span><span class="sxs-lookup"><span data-stu-id="220d0-169">Built-in</span></span>  <br/> |
|<span data-ttu-id="220d0-170">Exchange Online과 호환 되는 기본 제공 전자 메일 앱</span><span class="sxs-lookup"><span data-stu-id="220d0-170">Built-in email apps compatible with Exchange Online</span></span>  <br/> |<span data-ttu-id="220d0-171">Gmail 앱/Samsung Email 응용 프로그램</span><span class="sxs-lookup"><span data-stu-id="220d0-171">Gmail app/Samsung Email app</span></span>  <br/> |<span data-ttu-id="220d0-172">iOS 메일 앱</span><span class="sxs-lookup"><span data-stu-id="220d0-172">iOS Mail app</span></span>  <br/> |<span data-ttu-id="220d0-173">Outlook 메일, 일정, 연락처</span><span class="sxs-lookup"><span data-stu-id="220d0-173">Outlook Mail, calendar, contacts</span></span>  <br/> |
|<span data-ttu-id="220d0-174">추가 정보</span><span class="sxs-lookup"><span data-stu-id="220d0-174">More information</span></span>  <br/> |[<span data-ttu-id="220d0-175">Android 모바일 설정</span><span class="sxs-lookup"><span data-stu-id="220d0-175">Android mobile setup</span></span>](https://go.microsoft.com/fwlink/?linkid=525632) <br/> |[<span data-ttu-id="220d0-176">iPhone 또는 iPad 설치</span><span class="sxs-lookup"><span data-stu-id="220d0-176">iPhone or iPad setup</span></span>](https://go.microsoft.com/fwlink/?linkid=396655) <br/> |[<span data-ttu-id="220d0-177">Windows Phone 설정</span><span class="sxs-lookup"><span data-stu-id="220d0-177">Windows Phone setup</span></span>](https://go.microsoft.com/fwlink/?linkid=831342) <br/> |

<span data-ttu-id="220d0-178">또한 Blackberry를 포함 하 여 Exchange Online과 장치를 함께 사용 하기 위한 옵션도 있습니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-178">There are also options for using Exchange Online with devices, including Blackberry.</span></span>
  
### <a name="feature-availability"></a><span data-ttu-id="220d0-179">기능 가용성</span><span class="sxs-lookup"><span data-stu-id="220d0-179">Feature availability</span></span>

<span data-ttu-id="220d0-180">사용자는 Outlook을 통해 최신 모바일 앱에서 기대할 수 있는 빠르고 직관적인 전자 메일 및 일정 환경을 제공 하지만, 최상의 기능을 지원 하기 위한 유일한 앱이 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-180">Outlook gives users the fast, intuitive email and calendar experience that they expect from a modern mobile app, while being the only app to provide support for the best features.</span></span> <span data-ttu-id="220d0-181">이 전자 메일 응용 프로그램은 전체 Microsoft 환경을 지원 하도록 특별히 설계 된 것으로, 데스크톱에서 모바일으로 사용자에 게 일관 된 환경을 제공 합니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-181">It is the only email app specifically designed to support the full Microsoft experience, giving users a coherent experience from desktop to mobile.</span></span> <span data-ttu-id="220d0-182">Outlook은 Intune, enterprise mobility and security 및 Exchange 컨트롤을 사용 하 여 데이터와 사용자를 안전 하 게 유지 합니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-182">Outlook is integrated with Intune, enterprise mobility and security, and Exchange controls to keep data and users safe.</span></span>
  
<span data-ttu-id="220d0-183">Outlook에서는 사용자가 다음 작업을 수행할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-183">With Outlook, users can:</span></span>
  
- <span data-ttu-id="220d0-184">모바일 장치에서 전체 날짜를 관리 합니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-184">Manage their entire day from a mobile device.</span></span>

- <span data-ttu-id="220d0-185">업무와 개인 정보를 별도로 유지 하 고 보호 하면서도 생산성을 높이는 데 필요한 앱 및 서비스에 연결 합니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-185">Connect to the apps and services they need to be productive, while keeping their work and personal information separate and secure.</span></span>

<span data-ttu-id="220d0-186">IOS, Android 용 Outlook 또는 Windows Phone 용 outlook을 사용 하 여 사용자는 다음을 수행할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-186">With Outlook for iOS, Outlook for Android, or Outlook for Windows Phone, users can:</span></span> 
  
- <span data-ttu-id="220d0-187">중요 받은 편지함의 우선 순위를 지정 하는 혜택</span><span class="sxs-lookup"><span data-stu-id="220d0-187">Benefit from a focused inbox that priorities important email</span></span>

- <span data-ttu-id="220d0-188">고유한 전자 메일 습관과 일치 하도록 살짝 밀기 제스처 사용자 지정</span><span class="sxs-lookup"><span data-stu-id="220d0-188">Customize swipe gestures to match their unique email habits</span></span>

- <span data-ttu-id="220d0-189">주요 정보를 한눈에 볼 수 있도록 일정에 직접 추가할 수 있는 여행 일정 만들기</span><span class="sxs-lookup"><span data-stu-id="220d0-189">Create travel itineraries that can be added directly to the calendar, with key information available at a glance</span></span>

- <span data-ttu-id="220d0-190">받은 편지함의 모임에 RSVP를 배달 합니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-190">RSVP to meetings from the inbox.</span></span>

- <span data-ttu-id="220d0-191">전자 메일 및 일정 약속의 직관적인 아이콘을 사용 하 여 정보를 빠르게 처리할 수 있도록 합니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-191">Use intuitive icons in email and calendar appointments that help them process information quickly</span></span>

- <span data-ttu-id="220d0-192">모든 장치에서 일관 되 고 익숙한 Outlook 환경 사용</span><span class="sxs-lookup"><span data-stu-id="220d0-192">Use a consistent and familiar Outlook experience across all devices</span></span>

- <span data-ttu-id="220d0-193">일정에서 Skype 모임을 간편 하 게 시작 및 참가</span><span class="sxs-lookup"><span data-stu-id="220d0-193">Easily launch and join Skype meetings from the calendar</span></span>

- <span data-ttu-id="220d0-194">IRM 암호화 및 보호 된 전자 메일 읽기 및 응답</span><span class="sxs-lookup"><span data-stu-id="220d0-194">Read and respond to IRM encrypted and protected emails</span></span>

- <span data-ttu-id="220d0-195">비즈니스용 OneDrive에 저장 된 파일 공유</span><span class="sxs-lookup"><span data-stu-id="220d0-195">Share files stored in OneDrive for Business</span></span>

- <span data-ttu-id="220d0-196">탭을 사용 하 여 자동 회신 설정</span><span class="sxs-lookup"><span data-stu-id="220d0-196">Set Automatic Replies with a tap</span></span>

- <span data-ttu-id="220d0-197">공유 및 위임 된 일정 보기 및 관리</span><span class="sxs-lookup"><span data-stu-id="220d0-197">View and manage shared and delegated calendars</span></span>

- <span data-ttu-id="220d0-198">회사의 전체 주소 목록에서 몇 번의 탭으로 검색</span><span class="sxs-lookup"><span data-stu-id="220d0-198">Search their company's global address list with a few taps</span></span>

- <span data-ttu-id="220d0-199">동료의 가용성 보기 및 모든 사용자에 대해 작동 하는 모임 시간 예약</span><span class="sxs-lookup"><span data-stu-id="220d0-199">View coworker's availability and schedule a meeting time that works for everyone</span></span>

- <span data-ttu-id="220d0-200">초대 대 상자 수락, 미정 및 거절 상태 보기</span><span class="sxs-lookup"><span data-stu-id="220d0-200">See invitees accept, tentative, and decline status</span></span>

- <span data-ttu-id="220d0-201">휴대폰에서 바로 일정 공유</span><span class="sxs-lookup"><span data-stu-id="220d0-201">Share calendars right from their phones</span></span>

- <span data-ttu-id="220d0-202">일정에서 바로 Skype 모임 시작 및 참가</span><span class="sxs-lookup"><span data-stu-id="220d0-202">Start and join Skype meetings right from a calendar</span></span>

- <span data-ttu-id="220d0-203">앱을 전환 하지 않고 한 곳에서 작업 및 개인 일정에 액세스</span><span class="sxs-lookup"><span data-stu-id="220d0-203">Access work and personal calendars in one place, without switching apps</span></span>
    
## <a name="exchange-activesync"></a><span data-ttu-id="220d0-204">Exchange ActiveSync</span><span class="sxs-lookup"><span data-stu-id="220d0-204">Exchange ActiveSync</span></span>

<span data-ttu-id="220d0-205">Exchange Online은 모바일 장치와 Exchange Online 간에 사서함 데이터를 동기화하는 Microsoft Exchange ActiveSync 프로토콜을 지원합니다. 따라서 사용자는 자신의 전자 메일, 연락처 및 작업을 이동 중에도 액세스할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-205">Exchange Online supports the Microsoft Exchange ActiveSync protocol, which synchronizes mailbox data between mobile devices and Exchange Online, so users can access their email, calendar, contacts, and tasks on the go.</span></span>
  
<span data-ttu-id="220d0-206">Exchange ActiveSync는 Microsoft Windows Phone, Apple iPhone 및 iPad, Android 휴대폰 및 태블릿 등을 비롯한 매우 다양한 유형의 모바일 장치에서 작동합니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-206">A wide range of mobile devices work with Exchange ActiveSync, including Microsoft Windows Phone, Apple iPhone and iPad, and Android phones and tablets.</span></span> <span data-ttu-id="220d0-207">휴대폰 및 장치 외에도 Windows Phone의 메일 응용 프로그램은 Exchange ActiveSync를 사용 하 여 Exchange Online에 연결 합니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-207">In addition to mobile phones and devices, the Mail application in Windows Phone uses Exchange ActiveSync to connect to Exchange Online.</span></span> <span data-ttu-id="220d0-208">현재 Exchange ActiveSync 라이선스 실시권자 전체 목록은 Exchange ActiveSync 라이선싱 사이트에서 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-208">A complete list of current Exchange ActiveSync licensees is available at the Exchange ActiveSync Licensing site.</span></span>
  
<span data-ttu-id="220d0-209">Exchange ActiveSync에 대 한 자세한 내용은 [Exchange activesync](https://go.microsoft.com/fwlink/p/?LinkId=271792)를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="220d0-209">For more information about Exchange ActiveSync, see [Exchange ActiveSync](https://go.microsoft.com/fwlink/p/?LinkId=271792).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="220d0-210">사서함당 Exchange ActiveSync 장치 수는 최대 100개입니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-210">The maximum number of Exchange ActiveSync devices per mailbox is 100.</span></span> 
  
## <a name="applications-developed-with-exchange-web-services-ews"></a><span data-ttu-id="220d0-211">Exchange 웹 서비스(EWS)로 개발된 응용 프로그램</span><span class="sxs-lookup"><span data-stu-id="220d0-211">Applications developed with Exchange Web Services (EWS)</span></span>

 <span data-ttu-id="220d0-212">EWS(Exchange 웹 서비스) 또는 EWS Managed API로 개발된 응용 프로그램을 사용하여 관리자는 온-프레미스, Azure 또는 기타 호스트된 서비스에서 실행되는 응용 프로그램에서 Exchange Online에 저장된 데이터에 액세스할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-212">Applications developed using Exchange Web Services (EWS) or the EWS Managed API let administrators access data stored with Exchange Online from applications that are running on-premises, in Azure, or in other hosted services.</span></span> 
  
<span data-ttu-id="220d0-213">Exchange 웹 서비스로 개발된 응용 프로그램에 대한 자세한 내용은 [Exchange의 웹 서비스](https://go.microsoft.com/fwlink/?LinkId=325346)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="220d0-213">For more information on applications developed with Exchange Web Services, see [Web Services in Exchange](https://go.microsoft.com/fwlink/?LinkId=325346).</span></span>
  
## <a name="pop-and-imap"></a><span data-ttu-id="220d0-214">POP 및 IMAP</span><span class="sxs-lookup"><span data-stu-id="220d0-214">POP and IMAP</span></span>

<span data-ttu-id="220d0-p114">Exchange Online은 POP3 및 IMAP4 프로토콜을 통해 사서함 액세스를 지원합니다. POP 및 IMAP 액세스에는 SSL를 사용한 암호화가 필요합니다. POP는 기본적으로 모든 사용자에 대해 사용하도록 설정되어 있습니다. 사용자는 자신의 POP 및 IMAP 연결 설정을 웹상의 Outlook에서 볼 수 있습니다. 관리자는 POP 및 IMAP 액세스를 각 사용자별로 사용하지 않도록 설정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-p114">Exchange Online supports mailbox access through both POP3 and IMAP4 protocols. POP and IMAP access requires encryption using SSL. POP is enabled by default for all users. Users can view their POP and IMAP connection settings in Outlook on the web. Administrators can disable POP and IMAP access on a per-user basis.</span></span>
  
<span data-ttu-id="220d0-220">POP3 및 IMAP4 연결에 대한 자세한 내용은 [POP3 및 IMAP4](https://go.microsoft.com/fwlink/p/?LinkId=272070)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="220d0-220">For more information about POP3 and IMAP4 connectivity, see [POP3 and IMAP4](https://go.microsoft.com/fwlink/p/?LinkId=272070).</span></span>
  
## <a name="smtp"></a><span data-ttu-id="220d0-221">SMTP</span><span class="sxs-lookup"><span data-stu-id="220d0-221">SMTP</span></span>

<span data-ttu-id="220d0-p115">SMTP(Simple Mail Transfer Protocol)은 IMAP 또는 POP를 통해 Exchange Online에 연결하는 클라이언트의 아웃바운드 메일을 보내는 데 사용됩니다. Exchange Server를 통한 배달 및 라우팅의 기본 프로토콜입니다. Exchange Online은 SMTP 메일 전송에 필요한 승인된 내부 고객 응용 프로그램에 대해 2가지 유형의 SMTP 릴레이 서비스를 지원합니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-p115">Simple Mail Transfer Protocol (SMTP) is used to send outbound mail for clients that connect to Exchange Online through IMAP or POP. It is the primary protocol for routing and delivery through Exchange Server. Exchange Online supports two types of SMTP relay services for authorized internal customer applications that require SMTP mail submission:</span></span>
  
- <span data-ttu-id="220d0-225">관리 환경 내부 사용자에 대한 SMTP 메시지 전송.</span><span class="sxs-lookup"><span data-stu-id="220d0-225">SMTP message submission to users inside the managed environment.</span></span>

- <span data-ttu-id="220d0-226">관리 환경 외부의 주소에 대한 인증된 SMTP 메시지 릴레이.</span><span class="sxs-lookup"><span data-stu-id="220d0-226">Authenticated SMTP message relay to addresses outside the managed environment.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="220d0-p116">SMTP 릴레이를 허용하려면 승인된 원본 서버에 대한 IP 주소가 필요합니다. SMTP를 사용해 전자 메일을 보낼 때는 전송 계층 보안(TLS) 암호화 및 인증이 필요합니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-p116">IP addresses for authorized source servers are required to allow SMTP relay. Transport Layer Security (TLS) encryption and authentication is required when using SMTP to send email.</span></span> 
  
## <a name="blackberry-devices"></a><span data-ttu-id="220d0-229">BlackBerry 장치</span><span class="sxs-lookup"><span data-stu-id="220d0-229">BlackBerry devices</span></span>

<span data-ttu-id="220d0-230">전자 메일은 Exchange ActiveSync를 통해 BlackBerry 장치에서 사용할 수 있습니다 &reg; .</span><span class="sxs-lookup"><span data-stu-id="220d0-230">Email is available on BlackBerry&reg; devices via Exchange ActiveSync.</span></span> <span data-ttu-id="220d0-231">옵션에 대 한 자세한 내용은 다음 항목을 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="220d0-231">To find out what your options are, see these topics:</span></span>
  
- [<span data-ttu-id="220d0-232">BlackBerry 장치에서 전자 메일 설정</span><span class="sxs-lookup"><span data-stu-id="220d0-232">Set up email on a BlackBerry device</span></span>](https://go.microsoft.com/fwlink/?linkid=863394)

- [<span data-ttu-id="220d0-233">BlackBerry 장치에서 전자 메일 설정 7.1 OS 및 이전 버전</span><span class="sxs-lookup"><span data-stu-id="220d0-233">Set up email on a BlackBerry device 7.1 OS and earlier</span></span>](https://go.microsoft.com/fwlink/?linkid=863403)

<span data-ttu-id="220d0-234">자세한 내용은 [BlackBerry](../office-365-platform-service-description/blackberry.md)를 참고하세요.</span><span class="sxs-lookup"><span data-stu-id="220d0-234">For more information, see [BlackBerry](../office-365-platform-service-description/blackberry.md).</span></span>
  
> [!NOTE]
> <span data-ttu-id="220d0-p118">중국의 21Vianet에서 운영하는 Office 365를 사용하는 경우 BlackBerry Business Cloud Services를 사용할 수 없지만 Exchange ActiveSync 장치 또는 RIM(Research in Motion, BlackBerry 무선 전자 메일 솔루션)의 기능을 사용하여 BES(Blackberry Enterprise Server)를 실행할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="220d0-p118">If you are using Office 365 operated by 21Vianet in China, BlackBerry Business Cloud Services is not available. However, you can use Exchange ActiveSync devices or an offering from Research in Motion (RIM, the BlackBerry wireless email solution) to run Blackberry Enterprise Server (BES).</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="220d0-237">기능 가용성</span><span class="sxs-lookup"><span data-stu-id="220d0-237">Feature availability</span></span>

<span data-ttu-id="220d0-238">계획, 독립 실행형 옵션 및 온-프레미스 솔루션 별로 기능 가용성을 확인 하려면 [Exchange Online 서비스 설명을](exchange-online-service-description.md)참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="220d0-238">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online service description](exchange-online-service-description.md).</span></span>
  