---
title: 받는 사람, 도메인 및 회사 관리
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- recipient-domain-and-company-management-features-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 10812b48-7df5-47e9-b643-dbc3c85d7de0
description: Microsoft EOP (Exchange Online Protection)에서는 받는 사람, 도메인 및 회사 정보를 관리 하는 여러 가지 방법을 제공 합니다. 관리자는 EAC (Exchange 관리 센터) 내에서 특정 관리 작업을 수행 하 고 Microsoft 365 관리 센터에서 수행 된 기타 관리 작업을 확인할 수 있습니다.
ms.openlocfilehash: fcae2c3ad93b977fb197089e2c8809b74ada7bd7
ms.sourcegitcommit: 4abe1be8a63406e8a8c1a4a69f95386906ea1499
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/22/2019
ms.locfileid: "30210331"
---
# <a name="recipient-domain-and-company-management"></a>받는 사람, 도메인 및 회사 관리

Microsoft EOP (Exchange Online Protection)에서는 받는 사람, 도메인 및 회사 정보를 관리 하는 여러 가지 방법을 제공 합니다. 관리자는 EAC (Exchange 관리 센터) 내에서 특정 관리 작업을 수행 하 고 Microsoft 365 관리 센터에서 수행 된 기타 관리 작업을 확인할 수 있습니다.
  
모든 EOP 기능에 대한 자세한 내용은 [Exchange Online Protection 서비스 설명](exchange-online-protection-service-description.md)을 참조하세요.
  
## <a name="mail-recipients"></a>메일 받는 사람
<a name="BKMK_mailrecipients"> </a>

메일 받는 사람은 메일 사용자 또는 그룹으로 분류 되며 디렉터리 동기화, EAC에서 직접 또는 원격 Windows PowerShell을 통해 관리할 수 있습니다. 온-프레미스에서 받는 사람을 관리 하는 경우 EAC에 메일 받는 사람이 반영 되도록 디렉터리 동기화를 실행 해야 합니다. Microsoft 365 관리 센터 에서만 관리 되는 사용자는 eac에서 볼 수 없지만 eac에서 관리자 역할 그룹의 구성원 자격에 게 추가 되거나 제거 될 수도 있습니다. EOP의 받는 사람에 대 한 자세한 내용은 [EOP의 받는 사람](https://go.microsoft.com/fwlink/p/?LinkId=280011)을 참조 하십시오.
  
## <a name="admin-role-group-permissions"></a>관리자 역할 그룹 권한
<a name="BKMK_adminrolegrouppermissions"> </a>

EOP에서는 관리자 역할만 구성할 수 있습니다. EAC에서 직접 사용자를 기본 관리자 역할 그룹에 추가하거나 그룹에서 제거할 수 있습니다. RBAC는 사용자 지정할 수 없습니다. 자세한 내용은 [EOP에서 관리자 역할 그룹 권한 관리](https://go.microsoft.com/fwlink/p/?LinkId=282238)를 참조하세요.
  
## <a name="domain-management"></a>도메인 관리
<a name="BKMK_domainmanagement"> </a>

관리 되는 도메인은 EOP으로 보호 되는 도메인입니다. 관리 되는 도메인을 보고 EAC에서 도메인 유형을 편집할 수 있습니다. 도메인 프로 비전 및 관리는 Microsoft 365 관리 센터에서 수행 되며 변경 내용은 EAC에 반영 됩니다. 자세한 내용은 [EOP에서 관리 되는 도메인 보기 또는 편집](https://go.microsoft.com/fwlink/p/?LinkId=282239)을 참조 하세요.
  
## <a name="match-subdomains"></a>하위 도메인 일치
<a name="BKMK_EOP_Match_Subdomains"> </a>

EOP에서는 관리되는 도메인의 하위 도메인에 대한 메일 흐름을 사용하도록 설정할 수 있습니다. 자세한 내용은 [EOP에서 하위 도메인에 대해 전자 메일 흐름 사용](https://go.microsoft.com/fwlink/p/?LinkId=397213)을 참조하세요. 
  
## <a name="directory-based-edge-blocking-dbeb"></a>DBEB(디렉터리 기반 Edge 차단)
<a name="BKMK_DBEB"> </a>

디렉터리 기반 Edge 차단 기능을 사용하면 서비스 네트워크 경계에서 잘못된 받는 사람의 메시지를 거부할 수 있습니다. 관리자는 DBEB를 사용하여 메일 사용 가능 받는 사람을 Office 365에 추가하고 Office 365에 없는 전자 메일 주소로 전송된 모든 메시지를 차단할 수 있습니다. Office 365에 있는 올바른 전자 메일 주소로 보낸 메시지는 계속해서 나머지 서비스 필터링 계층(맬웨어 방지, 스팸 방지, 전송 규칙)을 통과합니다. 주소가 없는 경우 필터링이 이루어지기 전에 서비스에서 메시지가 차단되고, 메시지가 배달되지 않았음을 알리는 NDR(배달 못 함 보고서)이 보낸 사람에게 보냅니다. 
  
DBEB를 사용하려면 일부 사용자 및 도메인 구성이 필요합니다. 자세한 내용은 [디렉터리 기반 Edge 차단을 사용하여 잘못된 받는 사람에게 전송된 메시지 거부](https://go.microsoft.com/fwlink/p/?LinkId=390676)를 참조하세요.
  
## <a name="feature-availability"></a>기능 가용성
<a name="BKMK_DBEB"> </a>

Office 365 계획, 독립 실행형 옵션 및 온-프레미스 솔루션별로 기능 가용성을 확인하려면 [Exchange Online Protection 서비스 설명](exchange-online-protection-service-description.md)을 참조하세요.
  

