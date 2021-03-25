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
description: Microsoft Exchange Online에서는 RBAC(역할 기반 액세스 제어) 모델을 사용하여 조직의 관리자가 사용자 및 IT 직원이 서비스에서 수행할 수 있는 작업을 세부적으로 제어할 수 있도록 합니다. 예를 들어, 준수 관리자가 사서함 검색 요청을 담당하는 경우 관리자는 RBAC를 통해 이 관리 기능을 준수 관리자에게 위임할 수 있습니다. Exchange Online에서는 Microsoft Exchange Server 2013과 동일한 RBAC 프레임워크를 사용합니다.
ms.openlocfilehash: b66dc5b0cfdfea5c700afbb5ac38a8309236b427
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173763"
---
# <a name="permissions"></a>사용 권한

Microsoft Exchange Online에서는 RBAC(역할 기반 액세스 제어) 모델을 사용하여 조직의 관리자가 사용자 및 IT 직원이 서비스에서 수행할 수 있는 작업을 세부적으로 제어할 수 있도록 합니다. 예를 들어, 준수 관리자가 사서함 검색 요청을 담당하는 경우 관리자는 RBAC를 통해 이 관리 기능을 준수 관리자에게 위임할 수 있습니다. Exchange Online에서는 Microsoft Exchange Server 2013과 동일한 RBAC 프레임워크를 사용합니다. 
  
RBAC는 이 프레임워크의 최상위 수준에서 관리 역할, 관리 역할 그룹 및 관리 역할 할당 정책으로 구성됩니다. 다음 섹션에서는 각 RBAC 구성 요소에 대한 자세한 내용을 설명합니다.
  
Exchange Online에 사용되는 RBAC 권한 모델에 대한 자세한 내용은 [사용 권한](/exchange/permissions-exchange-2013-help)을 참조하세요.
  
## <a name="role-based-permissions"></a>역할 기반 사용 권한

Exchange Online에서 관리자와 사용자에게 부여되는 권한은 관리 역할을 기반으로 합니다. 역할은 관리자나 사용자가 수행할 수 있는 일련의 작업을 정의합니다. 예를 들어  `Mail Recipients`라고 하는 관리 역할은 사서함, 연락처 및 메일 그룹 집합에서 수행할 수 있는 작업을 정의합니다. 역할이 관리자나 사용자에게 할당되면 해당 사람에게 해당 역할에서 제공되는 권한이 주어집니다. 
  
관리 역할, 최종 사용자 역할의 두 유형의 역할이 있습니다.
  
- **관리 역할** 이러한 역할에는 받는 사람, 서버 또는 데이터베이스 같은 Exchange Online 조직의 일부를 관리하는 역할 그룹을 사용하여 관리자나 전문가 사용자에게 할당할 수 있는 권한이 포함되어 있습니다. 
    
- **최종 사용자 역할** 역할 할당 정책을 사용하여 할당된 이러한 역할을 통해 사용자는 자신의 사서함 및 소유한 메일 그룹을 관리할 수 있습니다. 최종 사용자 역할은 접두사  `My`로 시작합니다.
    
역할은 해당 역할에 할당된 사람이 cmdlet을 사용할 수 있게 하여 관리자와 사용자에게 작업을 수행할 수 있는 권한을 부여합니다. EAC(Exchange 관리 센터) 및 Exchange 관리 셸에서는 cmdlet을 사용하여 Exchange Online을 관리하므로, cmdlet에 액세스 권한을 부여하면 관리자나 사용자는 각 Exchange Online 관리 인터페이스에서 작업을 수행할 수 있는 권한을 얻게 됩니다.
  
Microsoft Online Services의 역할 기반 권한은 Exchange Online RBAC의 해당 권한과 두 가지 방식으로 겹칩니다. 첫째, Microsoft Online의 전역 관리자 또는 서비스 관리자인 사용자는 Exchange Online의 조직 관리 역할 그룹에 자동으로 할당됩니다. 둘째, Microsoft Online의 지원 센터 관리자인 사용자는 Exchange Online의 지원 센터 역할 그룹에 자동으로 할당됩니다. 그렇지 않으면 두 개의 보안 모델은 개별적으로 관리됩니다.
  
