---
title: 보관 기능의 Exchange Online Archiving
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
description: 보관에서 사용할 수 있는 보관 기능에 Microsoft Exchange Online 대해 자세히 알아보습니다.
ms.openlocfilehash: 5abc6ed09d96b952439232a4c8ac091d2dccd07d
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173523"
---
# <a name="archive-features-in-exchange-online-archiving"></a><span data-ttu-id="89eca-103">보관 기능의 Exchange Online Archiving</span><span class="sxs-lookup"><span data-stu-id="89eca-103">Archive features in Exchange Online Archiving</span></span>

<span data-ttu-id="89eca-104">다음 섹션에서는 보관의 보관 Microsoft Exchange Online 설명합니다.</span><span class="sxs-lookup"><span data-stu-id="89eca-104">The following sections describe the archive features of Microsoft Exchange Online Archiving.</span></span>
  
## <a name="archive-mailbox"></a><span data-ttu-id="89eca-105">보관 사서함</span><span class="sxs-lookup"><span data-stu-id="89eca-105">Archive mailbox</span></span>

<span data-ttu-id="89eca-106">Exchange Online Archiving에서는 보관 사서함 기능과 함께 고급 보관 기능을 사용자에게 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="89eca-106">Exchange Online Archiving offers users advanced archiving capabilities with the archive mailbox feature.</span></span> <span data-ttu-id="89eca-107">보관 사서함은 Outlook 또는 웹용 Outlook에서 사용자의 기본 사서함 폴더와 함께 나타나는 특수한 사서함입니다.</span><span class="sxs-lookup"><span data-stu-id="89eca-107">An archive mailbox is a specialized mailbox that appears alongside the users' primary mailbox folders in Outlook or Outlook on the web.</span></span> <span data-ttu-id="89eca-108">사용자는 기본 사서함에 액세스하는 방법으로 보관 사서함에도 액세스할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="89eca-108">Users can access the archive in the same way that they access their primary mailboxes.</span></span> <span data-ttu-id="89eca-109">또한 보관 사서함과 기본 사서함을 모두 검색할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="89eca-109">In addition, they can search both their archives and primary mailboxes.</span></span>
  
<span data-ttu-id="89eca-p102">관리자는 EAC(Exchange 관리 센터)나 원격 Windows PowerShell을 통해 특정 사용자가 보관 기능을 사용하도록 설정할 수 있습니다. 자세한 내용은 [Exchange Online의 보관 사서함을 사용하거나 사용하지 않도록 설정](/office365/securitycompliance/enable-archive-mailboxes)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="89eca-p102">Administrators can use the Exchange admin center (EAC) or remote Windows PowerShell to enable the archive feature for specific users. For more information, see [Enable or disable archive mailboxes in Exchange Online](/office365/securitycompliance/enable-archive-mailboxes).</span></span>
  
> [!IMPORTANT]
>  <span data-ttu-id="89eca-112">보관 목적으로 저널링, 전송 규칙 또는 자동 전달 규칙을 사용하여 Exchange Online Archiving에 메시지를 복사할 수는 없습니다.</span><span class="sxs-lookup"><span data-stu-id="89eca-112">Using journaling, transport rules, or auto-forwarding rules to copy messages to Exchange Online Archiving for the purposes of archiving is not permitted.</span></span> <br/>
>  <span data-ttu-id="89eca-113">사용자의 보관 사서함은 해당 사용자만을 위한 것입니다.</span><span class="sxs-lookup"><span data-stu-id="89eca-113">A user's archive mailbox is intended for just that user.</span></span> <span data-ttu-id="89eca-114">Microsoft는 사용자의 보관 사서함이 다른 사용자의 보관 데이터를 저장하는 데 사용되는 경우 또는 부적절한 사용이 있는 경우 무제한 보관을 거부할 권리가 있습니다.</span><span class="sxs-lookup"><span data-stu-id="89eca-114">Microsoft reserves the right to deny unlimited archiving in instances where a user's archive mailbox is used to store archive data for other users or in other cases of inappropriate use.</span></span>
  
### <a name="move-messages-to-exchange-online-archiving"></a><span data-ttu-id="89eca-115">Exchange Online Archiving으로 메시지 이동</span><span class="sxs-lookup"><span data-stu-id="89eca-115">Move messages to Exchange Online Archiving</span></span>

<span data-ttu-id="89eca-116">사용자는 온라인에서 간편하게 액세스하기 위해 .pst 파일에서 메시지를 끌어 보관 사서함에 놓을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="89eca-116">Users can drag and drop messages from .pst files into the archive, for easy online access.</span></span> <span data-ttu-id="89eca-117">또한 보관 정책을 사용하여 전자 메일 항목을 자동으로 기본 사서함에서 보관 사서함으로 이동해서, 기본 사서함의 크기를 줄이고 성능을 개선할 수도 있습니다.</span><span class="sxs-lookup"><span data-stu-id="89eca-117">Users can also move email items from the primary mailbox to the archive mailbox automatically, using Archive Polices, to reduce the size and improve the performance of the primary mailbox.</span></span> 
  
