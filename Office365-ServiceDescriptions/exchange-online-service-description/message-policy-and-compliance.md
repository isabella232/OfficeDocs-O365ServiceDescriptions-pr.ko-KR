---
title: 메시지 정책 및 규정 준수
ms.author: office365servicedesc
author: pamelaar
manager: gailw
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-message-policy-recovery-and-compliance
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
ms.assetid: 5c43c8eb-f8f7-4b5a-a743-b1dab7dc2fc8
description: 메시지 정책 및 규정 준수에 대해 Exchange Online.
ms.openlocfilehash: c53f4deb052bfe149ed3adf7821ace90ded01126
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/24/2021
ms.locfileid: "59671874"
---
# <a name="message-policy-and-compliance"></a>메시지 정책 및 규정 준수

## <a name="archiving-exchange-online-based-mailboxes"></a>Exchange Online 기반 사서함 보관

Exchange Online 사서함은 클라우드에 있으며, 이를 보관하려면 고유한 호스트 환경이 필요합니다. 경우에 따라 Exchange Online은 클라우드에 온-프레미스 사서함을 보관하는 데 사용되기도 합니다. Exchange Online을 사용한 보관 옵션을 이 섹션에서 설명합니다.
  
Exchange Online은 사용자가 오래된 전자 메일 메시지를 저장할 수 있는 편리한 위치를 제공하는 원본 위치 보관을 비롯하여 클라우드 기반 사서함에 대한 보관 기능을 기본 제공합니다. In-Place 보관 사서함은 사용자 기본 사서함 폴더와 함께 나타나는 특수한 유형의 사서함으로 Outlook 웹용 Outlook. 사용자는 기본 사서함에 액세스하고 검색할 때와 동일한 방식으로 보관 사서함에 액세스하고 검색할 수 있습니다. 사용 가능한 기능은 사용 중인 클라이언트에 따라 다릅니다.
  
- **Outlook 2016, Outlook 2013, Outlook 2010** 및 웹용 Outlook 사용자는 보관함의 전체 기능과 보존 및 보관 정책 제어와 같은 관련 규정 준수 기능에 액세스할 수 있습니다. 
    
- **Outlook 2007** 사용자는 원본 위치 보관에 대해 기본 지원을 제공받지만 일부 보관 및 준수 기능은 사용할 수 없습니다. 예를 들면, 사용자는 사서함 항목에 대해 보존 및 보관 정책을 적용할 수 없으며 관리자 프로비저닝 정책을 대신 사용해야 합니다 Outlook 2007 사용자는 원본 위치 보관에 대해 기본 지원을 제공받지만 일부 보관 및 준수 기능은 사용할 수 없습니다. 
    
예를 들면, 사용자는 사서함 항목에 대해 보존 및 보관 정책을 적용할 수 없으며 관리자 프로비저닝 정책을 대신 사용해야 합니다
  
자세한 내용은 다음 항목을 참조하십시오.
  
- 자세한 내용은 다음 항목을 참조하십시오.
    
- [Exchange Online의 활성 사서함](/office365/securitycompliance/enable-archive-mailboxes)
    
### <a name="archive-sizes"></a>보관 크기

사용자 한 명의 메시지 데이터만 각 개인 보관 사서함에 저장할 수 있습니다. 저장소의 할당은 구독 계획에 따라 다릅니다. 보관 사서함 크기에 대한 자세한 내용은 제한의 "사서함 저장소 제한" [Exchange Online 참조하세요.](exchange-online-limits.md)
  
> [!IMPORTANT]
> - 보관 목적으로 Exchange Online 사서함에 메시지를 복사하는 저널링, 전송 규칙 또는 자동 전달 규칙을 사용하는 것은 허용되지 않습니다. Microsoft는 사서함 보관함이 개인 시나리오에서 사용되지 않는 경우 또는 부적절한 사용의 경우 무제한 보관을 거부할 수 있는 권리가 있습니다.
> - Outlook 사용자의 경우 원본 위치 보관에 특정 라이선스 요구 사항이 적용됩니다. Outlook 2007 사용자의 경우 개인 보관 파일에 액세스하려면 2011년 2월 Office 2007 누적 업데이트가 필요합니다. 
> - Exchange Online .pst 파일을 개인 보관함으로 가져오기 위해 Exchange Server 2010 서비스 팩 1 이상의 _New-MailboxImportRequest_ Windows PowerShell cmdlet을 지원하지 않습니다. 사용자의 기본 사서함과 보관 사서함 모두가 Exchange Online에 있으면 관리자는 무료 도구인 PST Capture를 사용하여 사용자의 기본 사서함이나 보관 사서함으로 .pst 파일 데이터를 가져올 수 있습니다.

