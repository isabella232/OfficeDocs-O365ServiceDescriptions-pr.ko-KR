---
title: 받는 사람, 도메인 및 회사 관리
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- recipient-domain-and-company-management-features-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 10812b48-7df5-47e9-b643-dbc3c85d7de0
description: Microsoft EOP (Exchange Online Protection)에서는 받는 사람, 도메인 및 회사 정보를 관리 하는 여러 가지 방법을 제공 합니다. 관리자는 EAC (Exchange 관리 센터) 내에서 특정 관리 작업을 수행 하 고 Microsoft 365 관리 센터에서 수행 된 기타 관리 작업을 확인할 수 있습니다.
ms.openlocfilehash: 4a2d2d091a6170e0606702a4a8047a21ad57ac11
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132772"
---
# <a name="recipient-domain-and-company-management"></a><span data-ttu-id="32183-104">받는 사람, 도메인 및 회사 관리</span><span class="sxs-lookup"><span data-stu-id="32183-104">Recipient, domain, and company management</span></span>

<span data-ttu-id="32183-105">Microsoft EOP (Exchange Online Protection)에서는 받는 사람, 도메인 및 회사 정보를 관리 하는 여러 가지 방법을 제공 합니다.</span><span class="sxs-lookup"><span data-stu-id="32183-105">Microsoft Exchange Online Protection (EOP) offers several means of managing your recipient, domain, and company information.</span></span> <span data-ttu-id="32183-106">관리자는 EAC (Exchange 관리 센터) 내에서 특정 관리 작업을 수행 하 고 Microsoft 365 관리 센터에서 수행 된 기타 관리 작업을 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="32183-106">As an administrator, you can perform certain management tasks within the Exchange admin center (EAC), and verify other management tasks performed in the Microsoft 365 admin center.</span></span>
  