### <a name="import-data-to-the-archive"></a><span data-ttu-id="89eca-118">보관 사서함으로 데이터 가져오기</span><span class="sxs-lookup"><span data-stu-id="89eca-118">Import data to the archive</span></span>

<span data-ttu-id="89eca-119">사용자는 다음과 같은 방법으로 보관 사서함에 데이터를 가져올 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="89eca-119">Users can import data to the archive in the following ways:</span></span>
  
- <span data-ttu-id="89eca-120">Outlook의 가져오기 및 내보내기 마법사를 사용하여 .pst 파일에서 데이터를 가져옵니다.</span><span class="sxs-lookup"><span data-stu-id="89eca-120">Import data from a .pst file using Outlook's Import and Export wizard.</span></span>
    
- <span data-ttu-id="89eca-121">전자 메일 메시지를 .pst 파일에서 보관 사서함으로 끕니다.</span><span class="sxs-lookup"><span data-stu-id="89eca-121">Drag email messages from .pst files into the archive.</span></span>
    
- <span data-ttu-id="89eca-122">기본 사서함에서 보관 사서함으로 전자 메일 메시지를 끌어 놓습니다.</span><span class="sxs-lookup"><span data-stu-id="89eca-122">Drag email messages from the primary mailbox into the archive.</span></span>
    
