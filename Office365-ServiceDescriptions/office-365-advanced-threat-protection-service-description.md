---
title: Office 365 Advanced Threat Protection 서비스 설명
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Office 365 Advanced Threat Protection (ATP)은 강력한 제로 보호를 제공 하 여 알 수 없는 맬웨어 및 바이러스 로부터 조직을 보호 하는 클라우드 기반 전자 메일 필터링 서비스로, 실시간으로 유해한 링크 로부터 조직을 보호 하는 기능을 포함 합니다.
ms.openlocfilehash: 0e9c7e76cabd9f39a13c16689a4255732617b09d
ms.sourcegitcommit: 0f2d249dfc93432e17344f70b8317a455204f018
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/01/2020
ms.locfileid: "47318945"
---
# <a name="office-365-advanced-threat-protection-service-description"></a>Office 365 Advanced Threat Protection 서비스 설명

Microsoft Office 365 Advanced Threat Protection (ATP)은 강력한 제로 보호를 제공 하 여 알 수 없는 맬웨어 및 바이러스 로부터 조직을 보호 하는 클라우드 기반 전자 메일 필터링 서비스로, 실시간으로 유해한 링크 로부터 조직을 보호 하는 기능을 포함 합니다. ATP에는 조직에서 발생 하는 공격 종류를 관리자에 게 제공 하는 다양 한 보고 및 URL 추적 기능이 있습니다.

다음은 메시지 보호에 ATP를 사용하는 기본 방법입니다.

- Office 365 ATP 필터링 전용 시나리오에서 ATP는 온-프레미스 Exchange Server 환경이나 다른 온-프레미스 SMTP 전자 메일 솔루션에 클라우드 기반 전자 메일 보호를 제공합니다.

- Office 365 ATP를 사용하도록 설정하여 Exchange Online 클라우드 호스트 사서함을 보호할 수 있습니다. Exchange Online에 대 한 자세한 내용은 [Exchange online 서비스 설명을](exchange-online-service-description/exchange-online-service-description.md)참조 하세요.

- 하이브리드 배포에서 온-프레미스 사서함과 클라우드 사서함을 인바운드 전자 메일 필터링용 Exchange Online Protection과 함께 사용하는 경우 메시징 환경을 보호하고 전자 메일 라우팅을 제어하도록 ATP를 구성할 수 있습니다.

## <a name="office-365-advanced-threat-protection-atp-availability"></a>Office 365 ATP (Advanced Threat Protection) 가용성

Office 365 ATP 계획 2는 Office 365 E5, Office 365 A5 및 Microsoft 365 E5에 포함되어 있습니다. Office 365 ATP 계획 1은 Microsoft 365 Business Premium에 포함되어 있습니다.

ATP를 다음 Exchange 및 Microsoft 365 구독 계획에 추가할 수 있습니다.

- Exchange Online 요금제 1

- Exchange Online 계획 2

- Exchange Online Kiosk

- Exchange Online Protection

- Microsoft 365 Business Basic

- Microsoft 365 Business Standard

- Office 365 Enterprise E1

- Office 365 Enterprise E3

- Office 365 Enterprise F3

- Office 365 A1

- Office 365 A3

Office 365 Advanced threat Protection을 구입 하려면 [office 365 Advanced Threat protection](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content)를 참조 하세요.

계획 간에 기능을 비교 하려면 엔터프라이즈를 지원 하 고 [Microsoft 365으로 엔터프라이즈를 변환](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans) [하는 강력한 도구](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) 를 참조 하세요.

## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a>Office 365의 새로운 기능 (Advanced Threat Protection (ATP)

계속 해 서 Office 365 ATP에 새로운 기능을 추가 하 고 있습니다. ATP에 게 제공 되는 새로운 기능 (또는 일반적인 경우 Microsoft 365)에 대 한 자세한 내용은 다음 리소스를 참조 하십시오.