## <a name="cloud-based-archiving-of-on-premises-mailboxes"></a>온-프레미스 사서함의 클라우드 기반 보관

온-프레미스 Exchange Server 2010 이상 사서함의 클라우드 기반 보관에 Exchange Online을 사용하려는 경우 Microsoft에서 호스트하는 보관 솔루션인 Microsoft Exchange Online Archiving을 구현할 수 있습니다. 이를 위해서는 온-프레미스 조직이 하이브리드 모드이거나 Exchange Online Archiving에 맞게 설정되어야 합니다.
  
> [!IMPORTANT]
> 관리되는 폴더 정책이 적용되는 Exchange 2010 사서함 서버에 온-프레미스 사서함이 있는 사용자는 온-프레미스 또는 클라우드 기반 원본 위치 보관을 사용할 수 없습니다. 
  
## <a name="retention-tags-and-retention-policies"></a>보존 태그 및 보존 정책

Exchange Online은 전자 메일 및 다른 통신과 관련한 조직의 부담을 줄이는 데 도움을 주는 보존 정책을 제공합니다. 이러한 정책을 사용하면 관리자가 사용자 사서함의 특정 폴더에 보존 설정을 적용할 수 있습니다. 관리자는 또한 사용자에게 보존 정책 메뉴를 제공하고 2010 이상 또는 2010 이상을 사용하여 특정 항목, 대화 또는 폴더에 정책을 Outlook 수 웹용 Outlook.
  
또한 관리자는 Outlook 2010 이상 또는 Outlook Web App를 통해 사용자에게 보존 정책 메뉴를 제공하고 이를 특정 항목, 대화 또는 폴더에 적용하도록 할 수 있습니다.
  
Exchange Online은 보관 정책 및 삭제 정책이라는 두 가지 유형의 정책을 제공합니다. 이 두 가지 유형을 동일한 항목이나 폴더에 함께 적용할 수 있습니다. 예를 들어, 사용자는 특정 기간 후 전자 메일 메시지가 자동으로 원본 위치 보관으로 이동되고 그로부터 며칠이 지나면 삭제되도록 태그를 설정할 수 있습니다. Exchange Online은 보관 정책 및 삭제 정책이라는 두 가지 유형의 정책을 제공합니다. 이 두 가지 유형을 동일한 항목이나 폴더에 함께 적용할 수 있습니다.
  
Outlook 2010 이상을 웹용 Outlook 폴더, 대화 또는 개별 메시지에 보존 정책을 적용할 수 있습니다. 또한 적용되는 보존 정책 및 메시지의 예상 삭제 날짜를 직접 확인할 수 있습니다. 그러나 다른 전자 메일 클라이언트 사용자는 관리자가 설정한 서버 쪽 보존 정책을 기반으로 전자 메일을 삭제하거나 보관할 수만 있습니다.
  
Exchange Online에서 제공하는 보존 정책 기능은 Exchange Server 2010 SP2 RU4에서 제공하는 기능과 동일합니다. 관리자는 원격 Windows PowerShell을 사용하여 온-프레미스 Exchange Server 2010 이상 환경에서 Exchange Online으로 보존 정책을 마이그레이션할 수 있습니다. Exchange Online에서 제공하는 보존 정책 기능은 Exchange Server 2010 SP2 RU4에서 제공하는 기능과 동일합니다.
  
> [!IMPORTANT]
> 관리자는 원격 Windows PowerShell을 사용하여 온-프레미스 Exchange Server 2010 이상 환경에서 Exchange Online으로 보존 정책을 마이그레이션할 수 있습니다. 
  
Exchange Server 2007에서 제공했던 기존의 메시징 레코드 관리 접근 방식인 관리되는 폴더는 사용할 수 없습니다.
  
## <a name="encryption-of-data-at-rest"></a>보관된 데이터 암호화

