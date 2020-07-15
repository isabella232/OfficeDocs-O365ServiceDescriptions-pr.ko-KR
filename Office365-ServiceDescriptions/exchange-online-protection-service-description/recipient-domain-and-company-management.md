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
# <a name="recipient-domain-and-company-management"></a>받는 사람, 도메인 및 회사 관리

Microsoft EOP (Exchange Online Protection)에서는 받는 사람, 도메인 및 회사 정보를 관리 하는 여러 가지 방법을 제공 합니다. 관리자는 EAC (Exchange 관리 센터) 내에서 특정 관리 작업을 수행 하 고 Microsoft 365 관리 센터에서 수행 된 기타 관리 작업을 확인할 수 있습니다.
  
모든 EOP 기능에 대 한 정보를 찾으십니까? [Exchange Online Protection 서비스 설명을](exchange-online-protection-service-description.md)참조 하세요.
  
## <a name="mail-recipients"></a>Mail recipients

메일 받는 사람은 메일 사용자 또는 그룹으로 분류되며 디렉터리 동기화를 통해하거나 EAC에서 직접 또는 원격 Windows PowerShell을 통해 관리할 수 있습니다. 온-프레미스에서 받는 사람을 관리하는 경우 EAC에 메일 받는 사람이 반영되도록 디렉터리 동기화를 실행해야 합니다. Microsoft 365 관리 센터 에서만 관리 되는 사용자는 EAC에서 볼 수 없지만 EAC에서 관리자 역할 그룹의 구성원 자격에 게 추가 되거나 제거 될 수도 있습니다. EOP의 받는 사람에 대한 자세한 내용은 [EOP의 받는 사람](https://go.microsoft.com/fwlink/p/?LinkId=280011)을 참조하세요.
  
## <a name="admin-role-group-permissions"></a>Admin role group permissions

In EOP, you can configure administrative roles only. Users can be added and removed from default admin role groups directly in the EAC. No RBAC customization is available. For more information, see [Manage Admin Role Group Permissions in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282238).
  
## <a name="domain-management"></a>도메인 관리

관리되는 도메인은 EOP의 보호를 받는 도메인입니다. EAC에서는 관리되는 도메인을 볼 수 있고 도메인 유형을 편집할 수 있습니다. 도메인 프로 비전 및 관리는 Microsoft 365 관리 센터에서 수행 되며 변경 내용은 EAC에 반영 됩니다. 자세한 내용은 [EOP에서 관리되는 도메인 보기 또는 편집](https://go.microsoft.com/fwlink/p/?LinkId=282239)을 참조하세요.
  
## <a name="match-subdomains"></a>하위 도메인 일치

In EOP, you can enable mail flow to subdomains of a managed domain. For more information, see [Enable Email Flow for Subdomains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=397213). 
  
## <a name="directory-based-edge-blocking-dbeb"></a>DBEB(디렉터리 기반 Edge 차단)

디렉터리 기반 Edge 차단 기능을 사용하면 서비스 네트워크 경계에서 잘못된 받는 사람의 메시지를 거부할 수 있습니다. DBEB를 사용 하면 관리자가 메일 사용이 가능한 받는 사람을 Microsoft에 추가 하 고 Microsoft에 제공 되지 않은 전자 메일 주소로 전송 된 모든 메시지를 차단할 수 있습니다. Microsoft에 있는 유효한 전자 메일 주소로 메시지가 전송 되는 경우 해당 메시지는 나머지 서비스 필터링 계층 (맬웨어 방지, 스팸 방지, 전송 규칙)을 통해 계속 진행 됩니다. 주소가 없는 경우 필터링이 이루어지기 전에 서비스에서 메시지가 차단되고, 메시지가 배달되지 않았음을 알리는 NDR(배달 못 함 보고서)이 보낸 사람에게 보냅니다. 
  
Enabling DBEB requires some user and domain configuration. For more information, see [Use Directory Based Edge Blocking to Reject Messages Sent to Invalid Recipients](https://go.microsoft.com/fwlink/p/?LinkId=390676).
  
## <a name="feature-availability"></a>기능 가용성

계획, 독립 실행형 옵션 및 온-프레미스 솔루션 별로 기능 가용성을 확인 하려면 [Exchange Online Protection 서비스 설명을](exchange-online-protection-service-description.md)참조 하세요.