- <span data-ttu-id="89eca-p106">메시지가 기본 사서함에 보관된 기간을 기준으로 기본 사서함의 전자 메일 메시지를 자동으로 이동하도록 보관 정책을 설정합니다. 자세한 내용은 [보존 태그 및 보존 정책](/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="89eca-p106">Let archive policies automatically move email messages from the primary mailbox, based on the age of the messages. For more information, see [Retention Tags and Retention Policies](/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies).</span></span>
    
> [!NOTE]
> <span data-ttu-id="89eca-p107">관리자는 Office 365 가져오기 서비스를 사용하여 .pst 파일을 사용자의 클라우드 기반 보관 사서함에 가져올 수도 있습니다. 자세한 내용은 [네트워크 업로드를 사용하여 PST 파일을 Office 365에 가져오기](/office365/securitycompliance/use-network-upload-to-import-pst-files)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="89eca-p107">Administrators can also use Office 365 Import service to import .pst files to users' cloud-based archive mailboxes. For more information, see [Use network upload to import PST files to Office 365](/office365/securitycompliance/use-network-upload-to-import-pst-files).</span></span> 
  
## <a name="deleted-item-recovery"></a><span data-ttu-id="89eca-127">삭제된 항목 복구</span><span class="sxs-lookup"><span data-stu-id="89eca-127">Deleted item recovery</span></span>

<span data-ttu-id="89eca-p108">사용자는 전자 메일 폴더에서 삭제된 항목을 보관 사서함에서 복원할 수 있습니다. 삭제된 항목은 보관 사서함의 지운 편지함 폴더에 보관되고, 사용자가 수동으로 제거하거나 보존 정책에 따라 자동으로 제거될 때까지 해당 폴더에 보관됩니다.</span><span class="sxs-lookup"><span data-stu-id="89eca-p108">Users can restore items they have deleted from any email folder in their archive. When an item is deleted, it is kept in the archive's Deleted Items folder. It remains there until it is manually removed by the user, or automatically removed by retention policies.</span></span>
  
<span data-ttu-id="89eca-131">보관 사서함의 지운 편지함 폴더에서 제거된 항목은 보관 사서함의 복구 가능한 항목 폴더에서 14일 동안 더 보관되었다가 영구적으로 제거됩니다.</span><span class="sxs-lookup"><span data-stu-id="89eca-131">After an item has been removed from the archive's Deleted Items folder, the item is kept in the archive's Recoverable Items folder for an additional 14 days before being permanently removed.</span></span> <span data-ttu-id="89eca-132">사용자는 Microsoft Outlook 또는  웹용 Outlook에서 지우기 항목 복구 기능을 사용하여 이러한 항목을 복구할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="89eca-132">Users can recover these items using the **Recover Deleted Items** feature in Microsoft Outlook or Outlook on the web.</span></span> 
  
<span data-ttu-id="89eca-p110">사용자가 복구 가능한 항목 폴더에서 항목을 수동으로 제거한 경우 관리자는 단일 항목 복구라는 기능을 사용하여 같은 기간(14일) 내에 항목을 복구할 수 있습니다. 관리자는 이 기능을 통해 여러 사서함 검색을 수행하여 제거된 항목을 찾은 다음  `Search-Mailbox` Windows PowerShell cmdlet을 사용해 검색 사서함에서 사용자 사서함으로 항목을 이동할 수 있습니다. 자세한 내용은 [사서함에 대한 단일 항목을 사용하거나 사용하지 않도록 설정](/office365/securitycompliance/use-network-upload-to-import-pst-files)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="89eca-p110">If a user has manually purged an item from the Recoverable Items folder, an administrator can recover the item within the same 14 day window, through a feature called Single Item Recovery. This feature allows administrators to conduct a multi-mailbox search to find purged items and then use the  `Search-Mailbox` Windows PowerShell cmdlet to move the items from the discovery mailbox to users' mailboxes. For more information, see [Enable or disable single item recovery for a mailbox](/office365/securitycompliance/use-network-upload-to-import-pst-files).</span></span>
  
> [!NOTE]
>  <span data-ttu-id="89eca-136">단일 항목 복구 기간은 기본적으로 14일이지만 경우에 따라 사용자가 지정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="89eca-136">The Single Item Recovery period is 14 days by default, but it can be customized in some circumstances.</span></span> <br/>
>  <span data-ttu-id="89eca-137">관리자가 사용자의 사서함을 In-Place 보존 또는 소송 보존으로 설정한 경우 제거된 항목은 무기한 보존되고 14일 기간이 적용되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="89eca-137">If an administrator has placed a user's mailbox on In-Place Hold or Litigation Hold, purged items are retained indefinitely and the 14-day window does not apply.</span></span> 
  
## <a name="deleted-mailbox-recovery"></a><span data-ttu-id="89eca-138">삭제된 사서함 복구</span><span class="sxs-lookup"><span data-stu-id="89eca-138">Deleted mailbox recovery</span></span>

<span data-ttu-id="89eca-139">관리자가 사용자를 온-프레미스 Exchange Server에서 삭제하면 해당 사용자의 보관 사서함도 삭제됩니다.</span><span class="sxs-lookup"><span data-stu-id="89eca-139">When administrators delete users from the on-premises Exchange Server, the users' archives are also deleted.</span></span> <span data-ttu-id="89eca-140">삭제된 보관 사서함을 복구해야 하는 경우 Microsoft 지원 팀에서 이 복구를 수행할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="89eca-140">If the deleted archive mailboxes need to be recovered, the Microsoft support team can perform this recovery.</span></span> <span data-ttu-id="89eca-141">복구된 보관 사서함에는 삭제 당시에 저장되어 있던 모든 메일이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="89eca-141">A recovered archive will contain all of the mail stored in it at the time it was deleted.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="89eca-p113">관리자는 사용자 사서함이 삭제된 시점부터 30일 동안 보관 사서함의 복구를 요청할 수 있습니다. 30일 후에는 보관 사서함을 복구할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="89eca-p113">Administrators have 30 days from the time a user's mailbox is deleted to request an archive mailbox recovery. After 30 days, the archive mailbox is not recoverable.</span></span> 
  
## <a name="mailbox-service-redundancy"></a><span data-ttu-id="89eca-144">사서함 서비스 중복</span><span class="sxs-lookup"><span data-stu-id="89eca-144">Mailbox service redundancy</span></span>

<span data-ttu-id="89eca-145">Exchange Online Archiving의 보관 사서함은 메시징 인프라에 오류가 발생했을 때 데이터를 복원할 수 있도록 지리적으로 분산된 Microsoft 데이터 센터에서 여러 데이터베이스 복사본으로 복제됩니다.</span><span class="sxs-lookup"><span data-stu-id="89eca-145">Archive mailboxes in Exchange Online Archiving are replicated to multiple database copies, in geographically dispersed Microsoft data centers, to provide data restoration capability in the event of a messaging infrastructure failure.</span></span> <span data-ttu-id="89eca-146">대규모 오류인 경우 비즈니스 연속성 관리가 시작됩니다.</span><span class="sxs-lookup"><span data-stu-id="89eca-146">For large-scale failures, business continuity management is initiated.</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="89eca-147">기능 가용성</span><span class="sxs-lookup"><span data-stu-id="89eca-147">Feature availability</span></span>

<span data-ttu-id="89eca-148">계획, 독립 실행형 옵션 및 사내 솔루션에서 기능 가용성을 확인한 경우 Exchange Online Archiving [설명을 참조하세요.](exchange-online-archiving-service-description.md)</span><span class="sxs-lookup"><span data-stu-id="89eca-148">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online Archiving service description](exchange-online-archiving-service-description.md).</span></span>
