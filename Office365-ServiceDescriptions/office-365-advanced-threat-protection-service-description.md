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
description: Microsoft Office 365 Advanced Threat Protection (ATP)은 강력한 제로 보호를 제공 하 여 알 수 없는 맬웨어 및 바이러스 로부터 조직을 보호 하는 클라우드 기반 전자 메일 필터링 서비스 이며, 다음을 보호 하는 기능을 포함 합니다. 실시간으로 해로운 링크에서 조직으로 구성 합니다.
ms.openlocfilehash: 30b57b2bc0150be299861626aa17aa32fa5d3f6f
ms.sourcegitcommit: 2095e87cbb266c798474c33124a75bb32409040f
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 12/11/2019
ms.locfileid: "39969974"
---
# <a name="office-365-advanced-threat-protection-service-description"></a>Office 365 Advanced Threat Protection 서비스 설명

Microsoft Office 365 Advanced Threat Protection (ATP)은 강력한 제로 보호를 제공 하 여 알 수 없는 맬웨어 및 바이러스 로부터 조직을 보호 하는 클라우드 기반 전자 메일 필터링 서비스 이며, 다음을 보호 하는 기능을 포함 합니다. 실시간으로 해로운 링크에서 조직으로 구성 합니다. ATP에는 조직에서 발생 하는 공격 종류를 관리자에 게 제공 하는 다양 한 보고 및 URL 추적 기능이 있습니다.

다음은 메시지 보호에 ATP를 사용할 수 있는 기본 방법입니다.

- Office 365 ATP 필터링 전용 시나리오에서 ATP는 온-프레미스 Exchange 서버 환경 또는 기타 모든 온-프레미스 SMTP 전자 메일 솔루션에 대해 클라우드 기반 전자 메일 보호 기능을 제공 합니다.

- Office 365 ATP를 사용 하도록 설정 하 여 Exchange Online 클라우드 호스트 사서함을 보호할 수 있습니다. Exchange Online에 대 한 자세한 내용은 [Exchange online 서비스 설명을](exchange-online-service-description/exchange-online-service-description.md)참조 하세요.

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

계획 간에 기능을 비교 하려면 [Office 365 For Business 요금제 비교](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) 및 [적절 한 Microsoft 365 Enterprise 솔루션 검색](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans)을 참조 하세요.

## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a>Office 365의 새로운 기능 (Advanced Threat Protection (ATP)

계속 해 서 Office 365 ATP에 새로운 기능을 추가 하 고 있습니다. ATP에 게 제공 되는 새로운 기능 (또는 일반적인 경우 Microsoft 365)에 대 한 자세한 내용은 다음 리소스를 참조 하십시오.

