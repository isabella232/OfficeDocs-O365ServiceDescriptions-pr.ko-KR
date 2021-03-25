---
title: Microsoft 365 규정 준수 - GCC 계획
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 이 지침은 Microsoft 365 Government - GCC를 사용하는 것이 이러한 요구 사항을 충족하는 데 적합한 미국 연방, 주, 지방, 부족 또는 영토적 정부 기관 또는 정부 규정 및 요구 사항을 준수하는 데이터를 처리하는 기타 엔터티에서 Office 365 배포를 진행하는 IT 프로를 위한 것입니다.
ms.openlocfilehash: 702ed14de312588aee1cad6094683fcada2333bc
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173513"
---
# <a name="plan-for-microsoft-365-compliance--gcc"></a>Microsoft 365 규정 준수 계획 - GCC

이 지침은 Microsoft 365 Government - GCC를 사용하는 것이 이러한 요구 사항을 충족하는 데 적합한 미국 연방, 주, 지방, 부족 또는 영토적 정부 기관 또는 정부 규정 및 요구 사항을 준수하는 데이터를 처리하는 기타 엔터티에서 Office 365 배포를 진행하는 IT 프로를 위한 것입니다.

> [!NOTE]
> 조직이 이미 Microsoft 365 Government - GCC 자격 요구 사항을 충족하고 프로그램에 적용되고 프로그램에 수락된 경우 1단계와 2단계를 건너뛰고 3단계로 바로 이동하면 됩니다.

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---gcc-and-meets-eligibility-requirements"></a>1단계. 조직에 Microsoft 365 Government - GCC가 필요한지 여부 및 자격 요구 사항을 충족하는지 확인

Microsoft 365 Government - GCC 환경은 FedRAMP Moderate을 비롯한 클라우드 서비스에 대한 미국 정부 요구 사항 및 범죄 사법 및 연방 세금 정보 시스템(CJI 및 FTI 데이터 형식)에 대한 요구 사항을 준수합니다.

조직은 Office 365의 기능과 기능을 즐길 뿐만 아니라 Microsoft 365 Government - GCC에 고유한 다음과 같은 기능을 사용할 수 있습니다.

- 조직의 고객 콘텐츠는 Microsoft에서 상용 Office 365 서비스의 고객 콘텐츠와 논리적으로 은(는) 분판됩니다.

- 조직의 고객 콘텐츠는 미국에 보관됩니다.

- 조직 고객 콘텐츠에 대한 액세스는 선별된 Microsoft 직원으로 제한됩니다.

- Microsoft 365 Government - GCC는 미국 공공 부문 고객에게 필요한 인증 및 인증을 준수합니다.

