---
title: Exchange Online Protection 서비스 설명
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c9127cb4-689c-43b0-b224-a44ebf4374c8
description: Exchange Online Protection의 기능 및 요구 사항에 대해 알아봅니다. Exchange Online Protection을 제공하는 계획 목록과 계획 간 기능 비교가 포함되어 있습니다.
ms.openlocfilehash: 22116d6771ccafe421cf1a3fc1abc87ab4af1d43
ms.sourcegitcommit: 15e92292209454f6778bfef26ecab96bfc71ef5f
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/22/2019
ms.locfileid: "34342088"
---
# <a name="exchange-online-protection-service-description"></a>Exchange Online Protection 서비스 설명

Exchange Online Protection의 기능 및 요구 사항에 대해 알아봅니다. Exchange Online Protection을 제공하는 계획 목록과 계획 간 기능 비교가 포함되어 있습니다.
  
Microsoft EOP(Exchange Online Protection)는 스팸 및 맬웨어로부터 조직을 보호하는 클라우드 기반 전자 메일 필터링 서비스로, 메시징 정책 위반으로부터 조직을 보호하는 기능을 포함합니다. EOP를 사용하면 메시징 환경을 쉽게 관리하고 온-프레미스 하드웨어 및 소프트웨어 유지 관리 시의 부담을 대부분 완화할 수 있습니다.
  
기본적으로 다음과 같은 방식을 통해 메시징 보호에 EOP를 사용할 수 있습니다.
  
- **독립 실행형 시나리오에서** EOP에서는 온-프레미스 Exchange Server 2013 환경, 레거시 Exchange Server 버전 또는 기타 모든 온-프레미스 SMTP 전자 메일 솔루션에 대해 클라우드 기반 전자 메일 보호 기능을 제공 합니다. 
    
- **Microsoft Exchange Online의 일부로** 기본적으로 EOP는 Exchange Online 클라우드 호스트 사서함을 보호합니다. Exchange Online에 대한 자세한 내용은 [Exchange Online 서비스 설명](../exchange-online-service-description/exchange-online-service-description.md)을 참조하세요.
    
- **하이브리드 배포에서** 온-프레미스 사서함과 클라우드 사서함을 함께 사용하는 경우 메시징 환경을 보호하고 메일 라우팅을 제어하도록 EOP를 구성할 수 있습니다. 
    
계획 간에 기능을 비교하려면 [Office 365 비즈니스 에디션 계획 비교](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409)를 참조하세요.
  
Exchange Online Protection을 구입하려면 [Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=294201)을 참조하세요.
  
