---
title: 보고 기능 및 문제 해결 도구
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-reporting-features-and-troubleshooting-tools
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7a89aaf4-747a-434a-a20b-ebc1ee10c742
description: Microsoft Exchange Online에서는 다양 한 Exchange 관리 센터 (EAC) 및 로그 아웃 기능을 보고 합니다.
ms.openlocfilehash: b95ab58d2ec09f5e6bae32a3902e92deb75d789f
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036488"
---
# <a name="reporting-features-and-troubleshooting-tools"></a>보고 기능 및 문제 해결 도구

Microsoft Exchange Online에서는 다양 한 Exchange 관리 센터 (EAC) 및 로그 아웃 기능을 보고 합니다.
  
## <a name="reporting-features"></a>보고 기능

Exchange Online 고객은 Excel 보고 통합 문서를 다운로드하거나 웹 서비스를 사용하여 Office 365 관리 센터의 보고서에 액세스할 수 있습니다.
  
### <a name="reporting-in-the-office-365-admin-center"></a>Office 365 관리 센터에서 보고

Microsoft Office 365 관리 센터의 보고서 페이지에는 사서함 및 그룹에 대한 요약 정보를 제공하는 보고서가 있습니다. 예를 들면, 만들어지고 삭제된 그룹의 수를 일, 주, 월 또는 연도별로 나열하는 보고서와 새 사서함과 삭제된 사서함, 활성 사서함과 비활성 사서함에 대한 요약 보고서가 있습니다. 
  
그뿐만 아니라 Microsoft Office 365 관리 센터의 보고서 페이지에는 메시지 트래픽, 스팸 및 맬웨어 검색, Exchange 전송 규칙이나 DLP(데이터 손실 방지)로 영향을 받는 메시지에 대한 정보가 제공되는 메시징 데이터 보고서가 있습니다. 보호, 규칙 및 DLP에 대한 향상된 보고서에서는 Exchange Online 관리자에게 대화형 보고 환경이 제공됩니다. 이러한 보고서에서는 개별 메시지에 대한 세부 정보로 드릴다운할 수 있는 기능과 함께 요약 데이터가 제공됩니다.
  
각 Office 365 구독에 사용할 수 있는 보고서에 대한 자세한 내용은 [보고서](../office-365-platform-service-description/reports.md)를 참조하세요. Office 365 관리 센터의 보고서 페이지에 대한 자세한 내용은 [Office 365에서 서비스 사용에 대한 보고서 보기 및 다운로드](https://go.microsoft.com/fwlink/p/?LinkId=401187) 및 [Office 365의 메일 보호 보고서를 사용하여 맬웨어, 스팸 및 규칙 감지에 대한 데이터 보기](https://go.microsoft.com/fwlink/p/?LinkID=401102)를 참조하세요.
  
### <a name="reporting-using-the-excel-reporting-workbook"></a>Excel 보고 통합 문서를 사용하여 보고

Excel 2013 보고 통합 문서를 사용하여 드릴다운 기능을 통해 요약 보고서를 확인할 수도 있습니다. 그러나 이 보고서 대신 향상된 Office 365 관리 센터 보고서를 사용하는 것이 좋습니다. Excel 2013 보고 통합 문서는 향후 더 이상 사용되지 않을 예정입니다. 개요에 대한 자세한 내용과 통합 문서를 다운로드 및 설치하기 위한 링크는 다음 [다운로드 페이지](https://go.microsoft.com/fwlink/p/?LinkId=271776)를 참조하십시오. 통합 문서 사용 방법에 대한 자세한 내용은 [Excel 보고 통합 문서를 사용한 메일 보호 보고서](https://go.microsoft.com/fwlink/p/?LinkId=285211)를 참조하세요. 
  
### <a name="reporting-using-web-services"></a>웹 서비스를 사용하여 보고

사용자 지정 보고서를 만들 수 있는 프로그래밍 인터페이스인 REST/OData 테넌트 보고 웹 서비스를 사용하여 사서함, 그룹 및 메시징 데이터에 대한 요약 보고서와 세부 보고서에 모두 액세스할 수 있습니다. 자세한 내용은 [Office 365 보고 웹 서비스](https://go.microsoft.com/fwlink/p/?LinkId=287041)를 참조하세요.
  
## <a name="reporting-features-and-troubleshooting-tools-in-the-eac"></a>EAC의 보고 기능 및 문제 해결 도구

Exchange 관리 센터에서 다음 보고 기능 및 문제 해결 도구를 사용할 수 있습니다.
  
### <a name="trace-an-email-message"></a>전자 메일 메시지 추적

메시지 추적 기능을 사용하면 전자 메일 메시지가 Exchange Online 서비스를 통과할 때 관리자로서 이를 추적할 수 있습니다. 이렇게 하면 서비스에서 대상 전자 메일 메시지를 수신, 거부, 지연 또는 배달했는지 여부를 확인하는 데 도움이 되며, 사용자의 질문에 효과적으로 답변하고, 메일 흐름 문제를 해결하고, 기술 지원팀에 문의해야 하는 수고를 덜어 줍니다.
  
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

Office 365 계획, 독립 실행형 옵션 및 온-프레미스 솔루션별로 기능 가용성을 확인하려면 [Exchange Online 서비스 설명](exchange-online-service-description.md)을 참조하세요.
  

