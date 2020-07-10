---
title: Microsoft 365 규정 준수 - GCC High 계획
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 이 지침은 미국 연방 정부 엔터티 또는 정부 규정 요구 사항이 적용 되는 데이터를 처리 하는 기타 엔터티와의 Office 365 배포를 추진 하는 IT 전문가를 위한 것으로, Microsoft 365 정부의 사용은 이러한 요구 사항을 충족 하는 데 적합 합니다.
ms.openlocfilehash: 0d5fe248080b816056276ccb79687960cd1c58df
ms.sourcegitcommit: 9297397dbc35931a75b2c7e0e8acb321d70bfd3f
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/09/2020
ms.locfileid: "45089639"
---
# <a name="plan-for-microsoft-365-compliance--gcc-high"></a>Microsoft 365 준수 계획 – GCC High

이 지침은 미국 연방 정부 엔터티 또는 정부 규정 요구 사항이 적용 되는 데이터를 처리 하는 기타 엔터티와의 Office 365 배포를 추진 하는 IT 전문가를 위한 것으로, Microsoft 365 정부의 사용은 이러한 요구 사항을 충족 하는 데 적합 합니다.

> [!NOTE]
>조직이 Microsoft 365 정부-GCC 높은 자격 요건을 이미 충족 하 여 프로그램에 적용 되 고이에 동의 하는 경우 1 단계와 2 단계로 건너뛰고 3 단계로 바로 이동할 수 있습니다.
 
## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government--gcc-high-and-meets-eligibility-requirements"></a>1단계. 조직에서 Microsoft 365 정부를 필요로 하는지 확인-GCC 고가용성 및 자격 요구 사항 충족

Microsoft 365 정부 GCC High 환경은 클라우드 서비스에 대 한 미국 정부 요구 사항을 준수 합니다. Office 365의 기능을 사용할 수 있을 뿐만 아니라, 조직에서는 Microsoft 365 정부에 고유한 다음과 같은 기능이 제공 됩니다 (GCC High).

- 조직의 고객 콘텐츠는 Microsoft의 상용 Office 365 서비스에 있는 고객 콘텐츠와 논리적으로 분리 됩니다.
- 조직의 고객 콘텐츠는 미국에 보관됩니다.
- 조직 고객 콘텐츠에 대한 액세스는 선별된 Microsoft 직원으로 제한됩니다.
- Microsoft 365 정부-GCC High는 미국 공공 부문 고객에 게 필요한 인증 및 승인을 준수 합니다.

