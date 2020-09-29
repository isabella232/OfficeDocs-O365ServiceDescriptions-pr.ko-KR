---
title: Microsoft 365 규정 준수 - GCC 계획
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 이 지침은 Microsoft 365 정부-GCC 사용이 이러한 요구 사항을 충족 하는 데 적합 한 미국 연방, 주, 로컬, 부족 또는 territorial 정부 기관 또는 기타 기관에서 Office 365의 배포를 추진 하는 IT 전문가를 위한 것입니다.
ms.openlocfilehash: 564c8c55b1659d80ffa18802e623634088740ba5
ms.sourcegitcommit: e342174df76128430dfc8c971716da5c4b2942ac
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/28/2020
ms.locfileid: "48293874"
---
# <a name="plan-for-microsoft-365-compliance--gcc"></a>Microsoft 365 준수 계획 – GCC

이 지침은 Microsoft 365 정부-GCC 사용이 이러한 요구 사항을 충족 하는 데 적합 한 미국 연방, 주, 로컬, 부족 또는 territorial 정부 기관 또는 기타 기관에서 Office 365의 배포를 추진 하는 IT 전문가를 위한 것입니다.

> [!NOTE]
> 조직이 Microsoft 365 정부 및 GCC 자격 요건을 이미 충족 하 여 해당 프로그램에 적용 되 고 수용 된 경우 1-2 단계를 건너뛰고 3 단계로 바로 이동할 수 있습니다.

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---gcc-and-meets-eligibility-requirements"></a>1단계. 조직에 Microsoft 365 정부-GCC가 필요 하며 자격 요구 사항을 충족 하는지 확인

Microsoft 365 정부-GCC 환경은 FedRAMP 중간을 포함 하 여 클라우드 서비스에 대 한 미국 정부 요구 사항을 준수 하 고, 범죄 사전 및 연방 세금 정보 시스템 (CJI 및 FTI 데이터 형식)에 대 한 요구 사항을 충족 합니다.

Office 365의 기능과 기능을 함께 사용 하는 것 외에도, 조직은 Microsoft 365 정부-GCC에 고유한 다음과 같은 기능을 활용할 수 있습니다.

- 조직의 고객 콘텐츠는 Microsoft의 상용 Office 365 서비스에 있는 고객 콘텐츠와 논리적으로 분리 됩니다.

- 조직의 고객 콘텐츠는 미국에 보관됩니다.

- 조직 고객 콘텐츠에 대한 액세스는 선별된 Microsoft 직원으로 제한됩니다.

- Microsoft 365 정부-GCC는 미국 공공 부문 고객에 게 필요한 인증 및 승인을 준수 합니다.

