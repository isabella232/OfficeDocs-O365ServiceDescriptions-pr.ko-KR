---
title: 메시지 정책 및 규정 준수
ms.author: office365servicedesc
author: pamelaar
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-message-policy-recovery-and-compliance
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 5c43c8eb-f8f7-4b5a-a743-b1dab7dc2fc8
ms.openlocfilehash: 5565085472d43230f9059e1dcac115105a2e20d5
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132702"
---
# <a name="message-policy-and-compliance"></a>메시지 정책 및 규정 준수

## <a name="archiving-exchange-online-based-mailboxes"></a>Exchange Online 기반 사서함 보관

Exchange Online mailboxes reside in the cloud, and archiving them requires unique hosting environments. In some cases, Exchange Online can also be used to archive on-premises mailboxes in the cloud. The options for archiving with Exchange Online are described in this section.
  
Exchange Online은 사용자가 오래된 전자 메일 메시지를 저장할 수 있는 편리한 위치를 제공하는 원본 위치 보관을 비롯하여 클라우드 기반 사서함에 대한 보관 기능을 기본 제공합니다. 원본 위치 보관은 Outlook 및 웹용 Outlook에서 사용자의 기본 사서함 폴더 옆에 표시 되는 특수 한 유형의 사서함입니다. 사용자는 기본 사서함에 액세스하고 검색할 때와 동일한 방식으로 보관 사서함에 액세스하고 검색할 수 있습니다. 사용 가능한 기능은 사용 중인 클라이언트에 따라 다릅니다.
  
- **웹용 outlook 2016, outlook 2013, outlook 2010 및 outlook** 사용자는 보존 및 보관 정책에 대 한 제어와 같은 관련 준수 기능 뿐만 아니라 보관 함의 모든 기능에 액세스할 수 있습니다. 
    
- **Outlook 2007** Users have basic support for the In-Place Archive, but not all archiving and compliance features are available. For example, users cannot apply retention or archive policies to mailbox items and must rely on administrator-provisioned policies instead. 
    
예를 들면, 사용자는 사서함 항목에 대해 보존 및 보관 정책을 적용할 수 없으며 관리자 프로비저닝 정책을 대신 사용해야 합니다
  
자세한 내용은 다음 항목을 참조하십시오.
  
- 자세한 내용은 다음 항목을 참조하십시오.
    
- [Exchange Online의 활성 사서함](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes)
    
### <a name="archive-sizes"></a>보관 크기

사용자 한 명의 메시지 데이터만 각 개인 보관 사서함에 저장할 수 있습니다. 저장소의 할당은 구독 계획에 따라 다릅니다. 보관 사서함 크기에 대 한 자세한 내용은 [Exchange Online 제한](exchange-online-limits.md)의 "사서함 저장소 제한" 섹션을 참조 하십시오.
  
> [!IMPORTANT]
> - 보관 목적으로 Exchange Online 사서함에 메시지를 복사하는 저널링, 전송 규칙 또는 자동 전달 규칙을 사용하는 것은 허용되지 않습니다. Microsoft는 개인 시나리오에서 또는 부적절 하 게 사용 되는 다른 경우에 사서함 보관이 사용 되지 않는 인스턴스에서 무제한 보관을 거부할 권한을 보유 합니다.
> - In-Place Archive has specific licensing requirements for Outlook users. Outlook 2007 users must have the Office 2007 Cumulative Update for February 2011 to access the personal archive. 
> - Exchange Online에서는 관리자가 .pst 파일을 개인 보관 함으로 가져올 때 Exchange Server 2010 서비스 팩 1 이상 버전의 _새로운 New-mailboximportrequest_ Windows PowerShell cmdlet을 지원 하지 않습니다. 사용자의 기본 사서함과 보관 사서함 모두가 Exchange Online에 있으면 관리자는 무료 도구인 PST Capture를 사용하여 사용자의 기본 사서함이나 보관 사서함으로 .pst 파일 데이터를 가져올 수 있습니다.

