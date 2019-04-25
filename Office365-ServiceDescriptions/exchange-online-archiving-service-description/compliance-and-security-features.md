---
title: Exchange Online Archiving의 규정 준수 및 보안 기능
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- compliance-and-security-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7482322a-39fe-4a99-b29c-63cb1bc3cf1f
ms.openlocfilehash: 6da22293e465f83a69181aec78c47866154a6b79
ms.sourcegitcommit: 830694c729ab53fcc8518b0cdd5322b322514431
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/25/2019
ms.locfileid: "33245054"
---
# <a name="compliance-and-security-features-in-exchange-online-archiving"></a><span data-ttu-id="9edff-102">Exchange Online Archiving의 규정 준수 및 보안 기능</span><span class="sxs-lookup"><span data-stu-id="9edff-102">Compliance and Security Features in Exchange Online Archiving</span></span>

## <a name="compliance-features-in-exchange-online-archiving"></a><span data-ttu-id="9edff-103">Exchange Online Archiving의 규정 준수 기능</span><span class="sxs-lookup"><span data-stu-id="9edff-103">Compliance features in Exchange Online Archiving</span></span>

<span data-ttu-id="9edff-104">다음 섹션에서는 Microsoft Exchange Online Archiving의 규정 준수 기능을 설명합니다.</span><span class="sxs-lookup"><span data-stu-id="9edff-104">The following sections describe the compliance features of Microsoft Exchange Online Archiving.</span></span>
  
### <a name="retention-policies"></a><span data-ttu-id="9edff-105">보존 정책</span><span class="sxs-lookup"><span data-stu-id="9edff-105">Retention policies</span></span>
<span data-ttu-id="9edff-106"><a name="BKMK_Retentionpolicies"> </a></span><span class="sxs-lookup"><span data-stu-id="9edff-106"></span></span>

<span data-ttu-id="9edff-p101">Exchange Online Archiving은 전자 메일 및 기타 통신과 관련한 조직의 부담을 줄이는 데 도움을 주는 보존 정책을 제공합니다. 이러한 정책을 사용하면 관리자가 사용자 사서함의 특정 폴더에 보존 설정을 적용할 수 있습니다. 또한 관리자는 Outlook 2010 이상 또는 Outlook Web App을 통해 사용자에게 보존 정책 메뉴를 제공하고 이를 특정 항목, 대화 또는 폴더에 적용하도록 할 수 있습니다. Exchange Online Archiving에서 관리자는 온-프레미스 인프라의 보존 정책을 관리합니다.</span><span class="sxs-lookup"><span data-stu-id="9edff-p101">Exchange Online Archiving offers retention policies to help organizations reduce the liabilities associated with email and other communications. With these policies, administrators can apply retention settings to specific folders in users' inboxes. Administrators can also give users a menu of retention policies and let them apply the policies to specific items, conversations, or folders using Outlook 2010 or later or Outlook Web App. In Exchange Online Archiving, administrators manage retention policies from the on-premises infrastructure.</span></span>
  
<span data-ttu-id="9edff-p102">Exchange Online Archiving은 보관과 삭제라는 두 가지 유형의 정책을 제공합니다. 이 두 가지 유형을 동일한 항목이나 폴더에 적용할 수 있습니다. 예를 들어, 사용자가 지정한 기간(일)이 지나면 자동으로 전자 메일 메시지가 보관 사서함으로 이동되고 또 다른 지정한 기간(일)이 지나면 삭제되도록 전자 메일 메시지에 태그를 지정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="9edff-p102">Exchange Online Archiving offers two types of policies: archive and delete. Both types can be applied to the same item or folder. For example, a user can tag an email message so that it is automatically moved to the personal archive in a specified number of days and deleted after another span of days.</span></span>
  
