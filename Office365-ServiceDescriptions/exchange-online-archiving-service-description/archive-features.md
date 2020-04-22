---
title: Exchange Online 보관의 보관 기능
ms.author: sharik
author: skjerland
manager: mnirkhe
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
ms.openlocfilehash: cc4b6cb6f0aa817f3b0369f2bf3517fd480a11e8
ms.sourcegitcommit: 7a68dc894dde0d06fab014c56914a78aa8cda847
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/21/2020
ms.locfileid: "43639837"
---
# <a name="archive-features-in-exchange-online-archiving"></a><span data-ttu-id="9ed98-103">Exchange Online 보관의 보관 기능</span><span class="sxs-lookup"><span data-stu-id="9ed98-103">Archive features in Exchange Online Archiving</span></span>

<span data-ttu-id="9ed98-104">다음 섹션에서는 Microsoft Exchange Online 보관의 보관 기능에 대해 설명 합니다.</span><span class="sxs-lookup"><span data-stu-id="9ed98-104">The following sections describe the archive features of Microsoft Exchange Online Archiving.</span></span>
  
## <a name="archive-mailbox"></a><span data-ttu-id="9ed98-105">보관 사서함</span><span class="sxs-lookup"><span data-stu-id="9ed98-105">Archive mailbox</span></span>

<span data-ttu-id="9ed98-106">Exchange Online Archiving에서는 보관 사서함 기능과 함께 고급 보관 기능을 사용자에게 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="9ed98-106">Exchange Online Archiving offers users advanced archiving capabilities with the archive mailbox feature.</span></span> <span data-ttu-id="9ed98-107">보관 사서함은 Outlook 또는 웹용 Outlook에서 사용자의 기본 사서함 폴더 옆에 표시 되는 특수 한 사서함입니다.</span><span class="sxs-lookup"><span data-stu-id="9ed98-107">An archive mailbox is a specialized mailbox that appears alongside the users' primary mailbox folders in Outlook or Outlook on the web.</span></span> <span data-ttu-id="9ed98-108">사용자는 기본 사서함에 액세스하는 방법으로 보관 사서함에도 액세스할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="9ed98-108">Users can access the archive in the same way that they access their primary mailboxes.</span></span> <span data-ttu-id="9ed98-109">또한 보관 사서함과 기본 사서함을 모두 검색할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="9ed98-109">In addition, they can search both their archives and primary mailboxes.</span></span>
  
