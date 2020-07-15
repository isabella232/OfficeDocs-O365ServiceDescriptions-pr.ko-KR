---
title: 받는 사람
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-recipients
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: da22b03a-c981-49c6-9928-4312c2c5e2ee
description: 이 항목에서는 Microsoft Exchange Online에 포함된 받는 사람 관련 기능에 대해 설명합니다. 설명에는 전자 메일, 연락처, 메일 그룹 및 달력/예약 기능이 포함됩니다.
ms.openlocfilehash: a2d1f37bf4f86399522573d18177f6c397fd761c
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132642"
---
# <a name="recipients"></a>받는 사람

This topic describes recipient-related features included with Microsoft Exchange Online. This includes email, contacts, distribution groups, and calendar and scheduling capabilities.
  
## <a name="email"></a>전자 메일

Every Microsoft Exchange Online subscriber receives a mailbox, and specialty mailboxes are available for scheduling facilities resources (such as conference rooms) and for multiuser access to shared email addresses. Maximum storage limits apply to most mailboxes, and administrators can control allowable mailbox sizes. Automated notifications and restrictions can alert users when their mailboxes are nearing, or at, capacity. Exchange Online also has several types of message limitations—message size, message rate, and recipient list limits. Details of all these features and limits are provided below.
  
> [!NOTE]
> 범용 주소는 Exchange Online에서 더 이상 지원되지 않습니다. 잠재적 스팸 메시지 로부터 보호 하기 위해 받는 사람 필터링이 적용 되므로 조직에 없는 전자 메일 주소는 거부 됩니다. 
  
### <a name="mailbox-types-storage-limits-and-capacity-alerts"></a>사서함 유형, 저장소 제한 및 용량 경고

The amount of mailbox storage available to a user and the default mailbox size are determined by the mailbox type and the user's subscription license. Administrators can reduce maximum mailbox sizes per user or globally. Exchange Online also provides notifications when a user's mailbox is nearing, or at, capacity.
  
자세한 내용은 [Exchange Online 제한](exchange-online-limits.md)항목의 "사서함 저장소 제한" 및 "용량 경고" 섹션을 참조 하십시오.
  
### <a name="mailtips"></a>메일 설명