- [Microsoft 365 로드맵](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Office 365 ATP의 새로운 기능](https://docs.microsoft.com/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a>Office 365의 ATP (Advanced Threat Protection)에 대 한 요구 사항

ATP는 Microsoft Exchange Server와 같은 SMTP 메일 전송 에이전트와 함께 사용할 수 있습니다. ATP에서 지 원하는 운영 체제, 웹 브라우저 및 언어에 대 한 자세한 내용은 exchange [Online Protection의 exchange 관리 센터](https://go.microsoft.com/fwlink/p/?LinkId=282381)에서 "지원 되는 브라우저" 및 "지원 되는 언어" 섹션을 참조 하십시오.

## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a>ATP (Advanced Threat Protection) 계획에서의 기능 가용성

각 기능은 아래와 같습니다. Exchange Online은 대개 Office 365 Enterprise 서비스 제품군을 지칭하는 것입니다.

|**기능**|**ATP 계획 1**<br>(이전의 ATP 독립 실행형)|**ATP 계획 2**<br>(이전의 위협 인텔리전스 <br>독립| Microsoft 365 E5/E5 보안|
|:-----|:-----|:-----|:-----|
|*구성, 보호 및 검색*|
|[안전한 첨부 파일](#safe-attachments)|예|예|예|
|팀의 안전한 첨부 파일|예|예|예|
|[안전한 링크](#safe-links)|예|예|예|
|[안전한 문서](#safe-documents)|아니요|아니요|예|
|Teams의 안전한 링크|예|예|예|
|[SharePoint, OneDrive 및 Microsoft 팀에 대 한 ATP](#atp-for-sharepoint-onedrive-and-microsoft-teams)|예|예|예|
|[피싱 방지 정책](#anti-phishing-policies)|예|예|예|
|[실시간 보고서](#real-time-reports)|예|예|예|
|*자동화, 조사, 수정 및 교육*|
|[위협 트래커](#threat-trackers)|아니요|예|예|
|위협 조사 (advanced threat 조사의)|[실시간 탐지](#real-time-detections)|[탐색기](#explorer)|[탐색기](#explorer)|
|[자동 인시던트 대응](#automated-incident-response)|아니요|예|예|
|[공격 시뮬레이터](#attack-simulator)|아니요|예|예|

> [!TIP]
> Office 365 ATP 계획 1과 계획 2 간의 차이점에 대 한 다운로드 가능 목록을 원하십니까? [PDF를 가져옵니다](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf). 

## <a name="advanced-threat-protection-atp-capabilities"></a>ATP(고급 위협 방지) 기능

### <a name="safe-attachments"></a>안전한 첨부 파일

[ATP 안전한 첨부 파일](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments) 은 알 수 없는 맬웨어 및 바이러스 로부터 보호 하 고, 메시징 시스템을 보호 하기 위한 제로 일 보호를 제공 합니다. 알려진 바이러스/맬웨어 서명이 없는 모든 메시지와 첨부 파일은 ATP가 여러 가지 기계 학습 및 분석 기술을 사용하여 악의적인 의도를 감지하는 특수한 환경으로 라우팅됩니다. 의심스러운 활동이 감지되지 않으면 메시지가 사서함 배달을 위해 릴리스됩니다.

> [!NOTE]
> ATP 안전한 첨부 파일 검사는 Office 365 데이터가 있는 동일한 지역에서 발생 합니다. 데이터 센터 지역에 대 한 자세한 내용은 [어디에 있습니까?](https://products.office.com/where-is-your-data-located?geo=All) 를 참조 하세요.

### <a name="safe-links"></a>안전한 링크

[ATP Safe Links](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links) 기능은 메시지나 Office 문서의 악의적인 url 로부터 사용자를 사전에 보호 합니다. 악의적인 링크는 동적으로 차단되지만 정상 링크에는 액세스할 수 있으므로 링크를 선택할 때마다 보호 기능이 유지됩니다.

다음과 같은 앱의 Url에 대해 안전한 링크를 사용할 수 있습니다.

- Windows 또는 Mac의 엔터프라이즈에 대 한 Microsoft 365 앱

- 웹 (웹의 Word, 웹의 경우 Excel, 웹의 경우 PowerPoint, 웹의 OneNote)에 대 한 Office

- IOS 및 Android 장치의 Office 앱은 물론 Word, Excel, PowerPoint, Visio의 Windows

- Microsoft 팀 채널 및 채팅

> [!NOTE]
> 사용자에 게 ATP 라이선스가 있어야 <sup>\*</sup> 하 고, Atp 안전한 링크 정책에 포함 되어야 하며, 보호를 위해 해당 장치에 로그인 되어 있어야 합니다.
>
> <sup>\*</sup> 조직 전반의 ATP 라이선스 (예: ATP_ENTERPRISE_FACULTY)의 경우에는 개별 사용자에 게 ATP 라이선스를 할당할 필요가 없습니다.
>
> ATP 안전한 링크 보호에 대 한 자세한 내용은 [How To Safe 링크가 Office 문서의 url과 함께 작동 하는 방식을](https://docs.microsoft.com/microsoft-365/security/office-365-security/how-atp-safe-links-works#how-atp-safe-links-works-with-urls-in-office-documents)참조 하세요.

### <a name="safe-documents"></a>안전한 문서

[ATP 안전한 문서](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs) 기능은 [Microsoft Defender Advanced Threat Protection](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) 을 사용 하 여 [제한 된 보기](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)에서 열린 문서와 파일을 검색 합니다.

시작하기 전에 알아야 할 사항은 무엇인가요?

- 이제 Office 버전 2004 (12730) 이상이 있는 사용자는 안전한 문서를 사용할 수 있습니다. 이 기능은 기본적으로 해제 되어 있으며 보안 관리자가 사용 하도록 설정 해야 합니다.

- 이 기능은 Microsoft 365 E5 또는 Microsoft 365 E5 보안 라이선스가 있는 사용자만 사용할 수 있습니다 (Office 365 ATP 계획에 포함 되지 않음).

- IOS 및 Android 장치의 Office 앱은 물론 Word, Excel, PowerPoint, Visio의 Windows

- Microsoft 팀 채널 및 채팅

> [!NOTE]
> 사용자에 게 Microsoft 365 E5 또는 Microsoft 365 E5 보안에 대 한 라이선스가 있어야 <sup>\*</sup> 하 고, ATP 안전한 문서 정책에 포함 되어야 하며, 보호를 위해 장치에 로그인 되어 있어야 합니다.
>
> ATP 안전한 문서 보호에 대 한 자세한 내용은 [Microsoft 365 E5의 안전 문서](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs)를 참조 하세요.

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>SharePoint, OneDrive 및 Microsoft Teams에 대한 ATP

[SharePoint, OneDrive 및 Microsoft 팀의 ATP](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)  는 팀 사이트 및 문서 라이브러리에서 악의적으로 식별 된 파일을 검색 하 고 차단 하는 데 도움이 됩니다. 또한 이제는 Microsoft 팀 채널과 채팅에서 ATP 안전한 링크 보호 기능을 사용할 수 있습니다.

### <a name="anti-phishing-policies"></a>피싱 방지 정책

[ATP 피싱 방지](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing) 는 메시지가 피싱 인 경우 메시지에 대 한 표시기를 확인 합니다. 사용자에게 ATP 정책(안전한 첨부 파일, 안전한 링크 또는 피싱 방지)이 적용되는 경우 들어오는 메시지는 메시지를 분석하고 구성된 정책을 기반으로 해당 조치를 수행하는 여러 기계 학습 모델에 의해 평가됩니다.

### <a name="real-time-reports"></a>실시간 보고서

보안 및 준수 관리자가 보안 공격이 나 향상 된 수상한 활동과 같은 우선 순위가 높은 문제에 집중할 수 있도록 하는 [실시간 보고서 및 정보](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp) 를 제공 하는 모니터링 기능 (Security & 준수 센터)이 포함 되어 있습니다. 문제 영역을 강조 표시 하는 것 외에도 smart reports 및 insights에는 데이터를 보고 탐색 하 고 빠른 작업도 수행할 수 있는 권장 사항과 링크가 포함 되어 있습니다.

### <a name="explorer"></a>탐색기

탐색기(위협 탐색기라고도 함)는 인증된 사용자가 최근 위협을 식별하고 분석하는 데 사용되는 실시간 보고서입니다. 기본적으로 이 보고서에는 지난 7일간에 대한 데이터가 표시됩니다. 그러나 이전의 30일간에 대한 데이터를 표시하도록 보기를 수정할 수 있습니다.

탐색기에는 맬웨어 (전자 메일 및 콘텐츠에 대 한), 전송, 피싱 및 모든 전자 메일 같은 보기가 포함 되어 있습니다. Explorer에서 실시간 검색을 비교 하는 방법을 보려면 [이 PDF를 다운로드](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)하세요.

Explorer (Office 365 Advanced Threat Protection 계획 2) 및 실시간 검색 (Office 365 Advanced Threat Protection 계획 1)에 대 한 자세한 내용은 [Threat Explorer 및 실시간](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)검색을 참조 하십시오.

### <a name="real-time-detections"></a>실시간 탐지

실시간 검색은 권한있는 사용자가 최근 위협을 식별하고 분석하는 데 사용되는 실시간 보고서입니다. 기본적으로 이 보고서에는 탐색기와 유사한 지난 7일 동안의 데이터가 표시됩니다.

실시간 검색에는 맬웨어 (전자 메일 및 콘텐츠에 대 한), 전송 및 피싱 같은 보기가 포함 됩니다. 실시간 검색이 탐색기와 비교 되는지 확인 하려면 [이 PDF를 다운로드](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)하세요.

Explorer (Office 365 Advanced Threat Protection 계획 2) 및 실시간 검색 (Office 365 Advanced Threat Protection 계획 1)에 대 한 자세한 내용은 [Threat Explorer 및 실시간](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)검색을 참조 하십시오.

### <a name="threat-trackers"></a>위협 트래커

[위협 추적기](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers) 는 권한 있는 사용자에 게 조직에 영향을 줄 수 있는 cybersecurity 문제에 대 한 정보를 제공 하는 정보와 관련 된 위젯 및 뷰입니다.

### <a name="automated-incident-response"></a>자동 인시던트 대응

Office 365에서 사용할 수 있는 [자동화 된 문제 대응](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air) (AIR) 기능 현재로 서는 잘 알려진 위협에 대응 하 여 자동 조사 프로세스를 실행할 수 있습니다. 자동화 된 특정 조사 작업을 통해 보안 운영 팀이 보다 효율적이 고 효율적으로 작동할 수 있습니다. 악의적인 전자 메일 메시지 삭제와 같은 수정 작업은 보안 운영 팀의 승인에 따라 수행 됩니다. 자세한 내용은 [Office 365에서 AIR works](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office)를 참조 하세요.

### <a name="attack-simulator"></a>공격 시뮬레이터

[공격 시뮬레이터](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator) 를 사용 하면 권한 있는 사용자가 조직에서 현실적인 공격 시나리오를 실행할 수 있습니다. 표시 이름 스피어 피싱 공격, 암호 분무 공격, 무작위 암호 공격 등 다양 한 유형의 공격을 사용할 수 있습니다.
