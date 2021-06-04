---
title: 2013의 규정 준수 및 보안 Exchange Online Archiving
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- compliance-and-security-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7482322a-39fe-4a99-b29c-63cb1bc3cf1f
description: 이 문서를 읽고 보관에서 사용할 수 있는 준수 기능에 대해 Microsoft Exchange Online 있습니다.
ms.openlocfilehash: 0d424823116dd670c81628eaf85d1d553fdb5b8e
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653090"
---
# <a name="compliance-and-security-features-in-exchange-online-archiving"></a>2013의 규정 준수 및 보안 Exchange Online Archiving

## <a name="compliance-features-in-exchange-online-archiving"></a>Exchange Online Archiving의 규정 준수 기능

이 문서에서는 보관의 규정 Microsoft Exchange Online 설명합니다.
  
### <a name="retention-policies"></a>보존 정책

Exchange Online Archiving은 전자 메일 및 기타 통신과 관련한 조직의 부담을 줄이는 데 도움을 주는 보존 정책을 제공합니다. 이러한 정책을 사용하면 관리자가 사용자 사서함의 특정 폴더에 보존 설정을 적용할 수 있습니다. 관리자는 또한 사용자에게 보존 정책 메뉴를 제공하고 웹에서 Outlook 2010 이상 또는 Outlook 사용하여 특정 항목, 대화 또는 폴더에 정책을 적용하도록 할 수 있습니다. Exchange Online Archiving에서 관리자는 온-프레미스 인프라의 보존 정책을 관리합니다.
  
Exchange Online Archiving은 보관과 삭제라는 두 가지 유형의 정책을 제공합니다. 이 두 가지 유형을 동일한 항목이나 폴더에 적용할 수 있습니다. 예를 들어, 사용자가 지정한 기간(일)이 지나면 자동으로 전자 메일 메시지가 보관 사서함으로 이동되고 또 다른 지정한 기간(일)이 지나면 삭제되도록 전자 메일 메시지에 태그를 지정할 수 있습니다.
  
웹에서 Outlook 2010 이상 및 Outlook 사용하여 사용자는 폴더, 대화 또는 개별 메시지에 보존 정책을 적용할 수 있으며 적용된 보존 정책 및 메시지의 예상 삭제 날짜를 볼 수도 있습니다. 다른 전자 메일 클라이언트 사용자의 경우 관리자가 프로비전한 서버 쪽 보존 정책에 따라 전자 메일이 삭제되거나 보관되도록 할 수는 있지만 Outlook 2010 및 Outlook Web App에서와 같은 수준으로 메시지를 보거나 제어할 수는 없습니다.
  
Exchange Online Archiving에서 제공하는 보존 정책 기능은 Exchange Server 2010 SP2(서비스 팩 2) 이상에서 제공하는 기능과 동일합니다. 관리자는 온-프레미스 Exchange Server 2010 이상 환경에서 보존 정책을 관리할 수 있습니다. Exchange 2007에 도입되었던 이전의 메시징 레코드 관리 방법인 관리 폴더는 Exchange Online Archiving에서 사용할 수 없으며 Exchange Online Archiving과 호환되지 않습니다. Exchange Server 2007에서 제공했던 기존의 메시징 레코드 관리 접근 방식인 관리되는 폴더는 사용할 수 없습니다.
  
### <a name="in-place-hold-and-litigation-hold"></a>원본 위치 유지 및 소송 보존

소송 가능성이 존재하는 경우 조직은 해당 사례와 관련된 전자 메일을 비롯한 ESI(전자적으로 저장된 정보)를 보존해야 합니다. 이러한 가능성은 사례의 세부 사항이 알려지기 전에 발생할 수 있으며 많은 경우 보존 범위가 넓습니다. 조직에서는 특정 항목과 관련된 모든 전자 메일 또는 특정 개인의 모든 전자 메일을 보존할 수 있습니다.
  
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
  
자세한 내용은 [원본 위치 유지 및 소송 보존](/exchange/security-and-compliance/in-place-and-litigation-holds)을 참조하세요.
  
> [!NOTE]
> Exchange Online Archiving 사용자의 복구 가능한 항목 폴더의 기본 할당량은 100 GB입니다. 
  
### <a name="in-place-ediscovery"></a>원본 위치 eDiscovery

