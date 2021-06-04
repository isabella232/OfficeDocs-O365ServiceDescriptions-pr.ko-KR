---
title: 사용자 계정의 받는 사람, 도메인 및 Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- recipient-domain-and-company-management-features-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 10812b48-7df5-47e9-b643-dbc3c85d7de0
description: 이 문서를 읽고 EOP(Microsoft Exchange Online 보호)의 받는 사람, 도메인 및 회사 관리에 대해 자세히 알아보습니다.
ms.openlocfilehash: f58ffe829be839d8321cfc98f331d1836986e293
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653000"
---
# <a name="recipient-domain-and-company-management-in-exchange-online-protection"></a><span data-ttu-id="e6c93-103">사용자 계정의 받는 사람, 도메인 및 Exchange Online Protection</span><span class="sxs-lookup"><span data-stu-id="e6c93-103">Recipient, domain, and company management in Exchange Online Protection</span></span>

<span data-ttu-id="e6c93-104">Microsoft Exchange Online EOP(보호)는 받는 사람, 도메인 및 회사 정보를 관리하는 여러 가지 방법을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="e6c93-104">Microsoft Exchange Online Protection (EOP) offers several means of managing your recipient, domain, and company information.</span></span> <span data-ttu-id="e6c93-105">관리자는 EAC(Exchange 관리 센터) 내에서 특정 관리 작업을 수행하고 Microsoft 365 관리 센터에서 수행되는 기타 관리 작업을 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e6c93-105">As an administrator, you can perform certain management tasks within the Exchange admin center (EAC), and verify other management tasks performed in the Microsoft 365 admin center.</span></span>
  
