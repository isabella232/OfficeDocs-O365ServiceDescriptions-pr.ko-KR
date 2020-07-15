---
title: Exchange Online Protection 제한
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-limits
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: f866fe3b-a183-4e6d-abd9-bbec0a0c7fae
description: 현재 Exchange Online Protection에 대 한 제한은 다음과 같습니다. 별도로 지정 되지 않은 경우 이러한 제한은 구성할 수 없습니다.
ms.openlocfilehash: 3c5a8e0c5f9a19c9cae81b3bc1e39bb153af0137
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45133012"
---
# <a name="exchange-online-protection-limits"></a>Exchange Online Protection 제한

현재 Exchange Online Protection에 대 한 제한은 다음과 같습니다. 별도로 지정 되지 않은 경우 이러한 제한은 구성할 수 없습니다. 
  
> [!TIP]
> Exchange Online의 제한 사항에 대 한 자세한 내용은 [Exchange online 제한을](../exchange-online-service-description/exchange-online-limits.md)참조 하세요. EOP 독립 실행형 고객에게는 전송 규칙 제한도 적용됩니다. Exchange Online의 받는 사람 처리 속도 및 메시지 속도 제한은 EOP 독립 실행형 고객에게 적용되지 않습니다. 
  
- **Domain limit** You can add up to 900 domains per tenant. Subdomains can be included in this 900 limit, or if necessary, as part of a catch-all option, match subdomains. For more information, see [Manage Accepted Domains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).
    
- **메시지 크기 제한** EOP 독립 실행형 고객의 최대 메시지 크기는 첨부 파일을 포함하여 150MB입니다. 
    
- **Number of outbound messages sent** The limit for the number of outbound messages sent through EOP is high enough to ensure that normal email communication is not treated as spam. If you want to send commercial bulk email messages, rather than sending outbound messages through EOP, we recommend that you either use a third-party email service provider (ESP) or send them through your on-premises email servers. 
    
- **Recipient limit** As long as the sending host can split the message into "chunks" of fewer than 500 recipients, no explicit limit is defined. However, each "chunk" is effectively treated as a new message. Too many messages in a short period, messages from a host with a poor reputation, or messages with questionable content could be throttled or blocked. 
    
- **IP 허용 목록 또는 IP 차단 목록 제한** 연결 필터에서 IP 허용 목록이나 IP 차단 목록을 구성할 때 항목을 1,273개까지 지정할 수 있습니다. 단, 한 항목은 단일 IP 주소이거나 CIDR 범위의 IP 주소(/24~/32)입니다. 
    
- **메시지 지연 제한** 지연 상태의 메시지는 24 시간 동안 큐에 남아 있습니다. 메시지 다시 시도는 받는 사람의 메일 시스템에서 수신된 오류 유형을 기반으로 합니다. 메시지는 15분마다 다시 시도됩니다. 
    
- **스팸 격리 보존 기간** 기본적으로 격리로 전송 된 스팸 메시지는 30 일 동안 보존 됩니다. 관리자는 콘텐츠 필터 정책을 통해 이 값을 낮출 수 있습니다. 
    
- **End-user spam quarantine notifications** By default, if enabled, end-user spam quarantine notifications are sent every 3 days. They can be configured to be sent every 1 to 15 days. 
    
- **보고 및 메시지 추적 제한** 보고 및 메시지 추적 제한에 대 한 자세한 내용은 [reporting and message trace In Exchange Online Protection](https://go.microsoft.com/fwlink/?LinkId=394248)의 "보고 및 메시지 추적 데이터 사용 가능 여부 및 대기 시간" 섹션을 참조 하십시오.
    
### <a name="limits-across-eop-options"></a>EOP 옵션별 제한

|**기능**|****EOP 독립 실행형****|****EOP 기능: Exchange Online****|****Exchange Enterprise CAL with Services****|
|:-----|:-----|:-----|:-----|
|도메인 제한  <br/> |900  <br/> |900  <br/> |900  <br/> |
|메시지 크기 제한(첨부 파일 포함)  <br/> |150MB  <br/> |150MB  <br/> |150MB  <br/> |
|받는 사람 제한  <br/> |위의 "받는 사람 제한" 참조  <br/> |호스트된 사서함에서 보낼 경우 받는 사람 500명. 다른 시나리오의 경우 위의 "받는 사람 제한" 참조  <br/> |위의 "받는 사람 제한" 참조  <br/> |
|수신 허용 제한  <br/> |항목 1024개  <br/> |항목 1024개  <br/> ||
|정책 당 차단 된 보낸 사람 제한  <br/> |항목 1024개  <br/> |항목 1024개  <br/> ||
|IP 허용 목록 또는 IP 차단 목록 제한  <br/> |항목 1273개  <br/> |항목 1273개  <br/> |항목 1273개  <br/> |
|지연 메시지 제한  <br/> |1 일, 15 분 마다 다시 시도  <br/> |1 일, 15 분 마다 다시 시도  <br/> |1 일, 15 분 마다 다시 시도  <br/> |
|스팸 격리 보존 기간  <br/> |기본적으로 30 일 이지만 낮출 수 있음  <br/> |기본적으로 30 일 이지만 낮출 수 있음  <br/> |기본적으로 30 일 이지만 낮출 수 있음  <br/> |
|최종 사용자 스팸 격리 알림  <br/> |기본적으로 3일이지만 1일에서 15일 사이로 구성할 수 있음  <br/> |기본적으로 3일이지만 1일에서 15일 사이로 구성할 수 있음  <br/> |기본적으로 3일이지만 1일에서 15일 사이로 구성할 수 있음  <br/> |
   

