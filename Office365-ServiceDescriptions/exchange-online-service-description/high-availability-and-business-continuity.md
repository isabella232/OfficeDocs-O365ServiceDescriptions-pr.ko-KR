---
title: 고가용성 및 비즈니스 연속성
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-high-availability-and-business-continuity
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7b03465e-3b9c-4500-8956-a83377f4c2c3
description: Microsoft Exchange Online에서는 조직의 전자 메일 인프라에 대 한 광범위 한 보존 및 복구 지원을 제공 합니다. 여기에는 데이터 센터에서의 사서함 복제와 삭제된 사서함 및 삭제된 항목의 복원 기능이 포함됩니다.
ms.openlocfilehash: 395977f77d4293d18c5cf53e02d43566ca9f7313
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45131972"
---
# <a name="high-availability-and-business-continuity"></a>고가용성 및 비즈니스 연속성

Microsoft Exchange Online에서는 조직의 전자 메일 인프라에 대 한 광범위 한 보존 및 복구 지원을 제공 합니다. 여기에는 데이터 센터에서의 사서함 복제와 삭제된 사서함 및 삭제된 항목의 복원 기능이 포함됩니다.
  
## <a name="mailbox-replication-at-data-centers"></a>데이터 센터에서 사서함 복제

Exchange Online mailboxes are continuously replicated to multiple database copies, in geographically dispersed Microsoft data centers, to provide data restoration capability in the event of a local messaging infrastructure failure. For large-scale failures, service continuity management procedures are initiated.
  
For more information about how Microsoft protects your data, see [Office 365 Trust Center](https://go.microsoft.com/fwlink/p/?LinkId=299135). If you are using Office 365 operated by 21Vianet, see the [21Vianet Trust Center](https://www.21vbluecloud.com/office365/trustcenter/onlineservices.mdl).
  
## <a name="deleted-mailbox-recovery"></a>삭제된 사서함 복구

관리자는 Microsoft 365 관리 센터를 사용 하 여 해당 사용자 계정을 삭제 하거나, Exchange Online 라이선스를 제거 하거나, 원격 Windows PowerShell의 **사서함 제거** cmdlet을 사용 하 여 exchange online 사서함을 삭제할 수 있습니다. 사서함이 삭제 되 면 Exchange Online은 기본적으로 30 일 동안 사서함과 해당 콘텐츠를 보존 합니다. 30 일 후에는 사서함을 복구할 수 없습니다. 복구 된 사서함에는 삭제 당시에 저장 된 모든 데이터가 포함 됩니다. 관리자는 Microsoft 365 관리 센터를 사용 하 여 보존 기간 내에 삭제 된 사서함을 복구할 수 있습니다. 삭제 된 사서함을 복구 하기 위해 관리자는 해당 사용자 계정을 복원 하거나 사용자 계정에 Exchange Online 라이선스를 다시 할당 해야 합니다. 자세한 내용은 [Exchange Online에서 사용자 사서함 삭제 또는 복원을](https://go.microsoft.com/fwlink/p/?LinkId=286992)참조 하세요.
  
## <a name="deleted-item-recovery"></a>삭제된 항목 복구

Exchange Online에서는 사용자가 지운 편지함 폴더를 포함 하 여 모든 전자 메일 폴더에서 삭제 한 항목을 복원할 수 있습니다. 삭제 된 항목은 사용자의 지운 편지함 폴더에 보관 됩니다. 사용자가 수동으로 제거 하거나 보존 정책에 따라 자동으로 제거 될 때까지 유지 됩니다. 관리자는 EAC 또는 원격 Windows PowerShell을 사용 하 여 보존 정책을 사용자 지정할 수 있습니다.
  
지운 편지함 폴더에서 제거된 항목은 휴지통 폴더에서 14일 동안 보관되었다가 영구적으로 제거되지만 관리자는 원격 Windows PowerShell을 사용하여 이 기간을 최대 30일까지 연장할 수 있습니다. 사용자는이 기간 동안 웹 이나 Outlook에서 Outlook의 삭제 된 항목 복구 기능을 사용 하 여 항목을 복구할 수 있습니다. [삭제된 항목 보존 기간 변경](https://go.microsoft.com/fwlink/p/?LinkId=286940) 방법을 알아보세요.
  
If a user has manually purged an item from the Recoverable Items folder, an administrator can recover the item within the same time period by using the Single Item Recovery feature with remote Windows PowerShell. By default, Single Item Recovery is enabled when a mailbox is created. To learn more, see [Enable or disable single item recovery for a mailbox](https://go.microsoft.com/fwlink/p/?LinkID=286941).
  
To preserve messages for longer than 30 days in the Recoverable Items folder, organizations can implement longer-term email preservation or time-based In-Place Holds. Learn more about [placing a mailbox on In-Place Hold](https://go.microsoft.com/fwlink/p/?LinkId=271746).
  
## <a name="feature-availability"></a>기능 가용성

계획, 독립 실행형 옵션 및 온-프레미스 솔루션 별로 기능 가용성을 확인 하려면 [Exchange Online 서비스 설명을](exchange-online-service-description.md)참조 하세요.
  