자격 요구 사항을 포함하여 [Office 365 Government](https://products.office.com/government/compare-office-365-government-plans)요금제에서 미국 정부 고객을 위한 Microsoft 365 Government - GCC 제공에 대한 자세한 정보를 찾을 수 있습니다.

[Office 365 Government](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md) 서비스 설명에서는 미국 내 규정 준수 요구 사항을 충족하는 데 중심을 두는 플랫폼의 이점에 대해 설명합니다.

> [!TIP]
> 서비스 설명의 정보 표를 Excel 통합 문서로 전송하고 조직의 **Y/N** 및 조직의 요구 사항 충족의 두 열을 추가할 수 **있습니다.** 그런 다음 이 목록을 동료와 검토하여 이 서비스가 조직의 요구 사항을 충족하는지 확인할 수 있습니다.

> [!NOTE]
> Microsoft 365 Government - GCC는 미국에서만 사용할 수 있습니다. 미국 정부 이 아닌 고객은 다양한 [Office 365 Government 요금제에서](https://products.office.com/government/compare-office-365-government-plans)선택할 수 있습니다.

**결정 사항**: <br/>
- *Microsoft 365 Government - GCC가 조직에 적합한지 여부를 결정하십시오.*
- *조직이 자격 요구 사항을 충족하는지 확인합니다.*

## <a name="step-2-apply-for-microsoft-365-government---gcc"></a>2단계. Microsoft 365 Government 신청 - GCC

이 서비스가 조직에 적합한 것으로 결정한 후 이 서비스에 적용하는 [프로세스를 시작하십시오.](https://products.office.com/government/eligibility-validation)

## <a name="step-3-understand-microsoft-365-government---gcc-default-security-settings"></a>3단계. Microsoft 365 Government - GCC 기본 보안 설정 이해

관리자 및 보안 설정을 수정하기 전에 신중하게 검토하고 기본 보안 설정을 변경하기 전에 규정 준수에 미치는 영향을 고려하는 것이 좋습니다.

**의사** 결정 지점: *기본 Microsoft 365 Government - GCC* 보안 설정을 수정할지 여부를 결정하여 변경 내용이 미치는 영향을 먼저 파악합니다.

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gccsup1sup"></a>4단계. Microsoft 365 Government - GCC<sup>1에서</sup> 현재 사용할 수 없거나 사용하지 않도록 설정되어 있는 기능 이해

정부 클라우드 고객의 요구 사항을 수용하기 위해 Microsoft 365 Government - GCC 및 엔터프라이즈 계획 간에는 몇 가지 차이점이 있습니다. 다음 표를 참조하여 사용 가능한 기능을 참조합니다. Microsoft [](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) 365 로드맵에 게시된 최신 규정 준수 제품 업데이트는 여기를 참조하세요.<br><br>

| 영역 | 기능 | GCC 상태 |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **정보 보호**              | 통합 레이블 클라이언트 및 스캐너         | 사용할 수 있음              |
|                                         | 정확한 데이터 일치          | 사용할 수 있음              |
|                                         | Exchange Online, SharePoint Online 및 OneDrive에 대한 자동 분류 및 레이블 지정                      | 배포 중              |
|                                         | 플랫폼(웹, Android, iOS, Windows 및 Mac)에서 Office 앱(Word, Excel, PowerPoint, Outlook)에 대한 자동 분류 및 레이블 지정 |  개발 중              |
|                                         | Office 클라이언트에 대한 자동 분류 및 레이블 지정(모바일)                                       | 백로그 엔지니어링              |
|                                         | Teams에 대한 자동 분류 및 레이블 지정                            | 백로그 엔지니어링 |
|                                         | 데이터 분류 분석: 개요 및 콘텐츠 탐색기                            | 백로그 엔지니어링 |
|                                         | 분석: 서비스 쪽에서 자동 레이블을 지정하는 기계 학습 분류자                           | 백로그 엔지니어링  |
|                                         | 분석: Office 앱/클라이언트 쪽에서 자동 레이블 지정을 사용하는 기계 학습 분류자                           | 백로그 엔지니어링  |
|                                         | 기본 Office 365 메시지 암호화(E3)                            | 사용할 수 있음              |
|                                         | 고급 Office 365 메시지 암호화(E5)  | 사용할 수 있음              |
|                                         | Office 365에 대한 고객 키    | 사용할 수 있음 |
|                                         | 고객 관리 키 프로비전 수명 주기를 위해 BYOK(Bring Your Own Key)를 가져오기                            | 사용할 수 있음 |
|                                         | 높은 규제 시나리오(미리 보기)에 대한 Azure INFORMATION Protection 및 AD(Active Directory) 권한 관리에 걸쳐 있는 HYOK(사용자 소유 키)를 보유합니다.                         | 사용할 수 있음 |
|                                         | 이중 키 암호화                           | 사용할 수 있음 |
|                                         | 암호화: WXP 웹앱을 사용하여 암호화된 문서에 대한 공동 작성                           | 백로그 엔지니어링 |
|                                         | 파일 및 전자 메일에 대한 DLP(데이터 손실 방지)         | 사용할 수 있음 |
|                                         | Teams 채팅 및 채널 대화용 DLP         | 개발 중 |
|                                         | DLP 끝점 | 백로그 엔지니어링 |
| **정보 거버넌스** | 정보 거버넌스: 전자 메일 보관                                       | 사용할 수 있음              |
|                                         | 정보 거버넌스: 보존 잠금          | 사용할 수 있음              |
|                                         | 정보 거버넌스: PST 가져오기                      | 사용할 수 있음              |
|                                         | 정보 거버넌스: 수동 비기록 보존 레이블            | 사용할 수 있음 |
|                                         | 정보 거버넌스: SharePoint, 비즈니스용 OneDrive 라이브러리, 폴더 및 문서 집합에 대한 기본 보존 레이블 Exchange 받은 편지함 및 Office 365 그룹 | 사용할 수 있음              |
|                                         | 정보 거버넌스: 전체 조직에 대한 보존 정책 특정 위치 또는 사용자 특정 조건에 따라 자동으로(예: 키워드 또는 중요한 정보) 및 이벤트 기반                                       | 사용할 수 있음              |
|                                         | 정보 거버넌스: Teams의 보존 정책                            | 사용할 수 있음 |
|                                         | 정보 거버넌스: SharePoint Syntex 분류를 사용하는 보존 레이블                            | 백로그 엔지니어링 |
|                                         | 정보 거버넌스: 교육 가능한 분류자 보유 정책                            | 백로그 엔지니어링 |
|                                         | 정보 거버넌스: Teams 모임 녹음/녹화에 대한 보존 정책                            | 백로그 엔지니어링 |
|                                         | 정보 거버넌스: 관리에 대한 Yammer                            | 백로그 엔지니어링 |
|                                         | 레코드 관리: 레코드 레이블에 대한 수동 분류                           | 사용할 수 있음              |
|                                         | 레코드 관리: SharePoint, 비즈니스용 OneDrive 라이브러리, 폴더 및 문서 집합에 대한 기본 레코드 레이블 및 Office 365 그룹                              | 사용할 수 있음              |
|                                         | 레코드 관리: 특정 조건(예: 키워드 또는 중요한 정보)에 기반한 자동 레코드 정책 및 이벤트 기반                            | 사용할 수 있음              |
|                                         | 레코드 관리: 파기 검토  | 사용할 수 있음              |
|                                         | 레코드 관리: 파일 계획 관리자    | 사용할 수 있음 |
|                                         | 레코드 관리: 폐기 증명                            | 사용할 수 있음 |
|                                         | 레코드 관리: 레코드 버전 관리                            | 사용할 수 있음 |
|                                         | 레코드 관리: 규정 레코드(공개 미리 보기)                         | 개발 중 |
|                                         | 레코드 관리: 다단계 분해 검토 | 백로그 엔지니어링 |
|                                         | 레코드 관리: SharePoint Syntex 분류를 사용하여 레코드 레이블 적용 | 백로그 엔지니어링 |
| **내부 위험 관리**             | 고객 Lockbox                                | 사용할 수 있음            |
|                                         | 내부자 위험 관리: Teams, SharePoint 사이트, 전자 메일 메시징에 대한 Office 표시기                         | 개발 중 |
|                                         | 내부자 위험 관리: 떠날 사용자의 데이터 도용                        | 개발 중 |
|                                         | 내부자 위험 관리: 일반 데이터 누수                                | 개발 중              |
|                                         | 내부자 위험 관리: 내부자 위험 관리 경고 조사                                   | 개발 중              |
|                                         | 내부자 위험 관리: 사례 대시보드, 콘텐츠 탐색기 및 알림 서식 파일 | 개발 중 |
|                                         | 내부자 위험 관리: Advanced eDiscovery에 대한 조사 에스컬레이터 | 개발 중|
|                                         | 내부자 위험 관리: Windows 10 빌드 1809 이상에서의 활동에 대한 장치 표시기 | 백로그 엔지니어링|
|                                         | 내부자 위험 관리: 보안 정책 위반 표시기(미리 보기) | 백로그 엔지니어링|
|                                         | 내부자 위험 관리: 끝점 경고에 대한 Microsoft Defender 표시기(미리 보기) | 백로그 엔지니어링|
|                                         | 내부자 위험 관리: 우선 순위 사용자에 의해 데이터 누출을 위한 정책 템플릿(미리 보기) | 백로그 엔지니어링 |
|                                         | 내부자 위험 관리: 불만이 있는 사용자에 의해 데이터 누출을 위한 정책 템플릿(미리 보기) | 백로그 엔지니어링 |
|                                         | 내부자 위험 관리: 일반 보안 정책 위반에 대한 정책 템플릿(미리 보기) | 백로그 엔지니어링 |
|                                         | 내부자 위험 관리: 우선 순위 사용자, 퇴사한 사용자, 불만이 있는 사용자(미리 보기)의 보안 정책 위반에 대한 정책 템플릿 | 백로그 엔지니어링 |
|                                         | 내부자 위험 관리: 정책 사용자 지정(미리 보기) | 백로그 엔지니어링 |
|                                         | 내부자 위험 관리: 경고 내보내기(미리 보기) | 백로그 엔지니어링 |
|                                         | 내부자 위험 관리: 우선 순위 사용자 그룹(미리 보기) | 백로그 엔지니어링 |
|                                         | 커뮤니케이션 규정 준수(감독 정책 포함): 고객 정책 만들기, 미리 구성된 3  | 배포 중 |
|                                         | 커뮤니케이션 규정 준수(감독 정책 포함): Teams 지원, Exchange 및 Teams 메시지 제거 | 배포 중 |
|                                         | 커뮤니케이션 규정 준수(감독 정책 포함): 경고 액세스 알림 서식 파일 통신 정책 대시보드 | 배포 중  |
|                                         | 커뮤니케이션 규정 준수(감독 정책 포함): Advanced eDiscovery에 대한 조사를 위해 에스컬레이터 | 배포 중 |
|                                         | 커뮤니케이션 규정 준수(감독 정책 포함): 성인용 콘텐츠 검색 | 배포 중 |
|                                         | 통신 규정 준수: 시간의에 따라 반복되는 행동 위반 감지 | 배포 중 |
|                                         | 커뮤니케이션 규정 준수: 보다 세부적인 사용 권한 지원 | 배포 중 |
|                                         | 커뮤니케이션 규정 준수: 프레미스 사서함을 사용하여 사용자의 Teams 채팅 데이터 분석 | 배포 중 |
|                                         | 통신 규정 준수: 이해 상충 템플릿 | 백로그 엔지니어링 |
|                                         | 통신 준수: 전자 메일 서명 또는 고지 사항 무시 | 백로그 엔지니어링 |
|                                         | 커뮤니케이션 규정 준수: 내부자 위험 관리 전달 | 백로그 엔지니어링 |
|                                         | 통신 준수: 정책 상태 검사 및 정책 일시 중지 능력 | 백로그 엔지니어링 |
|                                         | 커뮤니케이션 규정 준수: 조사 중에 상태 콘텐츠 번역 | 백로그 엔지니어링 |
|                                         | 커뮤니케이션 규정 준수: 번아웃 및 자살 감지 | 백로그 엔지니어링 |
|                                         | 정보 장벽 | 백로그 엔지니어링 |
|                                         | 권한이 부여된 액세스 관리                    | 백로그 엔지니어링 |
| **응답 & 검색**                  | Core eDiscovery: In-place preservation                            | 사용할 수 있음              |
|                                         | 핵심 eDiscovery: 감사                                 | 사용할 수 있음              |
|                                         | 핵심 eDiscovery: 사례 관리                                 | 사용할 수 있음              |
|                                         | Core eDiscovery: Export                                          | 사용할 수 있음              |
|                                         | Core eDiscovery: 기본 내보내기                                  | 사용할 수 있음              |
|                                         | Core eDiscovery: RMS 암호 해독                                   | 사용할 수 있음              |
|                                         | 핵심 eDiscovery: Microsoft 규정 준수 센터에서 SharePoint 및 비즈니스용 OneDrive의 항목 검색 및 내보내기 지원을 확장                                        | 개발 중              |
|                                         | Advanced eDiscovery: Advanced processing                             | 사용할 수 있음 |
|                                         | Advanced eDiscovery: Dashboard                                 | 사용할 수 있음 |
|                                         | Advanced eDiscovery: 전자 메일 스레딩                   | 사용할 수 있음 |
|                                         | Advanced eDiscovery: 내보내기(다운로드, 내보내기, 다른 보기 집합에 추가)                                          | 사용할 수 있음 |
|                                         | Advanced eDiscovery: 필터링                               | 사용할 수 있음 |
|                                         | Advanced eDiscovery: Teams 비공개 채널 메시지에 대한 법적 보유                 | 사용할 수 있음 |
|                                         | Advanced eDiscovery: 거의 중복 식별                                         | 사용할 수 있음 |
|                                         | Advanced eDiscovery: 비보조 데이터 원본                                         | 사용할 수 있음 |
|                                         | Advanced eDiscovery: 비 Office 365 Ingestion                                      | 사용할 수 있음 |
|                                         | Advanced eDiscovery: 예측 코딩                                       | 사용할 수 있음 |
|                                         | Advanced eDiscovery: 로드 파일로 내보내기 처리                   | 사용할 수 있음 |
|                                         | Advanced eDiscovery: Redactions                        | 사용할 수 있음 |
|                                         | 고급 eDiscovery: 검토 집합                                     | 사용할 수 있음 |
|                                         | Advanced eDiscovery: 데이터(쿼리 데이터, 스마트 태그, 대시보드)를 검토하고 주석을 작성(변경)                             | 사용할 수 있음 |
|                                         | 고급 eDiscovery: 검색 용어 보고서                        | 사용할 수 있음 |
|                                         | Advanced eDiscovery: 단일 항목 오류 수정                              | 사용할 수 있음 |
|                                         | Advanced eDiscovery: Support PST Export                              | 사용할 수 있음 |
|                                         | Advanced eDiscovery: OneDrive 및 SharePoint Online의 연결된 콘텐츠 지원(최신 첨부 파일)                              | 사용할 수 있음 |
|                                         | Advanced eDiscovery: Tagging                              | 사용할 수 있음 |
|                                         | Advanced eDiscovery: 테넌트 보고서                              | 사용할 수 있음 |
|                                         | Advanced eDiscovery: Themes                              | 사용할 수 있음 |
|                                         | Advanced eDiscovery: Viewers                              | 사용할 수 있음 |
|                                         | Advanced eDiscovery: Yammer 준수 센터의 Advanced eDiscovery                              | 사용할 수 있음 |
|                                         | Advanced eDiscovery: Microsoft 준수 센터에서 SharePoint 및 비즈니스용 OneDrive의 항목 검색 및 내보내기 지원을 확장                              | 개발 중 |
|                                         | Advanced eDiscovery: Teams 반응 지원                              | 개발 중 |
|                                         | 기본 감사                              | 사용할 수 있음 |
|                                         | 고급 감사: 중요한 이벤트에 대한 액세스(예: mailitemsaccessed)                              | 사용할 수 있음 |
|                                         | 고급 감사: 관리 활동 API에 대한 대역폭 증가                              | 사용할 수 있음 |
|                                         | 고급 감사: Teams 비공개 채널 메시지에 대한 법적 보유                               | 사용할 수 있음 |
|                                         | 고급 감사: 로그 보존(1년)                               | 배포 중 |
|                                         | 고급 감사: 보안 및 준수 센터                               | 사용할 수 있음 |
|                                         | 고급 감사: 감사 로그에 대한 장기 보존(10년)                               | 백로그 엔지니어링 |
|                                         | 고급 감사: 메일 전달 및 메일 보내기 이벤트                               | 백로그 엔지니어링 |
|                                         | 고급 감사: 처리된 감사 인사이트                               | 백로그 엔지니어링 |
|                                         | 고급 감사: Exchange Online 및 SharePoint Online의 검색 용어 이벤트                              | 백로그 엔지니어링 |
|    **준수 관리**            | Microsoft 365 보안 및 준수 센터                              | 사용할 수 있음 |
|                                         | 규정 관리자                              | 사용할 수 있음 |
|                                         | Microsoft Cloud App Security                              | 백로그 엔지니어링 |
|                                         | 더블 Byte 문자 지원                              | 백로그 엔지니어링 |
|    **에코시스템**            | Advanced eDiscovery용 그래프 API                              | 개발 중 |
|                                         | 자체 데이터 커넥터                              | 백로그 엔지니어링 |
|                                         | 타사 데이터 커넥터                              | 백로그 엔지니어링 |
|                                         | Teams 내보내기 데이터용 그래프 API                              | 백로그 엔지니어링 |




<sup>1</sup> 프로젝트 계획 및 우선 순위가 다시 평가되면 식별된 상태는 변경될 수 있습니다.<br/>

**결정 지점:** 규정 준수 기능이 조직의 요구 *사항을 충족하는지 여부를 결정합니다.*