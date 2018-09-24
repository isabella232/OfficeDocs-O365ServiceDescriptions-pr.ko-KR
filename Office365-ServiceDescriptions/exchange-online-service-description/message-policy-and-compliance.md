---
title: 메시지 정책 및 규정 준수
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-message-policy-recovery-and-compliance
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 5c43c8eb-f8f7-4b5a-a743-b1dab7dc2fc8
ms.openlocfilehash: fd5062df19298720417566d91667f3c3b237b164
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036670"
---
# <a name="message-policy-and-compliance"></a><span data-ttu-id="335bc-102">메시지 정책 및 규정 준수</span><span class="sxs-lookup"><span data-stu-id="335bc-102">Message Policy and Compliance</span></span>

## <a name="archiving-exchange-online-based-mailboxes"></a><span data-ttu-id="335bc-103">Exchange Online 기반 사서함 보관</span><span class="sxs-lookup"><span data-stu-id="335bc-103">Archiving Exchange Online-based mailboxes</span></span>

<span data-ttu-id="335bc-p101">Exchange Online 사서함은 클라우드에 있으며, 이를 보관하려면 고유한 호스트 환경이 필요합니다. 경우에 따라 Exchange Online은 클라우드에 온-프레미스 사서함을 보관하는 데 사용되기도 합니다. Exchange Online을 사용한 보관 옵션을 이 섹션에서 설명합니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-p101">Exchange Online mailboxes reside in the cloud, and archiving them requires unique hosting environments. In some cases, Exchange Online can also be used to archive on-premises mailboxes in the cloud. The options for archiving with Exchange Online are described in this section.</span></span>
  
<span data-ttu-id="335bc-p102">Exchange Online은 사용자가 오래된 전자 메일 메시지를 저장할 수 있는 편리한 위치를 제공하는 원본 위치 보관을 비롯하여 클라우드 기반 사서함에 대한 보관 기능을 기본 제공합니다. 원본 위치 보관은 Outlook 및 Outlook Web App에서 사용자의 기본 사서함 폴더와 함께 표시되는 특수한 사서함 유형입니다. 사용자는 기본 사서함에 액세스하고 검색할 때와 동일한 방식으로 보관 사서함에 액세스하고 검색할 수 있습니다. 사용 가능한 기능은 사용 중인 클라이언트에 따라 다릅니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-p102">Exchange Online provides built-in archiving capabilities for cloud-based mailboxes, including an In-Place Archive that gives users a convenient place to store older email messages. An In-Place Archive is a special type of mailbox that appears alongside a user's primary mailbox folders in Outlook and Outlook Web App. Users can access and search the archive in the same way they access and search their primary mailboxes. Available functionality depends on the client in use:</span></span>
  
- <span data-ttu-id="335bc-111">**Outlook 2016, Outlook 2013, Outlook 2010 및 Outlook Web App** 사용자는 보존 및 보관 정책에 대한 제어와 같은 관련 준수 기능뿐만 아니라 보관함의 모든 기능에 액세스할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-111">**Outlook 2016, Outlook 2013, Outlook 2010, and Outlook Web App** Users have access to the full features of the archive, as well as related compliance features like control over retention and archive policies.</span></span> 
    
- <span data-ttu-id="335bc-p103">**Outlook 2007** 사용자는 원본 위치 보관에 대해 기본 지원을 제공받지만 일부 보관 및 준수 기능은 사용할 수 없습니다. 예를 들면, 사용자는 사서함 항목에 대해 보존 및 보관 정책을 적용할 수 없으며 관리자 프로비저닝 정책을 대신 사용해야 합니다</span><span class="sxs-lookup"><span data-stu-id="335bc-p103">**Outlook 2007** Users have basic support for the In-Place Archive, but not all archiving and compliance features are available. For example, users cannot apply retention or archive policies to mailbox items and must rely on administrator-provisioned policies instead.</span></span> 
    
<span data-ttu-id="335bc-114">관리자는 Exchange 관리 센터 또는 원격 Windows PowerShell을 통해 특정 사용자에 대해 개인 보관 기능을 사용하도록 설정합니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-114">Administrators use the Exchange admin center or remote Windows PowerShell to enable the personal archive feature for specific users.</span></span>
  
<span data-ttu-id="335bc-115">자세한 내용은 다음 항목을 참조하십시오.</span><span class="sxs-lookup"><span data-stu-id="335bc-115">For more information, see:</span></span>
  
