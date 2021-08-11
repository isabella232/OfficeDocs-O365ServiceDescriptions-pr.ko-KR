---
title: Exchange Online 제한
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-limits
ms.service: o365-administration
localization_priority: Priority
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 70b38a05-6cfa-4ced-a137-116019262fed
description: 주소록 제한, 사서함 저장 용량 제한, 보고 및 메시지 추적 제한을 비롯하여 다양한 서비스 영역에 대한 Exchange Online 제한을 확인할 수 있습니다.
ms.openlocfilehash: c966b23f0a2ef50bbec57ed1974e9ffb6f7926888481b38dc8bdd3daa227592c
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/06/2021
ms.locfileid: "54664041"
---
# <a name="exchange-online-limits"></a>Exchange Online 제한

주소록 제한, 사서함 저장 용량 제한, 보고 및 메시지 추적 제한을 비롯하여 다양한 서비스 영역에 대한 Exchange Online 제한을 확인할 수 있습니다.

> [!NOTE]
> 작업에 대한 도움이 필요한 경우나 문제를 해결하고 있는 경우 다음 문서가 도움이 될 수 있습니다.
> - [전자 메일](https://support.office.com/article/94275804-7147-4332-9ccd-5d421760a9ed)(전자 메일 작성 및 보내기 지원)
>- [비즈니스용 Microsoft 365의 전자 메일 - 관리자 도움말](/microsoft-365/admin/email/)
>- [Microsoft 지원 및 복구 도우미를 통해 Outlook 및 Microsoft 365 문제 해결](https://diagnostics.office.com/)
>- [전자 메일 전달 못 함 보고서](/Exchange/mail-flow-best-practices/non-delivery-reports-in-exchange-online/non-delivery-reports-in-exchange-online)
>- [Exchange Online 도움말](/exchange/exchange-online)

Microsoft Exchange Online 제한은 다음 범주 중 하나에 속합니다.

- [주소록 제한](#address-book-limits)

- [사서함 저장소 제한](#mailbox-storage-limits)

- [Capacity alerts](#capacity-alerts)

- [Mailbox folder limits](#mailbox-folder-limits)

- [Message limits](#message-limits)

- [수신 및 전송 제한](#receiving-and-sending-limits)

- [Reporting and message trace limits](#reporting-and-message-trace-limits)

- [Retention limits](#retention-limits)

- [메일 그룹 제한](#distribution-group-limits)

- [저널, 전송 및 받은 편지함 규칙 제한](#journal-transport-and-inbox-rule-limits)

- [중재 제한](#moderation-limits)

- [Exchange ActiveSync limits](#exchange-activesync-limits)

> [!IMPORTANT]
> - Microsoft 365 조직에 적용된 제한은 조직이 서비스에 등록된 기간에 따라 다를 수 있습니다. 
> - 제한이 Microsoft 데이터 센터에서 변경된 경우 기존의 모든 고객에게 변경 사항을 적용하는 데 시간이 걸릴 수 있습니다.
> - 이러한 제한은 대부분 수정할 수 없지만 사용자와 함께 어떠한 제한이 있는지 알고 있어야 합니다.
> - 이들 제한은 내부 및 외부의 받는 사람에게 모두 적용됩니다.
> - 기본적으로 EOP(ExchangeOnlineProtection)는 Exchange Online 사서함을 보호합니다. ExchangeOnline의 EOP 기능에 적용되는 제한 사항은 [Exchange Online Protection 제한](../exchange-online-protection-service-description/exchange-online-protection-limits.md)을 참조하세요.
> - Office 365 그룹 제한에 대한 자세한 내용은 [Microsoft 365 그룹에 대해 알아보기](https://go.microsoft.com/fwlink/?linkid=846714)의 "내 그룹을 어떻게 관리하나요?"를 참조하세요.

## <a name="address-book-limits"></a>주소록 제한

- **주소록 목록 제한**: Exchange Online 또는 Exchange Server 2013 조직에서 만들 수 있는 주소 목록의 최대 수입니다. 이 수에는 Exchange Online의 기본 주소 목록(예: 모든 연락처 및 모든 그룹)이 포함됩니다.

    > [!NOTE]
    > 최대 20개의 주소 목록을 단일 오프라인 주소록(OAB)으로 할당할 수 있습니다.

- **오프라인 주소록 제한**: Exchange Online 또는 Exchange Server 2013 조직에서 만들 수 있는 OAB(오프라인 주소록)의 최대 수입니다.

- **주소록 정책 제한**: Exchange Online 또는 Exchange Server 2013 조직에서 만들 수 있는 ABP(주소록 정책)의 최대 수입니다.

- **전체 주소 목록**: Exchange Online 또는 Exchange Server 2013 조직에서 만들 수 있는 GAL(전체 주소 목록)의 최대 수입니다.

### <a name="address-book-limits"></a>주소록 제한

| 기능 | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|주소 목록 제한|1000|1000|1000|1000|1000|1000|
|OAB(오프라인 주소록) 제한|250|250|250|250|250|250|
|ABP(주소록 정책) 제한|250|250|250|250|250|250|
|전체 주소 목록 제한|250|250|250|250|250|250|

### <a name="address-book-limits-across-standalone-plans"></a>독립 실행형 계획의 주소록 제한

| 기능 | Exchange Server 2013 | Exchange Online 요금제 1 | Exchange Online 계획 2 | Exchange Online Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|주소 목록 제한|1000|1000|1000|1000|
|OAB(오프라인 주소록) 제한|250|250|250|250|
|ABP(주소록 정책) 제한|250|250|250|250|
|전체 주소 목록 제한|250|250|250|250|

## <a name="mailbox-storage-limits"></a>사서함 저장소 제한

사용할 수 있는 사서함 저장소의 크기는 사서함 유형 및 사용자의 구독 라이선스에 따라 결정됩니다. 관리자는 각 사용자별 사서함 크기 또는 모든 사용자의 사서함 크기를 줄일 수 있습니다.

> [!NOTE]
> 보관 목적으로 Exchange Online 사서함에 메시지를 복사하는 저널링, 전송 규칙 또는 자동 전달 규칙을 사용하는 것은 허용되지 않습니다. 사용자의 보관 사서함은 해당 사용자만을 위한 것입니다. Microsoft는 사용자의 보관 사서함이 다른 사용자의 보관 데이터를 저장하는 데 사용되는 경우 또는 부적절한 다른 경우에 무제한 보관을 거부할 권한을 보유합니다.

### <a name="storage-limits"></a>저장 용량 제한

| 기능 | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|사용자 사서함|50GB|50GB|50GB|100GB|100GB|2GB|
|보관 사서함<sup>7,8</sup>|50GB|50GB|50 GB|Unlimited<sup>1</sup>|Unlimited<sup>1</sup>|사용할 수 없음<sup>4</sup>|
|공유 사서함<sup>10</sup>|50GB<sup>2</sup>|50GB<sup>2</sup>|50GB<sup>2</sup>|50/100 GB<sup>2,9</sup>|50/100 GB<sup>2,9</sup>|50GB<sup>2</sup>|
|리소스 사서함|50GB<sup>3</sup>|50GB<sup>3</sup>|50GB<sup>3</sup>|50GB<sup>3,9</sup>|50GB<sup>3,9</sup>|50GB<sup>3</sup>|
|사이트 사서함<sup>5</sup>|50 GB|50GB|50GB|50GB|50 GB|사용할 수 없음|
|공용 폴더 사서함|100GB<sup>6</sup>|100GB<sup>6</sup>|100GB<sup>6</sup>|100GB<sup>6</sup>|100GB<sup>6</sup>|100GB<sup>6</sup>|
|그룹 사서함|50GB|50GB|50GB|50GB|50GB|50GB|

> [!NOTE]
> <sup>1</sup> 각 사용자는 처음에 보관 사서함에 100GB의 저장소를 받습니다. 자동 확장 보관이 켜져 있는 경우 100GB의 저장소 용량에 도달하면 이 추가 저장소가 자동으로 추가됩니다. 자세한 내용은 [Office 365 무제한 보관의 개요](/microsoft-365/compliance/unlimited-archiving)를 참조하세요.<br/> <sup>2</sup> 공유 사서함에 액세스하려면 사용자에게 Exchange Online 라이선스가 있어야 하지만 공유 사서함에는 별도의 라이선스가 필요하지 않습니다. 라이선스가 없는 공유 사서함은 50GB로 제한됩니다. 크기 제한을 100GB로 늘리려면 공유 사서함에 Exchange Online 계획 2 라이선스가 할당되어야 합니다. Exchange Online Archiving 추가 기능 라이선스가 있는 Exchange Online 계획 1 라이선스가 할당된 경우 보관 저장소 용량을 무제한으로 자동 확장할 수 있습니다. 마찬가지로, 공유 사서함을 소송 보존에 추가하려면 공유 사서함에 Exchange Online 플랜 2 라이선스 또는 Exchange Online Archiving 추가 기능 라이선스가 있는 Exchange Online 플랜 1 라이선스가 있어야 합니다. Office 365용 Microsoft Defender, Advanced eDiscovery 또는 자동 보존 정책과 같은 고급 기능을 적용하려면 공유 사서함에 해당 기능에 대한 라이선스가 있어야 합니다. <br/> <sup>3</sup> 리소스 사서함에는 라이선스가 필요하지 않습니다. 그러나 라이센스가 없으면 리소스 사서함이 50GB로 제한됩니다. 사서함 크기를 늘리려면 E3 또는 E5 라이선스가 할당되어야 합니다. 그러면 100GB로 사서함이 늘어납니다. <br/> <sup>4</sup> Exchange Online Kiosk에는 보관 사서함이 포함되지 않습니다. 하지만 Exchange Online Archiving을 통해 추가 기능으로 구입할 수 있습니다. 자세한 내용은 [Exchange Online Archiving 서비스 설명](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md)을 참조하십시오. <br/> <sup>5</sup> 2017년에 사이트 사서함이 Exchange Online 및 SharePoint Online에서 제거되었습니다. <br/> <sup>6</sup> 공용 폴더 사서함은 1,000개로 제한되며 모든 공용 폴더 사서함의 최대 총 크기는 100TB입니다. 계층 구조 서비스 사서함은 100개의 공용 폴더 사서함으로 제한됩니다.<br/> <sup>7</sup> 보관 사서함은 라이선스가 적용된 단일 사용자나 엔터티의 메일을 보관하는 경우(예: 공유 사서함)에만 사용할 수 있습니다. 여러 사용자나 엔터티의 메일을 저장하는 목적으로 보관 사서함을 사용할 수는 없습니다. 예를 들어 IT 관리자는 공유 사서함을 만들 수 없고, 사용자가 명백히 보관을 목적으로 참조, 숨은 참조 필드 또는 전송 규칙을 통해 복사하도록 할 수 없습니다. 여러 사람이 사용하는 공유 사서함은 실제로 해당 개별 사용자의 전자 메일을 저장하지 않습니다. 여러 사용자에게 액세스 권한이 있으며 이러한 사용자는 공유 사서함으로 전자 메일을 보냅니다. 따라서 공유 사서함에 저장된 전자 메일은 와 공유 사서함 *으로서* 이 사서함에서 주고받은 메일 뿐입니다. <br/> <sup>8</sup> Exchange Online에서 보존 정책을 만든 경우 사용자의 기본 사서함이 10MB보다 큰 경우에만 메시지가 사용자 보관 사서함으로 자동 이동됩니다. 10MB보다 작은 사서함에 대해서는 보존 정책이 자동으로 실행되지 않습니다. <br/> <sup>9</sup> 공유 및 리소스 사서함에는 라이선스가 필요하지 않습니다. 그러나 라이센스가 없으면 해당 사서함이 50GB로 제한됩니다. 사서함 크기를 늘리려면 E3 또는 E5 라이선스가 할당되어야 합니다. 그러면 100GB로 사서함이 늘어납니다. <br/> <sup>10</sup> 기본적으로 공유 사서함에는 시스템에서 생성된 (알 수 없는) 암호가 포함된 연결된 활성 사용자 계정이 있습니다. 연결된 공유 사서함 계정의 로그인을 차단하려면 [공유 사서함 계정의 로그인 차단](/office365/admin/email/create-a-shared-mailbox#block-sign-in-for-the-shared-mailbox-account)을 참조하세요.

### <a name="storage-limits-across-standalone-plans"></a>독립 실행형 계획별 저장소 제한

| 기능 | Exchange Server 2013 | Exchange Online 요금제 1 | Exchange Online 계획 2 | Exchange Online Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|사용자 사서함|2GB<sup>1</sup>|50 GB|100GB|2GB|
|보관 사서함<sup>8, 9</sup>|100GB<sup>1</sup>|50GB|Unlimited<sup>2</sup>|사용할 수 없음<sup>5</sup>|
|공유 사서함<sup>11</sup>|2GB<sup>1</sup>|50GB<sup>3</sup>|50GB<sup>3,10</sup>|50GB<sup>3</sup>|
|리소스 사서함|2GB<sup>1</sup>|50GB<sup>4</sup>|50GB<sup>4,10</sup>|50GB<sup>4</sup>|
|공용 폴더 사서함|2GB<sup>6</sup>|50GB<sup>7</sup>|100GB<sup>7</sup>|사용할 수 없음|
|그룹 사서함|50GB|50GB|50GB|50GB|

> [!NOTE]
> <sup>1</sup> ExchangeServer2013 조직의 기본 사서함 크기입니다. 관리자는 자신의 조직에 대한 이 값을 변경할 수 있습니다. 온-프레미스 사서함의 경우에는 최대 저장소 제한이 없습니다. <br/> <sup>2</sup> 각 사용자는 처음에 보관 사서함에서 100GB의 저장 용량을 받습니다. 자동 확장 보관 기능이 켜져 있으면 100GB 저장소 용량에 도달할 경우 추가 저장소가 자동으로 추가됩니다. 자세한 내용은 [Office 365의 무제한 보관 개요](/microsoft-365/compliance/unlimited-archiving)를 참조하세요. 자동 확장 보관 사용 가능 여부에 대한 자세한 내용은 [Microsoft 365 로드맵](https://go.microsoft.com/fwlink/?LinkId=509914)을 참조하세요.<br/> <sup>3</sup> 공유 사서함에 액세스하려면 사용자에게 Exchange Online 라이선스가 있어야 하지만 공유 사서함에는 별도의 라이선스가 필요하지 않습니다. 라이선스가 없는 공유 사서함은 50GB로 제한됩니다. 크기 제한을 100GB로 늘리려면 공유 사서함에 Exchange Online 계획 2 라이선스가 할당되어야 합니다. Exchange Online Archiving 추가 기능 라이선스가 있는 Exchange Online 계획 1 라이선스는 보관 사서함의 크기를 늘 수 있습니다. 이렇게 하면 보관 저장소 용량을 무제한으로 자동 확장할 수 있습니다. 마찬가지로, 공유 사서함을 소송 보존에 추가하려면 공유 사서함에 Exchange Online 플랜 2 라이선스 또는 Exchange Online Archiving 추가 기능 라이선스가 있는 Exchange Online 플랜 1 라이선스가 있어야 합니다. Office 365용 Microsoft Defender, Advanced eDiscovery 또는 자동 보존 정책과 같은 고급 기능을 적용하려면 공유 사서함에 해당 기능에 대한 라이선스가 있어야 합니다. <br/> <sup>4</sup> 리소스 사서함에는 라이선스가 필요하지 않습니다. 그러나 라이센스가 없으면 리소스 사서함이 50GB로 제한됩니다. 사서함 크기를 늘리려면 Exchange Online Plan 2 라이선스가 할당되어야 합니다. 그러면 100GB로 사서함이 늘어납니다. <br/> <sup>5</sup> 보관 사서함을 Exchange Online Kiosk에 포함 되지 않습니다. 하지만 Exchange Online Archiving을 통해 추가 기능으로 구입할 수 있습니다. 자세한 내용은 [Exchange Online Archiving 서비스 설명](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md)을 참조하십시오. <br/> <sup>6</sup> Microsoft Exchange Server 2013 조직의 기본 사서함 크기입니다. 관리자는 자신의 조직에 대한 이 값을 변경할 수 있습니다. ExchangeServer2013에서 공용 폴더 사서함은 100개까지만 사용할 수 있으며 모든 공용 폴더 사서함의 최대 크기는 50TB입니다. <br/> <sup>7</sup> Exchange Online에서 공용 폴더 사서함은 1,000개까지만 사용할 수 있으며 모든 공용 폴더 사서함의 최대 총 크기는 50TB입니다.  <br/> <sup>8</sup> 보관 사서함은 라이선스가 적용된 단일 사용자나 엔터티의 메일을 보관하는 경우에만 사용할 수 있습니다. 여러 사용자나 엔터티의 메일을 저장하는 목적으로 보관 사서함을 사용할 수는 없습니다. 예를 들어 IT 관리자는 공유 사서함을 만들 수 없고, 사용자가 명백히 보관을 목적으로 참조, 숨은 참조 필드 또는 전송 규칙을 통해 공유 사서함을 복사하도록 할 수 없습니다. <br/> <sup>9</sup> Exchange Online에서 보존 정책을 만든 경우 사용자의 기본 사서함이 10MB보다 큰 경우에만 메시지가 사용자 보관 사서함으로 자동 이동됩니다. 10MB보다 작은 사서함에 대해서는 보존 정책이 자동으로 실행되지 않습니다.<br/> <sup>10</sup> 공유 및 리소스 사서함에는 라이선스가 필요하지 않습니다. 그러나 라이센스가 없으면 해당 사서함이 50GB로 제한됩니다. 사서함 크기를 늘리려면 Exchange Online Plan 2 라이선스가 할당되어야 합니다. 그러면 100GB로 사서함이 늘어납니다. <br/> <sup>11</sup> 기본적으로 공유 사서함에는 시스템에서 생성된 (알 수 없는) 암호가 포함된 연결된 활성 사용자 계정이 있습니다. 연결된 공유 사서함 계정의 로그인을 차단하려면 [공유 사서함 계정의 로그인 차단](/office365/admin/email/create-a-shared-mailbox#block-sign-in-for-the-shared-mailbox-account)을 참조하세요.

## <a name="capacity-alerts"></a>용량 경고

Exchange Online에서는 사용자 사서함이 제한 용량에 가까워지거나 도달했을 경우 3가지 유형의 알림을 통해 사용자에게 경고합니다.

- **경고**: 사서함이 최대 크기 제한에 가까워지고 있다는 전자 메일 경고가 사용자에게 발송됩니다. 이 경고는 사용자가 원치 않는 메일을 삭제하도록 장려하기 위해 발송됩니다.

- **보내기 금지** 사서함 크기가 제한 용량에 도달할 경우 보내기 금지 알림 전자 메일이 사용자에게 발송됩니다. 전자 메일을 삭제하여 사서함 크기가 제한 용량 미만으로 줄어들 때까지 새로운 메시지를 보낼 수 없습니다.

- **보내기/받기 금지**: 사서함 크기가 제한 용량에 도달할 경우 Exchange Online은 모든 받는 메일을 거부하고 보낸 사람에게는 배달 못 함 보고서(NDR)을 보냅니다. 보낸 사람에게는 나중에 다시 해당 전자 메일을 보내도록 시도할 수 있는 옵션이 제공됩니다. 사용자는 사서함 크기가 제한 용량 미만으로 줄어들 때까지 전자 메일을 삭제해야만 다시 메시지를 받을 수 있습니다.

### <a name="capacity-alerts"></a>용량 경고

| 기능 | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|경고|49GB|49GB|49GB|98GB|98GB|1.96GB|
|보내기 금지|49.5GB|49.5GB|49.5GB|99GB|99GB|1.98GB|
|보내기/받기 금지|50 GB|50GB|50GB|100GB|100GB|2GB|

### <a name="capacity-alerts-across-standalone-plans"></a>독립 실행형 계획별 용량 경고

| 기능 | Exchange Server 2013 | Exchange Online 요금제 1 | Exchange Online 계획 2 | Exchange Online Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|경고|1.9GB<sup>1</sup>|49GB|98GB|1.96GB|
|보내기 금지|2GB<sup>1</sup>|49.5GB|99GB|1.98GB|
|보내기/받기 금지|2.3GB<sup>1</sup>|50GB|100GB|2GB|

> [!NOTE]
> <sup>1</sup>Exchange Server 2013 조직의 기본값입니다. 관리자는 자신의 조직에 대한 이 값을 변경할 수 있습니다.

## <a name="mailbox-folder-limits"></a>사서함 폴더 제한

이러한 제한은 사서함을 Exchange Online에서 지원 가능한 크기로 제한하기 위한 값입니다. 이러한 제한을 둠으로써 폴더당 사서함 항목, 사서함당 폴더 또는 Exchange Online 조직당 공용 폴더가 무제한으로 사용되는 것을 방지할 수 있습니다. 사실상 사서함 폴더 제한은 무한하며 대부분의 Exchange Online 사서함 및 Exchange Online으로 마이그레이션되는 온-프레미스 사서함을 지원하기에 충분합니다.

- **사서함 폴더당 최대 메시지 수**: 사서함 폴더의 최대 메시지 수를 지정합니다. 이 제한에 도달하면 새 메시지를 폴더에 배달하거나 저장할 수 없습니다.

- **사서함 폴더당 메시지 수에 대한 경고**: Exchange Online이 사서함 소유자에게 경고 메시지를 보내기 전까지 최대한 사서함 폴더에 보유할 수 있는 메시지 수를 지정합니다. 이 할당량에 도달하면 경고 메시지가 하루에 한 번 전송됩니다.

- **복구 가능한 항목 폴더의 폴더당 최대 메시지 수**: 복구 가능한 항목 폴더의 각 폴더에 포함할 수 있는 최대 메시지 수를 지정합니다. 폴더에서 이 제한을 초과하면 새 메시지를 저장할 수 없습니다. 예를 들어 복구 가능한 항목 폴더의 삭제 폴더가 메시지 개수 제한을 넘고 사서함 소유자가 자신의 사서함의 항목을 영구 삭제하려고 하는 경우 삭제에 실패합니다.

- **복구 가능한 항목 폴더의 폴더당 메시지 수 경고**: Exchange Online이 응용 프로그램 이벤트 로그에 이벤트를 기록하게 되는 복구 가능한 항목 폴더의 폴더당 메시지 수를 지정합니다.

- **사서함 폴더당 최대 하위 폴더 수**: 사서함 폴더에 만들 수 있는 최대 하위 폴더 수를 지정합니다. 이 제한에 도달하면 사서함 사용자가 하위 폴더를 새로 만들 수 없습니다.

- **사서함 폴더당 하위 폴더 수에 대한 경고**: Exchange Online이 사서함 소유자에게 경고 메시지를 보내기 전까지 사서함 폴더당 생성 가능한 하위 폴더 수를 지정합니다. 이 할당량에 도달하면 경고 메시지가 하루에 한 번 전송됩니다.

- **최대 폴더 계층 수준**: 사서함 폴더 계층 구조의 최대 폴더 단계 수를 지정합니다. 이 제한에 도달하면 사서함 사용자가 사서함 폴더 계층 구조에 폴더 단계를 더 추가하여 만들 수 없습니다.

- **폴더 계층 수준에 대한 경고**: Exchange Online이 사서함 소유자에게 경고 메시지를 보내기 전까지 생성할 수 있는 사서함 폴더의 폴더 계층 수를 지정합니다. 이 할당량에 도달하면 경고 메시지가 하루에 한 번 전송됩니다.

- **최대 공용 폴더 수**: 전체 공용 폴더 계층 구조에서 공용 폴더의 최대 수를 지정합니다. 이 제한에 도달하면 기존 공용 폴더를 삭제해야 새 공용 폴더를 만들 수 있습니다.

- **공용 폴더당 최대 하위 폴더 수**: 공용 폴더에 만들 수 있는 최대 하위 폴더 수를 지정합니다. 이 제한에 도달하면 공용 폴더에서 새 하위 폴더를 만들 수 없습니다.

- **공용 폴더당 하위 폴더 수에 대한 경고**: Exchange Online이 폴더 소유자에게 경고 메시지를 보내기 전까지 공용 폴더당 생성 가능한 하위 폴더 수를 지정합니다. 소유자가 없으면 소유자 권한이 있는 사용자에게 경고 메시지가 전달됩니다. 이 할당량에 도달하면 경고 메시지가 하루에 한 번 전송됩니다.

### <a name="mailbox-folder-limits"></a>사서함 폴더 제한

| 기능 | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|사서함 폴더당 최대 메시지 수|1백만|1백만|1백만|1백만|1백만|1백만|
|사서함 폴더당 메시지 수에 대한 경고|900,000|900,000|900,000|900,000|900,000|900,000|
|복구 가능한 항목 폴더의 폴더당 최대 메시지 수|3백만 개|3백만 개|3백만 개|3백만 개|3백만 개|3백만 개|
|기본 사서함에서 복구 가능한 항목 폴더에 대한 저장소 할당량(보류 중 아님)|30GB|30GB|30GB|30GB|30GB|30GB|
|기본 사서함에서 복구 가능한 항목 폴더에 대한 저장소 할당량(보류 중)|100GB|100GB|100GB|100GB|100GB|100GB|
|보관 사서함에서 복구 가능한 항목 폴더에 대한 저장소 할당량(보류 중 아님)|30GB|30GB|30GB|Unlimited<sup>2</sup>|Unlimited<sup>2</sup>|30GB|
|보관 사서함에서 복구 가능한 항목 폴더에 대한 저장소 할당량(보류 중)|100 GB<sup>1</sup>|100 GB<sup>1</sup>|100 GB<sup>1</sup>|Unlimited<sup>2</sup>|Unlimited<sup>2</sup>|100 GB<sup>1</sup>|
|복구 가능한 항목 폴더의 폴더당 메시지 수에 대한 경고|2,750,000개|2,750,000개|2,750,000개|2,750,000개|2,750,000개|2,750,000개|
|사서함 폴더당 최대 하위 폴더 수|10,000<sup>2</sup>|10,000<sup>2</sup>|10,000<sup>2</sup>|10,000<sup>2</sup>|10,000<sup>2</sup>|10,000<sup>2</sup>|
|사서함 폴더당 하위 폴더 수에 대한 경고|9000|9000|9000|9000|9000|9000|
|최대 폴더 계층 수|300|300|300|300|300|300|
|폴더 계층 수에 대한 경고|250|250|250|250|250|250|
|최대 공용 폴더 수|500,000|500,000|500,000|500,000|500,000|사용할 수 없음|
|공용 폴더당 최대 하위 폴더 수|10,000|10,000|10,000|10,000|10,000|사용할 수 없음|
|공용 폴더당 하위 폴더 수에 대한 경고|9000|9000|9000|9000|9000|사용할 수 없음|

> [!NOTE]
> <sup>1</sup> 이것은 전체 보관 사서함의 할당량이 아닌 복구 가능한 항목 폴더의 저장소 할당량입니다. Exchange Online 플랜 2 라이선스 또는 ExchangeOnlinePlan1과 Exchange Online Archiving 라이선스를 모두 가진 사용자의 경우, 보관 사서함의 저장소 할당량이 제한되지 않습니다. 복구 가능한 항목 할당량을 늘리는 방법에 대한 자세한 내용은 [보류 중인 사서함의 복구 가능한 항목 할당량 늘리기](/microsoft-365/compliance/increase-the-recoverable-quota-for-mailboxes-on-hold)를 참조하세요.<br/> <sup>2</sup> 보관 사서함에서 복구 가능한 항목 폴더에 대한 초기 저장소 할당량은 100GB입니다. 자동 확장 보관이 켜져 있는 경우 복구 가능한 항목 폴더의 저장소 용량에 도달하면 이 추가 저장소가 자동으로 추가됩니다. 자세한 내용은 [Office 365 무제한 보관의 개요](/microsoft-365/compliance/unlimited-archiving)를 참조하세요. 자동 확장 보관의 가용성에 대한 자세한 내용은 [Microsoft 365 로드맵](https://go.microsoft.com/fwlink/?LinkId=509914)을 참조하세요.
> <sup>2</sup> 이 항목은 저장 한도입니다. 사서함 셰이프 제약 조건 중 하나입니다. 주어진 부모에 대한 직접 자식 폴더는 10,000개만 있을 수 있습니다. 이는 폴더를 만드는 마이그레이션 또는 다른 클라이언트에 관계없이 적용됩니다.

### <a name="mailbox-folder-limits-across-standalone-plans"></a>독립 실행형 계획별 사서함 폴더 제한

| 기능 | Exchange Server 2013 | Exchange Online 요금제 1 | Exchange Online 계획 2 | Exchange Online Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|사서함 폴더당 최대 메시지 수|제한 없음<sup>1</sup>|1백만|1백만|1백만|
|사서함 폴더당 메시지 수에 대한 경고|제한 없음|900,000|900,000|900,000|
|복구 가능한 항목 폴더의 폴더당 최대 메시지 수|제한 없음|3백만 개|3백만 개|3백만 개|
|기본 사서함에서 복구 가능한 항목 폴더에 대한 저장소 할당량(보류 중 아님)|30GB|30GB|30GB|30GB|
|기본 사서함에서 복구 가능한 항목 폴더에 대한 저장소 할당량(보류 중)|100GB|100GB|100GB|100GB|
|보관 사서함에서 복구 가능한 항목 폴더에 대한 저장소 할당량(보류 중 아님)|30GB|30GB|30GB|30GB|
|보관 사서함에서 복구 가능한 항목 폴더에 대한 저장소 할당량(보류 중)|100 GB<sup>2</sup>|100 GB<sup>2</sup>|Unlimited<sup>3</sup>|Unlimited<sup>3</sup>|
|복구 가능한 항목 폴더의 폴더당 메시지 수에 대한 경고|제한 없음|2,750,000개|2,750,000개|2,750,000개|
|사서함 폴더당 최대 하위 폴더 수|제한 없음|1000|1000|1000|
|사서함 폴더당 하위 폴더 수에 대한 경고|제한 없음|900|900|900|
|최대 폴더 계층 수|제한 없음|300|300|300|
|폴더 계층 수에 대한 경고|제한 없음|250|250|250|
|최대 공용 폴더 수|1,000,000|100,000|100,000|사용할 수 없음|
|공용 폴더당 최대 하위 폴더 수|해당 없음|1,000|1,000|사용할 수 없음|
|공용 폴더당 하위 폴더 수에 대한 경고|해당 없음|900|900|사용할 수 없음|

> [!NOTE]
> <sup>1</sup> 사서함 폴더당 메시지 수는 1,000,000개 이하로 하는 것이 좋습니다. > <br/> <sup>2</sup> 이것은 전체 보관 사서함의 할당량이 아닌 복구 가능한 항목 폴더의 저장소 할당량입니다. Exchange Online 플랜 2 라이선스 또는 ExchangeOnlinePlan1과 Exchange Online Archiving 라이선스를 모두 가진 사용자의 경우, 보관 사서함의 저장소 할당량이 제한되지 않습니다. 복구 가능한 항목 할당량을 늘리는 방법에 대한 자세한 내용은 [보류 중인 사서함의 복구 가능한 항목 할당량 늘리기](/microsoft-365/compliance/increase-the-recoverable-quota-for-mailboxes-on-hold)를 참조하세요.<br/> <sup>3</sup> 보관 사서함에 있는 복구 가능한 항목 폴더의 초기 저장소 할당량은 100GB입니다. 자동 확장 보관 기능이 켜져 있는 경우 복구 가능한 항목 폴더의 저장 용량에 도달하면 추가 저장소가 자동으로 추가됩니다. 자세한 내용은 [Office 365의 무제한 보관 개요](/microsoft-365/compliance/unlimited-archiving)를 참조하세요. 자동 확장 보관 사용 가능 여부에 대한 자세한 내용은 [Microsoft 365 로드맵](https://go.microsoft.com/fwlink/?LinkId=509914)을 참조하세요.

## <a name="message-limits"></a>메시지 제한

다음 제한은 모든 전자 메일 메시지에 적용됩니다.

- **메시지 크기 제한**: 대용량 메시지가 다른 메시지의 배달을 차단하거나 사용자에 대한 서비스 성능에 영향을 미치지 않도록 하려면 메시지 크기 제한이 필요합니다. 이 제한은 첨부 파일을 포함하며 조직 전체에 대한 모든 메시지(인바운드, 아웃바운드, 내부)에 적용됩니다. 이 제한보다 큰 메시지는 배달되지 않으며, 보낸 사람에게는 배달 못 함 보고서(NDR)가 전송됩니다. 메시지 크기 제한은 더 크게, 더 작게 또는 각 사용자별로 구성할 수 있으며, 관리자는 전송 규칙을 만들어 모든 개별 첨부 파일의 최대 크기를 제한할 수도 있습니다. 자세한 내용은 [Microsoft 365에서 더 큰 전자 메일 메시지 지원](https://go.microsoft.com/fwlink/?linkid=2144144)을 참조하세요.

    > [!NOTE]
    > 일부 전자 메일 클라이언트의 메시지 크기 제한 또는 개별 첨부 파일의 크기 제한은 Exchange Online 메시지 크기 제한 값보다 작을 수 있습니다.

- **메시지 헤더 크기 제한**: 메시지에 있는 모든 메시지 헤더 필드의 최대 크기에 지정합니다. 현재 제한은 256KB입니다. 모든 메시지 머리글의 전체 크기가 256KB를 초과하면 Exchange Online에서 “552 5.3.4 머리글 크기가 고정 최대 크기를 초과합니다”라는 오류를 표시하며 메시지를 거부합니다. 메시지 본문이나 첨부 파일의 크기는 고려되지 않습니다. 헤더 필드는 일반 텍스트이므로 헤더의 크기는 각 헤더 필드의 문자 수와 헤더 필드의 전체 수에 의해 결정됩니다. 텍스트의 각 문자는 1바이트를 차지합니다.

- **제목 길이 제한**: 전자 메일 메시지의 제목 줄에서 허용되는 텍스트 문자의 최대 개수입니다.

- **첨부 파일 제한**: 전자 메일 메시지에 허용되는 최대 첨부 파일 수입니다. 모든 첨부 파일의 전체 크기가 메시지 크기 제한을 넘지 않는 경우에도 메시지에서 허용되는 첨부 파일 수에 대한 제한이 있습니다. 이 제한은 여러 부분으로 구성된 메시지 제한을 통해 제어됩니다.

- **첨부 파일 크기 제한**: 단일 첨부 파일의 최대 파일 크기입니다.

    > [!NOTE]
    > 단일 첨부 파일의 최대 파일 크기입니다. 웹용 Outlook을 포함한 개별 클라이언트 프로그램에서 첨부 파일 크기를 이 최대값 미만으로 제한할 수 있습니다. Exchange ActiveSync에서는 첨부 파일 크기 제한을 개별 첨부 파일별로 설정하지 않습니다. Exchange ActiveSync 메시지에 대한 모든 첨부 파일의 전체 크기는 메시지 크기 제한보다 작아야 합니다.

- **여러 부분으로 구성된 메시지 제한**: 여러 부분으로 구성된 MIME 형식의 메시지에서 허용되는 메시지 본문 부분의 최대 개수입니다. 이 제한은 메시지에서 허용되는 첨부 파일의 최대 수도 제어합니다.

- **포함 메시지 수준 제한**: 전자 메일 메시지에 허용되는 전달된 전자 메일 메시지의 최대 수입니다.

### <a name="message-limits"></a>메시지 제한

| 기능 | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|메시지 크기 제한 - Outlook|150MB<sup>1, 2</sup>|150MB<sup>1, 2</sup>|150MB<sup>1, 2</sup>|150MB<sup>1, 2</sup>|150MB<sup>1, 2</sup>|150MB<sup>1, 2</sup>|
|메시지 크기 제한 - OWA|112MB<sup>1, 3</sup>|112MB<sup>1, 3</sup>|112MB<sup>1, 3</sup>|112MB<sup>1, 3</sup>|112MB<sup>1, 3</sup>|112MB<sup>1, 3</sup>|
|메시지 크기 제한 - Outlook for Mac|150MB<sup>1, 2</sup>|150MB<sup>1, 2</sup>|150MB<sup>1, 2</sup>|150MB<sup>1, 2</sup>|150MB<sup>1, 2</sup>|150MB<sup>1, 2</sup>|
|메시지 크기 제한 - 마이그레이션|150MB <sup>1, 4</sup>|150MB <sup>1, 4</sup>|150MB <sup>1, 4</sup>|150MB <sup>1, 4</sup>|150MB <sup>1, 4</sup>|150MB <sup>1, 4</sup>|
|메시지 크기 제한 - iOS 및 Android용 Outlook | 33 MB| 33 MB| 33 MB| 33 MB| 33 MB| 33 MB|
|암호화된 메시지의 크기 제한(새 기능에 Office 365 메시지 암호화를 사용하는 구독자)<sup>5</sup>|25MB|25MB|25MB|25MB|25MB|25MB|
|암호화된 메시지의 크기 제한(Office 365 메시지 암호화 레거시 버전을 사용하는 구독자)<sup>5</sup>|25MB|25MB|25MB|25MB|25MB|25MB|
|제목 길이 제한|255자|255자|255자|255자|255자|255자|
|파일 첨부 제한|250개 첨부 파일|250개 첨부 파일|250개 첨부 파일|250개 첨부 파일|250개 첨부 파일|250개 첨부 파일|
|첨부 파일 크기 제한 - Outlook|150MB|150MB|150MB|150MB|150MB|150MB|
|첨부 파일 크기 제한 - OWA |112 MB<sup>3, 6</sup>|112 MB<sup>3, 6</sup>|112 MB<sup>3, 6</sup>|112 MB<sup>3, 6</sup>|112 MB<sup>3, 6</sup>|112 MB<sup>3, 6</sup>|
|첨부 파일 크기 제한 - Outlook for Mac|150MB|150MB|150MB|150MB|150MB|150MB|
|파일 첨부 파일 크기 제한 - iOS 및 Android용 Outlook|33 MB |33 MB |33 MB |33 MB |33 MB |33 MB |
|여러 부분으로 구성된 메시지 제한|250개 부분|250개 부분|250개 부분|250개 부분|250개 부분|250개 부분|
|포함 메시지 수준 제한|30개 포함 메시지|30개 포함 메시지|30개 포함 메시지|30개 포함 메시지|30개 포함 메시지|30개 포함 메시지|

> [!NOTE]
> <sup>1</sup> Microsoft 사서함의 기본 최대 메시지 크기는 25MB입니다. Microsoft 관리자는 1MB에서 150MB 사이의 사용자 지정 제한을 지정할 수 있습니다. 그러나 보내거나 받을 수 있는 메시지의 크기는 이메일 클라이언트 또는 솔루션이 지원하는 항목에 따라 다릅니다. 조직에 허용되는 최대 메시지 크기 사용자 지정에 대한 자세한 내용은 [Microsoft는 더 큰 이메일 메시지 지원](https://go.microsoft.com/fwlink/?linkid=2144144)을 참조하세요. <br/> <sup>2</sup> 사용자 간에 최대 150MB의 메시지를 보내고 받을 수 있습니다(메시지가 Microsoft 데이터 센터를 벗어나지 않을 경우). Microsoft 데이터 센터 외부로 전송되는 메시지는 변환 인코딩이 추가로 33% 증가할 수 있습니다. 이 경우 최대 메시지 크기는 112MB가 됩니다. <br/> 
<sup>3</sup> OWA는 메시지의 인코딩이 33% 증가할 가능성을 고려하여 사용자가 보낼 수 있는 메시지 크기를 구성된 설정보다 25% 작게 제한합니다. 예를 들어 100MB의 최대 메시지 크기에 대한 설정을 사용자 지정하는 경우 75MB보다 크지 않은 메시지를 보낼 수 있습니다. <br/> <sup>4</sup> Exchange Online으로 이동될 메시지 크기는 Exchange Online에서 계산됩니다. Exchange Server 2013 이전의 Exchange 버전에서는 좀 더 작은 항목 크기를 보고할 수 있습니다. 이 제한은 지원되는 Exchange 사서함 복제 서비스를 사용하는 이동 기반 마이그레이션에 적용됩니다. 다른 마이그레이션 방법(단독형, 미리 구성, IMAP, PST) 및 기타 타사 도구는 일반 메시지 크기 제한에 따라 제한됩니다. <br/> 
<sup>5</sup> 새로운 기능이 있는 OME에 관한 정보는 [Azure Information Protection을 기반으로 빌드된 새 Office 365 Message Encryption 기능 설정](https://support.office.com/article/7ff0c040-b25c-4378-9904-b1b50210d00e)을 참조하세요.<br/> 
<sup>6</sup> 클래식 첨부 파일은 112MB로 제한되지만 OneDrive 파일 첨부 파일은 최대 2GB까지 사용할 수 있습니다.


### <a name="message-limits-across-standalone-options"></a>독립 실행형 옵션별 메시지 제한

| 기능 | Exchange Server 2013 | Exchange Online 요금제 1 | Exchange Online 계획 2 | Exchange Online Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|메시지 크기 제한 - Outlook|10MB<sup>4</sup>|150MB<sup>1, 2</sup>|150MB<sup>1, 2</sup>|150MB<sup>2</sup>|
|메시지 크기 제한 - OWA|10MB<sup>4</sup>|112MB<sup>1, 3</sup>|112MB<sup>1, 3</sup>|150MB<sup>1, 2</sup>|
|메시지 크기 제한 - Outlook for Mac|10MB<sup>4</sup>|150MB|150MB||
|메시지 크기 제한 - 마이그레이션|해당 없음|150MB <sup>5</sup>|150MB <sup>5</sup>|150MB <sup>5</sup>|
|메시지 크기 제한 - iOS 및 Android용 Outlook |25 MB |33 MB |33 MB |33 MB |
|암호화된 메시지의 크기 제한(새 기능에 Office 365 메시지 암호화를 사용하는 구독자)<sup>6</sup>|150MB|150MB|150MB|150MB|
|암호화된 메시지의 크기 제한(Office 365 메시지 암호화 레거시 버전을 사용하는 구독자)<sup>6</sup>|25MB|25MB|25MB|25MB|
|제목 길이 제한|255자|255자|255자|255자|
|파일 첨부 제한|1024 attachments<sup>4</sup>|250개 첨부 파일|250개 첨부 파일|250개 첨부 파일|
|첨부 파일 크기 제한 - Outlook|35MB<sup>4</sup>|150MB|150MB|150MB|
|첨부 파일 크기 제한 - OWA|35MB<sup>4</sup>|112 MB<sup>3</sup>|112 MB<sup>3</sup>|112 MB<sup>3</sup>|
|첨부 파일 크기 제한 - Outlook for Mac|35MB<sup>4</sup>|150MB|150MB|35MB|
|파일 첨부 파일 크기 제한 - iOS 및 Android용 Outlook|25 MB |33 MB|33 MB|33 MB|
|여러 부분으로 구성된 메시지 제한|250개 부분|250개 부분|250개 부분|250개 부분|
|포함 메시지 수준 제한|30개 포함 메시지|30개 포함 메시지|30개 포함 메시지|30개 포함 메시지|

> [!NOTE]
> <sup>1</sup> Microsoft 관리자는 1MB에서 150MB 사이의 사용자 지정 제한을 지정할 수 있습니다. 그러나 보내거나 받을 수 있는 메시지의 크기는 이메일 클라이언트 또는 솔루션이 지원하는 항목에 따라 다릅니다. 조직에 허용되는 최대 메시지 크기 사용자 지정에 대한 자세한 내용은 [Microsoft는 더 큰 이메일 메시지 지원](https://go.microsoft.com/fwlink/?linkid=2144144)을 참조하세요. <br/> <sup>2</sup> 사용자 간에 최대 150MB의 메시지를 보내고 받을 수 있습니다(메시지가 Microsoft 데이터 센터를 벗어나지 않을 경우). Microsoft 데이터 센터 외부로 전송되는 메시지는 변환 인코딩이 추가로 33% 증가할 수 있습니다. 이 경우 최대 메시지 크기는 112MB가 됩니다. <br/> 
<sup>3</sup> OWA는 메시지의 인코딩이 33% 증가할 가능성을 고려하여 사용자가 보낼 수 있는 메시지 크기를 구성된 설정보다 25% 작게 제한합니다. 예를 들어 100MB의 최대 메시지 크기에 대한 설정을 사용자 지정하는 경우 75MB보다 크지 않은 메시지를 보낼 수 있습니다. <br/> 
<sup>4</sup> Exchange Server 2013 조직의 기본 제한입니다. 관리자는 자신의 조직에 대한 이 값을 변경할 수 있습니다. <br/> 
<sup>5</sup> Exchange Online으로 이동될 메시지 크기는 Exchange Online에서 계산됩니다. Exchange Server 2013 이전의 Exchange 버전에서는 좀 더 작은 항목 크기를 보고할 수 있습니다. <br/> 
<sup>6</sup> 새로운 기능이 있는 OME에 관한 정보는 [Azure Information Protection을 기반으로 빌드된 새 Office 365 Message Encryption 기능 설정](https://support.office.com/article/7ff0c040-b25c-4378-9904-b1b50210d00e)을 참조하세요.

## <a name="receiving-and-sending-limits"></a>수신 및 전송 제한

수신 및 전송 제한은 스팸 및 대량 메일 웜 또는 바이러스를 방지하기 위해 적용됩니다. 이러한 제한은 시스템의 상태를 보호하고 사용자를 안전하게 유지하는 데 도움이 됩니다.

### <a name="receiving-limits"></a>수신 제한

수신 제한은 Exchange Online 사용자, 그룹 또는 공용 폴더가 받을 수 있는 메시지 수에 적용됩니다.

- **수신 제한:** 이 제한은 *모든 원본* 에서 시간당 메시지 수에 적용됩니다. 여기에는 내부 발신자가 보내는 메시지, 인터넷에서 발송되는 메시지, 온-프레미스 서버에서 발송되는 메시지가 모두 포함됩니다. 사서함의 수신 제한이 초과될 경우 사서함에 발송된 메시지는 사서함의 전송 임계치가 초과되었다는 내용을 담은 배달 못 함 보고서(NDR 또는 반송 메시지라고도 함)와 함께 보낸 사람에게 다시 반송됩니다. 한 시간 후에 이 제한이 새로 고쳐지고 사서함은 메시지를 받을 수 있게 됩니다.
- **발신자-수신자 쌍 제한:** 이 제한은 *단일 발신자* 가 보내는 시간당 메시지 수에 적용됩니다. 이것은 단일 발신자 메일 폭풍으로부터 보호하기 위해 전체 수신 제한의 비율로 설정됩니다.

| 기능 | Microsoft 365 Business Basic | Microsoft 365 Business Standard Office | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|메시지 수신됨|시간당 3600개 메시지|시간당 3600개 메시지|시간당 3600개 메시지|시간당 3600개 메시지|시간당 3600개 메시지|하루에 3600개 메시지|
|단일 발신자로부터 받은 메시지|수신된 메시지의 33%|수신된 메시지의 33%|수신된 메시지의 33%|수신된 메시지의 33%|수신된 메시지의 33%|수신된 메시지의 33%|

### <a name="sending-limits"></a>전송 제한

전송 제한은 사용자가 Exchange Online 계정에서 보낼 수 있는 메시지당 받는 사람 수, 메시지의 수 및 받는 사람 수에 적용됩니다.

> [!NOTE]
> 조직의 주소록에 저장된 메일 그룹은 받는 사람 한 명으로 계산합니다. 사서함의 연락처 폴더에 저장된 메일 그룹은 해당 그룹의 구성원들을 각각 계산합니다.

- **받는 사람 처리 속도 제한**: 원치 않는 대량 메시지의 배달을 막기 위해 Exchange Online에서는 받는 사람 제한을 통해 사용자와 응용 프로그램이 대용량 전자 메일을 보내는 것을 방지합니다. 이러한 제한은 모든 아웃바운드 메시지 및 내부 메시지에 사용자당 적용됩니다.

    > [!NOTE]
    > 적법한 상업성 대량 전자 메일(예: 고객 회보)을 보내려는 Exchange Online 고객은 이러한 서비스를 제공하는 타사 제공업체를 이용해야 합니다.

- **받는 사람 제한**: 단일 전자 메일 메시지에 대한 받는 사람, 참조 및 숨은 참조 필드에서 허용되는 최대 받는 사람 수입니다.

    > [!NOTE]
    > 받는 사람 처리 속도 제한 및 받는 사람 제한을 적용하기 위해 조직의 공유 주소록에 저장된 메일 그룹이 하나의 받는 사람으로 계산됩니다. 개인 메일 그룹의 받는 사람은 각각 하나의 받는 사람으로 계산됩니다.

- **받는 사람 프록시 주소 제한**: 받는 사람 프록시 주소 제한은 받는 사람 사서함에 사용할 수 있는 별칭(전자 메일 주소)의 최대 개수입니다. 

- **메시지 처리 속도 제한**: 메시지 처리 속도 제한은 사용자가 일정 기간 동안 Exchange Online 계정에서 보낼 수 있는 메시지의 수를 결정합니다. 이 제한은 보낸 사람 한 명이 시스템 리소스를 과도하게 사용하지 못하도록 방지할 수 있습니다. 사용자가 SMTP 클라이언트 전송을 통해 제한을 초과하는 속도로 메시지를 전송하면 메시지가 거부되므로 해당 클라이언트가 다시 시도해야 합니다.

#### <a name="sending-limits"></a>전송 제한

| 기능 | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|받는 사람 처리 속도 제한<sup>1</sup>|하루에 받는 사람 10,000명|하루에 받는 사람 10,000명|하루에 받는 사람 10,000명|하루에 받는 사람 10,000명|하루에 받는 사람 10,000명|하루에 받는 사람 10,000명|
|수신자 제한<sup>2</sup>|수신자 최대 1,000명으로 사용자 지정 가능|수신자 최대 1,000명으로 사용자 지정 가능|수신자 최대 1,000명으로 사용자 지정 가능|수신자 최대 1,000명으로 사용자 지정 가능|수신자 최대 1,000명으로 사용자 지정 가능|수신자 최대 1,000명으로 사용자 지정 가능|
|받는 사람 프록시 주소 제한|400|400|400|400|400|400|
|메시지 속도 제한<sup>3</sup>|분당 30개 메시지|분당 30개 메시지|분당 30개 메시지|분당 30개 메시지|분당 30개 메시지|분당 30개 메시지|

> [!NOTE]
> <sup>1</sup> 받는 사람 비율 제한에 도달하면 지난 24시간 내에 메시지를 받았던 받는 사람 수가 한도 미만이 될 때까지 사서함에서 메시지를 보낼 수 없습니다. 예를 들어, 사용자는 오전 09:00에 5000명의 수신자에게 전자 메일 메시지를 보낸 다음 오전 10:00에 2500명의 수신자에게 다른 메시지를 보낸 다음 오전 11:00에 2500명의 수신자에게 다른 메시지를 보내 10,000개의 메시지 제한을 초과하게 됩니다. 사용자는 다음 날 오전 09:00까지 메시지를 다시 보낼 수 없습니다.  
> <sup>2</sup> 기존 사서함과 향후 만들 새 사서함에 대해 받는 사람 제한을 1에서 1000 사이로 사용자 지정할 수 있습니다. Exchange 관리 센터를 사용하여 개별적으로 또는 대량으로 기존 사서함에 대한 받는 사람 제한을 편집하고 원격 PowerShell을 통해 새 사서함에 대한 기본 설정을 사용자 지정합니다. 자세한 내용은 Office 365 [사용자 지정 가능한 수신자 제한](https://techcommunity.microsoft.com/t5/exchange-team-blog/customizable-recipient-limits-in-office-365/ba-p/1183228)을 참조하세요.  
> <sup>3</sup> 아웃바운드 메시지 볼륨이 메시지 속도 제한을 초과하면 메시지 전송이 초과된 모든 제한이 제한되어 다음 분(시간)까지 연속적으로 전송됩니다. 일반적으로 이 작업은 보낸 사람 계정을 차단하지는 않지만 Exchange Online은 대량 메일 발송 시나리오를 수용하는 경우 적합하지 않습니다. 이 사용 사례의 경우 [여기](/exchange/mail-flow-best-practices/how-to-set-up-a-multifunction-device-or-application-to-send-email-using-microsoft-365-or-office-365)에 있는 옵션 2와 3을 대신 사용하는 것이 좋습니다.

#### <a name="sending-limits-across-standalone-options"></a>독립 실행형 옵션별 전송 제한

| 기능 | Exchange Server 2013 | Exchange Online 요금제 1 | Exchange Online 계획 2 | Exchange Online Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|받는 사람 처리 속도 제한|제한 없음<sup>1</sup>|하루당 수신자 10,000명<sup>2</sup>|하루당 수신자 10,000명<sup>2</sup>|하루당 수신자 10,000명<sup>2</sup>|
|수신자 제한|수신자 1000명<sup>1</sup>|수신자 1000명|수신자 1000명|수신자 1000명|
|받는 사람 프록시 주소 제한|400|400|400|400|
|메시지 속도 제한|제한 없음|분당 30개 메시지|분당 30개 메시지|분당 30개 메시지|

> [!NOTE]
> <sup>1</sup>Exchange Server 2013 조직의 기본 제한입니다. 관리자는 자신의 조직에 대한 이 값을 변경할 수 있습니다.<br/>
<sup>2</sup>: 받는 사람 비율 제한에 도달하면 지난 24시간 내에 메시지를 받았던 받는 사람 수가 한도 미만이 될 때까지 사서함에서 메시지를 보낼 수 없습니다. 예를 들어, 사용자는 오전 09:00에 5000명의 수신자에게 전자 메일 메시지를 보낸 다음 오전 10:00에 2500명의 수신자에게 다른 메시지를 보낸 다음 오전 11:00에 2500명의 수신자에게 다른 메시지를 보내 10,000개의 메시지 제한을 초과하게 됩니다. 사용자는 다음 날 오전 09:00까지 메시지를 다시 보낼 수 없습니다.

## <a name="reporting-and-message-trace-limits"></a>보고 및 메시지 추적 제한

보고 및 메시지 추적 제한에 대한 내용은 Exchange Online Protection의 보고 및 메시지 추적의 [보고 및 메시지 추적 데이터 사용 가능 여부 및 대기 시간](/microsoft-365/security/office-365-security/reporting-and-message-trace-in-exchange-online-protection) 섹션을 참조하세요.

## <a name="retention-limits"></a>보존 제한

다음 제한은 받은 편지함의 특정 폴더에 있는 항목에 액세스할 수 있는 기간을 제어합니다.

- **지운 편지함 폴더 보존 기간**: 항목이 자동으로 제거되기 전에 지운 편지함 폴더에 남아 있을 수 있는 최대 기간(일)입니다.

- **지운 편지함 폴더에서 제거한 항목의 보존 기간**: 지운 편지함 폴더에서 제거된 항목이 영구적으로 삭제되기 전에 보존되는 최대 기간(일)입니다.

- **정크 메일 폴더 보존 기간**: 항목이 자동으로 제거되기 전에 정크 메일 폴더에 남아 있을 수 있는 최대 기간(일)입니다.

> [!NOTE]
> 소프트 삭제된 사용자 사서함&mdash;Microsoft 365 관리 센터 또는 Exchange Online PowerShell에서 Remove-Mailbox cmdlet을 사용하여 삭제되고 여전히 Azure Active Directory 휴지통에 있는 사서함&mdash;은 30일 이내에 복구할 수 있습니다.

### <a name="retention-limits"></a>보존 제한

| 기능 | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|지운 편지함 폴더 보존 기간|제한 없음<sup>1</sup>|제한 없음<sup>1</sup>|제한 없음<sup>1</sup>|제한 없음<sup>1</sup>|제한 없음<sup>1</sup>|제한 없음<sup>1</sup>|
|지운 편지함 폴더에서 제거한 항목의 보존 기간|14일<sup>1</sup>|14일<sup>1</sup>|14일<sup>1</sup>|14일<sup>1</sup>|14일<sup>1</sup>|14일<sup>1</sup>|
|정크 메일 폴더 보존 기간|30일|30일|30일|30일|30일|30일|

> [!NOTE]
> <sup>1</sup> Microsoft 365 조직의 기본값입니다. 관리자는 조직 사서함에 대해 이 값을 최대 30일로 변경할 수 있습니다.

### <a name="retention-limits-across-standalone-options"></a>독립 실행형 옵션별 보존 제한

| 기능 | Exchange Server 2013 | Exchange Online 요금제 1 | Exchange Online 계획 2 | Exchange Online Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|지운 편지함 폴더 보존 기간|제한 없음<sup>1</sup>|제한 없음<sup>1</sup>|제한 없음<sup>1</sup>|제한 없음<sup>1</sup>|
|지운 편지함 폴더에서 제거한 항목의 보존 기간|14일<sup>1</sup>|14일<sup>2</sup>|14일<sup>2</sup>|14일<sup>2</sup>|
|정크 메일 폴더 보존 기간|2년<sup>1</sup>|30일|30일|30일|

> [!NOTE]
> <sup>1</sup> 기본 제한입니다. 관리자는 자신의 조직에 대한 이 값을 변경할 수 있습니다.<br/> <sup>2</sup> Exchange Online 조직의 기본값입니다. 관리자는 조직 사서함에 대해 이 값을 최대 30일로 변경할 수 있습니다.

## <a name="distribution-group-limits"></a>메일 그룹 제한

이러한 제한은 조직의 공유 주소록에 포함된 메일 그룹에 적용됩니다.

- **최대 메일 그룹 구성원 수**: 총 수신자 수는 메일 그룹 확장 후 결정됩니다.

- **큰 메일 그룹에 메시지 보내기 제한**: 이 제한에 지정된 수의 구성원을 포함하는 메일 그룹에 대해 배달 관리 또는 메시지 승인 옵션을 구성해야 합니다. 배달 관리는 메일 그룹에 메시지를 보낼 수 있는 보낸 사람 목록을 지정하고, 메시지 승인은 메일 그룹에 보낸 모든 메시지를 승인해야 하는 한 명 이상의 중재자를 지정합니다.

- **대규모 메일 그룹의 최대 메시지 크기**: 메시지가 5,000명 이상의 수신자에게 전송되는 경우 메시지 크기는 이 제한을 초과할 수 없습니다. 메시지 크기가 제한을 초과하면 메시지가 배달되지 않고 보낸 사람은 NDR(배달 못 함 보고서)을 받습니다.

### <a name="distribution-group-limits"></a>메일 그룹 제한

| 기능 | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|최대 메일 그룹 구성원 수<sup>1</sup>|구성원 100,000명|구성원 100,000명|구성원 100,000명|구성원 100,000명|구성원 100,000명|구성원 100,000명|
|큰 메일 그룹에 메시지 보내기 제한|구성원 5,000명 이상|구성원 5,000명 이상|구성원 5,000명 이상|구성원 5,000명 이상|구성원 5,000명 이상|구성원 5,000명 이상|
|5,000명 ~ 99,999명의 구성원이 있는 메일 그룹에 대한 최대 메시지 크기|25MB|25MB|25MB|25MB|25MB|25MB|
|100,000명의 구성원이 있는 큰 메일 그룹에 대한 최대 메시지 크기|5MB|5MB|5MB|5MB|5MB|5MB|
|최대 메일 그룹 소유자 수|10|10|10|10|10|10|
|사용자가 만들 수 있는 최대 그룹 수|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|

> [!NOTE]
> <sup>1</sup> Azure Active Directory DirSync를 사용하는 경우 온-프레미스 Active Directory에서 Azure Active Directory로 동기화할 수 있는 메일 그룹 구성원의 최대 수는 15,000개입니다. Azure AD Connect를 사용하는 경우에는 이 수가 50,000개입니다. <br/> <sup>2</sup> 이 제한은 관리자에게도 적용됩니다.

### <a name="distribution-group-limits-across-standalone-options"></a>독립 실행형 옵션별 메일 그룹 제한

| 기능 | Exchange Server 2013 | Exchange Online 요금제 1 | Exchange Online 계획 2 | Exchange Online Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|최대 메일 그룹 구성원 수|구성원 100,000명<sup>1</sup>|구성원 100,000명|구성원 100,000명|구성원 100,000명|
|큰 메일 그룹에 메시지 보내기 제한|구성원 5,000명 이상<sup>1</sup>|구성원 5,000명 이상|구성원 5,000명 이상|구성원 5,000명 이상|
|최대 메일 그룹 소유자 수|10|10|10|10|
|사용자가 만들 수 있는 최대 그룹 수|250<sup>2</sup>|250<sup>2</sup>|250<sup>2</sup>|250<sup>2</sup>|

> [!NOTE]
> <sup>1</sup>Exchange Server 2013 조직의 기본 제한입니다. 관리자는 자신의 조직에 대한 이 값을 변경할 수 있습니다. <br/> <sup>2</sup> 이 제한은 관리자에게도 적용됩니다.

## <a name="journal-transport-and-inbox-rule-limits"></a>저널, 전송 및 받은 편지함 규칙 제한

다음 목록에는 저널 규칙, 전송 규칙에 적용되는 제한(조직 차원 규칙이라고도 함)과 받은 편지함 규칙에 적용되는 제한이 나와 있습니다. 받은 편지함 규칙은 개별 사용자에 의해 설정되어 개별 사용자 사서함에서 보내고 받는 메시지에 적용됩니다.

- **최대 저널 규칙 수**: 조직에 존재할 수 있는 최대 저널 규칙 수입니다.

- **최대 전송 규칙 수**: 조직에 존재할 수 있는 최대 규칙 수입니다.

- **개별 전송 규칙의 최대 크기**: 단일 전송 규칙에 사용할 수 있는 최대 문자 수입니다. 문자는 조건, 예외 및 작업에 사용됩니다.

- **모든 전송 규칙에 사용되는 모든 정규식에 대한 문자 제한**: 조직의 모든 전송 규칙 조건 및 예외의 모든 정규식을 포함하여 사용된 총 문자 수입니다. 길고 복잡한 정규식을 사용하는 몇 가지 규칙이 있거나 간단한 정규식을 사용하는 많은 규칙이 있을 수 있습니다.

- **첨부 파일 내용 검사 제한**: 이 전송 규칙 조건을 사용하여 메시지 첨부 파일의 내용을 검사할 수 있지만 첨부 파일에서 추출된 텍스트의 처음 1MB만 검사됩니다. 이 1MB 제한은 첨부 파일의 파일 크기가 아닌 첨부 파일에서 추출된 텍스트를 나타냅니다. 예를 들어 2MB 파일에는 1MB 미만의 텍스트가 포함되어 있을 수 있으므로 모든 텍스트가 검사됩니다.

- **모든 전송 규칙에 의해 메시지에 추가되는 받는 사람의 최대 수**: 여러 전송 규칙에 의해 메시지가 처리될 때 제한된 수의 받는 사람만 메시지에 추가될 수 있습니다. 제한에 도달하면 나머지 받는 사람은 메시지가 추가되지 않습니다. 메일 그룹도 전송 규칙에 의해 메시지에 추가될 수 없습니다.

- **전달받는 사람 제한**: 리디렉션 작업을 통해 받은 편지함 또는 전송 규칙에 대해 구성할 수 있는 최대 받는 사람 수입니다. 이 받는 사람 수보다 많은 사람에게 메시지를 리디렉션하도록 구성하는 규칙은 적용되지 않으며, 규칙 조건을 충족하는 메시지는 규칙에 나와 있는 받는 사람에게 리디렉션되지 않습니다.
    
- **메시지 리디렉션 횟수**: 받은 편지함 규칙을 기준으로 메시지를 자동으로 리디렉션, 전달 또는 회신할 횟수입니다. 보낸 사람을 기준으로 메시지를 사용자 B에게 리디렉션하는 받은 편지함 규칙이 사용자 A에게 적용되는 경우를 예로 들어 보겠습니다. 사용자 B의 경우에는 제목 줄의 키워드를 기준으로 메시지를 사용자 C에게 전달하는 받은 편지함 규칙이 적용됩니다. 이 두 조건을 모두 충족하는 메시지는 사용자 B에게만 발송됩니다. 리디렉션은 한 번만 허용되므로 사용자 C에게는 메시지가 전달되지 않습니다. 이 경우 사용자 C에게 메시지가 배달되지 않았음을 나타내는 NDR(배달 못 함 보고서)을 사용자 B에게 보내지 않고 메시지가 삭제됩니다. Microsoft는 X-MS-Exchange-Inbox-Rules-Loop 헤더를 사용합니다. 메시지가 리디렉션된 횟수를 확인합니다. 이 헤더는 Exchange 조직 경계에도 남아 있습니다.

- **전송 규칙에 따라 메시지가 리디렉션되는 횟수**: 전송 규칙에 따라 메시지가 리디렉션되는 횟수입니다. 예를 들어 Exchange 조직 Tailspin Toys에는 Exchange 조직 Contoso에 있는 사용자 A에게 전송된 모든 메시지를 사용자 B로 리디렉션하는 전송 규칙이 있습니다. Exchange 조직 Contoso 내에서 사용자 B에 전송된 모든 메시지를 Exchange 조직 A. Datum Corporation에 있는 사용자 C로 리디렉션하는 전송 규칙이 있습니다. 이 경우 메시지가 삭제되고 상태 코드 및 거부 메시지가 있는 NDR(전달 못 함 보고서) *550 5.7.128 TRANSPORT.RULES.RejectMessage; 전송 규칙 루프 수가 초과되고 메시지 거부됨* 이 사용자 A에게 전송됩니다. X-MS-Exchange-Transport-Rules-Loop 머리글을 사용하여 전송 규칙에 의해 메시지가 리디렉션된 횟수를 확인합니다. 이 머리글은 Exchange 조직 경계에도 남아 있습니다.

### <a name="journal-transport-and-inbox-rule-limits"></a>저널, 전송 및 받은 편지함 규칙 제한

| 기능 | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|최대 저널 규칙 수|300개 규칙|300개 규칙|300개 규칙|300개 규칙|300개 규칙|300개 규칙|
|최대 전송 규칙 수|300개 규칙|300개 규칙|300개 규칙|300개 규칙|300개 규칙|300개 규칙|
|개별 전송 규칙의 최대 크기|8KB|8KB|8KB|8KB|8KB|8KB|
|모든 전송 규칙에서 사용되는 모든 정규식의 문자 제한|20KB|20KB|20KB|20KB|20KB|20KB|
|첨부 파일 내용 검사 제한|1MB|1MB|1MB|1MB|1MB|1MB|
|모든 전송 규칙에 의해 메시지에 추가되는 최대 받는 사람 수|받는 사람 100명|받는 사람 100명|받는 사람 100명|받는 사람 100명|받는 사람 100명|받는 사람 100명|
|전달받는 사람 제한|받는 사람 10명|받는 사람 10명|받는 사람 10명|받는 사람 10명|받는 사람 10명|받는 사람 10명|
|메시지 리디렉션 횟수|리디렉션 1회|리디렉션 1회|리디렉션 1회|리디렉션 1회|리디렉션 1회|리디렉션 1회|
|전송 규칙에 따라 메시지가 리디렉션되는 횟수|리디렉션 1회|리디렉션 1회|리디렉션 1회|리디렉션 1회|리디렉션 1회|리디렉션 1회|
|메시지 리디렉션 횟수|리디렉션 1회|리디렉션 1회|리디렉션 1회|리디렉션 1회|리디렉션 1회|리디렉션 1회|
|받은 편지함 규칙|256kb<sup>1</sup>|256kb<sup>1</sup>|256kb<sup>1</sup>|256kb<sup>1</sup>|256kb<sup>1</sup>|256kb<sup>1</sup>|

> [!NOTE]
> <sup>1</sup> Exchange Online으로 마이그레이션된 경우 받은 편지함 규칙 제한이 기본 EXO 값보다 낮은 값으로 설정될 수 있습니다. 이 경우 받은 편지함 규칙 값을 늘어날 수 있습니다. 자세한 내용은 [Exchange Online에서 받은 편지함 규칙에 사용되는 공간 수정](/exchange/clients-and-mobile-in-exchange-online/outlook-on-the-web/increase-the-space-used-by-inbox-rules)을 참조하세요. 

### <a name="journal-transport-and-inbox-rule-limits-across-standalone-options"></a>독립 실행형 옵션별 저널, 전송 및 받은 편지함 규칙 제한

| 기능 | Exchange Server 2013 | Exchange Online 요금제 1 | Exchange Online 계획 2 | Exchange Online Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|최대 저널 규칙 수|제한 없음|50개 규칙|50개 규칙|50개 규칙|
|최대 전송 규칙 수|제한 없음|300개 규칙|300개 규칙|300개 규칙|
|개별 전송 규칙의 최대 크기|40 KB|8KB|8KB|8KB|
|모든 전송 규칙에서 사용되는 모든 정규식의 문자 제한|제한 없음|20KB|20KB|20KB|
|모든 전송 규칙에 의해 메시지에 추가되는 최대 받는 사람 수|제한 없음|받는 사람 100명|받는 사람 100명|받는 사람 100명|
|전달받는 사람 제한|제한 없음|받는 사람 10명|받는 사람 10명|받는 사람 10명|
|메시지 리디렉션 횟수|리디렉션 3회|리디렉션 1회|리디렉션 1회|리디렉션 1회|
|전송 규칙에 따라 메시지가 리디렉션되는 횟수|제한 없음|리디렉션 1회|리디렉션 1회|리디렉션 1회|

## <a name="moderation-limits"></a>중재 제한

다음 제한은 메일 그룹과 전송 규칙에 적용된 메시지 승인에 사용되는 중재 설정을 제어합니다.

- **중재 사서함의 최대 크기**: 중재 사서함이 이 제한을 초과하면 중재를 요구하는 메시지가 NDR(전달 못 함 보고서)과 함께 보낸 사람에게 반송됩니다.

- **최대 중재자 수**: 단일 전송 규칙을 사용하여 메시지에 추가할 수 있거나 중재된 단일 메일 그룹에 할당할 수 있는 최대 중재자 수입니다. 메일 그룹은 중재자로 지정할 수 없습니다.

- **중재 대기 중인 메시지의 만료**: 기본적으로 중재 대기 중인 메시지는 2일 후 만료됩니다. 그러니 만료된 중재된 메시지의 처리가 7일마다 실행되므로 2~9일 사이에 언제든지 중재된 메시지가 만료될 수 있습니다.

- **만료된 중재 알림 메시지의 최대 처리 속도**: 이 제한은 1시간 동안 만료된 중재된 메시지에 대한 최대 알림 메시지 수를 설정합니다. 데이터 센터의 각 사서함 데이터베이스에 이 제한이 적용됩니다.

사용량이 많은 기간에는 일부 보낸 사람이 만료된 중재된 메시지에 대한 알림 메시지를 받지 못할 수 있습니다. 그러나 배달 보고서에서 이러한 알림을 검색할 수 있습니다.

### <a name="moderation-limits"></a>중재 제한

| 기능 | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|중재 사서함의 최대 크기|10GB|10GB|10GB|10GB|10GB|10GB|
|최대 중재자 수|중재자 10명|중재자 10명|중재자 10명|중재자 10명|중재자 10명|중재자 10명|
|중재 대기 중인 메시지의 만료|2일|2일|2일|2일|2일|2일|
|만료된 중재 알림 메시지의 최대 처리 속도|시간당 만료 알림 300개|시간당 만료 알림 300개|시간당 만료 알림 300개|시간당 만료 알림 300개|시간당 만료 알림 300개|시간당 만료 알림 300개|

### <a name="moderation-limits-across-standalone-options"></a>독립 실행형 옵션별 중재 제한

| 기능 | Exchange Server 2013 | Exchange Online 요금제 1 | Exchange Online 계획 2 | Exchange Online Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|중재 사서함의 최대 크기|제한 없음<sup>1</sup>|10GB|10GB|10GB|
|최대 중재자 수|제한 없음|중재자 10명|중재자 10명|중재자 10명|
|중재 대기 중인 메시지의 만료|5일<sup>1</sup>|2일|2일|2일|
|만료된 중재 알림 메시지의 최대 처리 속도|시간당 만료 알림 300개|시간당 만료 알림 300개|시간당 만료 알림 300개|시간당 만료 알림 300개|

> [!NOTE]
> <sup>1</sup>Exchange Server 2013 조직의 기본 제한입니다. 관리자는 자신의 조직에 대한 이 값을 변경할 수 있습니다.

## <a name="exchange-activesync-limits"></a>Exchange ActiveSync 제한

모바일 장치와 Exchange 간에 사서함 데이터를 동기화하는 클라이언트 프로토콜인 Microsoft Exchange ActiveSync에 다음 제한이 적용됩니다.

- **Exchange ActiveSync 장치 제한**: 사서함당 최대 Exchange ActiveSync 장치 수입니다.

- **Exchange ActiveSync 장치 삭제 제한**: Exchange 관리자가 1달에 삭제할 수 있는 최대 Exchange ActiveSync 장치 수입니다.

### <a name="exchange-activesync-limits"></a>Exchange ActiveSync 제한

| 기능 | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Exchange ActiveSync 장치 제한|100|100|100|100|100|100|
|Exchange ActiveSync 장치 삭제 제한|20|20|20|20|20|20|

### <a name="exchange-activesync-limits-across-standalone-options"></a>독립 실행형 옵션에서 Exchange ActiveSync 제한

| 기능 | Exchange Server 2013 | Exchange Online 요금제 1 | Exchange Online 계획 2 | Exchange Online Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|Exchange ActiveSync 장치 제한|100|100|100|100|
|Exchange ActiveSync 장치 삭제 제한|20|20|20|20|