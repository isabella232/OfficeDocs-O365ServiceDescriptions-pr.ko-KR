---
title: Microsoft Purview 계획 - GCC 배포
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
description: 이 지침은 미국 연방, 주, 지방, 부족 또는 영토 정부 기관 또는 정부 규정 및 요구 사항의 적용을 받는 데이터를 처리하는 기타 법인에서 Office 365 배포를 유도하는 IT 전문가를 위한 것입니다. 여기서 Microsoft 365 정부 - GCC 이러한 요구 사항을 충족하는 데 적합합니다.
ms.openlocfilehash: 267c4b384cc210b3396d7681551392146e512f65
ms.sourcegitcommit: c2d2064d8fbebbe9843a4e824860e214b0b54c58
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/04/2022
ms.locfileid: "65187469"
---
# <a name="plan-for-microsoft-purview-compliance-and-risk-management-solutions--gcc-deployments"></a>Microsoft Purview 규정 준수 및 위험 관리 솔루션 계획 - GCC 배포

이 지침은 미국 연방, 주, 지방, 부족 또는 영토 정부 기관 또는 정부 규정 및 요구 사항의 적용을 받는 데이터를 처리하는 기타 법인에서 Office 365 배포를 유도하는 IT 전문가를 위한 것입니다. 여기서 Microsoft 365 정부 - GCC 이러한 요구 사항을 충족하는 데 적합합니다.

> [!NOTE]
> 조직이 이미 Microsoft 365 정부-GCC 자격 요구 사항을 충족하고 프로그램에 신청하고 수락한 경우 1단계와 2단계를 건너뛰고 3단계로 직접 이동하면 됩니다.

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---gcc-and-meets-eligibility-requirements"></a>1단계. 조직에 Microsoft 365 Government가 필요한지 여부 확인 - GCC 및 자격 요구 사항 충족

Microsoft 365 정부 - GCC 환경은 FedRAMP Moderate를 포함한 클라우드 서비스에 대한 미국 정부의 요구 사항과 형사 사법 및 연방 세금 정보 시스템(CJI 및 FTI 데이터 형식)에 대한 요구 사항을 준수합니다.

조직은 Office 365 기능과 기능을 즐기는 것 외에도 Microsoft 365 Government - GCC 고유한 다음과 같은 기능을 활용할 수 있습니다.

- 조직의 고객 콘텐츠는 Microsoft의 상업용 Office 365 서비스의 고객 콘텐츠와 논리적으로 분리됩니다.

- 조직의 고객 콘텐츠는 미국에 보관됩니다.

- 조직 고객 콘텐츠에 대한 액세스는 선별된 Microsoft 직원으로 제한됩니다.

- Microsoft 365 정부 - GCC 미국 공공 부문 고객에게 필요한 인증 및 인증을 준수합니다.