<span data-ttu-id="e6c93-106">모든 EOP 기능에 대한 정보를 찾고 있나요?</span><span class="sxs-lookup"><span data-stu-id="e6c93-106">Looking for information about all EOP features?</span></span> <span data-ttu-id="e6c93-107">자세한 [내용은 Exchange Online Protection 설명을 참조하세요.](exchange-online-protection-service-description.md)</span><span class="sxs-lookup"><span data-stu-id="e6c93-107">See the [Exchange Online Protection service description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="mail-recipients"></a><span data-ttu-id="e6c93-108">Mail recipients</span><span class="sxs-lookup"><span data-stu-id="e6c93-108">Mail recipients</span></span>

<span data-ttu-id="e6c93-109">메일 받는 사람은 메일 사용자 또는 그룹으로 분류되며 디렉터리 동기화를 통해하거나 EAC에서 직접 또는 원격 Windows PowerShell을 통해 관리할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e6c93-109">Mail recipients are categorized as mail users or groups and can be managed through directory synchronization, directly in the EAC, or via remote Windows PowerShell.</span></span> <span data-ttu-id="e6c93-110">온-프레미스에서 받는 사람을 관리하는 경우 EAC에 메일 받는 사람이 반영되도록 디렉터리 동기화를 실행해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="e6c93-110">If you're managing your recipients on-premises, you must run directory synchronization in order for your mail recipients to be reflected in the EAC.</span></span> <span data-ttu-id="e6c93-111">Microsoft 365 관리 센터에서만 관리되는 사용자는 EAC에서 볼 수 없지만 EAC의 관리자 역할 그룹의 구성원 자격에 추가되거나 제거될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e6c93-111">Users managed solely in the Microsoft 365 admin center aren't viewable in the EAC, but they can be added to or removed from membership in an administrator role group in the EAC.</span></span> <span data-ttu-id="e6c93-112">EOP의 받는 사람에 대한 자세한 내용은 [EOP의 받는 사람](/microsoft-365/security/office-365-security/manage-recipients-in-eop)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="e6c93-112">For more information about recipients in EOP, see [Recipients in EOP](/microsoft-365/security/office-365-security/manage-recipients-in-eop).</span></span>
  
## <a name="admin-role-group-permissions"></a><span data-ttu-id="e6c93-113">Admin role group permissions</span><span class="sxs-lookup"><span data-stu-id="e6c93-113">Admin role group permissions</span></span>

<span data-ttu-id="e6c93-p104">EOP에서는 관리자 역할만 구성할 수 있습니다. EAC에서 직접 사용자를 기본 관리자 역할 그룹에 추가하거나 그룹에서 제거할 수 있습니다. RBAC는 사용자 지정할 수 없습니다. 자세한 내용은 [EOP에서 관리자 역할 그룹 권한 관리](/microsoft-365/security/office-365-security/manage-admin-role-group-permissions-in-eop)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="e6c93-p104">In EOP, you can configure administrative roles only. Users can be added and removed from default admin role groups directly in the EAC. No RBAC customization is available. For more information, see [Manage Admin Role Group Permissions in EOP](/microsoft-365/security/office-365-security/manage-admin-role-group-permissions-in-eop).</span></span>
  
## <a name="domain-management"></a><span data-ttu-id="e6c93-118">도메인 관리</span><span class="sxs-lookup"><span data-stu-id="e6c93-118">Domain management</span></span>

<span data-ttu-id="e6c93-119">관리되는 도메인은 EOP의 보호를 받는 도메인입니다.</span><span class="sxs-lookup"><span data-stu-id="e6c93-119">Managed domains are domains that are protected by EOP.</span></span> <span data-ttu-id="e6c93-120">EAC에서는 관리되는 도메인을 볼 수 있고 도메인 유형을 편집할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e6c93-120">Managed domains can be viewed and domain types can be edited in the EAC.</span></span> <span data-ttu-id="e6c93-121">도메인 프로비전 및 관리는 Microsoft 365 관리 센터에서 발생하며 변경 내용은 EAC에 반영됩니다.</span><span class="sxs-lookup"><span data-stu-id="e6c93-121">Domain provisioning and management occurs in the Microsoft 365 admin center and changes are reflected in the EAC.</span></span> <span data-ttu-id="e6c93-122">자세한 내용은 [EOP에서 관리되는 도메인 보기 또는 편집](/microsoft-365/security/office-365-security/exchange-online-protection-overview)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="e6c93-122">For more information, see [View or Edit Managed Domains in EOP](/microsoft-365/security/office-365-security/exchange-online-protection-overview).</span></span>
  
## <a name="match-subdomains"></a><span data-ttu-id="e6c93-123">하위 도메인 일치</span><span class="sxs-lookup"><span data-stu-id="e6c93-123">Match subdomains</span></span>

<span data-ttu-id="e6c93-p106">EOP에서는 관리되는 도메인의 하위 도메인에 대한 메일 흐름을 사용하도록 설정할 수 있습니다. 자세한 내용은 [EOP에서 하위 도메인에 대해 전자 메일 흐름 사용](/microsoft-365/security/office-365-security/mail-flow-in-eop)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="e6c93-p106">In EOP, you can enable mail flow to subdomains of a managed domain. For more information, see [Enable Email Flow for Subdomains in EOP](/microsoft-365/security/office-365-security/mail-flow-in-eop).</span></span> 
  
## <a name="directory-based-edge-blocking-dbeb"></a><span data-ttu-id="e6c93-126">DBEB(디렉터리 기반 Edge 차단)</span><span class="sxs-lookup"><span data-stu-id="e6c93-126">Directory Based Edge Blocking (DBEB)</span></span>

<span data-ttu-id="e6c93-127">디렉터리 기반 Edge 차단 기능을 사용하면 서비스 네트워크 경계에서 잘못된 받는 사람의 메시지를 거부할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e6c93-127">The Directory Based Edge Blocking feature lets you reject messages for invalid recipients at the service network perimeter.</span></span> <span data-ttu-id="e6c93-128">DBEB를 사용하면 관리자가 메일 사용이 가능한 받는 사람을 Microsoft에 추가하고 Microsoft에 없는 전자 메일 주소로 전송된 모든 메시지를 차단할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e6c93-128">DBEB lets admins add mail-enabled recipients to Microsoft and block all messages sent to email addresses that aren't present in Microsoft.</span></span> <span data-ttu-id="e6c93-129">메시지가 Microsoft에 있는 유효한 전자 메일 주소로 전송되는 경우 메시지는 나머지 서비스 필터링 계층(맬웨어 방지, 스팸 방지, 전송 규칙)을 통해 계속됩니다.</span><span class="sxs-lookup"><span data-stu-id="e6c93-129">If a message is sent to a valid email address present in Microsoft, the message continues through the rest of the service filtering layers (anti-malware, anti-spam, transport rules).</span></span> <span data-ttu-id="e6c93-130">주소가 없는 경우 필터링이 이루어지기 전에 서비스에서 메시지가 차단되고, 메시지가 배달되지 않았음을 알리는 NDR(배달 못 함 보고서)이 보낸 사람에게 보냅니다.</span><span class="sxs-lookup"><span data-stu-id="e6c93-130">If the address is not present, the service blocks the message before filtering even occurs, and a non-delivery report (NDR) is sent to the sender informing them that their message was not delivered.</span></span> 
  
<span data-ttu-id="e6c93-p108">DBEB를 사용하려면 일부 사용자 및 도메인 구성이 필요합니다. 자세한 내용은 [디렉터리 기반 Edge 차단을 사용하여 잘못된 받는 사람에게 전송된 메시지 거부](/exchange/mail-flow-best-practices/use-directory-based-edge-blocking)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="e6c93-p108">Enabling DBEB requires some user and domain configuration. For more information, see [Use Directory Based Edge Blocking to Reject Messages Sent to Invalid Recipients](/exchange/mail-flow-best-practices/use-directory-based-edge-blocking).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="e6c93-133">기능 가용성</span><span class="sxs-lookup"><span data-stu-id="e6c93-133">Feature availability</span></span>

<span data-ttu-id="e6c93-134">계획, 독립 실행형 옵션 및온-프레미스 솔루션에 대한 기능 가용성을 확인 내용은 Exchange Online Protection [설명을 참조하세요.](exchange-online-protection-service-description.md)</span><span class="sxs-lookup"><span data-stu-id="e6c93-134">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online Protection service description](exchange-online-protection-service-description.md).</span></span>