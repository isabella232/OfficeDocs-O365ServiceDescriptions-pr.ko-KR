---
title: 보고 기능 및 문제 해결 도구
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-reporting-features-and-troubleshooting-tools
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7a89aaf4-747a-434a-a20b-ebc1ee10c742
description: Microsoft Exchange Online은 EAC (Exchange 관리 센터)에 대 한 다양 한 보고 기능을 제공 합니다.
ms.openlocfilehash: f2cc51c9923be8d399fa2837e5b5fabe3117d5ba
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132602"
---
# <a name="reporting-features-and-troubleshooting-tools"></a>보고 기능 및 문제 해결 도구

Microsoft Exchange Online은 EAC (Exchange 관리 센터)에 대 한 다양 한 보고 기능을 제공 합니다.
  
## <a name="reporting-features"></a>보고 기능

Exchange Online 고객은 Excel 보고 통합 문서를 다운로드 하거나 웹 서비스를 사용 하 여 Microsoft 365 관리 센터의 보고서에 액세스할 수 있습니다.
  
### <a name="reporting-in-the-microsoft-365-admin-center"></a>Microsoft 365 관리 센터의 보고 기능

Microsoft 365 관리 센터의 보고서 페이지에는 사서함 및 그룹에 대 한 요약 정보를 제공 하는 보고서가 있습니다. 예를 들어 한 보고서에는 일, 주, 월 또는 연도에 따라 만들고 삭제 한 그룹 수가 나열 됩니다. 또한 새 사서함 및 삭제 된 우편함 및 활성 및 비활성 사서함에 대 한 요약 보고서도 있습니다. 
  
또한 Microsoft 365 관리 센터의 보고서 페이지에는 메시지 트래픽, 스팸 및 맬웨어 감지, Exchange 전송 규칙이 나 DLP (데이터 손실 방지) 정책의 영향을 받는 메시지에 대 한 정보를 제공 하는 메시징 데이터 보고서가 포함 되어 있습니다. 보호, 규칙 및 DLP에 대한 향상된 보고서에서는 Exchange Online 관리자에게 대화형 보고 환경이 제공됩니다. 이러한 보고서에서는 개별 메시지에 대한 세부 정보로 드릴다운할 수 있는 기능과 함께 요약 데이터가 제공됩니다.
  
각 구독에서 사용할 수 있는 보고서에 대 한 자세한 내용은 [reports](../office-365-platform-service-description/reports.md)를 참조 하십시오. Microsoft 365 관리 센터의 보고서 페이지에 대 한 자세한 내용은 [보기 및 다운로드 보고서-Office 365의 서비스 사용 현황](https://go.microsoft.com/fwlink/p/?LinkId=401187) 및 [메일 보호 보고서를 사용 하 여 맬웨어, 스팸 및 규칙 감지에 대 한 데이터 보기](https://go.microsoft.com/fwlink/p/?LinkID=401102)를 참조 하세요.
  
### <a name="reporting-using-the-excel-reporting-workbook"></a>Excel 보고 통합 문서를 사용하여 보고

Excel 2013 보고 통합 문서를 사용하여 드릴다운 기능을 통해 요약 보고서를 확인할 수도 있습니다. 그러나 향상 된 Microsoft 365 관리 센터 보고서를 대신 사용 하는 것이 좋습니다. Excel 2013 보고 통합 문서는 향후 더 이상 사용되지 않을 예정입니다. 개요에 대한 자세한 내용과 통합 문서를 다운로드 및 설치하기 위한 링크는 다음 [다운로드 페이지](https://go.microsoft.com/fwlink/p/?LinkId=271776)를 참조하십시오. 통합 문서 사용 방법에 대한 자세한 내용은 [Excel 보고 통합 문서를 사용한 메일 보호 보고서](https://go.microsoft.com/fwlink/p/?LinkId=285211)를 참조하세요. 
  
### <a name="reporting-using-web-services"></a>Reporting using web services

사용자 지정 보고서를 만들 수 있는 프로그래밍 인터페이스인 REST/OData 테 넌 트 보고 웹 서비스를 사용 하 여 사서함, 그룹 및 메시징 데이터에 대 한 요약 및 상세 보고서에 모두 액세스할 수 있습니다. 자세한 내용은 [Office 365 Reporting web services](https://go.microsoft.com/fwlink/p/?LinkId=287041)를 참조 하세요.
  
## <a name="reporting-features-and-troubleshooting-tools-in-the-eac"></a>EAC의 보고 기능 및 문제 해결 도구

Exchange 관리 센터에서 다음 보고 기능 및 문제 해결 도구를 사용할 수 있습니다.
  
### <a name="trace-an-email-message"></a>전자 메일 메시지 추적

메시지 추적 기능을 사용 하면 관리자가 Exchange Online 서비스를 통과 하는 전자 메일 메시지를 팔 로우 할 수 있습니다. 이를 통해 대상이 지정 된 전자 메일 메시지의 수신, 거부, 지연 또는 서비스에 의해 전달 되었는지 여부를 확인할 수 있습니다. 이를 통해 사용자의 질문에 효과적으로 대답 하 고 메일 흐름 문제를 해결할 수 있으며 기술 지원 서비스에 문의 하 여 도움을 받을 필요가 없습니다.
  
> [!IMPORTANT]
> 일반 문제 및 추세 문제를 해결하려면 보고 도구를 사용하여 해당 데이터를 가져옵니다. 메시지에 대한 세부 정보가 필요한 단일 지점에 대해서는 메시지 추적 도구를 사용합니다. 
  
메시지 추적 기능에 대한 자세한 내용은 [전자 메일 메시지 추적](https://go.microsoft.com/fwlink/p/?LinkId=271777)을 참조하세요.
  
### <a name="auditing-reports"></a>감사 보고서

감사 로깅을 사용하면 관리자가 수행한 특정 변경을 추적하여 구성 문제를 해결하고 규정, 준수 및 소송 요구 사항을 따르는 데 도움이 될 수 있습니다. Exchange Online에서는 두 가지 유형의 감사 로깅을 제공합니다.
  
- 관리자 감사 로깅은 관리자가 수행한 작업을 기록합니다. 따라서 구성 문제를 해결하거나 보안 관련 또는 준수 관련 문제의 원인을 파악하는 데 도움이 될 수 있습니다. 
    
- 사서함 감사 로깅은 사서함 소유자 이외의 사용자가 사서함에 액세스할 때마다 기록합니다. 따라서 사서함에 액세스한 사용자와 해당 사용자가 수행한 작업을 확인하는 데 도움이 될 수 있습니다. 
    
감사 로깅에 대한 자세한 내용은 [감사 보고서](https://go.microsoft.com/fwlink/p/?LinkId=271779)를 참조하세요.
  
### <a name="unified-messaging-reports"></a>통합 메시징 보고서

이 보고서를 사용하여 Exchange Online 조직에서 UM(통합 메시징)을 모니터링하고 관련 문제를 해결할 수 있습니다. 자세한 내용은 [음성 사서함 호출에 대한 보고서 실행](https://go.microsoft.com/fwlink/p/?LinkId=287042)을 참조하세요.
  
## <a name="feature-availability"></a>기능 가용성

계획, 독립 실행형 옵션 및 온-프레미스 솔루션 별로 기능 가용성을 확인 하려면 [Exchange Online 서비스 설명을](exchange-online-service-description.md)참조 하세요.
  

