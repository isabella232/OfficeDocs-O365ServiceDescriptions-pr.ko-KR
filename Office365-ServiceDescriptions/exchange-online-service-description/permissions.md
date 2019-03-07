---
title: 사용 권한
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-permissions
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7803d7c0-93e6-43a2-b2a4-3a39abe25500
description: Microsoft Exchange Online에서는 RBAC(역할 기반 액세스 제어) 모델을 사용하여 조직의 관리자가 사용자 및 IT 직원이 서비스에서 수행할 수 있는 작업을 세부적으로 제어할 수 있도록 합니다. 예를 들어, 준수 관리자가 사서함 검색 요청을 담당하는 경우 관리자는 RBAC를 통해 이 관리 기능을 준수 관리자에게 위임할 수 있습니다. Exchange Online에서는 Microsoft Exchange Server 2013과 동일한 RBAC 프레임워크를 사용합니다.
ms.openlocfilehash: 9f7cad7587d3700971a9cedaf38a20161f203c01
ms.sourcegitcommit: 68eee0c2885fd112e37eea27370c3f8c1f0831cb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/07/2019
ms.locfileid: "30468135"
---
# <a name="permissions"></a><span data-ttu-id="a3eea-105">사용 권한</span><span class="sxs-lookup"><span data-stu-id="a3eea-105">Permissions</span></span>

<span data-ttu-id="a3eea-p102">Microsoft Exchange Online에서는 RBAC(역할 기반 액세스 제어) 모델을 사용하여 조직의 관리자가 사용자 및 IT 직원이 서비스에서 수행할 수 있는 작업을 세부적으로 제어할 수 있도록 합니다. 예를 들어, 준수 관리자가 사서함 검색 요청을 담당하는 경우 관리자는 RBAC를 통해 이 관리 기능을 준수 관리자에게 위임할 수 있습니다. Exchange Online에서는 Microsoft Exchange Server 2013과 동일한 RBAC 프레임워크를 사용합니다.</span><span class="sxs-lookup"><span data-stu-id="a3eea-p102">Microsoft Exchange Online uses a Role Based Access Control (RBAC) model to allow organization administrators to finely control what users and IT employees can do in the service. For example, if a compliance officer is responsible for mailbox search requests, the administrator can delegate this administrative feature to the officer through RBAC. Exchange Online uses the same RBAC framework as Microsoft Exchange Server 2013.</span></span> 
  
<span data-ttu-id="a3eea-p103">RBAC는 이 프레임워크의 최상위 수준에서 관리 역할, 관리 역할 그룹 및 관리 역할 할당 정책으로 구성됩니다. 다음 섹션에서는 각 RBAC 구성 요소에 대한 자세한 내용을 설명합니다.</span><span class="sxs-lookup"><span data-stu-id="a3eea-p103">At its highest level, RBAC is made up of management roles, management role groups, and management role assignment policies. The following sections provide more information about each RBAC component.</span></span>
  
