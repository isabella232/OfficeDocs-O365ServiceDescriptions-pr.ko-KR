---
title: Exchange Online 보관의 보관 기능
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- archive-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 38abfbd2-5aaa-444a-a431-5e71c566f3e4
description: 다음 섹션에서는 Microsoft Exchange Online 보관의 보관 기능에 대해 설명 합니다.
ms.openlocfilehash: 7f6b5863d94862644fb90d1d0d85c3765ad05e9b
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45131532"
---
# <a name="archive-features-in-exchange-online-archiving"></a>Exchange Online 보관의 보관 기능

다음 섹션에서는 Microsoft Exchange Online 보관의 보관 기능에 대해 설명 합니다.
  
## <a name="archive-mailbox"></a>보관 사서함

Exchange Online Archiving에서는 보관 사서함 기능과 함께 고급 보관 기능을 사용자에게 제공합니다. 보관 사서함은 Outlook 또는 웹용 Outlook에서 사용자의 기본 사서함 폴더 옆에 표시 되는 특수 한 사서함입니다. 사용자는 기본 사서함에 액세스하는 방법으로 보관 사서함에도 액세스할 수 있습니다. 또한 보관 사서함과 기본 사서함을 모두 검색할 수 있습니다.
  
Administrators can use the Exchange admin center (EAC) or remote Windows PowerShell to enable the archive feature for specific users. For more information, see [Enable or disable archive mailboxes in Exchange Online](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes).
  
> [!IMPORTANT]
>  보관 목적으로 저널링, 전송 규칙 또는 자동 전달 규칙을 사용하여 Exchange Online Archiving에 메시지를 복사할 수는 없습니다. <br/>
>  사용자의 보관 사서함은 해당 사용자만을 위한 것입니다. Microsoft는 사용자의 보관 사서함이 다른 사용자의 보관 데이터를 저장 하는 데 사용 되거나 부적절 하 게 사용 되는 경우를 제외 하 고 무제한 보관을 거부할 수 있는 권한을 보유 합니다.
  
### <a name="move-messages-to-exchange-online-archiving"></a>Exchange Online Archiving으로 메시지 이동

사용자는 온라인에서 간편하게 액세스하기 위해 .pst 파일에서 메시지를 끌어 보관 사서함에 놓을 수 있습니다. 또한 보관 정책을 사용하여 전자 메일 항목을 자동으로 기본 사서함에서 보관 사서함으로 이동해서, 기본 사서함의 크기를 줄이고 성능을 개선할 수도 있습니다. 
  
### <a name="import-data-to-the-archive"></a>보관 사서함으로 데이터 가져오기

사용자는 다음과 같은 방법으로 보관 사서함에 데이터를 가져올 수 있습니다.
  
- Outlook의 가져오기 및 내보내기 마법사를 사용하여 .pst 파일에서 데이터를 가져옵니다.
    
- 전자 메일 메시지를 .pst 파일에서 보관 사서함으로 끕니다.
    
- 기본 사서함에서 보관 사서함으로 전자 메일 메시지를 끌어 놓습니다.
    
- Let archive policies automatically move email messages from the primary mailbox, based on the age of the messages. For more information, see [Retention Tags and Retention Policies](https://docs.microsoft.com/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies).
    
> [!NOTE]
> Administrators can also use Office 365 Import service to import .pst files to users' cloud-based archive mailboxes. For more information, see [Use network upload to import PST files to Office 365](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files). 
  
## <a name="deleted-item-recovery"></a>삭제된 항목 복구

Users can restore items they have deleted from any email folder in their archive. When an item is deleted, it is kept in the archive's Deleted Items folder. It remains there until it is manually removed by the user, or automatically removed by retention policies.
  
보관 사서함의 지운 편지함 폴더에서 제거된 항목은 보관 사서함의 복구 가능한 항목 폴더에서 14일 동안 더 보관되었다가 영구적으로 제거됩니다. 사용자는 Microsoft Outlook 또는 웹용 Outlook에서 **삭제 된 항목 복구** 기능을 사용 하 여 이러한 항목을 복구할 수 있습니다. 
  
If a user has manually purged an item from the Recoverable Items folder, an administrator can recover the item within the same 14 day window, through a feature called Single Item Recovery. This feature allows administrators to conduct a multi-mailbox search to find purged items and then use the  `Search-Mailbox` Windows PowerShell cmdlet to move the items from the discovery mailbox to users' mailboxes. For more information, see [Enable or disable single item recovery for a mailbox](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files).
  
> [!NOTE]
>  단일 항목 복구 기간은 기본적으로 14일이지만 경우에 따라 사용자가 지정할 수 있습니다. <br/>
>  관리자가 사용자의 사서함에 원본 위치 유지 또는 소송 보존을 적용 한 경우 제거 된 항목은 무기한 유지 되 고, 14 일 동안 지속 되지 않습니다. 
  
## <a name="deleted-mailbox-recovery"></a>삭제된 사서함 복구

관리자가 사용자를 온-프레미스 Exchange Server에서 삭제하면 해당 사용자의 보관 사서함도 삭제됩니다. 삭제 된 보관 사서함을 복구 해야 하는 경우 Microsoft 지원 팀에서이 복구를 수행할 수 있습니다. 복구된 보관 사서함에는 삭제 당시에 저장되어 있던 모든 메일이 포함됩니다.
  
> [!IMPORTANT]
> Administrators have 30 days from the time a user's mailbox is deleted to request an archive mailbox recovery. After 30 days, the archive mailbox is not recoverable. 
  
## <a name="mailbox-service-redundancy"></a>사서함 서비스 중복

Exchange Online Archiving의 보관 사서함은 메시징 인프라에 오류가 발생했을 때 데이터를 복원할 수 있도록 지리적으로 분산된 Microsoft 데이터 센터에서 여러 데이터베이스 복사본으로 복제됩니다. 대규모 오류인 경우 비즈니스 연속성 관리가 시작됩니다. 
  
## <a name="feature-availability"></a>기능 가용성

계획, 독립 실행형 옵션 및 온-프레미스 솔루션 별로 기능 가용성을 확인 하려면 [Exchange Online 보관 서비스 설명을](exchange-online-archiving-service-description.md)참조 하세요.
  
