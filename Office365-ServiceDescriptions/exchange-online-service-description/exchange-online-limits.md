---
title: Exchange Online 제한
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 7/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-limits
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 70b38a05-6cfa-4ced-a137-116019262fed
description: 주소록 제한, 사서함 저장 용량 제한, 보고 및 메시지 추적 제한을 비롯하여 다양한 서비스 영역에 대한 Exchange Online 제한을 확인할 수 있습니다.
ms.openlocfilehash: f6b47ddbbba3eeb40c564bbcfa5ace25671ade9e
ms.sourcegitcommit: 451688016111b1ccae37b9b84d7cf53d844acdbc
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/08/2018
ms.locfileid: "25450580"
---
# <a name="exchange-online-limits"></a>Exchange Online 제한

주소록 제한, 사서함 저장 용량 제한, 보고 및 메시지 추적 제한을 비롯하여 다양한 서비스 영역에 대한 Exchange Online 제한을 확인할 수 있습니다.
  
> [!NOTE]
>  작업에 대한 도움이 필요한 경우나 문제를 해결하고 있는 경우 다음 문서가 도움이 될 수 있습니다.  <br/> • [전자 메일](https://support.office.com/en-us/article/Email-94275804-7147-4332-9ccd-5d421760a9ed?ui=en-US&amp;rs=en-US&amp;ad=US) (도움말에 대 한 전자 메일을 발송 하 고 만들기 (영문))  <br/> • [-관리자 도움말 비즈니스용 Office 365의 전자 메일](https://go.microsoft.com/fwlink/?linkid=529722) <br/>   • [수정 Outlook 및 Microsoft 기술 지원 서비스 및 Office 365에 대 한 복구 도우미 사용 하 여 Office 365 문제](https://diagnostics.office.com/) <br/>  • [Office 365에서 전자 메일 배달 못함 보고서](https://go.microsoft.com/fwlink/?linkid=526653) <br/> • [Exchange 온라인 도움말](https://go.microsoft.com/fwlink/?linkid=825607) <br/>
  
Microsoft Exchange Online의 제한은 다음 범주 중 하나에 맞게:
  
- [주소록 제한](#address-book-limits)
    
- [사서함 저장소 제한](#mailbox-storage-limits)
    
- [용량 경고](#capacity-alerts)
    
- [사서함 폴더 제한](#mailbox-folder-limits)
    
- [메시지 제한](#message-limits)

- [수신 및 전송 제한](#receiving-and-sending-limits)
    
- [보고 및 메시지 추적 제한](#reporting-and-message-trace-limits)
    
- [보존 제한](#retention-limits)
    
- [메일 그룹 제한](#distribution-group-limits)
    
- [저널, 전송 및 받은 편지함 규칙 제한](#journal-transport-and-inbox-rule-limits)
    
- [중재 제한](#moderation-limits)
    
- [Exchange ActiveSync 제한](#exchange-activesync-limits)
    
> [!IMPORTANT]
>  • Microsoft Office 365 조직에 적용 되는 제한 시간 조직에 따라 다를 수 있습니다 서비스에 등록 된 했습니다.<br/> • Microsoft 데이터에는 한도 변경 되 면 센터, 모든 기존 고객에 게는 변경 내용을 적용 하려면 시간이 다소 걸릴 수 있습니다.<br/> • 이러한 제한 하지만 사용자와 함께 대부분을 수정할 수는 그 중 알고 있어야 합니다.<br/> • 이러한 제한은 내부 및 외부 받는 사람에 게 적용 됩니다.<br/> 기본적으로 Exchange Online Protection (EOP)? Exchange Online 사서함을 보호 합니다. Exchange Online EOP 기능에 적용 되는 제한에 대 한 [Exchange Online Protection Limits](../exchange-online-protection-service-description/exchange-online-protection-limits.md)을 참조 하십시오.<br/> • Office 365 그룹 제한에 대 한 정보에 대 한 [Office 365 그룹에 대 한 설명](https://go.microsoft.com/fwlink/?linkid=846714)의 "관리 하려면 어떻게 해야 합니까 groups?"를 참조 합니다. 
  
## <a name="address-book-limits"></a>주소록 제한

- **주소록 목록 제한** Exchange Online 또는 Exchange Server 2013 조직에서 만들 수 있는 주소 목록의 최대 수입니다. 이 수에는 Exchange Online의 기본 주소 목록(예: 모든 연락처 및 모든 그룹)이 포함됩니다. 
    
    > [!NOTE]
    > 최대 20개의 주소 목록을 단일 오프라인 주소록(OAB)으로 할당할 수 있습니다. 
  
- **오프라인 주소록 제한** Exchange Online 또는 Exchange Server 2013 조직에서 만들 수 있는 OAB(오프라인 주소록)의 최대 수입니다. 
    
- **주소록 정책 제한** Exchange Online 또는 Exchange Server 2013 조직에서 만들 수 있는 ABP(주소록 정책)의 최대 수입니다. 
    
- **전체 주소 목록** Exchange Online 또는 Exchange Server 2013 조직에서 만들 수 있는 GAL(전체 주소 목록)의 최대 수입니다. 
    
### <a name="address-book-limits-across-office-365-options"></a>Office 365 옵션의 주소록 제한

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**기능** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|주소 목록 제한  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |
|OAB(오프라인 주소록) 제한  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|ABP(주소록 정책) 제한  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|전체 주소 목록 제한  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
   
### <a name="address-book-limits-across-standalone-plans"></a>독립 실행형 계획의 주소록 제한

||||||
|:-----|:-----|:-----|:-----|:-----|
|**기능** <br/> |**Exchange Server 2013** <br/> |**Exchange Online 계획 1** <br/> |**Exchange Online 계획 2** <br/> |**Exchange Online Kiosk** <br/> |
|주소 목록 제한  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |
|OAB(오프라인 주소록) 제한  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|ABP(주소록 정책) 제한  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|전체 주소 목록 제한  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
   
## <a name="mailbox-storage-limits"></a>사서함 저장소 제한

사용할 수 있는 사서함 저장소의 크기는 사서함 유형 및 사용자의 구독 라이선스에 따라 결정됩니다. 관리자는 각 사용자별 사서함 크기 또는 모든 사용자의 사서함 크기를 줄일 수 있습니다.
  
> [!NOTE]
> 보관 목적으로 Exchange Online 사서함에 메시지를 복사하는 저널링, 전송 규칙 또는 자동 전달 규칙을 사용하는 것은 허용되지 않습니다. 사용자의 보관 사서함은 해당 사용자만을 위한 것입니다. Microsoft는 사용자의 보관 사서함이 다른 사용자의 보관 데이터를 저장하는데 사용되는 경우 인스턴스의 무제한 보관을 거부할 권리를 가지고 있습니다. 
  
### <a name="storage-limits-across-office-365-options"></a>Office 365 옵션별 저장소 제한

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**기능** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|사용자 사서함  <br/> |50GB  <br/> |50GB  <br/> |50GB  <br/> |100GB  <br/> |100GB  <br/> |2GB  <br/> |
|보관 사서함<sup>7, 8</sup> <br/> |50GB  <br/> |50GB  <br/> |50GB  <br/> |무제한<sup>1</sup> <br/> |무제한<sup>1</sup> <br/> |사용할 수 없음<sup>4</sup> <br/> |
|공유 사서함  <br/> |50GB<sup>2</sup> <br/> |50GB<sup>2</sup> <br/> |50GB<sup>2</sup> <br/> |50GB<sup>2,9</sup> <br/> |50GB<sup>2,9</sup> <br/> |50GB<sup>2</sup> <br/> |
|리소스 사서함  <br/> |50GB<sup>3</sup> <br/> |50GB<sup>3</sup> <br/> |50GB<sup>3</sup> <br/> |50GB<sup>3,9</sup> <br/> |50GB<sup>3,9</sup> <br/> |50GB<sup>3</sup> <br/> |
|사이트 사서함<sup>5</sup> <br/> |50GB  <br/> |50GB  <br/> |50GB  <br/> |50GB  <br/> |50GB  <br/> |사용할 수 없음  <br/> |
|공용 폴더 사서함  <br/> |50GB<sup>6</sup> <br/> |50GB<sup>6</sup> <br/> |50GB<sup>6</sup> <br/> |100GB<sup>6</sup> <br/> |100GB<sup>6</sup> <br/> |사용할 수 없음  <br/> |
|그룹 사서함  <br/> |50GB  <br/> |50GB  <br/> |50GB  <br/> |50GB  <br/> |50GB  <br/> |50GB  <br/> |
   
> [!NOTE]
> 각 사용자는 <sup>1</sup> 보관 사서함에 100GB의 저장을 처음 받습니다. 보관 자동 확장 기능이 켜져은 추가 저장소 100GB 저장 용량에 도달 하면 자동으로 추가 됩니다. 자세한 내용은 [Office 365 무제한 보관의 개요](https://go.microsoft.com/fwlink/?linkid=844060)를 참조 하십시오. 가용성에 대 한 자세한 내용은 [Office 365 로드맵](http://go.microsoft.com/fwlink/?LinkId=509914) 를 참조 하십시오.<br/>  <sup>2</sup> 공유 사서함에 액세스 하려면 사용자는 Exchange Online 라이센스가 있어야 합니다. 공유 사서함에는 별도 라이선스가 필요 하지 않습니다. 그러나 한 라이선스가 없는 공유 사서함은 50GB로 제한 합니다. 사서함 크기를 늘리려면 E3 또는 e 5 라이선스를 할당 해야 합니다. 이렇게 하면 사서함 100GB로 증가 합니다. 공유 사서함에 소송 보존을 배치 하거나 보관 사서함을 사용 하려는 경우 Exchange Online 계획 2 라이선스 또는 Exchange Online 계획 1 Exchange Online 보관 라이선스로 필요 합니다. 보관 사서함 및 공유 사서함에 대 한 보관 자동 확장을 사용 하는 경우의 보관 사서함에 100GB 저장 용량에 도달 하면 추가 저장소 자동으로 추가 됩니다.<br/>  <sup>3</sup> 리소스 사서함에는 라이선스가 필요 하지 않습니다. 그러나 한 라이선스가 없는 공유 사서함은 50GB로 제한 합니다. 사서함 크기를 늘리려면 E3 또는 e 5 라이선스를 할당 해야 합니다. 이렇게 하면 사서함 100GB로 증가 합니다.<br/>  <sup>4</sup> 보관 사서함에는 Exchange Online Kiosk에 포함 되지 않습니다. 그러나 Exchange Online 보관을 통해 추가 기능으로 구입할 수 있습니다. 자세한 내용은 [Exchange Online 보관 서비스 설명](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md)을 참조 하십시오.<br/>  <sup>5</sup> 사이트 사서함 만들고 SharePoint Online에서 관리 합니다. 자세한 내용은 [Office 365에서 사이트 사서함을 사용 하 여 준비](http://go.microsoft.com/fwlink/p/?LinkId=299131)를 참조 합니다.<br/>  <sup>6</sup> 공용 폴더 사서함 1, 000 개로 제한 되며 모든 공용 폴더 사서함의 최대 크기는 50 t B입니다.<br/>  <sup>7</sup> 보관 사서함만 사용할 수 있습니다는 라이선스가 적용 되었는지에 대 한 단일 사용자 또는 엔터티 (예: 공유 사서함)에 대 한 메일을 보관할 수 있습니다. 보관 사서함을 사용 하 여 여러 사용자 또는 엔터티에서 메일을 저장 하는 수단으로 행위는 금지 됩니다. 예, IT 관리자가 공유 사서함 만들기 및 보관 명시적 목적을 위해 (참조 또는 숨은 참조 필드를 통해 또는 전송 규칙을 통해) 복사 하는 사용자가 수는 없습니다. 참고 여러 사용자를 사용 하는 공유 사서함 실제로 이러한 개별 사용자에 대 한 전자 메일 저장 하 고 있지 않습니다. 여러 사용자가 액세스 하 고 공유 사서함으로 전자 메일을 보낼 합니다. 따라서 공유 사서함에 저장 된 유일한 전자 메일이 것 *으로* 공유 사서함에서 주고받은입니다.<br/>  <sup>8</sup> Exchange Online의 보존 정책을 만든 경우 메시지가 자동으로 이동할 사용자의 보관 사서함 사용자의 기본 사서함 10MB 보다 큰 경우에 합니다. 10MB 보다 작은 수 있는 사서함에 대 한 보존 정책을 자동으로 실행 되지 않습니다.<br/>  <sup>9</sup> 공유 및 리소스 사서함에는 라이선스가 필요 하지 않습니다. 그러나 한 라이선스가 없는 공유 사서함은 50GB로 제한 합니다. 사서함 크기를 늘리려면 E3 또는 e 5 라이선스를 할당 해야 합니다. 이렇게 하면 사서함 100GB로 증가 합니다. 
  
### <a name="storage-limits-across-standalone-plans"></a>독립 실행형 계획별 저장소 제한

||||||
|:-----|:-----|:-----|:-----|:-----|
|**기능** <br/> |**Exchange Server 2013** <br/> |**Exchange Online 계획 1** <br/> |**Exchange Online 계획 2** <br/> |**Exchange Online Kiosk** <br/> |
|사용자 사서함  <br/> |2GB<sup>1</sup> <br/> |50GB  <br/> |100GB  <br/> |2GB  <br/> |
|보관 사서함<sup>8, 9</sup> <br/> |100GB<sup>1</sup> <br/> |50GB  <br/> |무제한<sup>2</sup> <br/> |사용할 수 없음<sup>5</sup> <br/> |
|공유 사서함  <br/> |2GB<sup>1</sup> <br/> |50GB<sup>3</sup> <br/> |50GB<sup>3,10</sup> <br/> |50GB<sup>3</sup> <br/> |
|리소스 사서함  <br/> |2GB<sup>1</sup> <br/> |50GB<sup>4</sup> <br/> |50GB<sup>4,10</sup> <br/> |50GB<sup>4</sup> <br/> |
|공용 폴더 사서함  <br/> |2GB<sup>6</sup> <br/> |50GB<sup>7</sup> <br/> |100GB<sup>7</sup> <br/> |사용할 수 없음  <br/> |
|그룹 사서함  <br/> |50GB  <br/> |50GB  <br/> |50GB  <br/> |50GB  <br/> |
   
> [!NOTE]
> <sup>1</sup> Exchange Server 2013 조직에 대 한 기본 사서함 크기입니다. 관리자가 조직에 대 한이 값을 변경할 수 있습니다. 온-프레미스 사서함에 대 한 최대 저장 용량 제한이 없습니다.<br/>  각 사용자는 <sup>2</sup> 의 보관 사서함에 100GB의 저장을 처음 받습니다. 보관 자동 확장 기능이 켜져은 추가 저장소 100GB 저장 용량에 도달 하면 자동으로 추가 됩니다. 자세한 내용은 [Office 365 무제한 보관의 개요](https://go.microsoft.com/fwlink/?linkid=844060)를 참조 하십시오. 자동 확장에 대 한 가용성에 대 한 자세한 내용은 [Office 365 로드맵](http://go.microsoft.com/fwlink/?LinkId=509914) 참조 보관 합니다.<br/> <sup>3</sup> 을 공유 사서함에 액세스 하려면 사용자는 Exchange Online 라이선스가 있어야 합니다. 공유 사서함에는 별도 라이선스가 필요 하지 않습니다. 그러나 한 라이선스가 없는 공유 사서함은 50GB로 제한 합니다. 사서함 크기를 늘리려면 Exchange Online 계획 2 라이선스를 할당 되어야 합니다. 이렇게 하면 사서함 100GB로 증가 합니다. 공유 사서함에 소송 보존을 배치 하거나 보관 사서함을 사용 하려는 경우 Exchange Online 계획 2 라이선스 또는 Exchange Online 계획 1 Exchange Online 보관 라이선스로 필요 합니다. 보관 사서함 및 공유 사서함에 대 한 보관 자동 확장을 사용 하는 경우의 보관 사서함에 100GB 저장 용량에 도달 하면 추가 저장소 자동으로 추가 됩니다.<br/> <sup>4</sup> 리소스 사서함에는 라이선스가 필요 하지 않습니다. 그러나 한 라이선스가 없는 공유 사서함은 50GB로 제한 합니다. 사서함 크기를 늘리려면 Exchange Online 계획 2 라이선스를 할당 되어야 합니다. 이렇게 하면 사서함 100GB로 증가 합니다.<br/>  <sup>5</sup> 보관 사서함에는 Exchange Online Kiosk에 포함 되지 않습니다. 그러나 Exchange Online 보관을 통해 추가 기능으로 구입할 수 있습니다. 자세한 내용은 [Exchange Online 보관 서비스 설명](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md)을 참조 하십시오.<br/>  <sup>6</sup> Microsoft Exchange Server 2013 조직에 대 한 기본 사서함 크기입니다. 관리자가 조직에 대 한이 값을 변경할 수 있습니다. Exchange Server 2013 공용 폴더 사서함 개수는 100 개로 제한 되며 모든 공용 폴더 사서함의 최대 크기는 50 t B입니다.<br/>  <sup>7</sup> In Exchange Online에서 공용 폴더 사서함 1, 000 개로 제한 되며 모든 공용 폴더 사서함의 최대 크기는 50 t B입니다.<br/>  <sup>8</sup> 보관 사서함만 하는데 사용할 수는 단일 사용자 또는 라이선스 적용 된 엔터티에 대 한 메일을 보관 합니다. 하는 수단으로 보관 사서함을 사용 하 여 여러 사용자 또는 엔터티에서 메일을 저장 하는 금지 됩니다. 예, IT 관리자 공유 사서함을 만들 및 보관 명시적 목적을 위해 (참조 또는 숨은 참조 필드를 통해 또는 전송 규칙을 통해) 공유 사서함을 복사 하는 사용자가 수는 없습니다.<br/>  <sup>9</sup> Exchange Online의 보존 정책을 만든 경우 메시지가 자동으로 이동할 사용자의 보관 사서함 사용자의 기본 사서함 10MB 보다 큰 경우에 합니다. 10MB 보다 작은 수 있는 사서함에 대 한 보존 정책을 자동으로 실행 되지 않습니다.<br/>  <sup>10</sup> 공유 및 리소스 사서함에 게 할당할 라이선스를 필요 하지 않습니다. 그러나 한 라이선스 없이 이러한 사서함은 50GB로 제한 합니다. 사서함 크기를 늘리려면 Exchange Online 계획 2 라이선스를 할당 해야 합니다. 이렇게 하면 사서함 100GB로 증가 합니다. 
  
> [!NOTE]
> 공유 사서함 직접 로그온을 위해 설계 되지 않았습니다. 자체는 공유 사서함에 대 한 사용자 계정을 **비활성화 된** (또는 "연결이 끊긴")에서 상태를 유지 해야 상태입니다. 
  
## <a name="capacity-alerts"></a>용량 경고

Exchange Online에서는 사용자 사서함이 제한 용량에 가까워지거나 도달했을 경우 3가지 유형의 알림을 통해 사용자에게 경고합니다.
  
- **경고** 사서함이 최대 크기 제한에 가까워지고 있다는 전자 메일 경고가 사용자에게 발송됩니다. 이 경고는 사용자가 원치 않는 메일을 삭제하도록 장려하기 위해 발송됩니다. 
    
- **보내기 금지** 사서함 크기가 제한 용량에 도달할 경우 보내기 금지 알림 전자 메일이 사용자에게 발송됩니다. 전자 메일을 삭제하여 사서함 크기가 제한 용량 미만으로 줄어들 때까지 새로운 메시지를 보낼 수 없습니다. 
    
- **보내기/받기 금지** 사서함 크기가 제한 용량에 도달할 경우 Exchange Online은 모든 받는 메일을 거부하고 보낸 사람에게는 배달 못 함 보고서(NDR)을 보냅니다. 보낸 사람에게는 나중에 다시 해당 전자 메일을 보내도록 시도할 수 있는 옵션이 제공됩니다. 사용자는 사서함 크기가 제한 용량 미만으로 줄어들 때까지 전자 메일을 삭제해야만 다시 메시지를 받을 수 있습니다. 
    
### <a name="capacity-alerts-across-office-365-options"></a>Office 365 옵션별 용량 경고

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**기능** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|경고  <br/> |49GB  <br/> |49GB  <br/> |49GB  <br/> |98GB  <br/> |98GB  <br/> |1.96GB  <br/> |
|보내기 금지  <br/> |49.5GB  <br/> |49.5GB  <br/> |49.5GB  <br/> |99GB  <br/> |99GB  <br/> |1.98GB  <br/> |
|보내기/받기 금지  <br/> |50GB  <br/> |50GB  <br/> |50GB  <br/> |100GB  <br/> |100GB  <br/> |2GB  <br/> |
   
### <a name="capacity-alerts-across-standalone-plans"></a>독립 실행형 계획별 용량 경고

||||||
|:-----|:-----|:-----|:-----|:-----|
|**기능** <br/> |**Exchange Server 2013** <br/> |**Exchange Online 계획 1** <br/> |**Exchange Online 계획 2** <br/> |**Exchange Online Kiosk** <br/> |
|경고  <br/> |1.9GB<sup>1</sup> <br/> |49GB  <br/> |98GB  <br/> |1.96GB  <br/> |
|보내기 금지  <br/> |2GB<sup>1</sup> <br/> |49.5GB  <br/> |99GB  <br/> |1.98GB  <br/> |
|보내기/받기 금지  <br/> |2.3GB<sup>1</sup> <br/> |50GB  <br/> |100GB  <br/> |2GB  <br/> |
   
> [!NOTE]
> <sup>1</sup>Exchange Server 2013 조직의 기본값입니다. 관리자는 자신의 조직에 대한 이 값을 변경할 수 있습니다. 
  
## <a name="mailbox-folder-limits"></a>사서함 폴더 제한

이러한 제한은 사서함을 Exchange Online에서 지원 가능한 크기로 제한하기 위한 값입니다. 이러한 제한을 둠으로써 폴더당 사서함 항목, 사서함당 폴더 또는 Exchange Online 조직당 공용 폴더가 무제한으로 사용되는 것을 방지할 수 있습니다. 사실상 사서함 폴더 제한은 무한하며 대부분의 Exchange Online 사서함 및 Exchange Online으로 마이그레이션되는 온-프레미스 사서함을 지원하기에 충분합니다.
  
- **사서함 폴더당 최대 메시지 수** 사서함 폴더의 최대 메시지 수를 지정합니다. 이 제한에 도달하면 새 메시지를 폴더에 배달하거나 저장할 수 없습니다. 
    
- **사서함 폴더당 메시지 수에 대한 경고** Exchange Online이 사서함 소유자에게 경고 메시지를 보내기 전까지 최대한 사서함 폴더에 보유할 수 있는 메시지 수를 지정합니다. 이 할당량에 도달하면 경고 메시지가 하루에 한 번 전송됩니다. 
    
- **복구 가능한 항목 폴더의 폴더당 최대 메시지 수** 복구 가능한 항목 폴더의 각 폴더에 포함할 수 있는 최대 메시지 수를 지정합니다. 폴더에서 이 제한을 초과하면 새 메시지를 저장할 수 없습니다. 예를 들어 복구 가능한 항목 폴더의 삭제 폴더가 메시지 개수 제한을 넘고 사서함 소유자가 자신의 사서함의 항목을 영구 삭제하려고 하는 경우 삭제에 실패합니다. 
    
- **복구 가능한 항목 폴더의 폴더당 메시지 수 경고** Exchange Online이 응용 프로그램 이벤트 로그에 이벤트를 기록하게 되는 복구 가능한 항목 폴더의 폴더당 메시지 수를 지정합니다. 
    
- **사서함 폴더당 최대 하위 폴더 수** 사서함 폴더에 만들 수 있는 최대 하위 폴더 수를 지정합니다. 이 제한에 도달하면 사서함 사용자가 하위 폴더를 새로 만들 수 없습니다. 
    
- **사서함 폴더당 하위 폴더 수에 대한 경고** Exchange Online이 사서함 소유자에게 경고 메시지를 보내기 전까지 사서함 폴더당 생성 가능한 하위 폴더 수를 지정합니다. 이 할당량에 도달하면 경고 메시지가 하루에 한 번 전송됩니다. 
    
- **최대 폴더 계층** 사서함 폴더 계층 구조의 최대 폴더 단계 수를 지정합니다. 이 제한에 도달하면 사서함 사용자가 사서함 폴더 계층 구조에 폴더 단계를 더 추가하여 만들 수 없습니다. 
    
- **폴더 계층 수에 대한 경고** Exchange Online이 사서함 소유자에게 경고 메시지를 보내기 전까지 생성할 수 있는 사서함 폴더의 폴더 계층 수를 지정합니다. 이 할당량에 도달하면 경고 메시지가 하루에 한 번 전송됩니다. 
    
- **최대 공용 폴더 수** 전체 공용 폴더 계층 구조에서 공용 폴더의 최대 수를 지정합니다. 이 제한에 도달하면 기존 공용 폴더를 삭제해야 새 공용 폴더를 만들 수 있습니다. 
    
- **공용 폴더당 최대 하위 폴더 수** 공용 폴더에 만들 수 있는 최대 하위 폴더 수를 지정합니다. 이 제한에 도달하면 공용 폴더에서 새 하위 폴더를 만들 수 없습니다. 
    
- **공용 폴더당 하위 폴더 수에 대한 경고** Exchange Online이 폴더 소유자에게 경고 메시지를 보내기 전까지 공용 폴더당 생성 가능한 하위 폴더 수를 지정합니다. 소유자가 없으면 소유자 권한이 있는 사용자에게 경고 메시지가 전달됩니다. 이 할당량에 도달하면 경고 메시지가 하루에 한 번 전송됩니다. 
    
### <a name="mailbox-folder-limits-across-office-365-options"></a>Office 365 옵션별 사서함 폴더 제한

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**기능** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|사서함 폴더당 최대 메시지 수  <br/> |1백만 개  <br/> |1백만 개  <br/> |1백만 개  <br/> |1백만 개  <br/> |1백만 개  <br/> |1백만 개  <br/> |
|사서함 폴더당 메시지 수에 대한 경고  <br/> |900,000  <br/> |900,000  <br/> |900,000  <br/> |900,000  <br/> |900,000  <br/> |900,000  <br/> |
|복구 가능한 항목 폴더의 폴더당 최대 메시지 수  <br/> |3백만 개  <br/> |3백만 개  <br/> |3백만 개  <br/> |3백만 개  <br/> |3백만 개  <br/> |3백만 개  <br/> |
|기본 사서함에서 복구 가능한 항목 폴더에 대한 저장소 할당량(보류 중 아님)  <br/> |30GB  <br/> |30GB  <br/> |30GB  <br/> |30GB  <br/> |30GB  <br/> |30GB  <br/> |
|기본 사서함에서 복구 가능한 항목 폴더에 대한 저장소 할당량(보류 중)  <br/> |100GB  <br/> |100GB  <br/> |100GB  <br/> |100GB  <br/> |100GB  <br/> |100GB  <br/> |
|보관 사서함에서 복구 가능한 항목 폴더에 대한 저장소 할당량(보류 중 아님)  <br/> |30GB  <br/> |30GB  <br/> |30GB  <br/> |무제한<sup>2</sup> <br/> |무제한<sup>2</sup> <br/> |30GB  <br/> |
|보관 사서함에서 복구 가능한 항목 폴더에 대한 저장소 할당량(보류 중)  <br/> |100GB<sup>1</sup> <br/> |100GB<sup>1</sup> <br/> |100GB<sup>1</sup> <br/> |무제한<sup>2</sup> <br/> |무제한<sup>2</sup> <br/> |100GB<sup>1</sup> <br/> |
|복구 가능한 항목 폴더의 폴더당 메시지 수에 대한 경고  <br/> |2.75백만 개  <br/> |2,750,000개  <br/> |2,750,000개  <br/> |2,750,000개  <br/> |2,750,000개  <br/> |2,750,000개  <br/> |
|사서함 폴더당 최대 하위 폴더 수  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |
|사서함 폴더당 하위 폴더 수에 대한 경고  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |
|최대 폴더 계층 수  <br/> |300  <br/> |300  <br/> |300  <br/> |300  <br/> |300  <br/> |300  <br/> |
|폴더 계층 수에 대한 경고  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|최대 공용 폴더 수  <br/> | 500,000명  <br/> | 500,000명  <br/> | 500,000명  <br/> | 500,000명  <br/> | 500,000명  <br/> |사용할 수 없음  <br/> |
|공용 폴더당 최대 하위 폴더 수  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |사용할 수 없음  <br/> |
|공용 폴더당 하위 폴더 수에 대한 경고  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |사용할 수 없음  <br/> |
   
> [!NOTE]
> <sup>1</sup> 전체 보관 사서함에 대 한 할당량 하지 복구 가능한 항목 폴더에 대 한 저장소 할당량입니다. 보관 사서함에 대 한 저장소 할당량 Exchange Online 계획 2 라이선스를 사용 하 여 사용자 또는 Exchange Online 계획 1과 Exchange Online 보관 라이선스를 가진 사용자에 대 한 제한 되지 않습니다. 복구 가능한 항목 할당량 증가 하는 방법에 대 한 정보를 [증가에 있는 사서함에 대 한 할당량 대기 복구 가능한 항목을](http://technet.microsoft.com/library/a8bdcbdd-9298-462f-b889-df26037a990c.aspx)참조 하십시오.<br/> <sup>2</sup> 보관 사서함의 복구 가능한 항목 폴더에 대 한 초기 저장소 할당량은 100GB입니다. 보관 자동 확장 기능이 켜져은 추가 저장소 복구 가능한 항목 폴더에 대 한 저장 용량에 도달 하면 자동으로 추가 됩니다. 자세한 내용은 [Office 365 무제한 보관의 개요](https://go.microsoft.com/fwlink/?linkid=844060)를 참조 하십시오. 자동 확장의 가용성에 대 한 자세한 내용은 [Office 365 로드맵](http://go.microsoft.com/fwlink/?LinkId=509914) 참조 보관 합니다. 
  
### <a name="mailbox-folder-limits-across-standalone-plans"></a>독립 실행형 계획별 사서함 폴더 제한

||||||
|:-----|:-----|:-----|:-----|:-----|
|**기능** <br/> |**Exchange Server 2013** <br/> |**Exchange Online 계획 1** <br/> |**Exchange Online 계획 2** <br/> |**Exchange Online Kiosk** <br/> |
|사서함 폴더당 최대 메시지 수  <br/> |제한 없음<sup>1</sup> <br/> |1백만 개  <br/> |1백만 개  <br/> |1백만 개  <br/> |
|사서함 폴더당 메시지 수에 대한 경고  <br/> |제한 없음  <br/> |900,000  <br/> |900,000  <br/> |900,000  <br/> |
|복구 가능한 항목 폴더의 폴더당 최대 메시지 수  <br/> |제한 없음  <br/> |3백만 개  <br/> |3백만 개  <br/> |3백만 개  <br/> |
|기본 사서함에서 복구 가능한 항목 폴더에 대한 저장소 할당량(보류 중 아님)  <br/> |30GB  <br/> |30GB  <br/> |30GB  <br/> |30GB  <br/> |
|기본 사서함에서 복구 가능한 항목 폴더에 대한 저장소 할당량(보류 중)  <br/> |100GB  <br/> |100GB  <br/> |100GB  <br/> |100GB  <br/> |
|보관 사서함에서 복구 가능한 항목 폴더에 대한 저장소 할당량(보류 중 아님)  <br/> |30GB  <br/> |30GB  <br/> |30GB  <br/> |30GB  <br/> |
|보관 사서함에서 복구 가능한 항목 폴더에 대한 저장소 할당량(보류 중)  <br/> |100GB<sup>2</sup> <br/> |100GB<sup>2</sup> <br/> |무제한<sup>3</sup> <br/> |무제한<sup>3</sup> <br/> |
|복구 가능한 항목 폴더의 폴더당 메시지 수에 대한 경고  <br/> |제한 없음  <br/> |2,750,000개  <br/> |2,750,000개  <br/> |2,750,000개  <br/> |
|사서함 폴더당 최대 하위 폴더 수  <br/> |제한 없음  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |
|사서함 폴더당 하위 폴더 수에 대한 경고  <br/> |제한 없음  <br/> |900  <br/> |900  <br/> |900  <br/> |
|최대 폴더 계층 수  <br/> |제한 없음  <br/> |300  <br/> |300  <br/> |300  <br/> |
|폴더 계층 수에 대한 경고  <br/> |제한 없음  <br/> |250  <br/> |250  <br/> |250  <br/> |
|최대 공용 폴더 수  <br/> |1,000,000  <br/> |100,000  <br/> |100,000  <br/> |사용할 수 없음  <br/> |
|공용 폴더당 최대 하위 폴더 수  <br/> |해당 없음  <br/> |1,000  <br/> |1,000  <br/> |사용할 수 없음  <br/> |
|공용 폴더당 하위 폴더 수에 대한 경고  <br/> |해당 없음  <br/> |900  <br/> |900  <br/> |사용할 수 없음  <br/> |
   
> [!NOTE]
> <sup>1</sup> 개 이하의 1000000 메시지 사서함 폴더당 권장 됩니다. ><br/> <sup>2</sup> 전체 보관 사서함에 대 한 할당량 하지 복구 가능한 항목 폴더에 대 한 저장소 할당량입니다. 보관 사서함에 대 한 저장소 할당량 Exchange Online 계획 2 라이선스를 사용 하 여 사용자 또는 Exchange Online 계획 1과 Exchange Online 보관 라이선스를 가진 사용자에 대 한 제한 되지 않습니다. 복구 가능한 항목 할당량 증가 하는 방법에 대 한 정보를 [증가에 있는 사서함에 대 한 할당량 대기 복구 가능한 항목을](http://technet.microsoft.com/library/a8bdcbdd-9298-462f-b889-df26037a990c.aspx)참조 하십시오.<br/> <sup>3</sup> 보관 사서함의 복구 가능한 항목 폴더에 대 한 초기 저장소 할당량은 100GB입니다. 보관 자동 확장 기능이 켜져은 추가 저장소 복구 가능한 항목 폴더에 대 한 저장 용량에 도달 하면 자동으로 추가 됩니다. 자세한 내용은 [Office 365 무제한 보관의 개요](https://go.microsoft.com/fwlink/?linkid=844060)를 참조 하십시오. 자동 확장의 가용성에 대 한 자세한 내용은 [Office 365 로드맵](http://go.microsoft.com/fwlink/?LinkId=509914) 참조 보관 합니다. 
  
## <a name="message-limits"></a>메시지 제한

다음 제한은 모든 전자 메일 메시지에 적용됩니다.
  
- **메시지 크기 제한** 대용량 메시지가 다른 메시지의 배달을 차단하거나 사용자에 대한 서비스 성능에 영향을 미치지 않도록 하려면 메시지 크기 제한이 필요합니다. 이 제한은 첨부 파일을 포함하며 조직 전체에 대한 모든 메시지(인바운드, 아웃바운드, 내부)에 적용됩니다. 이 제한보다 큰 메시지는 배달되지 않으며, 보낸 사람에게는 배달 못 함 보고서(NDR)가 전송됩니다. 메시지 크기 제한은 더 크게, 더 작게 또는 각 사용자별로 구성할 수 있으며, 관리자는 전송 규칙을 만들어 모든 개별 첨부 파일의 최대 크기를 제한할 수도 있습니다. 자세한 내용은 [Office 365에서 더 큰 전자 메일 메시지 지원](https://blogs.office.com/2015/04/15/office-365-now-supports-larger-email-messages-up-to-150-mb/)을 참조하세요.
    
    > [!NOTE]
    > 특정 전자 메일 클라이언트의 메시지 크기 제한 또는 개별 첨부 파일의 크기 제한은 Exchange Online 메시지 크기 제한 값보다 작을 수 있습니다. 
  
- **제목 길이 제한** 전자 메일 메시지의 제목 줄에서 허용되는 텍스트 문자의 최대 개수입니다. 
    
- **첨부 파일 제한** 전자 메일 메시지에 허용되는 최대 첨부 파일 수입니다. 모든 첨부 파일의 전체 크기가 메시지 크기 제한을 넘지 않는 경우에도 메시지에서 허용되는 첨부 파일 수에 대한 제한이 있습니다. 이 제한은 여러 부분으로 구성된 메시지 제한을 통해 제어됩니다. 
    
- **첨부 파일 크기 제한** 단일 첨부 파일의 최대 파일 크기입니다. 
    
    > [!NOTE]
    > 단일 첨부 파일의 최대 파일 크기입니다. Outlook Web App을 포함한 개별 클라이언트 프로그램에서 첨부 파일 크기를 이 최대값 미만으로 제한할 수 있습니다. Exchange ActiveSync에서는 첨부 파일 크기 제한을 개별 첨부 파일별로 설정하지 않습니다. Exchange ActiveSync 메시지에 대한 모든 첨부 파일의 전체 크기는 메시지 크기 제한보다 작아야 합니다. 
  
- **여러 부분으로 구성된 메시지 제한** 여러 부분으로 구성된 MIME 형식의 메시지에서 허용되는 메시지 본문 부분의 최대 개수입니다. 이 제한은 메시지에서 허용되는 첨부 파일의 최대 수도 제어합니다. 
    
- **포함 메시지 수준 제한** 전자 메일 메시지에 허용되는 전달된 전자 메일 메시지의 최대 수입니다. 
    
### <a name="message-limits-across-office-365-options"></a>Office 365 옵션별 메시지 제한

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**기능** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|메시지 크기 제한 - Outlook  <br/> |150MB<sup>1, 2</sup> <br/> |150MB<sup>1, 2</sup> <br/> |150MB<sup>1, 2</sup> <br/> |150MB<sup>1, 2</sup> <br/> |150MB<sup>1, 2</sup> <br/> |150MB<sup>1, 2</sup> <br/> |
|메시지 크기 제한 - OWA  <br/> |112MB<sup>1, 3</sup> <br/> |112MB<sup>1, 3</sup> <br/> |112MB<sup>1, 3</sup> <br/> |112MB<sup>1, 3</sup> <br/> |112MB<sup>1, 3</sup> <br/> |112MB<sup>1, 3</sup> <br/> |
|메시지 크기 제한 - Outlook for Mac  <br/> |150MB<sup>1, 2</sup> <br/> |150MB<sup>1, 2</sup> <br/> |150MB<sup>1, 2</sup> <br/> |150MB<sup>1, 2</sup> <br/> |150MB<sup>1, 2</sup> <br/> |150MB<sup>1, 2</sup> <br/> |
|메시지 크기 제한 - 마이그레이션  <br/> |150MB <sup>4</sup> <br/> |150MB <sup>4</sup> <br/> |150MB <sup>4</sup> <br/> |150MB <sup>4</sup> <br/> |150MB <sup>4</sup> <br/> |150MB <sup>4</sup> <br/> |
|암호화된 메시지의 크기 제한(새 기능에 Office 365 메시지 암호화를 사용하는 구독자)<sup>5</sup> <br/> |150MB  <br/> |150MB  <br/> |150MB  <br/> |150MB  <br/> |150MB  <br/> |150MB  <br/> |
|암호화된 메시지의 크기 제한(Office 365 메시지 암호화 레거시 버전을 사용하는 구독자)<sup>5</sup> <br/> |25MB  <br/> |25MB  <br/> |25MB  <br/> |25MB  <br/> |25MB  <br/> |25MB  <br/> |
|제목 길이 제한  <br/> |255자  <br/> |255자  <br/> |255자  <br/> |255자  <br/> |255자  <br/> |255자  <br/> |
|파일 첨부 제한  <br/> |250개 첨부 파일  <br/> |250개 첨부 파일  <br/> |250개 첨부 파일  <br/> |250개 첨부 파일  <br/> |250개 첨부 파일  <br/> |250개 첨부 파일  <br/> |
|첨부 파일 크기 제한 - Outlook  <br/> |150MB  <br/> |150MB  <br/> |150MB  <br/> |150MB  <br/> |150MB  <br/> |150MB  <br/> |
|첨부 파일 크기 제한 - OWA <sup>6</sup> <br/> |35MB  <br/> |35MB  <br/> |35MB  <br/> |35MB  <br/> |35MB  <br/> |35MB  <br/> |
|첨부 파일 크기 제한 - Outlook for Mac  <br/> |150MB  <br/> |150MB  <br/> |150MB  <br/> |150MB  <br/> |150MB  <br/> |150MB  <br/> |
|여러 부분으로 구성된 메시지 제한  <br/> |250개 부분  <br/> |250개 부분  <br/> |250개 부분  <br/> |250개 부분  <br/> |250개 부분  <br/> |250개 부분  <br/> |
|포함 메시지 수준 제한  <br/> |30개 포함 메시지  <br/> |30개 포함 메시지  <br/> |30개 포함 메시지  <br/> |30개 포함 메시지  <br/> |30개 포함 메시지  <br/> |30개 포함 메시지  <br/> |
   
> [!NOTE]
> <sup>1</sup> Office 365 사서함에 대 한 기본 최대 메시지 크기는 25MB 합니다. Office 365 관리자 1MB 사이의 150MB 사용자 지정 제한을 지정할 수 있습니다. 그러나 메시지를 보내거나 받을 수 있는 크기 전자 메일 클라이언트 또는 솔루션 지원 기능에 따라 다릅니다. 조직에 대해 허용 되는 최대 메시지 크기를 사용자 지정 하는 방법에 대 한 자세한 내용은 [Office 365 이제 지원 더 큰 전자 메일 메시지를](https://blogs.office.com/2015/04/15/office-365-now-supports-larger-email-messages-up-to-150-mb/)참조 하십시오.<br/> <sup>2</sup> Office 365 사용자 간에 최대 150MB의 메시지를 보내고 받을 수 있습니다(메시지가 Office 365 데이터 센터를 벗어나지 않을 경우). Office 365 데이터 센터 외부로 전송되는 메시지는 변환 인코딩이 추가로 33% 증가할 수 있습니다. 이 경우 최대 메시지 크기는 112MB가 됩니다. <br/> <sup>3</sup> OWA 계정 메시지 인코딩 증가 33% 적용 될 수 있습니다 및 메시지의 크기를 제한 합니다. 가능성에 대 한 구성된 설정을 보다 작은 25%로 보낼 수 있습니다. 예, 100MB 최대 메시지 크기에 대 한 설정을, 사용자 지정 하는 경우 있습니다 메시지를 보낼 수 75MB를 넘지 않도록 합니다.<br/> <sup>4</sup> Exchange Online으로 이동될 메시지 크기는 Exchange Online에서 계산됩니다. Exchange Server 2013 이전의 Exchange 버전에서는 좀 더 작은 항목 크기를 보고할 수 있습니다. 이 제한은 지원되는 Exchange 사서함 복제 서비스를 사용하는 이동 기반 마이그레이션에 적용됩니다. 다른 마이그레이션 방법(단독형, 미리 구성, IMAP, PST) 및 기타 타사 도구는 일반 메시지 크기 제한에 따라 제한됩니다. <br/> <sup>5</sup> OME 하는 방법에 대 한 새로운 기능을 갖춘 정보에 대 한 참조 [Azure 정보 보호 위쪽에 구축 된 새로운 Office 365 메시지 암호화 기능을 설정](https://support.office.com/en-us/article/Set-up-new-Office-365-Message-Encryption-capabilities-built-on-top-of-Azure-Information-Protection-7ff0c040-b25c-4378-9904-b1b50210d00e?ui=en-US&amp;rs=en-US&amp;ad=US)합니다.<br/> <sup>6</sup> 35MB를 초과하는 단일 파일을 첨부할 수 없습니다. 또한 전체적으로 35MB를 초과하는 파일도 첨부할 수 없습니다. 예를 들어, 34MB 파일 하나를 첨부한 경우 추가로 1MB의 파일만 더 첨부할 수 있습니다. 
  
### <a name="message-limits-across-standalone-options"></a>독립 실행형 옵션별 메시지 제한

||||||
|:-----|:-----|:-----|:-----|:-----|
|**기능** <br/> |**Exchange Server 2013** <br/> |**Exchange Online 계획 1** <br/> |**Exchange Online 계획 2** <br/> |**Exchange Online Kiosk** <br/> |
|메시지 크기 제한 - Outlook  <br/> |10MB<sup>4</sup> <br/> |150MB<sup>1, 2</sup> <br/> |150MB<sup>1, 2</sup> <br/> |150MB<sup>2</sup> <br/> |
|메시지 크기 제한 - OWA  <br/> |10MB<sup>4</sup> <br/> |112MB<sup>1, 3</sup> <br/> |112MB<sup>1, 3</sup> <br/> |150MB<sup>1, 2</sup> <br/> |
|메시지 크기 제한 - Outlook for Mac  <br/> |10MB<sup>4</sup> <br/> |150MB  <br/> |150MB  <br/> ||
|메시지 크기 제한 - 마이그레이션  <br/> |해당 없음  <br/> |150MB <sup>5</sup> <br/> |150MB <sup>5</sup> <br/> |150MB <sup>5</sup> <br/> |
|암호화된 메시지의 크기 제한(새 기능에 Office 365 메시지 암호화를 사용하는 구독자)<sup>6</sup> <br/> |150MB  <br/> |150MB  <br/> |150MB  <br/> |150MB  <br/> |
|암호화된 메시지의 크기 제한(Office 365 메시지 암호화 레거시 버전을 사용하는 구독자)<sup>6</sup> <br/> |25MB  <br/> |25MB  <br/> |25MB  <br/> |25MB  <br/> |
|제목 길이 제한  <br/> |255자  <br/> |255자  <br/> |255자  <br/> |255자  <br/> |
|파일 첨부 제한  <br/> |1024 첨부 파일<sup>4</sup> <br/> |250개 첨부 파일  <br/> |250개 첨부 파일  <br/> |250개 첨부 파일  <br/> |
|첨부 파일 크기 제한 - Outlook  <br/> |35 MB<sup>4</sup> <br/> |150MB  <br/> |150MB  <br/> |150MB  <br/> |
|첨부 파일 크기 제한 - OWA  <br/> |35 MB<sup>4</sup> <br/> |35MB  <br/> |35MB  <br/> |35MB  <br/> |
|첨부 파일 크기 제한 - Outlook for Mac  <br/> |35 MB<sup>4</sup> <br/> |150MB  <br/> |150MB  <br/> |35MB  <br/> |
|여러 부분으로 구성된 메시지 제한  <br/> |250개 부분  <br/> |250개 부분  <br/> |250개 부분  <br/> |250개 부분  <br/> |
|포함 메시지 수준 제한  <br/> |30개 포함 메시지  <br/> |30개 포함 메시지  <br/> |30개 포함 메시지  <br/> |30개 포함 메시지  <br/> |
   
> [!NOTE]
> <sup>1</sup> office 365 관리자는 1MB 사이의 150MB 사용자 지정 제한을 지정할 수 있습니다. 그러나 메시지를 보내거나 받을 수 있는 크기 전자 메일 클라이언트 또는 솔루션 지원 기능에 따라 다릅니다. 조직에 대해 허용 되는 최대 메시지 크기를 사용자 지정 하는 방법에 대 한 자세한 내용은 [Office 365 이제 지원 더 큰 전자 메일 메시지를](https://blogs.office.com/2015/04/15/office-365-now-supports-larger-email-messages-up-to-150-mb/)참조 하십시오.<br/> <sup>2</sup> Office 365 사용자 간에 최대 150MB의 메시지를 보내고 받을 수 있습니다(메시지가 Office 365 데이터 센터를 벗어나지 않을 경우). Office 365 데이터 센터 외부로 전송되는 메시지는 변환 인코딩이 추가로 33% 증가할 수 있습니다. 이 경우 최대 메시지 크기는 112MB가 됩니다. <br/> <sup>3</sup> OWA 계정 메시지 인코딩 증가 33% 적용 될 수 있습니다 및 메시지의 크기를 제한 합니다. 가능성에 대 한 구성된 설정을 보다 작은 25%로 보낼 수 있습니다. 예, 100MB 최대 메시지 크기에 대 한 설정을, 사용자 지정 하는 경우 있습니다 메시지를 보낼 수 75MB를 넘지 않도록 합니다.<br/> Exchange Server 2013 조직에 대 한 기본 제한 이것이 <sup>4</sup> 입니다. 관리자가 조직에 대 한이 값을 변경할 수 있습니다.<br/> <sup>5</sup> Exchange Online으로 이동 될 메시지의 크기는 Exchange Online에서 계산 됩니다. Exchange Server 2013 이전 버전 Exchange의 버전 보다 작은 항목 크기를 보고할 수 있습니다.<br/> <sup>6</sup> OME 하는 방법에 대 한 새로운 기능을 갖춘 정보에 대 한 참조 [Azure 정보 보호 위쪽에 구축 된 새로운 Office 365 메시지 암호화 기능을 설정](https://support.office.com/en-us/article/Set-up-new-Office-365-Message-Encryption-capabilities-built-on-top-of-Azure-Information-Protection-7ff0c040-b25c-4378-9904-b1b50210d00e?ui=en-US&amp;rs=en-US&amp;ad=US)합니다. 
  
## <a name="receiving-and-sending-limits"></a>수신 및 전송 제한

수신 및 전송 제한은 스팸 및 대량 메일 웜 또는 바이러스를 방지하기 위해 적용됩니다. 이러한 제한은 시스템의 상태를 보호하고 사용자를 안전하게 유지하는 데 도움이 됩니다.
  
### <a name="receiving-limits"></a>수신 제한

수신 제한은 사용자, 그룹 또는 공용 폴더가 시간당 받을 수 있는 메시지 수에 적용됩니다. 이 제한은 인터넷에서 받은 메시지와 온-프레미스 서버에서 받은 메시지 둘 다에 적용됩니다. 수신 제한을 초과할 경우 해당 사서함으로 전송된 모든 전자 메일은 사서함이 최대 배달 임계값을 초과했다는 배달 못 함 보고서(NDR)를 받게 됩니다. 1시간 후에 이 제한이 새로 고쳐지고 사서함은 다시 한 번 메시지를 받을 수 있게 됩니다.
  
||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**기능** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium Office** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|메시지 수신됨  <br/> |시간당 3, 600 메시지  <br/> |시간당 3, 600 메시지  <br/> |시간당 3, 600 메시지  <br/> |시간당 3, 600 메시지  <br/> |하루에 3600개 메시지  <br/> |하루에 3600개 메시지  <br/> |
   
### <a name="sending-limits"></a>전송 제한

전송 제한은 사용자가 Exchange Online 계정에서 보낼 수 있는 메시지당 받는 사람 수, 메시지의 수 및 받는 사람 수에 적용됩니다.
  
> [!NOTE]
> 조직의 주소록에 저장된 메일 그룹은 받는 사람 한 명으로 계산합니다. 사서함의 연락처 폴더에 저장된 메일 그룹은 해당 그룹의 구성원들을 각각 계산합니다. 
  
- **받는 사람 처리 속도 제한** 원치 않는 대량 메시지의 배달을 막기 위해 Exchange Online에서는 받는 사람 제한을 통해 사용자와 응용 프로그램이 대용량 전자 메일을 보내는 것을 방지합니다. 이러한 제한은 모든 아웃바운드 메시지 및 내부 메시지에 사용자당 적용됩니다. 
    
    > [!NOTE]
    > 적법한 상업성 대량 전자 메일(예: 고객 회보)을 보내려는 Exchange Online 고객은 이러한 서비스를 제공하는 타사 제공업체를 이용해야 합니다. 
  
- **받는 사람 제한** 단일 전자 메일 메시지에 대한 받는 사람:, 참조: 및 숨은 참조: 필드에서 허용되는 최대 받는 사람 수입니다. 
    
    > [!NOTE]
    > 받는 사람 처리 속도 제한 및 받는 사람 제한을 적용하기 위해 조직의 공유 주소록에 저장된 메일 그룹이 하나의 받는 사람으로 계산됩니다. 개인 메일 그룹의 받는 사람은 각각 하나의 받는 사람으로 계산됩니다. 
  
- **메시지 처리 속도 제한** 메시지 처리 속도 제한은 사용자가 일정 기간 동안 Exchange Online 계정에서 보낼 수 있는 메시지의 수를 결정합니다. 이 제한은 보낸 사람 한 명이 시스템 리소스를 과도하게 사용하지 못하도록 방지할 수 있습니다. 사용자가 SMTP 클라이언트 전송을 통해 제한을 초과하는 속도로 메시지를 전송하면 메시지가 거부되므로 해당 클라이언트가 다시 시도해야 합니다. 
    
#### <a name="sending-limits-across-office-365-options"></a>Office 365 옵션별 전송 제한

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**기능** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|받는 사람 처리 속도 제한  <br/> |하루에 받는 사람 10,000명  <br/> |하루에 받는 사람 10,000명  <br/> |하루에 받는 사람 10,000명  <br/> |하루에 받는 사람 10,000명  <br/> |하루에 받는 사람 10,000명  <br/> |하루에 받는 사람 10,000명  <br/> |
|받는 사람 제한  <br/> |받는 사람 500명  <br/> |받는 사람 500명  <br/> |받는 사람 500명  <br/> |받는 사람 500명  <br/> |받는 사람 500명  <br/> |받는 사람 500명  <br/> |
|받는 사람 프록시 주소 제한  <br/> |400  <br/> |400  <br/> |400  <br/> |400  <br/> |400  <br/> |400  <br/> |
|메시지 속도 제한(SMTP 클라이언트 전송만 해당)  <br/> |분당 30개 메시지  <br/> |분당 30개 메시지  <br/> |분당 30개 메시지  <br/> |분당 30개 메시지  <br/> |분당 30개 메시지  <br/> |분당 30개 메시지  <br/> |
   
#### <a name="sending-limits-across-standalone-options"></a>독립 실행형 옵션별 전송 제한

||||||
|:-----|:-----|:-----|:-----|:-----|
|**기능** <br/> |**Exchange Server 2013** <br/> |**Exchange Online 계획 1** <br/> |**Exchange Online 계획 2** <br/> |**Exchange Online Kiosk** <br/> |
|받는 사람 처리 속도 제한  <br/> |제한 없음<sup>1</sup> <br/> |하루에 받는 사람 10,000명  <br/> |하루에 받는 사람 10,000명  <br/> |하루에 받는 사람 10,000명  <br/> |
|받는 사람 제한  <br/> |500 받는 사람에 게<sup>1</sup> <br/> |받는 사람 500명  <br/> |받는 사람 500명  <br/> |받는 사람 500명  <br/> |
|받는 사람 프록시 주소 제한  <br/> |400  <br/> |400  <br/> |400  <br/> |400  <br/> |
   
> [!NOTE]
> <sup>1</sup>Exchange Server 2013 조직의 기본 제한입니다. 관리자는 자신의 조직에 대한 이 값을 변경할 수 있습니다. 
  
## <a name="reporting-and-message-trace-limits"></a>보고 및 메시지 추적 제한
<a name="bkmk_Reporting_Message_Trace_Limits"> </a>

보고 및 메시지 추적 제한에 대한 내용은 [Exchange Online Protection의 보고 및 메시지 추적](http://go.microsoft.com/fwlink/p/?LinkId=394248)의 "보고 및 메시지 추적 데이터 사용 가능 여부 및 대기 시간" 섹션을 참조하세요.
  
## <a name="retention-limits"></a>보존 제한
<a name="RetentionLimits"> </a>

다음 제한은 받은 편지함의 특정 폴더에 있는 항목에 액세스할 수 있는 기간을 제어합니다.
  
- **지운 편지함 폴더 보존 기간** 항목이 자동으로 제거되기 전에 지운 편지함 폴더에 남아 있을 수 있는 최대 기간(일)입니다. 
    
- **지운 편지함 폴더에서 제거한 항목의 보존 기간** 지운 편지함 폴더에서 제거된 항목이 영구적으로 삭제되기 전에 보존되는 최대 기간(일)입니다. 
    
- **정크 메일 폴더 보존 기간** 항목이 자동으로 제거되기 전에 정크 메일 폴더에 남아 있을 수 있는 최대 기간(일)입니다. 
    
### <a name="retention-limits-across-office-365-options"></a>Office 365 옵션별 보존 제한

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**기능** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|지운 편지함 폴더 보존 기간  <br/> |제한 없음<sup>1</sup> <br/> |제한 없음<sup>1</sup> <br/> |제한 없음<sup>1</sup> <br/> |제한 없음<sup>1</sup> <br/> |제한 없음<sup>1</sup> <br/> |제한 없음<sup>1</sup> <br/> |
|지운 편지함 폴더에서 제거한 항목의 보존 기간  <br/> |14 일<sup>1</sup> <br/> |14 일<sup>1</sup> <br/> |14 일<sup>1</sup> <br/> |14 일<sup>1</sup> <br/> |14 일<sup>1</sup> <br/> |14 일<sup>1</sup> <br/> |
|정크 메일 폴더 보존 기간  <br/> |30일  <br/> |30일  <br/> |30일  <br/> |30일  <br/> |30일  <br/> |30일  <br/> |
   
> [!NOTE]
> <sup>1</sup> 기본 제한입니다. 관리자는 자신의 조직에 대한 이 값을 변경할 수 있습니다. 
  
### <a name="retention-limits-across-standalone-options"></a>독립 실행형 옵션별 보존 제한

||||||
|:-----|:-----|:-----|:-----|:-----|
|**기능** <br/> |**Exchange Server 2013** <br/> |**Exchange Online 계획 1** <br/> |**Exchange Online 계획 2** <br/> |**Exchange Online Kiosk** <br/> |
|지운 편지함 폴더 보존 기간  <br/> |제한 없음<sup>1</sup> <br/> |제한 없음<sup>1</sup> <br/> |제한 없음<sup>1</sup> <br/> |제한 없음<sup>1</sup> <br/> |
|지운 편지함 폴더에서 제거한 항목의 보존 기간  <br/> |14 일<sup>1</sup> <br/> |14 일<sup>2</sup> <br/> |14 일<sup>2</sup> <br/> |14 일<sup>2</sup> <br/> |
|정크 메일 폴더 보존 기간  <br/> |2 년<sup>1</sup> <br/> |30일  <br/> |30일  <br/> |30일  <br/> |
   
> [!NOTE]
> <sup>1</sup> 기본 제한입니다. 관리자는 자신의 조직에 대한 이 값을 변경할 수 있습니다.<br/> <sup>2</sup> Exchange Online 조직에 대 한 기본 값입니다. 관리자가 조직에서 사서함에 대 한 일의 최대이 값을 변경할 수 있습니다. 
  
## <a name="distribution-group-limits"></a>메일 그룹 제한

이러한 제한은 조직의 공유 주소록에 포함된 메일 그룹에 적용됩니다.
  
- **메일 그룹 구성원의 최대 수** 메일 그룹 확장 후 총 받는 사람 수가 결정 됩니다. 
    
- **큰 메일 그룹에 메시지 보내기 제한** 이 제한에 지정된 수의 구성원을 포함하는 메일 그룹에 대해 배달 관리 또는 메시지 승인 옵션을 구성해야 합니다. 배달 관리는 메일 그룹에 메시지를 보낼 수 있는 보낸 사람 목록을 지정하고, 메시지 승인은 메일 그룹에 보낸 모든 메시지를 승인해야 하는 한 명 이상의 중재자를 지정합니다. 
    
- **큰 메일 그룹에 대한 최대 메시지 크기** 5,000명 이상의 받는 사람에게 메시지를 보낼 경우 메시지 크기가 이 제한을 초과할 수 없습니다. 메시지 크기가 이 제한을 초과하면 메시지가 배달되지 않고 보낸 사람에게 NDR(배달 못 함 보고서)이 전송됩니다. 메일 그룹 확장 후 총 받는 사람 수가 결정됩니다. 
    
### <a name="distribution-group-limits-across-office-365-options"></a>Office 365 옵션별 메일 그룹 제한

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**기능** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|최대 메일 그룹 구성원 수<sup>1</sup> <br/> |구성원 100,000명  <br/> |구성원 100,000명  <br/> |구성원 100,000명  <br/> |구성원 100,000명  <br/> |구성원 100,000명  <br/> |구성원 100,000명  <br/> |
|큰 메일 그룹에 메시지 보내기 제한  <br/> |구성원 5,000명 이상  <br/> |구성원 5,000명 이상  <br/> |구성원 5,000명 이상  <br/> |구성원 5,000명 이상  <br/> |구성원 5,000명 이상  <br/> |구성원 5,000명 이상  <br/> |
|5, 000 개를 100, 000 개 구성원이 있는 메일 그룹에 대 한 최대 메시지 크기  <br/> |25MB  <br/> |25MB  <br/> |25MB  <br/> |25MB  <br/> |25MB  <br/> |25MB  <br/> |
|100, 000 명 이상의 구성원이 있는 메일 그룹에 대 한 최대 메시지 크기  <br/> |5MB  <br/> |5MB  <br/> |5MB  <br/> |5MB  <br/> |5MB  <br/> |5MB  <br/> |
|최대 메일 그룹 소유자 수  <br/> |10   <br/> |10   <br/> |10   <br/> |10   <br/> |10   <br/> |10   <br/> |
|사용자가 만들 수 있는 최대 그룹 수  <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> Azure Active Directory 디렉터리 동기화를 사용 하는 경우 온-프레미스 Active Directory에서 Azure Active Directory에는 동기화 할 수 있는 메일 그룹 구성원의 최대 수는 15, 000입니다. Azure AD 연결을 사용 하는 경우 해당 번호가 50, 000입니다.<br/> <sup>2</sup> 이 제한은 관리자에게도 적용됩니다. 
  
### <a name="distribution-group-limits-across-standalone-options"></a>독립 실행형 옵션별 메일 그룹 제한

||||||
|:-----|:-----|:-----|:-----|:-----|
|**기능** <br/> |**Exchange Server 2013** <br/> |**Exchange Online 계획 1** <br/> |**Exchange Online 계획 2** <br/> |**Exchange Online Kiosk** <br/> |
|최대 메일 그룹 구성원 수  <br/> |구성원 100,000명<sup>1</sup> <br/> |구성원 100,000명  <br/> |구성원 100,000명  <br/> |구성원 100,000명  <br/> |
|큰 메일 그룹에 메시지 보내기 제한  <br/> |구성원 5,000명 이상<sup>1</sup> <br/> |구성원 5,000명 이상  <br/> |구성원 5,000명 이상  <br/> |구성원 5,000명 이상  <br/> |
|최대 메일 그룹 소유자 수  <br/> |10   <br/> |10   <br/> |10   <br/> |10   <br/> |
|사용자가 만들 수 있는 최대 그룹 수  <br/> |250<sup>2</sup> <br/> |250<sup>2</sup> <br/> |250<sup>2</sup> <br/> |250<sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup>Exchange Server 2013 조직의 기본 제한입니다. 관리자는 자신의 조직에 대한 이 값을 변경할 수 있습니다.<br/> <sup>2</sup> 이 제한은 관리자에게도 적용됩니다. 
  
## <a name="journal-transport-and-inbox-rule-limits"></a>저널, 전송 및 받은 편지함 규칙 제한

다음 목록에는 저널 규칙, 전송 규칙에 적용되는 제한(조직 차원 규칙이라고도 함)과 받은 편지함 규칙에 적용되는 제한이 나와 있습니다. 받은 편지함 규칙은 개별 사용자에 의해 설정되어 개별 사용자 사서함에서 보내고 받는 메시지에 적용됩니다.
  
- **최대 저널 규칙 수** 조직에 존재할 수 있는 최대 저널 규칙 수입니다. 
    
- **최대 전송 규칙 수** 조직에 존재할 수 있는 최대 규칙 수입니다. 
    
- **개별 전송 규칙의 최대 크기** 단일 전송 규칙에 사용할 수 있는 문자의 최대 수입니다. 문자에 조건, 예외 및 작업에 사용 됩니다. 
    
- **모든 전송 규칙에 사용되는 모든 정규식에 대한 문자 제한** 조직에서 모든 전송 규칙 조건 및 예외의 모든 정규식에 사용되는 총 문자 수입니다. 길고 복잡한 정규식을 사용하는 규칙이 몇 가지 있거나 단순한 정규식을 사용하는 규칙이 많이 있을 수 있습니다. 
    
- **첨부 파일 내용 검사 제한** 이 전송 규칙 조건을 사용하여 메시지 첨부 파일의 내용을 검사할 수 있지만 첨부 파일에서 추출된 텍스트의 처음 1MB만 검사됩니다. 이 1MB 제한은 첨부 파일의 파일 크기가 아닌 첨부 파일에서 추출된 텍스트를 나타냅니다. 예를 들어 2MB 파일에는 1MB 미만의 텍스트가 포함되어 있을 수 있으므로 모든 텍스트가 검사됩니다. 
    
- **모든 전송 규칙에 의해 메시지에 추가되는 받는 사람의 최대 수** 여러 전송 규칙에 의해 메시지가 처리될 때 제한된 수의 받는 사람만 메시지에 추가될 수 있습니다. 제한에 도달하면 나머지 받는 사람은 메시지가 추가되지 않습니다. 메일 그룹도 전송 규칙에 의해 메시지에 추가될 수 없습니다. 
    
- **전달받는 사람 제한** 리디렉션 작업을 통해 받은 편지함 또는 전송 규칙에 대해 구성할 수 있는 최대 받는 사람 수입니다. 이 받는 사람 수보다 많은 사람에게 메시지를 리디렉션하도록 구성하는 규칙은 적용되지 않으며, 규칙 조건을 충족하는 메시지는 규칙에 나와 있는 받는 사람에게 리디렉션되지 않습니다. 
    
- **메시지 리디렉션 횟수** 받은 편지함 규칙을 기준으로 메시지를 자동으로 리디렉션, 전달 또는 회신할 횟수입니다. 보낸 사람을 기준으로 메시지를 사용자 B에게 리디렉션하는 받은 편지함 규칙이 사용자 A에게 적용되는 경우를 예로 들어 보겠습니다. 사용자 B의 경우에는 제목 줄의 키워드를 기준으로 메시지를 사용자 C에게 전달하는 받은 편지함 규칙이 적용됩니다. 이 두 조건을 모두 충족하는 메시지는 사용자 B에게만 발송됩니다. 리디렉션은 한 번만 허용되므로 사용자 C에게는 메시지가 전달되지 않습니다. 이 경우 사용자 C에게 메시지가 배달되지 않았음을 나타내는 NDR(배달 못 함 보고서)을 사용자 B에게 보내지 않고 메시지가 삭제됩니다. 
    
### <a name="journal-transport-and-inbox-rule-limits-across-office-365-options"></a>Office 365 옵션별 저널, 전송 및 받은 편지함 규칙 제한

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**기능** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|최대 저널 규칙 수  <br/> |10개 규칙  <br/> |10개 규칙  <br/> |10개 규칙  <br/> |10개 규칙  <br/> |10개 규칙  <br/> |10개 규칙  <br/> |
|최대 전송 규칙 수  <br/> |300개 규칙  <br/> |300개 규칙  <br/> |300개 규칙  <br/> |300개 규칙  <br/> |300개 규칙  <br/> |300개 규칙  <br/> |
|개별 전송 규칙의 최대 크기  <br/> |8 KB  <br/> |8KB  <br/> |8KB  <br/> |8KB  <br/> |8KB  <br/> |8KB  <br/> |
|모든 전송 규칙에서 사용되는 모든 정규식의 문자 제한  <br/> |20 KB  <br/> |20KB  <br/> |20KB  <br/> |20KB  <br/> |20KB  <br/> |20KB  <br/> |
|첨부 파일 내용 검사 제한  <br/> |1MB  <br/> |1MB  <br/> |1MB  <br/> |1MB  <br/> |1MB  <br/> |1MB  <br/> |
|모든 전송 규칙에 의해 메시지에 추가되는 최대 받는 사람 수  <br/> |받는 사람 100명  <br/> |받는 사람 100명  <br/> |받는 사람 100명  <br/> |받는 사람 100명  <br/> |받는 사람 100명  <br/> |받는 사람 100명  <br/> |
|전달받는 사람 제한  <br/> |받는 사람 10명  <br/> |받는 사람 10명  <br/> |받는 사람 10명  <br/> |받는 사람 10명  <br/> |받는 사람 10명  <br/> |받는 사람 10명  <br/> |
|메시지 리디렉션 횟수  <br/> |리디렉션 1회  <br/> |리디렉션 1회  <br/> |리디렉션 1회  <br/> |리디렉션 1회  <br/> |리디렉션 1회  <br/> |리디렉션 1회  <br/> |
   
### <a name="journal-transport-and-inbox-rule-limits-across-standalone-options"></a>독립 실행형 옵션별 저널, 전송 및 받은 편지함 규칙 제한

||||||
|:-----|:-----|:-----|:-----|:-----|
|**기능** <br/> |**Exchange Server 2013** <br/> |**Exchange Online 계획 1** <br/> |**Exchange Online 계획 2** <br/> |**Exchange Online Kiosk** <br/> |
|최대 저널 규칙 수  <br/> |제한 없음  <br/> |10개 규칙  <br/> |10개 규칙  <br/> |10개 규칙  <br/> |
|최대 전송 규칙 수  <br/> |제한 없음  <br/> |300개 규칙  <br/> |300개 규칙  <br/> |300개 규칙  <br/> |
|개별 전송 규칙의 최대 크기  <br/> |40 KB  <br/> |8KB  <br/> |8KB  <br/> |8KB  <br/> |
|모든 전송 규칙에서 사용되는 모든 정규식의 문자 제한  <br/> |제한 없음  <br/> |20KB  <br/> |20KB  <br/> |20KB  <br/> |
|모든 전송 규칙에 의해 메시지에 추가되는 최대 받는 사람 수  <br/> |제한 없음  <br/> |받는 사람 100명  <br/> |받는 사람 100명  <br/> |받는 사람 100명  <br/> |
|전달받는 사람 제한  <br/> |제한 없음  <br/> |받는 사람 10명  <br/> |받는 사람 10명  <br/> |받는 사람 10명  <br/> |
|메시지 리디렉션 횟수  <br/> |리디렉션 3회  <br/> |리디렉션 1회  <br/> |리디렉션 1회  <br/> |리디렉션 1회  <br/> |
  
## <a name="moderation-limits"></a>중재 제한
<a name="ModerationLimits"> </a>

다음 제한은 메일 그룹과 전송 규칙에 적용된 메시지 승인에 사용되는 중재 설정을 제어합니다.
  
- **중재 사서함의 최대 크기** 중재 사서함이 이 제한을 초과하면 중재를 요구하는 메시지가 NDR(배달 못 함 보고서)과 함께 보낸 사람에게 반송됩니다. 
    
- **최대 중재자 수** 단일 전송 규칙을 사용하여 메시지에 추가할 수 있거나 중재된 단일 메일 그룹에 할당할 수 있는 최대 중재자 수입니다. 메일 그룹은 중재자로 지정할 수 없습니다. 
    
- **중재 대기 중인 메시지의 만료** 기본적으로 중재 대기 중인 메시지는 2일 후 만료됩니다. 그러니 만료된 중재된 메시지의 처리가 7일마다 실행되므로 2~9일 사이에 언제든지 중재된 메시지가 만료될 수 있습니다. 
    
- **만료된 중재 알림 메시지의 최대 처리 속도** 이 제한은 1시간 동안 만료된 중재된 메시지에 대한 최대 알림 메시지 수를 설정합니다. 데이터 센터의 각 사서함 데이터베이스에 이 제한이 적용됩니다. 
    
    사용량이 많은 기간에는 일부 보낸 사람이 만료된 중재된 메시지에 대한 알림 메시지를 받지 못할 수 있습니다. 그러나 배달 보고서에서 이러한 알림을 검색할 수 있습니다.
    
### <a name="moderation-limits-across-office-365-options"></a>Office 365 옵션별 중재 제한

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**기능** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|중재 사서함의 최대 크기  <br/> |10GB  <br/> |10GB  <br/> |10GB  <br/> |10GB  <br/> |10GB  <br/> |10GB  <br/> |
|최대 중재자 수  <br/> |중재자 10명  <br/> |중재자 10명  <br/> |중재자 10명  <br/> |중재자 10명  <br/> |중재자 10명  <br/> |중재자 10명  <br/> |
|중재 대기 중인 메시지의 만료  <br/> |2일  <br/> |2일  <br/> |2일  <br/> |2일  <br/> |2일  <br/> |2일  <br/> |
|만료된 중재 알림 메시지의 최대 처리 속도  <br/> |시간당 만료 알림 300개  <br/> |시간당 만료 알림 300개  <br/> |시간당 만료 알림 300개  <br/> |시간당 만료 알림 300개  <br/> |시간당 만료 알림 300개  <br/> |시간당 만료 알림 300개  <br/> |
   
### <a name="moderation-limits-across-standalone-options"></a>독립 실행형 옵션별 중재 제한

||||||
|:-----|:-----|:-----|:-----|:-----|
|**기능** <br/> |**Exchange Server 2013** <br/> |**Exchange Online 계획 1** <br/> |**Exchange Online 계획 2** <br/> |**Exchange Online Kiosk** <br/> |
|중재 사서함의 최대 크기  <br/> |제한 없음<sup>1</sup> <br/> |10GB  <br/> |10GB  <br/> |10GB  <br/> |
|최대 중재자 수  <br/> |제한 없음  <br/> |중재자 10명  <br/> |중재자 10명  <br/> |중재자 10명  <br/> |
|중재 대기 중인 메시지의 만료  <br/> |5 일<sup>1</sup> <br/> |2일  <br/> |2일  <br/> |2일  <br/> |
|만료된 중재 알림 메시지의 최대 처리 속도  <br/> |시간당 만료 알림 300개  <br/> |시간당 만료 알림 300개  <br/> |시간당 만료 알림 300개  <br/> |시간당 만료 알림 300개  <br/> |
   
> [!NOTE]
> <sup>1</sup>Exchange Server 2013 조직의 기본 제한입니다. 관리자는 자신의 조직에 대한 이 값을 변경할 수 있습니다. 
  
## <a name="exchange-activesync-limits"></a>Exchange ActiveSync 제한
<a name="BKMK_ExchangeActiveSync_Limits"> </a>

모바일 장치와 Exchange 간에 사서함 데이터를 동기화하는 클라이언트 프로토콜인 Microsoft Exchange ActiveSync에 다음 제한이 적용됩니다. 
  
- **Exchange ActiveSync 장치 제한** 사서함당 최대 Exchange ActiveSync 장치 수. 
    
- **Exchange ActiveSync 장치 삭제 제한** Exchange 관리자가 1달에 삭제할 수 있는 최대 Exchange ActiveSync 장치 수. 
    
- **Exchange ActiveSync 첨부 파일 제한** Exchange ActiveSync 장치에서 송수신될 수 있는 메시지 첨부 파일의 최대 크기. 
    
### <a name="exchange-activesync-limits-across-office-365-options"></a>Office 365 옵션에서 Exchange ActiveSync 제한

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**기능** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Exchange ActiveSync 장치 제한  <br/> |100  <br/> |100  <br/> |100  <br/> |100  <br/> |100  <br/> |100  <br/> |
|Exchange ActiveSync 장치 삭제 제한  <br/> |20 개  <br/> |20 개  <br/> |20 개  <br/> |20 개  <br/> |20 개  <br/> |20 개  <br/> |
|Exchange ActiveSync 첨부 파일 제한  <br/> |25MB  <br/> |25MB  <br/> |25MB  <br/> |25MB  <br/> |25MB  <br/> |25MB  <br/> |
   
### <a name="exchange-activesync-limits-across-standalone-options"></a>독립 실행형 옵션에서 Exchange ActiveSync 제한

||||||
|:-----|:-----|:-----|:-----|:-----|
|**기능** <br/> |**Exchange Server 2013** <br/> |**Exchange Online 계획 1** <br/> |**Exchange Online 계획 2** <br/> |**Exchange Online Kiosk** <br/> |
|Exchange ActiveSync 장치 제한  <br/> |100  <br/> |100  <br/> |100  <br/> |100  <br/> |
|Exchange ActiveSync 장치 삭제 제한  <br/> |20 개  <br/> |20 개  <br/> |20 개  <br/> |20 개  <br/> |
|Exchange ActiveSync 첨부 파일 제한  <br/> |25MB  <br/> |25MB  <br/> |25MB  <br/> |25MB  <br/> |
