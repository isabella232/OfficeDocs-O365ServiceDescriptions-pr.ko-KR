---
title: 보고 및 메시지 추적
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- reporting-and-message-trace-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: b9263f99-5921-44fd-bb4c-0d487b59a656
description: Microsoft EOP(Exchange Online Protection)에서는 조직의 전체 상태를 확인할 수 있는 다양한 보고서를 제공합니다. 일부 보고서는 Microsoft 365 관리 센터에서 사용할 수 있고, 일부는 EAC (Exchange 관리 센터)에서 사용할 수 있습니다.
ms.openlocfilehash: d4e0f1104bfc87f5641cc241d2a526e8d56f0d1a
ms.sourcegitcommit: 2b9f68f7731dfd6f9d3f33e31e6303e81985ebb2
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 11/26/2019
ms.locfileid: "39262671"
---
# <a name="reporting-and-message-trace"></a>보고 및 메시지 추적

Microsoft EOP(Exchange Online Protection)에서는 조직의 전체 상태를 확인할 수 있는 다양한 보고서를 제공합니다. 일부 보고서는 Microsoft 365 관리 센터에서 사용할 수 있고, 일부는 EAC (Exchange 관리 센터)에서 사용할 수 있습니다.

모든 EOP 기능에 대 한 정보를 찾으십니까? [Exchange Online Protection 서비스 설명을](exchange-online-protection-service-description.md)참조 하세요.

## <a name="microsoft-365-admin-center-reports"></a>Microsoft 365 관리 센터 보고서

Microsoft 365 관리 센터의 보고서 페이지에서는 메시지 트래픽, 스팸 및 맬웨어 감지, 메일 흐름 규칙 (전송 규칙이 라고도 함) 또는 DLP (데이터 손실 방지) 정책과 관련 된 메시지에 대 한 정보를 제공 합니다. 보호, 규칙 및 DLP에 대한 향상된 보고서에서는 EOP 관리자에게 대화형 보고 환경이 제공됩니다. 이러한 보고서에서는 개별 메시지에 대한 세부 정보로 드릴다운할 수 있는 기능과 함께 요약 데이터가 제공됩니다.

이러한 보고서에 대 한 자세한 내용은 [Use mail protection reports In Office 365에서 맬웨어, 스팸 및 규칙 감지에 대 한 데이터 보기](https://docs.microsoft.com/exchange/monitoring/use-mail-protection-reports)를 참조 하세요.

## <a name="reporting-using-web-services"></a>Reporting using web services

> [!NOTE]
> 대부분의 REST 기반 보고 기능 및 관련 cmdlet은 1 월 2018 일에 더 이상 사용 되지 않습니다. Office 365에서 사용 가능한 대체 Microsoft Graph 보고서에 대 한 자세한 내용은 [Microsoft graph에서 Office 365 사용 현황 보고서 작업](https://go.microsoft.com/fwlink/p/?LinkID=865135)의 하위 주제를 참조 하세요.

EOP 독립 실행형 고객에게는 제공되지 않습니다. REST/OData 테 넌 트 보고 웹 서비스를 사용 하 여 메시징 데이터에 대 한 요약 및 자세한 보고서를 프로그래밍 방식으로 수집 하 고 사용자 지정 웹 관리 포털에 웹 페이지에 데이터를 표시할 수 있습니다.

## <a name="message-trace"></a>Message trace

EAC의 메시지 추적 기능을 사용 하면 관리자가 EOP를 통과 하는 전자 메일 메시지를 팔 로우 할 수 있습니다. 이를 통해 대상이 지정 된 전자 메일 메시지의 수신, 거부, 지연 또는 서비스에 의해 전달 되었는지 여부를 확인할 수 있습니다. 또한 메시지가 최종 상태에 도달하기 전 메시지에 수행된 작업을 확인할 수 있습니다. 특정 메시지에 대한 자세한 정보를 파악하면 사용자 질문에 효과적으로 대답하고, 메일 흐름 문제를 해결하며, 정책 변경 사항의 유효성을 검사할 수 있을 뿐만 아니라 기술 지원 서비스에 지원을 문의해야 하는 수고를 덜 수 있습니다. 자세한 내용은 [메시지 추적 실행 및 Exchange 관리 센터에서 결과 보기](https://docs.microsoft.com/exchange/monitoring/trace-an-email-message/run-a-message-trace-and-view-results)를 참조 하세요.

## <a name="feature-availability"></a>기능 가용성

Office 365 계획, 독립 실행형 옵션 및 온-프레미스 솔루션 별로 기능 가용성을 확인 하려면 [Exchange Online Protection 서비스 설명을](exchange-online-protection-service-description.md)참조 하세요.