## <a name="cloud-based-archiving-of-on-premises-mailboxes"></a>온-프레미스 사서함의 클라우드 기반 보관

Using Exchange Online for cloud-based archiving of on-premises Exchange Server 2010 or later mailboxes is possible with Microsoft Exchange Online Archiving, a hosted archiving solution from Microsoft. This requires that the on-premises organization be in Hybrid mode or be set up for Exchange Online Archiving.
  
> [!IMPORTANT]
> 관리되는 폴더 정책이 적용되는 Exchange 2010 사서함 서버에 온-프레미스 사서함이 있는 사용자는 온-프레미스 또는 클라우드 기반 원본 위치 보관을 사용할 수 없습니다. 
  
## <a name="retention-tags-and-retention-policies"></a>보존 태그 및 보존 정책

Exchange Online은 전자 메일 및 다른 통신과 관련한 조직의 부담을 줄이는 데 도움을 주는 보존 정책을 제공합니다. 이러한 정책을 사용하면 관리자가 사용자 사서함의 특정 폴더에 보존 설정을 적용할 수 있습니다. 또한 관리자는 사용자에 게 보존 정책 메뉴를 제공 하 고 Outlook 2010 이상 또는 웹용 Outlook을 사용 하 여 특정 항목, 대화 또는 폴더에 정책을 적용 하도록 할 수 있습니다.
  
또한 관리자는 Outlook 2010 이상 또는 Outlook Web App를 통해 사용자에게 보존 정책 메뉴를 제공하고 이를 특정 항목, 대화 또는 폴더에 적용하도록 할 수 있습니다.
  
Exchange Online offers two types of policies: archive policies and delete policies. Both types can be combined on the same item or folder. For example, a user can tag an email message to be automatically moved to the In-Place Archive in a specified number of days and deleted after another span of days.
  
Outlook 2010 이상 및 웹용 Outlook에서는 사용자가 폴더, 대화 또는 개별 메시지에 보존 정책을 적용할 수 있습니다. 또한 적용되는 보존 정책 및 메시지의 예상 삭제 날짜를 직접 확인할 수 있습니다. 그러나 다른 전자 메일 클라이언트 사용자는 관리자가 설정한 서버 쪽 보존 정책을 기반으로 전자 메일을 삭제하거나 보관할 수만 있습니다.
  
The retention policy capabilities offered in Exchange Online are the same as those offered in Exchange Server 2010 Service Pack 2 RU4. Administrators can use remote Windows PowerShell to migrate retention policies from on-premises Exchange Server 2010 or later environments to Exchange Online.
  
> [!IMPORTANT]
> 관리자는 원격 Windows PowerShell을 사용하여 온-프레미스 Exchange Server 2010 이상 환경에서 Exchange Online으로 보존 정책을 마이그레이션할 수 있습니다. 
  
Exchange Server 2007에서 제공했던 기존의 메시징 레코드 관리 접근 방식인 관리되는 폴더는 사용할 수 없습니다.
  
## <a name="encryption-of-data-at-rest"></a>보관된 데이터 암호화

Exchange Online, 비즈니스용 Skype, 비즈니스용 OneDrive 및 SharePoint Online의 BitLocker, DKM, Azure Storage Service 암호화 및 서비스 암호화를 비롯 한 여러 서비스 쪽 기술에 따라 나머지 고객 데이터 암호화가 제공 됩니다. Office 365 서비스 암호화에는 Azure 키 자격 증명 모음에 저장 되는 고객 관리 암호화 키를 사용 하기 위한 옵션이 포함 됩니다. [고객 키](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key?redirectSourcePath=%252fen-us%252farticle%252fControlling-your-data-in-Office-365-using-Customer-Key-f2cd475a-e592-46cf-80a3-1bfb0fa17697)라고 하는이 고객 관리 키 옵션은 Exchange Online, SharePoint Online 및 비즈니스용 OneDrive에 사용할 수 있습니다. 
  
