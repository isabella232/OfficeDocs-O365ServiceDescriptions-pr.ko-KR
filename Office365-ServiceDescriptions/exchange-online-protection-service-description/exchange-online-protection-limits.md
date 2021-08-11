---
title: Exchange Online Protection 제한
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-limits
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: f866fe3b-a183-4e6d-abd9-bbec0a0c7fae
description: 현재 다음과 같은 제한이 Exchange Online Protection. 이러한 제한은 달리 지정하지 않는 한 구성할 수 없습니다.
ms.openlocfilehash: f573f73bf69944ecb400347978140e45a4c8700f74ac214572228ae83fc3c7fb
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/06/2021
ms.locfileid: "54664500"
---
# <a name="exchange-online-protection-limits"></a>Exchange Online Protection 제한

현재 다음과 같은 제한이 Exchange Online Protection. 이러한 제한은 달리 지정하지 않는 한 구성할 수 없습니다. 
  
> [!TIP]
> 제한에 대한 자세한 내용은 Exchange Online [제한을 Exchange Online 참조하세요.](../exchange-online-service-description/exchange-online-limits.md) EOP 독립 실행형 고객에게는 전송 규칙 제한도 적용됩니다. Exchange Online의 받는 사람 처리 속도 및 메시지 속도 제한은 EOP 독립 실행형 고객에게 적용되지 않습니다. 
  
- **도메인 제한** - 테넌트당 최대 900개 도메인을 추가할 수 있습니다. 하위 도메인은 이 900개 제한 내에 포함되거나 보완 옵션인 하위 도메인 일치의 일부분으로 포함될 수 있습니다. 자세한 내용은 [EOP에서 허용 도메인 관리](/microsoft-365/security/office-365-security/exchange-online-protection-overview)를 참조하세요.

- **원격 도메인 제한** - 테넌트당 최대 200개 원격 도메인을 추가할 수 있습니다.
    
- **메시지 크기 제한** - 첨부 파일을 포함하여 EOP 독립 실행형 고객의 최대 메시지 크기는 150MB입니다. 
    
- **전송된** 아웃바운드 메시지 수 - EOP를 통해 전송되는 아웃바운드 메시지 수에 대한 제한이 충분히 높기만 하면 정상적인 전자 메일 통신이 스팸으로 처리되지 않습니다. 상업용 대량 전자 메일 메시지를 보내려면 EOP를 통해 아웃바운드 메시지를 보내는 대신 타사 ESP(전자 메일 서비스 공급자)를 사용하거나 온-프레미스 전자 메일 서버를 통해 보내는 것이 좋습니다. 
    
- **받는 사람 제한** - 보내는 호스트가 메시지를 500명 미만의 받는 사람 "청크"로 분할할 수 있는 한 명시적 제한이 정의되지 않습니다. 그러나 각 "청크"는 새 메시지로 효과적으로 처리됩니다. 짧은 기간 동안 메시지가 너무 많거나, 평판이 나쁜 호스트에서 전송된 메시지이거나, 의심스러운 콘텐츠가 포함된 메시지는 제한하거나 차단할 수 있습니다. 
    
- **IP 허용 또는 IP** 차단 목록 제한 - 연결 필터에서 IP 허용 목록 또는 IP 차단 목록을 구성할 때 최대 1273개 항목을 지정할 수 있습니다. 여기서 항목은 단일 IP 주소 또는 /24에서 /32까지의 IP 주소의 CIDR 범위입니다. 
    
- **메시지 지연 제한** - 지연 메시지는 24시간 동안 큐에 남아 있습니다. 메시지 다시 시도는 받는 사람의 메일 시스템에서 수신된 오류 유형을 기반으로 합니다. 메시지는 15분마다 다시 시도됩니다. 
    
- **스팸 차단 보존 기간** - 기본적으로 스팸 메시지는 30일 동안 보존됩니다. 관리자는 콘텐츠 필터 정책을 통해 이 값을 낮출 수 있습니다. 
    
- **최종 사용자 스팸** 차단 알림 - 기본적으로 사용하도록 설정되어 있는 경우 최종 사용자 스팸 검지 알림은 3일마다 전송됩니다. 이 값을 1일에서 15일 사이로 구성할 수 있습니다. 
    
- **보고 및** 메시지 추적 제한 - 보고 및 메시지 추적 제한에 대한 자세한 내용은 에서 보고 및 메시지 추적의 "보고 및 메시지 추적 데이터 가용성 및 대기 [시간" 섹션을 Exchange Online Protection.](/microsoft-365/security/office-365-security/reporting-and-message-trace-in-exchange-online-protection)
    
### <a name="limits-across-eop-options"></a>EOP 옵션별 제한

| 기능 | EOP 독립 실행형 | Exchange Online의 EOP 기능 | Exchange Enterprise CAL with Services |
|:-----|:-----|:-----|:-----|
|도메인 제한  <br/> |900  <br/> |900  <br/> |900  <br/> |
|원격 도메인 제한  <br/> |200  <br/> |200  <br/> |200  <br/> |
|메시지 크기 제한(첨부 파일 포함)  <br/> |150MB  <br/> |150MB  <br/> |150MB  <br/> |
|받는 사람 제한  <br/> |위의 "받는 사람 제한" 참조  <br/> |호스트된 사서함에서 보낼 경우 받는 사람 500명. 다른 시나리오의 경우 위의 "받는 사람 제한" 참조  <br/> |위의 "받는 사람 제한" 참조  <br/> |
|수신 허용 제한  <br/> |항목 1024개  <br/> |항목 1024개  <br/> ||
|정책당 수신 차단된 보낸 사람 제한  <br/> |항목 1024개  <br/> |항목 1024개  <br/> ||
|IP 허용 목록 또는 IP 차단 목록 제한  <br/> |항목 1273개  <br/> |항목 1273개  <br/> |항목 1273개  <br/> |
|지연 메시지 제한  <br/> |1일, 15분마다 다시 검색  <br/> |1일, 15분마다 다시 검색  <br/> |1일, 15분마다 다시 검색  <br/> |
|스팸 격리 보존 기간  <br/> |기본적으로 30일이지만 낮출 수 있습니다.  <br/> |기본적으로 30일이지만 낮출 수 있습니다.  <br/> |기본적으로 30일이지만 낮출 수 있습니다.  <br/> |
|최종 사용자 스팸 격리 알림  <br/> |기본적으로 3일이지만 1일에서 15일 사이로 구성할 수 있음  <br/> |기본적으로 3일이지만 1일에서 15일 사이로 구성할 수 있음  <br/> |기본적으로 3일이지만 1일에서 15일 사이로 구성할 수 있음  <br/> |
