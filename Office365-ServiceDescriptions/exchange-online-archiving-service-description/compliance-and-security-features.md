---
title: Exchange Online 보관의 규정 준수 및 보안 기능
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- compliance-and-security-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7482322a-39fe-4a99-b29c-63cb1bc3cf1f
ms.openlocfilehash: b03c74e0c760cf22c12e6973a544553d119471fe
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132742"
---
# <a name="compliance-and-security-features-in-exchange-online-archiving"></a>Exchange Online 보관의 규정 준수 및 보안 기능

## <a name="compliance-features-in-exchange-online-archiving"></a>Exchange Online Archiving의 규정 준수 기능

다음 섹션에서는 Microsoft Exchange Online Archiving의 규정 준수 기능을 설명합니다.
  
### <a name="retention-policies"></a>보존 정책

Exchange Online Archiving은 전자 메일 및 기타 통신과 관련한 조직의 부담을 줄이는 데 도움을 주는 보존 정책을 제공합니다. 이러한 정책을 사용하면 관리자가 사용자 사서함의 특정 폴더에 보존 설정을 적용할 수 있습니다. 또한 관리자는 사용자에 게 보존 정책 메뉴를 제공 하 고 Outlook 2010 이상 또는 웹용 Outlook을 사용 하 여 특정 항목, 대화 또는 폴더에 정책을 적용 하도록 할 수 있습니다. Exchange Online Archiving에서 관리자는 온-프레미스 인프라의 보존 정책을 관리합니다.
  
Exchange Online Archiving offers two types of policies: archive and delete. Both types can be applied to the same item or folder. For example, a user can tag an email message so that it is automatically moved to the personal archive in a specified number of days and deleted after another span of days.
  
Outlook 2010 이상 및 웹용 Outlook을 사용 하면 사용자가 폴더, 대화 또는 개별 메시지에 보존 정책을 적용할 수 있으며, 적용 된 보존 정책 및 메시지의 예상 삭제 날짜를 볼 수도 있습니다. 다른 전자 메일 클라이언트 사용자의 경우 관리자가 프로비전한 서버 쪽 보존 정책에 따라 전자 메일이 삭제되거나 보관되도록 할 수는 있지만 Outlook 2010 및 Outlook Web App에서와 같은 수준으로 메시지를 보거나 제어할 수는 없습니다.
  
