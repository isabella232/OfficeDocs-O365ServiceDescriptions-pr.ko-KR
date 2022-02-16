---
title: Microsoft 365 규정 준수 - DoD 배포 계획
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
description: 이 지침은 미국 연방 정부 기관 또는 정부 규정 및 요구 사항을 준수하는 데이터를 처리하는 기타 엔터티에서 Office 365 배포를 주도하는 IT 프로를 위한 것입니다. 이러한 요구 사항을 충족하는 데 Microsoft 365 Government – DoD를 사용하는 것이 적절합니다.
ms.openlocfilehash: f400e2a7d6a6ee127247490f3c0f566fd0d7d74f
ms.sourcegitcommit: dc988a858c4df5da81edfef407a01f917a37c52c
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/15/2022
ms.locfileid: "62824381"
---
# <a name="plan-for-microsoft-365-compliance---dod-deployments"></a>Microsoft 365 규정 준수 - DoD 배포 계획

이 지침은 미국 연방 정부 기관 또는 정부 규정 및 요구 사항을 준수하는 데이터를 처리하는 기타 엔터티에서 Office 365 배포를 주도하는 IT 프로를 위한 것입니다. 이러한 요구 사항을 충족하는 데 Microsoft 365 Government – DoD를 사용하는 것이 적절합니다.

> [!NOTE]
> 조직이 이미 Microsoft 365 Government – DoD 자격 요구 사항을 충족하고 프로그램에 적용되고 프로그램에 수락된 경우 1단계와 2단계를 건너뛰고 3단계로 바로 이동하면 됩니다.

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---dod-and-meets-eligibility-requirements"></a>1단계. 조직에서 정부에 필요한 Microsoft 365 - DoD 및 자격 요구 사항을 충족하는지 확인

Microsoft 365 - DoD 환경은 클라우드 서비스에 대한 미국 정부 요구 사항을 준수합니다.

조직은 조직의 기능과 기능을 Office 365 Government - DoD에 고유한 다음과 같은 Microsoft 365 이점을 제공합니다.

- 조직의 고객 콘텐츠는 Microsoft의 상용 서비스에서 고객 콘텐츠와 Office 365 있습니다.
- 조직의 고객 콘텐츠는 미국에 보관됩니다.
- 조직 고객 콘텐츠에 대한 액세스는 선별된 Microsoft 직원으로 제한됩니다.
- Microsoft 365 - DoD는 미국 공공 부문 고객에게 필요한 인증 및 인증을 준수합니다.

