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
description: Office 365 Microsoft Defender는 강력한 제로 데이 보호를 제공하여 알 수 없는 맬웨어 및 바이러스로부터 조직을 보호하는 데 도움이 되는 클라우드 기반 이메일 필터링 서비스이며, 조직에 유해한 링크로부터 실시간으로 보호하는 기능을 포함합니다.
ms.openlocfilehash: 76b4d2e53c8a2942d4b974c5289c9ae4c8854b72
ms.sourcegitcommit: adcacf68ac75c4db2229ebf55be9c75aecd3070b
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52545975"
---
# <a name="microsoft-defender-for-office-365-service-description"></a>Office 365용 Microsoft Defender 서비스 설명

Office 365 Microsoft Defender는 강력한 제로 데이 보호를 제공하여 알 수 없는 맬웨어 및 바이러스로부터 조직을 보호하는 데 도움이 되는 클라우드 기반 이메일 필터링 서비스이며, 조직에 유해한 링크로부터 실시간으로 보호하는 기능을 포함합니다. Office 365 대한 수비수는 관리자에게 조직에서 일어나는 공격의 종류에 대한 통찰력을 제공하는 풍부한 보고 및 URL 추적 기능을 가지고 있습니다.

다음은 메시지 보호를 위해 Office 365 위해 Defender를 사용할 수 있는 주요 방법입니다.

- Office 365 필터링 전용 시나리오에 대한 Defender에서 Office 365 Office 365 온-프레미스 Exchange Server 환경 또는 기타 온-프레미스 SMTP 이메일 솔루션에 대한 클라우드 기반 전자 메일 보호를 제공합니다.

- Office 365 대한 수비수를 사용하여 클라우드 호스팅 사서함을 Exchange Online 보호할 수 있습니다. Exchange Online 대해 자세히 알아보려면 [Exchange Online 서비스 설명을](exchange-online-service-description/exchange-online-service-description.md)참조하십시오.

- 하이브리드 배포에서 Office 365 대한 Defender를 구성하여 인바운드 이메일 필터링을 위한 Exchange Online Protection 온프레미스 및 클라우드 사서함이 혼합된 경우 메시징 환경을 보호하고 메일 라우팅을 제어할 수 있습니다.

## <a name="microsoft-defender-for-office-365-availability"></a>Office 365 가용성에 대 한 마이크로소프트 수비수

Office 365 계획 2에 대한 Microsoft Defender는 여기에 명시된 대로 Office 365 E5, Office 365 A5, Microsoft 365 E5 Security 및 Microsoft 365 E5 [https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp](/microsoft-365/security/office-365-security/office-365-atp) 포함됩니다. Office 365 플랜 1의 수비수는 Microsoft 365 Business Premium 포함되어 있습니다.

다음과 같은 Exchange Microsoft 365 구독 계획에 Office 365 위해 Defender를 추가할 수 있습니다.

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

Office 365 대한 마이크로 소프트 수비수를 구입하려면, [Office 365 대한 마이크로 소프트 수비수를](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content)참조하십시오 .