<span data-ttu-id="a3eea-111">Exchange Online에 사용되는 RBAC 권한 모델에 대한 자세한 내용은 [사용 권한](https://go.microsoft.com/fwlink/p/?LinkId=271935)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="a3eea-111">For more information about the RBAC permissions model that's used in Exchange Online, see [Permissions](https://go.microsoft.com/fwlink/p/?LinkId=271935).</span></span>
  
## <a name="role-based-permissions"></a><span data-ttu-id="a3eea-112">역할 기반 권한</span><span class="sxs-lookup"><span data-stu-id="a3eea-112">Role-Based permissions</span></span>

<span data-ttu-id="a3eea-p104">Exchange Online에서 관리자와 사용자에게 부여되는 권한은 관리 역할을 기반으로 합니다. 역할은 관리자나 사용자가 수행할 수 있는 일련의 작업을 정의합니다. 예를 들어  `Mail Recipients`라고 하는 관리 역할은 사서함, 연락처 및 메일 그룹 집합에서 수행할 수 있는 작업을 정의합니다. 역할이 관리자나 사용자에게 할당되면 해당 사람에게 해당 역할에서 제공되는 권한이 주어집니다.</span><span class="sxs-lookup"><span data-stu-id="a3eea-p104">In Exchange Online, the permissions that you grant to administrators and users are based on management roles. A role defines the set of tasks that an administrator or user can perform. For example, a management role called  `Mail Recipients` defines the tasks that someone can perform on a set of mailboxes, contacts, and distribution groups. When a role is assigned to an administrator or user, that person is granted the permissions provided by the role.</span></span> 
  
<span data-ttu-id="a3eea-117">관리 역할, 최종 사용자 역할의 두 유형의 역할이 있습니다.</span><span class="sxs-lookup"><span data-stu-id="a3eea-117">There are two types of roles, administrative roles and end-user roles:</span></span>
  
- <span data-ttu-id="a3eea-118">**관리 역할** 이러한 역할에는 받는 사람, 서버 또는 데이터베이스 같은 Exchange Online 조직의 일부를 관리하는 역할 그룹을 사용하여 관리자나 전문가 사용자에게 할당할 수 있는 권한이 포함되어 있습니다.</span><span class="sxs-lookup"><span data-stu-id="a3eea-118">**Administrative roles** These roles contain permissions that can be assigned to administrators or specialist users by using role groups that manage a part of the Exchange Online organization, such as recipients, servers, or databases.</span></span> 
    
- <span data-ttu-id="a3eea-p105">**최종 사용자 역할** 역할 할당 정책을 통해 할당되는 이 역할을 사용하면 사용자는 자신의 사서함 및 자신이 속한 메일 그룹을 관리할 수 있습니다. 최종 사용자 역할은 접두사  `My`로 시작합니다.</span><span class="sxs-lookup"><span data-stu-id="a3eea-p105">**End-user roles** These roles, assigned by using role assignment policies, enable users to manage aspects of their own mailboxes and distribution groups that they own. End-user roles begin with the prefix  `My`.</span></span>
    
<span data-ttu-id="a3eea-p106">역할은 해당 역할에 할당된 사람이 cmdlet을 사용할 수 있게 하여 관리자와 사용자에게 작업을 수행할 수 있는 권한을 부여합니다. EAC(Exchange 관리 센터) 및 Exchange 관리 셸에서는 cmdlet을 사용하여 Exchange Online을 관리하므로, cmdlet에 액세스 권한을 부여하면 관리자나 사용자는 각 Exchange Online 관리 인터페이스에서 작업을 수행할 수 있는 권한을 얻게 됩니다.</span><span class="sxs-lookup"><span data-stu-id="a3eea-p106">Roles give administrators and users permissions to perform tasks by making cmdlets available to those who are assigned the roles. Because the Exchange admin center (EAC) and Exchange Management Shell use cmdlets to manage Exchange Online, granting access to a cmdlet gives the administrator or user permission to perform the task in each of the Exchange Online management interfaces.</span></span>
  
<span data-ttu-id="a3eea-p107">Microsoft Online Services의 역할 기반 권한은 Exchange Online RBAC의 해당 권한과 두 가지 방식으로 겹칩니다. 첫째, Microsoft Online의 전역 관리자 또는 서비스 관리자인 사용자는 Exchange Online의 조직 관리 역할 그룹에 자동으로 할당됩니다. 둘째, Microsoft Online의 지원 센터 관리자인 사용자는 Exchange Online의 지원 센터 역할 그룹에 자동으로 할당됩니다. 그렇지 않으면 두 개의 보안 모델은 개별적으로 관리됩니다.</span><span class="sxs-lookup"><span data-stu-id="a3eea-p107">The role-based permissions for Microsoft Online Services overlap with those of Exchange Online RBAC in two ways. First, users who are Global Administrators or Service Administrators in Microsoft Online are automatically assigned to the Organization Management role group in Exchange Online. Second, users who are Help Desk Administrators in Microsoft Online are automatically assigned to the Help Desk role group in Exchange Online. Otherwise, the two security models are managed separately.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="a3eea-127">Microsoft Exchange Server 2013의 온-프레미스 버전에서는 사용할 수 있는 일부 역할을 Exchange Online에서 사용하지 못할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="a3eea-127">Some roles available in the on-premises version of Microsoft Exchange Server 2013 may not be available in Exchange Online.</span></span> 
  
<span data-ttu-id="a3eea-128">Exchange Online의 사용 권한에 대한 자세한 내용은 [역할 기반 권한](https://go.microsoft.com/fwlink/p/?LinkId=271936)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="a3eea-128">For more information about permissions in Exchange Online, see [Role-Based Permissions](https://go.microsoft.com/fwlink/p/?LinkId=271936).</span></span>
  
## <a name="role-groups"></a><span data-ttu-id="a3eea-129">역할 그룹</span><span class="sxs-lookup"><span data-stu-id="a3eea-129">Role groups</span></span>

<span data-ttu-id="a3eea-p108">관리 역할 그룹은 관리 역할을 관리자 또는 전문가 사용자 그룹과 연결합니다. 관리자는 광범위한 Exchange Online 조직 또는 받는 사람 구성을 관리합니다. 전문가 사용자는 Exchange Online의 특정 기능(예: 준수)을 관리합니다. 또는 지원 센터 구성원과 같이 제한된 관리 기능은 가질 수 있지만 광범위한 관리 권한은 없습니다. 역할 그룹은 일반적으로 관리자 및 전문가 사용자가 조직 및 수신인의 구성을 관리하도록 허용하는 관리 역할을 연결합니다. 예를 들면, 관리자가 받는 사람을 관리할 수 있는지 또는 역할 그룹을 사용하여 사서함 검색 기능 사용을 제어할 수 있는지 여부 등이 있습니다.</span><span class="sxs-lookup"><span data-stu-id="a3eea-p108">Management role groups associate management roles to a group of administrators or specialist users. Administrators manage a broad Exchange Online organization or recipient configuration. Specialist users manage the specific features of Exchange Online, such as compliance, or they may have limited management abilities, such as Help desk members, but aren't given broad administrative rights. Role groups typically associate administrative management roles that enable administrators and specialist users to manage the configuration of their organization and recipients. For example, whether administrators can manage recipients or use mailbox discovery features is controlled by using role groups.</span></span> 
  
> [!IMPORTANT]
> <span data-ttu-id="a3eea-135">Microsoft Exchange Server 2013의 온-프레미스 버전에서는 사용할 수 있는 일부 역할 그룹을 Exchange Online에서 사용하지 못할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="a3eea-135">Some role groups available in the on-premises version of Microsoft Exchange Server 2013 may not be available in Exchange Online.</span></span> 
  
<span data-ttu-id="a3eea-136">역할 그룹에 대한 자세한 내용은 [역할 그룹 및 역할 할당 정책](https://go.microsoft.com/fwlink/p/?LinkId=271937)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="a3eea-136">For more information about role groups, see [Role groups and role assignment policies](https://go.microsoft.com/fwlink/p/?LinkId=271937).</span></span>
  
## <a name="role-assignment-policies"></a><span data-ttu-id="a3eea-137">역할 할당 정책</span><span class="sxs-lookup"><span data-stu-id="a3eea-137">Role assignment policies</span></span>

<span data-ttu-id="a3eea-p109">관리 역할 할당 정책은 최종 사용자 관리 역할에 사용자를 연결합니다. 역할 할당 정책은 사용자가 자신의 사서함 또는 메일 그룹을 사용하여 수행할 수 있는 작업을 제어하는 역할로 구성됩니다. 이러한 역할은 사용자와 직접 연결되지 않은 기능의 관리를 허용하지 않습니다. 역할 할당 정책을 만들 때는 사용자가 사서함을 사용하여 수행할 수 있는 모든 작업을 정의합니다. 예를 들면, 사용자가 표시 이름을 설정하고, 음성 사서함을 설정하고, 받은 편지함 규칙을 구성하도록 허용하는 역할 할당 정책이 있을 수 있습니다. 또 다른 역할 할당 정책은 사용자가 주소를 변경하고, 텍스트 메시징을 사용하고, 메일 그룹을 설정하도록 허용할 수 있습니다. 관리자를 포함하여 Exchange Online 사서함을 사용하는 모든 사용자에게는 기본적으로 역할 할당 정책이 지정됩니다. 기본적으로 할당할 역할 할당 정책을 결정하거나, 기본 역할 할당 정책에 포함할 내용을 선택하거나, 특정 사서함에 대해 기본값을 다시 정의하거나, 기본적으로 어떠한 역할 할당 정책도 할당하지 않을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="a3eea-p109">Management role assignment policies associate end-user management roles to users. Role assignment policies consist of roles that control what users can do with their mailboxes or distribution groups. These roles don't allow management of features that aren't directly associated with the user. When you create a role assignment policy, you define everything a user can do with his or her mailbox. For example, a role assignment policy might allow a user to set the display name, set up voice mail, and configure Inbox rules. Another role assignment policy might allow a user to change the address, use text messaging, and set up distribution groups. Every user with an Exchange Online mailbox, including administrators, is given a role assignment policy by default. You can decide which role assignment policy should be assigned by default, choose what the default role assignment policy should include, override the default for certain mailboxes, or not assign any role assignment policies by default.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="a3eea-146">Microsoft Exchange Server 2013의 온-프레미스 버전에서는 사용할 수 있는 일부 역할 할당을 Exchange Online에서 사용하지 못할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="a3eea-146">Some role assignments available in the on-premises version of Microsoft Exchange Server 2013 may not be available in Exchange Online.</span></span> 
  
<span data-ttu-id="a3eea-147">역할 할당 정책에 대한 자세한 내용은 [역할 그룹 및 역할 할당 정책](https://go.microsoft.com/fwlink/p/?LinkId=271937)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="a3eea-147">For more information about role assignment policies, see [Role groups and role assignment policies](https://go.microsoft.com/fwlink/p/?LinkId=271937).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="a3eea-148">기능 가용성</span><span class="sxs-lookup"><span data-stu-id="a3eea-148">Feature Availability</span></span>

<span data-ttu-id="a3eea-149">Office 365 계획, 독립 실행형 옵션 및 온-프레미스 솔루션별로 기능 가용성을 확인하려면 [Exchange Online 서비스 설명](exchange-online-service-description.md)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="a3eea-149">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