미국 정부 고객을 위한 Microsoft 365 - DoD 제공에 대한 자세한 내용은 자격 요구 사항을 포함하여 Office 365 Government 계획에서 찾을 [](https://products.office.com/government/compare-office-365-government-plans)수 있습니다.

이 [Office 365 미국](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md) 정부 서비스 설명에서는 미국 내 규정 준수 요구 사항을 충족하는 데 중심을 두는 플랫폼의 이점에 대해 설명하고 있습니다.

> [!TIP]
> 서비스 설명의 정보 표를 Excel 통합 문서로 전송하고 조직의 **Y/N** 과 관련이 있으며 조직의 요구 사항을 충족하는 두 개의 열을 추가할 수 **있습니다**. 그런 다음 이 목록을 동료와 검토하여 이 서비스가 조직의 요구 사항을 충족하는지 확인할 수 있습니다.

**결정 지점**:<br/>
- *조직에 Microsoft 365 - DoD가 조직에 적합한지 여부를 결정하십시오.*
- *조직이 자격 요구 사항을 충족하는지 확인합니다.*

> [!NOTE]
> Microsoft 365 - DoD는 미국에서만 사용할 수 있습니다. 미국 정부 이 아닌 고객은 다양한 요금제에서 Office 365 Government [있습니다](https://products.office.com/government/compare-office-365-government-plans).

## <a name="step-2-apply-for-microsoft-365-government---dod"></a>2단계. 정부 Microsoft 365 신청 - DoD

이 서비스가 조직에 적합한 것으로 결정한 경우 이 서비스에 대한 적용 [프로세스를 시작하십시오](https://products.office.com/government/eligibility-validation).

## <a name="step-3-understand-microsoft-365-government---dod-default-security-settings"></a>3단계. 정부 Microsoft 365 - DoD 기본 보안 설정 이해

관리자 및 보안 설정을 수정하기 전에 신중하게 검토하고 기본 보안 설정을 변경하기 전에 규정 준수에 미치는 영향을 고려하는 것이 좋습니다.

**의사** 결정 지점: *기본 Microsoft 365 Government - DoD* 보안 설정을 수정할지 여부를 결정하여 변경 내용이 미치는 영향을 먼저 파악합니다.

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--dodsup1sup"></a>4단계. Government – <sup>DoD1</sup>에서 현재 사용할 수 없거나 사용하지 않도록 설정되어 있는 Microsoft 365 이해

정부 클라우드 고객의 요구 사항을 충족하기 위해 정부- DoD 및 엔터프라이즈 Microsoft 365 몇 가지 차이점이 있습니다. 다음 표를 참조하여 사용 가능한 기능을 참조합니다. 이 [로드](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent)맵에 게시된 최신 준수 제품 업데이트는 Microsoft 365 참조하세요.<br><br>

| 영역  | 기능  | DoD 상태  |
|-------|----------|-------------|
| **정보 보호**  | | |
| 중요한 정보 유형  | 정확한 데이터 일치  | 사용 가능  |
| | 명명된 엔터티 중요한 정보 유형 및 정책 제작 템플릿 | 개발 중  |
| 민감도 레이블 지정  | 통합 레이블 클라이언트 및 스캐너 | 사용 가능  |
| | 온라인 문서 라이브러리에 업로드된 레이블이 없는 파일에 "기본 레이블"SharePoint 적용 | 개발 중 |
| | 기본 레이블 정책을 적용하여 문서를 편집할 수 있도록 합니다. | 개발 중 |
| | Exchange Online, SharePoint Online 및 비즈니스용 OneDrive  | 사용 가능 |
| | 플랫폼(웹, Windows 및 Mac)에서 Office 앱(Word, Excel, PowerPoint, Outlook)에 대한 자동 분류 및 레이블 지정  | 사용 가능  |
| | Office 클라이언트에 대한 자동 분류 및 레이블 지정 - 모바일  | 백로그 엔지니어링  |
| | Teams, Microsoft 365 그룹 및 SharePoint 분류 및 레이블 지정  | 사용 가능  |
| | 암호화 문서에 Microsoft Information Protection 공동 작성| 사용 가능  |
| | SharePoint Online 및 2016에서 자동 레이블 지정에 대한 향상된 시뮬레이션 및 위치 비즈니스용 OneDrive | 배포 중  |
| | Perview를 사용하여 기본 제공 민감도 레이블을 Azure의 자산으로 Microsoft Azure 확장 | 개발 중  |
| | 온라인 사이트에 대해 "민감도 레이블"을 통해 세부적인 SharePoint 액세스 정책 | 백로그 엔지니어링  |
| | 필수 레이블  | 사용 가능  |
| | 수동 레이블  | 사용 가능  |
| | 자동 레이블 지정에 대한 새로운 Exchange Online| 개발 중 |
| 분석  | 데이터 분류 분석: 개요 및 콘텐츠 탐색기 | 사용 가능 |
| | 앱의 감사 Office 분석 | 사용 가능 |
| | 활동 탐색기에는 Power BI 레이블 데이터가 포함됩니다. | 사용 가능 |
| | 활동 탐색기 기본 제공 필터 | 사용 가능 |
| | 콘텐츠 탐색기에는 Teams 포함 | 개발 중 |
| | 앱/클라이언트 쪽에서 자동 Office 기계 학습 분류자  | 사용 가능 |
| 암호화  | 기본 Office 365 메시지 암호화(E3) | 사용 가능 |
| | 고급 Office 365 메시지 암호화(E5) | TBD |
| | Office 365에 대한 고객 키 | 사용 가능 |
| | 고객 키: 사용자에 대한 미사용 데이터 Microsoft 365 | 사용 가능 |
| | 고객 키: SharePoint 온라인 및 비즈니스용 OneDrive | 사용 가능 |
| | 고객 관리 키 프로비전 수명 주기를 위해 BYOK(Bring Your Own Key)를 가져오기 | 사용 가능 |
| | 이중 키 암호화  | 사용 가능 |
| | Exchange Online 키를 사용하여 서비스 암호화 | 사용 가능 |
| 데이터 손실 방지  | 데이터 손실 방지: 경고 대시보드 및 경고 환경 | 사용 가능 |
| | 파일 및 전자 메일에 대한 데이터 손실 방지 | 사용 가능 |
| | 데이터 손실 방지: 활동 탐색기에 표시됩니다. | 사용 가능 |
| | 데이터 손실 방지: 끝점 | 사용 가능 |
| | 데이터 손실 방지: Microsoft Defender for Apps(이전 Microsoft Cloud App Security) 통합 | 사용 가능 |
| | On-prem에 대한 데이터 손실 방지 | 개발 중 |
| | 데이터 손실 방지: 개요 페이지 | 사용 가능 |
| | 데이터 손실 방지: Teams 및 채널 대화 | 사용 가능 |
| 정보 거버넌스  | 정보 거버넌스: 보존 및 레이블 지정 정책에 대한 적응형 범위 | 사용 가능   |
| | 정보 거버넌스: 보존 기간 종료 시 보존 레이블 작업 적용 | 백로그 엔지니어링 |
| | 정보 거버넌스: SharePoint, 비즈니스용 OneDrive, 폴더 및 문서 집합에 대한 기본 보존 레이블을 적용합니다. Exchange 받은 편지함 및 Office 365 그룹 | 사용 가능 |
| | 정보 거버넌스: 레코드에 대한 메타데이터 편집 기능을 차단하는 옵션 구성 | 개발 중 |
| | 정보 거버넌스: 레코드 잠금 해제 해제 | 개발 중 |
| | 정보 거버넌스: 전자 메일 보관 | 사용 가능 |
| | 정보 거버넌스: PST 가져오기 | 사용 가능  |
| | 정보 거버넌스: 수동 비기록 보존 레이블 | 사용 가능 |
| | 정보 거버넌스: 보존 잠금 | 사용 가능 |
| | 정보 거버넌스: SharePoint Online 및 비즈니스용 OneDrive  | 사용 가능 |
| | 정보 거버넌스: 보존 레이블 삭제 동작이 SharePoint  | 개발 중 |
| | 정보 거버넌스: 전체 조직에 대한 보존 정책 특정 위치 또는 사용자 특정 조건에 따라 자동으로(예: 키워드 또는 중요한 정보) 및 이벤트 기반 | 사용 가능 |
| | 정보 거버넌스: 관리에 대한 Teams | 사용 가능 |
| | 정보 거버넌스: 모임 Teams 보존 정책 | 사용 가능   |
| | 정보 거버넌스: 개인 채널에 Teams 정책 | 사용 가능   |
| 레코드 관리 | 레코드 레이블을 삭제하는 능력 | 사용 가능 |
| | 레코드 관리: 수동 레코드 선언에 대해 레코드 레이블이 "잠금 해제"를 시작할 수 있도록 허용 | 개발 중 |
| | 레코드 관리: 수동으로 레코드 레이블 적용  | 사용 가능 |
| | 레코드 관리: SharePoint, 비즈니스용 OneDrive 라이브러리, 폴더 및 문서 집합 및 Office 365 그룹에 대한 기본 레코드 레이블 적용 | 사용 가능  |
| | 레코드 관리: 특정 조건(예: 키워드 또는 중요한 정보)에 따라 레코드 정책을 자동으로 적용합니다. 및 이벤트 기반 | 사용 가능  |
| | 레코드 관리: 학습 가능한 분류자에 레코드 정책 자동 적용 | 개발 중 |
| | 레코드 관리: 레코드 잠금 해제 해제 | 개발 중 |
| | 레코드 관리: 파기 검토 | 사용 가능 |
| | 레코드 관리: 파일 계획 관리자 | 사용 가능 |
| | 레코드 관리: 다단계 분해 검토 | 백로그 엔지니어링 |
| | 레코드 관리: Outlook 클라이언트 지원 | 개발 중 |
| | 레코드 관리: Power Automate 통합 | 백로그 엔지니어링  |
| | 레코드 관리: 폐기 증명 | 사용 가능 |
| | 레코드 관리: 레코드 버전 관리 | 사용 가능 |
| | 레코드 관리: 규정 레코드 | 사용 가능 |
| **리스크 관리**  | | |
| 고객 Lockbox | 고객 Lockbox  | 사용 가능  |
| 커뮤니케이션 규정 준수  | 통신 준수: 통신 준수 정책에 대한 보존 기간을 설정하는 능력 | 공개 미리 보기 |
| | 통신 규정 준수: 알림 액세스 알림 서식 파일 통신 정책 대시보드 | 사용 가능 |
| | 통신 준수: Teams 사서함을 사용하여 사용자의 채팅 데이터 분석 | 사용 가능 |
| | 커뮤니케이션 규정 준수: 사용자가 구성원인 Teams 자동으로 모니터링 | 사용 가능 |
| | 통신 규정 준수: 이해 상충 템플릿 | 사용 가능 |
| | 커뮤니케이션 규정 준수: 고객 정책 만들기, 미리 구성된 3개 | 사용 가능 |
| | 커뮤니케이션 규정 준수: 성인용 콘텐츠 검색 | 사용 가능 |
| | 통신 규정 준수: 시간의에 따라 반복되는 행동 위반 감지 | 사용 가능 |
| | 커뮤니케이션 규정 준수: 차별 분류자 | 배포 중 |
| | 통신 규정 준수: 에스컬레이터에서 Advanced eDiscovery | 사용 가능 |
| | 커뮤니케이션 규정 준수: Exchange Teams 지원 | 사용 가능 |
| | 통신 준수: 정책 상태 검사 및 정책 일시 중지 능력  | 개발 중  |
| | 통신 규정 준수: Power Automate 통합 | 개발 중 |
| | 통신 준수: Teams 채널에서 Teams 메시지 제거 | 사용 가능 |
| | 통신 준수: 위치 보고서당 중요한 정보 유형  | 개발 중 |
| | 커뮤니케이션 규정 준수: 보다 세부적인 사용 권한 지원 | 사용 가능 |
| | 커뮤니케이션 규정 준수: 위협, 대상 괴롭음 및 비언어 분류자에 대한 7개 언어 지원  | 사용 가능 |
| | 커뮤니케이션 규정 준수: Teams, Exchange 및 메시지 제거 기능을 Teams 지원 | 사용 가능 |
| | 통신 규정 준수: Teams 컨텍스트 관리 | 사용 가능 |
| | 커뮤니케이션 규정 준수: 조사 중에 콘텐츠 번역 | 사용 가능 |
| 정보 장벽 | 정보 장벽 | 사용 가능 |
| 내부자 위험 관리 | 내부자 위험 관리: 경고 내보내기 | 사용 가능 |
| | 내부자 위험 관리: 활동 탐색기 데이터 노출 | 사용 가능 |
| | 내부자 위험 관리: 분석 | 공개 미리 보기 |
| | 내부자 위험 관리: 사례 대시보드 | 사용 가능 |
| | 내부자 위험 관리: 향상된 콘텐츠 탐색기 | 사용 가능 |  
| | 내부자 위험 관리: 불만이 있는 사용자의 데이터 누수 | 개발 중 |
| | 내부자 위험 관리: 떠날 사용자의 데이터 도용 | 사용 가능 |
| | 내부자 위험 관리: 우선 순위 사용자에 의해 데이터 도용 | 공개 미리 보기 |
| | 내부자 위험 관리: 내부자 위험 관리에 대한 조사 Advanced eDiscovery | 사용 가능  |
| | 내부자 위험 관리: 경고 내보내기 | 공개 미리 보기 |
| | 내부자 위험 관리: 일반 데이터 누수 | 사용 가능 |
| | 내부자 위험 관리: 일반 보안 정책 위반 | 개발 중 |
| | 내부자 위험 관리: 보안 정책 위반 표시기 | 개발 중 |
| | 내부자 위험 관리: 끝점 경고에 대한 Microsoft Defender 표시기  | 개발 중 |
| | 내부자 위험 관리: Office(Teams, SharePoint, 전자 메일 메시징) 표시기  | 사용 가능 |
| | 내부자 위험 관리: Windows 10 끝점 활동에 대한 표시기 | 공개 미리 보기  |
| | 내부자 위험 관리: 도메인 설정에 대한 지능적인 지원 | 사용 가능  |
| | 내부자 위험 관리: Microsoft Teams 통합  | 공개 미리 보기 |
| | 내부자 위험 관리: 기본 트리거(새 신호, 표시기 선택, 사용자 지정 및 활동 탐색기) | 사용 가능 |
| | 내부자 위험 관리: Office, Teams, SharePoint 메시지에 대한 표시기입니다.  | 사용 가능  |
| | 내부자 위험 관리: 정책 사용자 지정, 정책 상태 검사 및 향상된 정책 만들기 마법사 | 사용 가능 |
| | 내부자 위험 관리: 불만이 있는 사용자의 데이터 누출에 대한 정책 템플릿 | 공개 미리 보기  |
| | 내부자 위험 관리: 우선 순위 사용자에 의해 데이터 누출을 위한 정책 템플릿 | 공개 미리 보기 |
| | 내부자 위험 관리: 일반 보안 정책 위반에 대한 정책 템플릿 | 개발 중 |
| | 내부자 위험 관리: 우선 순위 사용자, 퇴사한 사용자, 불만이 있는 사용자에 대한 보안 정책 위반에 대한 정책 템플릿 | 개발 중 |
| | 내부자 위험 관리: Power Automate 통합 | 개발 중 |
| | 내부자 위험 관리: 우선 순위 사용자 그룹  | 공개 미리 보기  |
| | 내부자 위험 관리: 사용자를 떠날 경우 보안 정책 위반 | 개발 중 |
| | 내부자 위험 관리: 불만이 있는 사용자의 보안 정책 위반 | 개발 중 |
| | 내부자 위험 관리: 우선 순위 사용자에 대한 보안 정책 위반 | 개발 중 |
| | 내부자 위험 관리: 계정 삭제를 Azure Active Directory 기본 트리거 지원 | 사용 가능 |
| | 내부자 위험 관리: 사용자 활동 보고서 | 공개 미리 보기  |
| | 내부자 위험 관리: "감시자" 감사 내보내기 | 사용 가능 |
| **응답 & 검색**  | | |
| eDiscovery | 핵심 eDiscovery: 감사  | 사용 가능  |
| | 핵심 eDiscovery: 사례 관리 | 사용 가능 |
| | 핵심 eDiscovery: 비즈니스용 OneDrive | 사용 가능 |
| | Core eDiscovery: Export | 사용 가능 |
| | Core eDiscovery: In-place preservation | 사용 가능 |
| | Core eDiscovery: 기본 내보내기 | 사용 가능 |
| | Core eDiscovery: RMS 암호 해독 | 사용 가능 |
| | Core eDiscovery: 검색 | 사용 가능 |
| | 핵심 eDiscovery: Microsoft 준수 센터에서 지원이 확장되어 SharePoint 및 비즈니스용 OneDrive 수 있습니다. | 사용 가능 |
| | Advanced eDiscovery: 고급 처리 | 사용 가능 |
| | Advanced eDiscovery: 향상된 사례 제한 | 개발 중 |
| | Advanced eDiscovery: 암호화된 콘텐츠를 SharePoint 및/또는 비즈니스용 OneDrive | 사용 가능 |
| | Advanced eDiscovery: 대화 Teams 대화 모음 | 개발 중 |
| | Advanced eDiscovery: 커뮤니케이션 템플릿 및 발행 책임자 설정 | 개발 중 |
| | Advanced eDiscovery: Custodian에서 작업으로의 매핑 | 사용 가능 |
| | Advanced eDiscovery: Custodian communications | 사용 가능 |
| | Advanced eDiscovery: 대시보드 | 사용 가능 |
| | Advanced eDiscovery: Microsoft Teams | 개발 중 |
| | Advanced eDiscovery: 심층 크롤링/인덱싱 | 사용 가능 |
| | Advanced eDiscovery: 중국어, 일본어 및 한국어에 대한 더블 Byte 지원 | 사용 가능 |
| | Advanced eDiscovery: 전자 메일 스레딩 | 사용 가능 |
| | Advanced eDiscovery: 향상된 가져오기 마법사 환경 | 개발 중 |
| | Advanced eDiscovery: 내보내기(다운로드, 내보내기, 다른 검토 집합에 추가) | 사용 가능  |
| | Advanced eDiscovery: 필터링 | 사용 가능 |
| | Advanced eDiscovery: Graph API | 개발 중 |
| | Advanced eDiscovery: 이전 버전 | 개발 중 |
| | Advanced eDiscovery: 보류 최적화  | 개발 중  |
| | Advanced eDiscovery: Teams 원본으로 식별 | 백로그 엔지니어링 |
| | Advanced eDiscovery: Teams 채널 메시지에 대한 법적 보유 | 사용 가능 |
| | Advanced eDiscovery: Microsoft 규정 준수 센터는 지원이 확장되어 SharePoint, 비즈니스용 OneDrive, 핵심 및 서비스에서 항목을 검색하고 내보낼 Advanced eDiscovery | 개발 중 |
| | Advanced eDiscovery: 중복에 가까운 식별  | 사용 가능  |
| | Advanced eDiscovery: Core 및 Advanced eDiscovery | 개발 중 |
| | Advanced eDiscovery: 새로운 예측 코딩 모듈 및 처리 | 백로그 엔지니어링 |
| | Advanced eDiscovery: 비보조 데이터 원본 | 사용 가능 |
| | Advanced eDiscovery: 비영구 Office 365 | 사용 가능 |
| | Advanced eDiscovery: 예측 코딩  | 사용 가능 |
| | Advanced eDiscovery: 로드 파일로 내보내기 처리 | 사용 가능 |
| | Advanced eDiscovery: 재배포 | 사용 가능 |
| | Advanced eDiscovery: 검토 집합 | 사용 가능 |
| | Advanced eDiscovery: 데이터(쿼리 데이터, 스마트 태그, 대시보드) 및 주석 작성(재조정)  | 사용 가능  |
| | Advanced eDiscovery: 검색 용어 보고서 | 사용 가능 |
| | Advanced eDiscovery: 단일 항목 오류 수정 | 사용 가능 |
| | Advanced eDiscovery: PST 내보내기 지원 | 사용 가능 |
| | Advanced eDiscovery: OneDrive 및 SharePoint Online의 연결된 콘텐츠 지원(최신 첨부 파일) | 사용 가능 |
| | Advanced eDiscovery: 지원 Teams 반응 지원 | 개발 중 |
| | Advanced eDiscovery: 태그 지정 | 사용 가능 |
| | Advanced eDiscovery: 테넌트 보고서 | 사용 가능  |
| | Advanced eDiscovery: 테마  | 사용 가능  |
| | Advanced eDiscovery: 뷰어  | 사용 가능  |
| | Advanced eDiscovery: Yammer Advanced eDiscovery 준수 센터의 서비스  | 사용 가능  |
| 감사  | 기본 감사  | 사용 가능  |
| | 고급 감사: 중요한 이벤트에 대한 액세스(예: MailItemsAccessed) | 사용 가능  |
| | 고급 감사: 보존 대시보드 감사 | 사용 가능  |
| | 고급 감사: 검색 향상 감사 | 백로그 엔지니어링 |
| | 고급 감사: 관리 활동 API에 대한 대역폭 증가  | 사용 가능  |
| | 고급 감사: 개인 채널 Teams 법적 보유 | 사용 가능 |
| | 고급 감사: 로그 보존(1년)  | 사용 가능  |
| | 고급 감사: 감사 로그에 대한 장기 보존(10년)  | 배포 중  |
| | 고급 감사: 메일 전달 및 메일 보내기 이벤트  | 사용 가능  |
| | 고급 감사: Microsoft 365 및 준수 센터 | 사용 가능  |
| | 고급 감사: 온라인 및 Exchange Online SharePoint 검색 | 사용 가능 |
| **준수 관리** | | |
| 준수 관리  | Microsoft 365 규정 준수 센터  | 사용 가능  |
| | 규정 관리자  | 사용 가능  |
| | 준수 관리자: 지속적인 준수 평가  | 개발 중 |
| | 준수 관리자: 비영리 자산에 대한 첫 Microsoft 365 평가  | 사용 가능  |
| | 더블 Byte 문자 지원  | 사용 가능  |
| | Microsoft Cloud App Security  | 사용 가능  |
| **에코시스템** | | |
| 에코시스템  | 자체 데이터 커넥터: HR  | 사용 가능  |
| | 자체 데이터 커넥터: HR 1.2  | 사용 가능   |
| | 첫 번째 데이터 커넥터: 물리적 배지  | 사용 가능   |
| | Graph 대한 Advanced eDiscovery   | 개발 중  |
| | Graph 관리용 API(공개 미리 보기)  | 개발 중  |
| | Graph 내보내기용 Teams API  | 개발 중  |
 **개인 정보** | | |
| 개인 정보 관리  | Microsoft Priva  | 개발 중  |

<sup>1</sup> 프로젝트 계획 및 우선 순위가 다시 평가되면 식별된 상태는 변경될 수 있습니다.<br/>

**결정 지점**: 규정 준수 기능이 조직의 요구 *사항을 충족하는지 여부를 결정할 수 있습니다.*