Exchange Online Archiving에서는 조직의 사서함 콘텐츠 검색에 대해 원본 위치 eDiscovery를 지원합니다. 온-프레미스 Exchange 2013 서버에서 Exchange 관리 센터 또는 원격 Windows PowerShell을 사용하여 관리자나 권한 있는 Discovery 관리자는 전자 메일 메시지, 첨부 파일, 일정 약속, 작업, 연락처 등 다양한 사서함 항목을 검색할 수 있습니다. 원본 위치 eDiscovery는 기본 사서함 및 보관 사서함을 동시에 검색할 수 있습니다. KQL(Keyword Query Language) 구문과 함께, 다양한 필터링 기능에는 보낸 사람, 받는 사람, 메시지 유형, 보낸 날짜, 받은 날짜, 참조 및 숨은 참조가 있습니다. 자세한 내용은 [원본 위치 eDiscovery](/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery)를 참조하십시오.
  
Exchange 관리 센터 및 원격 Windows PowerShell을 사용하여 원본 위치 eDiscovery 검색에서 최대 5,000개의 사서함을 한 번에 검색할 수 있습니다. 원격 Windows PowerShell을 사용하여 원본 위치 eDiscovery 검색을 실행하는 방법에 대한 자세한 내용은 [New-MailboxSearch](/powershell/module/exchange/new-mailboxsearch)를 참조하세요. 
  
> [!NOTE]
> 원격 Windows PowerShell에서  `Search-Mailbox` cmdlet을 사용하여 5,000개가 넘는 사서함을 검색할 수 있습니다. 원격 Windows PowerShell을 사용하여 많은 수의 사서함을 검색하는 방법에 대한 자세한 내용은 [Search-Mailbox](/powershell/module/exchange/search-mailbox)를 참조하세요. 
  
원본 위치 eDiscovery 검색의 결과는 Exchange 관리 센터에서 미리 보거나 .pst 파일로 내보내거나 검색 사서함이라는 특수 유형의 사서함에 복사할 수 있습니다. 관리자 또는 준수 관리자는 검색 사서함에 연결하여 메시지를 검토할 수 있습니다. 자세한 내용은 [원본 위치 eDiscovery 검색 만들기](/microsoft-365/compliance/content-search)를 참조하세요.
  
> [!NOTE]
> 온-프레미스 및 클라우드 기반 사서함 또는 보관 사서함에 대해 수행된 원본 위치 eDiscovery 검색의 검색 결과를 복사할 때 온-프레미스 검색 사서함을 선택해야 합니다. 온-프레미스 기본 사서함과 클라우드 기반 보관 사서함의 메시지는 온-프레미스 검색 사서함에 복사됩니다. 
  
또한 관리자는 조직 전체의 여러 사서함으로 전송된 부적절한 전자 메일 메시지를 검색하여 삭제할 수도 있습니다. 예를 들어, 기밀에 해당하는 급여 정보가 실수로 모든 직원에게 전송된 경우 관리자는 사용자의 사서함에서 해당 전자 메일을 삭제할 수 있습니다. 이 유형의 검색은 Exchange 관리 센터에서는 사용할 수 없으며, 원격 PowerShell을 사용하여 수행해야 합니다. 사용자의 사서함에서 메시지를 삭제하는 방법에 대한 자세한 내용은 [메시지 검색 및 삭제](/Exchange/policy-and-compliance/ediscovery/delete-messages)를 참조하세요.
  
## <a name="security-features-in-exchange-online-archiving"></a>Exchange Online Archiving의 보안 기능

다음 섹션에서는 Microsoft Exchange Online Archiving의 보안 기능을 설명합니다.
  
### <a name="encryption-between-on-premises-servers-and-exchange-online-archiving"></a>온-프레미스 서버와 Exchange Online Archiving 간 암호화

전자 메일 서버 간 연결을 암호화하는 데는 TLS가 사용되어 스푸핑이 방지되도록 하고 전송 중인 메시지에 기밀성을 제공합니다. TLS는 Microsoft 데이터 센터에 대한 Microsoft 데이터 센터로의 사내 메일 서버 트래픽을 보호하는 데도 Exchange Online Archiving.
  
### <a name="encrypting-between-clients-and-exchange-online-archiving"></a>클라이언트와 Exchange Online Archiving 간 암호화

보안 향상을 위해 Exchange Online Archiving에 대한 클라이언트 연결에는 다음과 같은 암호화 방법이 사용됩니다.
  
- SSL은 TCP 포트 443을 Outlook, 웹 Outlook 및 Exchange 웹 서비스 트래픽을 보안하는 데 사용됩니다.
    
- Exchange Online Archiving이 도입된다고 해서 온-프레미스 서버에 대한 클라이언트 연결이 변경되지는 않습니다.
    