- [<span data-ttu-id="335bc-116">Exchange Online의 활성 사서함</span><span class="sxs-lookup"><span data-stu-id="335bc-116">Archive mailboxes in Exchange Online</span></span>](https://go.microsoft.com/fwlink/p/?LinkId=404421)
    
- [<span data-ttu-id="335bc-117">Exchange Online에서 보관 사서함을 사용하거나 사용하지 않도록 설정</span><span class="sxs-lookup"><span data-stu-id="335bc-117">Enable or disable an archive mailbox in Exchange Online</span></span>](https://go.microsoft.com/fwlink/p/?LinkId=404425)
    
### <a name="archive-sizes"></a><span data-ttu-id="335bc-118">보관 크기</span><span class="sxs-lookup"><span data-stu-id="335bc-118">Archive sizes</span></span>

<span data-ttu-id="335bc-p104">사용자 한 명의 메시지 데이터만 각 개인 보관 사서함에 저장할 수 있습니다. 저장소의 할당은 구독 계획에 따라 다릅니다. 보관 사서함 크기에 대한 자세한 내용은 [Exchange Online 제한](exchange-online-limits.md)의 "사서함 저장소 제한" 섹션을 참조하십시오.</span><span class="sxs-lookup"><span data-stu-id="335bc-p104">Only one user's messaging data can be stored in each personal archive. The allocation of storage depends on the subscription plan. For more information about archive mailbox sizes, see the "Mailbox storage limits" section in [Exchange Online Limits](exchange-online-limits.md).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="335bc-p105">보관 목적으로 Exchange Online 사서함에 메시지를 복사하는 저널링, 전송 규칙 또는 자동 전달 규칙을 사용하는 것은 허용되지 않습니다. Microsoft는 개인 시나리오에서 사서함 보관이 사용되지 않는 경우 인스턴스의 무제한 보관을 거부할 권한을 보유합니다. > Outlook 사용자의 경우 원본 위치 보관에 특정 라이선스 요구 사항이 적용됩니다. Outlook 2007 사용자의 경우 개인 보관 파일에 액세스하려면 2011년 2월 Office 2007 누적 업데이트가 필요합니다. > Exchange Online은 관리자 중심으로 개인 보관 사서함에 .pst 파일을 가져오기 위한 Exchange Server 2010 SP 1 이상 버전의  _New-MailboxImportRequest_ Windows PowerShell cmdlet을 지원하지 않습니다. 사용자의 기본 사서함과 보관 사서함 모두가 Exchange Online에 있으면 관리자는 무료 도구인 PST Capture를 사용하여 사용자의 기본 사서함이나 보관 사서함으로 .pst 파일 데이터를 가져올 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-p105">Using journaling, transport rules, or auto-forwarding rules to copy messages to an Exchange Online mailbox for the purposes of archiving is not permitted. Microsoft reserves the right to deny unlimited archiving in instances where a mailbox archive is not being used in a personal scenario. > In-Place Archive has specific licensing requirements for Outlook users. Outlook 2007 users must have the Office 2007 Cumulative Update for February 2011 to access the personal archive. > Exchange Online does not support the  _New-MailboxImportRequest_ Windows PowerShell cmdlet of Exchange Server 2010 Service Pack 1 or later for administrator-driven import of .pst files into a personal archive. If a user has both the primary mailbox and the archive in Exchange Online, an administrator can use PST Capture, a free tool, to import .pst file data to the user's primary mailbox or archive.</span></span> 
  
## <a name="cloud-based-archiving-of-on-premises-mailboxes"></a><span data-ttu-id="335bc-128">온-프레미스 사서함의 클라우드 기반 보관</span><span class="sxs-lookup"><span data-stu-id="335bc-128">Cloud-based archiving of on-premises mailboxes</span></span>

<span data-ttu-id="335bc-p106">온-프레미스 Exchange Server 2010 이상 사서함의 클라우드 기반 보관에 Exchange Online을 사용하려는 경우 Microsoft에서 호스트하는 보관 솔루션인 Microsoft Exchange Online Archiving을 구현할 수 있습니다. 이를 위해서는 온-프레미스 조직이 하이브리드 모드이거나 Exchange Online Archiving에 맞게 설정되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-p106">Using Exchange Online for cloud-based archiving of on-premises Exchange Server 2010 or later mailboxes is possible with Microsoft Exchange Online Archiving, a hosted archiving solution from Microsoft. This requires that the on-premises organization be in Hybrid mode or be set up for Exchange Online Archiving.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="335bc-131">관리되는 폴더 정책이 적용되는 Exchange 2010 사서함 서버에 온-프레미스 사서함이 있는 사용자는 온-프레미스 또는 클라우드 기반 원본 위치 보관을 사용할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-131">Users with an on-premises mailbox on an Exchange 2010 Mailbox server who have a Managed Folder policy applied cannot have an on-premises or cloud-based In-Place Archive enabled.</span></span> 
  
## <a name="retention-tags-and-retention-policies"></a><span data-ttu-id="335bc-132">보존 태그 및 보존 정책</span><span class="sxs-lookup"><span data-stu-id="335bc-132">Retention tags and retention policies</span></span>

<span data-ttu-id="335bc-p107">Exchange Online은 전자 메일 및 다른 통신과 관련한 조직의 부담을 줄이는 데 도움을 주는 보존 정책을 제공합니다. 이러한 정책을 사용하면 관리자가 사용자 사서함의 특정 폴더에 보존 설정을 적용할 수 있습니다. 또한 관리자는 Outlook 2010 이상 또는 Outlook Web App를 통해 사용자에게 보존 정책 메뉴를 제공하고 이를 특정 항목, 대화 또는 폴더에 적용하도록 할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-p107">Exchange Online offers retention policies to help organizations reduce the liabilities associated with email and other communications. With these policies, administrators can apply retention settings to specific folders in users' inboxes. Administrators can also give users a menu of retention policies and let them apply the policies to specific items, conversations, or folders using Outlook 2010 or later or Outlook Web App.</span></span>
  
<span data-ttu-id="335bc-136">Exchange Online에서 관리자는 EAC(Exchange 관리 센터) 또는 원격 Windows PowerShell을 사용하여 보존 정책을 관리합니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-136">In Exchange Online, administrators manage retention policies by using the Exchange admin center (EAC) or remote Windows PowerShell.</span></span>
  
<span data-ttu-id="335bc-p108">Exchange Online은 보관 정책 및 삭제 정책이라는 두 가지 유형의 정책을 제공합니다. 이 두 가지 유형을 동일한 항목이나 폴더에 함께 적용할 수 있습니다. 예를 들어, 사용자는 특정 기간 후 전자 메일 메시지가 자동으로 원본 위치 보관으로 이동되고 그로부터 며칠이 지나면 삭제되도록 태그를 설정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-p108">Exchange Online offers two types of policies: archive policies and delete policies. Both types can be combined on the same item or folder. For example, a user can tag an email message to be automatically moved to the In-Place Archive in a specified number of days and deleted after another span of days.</span></span>
  
<span data-ttu-id="335bc-p109">사용자는 Outlook 2010 이상 및 Outlook Web App를 통해 폴더, 대화 또는 개별 메시지에 보존 정책을 적용할 수 있습니다. 또한 적용되는 보존 정책 및 메시지의 예상 삭제 날짜를 직접 확인할 수 있습니다. 그러나 다른 전자 메일 클라이언트 사용자는 관리자가 설정한 서버 쪽 보존 정책을 기반으로 전자 메일을 삭제하거나 보관할 수만 있습니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-p109">With Outlook 2010 or later and Outlook Web App, users can apply retention policies to folders, conversations, or individual messages. They can also view the applied retention policies and expected deletion dates on messages. Users of other email clients can only have email messages deleted or archived based on server-side retention policies set by the administrator.</span></span>
  
<span data-ttu-id="335bc-p110">Exchange Online에서 제공하는 보존 정책 기능은 Exchange Server 2010 SP2 RU4에서 제공하는 기능과 동일합니다. 관리자는 원격 Windows PowerShell을 사용하여 온-프레미스 Exchange Server 2010 이상 환경에서 Exchange Online으로 보존 정책을 마이그레이션할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-p110">The retention policy capabilities offered in Exchange Online are the same as those offered in Exchange Server 2010 Service Pack 2 RU4. Administrators can use remote Windows PowerShell to migrate retention policies from on-premises Exchange Server 2010 or later environments to Exchange Online.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="335bc-145">Exchange Server 2007에서 제공했던 기존의 메시징 레코드 관리 접근 방식인 관리되는 폴더는 사용할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-145">Managed Folders, an older approach to messaging records management that was introduced in Exchange Server 2007, are not available in Exchange Online.</span></span> 
  
<span data-ttu-id="335bc-146">자세한 내용은 [보존 태그 및 보존 정책](https://go.microsoft.com/fwlink/p/?LinkId=271745)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="335bc-146">For more information, see [Retention Tags and Retention Policies](https://go.microsoft.com/fwlink/p/?LinkId=271745).</span></span>
  
## <a name="encryption-of-data-at-rest"></a><span data-ttu-id="335bc-147">보관된 데이터 암호화</span><span class="sxs-lookup"><span data-stu-id="335bc-147">Encryption of data at rest</span></span>

<span data-ttu-id="335bc-p111">보관 된 Office 365 고객 데이터의 암호화 알려준 Exchange BitLocker, DKM, Azure 저장소 서비스 암호화 및 암호화 서비스를 포함 하는 여러 서비스 측 기술, Online, Skype 비즈니스용 OneDrive 비즈니스, 및 SharePoint에 대 한 온라인. Office 365 서비스 암호화 키 추적용 Azure에에서 저장 된 고객 관리 되는 암호화 키를 사용 하는 옵션을 포함 합니다. [Office 365 고객 키](https://go.microsoft.com/fwlink/?linkid=863349)를 호출 하이 고객 관리 키 옵션을은 Exchange Online, SharePoint Online 및 비즈니스용 OneDrive에 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-p111">Encryption of Office 365 customer data at rest is provided by multiple service-side technologies, including BitLocker, DKM, Azure Storage Service Encryption, and service encryption in Exchange Online, Skype for Business, OneDrive for Business, and SharePoint Online. Office 365 Service Encryption include an option to use customer-managed encryption keys that are stored in Azure Key Vault. This customer-managed key option, called [Office 365 Customer Key](https://go.microsoft.com/fwlink/?linkid=863349), is available for Exchange Online, SharePoint Online, and OneDrive for Business.</span></span> 
  
### <a name="bitlocker"></a><span data-ttu-id="335bc-151">BitLocker</span><span class="sxs-lookup"><span data-stu-id="335bc-151">BitLocker</span></span>

<span data-ttu-id="335bc-p112">BitLocker를 사용 하 여 볼륨 수준에서 보관 된 고객 데이터를 포함 하는 디스크 드라이브를 암호화 하는 office 365 서버. BitLocker 암호화는 Windows에서 기본 제공 되는 데이터 보호 기능입니다. BitLocker에서 다른 프로세스 또는 고객 데이터를 포함 하는 디스크에 대 한 실제 액세스를 사용할 수 있는 사람에 게 발생할 수 있는 컨트롤 (예: 액세스 제어 또는 하드웨어의 재활용)에서 여행 있을 경우 위협 으로부터 보호 하기 위해 사용 되는 기술 중 하나입니다. 이 경우 BitLocker는 분실, 도난 또는 부적절 하 게 폐기 된 컴퓨터와 디스크 인해 데이터 도난 또는 노출 가능성을 제거합니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-p112">Office 365 servers use BitLocker to encrypt the disk drives containing customer data at rest at the volume-level. BitLocker encryption is a data protection feature that is built into Windows. BitLocker is one of the technologies used to safeguard against threats in case there are lapses in other processes or controls (e.g., access control or recycling of hardware) that could lead to someone gaining physical access to disks containing customer data. In this case, BitLocker eliminates the potential for data theft or exposure because of lost, stolen, or inappropriately decommissioned computers and disks.</span></span> 
  
### <a name="distributed-key-manager"></a><span data-ttu-id="335bc-156">분산 된 키 관리자</span><span class="sxs-lookup"><span data-stu-id="335bc-156">Distributed Key Manager</span></span>

<span data-ttu-id="335bc-p113">BitLocker, 외에도 분산 키 관리자 (DKM) 라는 기술을 사용 합니다. DKM은 비밀 키 집합을 사용 하 여 암호화 하 고 정보를 해독 하는 클라이언트쪽 기능입니다. Active Directory 도메인 서비스에서 특정 보안 그룹의 구성원만 암호를 해독 DKM 하 여 암호화 된 데이터에 대 한 이러한 키에 액세스할 수 있습니다. Exchange Online의 Exchange 프로세스를 실행 하는 특정 서비스 계정만는 해당 보안 그룹에 포함 됩니다. 데이터 센터의 표준 운영 절차의 일부로 없음 human는 지정이 보안 그룹에 속한 자격 증명 되 고 따라서에 이러한 암호를 해독할 수 있는 키에 대 한 액세스 권한이 없는 사람이 합니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-p113">In addition to BitLocker, we use a technology called Distributed Key Manager (DKM). DKM is a client-side functionality that uses a set of secret keys to encrypt and decrypt information. Only members of a specific security group in Active Directory Domain Services can access those keys to decrypt the data that is encrypted by DKM. In Exchange Online, only certain service accounts under which the Exchange processes run are part of that security group. As part of standard operating procedure in the datacenter, no human is given credentials that are part of this security group and therefore no human has access to the keys that can decrypt these secrets.</span></span>
  
## <a name="customer-key"></a><span data-ttu-id="335bc-162">고객 키</span><span class="sxs-lookup"><span data-stu-id="335bc-162">Customer Key</span></span>

<span data-ttu-id="335bc-p114">고객 키를 사용 하 컨트롤 조직의 암호화 키 및 Microsoft의 데이터 센터의 나머지 부분에서 데이터를 암호화 하 고 사용 하 여 Office 365를 구성 합니다. 보관 된 데이터에는 Exchange Online 및 사서함 및 SharePoint Online에 저장 된 파일에 저장 된 비즈니스를 위한 Skype 및 비즈니스용 OneDrive에서 데이터를 포함 합니다. 자세한 내용은 [고객 키를 사용 하 여 Office 365에서 데이터를 제어](https://go.microsoft.com/fwlink/?linkid=863349) 하 고 [Office 365 FAQ에 대 한 고객 키를 사용 하 여 서비스 암호화](https://go.microsoft.com/fwlink/?linkid=869438)를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="335bc-p114">With Customer Key, you control your organization's encryption keys and then configure Office 365 to use them to encrypt your data at rest in Microsoft's data centers. Data at rest includes data from Exchange Online and Skype for Business that is stored in mailboxes and files that are stored in SharePoint Online and OneDrive for Business. For more information, see [Controlling your data in Office 365 using Customer Key](https://go.microsoft.com/fwlink/?linkid=863349) and [Service Encryption with Customer Key for Office 365 FAQ](https://go.microsoft.com/fwlink/?linkid=869438).</span></span>
  
## <a name="office-365-message-encryption"></a><span data-ttu-id="335bc-166">Office 365 메시지 암호화</span><span class="sxs-lookup"><span data-stu-id="335bc-166">Office 365 Message Encryption</span></span>
<span data-ttu-id="335bc-167"><a name="bkmk_O365_MessageEncryption"> </a></span><span class="sxs-lookup"><span data-stu-id="335bc-167"></span></span>

<span data-ttu-id="335bc-p115">Office 365 메시지 암호화 전자 메일 사용자가 모든 사용자에 게 암호화 된 전자 메일 메시지를 보낼 수 있습니다. 발표 Azure 정보 암호화의 보호 기능을 활용 하는 Office 메시지 암호화의 새로운 기능입니다. 제공 이러한 새 기능에 보다 쉽게 공유 하 고는 조직의 내부 또는 외부 사람과 보호 된 메시지에 공동 작업을 수행할 수 있도록 최종 사용자 환경을 향상 되었습니다. 새로운 Office 메시지 암호화 기능에는 일부 설치 요구 사항이 있습니다. 설정 참조 Azure 정보 보호 위쪽에 구축 된 새로운 Office 365 메시지 암호화 기능을 합니다. 레거시 Office 365 메시지 암호화에 고객 위에 제공 된 지침 설정에 따라 없이 새로운 기능을 받지 않을 합니다. 새 레거시 Office 365 메시지 암호화 기능 비교에 포함 된 제품에 대 한 자세한 내용은 [FAQ](https://support.office.com/en-us/article/Office-365-Message-Encryption-FAQ-0432dce9-d9b6-4e73-8a13-4a932eb0081e) 를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="335bc-p115">Office 365 Message Encryption allows email users to send encrypted email messages to anyone. We announced new capabilities in Office Message Encryption that leverage the protection features in Azure Information Encryption. These new capabilities provided enhanced end user experiences that make it easier to share and collaborate on protected messages with anyone inside or outside the organization. The new Office Message Encryption capabilities have some setup requirements. See Set up new Office 365 Message Encryption capabilities built on top of Azure Information Protection. Customers on legacy Office 365 Message Encryption do not get the new capabilities without following the set up guidance provided above. Please read the [FAQ](https://support.office.com/en-us/article/Office-365-Message-Encryption-FAQ-0432dce9-d9b6-4e73-8a13-4a932eb0081e) for more details on what's included in the new vs. legacy Office 365 Message Encryption capabilities.</span></span> 
  
## <a name="securemultipurpose-internet-mail-extensions-smime"></a><span data-ttu-id="335bc-175">S/MIME(Secure/Multipurpose Internet Mail Extensions)</span><span class="sxs-lookup"><span data-stu-id="335bc-175">Secure/Multipurpose Internet Mail Extensions (S/MIME)</span></span>
<span data-ttu-id="335bc-176"><a name="bkmk_O365_MessageEncryption"> </a></span><span class="sxs-lookup"><span data-stu-id="335bc-176"></span></span>

<span data-ttu-id="335bc-p116">S/MIME을 사용하면 조직 내에서 서명 및 암호화된 전자 메일을 보내 중요한 정보를 보호할 수 있습니다. 관리자는 PKI 인증서를 설정하고 사용자에게 발급한 후 원격 Windows PowerShell을 사용하여 S/MIME을 설정할 수 있습니다. 이러한 인증서는 온-프레미스 Active Directory 인증서 서비스에서 동기화해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-p116">S/MIME allows you to help protect sensitive information by sending signed and encrypted email within your organization. Administrators can use remote Windows PowerShell to set up S/MIME after establishing and issuing PKI certificates to users. These certificates must be synchronized from an on-premises Active Directory Certificate Service.</span></span>
  
<span data-ttu-id="335bc-p117">S/MIME는 Internet Explorer 9 이상에서 지원되며 Firefox, Opera 및 Chrome에서는 지원되지 않습니다. 자세한 내용은 [메시지 서명 및 암호화용 S/MIME](https://go.microsoft.com/fwlink/p/?LinkID=393973)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="335bc-p117">S/MIME is supported on Internet Explorer 9 or later. Currently, S/MIME is unsupported on Firefox, Opera, and Chrome. For more information, see [S/MIME for Message Signing and Encryption](https://go.microsoft.com/fwlink/p/?LinkID=393973).</span></span>
  
## <a name="in-place-hold-and-litigation-hold"></a><span data-ttu-id="335bc-183">원본 위치 유지 및 소송 보존</span><span class="sxs-lookup"><span data-stu-id="335bc-183">In-Place Hold and Litigation Hold</span></span>
<span data-ttu-id="335bc-184"><a name="bkmk_O365_MessageEncryption"> </a></span><span class="sxs-lookup"><span data-stu-id="335bc-184"></span></span>

<span data-ttu-id="335bc-p118">소송 가능성이 존재하는 경우 조직은 해당 사례와 관련된 전자 메일을 비롯한 ESI(전자적으로 저장된 정보)를 보존해야 합니다. 이러한 가능성은 사례의 세부 사항이 알려지기 전에 발생할 수 있으며 많은 경우 보존 범위가 넓습니다. 조직에서는 특정 항목과 관련된 모든 전자 메일 또는 특정 개인의 모든 전자 메일을 보존할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-p118">When a reasonable expectation of litigation exists, organizations are required to preserve electronically stored information (ESI), including email that's relevant to the case. This expectation can occur before the specifics of the case are known, and preservation is often broad. Organizations may preserve all email related to a specific topic, or all email for certain individuals.</span></span>
  
<span data-ttu-id="335bc-188">Exchange Online에서는 원본 위치 유지 또는 소송 보존 기능을 사용하여 다음과 같은 목표를 달성할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-188">In Exchange Online, you can use In-Place Hold or Litigation Hold to accomplish the following goals:</span></span>
  
- <span data-ttu-id="335bc-189">사용자를 유지 상태로 설정하고 사서함 항목을 변경할 수 없는 상태로 보존</span><span class="sxs-lookup"><span data-stu-id="335bc-189">Enable users to be placed on hold and preserve mailbox items immutably</span></span>
    
- <span data-ttu-id="335bc-190">사용자나 MRM과 같은 자동 삭제 프로세스에 의해 삭제된 사서함 항목 보존</span><span class="sxs-lookup"><span data-stu-id="335bc-190">Preserve mailbox items deleted by users or automatic deletion processes such as MRM</span></span>
    
- <span data-ttu-id="335bc-191">원본 항목의 복사본을 저장하여 사서함 항목 변조 또는 사용자/자동 프로세스에 의한 변경 방지</span><span class="sxs-lookup"><span data-stu-id="335bc-191">Protect mailbox items from tampering, changes by a user, or automatic processes by saving a copy of the original item</span></span>
    
- <span data-ttu-id="335bc-192">무기한 또는 특정 기간 동안 항목 보존</span><span class="sxs-lookup"><span data-stu-id="335bc-192">Preserve items indefinitely or for a specific duration</span></span>
    
- <span data-ttu-id="335bc-193">MRM을 일시 중단할 필요 없이 보존 항목을 사용자에 대해 투명하게 유지 가능</span><span class="sxs-lookup"><span data-stu-id="335bc-193">Keep holds transparent from the user by not having to suspend MRM</span></span>
    
- <span data-ttu-id="335bc-194">원본 위치 eDiscovery를 사용하여 보존된 항목을 비롯한 사서함 항목 검색</span><span class="sxs-lookup"><span data-stu-id="335bc-194">Use In-Place eDiscovery to search mailbox items, including items placed on hold</span></span>
    
<span data-ttu-id="335bc-195">또한 원본 위치 유지 기능을 통해 다음 작업을 수행할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-195">Additionally, you can use In-Place Hold to:</span></span>
  
- <span data-ttu-id="335bc-196">지정한 조건과 일치하는 항목 검색 및 보존</span><span class="sxs-lookup"><span data-stu-id="335bc-196">Search and hold items matching specified criteria</span></span>
    
- <span data-ttu-id="335bc-197">다른 사례 또는 조사를 위해 여러 원본 위치 유지 상태로 사용자 배치</span><span class="sxs-lookup"><span data-stu-id="335bc-197">Place a user on multiple In-Place Holds for different cases or investigations</span></span>
    
> [!NOTE]
> <span data-ttu-id="335bc-198">사서함에 원본 위치 유지 또는 소송 보존을 적용하면 기본 사서함과 보관 사서함 둘 다 보류됩니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-198">When you put a mailbox on In-Place Hold or Litigation Hold, the hold is placed on both the primary and the archive mailbox.</span></span> 
  
<span data-ttu-id="335bc-199">자세한 내용은 [원본 위치 유지 및 소송 보존](https://go.microsoft.com/fwlink/p/?LinkId=271746)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="335bc-199">For more information, see [In-Place Hold and Litigation Hold](https://go.microsoft.com/fwlink/p/?LinkId=271746).</span></span>
  
## <a name="in-place-ediscovery"></a><span data-ttu-id="335bc-200">원본 위치 eDiscovery</span><span class="sxs-lookup"><span data-stu-id="335bc-200">In-Place eDiscovery</span></span>
<span data-ttu-id="335bc-201"><a name="bkmk_O365_MessageEncryption"> </a></span><span class="sxs-lookup"><span data-stu-id="335bc-201"></span></span>

<span data-ttu-id="335bc-p119">Exchange Online의 고객은 웹 기반 인터페이스를 사용하여 조직 전체의 사서함에서 내용을 검색할 수 있습니다. 할당을 통한 원본 위치 eDiscovery 검색을 수행할 권한이 있는 관리자나 규정 준수 및 보안 담당자는 전자 메일 메시지, 첨부 파일, 일정 약속, 작업, 연락처 및 기타 항목을 검색할 수 있습니다. 원본 위치 eDiscovery은 기본 사서함 및 보관함을 동시에 검색할 수 있습니다. KQL 구문과 함께, 다양한 필터링 기능에는 보낸 사람, 받는 사람, 메시지 유형, 보낸 날짜/받은 날짜, 참조/숨은 참조가 있습니다. 검색 쿼리와 일치할 경우 지운 편지함 폴더의 항목도 검색 결과에 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-p119">Exchange Online enables customers to search the contents of mailboxes across an organization using a web-based interface. Administrators or compliance and security officials who are authorized to perform In-Place eDiscovery search (by assigning) can search email messages, attachments, calendar appointments, tasks, contacts, and other items. In-Place eDiscovery can search simultaneously across primary mailboxes and archives. Rich filtering capabilities include sender, receiver, message type, sent/receive date, and carbon copy/blind carbon copy, along with KQL Syntax. Search results will also include items in the Deleted Items folder if they match the search query.</span></span>
  
<span data-ttu-id="335bc-p120">원본 위치 eDiscovery 검색의 결과는 웹 기반 인터페이스에서 미리 보거나 PST 파일로 내보내거나 검색 사서함이라는 특수 유형 사서함에 복사할 수 있습니다. 검색 사서함에는 검색 결과를 저장하기 위한 50GB의 할당량이 있습니다. 또한 관리자는 Outlook을 검색 사서함에 연결하여 검색 결과에 액세스하고 검색 결과를 .pst 파일로 내보낼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-p120">Results of In-Place eDiscovery searches can be previewed in the web-based interface, exported to a PST file or copied to a special type of mailbox called a Discovery mailbox. A Discovery mailbox has a 50 GB quota for storing search results. Administrators can also connect Outlook to the Discovery mailbox to access search results, and export the search results to a .pst file.</span></span>
  
<span data-ttu-id="335bc-p121">관리자는 Exchange 관리 센터 또는 원격 Windows PowerShell을 사용하여 여러 사서함 검색을 수행합니다. Exchange 관리 센터에서 검색 결과에 대한 읽기 전용 미리 보기를 제공하므로, 관리자는 신속하게 검색을 확인하고 필요한 경우 다른 매개 변수를 사용하여 검색을 다시 실행할 수 있습니다. 검색이 최적화되면 관리자는 검색 사서함에 결과를 복사할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-p121">Administrators use either the Exchange admin center or remote Windows PowerShell to perform multi-mailbox searches. The Exchange admin center can provide a read-only preview of the search results, enabling administrators to quickly verify a search and rerun it, if needed, with different parameters. Once a search is optimized, the administrator can copy the results to the Discovery mailbox.</span></span>
  
<span data-ttu-id="335bc-p122">기본적으로 조직별로 하나의 검색 사서함이 만들어지지만 관리자가 원격 Windows PowerShell을 사용하여 검색 사서함을 추가로 만들 수 있습니다. 검색 사서함은 원본 위치 eDiscovery 검색 결과 저장 이외의 용도로는 사용할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-p122">By default, one Discovery mailbox is created for each organization, but administrators can create additional Discovery mailboxes using remote Windows PowerShell. Discovery mailboxes cannot be used for any purpose other than storing In-Place eDiscovery search results.</span></span>
  
<span data-ttu-id="335bc-p123">관리자는 Exchange 관리 센터 또는 원격 Windows PowerShell을 사용하여 원본 위치 eDiscovery 검색을 수행합니다. Exchange 관리 센터에서 검색 결과에 대한 읽기 전용 미리 보기를 제공하므로, 관리자는 신속하게 검색을 확인하고 필요한 경우 다른 매개 변수를 사용하여 검색을 다시 실행할 수 있습니다. 검색이 최적화되면 관리자는 검색 사서함에 결과를 복사하거나 검색 결과를 PST 파일로 내보낼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-p123">Administrators use either the Exchange admin center or remote Windows PowerShell to perform In-Place eDiscovery searches. The Exchange admin center can provide a read-only preview of the search results, enabling administrators to quickly verify a search and rerun it, if needed, with different parameters. Once a search is optimized, the administrator can copy the results to the Discovery mailbox or export search results to a PST file.</span></span>
  
<span data-ttu-id="335bc-218">관리자는 Exchange 관리 센터 또는 원격 Windows PowerShell을 사용하여 원본 위치 eDiscovery 검색에서 한 번에 최대 10,000개의 사서함을 검색할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-218">Administrators can use either the Exchange admin center or remote Windows PowerShell to search up to 10,000 mailboxes at a time in an In-Place eDiscovery search.</span></span> 
  
<span data-ttu-id="335bc-219">Exchange Online에서 권한 있는 사용자는 원본 위치 eDiscovery를 수행할 수 있으며, 다음 작업 중 하나를 선택할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-219">In Exchange Online, authorized users can perform In-Place eDiscovery and choose one of the following actions:</span></span>
  
- <span data-ttu-id="335bc-220">**검색 결과 예상** - 검색에 사용된 키워드의 효율성을 확인하고 필요한 경우 검색 매개 변수를 조정하는 키워드 통계를 비롯하여 검색에서 반환할 예상 메시지 개수를 가져옵니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-220">**Estimate search results** Get an estimate of the number of messages the search will return, including keywords statistics to determine the effectiveness of keywords used in the search and tweak search parameters if required.</span></span> 
    
- <span data-ttu-id="335bc-221">**검색 결과 미리 보기**</span><span class="sxs-lookup"><span data-stu-id="335bc-221">**Preview search results**</span></span>
    
- <span data-ttu-id="335bc-222">검색 결과에 반환된 메시지를 검색 사서함에 복사합니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-222">Copy messages returned in search results to a Discovery mailbox.</span></span>
    
<span data-ttu-id="335bc-223">자세한 내용은 [원본 위치 eDiscovery](http://go.microsoft.com/fwlink/p/?LinkId=271747)를 참조하십시오.</span><span class="sxs-lookup"><span data-stu-id="335bc-223">For more information, see [In-Place eDiscovery](http://go.microsoft.com/fwlink/p/?LinkId=271747).</span></span>
  
## <a name="mail-flow-rules"></a><span data-ttu-id="335bc-224">메일 흐름 규칙</span><span class="sxs-lookup"><span data-stu-id="335bc-224">Mail flow rules</span></span>
<span data-ttu-id="335bc-225"><a name="bkmk_O365_MessageEncryption"> </a></span><span class="sxs-lookup"><span data-stu-id="335bc-225"></span></span>

<span data-ttu-id="335bc-p124">조직을 통해 전달 하 고 작업을 수행 하는 메시지에 대 한 특정 조건에 대 한 확인 메일 흐름 규칙을 사용할 수 있습니다. 메일 흐름 규칙을 통해 전자 메일 메시지, 메시지의 보안 하 고, 메시징 시스템을 보호 하 고 정보 유출 방지 하는 메시징 정책을 적용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-p124">You can use mail flow rules to look for specific conditions on messages that pass through your organization and act on them. Mail flow rules let you apply messaging policies to email messages, secure messages, protect messaging systems, and prevent information leakage.</span></span>
  
<span data-ttu-id="335bc-p125">현재 여러 조직들은 법률, 규정 요구 사항 또는 회사 정책에 따라 조직 내부 및 외부에서 받는 사람과 보낸 사람 사이의 상호 작용을 제한해야 합니다. 개인 사이의 상호 작용을 제한하는 것 외에 조직 내부의 부서 그룹 및 조직 외부의 엔터티와 일부 조직 역시 다음 메시징 정책 요구 사항에 의해 제한될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-p125">Many organizations today are required by law, regulatory requirements, or company policies to apply messaging policies that limit the interaction between recipients and senders, both inside and outside the organization. In addition to limiting interactions among individuals, departmental groups inside the organization, and entities outside the organization, some organizations are also subject to the following messaging policy requirements:</span></span>
  
- <span data-ttu-id="335bc-230">조직 내/외부에서 부적절한 콘텐츠를 주고받는 행위 차단</span><span class="sxs-lookup"><span data-stu-id="335bc-230">Preventing inappropriate content from entering or leaving the organization</span></span>
    
- <span data-ttu-id="335bc-231">조직의 기밀 정보 필터링</span><span class="sxs-lookup"><span data-stu-id="335bc-231">Filtering confidential organization information</span></span>
    
- <span data-ttu-id="335bc-232">특정 개인과 주고받은 메시지 추적 또는 복사</span><span class="sxs-lookup"><span data-stu-id="335bc-232">Tracking or copying messages that are sent to or received from specific individuals</span></span>
    
- <span data-ttu-id="335bc-233">배달 전에 메시지 검사를 위해 인바운드 및 아웃바운드 메시지 리디렉션</span><span class="sxs-lookup"><span data-stu-id="335bc-233">Redirecting inbound and outbound messages for inspection before delivery</span></span>
    
- <span data-ttu-id="335bc-234">조직을 통해 전달되는 메시지에 부인 적용</span><span class="sxs-lookup"><span data-stu-id="335bc-234">Applying disclaimers to messages as they pass through the organization</span></span>
    
> [!IMPORTANT]
> <span data-ttu-id="335bc-p126">적절 한 iFilter를 설치한 후까지 메일 흐름 규칙을 사용 하 여 전자 메일 서버 (예: Adobe.pdf)에서 타사 Ifilter 설치를 검사할 수 없는 필요로 하는 첨부 파일 형식입니다. 메일 흐름 규칙에서 지원 되는 파일 형식에 대 한 자세한 내용은 [Office 365의 메시지 첨부 파일 조사를 사용 하 여 메일 흐름 규칙](https://go.microsoft.com/fwlink/p/?LinkId=271748)을 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="335bc-p126">Attachment file types that require installation of third-party iFilters on the email server (such as Adobe .pdf) cannot be inspected using mail flow rules until after an appropriate iFilter is installed. For more information about file types that are supported by mail flow rules, see [Use mail flow rules to inspect message attachments in Office 365](https://go.microsoft.com/fwlink/p/?LinkId=271748).</span></span> 
  
<span data-ttu-id="335bc-237">메일 흐름 규칙에 대 한 자세한 내용은 [메일 규칙 Exchange 2016를 흐름](https://go.microsoft.com/fwlink/p/?LinkId=296488)을 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="335bc-237">For more information about mail flow rules, see [Mail flow rules in Exchange 2016](https://go.microsoft.com/fwlink/p/?LinkId=296488).</span></span>
  
## <a name="data-loss-prevention"></a><span data-ttu-id="335bc-238">데이터 손실 방지</span><span class="sxs-lookup"><span data-stu-id="335bc-238">Data loss prevention</span></span>
<span data-ttu-id="335bc-239"><a name="bkmk_O365_MessageEncryption"> </a></span><span class="sxs-lookup"><span data-stu-id="335bc-239"></span></span>

<span data-ttu-id="335bc-p127">DLP(데이터 손실 방지) 기능은 심도 있는 콘텐츠 분석을 통해 조직의 중요한 정보를 식별하고, 모니터링하고, 보호하는 데 도움을 줍니다. DLP는 업무상 중요한 전자 메일에는 보호해야 할 기밀 데이터가 포함되어 있으므로 엔터프라이즈 메시지 시스템에 점점 더 중요한 프리미엄 기능입니다. Exchange Online의 DLP 기능을 사용하면 직원의 생산성에 영향을 주지 않고 중요한 데이터를 보호할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-p127">The data loss prevention (DLP) feature will help you identify, monitor, and protect sensitive information in your organization through deep content analysis. DLP is a premium feature that is increasingly important for enterprise message systems because business-critical email includes sensitive data that needs to be protected. The DLP feature in Exchange Online enables you to protect sensitive data without affecting worker productivity.</span></span>
  
<span data-ttu-id="335bc-243">EAC(Exchange 관리 센터) 관리 인터페이스에서 DLP 정책을 구성하면 다음과 같은 기능을 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-243">You can configure DLP policies in the Exchange admin center (EAC) management interface, which allows you to:</span></span> 
  
- <span data-ttu-id="335bc-244">PCI-DSS 데이터, 금융서비스 현대화법(Gramm-Leach-Bliley Act) 데이터 같이 특정 형식의 중요한 정보 또는 또는 로캘별 PII(개인 식별 정보)를 검색하는 데 도움을 받을 수 있는, 미리 구성된 정책 템플릿으로 시작합니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-244">Start with a pre-configured policy template that can help you detect specific types of sensitive information such as PCI-DSS data, Gramm-Leach-Bliley act data, or even locale-specific personally identifiable information (PII).</span></span>
    
- <span data-ttu-id="335bc-245">기존 전송 규칙 조건 및 작업을 완벽하게 활용하고 새 전송 규칙을 추가합니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-245">Use the full power of existing transport rule criteria and actions and add new transport rules.</span></span>
    
- <span data-ttu-id="335bc-246">DLP 정책의 효율성을 테스트한 후에 완전히 적용합니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-246">Test the effectiveness of your DLP policies before fully enforcing them.</span></span>
    
- <span data-ttu-id="335bc-247">자신의 사용자 지정 DLP 정책 템플릿과 중요한 정보 형식을 통합합니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-247">Incorporate your own custom DLP policy templates and sensitive information types.</span></span>
    
- <span data-ttu-id="335bc-248">메시지 첨부 파일, 본문 텍스트 또는 제목줄에서 중요 한 정보를 검색 하 고는 Exchange Online 역할 신뢰 수준을 조정 합니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-248">Detect sensitive information in message attachments, body text, or subject lines and adjust the confidence level at which Exchange Online acts.</span></span>
    
- <span data-ttu-id="335bc-p128">문서 지문을 사용하여 중요한 양식 데이터를 감지합니다. 문서 지문을 사용하면 전송 규칙 및 DLP 정책을 정의하는 데 사용할 수 있는 텍스트 기반 양식의 중요한 사용자 지정 정보 유형을 손쉽게 만들 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-p128">Detect sensitive form data by using Document Fingerprinting. Document Fingerprinting helps you easily create custom sensitive information types based on text-based forms that you can use to define transport rules and DLP policies.</span></span>
    
- <span data-ttu-id="335bc-251">Outlook 2016, Outlook 2013, Outlook Web App 및 장치용 OWA 사용자에게 알림을 표시하여 데이터 손실을 줄이고, 가양성 보고를 허용하여 정책의 효율성도 향상시킬 수 있는 정책 팁을 추가합니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-251">Add Policy Tips, which can help reduce data loss by displaying a notice to your Outlook 2016, Outlook 2013, Outlook Web App, and OWA for Devices users and can also improve the effectiveness of your policies by allowing false-positive reporting.</span></span> 
    
- <span data-ttu-id="335bc-252">DLP 보고서의 문제 데이터를 검토하거나, 문제 보고서 생성 작업을 사용하여 자체 보고서를 추가합니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-252">Review incident data in DLP reports or add your own specific reports by using a generate incident report action.</span></span>
    
<span data-ttu-id="335bc-253">DLP에 대한 자세한 내용은 [데이터 손실 방지](https://go.microsoft.com/fwlink/p/?LinkId=271749)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="335bc-253">For more information about DLP, see [Data Loss Prevention](https://go.microsoft.com/fwlink/p/?LinkId=271749).</span></span>
  
## <a name="journaling"></a><span data-ttu-id="335bc-254">저널링</span><span class="sxs-lookup"><span data-stu-id="335bc-254">Journaling</span></span>
<span data-ttu-id="335bc-255"><a name="bkmk_O365_MessageEncryption"> </a></span><span class="sxs-lookup"><span data-stu-id="335bc-255"></span></span>

<span data-ttu-id="335bc-p129">SMTP를 통해 메시지를 수신할 수 있는 외부 사서함으로 전자 메일의 사본을 저널링하도록 Exchange Online을 구성할 수 있습니다. 저널링은 조직이 인바운드 및 아웃바운드 전자 메일 통신을 기록하여 법적, 규정 및 조직의 준수 요구 사항에 대응하는 데 도움이 됩니다. 메시징 보존 및 준수에 대한 계획을 세울 때는 저널링 및 저널링이 조직의 준수 정책과 잘 맞는지 이해하는 것이 중요합니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-p129">You can configure Exchange Online to journal copies of emails to any external mailbox that can receive messages via SMTP. Journaling can help your organization respond to legal, regulatory, and organizational compliance requirements by recording inbound and outbound email communications. When planning for messaging retention and compliance, it's important to understand journaling and how it fits in with your organization's compliance policies.</span></span>
  
<span data-ttu-id="335bc-p130">Exchange 관리 센터 또는 원격 Windows PowerShell을 사용하여 저널 규칙을 관리할 수 있습니다. 사용자별 및 메일 그룹별 기반으로 저널링을 구성하고, 내부 메시지만, 외부 메시지만 또는 둘 다 저널링하도록 선택할 수 있습니다. 저널링된 메시지에는 원본 메시지뿐 아니라 보낸 사람, 받는 사람, 참조, 숨은 참조에 대한 정보도 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-p130">You can manage journal rules by using the Exchange admin center or remote Windows PowerShell. You can configure journaling on a per-user and per-distribution list basis, and choose to journal only internal messages, only external messages, or both. Journaled messages include not only the original message but also information about the sender, recipients, copies, and blind copies.</span></span>
  
<span data-ttu-id="335bc-262">성공적이 고 안정적인 저널링 솔루션을 보장 하려면 다음 작업을 완료 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-262">To ensure a successful and reliable journaling solution, you need to complete the following tasks:</span></span>
  
- <span data-ttu-id="335bc-263">저널링 대상은 Exchange Online 사서함 되지가 있는지 확인 하십시오.</span><span class="sxs-lookup"><span data-stu-id="335bc-263">Make sure that the journaling destination is not be an Exchange Online mailbox.</span></span>
    
- <span data-ttu-id="335bc-264">고객 디렉터리에 저널링에 사용할 SMTP 대상 전자 메일 주소에 대한 연락처 개체를 만듭니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-264">Create in the customer directory a contact object for the SMTP target email address to be used for journaling.</span></span>
    
- <span data-ttu-id="335bc-265">기본 저널 사서함을 사용할 수 없는 경우 저널 보고서를 캡처할 대체 저널 사서함으로 보조 연락처 개체를 만듭니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-265">Create a second contact object as an alternative journal mailbox to capture any journal reports when the primary journal mailbox is unavailable.</span></span>
    
- <span data-ttu-id="335bc-266">적절 한 관리, 중복, 가용성, 성능 및 성공적인 메일 수락 항상 수 있도록 SMTP 대상의 기능 수준을 유지 관리 합니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-266">Maintain proper management, redundancy, availability, performance, and functionality levels of the SMTP target to ensure successful mail acceptance always.</span></span>
    
- <span data-ttu-id="335bc-267">메시지 형식, 보낸 사람/받는 사람 정보 통합 및 적절한 내용 변환을 비롯하여 Exchange Server와 Exchange 전송에 각각의 상호 운용성을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="335bc-267">Provide respective interoperability with Exchange Server and Exchange transport including message formats, sender/recipient information integration, and appropriate content conversion.</span></span>
    
<span data-ttu-id="335bc-268">저널링에 대한 자세한 내용은 [저널링](https://go.microsoft.com/fwlink/p/?LinkId=271750)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="335bc-268">For more information about journaling, see [Journaling](https://go.microsoft.com/fwlink/p/?LinkId=271750).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="335bc-269">기능 가용성</span><span class="sxs-lookup"><span data-stu-id="335bc-269">Feature Availability</span></span>
<span data-ttu-id="335bc-270"><a name="bkmk_O365_MessageEncryption"> </a></span><span class="sxs-lookup"><span data-stu-id="335bc-270"></span></span>

<span data-ttu-id="335bc-271">Office 365 계획, 독립 실행형 옵션 및 온-프레미스 솔루션별로 기능 가용성을 확인하려면 [Exchange Online 서비스 설명](exchange-online-service-description.md)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="335bc-271">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  
