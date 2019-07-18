---
title: Office 365 Advanced Threat Protection 서비스 설명
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Office 365 Advanced Threat Protection (ATP)은 강력한 제로 보호를 제공 하 여 알 수 없는 맬웨어 및 바이러스 로부터 조직을 보호 하는 클라우드 기반 전자 메일 필터링 서비스 이며, 다음을 보호 하는 기능을 포함 합니다. 실시간으로 해로운 링크에서 조직으로 구성 합니다. ATP에는 조직에서 발생 하는 공격 종류를 관리자에 게 제공 하는 다양 한 보고 및 URL 추적 기능이 있습니다.
ms.openlocfilehash: a54d0fddae4430b450b944781cbeca1cbb1e414f
ms.sourcegitcommit: 96dc758c790ddaf05f5c2b836451b417729cf119
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/18/2019
ms.locfileid: "35776419"
---
# <a name="office-365-advanced-threat-protection-service-description"></a>Office 365 Advanced Threat Protection 서비스 설명

Microsoft Office 365 Advanced Threat Protection (ATP)은 강력한 제로 보호를 제공 하 여 알 수 없는 맬웨어 및 바이러스 로부터 조직을 보호 하는 클라우드 기반 전자 메일 필터링 서비스 이며, 다음을 보호 하는 기능을 포함 합니다. 실시간으로 해로운 링크에서 조직으로 구성 합니다. ATP에는 조직에서 발생 하는 공격 종류를 관리자에 게 제공 하는 다양 한 보고 및 URL 추적 기능이 있습니다.
  
다음은 메시지 보호에 ATP를 사용할 수 있는 기본 방법입니다.
  
- Office 365 ATP 필터링 전용 시나리오에서 ATP는 온-프레미스 Exchange 서버 환경 또는 기타 모든 온-프레미스 SMTP 전자 메일 솔루션에 대해 클라우드 기반 전자 메일 보호 기능을 제공 합니다.
    
- Office 365 ATP를 사용 하도록 설정 하 여 Exchange Online 클라우드 호스트 사서함을 보호할 수 있습니다. Exchange Online에 대한 자세한 내용은 [Exchange Online 서비스 설명](exchange-online-service-description/exchange-online-service-description.md)을 참조하세요.
    
- 하이브리드 배포에서는 인바운드 전자 메일 필터링에 대 한 Exchange Online 보호와 함께 온-프레미스 및 클라우드 사서함을 함께 사용 하는 경우 메시징 환경을 보호 하 고 메일 라우팅을 제어 하도록 ATP를 구성할 수 있습니다.
    
## <a name="office-365-advanced-threat-protection-atp-availability"></a>Office 365 ATP (Advanced Threat Protection) 가용성

ATP는 Office 365 Enterprise E5, Office 365 교육 A5 및 Microsoft 365 Business에 포함 되어 있습니다. 
  
ATP를 다음 Exchange 및 Office 365 구독 계획에 추가할 수 있습니다. 
  
- Exchange Online 요금제 1
    
- Exchange Online 계획 2
    
- Exchange Online Kiosk
    
- Exchange Online Protection
    
- Office 365 Business Essentials
    
- Office 365 Business Premium
    
- Office 365 Enterprise E1
    
- Office 365 Enterprise E3
    
- Office 365 Enterprise F1
    
- Office 365 A1
    
- Office 365 A3
    
Office 365 Advanced threat Protection을 구입 하려면 [office 365 Advanced Threat protection](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content)를 참조 하세요.
  
계획 간에 기능을 비교 하려면 [Office 365 For Business 요금제 비교](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) 및 [적절 한 Microsoft 365 Enterprise 솔루션 검색](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans)을 참조 하세요.
  
## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a>Office 365의 새로운 기능 (Advanced Threat Protection (ATP)

계속 해 서 Office 365 ATP에 새로운 기능을 추가 하 고 있습니다. 다음은 몇 가지 새로운 기능과 ATP 정책을 검토 하 고 업데이트 하기 위한 호출의 목록입니다. ATP에 게 제공 되는 새로운 기능 (또는 일반적인 경우 Microsoft 365)에 대 한 자세한 내용은 [microsoft 365 로드맵을](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)참조 하세요.

