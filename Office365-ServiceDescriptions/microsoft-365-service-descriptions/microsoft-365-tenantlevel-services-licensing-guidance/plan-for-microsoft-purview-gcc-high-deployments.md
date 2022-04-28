---
title: Microsoft Purview 계획 - GCC 높은 배포
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
description: 이 지침은 미국 연방 정부 기관 또는 정부 규정 및 요구 사항의 적용을 받는 데이터를 처리하는 기타 기관에서 Office 365 배포를 유도하는 IT 전문가를 위한 것입니다. 여기서 Microsoft 365 Government의 사용 – GCC High는 이러한 요구 사항을 충족하는 데 적합합니다.
ms.openlocfilehash: ee48e17341b6b24255859238b4ea96152b6a01ee
ms.sourcegitcommit: f726c50abbc680dee8beaf602260916a28f0263e
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/27/2022
ms.locfileid: "65076990"
---
# <a name="plan-for-microsoft-purview-compliance-and-risk-management-solutions--gcc-high-deployments"></a>Microsoft Purview 규정 준수 및 위험 관리 솔루션 계획 - GCC 높은 배포

이 지침은 미국 연방 정부 기관 또는 정부 규정 및 요구 사항의 적용을 받는 데이터를 처리하는 기타 기관에서 Office 365 배포를 유도하는 IT 전문가를 위한 것입니다. 여기서 Microsoft 365 Government의 사용 – GCC High는 이러한 요구 사항을 충족하는 데 적합합니다.

> [!NOTE]
>조직에서 이미 Microsoft 365 정부–GCC 높은 자격 요구 사항을 충족하고 프로그램에 신청하고 수락한 경우 1단계와 2단계를 건너뛰고 3단계로 직접 이동하면 됩니다.
 
## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government--gcc-high-and-meets-eligibility-requirements"></a>1단계. 조직에 Microsoft 365 Government가 필요한지 여부 확인 - GCC 높음 및 자격 요구 사항 충족

Microsoft 365 Government - GCC High 환경은 클라우드 서비스에 대한 미국 정부의 요구 사항을 준수합니다. 조직은 Office 365 기능과 기능을 즐기는 것 외에도 Microsoft 365 정부 – GCC High에 고유한 다음과 같은 기능을 활용할 수 있습니다.

- 조직의 고객 콘텐츠는 Microsoft의 상업용 Office 365 서비스의 고객 콘텐츠와 논리적으로 분리됩니다.
- 조직의 고객 콘텐츠는 미국에 보관됩니다.
- 조직 고객 콘텐츠에 대한 액세스는 선별된 Microsoft 직원으로 제한됩니다.
- Microsoft 365 Government – GCC High는 미국 공공 부문 고객에게 필요한 인증 및 인증을 준수합니다.

