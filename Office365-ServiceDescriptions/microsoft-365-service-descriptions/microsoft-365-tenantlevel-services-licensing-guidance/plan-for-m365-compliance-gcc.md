---
title: Microsoft 365 규정 준수 - GCC 계획
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 이 지침은 미국 연방, 주Office 365 주, 지방, 부족 또는 영토적 정부 기관 또는 정부 규정 및 요구 사항을 준수하는 데이터를 처리하는 기타 기관에서 Microsoft 365 정부 - GCC 배포를 주도하는 IT 프로를 위한 것입니다.
ms.openlocfilehash: 44dd4a10560fb5bd0d1c0f36f3290b621798d03d390573d789b99d62047bad1e
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/06/2021
ms.locfileid: "54663271"
---
# <a name="plan-for-microsoft-365-compliance--gcc"></a>Microsoft 365 준수 계획 - GCC

이 지침은 미국 연방, 주Office 365 주, 지방, 부족 또는 영토적 정부 기관 또는 정부 규정 및 요구 사항을 준수하는 데이터를 처리하는 기타 기관에서 Microsoft 365 정부 - GCC 배포를 주도하는 IT 프로를 위한 것입니다.

> [!NOTE]
> 조직이 이미 Microsoft 365 - GCC 자격 요구 사항을 충족하고 프로그램에 적용된 경우 1단계와 2단계를 건너뛰고 3단계로 바로 이동하면 됩니다.

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---gcc-and-meets-eligibility-requirements"></a>1단계. 조직에서 정부에 필요한 Microsoft 365 - GCC 요구 사항 충족 여부 확인

Microsoft 365 - GCC 환경은 FedRAMP Moderate을 비롯한 클라우드 서비스에 대한 미국 정부 요구 사항 및 범죄 사법 및 연방 세금 정보 시스템(CJI 및 FTI 데이터 형식)에 대한 요구 사항을 준수합니다.

조직은 조직의 기능과 기능을 Office 365 Government에서만 사용할 수 있는 다음과 같은 기능을 Microsoft 365- GCC.

- 조직의 고객 콘텐츠는 Microsoft의 상용 서비스에서 고객 콘텐츠와 Office 365 있습니다.

- 조직의 고객 콘텐츠는 미국에 보관됩니다.

- 조직 고객 콘텐츠에 대한 액세스는 선별된 Microsoft 직원으로 제한됩니다.

- Microsoft 365 정부 - GCC 미국 공공 부문 고객에게 필요한 인증 및 인증을 준수합니다.