Microsoft 365 정부에 대 한 자세한 내용은 자격 요구 사항을 포함 하 여 [Office 365 정부 계획](https://products.office.com/government/compare-office-365-government-plans)에서 미국 정부 고객을 위한 GCC 최고 제공 정보를 확인할 수 있습니다.

[Office 365 US 정부 서비스 설명은](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government) 미국 내에서 모임 준수 요구 사항을 중심으로 하는 플랫폼의 이점을 설명 합니다.

> [!TIP]
> 서비스 설명의 정보 테이블을 Excel 통합 문서에 전송 하 고 **조직 y/n에 관련**된 두 개의 열을 추가 하   고 **조직 y/n의 요구 사항을 충족**해야 할 수 있습니다. 그런 다음 동료와 함께이 목록을 검토 하 여이 서비스가 조직의 요구를 충족 하는지 확인할 수 있습니다.

**의사 결정 사항**:<br/>
- *Microsoft 365 정부 (GCC-고가용성)이 조직에 적합 한지 여부를 결정 합니다.*
- *조직이 자격 요건을 충족 하는지 확인 합니다.*

> [!NOTE]
> Microsoft 365 정부-GCC High는 미국 에서만 사용할 수 있습니다. 미국 이외 지역의 정부 고객은 수많은 [Office 365 정부 계획](https://products.office.com/government/compare-office-365-government-plans)중에서 선택할 수 있습니다.

## <a name="step-2-apply-for-microsoft-365-government--gcc-high"></a>2단계. Microsoft 365 정부에 적용 – GCC-고가용성

이 서비스가 조직에 적합 하다 고 판단 되 면 [이 서비스에 대 한 적용](https://products.office.com/government/eligibility-validation)프로세스를 시작 합니다.
 
## <a name="step-3-understand-microsoft-365-government--gcc-high-default-security-settings"></a>3단계 Microsoft 365 정부-GCC-고가용성 기본 보안 설정 이해

관리 및 보안 설정을 수정 하기 전에 주의 깊게 검토 하 고, 기본 보안 설정을 변경 하기 전에 준수에 미치는 영향을 고려 하는 것이 좋습니다.

**의사 결정**사항: *기본 Microsoft 365 정부-GCC-고급 보안 설정을 수정할지 여부를 결정 하 고 먼저 변경 내용이 미치는 영향을 확인 합니다.*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gcc-highsup1sup"></a>4단계 Microsoft 365 정부에서 기본적으로 현재 사용할 수 없거나 사용 하지 않도록 설정 된 기능 확인-GCC-고가용성<sup>1</sup>

정부 클라우드 고객의 요구 사항을 충족 하기 위해 Microsoft 365 정부-GCC-첨단 및 기업 요금제 간에는 약간의 차이가 있습니다. 사용 가능한 기능을 확인 하려면 다음 표를 참조 하세요.

|                                         | 기능                                         | GCC 높은 상태        |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **정보 보호 & 거 버 넌 스** | 보관                                       | 사용할 수 있음              |
|                                         | 수동 레이블 및 정책<sup>2</sup>          | 사용할 수 있음              |
|                                         | 레이블 자동 응용 프로그램                      | 엔지니어링 백로그 |
|                                         | 중요 한 데이터 형식을 기반으로 하는 레이블            | 엔지니어링 백로그 |
|                                         | 쿼리 기반 레이블 및 관련 정책 | 엔지니어링 백로그 |
|                                         | 파일 플랜                                       | 엔지니어링 백로그 |
|                                         | 권장 정책                            | 엔지니어링 백로그 |
|                                         | 스마트 가져오기 필터                            | 엔지니어링 백로그 |
|                                         | 이벤트 기반 보존                           | 엔지니어링 백로그 |
|                                         | 처리 검토                              | 엔지니어링 백로그 |
|                                         | 정보 장벽                            | 사용할 수 있음              |
|                                         | 파일 및 전자 메일에 대 한 DLP (데이터 손실 방지)  | 사용할 수 있음              |
|                                         | 팀 채팅 및 채널 대화에 대 한 DLP    | 엔지니어링 백로그 |
|                                         | DLP 정확히 일치 하는 데이터                            | 엔지니어링 백로그 |
|                                         | 레이블 활동 탐색기                         | 엔지니어링 백로그 |
|                                         | Trainable 분류자                           | 엔지니어링 백로그 |
|                                         | 통합 레이블 및 민감도 레이블         | 엔지니어링 백로그 |
| **내부자 위험 관리**             | 고급 메시지 암호화                     | 사용할 수 있음              |
|                                         | 내부자 위험 관리                         | 엔지니어링 백로그 |
|                                         | 커뮤니케이션 규정 준수                        | 엔지니어링 백로그 |
|                                         | 고객 Lockbox                                | 사용할 수 있음              |
|                                         | 고객 키                                    | 사용할 수 있음              |
|                                         | 권한이 부여된 액세스 관리                    | 엔지니어링 백로그 |
| **응답 & 검색**                  | 원본 위치 예약                            | 사용할 수 있음              |
|                                         | 사례 관리                                 | 사용할 수 있음              |
|                                         | 검색                                          | 사용할 수 있음              |
|                                         | 내보내기                                          | 사용할 수 있음              |
|                                         | RMS 암호 해독                                  | 사용할 수 있음              |
|                                         | 네이티브 내보내기                                   | 사용할 수 있음              |
|                                         | 고급 처리                             | 사용할 수 있음              |
|                                         | 이메일 스레드                                 | 엔지니어링 백로그 |
|                                         | 중복 확인 근접                   | 엔지니어링 백로그 |
|                                         | 테마                                          | 엔지니어링 백로그 |
|                                         | 예측 코딩                               | 엔지니어링 백로그 |
|                                         | 로드 파일을 사용 하 여 내보내기 처리                 | 엔지니어링 백로그 |
|                                         | 열리면                                         | 엔지니어링 백로그 |
|                                         | 보기 권한자                                         | 엔지니어링 백로그 |
|                                         | Redactions                                      | 엔지니어링 백로그 |
|                                         | 필터링                                       | 엔지니어링 백로그 |
|                                         | Custodian 매핑                   | 엔지니어링 백로그 |
|                                         | Custodian 통신                        | 엔지니어링 백로그 |
|                                         | 집합 검토                                     | 엔지니어링 백로그 |
|                                         | 검토 및 주석 달기                             | 엔지니어링 백로그 |
|                                         | 비 Office 365 수집                        | 엔지니어링 백로그 |
|                                         | 검색 용어 보고서                              | 엔지니어링 백로그 |
| **준수 관리**               | 준수 점수                                | 엔지니어링 백로그 |

<sup>1</sup> 확인 된 상태는 프로젝트 계획 및 우선 순위를 다시 평가 하면서 변경 될 수 있습니다.<br/>
<sup>2</sup> 레이블 수동 응용 프로그램에는 [Aip (Azure Information Protection) 클라이언트 버전 1](https://docs.microsoft.com/azure/information-protection/rms-client/client-version-release-history)이 필요 합니다. 


**의사 결정**사항: *규정 준수 기능이 조직의 요구 사항을 충족 하는지 여부를 결정 합니다.*