> [!IMPORTANT]
> Microsoft Exchange Server 2013의 온-프레미스 버전에서는 사용할 수 있는 일부 역할을 Exchange Online에서 사용하지 못할 수 있습니다. 
  
Exchange Online의 사용 권한에 대한 자세한 내용은 [역할 기반 권한](/exchange/permissions-exchange-2013-help)을 참조하세요.
  
## <a name="role-groups"></a>역할 그룹

관리 역할 그룹은 관리 역할을 관리자 또는 전문가 사용자 그룹에 연결합니다. 관리자는 광범위한 Exchange Online 조직 또는 받는 사람 구성을 관리합니다. 전문가 사용자는 규정 준수와 같은 Exchange Online의 특정 기능을 관리하거나 지원 센터 구성원과 같은 관리 기능이 제한될 수 있지만 광범위한 관리 권한을 부여하지는 않습니다. 역할 그룹은 일반적으로 관리자와 전문가 사용자가 조직 및 받는 사람의 구성을 관리할 수 있도록 하는 관리 관리 역할을 연결합니다. 예를 들어 관리자가 받는 사람을 관리할 수 있는지 또는 사서함 검색 기능을 사용할 수 있는지 여부는 역할 그룹을 사용하여 제어합니다. 
  
> [!IMPORTANT]
> Microsoft Exchange Server 2013의 온-프레미스 버전에서는 사용할 수 있는 일부 역할 그룹을 Exchange Online에서 사용하지 못할 수 있습니다. 
  
역할 그룹에 대한 자세한 내용은 [역할 그룹 및 역할 할당 정책](/exchange/permissions-exchange-2013-help)을 참조하세요.
  
## <a name="role-assignment-policies"></a>역할 할당 정책

관리 역할 할당 정책은 최종 사용자 관리 역할에 사용자를 연결합니다. 역할 할당 정책은 사용자가 자신의 사서함 또는 메일 그룹을 사용하여 수행할 수 있는 작업을 제어하는 역할로 구성됩니다. 이러한 역할은 사용자와 직접 연결되지 않은 기능의 관리를 허용하지 않습니다. 역할 할당 정책을 만들 때는 사용자가 사서함을 사용하여 수행할 수 있는 모든 작업을 정의합니다. 예를 들면, 사용자가 표시 이름을 설정하고, 음성 사서함을 설정하고, 받은 편지함 규칙을 구성하도록 허용하는 역할 할당 정책이 있을 수 있습니다. 또 다른 역할 할당 정책은 사용자가 주소를 변경하고, 텍스트 메시징을 사용하고, 메일 그룹을 설정하도록 허용할 수 있습니다. 관리자를 포함하여 Exchange Online 사서함을 사용하는 모든 사용자에게는 기본적으로 역할 할당 정책이 지정됩니다. 기본적으로 할당할 역할 할당 정책을 결정하거나, 기본 역할 할당 정책에 포함할 내용을 선택하거나, 특정 사서함에 대해 기본값을 다시 정의하거나, 기본적으로 어떠한 역할 할당 정책도 할당하지 않을 수 있습니다.
  
> [!IMPORTANT]
> Microsoft Exchange Server 2013의 온-프레미스 버전에서는 사용할 수 있는 일부 역할 할당을 Exchange Online에서 사용하지 못할 수 있습니다. 
  
역할 할당 정책에 대한 자세한 내용은 [역할 그룹 및 역할 할당 정책](/exchange/permissions-exchange-2013-help)을 참조하세요.
  
## <a name="feature-availability"></a>기능 가용성

계획, 독립 실행형 옵션 및온-프레미스 솔루션에서 기능 가용성을 확인하면 Exchange Online 서비스 [설명을 참조하세요.](exchange-online-service-description.md)
