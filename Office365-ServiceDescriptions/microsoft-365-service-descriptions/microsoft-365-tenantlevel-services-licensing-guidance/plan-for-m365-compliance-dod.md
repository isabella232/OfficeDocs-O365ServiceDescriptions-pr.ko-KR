---
title: Microsoft 365 규정 준수 - DoD 배포 계획
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 이 지침은 미국 연방 정부 엔터티 또는 정부 규정 요구 사항이 적용 되는 데이터를 처리 하는 기타 엔터티와의 Office 365의 배포를 추진 하는 IT 전문가를 위한 것으로, Microsoft 365 정부-DoD를 사용 하는 것이 이러한 요구 사항을 충족 하는 데 적합 합니다.
ms.openlocfilehash: 6f0a271a6d547f69dfb7d3d20ba943465eb149a6
ms.sourcegitcommit: 0752cc6c082737a19c7dca24c8f3b555ea871f4f
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 12/01/2020
ms.locfileid: "49519049"
---
# <a name="plan-for-microsoft-365-compliance---dod-deployments"></a>Microsoft 365 규정 준수 - DoD 배포 계획

이 지침은 미국 연방 정부 엔터티 또는 정부 규정 요구 사항이 적용 되는 데이터를 처리 하는 기타 엔터티와의 Office 365의 배포를 추진 하는 IT 전문가를 위한 것으로, Microsoft 365 정부-DoD를 사용 하는 것이 이러한 요구 사항을 충족 하는 데 적합 합니다.

> [!NOTE]
> 조직이 Microsoft 365 정부-DoD 자격 요건을 이미 충족 하 여 프로그램에 적용 되 고이에 동의 하는 경우 1 단계와 2 단계로 건너뛰고 3 단계로 바로 이동할 수 있습니다.

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---dod-and-meets-eligibility-requirements"></a>1단계. 조직에 Microsoft 365 정부-DoD가 필요 하며 자격 요구 사항을 충족 하는지 확인

Microsoft 365 정부-DoD 환경은 클라우드 서비스에 대 한 미국 정부 요구 사항을 준수 합니다.

Office 365의 기능을 제공 하는 것 외에도 조직은 Microsoft 365 정부-DoD에 고유한 다음과 같은 기능을 활용할 수 있습니다.

- 조직의 고객 콘텐츠는 Microsoft의 상용 Office 365 서비스에 있는 고객 콘텐츠와 논리적으로 분리 됩니다.
- 조직의 고객 콘텐츠는 미국에 보관됩니다.
- 조직 고객 콘텐츠에 대한 액세스는 선별된 Microsoft 직원으로 제한됩니다.
- Microsoft 365 정부-DoD는 미국 공공 부문 고객에 게 필요한 인증 및 승인을 준수 합니다.

