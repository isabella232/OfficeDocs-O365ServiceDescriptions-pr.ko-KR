---
title: Office 365용 Microsoft Defender 서비스 설명
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Defender for Office 365 는 강력한 제로 데이 보호를 제공하여 알 수 없는 맬웨어 및 바이러스로부터 조직을 보호하는 클라우드 기반 전자 메일 필터링 서비스로, 유해한 링크로부터 조직을 실시간으로 보호하는 기능을 포함합니다.
ms.openlocfilehash: 76b4d2e53c8a2942d4b974c5289c9ae4c8854b72
ms.sourcegitcommit: adcacf68ac75c4db2229ebf55be9c75aecd3070b
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52545975"
---
# <a name="microsoft-defender-for-office-365-service-description"></a>Office 365용 Microsoft Defender 서비스 설명

Microsoft Defender for Office 365 는 강력한 제로 데이 보호를 제공하여 알 수 없는 맬웨어 및 바이러스로부터 조직을 보호하는 클라우드 기반 전자 메일 필터링 서비스로, 유해한 링크로부터 조직을 실시간으로 보호하는 기능을 포함합니다. Office 365 Defender에는 조직에서 일어나는 공격의 종류에 대한 정보를 관리자에게 제공하는 풍부한 보고 및 URL 추적 기능이 있습니다.

메시지 보호를 위해 Defender를 사용하여 Office 365 기본 방법은 다음과 같습니다.

- Office 365 필터링 전용 시나리오에서 Office 365 Defender for Exchange Server 환경 또는 기타 모든 사내 SMTP 전자 메일 솔루션에 대해 클라우드 기반 전자 메일 보호를 제공합니다.

- 클라우드 호스트 Office 365 사서함을 보호하기 위해 Exchange Online 수 있습니다. 자세한 내용은 Exchange Online 서비스 [설명을 Exchange Online 참조하세요.](exchange-online-service-description/exchange-online-service-description.md)

- 하이브리드 배포에서는 인바운드 전자 메일 필터링에 Office 365 사서함과 클라우드 사서함이 혼합된 경우 메시징 환경을 보호하고 메일 라우팅을 Exchange Online Protection Defender for Exchange Online Protection 수 있습니다.

## <a name="microsoft-defender-for-office-365-availability"></a>Microsoft Defender for Office 365 가용성

Microsoft Defender for Office 365 Plan 2는 에 Office 365 E5, Office 365 A5, Microsoft 365 E5 Security 및 Microsoft 365 E5 포함되어 [https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp](/microsoft-365/security/office-365-security/office-365-atp) 있습니다. . Office 365 요금제 1에 대한 Defender가 Microsoft 365 Business Premium.

다음 구독 계획 및 Office 365 계획에 Defender를 Exchange Microsoft 365 있습니다.

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

Microsoft Defender for Office 365 Microsoft [Defender for Office 365.](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content)

