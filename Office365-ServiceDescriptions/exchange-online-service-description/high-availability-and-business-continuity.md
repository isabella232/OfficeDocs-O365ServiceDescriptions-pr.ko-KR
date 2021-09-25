---
title: 고가용성 및 비즈니스 연속성
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-high-availability-and-business-continuity
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
ms.assetid: 7b03465e-3b9c-4500-8956-a83377f4c2c3
description: Microsoft Exchange Online 조직의 전자 메일 인프라에 대한 광범위한 보존 및 복구 지원을 제공합니다. 여기에는 데이터 센터에서의 사서함 복제와 삭제된 사서함 및 삭제된 항목의 복원 기능이 포함됩니다.
ms.openlocfilehash: f856c0bce99fc119ad1498daaf355541d40aac86
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/24/2021
ms.locfileid: "59671989"
---
# <a name="high-availability-and-business-continuity"></a>고가용성 및 비즈니스 연속성

Microsoft Exchange Online 조직의 전자 메일 인프라에 대한 광범위한 보존 및 복구 지원을 제공합니다. 여기에는 데이터 센터에서의 사서함 복제와 삭제된 사서함 및 삭제된 항목의 복원 기능이 포함됩니다.
  
## <a name="mailbox-replication-at-data-centers"></a>데이터 센터에서 사서함 복제

Exchange Online 사서함은 로컬 메시징 인프라에 오류가 발생했을 때 데이터를 복원할 수 있도록 지리적으로 분산된 Microsoft 데이터 센터에서 여러 데이터베이스 복사본으로 지속적으로 복제됩니다. 대규모 오류인 경우 서비스 연속성 관리 절차가 시작됩니다.
  
Microsoft의 데이터 보호 방식에 대한 자세한 내용은 [Office 365 보안 센터](https://go.microsoft.com/fwlink/p/?LinkId=299135)를 참조하세요. 21Vianet에서 운영하는 Office 365를 사용 중인 경우 [21Vianet 보안 센터](https://www.21vbluecloud.com/office365/trustcenter/onlineservices.mdl)를 참조하세요.
  
## <a name="deleted-mailbox-recovery"></a>삭제된 사서함 복구

관리자는 Exchange Online 사서함을 삭제하거나 Microsoft 365 관리 센터 사용자 계정을 삭제하거나 Exchange Online 라이선스를 제거하거나 원격 사서함에서 **Remove-Mailbox** cmdlet을 사용하여 사서함을 삭제할 수 Windows PowerShell. 사서함이 삭제되면 Exchange Online 사서함 및 해당 콘텐츠는 기본적으로 30일 동안 보존됩니다. 30일이 지난 후 사서함을 복구할 수 없습니다. 복구된 사서함에는 삭제 당시에 저장된 모든 데이터가 포함되어 있습니다. 관리자는 보존 기간 내에 삭제된 사서함을 복구할 수 Microsoft 365 관리 센터. 삭제된 사서함을 복구하려면 관리자는 해당 사용자 계정을 복원하거나 사용자 계정에 Exchange Online 라이선스를 다시 배정해야 합니다. 자세한 내용은 [Delete or Restore User Mailboxes in Exchange Online.](/exchange/recipients-in-exchange-online/delete-or-restore-mailboxes)
  
## <a name="deleted-item-recovery"></a>삭제된 항목 복구

Exchange Online 폴더를 포함하여 모든 전자 메일 폴더에서 삭제한 항목을 복원할 수 있습니다. 항목이 삭제되면 사용자의 지우기 항목 폴더에 보관됩니다. 사용자가 수동으로 제거하거나 보존 정책에 의해 자동으로 제거될 때까지 이 상태로 남아 있습니다. 관리자는 EAC에서 또는 원격 전자 메일 관리자를 사용하여 보존 정책을 사용자 지정할 Windows PowerShell.
  
지운 편지함 폴더에서 제거된 항목은 휴지통 폴더에서 14일 동안 보관되었다가 영구적으로 제거되지만 관리자는 원격 Windows PowerShell을 사용하여 이 기간을 최대 30일까지 연장할 수 있습니다. 사용자는 이 기간 동안 항목의 삭제된 항목 복구 기능을 사용하여 복구할 수 웹용 Outlook Outlook. [삭제된 항목 보존 기간 변경](/exchange/recipients-in-exchange-online/manage-user-mailboxes/change-deleted-item-retention) 방법을 알아보세요.
  
사용자가 휴지통 폴더에서 항목을 수동으로 제거한 경우 관리자는 원격 Windows PowerShell을 사용하는 단일 항목 복구 기능을 통해 그와 동일한 기간 내에 항목을 복구할 수 있습니다. 기본적으로 사서함을 만들 때 단일 항목 복구는 사용하도록 설정됩니다. 자세한 내용은 [사서함에 대해 단일 항목 복구를 사용하거나 사용하지 않도록 설정](/exchange/recipients-in-exchange-online/manage-user-mailboxes/enable-or-disable-single-item-recovery)을 참조하세요.
  
30일보다 오랫동안 복구 가능한 항목 폴더에 메시지를 보존하려는 조직에서는 장기 전자 메일 보존 또는 시간 기반 원본 위치 유지를 구현할 수 있습니다. [사서함을 원본 위치 유지 상태로 설정](/exchange/security-and-compliance/in-place-and-litigation-holds)하는 방법을 알아보세요.
  
## <a name="feature-availability"></a>기능 가용성

계획, 독립 실행형 옵션 및온-프레미스 솔루션에서 기능 가용성을 확인한 경우 서비스 [Exchange Online 참조하세요.](exchange-online-service-description.md)