<span data-ttu-id="32183-107">모든 EOP 기능에 대 한 정보를 찾으십니까?</span><span class="sxs-lookup"><span data-stu-id="32183-107">Looking for information about all EOP features?</span></span> <span data-ttu-id="32183-108">[Exchange Online Protection 서비스 설명을](exchange-online-protection-service-description.md)참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="32183-108">See the [Exchange Online Protection service description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="mail-recipients"></a><span data-ttu-id="32183-109">Mail recipients</span><span class="sxs-lookup"><span data-stu-id="32183-109">Mail recipients</span></span>

<span data-ttu-id="32183-110">메일 받는 사람은 메일 사용자 또는 그룹으로 분류되며 디렉터리 동기화를 통해하거나 EAC에서 직접 또는 원격 Windows PowerShell을 통해 관리할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="32183-110">Mail recipients are categorized as mail users or groups and can be managed through directory synchronization, directly in the EAC, or via remote Windows PowerShell.</span></span> <span data-ttu-id="32183-111">온-프레미스에서 받는 사람을 관리하는 경우 EAC에 메일 받는 사람이 반영되도록 디렉터리 동기화를 실행해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="32183-111">If you're managing your recipients on-premises, you must run directory synchronization in order for your mail recipients to be reflected in the EAC.</span></span> <span data-ttu-id="32183-112">Microsoft 365 관리 센터 에서만 관리 되는 사용자는 EAC에서 볼 수 없지만 EAC에서 관리자 역할 그룹의 구성원 자격에 게 추가 되거나 제거 될 수도 있습니다.</span><span class="sxs-lookup"><span data-stu-id="32183-112">Users managed solely in the Microsoft 365 admin center aren't viewable in the EAC, but they can be added to or removed from membership in an administrator role group in the EAC.</span></span> <span data-ttu-id="32183-113">EOP의 받는 사람에 대한 자세한 내용은 [EOP의 받는 사람](https://go.microsoft.com/fwlink/p/?LinkId=280011)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="32183-113">For more information about recipients in EOP, see [Recipients in EOP](https://go.microsoft.com/fwlink/p/?LinkId=280011).</span></span>
  
## <a name="admin-role-group-permissions"></a><span data-ttu-id="32183-114">Admin role group permissions</span><span class="sxs-lookup"><span data-stu-id="32183-114">Admin role group permissions</span></span>

<span data-ttu-id="32183-p105">EOP에서는 관리자 역할만 구성할 수 있습니다. EAC에서 직접 사용자를 기본 관리자 역할 그룹에 추가하거나 그룹에서 제거할 수 있습니다. RBAC는 사용자 지정할 수 없습니다. 자세한 내용은 [EOP에서 관리자 역할 그룹 권한 관리](https://go.microsoft.com/fwlink/p/?LinkId=282238)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="32183-p105">In EOP, you can configure administrative roles only. Users can be added and removed from default admin role groups directly in the EAC. No RBAC customization is available. For more information, see [Manage Admin Role Group Permissions in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282238).</span></span>
  
## <a name="domain-management"></a><span data-ttu-id="32183-119">도메인 관리</span><span class="sxs-lookup"><span data-stu-id="32183-119">Domain management</span></span>

<span data-ttu-id="32183-120">관리되는 도메인은 EOP의 보호를 받는 도메인입니다.</span><span class="sxs-lookup"><span data-stu-id="32183-120">Managed domains are domains that are protected by EOP.</span></span> <span data-ttu-id="32183-121">EAC에서는 관리되는 도메인을 볼 수 있고 도메인 유형을 편집할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="32183-121">Managed domains can be viewed and domain types can be edited in the EAC.</span></span> <span data-ttu-id="32183-122">도메인 프로 비전 및 관리는 Microsoft 365 관리 센터에서 수행 되며 변경 내용은 EAC에 반영 됩니다.</span><span class="sxs-lookup"><span data-stu-id="32183-122">Domain provisioning and management occurs in the Microsoft 365 admin center and changes are reflected in the EAC.</span></span> <span data-ttu-id="32183-123">자세한 내용은 [EOP에서 관리되는 도메인 보기 또는 편집](https://go.microsoft.com/fwlink/p/?LinkId=282239)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="32183-123">For more information, see [View or Edit Managed Domains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).</span></span>
  
## <a name="match-subdomains"></a><span data-ttu-id="32183-124">하위 도메인 일치</span><span class="sxs-lookup"><span data-stu-id="32183-124">Match subdomains</span></span>

<span data-ttu-id="32183-p107">EOP에서는 관리되는 도메인의 하위 도메인에 대한 메일 흐름을 사용하도록 설정할 수 있습니다. 자세한 내용은 [EOP에서 하위 도메인에 대해 전자 메일 흐름 사용](https://go.microsoft.com/fwlink/p/?LinkId=397213)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="32183-p107">In EOP, you can enable mail flow to subdomains of a managed domain. For more information, see [Enable Email Flow for Subdomains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=397213).</span></span> 
  
## <a name="directory-based-edge-blocking-dbeb"></a><span data-ttu-id="32183-127">DBEB(디렉터리 기반 Edge 차단)</span><span class="sxs-lookup"><span data-stu-id="32183-127">Directory Based Edge Blocking (DBEB)</span></span>

<span data-ttu-id="32183-128">디렉터리 기반 Edge 차단 기능을 사용하면 서비스 네트워크 경계에서 잘못된 받는 사람의 메시지를 거부할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="32183-128">The Directory Based Edge Blocking feature lets you reject messages for invalid recipients at the service network perimeter.</span></span> <span data-ttu-id="32183-129">DBEB를 사용 하면 관리자가 메일 사용이 가능한 받는 사람을 Microsoft에 추가 하 고 Microsoft에 제공 되지 않은 전자 메일 주소로 전송 된 모든 메시지를 차단할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="32183-129">DBEB lets admins add mail-enabled recipients to Microsoft and block all messages sent to email addresses that aren't present in Microsoft.</span></span> <span data-ttu-id="32183-130">Microsoft에 있는 유효한 전자 메일 주소로 메시지가 전송 되는 경우 해당 메시지는 나머지 서비스 필터링 계층 (맬웨어 방지, 스팸 방지, 전송 규칙)을 통해 계속 진행 됩니다.</span><span class="sxs-lookup"><span data-stu-id="32183-130">If a message is sent to a valid email address present in Microsoft, the message continues through the rest of the service filtering layers (anti-malware, anti-spam, transport rules).</span></span> <span data-ttu-id="32183-131">주소가 없는 경우 필터링이 이루어지기 전에 서비스에서 메시지가 차단되고, 메시지가 배달되지 않았음을 알리는 NDR(배달 못 함 보고서)이 보낸 사람에게 보냅니다.</span><span class="sxs-lookup"><span data-stu-id="32183-131">If the address is not present, the service blocks the message before filtering even occurs, and a non-delivery report (NDR) is sent to the sender informing them that their message was not delivered.</span></span> 
  
<span data-ttu-id="32183-p109">DBEB를 사용하려면 일부 사용자 및 도메인 구성이 필요합니다. 자세한 내용은 [디렉터리 기반 Edge 차단을 사용하여 잘못된 받는 사람에게 전송된 메시지 거부](https://go.microsoft.com/fwlink/p/?LinkId=390676)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="32183-p109">Enabling DBEB requires some user and domain configuration. For more information, see [Use Directory Based Edge Blocking to Reject Messages Sent to Invalid Recipients](https://go.microsoft.com/fwlink/p/?LinkId=390676).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="32183-134">기능 가용성</span><span class="sxs-lookup"><span data-stu-id="32183-134">Feature availability</span></span>

<span data-ttu-id="32183-135">계획, 독립 실행형 옵션 및 온-프레미스 솔루션 별로 기능 가용성을 확인 하려면 [Exchange Online Protection 서비스 설명을](exchange-online-protection-service-description.md)참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="32183-135">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online Protection service description](exchange-online-protection-service-description.md).</span></span>