- [Microsoft 365 로드맵](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Office 365 ATP의 새로운 기능](https://docs.microsoft.com/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a>Office 365의 ATP (Advanced Threat Protection)에 대 한 요구 사항

ATP는 Microsoft Exchange Server와 같은 SMTP 메일 전송 에이전트와 함께 사용할 수 있습니다. ATP에서 지원되는 운영 체제, 웹 브라우저, 언어에 대한 자세한 내용은 [Exchange Online Protection의 Exchange 관리 센터](https://go.microsoft.com/fwlink/p/?LinkId=282381)의 "지원되는 브라우저" 및 "지원되는 언어" 섹션을 참조하세요.

## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a>ATP (Advanced Threat Protection) 계획에서의 기능 가용성

각 기능은 아래와 같습니다. Exchange Online은 대개 Office 365 Enterprise 서비스 제품군을 지칭하는 것입니다.

|**기능**|**ATP 계획 1**<br>(이전의 ATP 독립 실행형)|**ATP 계획 2**<br>(이전의 위협 인텔리전스 <br>독립| Office 365 Enterprise E5|
|:-----|:-----|:-----|:-----|
|*구성, 보호 및 검색*|
|[안전한 첨부 파일](#safe-attachments)|예|예|예|
|팀의 안전한 첨부 파일|예|예|예|
|[안전한 링크](#safe-links)|예|예|예|
|팀의 안전한 링크|아니요|아니요|아니요|
|[SharePoint, OneDrive 및 Microsoft 팀에 대 한 ATP](#atp-for-sharepoint-onedrive-and-microsoft-teams)|예|예|예|
|[피싱 방지 정책](#anti-phishing-policies)|예|예|예|
|[실시간 보고서](#real-time-reports)|예|예|예|
|*자동화, 조사, 수정 및 교육*|
|[위협 트래커](#threat-trackers)|아니요|예|예|
|[Explorer](#explorer) (advanced threat 조사의)|아니요|예|예|
|[자동 인시던트 대응](#automated-incident-response)|아니요|예|예|
|[공격 시뮬레이터](#attack-simulator)|아니요|예|예|

## <a name="advanced-threat-protection-atp-capabilities"></a>ATP (Advanced Threat Protection) 기능

### <a name="safe-attachments"></a>안전한 첨부 파일

[ATP 안전한 첨부 파일](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments) 은 알 수 없는 맬웨어 및 바이러스 로부터 보호 하 고, 메시징 시스템을 보호 하기 위한 제로 일 보호를 제공 합니다. 알려진 바이러스/맬웨어 서명이 없는 모든 메시지와 첨부 파일은 ATP가 여러 가지 기계 학습 및 분석 기술을 사용하여 악의적인 의도를 감지하는 특수한 환경으로 라우팅됩니다. 의심스러운 활동이 감지되지 않으면 메시지가 사서함 배달을 위해 릴리스됩니다.

> [!NOTE]
> ATP 안전한 첨부 파일 검사는 Office 365 데이터가 있는 동일한 지역에서 발생 합니다. 데이터 센터 지역에 대 한 자세한 내용은 [어디에 있습니까?](https://products.office.com/where-is-your-data-located?geo=All) 를 참조 하세요.

### <a name="safe-links"></a>안전한 링크

[ATP Safe Links](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links) 기능은 메시지나 Office 문서의 악의적인 url 로부터 사용자를 사전에 보호 합니다. 악성 링크에 액세스할 수 있는 경우 악의적인 링크가 동적으로 차단 되므로이 기능은 링크를 선택할 때마다 유지 됩니다.

다음과 같은 앱의 Url에 대해 안전한 링크를 사용할 수 있습니다.

- Windows 또는 Mac의 Office 365 ProPlus

- 웹 (웹의 Word, 웹의 경우 Excel, 웹의 경우 PowerPoint, 웹의 OneNote)에 대 한 Office

- IOS 및 Android 장치의 Office 앱은 물론 Word, Excel, PowerPoint, Visio의 Windows

> [!NOTE]
> 사용자에 게 ATP<sup>\*</sup>라이선스가 있어야 하 고, Atp 안전한 링크 정책에 포함 되어야 하며, 보호를 위해 해당 장치에 로그인 되어 있어야 합니다.

<sup>\*</sup>조직 전반의 ATP 라이선스 (예: ATP_ENTERPRISE_FACULTY)의 경우에는 개별 사용자에 게 ATP 라이선스를 할당할 필요가 없습니다.

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>SharePoint, OneDrive 및 Microsoft Teams에 대한 ATP

[SharePoint, OneDrive 및 Microsoft 팀의 ATP](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams) 는 팀 사이트 및 문서 라이브러리에서 악의적으로 식별 된 파일을 검색 하 고 차단 하는 데 도움이 됩니다.

### <a name="anti-phishing-policies"></a>피싱 방지 정책

[ATP 피싱 방지](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing) 는 메시지가 피싱 인 경우 메시지에 대 한 표시기를 확인 합니다. 사용자에 게 ATP 정책 (안전한 첨부 파일, 안전한 링크 또는 피싱 방지)이 포함 되어 있는 경우 들어오는 메시지는 메시지를 분석 하는 여러 기계 학습 모델에 의해 평가 되며 구성 된 정책에 따라 적절 한 조치를 취할 수 있습니다.

### <a name="real-time-reports"></a>실시간 보고서

Office 365 보안 & 준수 센터에서 사용할 수 있는 모니터링 기능 보안 및 준수 관리자가 보안 공격이 나 향상 된 수상한 작업과 같은 우선 순위가 높은 문제에 집중할 수 있도록 하는 [실시간 보고서와 정보](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp) 를 포함 합니다. 문제 영역을 강조 표시 하는 것 외에도 smart reports 및 insights에는 데이터를 보고 탐색 하 고 빠른 작업도 수행할 수 있는 권장 사항과 링크가 포함 되어 있습니다.

### <a name="threat-trackers"></a>위협 트래커

[위협 추적기](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers) 는 권한 있는 사용자에 게 조직에 영향을 줄 수 있는 cybersecurity 문제에 대 한 정보를 제공 하는 정보와 관련 된 위젯 및 뷰입니다.

### <a name="explorer"></a>Explorer

Explorer (위협 탐색기 라고도 함)는 승인 된 사용자가 최근 위협을 식별 하 고 분석할 수 있도록 하는 실시간 보고서입니다. 기본적으로이 보고서에는 최근 7 일간의 데이터가 표시 됩니다. 그러나 보기를 수정 하 여 최근 30 일간의 데이터를 표시할 수 있습니다.

Explorer (Office 365 Advanced Threat Protection 계획 2) 및 실시간 검색 (Office 365 Advanced Threat Protection 계획 1)에 대 한 자세한 내용은 [Threat Explorer 및 실시간](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)검색을 참조 하십시오.

### <a name="automated-incident-response"></a>자동 인시던트 대응

Office 365에서 사용할 수 있는 [자동화 된 문제 대응](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air) (AIR) 기능 현재로 서는 잘 알려진 위협에 대응 하 여 자동 조사 프로세스를 실행할 수 있습니다. 자동화 된 특정 조사 작업을 통해 보안 운영 팀이 보다 효율적이 고 효율적으로 작동할 수 있습니다. 악의적인 전자 메일 메시지 삭제와 같은 수정 작업은 보안 운영 팀의 승인에 따라 수행 됩니다. 자세한 내용은 [Office 365에서 AIR works](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office)를 참조 하세요.

### <a name="attack-simulator"></a>공격 시뮬레이터

[공격 시뮬레이터](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator) 를 사용 하면 권한 있는 사용자가 조직에서 현실적인 공격 시나리오를 실행할 수 있습니다. 표시 이름 스피어 피싱 공격, 암호 분무 공격, 무작위 암호 공격 등 다양 한 유형의 공격을 사용할 수 있습니다.
