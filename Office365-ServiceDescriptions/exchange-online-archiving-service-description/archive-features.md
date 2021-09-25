---
title: 보관 기능의 Exchange Online Archiving
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- archive-features-in-exchange-online-archiving
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 38abfbd2-5aaa-444a-a431-5e71c566f3e4
description: 보관에서 사용할 수 있는 보관 기능에 Microsoft Exchange Online 대해 자세히 알아보습니다.
ms.openlocfilehash: 6f342899722b3d411c9eb0f45ef40237ca05bc9f
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/24/2021
ms.locfileid: "59670870"
---
# <a name="archive-features-in-exchange-online-archiving"></a>보관 기능의 Exchange Online Archiving

다음 섹션에서는 보관의 보관 Microsoft Exchange Online 설명합니다.
  
## <a name="archive-mailbox"></a>보관 사서함

Exchange Online Archiving에서는 보관 사서함 기능과 함께 고급 보관 기능을 사용자에게 제공합니다. 보관 사서함은 사서함 또는 사서함의 기본 사서함 폴더와 함께 나타나는 특수한 Outlook 웹용 Outlook. 사용자는 기본 사서함에 액세스하는 방법으로 보관 사서함에도 액세스할 수 있습니다. 또한 보관 사서함과 기본 사서함을 모두 검색할 수 있습니다.
  
관리자는 EAC(Exchange 관리 센터)나 원격 Windows PowerShell을 통해 특정 사용자가 보관 기능을 사용하도록 설정할 수 있습니다. 자세한 내용은 [Exchange Online의 보관 사서함을 사용하거나 사용하지 않도록 설정](/office365/securitycompliance/enable-archive-mailboxes)을 참조하세요.
  
> [!IMPORTANT]
>  보관 목적으로 저널링, 전송 규칙 또는 자동 전달 규칙을 사용하여 Exchange Online Archiving에 메시지를 복사할 수는 없습니다.<br/>
>  사용자의 보관 사서함은 해당 사용자만을 위한 것입니다. Microsoft는 사용자의 보관 사서함이 다른 사용자의 보관 데이터를 저장하는 데 사용되는 경우 또는 부적절한 사용이 있는 경우 무제한 보관을 거부할 권리가 있습니다.
  
### <a name="move-messages-to-exchange-online-archiving"></a>Exchange Online Archiving으로 메시지 이동

사용자는 온라인에서 간편하게 액세스하기 위해 .pst 파일에서 메시지를 끌어 보관 사서함에 놓을 수 있습니다. 또한 보관 정책을 사용하여 전자 메일 항목을 자동으로 기본 사서함에서 보관 사서함으로 이동해서, 기본 사서함의 크기를 줄이고 성능을 개선할 수도 있습니다. 
  
### <a name="import-data-to-the-archive"></a>보관 사서함으로 데이터 가져오기

사용자는 다음과 같은 방법으로 보관 사서함에 데이터를 가져올 수 있습니다.
  
- Outlook의 가져오기 및 내보내기 마법사를 사용하여 .pst 파일에서 데이터를 가져옵니다.
    
- 전자 메일 메시지를 .pst 파일에서 보관 사서함으로 끕니다.
    
- 기본 사서함에서 보관 사서함으로 전자 메일 메시지를 끌어 놓습니다.
    
- 메시지가 기본 사서함에 보관된 기간을 기준으로 기본 사서함의 전자 메일 메시지를 자동으로 이동하도록 보관 정책을 설정합니다. 자세한 내용은 [보존 태그 및 보존 정책](/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies)을 참조하세요.
    
> [!NOTE]
> 관리자는 Office 365 가져오기 서비스를 사용하여 .pst 파일을 사용자의 클라우드 기반 보관 사서함에 가져올 수도 있습니다. 자세한 내용은 [네트워크 업로드를 사용하여 PST 파일을 Office 365에 가져오기](/office365/securitycompliance/use-network-upload-to-import-pst-files)를 참조하세요. 
  
## <a name="deleted-item-recovery"></a>삭제된 항목 복구

사용자는 전자 메일 폴더에서 삭제된 항목을 보관 사서함에서 복원할 수 있습니다. 삭제된 항목은 보관 사서함의 지운 편지함 폴더에 보관되고, 사용자가 수동으로 제거하거나 보존 정책에 따라 자동으로 제거될 때까지 해당 폴더에 보관됩니다.
  
보관 사서함의 지운 편지함 폴더에서 제거된 항목은 보관 사서함의 복구 가능한 항목 폴더에서 14일 동안 더 보관되었다가 영구적으로 제거됩니다. 사용자는 Microsoft 365 또는 2013에서 지우기 항목 복구 기능을 사용하여 Outlook 수 웹용 Outlook.  
  
사용자가 복구 가능한 항목 폴더에서 항목을 수동으로 제거한 경우 관리자는 단일 항목 복구라는 기능을 사용하여 같은 기간(14일) 내에 항목을 복구할 수 있습니다. 관리자는 이 기능을 통해 여러 사서함 검색을 수행하여 제거된 항목을 찾은 다음  `Search-Mailbox` Windows PowerShell cmdlet을 사용해 검색 사서함에서 사용자 사서함으로 항목을 이동할 수 있습니다. 자세한 내용은 [사서함에 대한 단일 항목을 사용하거나 사용하지 않도록 설정](/office365/securitycompliance/use-network-upload-to-import-pst-files)을 참조하세요.
  
> [!NOTE]
>  단일 항목 복구 기간은 기본적으로 14일이지만 경우에 따라 사용자가 지정할 수 있습니다.<br/>
>  관리자가 사용자의 사서함을 In-Place 보존 또는 소송 보존으로 설정한 경우 제거된 항목은 무기한 보존되고 14일 기간이 적용되지 않습니다. 
  
## <a name="deleted-mailbox-recovery"></a>삭제된 사서함 복구

관리자가 사용자를 온-프레미스 Exchange Server에서 삭제하면 해당 사용자의 보관 사서함도 삭제됩니다. 삭제된 보관 사서함을 복구해야 하는 경우 Microsoft 지원 팀에서 이 복구를 수행할 수 있습니다. 복구된 보관 사서함에는 삭제 당시에 저장되어 있던 모든 메일이 포함됩니다.
  
> [!IMPORTANT]
> 관리자는 사용자 사서함이 삭제된 시점부터 30일 동안 보관 사서함의 복구를 요청할 수 있습니다. 30일 후에는 보관 사서함을 복구할 수 없습니다. 
  
## <a name="mailbox-service-redundancy"></a>사서함 서비스 중복

Exchange Online Archiving의 보관 사서함은 메시징 인프라에 오류가 발생했을 때 데이터를 복원할 수 있도록 지리적으로 분산된 Microsoft 데이터 센터에서 여러 데이터베이스 복사본으로 복제됩니다. 대규모 오류인 경우 비즈니스 연속성 관리가 시작됩니다. 
  
## <a name="feature-availability"></a>기능 가용성

계획, 독립 실행형 옵션 및온-프레미스 솔루션에 대한 기능 가용성을 확인하면 Exchange Online Archiving [설명을 참조하세요.](exchange-online-archiving-service-description.md)
