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
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
ms.assetid: 10812b48-7df5-47e9-b643-dbc3c85d7de0
description: 이 문서를 읽고 EOP(Microsoft Exchange Online 보호)의 받는 사람, 도메인 및 회사 관리에 대해 자세히 알아보습니다.
ms.openlocfilehash: 928f94153f91c5067bc5e7ea80525a36cc8e7de3
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/24/2021
ms.locfileid: "59672231"
---
# <a name="recipient-domain-and-company-management-in-exchange-online-protection"></a>사용자 계정의 받는 사람, 도메인 및 Exchange Online Protection

Microsoft Exchange Online EOP(보호)는 받는 사람, 도메인 및 회사 정보를 관리하는 여러 가지 방법을 제공합니다. 관리자는 EAC(Exchange 관리 센터) 내에서 특정 관리 작업을 수행하고, EAC(Microsoft 365 관리 센터 관리 센터)에서 수행되는 다른 관리 작업을 Microsoft 365 관리 센터.
  
모든 EOP 기능에 대한 정보를 찾고 있나요? 자세한 [내용은 Exchange Online Protection 설명을 참조하세요.](exchange-online-protection-service-description.md)
  
## <a name="mail-recipients"></a>Mail recipients

메일 받는 사람은 메일 사용자 또는 그룹으로 분류되며 디렉터리 동기화를 통해하거나 EAC에서 직접 또는 원격 Windows PowerShell을 통해 관리할 수 있습니다. 온-프레미스에서 받는 사람을 관리하는 경우 EAC에 메일 받는 사람이 반영되도록 디렉터리 동기화를 실행해야 합니다. 조직에서만 관리되는 Microsoft 365 관리 센터 EAC에서는 볼 수 없지만 EAC의 관리자 역할 그룹의 구성원 자격에 추가되거나 제거될 수 있습니다. EOP의 받는 사람에 대한 자세한 내용은 [EOP의 받는 사람](/microsoft-365/security/office-365-security/manage-recipients-in-eop)을 참조하세요.
  
## <a name="admin-role-group-permissions"></a>Admin role group permissions

EOP에서는 관리자 역할만 구성할 수 있습니다. EAC에서 직접 사용자를 기본 관리자 역할 그룹에 추가하거나 그룹에서 제거할 수 있습니다. RBAC는 사용자 지정할 수 없습니다. 자세한 내용은 [EOP에서 관리자 역할 그룹 권한 관리](/microsoft-365/security/office-365-security/manage-admin-role-group-permissions-in-eop)를 참조하세요.
  
## <a name="domain-management"></a>도메인 관리

관리되는 도메인은 EOP의 보호를 받는 도메인입니다. EAC에서는 관리되는 도메인을 볼 수 있고 도메인 유형을 편집할 수 있습니다. 도메인 프로비전 및 관리는 Microsoft 365 관리 센터 변경 내용이 EAC에 반영됩니다. 자세한 내용은 [EOP에서 관리되는 도메인 보기 또는 편집](/microsoft-365/security/office-365-security/exchange-online-protection-overview)을 참조하세요.
  
## <a name="match-subdomains"></a>하위 도메인 일치

EOP에서는 관리되는 도메인의 하위 도메인에 대한 메일 흐름을 사용하도록 설정할 수 있습니다. 자세한 내용은 [EOP에서 하위 도메인에 대해 전자 메일 흐름 사용](/microsoft-365/security/office-365-security/mail-flow-in-eop)을 참조하세요. 
  
## <a name="directory-based-edge-blocking-dbeb"></a>DBEB(디렉터리 기반 Edge 차단)

디렉터리 기반 Edge 차단 기능을 사용하면 서비스 네트워크 경계에서 잘못된 받는 사람의 메시지를 거부할 수 있습니다. DBEB를 사용하면 관리자가 메일 사용이 가능한 받는 사람을 Microsoft에 추가하고 Microsoft에 없는 전자 메일 주소로 전송된 모든 메시지를 차단할 수 있습니다. 메시지가 Microsoft에 있는 유효한 전자 메일 주소로 전송되는 경우 메시지는 나머지 서비스 필터링 계층(맬웨어 방지, 스팸 방지, 전송 규칙)을 통해 계속됩니다. 주소가 없는 경우 필터링이 이루어지기 전에 서비스에서 메시지가 차단되고, 메시지가 배달되지 않았음을 알리는 NDR(배달 못 함 보고서)이 보낸 사람에게 보냅니다. 
  
DBEB를 사용하려면 일부 사용자 및 도메인 구성이 필요합니다. 자세한 내용은 [디렉터리 기반 Edge 차단을 사용하여 잘못된 받는 사람에게 전송된 메시지 거부](/exchange/mail-flow-best-practices/use-directory-based-edge-blocking)를 참조하세요.
  
## <a name="feature-availability"></a>기능 가용성

계획, 독립 실행형 옵션 및온-프레미스 솔루션에 대한 기능 가용성을 확인 내용은 Exchange Online Protection [설명을 참조하세요.](exchange-online-protection-service-description.md)