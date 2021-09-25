---
title: Exchange Online Protection의 보고 및 메시지 추적
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- reporting-and-message-trace-in-eop
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
ms.assetid: b9263f99-5921-44fd-bb4c-0d487b59a656
description: 이 문서를 읽고 EOP(Microsoft Exchange Online 보호)의 보고 및 메시지 추적에 대해 자세히 알아보습니다.
ms.openlocfilehash: 2a920ba65c98a612d4343b893458b5bb34a4959e
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/24/2021
ms.locfileid: "59672207"
---
# <a name="reporting-and-message-trace-in-exchange-online-protection"></a>Exchange Online Protection의 보고 및 메시지 추적

Microsoft EOP(Exchange Online Protection)에서는 조직의 전체 상태를 확인할 수 있는 다양한 보고서를 제공합니다. 일부 보고서는 EAC(Microsoft 365 관리 센터 관리 센터)에서 사용할 Exchange 있습니다.

모든 EOP 기능에 대한 정보를 찾고 있나요? 자세한 [내용은 Exchange Online Protection 설명을 참조하세요.](exchange-online-protection-service-description.md)

## <a name="microsoft-365-admin-center-reports"></a>Microsoft 365 관리 센터 보고서

보고서 페이지의 Microsoft 365 관리 센터 메시지 트래픽, 스팸 및 맬웨어 검색, 메일 흐름 규칙(전송 규칙) 또는 DLP(데이터 손실 방지) 정책의 영향을 받는 메시지에 대한 정보를 제공합니다. 보호, 규칙 및 DLP에 대한 향상된 보고서에서는 EOP 관리자에게 대화형 보고 환경이 제공됩니다. 이러한 보고서에서는 개별 메시지에 대한 세부 정보로 드릴다운할 수 있는 기능과 함께 요약 데이터가 제공됩니다.

이러한 보고서에 대한 자세한 내용은 메일 보호 보고서를 사용하여 맬웨어, 스팸 및 규칙 검색에 대한 데이터 [보기를 참조하세요.](/exchange/monitoring/use-mail-protection-reports)

## <a name="reporting-using-web-services"></a>Reporting using web services

> [!NOTE]
> 대부분의 REST 기반 보고 기능 및 관련 cmdlet은 2018년 1월에 더 이상 사용이 불가능했습니다. microsoft에서 사용할 수 있는 대체 Microsoft Graph 보고서에 Office 365 Microsoft Graph 사용 현황 보고서 작업의 하위 [Graph.](/graph/api/resources/report)

EOP 독립 실행형 고객에게는 제공되지 않습니다. REST/OData 테넌트 보고 웹 서비스를 사용하여 메시징 데이터에 대한 요약 및 세부 보고서를 프로그래밍식으로 수집할 수 있으며, 사용자 지정 웹 관리 포털에서 웹 페이지에 데이터를 표시할 수 있습니다.

## <a name="message-trace"></a>메시지 추적

EAC의 메시지 추적 기능을 사용하면 관리자로서 EOP를 통과하는 전자 메일 메시지를 따를 수 있습니다. 서비스에서 대상 전자 메일 메시지를 수신, 거부, 지연 또는 배달할지 여부를 결정하는 데 도움이 됩니다. 또한 메시지가 최종 상태에 도달하기 전 메시지에 수행된 작업을 확인할 수 있습니다. 특정 메시지에 대한 자세한 정보를 파악하면 사용자 질문에 효과적으로 대답하고, 메일 흐름 문제를 해결하며, 정책 변경 사항의 유효성을 검사할 수 있을 뿐만 아니라 기술 지원 서비스에 지원을 문의해야 하는 수고를 덜 수 있습니다. 자세한 내용은 [Run a message trace and view the results in the Exchange 참조하세요.](/exchange/monitoring/trace-an-email-message/run-a-message-trace-and-view-results)

## <a name="feature-availability"></a>기능 가용성

계획, 독립 실행형 옵션 및온-프레미스 솔루션에 대한 기능 가용성을 확인 내용은 Exchange Online Protection [설명을 참조하세요.](exchange-online-protection-service-description.md)