### <a name="bitlocker"></a>BitLocker

Microsoft 서버는 BitLocker를 사용 하 여 볼륨 수준에서 남은 고객 데이터를 포함 하는 디스크 드라이브를 암호화 합니다. BitLocker 암호화는 Windows에 기본적으로 제공 되는 데이터 보호 기능입니다. BitLocker는 다른 프로세스나 컨트롤에 lapses가 있는 경우 (예: 액세스 제어 또는 하드웨어 재활용) 고객이 고객 데이터를 포함 하는 디스크에 물리적으로 액세스할 수 있도록 하는 데 사용 되는 기술 중 하나입니다. 이 경우 BitLocker는 컴퓨터 및 디스크 분실, 도난 또는 부적절 한 제거로 인 한 데이터 도용 또는 노출을 방지할 수 있습니다. 
  
### <a name="distributed-key-manager"></a>배포 된 키 관리자

BitLocker 외에도, DKM (Distributed Key Manager) 이라는 기술을 사용 합니다. DKM는 비밀 키 집합을 사용 하 여 정보를 암호화 하 고 암호를 해독 하는 클라이언트 쪽 기능입니다. Active Directory 도메인 서비스에 있는 특정 보안 그룹의 구성원만이 키에 액세스 하 여 DKM에서 암호화 된 데이터의 암호를 해독할 수 있습니다. Exchange Online에서는 Exchange 프로세스가 실행되는 특정 서비스 계정만 해당 보안 그룹에 속합니다. 데이터 센터의 표준 운영 절차의 일부로, 이 보안 그룹에 속하는 사용자에게 자격 증명이 제공되지 않으므로 이러한 암호를 해독할 수 있는 키에 액세스할 수 없습니다.
  
## <a name="customer-key"></a>고객 키

