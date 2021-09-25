---
title: 받는 사람
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-recipients
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
ms.assetid: da22b03a-c981-49c6-9928-4312c2c5e2ee
description: 이 항목에서는 Microsoft Exchange Online에 포함된 받는 사람 관련 기능에 대해 설명합니다. 설명에는 전자 메일, 연락처, 메일 그룹 및 달력/예약 기능이 포함됩니다.
ms.openlocfilehash: 32df1af7663f4a57419432b9c8a64a87ade4e857
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/24/2021
ms.locfileid: "59671782"
---
# <a name="recipients"></a>받는 사람

이 항목에서는 Microsoft Exchange Online에 포함된 받는 사람 관련 기능에 대해 설명합니다. 설명에는 전자 메일, 연락처, 메일 그룹 및 달력/예약 기능이 포함됩니다.
  
## <a name="email"></a>전자 메일

모든 Microsoft Exchange Online 구독자에게는 사서함이 제공되며, 회의실 등의 시설 리소스에 대한 일정 예약 및 다중 액세스를 통한 전자 메일 주소 공유를 위한 특수 사서함도 사용할 수 있습니다. 대부분의 사서함에는 최대 저장 용량 제한이 적용되며, 관리자는 허용 가능한 사서함 크기를 제어할 수 있습니다. 제한 용량에 가까워지거나 도달했을 경우 자동 알림 및 제한을 통해 사용자에게 경고합니다. Exchange Online에는 메시지 크기, 메시지 속도, 받는 사람 목록 제한 등 여러 유형의 메시지 제한도 있습니다. 이러한 모든 기능과 제한의 세부 정보는 아래에 나와 있습니다.
  
> [!NOTE]
> 범용 주소는 Exchange Online에서 더 이상 지원되지 않습니다. 잠재적인 스팸 메시지로부터 보호하기 위해 받는 사람 필터링이 적용되어 조직에 존재하지 않는 전자 메일 주소는 거부됩니다. 
  
### <a name="mailbox-types-storage-limits-and-capacity-alerts"></a>사서함 유형, 저장소 제한 및 용량 경고

사용자가 사용 가능한 사서함 저장소 용량 및 기본 사서함 크기는 사서함 유형과 사용자의 구독 라이선스에 따라 결정됩니다. 관리자는 각 사용자별 사서함 크기 또는 모든 사용자의 사서함 크기를 줄일 수 있습니다. 또한 Exchange Online은 사용자의 사서함이 최대 용량에 가까워졌거나 도달하면 알림을 제공합니다.
  
자세한 내용은 이 항목의 "사서함 저장소 제한" 및 "용량 알림" [섹션을 Exchange Online 참조하세요.](exchange-online-limits.md)
  
### <a name="mailtips"></a>메일 설명

메일 설명은 사용자가 메시지를 작성하는 동안이나 주소를 입력하는 동안 받는 사람: 줄 위에 자동으로 나타나는 정보 메시지입니다. 잘못된 배달, 정책 위반 또는 불필요한 배달 못 함 보고서(NDR)를 방지하는 데 도움이 됩니다. 예를 들어 너무 큰 그룹이나 외부 받는 사람이 포함된 그룹, 또는 중재되거나 제한된 메일 그룹에 메시지를 보내려고 할 경우에는 메일 설명이 경고를 생성합니다. 자세한 내용은 [메일 설명](/exchange/clients-and-mobile-in-exchange-online/mailtips/mailtips)을 참조하세요.
  
### <a name="delegate-access"></a>대리인 액세스

Exchange Online은 사용자가 다른 사람에게 자신의 전자 메일 및 일정을 관리할 수 있게 하는 대리인 액세스를 지원합니다. 대리인 액세스는 일반적으로 관리자와 비서 간에 사용되는 기능으로, 비서가 관리자의 받는 메일 메시지를 처리하고 일정을 관리하는 경우 사용됩니다. 위임 액세스는 Exchange Online 또는 Outlook 웹용 Outlook 또는 Exchange 관리 센터의 관리자가 사용할 수 있습니다. 
  
대리인은 2가지 유형의 액세스를 사용할 수 있습니다.
  
