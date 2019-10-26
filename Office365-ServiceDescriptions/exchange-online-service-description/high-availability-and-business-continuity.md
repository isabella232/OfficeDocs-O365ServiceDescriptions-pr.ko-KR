---
title: 고가용성 및 비즈니스 연속성
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-high-availability-and-business-continuity
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7b03465e-3b9c-4500-8956-a83377f4c2c3
description: Microsoft Exchange Online에서는 조직의 전자 메일 인프라에 대 한 광범위 한 보존 및 복구 지원을 제공 합니다. 여기에는 데이터 센터에서의 사서함 복제와 삭제된 사서함 및 삭제된 항목의 복원 기능이 포함됩니다.
ms.openlocfilehash: aad8576e35af04eb819d9f5809f1862613298651
ms.sourcegitcommit: fb245074a57da585566096f6956d37325f451262
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/26/2019
ms.locfileid: "37734246"
---
# <a name="high-availability-and-business-continuity"></a><span data-ttu-id="d42a4-104">고가용성 및 비즈니스 연속성</span><span class="sxs-lookup"><span data-stu-id="d42a4-104">High availability and business continuity</span></span>

<span data-ttu-id="d42a4-105">Microsoft Exchange Online에서는 조직의 전자 메일 인프라에 대 한 광범위 한 보존 및 복구 지원을 제공 합니다.</span><span class="sxs-lookup"><span data-stu-id="d42a4-105">Microsoft Exchange Online offers extensive retention and recovery support for an organization's email infrastructure.</span></span> <span data-ttu-id="d42a4-106">여기에는 데이터 센터에서의 사서함 복제와 삭제된 사서함 및 삭제된 항목의 복원 기능이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="d42a4-106">This includes mailbox replication at data centers and the ability to restore deleted mailboxes and deleted items.</span></span>
  
## <a name="mailbox-replication-at-data-centers"></a><span data-ttu-id="d42a4-107">데이터 센터에서 사서함 복제</span><span class="sxs-lookup"><span data-stu-id="d42a4-107">Mailbox replication at data centers</span></span>

<span data-ttu-id="d42a4-p103">Exchange Online 사서함은 로컬 메시징 인프라에 오류가 발생했을 때 데이터를 복원할 수 있도록 지리적으로 분산된 Microsoft 데이터 센터에서 여러 데이터베이스 복사본으로 지속적으로 복제됩니다. 대규모 오류인 경우 서비스 연속성 관리 절차가 시작됩니다.</span><span class="sxs-lookup"><span data-stu-id="d42a4-p103">Exchange Online mailboxes are continuously replicated to multiple database copies, in geographically dispersed Microsoft data centers, to provide data restoration capability in the event of a local messaging infrastructure failure. For large-scale failures, service continuity management procedures are initiated.</span></span>
  