자격 요구 사항을 포함하여 Office 365 Government 계획에서 미국 정부 고객을위한 [Microsoft 365 정부 - GCC](https://products.office.com/government/compare-office-365-government-plans) 제공에 대한 자세한 정보를 찾을 수 있습니다.

[Office 365 미국 정부 서비스 설명](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md)은 미국 내 규정 준수 요구 사항을 충족하는 데 중점을 두는 플랫폼의 이점을 설명합니다.

> [!TIP]
> 서비스 설명의 정보 테이블을 Excel 통합 문서로 전송하고 조직 **Y/N과 관련이** 있고 **조직의 요구 사항을 충족하는** 두 개의 열을 추가할 수 있습니다. 그런 다음 동료와 함께 이 목록을 검토하여 이 서비스가 조직의 요구 사항을 충족하는지 확인할 수 있습니다.

> [!NOTE]
> Microsoft 365 Government - GCC 미국만 사용할 수 있습니다. 미국 정부 이외의 고객은 다양한 [Office 365 Government 플랜](https://products.office.com/government/compare-office-365-government-plans) 중에서 선택할 수 있습니다.

**의사 결정 사항**: <br/>
- *Microsoft 365 Government - GCC 조직에 적합한지 여부를 결정합니다.*
- *조직이 자격 요구 사항을 충족하는지 확인합니다.*

## <a name="step-2-apply-for-microsoft-365-government---gcc"></a>2단계. Microsoft 365 정부 신청 - GCC

이 서비스가 조직에 적합하다는 것을 결정한 후 [이 서비스에 적용하는](https://products.office.com/government/eligibility-validation) 프로세스를 시작합니다.

## <a name="step-3-understand-microsoft-365-government---gcc-default-security-settings"></a>3단계. Microsoft 365 Government 이해 - 기본 보안 설정 GCC

관리자 및 보안 설정을 수정하기 전에 신중하게 검토하고 기본 보안 설정을 변경하기 전에 규정 준수에 미치는 영향을 고려하는 것이 좋습니다.

**의사 결정 지점**: *기본 Microsoft 365 정부-GCC 보안 설정을 수정할지 여부를 결정하여 변경 내용의 영향을 먼저 파악합니다.*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gccsup1sup"></a>4단계. Microsoft 365 Government에서 현재 사용할 수 없거나 사용하지 않도록 설정된 기능 이해 - GCC <sup>1</sup>

정부 클라우드 고객의 요구 사항을 수용하기 위해 GCC 및 엔터프라이즈 계획과 Microsoft 365 정부 간에는 몇 가지 차이점이 있습니다. 사용 가능한 기능을 보려면 다음 표를 참조하세요. Microsoft 365 로드맵에 게시된 최신 규정 준수 제품 업데이트는 [여기](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent)를 참조하세요.<br><br>

| 영역 | 기능 | GCC 상태 |
| ---- | ------- | ---------- |
| **데이터 보호**  | | |
| 중요한 정보 유형  | 정확한 데이터 일치  | 사용 가능  |
| | 명명된 엔터티 중요한 정보 유형 및 정책 작성 템플릿 | 개발 중  |
| 민감도 레이블 지정  | 통합 레이블 지정 클라이언트 및 스캐너 | 사용 가능  |
| | SharePoint Online 문서 라이브러리에 업로드된 레이블이 지정되지 않은 파일에 "기본 레이블"을 적용합니다. | 개발 중 |
| | 문서를 편집할 수 있도록 기본 레이블 정책 적용 | 개발 중 |
| | Exchange Online, SharePoint Online 및 비즈니스용 OneDrive 대한 자동 분류 및 레이블 지정  | 사용 가능 |
| | 플랫폼(웹, Android, iOS, Windows 및 Mac)에서 Office 앱(Word, Excel, PowerPoint, Outlook)에 대한 자동 분류 및 레이블 지정 | 사용 가능  |
| | Office 클라이언트에 대한 자동 분류 및 레이블 지정(모바일) | 엔지니어링 백로그에서  |
| | Teams, Microsoft 365 그룹 및 SharePoint 사이트에 대한 자동 분류 및 레이블 지정  | 사용 가능  |
| | 자동 레이블 지정 정책은 수동 레이블 덮어쓰기 및 모든 조직에서 받은 메일 암호화를 지원합니다. | 사용 가능  |
| | Microsoft Information Protection 암호화 문서에 대한 공동 작성| 사용 가능  |
| | SharePoint Online 및 비즈니스용 OneDrive 자동 레이블 지정에 대한 향상된 시뮬레이션 및 위치 지원 | 사용 가능 |
| | Microsoft Azure Purview를 사용하여 기본 제공 민감도 레이블을 Azure의 자산으로 확장 | 개발 중  |
| | SharePoint Online 사이트에 대한 "민감도 레이블"을 통한 세분화된 조건부 액세스 정책 | 엔지니어링 백로그에서  |
| | 필수 레이블  | 사용 가능  |
| | 수동 레이블  | 사용 가능  |
| | Exchange Online 자동 레이블 지정에 대한 새로운 조건| 개발 중 |
| 분석  | 데이터 분류 분석: 개요 및 콘텐츠 탐색기 | 사용 가능 |
| | Office 앱의 감사 및 분석 | 사용 가능 |
| | 활동 탐색기에는 Power BI 민감도 레이블 데이터가 포함됩니다. | 사용 가능 |
| | 활동 탐색기 기본 제공 필터 | 사용 가능 |
| | 활동 탐색기 사용자 환경 개선 사항 | 사용 가능 |
| | 민감도 레이블 데이터를 Power BI 활동 탐색기 | 사용 가능 |
| | 활동 탐색기 보안 판독기 역할이 업데이트됨 | 사용 가능 |
| | 콘텐츠 탐색기에는 Teams 데이터가 포함됩니다. | 개발 중 |
| | Office 앱/클라이언트 쪽에서 자동 레이블 지정이 있는 기계 학습 분류자  | 사용 가능 |
| 암호화  | Microsoft Purview 메시지 암호화(E3) | 사용 가능 |
| | Microsoft Purview E5(Advanced Message Encryption) | 사용 가능 |
| | 고급 메시지 암호화: 전자 메일 해지 확장 | 사용 가능 |
| | Microsoft Purview 고객 키 | 사용 가능 |
| | 고객 키: Microsoft 365 대한 미사용 데이터 암호화 | 사용 가능 |
| | 고객 키: SharePoint Online 및 비즈니스용 OneDrive | 사용 가능 |
| | 고객 관리형 키 프로비전 수명 주기를 위한 BYOK(Bring Your Own Key) | 사용 가능 |
| | Microsoft Purview 이중 키 암호화 | 사용 가능 |
| | Microsoft 관리형 키를 사용하여 서비스 암호화 Exchange Online | 사용 가능 |
| 데이터 손실 방지 | 경고 대시보드 및 경고 환경 | 사용 가능 |
|  | 활동 탐색기에 표시된 데이터 | 사용 가능 |
|  | 끝점 데이터 손실 방지 | 사용 가능 |
|  | 파일(SPO/ODB) 및 전자 메일 | 사용 가능 |
|  | Microsoft Defender for Cloud Apps(이전 Microsoft Cloud App Security) 통합 | 사용 가능 |
|  | 온-프레미스 스캐너 | 사용 가능 |
|  | 솔루션 개요 페이지 | 사용 가능 |
|  | 채팅 및 채널 대화 Teams  | 사용 가능 |
| **데이터 수명 주기 관리 & 레코드 관리** |  |  |
| 데이터 수명 주기 관리(이전의 정보 거버넌스) | 보존 및 레이블 지정 정책에 대한 적응형 범위 | 사용 가능 |
| | 보존 기간 종료 시 보존 레이블 작업 적용  | 개발 중 |
| | SharePoint, 비즈니스용 OneDrive 라이브러리, 폴더 및 문서 집합에 대한 기본 보존 레이블을 적용합니다. 받은 편지함 및 Office 365 그룹 Exchange | 사용 가능 |
| | 레코드에 대한 메타데이터를 편집하는 기능을 차단하는 옵션 구성 | 개발 중 |
| | 레코드 잠금 해제 사용 안 함 | 개발 중 |
| | 전자 메일 보관 | 사용 가능 |
| | PST 가져오기 | 사용 가능 |
| | 수동 비 레코드 보존 레이블 | 사용 가능 |
| | 보존 잠금 | 사용 가능 |
| | SharePoint Online 및 비즈니스용 OneDrive 대한 보존 개선 사항 | 사용 가능 |
| | SharePoint 보존 레이블 삭제 동작 변경 | 사용 가능 |
| | 전체 조직에 대한 보존 정책; 특정 위치 또는 사용자; 는 특정 조건(예: 키워드 또는 중요한 정보)에 따라 자동으로 및 이벤트 기반 | 사용 가능 |
| | Teams 보존 정책(채팅) | 사용 가능 |
| | Teams 모임 녹음/녹화에 대한 보존 정책 | 사용 가능 |
| | Teams 프라이빗 채널에 대한 보존 정책 | 사용 가능 |
| 레코드 관리 | 레코드 레이블을 삭제하는 기능 | 사용 가능 |
| | 수동 레코드 선언에 대해 레코드 레이블이 "잠금 해제됨"으로 시작되도록 허용 | 개발 중 |
| | 레코드 레이블을 수동으로 적용 | 사용 가능 |
| | SharePoint, 비즈니스용 OneDrive 라이브러리, 폴더 및 문서 집합 및 Office 365 그룹에 대한 기본 레코드 레이블 적용 | 사용 가능 |
| | 특정 조건(예: 키워드 또는 중요한 정보)에 따라 레코드 정책을 자동으로 적용합니다. 및 이벤트 기반 | 사용 가능 |
| | 학습 가능한 분류자를 사용하여 레코드 정책 자동 적용  | 개발 중 |
| | 레코드 잠금 해제 사용 안 함 | 사용 가능 |
| | 처리 검토 | 사용 가능 |
| | 파일 플랜 관리자 | 사용 가능 |
| | 다단계 처리 검토 | 배포 중 |
| | 레코드 관리에 대한 Outlook 클라이언트 지원 | 사용 가능 |
| | 파워 자동화 통합 | 엔지니어링 백로그에서 |
| | 폐기 증명 | 사용 가능 |
| | 레코드 버전 관리 | 사용 가능 |
| | 규정 레코드 | 사용 가능 |
| **리스크 관리**  | | |
| 고객 Lockbox | 고객 Lockbox | 사용 가능 |
| 커뮤니케이션 규정 준수 | 통신 준수 정책에 대한 보존 기간을 설정하는 기능 | 엔지니어링 백로그에서 |
| | 액세스 경고; 알림 템플릿; 통신 정책 대시보드 | 사용 가능 |
| | 온-프레미스 사서함을 사용하여 사용자의 Teams 채팅 데이터 분석 | 사용 가능 |
| | 사용자가 의 구성원인 Teams 자동으로 모니터링 | 사용 가능 |
| | 이해 상충 템플릿 | 사용 가능 |
| | 고객 정책 만들기, 미리 구성된 3개 | 사용 가능 |
| | 데이터 손실 방지 정책 권장 사항 | 사용 가능 |
| | 일 제로 인사이트 | 엔지니어링 백로그에서 |
| | 성인 콘텐츠 검색 | 사용 가능 |
| | 고객 불만 검색  | 개발 중 |
| | 시간에 따른 반복 행동 강령 위반 감지 | 사용 가능 |
| | 차별 분류자 | 사용 가능 |
| | eDiscovery에 대한 조사를 위해 에스컬레이션(Premium) | 사용 가능 |
| | Exchange 및 Teams 지원 | 사용 가능 |
| | 필기 및 인쇄 텍스트를 지원하도록 확장된 광학 문자 인식 | 개발 중 |
| | 메시지 세부 정보 보고서 | 엔지니어링 백로그에서 |
| | 최신 첨부 파일: SharePoint Online 및 비즈니스용 OneDrive 연결된 콘텐츠 분석 | 개발 중 |
| | 정책 상태 검사 및 정책 일시 중지 기능 | 개발 중 |
| | 파워 자동화 통합 | 공개 미리 보기 |
| | Teams 채팅 또는 채널에서 Teams 메시지 제거 | 사용 가능 |
| | 위치 보고서당 중요한 정보 유형  | 개발 중 |
| | 보다 세분화된 권한에 대한 지원 | 사용 가능 |
| | 위협, 대상 괴롭힘 및 욕설 분류자를 위한 7개 언어를 지원합니다. | 사용 가능 |
| | Teams, Exchange 및 Teams 메시지 제거 기능 지원 | 사용 가능 |
| | 태그 지정 개선 사항 | 사용 가능 |
| | Teams 대화 컨텍스트 | 사용 가능 |
| | 조사 중 콘텐츠 번역 | 사용 가능 |
| 정보 장벽 | 정보 장벽 | 사용 가능 |
| | 관리자 환경: 세그먼트 및 정책 방문 페이지 | 배포 중 |
| 내부자 위험 관리 | 경고를 내보내는 기능 | 사용 가능 |
| | 활동 탐색기 데이터가 표시됩니다. | 사용 가능 |
| | 분석 | 공개 미리 보기 |
| | 케이스 대시보드 | 사용 가능 |
| | 콘텐츠 탐색기 향상된 기능 | 사용 가능 |
| | 불만을 품은 사용자의 데이터 유출 | 개발 중 |
| | 퇴사하는 직원의 데이터 도난 | 사용 가능 |
| | 우선순위 사용자의 데이터 유출 | 공개 미리 보기 |
| | 도메인에 대한 향상된 지원 | 개발 중 |
| | eDiscovery에 대한 조사를 위해 에스컬레이션(Premium) | 사용 가능 |
| | 향상된 경고 내보내기 | 개발 중 |
| | 일반적인 데이터 유출 | 사용 가능 |
| | 일반 보안 정책 위반 | 개발 중 |
| | 자사 지표 집합 증가 | 개발 중 |
| | 보안 정책 위반에 대한 지표 | 개발 중 |
| | 엔드포인트용 Microsoft Defender 경고에 대한 지표 | 개발 중 |
| | Office(Teams, SharePoint 사이트, 전자 메일 메시징)에 대한 지표 | 사용 가능  |
| | Windows 10 엔드포인트 활동에 대한 지표 | 사용 가능 |
| | 도메인 설정에 대한 지능형 지원 | 사용 가능 |
| | 경고 엔드포인트용 Microsoft Defender | 개발 중 |
| | Microsoft Teams 통합 | 공개 미리 보기 |
| | 네이티브 트리거(새 신호, 표시기 선택, 사용자 지정 및 활동 탐색기) | 배포 중 |
| | Teams, SharePoint 사이트, 전자 메일 메시징에 대한 Office 표시기 | 사용 가능 |
| | 정책 사용자 지정, 정책 상태 검사 및 향상된 정책 만들기 마법사 | 사용 가능 |
| | 불만을 품은 사용자의 데이터 유출에 대한 정책 템플릿 | 공개 미리 보기 |
| | 우선 순위 사용자에 의한 데이터 유출에 대한 정책 템플릿 | 공개 미리 보기 |
| | 일반 보안 정책 위반에 대한 정책 템플릿 | 개발 중 |
| | 우선 순위 사용자, 출발 사용자, 불만을 품은 사용자에 의한 보안 정책 위반에 대한 정책 템플릿 | 개발 중 |
| | 파워 자동화 통합 | 공개 미리 보기 |
| | 우선 순위 사용자 그룹 | 공개 미리 보기 |
| | 디바이스 표시기 인식 | 공개 미리 보기 |
| | 퇴사하는 사용자의 보안 정책 위반 | 개발 중 |
| | 불만을 품은 사용자의 보안 정책 위반 | 개발 중 |
| | 우선순위 사용자의 보안 정책 위반 | 개발 중 |
| | Power Automate 대한 ServiceNow 템플릿 | 공개 미리 보기 |
| | Azure Active Directory 계정 삭제에 대한 네이티브 트리거 지원 | 사용 가능 |
| | 심사 및 조사 개선 사항 | 개발 중 |
| | 사용자 활동 보고서 | 공개 미리 보기 |
| | "감시자 보기" 감사 내역 | 사용 가능 |
| eDiscovery(표준) | 감사 | 사용 가능 |
| | 사례 관리 | 사용 가능 |
| | 비즈니스용 OneDrive 규정 준수 경계 | 사용 가능 |
| | 내보내기 | 사용 가능 |
| | 현재 위치 보존 | 사용 가능 |
| | 네이티브 내보내기 | 사용 가능 |
| | RMS 암호 해독 | 사용 가능 |
| | 검색 | 사용 가능 |
| | Microsoft 규정 준수 센터는 SharePoint 및 비즈니스용 OneDrive 휴지통에서 항목을 검색하고 내보내기 위한 지원을 확장했습니다. | 사용 가능 |
| eDiscovery(프리미엄) | 고급 처리 | 사용 가능 |
| | 사례 제한 향상 | 개발 중 |
| | SharePoint 및/또는 비즈니스용 OneDrive 암호화된 콘텐츠 수집 및 검토 | 사용 가능 |
| | 대본으로 Teams 대화의 컬렉션 | 개발 중 |
| | 통신 템플릿 및 발급 책임자 설정 | 배포 중 |
| | 워크로드 매핑에 대한 보유자 | 사용 가능 |
| | 보유자 통신 | 사용 가능 |
| | 대시보드 | 사용 가능 |
| | Microsoft Teams 대한 데이터 제거 기능  | 개발 중 |
| | 심층 크롤링/인덱싱 | 사용 가능 |
| | 더블 바이트 문자 지원(중국어, 일본어, 한국어) | 사용 가능 |
| | 전자 메일 스레딩 | 사용 가능 |
| | 향상된 가져오기 보유자 마법사 환경 | 배포 중 |
| | 내보내기(다운로드, 내보내기, 다른 보기 집합에 추가) | 사용 가능 |
| | 필터링 | 사용 가능 |
| | 기록 버전 | 개발 중 |
| | 유지 최적화 | 개발 중 |
| | 보고서 보관 | 개발 중 |
| | 데이터 원본으로 Teams 식별 | 개발 중 |
| | Teams 비공개 채널 메시지에 대한 법적 보존 | 사용 가능 |
| | Microsoft Purview 준수 포털은 SharePoint 및 비즈니스용 OneDrive 휴지통에서 항목을 검색하고 내보내기 위한 지원을 확장했습니다. | 개발 중 |
| | 거의 중복 식별 | 사용 가능 |
| | 새 예측 코딩 모듈 | 엔지니어링 백로그에서 |
| | 비보관 데이터 원본 | 사용 가능 |
| | 비 Office 365 수집 | 사용 가능 |
| | 예측 코딩 | 사용 가능 |
| | 로드 파일을 사용하여 처리된 내보내기 | 사용 가능 |
| | 수정 | 사용 가능 |
| | 검토 집합 | 사용 가능 |
| | 데이터 검토(쿼리 데이터, 스마트 태그, 대시보드) 및 주석 달기(수정) | 사용 가능 |
| | 검색 용어 보고서 | 사용 가능 |
| | 단일 항목 오류 수정 | 사용 가능 |
| | PST 내보내기 지원 | 사용 가능 |
| | OneDrive 및 SharePoint Online에서 연결된 콘텐츠 지원(최신 첨부 파일) | 사용 가능 |
| | Teams 반응 지원 | 개발 중 |
| | 태깅 | 사용 가능 |
| | 테넌트 보고서 | 사용 가능 |
| | 테마 | 사용 가능 |
| | 보기 권한자 | 사용 가능 |
| 감사(표준) | 감사(표준)| 사용 가능 |
| 감사(프리미엄) | 중요한 이벤트에 대한 액세스(예: MailItemsAccessed) | 사용 가능 |
| | 감사 보존 대시보드 | 사용 가능 |
| | 감사 검색 기능 향상 | 엔지니어링 백로그에서 |
| | 관리 작업 API에 대한 대역폭 증가 | 사용 가능 |
| | Teams 비공개 채널 메시지에 대한 법적 보존 | 사용 가능 |
| | 로그 보존(1년) | 사용 가능 |
| | 감사 로그에 대한 장기 보존(10년) | 사용 가능 |
| | 메일 전달 및 메일 보내기 이벤트 | 사용 가능 |
| | Microsoft 365 보안 및 규정 준수 센터 | 사용 가능 |
| | Exchange Online 및 SharePoint Online에서 용어 이벤트 검색 | 사용 가능 |
| **규정 준수 상태** |  |  |
| 준수 관리 | Microsoft Purview 규정 준수 포털 | 사용 가능 |
| | Microsoft Purview 준수 관리자 | 사용 가능 |
| | 준수 관리자: 경고 및 알림 | 개발 중 |
| | 준수 관리자: 지속적인 규정 준수 평가 | 배포 중 |
| | 규정 준수 관리자: Microsoft 365 아닌 자산에 대한 기본 평가 | 사용 가능 |
| | 준수 관리자: 대량 평가 만들기에 권장되는 엔진 | 개발 중 |
| | 더블 바이트 문자 지원 | 사용 가능 |
| | Microsoft Defender for Cloud Apps | 사용 가능 |
| **생태계** |  |  |
| 데이터 커넥터 | 자사 데이터 커넥터: HR  | 사용 가능 |
| | 자사 데이터 커넥터: HR 1.2 | 개발 중 |
| | 자사 데이터 커넥터: 물리적 불량 | 사용 가능 |
| | eDiscovery용 Graph API(Premium) | 개발 중 |
| | 레코드 관리를 위한 Graph API | 개발 중 |
| | Teams 내보내기 데이터를 위한 API Graph | 개발 중 |
| | 타사 데이터 커넥터(17a-4 및 CellTrust Connectors) | 사용 가능 |
| | 타사 데이터 커넥터(Telemessage) | 사용 가능 |
| | 타사 데이터 커넥터(Veritas) | 개발 중 |
 **개인 정보** | | |
| 개인 정보 관리 | Microsoft Priva 개인 정보 보호 위험 관리 | 개발 중 |
| | Microsoft Priva 주체 권한 요청 | 개발 중 |

<sup>1</sup> 식별된 상태는 프로젝트 계획 및 우선 순위가 다시 평가됨에 따라 변경될 수 있습니다.<br/>

**의사 결정 지점**: *규정 준수 기능이 조직의 요구 사항을 충족하는지 여부를 결정합니다.*