고객 키를 사용 하 여 조직의 암호화 키를 제어 하 고 Microsoft 데이터 센터의 휴지 상태에서 데이터가 암호화 되도록 구성 합니다. 미사용 데이터에는 SharePoint Online 및 비즈니스용 OneDrive에 저장되어 있는 사서함과 파일에 저장된 Exchange Online 및 비즈니스용 Skype의 데이터를 포함합니다. 자세한 내용은 고객 키 및 [서비스 암호화](https://docs.microsoft.com/office365/securitycompliance/service-encryption-with-customer-key-faq)를 [사용 하 여 데이터 제어](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key) FAQ를 참조 하세요.
  
## <a name="office-365-message-encryption"></a>Office 365 메시지 암호화

Office 365 메시지 암호화를 사용 하면 전자 메일 사용자가 암호화 된 전자 메일 메시지를 누구 든 지 보낼 수 있습니다. Azure Information Encryption의 보호 기능을 활용 하는 Office 메시지 암호화의 새로운 기능을 발표 했습니다. 이러한 새로운 기능을 통해 조직 내부 또는 외부의 모든 사용자와 보호 된 메시지를 보다 쉽게 공유 하 고 공동으로 작업할 수 있도록 하는 향상 된 최종 사용자 환경이 제공 됩니다. 새 Office 메시지 암호화 기능에는 몇 가지 설치 요구 사항이 있습니다. Azure Information Protection 기반으로 구축 된 새 Office 365 메시지 암호화 기능을 참조 하세요. 고객이 레거시 Office 365 메시지 암호화를 사용 하는 경우에는 위에 나와 있는 설정 지침을 따르지 않으면 새로운 기능을 얻을 수 없습니다. 신규 및 레거시 Office 365 메시지 암호화 기능에 포함 된 항목에 대 한 자세한 내용은 [FAQ](https://support.office.com/article/Office-365-Message-Encryption-FAQ-0432dce9-d9b6-4e73-8a13-4a932eb0081e) 를 참조 하세요. 

Office 365 고급 메시지 암호화는 메시지 만료 및 해지를 허용 하 여 추가 보호 기능을 제공 합니다.  조직에서 보내는 암호화 된 전자 메일용으로 여러 템플릿을 만들 수도 있습니다.  고급 메시지 암호화는 Microsoft 365 E5, Office 365 E5, Microsoft 365 E5 (비영리 스태프 가격), Office 365 Enterprise E5 (비영리 스태프 가격) 또는 Office 365 교육용 A5에 포함 되어 있습니다. 조직에서 Office 365 고급 메시지 암호화를 포함 하지 않는 구독을 사용 하는 경우에는 Microsoft 365 E5 규정 준수 또는 Office 365 Advanced 준수 SKU를 추가 기능으로 구입할 수 있습니다.

## <a name="securemultipurpose-internet-mail-extensions-smime"></a>S/MIME(Secure/Multipurpose Internet Mail Extensions)

S/MIME allows you to help protect sensitive information by sending signed and encrypted email within your organization. Administrators can use remote Windows PowerShell to set up S/MIME after establishing and issuing PKI certificates to users. These certificates must be synchronized from an on-premises Active Directory Certificate Service.
  
S/MIME은 Microsoft Edge 및 Internet Explorer 11에서 지원 됩니다. 현재 Firefox, Opera 및 Chrome에서는 S/MIME이 지원 되지 않습니다. 자세한 내용은 [S/MIME for Message Signing and Encryption](https://docs.microsoft.com/Exchange/policy-and-compliance/smime?view=exchserver-2019)을 참조하십시오.
  
## <a name="in-place-hold-and-litigation-hold"></a>원본 위치 유지 및 소송 보존

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
  
자세한 내용은 [원본 위치 유지 및 소송 보존](https://docs.microsoft.com/exchange/security-and-compliance/in-place-and-litigation-holds)을 참조하세요.
  
## <a name="in-place-ediscovery"></a>원본 위치 eDiscovery

고객은 Exchange Online을 통해 웹 기반 인터페이스를 사용 하 여 조직 전체의 사서함 내용을 검색할 수 있습니다. 할당을 통한 원본 위치 eDiscovery 검색을 수행할 권한이 있는 관리자나 규정 준수 및 보안 담당자는 전자 메일 메시지, 첨부 파일, 일정 약속, 작업, 연락처 및 기타 항목을 검색할 수 있습니다. 원본 위치 eDiscovery은 기본 사서함 및 보관함을 동시에 검색할 수 있습니다. KQL 구문과 함께, 다양한 필터링 기능에는 보낸 사람, 받는 사람, 메시지 유형, 보낸 날짜/받은 날짜, 참조/숨은 참조가 있습니다. 검색 쿼리와 일치할 경우 지운 편지함 폴더의 항목도 검색 결과에 포함됩니다.
  
Results of In-Place eDiscovery searches can be previewed in the web-based interface, exported to a PST file or copied to a special type of mailbox called a Discovery mailbox. A Discovery mailbox has a 50 GB quota for storing search results. Administrators can also connect Outlook to the Discovery mailbox to access search results, and export the search results to a .pst file.
  
Administrators use either the Exchange admin center or remote Windows PowerShell to perform multi-mailbox searches. The Exchange admin center can provide a read-only preview of the search results, enabling administrators to quickly verify a search and rerun it, if needed, with different parameters. Once a search is optimized, the administrator can copy the results to the Discovery mailbox.
  
By default, one Discovery mailbox is created for each organization, but administrators can create additional Discovery mailboxes using remote Windows PowerShell. Discovery mailboxes cannot be used for any purpose other than storing In-Place eDiscovery search results.
  
Administrators use either the Exchange admin center or remote Windows PowerShell to perform In-Place eDiscovery searches. The Exchange admin center can provide a read-only preview of the search results, enabling administrators to quickly verify a search and rerun it, if needed, with different parameters. Once a search is optimized, the administrator can copy the results to the Discovery mailbox or export search results to a PST file.
  
관리자는 Exchange 관리 센터 또는 원격 Windows PowerShell을 사용하여 원본 위치 eDiscovery 검색에서 한 번에 최대 10,000개의 사서함을 검색할 수 있습니다. 
  
Exchange Online에서 권한 있는 사용자는 원본 위치 eDiscovery를 수행할 수 있으며, 다음 작업 중 하나를 선택할 수 있습니다.
  
- **검색 결과 예상** - 검색에 사용된 키워드의 효율성을 확인하고 필요한 경우 검색 매개 변수를 조정하는 키워드 통계를 비롯하여 검색에서 반환할 예상 메시지 개수를 가져옵니다. 
    
- **검색 결과 미리 보기**
    
- 검색 결과에 반환된 메시지를 검색 사서함에 복사합니다.
    
자세한 내용은 [원본 위치 eDiscovery](https://docs.microsoft.com/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery)를 참조하십시오.
  
## <a name="mail-flow-rules"></a>메일 흐름 규칙

메일 흐름 규칙을 사용 하 여 조직을 통과 하는 메시지에 대 한 특정 조건을 찾아보고 작업을 수행할 수 있습니다. 메일 흐름 규칙을 사용 하면 전자 메일 메시지, 보안 메시지, 메시징 시스템 보호 및 정보 누출 방지에 메시징 정책을 적용할 수 있습니다.
  
Many organizations today are required by law, regulatory requirements, or company policies to apply messaging policies that limit the interaction between recipients and senders, both inside and outside the organization. In addition to limiting interactions among individuals, departmental groups inside the organization, and entities outside the organization, some organizations are also subject to the following messaging policy requirements:
  
- 조직 내/외부에서 부적절한 콘텐츠를 주고받는 행위 차단
    
- 조직의 기밀 정보 필터링
    
- 특정 개인과 주고받은 메시지 추적 또는 복사
    
- 배달 전에 메시지 검사를 위해 인바운드 및 아웃바운드 메시지 리디렉션
    
- 조직을 통해 전달되는 메시지에 부인 적용
    
> [!IMPORTANT]
> 전자 메일 서버에 타사 Ifilter를 설치 해야 하는 첨부 파일 형식 (예: Adobe .pdf)은 적절 한 iFilter가 설치 될 때까지 메일 흐름 규칙을 사용 하 여 검사할 수 없습니다. 메일 흐름 규칙에서 지원 되는 파일 형식에 대 한 자세한 내용은 [메일 흐름 규칙을 사용 하 여 Office 365에서 메시지 첨부 파일 검사를](https://docs.microsoft.com/exchange/security-and-compliance/mail-flow-rules/inspect-message-attachments)참조 하십시오.
  
메일 흐름 규칙에 대 한 자세한 내용은 [Exchange 2016의 메일 흐름 규칙](https://docs.microsoft.com/Exchange/policy-and-compliance/mail-flow-rules/mail-flow-rules?view=exchserver-2019)을 참조 하십시오.
  
## <a name="data-loss-prevention"></a>데이터 손실 방지

DLP(데이터 손실 방지) 기능은 심도 있는 콘텐츠 분석을 통해 조직의 중요한 정보를 식별하고, 모니터링하고, 보호하는 데 도움을 줍니다. DLP는 업무상 중요한 전자 메일에는 보호해야 할 기밀 데이터가 포함되어 있으므로 엔터프라이즈 메시지 시스템에 점점 더 중요한 프리미엄 기능입니다. Exchange Online의 DLP 기능을 사용 하면 작업자 생산성에 영향을 주지 않고 중요 한 데이터를 보호할 수 있습니다.
  
EAC(Exchange 관리 센터) 관리 인터페이스에서 DLP 정책을 구성하면 다음과 같은 기능을 사용할 수 있습니다. 
  
- PCI-DSS 데이터, 금융서비스 현대화법(Gramm-Leach-Bliley Act) 데이터 같이 특정 형식의 중요한 정보 또는 또는 로캘별 PII(개인 식별 정보)를 검색하는 데 도움을 받을 수 있는, 미리 구성된 정책 템플릿으로 시작합니다.
    
- 기존 전송 규칙 조건 및 작업을 완벽하게 활용하고 새 전송 규칙을 추가합니다.
    
- DLP 정책의 효율성을 테스트한 후에 완전히 적용합니다.
    
- 자신의 사용자 지정 DLP 정책 템플릿과 중요한 정보 형식을 통합합니다.
    
- 메시지 첨부 파일, 본문 텍스트 또는 제목 줄에서 중요 한 정보를 검색 하 고 Exchange Online이 작동 하는 신뢰 수준을 조정 합니다.
    
- Detect sensitive form data by using Document Fingerprinting. Document Fingerprinting helps you easily create custom sensitive information types based on text-based forms that you can use to define transport rules and DLP policies.
    
- Outlook 2016, Outlook 2013, 웹용 Outlook 및 장치용 OWA에 알림을 표시 하 여 데이터 손실을 줄이는 데 도움이 되는 정책 팁을 추가 하 고, 가양성 보고를 허용 하 여 정책의 효율성을 향상 시킬 수 있습니다. 
    
- DLP 보고서의 문제 데이터를 검토하거나, 문제 보고서 생성 작업을 사용하여 자체 보고서를 추가합니다.
    
DLP에 대한 자세한 내용은 [데이터 손실 방지](https://docs.microsoft.com/exchange/security-and-compliance/data-loss-prevention/data-loss-prevention)를 참조하세요.
  
## <a name="journaling"></a>저널링

You can configure Exchange Online to journal copies of emails to any external mailbox that can receive messages via SMTP. Journaling can help your organization respond to legal, regulatory, and organizational compliance requirements by recording inbound and outbound email communications. When planning for messaging retention and compliance, it's important to understand journaling and how it fits in with your organization's compliance policies.
  
You can manage journal rules by using the Exchange admin center or remote Windows PowerShell. You can configure journaling on a per-user and per-distribution list basis, and choose to journal only internal messages, only external messages, or both. Journaled messages include not only the original message but also information about the sender, recipients, copies, and blind copies.
  
정상적이 고 안정적인 저널링 솔루션을 보장 하려면 다음 작업을 완료 해야 합니다.
  
- 저널링 대상이 Exchange Online 사서함이 아닌지 확인 합니다.
    
- 고객 디렉터리에 저널링에 사용할 SMTP 대상 전자 메일 주소에 대한 연락처 개체를 만듭니다.
    
- 기본 저널 사서함을 사용할 수 없는 경우 저널 보고서를 캡처할 대체 저널 사서함으로 보조 연락처 개체를 만듭니다.
    
- 메일을 효과적으로 수락 하려면 SMTP 대상의 적절 한 관리, 중복, 가용성, 성능 및 기능 수준을 유지 관리 해야 합니다.
    
- 메시지 형식, 보낸 사람/받는 사람 정보 통합 및 적절한 내용 변환을 비롯하여 Exchange Server와 Exchange 전송에 각각의 상호 운용성을 제공합니다.
    
저널링에 대한 자세한 내용은 [저널링](https://docs.microsoft.com/exchange/security-and-compliance/journaling/journaling)을 참조하세요.
  
## <a name="feature-availability"></a>기능 가용성

계획, 독립 실행형 옵션 및 온-프레미스 솔루션 별로 기능 가용성을 확인 하려면 [Exchange Online 서비스 설명을](exchange-online-service-description.md)참조 하세요.
  