내게 필요한 옵션을 포함 하 여 [Office 365 정부 계획](https://products.office.com/government/compare-office-365-government-plans)에서 미국 정부 고객을 위한 Microsoft 365 정부-GCC 제품에 대 한 자세한 정보를 확인할 수 있습니다.

[Office 365 US 정부 서비스 설명은](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government) 미국 내에서 모임 준수 요구 사항을 중심으로 하는 플랫폼의 이점을 설명 합니다.

> [!TIP]
> 서비스 설명의 정보 테이블을 Excel 통합 문서에 전송 하 고 **조직 y/n에 관련**된 두 개의 열을 추가 하   고 **조직 y/n의 요구 사항을 충족**해야 할 수 있습니다. 그런 다음 동료와 함께이 목록을 검토 하 여이 서비스가 조직의 요구를 충족 하는지 확인할 수 있습니다.

> [!NOTE]
> Microsoft 365 정부-GCC는 미국 에서만 제공 됩니다. 미국 이외 지역의 정부 고객은 수많은 [Office 365 정부 계획](https://products.office.com/government/compare-office-365-government-plans)중에서 선택할 수 있습니다.

**의사 결정 사항**: <br/>
- *Microsoft 365 정부-GCC가 조직에 적합 한지 여부를 결정 합니다.*
- *조직이 자격 요건을 충족 하는지 확인 합니다.*

## <a name="step-2-apply-for-microsoft-365-government---gcc"></a>2단계. Microsoft 365 정부에 적용 합니다-GCC

이 서비스가 조직에 적합 하다 고 판단 되 면 [이 서비스에 대 한 적용](https://products.office.com/government/eligibility-validation)프로세스를 시작 합니다.

## <a name="step-3-understand-microsoft-365-government---gcc-default-security-settings"></a>3단계. Microsoft 365 정부-GCC 기본 보안 설정 이해

관리 및 보안 설정을 수정 하기 전에 주의 깊게 검토 하 고, 기본 보안 설정을 변경 하기 전에 준수에 미치는 영향을 고려 하는 것이 좋습니다.

**의사 결정**사항: *기본 Microsoft 365 정부 보안 설정을 수정할 지 여부를 결정 하 고 먼저 변경 내용의 영향을 확인 합니다.*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gccsup1sup"></a>4단계. Microsoft 365 정부-GCC<sup>1</sup> 에서 현재 어떤 기능을 사용할 수 없거나 기본적으로 사용 하지 않도록 설정 되어 있는지 이해 합니다.

정부 클라우드 고객의 요구 사항을 충족 하기 위해 Microsoft 365 정부-GCC와 기업 계획 간에는 약간의 차이가 있습니다. 사용 가능한 기능을 확인 하려면 다음 표를 참조 하세요.<br><br>

| 영역 | 기능 | GCC 상태 |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **정보 보호**              | 통합 레이블 및 민감도 레이블         | 사용할 수 있음              |
|                                         | Sharepoint Online, Office 그룹의 컨테이너 레이블          | 배포 중              |
|                                         | Excel Online, SharePoint Online, 비즈니스용 OneDrive에 대 한 중요 한 데이터 형식을 기반으로 하는 자동 레이블 지정                      | 배포 중              |
|                                         | Win32 및 Mac Office 클라이언트에 대 한 중요 한 데이터 형식을 기반으로 하는 레이블            | 엔지니어링 백로그 |
|                                         | Win 32, Mac에 대 한 중요 한 데이터 형식을 기반으로 하는 자동 레이블 |  엔지니어링 백로그              |
|                                         | 팀에 대 한 중요 한 데이터 형식을 기반으로 하는 자동 레이블 지정                                       |엔지니어링 백로그              |
|                                         | 중요 한 데이터 형식을 기반으로 하는 모바일에 대 한 자동 레이블 지정                            |엔지니어링 백로그 |
|                                         | 쿼리 기반 레이블 및 관련 정책                            | 사용할 수 있음 |
|                                         | 레이블 활동 탐색기                           | 엔지니어링 백로그  |
|                                         | 교육 가능한 분류자                              | 엔지니어링 백로그              |
|                                         | 기본 Office 365 메시지 암호화 (E3)                            | 사용할 수 있음              |
|                                         | 고급 Office 365 메시지 암호화 (E5)  | 사용할 수 있음              |
|                                         | Office 365에 대한 고객 키    | 사용할 수 있음 |
|                                         | 사용자가 관리 하는 키 프로 비전 수명 주기에 대해 사용자 키 (BYOK) 가져오기                            | 사용할 수 있음 |
|                                         | 높은 규제 대상 시나리오 (미리 보기)에 대 한 Azure Information Protection 및 AD (Active Directory) 권한 관리 범위를 적용 하는 자체 키 (HYOK)를 포함 합니다.                         | 사용할 수 있음 |
|                                         | 이중 키 암호화                           | 엔지니어링 백로그 |
|                                         | 파일 및 전자 메일에 대 한 DLP (데이터 손실 방지)         | 사용할 수 있음 |
|                                         | 팀 채팅 및 채널 대화에 대 한 DLP         | 배포 중 |
|                                         | DLP 정확히 일치 하는 데이터 | 엔지니어링 백로그 |
|                                         | DLP 끝점 | 엔지니어링 백로그 |
| **정보 거 버 넌 스** | 전자 메일 보관                                       | 사용할 수 있음              |
|                                         | 보존 잠금          | 사용할 수 있음              |
|                                         | PST 가져오기                      | 사용할 수 있음              |
|                                         | 수동 비 레코드 보존 레이블            | 사용할 수 있음 |
|                                         | SharePoint/비즈니스용 OneDrive 라이브러리, 폴더 및 문서 집합에 대 한 기본 보존 레이블 Exchange 받은 편지함; 및 Office 365 그룹 | 사용할 수 있음              |
|                                         | 전체 조직에 대 한 보존 정책 특정 위치 또는 사용자 특정 조건 (예: 키워드 또는 중요 한 정보)에 따라 자동으로                                       | 사용할 수 있음              |
|                                         | Trainable 분류자가 있는 보존 정책                            | 엔지니어링 백로그 |
|                                         | Yammer 및 팀에 대 한 보존 정책                            | 엔지니어링 백로그 |
|                                         | 수동 레코드 레이블                           | 사용할 수 있음              |
|                                         | SharePoint, 비즈니스용 OneDrive 라이브러리, 폴더 및 문서 집합에 대 한 기본 레코드 레이블 및 Office 365 그룹                              | 사용할 수 있음              |
|                                         | 특정 조건 (예: 키워드 또는 중요 한 정보)을 기반으로 하는 자동 레코드 정책 이벤트를 기반으로 합니다.                            | 사용할 수 있음              |
|                                         | 처리 검토  | 사용할 수 있음              |
|                                         | 파일 플랜 관리자    | 사용할 수 있음 |
|                                         | 폐기 증거                            | 사용할 수 있음 |
|                                         | 규정 레코드                         | 엔지니어링 백로그 |
|                                         | 레코드 관리 라이선스 적용                           | 엔지니어링 백로그 |
|                                         | 레코드 관리 다중 단계 처리 검토 | 엔지니어링 백로그 |
|                                         | 레이블 활동 탐색기 | 엔지니어링 백로그 |
|                                         | 교육 가능한 분류자 | 엔지니어링 백로그 |
|                                         | 통합 레이블 및 민감도 레이블         | 엔지니어링 백로그 |
| **참가자 위험 관리**             | 고객 Lockbox                                | 사용할 수 있음            |
|                                         | 팀, SharePoint 사이트, 전자 메일 메시지에 대 한 Office 지표                         | 배포 중 |
|                                         | Departing 사용자의 데이터 도난                        | 배포 중 |
|                                         | 일반 데이터 누수                                | 배포 중              |
|                                         | 참가자 위험 관리 알림 조사                                   | 배포 중              
|                                         | 참가자 위험 관리 사례 대시보드, 콘텐츠 탐색기 및 알림 서식 파일 | 배포 중 |
|                                         | Advanced eDiscovery에 대 한 조사 확대 | 배포 중|
|                                         | 우선 순위 사용자의 데이터 누수 (미리 보기) | 엔지니어링 백로그 |
|                                         | 불만 사용자의 데이터 유출 (미리 보기) | 엔지니어링 백로그 |
|                                         | 일반 보안 정책 위반 (미리 보기) | 엔지니어링 백로그 |
|                                         | 우선 순위 사용자에의 한 보안 정책 위반, departing 사용자, 불만 사용자 (미리 보기) | 엔지니어링 백로그 |
|                                         | 정책 사용자 지정 (미리 보기) | 엔지니어링 백로그 |
|                                         | 알림 내보내기 (미리 보기) | 엔지니어링 백로그 |
|                                         | 우선 순위 사용자 그룹 (미리 보기) | 엔지니어링 백로그 |
|                                         | 고객 정책 만들기, 통신 준수를 위해 미리 구성 된 3 incl (감독 정책)  | 배포 중 |
|                                         | 팀, Exchange 및 팀 제거 메시지에 대 한 통신 준수 (incl (감독 정책) 지원 | 배포 중 |
|                                         | 통신 준수 (incl 정책) 액세스 경고 참고 서식 파일 통신 정책 대시보드 | 배포 중  |
|                                         | Advanced eDiscovery에 대 한 통신 준수 (incl 정책) 확대 조사 | 배포 중 |
|                                         | 통신 준수 (incl-감독 정책) 성인 콘텐츠 검색 | 배포 중 |
|                                         | 정보 장벽 | 엔지니어링 백로그 |
|                                         | 권한이 부여된 액세스 관리                    | 엔지니어링 백로그 |
| **응답 & 검색**                  | 코어 eDiscovery: 원본 위치 유지                            | 사용할 수 있음              |
|                                         | 코어 eDiscovery: 사례 관리                                 | 사용할 수 있음              |
|                                         | 코어 eDiscovery: 검색                                          | 사용할 수 있음              |
|                                         | 코어 eDiscovery: 내보내기                                          | 사용할 수 있음              |
|                                         | 코어 eDiscovery: RMS 암호 해독                                  | 사용할 수 있음              |
|                                         | 코어 eDiscovery: 네이티브 내보내기                                   | 사용할 수 있음              |
|                                         | 코어 eDiscovery: 감사                                        | 사용할 수 있음              |
|                                         | 고급 eDiscovery: 고급 처리                             | 사용할 수 있음 |
|                                         | 고급 eDiscovery: 전자 메일 스레딩                                 | 사용할 수 있음 |
|                                         | 고급 eDiscovery: 근접 중복 식별                   | 사용할 수 있음 |
|                                         | 고급 eDiscovery: 테마                                          | 사용할 수 있음 |
|                                         | 고급 eDiscovery: 예측 코딩                               | 사용할 수 있음 |
|                                         | 고급 eDiscovery: 로드 파일을 사용 하 여 내보내기 처리                 | 사용할 수 있음 |
|                                         | 고급 eDiscovery: 태그 지정                                         | 사용할 수 있음 |
|                                         | 고급 eDiscovery: 뷰어                                         | 사용할 수 있음 |
|                                         | Advanced eDiscovery: Redactions                                      | 사용할 수 있음 |
|                                         | 고급 eDiscovery: 필터링                                       | 사용할 수 있음 |
|                                         | 고급 eDiscovery: Custodian-작업에 대 한 매핑                   | 사용할 수 있음 |
|                                         | Advanced eDiscovery: Custodian 통신                        | 사용할 수 있음 |
|                                         | Advanced eDiscovery: 검토 집합                                     | 사용할 수 있음 |
|                                         | 고급 eDiscovery: 검토 및 주석 달기                             | 사용할 수 있음 |
|                                         | 고급 eDiscovery: 비 Office 365 수집                        | 사용할 수 있음 |
|                                         | Advanced eDiscovery: 용어 검색 보고서                              | 사용할 수 있음 |
|                                         | 기본 감사                              | 사용할 수 있음 |
|                                         | 고급 감사: 중요 한 이벤트에 대 한 액세스 (예: 액세스 한 mail항목)                              | 배포 중 |
|                                         | 고급 감사 로그 보존 (1 년)                               | 배포 중 |
|                                         | 고급 감사 향상 된 대역폭을 관리 활동 API로 강화                              | 배포 중 |
|    **준수 관리**            | 준수 관리자 및 점수                              | 엔지니어링 백로그 |




<sup>1</sup> 확인 된 상태는 프로젝트 계획 및 우선 순위를 다시 평가 하면서 변경 될 수 있습니다.<br/>
<sup>2</sup> 레이블 수동 응용 프로그램에는 [Aip (Azure Information Protection) 클라이언트 버전 1](https://docs.microsoft.com/azure/information-protection/rms-client/client-version-release-history)이 필요 합니다.


**의사 결정**사항: *규정 준수 기능이 조직의 요구 사항을 충족 하는지 여부를 결정 합니다.*