Office 365 서비스 설명의 페이지를 내보내고 저장하며 인쇄할 수 있습니다. [여러 페이지 내보내기](https://go.microsoft.com/fwlink/?LinkId=403349) 방법을 알아보세요.
  
> [!IMPORTANT]
> EOP는 FOPE(Forefront Online Protection for Exchange)를 대체합니다. 모든 FOPE 고객은 EOP로 전환됩니다. EOP는 FOPE에서 제공되었던 보호 및 제어 기능을 제공할 뿐 아니라 추가 기능도 포함합니다. FOPE에서 EOP로의 전환에 대한 자세한 내용은 [FOPE(Forefront Online Protection for Exchange) 전환 센터](http://www.movetoeop.com)를 참조하세요. 
  
## <a name="whats-new-in-exchange-online-protection-eop"></a>EOP(Exchange Online Protection)의 새로운 기능

EOP의 새로운 기능에 대한 자세한 내용은 [Exchange Online Protection의 새로운 기능](https://go.microsoft.com/fwlink/p/?LinkId=320390)을 참조하세요. FOPE와 EOP 간의 기능 비교는 [FOPE와 EOP의 기능 비교](https://go.microsoft.com/fwlink/p/?LinkId=320391)를 참조하세요.
  
## <a name="exchange-online-protection-eop-plans"></a>EOP(Exchange Online Protection) 계획

EOP는 다음의 구독 계획을 통해 사용할 수 있습니다.
  
|**계획**|**설명**|
|:-----|:-----|
|[EOP 독립 실행형](https://go.microsoft.com/fwlink/p/?LinkId=294201) <br/> |EOP가 온-프레미스 사서함을 보호합니다.  <br/> |
|[Exchange Online의 EOP 기능](https://go.microsoft.com/fwlink/p/?LinkId=294197) <br/> |EOP가 Exchange Online 클라우드 호스트 사서함을 보호합니다.  <br/> |
|[Exchange Enterprise CAL with Services](https://go.microsoft.com/fwlink/p/?LinkId=293699) <br/> |EOP에는 EOP 독립 실행형 같이 온-프레미스 사서함을 보호하고 웹 서비스를 사용하는 DLP(데이터 손실 방지) 및 보고 기능이 포함됩니다.  <br/> |
   
### <a name="exchange-enterprise-cal-with-services-features"></a>Exchange Enterprise CAL with Services 기능

Microsoft Exchange Enterprise CAL with Services에서는 온-프레미스 메시징 환경을 위한 EOP의 전자 메일 보호 기능과 함께 다음과 같은 기능을 제공합니다.
  
- [DLP(데이터 손실 방지)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)
    
- [웹 서비스를 사용하여 보고](reporting-and-message-trace.md#reporting-using-web-services)
    
Exchange Enterprise CAL with Services 라이선스에 대한 자세한 내용은 [Exchange Server 2013 라이선스](https://go.microsoft.com/fwlink/p/?LinkId=293699)를 참조하세요.
  
Exchange Enterprise CAL with Services 라이선스를 보유한 상태에서 서비스를 프로비전하려는 경우 [EOP 서비스 설정](https://go.microsoft.com/fwlink/p/?LinkId=320397)의 지침을 따르세요. 설정 단계는 EOP 독립 실행형 설정 단계와 동일합니다.
  
> [!NOTE]
> Exchange Enterprise CAL with Services의 새 기능은 EOP 독립 실행형이 아닌 Exchange Online과 같은 시기에 배포됩니다. EOP 독립 실행형과 Exchange Online/Exchange Enterprise CAL with Services의 배포 일정은 약간 다를 수도 있습니다. 
  
## <a name="requirements-for-exchange-online-protection-eop"></a>EOP(Exchange Online Protection)에 대한 요구 사항

EOP는 Microsoft Exchange Server 2013과 같은 모든 SMTP 메일 전송 에이전트와 함께 사용할 수 있습니다. EOP에서 지원되는 운영 체제, 웹 브라우저 및 언어에 대한 자세한 내용은 [Exchange Online Protection의 Exchange 관리 센터](https://go.microsoft.com/fwlink/p/?LinkId=282381)의 "지원되는 브라우저" 및 "지원되는 언어" 섹션을 참조하세요.
  
## <a name="limits"></a>제한

EOP의 제한은 [Exchange Online Protection 제한](exchange-online-protection-limits.md)을 참조하세요.
  
## <a name="feature-availability-across-exchange-online-protection-eop-plans"></a>EOP(Exchange Online Protection) 계획에서의 기능 가용성

각 기능은 아래와 같습니다. EOP 기능에 대한 자세한 내용을 보려면 표에 있는 링크를 클릭하세요. Exchange Online이 언급된 경우 대개 Office 365 Enterprise 서비스 제품군을 지칭하는 것입니다.
  
|||||
|:-----|:-----|:-----|:-----|
|**기능** <br/> |**EOP 독립 실행형** <br/> |**Exchange Online의 EOP 기능** <br/> |**Exchange Enterprise CAL with Services** <br/> |
|[메일 받는 사람](recipient-domain-and-company-management.md#mail-recipients) <br/> |예<sup>1</sup> <br/> |예<sup>1</sup> <br/> |예  <br/> |
|[관리자 역할 그룹 권한](recipient-domain-and-company-management.md#admin-role-group-permissions) <br/> |예<sup>2</sup> <br/> |예  <br/> |예  <br/> |
|[도메인 관리](recipient-domain-and-company-management.md#domain-management) <br/> |예<sup>3</sup> <br/> |예<sup>3</sup> <br/> |예<sup>3</sup> <br/> |
|[하위 도메인 일치](recipient-domain-and-company-management.md#match-subdomains) <br/> |예  <br/> |예  <br/> |아니요  <br/> |
|[DBEB(디렉터리 기반 Edge 차단)](recipient-domain-and-company-management.md#directory-based-edge-blocking-dbeb) <br/> |예  <br/> |예  <br/> |예  <br/> |
|[전송 규칙](messaging-policy-and-compliance-servicedesc.md#transport-rules) <br/> |예 <sup>3, 4, 14</sup> <br/> |예 <sup>3, 4, 14</sup> <br/> |예  <br/> |
|[감사 로깅](messaging-policy-and-compliance-servicedesc.md#audit-logging) <br/> |예<sup>5</sup> <br/> |예  <br/> |예  <br/> |
|[DLP(데이터 손실 방지)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp) <br/> |아니요  <br/> |있음  <br/> |예<sup>6</sup> <br/> |
|[Office 365 메시지 암호화](messaging-policy-and-compliance-servicedesc.md#office-365-message-encryption) <br/> |예<sup>12</sup> <br/> |예  <br/> |예<sup>12</sup> <br/> |
|[스팸 방지 보호 기능](anti-spam-and-anti-malware-protection-eop.md#anti-spam-protection)(기본 제공)  <br/> |예  <br/> |예  <br/> |예  <br/> |
|[스팸 방지 정책 사용자 지정](anti-spam-and-anti-malware-protection-eop.md#customize-anti-spam-policies) <br/> |예<sup>7</sup> <br/> |예  <br/> |예  <br/> |
|[맬웨어 방지 보호 기능](anti-spam-and-anti-malware-protection-eop.md#anti-malware-protection)(기본 제공)  <br/> |예<sup>13</sup> <br/> |예  <br/> |예  <br/> |
|[맬웨어 방지 정책 사용자 지정](anti-spam-and-anti-malware-protection-eop.md#customize-anti-malware-policies) <br/> |예  <br/> |예  <br/> |예  <br/> |
|[격리](anti-spam-and-anti-malware-protection-eop.md#quarantine): 관리자 관리  <br/> |예  <br/> |예  <br/> |예  <br/> |
|[격리](anti-spam-and-anti-malware-protection-eop.md#quarantine): 최종 사용자 자기 관리  <br/> |예  <br/> |예  <br/> |예  <br/> |
|[Microsoft Office Outlook용 정크 메일 보고 추가 기능](anti-spam-and-anti-malware-protection-eop.md#junk-email-reporting-add-in-for-microsoft-office-outlook) <br/> |예  <br/> |예  <br/> |예  <br/> |
|[Outlook Web App의 정크 메일 보고 기능](anti-spam-and-anti-malware-protection-eop.md#junk-email-reporting-in-outlook-web-app) <br/> |예<sup>8</sup> <br/> |<sup>8</sup> <br/> |<sup>8</sup> <br/> |
|[Office 365와 자체 메일 서버 간의 이메일 라우팅](mail-flow-eop.md#routing-email-between-office-365-and-your-own-email-servers) <br/> |예  <br/> |예  <br/> |예  <br/> |
|[신뢰할 수 있는 파트너와의 보안 메시징](mail-flow-eop.md#secure-messaging-with-a-trusted-partner) <br/> |예  <br/> |예  <br/> |예  <br/> |
|[수신 허용 목록에 파트너의 IP 주소 추가](mail-flow-eop.md#safe-listing-a-partners-ip-address) <br/> |예  <br/> |예  <br/> |예  <br/> |
|[조건부 메일 라우팅](mail-flow-eop.md#conditional-mail-routing) <br/> |예  <br/> |예  <br/> |예  <br/> |
|[하이브리드 메일 라우팅](mail-flow-eop.md#hybrid-mail-routing) <br/> |예  <br/> |예  <br/> |예  <br/> |
|[Microsoft 365 관리 센터 보고서](reporting-and-message-trace.md#microsoft-365-admin-center-reports)<br/> |예<sup>9</sup> <br/> |예<sup>10</sup> <br/> |예 <sup>9, 10</sup> <br/> |
|[Excel 다운로드 응용 프로그램 보고서](reporting-and-message-trace.md#excel-download-application-reports) <br/> |예  <br/> |예  <br/> |예<sup>11</sup> <br/> |
|[웹 서비스를 사용하여 보고](reporting-and-message-trace.md#reporting-using-web-services) <br/> |아니요  <br/> |예  <br/> |예  <br/> |
|[메시지 추적](reporting-and-message-trace.md#message-trace) <br/> |예<sup>15</sup> <br/> |예<sup>15</sup> <br/> |예  <br/> |
|[Microsoft 365 관리 센터에 대 한 액세스 권한](administration-and-management-eop.md#access-to-the-microsoft-365-admin-center) <br/> |예  <br/> |예  <br/> |예  <br/> |
|[Exchange 관리 센터 액세스](administration-and-management-eop.md#access-to-the-exchange-admin-center)(EAC)  <br/> |예  <br/> |예  <br/> |예  <br/> |
|[원격 Windows PowerShell 액세스](administration-and-management-eop.md#remote-windows-powershell-access) <br/> |예<sup>2</sup> <br/> |예  <br/> |예  <br/> |
   
> [!NOTE]
> <sup>1</sup> 메일 사용자는 "사서함"으로 정의되며 외부 메일 연락처와 마찬가지로 EAC(Exchange 관리 센터)에서 직접 추가, 제거 및 관리할 수 있습니다. 
 <br/><sup>2</sup> RBAC 사용자 지정은 해당하지 않습니다. 관리자 역할만 해당합니다. 
 <br/> <sup>3</sup> EAC에서 관리되는 도메인을 볼 수 있으며 도메인 유형을 편집할 수 있습니다. 다른 모든 도메인 관리는 Microsoft 365 관리 센터에서 수행 해야 합니다. 
 <br/><sup>4</sup> EOP와 Exchange Online의 사용 가능한 유연한 조건 및 동작은 서로 다릅니다. EOP에서 사용 가능한 조건 및 동작 목록은 [전송 규칙 조건](https://go.microsoft.com/fwlink/p/?LinkId=320392) 및 [전송 규칙 동작](https://go.microsoft.com/fwlink/p/?LinkId=320393)을 참조하세요. Exchange Online에서 사용 가능한 조건 및 동작 목록은 [전송 규칙 조건](https://go.microsoft.com/fwlink/p/?LinkId=320394) 및 [전송 규칙 동작](https://go.microsoft.com/fwlink/p/?LinkId=320395)을 참조하세요. 
 <br/><sup>5</sup> EOP 감사 보고서는 사서함에 대한 정보가 제외된, Exchange Online 감사 보고서의 하위 집합입니다. 
 <br/> <sup>6</sup> Exchange Enterprise CAL with Services 고객은 DLP 정책 팁을 사용할 수 없습니다.  <br/><sup>7</sup> 기본 콘텐츠 필터 동작은 스팸 메시지를 받는 사람의 정크 메일 폴더로 이동하는 것입니다. 온-프레미스 사서함에서 이 동작이 작동하도록 하려면 EOP에서 추가한 스팸 헤더를 검색하도록 온-프레미스 서버에서 Exchange 전송 규칙 두 개를 구성해야 합니다. 자세한 내용은 [스팸이 각 사용자의 정크 메일 폴더로 라우팅되는지 확인](https://go.microsoft.com/fwlink/p/?LinkId=320396)을 참조하세요. 
 <br/><sup>8</sup> 이 기능은 사서함이 EOP에 의해 필터링되는 Exchange Server 2013 SP1(서비스 팩 1) 고객에게 제공되며 Exchange Online 고객에게도 곧 제공될 예정입니다. 
 <br/><sup>9</sup> EOP 보고서는 사서함에 대한 정보를 제외한 Exchange Online 보고서의 하위 집합입니다.
 <br/><sup>10</sup> DLP 보고서가 포함됩니다. 
 <br/><sup>11</sup> Exchange Enterprise CAL with Services 고객은 **Exchange Online Protection** 서비스가 아니라 **Exchange Online** 서비스를 선택하여 통합 문서를 설치해야 합니다. 
 <br/><sup>12</sup> Azure Information protection을 구입 하 고 Exchange online Protection을 사용 하 여 exchange online을 통해 전자 메일을 라우팅하는 온-프레미스 고객에 게 지원 됩니다. 
 <br/> <sup>13</sup> 인바운드 및 아웃바운드 메시지는 검사하지만 조직의 보낸 사람이 조직의 받는 사람에게 보낸 내부 메시지는 검사하지 않습니다. 
 <br/><sup>14</sup> EOP 및 Exchange Online에서 사용할 수 있는 조건자와 작업은 각기 다릅니다. 
 <br/> <sup>15</sup> 하이브리드 설치는 하이브리드 마법사를 통해 사용할 수 없지만 Exchange SP1이 있는 경우에는 수동으로 설정할 수 있습니다. 