<span data-ttu-id="9edff-p103">Outlook 2010 이상 및 Outlook Web App을 사용할 경우 사용자는 폴더, 대화 또는 개별 메시지에 보존 정책을 적용할 수 있으며, 적용된 보존 정책과 메시지의 예상 삭제 날짜도 볼 수 있습니다. 다른 전자 메일 클라이언트 사용자의 경우 관리자가 프로비전한 서버 쪽 보존 정책에 따라 전자 메일이 삭제되거나 보관되도록 할 수는 있지만 Outlook 2010 및 Outlook Web App에서와 같은 수준으로 메시지를 보거나 제어할 수는 없습니다.</span><span class="sxs-lookup"><span data-stu-id="9edff-p103">With Outlook 2010 and later and Outlook Web App, users can apply retention policies to folders, conversations, or individual messages and can also view the applied retention policies and expected deletion dates on messages. Users of other email clients can have email deleted or archived based on server-side retention policies provisioned by the administrator, but they do not have the same level of visibility and control.</span></span>
  
<span data-ttu-id="9edff-p104">Exchange Online Archiving에서 제공하는 보존 정책 기능은 Exchange Server 2010 SP2(서비스 팩 2) 이상에서 제공하는 기능과 동일합니다. 관리자는 온-프레미스 Exchange Server 2010 이상 환경에서 보존 정책을 관리할 수 있습니다. Exchange 2007에 도입되었던 이전의 메시징 레코드 관리 방법인 관리 폴더는 Exchange Online Archiving에서 사용할 수 없으며 Exchange Online Archiving과 호환되지 않습니다. 자세한 내용은 [보존 태그 및 보존 정책](https://go.microsoft.com/fwlink/p/?LinkID=314153)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="9edff-p104">The retention policy capabilities offered in Exchange Online Archiving are the same as those offered in Exchange Server 2010 Service Pack 2 (SP2) and later. Administrators can manage retention policies from on-premises Exchange Server 2010 and later environments. Managed Folders, an older approach to messaging records management that was introduced in Exchange 2007, are not available in and not compatible with Exchange Online Archiving. For more details, see [Retention Tags and Retention Policies](https://go.microsoft.com/fwlink/p/?LinkID=314153).</span></span>
  
### <a name="in-place-hold-and-litigation-hold"></a><span data-ttu-id="9edff-120">원본 위치 유지 및 소송 보존</span><span class="sxs-lookup"><span data-stu-id="9edff-120">In-Place Hold and Litigation Hold</span></span>
<span data-ttu-id="9edff-121"><a name="BKMK_In_placehold"> </a></span><span class="sxs-lookup"><span data-stu-id="9edff-121"></span></span>

<span data-ttu-id="9edff-p105">소송 가능성이 존재하는 경우 조직은 해당 사례와 관련된 전자 메일을 비롯한 ESI(전자적으로 저장된 정보)를 보존해야 합니다. 이러한 가능성은 사례의 세부 사항이 알려지기 전에 발생할 수 있으며 많은 경우 보존 범위가 넓습니다. 조직에서는 특정 항목과 관련된 모든 전자 메일 또는 특정 개인의 모든 전자 메일을 보존할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="9edff-p105">When a reasonable expectation of litigation exists, organizations are required to preserve electronically stored information (ESI), including email that's relevant to the case. This expectation can occur before the specifics of the case are known, and preservation is often broad. Organizations may preserve all email related to a specific topic, or all email for certain individuals.</span></span>
  
> [!NOTE]
> <span data-ttu-id="9edff-125">원본 위치 유지 및 소송 보존은 현재 POP 또는 IMAP 클라이언트를 사용하여 보냈거나 SMTP 프로토콜을 사용하는 사용자 지정 응용 프로그램에서 보낸 전자 메일에는 적용되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="9edff-125">In-place hold and litigation hold currently do not apply to emails sent using POP or IMAP clients, or by custom applications that use the SMTP protocol.</span></span> 
  
<span data-ttu-id="9edff-126">Exchange Online에서는 원본 위치 유지 또는 소송 보존 기능을 사용하여 다음과 같은 목표를 달성할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="9edff-126">In Exchange Online, you can use In-Place Hold or Litigation Hold to accomplish the following goals:</span></span>
  
- <span data-ttu-id="9edff-127">사용자를 유지 상태로 설정하고 사서함 항목을 변경할 수 없는 상태로 보존</span><span class="sxs-lookup"><span data-stu-id="9edff-127">Enable users to be placed on hold and preserve mailbox items immutably</span></span>
    
- <span data-ttu-id="9edff-128">사용자나 MRM과 같은 자동 삭제 프로세스에 의해 삭제된 사서함 항목 보존</span><span class="sxs-lookup"><span data-stu-id="9edff-128">Preserve mailbox items deleted by users or automatic deletion processes such as MRM</span></span>
    
- <span data-ttu-id="9edff-129">원본 항목의 복사본을 저장하여 사서함 항목 변조 또는 사용자/자동 프로세스에 의한 변경 방지</span><span class="sxs-lookup"><span data-stu-id="9edff-129">Protect mailbox items from tampering, changes by a user, or automatic processes by saving a copy of the original item</span></span>
    
- <span data-ttu-id="9edff-130">무기한 또는 특정 기간 동안 항목 보존</span><span class="sxs-lookup"><span data-stu-id="9edff-130">Preserve items indefinitely or for a specific duration</span></span>
    
- <span data-ttu-id="9edff-131">MRM을 일시 중단할 필요 없이 보존 항목을 사용자에 대해 투명하게 유지 가능</span><span class="sxs-lookup"><span data-stu-id="9edff-131">Keep holds transparent from the user by not having to suspend MRM</span></span>
    
- <span data-ttu-id="9edff-132">원본 위치 eDiscovery를 사용하여 보존된 항목을 비롯한 사서함 항목 검색</span><span class="sxs-lookup"><span data-stu-id="9edff-132">Use In-Place eDiscovery to search mailbox items, including items placed on hold</span></span>
    
<span data-ttu-id="9edff-133">또한 원본 위치 유지 기능을 통해 다음 작업을 수행할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="9edff-133">Additionally, you can use In-Place Hold to:</span></span>
  
- <span data-ttu-id="9edff-134">지정한 조건과 일치하는 항목 검색 및 보존</span><span class="sxs-lookup"><span data-stu-id="9edff-134">Search and hold items matching specified criteria</span></span>
    
- <span data-ttu-id="9edff-135">다른 사례 또는 조사를 위해 여러 원본 위치 유지 상태로 사용자 배치</span><span class="sxs-lookup"><span data-stu-id="9edff-135">Place a user on multiple In-Place Holds for different cases or investigations</span></span>
    
> [!NOTE]
> <span data-ttu-id="9edff-136">사서함에 원본 위치 유지 또는 소송 보존을 적용하면 기본 사서함과 보관 사서함 둘 다 보류됩니다.</span><span class="sxs-lookup"><span data-stu-id="9edff-136">When you put a mailbox on In-Place Hold or Litigation Hold, the hold is placed on both the primary and the archive mailbox.</span></span> 
  
<span data-ttu-id="9edff-137">자세한 내용은 [원본 위치 유지 및 소송 보존](https://go.microsoft.com/fwlink/p/?LinkId=271746)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="9edff-137">For more information, see [In-Place Hold and Litigation Hold](https://go.microsoft.com/fwlink/p/?LinkId=271746).</span></span>
  
> [!NOTE]
> <span data-ttu-id="9edff-138">Exchange Online Archiving 사용자의 복구 가능한 항목 폴더의 기본 할당량은 100 GB입니다.</span><span class="sxs-lookup"><span data-stu-id="9edff-138">The default quota for the Recoverable Items Folder is 100 GB for Exchange Online Archiving users.</span></span> 
  
### <a name="in-place-ediscovery"></a><span data-ttu-id="9edff-139">원본 위치 eDiscovery</span><span class="sxs-lookup"><span data-stu-id="9edff-139">In-Place eDiscovery</span></span>
<span data-ttu-id="9edff-140"><a name="BKMK_In_placehold"> </a></span><span class="sxs-lookup"><span data-stu-id="9edff-140"></span></span>

<span data-ttu-id="9edff-p106">Exchange Online Archiving에서는 조직의 사서함 콘텐츠 검색에 대해 원본 위치 eDiscovery를 지원합니다. 온-프레미스 Exchange 2013 서버에서 Exchange 관리 센터 또는 원격 Windows PowerShell을 사용하여 관리자나 권한 있는 Discovery 관리자는 전자 메일 메시지, 첨부 파일, 일정 약속, 작업, 연락처 등 다양한 사서함 항목을 검색할 수 있습니다. 원본 위치 eDiscovery는 기본 사서함 및 보관 사서함을 동시에 검색할 수 있습니다. KQL(Keyword Query Language) 구문과 함께, 다양한 필터링 기능에는 보낸 사람, 받는 사람, 메시지 유형, 보낸 날짜, 받은 날짜, 참조 및 숨은 참조가 있습니다. 자세한 내용은 [원본 위치 eDiscovery](https://go.microsoft.com/fwlink/p/?LinkId=314169)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="9edff-p106">Exchange Online Archiving supports In-Place eDiscovery for searching the contents of mailboxes in an organization. Using the Exchange admin center or remote Windows PowerShell from an on-premises Exchange 2013 server, administrators or authorized Discovery managers can search a variety of mailbox items - including email messages, attachments, calendar appointments, tasks, and contacts. In-Place eDiscovery can search simultaneously across primary mailboxes and archives. Rich filtering capabilities include sender, receiver, message types, sent date, received date, carbon copy, and blind carbon copy, along with Keyword Query Language (KQL) syntax. For more details, see [In-Place eDiscovery](https://go.microsoft.com/fwlink/p/?LinkId=314169).</span></span>
  
<span data-ttu-id="9edff-p107">Exchange 관리 센터 및 원격 Windows PowerShell을 사용하여 원본 위치 eDiscovery 검색에서 최대 5,000개의 사서함을 한 번에 검색할 수 있습니다. 원격 Windows PowerShell을 사용하여 원본 위치 eDiscovery 검색을 실행하는 방법에 대한 자세한 내용은 [New-MailboxSearch](https://go.microsoft.com/fwlink/p/?LinkId=314170)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="9edff-p107">The Exchange admin center and remote Windows PowerShell can be used to search up to 5,000 mailboxes at a time in an In-Place eDiscovery search. For details about using remote Windows PowerShell to run In-Place eDiscovery searches, see [New-MailboxSearch](https://go.microsoft.com/fwlink/p/?LinkId=314170).</span></span> 
  
> [!NOTE]
> <span data-ttu-id="9edff-p108">원격 Windows PowerShell에서  `Search-Mailbox` cmdlet을 사용하여 5,000개가 넘는 사서함을 검색할 수 있습니다. 원격 Windows PowerShell을 사용하여 많은 수의 사서함을 검색하는 방법에 대한 자세한 내용은 [Search-Mailbox](https://go.microsoft.com/fwlink/p/?LinkId=314171)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="9edff-p108">In remote Windows PowerShell, the  `Search-Mailbox` cmdlet can be used to search more than 5,000 mailboxes. For details about searching large numbers of mailboxes using remote Windows PowerShell, see [Search-Mailbox](https://go.microsoft.com/fwlink/p/?LinkId=314171).</span></span> 
  
<span data-ttu-id="9edff-p109">원본 위치 eDiscovery 검색의 결과는 Exchange 관리 센터에서 미리 보거나 .pst 파일로 내보내거나 검색 사서함이라는 특수 유형의 사서함에 복사할 수 있습니다. 관리자 또는 준수 관리자는 검색 사서함에 연결하여 메시지를 검토할 수 있습니다. 자세한 내용은 [원본 위치 eDiscovery 검색 만들기](https://go.microsoft.com/fwlink/p/?LinkId=314172)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="9edff-p109">Results of an In-Place eDiscovery search can be previewed in the Exchange admin center, exported to a .pst file, or copied to a special type of mailbox, called a discovery mailbox. Administrators or compliance officers can connect to the discovery mailbox to review messages. For details, see [Create an In-Place eDiscovery Search](https://go.microsoft.com/fwlink/p/?LinkId=314172).</span></span>
  
> [!NOTE]
> <span data-ttu-id="9edff-p110">온-프레미스 및 클라우드 기반 사서함 또는 보관 사서함에 대해 수행된 원본 위치 eDiscovery 검색의 검색 결과를 복사할 때 온-프레미스 검색 사서함을 선택해야 합니다. 온-프레미스 기본 사서함과 클라우드 기반 보관 사서함의 메시지는 온-프레미스 검색 사서함에 복사됩니다.</span><span class="sxs-lookup"><span data-stu-id="9edff-p110">When copying search results for an In-Place eDiscovery search performed across on-premises and cloud-based mailboxes or archives, you must select an on-premises discovery mailbox. Messages from the on-premises primary mailbox and the cloud-based archive are copied to the on-premises discovery mailbox.</span></span> 
  
<span data-ttu-id="9edff-p111">또한 관리자는 조직 전체의 여러 사서함으로 전송된 부적절한 전자 메일 메시지를 검색하여 삭제할 수도 있습니다. 예를 들어, 기밀에 해당하는 급여 정보가 실수로 모든 직원에게 전송된 경우 관리자는 사용자의 사서함에서 해당 전자 메일을 삭제할 수 있습니다. 이 유형의 검색은 Exchange 관리 센터에서는 사용할 수 없으며, 원격 PowerShell을 사용하여 수행해야 합니다. 사용자의 사서함에서 메시지를 삭제하는 방법에 대한 자세한 내용은 [메시지 검색 및 삭제](https://go.microsoft.com/fwlink/p/?LinkId=314173)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="9edff-p111">Administrators can also search for and delete inappropriate email messages sent to multiple mailboxes across their organizations. For example, if confidential salary information was accidentally sent to all employees, an administrator can delete the email from the users' mailboxes. This type of search is not available in the Exchange admin center. It must be performed using Remote PowerShell. For details on how to delete messages from users' mailboxes, see [Search and Delete Messages](https://go.microsoft.com/fwlink/p/?LinkId=314173).</span></span>
  
## <a name="security-features-in-exchange-online-archiving"></a><span data-ttu-id="9edff-160">Exchange Online Archiving의 보안 기능</span><span class="sxs-lookup"><span data-stu-id="9edff-160">Security features in Exchange Online Archiving</span></span>

<span data-ttu-id="9edff-161">다음 섹션에서는 Microsoft Exchange Online Archiving의 보안 기능을 설명합니다.</span><span class="sxs-lookup"><span data-stu-id="9edff-161">The following sections describe the security features of Microsoft Exchange Online Archiving.</span></span>
  
### <a name="encryption-between-on-premises-servers-and-exchange-online-archiving"></a><span data-ttu-id="9edff-162">온-프레미스 서버와 Exchange Online Archiving 간 암호화</span><span class="sxs-lookup"><span data-stu-id="9edff-162">Encryption between on-premises servers and Exchange Online Archiving</span></span>

<span data-ttu-id="9edff-p112">전자 메일 서버 간 연결을 암호화하는 데는 TLS가 사용되어 스푸핑이 방지되도록 하고 전송 중인 메시지에 기밀성을 제공합니다. 또한 TLS는 Exchange Online Archiving용 Office 365 데이터 센터로 전송되는 온-프레미스 메일 서버 트래픽의 보안을 유지하는 데 사용됩니다.</span><span class="sxs-lookup"><span data-stu-id="9edff-p112">TLS is used to encrypt the connection between email servers to help prevent spoofing and provide confidentiality for messages in transit. TLS is also used for securing on-premises mail server traffic to Office 365 data centers for Exchange Online Archiving.</span></span>
  
### <a name="encrypting-between-clients-and-exchange-online-archiving"></a><span data-ttu-id="9edff-165">클라이언트와 Exchange Online Archiving 간 암호화</span><span class="sxs-lookup"><span data-stu-id="9edff-165">Encrypting between clients and Exchange Online Archiving</span></span>

<span data-ttu-id="9edff-166">보안 향상을 위해 Exchange Online Archiving에 대한 클라이언트 연결에는 다음과 같은 암호화 방법이 사용됩니다.</span><span class="sxs-lookup"><span data-stu-id="9edff-166">Client connections to Exchange Online Archiving use the following encryption methods to enhance security:</span></span>
  
- <span data-ttu-id="9edff-167">SSL은 TCP 포트 443을 통해 Outlook, Outlook Web App 및 Exchange 웹 서비스 트래픽의 보안을 유지하는 데 사용됩니다.</span><span class="sxs-lookup"><span data-stu-id="9edff-167">SSL is used for securing Outlook, Outlook Web App, and Exchange Web Services traffic, using TCP port 443.</span></span>
    
- <span data-ttu-id="9edff-168">Exchange Online Archiving이 도입된다고 해서 온-프레미스 서버에 대한 클라이언트 연결이 변경되지는 않습니다.</span><span class="sxs-lookup"><span data-stu-id="9edff-168">Client connections to on-premises servers do not change with the introduction of Exchange Online Archiving.</span></span>
    
### <a name="encryption-smime-and-pgp"></a><span data-ttu-id="9edff-169">암호화: S/MIME 및 PGP</span><span class="sxs-lookup"><span data-stu-id="9edff-169">Encryption: S/MIME and PGP</span></span>

<span data-ttu-id="9edff-p113">Exchange Online Archiving에서는 S/MIME(Secure/Multipurpose Internet Mail Extensions) 메시지를 저장합니다. 그러나 Exchange Online Archiving에서 S/MIME 기능을 호스트하거나 공개 키를 호스트하지는 않으며 키 리포지토리, 키 관리 또는 키 디렉터리 서비스를 제공하지도 않습니다. 이러한 모든 서비스가 온-프레미스 Exchange 인프라에 연결되기 때문입니다.</span><span class="sxs-lookup"><span data-stu-id="9edff-p113">Exchange Online Archiving will store Secure/Multipurpose Internet Mail Extensions (S/MIME) messages. However, Exchange Online Archiving does not host S/MIME functions or host the public keys, nor does it provide key repository, key management, or key directory services because all of these services attach to the on-premises Exchange infrastructure.</span></span>
  
<span data-ttu-id="9edff-172">마찬가지로, Exchange Online Archiving에서는 클라이언트 쪽, 타사 암호화 솔루션(예: PGP(Pretty Good Privacy))을 사용하여 암호화된 메시지를 저장합니다.</span><span class="sxs-lookup"><span data-stu-id="9edff-172">Similarly, Exchange Online Archiving will store messages that are encrypted using client-side, third-party encryption solutions such as Pretty Good Privacy (PGP).</span></span>
  
### <a name="information-rights-management"></a><span data-ttu-id="9edff-173">정보 권한 관리</span><span class="sxs-lookup"><span data-stu-id="9edff-173">Information Rights Management</span></span>

<span data-ttu-id="9edff-p114">Exchange Online Archiving에서 호스트 IRM(정보 권한 관리) 서비스를 제공하지는 않지만 관리자는 온-프레미스 AD RMS(Active Directory Rights Management Services)를 사용할 수 있습니다. AD RMS 서버가 배포되면 Outlook은 해당 서버와 직접 통신할 수 있으며, 사용자는 IRM으로 보호된 메시지를 작성하고 읽을 수 있습니다. AD RMS 서버와 온-프레미스 Exchange 환경 간의 상호 운용성이 구성된 경우 사용자는 IRM으로 보호된 메시지를 작성하고 읽을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="9edff-p114">Exchange Online Archiving does not provide hosted Information Rights Management (IRM) services, but administrators can use on-premises Active Directory Rights Management Services (AD RMS). If an AD RMS server is deployed, Outlook can communicate directly with that server, enabling users to compose and read IRM-protected messages. If interoperability between the AD RMS server and the on-premises Exchange environment is configured, users will be able to compose and read IRM-protected messages.</span></span>
  
#### <a name="support-for-irm-in-outlook-web-app"></a><span data-ttu-id="9edff-177">Outlook Web App의 IRM 지원</span><span class="sxs-lookup"><span data-stu-id="9edff-177">Support for IRM in Outlook Web App</span></span>

<span data-ttu-id="9edff-p115">사용자는 Outlook에서와 마찬가지로 Outlook Web App에서 IRM으로 보호된 메시지를 기본적으로 읽고 만들 수 있습니다. Internet Explorer, Firefox, Safari 및 Chrome을 통해 Outlook Web App의 IRM으로 보호된 메시지에 액세스할 수 있습니다(플러그 인 불필요). 메시지에는 전체 텍스트 검색, 대화 보기 및 미리 보기 창이 포함됩니다. 이 기능이 가능하도록 Active Directory Rights Management Services 서버와 온-프레미스 Exchange 환경 간의 상호 운용성이 구성되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="9edff-p115">Users can read and create IRM-protected messages natively in Outlook Web App, just as they can in Outlook. IRM-protected messages in Outlook Web App can be accessed through Internet Explorer, Firefox, Safari, and Chrome (with no plug-in required). The messages include full-text search, conversation view, and the preview pane. Interoperability between the Active Directory Rights Management Services server and the on-premises Exchange environment must be configured to enable this.</span></span>
  
#### <a name="irm-search"></a><span data-ttu-id="9edff-182">IRM 검색</span><span class="sxs-lookup"><span data-stu-id="9edff-182">IRM Search</span></span>

<span data-ttu-id="9edff-p116">헤더, 제목, 본문 및 첨부 파일을 비롯하여 IRM으로 보호된 메시지는 인덱싱되며 검색 가능합니다. 사용자는 Outlook 및 Outlook Web App에서 IRM으로 보호된 항목을 검색할 수 있으며, 관리자는 원본 위치 eDiscovery 또는 **Search-Mailbox** cmdlet을 사용하여 IRM으로 보호된 항목을 검색할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="9edff-p116">IRM-protected messages are indexed and searchable, including headers, subject, body, and attachments. Users can search IRM-protected items in Outlook and Outlook Web App, and administrators can search IRM-protected items by using In-Place eDiscovery or the **Search-Mailbox** cmdlet.</span></span> 
  
### <a name="auditing"></a><span data-ttu-id="9edff-185">감사</span><span class="sxs-lookup"><span data-stu-id="9edff-185">Auditing</span></span>

<span data-ttu-id="9edff-186">Exchange Online Archiving에서는 다음과 같은 두 가지 유형의 기본 제공 감사 기능을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="9edff-186">Exchange Online Archiving provides two types of built-in auditing capabilities:</span></span>
  
- <span data-ttu-id="9edff-187">**관리자 감사 로깅** 관리자 감사 로깅을 통해 고객은 RBAC 역할이나 Exchange 정책 및 설정에 대한 변경 내용을 비롯하여 Exchange Online Archiving 환경에서 관리자가 수행한 변경 내용을 추적할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="9edff-187">**Administrator audit logging** Administrator audit logging allows customers to track changes made by their administrators in the Exchange Online Archiving environment, including changes to RBAC roles or Exchange policies and settings.</span></span> 
    
- <span data-ttu-id="9edff-188">**사서함 감사 로깅** 사서함 감사 로깅을 통해 고객은 사서함 소유자가 아닌 다른 사용자에 의한 사서함 액세스를 추적할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="9edff-188">**Mailbox audit logging** Mailbox audit logging allows customers to track access to mailboxes by users other than the mailbox owner.</span></span> 
    
<span data-ttu-id="9edff-p117">Exchange 관리 센터에서는 관리자 역할 변경, 소송 보존, 비소유자 사서함 액세스 등 미리 정의된 여러 감사 보고서를 사용할 수 있습니다. 관리자는 날짜 및 역할별로 보고서를 필터링하고 장기 보존 또는 사용자 지정 보고를 위해 지정된 사서함에 대한 모든 감사 이벤트를 XML 형식으로 내보낼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="9edff-p117">Several predefined audit reports are available in the Exchange admin center, including Administrator Role Changes, Litigation Hold, and Non-Owner Mailbox Access. Administrators can filter reports by date and role, and they can export all audit events for specified mailboxes in XML format for long-term retention or custom reporting.</span></span>
  
<span data-ttu-id="9edff-p118">관리자 감사 로깅은 기본적으로 설정되며, 사서함 감사 로깅은 기본적으로 해제됩니다. 관리자는 원격 Windows PowerShell을 사용하여 조직에 있는 사서함 일부 또는 전부에 대해 사서함 감사 로깅을 사용하도록 설정할 수 있습니다. 자세한 내용은 [감사 보고서](https://go.microsoft.com/fwlink/p/?LinkId=314175)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="9edff-p118">Administrator audit logging is on by default, and mailbox audit logging is off by default. Administrators can use remote Windows PowerShell to enable mailbox audit logging for some or all mailboxes in their organization. For more information, see [Auditing Reports](https://go.microsoft.com/fwlink/p/?LinkId=314175).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="9edff-194">기능 가용성</span><span class="sxs-lookup"><span data-stu-id="9edff-194">Feature Availability</span></span>

<span data-ttu-id="9edff-195">Office 365 계획, 독립 실행형 옵션 및 온-프레미스 솔루션별로 기능 가용성을 확인하려면 [Exchange Online Archiving 서비스 설명](exchange-online-archiving-service-description.md)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="9edff-195">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Archiving Service Description](exchange-online-archiving-service-description.md).</span></span>
  