자격 요구 사항을 포함하여 Office 365 Government 계획에서 미국 정부 고객을 위한 Microsoft 365 정부 - [GCC](https://products.office.com/government/compare-office-365-government-plans) High 제품에 대한 자세한 정보를 찾을 수 있습니다.

[Office 365 미국 정부 서비스 설명](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md)은 미국 내 규정 준수 요구 사항을 충족하는 데 중점을 두는 플랫폼의 이점을 설명합니다.

> [!TIP]
> 서비스 설명의 정보 테이블을 Excel 통합 문서로 전송하고 조직 **Y/N과 관련이** 있고 **조직의 요구 사항을 충족하는** 두 개의 열을 추가할 수 있습니다. 그런 다음 동료와 함께 이 목록을 검토하여 이 서비스가 조직의 요구 사항을 충족하는지 확인할 수 있습니다.

**의사 결정 사항**:<br/>

- *Microsoft 365 정부 - GCC-High 조직에 적합한지 여부를 결정합니다.*
- *조직이 자격 요구 사항을 충족하는지 확인합니다.*

> [!NOTE]
> Microsoft 365 Government - GCC High는 미국만 사용할 수 있습니다. 미국 정부 이외의 고객은 다양한 [Office 365 Government 플랜](https://products.office.com/government/compare-office-365-government-plans) 중에서 선택할 수 있습니다.

## <a name="step-2-apply-for-microsoft-365-government--gcc-high"></a>2단계. Microsoft 365 정부 신청 – GCC-High

이 서비스가 조직에 적합하다는 것을 결정한 후 [이 서비스에 적용하는](https://products.office.com/government/eligibility-validation) 프로세스를 시작합니다.

## <a name="step-3-understand-microsoft-365-government--gcc-high-default-security-settings"></a>3단계. Microsoft 365 Government 이해 - 기본 보안 설정 GCC-High

관리자 및 보안 설정을 수정하기 전에 신중하게 검토하고 기본 보안 설정을 변경하기 전에 규정 준수에 미치는 영향을 고려하는 것이 좋습니다.

**의사 결정 지점**: *기본 Microsoft 365 정부-GCC-High 보안 설정을 수정할지 여부를 결정하여 변경 내용의 영향을 먼저 파악합니다.*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gcc-highsup1sup"></a>4단계. Microsoft 365 Government에서 현재 사용할 수 없거나 사용하지 않도록 설정된 기능 이해 - <sup>GCC-High1</sup>

정부 클라우드 고객의 요구 사항을 충족하기 위해 Microsoft 365 정부(GCC-High 및 엔터프라이즈 계획) 간에는 몇 가지 차이점이 있습니다. 사용 가능한 기능을 보려면 다음 표를 참조하세요. Microsoft 365 로드맵에 게시된 최신 규정 준수 제품 업데이트는 [여기](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent)를 참조하세요.<br><br>

| 영역 | 기능 | GCC 높음 상태 |
|------|---------|-----------------|
| **정보 보호** |  |  |
| 중요한 정보 유형 | 정확한 데이터 일치 | 사용 가능 |
|  | 명명된 엔터티 중요한 정보 유형 및 정책 작성 템플릿 | 엔지니어링 백로그에서 |
| 민감도 레이블 지정 | 통합 레이블 지정 클라이언트 및 스캐너  | 사용 가능 |
|  | SharePoint Online 문서 라이브러리에 업로드된 레이블이 지정되지 않은 파일에 "기본 레이블"을 적용합니다. | 개발 중 |
|  | 문서를 편집할 수 있도록 기본 레이블 정책 적용 | 개발 중 |
|  | Exchange Online, SharePoint Online 및 OneDrive 대한 자동 분류 및 레이블 지정 | 사용 가능 |
|  | 플랫폼(웹, Android, iOS, Windows 및 Mac)에서 Office 앱(Word, Excel, PowerPoint, Outlook)에 대한 자동 분류 및 레이블 지정 | 사용 가능 |
|  | Office 클라이언트에 대한 자동 분류 및 레이블 지정(모바일) | 엔지니어링 백로그에서 |
|  | Teams, Microsoft 365 그룹 및 SharePoint 사이트에 대한 자동 분류 및 레이블 지정 | 사용 가능 |
|  | Microsoft Information Protection 암호화 문서에 대한 공동 작성 | 사용 가능 |
|  | SharePoint Online 및 비즈니스용 OneDrive 자동 레이블 지정에 대한 향상된 시뮬레이션 및 위치 지원 | 배포 중 |
|  | Microsoft Azure Purview를 사용하여 기본 제공 민감도 레이블을 Azure의 자산으로 확장 | 개발 중 |
|  | SharePoint Online 사이트에 대한 "민감도 레이블"을 통한 세분화된 조건부 액세스 정책 | 엔지니어링 백로그에서 |
|  | 필수 레이블 | 사용 가능 |
|  | 수동 레이블 | 사용 가능 |
|  | Exchange Online 자동 레이블 지정에 대한 새로운 조건 | 개발 중 |
| 분석 | 데이터 분류 분석: 개요 및 콘텐츠 탐색기 | 사용 가능 |
|  | Office 앱의 감사 및 분석 | 사용 가능 |
|  | 활동 탐색기에는 Power BI 민감도 레이블 데이터가 포함됩니다. | 사용 가능 |
|  | 활동 탐색기 기본 제공 필터 | 사용 가능 |
|  | 콘텐츠 탐색기에는 Teams 데이터가 포함됩니다. | 개발 중 |
|  | Office 앱/클라이언트 쪽에서 자동 레이블 지정이 있는 기계 학습 분류자 | 사용 가능 |
| 암호화 | 기본 Office 365 메시지 암호화(E3) | 사용 가능 |
|  | 고급 Office 365 메시지 암호화(E5) | 사용 가능 |
|  | Office 365에 대한 고객 키 | 사용 가능 |
|  | 고객 키: Microsoft 365 대한 미사용 데이터 암호화 | 사용 가능 |
|  | 고객 키: SharePoint Online 및 비즈니스용 OneDrive | 사용 가능 |
|  | 고객 관리형 키 프로비전 수명 주기를 위한 BYOK(Bring Your Own Key) | 사용 가능 |
|  | 이중 키 암호화 | 사용 가능 |
|  | Microsoft 관리형 키를 사용하여 서비스 암호화 Exchange Online | 사용 가능 |
| 데이터 손실 방지 | 데이터 손실 방지: 경고 대시보드 및 경고 환경 | 사용 가능 |
|  | 파일 및 전자 메일에 대한 데이터 손실 방지 | 사용 가능 |
|  | 데이터 손실 방지: 활동 탐색기에 표시된 데이터 | 사용 가능 |
|  | 데이터 손실 방지: 엔드포인트  | 사용 가능 |
|  | 데이터 손실 방지: Microsoft Defender for Cloud Apps(이전 Microsoft Cloud App Security) 통합 | 사용 가능 |
|  | 온-프레미스에 대한 데이터 손실 방지 | 개발 중 |
|  | 데이터 손실 방지: 개요 페이지 | 사용 가능 |
|  | 데이터 손실 방지: 채팅 및 채널 대화 Teams  | 사용 가능 |
| **정보 거버넌스** |  |  |
| 정보 거버넌스 | 정보 거버넌스: 보존 및 레이블 지정 정책에 대한 적응형 범위 | 사용 가능 |
| | 정보 거버넌스: 보존 기간이 끝나면 보존 레이블 작업 적용 | 엔지니어링 백로그에서 |
| | 정보 거버넌스: SharePoint, 비즈니스용 OneDrive 라이브러리, 폴더 및 문서 집합에 대한 기본 보존 레이블을 적용합니다. 받은 편지함 및 Office 365 그룹 Exchange  | 사용 가능 |
| | 정보 거버넌스: 레코드에 대한 메타데이터를 편집하는 기능을 차단하도록 옵션 구성 | 개발 중 |
| | 정보 거버넌스: 레코드 잠금 해제 사용 안 함 | 개발 중 |
| | 정보 거버넌스: 전자 메일 보관 | 사용 가능 |
| | 정보 거버넌스: PST 가져오기 | 사용 가능 |
| | 정보 거버넌스: 수동 비기록 보존 레이블 | 사용 가능 |
| | 정보 거버넌스: 보존 잠금 | 사용 가능 |
| | 정보 거버넌스: SharePoint Online 및 비즈니스용 OneDrive 대한 보존 개선 사항 | 사용 가능 |
| | 정보 거버넌스: SharePoint 보존 레이블 삭제 동작 변경 | 개발 중 |
| | 정보 거버넌스: 전체 조직에 대한 보존 정책; 특정 위치 또는 사용자; 는 특정 조건(예: 키워드 또는 중요한 정보)에 따라 자동으로 및 이벤트 기반 | 사용 가능 |
| | 정보 거버넌스: Teams 보존 정책 | 사용 가능 |
| | 정보 거버넌스: Teams 모임 녹음/녹화에 대한 보존 정책 | 사용 가능 |
| | 정보 거버넌스: Teams 비공개 채널에 대한 보존 정책 | 사용 가능 |
| 레코드 관리 | 레코드 관리: 레코드 레이블을 삭제하는 기능 | 사용 가능 |
| | 레코드 관리: 수동 레코드 선언에 대해 레코드 레이블이 "잠금 해제됨"으로 시작되도록 허용 | 개발 중 |
| | 레코드 관리: 레코드 레이블을 수동으로 적용 | 사용 가능 |
| | 레코드 관리: SharePoint, 비즈니스용 OneDrive 라이브러리, 폴더 및 문서 집합 및 Office 365 그룹에 대한 기본 레코드 레이블 적용 | 사용 가능 |
| | 레코드 관리: 특정 조건(예: 키워드 또는 중요한 정보)에 따라 레코드 정책을 자동으로 적용합니다. 및 이벤트 기반 | 사용 가능 |
| | 레코드 관리: 학습 가능한 분류자를 사용하여 자동으로 레코드 정책 적용  | 개발 중 |
| | 레코드 관리: 레코드 잠금 해제 사용 안 함 | 개발 중 |
| | 레코드 관리: 처리 검토 | 사용 가능 |
| | 레코드 관리: 파일 계획 관리자 | 사용 가능 |
| | 레코드 관리: 다단계 처리 검토 | 엔지니어링 백로그에서 |
| | 레코드 관리: 레코드 관리에 대한 Outlook 클라이언트 지원 | 개발 중 |
| | 레코드 관리: Power Automate 통합 | 엔지니어링 백로그에서 |
| | 레코드 관리: 폐기 증명 | 사용 가능 |
| | 레코드 관리: 레코드 버전 관리 | 사용 가능 |
| | 레코드 관리: 규정 레코드 | 사용 가능 |
| **리스크 관리** |  |  |
| 고객 Lockbox | 고객 Lockbox | 사용 가능 |
| 커뮤니케이션 규정 준수 | 통신 준수: 통신 준수 정책에 대한 보존 기간을 설정하는 기능 | 공개 미리 보기 |
| | 통신 규정 준수: 액세스 경고; 알림 템플릿; 통신 정책 대시보드 | 사용 가능 |
| | 커뮤니케이션 규정 준수: 온-프레미스 사서함을 사용하여 사용자의 Teams 채팅 데이터 분석 | 사용 가능 |
| | 통신 준수: 사용자가 의 구성원인 Teams 자동으로 모니터링 | 사용 가능 |
| | 커뮤니케이션 규정 준수: 이해 상충 템플릿 | 사용 가능 |
| | 커뮤니케이션 규정 준수: 고객 정책 만들기, 미리 구성된 3개 | 사용 가능 |
| | 커뮤니케이션 규정 준수: 성인 콘텐츠 검색 | 사용 가능 |
| | 통신 규정 준수: 시간에 따른 반복 행동 강령 위반 감지 | 사용 가능 |
| | 커뮤니케이션 규정 준수: 차별 분류자 | 배포 중 |
| | 커뮤니케이션 규정 준수: Advanced eDiscovery 대한 조사를 위해 에스컬레이션 | 사용 가능 |
| | 커뮤니케이션 규정 준수: Exchange 및 Teams 지원 | 사용 가능 |
| | 통신 준수: 정책 상태 검사 및 정책 일시 중지 기능 | 개발 중 |
| | 통신 규정 준수: Power Automate 통합 | 개발 중 |
| | 통신 준수: Teams 채팅 또는 채널에서 Teams 메시지 제거 | 사용 가능 |
| | 통신 준수: 위치 보고서당 중요한 정보 유형  | 개발 중 |
| | 커뮤니케이션 규정 준수: 위협, 대상 괴롭힘 및 욕설 분류자를 위한 7개 언어를 지원합니다. | 사용 가능 |
| | 통신 규정 준수: 보다 세분화된 권한 지원 | 사용 가능 |
| | 커뮤니케이션 규정 준수: Teams, Exchange 및 Teams 메시지 제거 기능 지원 | 사용 가능 |
| | 커뮤니케이션 규정 준수: 대화 컨텍스트 Teams | 사용 가능 |
| | 커뮤니케이션 규정 준수: 조사 중 콘텐츠 번역 | 사용 가능 |
| 정보 장벽 | 정보 장벽 | 사용 가능 |
| 내부자 위험 관리 | 내부 위험 관리: 경고를 내보내는 기능 | 사용 가능 |
| | 참가자 위험 관리: 활동 탐색기 데이터가 표시됩니다. | 사용 가능 |
| | 내부 위험 관리: 분석 | 공개 미리 보기 |
| | 내부자 위험 관리: 사례 대시보드 | 사용 가능 |
| | 참가자 위험 관리: 콘텐츠 탐색기 향상된 기능 | 사용 가능 |
| | 내부자 위험 관리: 불만을 품은 사용자에 의한 데이터 유출 | 개발 중 |
| | 내부자 위험 관리: 퇴사한 사용자에 의한 데이터 도난 | 사용 가능 |
| | 내부자 위험 관리: 우선 순위 사용자에 의한 데이터 도난 | 공개 미리 보기 |
| | 내부자 위험 관리: Advanced eDiscovery 대한 조사를 위해 에스컬레이션 | 사용 가능 |
| | 내부 위험 관리: 경고 내보내기 | 공개 미리 보기 |
| | 내부자 위험 관리: 일반 데이터 누출 | 사용 가능 |
| | 내부 위험 관리: 일반 보안 정책 위반 | 개발 중 |
| | 내부 위험 관리: 보안 정책 위반에 대한 지표 | 개발 중 |
| | 내부자 위험 관리: 엔드포인트용 Microsoft Defender 경고에 대한 지표 | 개발 중 |
| | 내부자 위험 관리: Office 지표(Teams, SharePoint 사이트, 전자 메일 메시지) | 사용 가능  |
| | 내부 위험 관리: Windows 10 엔드포인트 활동에 대한 지표 | 공개 미리 보기  |
| | 참가자 위험 관리: 도메인 설정에 대한 지능형 지원 | 사용 가능 |
| | 내부 위험 관리: Microsoft Teams 통합 | 공개 미리 보기 |
| | 참가자 위험 관리: 네이티브 트리거(새 신호, 표시기 선택, 사용자 지정 및 활동 탐색기) | 사용 가능 |
| | 내부자 위험 관리: Teams, SharePoint 사이트, 전자 메일 메시징에 대한 지표 Office | 사용 가능 |
| | 참가자 위험 관리: 정책 사용자 지정, 정책 상태 검사 및 향상된 정책 만들기 마법사 | 사용 가능 |
| | 내부자 위험 관리: 불만을 품은 사용자의 데이터 유출에 대한 정책 템플릿 | 공개 미리 보기 |
| | 내부 위험 관리: 우선 순위 사용자의 데이터 유출에 대한 정책 템플릿 | 공개 미리 보기 |
| | 내부 위험 관리: 일반 보안 정책 위반에 대한 정책 템플릿 | 개발 중 |
| | 내부자 위험 관리: 우선 순위 사용자, 출발 사용자, 불만을 품은 사용자에 의한 보안 정책 위반에 대한 정책 템플릿 | 개발 중 |
| | 내부 위험 관리: Power Automate 통합 | 개발 중 |
| | 참가자 위험 관리: 우선 순위 사용자 그룹 | 공개 미리 보기 |
| | 내부 위험 관리: 퇴사한 사용자의 보안 정책 위반 | 개발 중 |
| | 내부자 위험 관리: 불만을 품은 사용자의 보안 정책 위반 | 개발 중 |
| | 내부 위험 관리: 우선 순위 사용자의 보안 정책 위반 | 개발 중 |
| | 내부 위험 관리: Azure Active Directory 계정 삭제에 대한 네이티브 트리거 지원 | 사용 가능 |
| | 내부자 위험 관리: 사용자 활동 보고서 | 공개 미리 보기 |
| | 내부자 위험 관리: "감시자 감시자" 감사 추적 | 사용 가능 |
| **응답 검색 &amp;** |  |  |
| eDiscovery | 핵심 eDiscovery: 감사 | 사용 가능 |
| | 핵심 eDiscovery: 사례 관리 | 사용 가능 |
| | 핵심 eDiscovery: 비즈니스용 OneDrive 규정 준수 경계 | 사용 가능 |
| | 핵심 eDiscovery: 내보내기 | 사용 가능 |
| | 핵심 eDiscovery: 현재 위치 보존 | 사용 가능 |
| | Core eDiscovery: 네이티브 내보내기 | 사용 가능 |
| | 핵심 eDiscovery: RMS 암호 해독 | 사용 가능 |
| | 핵심 eDiscovery: 검색 | 사용 가능 |
| | 핵심 eDiscovery: Microsoft 규정 준수 센터에서 SharePoint 및 비즈니스용 OneDrive 휴지통에서 항목을 검색하고 내보내기 위한 지원을 확장했습니다. | 사용 가능 |
| | Advanced eDiscovery: 고급 처리 | 사용 가능 |
| | Advanced eDiscovery: 사례 제한 향상 | 개발 중 |
| | Advanced eDiscovery: SharePoint 및/또는 비즈니스용 OneDrive 암호화된 콘텐츠 수집 및 검토 | 사용 가능 |
| | Advanced eDiscovery: Teams 대화를 대본으로 수집 | 개발 중 |
| | Advanced eDiscovery: 통신 템플릿 및 발급 임원 설정 | 개발 중 |
| | Advanced eDiscovery: 관리자와 워크로드 매핑 | 사용 가능 |
| | Advanced eDiscovery: 보유자 통신 | 사용 가능 |
| | Advanced eDiscovery: 대시보드 | 사용 가능 |
| | Advanced eDiscovery: Microsoft Teams 대한 데이터 제거 기능  | 개발 중 |
| | Advanced eDiscovery: 심층 크롤링/인덱싱 | 사용 가능 |
| | Advanced eDiscovery: 더블 바이트 문자 지원(중국어, 일본어, 한국어) | 사용 가능 |
| | Advanced eDiscovery: 이메일 스레딩 | 사용 가능 |
| | Advanced eDiscovery: 향상된 가져오기 보유자 마법사 환경 | 개발 중 |
| | Advanced eDiscovery: 내보내기(다운로드, 내보내기, 다른 보기 집합에 추가) | 사용 가능 |
| | Advanced eDiscovery: 필터링 | 사용 가능 |
| | Advanced eDiscovery: Graph API | 개발 중 |
| | Advanced eDiscovery: 기록 버전 | 개발 중 |
| | Advanced eDiscovery: 최적화 유지 | 개발 중 |
| | Advanced eDiscovery: 데이터 원본으로 Teams 식별 | 엔지니어링 백로그에서 |
| | Advanced eDiscovery: Teams 비공개 채널 메시지에 대한 법적 보존 | 사용 가능 |
| | Advanced eDiscovery: Microsoft 규정 준수 센터에서 SharePoint 및 비즈니스용 OneDrive 휴지통에서 항목을 검색하고 내보내기 위한 지원을 확장했습니다. | 개발 중 |
| | Advanced eDiscovery: 거의 중복 식별 | 사용 가능 |
| | Advanced eDiscovery: Core 및 Advanced eDiscovery 대한 새로운 내보내기 환경  | 개발 중 |
| | Advanced eDiscovery: 새로운 예측 코딩 모듈 및 처리 | 엔지니어링 백로그에서 |
| | Advanced eDiscovery: 비보관 데이터 원본 | 사용 가능 |
| | Advanced eDiscovery: 비 Office 365 수집 | 사용 가능 |
| | Advanced eDiscovery: 예측 코딩 | 사용 가능 |
| | Advanced eDiscovery: 로드 파일을 사용하여 처리된 내보내기 | 사용 가능 |
| | Advanced eDiscovery: 수정 | 사용 가능 |
| | Advanced eDiscovery: 집합 검토 | 사용 가능 |
| | Advanced eDiscovery: 데이터 검토(쿼리 데이터, 스마트 태그, 대시보드) 및 주석 달기(수정) | 사용 가능 |
| | Advanced eDiscovery: 검색어 보고서 | 사용 가능 |
| | Advanced eDiscovery: 단일 항목 오류 수정 | 사용 가능 |
| | Advanced eDiscovery: PST 내보내기 지원 | 사용 가능 |
| | Advanced eDiscovery: OneDrive 및 SharePoint Online에서 연결된 콘텐츠 지원(최신 첨부 파일) | 사용 가능 |
| | Advanced eDiscovery: Teams 반응 지원 | 개발 중 |
| | Advanced eDiscovery: 태그 지정 | 사용 가능 |
| | Advanced eDiscovery: 테넌트 보고서 | 사용 가능 |
| | Advanced eDiscovery: 테마 | 사용 가능 |
| | Advanced eDiscovery: 뷰어 | 사용 가능 |
| | Advanced eDiscovery: Microsoft 규정 준수 센터의 Yammer Advanced eDiscovery | 사용 가능 |
| 감사 | 기본 감사 | 사용 가능 |
| | 고급 감사: 중요한 이벤트에 대한 액세스(예: *MailItemsAccessed*) | 사용 가능 |
| | 고급 감사: 감사 보존 대시보드 | 사용 가능 |
| | 고급 감사: 감사 검색 기능 향상 | 엔지니어링 백로그에서 |
| | 고급 감사: 관리 작업 API에 대한 대역폭 증가 | 사용 가능 |
| | 고급 감사: Teams 비공개 채널 메시지에 대한 법적 보존 | 사용 가능 |
| | 고급 감사: 로그 보존(1년) | 사용 가능 |
| | 고급 감사: 감사 로그에 대한 장기 보존(10년) | 사용 가능 |
| | 고급 감사: 메일 전달 및 메일 보내기 이벤트 | 사용 가능 |
| | 고급 감사: Microsoft 365 보안 및 규정 준수 센터 | 사용 가능 |
| | 고급 감사: Exchange Online 및 SharePoint Online에서 용어 이벤트 검색 | 사용 가능 |
| **준수 관리** |  |  |
| 준수 관리 | Microsoft 365 규정 준수 센터 | 사용 가능 |
| | 규정 관리자 | 사용 가능 |
| | 준수 관리자: 지속적인 규정 준수 평가 | 개발 중 |
| | 준수 관리자: Microsoft 365 아닌 자산에 대한 기본 평가 | 사용 가능 |
| | 더블 바이트 문자 지원 | 사용 가능 |
| | Microsoft Defender for Cloud Apps(이전 Microsoft Cloud App Security) | 사용 가능 |
| **생태계** |  |  |
| 생태계 | 자사 데이터 커넥터: HR  | 사용 가능 |
| | 자사 데이터 커넥터: HR 1.2 | 사용 가능 |
| | 자사 데이터 커넥터: 물리적 불량 | 사용 가능 |
| | Advanced eDiscovery 대한 API Graph  | 개발 중 |
| | 레코드 관리를 위한 Graph API(공개 미리 보기) | 개발 중 |
| | Teams 내보내기 데이터를 위한 API Graph | 개발 중 |
| **개인 정보** |  |  |
| 개인 정보 관리 | Microsoft Priva | 개발 중 |

<sup>1</sup> 식별된 상태는 프로젝트 계획 및 우선 순위가 다시 평가됨에 따라 변경될 수 있습니다.<br/>

**의사 결정 지점**: *규정 준수 기능이 조직의 요구 사항을 충족하는지 여부를 결정합니다.*
