---
title: 사용 권한
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-permissions
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7803d7c0-93e6-43a2-b2a4-3a39abe25500
description: Microsoft Exchange Online uses a Role Based Access Control (RBAC) model to allow organization administrators to finely control what users and IT employees can do in the service. For example, if a compliance officer is responsible for mailbox search requests, the administrator can delegate this administrative feature to the officer through RBAC. Exchange Online uses the same RBAC framework as Microsoft Exchange Server 2013.
ms.openlocfilehash: 0593c98857a7ce0c487c628018097395d7a5fe50
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132692"
---
# <a name="permissions"></a>사용 권한

Microsoft Exchange Online uses a Role Based Access Control (RBAC) model to allow organization administrators to finely control what users and IT employees can do in the service. For example, if a compliance officer is responsible for mailbox search requests, the administrator can delegate this administrative feature to the officer through RBAC. Exchange Online uses the same RBAC framework as Microsoft Exchange Server 2013. 
  
At its highest level, RBAC is made up of management roles, management role groups, and management role assignment policies. The following sections provide more information about each RBAC component.
  
Exchange Online에 사용되는 RBAC 권한 모델에 대한 자세한 내용은 [사용 권한](https://go.microsoft.com/fwlink/p/?LinkId=271935)을 참조하세요.
  
## <a name="role-based-permissions"></a>역할 기반 권한

In Exchange Online, the permissions that you grant to administrators and users are based on management roles. A role defines the set of tasks that an administrator or user can perform. For example, a management role called  `Mail Recipients` defines the tasks that someone can perform on a set of mailboxes, contacts, and distribution groups. When a role is assigned to an administrator or user, that person is granted the permissions provided by the role. 
  
관리 역할, 최종 사용자 역할의 두 유형의 역할이 있습니다.
  
- **관리 역할** 이러한 역할에는 받는 사람, 서버 또는 데이터베이스 같은 Exchange Online 조직의 일부를 관리하는 역할 그룹을 사용하여 관리자나 전문가 사용자에게 할당할 수 있는 권한이 포함되어 있습니다. 
    
- **최종 사용자 역할** 역할 할당 정책을 사용 하 여 할당 된 이러한 역할을 통해 사용자는 자신의 사서함 및 자신이 소유한 메일 그룹의 특성을 관리할 수 있습니다. 최종 사용자 역할은 접두사  `My`로 시작합니다.
    
Roles give administrators and users permissions to perform tasks by making cmdlets available to those who are assigned the roles. Because the Exchange admin center (EAC) and Exchange Management Shell use cmdlets to manage Exchange Online, granting access to a cmdlet gives the administrator or user permission to perform the task in each of the Exchange Online management interfaces.
  
The role-based permissions for Microsoft Online Services overlap with those of Exchange Online RBAC in two ways. First, users who are Global Administrators or Service Administrators in Microsoft Online are automatically assigned to the Organization Management role group in Exchange Online. Second, users who are Help Desk Administrators in Microsoft Online are automatically assigned to the Help Desk role group in Exchange Online. Otherwise, the two security models are managed separately.
  
> [!IMPORTANT]
> Microsoft Exchange Server 2013의 온-프레미스 버전에서는 사용할 수 있는 일부 역할을 Exchange Online에서 사용하지 못할 수 있습니다. 
  
Exchange Online의 사용 권한에 대한 자세한 내용은 [역할 기반 권한](https://go.microsoft.com/fwlink/p/?LinkId=271936)을 참조하세요.
  
## <a name="role-groups"></a>역할 그룹

관리 역할 그룹은 관리 역할을 관리자 또는 전문가 사용자 그룹에 연결 합니다. 관리자는 광범위 한 Exchange Online 조직 또는 받는 사람 구성을 관리 합니다. 전문 사용자는 규정 준수와 같은 Exchange Online의 특정 기능을 관리 하거나, 지원 센터 구성원 등의 관리 기능을 제한 하거나, 광범위 한 관리 권한을 부여 하지 않을 수 있습니다. 일반적으로 역할 그룹은 관리자 및 전문가 사용자가 조직 및 받는 사람의 구성을 관리할 수 있도록 하는 관리 관리 역할을 연결 합니다. 예를 들어 관리자가 받는 사람을 관리 하거나 사서함 검색 기능을 사용할 수 있는지 여부는 역할 그룹을 사용 하 여 제어 합니다. 
  
> [!IMPORTANT]
> Microsoft Exchange Server 2013의 온-프레미스 버전에서는 사용할 수 있는 일부 역할 그룹을 Exchange Online에서 사용하지 못할 수 있습니다. 
  
역할 그룹에 대한 자세한 내용은 [역할 그룹 및 역할 할당 정책](https://go.microsoft.com/fwlink/p/?LinkId=271937)을 참조하세요.
  
## <a name="role-assignment-policies"></a>역할 할당 정책

Management role assignment policies associate end-user management roles to users. Role assignment policies consist of roles that control what users can do with their mailboxes or distribution groups. These roles don't allow management of features that aren't directly associated with the user. When you create a role assignment policy, you define everything a user can do with his or her mailbox. For example, a role assignment policy might allow a user to set the display name, set up voice mail, and configure Inbox rules. Another role assignment policy might allow a user to change the address, use text messaging, and set up distribution groups. Every user with an Exchange Online mailbox, including administrators, is given a role assignment policy by default. You can decide which role assignment policy should be assigned by default, choose what the default role assignment policy should include, override the default for certain mailboxes, or not assign any role assignment policies by default.
  
> [!IMPORTANT]
> Microsoft Exchange Server 2013의 온-프레미스 버전에서는 사용할 수 있는 일부 역할 할당을 Exchange Online에서 사용하지 못할 수 있습니다. 
  
역할 할당 정책에 대한 자세한 내용은 [역할 그룹 및 역할 할당 정책](https://go.microsoft.com/fwlink/p/?LinkId=271937)을 참조하세요.
  
## <a name="feature-availability"></a>기능 가용성

계획, 독립 실행형 옵션 및 온-프레미스 솔루션 별로 기능 가용성을 확인 하려면 [Exchange Online 서비스 설명을](exchange-online-service-description.md)참조 하세요.
  