- **다른 사람 대신 보내기** 대리인은 전자 메일 메시지를 작성한 후 보낸 사람 필드에 다른 사람의 이름을 입력할 수 있습니다. 보낸 사람 필드에는 "[대리인 이름]이(가) 다음 사람 대신 보냄: [다른 사람 이름]"으로 표시됩니다. 
    
- **다른 사람 이름으로 보내기** 대리인은 다른 사람의 사서함에서 사서함 소유자인 것처럼 메시지를 보낼 수 있습니다. 이 기능은 일반적으로 여러 직원이 각자의 Exchange Online 계정에서 전자 메일을 보내는 대신 공유 사서함에서 전자 메일 메시지를 보낼 때 사용됩니다. 
    
액세스 권한 위임에 대한 자세한 내용은 [받은 사람의 권한 관리](/Exchange/recipients/mailbox-permissions)를 참조하세요.
  
### <a name="inbox-rules"></a>받은 편지함 규칙

사용자는 Exchange Online에서 받은 편지함 규칙을 만들어 메시지를 받았을 때 조건을 기반으로 한 특정 작업을 메시지에 자동으로 수행할 수 있습니다. 예를 들어 특정 메일 그룹으로 보낸 모든 메일은 자동으로 특정 폴더로 이동되도록 규칙을 만들 수 있습니다. 사용자는 받은 편지함 규칙의 Outlook 또는 웹용 Outlook. 관리자는 서버 쪽 전달 및/또는 서버 쪽 자동 회신을 사용하지 않도록 설정하여 특정 유형의 받은 편지함 규칙을 차단할 수 있습니다. 예를 들어 서버 쪽 전자 메일 전달을 사용하지 않도록 설정할 경우 사용자는 자동으로 전자 메일을 개인 계정에 전달할 수 없습니다. 마찬가지로 서버 쪽 자동 회신을 사용하지 않도록 설정할 경우 외부에서 이 답장을 사용해 유효한 전자 메일 주소를 식별할 수 없습니다. 이러한 변경 내용은 원격 Windows Powershell을 통해 이루어집니다.
  
### <a name="clutter"></a>Clutter