미국 정부 고객을 위한 Microsoft 365 - GCC 대한 자세한 내용은 Office 365 Government [](https://products.office.com/government/compare-office-365-government-plans)요금제에서 찾을 수 있습니다.

이 [Office 365 미국 정부](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md) 서비스 설명에서는 미국 내 규정 준수 요구 사항을 충족하는 데 중심을 두는 플랫폼의 이점에 대해 설명하고 있습니다.

> [!TIP]
> 서비스 설명의 정보 표를 Excel 통합 문서로 전송하고 두 개의 열(조직 **관련 Y/N** 및 조직 Y/N 요구 사항 충족)을 **추가할 수 있습니다.** 그런 다음 이 목록을 동료와 검토하여 이 서비스가 조직의 요구 사항을 충족하는지 확인할 수 있습니다.

> [!NOTE]
> Microsoft 365 Government - GCC 미국에서만 사용할 수 있습니다. 미국 정부 이 아닌 고객은 다양한 요금제 중 Office 365 Government [있습니다.](https://products.office.com/government/compare-office-365-government-plans)

**결정 사항**: <br/>
- *조직에 Microsoft 365 - GCC 적합한지 여부를 결정하십시오.*
- *조직이 자격 요구 사항을 충족하는지 확인합니다.*

## <a name="step-2-apply-for-microsoft-365-government---gcc"></a>2단계. 정부 Microsoft 365 신청 - GCC

이 서비스가 조직에 적합한 것으로 결정한 후 이 서비스에 적용하는 [프로세스를 시작하십시오.](https://products.office.com/government/eligibility-validation)

## <a name="step-3-understand-microsoft-365-government---gcc-default-security-settings"></a>3단계. 정부 Microsoft 365 - GCC 보안 설정 이해

관리자 및 보안 설정을 수정하기 전에 신중하게 검토하고 기본 보안 설정을 변경하기 전에 규정 준수에 미치는 영향을 고려하는 것이 좋습니다.

**결정 지점:** 기본 Microsoft 365 Government - GCC 보안 설정을 수정할지 여부를 결정하여 변경 내용이 미치는 영향을 먼저 *파악합니다.*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gccsup1sup"></a>4단계. Microsoft 365 Government에서 현재 사용할 수 없거나 사용하지 않도록 설정되어 있는 기능 이해 - GCC<sup>1</sup>

정부 클라우드 고객의 요구 사항을 수용하기 위해 정부- Microsoft 365 및 엔터프라이즈 계획 간에 GCC 있습니다. 다음 표를 참조하여 사용 가능한 기능을 참조합니다. 이 [로드맵에](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) 게시된 최신 준수 제품 업데이트는 Microsoft 365 참조하세요.<br><br>

| 영역 | 기능 | GCC 상태 |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **정보 보호**              | 통합 레이블 클라이언트 및 스캐너         | 사용할 수 있음              |
|                                         | 정확한 데이터 일치          | 사용할 수 있음              |
| 민감도 레이블 지정                    | Exchange Online, SharePoint Online 및 OneDrive                      | 사용할 수 있음         |
| 민감도 레이블 지정                    | 플랫폼(웹, Android, iOS, Windows 및 Mac)에서 Office 앱(Word, Excel, PowerPoint, Outlook)에 대한 자동 분류 및 레이블 지정 |  사용할 수 있음              |
| 민감도 레이블 지정                    | Office 클라이언트에 대한 자동 분류 및 레이블 지정(모바일)                                       | 백로그 엔지니어링              |
| 민감도 레이블 지정                    | Teams, Microsoft 365, SharePoint 사이트에 대한 자동 분류 및 레이블 지정                            | 사용할 수 있음 |
| 분석                               | 데이터 분류 분석: 개요 및 콘텐츠 탐색기                            | 사용할 수 있음 |
| 분석                               | 분석: 서비스 쪽에서 자동 레이블을 지정하는 기계 학습 분류자                           | 백로그 엔지니어링  |
| 분석                               | 분석: 앱/클라이언트 쪽에서 자동 Office 기계 학습 분류자                           | 배포 중 |
| 암호화                              | 기본 Office 365 메시지 암호화(E3)                            | 사용할 수 있음              |
| 암호화                              | 고급 Office 365 메시지 암호화(E5)  | 사용할 수 있음              |
| 암호화                              | Office 365에 대한 고객 키    | 사용할 수 있음 |
| 암호화                              | 고객 키: 사용자에 대한 미사용 데이터 Microsoft 365    | 배포 중 |
| 암호화                              | 고객 관리 키 프로비전 수명 주기를 위해 BYOK(Bring Your Own Key)를 가져오기                            | 사용할 수 있음 |
| 암호화                              | 이중 키 암호화                           | 사용할 수 있음 |
| 암호화                              | Exchange Online 키를 사용하여 서비스 암호화         | 사용할 수 있음 |
| 데이터 손실 방지                    | 파일 및 전자 메일에 대한 DLP(데이터 손실 방지)         | 사용할 수 있음 |
| 데이터 손실 방지                    | 채팅 및 Teams 대화용 DLP         | 사용할 수 있음 |
| 데이터 손실 방지                    | DLP 끝점 | 배포 중 |
| 데이터 손실 방지                    | 경고 대시보드 | 개발 중 |
| 데이터 손실 방지                    | 개요 페이지 | 개발 중 |
| **정보 거버넌스** | 보존 및 레이블 지정 정책에 대한 적응 범위                 | 백로그 엔지니어링              |
| 정보 거버넌스                 | 전자 메일 보관          | 사용할 수 있음              |
| 정보 거버넌스                 | SharePoint, 비즈니스용 OneDrive, 폴더 및 문서 집합에 대한 기본 보존 레이블 Exchange 받은 편지함; 및 Office 365 그룹          | 사용할 수 있음              |
| 정보 거버넌스                 | PST 가져오기                      | 사용할 수 있음              |
| 정보 거버넌스                 | 수동 레코드가 아닌 보존 레이블            | 사용할 수 있음 |
| 정보 거버넌스                 | 보존 잠금            | 사용할 수 있음 |
| 정보 거버넌스                 | 전체 조직에 대한 보존 정책 특정 위치 또는 사용자 특정 조건에 따라 자동으로(예: 키워드 또는 중요한 정보) 및 이벤트 기반                                       | 사용할 수 있음              |
| 정보 거버넌스                 | 보존 정책에 Teams                            | 사용할 수 있음 |
| 정보 거버넌스                 | 모임 녹음/Teams 보존 정책                            | 개발 중 |
| 정보 거버넌스                 | 개인 채널에 대한 Teams 정책                            | 백로그 엔지니어링 |
| 정보 거버넌스                 | 공유 채널에 대한 Teams 정책                            | 백로그 엔지니어링 |
| 정보 거버넌스                 | 학습 가능한 분류자에 대한 보존 정책                            | 백로그 엔지니어링 |
| 정보 거버넌스                 | 보존 정책에 Yammer                            | 백로그 엔지니어링 |
| 레코드 관리                     | 레코드 레이블을 삭제하는 능력                           | 개발 중              |
| 레코드 관리                     | 수동으로 레코드 레이블 적용                            | 사용할 수 있음              |
| 레코드 관리                     | 기본 레코드 레이블을 SharePoint, 비즈니스용 OneDrive, 폴더 및 문서 집합에 적용합니다. 및 Office 365 그룹                              | 사용할 수 있음              |
| 레코드 관리                     | 특정 조건(예: 키워드 또는 중요한 정보)에 따라 레코드 정책을 자동으로 적용합니다. 및 이벤트 기반                            | 사용할 수 있음              |
| 레코드 관리                     | 학습 가능한 분류자에 레코드 정책 자동 적용  | 개발 중              |
| 레코드 관리                     | 처리 검토  | 사용할 수 있음              |
| 레코드 관리                     | 파일 플랜 관리자    | 사용할 수 있음 |
| 레코드 관리                     | 다단계 진행 검토    | 백로그 엔지니어링 |
| 레코드 관리                     | Outlook 관리에 대한 클라이언트 지원    | 백로그 엔지니어링 |
| 레코드 관리                     | Power Automate Flow 종료 시    | 백로그 엔지니어링 |
| 레코드 관리                     | 클라우드 첨부 파일 보존 및 자동 레이블 지정    | 백로그 엔지니어링 |
| 레코드 관리                     | 폐기 증명                            | 사용할 수 있음 |
| 레코드 관리                     | 레코드 버전 관리                            | 사용할 수 있음 |
| 레코드 관리                     | 규정 레코드                         | 사용할 수 있음 |
| 레코드 관리                     | 레코드 SharePoint Syntex 분류를 사용하여 레코드 레이블 적용 | 백로그 엔지니어링 |
| **내부자 위험 관리**             | 고객 Lockbox                                | 사용할 수 있음            |
| 커뮤니케이션 규정 준수                | 전자 메일 서명 또는 고지 조항을 무시하는 능력                         | 개발 중 |
| 커뮤니케이션 규정 준수                | 통신 준수 정책에 대한 보존 기간을 설정하는 능력                         | 개발 중 |
| 커뮤니케이션 규정 준수                | 알림 액세스 알림 서식 파일 통신 정책 대시보드                         | 사용할 수 있음 |
| 커뮤니케이션 규정 준수                | 프레미스 Teams 사용자의 채팅 데이터 분석                         | 사용할 수 있음 |
| 커뮤니케이션 규정 준수                | 사용자가 구성원인 Teams 자동으로 모니터링                         | 사용할 수 있음 |
| 커뮤니케이션 규정 준수                | 이해 상충 템플릿                         | 사용할 수 있음 |
| 커뮤니케이션 규정 준수                | 고객 정책 만들기, 미리 구성된 3개                         | 사용할 수 있음 |
| 커뮤니케이션 규정 준수                | 성인용 콘텐츠 검색                         | 사용할 수 있음 |
| 커뮤니케이션 규정 준수                | 시간의 반복적인 행동 위반 감지                         | 사용할 수 있음 |
| 커뮤니케이션 규정 준수                | 에스컬레이터에서 조사를 Advanced eDiscovery                         | 사용할 수 있음 |
| 커뮤니케이션 규정 준수                | 내부자 위험 관리 손도장                         | 백로그 엔지니어링 |
| 커뮤니케이션 규정 준수                | 광학 문자 인식을 활용하여 메시지 추출 및 평가                         | 개발 중 |
| 커뮤니케이션 규정 준수                | 소규모 기업을 위한 새로운 간소화된 보기                         | 개발 중 |
| 커뮤니케이션 규정 준수                | 정책 상태 검사 및 정책 일시 중지 능력                         | 개발 중 |
| 커뮤니케이션 규정 준수                | 파워 자동화 통합                         | 개발 중 |
| 커뮤니케이션 규정 준수                | 보다 세분화된 사용 권한 지원                         | 사용할 수 있음 |
| 커뮤니케이션 규정 준수                | 위협, 괴롭음 및 괴롭음 분류자에 대한 7개 언어 지원                         | 개발 중 |
| 커뮤니케이션 규정 준수                | Microsoft Teams 통합                         | 백로그 엔지니어링 |
| 커뮤니케이션 규정 준수                | Teams 대화 컨텍스트                         | 개발 중 |
| 커뮤니케이션 규정 준수                | 조사 중에 콘텐츠 번역                         | 백로그 엔지니어링 |
| 고객 Lockbox                | 고객 Lockbox                         | 사용할 수 있음 |
| 정보 장벽                | 정보 장벽                         | 사용할 수 있음 |
| 내부자 위험 관리             | 케이스 대시보드                         | 사용할 수 있음 |
| 내부자 위험 관리             | 퇴사하는 직원의 데이터 도난                        | 사용할 수 있음 |
| 내부자 위험 관리             | 빌드 1809 이상에서 Windows 10 대한 장치 표시기                        | 백로그 엔지니어링 |
| 내부자 위험 관리             | 에스컬레이터에서 조사를 Advanced eDiscovery                        | 사용할 수 있음 |
| 내부자 위험 관리             | 경고 내보내기                        | 백로그 엔지니어링 |
| 내부자 위험 관리             | 일반적인 데이터 유출                                | 사용할 수 있음              |
| 내부자 위험 관리             | 보안 정책 위반 표시기                   | 백로그 엔지니어링              |
| 내부자 위험 관리             | 끝점 경고에 대한 Microsoft Defender 표시기      | 백로그 엔지니어링              |
| 내부자 위험 관리             | 내부자 위험 관리 활동 탐색기      | 개발 중              |
| 내부자 위험 관리             | 내부자 위험 관리 콘텐츠 탐색기      | 개발 중              |
| 내부자 위험 관리             | 내부자 위험 관리 경고 조사      | 사용할 수 있음              |
| 내부자 위험 관리             | 알림 템플릿      | 사용할 수 있음              |
| 내부자 위험 관리             | Office, Teams, SharePoint 메시지에 대한 SharePoint 표시기      | 사용할 수 있음              |
| 내부자 위험 관리             | 정책 사용자 지정      | 백로그 엔지니어링              |
| 내부자 위험 관리             | 불만이 있는 사용자의 데이터 누출을 위한 정책 템플릿      | 백로그 엔지니어링              |
| 내부자 위험 관리             | 우선 순위 사용자에 의해 데이터 누출을 위한 정책 템플릿 | 백로그 엔지니어링 |
| 내부자 위험 관리             | 일반 보안 정책 위반에 대한 정책 템플릿 | 백로그 엔지니어링 |
| 내부자 위험 관리             | 우선 순위 사용자, 퇴사한 사용자, 불만이 있는 사용자에 대한 보안 정책 위반에 대한 정책 템플릿 | 백로그 엔지니어링 |
| 내부자 위험 관리             | 우선 순위 사용자 그룹 | 백로그 엔지니어링 |
| 내부자 위험 관리             | 파워 자동화 통합 | 개발 중 |
| 내부자 위험 관리             | Microsoft Teams 통합 | 백로그 엔지니어링 |
| 권한 있는 액세스 관리        | 권한이 부여된 액세스 관리 | 백로그 엔지니어링 |
| **응답 & 검색**                  | 핵심 eDiscovery: 감사                            | 사용할 수 있음              |
| eDiscovery                              | 핵심 eDiscovery: 사례 관리                                 | 사용할 수 있음              |
| eDiscovery                              | Core eDiscovery: Export                                          | 사용할 수 있음              |
| eDiscovery                              | Core eDiscovery: In-place preservation                           | 사용할 수 있음              |
| eDiscovery                              | Core eDiscovery: 기본 내보내기                                  | 사용할 수 있음              |
| eDiscovery                              | Core eDiscovery: RMS 암호 해독                                   | 사용할 수 있음              |
| eDiscovery                              | Core eDiscovery: 검색                                   | 사용할 수 있음              |
| eDiscovery                              | 핵심 eDiscovery: Microsoft 준수 센터에서 지원이 확장되어 SharePoint 및 비즈니스용 OneDrive 수 있습니다.                                        | 사용할 수 있음              |
| eDiscovery                              | Advanced eDiscovery: 고급 처리                             | 사용할 수 있음 |
| eDiscovery                              | Advanced eDiscovery: 작업 매핑에 대한 관리                             | 사용할 수 있음 |
| eDiscovery                              | Advanced eDiscovery: Custodian communications                             | 사용할 수 있음 |
| eDiscovery                              | Advanced eDiscovery: 대시보드                                 | 사용할 수 있음 |
| eDiscovery                              | Advanced eDiscovery: 더블 Byte 문자 지원(중국어, 일본어, 한국어)                                 | 사용할 수 있음 |
| eDiscovery                              | Advanced eDiscovery: 전자 메일 스레딩                   | 사용할 수 있음 |
| eDiscovery                              | Advanced eDiscovery: 내보내기(다운로드, 내보내기, 다른 보기 집합에 추가)                                          | 사용할 수 있음 |
| eDiscovery                              | Advanced eDiscovery: 필터링                               | 사용할 수 있음 |
| eDiscovery                              | Advanced eDiscovery: 보류 최적화                      | 개발 중 |
| eDiscovery                              | Advanced eDiscovery: Teams 채널 메시지에 대한 법적 보유            | 사용할 수 있음 |
| eDiscovery                              | Advanced eDiscovery: Microsoft 준수 센터에서 지원이 확장되어 SharePoint 및 비즈니스용 OneDrive 수 있습니다.            | 개발 중 |
| eDiscovery                              | Advanced eDiscovery: 중복에 가까운 식별                               | 사용할 수 있음 |
| eDiscovery                              | Advanced eDiscovery: 새로운 예측 코딩 모듈                   | 백로그 엔지니어링 |
| eDiscovery                              | Advanced eDiscovery: 비보조 데이터 원본                                  | 사용할 수 있음 |
| eDiscovery                              | Advanced eDiscovery: 비영구 Office 365                                    | 사용할 수 있음 |
| eDiscovery                              | Advanced eDiscovery: 예측 코딩                                       | 사용할 수 있음 |
| eDiscovery                              | Advanced eDiscovery: 로드 파일로 내보내기 처리                   | 사용할 수 있음 |
| eDiscovery                              | Advanced eDiscovery: 재배포                        | 사용할 수 있음 |
| eDiscovery                              | Advanced eDiscovery: 검토 집합                                     | 사용할 수 있음 |
| eDiscovery                              | Advanced eDiscovery: 데이터(쿼리 데이터, 스마트 태그, 대시보드) 및 주석 작성(재조정)                             | 사용할 수 있음 |
| eDiscovery                              | Advanced eDiscovery: 검색 용어 보고서                        | 사용할 수 있음 |
| eDiscovery                              | Advanced eDiscovery: 단일 항목 오류 수정                              | 사용할 수 있음 |
| eDiscovery                              | Advanced eDiscovery: PST 내보내기 지원                              | 사용할 수 있음 |
| eDiscovery                              | Advanced eDiscovery: OneDrive 및 SharePoint Online의 연결된 콘텐츠 지원(최신 첨부 파일)                              | 사용할 수 있음 |
| eDiscovery                              | Advanced eDiscovery: 지원 Teams 반응 지원                      | 백로그 엔지니어링 |
| eDiscovery                              | Advanced eDiscovery: 태그 지정                              | 사용할 수 있음 |
| eDiscovery                              | Advanced eDiscovery: 테넌트 보고서                              | 사용할 수 있음 |
| eDiscovery                              | Advanced eDiscovery: 테마                              | 사용할 수 있음 |
| eDiscovery                              | Advanced eDiscovery: 뷰어                              | 사용할 수 있음 |
| eDiscovery                              | Advanced eDiscovery: Yammer Advanced eDiscovery 준수 센터의 서비스                              | 사용할 수 있음 |
| 감사                                   | 기본 감사                              | 사용할 수 있음 |
| 감사                                   | 고급 감사: 중요한 이벤트에 대한 액세스(예: *MailItemsAccessed*)                              | 사용할 수 있음 |
| 감사                                   | 고급 감사: 관리 활동 API에 대한 대역폭 증가                   | 사용할 수 있음 |
| 감사                                   | 고급 감사: 개인 채널 Teams 법적 보유                   | 사용할 수 있음 |
| 감사                                   | 고급 감사: 로그 보존(1년)                               | 사용할 수 있음 |
| 감사                                   | 고급 감사: 감사 로그에 대한 장기 보존(10년)              | 개발 중 |
| 감사                                   | 고급 감사: 메일 전달 및 메일 보내기 이벤트                               | 사용할 수 있음 |
| 감사                                   | 고급 감사: Microsoft 365 및 준수 센터                    | 사용할 수 있음 |
| 감사                                   | 고급 감사: 온라인 및 Exchange Online SharePoint 검색                              | 백로그 엔지니어링 |
|    **준수 관리**            | Microsoft 365 보안 및 준수 센터                              | 사용할 수 있음 |
|                                         | 규정 관리자                              | 사용할 수 있음 |
|                                         | 더블 Byte 문자 지원                              | 사용할 수 있음 |
|                                         | Microsoft Cloud App Security                              | 백로그 엔지니어링 |
|    **에코시스템**            | Graph Advanced eDiscovery                              | 개발 중 |
|                                         | Graph 데이터 내보내기 Teams API                              | 백로그 엔지니어링 |
|                                         | 자체 데이터 커넥터                              | 백로그 엔지니어링 |
|                                         | 타사 데이터 커넥터                              | 개발 중 |




<sup>1</sup> 프로젝트 계획 및 우선 순위가 다시 평가되면 식별된 상태는 변경될 수 있습니다.<br/>

**결정 지점:** 규정 준수 기능이 조직의 요구 *사항을 충족하는지 여부를 결정합니다.*
