---
title: 보고 기능 및 문제 해결 도구
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-reporting-features-and-troubleshooting-tools
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
ms.assetid: 7a89aaf4-747a-434a-a20b-ebc1ee10c742
description: Microsoft Exchange Online EAC(Exchange 관리 센터)에서 다양한 보고 기능을 제공합니다.
ms.openlocfilehash: a2a0f2f749733b32b9b0996fb368739bb42b523f
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/24/2021
ms.locfileid: "59671802"
---
# <a name="reporting-features-and-troubleshooting-tools"></a>보고 기능 및 문제 해결 도구

Microsoft Exchange Online EAC(Exchange 관리 센터)에서 다양한 보고 기능을 제공합니다.
  
## <a name="reporting-features"></a>보고 기능

Exchange Online 보고 통합 Microsoft 365 관리 센터 다운로드하거나 웹 서비스를 사용하여 Excel 보고서에 액세스할 수 있습니다.
  
### <a name="reporting-in-the-microsoft-365-admin-center"></a>보고서의 Microsoft 365 관리 센터

보고서 페이지에는 사서함 및 그룹에 대한 Microsoft 365 관리 센터 정보를 제공하는 보고서가 있습니다. 예를 들어 하나의 보고서에는 일, 주, 월 또는 연도로 만들어지거나 삭제된 그룹 수가 나열됩니다. 또한 새 사서함 및 삭제된 사서함과 활성 및 비활성 사서함에 대한 요약 보고서도 있습니다. 
  
또한 Microsoft 365 관리 센터 보고서 페이지에는 메시지 트래픽, 스팸 및 맬웨어 검색, Exchange 전송 규칙 또는 DLP(데이터 손실 방지) 정책의 영향을 받는 메시지에 대한 정보를 제공하는 메시징 데이터 보고서가 포함되어 있습니다. 보호, 규칙 및 DLP에 대한 향상된 보고서에서는 Exchange Online 관리자에게 대화형 보고 환경이 제공됩니다. 이러한 보고서에서는 개별 메시지에 대한 세부 정보로 드릴다운할 수 있는 기능과 함께 요약 데이터가 제공됩니다.
  
각 구독에서 사용할 수 있는 보고서에 대한 자세한 내용은 Reports를 [참조하십시오.](../office-365-platform-service-description/reports.md) Microsoft 365 관리 센터 보고서 페이지에 대한 자세한 내용은 Microsoft 365 관리 센터 서비스 사용 현황에 대한 보고서 보기 및 [](/exchange/monitoring/use-mail-protection-reports)다운로드 및 Office 365 메일 보호 보고서를 사용하여 맬웨어, 스팸 및 규칙 검색에 대한 데이터 보기를 참조하세요. [](/microsoft-365/admin/activity-reports/activity-reports)
  
### <a name="reporting-using-the-excel-reporting-workbook"></a>Excel 보고 통합 문서를 사용하여 보고

Excel 2013 보고 통합 문서를 사용하여 드릴다운 기능을 통해 요약 보고서를 확인할 수도 있습니다. 그러나 대신 고급 Microsoft 365 관리 센터 사용하는 것이 좋습니다. Excel 2013 보고 통합 문서는 향후 더 이상 사용되지 않을 예정입니다. 개요에 대한 자세한 내용과 통합 문서를 다운로드 및 설치하기 위한 링크는 다음 [다운로드 페이지](https://go.microsoft.com/fwlink/p/?LinkId=271776)를 참조하십시오. 통합 문서 사용 방법에 대한 자세한 내용은 [Excel 보고 통합 문서를 사용한 메일 보호 보고서](/previous-versions/exchange-server/exchange-150/jj945734(v=exchg.150))를 참조하세요. 
  
### <a name="reporting-using-web-services"></a>Reporting using web services

사용자 지정 보고서를 만들 수 있는 프로그래밍 인터페이스인 REST/OData 테넌트 보고 웹 서비스를 사용하여 사서함, 그룹 및 메시징 데이터에 대한 요약 보고서 및 자세한 보고서에 액세스할 수 있습니다. 자세한 내용은 Office 365 [보고 웹 서비스를 참조하세요.](/previous-versions/office/developer/o365-enterprise-developers/jj984325(v=office.15))
  
## <a name="reporting-features-and-troubleshooting-tools-in-the-eac"></a>EAC의 보고 기능 및 문제 해결 도구

Exchange 관리 센터에서 다음 보고 기능 및 문제 해결 도구를 사용할 수 있습니다.
  
### <a name="trace-an-email-message"></a>전자 메일 메시지 추적

메시지 추적 기능을 사용하면 관리자로서 전자 메일 메시지가 사용자 서비스에서 통과하는 전자 메일 메시지를 Exchange Online 있습니다. 서비스에서 대상 전자 메일 메시지를 수신, 거부, 지연 또는 배달할지 여부를 결정하는 데 도움이 됩니다. 이를 통해 사용자의 질문에 효율적으로 답변하고 메일 흐름 문제를 해결할 수 있으며 기술 지원에 문의하여 도움을 받을 필요가 없습니다.
  
> [!IMPORTANT]
> 일반 문제 및 추세 문제를 해결하려면 보고 도구를 사용하여 해당 데이터를 가져옵니다. 메시지에 대한 세부 정보가 필요한 단일 지점에 대해서는 메시지 추적 도구를 사용합니다. 
  
메시지 추적 기능에 대한 자세한 내용은 [전자 메일 메시지 추적](/exchange/monitoring/trace-an-email-message/trace-an-email-message)을 참조하세요.
  
### <a name="auditing-reports"></a>감사 보고서

감사 로깅을 사용하면 관리자가 수행한 특정 변경을 추적하여 구성 문제를 해결하고 규정, 준수 및 소송 요구 사항을 따르는 데 도움이 될 수 있습니다. Exchange Online에서는 두 가지 유형의 감사 로깅을 제공합니다.
  
- 관리자 감사 로깅은 관리자가 수행한 작업을 기록합니다. 따라서 구성 문제를 해결하거나 보안 관련 또는 준수 관련 문제의 원인을 파악하는 데 도움이 될 수 있습니다. 
    
- 사서함 감사 로깅은 사서함 소유자 이외의 사용자가 사서함에 액세스할 때마다 기록합니다. 따라서 사서함에 액세스한 사용자와 해당 사용자가 수행한 작업을 확인하는 데 도움이 될 수 있습니다. 
    
감사 로깅에 대한 자세한 내용은 [감사 보고서](/exchange/security-and-compliance/exchange-auditing-reports/exchange-auditing-reports)를 참조하세요.
  
### <a name="unified-messaging-reports"></a>통합 메시징 보고서

이 보고서를 사용하여 Exchange Online 조직에서 UM(통합 메시징)을 모니터링하고 관련 문제를 해결할 수 있습니다. 자세한 내용은 [음성 사서함 호출에 대한 보고서 실행](/exchange/voice-mail-unified-messaging/run-voice-mail-call-reports/run-voice-mail-call-reports)을 참조하세요.
  
## <a name="feature-availability"></a>기능 가용성

계획, 독립 실행형 옵션 및온-프레미스 솔루션에서 기능 가용성을 확인한 경우 서비스 [Exchange Online 참조하세요.](exchange-online-service-description.md)