The retention policy capabilities offered in Exchange Online Archiving are the same as those offered in Exchange Server 2010 Service Pack 2 (SP2) and later. Administrators can manage retention policies from on-premises Exchange Server 2010 and later environments. Managed Folders, an older approach to messaging records management that was introduced in Exchange 2007, are not available in and not compatible with Exchange Online Archiving. For more details, see [Retention Tags and Retention Policies](https://go.microsoft.com/fwlink/p/?LinkID=314153).
  
### <a name="in-place-hold-and-litigation-hold"></a>원본 위치 유지 및 소송 보존

When a reasonable expectation of litigation exists, organizations are required to preserve electronically stored information (ESI), including email that's relevant to the case. This expectation can occur before the specifics of the case are known, and preservation is often broad. Organizations may preserve all email related to a specific topic, or all email for certain individuals.
  
Exchange Online에서는 원본 위치 유지 또는 소송 보존 기능을 사용하여 다음과 같은 목표를 달성할 수 있습니다.
  
- 사용자를 유지 상태로 설정하고 사서함 항목을 변경할 수 없는 상태로 보존
    
- 사용자나 MRM과 같은 자동 삭제 프로세스에 의해 삭제된 사서함 항목 보존
    
- 원본 항목의 복사본을 저장하여 사서함 항목 변조 또는 사용자/자동 프로세스에 의한 변경 방지
    
- 무기한 또는 특정 기간 동안 항목 보존
    
- MRM을 일시 중단할 필요 없이 보존 항목을 사용자에 대해 투명하게 유지 가능
    
- 원본 위치 eDiscovery를 사용하여 보존된 항목을 비롯한 사서함 항목 검색
    
또한 원본 위치 유지 기능을 통해 다음 작업을 수행할 수 있습니다.
  
- 지정한 조건과 일치하는 항목 검색 및 보존
    
- 다른 사례 또는 조사를 위해 여러 원본 위치 유지 상태로 사용자 배치
    
> [!NOTE]
> 사서함에 원본 위치 유지 또는 소송 보존을 적용하면 기본 사서함과 보관 사서함 둘 다 보류됩니다. 
  
자세한 내용은 [원본 위치 유지 및 소송 보존](https://go.microsoft.com/fwlink/p/?LinkId=271746)을 참조하세요.
  
> [!NOTE]
> Exchange Online Archiving 사용자의 복구 가능한 항목 폴더의 기본 할당량은 100 GB입니다. 
  
### <a name="in-place-ediscovery"></a>원본 위치 eDiscovery

Exchange Online Archiving supports In-Place eDiscovery for searching the contents of mailboxes in an organization. Using the Exchange admin center or remote Windows PowerShell from an on-premises Exchange 2013 server, administrators or authorized Discovery managers can search a variety of mailbox items - including email messages, attachments, calendar appointments, tasks, and contacts. In-Place eDiscovery can search simultaneously across primary mailboxes and archives. Rich filtering capabilities include sender, receiver, message types, sent date, received date, carbon copy, and blind carbon copy, along with Keyword Query Language (KQL) syntax. For more details, see [In-Place eDiscovery](https://go.microsoft.com/fwlink/p/?LinkId=314169).
  
The Exchange admin center and remote Windows PowerShell can be used to search up to 5,000 mailboxes at a time in an In-Place eDiscovery search. For details about using remote Windows PowerShell to run In-Place eDiscovery searches, see [New-MailboxSearch](https://go.microsoft.com/fwlink/p/?LinkId=314170). 
  
> [!NOTE]
> In remote Windows PowerShell, the  `Search-Mailbox` cmdlet can be used to search more than 5,000 mailboxes. For details about searching large numbers of mailboxes using remote Windows PowerShell, see [Search-Mailbox](https://go.microsoft.com/fwlink/p/?LinkId=314171). 
  
Results of an In-Place eDiscovery search can be previewed in the Exchange admin center, exported to a .pst file, or copied to a special type of mailbox, called a discovery mailbox. Administrators or compliance officers can connect to the discovery mailbox to review messages. For details, see [Create an In-Place eDiscovery Search](https://go.microsoft.com/fwlink/p/?LinkId=314172).
  
> [!NOTE]
> When copying search results for an In-Place eDiscovery search performed across on-premises and cloud-based mailboxes or archives, you must select an on-premises discovery mailbox. Messages from the on-premises primary mailbox and the cloud-based archive are copied to the on-premises discovery mailbox. 
  
Administrators can also search for and delete inappropriate email messages sent to multiple mailboxes across their organizations. For example, if confidential salary information was accidentally sent to all employees, an administrator can delete the email from the users' mailboxes. This type of search is not available in the Exchange admin center. It must be performed using Remote PowerShell. For details on how to delete messages from users' mailboxes, see [Search and Delete Messages](https://go.microsoft.com/fwlink/p/?LinkId=314173).
  
## <a name="security-features-in-exchange-online-archiving"></a>Exchange Online Archiving의 보안 기능

다음 섹션에서는 Microsoft Exchange Online Archiving의 보안 기능을 설명합니다.
  
### <a name="encryption-between-on-premises-servers-and-exchange-online-archiving"></a>온-프레미스 서버와 Exchange Online Archiving 간 암호화

전자 메일 서버 간 연결을 암호화하는 데는 TLS가 사용되어 스푸핑이 방지되도록 하고 전송 중인 메시지에 기밀성을 제공합니다. TLS는 Exchange Online 보관용 Microsoft 데이터 센터에 대 한 온-프레미스 메일 서버 트래픽을 보호 하는 데도 사용 됩니다.
  
### <a name="encrypting-between-clients-and-exchange-online-archiving"></a>클라이언트와 Exchange Online Archiving 간 암호화

보안 향상을 위해 Exchange Online Archiving에 대한 클라이언트 연결에는 다음과 같은 암호화 방법이 사용됩니다.
  
- SSL은 TCP 포트 443을 사용 하 여 Outlook, 웹용 Outlook 및 Exchange 웹 서비스 트래픽의 보안을 유지 하는 데 사용 됩니다.
    
- Exchange Online Archiving이 도입된다고 해서 온-프레미스 서버에 대한 클라이언트 연결이 변경되지는 않습니다.
    
### <a name="encryption-smime-and-pgp"></a>암호화: S/MIME 및 PGP

Exchange Online Archiving will store Secure/Multipurpose Internet Mail Extensions (S/MIME) messages. However, Exchange Online Archiving does not host S/MIME functions or host the public keys, nor does it provide key repository, key management, or key directory services because all of these services attach to the on-premises Exchange infrastructure.
  
마찬가지로, Exchange Online Archiving에서는 클라이언트 쪽, 타사 암호화 솔루션(예: PGP(Pretty Good Privacy))을 사용하여 암호화된 메시지를 저장합니다.
  
### <a name="information-rights-management"></a>정보 권한 관리

Exchange Online Archiving does not provide hosted Information Rights Management (IRM) services, but administrators can use on-premises Active Directory Rights Management Services (AD RMS). If an AD RMS server is deployed, Outlook can communicate directly with that server, enabling users to compose and read IRM-protected messages. If interoperability between the AD RMS server and the on-premises Exchange environment is configured, users will be able to compose and read IRM-protected messages.
  
#### <a name="support-for-irm-in-outlook-on-the-web"></a>웹용 Outlook의 IRM 지원

사용자는 Outlook에서와 마찬가지로, 웹에서 Outlook을 사용 하 여 IRM으로 보호 된 메시지를 기본적으로 읽고 만들 수 있습니다. Internet Explorer, Firefox, Safari 및 Chrome을 통해 웹에서 Outlook의 IRM으로 보호 된 메시지에 액세스할 수 있습니다 (플러그 인 필요 없음). 메시지에는 전체 텍스트 검색, 대화 보기 및 미리 보기 창이 포함됩니다. 이 기능이 가능하도록 Active Directory Rights Management Services 서버와 온-프레미스 Exchange 환경 간의 상호 운용성이 구성되어야 합니다.
  
#### <a name="irm-search"></a>IRM 검색

헤더, 제목, 본문 및 첨부 파일을 비롯하여 IRM으로 보호된 메시지는 인덱싱되며 검색 가능합니다. 사용자는 Outlook 및 웹용 Outlook에서 IRM으로 보호 된 항목을 검색할 수 있으며, 관리자는 원본 위치 eDiscovery 또는 **검색-사서함** cmdlet을 사용 하 여 irm으로 보호 된 항목을 검색할 수 있습니다.
  
### <a name="auditing"></a>감사

Exchange Online Archiving에서는 다음과 같은 두 가지 유형의 기본 제공 감사 기능을 제공합니다.
  
- **관리자 감사 로깅** 관리자 감사 로깅을 통해 고객은 RBAC 역할이나 Exchange 정책 및 설정에 대한 변경 내용을 비롯하여 Exchange Online Archiving 환경에서 관리자가 수행한 변경 내용을 추적할 수 있습니다. 
    
- **사서함 감사 로깅** 사서함 감사 로깅을 통해 고객은 사서함 소유자가 아닌 다른 사용자에 의한 사서함 액세스를 추적할 수 있습니다. 
    
Several predefined audit reports are available in the Exchange admin center, including Administrator Role Changes, Litigation Hold, and Non-Owner Mailbox Access. Administrators can filter reports by date and role, and they can export all audit events for specified mailboxes in XML format for long-term retention or custom reporting.
  
Administrator audit logging is on by default, and mailbox audit logging is off by default. Administrators can use remote Windows PowerShell to enable mailbox audit logging for some or all mailboxes in their organization. For more information, see [Auditing Reports](https://go.microsoft.com/fwlink/p/?LinkId=314175).
  
## <a name="feature-availability"></a>기능 가용성

계획, 독립 실행형 옵션 및 온-프레미스 솔루션 별로 기능 가용성을 확인 하려면 [Exchange Online 보관 서비스 설명을](exchange-online-archiving-service-description.md)참조 하세요.
  