<span data-ttu-id="d42a4-p104">Microsoft의 데이터 보호 방식에 대한 자세한 내용은 [Office 365 보안 센터](https://go.microsoft.com/fwlink/p/?LinkId=299135)를 참조하세요. 21Vianet에서 운영하는 Office 365를 사용 중인 경우 [21Vianet 보안 센터](https://www.21vbluecloud.com/office365/trustcenter/onlineservices.mdl)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="d42a4-p104">For more information about how Microsoft protects your data, see [Office 365 Trust Center](https://go.microsoft.com/fwlink/p/?LinkId=299135). If you are using Office 365 operated by 21Vianet, see the [21Vianet Trust Center](https://www.21vbluecloud.com/office365/trustcenter/onlineservices.mdl).</span></span>
  
## <a name="deleted-mailbox-recovery"></a><span data-ttu-id="d42a4-112">삭제된 사서함 복구</span><span class="sxs-lookup"><span data-stu-id="d42a4-112">Deleted mailbox recovery</span></span>

<span data-ttu-id="d42a4-113">관리자는 Microsoft 365 관리 센터를 사용 하 여 해당 사용자 계정을 삭제 하거나, Exchange Online 라이선스를 제거 하거나, 원격 Windows PowerShell의 **사서함 제거** cmdlet을 사용 하 여 exchange online 사서함을 삭제할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d42a4-113">Administrators can delete Exchange Online mailboxes by using the Microsoft 365 admin center to delete the corresponding user account or remove the Exchange Online license, or by using the **Remove-Mailbox** cmdlet in remote Windows PowerShell.</span></span> <span data-ttu-id="d42a4-114">사서함이 삭제 되 면 Exchange Online은 기본적으로 30 일 동안 사서함과 해당 콘텐츠를 보존 합니다.</span><span class="sxs-lookup"><span data-stu-id="d42a4-114">When a mailbox is deleted, Exchange Online retains the mailbox and its contents for 30 days by default.</span></span> <span data-ttu-id="d42a4-115">30 일 후에는 사서함을 복구할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="d42a4-115">After 30 days, the mailbox is not recoverable.</span></span> <span data-ttu-id="d42a4-116">복구 된 사서함에는 삭제 당시에 저장 된 모든 데이터가 포함 됩니다.</span><span class="sxs-lookup"><span data-stu-id="d42a4-116">A recovered mailbox contains all of the data stored in it at the time it was deleted.</span></span> <span data-ttu-id="d42a4-117">관리자는 Microsoft 365 관리 센터를 사용 하 여 보존 기간 내에 삭제 된 사서함을 복구할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d42a4-117">Administrators can recover a deleted mailbox within the retention period by using the Microsoft 365 admin center.</span></span> <span data-ttu-id="d42a4-118">삭제 된 사서함을 복구 하기 위해 관리자는 해당 하는 Office 365 사용자 계정을 복원 하거나 사용자 계정에 Exchange Online 라이선스를 다시 할당 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="d42a4-118">To recover a deleted mailbox, administrators have to restore the corresponding Office 365 user account or reassign an Exchange Online license to the user account.</span></span> <span data-ttu-id="d42a4-119">자세한 내용은 [Exchange Online에서 사용자 사서함 삭제 또는 복원을](https://go.microsoft.com/fwlink/p/?LinkId=286992)참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="d42a4-119">For more information, see [Delete or Restore User Mailboxes in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=286992).</span></span>
  
## <a name="deleted-item-recovery"></a><span data-ttu-id="d42a4-120">삭제된 항목 복구</span><span class="sxs-lookup"><span data-stu-id="d42a4-120">Deleted item recovery</span></span>

<span data-ttu-id="d42a4-121">Exchange Online에서는 사용자가 지운 편지함 폴더를 포함 하 여 모든 전자 메일 폴더에서 삭제 한 항목을 복원할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d42a4-121">Exchange Online lets users restore items they have deleted from any email folder, including the Deleted Items folder.</span></span> <span data-ttu-id="d42a4-122">삭제 된 항목은 사용자의 지운 편지함 폴더에 보관 됩니다.</span><span class="sxs-lookup"><span data-stu-id="d42a4-122">When an item is deleted, it's kept in a user's Deleted Items folder.</span></span> <span data-ttu-id="d42a4-123">사용자가 수동으로 제거 하거나 보존 정책에 따라 자동으로 제거 될 때까지 유지 됩니다.</span><span class="sxs-lookup"><span data-stu-id="d42a4-123">It remains there until it's either manually removed by the user or automatically removed by retention policies.</span></span> <span data-ttu-id="d42a4-124">관리자는 EAC 또는 원격 Windows PowerShell을 사용 하 여 보존 정책을 사용자 지정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d42a4-124">Administrators can customize retention policies in the EAC or by using remote Windows PowerShell.</span></span>
  
<span data-ttu-id="d42a4-125">지운 편지함 폴더에서 제거된 항목은 휴지통 폴더에서 14일 동안 보관되었다가 영구적으로 제거되지만 관리자는 원격 Windows PowerShell을 사용하여 이 기간을 최대 30일까지 연장할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d42a4-125">After an item has been removed from the Deleted Items folder, it's kept in a Recoverable Items folder for an additional 14 days before being permanently removed, but administrators can increase this to a maximum of 30 days by using remote Windows PowerShell.</span></span> <span data-ttu-id="d42a4-126">사용자는이 기간 동안 웹 이나 Outlook에서 Outlook의 삭제 된 항목 복구 기능을 사용 하 여 항목을 복구할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d42a4-126">Users can recover the item during this time period by using the Recover Deleted Items feature in Outlook on the web or Outlook.</span></span> <span data-ttu-id="d42a4-127">[삭제된 항목 보존 기간 변경](https://go.microsoft.com/fwlink/p/?LinkId=286940) 방법을 알아보세요.</span><span class="sxs-lookup"><span data-stu-id="d42a4-127">Learn how to [change the deleted item retention period](https://go.microsoft.com/fwlink/p/?LinkId=286940).</span></span>
  
<span data-ttu-id="d42a4-p108">사용자가 휴지통 폴더에서 항목을 수동으로 제거한 경우 관리자는 원격 Windows PowerShell을 사용하는 단일 항목 복구 기능을 통해 그와 동일한 기간 내에 항목을 복구할 수 있습니다. 기본적으로 사서함을 만들 때 단일 항목 복구는 사용하도록 설정됩니다. 자세한 내용은 [사서함에 대해 단일 항목 복구를 사용하거나 사용하지 않도록 설정](https://go.microsoft.com/fwlink/p/?LinkID=286941)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="d42a4-p108">If a user has manually purged an item from the Recoverable Items folder, an administrator can recover the item within the same time period by using the Single Item Recovery feature with remote Windows PowerShell. By default, Single Item Recovery is enabled when a mailbox is created. To learn more, see [Enable or disable single item recovery for a mailbox](https://go.microsoft.com/fwlink/p/?LinkID=286941).</span></span>
  
<span data-ttu-id="d42a4-p109">30일보다 오랫동안 복구 가능한 항목 폴더에 메시지를 보존하려는 조직에서는 장기 전자 메일 보존 또는 시간 기반 원본 위치 유지를 구현할 수 있습니다. [사서함을 원본 위치 유지 상태로 설정](https://go.microsoft.com/fwlink/p/?LinkId=271746)하는 방법을 알아보세요.</span><span class="sxs-lookup"><span data-stu-id="d42a4-p109">To preserve messages for longer than 30 days in the Recoverable Items folder, organizations can implement longer-term email preservation or time-based In-Place Holds. Learn more about [placing a mailbox on In-Place Hold](https://go.microsoft.com/fwlink/p/?LinkId=271746).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="d42a4-133">기능 가용성</span><span class="sxs-lookup"><span data-stu-id="d42a4-133">Feature availability</span></span>

<span data-ttu-id="d42a4-134">Office 365 계획, 독립 실행형 옵션 및 온-프레미스 솔루션 별로 기능 가용성을 확인 하려면 [Exchange Online 서비스 설명을](exchange-online-service-description.md)참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="d42a4-134">To view feature availability across Office 365 plans, standalone options, and on-premises solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  