Microsoft Defender for Office 365 구독에 대한 자세한 계획 정보는 전체 구독 비교 표를 [참조하세요.](https://go.microsoft.com/fwlink/?linkid=2139145)

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>Microsoft Defender for Office 365

We are continuing to add new features to Defender for Office 365. Office 365 (또는 일반적으로 Microsoft 365 Defender에 제공될 새로운 기능에 대한 자세한 내용은 다음 리소스를 참조합니다.

- [Microsoft 365 로드맵](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Microsoft Defender for Office 365](/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-microsoft-defender-for-office-365"></a>Microsoft Defender for Office 365

Defender for Office 365 SMTP 메일 전송 에이전트와 함께 사용할 수 Microsoft Exchange Server. Office 365 Defender에서 지원하는 운영 체제, 웹 브라우저 및 언어에 대한 자세한 내용은 Exchange 관리 센터의 "지원되는 브라우저" 및 "지원되는 언어" [섹션을 Exchange Online Protection.](/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop)

## <a name="feature-availability-across-defender-for-office-365-plans"></a>계획용 Defender의 Office 365 가용성

각 기능은 아래와 같습니다. Exchange Online은 대개 Office 365 Enterprise 서비스 제품군을 지칭하는 것입니다.<br><br>

| 기능 | Office 365용 Defender 플랜 1 | Office 365용 Defender 플랜 2 | Microsoft 365 E5 / A5 보안|
|:-----|:-----|:-----|:-----|
|*구성, 보호 및 검색*|
|[안전한 첨부 파일](#safe-attachments)|예|예|예|
|안전 첨부 파일 Teams|예|예|예|
|[안전한 링크](#safe-links)|예|예|예|
|[안전한 문서](#safe-documents)|아니요|아니요|예|
|Teams의 안전한 링크|예|예|예|
|[SharePoint, OneDrive 및 Microsoft Teams에 대한 ATP](#atp-for-sharepoint-onedrive-and-microsoft-teams)|예|예|예|
|[피싱 방지 정책](#anti-phishing-policies)|예|예|예|
|[실시간 보고서](#real-time-reports)|예|예|예|
|*자동화, 조사, 수정 및 교육*|
|[위협 트래커](#threat-trackers)|아니요|예|예|
|위협 조사(고급 위협 조사)|[실시간 탐지](#real-time-detections)|[탐색기](#explorer)|[탐색기](#explorer)|
|[자동화된 인시던트 대응](#automated-incident-response)|아니요|예|예|
|[공격 시뮬레이션 교육](#attack-simulation-training)|아니요|예|예|
|*Microsoft 365 [Defender와의 통합](/microsoft-365/security/mtp/microsoft-threat-protection)*|아니요|예|예|

> [!NOTE]
> 테넌트에 Office P2 평가판 라이선스 또는 Office 365 E5 평가판 라이선스를 위한 Microsoft Defender만 있는 경우 Microsoft 365 Defender에 대한 다른 적격 라이선스가 없는 경우 Microsoft 365 Defender에 액세스할 수 없습니다. MTP 라이선스에 대한 자세한 내용은 Defender 요구 [Microsoft 365 참조하세요.](/microsoft-365/security/mtp/prerequisites)

## <a name="defender-for-office-365-capabilities"></a>Office 365 기능용 Defender

### <a name="safe-attachments"></a>안전한 첨부 파일

[안전한 첨부 파일은](/microsoft-365/security/office-365-security/atp-safe-attachments) 알 수 없는 맬웨어 및 바이러스로부터 보호하고 제로 데이 보호 기능을 제공하여 메시징 시스템을 보호합니다. 알려진 바이러스/맬웨어 서명이 없는 모든 메시지와 첨부 파일은 맬웨어에 대한 Defender가 Office 365 기계 학습 및 분석 기술을 사용하여 악의적인 의도를 감지하는 특수한 환경으로 라우팅됩니다. 의심스러운 활동이 감지되지 않으면 메시지가 사서함 배달을 위해 릴리스됩니다.

> [!NOTE]
> 안전한 첨부 파일 검색은 안전 첨부 파일이 있는 Office 365 지역에서 진행됩니다. 데이터 센터 지리에 대한 자세한 내용은 데이터가 어디에 [있나요?를 참조하세요.](https://products.office.com/where-is-your-data-located?geo=All)

### <a name="safe-links"></a>안전한 링크

안전한 [링크 기능은](/microsoft-365/security/office-365-security/atp-safe-links) 메시지나 문서의 악의적인 URL로부터 사용자를 Office 합니다. 악의적인 링크는 동적으로 차단되지만 정상 링크에는 액세스할 수 있으므로 링크를 선택할 때마다 보호 기능이 유지됩니다.

다음과 같은 앱에서 URL에 대한 안전한 링크를 사용할 수 있습니다.

- 엔터프라이즈용 Microsoft 365 앱 또는 mac에서 Windows

- 웹용 Office(웹용 Word, 웹용 Excel, 웹용 PowerPoint, 웹용 OneNote)

- Word, Excel 및 PowerPoint Windows

- Microsoft Teams 채널 및 채팅

> [!NOTE]
> 사용자에 대한 Defender 사용이 허가되어야 Office 365 안전한 링크 정책에 포함되어야 합니다. 보호가 적용될 수 있도록 장치에 로그인해야 <sup>\*</sup> 합니다.
>
> <sup>\*</sup>조직 전체의 Office 365 라이선스(예: ATP_ENTERPRISE_FACULTY)의 경우 개별 사용자에게 Office 365 대한 Defender를 할당할 필요가 없습니다.
>
> 안전한 링크 보호에 대한 자세한 내용은 Microsoft [Defender for Office 365.](/microsoft-365/security/office-365-security/atp-safe-links)

### <a name="safe-documents"></a>안전한 문서

안전한 [문서 기능은](/microsoft-365/security/office-365-security/safe-docs) [끝점용 Microsoft Defender를](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) 사용하여 보호된 보기에서 연 문서 및 파일을 [검사합니다.](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)

시작하기 전에 알아야 할 내용은 무엇인가요?

- 이제 안전한 문서는 현재 버전 2004(Office 12730.x) 이상의 사용자가 사용할 수 있습니다! 이 기능은 기본적으로 해제되어 있으며 보안 관리자가 사용하도록 설정해야 합니다.

- 이 기능은 Microsoft 365 E5 또는 Microsoft 365 E5 Security 라이선스가 있는 사용자만 사용할 Office 365 있습니다.

- Word, Excel 및 PowerPoint Windows

- Microsoft Teams 채널 및 채팅

> [!NOTE]
> 사용자는 안전한 문서 정책에 Microsoft 365 E5 또는 Microsoft 365 E5 Security 라이선스가 있어야 합니다. 보호가 적용될 수 있도록 장치에 로그인해야 <sup>\*</sup> 합니다.
>
> 안전한 문서 보호에 대한 자세한 내용은 에서 [Safe Documents in Microsoft 365 E5.](/microsoft-365/security/office-365-security/safe-docs)

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>SharePoint, OneDrive 및 Microsoft Teams에 대한 ATP

SharePoint, OneDrive 및 Microsoft Teams [ATP는](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams) 팀 사이트 및 문서 라이브러리에서 악성으로 식별된 파일을 검색하고 차단하는 데 도움이 됩니다. 또한 이제 모든 채널 및 채팅에서 안전한 링크 Microsoft Teams 사용할 수 있습니다.

### <a name="anti-phishing-policies"></a>피싱 방지 정책

[피싱 방지는](/microsoft-365/security/office-365-security/atp-anti-phishing) 들어오는 메시지에서 메시지가 피싱 시도일 수 있는 표시기를 검사합니다. 사용자가 Office 365 정책(안전한 첨부 파일, 안전한 링크 또는 피싱 방지)에 대해 Defender의 적용을 받는 경우 들어오는 메시지는 메시지를 분석하는 여러 기계 학습 모델을 통해 평가하며 구성된 정책에 따라 적절한 조치를 취합니다.

### <a name="real-time-reports"></a>실시간 보고서

보안 & 준수 센터()에서 사용할 수 있는 모니터링 기능에는 보안 및 규정 준수 관리자가 보안 공격이나 증가된 의심스러운 활동과 같은 우선 순위가 높은 문제에 집중할 수 있는 실시간 보고서 및 인사이트가 포함되어 [https://protection.office.com](https://protection.office.com) 있습니다. [](/microsoft-365/security/office-365-security/view-reports-for-atp) 문제 영역을 강조 표시하는 것 외에도 스마트 보고서 및 인사이트에는 데이터를 보고 탐색하는 권장 사항과 링크가 포함되어 있으며, 빠른 작업을 수행할 수 있습니다.

### <a name="explorer"></a>탐색기

탐색기(위협 탐색기라고도 함)는 인증된 사용자가 최근 위협을 식별하고 분석하는 데 사용되는 실시간 보고서입니다. 기본적으로 이 보고서에는 지난 7일간의 데이터가 표시됩니다. 그러나 지난 30일 동안의 데이터를 표시하기 위해 보기를 수정할 수 있습니다.

탐색기에는 맬웨어(전자 메일 및 콘텐츠용), 제출, 피싱 및 모든 전자 메일과 같은 보기가 포함되어 있습니다. 탐색기가 실시간 검색과 비교하는 방법을 표시하려면 이 [PDF 를 다운로드하세요.](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

탐색기(Office 365 계획 2용 Microsoft Defender) 및 실시간 검색(Office 365 계획 1용 Microsoft Defender)에 대한 자세한 내용은 [위협](/microsoft-365/security/office-365-security/threat-explorer)탐색기 및 실시간 검색을 참조하세요.

### <a name="real-time-detections"></a>실시간 탐지

실시간 검색은 권한있는 사용자가 최근 위협을 식별하고 분석하는 데 사용되는 실시간 보고서입니다. 기본적으로 이 보고서에는 Explorer와 마찬가지로 지난 7일간의 데이터가 표시됩니다.

실시간 검색에는 맬웨어(전자 메일 및 콘텐츠용), 제출, 피싱 등의 보기가 포함되어 있습니다. 실시간 검색이 탐색기와 어떻게 비교하는지 표시하려면 이 [PDF를 다운로드하세요.](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

탐색기(Office 365 계획 2용 Microsoft Defender) 및 실시간 검색(Office 365 계획 1용 Microsoft Defender)에 대한 자세한 내용은 [위협](/microsoft-365/security/office-365-security/threat-explorer)탐색기(및 실시간 검색)를 참조하세요.

### <a name="threat-trackers"></a>위협 추적기

[위협 추적은](/microsoft-365/security/office-365-security/threat-trackers) 권한이 부여된 사용자에게 조직에 영향을 줄 수 있는 사이버 보안 문제에 대한 인텔리전스를 제공하는 정보 위젯 및 보기입니다.

### <a name="automated-incident-response"></a>자동화된 인시던트 대응

[Office 365](/microsoft-365/security/office-365-security/office-365-air) Plan 2용 Defender에서 사용할 수 있는 AIR(자동화된 인시던트 대응) 기능을 사용하면 현재 존재하는 잘 알려진 위협에 대응하여 자동화된 조사 프로세스를 실행할 수 있습니다. 자동화된 특정 조사 작업을 통해 보안 운영 팀이 보다 효율적이고 효율적으로 작업할 수 있습니다. 악의적인 전자 메일 메시지 삭제와 같은 수정 작업은 보안 운영 팀의 승인에 따라 수행됩니다. 자세한 내용은 에서 [AIR의 작동 Office 365.](/microsoft-365/security/office-365-security/automated-investigation-response-office)

### <a name="attack-simulation-training"></a>공격 시뮬레이션 교육

[공격 시뮬레이션 교육은](/microsoft-365/security/office-365-security/attack-simulation-training-get-started) 피싱 시뮬레이션의 생성 및 관리를 자동화하는 지능형 소셜 위험 관리 도구입니다. 시뮬레이션은 고객이 실제 피싱 무차원 및 하이퍼 대상 교육을 사용하여 직원의 행동을 변경하여 피싱 위험을 감지, 우선 순위 지정 및 수정하는 데 도움이 됩니다.

- 공격 시뮬레이션 교육은 이제 WW 및 GCC 있습니다(6월 21일 GCC 예정임).
- 시작 방법에 대한 자세한 내용은 공격 시뮬레이션 교육 사용 [시작을 참조하세요.](/microsoft-365/security/office-365-security/attack-simulation-training-get-started)
- 피싱 시뮬레이션과 관련이 있도록 실제 공격자 동작을 복제하는 다국어 피싱 페이로드를 적용하는 다양한 공격 기술을 사용할 수 있습니다.
- 이 서비스는 Microsoft 365 E5, Office 365 E5 또는 [Microsoft Defender for Office 365](/microsoft-365/security/office-365-security/defender-for-office-365#microsoft-defender-for-office-365-plan-1-and-plan-2) 라이선스가 있는 조직에서 사용할 수 있습니다. E3 고객에게는 평가판 기능의 하위 집합이 제공됩니다.
- 자세한 내용을 알아보고 시뮬레이션을 시도해보시고 피싱 공격 [시뮬레이션을 참조합니다.](/microsoft-365/security/office-365-security/attack-simulation-training)