|기능 업데이트  |작업 항목  |
|---------|---------|
|[Office 365 위협 인텔리전스](https://docs.microsoft.com/office365/securitycompliance/office-365-ti) (TI) 기능은 이제 ATP 계획 2의 일부로 위협 조사 및 응답 기능을 합니다. [자동 조사 및 응답과](https://docs.microsoft.com/office365/securitycompliance/automated-investigation-response-office)같은 새로운 기능과 [위협 탐색기](https://docs.microsoft.com/office365/securitycompliance/use-explorer-in-security-and-compliance)에 대 한 향상 된 기능을 제공 합니다.<br/><br/>조직에서 현재 ATP가 없거나 ATP가 있지만 TI가 없는 경우 ATP 계획 1 및 ATP 계획 2의 가용성을 고려 하 여 몇 가지 옵션을 고려해 야 합니다. 자세한 내용은 [Advanced Threat protection (ATP) 계획](#feature-availability-across-advanced-threat-protection-atp-plans) (이 문서의) 및 [Office 365 Advanced Threat protection 요금제 및 가격 책정](https://products.office.com/exchange/advance-threat-protection)에서 기능 가용성을 참조 하십시오. |조직의 구독을 검토 하 고, 필요한 경우 [추가 기능을 구입 하거나 편집](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/buy-or-edit-an-add-on)합니다.  |
|사용자가 Outlook 또는 OWA (Outlook Web Application)를 사용 하는 경우 [ATP 안전한 링크](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links) 는 다시 작성 된 url이 아닌 원래 url을 렌더링 합니다. (이 네이티브 링크 렌더링을 호출 합니다.)<br>조직에서 기본 링크 렌더링을 사용할 수 있는 경우이 기능은 Outlook 365 (간편 실행), OWA 및 Windows 및 Mac OS에서 작동 합니다. |없음         |
|[Office 365 ATP 경고 페이지](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links-warning-pages) 기능은 새로운 색 구성표, 자세한 내용 및 경고 및 권장 사항에도 불구 하 고 사이트를 계속 사용할 수 있는 기능을 제공 합니다. |없음         |
|[ATP Safe Links](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links) protection은 웹에 대 한 Office의 url, 웹의 Word, 웹의 PowerPoint, 웹의 OneNote, 그리고 Mac의 Office 365 ProPlus에 적용 되도록 확장 됩니다.   |[ATP 안전한 링크 정책 검토 및 편집](https://docs.microsoft.com/office365/SecurityCompliance/set-up-atp-safe-links-policies)  |
|보안 &amp; 및 준수 센터의 격리 기능은 [SharePoint Online, 비즈니스용 OneDrive 및 Microsoft 팀을 위해 ATP](https://docs.microsoft.com/office365/SecurityCompliance/atp-for-spo-odb-and-teams)로 확장 됩니다. |[ATP 안전한 첨부 파일 정책 검토 및 편집](https://docs.microsoft.com/office365/SecurityCompliance/set-up-atp-safe-attachments-policies) |
|[ATP 안전한 링크](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links) 보호는 조직 내 사용자 간에 전송 되는 전자 메일에 적용 되도록 확장 됩니다. |[ATP 안전한 링크 정책 검토 및 편집](https://docs.microsoft.com/office365/SecurityCompliance/set-up-atp-safe-links-policies) |
|[ATP 안전한 링크](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links) 보호는 IOS 및 Android 장치의 office 앱은 물론 Word, Excel, PowerPoint, Visio 등의 Office 365 ProPlus 문서에 있는 url 뿐만 아니라 전자 메일의 url에도 적용 되도록 확장 되었습니다.  |[최신 Office 인증](https://docs.microsoft.com/office365/enterprise/modern-auth-for-office-2013-and-2016) 을 사용 하 고 있는지 확인 |

  
## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a>Office 365의 ATP (Advanced Threat Protection)에 대 한 요구 사항

ATP는 Microsoft Exchange Server와 같은 SMTP 메일 전송 에이전트와 함께 사용할 수 있습니다. ATP에서 지원되는 운영 체제, 웹 브라우저, 언어에 대한 자세한 내용은 [Exchange Online Protection의 Exchange 관리 센터](https://go.microsoft.com/fwlink/p/?LinkId=282381)의 "지원되는 브라우저" 및 "지원되는 언어" 섹션을 참조하세요.
  
## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a>ATP (Advanced Threat Protection) 계획에서의 기능 가용성

각 기능은 아래와 같습니다. Exchange Online은 대개 Office 365 Enterprise 서비스 제품군을 지칭하는 것입니다.
  
|**기능**|**ATP 계획 1**<br>(이전의 ATP 독립 실행형)|**ATP 계획 2**<br>(이전의 위협 인텔리전스 <br>독립 | Office 365 Enterprise E5| 
|:-----|:-----|:-----|:-----|
| *구성, 보호 및 검색* | 
|안전한 첨부 파일 |예|예 |예|
|안전한 링크 |예|예 |예 | 
|피싱 방지 정책 |예 |예 |예 |
|SharePoint, OneDrive 및 Microsoft 팀에 대 한 ATP |예 |예 |예|
|팀의 안전한 링크 |예|예 |예 |
|실시간 보고서 |예 |예 |예|
|*자동화, 조사, 교정 및 교육* |
|위협 트래커 |아니요 |예 |예 |
|Explorer (advanced threat 조사의) |아니요 |예 |예 |
|자동화된 조사 및 응답  |아니요 |예 |예 |
|공격 시뮬레이터 |아니요 |예 |예 |

   
## <a name="advanced-threat-protection-atp-capabilities"></a>ATP (Advanced Threat Protection) 기능

### <a name="safe-attachments"></a>안전한 첨부 파일

[ATP 안전한 첨부 파일](https://docs.microsoft.com/office365/securitycompliance/atp-safe-attachments) 은 알 수 없는 맬웨어 및 바이러스 로부터 보호 하 고, 메시징 시스템을 보호 하기 위한 제로 일 보호를 제공 합니다. 알려진 바이러스/맬웨어 서명이 없는 모든 메시지와 첨부 파일은 ATP가 여러 가지 기계 학습 및 분석 기술을 사용하여 악의적인 의도를 감지하는 특수한 환경으로 라우팅됩니다. 의심스러운 활동이 감지되지 않으면 메시지가 사서함 배달을 위해 릴리스됩니다. 

> [!NOTE]
> ATP 안전한 첨부 파일 검사는 Office 365 데이터가 있는 동일한 지역에서 발생 합니다. 데이터 센터 지역에 대 한 자세한 내용은 [어디에 있습니까?](https://products.office.com/where-is-your-data-located?geo=All) 를 참조 하세요. 

### <a name="safe-links"></a>안전한 링크

[ATP Safe Links](https://docs.microsoft.com/Office365/SecurityCompliance/atp-safe-links) 기능은 메시지나 Office 문서의 악의적인 url 로부터 사용자를 사전에 보호 합니다. 악의적인 링크는 동적으로 차단되지만 정상 링크에는 액세스할 수 있으므로 클릭할 때마다 보호 기능이 유지됩니다.

### <a name="anti-phishing-policies"></a>피싱 방지 정책

[ATP 피싱 방지](https://docs.microsoft.com/office365/securitycompliance/atp-anti-phishing) 는 메시지가 피싱 인 경우 메시지에 대 한 표시기를 확인 합니다. 사용자에 게 ATP 정책 (안전한 첨부 파일, 안전한 링크 또는 피싱 방지)이 포함 되어 있는 경우 들어오는 메시지는 메시지를 분석 하는 여러 기계 학습 모델에 의해 평가 되며 구성 된 정책에 따라 적절 한 조치를 취할 수 있습니다.
  
### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>SharePoint, OneDrive 및 Microsoft Teams에 대한 ATP

[SharePoint, OneDrive 및 Microsoft 팀의 ATP](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams) 는 팀 사이트 및 문서 라이브러리에서 악의적으로 식별 된 파일을 검색 하 고 차단 하는 데 도움이 됩니다.

### <a name="real-time-reports"></a>실시간 보고서

Office 365 보안 & 준수 센터에서 사용할 수 있는 모니터링 기능-보안 및 준수 관리자가 보안 공격이 나 증대와 같은 우선 순위가 높은 문제에 집중할 수 있도록 하는 [실시간 보고서 및 통찰력](https://docs.microsoft.com/office365/securitycompliance/view-reports-for-atp) 을 포함 합니다. 의심 스러운 활동 문제 영역을 강조 표시 하는 것 외에도 smart reports 및 insights에는 데이터를 보고 탐색 하 고 빠른 작업도 수행할 수 있는 권장 사항과 링크가 포함 되어 있습니다. 
  
### <a name="threat-trackers"></a>위협 트래커

[위협 추적기](https://docs.microsoft.com/office365/securitycompliance/threat-trackers) 는 권한 있는 사용자에 게 조직에 영향을 줄 수 있는 cybersecurity 문제에 대 한 정보를 제공 하는 정보와 관련 된 위젯 및 뷰입니다.

### <a name="explorer"></a>Explorer

[탐색기](https://docs.microsoft.com/office365/securitycompliance/use-explorer-in-security-and-compliance) (위협 탐색기 라고도 함)은 인증 된 사용자가 최근 위협을 식별 하 고 분석할 수 있도록 하는 실시간 보고서입니다. 기본적으로이 보고서에는 최근 7 일간의 데이터가 표시 됩니다. 그러나 보기를 수정 하 여 최근 30 일간의 데이터를 표시할 수 있습니다. 

### <a name="attack-simulator"></a>공격 시뮬레이터
  
[공격 시뮬레이터](https://docs.microsoft.com/office365/SecurityCompliance/attack-simulator) 를 사용 하면 권한 있는 사용자가 조직에서 현실적인 공격 시나리오를 실행할 수 있습니다. 표시 이름 스피어 피싱 공격, 암호 분무 공격, 무작위 암호 공격 등 다양 한 유형의 공격을 사용할 수 있습니다.