클러터는 받은 편지함에서 가장 중요한 메시지에 중점을 둘 수 있게 도와줍니다. 이 기능은 기계 학습을 사용하여 우선 순위가 낮은 메시지를 새 클러터 폴더로 이동함으로써 받은 편지함을 우선 순위가 높은 메시지 위주로 정리합니다. 클러터는 기존 전자 메일 규칙을 따르므로, 전자 메일을 구성하는 규칙을 만든 경우 해당 규칙이 계속 적용되며 클러터 기능이 이러한 메시지에는 작용하지 않습니다. 클러터는 받은 편지함에 대해 기본적으로 사용되지 않도록 설정되어 있습니다. 자세한 내용은 [Office 365에서 받은 편지함 정리](https://go.microsoft.com/fwlink/?linkid=2144145)를 참조하세요.
  
### <a name="connected-accounts"></a>연결된 계정

연결된 계정 기능을 Exchange Online 사용자가 외부 전자 메일 계정(예: 개인 계정)을 Exchange Online 내부 전자 메일 계정에 연결한 다음 웹용 Outlook 사용하여 모든 메시지와 한 장소에서 상호 작용할 수 있습니다. 연결된 계정은 로그인 시 자동으로 웹용 Outlook. 사용자가 계정의 계정을 수동으로 동기화할 수도 웹용 Outlook. 관리자는 Exchange 관리 센터를 통해 특정 사용자 또는 모든 사용자에 대해 이 기능을 사용하도록 설정하고 사용하지 [않도록 설정할 수 있습니다.](/exchange/exchange-admin-center)
  
### <a name="inactive-mailboxes"></a>비활성 사서함

Exchange Online에서는 삭제된 사서함의 콘텐츠를 무기한 유지하는 기능을 제공합니다. 이 기능을 비활성 사서함이라고 합니다. 사서함을 삭제하기 전 사서함에 원본 위치 유지 또는 소송 보존 기능을 적용하면 사서함이 비활성 상태가 됩니다. 이렇게 하면 사서함의 콘텐츠가 무기한 유지됩니다. 관리자, 규정 준수 담당자 또는 레코드 관리자는 Exchange Online의 원본 위치 eDiscovery 기능을 사용하여 비활성 사서함의 콘텐츠에 액세스할 수 있습니다.
  
비활성 사서함을 사용하도록 설정하려면 삭제하기 전 사서함에 원본 위치 유지 또는 소송 보존 기능을 적용할 수 있도록 사서함에 Exchange Online 보관 구독이 포함되어 있거나 Exchange Online(계획 2) 라이선스가 할당되어 있어야 합니다.
  
> [!IMPORTANT]
> 삭제되기 전에 사서함에 유지가 배치되지 않으면 사서함의 콘텐츠가 보존되지 않거나 검색할 수 없습니다. 삭제 후 30일 내에 사서함을 복구할 수 있지만 사서함과 해당 콘텐츠는 복구된 경우 30일 후 영구적으로 삭제됩니다. 
  
자세한 내용은 다음 항목을 참조하십시오.
  
- [사서함의 비활성 사서함 Exchange Online](/microsoft-365/security/office-365-security/exchange-online-protection-overview)
    
- [원본 위치 유지 및 소송 보존](/exchange/security-and-compliance/in-place-and-litigation-holds)
    
- [원본 위치 eDiscovery](/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery)
    
## <a name="contacts-and-distribution-groups"></a>연락처 및 메일 그룹

### <a name="offline-address-book"></a>오프라인 주소록

오프라인 주소 목록 기능은 GAL(전체 주소 목록)에서 사용할 Outlook Active Directory 정보의 스냅숏을 제공합니다. 이러한 정보는 사용자가 오프라인으로 작업할 때 사용할 수 있도록 로컬에서 캐시됩니다.
  
### <a name="address-book-policies"></a>주소록 정책

Exchange Online 정책이 지원됩니다. ABP(주소록 정책)를 사용하면 사용자를 특정 그룹으로 분할하여 조직의 GAL(전체 주소 목록)에 대한 사용자 지정 보기를 제공할 수 있습니다. ABP를 만들 때 GAL, OAB(오프라인 주소록), 방 목록 및 하나 이상의 주소 목록을 정책에 할당합니다. 그런 다음 사서함 사용자에게 ABP를 할당하여 사용자 지정된 GAL에 대한 액세스 권한을 Outlook 웹용 Outlook. 관리자는 원격 Windows PowerShell을 사용하여 주소록 정책을 구성할 수 있습니다. 주소록 정책에 대한 자세한 내용은 [Exchange Online의 주소록](/exchange/address-books/address-books)을 참조하세요.
  
### <a name="address-lists"></a>주소 목록

Exchange Online 목록 및 GAL의 사용자 지정을 지원할 수 있습니다. GAL은 메일 사용이 가능한 모든 사용자, 메일 그룹 및 외부 연락처의 조직 전체 디렉터리입니다. 관리자는 디렉터리 동기화 도구 또는 원격 동기화 도구를 사용하여 GAL에서 사용자, 메일 그룹 및 연락처를 숨길 수 Windows PowerShell.
  
### <a name="hierarchical-address-books"></a>계층 구조 주소록

 계층 구조 주소록을 사용하면 최종 사용자가 조직 계층 구조를 사용하여 Exchange 조직에서 받는 사람을 찾을 수 있습니다. 관리자는 사전 순서의 목록이 아니라 연공서열 및 순위별로 주소록을 사용자 지정할 수 있습니다. 
  
### <a name="distribution-groups-global"></a>메일 그룹(전체)

메일 그룹(또는 메일 목록)은 회사에서 모든 사용자가 사용할 수 있는 사용자, 연락처, 다른 메일 그룹을 모아놓은 것입니다. 사용자가 메일 그룹 별칭에 전자 메일을 보내면 해당 그룹에 있는 모든 사람이 메시지를 받게 됩니다. 메일 그룹은 개인이 Outlook에 만든 개인 메일 그룹과 비슷하지만, 구성원 목록을 회사 전체에서 사용할 수 있다는 점만 다릅니다. 관리자는 Exchange 관리 센터에서 메일 그룹을 만듭니다. 이렇게 만든 그룹은 Exchange Online을 통해 온-프레미스 Active Directory에서 동기화할 수도 있습니다. 이러한 은하수의 GAL에 Outlook. Exchange Online은 아래 설명된 기능을 비롯한 고급 메일 그룹 기능을 지원합니다.
  
- **제한된 메일 그룹** 기본적으로 모든 사람은 모든 메일 그룹에 전자 메일을 보낼 수 있습니다. 관리자는 특정 개인만이 특정 그룹에 전자 메일을 보낼 수 있도록 권한을 변경하여 대형 메일 그룹의 부적절한 사용을 막는 등의 작업을 수행할 수 있습니다. 관리자는 또한 스팸 방지에 도움이 되도록 외부 소스가 전자 메일을 보내는 것을 차단할 수 있습니다. 디렉터리 동기화 도구를 사용하여 온-프레미스 Active Directory에서 동기화된 그룹의 경우, 제한의 특성이 클라우드에 자동으로 동기화됩니다. 자세한 내용은 [메일 그룹 관리](/Exchange/recipients/distribution-groups)를 참조하세요.
    
- **동적 메일 그룹** 동적 메일 목록 또는 쿼리 기반 메일 목록이라고도 하는 동적 메일 그룹은 해당 그룹에 메일을 보낼 때마다 산정됩니다. 이러한 산정은 관리자가 정의하는 필터 및 조건을 기준으로 합니다. 동적 메일 그룹은 원격 Windows Powershell을 통해 Exchange Online에서 관리됩니다. 동적 메일 그룹에 대한 자세한 내용은 [동적 메일 그룹 관리](/Exchange/recipients/dynamic-distribution-groups/dynamic-distribution-groups)를 참조하세요.
    
    > [!IMPORTANT]
    > Office 365 디렉터리 동기화 도구는 온-프레미스 Active Directory의 동적 메일 그룹을 무시하며, 이러한 동적 메일 그룹을 Exchange Online에 동기화하지 않습니다. 디렉터리 동기화 도구를 사용하는 조직은 온-프레미스에서 관리되는 일반적인 메일 그룹과 Exchange Online에서 관리되는 동적 메일 그룹을 구분할 수 있는 명명 규칙을 사용해야 합니다. 
  
- **중재된 메일 그룹** 관리자는 중재자를 선택하여 메일 그룹으로 가는 메시지의 흐름을 조정할 수 있습니다. 중재된 메일 그룹을 사용하면 아무나 메일 그룹 별칭에 전자 메일을 보낼 수 있지만, 메시지가 해당 그룹의 구성원에게 전달되기 전에 먼저 중재자가 이를 검토하고 승인해야 합니다. 중재에 대한 자세한 내용은 [메일 그룹 관리](/Exchange/recipients/distribution-groups)의 메시지 승인 섹션을 참조하세요.
    
- **셀프 서비스 메일 그룹** 관리자는 사용자에게 웹 기반의 인터페이스에서 사용자만의 메일 그룹 구성원을 관리할 수 있는 기능을 제공할 수 있습니다. 사용자는 메일 그룹 만들기, 삭제, 참여 또는 나가기에 대한 권한이 주어집니다. 이러한 기능은 모든 Exchange Online 사용자에 대해 기본적으로 사용하도록 설정되어 있습니다. 관리자는 원할 경우 이 기능을 사용하지 않도록 설정하여 IT 부서에서만 메일 그룹을 관리하도록 할 수 있습니다. 관리자는 또한 명명 정책을 만들어 사용자가 만드는 메일 그룹의 이름을 표준화하고 관리할 수 있습니다. 예를 들어 메일 그룹이 만들어졌을 때 메일 그룹 이름에 특정 접두사 또는 접미사를 추가하거나, 그룹 이름에 특정 단어를 사용할 수 없도록 할 수 있습니다. 
    
    > [!IMPORTANT]
    > 셀프 서비스 기능은 온-프레미스 Active Directory에서 Exchange Online으로 동기화된 메일 그룹에는 사용할 수 없습니다. 디렉터리 동기화를 사용하는 조직은 온-프레미스에서 관리되는 메일 그룹과 클라우드에서 관리되는 메일 그룹을 구분할 수 있는 명명 규칙을 사용해야 합니다. 
  
### <a name="external-contacts-global"></a>외부 연락처(전체)

외부 연락처는 지정된 조직의 외부에서 작업하는 사람에 대한 정보를 기록한 것입니다. 외부 연락처는 개인이 Outlook에 만든 개인 연락처와 비슷하지만, 회사 전체에서 사용할 수 있다는 점만 다릅니다. 관리자는 Exchange 관리 센터 또는 원격 Windows PowerShell을 사용하여 외부 연락처를 만듭니다. 이렇게 만든 연락처는 Exchange Online을 통해 온-프레미스 Active Directory에서 동기화할 수도 있습니다. 이러한 은하수의 GAL에 Outlook.
  
외부 연락처에 대한 자세한 내용은 [Exchange Online에서 조직 관계 만들기](/exchange/sharing/organization-relationships/create-an-organization-relationship)를 참조하세요.
  
## <a name="calendar-and-scheduling"></a>달력 및 일정

### <a name="resource-mailboxes"></a>리소스 사서함

회의실과 물리적 장비 등을 위한 리소스 사서함은 회사의 회의실이나 기타 시설 또는 리소스를 나타냅니다. 사용자는 모임 요청 또는 모임 요청에 리소스의 전자 메일 별칭을 추가하여 회의실 또는 리소스를 예약할 Outlook 웹용 Outlook. 회의실 및 리소스는 OUTLOOK 및 웹용 Outlook.
  
관리자는 Exchange 관리 센터 또는 원격 Windows PowerShell을 사용하여 리소스 사서함을 만듭니다. 이렇게 만든 사서함은 Exchange Online을 통해 온-프레미스 Active Directory에서 동기화할 수도 있습니다.
  
리소스 사서함에 대한 자세한 내용은 다음을 참조하십시오.
  
- [회의실 사서함 만들기 및 관리](/Exchange/recipients/room-mailboxes)
    
- [장비 사서함 관리](/Exchange/recipients/equipment-mailboxes)
    
### <a name="conference-room-management"></a>회의실 관리

Exchange Online에는 리소스 예약 도우미(RBA)가 포함되어 있어 회의실과 기타 리소스의 일정을 자동으로 관리할 수 있습니다. RBA가 구성된 리소스 사서함은 모임 이끌이의 모임 요청을 리소스의 가용 일정을 바탕으로 수락, 거절 또는 확인합니다. 
  
관리자는 자동화된 회의실 응답을 사용자 지정하고 조직의 예약 정책을 구성할 웹용 Outlook. 이러한 정책에는 누가 리소스의 일정을 예약할 수 있는지, 언제 예약할 수 있는지, 리소스의 일정에 어떤 모임 정보가 표시되는지, 허용되는 일정 충돌의 비율 등이 포함됩니다. 관리자는 리소스 예약 도우미를 사용하지 않도록 설정하고 특정 사용자를 할당하여 수동으로 회의실에 대한 모임 요청을 관리하게 할 수 있습니다.
  
관리자는 반드시 원격 Windows Powershell을 통해 RBA 설정을 정의하고 관리해야 합니다.
  
### <a name="out-of-office-replies"></a>부재 중 회신

부재 중 메시지는 메시지를 받았을 때 사용자를 대신하여 Exchange Online가 보내는 자동 회신입니다. 사용자는 시작 시간과 종료 시간을 지정하여 부재 중 메시지를 미리 예약할 수 있으며, 내부 받는 사람과 외부 받는 사람에게 별도의 부재 중 메시지를 보내도록 구성할 수도 있습니다. 이 Exchange ActiveSync 기능을 지원하는 모바일 장치에서도 부재 중 메시지를 설정할 수 있습니다. 정크 메일 및 메일 그룹을 인식하는 Exchange Online은 사용자가 외부 부재 중 메시지를 확장된 메일 그룹과 잠재적인 스패머에게 보내는 것을 방지해 줍니다. 관리자는 원격 Windows PowerShell을 사용하여 부재 중 메시지를 외부 사용자에게 보내는 것을 방지할 수도 있습니다.
  
### <a name="calendar-sharing"></a>일정 공유

사용자는 다음 두 가지 방법을 통해 개인 일정을 공유할 수 있습니다.
  
- **페더레이션 일정 공유** 페더레이션은 페더레이션 공유를 지원하는 기본 트러스트 인프라를 나타내며, Exchange 사용자가 다른 외부 페더레이션 조직의 받는 사람과 약속 있음/없음 일정 데이터 및 연락처 정보를 쉽게 공유할 수 있는 방법입니다. 여기에는 Exchange Online 조직이나 Exchange Server 2010 또는 Exchange Server 2013 온-프레미스를 실행하는 조직이 포함됩니다. Exchange Online Microsoft 서비스를 만들 때 모든 Microsoft Federation Gateway 고객에 대해 이 트러스트가 미리 구성되어 Exchange Online 관리자와 트러스트 설정을 할 필요가 없습니다. 기본 공유 정책을 사용하면 사용자가 2010 또는 2010 또는 2010에서 일정 공유 초대를 웹용 Outlook Outlook 있습니다. 관리자는 원격 Windows PowerShell을 사용해 이 정책을 사용하지 않도록 설정하거나 사용자가 공유하는 약속 있음/없음 일정 데이터의 수준을 구성할 수 있습니다. 관리자는 또한 다른 페더레이션 조직과 조직 대 조직 관계를 생성하여, 개별 사용자가 공유 초대를 만들 필요 없이 모든 사용자에 대한 약속 있음/없음 정보를 원하는 수준으로 조직 서로 간에 볼 수 있도록 허용할 수 있습니다. 관리자가 정의한 공유 정책 및/또는 조직 대 조직 관계의 범위 내에서 사용자는 각자의 공유 세부 정보를 제한할 수 있습니다. 
    
- **인터넷 일정 공유** Exchange Online에서 사용자는 조직 내부 또는 외부 사람의 익명 액세스에 대해 iCal 형식을 사용하여 자신의 일정을 게시할 수 있습니다. Exchange나 다른 플랫폼, 또는 단순히 웹 브라우저의 사용자에게 보낼 수 있습니다. Exchange Online 다른 사용자가 iCal을 통해 인터넷 위치에 게시한 일정을 구독할 수 있습니다. 이 개인 일정 공유는 관리자가 구성하고 조직 대 조직 약속 있음/없음 공유를 제공하는 페더레이션 일정 공유와는 다릅니다. 관리자가 일정 데이터를 허용하는 공유 정책을 설정하고 적용하기 전까지는 어떤 사용자도 iCal 형식으로 일정 데이터를 게시할 수 없습니다. 관리자는 원격 Windows PowerShell을 사용하여 조직 내 사용자에 대해 iCal 게시 및 iCal 구독을 사용하지 않도록 설정할 수 있습니다.
    
페더레이션 공유에 대한 자세한 내용은 [Exchange Online의 공유](/exchange/sharing/sharing)를 참조하세요.
  
### <a name="outlook-2010-room-finder"></a>Outlook 2010 회의실 찾기

Exchange Online은 모임을 예약할 때 가까운 회의실을 쉽게 찾을 수 있도록 회의실 목록(예: "5번 건물 회의실")을 만들어주는 Outlook 2010의 회의실 찾기 기능을 지원합니다. 회의실 목록에 표시되려면 다음 2가지 방법을 통해 메일 그룹을 특수하게 표시해야 합니다. 
  
- 새 회의실 목록은 원격 Windows Powershell을 사용하여 만들 수 있습니다. 
    
- 회의실만 포함된 모든 메일 그룹은 원격 Windows PowerShell을 통해 회의실 목록으로 변환할 수 있습니다.
    
## <a name="feature-availability"></a>기능 가용성

계획, 독립 실행형 옵션 및온-프레미스 솔루션에서 기능 가용성을 확인한 경우 서비스 [Exchange Online 참조하세요.](exchange-online-service-description.md)
