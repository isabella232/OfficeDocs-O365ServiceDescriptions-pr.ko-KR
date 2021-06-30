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
ms.openlocfilehash: 5781f34419eb697cb97634c55fa486fd141d76dd
ms.sourcegitcommit: 7ee8775831fd481ab2ef477245d2ae2af98ac2d7
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/30/2021
ms.locfileid: "53204845"
---
# <a name="microsoft-defender-for-office-365-service-description"></a>Office 365용 Microsoft Defender 서비스 설명

Microsoft Defender for Office 365 피싱, 비즈니스 전자 메일 손상 및 맬웨어 공격과 같은 전자 메일 및 공동 작업 도구에 대한 고급 위협으로부터 조직을 보호하는 클라우드 기반 전자 메일 필터링 서비스입니다. 또한 Office 365 Defender는 보안 팀이 위협을 효율적으로 식별, 우선 순위 지정, 조사 및 대응하는 데 도움이 되는 조사, 헌팅 및 수정 기능을 제공합니다.

메시지 보호를 위해 Defender를 사용하여 Office 365 기본 방법은 다음과 같습니다.

- Office 365 필터링 전용 시나리오에서 Office 365 Defender for Exchange Server 환경 또는 기타 모든 사내 SMTP 전자 메일 솔루션에 대해 클라우드 기반 전자 메일 보호를 제공합니다.

- 클라우드 호스트 Office 365 사서함을 보호하기 위해 Exchange Online 수 있습니다. 자세한 내용은 Exchange Online 서비스 [설명을 Exchange Online 참조하세요.](exchange-online-service-description/exchange-online-service-description.md)

- 하이브리드 배포에서는 인바운드 전자 메일 필터링에 Office 365 사서함과 클라우드 사서함이 혼합된 경우 메시징 환경을 보호하고 메일 라우팅을 Exchange Online Protection Defender for Exchange Online Protection 수 있습니다.

## <a name="available-plans"></a>사용 가능한 계획

Microsoft Defender for Office 365 구독에 대한 자세한 계획 정보는 전체 구독 비교 표를 [참조하세요.](https://go.microsoft.com/fwlink/?linkid=2139145)

## <a name="feature-availability"></a>기능 가용성

다음 표에는 계획에서 사용할 수 있는 Office 365 Microsoft Defender의 주요 기능이 나열되어 있습니다. 특정 주의가 적용됩니다. 자세한 내용은 각주를 참조하세요. 이 표는 예고 없이 변경될 수 있습니다. 계획 전반에 걸쳐 다양한 기능에 대한 Microsoft Defender의 전체 최신 Office 365 내용은 [Microsoft Defender for Office 365 Features service description을 참조하세요.](microsoft-defender-for-office-365-features.md)

| 기능 | Office 365용 Defender 플랜 1 | Office 365용 Defender 플랜 2 | Microsoft 365 E5 / A5 보안 |
|---------|--------------------------------|--------------------------------|--------------------------------|
| *구성, 보호 및 검색* | | | |
| 보안 정책 및 구성 분석기 미리 설정 | 예 | 예 | 예 |
| [안전한 첨부 파일](microsoft-defender-for-office-365-features.md#safe-attachments) | 예 | 예 | 예 |
| 금고 Teams | 예 | 예 | 예 |
| [안전한 링크](microsoft-defender-for-office-365-features.md#safe-links) | 예 | 예 | 예 |
| [안전한 문서](microsoft-defender-for-office-365-features.md#safe-documents) | 아니요 | 아니요 | 예 |
| Teams의 안전한 링크 | 예 | 예 | 예 |
| 보고서 메시지 Add-In | 예 | 예 | 예 |
| [SharePoint, OneDrive 및 Microsoft Teams](microsoft-defender-for-office-365-features.md#protection-for-sharepoint-onedrive-and-microsoft-teams) | 예 | 예 | 예 |
| [피싱 방지 정책](microsoft-defender-for-office-365-features.md#anti-phishing-policies) | 예 | 예 | 예 |
| [실시간 보고서](microsoft-defender-for-office-365-features.md#real-time-reports) | 예 | 예 | 예 |
| 내부 메일에 대한 고급 보호 | 예 | 예 | 예 |
| *자동화, 조사, 수정 및 교육* | | | |
| [위협 트래커](microsoft-defender-for-office-365-features.md#threat-trackers) | 아니요 | 예 | 예 |
| 캠페인 보기 | 아니요 | 예 | 예 |
| 위협 조사(고급 위협 조사) | [실시간 탐지](microsoft-defender-for-office-365-features.md#real-time-detections) | [탐색기](microsoft-defender-for-office-365-features.md#threat-explorer) | [탐색기](microsoft-defender-for-office-365-features.md#threat-explorer) |
| [자동화된 조사 & 응답](microsoft-defender-for-office-365-features.md#automated-investigation--response) | 아니요 | 예 | 예 |
| [공격 시뮬레이션 교육](microsoft-defender-for-office-365-features.md#attack-simulation-training) | 아니요 | 예 | 예 |
| *통합 [Microsoft 365 Defender](/microsoft-365/security/defender/microsoft-365-defender)* | 아니요 | 예 | 예 |

> [!NOTE]
> Microsoft Defender for Office 365 구성 요소는 Microsoft 365 Defender. 도메인 간 보안에 대한 자세한 내용은 Microsoft 365 Defender 요구 [Microsoft 365 Defender 참조하세요.](/microsoft-365/security/mtp/prerequisites)

## <a name="learn-more"></a>자세한 정보

Microsoft Defender for Office 365 자세한 내용은 다음 리소스를 참조하십시오.

- [Microsoft Docs의 Office 365 Microsoft Defender](/microsoft-365/security/office-365-security/defender-for-office-365)
- [Microsoft Defender for Office 365 웹 사이트](https://www.microsoft.com/security/business/threat-protection/office-365-defender)
- [Microsoft Defender for Office 365 블로그](https://techcommunity.microsoft.com/t5/microsoft-defender-for-office/bg-p/MicrosoftDefenderforOffice365Blog)
- [Microsoft Defender for Office 365 포럼](https://techcommunity.microsoft.com/t5/microsoft-defender-for-office/bd-p/MicrosoftDefenderforOffice365)

### <a name="licensing-terms"></a>사용 조건

Microsoft 상업용 볼륨 라이선스 프로그램을 통해 구매한 제품 및 서비스에 대한 사용 조건은 제품 사용 조건 [사이트를 참조하세요.](https://www.microsoft.com/licensing/terms/)

### <a name="messaging"></a>메시징

새 기능 및 변경된 기능, 계획된 유지 관리 또는 기타 중요한 공지 사항을 포함하여 예정된 변경 내용에 대한 정보를 확인하기 위해 메시지 센터를 방문합니다. 자세한 내용은 메시지 센터 [를 참조하세요.](/microsoft-365/admin/manage/message-center)

### <a name="accessibility"></a>내게 필요한 옵션

Microsoft는 사용자의 데이터 보안 및 서비스의 접근성을 위해 계속 최선을 [다하고](https://www.microsoft.com/trust-center/compliance/accessibility) 있습니다. 자세한 내용은 Microsoft [보안](https://www.microsoft.com/trust-center) 센터 및 Office [접근성 센터를 참조하세요.](https://support.office.com/article/ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d)