<span data-ttu-id="9ed98-p102">관리자는 EAC(Exchange 관리 센터)나 원격 Windows PowerShell을 통해 특정 사용자가 보관 기능을 사용하도록 설정할 수 있습니다. 자세한 내용은 [Exchange Online의 보관 사서함을 사용하거나 사용하지 않도록 설정](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="9ed98-p102">Administrators can use the Exchange admin center (EAC) or remote Windows PowerShell to enable the archive feature for specific users. For more information, see [Enable or disable archive mailboxes in Exchange Online](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes).</span></span>
  
> [!IMPORTANT]
>  <span data-ttu-id="9ed98-112">보관 목적으로 저널링, 전송 규칙 또는 자동 전달 규칙을 사용하여 Exchange Online Archiving에 메시지를 복사할 수는 없습니다.</span><span class="sxs-lookup"><span data-stu-id="9ed98-112">Using journaling, transport rules, or auto-forwarding rules to copy messages to Exchange Online Archiving for the purposes of archiving is not permitted.</span></span> <br/>
>  <span data-ttu-id="9ed98-113">사용자의 보관 사서함은 해당 사용자만을 위한 것입니다.</span><span class="sxs-lookup"><span data-stu-id="9ed98-113">A user's archive mailbox is intended for just that user.</span></span> <span data-ttu-id="9ed98-114">Microsoft는 사용자의 보관 사서함이 다른 사용자의 보관 데이터를 저장 하는 데 사용 되거나 부적절 하 게 사용 되는 경우를 제외 하 고 무제한 보관을 거부할 수 있는 권한을 보유 합니다.</span><span class="sxs-lookup"><span data-stu-id="9ed98-114">Microsoft reserves the right to deny unlimited archiving in instances where a user's archive mailbox is used to store archive data for other users or in other cases of inappropriate use.</span></span>
  
### <a name="move-messages-to-exchange-online-archiving"></a><span data-ttu-id="9ed98-115">Exchange Online Archiving으로 메시지 이동</span><span class="sxs-lookup"><span data-stu-id="9ed98-115">Move messages to Exchange Online Archiving</span></span>

<span data-ttu-id="9ed98-116">사용자는 온라인에서 간편하게 액세스하기 위해 .pst 파일에서 메시지를 끌어 보관 사서함에 놓을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="9ed98-116">Users can drag and drop messages from .pst files into the archive, for easy online access.</span></span> <span data-ttu-id="9ed98-117">또한 보관 정책을 사용하여 전자 메일 항목을 자동으로 기본 사서함에서 보관 사서함으로 이동해서, 기본 사서함의 크기를 줄이고 성능을 개선할 수도 있습니다.</span><span class="sxs-lookup"><span data-stu-id="9ed98-117">Users can also move email items from the primary mailbox to the archive mailbox automatically, using Archive Polices, to reduce the size and improve the performance of the primary mailbox.</span></span> 
  
### <a name="import-data-to-the-archive"></a><span data-ttu-id="9ed98-118">보관 사서함으로 데이터 가져오기</span><span class="sxs-lookup"><span data-stu-id="9ed98-118">Import data to the archive</span></span>

<span data-ttu-id="9ed98-119">사용자는 다음과 같은 방법으로 보관 사서함에 데이터를 가져올 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="9ed98-119">Users can import data to the archive in the following ways:</span></span>
  
- <span data-ttu-id="9ed98-120">Outlook의 가져오기 및 내보내기 마법사를 사용하여 .pst 파일에서 데이터를 가져옵니다.</span><span class="sxs-lookup"><span data-stu-id="9ed98-120">Import data from a .pst file using Outlook's Import and Export wizard.</span></span>
    
- <span data-ttu-id="9ed98-121">전자 메일 메시지를 .pst 파일에서 보관 사서함으로 끕니다.</span><span class="sxs-lookup"><span data-stu-id="9ed98-121">Drag email messages from .pst files into the archive.</span></span>
    
- <span data-ttu-id="9ed98-122">기본 사서함에서 보관 사서함으로 전자 메일 메시지를 끌어 놓습니다.</span><span class="sxs-lookup"><span data-stu-id="9ed98-122">Drag email messages from the primary mailbox into the archive.</span></span>
    
- <span data-ttu-id="9ed98-p106">메시지가 기본 사서함에 보관된 기간을 기준으로 기본 사서함의 전자 메일 메시지를 자동으로 이동하도록 보관 정책을 설정합니다. 자세한 내용은 [보존 태그 및 보존 정책](https://docs.microsoft.com/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="9ed98-p106">Let archive policies automatically move email messages from the primary mailbox, based on the age of the messages. For more information, see [Retention Tags and Retention Policies](https://docs.microsoft.com/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies).</span></span>
    
> [!NOTE]
> <span data-ttu-id="9ed98-p107">관리자는 Office 365 가져오기 서비스를 사용하여 .pst 파일을 사용자의 클라우드 기반 보관 사서함에 가져올 수도 있습니다. 자세한 내용은 [네트워크 업로드를 사용하여 PST 파일을 Office 365에 가져오기](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="9ed98-p107">Administrators can also use Office 365 Import service to import .pst files to users' cloud-based archive mailboxes. For more information, see [Use network upload to import PST files to Office 365](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files).</span></span> 
  
## <a name="deleted-item-recovery"></a><span data-ttu-id="9ed98-127">삭제된 항목 복구</span><span class="sxs-lookup"><span data-stu-id="9ed98-127">Deleted item recovery</span></span>

<span data-ttu-id="9ed98-p108">사용자는 전자 메일 폴더에서 삭제된 항목을 보관 사서함에서 복원할 수 있습니다. 삭제된 항목은 보관 사서함의 지운 편지함 폴더에 보관되고, 사용자가 수동으로 제거하거나 보존 정책에 따라 자동으로 제거될 때까지 해당 폴더에 보관됩니다.</span><span class="sxs-lookup"><span data-stu-id="9ed98-p108">Users can restore items they have deleted from any email folder in their archive. When an item is deleted, it is kept in the archive's Deleted Items folder. It remains there until it is manually removed by the user, or automatically removed by retention policies.</span></span>
  
<span data-ttu-id="9ed98-131">보관 사서함의 지운 편지함 폴더에서 제거된 항목은 보관 사서함의 복구 가능한 항목 폴더에서 14일 동안 더 보관되었다가 영구적으로 제거됩니다.</span><span class="sxs-lookup"><span data-stu-id="9ed98-131">After an item has been removed from the archive's Deleted Items folder, the item is kept in the archive's Recoverable Items folder for an additional 14 days before being permanently removed.</span></span> <span data-ttu-id="9ed98-132">사용자는 Microsoft Outlook 또는 웹용 Outlook에서 **삭제 된 항목 복구** 기능을 사용 하 여 이러한 항목을 복구할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="9ed98-132">Users can recover these items using the **Recover Deleted Items** feature in Microsoft Outlook or Outlook on the web.</span></span> 
  
<span data-ttu-id="9ed98-p110">사용자가 복구 가능한 항목 폴더에서 항목을 수동으로 제거한 경우 관리자는 단일 항목 복구라는 기능을 사용하여 같은 기간(14일) 내에 항목을 복구할 수 있습니다. 관리자는 이 기능을 통해 여러 사서함 검색을 수행하여 제거된 항목을 찾은 다음  `Search-Mailbox` Windows PowerShell cmdlet을 사용해 검색 사서함에서 사용자 사서함으로 항목을 이동할 수 있습니다. 자세한 내용은 [사서함에 대한 단일 항목을 사용하거나 사용하지 않도록 설정](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="9ed98-p110">If a user has manually purged an item from the Recoverable Items folder, an administrator can recover the item within the same 14 day window, through a feature called Single Item Recovery. This feature allows administrators to conduct a multi-mailbox search to find purged items and then use the  `Search-Mailbox` Windows PowerShell cmdlet to move the items from the discovery mailbox to users' mailboxes. For more information, see [Enable or disable single item recovery for a mailbox](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files).</span></span>
  
> [!NOTE]
>  <span data-ttu-id="9ed98-136">단일 항목 복구 기간은 기본적으로 14일이지만 경우에 따라 사용자가 지정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="9ed98-136">The Single Item Recovery period is 14 days by default, but it can be customized in some circumstances.</span></span> <br/>
>  <span data-ttu-id="9ed98-137">관리자가 사용자의 사서함에 원본 위치 유지 또는 소송 보존을 적용 한 경우 제거 된 항목은 무기한 유지 되 고, 14 일 동안 지속 되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="9ed98-137">If an administrator has placed a user's mailbox on In-Place Hold or Litigation Hold, purged items are retained indefinitely and the 14-day window does not apply.</span></span> 
  
## <a name="deleted-mailbox-recovery"></a><span data-ttu-id="9ed98-138">삭제된 사서함 복구</span><span class="sxs-lookup"><span data-stu-id="9ed98-138">Deleted mailbox recovery</span></span>

<span data-ttu-id="9ed98-139">관리자가 사용자를 온-프레미스 Exchange Server에서 삭제하면 해당 사용자의 보관 사서함도 삭제됩니다.</span><span class="sxs-lookup"><span data-stu-id="9ed98-139">When administrators delete users from the on-premises Exchange Server, the users' archives are also deleted.</span></span> <span data-ttu-id="9ed98-140">삭제 된 보관 사서함을 복구 해야 하는 경우 Microsoft 지원 팀에서이 복구를 수행할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="9ed98-140">If the deleted archive mailboxes need to be recovered, the Microsoft support team can perform this recovery.</span></span> <span data-ttu-id="9ed98-141">복구된 보관 사서함에는 삭제 당시에 저장되어 있던 모든 메일이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="9ed98-141">A recovered archive will contain all of the mail stored in it at the time it was deleted.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="9ed98-p113">관리자는 사용자 사서함이 삭제된 시점부터 30일 동안 보관 사서함의 복구를 요청할 수 있습니다. 30일 후에는 보관 사서함을 복구할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="9ed98-p113">Administrators have 30 days from the time a user's mailbox is deleted to request an archive mailbox recovery. After 30 days, the archive mailbox is not recoverable.</span></span> 
  
## <a name="mailbox-service-redundancy"></a><span data-ttu-id="9ed98-144">사서함 서비스 중복</span><span class="sxs-lookup"><span data-stu-id="9ed98-144">Mailbox service redundancy</span></span>

<span data-ttu-id="9ed98-145">Exchange Online Archiving의 보관 사서함은 메시징 인프라에 오류가 발생했을 때 데이터를 복원할 수 있도록 지리적으로 분산된 Microsoft 데이터 센터에서 여러 데이터베이스 복사본으로 복제됩니다.</span><span class="sxs-lookup"><span data-stu-id="9ed98-145">Archive mailboxes in Exchange Online Archiving are replicated to multiple database copies, in geographically dispersed Microsoft data centers, to provide data restoration capability in the event of a messaging infrastructure failure.</span></span> <span data-ttu-id="9ed98-146">대규모 오류인 경우 비즈니스 연속성 관리가 시작됩니다.</span><span class="sxs-lookup"><span data-stu-id="9ed98-146">For large-scale failures, business continuity management is initiated.</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="9ed98-147">기능 가용성</span><span class="sxs-lookup"><span data-stu-id="9ed98-147">Feature availability</span></span>

<span data-ttu-id="9ed98-148">계획, 독립 실행형 옵션 및 온-프레미스 솔루션 별로 기능 가용성을 확인 하려면 [Exchange Online 보관 서비스 설명을](exchange-online-archiving-service-description.md)참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="9ed98-148">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online Archiving service description](exchange-online-archiving-service-description.md).</span></span>
  
