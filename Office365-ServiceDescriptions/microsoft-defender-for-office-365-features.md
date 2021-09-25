---
title: Office 365용 Microsoft Defender 기능 서비스 설명
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
ms.assetid: ''
description: Microsoft Defender for Office 365.
ms.openlocfilehash: 591236d6028d57025d2dd7a9cfc5ef80d3617176
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/24/2021
ms.locfileid: "59671458"
---
# <a name="microsoft-defender-for-office-365-features-service-description"></a>Office 365용 Microsoft Defender 기능 서비스 설명

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>Microsoft Defender for Office 365

We are continuing to add new features to Defender for Office 365. Office 365 (또는 일반적으로 Microsoft 365 Defender에 제공될 새로운 기능에 대한 자세한 내용은 다음 리소스를 참조합니다.

- [Microsoft 365 로드맵](https://www.microsoft.com/microsoft-365/roadmap)

- [Microsoft Defender for Office 365 - Office 365 | Microsoft Docs](/microsoft-365/security/office-365-security/whats-new-in-defender-for-office-365)

## <a name="defender-for-office-365-capabilities"></a>Office 365 기능용 Defender

### <a name="safe-attachments"></a>안전한 첨부 파일

[금고 첨부 파일은](/microsoft-365/security/office-365-security/atp-safe-attachments) 알 수 없는 맬웨어 및 바이러스로부터 보호하고 제로 데이 보호 기능을 통해 메시징 시스템을 보호합니다. 알려진 바이러스/맬웨어 서명이 없는 모든 메시지와 첨부 파일은 맬웨어에 대한 Defender가 Office 365 기계 학습 및 분석 기술을 사용하여 악의적인 의도를 감지하는 특수한 환경으로 라우팅됩니다. 의심스러운 활동이 감지되지 않으면 메시지가 사서함 배달을 위해 릴리스됩니다.

> [!NOTE]
> 금고 첨부 파일 검색은 첨부 파일 데이터가 Office 365 지역에서 진행됩니다. 데이터 센터 지리에 대한 자세한 내용은 데이터가 어디에 [있나요?를 참조하세요.](/microsoft-365/enterprise/o365-data-locations)

### <a name="safe-links"></a>안전한 링크

금고 [링크](/microsoft-365/security/office-365-security/atp-safe-links) 기능은 메시지 또는 문서의 악의적인 URL로부터 사용자를 Office 합니다. 악의적인 링크는 동적으로 차단되지만 정상 링크에는 액세스할 수 있으므로 링크를 선택할 때마다 보호 기능이 유지됩니다.

다음과 같은 앱에서 URL에 대한 안전한 링크를 사용할 수 있습니다.

- 엔터프라이즈용 Microsoft 365 앱 또는 mac에서 Windows

- 웹용 Office(웹용 Word, 웹용 Excel, 웹용 PowerPoint, 웹용 OneNote)

- Word, Excel 및 PowerPoint Windows

- Microsoft Teams 채널 및 채팅

> [!NOTE]
> 사용자는 Office 365 대한 Defender 라이선스가 있어야 금고 링크 정책에 포함되어야 합니다. 보호가 적용될 수 있도록 장치에 로그인해야 <sup>\*</sup> 합니다.
>
> <sup>\*</sup>조직 전체의 Office 365 라이선스(예: ATP_ENTERPRISE_FACULTY)의 경우 개별 사용자에게 Office 365 대한 Defender를 할당할 필요가 없습니다.
>
> 링크 보호에 금고 대한 자세한 내용은 microsoft [Defender에서](/microsoft-365/security/office-365-security/atp-safe-links)금고 링크를 Office 365.

### <a name="safe-documents"></a>안전 문서

금고 [문서](/microsoft-365/security/office-365-security/safe-docs) 기능은 [끝점용 Microsoft Defender를](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) 사용하여 보호된 보기에서 연 문서 및 파일을 [검사합니다.](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)

시작하기 전에 알아야 할 내용은 무엇인가요?

- 금고 이제 버전 2004(Office 12730.x) 이상의 사용자가 문서를 일반적으로 사용할 수 있습니다! 이 기능은 기본적으로 해제되어 있으며 보안 관리자가 사용하도록 설정해야 합니다.

- 이 기능은 Microsoft 365 E5 또는 Microsoft 365 E5 Security 라이선스가 있는 사용자만 사용할 Office 365 있습니다.

- Word, Excel 및 PowerPoint Windows

- Microsoft Teams 채널 및 채팅

> [!NOTE]
> 사용자에게 Microsoft 365 E5 또는 Microsoft 365 E5 Security 라이선스가 있어야 금고 문서 정책에 포함되어야 합니다. 보호가 적용될 수 있도록 장치에 로그인해야 <sup>\*</sup> 합니다.
>
> 문서 보호를 금고 대한 자세한 내용은 금고 [문서를 Microsoft 365 E5.](/microsoft-365/security/office-365-security/safe-docs)

### <a name="protection-for-sharepoint-onedrive-and-microsoft-teams"></a>SharePoint, OneDrive 및 Microsoft Teams

[SharePoint,](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams) OneDrive 및 Microsoft Teams 보호는 팀 사이트 및 문서 라이브러리에서 악성으로 식별된 파일을 검색하고 차단하는 데 도움이 됩니다. 또한 이제 금고 및 채팅에서 링크 Microsoft Teams 사용할 수 있습니다.

### <a name="anti-phishing-policies"></a>피싱 방지 정책

[피싱 방지는](/microsoft-365/security/office-365-security/atp-anti-phishing) 들어오는 메시지에서 메시지가 피싱 시도일 수 있는 표시기를 검사합니다. 사용자가 Office 365 정책(금고 첨부 파일, 금고 링크 또는 피싱 방지)에 대한 보호를 받는 경우 들어오는 메시지는 메시지를 분석하는 여러 기계 학습 모델을 통해 평가하며 구성된 정책에 따라 적절한 조치를 취합니다.

### <a name="real-time-reports"></a>실시간 보고서

[보안](https://protection.office.com) & 준수 센터에서 사용할 수 있는 [](/microsoft-365/security/office-365-security/view-reports-for-atp) 모니터링 기능에는 보안 및 준수 관리자가 보안 공격이나 증가된 의심스러운 활동과 같은 우선 순위가 높은 문제에 집중할 수 있는 실시간 보고서 및 인사이트가 포함되어 있습니다. 문제 영역을 강조 표시하는 것 외에도 스마트 보고서 및 인사이트에는 데이터를 보고 탐색하는 권장 사항과 링크가 포함되어 있으며, 빠른 작업을 수행할 수 있습니다.

### <a name="threat-explorer"></a>위협 탐색기

위협 탐색기(탐색기라고도 지칭)는 권한이 부여된 사용자가 최근 위협을 식별하고 분석할 수 있는 실시간 보고서입니다. 기본적으로 이 보고서에는 지난 7일간의 데이터가 표시됩니다. 그러나 지난 30일 동안의 데이터를 표시하기 위해 보기를 수정할 수 있습니다.

탐색기에는 맬웨어(전자 메일 및 콘텐츠용), 제출, 피싱 및 모든 전자 메일과 같은 보기가 포함되어 있습니다. 탐색기가 실시간 검색과 비교하는 방법을 표시하려면 이 [PDF 를 다운로드하세요.](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

탐색기(Office 365 계획 2용 Microsoft Defender) 및 실시간 검색(Office 365 계획 1용 Microsoft Defender)에 대한 자세한 내용은 [위협](/microsoft-365/security/office-365-security/threat-explorer)탐색기 및 실시간 검색을 참조하세요.

### <a name="real-time-detections"></a>실시간 탐지

실시간 검색은 권한있는 사용자가 최근 위협을 식별하고 분석하는 데 사용되는 실시간 보고서입니다. 기본적으로 이 보고서에는 Explorer와 마찬가지로 지난 7일간의 데이터가 표시됩니다.

실시간 검색에는 맬웨어(전자 메일 및 콘텐츠용), 제출, 피싱 등의 보기가 포함되어 있습니다. 실시간 검색이 탐색기와 어떻게 비교하는지 표시하려면 이 [PDF를 다운로드하세요.](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

탐색기(Office 365 계획 2용 Microsoft Defender) 및 실시간 검색(Office 365 계획 1용 Microsoft Defender)에 대한 자세한 내용은 [위협](/microsoft-365/security/office-365-security/threat-explorer)탐색기 및 실시간 검색을 참조하세요.

### <a name="threat-trackers"></a>위협 추적기

[위협 추적은](/microsoft-365/security/office-365-security/threat-trackers) 권한이 부여된 사용자에게 조직에 영향을 줄 수 있는 사이버 보안 문제에 대한 인텔리전스를 제공하는 정보 위젯 및 보기입니다.

### <a name="automated-investigation--response"></a>자동화된 조사 & 응답

[Office 365](/microsoft-365/security/office-365-security/office-365-air) Plan 2용 Defender에서 사용할 수 있는 자동화된 조사 & AIR(대응) 기능을 사용하면 현재 존재하는 잘 알려진 위협에 대응하여 자동화된 조사 프로세스를 실행할 수 있습니다. 특정 조사 작업을 자동화하면 보안 운영 팀이 보다 효율적이고 효율적으로 작업할 수 있습니다. 악의적인 전자 메일 메시지 삭제와 같은 수정 작업은 보안 운영 팀의 승인에 따라 수행됩니다. 자세한 내용은 에서 [AIR의 작동 Office 365.](/microsoft-365/security/office-365-security/automated-investigation-response-office)

### <a name="attack-simulation-training"></a>공격 시뮬레이션 교육

[공격 시뮬레이션 교육은](/microsoft-365/security/office-365-security/attack-simulation-training-get-started) 피싱 시뮬레이션의 생성 및 관리를 자동화하는 지능형 소셜 위험 관리 도구입니다. 시뮬레이션은 고객이 실제 피싱 무차원 및 하이퍼 대상 교육을 사용하여 직원의 행동을 변경하여 피싱 위험을 감지, 우선 순위 지정 및 수정하는 데 도움이 됩니다.

- 공격 시뮬레이션 교육은 이제 WW 및 GCC 있습니다(6월 21일 GCC 예정임).
- 시작 방법에 대한 자세한 내용은 공격 시뮬레이션 교육 사용 [시작을 참조하세요.](/microsoft-365/security/office-365-security/attack-simulation-training-get-started)
- 피싱 시뮬레이션과 관련이 있도록 실제 공격자 동작을 복제하는 다국어 피싱 페이로드를 적용하는 다양한 공격 기술을 사용할 수 있습니다.
- 이 서비스는 Microsoft 365 E5, Office 365 E5 또는 [Microsoft Defender for](/microsoft-365/security/office-365-security/defender-for-office-365#microsoft-defender-for-office-365-plan-1-and-plan-2) Office 365 라이선스가 있는 조직에서 사용할 수 있습니다. E3 고객에게는 평가판 기능의 하위 집합이 제공됩니다.
- 자세한 내용을 알아보고 시뮬레이션을 시도해보시고 피싱 공격 [시뮬레이션을 참조합니다.](/microsoft-365/security/office-365-security/attack-simulation-training)