### <a name="encryption-smime-and-pgp"></a>암호화: S/MIME 및 PGP

Exchange Online Archiving에서는 S/MIME(Secure/Multipurpose Internet Mail Extensions) 메시지를 저장합니다. 그러나 Exchange Online Archiving에서 S/MIME 기능을 호스트하거나 공개 키를 호스트하지는 않으며 키 리포지토리, 키 관리 또는 키 디렉터리 서비스를 제공하지도 않습니다. 이러한 모든 서비스가 온-프레미스 Exchange 인프라에 연결되기 때문입니다.
  
마찬가지로, Exchange Online Archiving에서는 클라이언트 쪽, 타사 암호화 솔루션(예: PGP(Pretty Good Privacy))을 사용하여 암호화된 메시지를 저장합니다.
  
### <a name="information-rights-management"></a>정보 권한 관리

Exchange Online Archiving에서 호스트 IRM(정보 권한 관리) 서비스를 제공하지는 않지만 관리자는 온-프레미스 AD RMS(Active Directory Rights Management Services)를 사용할 수 있습니다. AD RMS 서버가 배포되면 Outlook은 해당 서버와 직접 통신할 수 있으며, 사용자는 IRM으로 보호된 메시지를 작성하고 읽을 수 있습니다. AD RMS 서버와 온-프레미스 Exchange 환경 간의 상호 운용성이 구성된 경우 사용자는 IRM으로 보호된 메시지를 작성하고 읽을 수 있습니다.
  
#### <a name="support-for-irm-in-outlook-on-the-web"></a>웹용 응용 Outlook IRM 지원

사용자는 웹에서 기본적으로 IRM으로 보호된 메시지를 읽고 만들 수 Outlook 있는 경우와 Outlook. 웹용 응용 Outlook IRM으로 보호된 메시지는 플러그 인이 필요하지 Internet Explorer, Firefox, Safari 및 Chrome을 통해 액세스할 수 있습니다. 메시지에는 전체 텍스트 검색, 대화 보기 및 미리 보기 창이 포함됩니다. 이 기능이 가능하도록 Active Directory Rights Management Services 서버와 온-프레미스 Exchange 환경 간의 상호 운용성이 구성되어야 합니다.
  
#### <a name="irm-search"></a>IRM 검색

헤더, 제목, 본문 및 첨부 파일을 비롯하여 IRM으로 보호된 메시지는 인덱싱되며 검색 가능합니다. 사용자는 웹에서 Outlook 및 Outlook IRM으로 보호된 항목을 검색할 수 있으며 관리자는 In-Place eDiscovery 또는 **Search-Mailbox** cmdlet을 사용하여 IRM으로 보호된 항목을 검색할 수 있습니다.
  
### <a name="auditing"></a>감사

Exchange Online Archiving에서는 다음과 같은 두 가지 유형의 기본 제공 감사 기능을 제공합니다.
  
- **관리자 감사 로깅** - 관리자 감사 로깅을 사용하면 고객이 RBAC 역할이나 정책 및 설정에 대한 변경 내용을 포함하여 Exchange Online Archiving 관리자가 변경한 내용을 추적할 Exchange 있습니다. 
    
- **사서함 감사 로깅** - 사서함 감사 로깅을 사용하면 고객이 사서함 소유자가 아는 사용자의 사서함 액세스를 추적할 수 있습니다. 
    
Exchange 관리 센터에서는 관리자 역할 변경, 소송 보존, 비소유자 사서함 액세스 등 미리 정의된 여러 감사 보고서를 사용할 수 있습니다. 관리자는 날짜 및 역할별로 보고서를 필터링하고 장기 보존 또는 사용자 지정 보고를 위해 지정된 사서함에 대한 모든 감사 이벤트를 XML 형식으로 내보낼 수 있습니다.
  
관리자 감사 로깅은 기본적으로 설정되며, 사서함 감사 로깅은 기본적으로 해제됩니다. 관리자는 원격 Windows PowerShell을 사용하여 조직에 있는 사서함 일부 또는 전부에 대해 사서함 감사 로깅을 사용하도록 설정할 수 있습니다. 자세한 내용은 [감사 보고서](/exchange/security-and-compliance/exchange-auditing-reports/exchange-auditing-reports)를 참조하세요.
  
## <a name="feature-availability"></a>기능 가용성

계획, 독립 실행형 옵션 및 사내 솔루션에서 기능 가용성을 확인한 경우 서비스 [Exchange Online Archiving 참조하세요.](exchange-online-archiving-service-description.md)