microsoft Defender용 사용자가 Office 365 사용할 수 있는 구독에 대한 자세한 계획 정보는 [전체 구독 비교 테이블을](https://go.microsoft.com/fwlink/?linkid=2139145)참조하십시오.

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>Office 365 대한 마이크로 소프트 수비수의 새로운 것은 무엇입니까

우리는 Office 365 대한 수비수에 새로운 기능을 추가하기 위해 계속. Office 365(또는 일반적으로 Microsoft 365)에 대한 Defender에 오는 새로운 기능에 대해 자세히 알아보려면 다음 리소스를 참조하십시오.

- [Microsoft 365 로드맵](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Office 365 대한 마이크로 소프트 수비수의 새로운 것은 무엇입니까](/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-microsoft-defender-for-office-365"></a>Office 365 대한 마이크로 소프트 디펜더에 대한 요구 사항

Office 365 대한 수비수는 Microsoft Exchange Server 같은 모든 SMTP 메일 전송 에이전트와 함께 사용할 수 있습니다. Office 365 위해 Defender에서 지원하는 운영 체제, 웹 브라우저 및 언어에 대한 자세한 내용은 [Exchange Online Protection Exchange 관리 센터의](/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop)"지원되는 브라우저" 및 "지원되는 언어" 섹션을 참조하십시오.

## <a name="feature-availability-across-defender-for-office-365-plans"></a>Office 365 계획에 대한 수비수에 걸쳐 기능 가용성

각 기능은 아래와 같습니다. Exchange Online은 대개 Office 365 Enterprise 서비스 제품군을 지칭하는 것입니다.<br><br>

| 기능 | Office 365용 Defender 플랜 1 | Office 365용 Defender 플랜 2 | Microsoft 365 E5 / A5 보안|
|:-----|:-----|:-----|:-----|
|*구성, 보호 및 감지*|
|[안전한 첨부 파일](#safe-attachments)|예|예|예|
|Teams 안전한 첨부 파일|예|예|예|
|[안전한 링크](#safe-links)|예|예|예|
|[안전한 문서](#safe-documents)|아니요|아니요|예|
|Teams의 안전한 링크|예|예|예|
|[SharePoint, OneDrive 및 Microsoft Teams에 대한 ATP](#atp-for-sharepoint-onedrive-and-microsoft-teams)|예|예|예|
|[피싱 방지 정책](#anti-phishing-policies)|예|예|예|
|[실시간 보고서](#real-time-reports)|예|예|예|
|*자동화, 조사, 치료 및 교육*|
|[위협 트래커](#threat-trackers)|아니요|예|예|
|위협 조사(지능형 위협 조사)|[실시간 탐지](#real-time-detections)|[탐색기](#explorer)|[탐색기](#explorer)|
|[자동화된 인시던트 대응](#automated-incident-response)|아니요|예|예|
|[공격 시뮬레이션 교육](#attack-simulation-training)|아니요|예|예|
|*Microsoft 365 [수비수와의](/microsoft-365/security/mtp/microsoft-threat-protection) 통합*|아니요|예|예|

> [!NOTE]
> 임차인이 Office 플랜 P2 평가판 라이센스 또는 Office 365 E5 평가판 라이센스에 대한 Microsoft Defender만 있는 경우 Microsoft 365 수비수에 대한 다른 자격 라이선스가 없는 경우 Microsoft 365 수비수에 액세스할 수 없습니다. MTP 라이선스에 대해 자세히 알아보려면 [Microsoft 365 Defender 요구 사항을](/microsoft-365/security/mtp/prerequisites)참조하십시오.

## <a name="defender-for-office-365-capabilities"></a>Office 365 기능을 위한 수비수

### <a name="safe-attachments"></a>안전한 첨부 파일

[안전 첨부 파일은](/microsoft-365/security/office-365-security/atp-safe-attachments) 알 수없는 악성 코드 및 바이러스로부터 보호하며 메시징 시스템을 보호하기 위해 제로 데이 보호를 제공합니다. 알려진 바이러스/맬웨어 서명이 없는 모든 메시지와 첨부 파일은 Office 365 수 있는 Defender가 다양한 기계 학습 및 분석 기술을 사용하여 악의적인 의도를 감지하는 특수 환경으로 라우팅됩니다. 의심스러운 활동이 감지되지 않으면 메시지가 사서함 배달을 위해 릴리스됩니다.

> [!NOTE]
> 안전한 첨부 파일 검색은 Office 365 데이터가 있는 동일한 영역에서 이루어집니다. 데이터 센터 지리에 대한 자세한 내용은 [데이터가 어디에 있습니까?](https://products.office.com/where-is-your-data-located?geo=All)

### <a name="safe-links"></a>안전한 링크

[세이프 링크](/microsoft-365/security/office-365-security/atp-safe-links) 기능은 메시지 또는 Office 문서에서 사용자를 악의적인 URL로부터 사전에 보호합니다. 악의적인 링크는 동적으로 차단되지만 정상 링크에는 액세스할 수 있으므로 링크를 선택할 때마다 보호 기능이 유지됩니다.

다음과 같은 앱에서 URL에 대한 안전한 링크를 사용할 수 있습니다.

- Windows 또는 맥에 엔터프라이즈용 Microsoft 365 앱

- 웹용 Office(웹용 Word, 웹용 Excel, 웹용 PowerPoint, 웹용 OneNote)

- Windows 단어, Excel, PowerPoint

- Microsoft Teams 채널 및 채팅

> [!NOTE]
> 사용자는 Office 365 대한 수비수에 대한 라이센스를 <sup>\*</sup> 받아야하며, 세이프 링크 정책에 포함되어야하며, 보호가 준비되려면 장치에 로그인해야 합니다.
>
> <sup>\*</sup>Office 365 라이선스에 대한 조직 차원의 Defender(예: ATP_ENTERPRISE_FACULTY)의 경우 개별 사용자에게 Office 365 라이선스에 대한 Defender를 할당할 필요가 없습니다.
>
> 안전 링크 보호에 대 한 자세한 내용은 [Office 365 대 한 마이크로소프트 수비수에 안전 링크를](/microsoft-365/security/office-365-security/atp-safe-links)참조 하십시오.

### <a name="safe-documents"></a>안전한 문서

[안전 문서](/microsoft-365/security/office-365-security/safe-docs) 기능은 [엔드포인트에 대한 Microsoft Defender를](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) 사용하여 [보호된 보기에서](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)열리는 문서와 파일을 스캔합니다.

시작하기 전에 알아야 할 내용은 무엇인가요?

- 이제 Office 버전 2004(12730.x) 이상인 사용자가 안전한 문서를 사용할 수 있습니다! 이 기능은 기본적으로 꺼져 있으며 보안 관리자가 사용하도록 설정해야 합니다.

- 이 기능은 Microsoft 365 E5 또는 Microsoft 365 E5 Security 라이선스를 소지한 사용자만 사용할 수 있습니다(Office 365 계획에 대한 수비수에는 포함되지 않음).

- Windows 단어, Excel, PowerPoint

- Microsoft Teams 채널 및 채팅

> [!NOTE]
> 사용자는 Microsoft 365 E5 또는 Microsoft 365 E5 Security 대한 라이선스를 받아야 <sup>\*</sup> 하며, 안전 문서 정책에 포함되어야 하며, 보호를 위해 기기에 로그인해야 합니다.
>
> 안전 문서 보호에 대한 자세한 내용은 [Microsoft 365 E5 안전한 문서를](/microsoft-365/security/office-365-security/safe-docs)참조하십시오.

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>SharePoint, OneDrive 및 Microsoft Teams에 대한 ATP

[SharePoint, OneDrive 및 Microsoft Teams 대한 ATP는](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams) 팀 사이트 및 문서 라이브러리에서 악의적인 것으로 식별되는 파일을 감지하고 차단하는 데 도움이 됩니다. 또한 이제 Microsoft Teams 채널 및 채팅에서 안전 링크 보호를 사용할 수 있습니다.

### <a name="anti-phishing-policies"></a>피싱 방지 정책

[피싱 방지는](/microsoft-365/security/office-365-security/atp-anti-phishing) 메시지가 피싱 시도일 수 있는 지표에 대해 들어오는 메시지를 확인합니다. 사용자가 Office 365 정책(안전 첨부 파일, 안전 링크 또는 피싱 방지)에 대한 Defender의 적용을 받는 경우, 들어오는 메시지는 메시지를 분석하고 구성된 정책에 따라 적절한 조치를 취하는 여러 기계 학습 모델에 의해 평가됩니다.

### <a name="real-time-reports"></a>실시간 보고서

보안 & 규정 준수 센터에서 사용할 수 있는 모니터링 [https://protection.office.com](https://protection.office.com) 기능에는 보안 및 규정 준수 관리자가 보안 공격 이나 의심스러운 활동 증가와 같은 우선 순위가 높은 문제에 집중할 수 있는 [실시간 보고서 및 인사이트가](/microsoft-365/security/office-365-security/view-reports-for-atp) 포함됩니다. 문제 영역을 강조하는 것 외에도 스마트 보고서 및 인사이트는 데이터를 보고 탐색하고 신속한 조치를 취할 수 있는 권장 사항과 링크가 포함됩니다.

### <a name="explorer"></a>탐색기

탐색기(위협 탐색기라고도 함)는 인증된 사용자가 최근 위협을 식별하고 분석하는 데 사용되는 실시간 보고서입니다. 기본적으로 이 보고서는 지난 7일 동안의 데이터를 보여 주며, 그러나 지난 30일 동안 의 데이터를 표시하도록 뷰를 수정할 수 있습니다.

탐색기에는 맬웨어(이메일 및 콘텐츠용), 제출물, 피시 및 모든 이메일과 같은 뷰가 포함되어 있습니다. Explorer가 실시간 검색과 비교하는 방법을 보려면 [이 PDF를 다운로드합니다.](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

익스플로러 (Office 365 계획 2에 대 한 마이크로소프트 수비수) 및 실시간 검색에 대 한 자세한 내용은 (Office 365 계획 에 대 한 마이크로소프트 수비수에서 1), [위협 탐색기 및 실시간 탐지를](/microsoft-365/security/office-365-security/threat-explorer)참조 하십시오.

### <a name="real-time-detections"></a>실시간 탐지

실시간 검색은 권한있는 사용자가 최근 위협을 식별하고 분석하는 데 사용되는 실시간 보고서입니다. 탐색기와 마찬가지로 기본적으로 이 보고서에는 지난 7일 간의 데이터가 표시됩니다.

실시간 검색에는 맬웨어(이메일 및 콘텐츠용), 제출물 및 피시와 같은 보기가 포함됩니다. 실시간 검색이 탐색기와 비교하는 방법을 보려면 [이 PDF를 다운로드합니다.](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

익스플로러 (Office 365 계획 2에 대 한 마이크로소프트 수비수) 및 실시간 검색 (Office 365 계획에 대 한 마이크로소프트 수비수에서) 에 대 한 자세한 내용은 [위협 탐색기 (및 실시간 검색)를](/microsoft-365/security/office-365-security/threat-explorer)참조 합니다.

### <a name="threat-trackers"></a>위협 추적기

[위협 추적기는](/microsoft-365/security/office-365-security/threat-trackers) 조직에 영향을 줄 수 있는 사이버 보안 문제에 대한 정보를 권한이 있는 사용자에게 제공하는 유익한 위젯 및 보기입니다.

### <a name="automated-incident-response"></a>자동화된 인시던트 대응

Office 365 계획 2에 대한 Defender에서 사용할 수 있는 [자동화된 사고](/microsoft-365/security/office-365-security/office-365-air) 대응(AIR) 기능을 사용하면 현재 존재하는 알려진 위협에 대응하여 자동화된 조사 프로세스를 실행할 수 있습니다. 자동화된 특정 조사 작업을 통해 보안 운영 팀은 보다 효율적이고 효과적으로 운영할 수 있습니다. 악의적인 이메일 메시지 삭제와 같은 수정 작업은 보안 운영 팀의 승인을 받아 수행됩니다. 자세한 내용은 [air가 Office 365 작동하는 방식을](/microsoft-365/security/office-365-security/automated-investigation-response-office)참조하십시오.

### <a name="attack-simulation-training"></a>공격 시뮬레이션 교육

[공격 시뮬레이션 교육은](/microsoft-365/security/office-365-security/attack-simulation-training-get-started) 피싱 시뮬레이션의 생성 및 관리를 자동화하는 지능형 사회적 위험 관리 도구입니다. 시뮬레이션을 통해 고객은 실제 피시 미끼와 하이퍼 타겟 교육을 사용하여 직원 행동을 변경하여 피싱 위험을 감지, 우선 순위 지정 및 수정할 수 있습니다.

- 공격 시뮬레이션 훈련은 WW 및 GCC(6월 21일부터 GCC 예정)에서 사용할 수 있습니다.
- 시작하는 방법에 대한 자세한 내용은 [공격 시뮬레이션 교육을 사용하여 시작하세요.](/microsoft-365/security/office-365-security/attack-simulation-training-get-started)
- 피싱 시뮬레이션을 관련성 있게 만들기 위해 실제 공격자 동작을 복제하는 무기화, 실제 피시 페이로드를 적용하는 다양한 공격 기술을 사용할 수 있습니다.
- 이 서비스는 Microsoft 365 E5, Office 365 E5 또는 microsoft [Defender가 Office 365 계획 2 라이선스가](/microsoft-365/security/office-365-security/defender-for-office-365#microsoft-defender-for-office-365-plan-1-and-plan-2) 있는 조직에서 사용할 수 있습니다. E3 고객에게 는 시험으로 기능의 하위 집합이 제공됩니다.
- 자세한 내용을 알아보고 시뮬레이션을 시도하려면 [피싱 공격 시뮬레이션을](/microsoft-365/security/office-365-security/attack-simulation-training)참조하십시오.