미사용 고객 데이터 암호화는 BitLocker, DKM, Azure Storage Service Encryption 및 Exchange Online, 비즈니스용 Skype, 비즈니스용 OneDrive 및 SharePoint Online의 서비스 암호화를 비롯한 여러 서비스 쪽 기술을 통해 제공됩니다. Office 365 서비스 암호화에는 Azure Key Vault에 저장된 고객 관리 암호화 키를 사용하는 옵션이 포함되어 있습니다. 고객 키라고 하는 이 [](/microsoft-365/compliance/customer-key-overview)고객 관리 키 옵션은 Exchange Online, SharePoint Online 및 비즈니스용 OneDrive. 
  
### <a name="bitlocker"></a>BitLocker

Microsoft 서버는 BitLocker를 사용하여 볼륨 수준에서 미사용 고객 데이터가 포함된 디스크 드라이브를 암호화합니다. BitLocker 암호화는 기본 제공되는 데이터 보호 기능으로, Windows. BitLocker는 다른 프로세스 또는 컨트롤(예: 하드웨어의 액세스 제어 또는 재생)에 경과하여 고객 데이터가 포함된 디스크에 물리적으로 액세스할 수 있는 경우 위협을 보호하는 데 사용되는 기술 중 하나입니다. 이 경우 BitLocker는 분실, 도난 또는 부적절하게 해제된 컴퓨터 및 디스크로 데이터 도난 또는 노출 가능성을 제거합니다. 
  
### <a name="distributed-key-manager"></a>분산 키 관리자

BitLocker 외에도 DKM(분산 키 관리자)이라는 기술을 사용했습니다. DKM은 비밀 키 집합을 사용하여 정보를 암호화하고 암호 해독하는 클라이언트 쪽 기능입니다. Active Directory 도메인 서비스의 특정 보안 그룹의 구성원만 해당 키에 액세스하여 DKM으로 암호화된 데이터의 암호를 해독할 수 있습니다. Exchange Online에서는 Exchange 프로세스가 실행되는 특정 서비스 계정만 해당 보안 그룹에 속합니다. 데이터 센터의 표준 운영 절차의 일부로, 이 보안 그룹에 속하는 사용자에게 자격 증명이 제공되지 않으므로 이러한 암호를 해독할 수 있는 키에 액세스할 수 없습니다.
  
## <a name="customer-key"></a>고객 키

고객 키를 사용하여 조직의 암호화 키를 제어한 다음 Microsoft의 데이터 센터에서 휴지의 데이터를 암호화하도록 구성할 수 있습니다. 미사용 데이터에는 SharePoint Online 및 비즈니스용 OneDrive에 저장되어 있는 사서함과 파일에 저장된 Exchange Online 및 비즈니스용 Skype의 데이터를 포함합니다. 자세한 내용은 고객 키 [FAQ를](/office365/securitycompliance/controlling-your-data-using-customer-key) 사용하여 고객 키 및 서비스 암호화를 사용하여 데이터 [제어를 참조하세요.](/office365/securitycompliance/service-encryption-with-customer-key-faq)
  
## <a name="office-365-message-encryption"></a>Office 365 메시지 암호화