내게 필요한 옵션을 포함 하 여 [Office 365 정부 계획](https://products.office.com/government/compare-office-365-government-plans)에서 미국 정부 고객을 위한 Microsoft 365 정부-DoD 제공에 대 한 자세한 정보를 확인할 수 있습니다.

[Office 365 US 정부 서비스 설명은](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government) 미국 내에서 모임 준수 요구 사항을 중심으로 하는 플랫폼의 이점을 설명 합니다.

> [!TIP]
> 서비스 설명의 정보 테이블을 Excel 통합 문서에 전송 하 고 **조직 y/n에 관련** 된 두 개의 열을 추가 하 고 **조직 y/n의 요구 사항을 충족** 해야 할 수 있습니다. 그런 다음 동료와 함께이 목록을 검토 하 여이 서비스가 조직의 요구를 충족 하는지 확인할 수 있습니다.

**의사 결정 사항**:<br/>
- *Microsoft 365 정부-DoD가 조직에 적합 한지 여부를 결정 합니다.*
- *조직이 자격 요건을 충족 하는지 확인 합니다.*

> [!NOTE]
> Microsoft 365 정부-DoD는 미국 에서만 사용할 수 있습니다. 미국 이외 지역의 정부 고객은 수많은 [Office 365 정부 계획](https://products.office.com/government/compare-office-365-government-plans)중에서 선택할 수 있습니다.

## <a name="step-2-apply-for-microsoft-365-government---dod"></a>2단계. Microsoft 365 정부에 적용-DoD

이 서비스가 조직에 적합 하다 고 판단 되 면 [이 서비스에 대 한 적용](https://products.office.com/government/eligibility-validation)프로세스를 시작 합니다.

## <a name="step-3-understand-microsoft-365-government---dod-default-security-settings"></a>3단계. Microsoft 365 정부-DoD 기본 보안 설정 이해

관리 및 보안 설정을 수정 하기 전에 주의 깊게 검토 하 고, 기본 보안 설정을 변경 하기 전에 준수에 미치는 영향을 고려 하는 것이 좋습니다.

**의사 결정** 사항: *기본 Microsoft 365 정부 보안 설정을 수정 하 고, 변경 내용에 대 한 영향을 먼저 이해 하도록 확인 합니다.*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--dodsup1sup"></a>4단계. Microsoft 365 정부에서 기본적으로 현재 사용할 수 없거나 사용 하지 않도록 설정 된 기능 이해 (영문<sup>)</sup>

정부 클라우드 고객의 요구 사항을 충족 하기 위해 Microsoft 365 정부-DoD 및 enterprise 요금제 간에는 약간의 차이가 있습니다. 사용 가능한 기능을 확인 하려면 다음 표를 참조 하세요. Microsoft 365 로드맵에 게시 된 최신 준수 제품 업데이트는 [여기](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) 를 참조 하세요.<br><br>

| 영역                                    | 기능                                         | GCC 상태             |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **정보 보호**              | 통합 레이블 클라이언트 및 스캐너         | 사용할 수 있음              |
|                                         | 정확한 데이터 일치          | 사용할 수 있음               |
|                                         | Exchange Online, SharePoint Online 및 OneDrive에 대 한 자동 분류 및 레이블                      | 배포 중              |
|                                         | 플랫폼 간의 Office 앱 (Word, Excel, PowerPoint, Outlook)에 대 한 자동 분류 및 레이블 (웹, Android, iOS, Windows 및 Mac)            | 개발 환경 |
|                                         | 모바일에 대 한 자동 분류 및 레이블 지정                                       | 엔지니어링 백로그              |
|                                         | 팀에 대 한 자동 분류 및 레이블 지정                            | 엔지니어링 백로그 |
|                                         | 데이터 분류: 개요 및 콘텐츠 탐색기                            | 개발 환경 |
|                                         | 분석: 서비스 쪽에서 자동 레이블 지정을 사용 하는 기계 학습 분류자                           | 엔지니어링 백로그  |
|                                         | 분석: Office 앱/클라이언트 쪽에서 자동 레이블 지정을 사용 하는 기계 학습 분류자                           | 엔지니어링 백로그  |
|                                         | 기본 Office 365 메시지 암호화 (E3)                            | 사용할 수 있음              |
|                                         | 고급 Office 365 메시지 암호화 (E5)  | 사용할 수 있음              |
|                                         | Office 365에 대한 고객 키    | 사용할 수 있음 |
|                                         | 사용자가 관리 하는 키 프로 비전 수명 주기에 대해 사용자 키 (BYOK) 가져오기                            | 사용할 수 있음 |
|                                         | 높은 규제 대상 시나리오 (미리 보기)에 대 한 Azure Information Protection 및 AD (Active Directory) 권한 관리 범위를 적용 하는 자체 키 (HYOK)를 포함 합니다.                         | 사용할 수 있음 |
|                                         | 이중 키 암호화                           | 배포 중 |
|                                         | 파일 및 전자 메일에 대 한 DLP (데이터 손실 방지)         | 사용할 수 있음 |
|                                         | 팀 채팅 및 채널 대화에 대 한 DLP         | 엔지니어링 백로그 |
|                                         | DLP 정확히 일치 하는 데이터         | 엔지니어링 백로그 |
|                                         | DLP 끝점 | 엔지니어링 백로그 |
| **정보 거 버 넌 스** | 정보 거 버 넌 스: 전자 메일 보관                                       | 사용할 수 있음              |
|                                         | 정보 거 버 넌 스: 보존 잠금          | 사용할 수 있음              |
|                                         | 정보 거 버 넌 스 (가져오기 PST)                      | 사용할 수 있음              |
|                                         | 정보 거 버 넌 스: 수동 비 레코드 보존 레이블            | 사용할 수 있음 |
|                                         | 정보 거 버 넌 스: SharePoint/비즈니스용 OneDrive 라이브러리, 폴더 및 문서 집합에 대 한 기본 보존 레이블 Exchange 받은 편지함; 및 Office 365 그룹 | 사용할 수 있음              |
|                                         | 정보 거 버 넌 스: 전체 조직에 대 한 보존 정책 특정 위치 또는 사용자 특정 조건 (예: 키워드 또는 중요 정보)을 기반으로 자동으로                                       | 사용할 수 있음              |
|                                         | 정보 거 버 넌 스: trainable 분류자가 있는 보존 정책                            | 엔지니어링 백로그 |
|                                         | 정보 거 버 넌 스: 팀 모임 녹음에 대 한 보존 정책                            | 엔지니어링 백로그 |
|                                         | 정보 관리: Yammer 및 팀에 대 한 보존 정책                           | 엔지니어링 백로그              |
|                                         | 레코드 관리: 레코드 레이블에 대 한 수동 분류                              | 사용할 수 있음              |
|                                         | 레코드 관리: SharePoint, 비즈니스용 OneDrive 라이브러리, 폴더 및 문서 집합에 대 한 기본 레코드 레이블 및 Office 365 그룹                            | 사용할 수 있음              |
|                                         | 레코드 관리: 키워드 또는 중요 한 정보와 같은 특정 조건을 기반으로 하는 자동 레코드 정책 이벤트를 기반으로 합니다.  | 사용할 수 있음              |
|                                         | 레코드 관리: 처리 검토    | 사용할 수 있음 |
|                                         | 레코드 관리: 파일 계획 관리자                            | 사용할 수 있음 |
|                                         | 레코드 관리: 삭제 증명                         | 사용할 수 있음 |
|                                         | 레코드 관리: 규정 레코드 | 엔지니어링 백로그 |
|                                         | 레코드 관리: 다중 단계 처리 검토 | 엔지니어링 백로그 |
|                                         | 레코드 관리: SharePoint Syntex 분류를 사용 하 여 레코드 레이블 적용         | 엔지니어링 백로그 |
| **내부자 위험 관리**             | 고객 Lockbox                                | 사용할 수 있음            |
|                                         | 참가자 위험 관리: 팀, SharePoint 사이트, 전자 메일 메시지에 대 한 Office 지표                         | 엔지니어링 백로그 |
|                                         | 참가자 위험 관리: departing 사용자에의 한 데이터 도용                        | 엔지니어링 백로그 |
|                                         | 참가자 위험 관리: 일반 데이터 누수                                | 엔지니어링 백로그              |
|                                         | 참가자 위험 관리: 참가자 위험 관리 알림 조사                                   | 엔지니어링 백로그              |
|                                         | 참가자 위험 관리: 사례 대시보드, 콘텐츠 탐색기 및 알림 서식 파일 | 엔지니어링 백로그 |
|                                         | 참가자 위험 관리: Advanced eDiscovery에 대 한 조사 확대 |엔지니어링 백로그|
|                                         | 참가자 위험 관리: Windows 10 빌드 1809 이상에 대 한 활동에 대 한 장치 지표 |엔지니어링 백로그|
|                                         | 참가자 위험 관리: 보안 정책 위반에 대 한 지표 (미리 보기) |엔지니어링 백로그|
|                                         | 참가자 위험 관리: 끝점 경고 용 Microsoft Defender에 대 한 지표 (미리 보기) |엔지니어링 백로그|
|                                         | 참가자 위험 관리: 우선 순위 사용자의 데이터 누출에 대 한 정책 서식 파일 (미리 보기) | 엔지니어링 백로그 |
|                                         | 참가자 위험 관리: 불만 사용자의 데이터 누출에 대 한 정책 템플릿 (미리 보기) | 엔지니어링 백로그 |
|                                         | 참가자 위험 관리: 일반 보안 정책 위반에 대 한 정책 서식 파일 (미리 보기) | 엔지니어링 백로그 |
|                                         | 참가자 위험 관리: 우선 순위 사용자, departing 사용자, 불만 사용자에의 한 보안 정책 위반에 대 한 정책 서식 파일 (미리 보기) | 엔지니어링 백로그 |
|                                         | 참가자 위험 관리: 정책 사용자 지정 (미리 보기) | 엔지니어링 백로그 |
|                                         | 참가자 위험 관리: 알림 내보내기 (미리 보기) | 엔지니어링 백로그 |
|                                         | 참가자 위험 관리: 우선 순위 사용자 그룹 (미리 보기) | 엔지니어링 백로그 |
|                                         | 통신 준수 (incl-감독 정책): 고객 정책 만들기, 3 개 미리 구성 됨  | 엔지니어링 백로그 |
|                                         | 통신 준수 (incl-감독 정책): 팀, Exchange 및 팀 제거 메시지에 대 한 지원 | 엔지니어링 백로그 |
|                                         | 통신 준수 (incl-감독 정책): 경고 액세스 참고 서식 파일 통신 정책 대시보드 | 엔지니어링 백로그  |
|                                         | 통신 준수 (incl 정책): Advanced eDiscovery에 대 한 조사를 위해 에스컬레이션 합니다. | 엔지니어링 백로그 |
|                                         | 통신 준수 (incl 정책): 성인용 콘텐츠 검색 | 엔지니어링 백로그 |
|                                         | 통신 준수 (incl 정책): 시간에 따른 반복 위반 코드를 검색 합니다. | 배포 중 |
|                                         | 통신 준수 (incl 정책): 보다 세분화 된 사용 권한을 지원 합니다. | 배포 중 |
|                                         | 통신 준수 (incl 정책): 온-프레미스 사서함을 사용 하는 사용자의 팀 채팅 데이터 분석 | 배포 중 |
|                                         | 통신 준수 (incl 정책): 관심 서식 파일의 충돌 | 엔지니어링 백로그 |
|                                         | 통신 준수 (incl 정책): 전자 메일 서명 또는 고 지 사항을 무시할 수 있습니다. | 엔지니어링 백로그 |
|                                         | 통신 준수 (incl 정책): 위험 관리 직접 참가자 | 엔지니어링 백로그 |
|                                         | 통신 준수 (incl 정책): 정책 상태 확인 및 정책 일시 중지 기능 | 엔지니어링 백로그 |
|                                         | 통신 준수 (incl 정책): 조사 중에 상태 콘텐츠를 번역 합니다. | 엔지니어링 백로그 |
|                                         | 통신 준수 (incl-감독 정책): Burnout 및 suicide 검색 | 엔지니어링 백로그 |
|                                         | 정보 장벽 | 엔지니어링 백로그 |
|                                         | 권한이 부여된 액세스 관리                    | 엔지니어링 백로그 |
| **응답 & 검색**                  | 코어 eDiscovery: 원본 위치 유지                            | 사용할 수 있음              |
|                                         | 코어 eDiscovery: 사례 관리                                 | 사용할 수 있음              |
|                                         | 코어 eDiscovery: 검색                                          | 사용할 수 있음              |
|                                         | 코어 eDiscovery: 내보내기                                          | 사용할 수 있음              |
|                                         | 코어 eDiscovery: RMS 암호 해독                                  | 사용할 수 있음              |
|                                         | 코어 eDiscovery: 네이티브 내보내기                                   | 사용할 수 있음              |
|                                         | 코어 eDiscovery: 감사                                        | 사용할 수 있음              |
|                                         | 고급 eDiscovery: 고급 처리                                 | 배포 중 |
|                                         | 고급 eDiscovery: Custodian-작업에 대 한 매핑                                 | 배포 중 |
|                                         | Advanced eDiscovery: Custodian 통신                                 | 배포 중 |
|                                         | 고급 eDiscovery: 대시보드                   | 배포 중 |
|                                         | 고급 eDiscovery: 전자 메일 스레딩                                          | 배포 중 |
|                                         | 고급 eDiscovery: 내보내기 (다운로드, 내보내기, 다른 검토 설정에 추가)                               | 배포 중 |
|                                         | 고급 eDiscovery: 필터링                 | 배포 중 |
|                                         | 고급 eDiscovery: 팀 개인 채널 메시지에 대 한 법적 보존                                         | 배포 중 |
|                                         | 고급 eDiscovery: 근접 중복 식별                                         | 배포 중 |
|                                         | 고급 eDiscovery: 비 Office 365 수집                                      | 배포 중 |
|                                         | 고급 eDiscovery: 예측 코딩                                       | 배포 중 |
|                                         | 고급 eDiscovery: 로드 파일을 사용 하 여 내보내기 처리                   | 배포 중 |
|                                         | Advanced eDiscovery: Redactions                        | 배포 중 |
|                                         | Advanced eDiscovery: 검토 집합                                     | 배포 중 |
|                                         | 고급 eDiscovery: 검토 및 주석 달기                             | 배포 중 |
|                                         | Advanced eDiscovery: 용어 검색 보고서                        | 배포 중 |
|                                         | Advanced eDiscovery: OneDrive 및 SharePoint Online (최신 첨부 파일)에서 연결 된 콘텐츠 지원                        | 배포 중 |
|                                         | 고급 eDiscovery: 태그 지정                              | 배포 중 |
|                                         | 고급 eDiscovery: 팀 reactions 지원                              | 배포 중 |
|                                         | 고급 eDiscovery: 테 넌 트 보고서                              | 배포 중 |
|                                         | 고급 eDiscovery: 테마                              | 배포 중 |
|                                         | 고급 eDiscovery: 뷰어                              | 배포 중 |
|                                         | Advanced eDiscovery: Microsoft 준수 센터의 Yammer Advanced eDiscovery                              | 배포 중 |
|                                         | Advanced eDiscovery: 고급 eDiscovery에 대 한 CJK/더블 바이트 지원                              | 개발 환경 |
|                                         | 기본 감사                              | 사용할 수 있음 |
|                                         | 고급 감사: 중요 한 이벤트에 대 한 액세스 (예를 들어, 액세스 한 mail항목)                              | 배포 중 |
|                                         | 고급 감사: 관리 활동 API로의 대역폭 증가                              | 배포 중 |
|                                         | 고급 감사: 로그 보존 (1 년)                              | 배포 중 |
|                                         | 고급 감사: 보안 및 준수 센터 가용성                              | 사용할 수 있음 |
|                                         | 고급 감사: 감사 로그에 대 한 용어 보존 기간 초과                              | 엔지니어링 백로그 |
|                                         | 고급 감사: 메일 전달 및 메일 보내기 이벤트                              | 엔지니어링 백로그 |
|                                         | 고급 감사: 처리 된 감사 insights                              | 엔지니어링 백로그 |
|                                         | 고급 감사: Exchange Online 및 SharePoint Online의 용어 이벤트 검색                              | 엔지니어링 백로그 |
|    **준수 관리**            | Microsoft 365 보안 및 준수 센터                              | 사용할 수 있음 |
|                                         | Microsoft Cloud App Security                              | 엔지니어링 백로그 |
|                                         | 규정 관리자                              | 엔지니어링 백로그 |
|                                         | 더블 바이트 문자 지원                              | 엔지니어링 백로그 |
|    **환경**            | 고급 eDiscovery 용 Api 그래프                              | 개발 환경 |
|                                         | 제 1 사 데이터 커넥터                              | 엔지니어링 백로그 |
|                                         | 타사 데이터 커넥터                              | 엔지니어링 백로그 |
|                                         | 팀을 위한 데이터 내보내기 그래프 Api                              | 엔지니어링 백로그 |

<sup>1</sup> 확인 된 상태는 프로젝트 계획 및 우선 순위를 다시 평가 하면서 변경 될 수 있습니다.<br/>

**의사 결정** 사항: *규정 준수 기능이 조직의 요구 사항을 충족 하는지 여부를 결정 합니다.*