MailTips are automated, informative messages that appear above the To: line while users are composing or addressing a message. They are designed to help prevent accidental delivery, policy violations, or unnecessary non-delivery reports (NDRs). For example, MailTips can generate an alert if senders try to send messages to overly large groups, to groups that contain external recipients, or to a distribution group that is moderated or restricted. For more information, see [MailTips](https://go.microsoft.com/fwlink/p/?LinkId=401472).
  
### <a name="delegate-access"></a>대리인 액세스

Exchange Online은 사용자가 다른 사람에게 자신의 전자 메일 및 일정을 관리할 수 있게 하는 대리인 액세스를 지원합니다. 대리인 액세스는 일반적으로 관리자와 비서 간에 사용되는 기능으로, 비서가 관리자의 받는 메일 메시지를 처리하고 일정을 관리하는 경우 사용됩니다. 대리인 액세스는 Outlook 또는 웹용 Outlook의 Exchange Online 사용자나 Exchange 관리 센터의 관리자가 사용 하도록 설정할 수 있습니다. 
  
대리인은 2가지 유형의 액세스를 사용할 수 있습니다.
  
- **다른 사람 대신 보내기** 대리인은 전자 메일 메시지를 작성한 후 보낸 사람 필드에 다른 사람의 이름을 입력할 수 있습니다. 보낸 사람 필드에는 "[대리인 이름]이(가) 다음 사람 대신 보냄: [다른 사람 이름]"으로 표시됩니다. 
    
- **Send As permissions** The delegate can send messages from the other person's mailbox as if the delegate were the mailbox owner. This scenario is common where there is a shared mailbox and several employees send email messages from that shared mailbox instead of from their Exchange Online accounts. 
    
액세스 권한 위임에 대한 자세한 내용은 [받은 사람의 권한 관리](https://technet.microsoft.com/library/jj919240%28v=exchg.160%29.aspx)를 참조하세요.
  
### <a name="inbox-rules"></a>받은 편지함 규칙

사용자는 Exchange Online에서 받은 편지함 규칙을 만들어 메시지를 받았을 때 조건을 기반으로 한 특정 작업을 메시지에 자동으로 수행할 수 있습니다. 예를 들어 특정 메일 그룹으로 보낸 모든 메일은 자동으로 특정 폴더로 이동되도록 규칙을 만들 수 있습니다. 사용자는 Outlook 또는 웹용 Outlook에서 받은 편지함 규칙을 관리 합니다. 관리자는 서버 쪽 전달 및/또는 서버 쪽 자동 회신을 사용하지 않도록 설정하여 특정 유형의 받은 편지함 규칙을 차단할 수 있습니다. 예를 들어 서버 쪽 전자 메일 전달을 사용하지 않도록 설정할 경우 사용자는 자동으로 전자 메일을 개인 계정에 전달할 수 없습니다. 마찬가지로 서버 쪽 자동 회신을 사용하지 않도록 설정할 경우 외부에서 이 답장을 사용해 유효한 전자 메일 주소를 식별할 수 없습니다. 이러한 변경 내용은 원격 Windows Powershell을 통해 이루어집니다.
  
### <a name="clutter"></a>Clutter

Clutter is designed to help you focus on the most important messages in your inbox. It uses machine learning to de-clutter your inbox by moving lower priority messages out of your way and into a new Clutter folder. Clutter respects your existing email rules, so if you have created rules to organize your email those rules continue to be applied and Clutter won't act on those messages. Clutter is disabled by default for your inbox. To learn more, see [De-clutter your inbox in Office 365](https://www.microsoft.com/en-us/microsoft-365/blog/2014/11/11/de-clutter-inbox-office-365/).
  
### <a name="connected-accounts"></a>연결된 계정

연결 된 계정 기능을 사용 하면 Exchange Online 사용자가 외부 전자 메일 계정 (예: 개인 계정)을 Exchange Online의 내부 전자 메일 계정에 연결한 다음, 웹에서 Outlook을 사용 하 여 모든 메시지를 한 곳에서 상호 작용할 수 있습니다. 연결 된 계정은 웹에서 Outlook에 로그인 시 자동으로 동기화 합니다. 사용자는 웹에서 Outlook의 계정을 수동으로 동기화 할 수도 있습니다. 관리자는 [Exchange 관리 센터](https://go.microsoft.com/fwlink/?LinkID=785297&amp;clcid=0x409)를 통해 특정 사용자 또는 모든 사용자에 대해이 기능을 사용 하거나 사용 하지 않도록 설정할 수 있습니다.
  
### <a name="inactive-mailboxes"></a>비활성 사서함

Exchange Online provides the capability to preserve the contents of deleted mailboxes indefinitely. This feature is called inactive mailboxes. A mailbox becomes inactive when an In-Place Hold or a Litigation Hold is placed on the mailbox before it's deleted. This results in the contents of the mailbox being preserved indefinitely. Administrators, compliance officers, or record managers can use the In-Place eDiscovery feature in Exchange Online to access the contents of an inactive mailbox.
  
비활성 사서함을 사용하도록 설정하려면 삭제하기 전 사서함에 원본 위치 유지 또는 소송 보존 기능을 적용할 수 있도록 사서함에 Exchange Online 보관 구독이 포함되어 있거나 Exchange Online(계획 2) 라이선스가 할당되어 있어야 합니다.
  
> [!IMPORTANT]
> If a hold isn't placed on a mailbox before it's deleted, the contents of the mailbox will not be preserved or discoverable. The mailbox can be recovered within 30 days of deletion, but the mailbox and its contents will be permanently deleted after 30 days if it isn't recovered. 
  
자세한 내용은 다음 항목을 참조하십시오.
  
- [Exchange Online에서 비활성 사서함 관리](https://go.microsoft.com/fwlink/p/?LinkId=286991)
    
- [원본 위치 유지 및 소송 보존](https://go.microsoft.com/fwlink/p/?LinkId=271746)
    
- [원본 위치 eDiscovery](https://go.microsoft.com/fwlink/p/?LinkId=271747)
    
## <a name="contacts-and-distribution-groups"></a>연락처 및 메일 그룹

### <a name="offline-address-book"></a>오프라인 주소록

오프 라인 주소록 기능은 Outlook GAL (전체 주소 목록)에서 사용할 수 있는 Active Directory 정보의 스냅숏을 제공 합니다. 이러한 정보는 사용자가 오프라인으로 작업할 때 사용할 수 있도록 로컬에서 캐시됩니다.
  
### <a name="address-book-policies"></a>주소록 정책

Exchange Online에서는 주소록 정책을 지원 합니다. ABP(주소록 정책)를 사용하면 사용자를 특정 그룹으로 분할하여 조직의 GAL(전체 주소 목록)에 대한 사용자 지정 보기를 제공할 수 있습니다. ABP를 만들 때 GAL, OAB(오프라인 주소록), 방 목록 및 하나 이상의 주소 목록을 정책에 할당합니다. 그런 다음 ABP를 사서함 사용자에 게 할당 하 여 Outlook 및 웹용 Outlook에서 사용자 지정 된 GAL에 대 한 액세스 권한을 제공할 수 있습니다. 관리자는 원격 Windows PowerShell을 사용하여 주소록 정책을 구성할 수 있습니다. 주소록 정책에 대한 자세한 내용은 [Exchange Online의 주소록](https://go.microsoft.com/fwlink/p/?LinkId=394203)을 참조하세요.
  
### <a name="address-lists"></a>주소 목록

Exchange Online은 주소 목록 및 Gal의 사용자 지정을 지원 합니다. GAL은 메일 사용이 가능한 모든 사용자, 메일 그룹 및 외부 연락처의 조직 전체 디렉터리입니다. 관리자는 디렉터리 동기화 도구 또는 원격 Windows PowerShell을 사용 하 여 GAL의 사용자, 메일 그룹 및 연락처를 숨길 수 있습니다.
  
### <a name="hierarchical-address-books"></a>계층 구조 주소록

 Hierarchical address books allow end users to browse for recipients in their Exchange organization using an organizational hierarchy. Administrators can customize the address book by seniority and rank rather than alphabetical listings. 
  
### <a name="distribution-groups-global"></a>메일 그룹(전체)

메일 그룹(또는 메일 목록)은 회사에서 모든 사용자가 사용할 수 있는 사용자, 연락처, 다른 메일 그룹을 모아놓은 것입니다. 사용자가 메일 그룹 별칭에 전자 메일을 보내면 해당 그룹에 있는 모든 사람이 메시지를 받게 됩니다. 메일 그룹은 개인이 Outlook에 만든 개인 메일 그룹과 비슷하지만, 구성원 목록을 회사 전체에서 사용할 수 있다는 점만 다릅니다. 관리자는 Exchange 관리 센터에서 메일 그룹을 만듭니다. 이렇게 만든 그룹은 Exchange Online을 통해 온-프레미스 Active Directory에서 동기화할 수도 있습니다. Outlook의 GAL에 표시 됩니다. Exchange Online은 아래 설명된 기능을 비롯한 고급 메일 그룹 기능을 지원합니다.
  
- **Restricted distribution groups** By default, anyone can send emails to any distribution group. Administrators can change permissions to allow only specific individuals to send emails to a particular group—for example, to discourage inappropriate use of large distribution lists. Administrators can also block external sources from sending email to distribution groups to help prevent spam. For distribution groups that are synchronized from on-premises Active Directory using the Directory Synchronization tool, the attributes for restriction are synchronized to the cloud automatically. For more information, see [Manage Distribution Groups](https://technet.microsoft.com/library/mt577270%28v=exchg.160%29.aspx).
    
- **Dynamic distribution groups** The membership list for a dynamic distribution group (also known as a dynamic distribution list, or query-based distribution list) is calculated every time a message is sent to the group. This calculation is based on filters and conditions that the administrator defines. They are managed in Exchange Online through remote Windows PowerShell. For more information about dynamic distribution groups, see [Manage Dynamic Distribution Groups](https://technet.microsoft.com/library/bb123722%28v=exchg.160%29.aspx).
    
    > [!IMPORTANT]
    > The Office 365 Directory Synchronization tool ignores dynamic distribution groups in on-premises Active Directory, and does not synchronize these to Exchange Online. Organizations that use the Directory Synchronization tool should use a naming convention that avoids conflicts between the regular distribution groups that are managed on-premises and the dynamic distribution groups that are managed in Exchange Online. 
  
- **Moderated distribution groups** Administrators can select a moderator to regulate the flow of messages to a distribution group. With moderated distribution groups, anyone can email the distribution group alias, but before the message is delivered to the members of the group, a moderator must review and approve it. For more information about moderation, see the Message Approval section in [Manage Distribution Groups](https://technet.microsoft.com/library/mt577270%28v=exchg.160%29.aspx).
    
- **Self-Service distribution groups** Administrators can give users the ability to manage their own distribution group membership from a web-based interface. Users can be given permissions to create, delete, join, or leave distribution groups. These capabilities are enabled by default for all Exchange Online users. Administrators can disable them so that only the IT department can manage distribution groups, if desired. They can also create naming policies to standardize and manage the names of distribution groups that their users create. For example, they can add a specific prefix or suffix to the distribution group name when it is created, or block specific words from being used in the group's name. 
    
    > [!IMPORTANT]
    > Self-service capabilities are not available for distribution groups that are synchronized from on-premises Active Directory to Exchange Online. Organizations that use Directory Synchronization should use a naming convention that avoids conflicts between distribution groups that are managed on-premises and distribution groups that are managed in the cloud. 
  
### <a name="external-contacts-global"></a>외부 연락처(전체)

외부 연락처는 지정된 조직의 외부에서 작업하는 사람에 대한 정보를 기록한 것입니다. 외부 연락처는 개인이 Outlook에 만든 개인 연락처와 비슷하지만, 회사 전체에서 사용할 수 있다는 점만 다릅니다. 관리자는 Exchange 관리 센터 또는 원격 Windows PowerShell을 사용하여 외부 연락처를 만듭니다. 이렇게 만든 연락처는 Exchange Online을 통해 온-프레미스 Active Directory에서 동기화할 수도 있습니다. Outlook의 GAL에 표시 됩니다.
  
외부 연락처에 대한 자세한 내용은 [Exchange Online에서 조직 관계 만들기](https://technet.microsoft.com/library/jj916671%28v=exchg.150%29.aspx)를 참조하세요.
  
## <a name="calendar-and-scheduling"></a>달력 및 일정

### <a name="resource-mailboxes"></a>리소스 사서함

회의실과 물리적 장비 등을 위한 리소스 사서함은 회사의 회의실이나 기타 시설 또는 리소스를 나타냅니다. 사용자는 Outlook 또는 웹용 Outlook의 모임 요청에 리소스의 전자 메일 별칭을 추가 하 여 대화방 이나 리소스를 예약할 수 있습니다. 회의실 및 리소스는 Outlook 및 웹용 Outlook의 GAL에 표시 됩니다.
  
Administrators create resource mailboxes using the Exchange admin center or remote Windows PowerShell. The mailboxes can also be synchronized with Exchange Online from on-premises Active Directory.
  
리소스 사서함에 대한 자세한 내용은 다음을 참조하십시오.
  
- [대화방 사서함 만들기 및 관리](https://go.microsoft.com/fwlink/?LinkId=717533&amp;clcid=0x409)
    
- [장비 사서함 관리](https://go.microsoft.com/fwlink/?LinkId=717534)
    
### <a name="conference-room-management"></a>회의실 관리

Exchange Online includes the Resource Booking Attendant (RBA), which automates scheduling of conference rooms and other resources. A resource mailbox that is RBA-configured accepts, declines, or acknowledges meeting requests from a meeting organizer based on the resource's calendar availability. 
  
관리자는 웹에서 Outlook의 자동 전화 회의 대화방 응답을 사용자 지정 하 고 예약 정책을 구성할 수 있습니다. 이러한 정책에는 누가 리소스의 일정을 예약할 수 있는지, 언제 예약할 수 있는지, 리소스의 일정에 어떤 모임 정보가 표시되는지, 허용되는 일정 충돌의 비율 등이 포함됩니다. 관리자는 리소스 예약 도우미를 사용하지 않도록 설정하고 특정 사용자를 할당하여 수동으로 회의실에 대한 모임 요청을 관리하게 할 수 있습니다.
  
관리자는 반드시 원격 Windows Powershell을 통해 RBA 설정을 정의하고 관리해야 합니다.
  
### <a name="out-of-office-replies"></a>부재 중 회신

Out-of-office messages are automatic replies to incoming messages that Exchange Online sends on behalf of a user. Users can schedule out-of-office messages in advance, with specific start and end times, and can configure separate out-of-office messages for internal and external recipients. They can also set out-of-office messages from mobile devices that support this Exchange ActiveSync feature. Junk-email and mailing-list awareness within Exchange Online prevents users from sending external out-of-office messages to extended mailing lists and potential spammers. Administrators can also prevent users from sending out-of-office messages to external users using remote Windows PowerShell.
  
### <a name="calendar-sharing"></a>일정 공유

사용자는 다음 두 가지 방법을 통해 개인 일정을 공유할 수 있습니다.
  
- **페더레이션 일정 공유** 페더레이션은 페더레이션 공유를 지원하는 기본 트러스트 인프라를 나타내며, Exchange 사용자가 다른 외부 페더레이션 조직의 받는 사람과 약속 있음/없음 일정 데이터 및 연락처 정보를 쉽게 공유할 수 있는 방법입니다. 여기에는 Exchange Online 조직이나 Exchange Server 2010 또는 Exchange Server 2013 온-프레미스를 실행하는 조직이 포함됩니다. Microsoft 서비스를 만들 때 exchange Online 관리자는 모든 Exchange Online 고객에 대해이 트러스트를 미리 구성 했기 때문에 Microsoft Federation Gateway와의 트러스트를 설정할 필요가 없습니다. 기본 공유 정책을 사용 하면 사용자가 웹에서 Outlook 또는 Outlook 2010에서 일정 공유 초대를 보낼 수 있습니다. 관리자는 원격 Windows PowerShell을 사용해 이 정책을 사용하지 않도록 설정하거나 사용자가 공유하는 약속 있음/없음 일정 데이터의 수준을 구성할 수 있습니다. 관리자는 또한 다른 페더레이션 조직과 조직 대 조직 관계를 생성하여, 개별 사용자가 공유 초대를 만들 필요 없이 모든 사용자에 대한 약속 있음/없음 정보를 원하는 수준으로 조직 서로 간에 볼 수 있도록 허용할 수 있습니다. 관리자가 정의한 공유 정책 및/또는 조직 대 조직 관계의 범위 내에서 사용자는 각자의 공유 세부 정보를 제한할 수 있습니다. 
    
- **인터넷 일정 공유** Exchange Online에서 사용자는 조직 내부 또는 외부 사람의 익명 액세스에 대해 iCal 형식을 사용하여 자신의 일정을 게시할 수 있습니다. Exchange나 다른 플랫폼, 또는 단순히 웹 브라우저의 사용자에게 보낼 수 있습니다. Exchange Online 사용자는 또한 다른 사람이 iCal을 통해 인터넷 위치에 게시 한 일정을 구독할 수 있습니다. 이 개인 일정 공유는 관리자가 구성하고 조직 대 조직 약속 있음/없음 공유를 제공하는 페더레이션 일정 공유와는 다릅니다. 관리자가 허용 되는 공유 정책을 설정 및 적용 하기 전 까지는 사용자가 일정 데이터를 iCal 형식으로 게시할 수 없습니다. 관리자는 원격 Windows PowerShell을 사용하여 조직 내 사용자에 대해 iCal 게시 및 iCal 구독을 사용하지 않도록 설정할 수 있습니다.
    
페더레이션 공유에 대한 자세한 내용은 [Exchange Online의 공유](https://go.microsoft.com/fwlink/p/?LinkId=271774)를 참조하세요.
  
### <a name="outlook-2010-room-finder"></a>Outlook 2010 회의실 찾기

Exchange Online supports the Room Finder feature of Outlook 2010, which arranges rooms into lists (for example, a list called "Building 5 rooms") to make it easier to find a nearby room when scheduling a meeting. To appear in the room list, a distribution group must be specially marked using one of two methods: 
  
- 새 회의실 목록은 원격 Windows Powershell을 사용하여 만들 수 있습니다. 
    
- 회의실만 포함된 모든 메일 그룹은 원격 Windows PowerShell을 통해 회의실 목록으로 변환할 수 있습니다.
    
## <a name="feature-availability"></a>기능 가용성

계획, 독립 실행형 옵션 및 온-프레미스 솔루션 별로 기능 가용성을 확인 하려면 [Exchange Online 서비스 설명을](exchange-online-service-description.md)참조 하세요.
  