Office 365 메시지 암호화 전자 메일 사용자는 누구에게나 암호화된 전자 메일 메시지를 보낼 수 있습니다. Azure Information Encryption의 보호 기능을 활용하는 Office 메시지 암호화의 새로운 기능을 발표했습니다. 이러한 새로운 기능을 통해 보호된 메시지를 조직 내부 또는 외부의 모든 사용자와 보다 쉽게 공유하고 공동 작업할 수 있는 향상된 최종 사용자 환경이 제공됩니다. 새로운 Office 메시지 암호화 기능에는 몇 가지 설정 요구 사항이 있습니다. Azure Information Protection을 Office 365 메시지 암호화 새로운 기능 설정하기를 참조하세요. 레거시 Office 365 메시지 암호화 설정된 지침에 따라 새로운 기능을 얻지 못합니다. 새로운 기능과 레거시 및 레거시 기능에 포함된 기능에 대한 자세한 내용은 [FAQ를](https://support.office.com/article/Office-365-Message-Encryption-FAQ-0432dce9-d9b6-4e73-8a13-4a932eb0081e) Office 365 메시지 암호화 참조하시기 바랍니다. 

Office 365 고급 메시지 암호화 메시지 만료 및 해지를 허용하여 추가 보호 기능을 제공합니다.  조직에서 시작된 암호화된 전자 메일에 대해 여러 템플릿을 만들 수도 있습니다.  고급 메시지 암호화는 Microsoft 365 E5, Office 365 E5, Microsoft 365 E5(비영리 직원 가격), Office 365 Enterprise E5(비영리 직원 가격 책정) 또는 Office 365 Education A5에 포함되어 있습니다. 조직에 추가 기능을 포함하지 않는 구독이 Office 365 고급 메시지 암호화 SKU 또는 Microsoft 365 E5 Compliance SKU를 Office 365 Advanced Compliance 수 있습니다.

## <a name="securemultipurpose-internet-mail-extensions-smime"></a>S/MIME(Secure/Multipurpose Internet Mail Extensions)

S/MIME을 사용하면 조직 내에서 서명 및 암호화된 전자 메일을 보내 중요한 정보를 보호할 수 있습니다. 관리자는 PKI 인증서를 설정하고 사용자에게 발급한 후 원격 Windows PowerShell을 사용하여 S/MIME을 설정할 수 있습니다. 이러한 인증서는 온-프레미스 Active Directory 인증서 서비스에서 동기화해야 합니다. S/MIME을 사용하면 조직 내에서 서명 및 암호화된 전자 메일을 보내 중요한 정보를 보호할 수 있습니다. 관리자는 PKI 인증서를 설정하고 사용자에게 발급한 후 원격 Windows PowerShell을 사용하여 S/MIME을 설정할 수 있습니다.
  
S/MIME은 11에서 Microsoft Edge Internet Explorer 지원됩니다. 현재 Firefox, Opera 및 Chrome에서는 S/MIME을 사용할 수 없습니다. 자세한 내용은 [S/MIME for Message Signing and Encryption](/Exchange/policy-and-compliance/smime?preserve-view=true&view=exchserver-2019)을 참조하십시오.
  
## <a name="in-place-hold-and-litigation-hold"></a>원본 위치 유지 및 소송 보존

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
  
## <a name="in-place-ediscovery"></a>원본 위치 eDiscovery

Exchange Online 웹 기반 인터페이스를 사용하여 조직 전체에서 사서함의 콘텐츠를 검색할 수 있습니다. 할당을 통한 원본 위치 eDiscovery 검색을 수행할 권한이 있는 관리자나 규정 준수 및 보안 담당자는 전자 메일 메시지, 첨부 파일, 일정 약속, 작업, 연락처 및 기타 항목을 검색할 수 있습니다. 원본 위치 eDiscovery은 기본 사서함 및 보관함을 동시에 검색할 수 있습니다. KQL 구문과 함께, 다양한 필터링 기능에는 보낸 사람, 받는 사람, 메시지 유형, 보낸 날짜/받은 날짜, 참조/숨은 참조가 있습니다. 검색 쿼리와 일치할 경우 지운 편지함 폴더의 항목도 검색 결과에 포함됩니다.
  
원본 위치 eDiscovery 검색의 결과는 웹 기반 인터페이스에서 미리 보거나 PST 파일로 내보내거나 검색 사서함이라는 특수 유형 사서함에 복사할 수 있습니다. 검색 사서함에는 검색 결과를 저장하기 위한 50GB의 할당량이 있습니다. 또한 관리자는 Outlook을 검색 사서함에 연결하여 검색 결과에 액세스하고 검색 결과를 .pst 파일로 내보낼 수 있습니다.
  
관리자는 Exchange 관리 센터 또는 원격 Windows PowerShell을 사용하여 여러 사서함 검색을 수행합니다. Exchange 관리 센터에서 검색 결과에 대한 읽기 전용 미리 보기를 제공하므로, 관리자는 신속하게 검색을 확인하고 필요한 경우 다른 매개 변수를 사용하여 검색을 다시 실행할 수 있습니다. 검색이 최적화되면 관리자는 검색 사서함에 결과를 복사할 수 있습니다.
  
기본적으로 조직별로 하나의 검색 사서함이 만들어지지만 관리자가 원격 Windows PowerShell을 사용하여 검색 사서함을 추가로 만들 수 있습니다. 검색 사서함은 원본 위치 eDiscovery 검색 결과 저장 이외의 용도로는 사용할 수 없습니다.
  
관리자는 Exchange 관리 센터 또는 원격 Windows PowerShell을 사용하여 원본 위치 eDiscovery 검색을 수행합니다. Exchange 관리 센터에서 검색 결과에 대한 읽기 전용 미리 보기를 제공하므로, 관리자는 신속하게 검색을 확인하고 필요한 경우 다른 매개 변수를 사용하여 검색을 다시 실행할 수 있습니다. 검색이 최적화되면 관리자는 검색 사서함에 결과를 복사하거나 검색 결과를 PST 파일로 내보낼 수 있습니다.
  
관리자는 Exchange 관리 센터 또는 원격 Windows PowerShell을 사용하여 원본 위치 eDiscovery 검색에서 한 번에 최대 10,000개의 사서함을 검색할 수 있습니다. 
  
Exchange Online에서 권한 있는 사용자는 원본 위치 eDiscovery를 수행할 수 있으며, 다음 작업 중 하나를 선택할 수 있습니다.
  
- **검색 결과 예상** - 검색에 사용된 키워드의 효율성을 확인하고 필요한 경우 검색 매개 변수를 조정하는 키워드 통계를 비롯하여 검색에서 반환할 예상 메시지 개수를 가져옵니다. 
    
- **검색 결과 미리 보기**
    
- 검색 결과에 반환된 메시지를 검색 사서함에 복사합니다.
    
자세한 내용은 [원본 위치 eDiscovery](/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery)를 참조하십시오.
  
## <a name="mail-flow-rules"></a>메일 흐름 규칙

메일 흐름 규칙을 사용하여 조직을 통과하고 메시지에 대해 행동하는 메시지에 대한 특정 조건을 검색할 수 있습니다. 메일 흐름 규칙을 사용하면 전자 메일 메시지에 메시징 정책을 적용하고, 메시지를 보호하고, 메시징 시스템을 보호하고, 정보 유출을 방지할 수 있습니다.
  
현재 여러 조직들은 법률, 규정 요구 사항 또는 회사 정책에 따라 조직 내부 및 외부에서 받는 사람과 보낸 사람 사이의 상호 작용을 제한해야 합니다. 개인 사이의 상호 작용을 제한하는 것 외에 조직 내부의 부서 그룹 및 조직 외부의 엔터티와 일부 조직 역시 다음 메시징 정책 요구 사항에 의해 제한될 수 있습니다.
  
- 조직 내/외부에서 부적절한 콘텐츠를 주고받는 행위 차단
    
- 조직의 기밀 정보 필터링
    
- 특정 개인과 주고받은 메시지 추적 또는 복사
    
- 배달 전에 메시지 검사를 위해 인바운드 및 아웃바운드 메시지 리디렉션
    
- 조직을 통해 전달되는 메시지에 부인 적용
    
> [!IMPORTANT]
> 전자 메일 서버에 타사 iFilter를 설치해야 하는 첨부 파일 형식(예: Adobe .pdf)은 적절한 iFilter가 설치될 때까지 메일 흐름 규칙을 사용하여 검사할 수 없습니다. 메일 흐름 규칙에서 지원되는 파일 형식에 대한 자세한 내용은 [Use mail flow rules to inspect message attachments in Office 365.](/exchange/security-and-compliance/mail-flow-rules/inspect-message-attachments)
  
메일 흐름 규칙에 대한 자세한 내용은 [Mail flow rules in Exchange 2016을 참조하십시오.](/Exchange/policy-and-compliance/mail-flow-rules/mail-flow-rules?preserve-view=true&view=exchserver-2019)
  
## <a name="data-loss-prevention"></a>데이터 손실 방지

DLP(데이터 손실 방지) 기능은 심도 있는 콘텐츠 분석을 통해 조직의 중요한 정보를 식별하고, 모니터링하고, 보호하는 데 도움을 줍니다. DLP는 업무상 중요한 전자 메일에는 보호해야 할 기밀 데이터가 포함되어 있으므로 엔터프라이즈 메시지 시스템에 점점 더 중요한 프리미엄 기능입니다. 2016의 DLP 기능을 Exchange Online 생산성에 영향을 주지 않고 중요한 데이터를 보호할 수 있습니다.
  
EAC(Exchange 관리 센터) 관리 인터페이스에서 DLP 정책을 구성하면 다음과 같은 기능을 사용할 수 있습니다. 
  
- PCI-DSS 데이터, 금융서비스 현대화법(Gramm-Leach-Bliley Act) 데이터 같이 특정 형식의 중요한 정보 또는 또는 로캘별 PII(개인 식별 정보)를 검색하는 데 도움을 받을 수 있는, 미리 구성된 정책 템플릿으로 시작합니다.
    
- 기존 전송 규칙 조건 및 작업을 완벽하게 활용하고 새 전송 규칙을 추가합니다.
    
- DLP 정책의 효율성을 테스트한 후에 완전히 적용합니다.
    
- 자신의 사용자 지정 DLP 정책 템플릿과 중요한 정보 형식을 통합합니다.
    
- 메시지 첨부 파일, 본문 텍스트 또는 제목 줄에서 중요한 정보를 검색하고 메시지의 Exchange Online 조정합니다.
    
- 문서 지문을 사용하여 중요한 양식 데이터를 감지합니다. 문서 지문을 사용하면 전송 규칙 및 DLP 정책을 정의하는 데 사용할 수 있는 텍스트 기반 양식의 중요한 사용자 지정 정보 유형을 손쉽게 만들 수 있습니다.
    
- 장치용 팁, Outlook 2016, Outlook 2013, 웹용 Outlook 및 장치용 OWA에 대한 공지를 표시하여 데이터 손실을 줄이는 데 도움이 되므로 정책 정책을 추가하고 가음성 보고를 허용하여 정책의 효율성을 향상시킬 수 있습니다. 
    
- DLP 보고서의 문제 데이터를 검토하거나, 문제 보고서 생성 작업을 사용하여 자체 보고서를 추가합니다.
    
DLP에 대한 자세한 내용은 [데이터 손실 방지](/exchange/security-and-compliance/data-loss-prevention/data-loss-prevention)를 참조하세요.
  
## <a name="journaling"></a>저널링

SMTP를 통해 메시지를 수신할 수 있는 외부 사서함으로 전자 메일의 사본을 저널링하도록 Exchange Online을 구성할 수 있습니다. 저널링은 조직이 인바운드 및 아웃바운드 전자 메일 통신을 기록하여 법적, 규정 및 조직의 준수 요구 사항에 대응하는 데 도움이 됩니다. 메시징 보존 및 준수에 대한 계획을 세울 때는 저널링 및 저널링이 조직의 준수 정책과 잘 맞는지 이해하는 것이 중요합니다.
  
Exchange 관리 센터 또는 원격 Windows PowerShell을 사용하여 저널 규칙을 관리할 수 있습니다. 사용자별 및 메일 그룹별 기반으로 저널링을 구성하고, 내부 메시지만, 외부 메시지만 또는 둘 다 저널링하도록 선택할 수 있습니다. 저널링된 메시지에는 원본 메시지뿐 아니라 보낸 사람, 받는 사람, 참조, 숨은 참조에 대한 정보도 포함됩니다.
  
성공적이고 안정적인 저널링 솔루션을 사용하려면 다음 작업을 완료해야 합니다.
  
- 저널링 대상이 사서함의 Exchange Online 합니다.
    
- 고객 디렉터리에 저널링에 사용할 SMTP 대상 전자 메일 주소에 대한 연락처 개체를 만듭니다.
    
- 기본 저널 사서함을 사용할 수 없는 경우 저널 보고서를 캡처할 대체 저널 사서함으로 보조 연락처 개체를 만듭니다.
    
- SMTP 대상의 적절한 관리, 중복성, 가용성, 성능 및 기능 수준을 유지 관리하여 성공적인 메일 수락을 항상 보장합니다.
    
- 메시지 형식, 보낸 사람/받는 사람 정보 통합 및 적절한 내용 변환을 비롯하여 Exchange Server와 Exchange 전송에 각각의 상호 운용성을 제공합니다.
    
저널링에 대한 자세한 내용은 [저널링](/exchange/security-and-compliance/journaling/journaling)을 참조하세요.
  
## <a name="feature-availability"></a>기능 가용성

계획, 독립 실행형 옵션 및온-프레미스 솔루션에서 기능 가용성을 확인한 경우 서비스 [Exchange Online 참조하세요.](exchange-online-service-description.md)
