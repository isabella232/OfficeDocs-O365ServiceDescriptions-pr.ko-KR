---
title: Microsoft 365 규정 준수 - DoD 배포 계획
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 이 지침은 미국 연방 정부 기관 이나 정부 규정 및 요구 사항의 적용을 받는 데이터를 처리 하는 다른 기관에서 Office 365 배포를 구동 하는 IT 프로에 대 한, Microsoft 365 정부의 사용 –DoD의 사용 이 요구 사항을 충족 하는 것이 적절 한.
ms.openlocfilehash: bc6d69c32db6801763e47984c0513da9c16ba0f8
ms.sourcegitcommit: adcacf68ac75c4db2229ebf55be9c75aecd3070b
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52546005"
---
# <a name="plan-for-microsoft-365-compliance---dod-deployments"></a>Microsoft 365 규정 준수 - DoD 배포 계획

이 지침은 미국 연방 정부 기관 이나 정부 규정 및 요구 사항의 적용을 받는 데이터를 처리 하는 다른 기관에서 Office 365 배포를 구동 하는 IT 프로에 대 한, Microsoft 365 정부의 사용 –DoD의 사용 이 요구 사항을 충족 하는 것이 적절 한.

> [!NOTE]
> 조직이 이미 Microsoft 365 정부- DoD 자격 요건을 충족하고 프로그램에 적용및 수락된 경우 1단계와 2단계를 건너뛰고 3단계로 직접 이동하여 신청할 수 있습니다.

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---dod-and-meets-eligibility-requirements"></a>1단계. 조직이 정부 - DoD Microsoft 365 요구 사항을 필요로 하는지 확인하고 자격 요건을 충족합니다.

Microsoft 365 정부 - DoD 환경은 클라우드 서비스에 대한 미국 정부의 요구 사항을 준수합니다.

Office 365 기능과 기능을 즐기는 것 외에도 조직은 정부 - DoD Microsoft 365 고유의 다음과 같은 기능의 혜택을 누릴 수 있습니다.

- 조직의 고객 콘텐츠는 Microsoft의 상용 Office 365 서비스의 고객 콘텐츠와 논리적으로 분리됩니다.
- 조직의 고객 콘텐츠는 미국에 보관됩니다.
- 조직 고객 콘텐츠에 대한 액세스는 선별된 Microsoft 직원으로 제한됩니다.
- Microsoft 365 정부 - DoD는 미국 공공 부문 고객에게 필요한 인증 및 인증을 준수합니다.

자격 요건을 포함하여 [Office 365 Government 계획에서](https://products.office.com/government/compare-office-365-government-plans)미국 정부 고객을 위한 doD 제공 - Microsoft 365 정부에 대한 자세한 정보를 찾을 수 있습니다.

[Office 365 미국 정부 서비스 설명은](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md) 미국 내 규정 준수 요구 사항을 충족하는 데 중점을 두고 있는 플랫폼의 이점을 설명합니다.

> [!TIP]
> 서비스 설명의 정보 테이블을 Excel 통합문서로 전송하고 두 개의 **열(조직 Y/N에 대한 관련성** 및 조직의 **Y/N)의 요구 사항을 충족하는** 두 개의 열을 추가할 수 있습니다. 그런 다음 동료와 함께 이 목록을 검토하여 이 서비스가 조직의 요구 사항을 충족하는지 확인할 수 있습니다.

**결정 사항**:<br/>
- *정부 Microsoft 365 결정 - DoD가 조직에 적합한지 여부를 결정합니다.*
- *조직이 자격 요건을 충족하는지 확인합니다.*

> [!NOTE]
> Microsoft 365 정부 - DoD는 미국에서만 사용할 수 있습니다. 미국 이외의 정부 고객은 [다양한 Office 365 Government 계획](https://products.office.com/government/compare-office-365-government-plans)중에서 선택할 수 있습니다.

## <a name="step-2-apply-for-microsoft-365-government---dod"></a>2단계. Microsoft 365 정부 신청 - DoD

이 서비스가 조직에 적합한지 결정한 후 이 [서비스를 신청하는 프로세스를](https://products.office.com/government/eligibility-validation)시작합니다.

## <a name="step-3-understand-microsoft-365-government---dod-default-security-settings"></a>3단계. 정부 Microsoft 365 이해 - DoD 기본 보안 설정

관리자 설정을 수정하기 전에 관리자 및 보안 설정을 주의 깊게 검토하고 기본 보안 설정을 변경하기 전에 규정 준수에 미치는 영향을 고려하는 것이 좋습니다.

**결정 지점**: *기본 Microsoft 365 정부 - DoD 보안 설정을 수정할지 여부를 결정하고 변경 내용의 영향을 먼저 이해하도록 해결합니다.*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--dodsup1sup"></a>4단계. 정부 Microsoft 365에서 기본적으로 사용할 수 없거나 비활성화되지 않는 기능을 이해합니다 - doD<sup>1</sup>

정부 클라우드 고객의 요구 사항을 충족하기 위해 정부 Microsoft 365 -DoD와 엔터프라이즈 계획 사이에는 몇 가지 차이점이 있습니다. 다음 표를 참조하여 사용할 수 있는 기능을 확인합니다. Microsoft 365 로드맵에 게시된 최신 규정 준수 제품 업데이트는 [여기를](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) 참조하십시오.<br><br>

| 영역 | 기능 | DoD 상태 |
|------|---------|------------|
| **정보 보호** | 통합 라벨링 클라이언트 및 스캐너 | 사용할 수 있음 |
| | 정확한 데이터 일치 | 사용할 수 있음 |
| | Exchange Online, SharePoint 온라인 및 비즈니스용 OneDrive 대한 자동 분류 및 라벨링 | 배포 중 |
| | 플랫폼(웹, Windows 및 Mac)에서 Office 앱(Word, Excel, PowerPoint, Outlook)에 대한 자동 분류 및 라벨링 | 사용할 수 있음 |
| | Office 클라이언트를 위한 자동 분류 및 라벨링 - 모바일 | 엔지니어링 백로그에 |
| | Teams, Microsoft 365 그룹 및 SharePoint 사이트에 대한 자동 분류 및 라벨링 | 사용할 수 있음 |
| | 필수 라벨링 | 사용할 수 있음 |
| | Office 앱(iOS, Android, Windows)에서 수동 감도 라벨링 | 사용할 수 있음 |
| | Outlook 메시지에 대한 암호화 전용 보호를 위한 감도 레이블 구성 | 배포 중 |
| **분석** | 데이터 분류: 개요 및 콘텐츠 탐색기 | 배포 중 |
| | 분석: 서비스 측에 자동 라벨이 부착된 기계 학습 분류기 | 개발 중 |
| | 분석: Office 앱/클라이언트 측에 자동 라벨이 부착된 기계 학습 분류기 | 배포 중 |
| **Encryption** | 기본 Office 365 메시지 암호화 (E3) | 사용할 수 있음 |
| | 고급 Office 365 메시지 암호화 (E5) | 사용할 수 있음 |
| | 고객이 관리하는 주요 프로비저닝 수명 주기를 위해 자신의 키(BYOK)를 가져오기 | 사용할 수 있음 |
| | Office 365에 대한 고객 키 | 사용할 수 있음 |
| | 이중 키 암호화 | 사용할 수 있음 |
| **데이터 손실 방지** | 파일 및 이메일에 대한 DLP(데이터 손실 방지) | 사용할 수 있음 |
| | 채팅 및 채널 대화 Teams 위한 DLP | 사용할 수 있음 |
| | DLP: 경고 대시보드 | 배포 중 |
| | DLP 엔드포인트 | 개발 중 |
| | DLP 온 프렘 | 엔지니어링 백로그에 |
| | DLP 개요 페이지 | 개발 중 |
| **정보 거버넌스** | 정보 거버넌스: 이메일 보관 | 사용할 수 있음 |
| | 정보 거버넌스: 보존 잠금 | 사용할 수 있음 |
| | 정보 거버넌스: 가져오기 PST | 사용할 수 있음 |
| | 정보 거버넌스: 레코드가 아닌 보존 레이블을 수동으로 적용 | 사용할 수 있음 |
| | 정보 거버넌스: SharePoint/비즈니스용 OneDrive 라이브러리, 폴더 및 문서 집합에 기본 보존 레이블을 적용합니다. 받은 편지함 Exchange; 및 Office 365 그룹 | 사용할 수 있음 |
| | 정보 거버넌스: 단일 기본 보존 레이블을 전체 조직에 적용합니다. 특정 위치 또는 사용자; 특정 조건(예: 키워드 또는 중요한 정보)을 기반으로 자동으로 | 사용할 수 있음 |
| | 정보 거버넌스: Exchange 받은 편지함에 기본 레이블 적용 | 사용할 수 있음 |
| | 정보 거버넌스: 다단계 처분 검토 | 엔지니어링 백로그에 |
| | 정보 거버넌스: 학습 가능한 분류자가 있는 보존 정책 | 개발 중 |
| | 정보 거버넌스: 채팅Teams 보존 정책 | 배포 중 |
| | 정보 거버넌스: Teams 회의 기록을 위한 보존 정책 | 사용할 수 있음 |
| | 정보 거버넌스: 개인 채널 메시지에 대한 보존 정책 Teams | 엔지니어링 백로그에 |
| | 정보 거버넌스: 정책 적응 범위 의 보존 및 라벨링 | 개발 중 |
| | 기록 관리: 레코드 레이블을 수동으로 적용 | 사용할 수 있음 |
| | 레코드 관리: SharePoint, 비즈니스용 OneDrive 라이브러리, 폴더 및 문서 집합에 대한 기본 레코드 레이블을 적용합니다. Office 365 그룹 | 사용할 수 있음 |
| | 레코드 관리: 특정 조건(예: 키워드 또는 중요한 정보)을 기반으로 하는 자동 레코드 정책 이벤트 및 이벤트 기반 | 사용할 수 있음 |
| | 기록 관리: 처분 검토 | 사용할 수 있음 |
| | 레코드 관리: 파일 계획 관리자 | 사용할 수 있음 |
| | 기록 관리: 처분 증명 | 사용할 수 있음 |
| | 레코드 관리: 레코드 버전 | 사용할 수 있음 |
| | 기록 관리: 규제 기록 | 사용할 수 있음 |
| | 레코드 관리: SharePoint Syntex 분류를 사용하여 레코드 레이블을 적용합니다. | 엔지니어링 백로그에 |
| **내부자 위험 관리** | 고객 Lockbox | 사용할 수 있음 |
| | 내부자 위험 관리: 사례 대시보드, 콘텐츠 탐색기 및 알림 템플릿 | 배포 중 |
| | 내부자 위험 관리: Advanced eDiscovery 대한 조사를 위해 에스컬레이션 | 배포 중 |
| | 내부자 위험 관리: 사용자를 출발하여 데이터 도난 | 배포 중 |
| | 내부자 위험 관리: 일반 데이터 유출 | 배포 중 |
| | 내부자 위험 관리: 내부자 위험 관리 경고 조사 | 배포 중 |
| | 내부자 위험 관리: Teams, SharePoint 사이트, 이메일 메시징에 대한 Office 지표 | 배포 중 |
| | 내부자 위험 관리 활동 탐색기 | 엔지니어링 백로그에 |
| | 내부자 위험 관리: 빌드 1809 이상 Windows 10 활동을 위한 장치 표시기 | 엔지니어링 백로그에 |
| | 내부자 위험 관리: 엔드포인트 경고에 대 한 마이크로소프트 수비수에 대 한 지표 | 엔지니어링 백로그에 |
| | 내부자 위험 관리: 보안 정책 위반에 대한 지표 | 엔지니어링 백로그에 |
| | 내부자 위험 관리: 불만을 품은 사용자가 데이터 유출을 위한 정책 템플릿 | 엔지니어링 백로그에 |
| | 내부자 위험 관리: 우선 순위 사용자에 의한 데이터 유출에 대한 정책 템플릿 | 엔지니어링 백로그에 |
| | 내부자 위험 관리: 일반 보안 정책 위반에 대한 정책 템플릿 | 엔지니어링 백로그에 |
| | 내부자 위험 관리: 우선 순위 사용자에 의한 보안 정책 위반에 대한 정책 템플릿, 사용자를 출발, 불만을 품은 사용자(미리 보기) | 엔지니어링 백로그에 |
| | 내부자 위험 관리: 정책 사용자 지정 | 엔지니어링 백로그에 |
| | 내부자 위험 관리: 내보내기 경고 | 엔지니어링 백로그에 |
| | 내부자 위험 관리: Microsoft Teams 통합 | 엔지니어링 백로그에 |
| | 내부자 위험 관리: 우선 순위 사용자 그룹 | 엔지니어링 백로그에 |
| | 통신 규정 준수: 고객 정책 수립, 미리 구성된 3가지 | 사용할 수 있음 |
| | 통신 규정 준수: Teams, Exchange 지원, Teams 메시지 제거 | 사용할 수 있음 |
| | 통신 규정 준수: 액세스 경고; 알림 템플릿; 통신 정책 대시보드 | 사용할 수 있음 |
| | 통신 규정 준수: Advanced eDiscovery 대한 조사 확대 | 사용할 수 있음 |
| | 통신 규정 준수: 시간이 지남에 따라 반복 행동 강령 위반 감지 | 사용할 수 있음 |
| | 통신 규정 준수: 보다 세분화된 권한 지원 | 사용할 수 있음 |
| | 통신 규정 준수: 온라인 사서함을 사용하여 사용자의 채팅 데이터를 Teams 분석 | 사용할 수 있음 |
| | 통신 규정 준수: 이해 상충 템플릿 | 사용할 수 있음 |
| | 통신 규정 준수: 이메일 서명 또는 면책 조항을 무시할 수 있는 기능 | 개발 중 |
| | 통신 규정 준수: 통신 규정 준수 정책에 대한 보존 기간을 설정할 수 있습니다. | 엔지니어링 백로그에 |
| | 통신 규정 준수: 성인 콘텐츠 감지 | 엔지니어링 백로그에 |
| | 통신 규정 준수: 내부자 위험 관리 핸드오프 | 개발 중 |
| | 통신 규정 준수: 정책 상태 확인 및 정책 일시 중지 기능 | 개발 중 |
| | 통신 규정 준수: 위협, 표적 괴롭힘 및 욕설 분류자에 대한 7개 언어 지원 | 개발 중 |
| | 통신 규정 준수: 조사 중 건강 콘텐츠 번역 | 개발 중 |
| | 정보 장벽 | 배포 중 |
| | 권한이 부여된 액세스 관리 | 엔지니어링 백로그에 |
| **& 대응 알아보기** | 코어 e디스커버리: 인플레이스 보존 | 사용할 수 있음 |
| | 핵심 e디스커버리: 사례 관리 | 사용할 수 있음 |
| | 코어 e디스커버리: 검색 | 사용할 수 있음 |
| | 코어 e디스커버리: 내보내기 | 사용할 수 있음 |
| | 코어 전자 디스커버리: RMS 암호 해독 | 사용할 수 있음 |
| | 코어 e디스커버리: 네이티브 내보내기 | 사용할 수 있음 |
| | 핵심 e디스커버리: 감사 | 사용할 수 있음 |
| | 핵심 e디스커버리: 비즈니스용 OneDrive 위한 규정 준수 경계 | 배포 중 |
| | Advanced eDiscovery: 고급 처리 | 사용할 수 있음 |
| | Advanced eDiscovery: CJK/더블 바이트 Advanced eDiscovery 지원 | 사용할 수 있음 |
| | Advanced eDiscovery: 워크로드 매핑에 대한 관리자 | 사용할 수 있음 |
| | Advanced eDiscovery: 관리인 커뮤니케이션 | 사용할 수 있음 |
| | Advanced eDiscovery: 대시보드 | 사용할 수 있음 |
| | Advanced eDiscovery: 이메일 스레딩 | 사용할 수 있음 |
| | Advanced eDiscovery: 내보내기(다운로드, 내보내기, 다른 검토 세트에 추가) | 사용할 수 있음 |
| | Advanced eDiscovery: 필터링 | 사용할 수 있음 |
| | Advanced eDiscovery: 중복 식별 에 가까운 | 사용할 수 있음 |
| | Advanced eDiscovery: 예측 코딩 | 사용할 수 있음 |
| | Advanced eDiscovery: 로드 파일로 처리된 내보내기 | 사용할 수 있음 |
| | Advanced eDiscovery: 수정 | 사용할 수 있음 |
| | Advanced eDiscovery: 세트 검토 | 사용할 수 있음 |
| | Advanced eDiscovery: 검토 및 인가 | 사용할 수 있음 |
| | Advanced eDiscovery: 검색 기간 보고서 | 사용할 수 있음 |
| | Advanced eDiscovery: OneDrive 및 SharePoint 온라인(최신 첨부 파일)의 연결된 콘텐츠 지원 | 사용할 수 있음 |
| | Advanced eDiscovery: 태그 지정 | 사용할 수 있음 |
| | Advanced eDiscovery: Teams 반응 지원 | 사용할 수 있음 |
| | Advanced eDiscovery: 테넌트 보고서 | 사용할 수 있음 |
| | Advanced eDiscovery: 테마 | 사용할 수 있음 |
| | Advanced eDiscovery: 시청자 | 사용할 수 있음 |
| | Advanced eDiscovery: 마이크로소프트 컴플라이언스 센터의 Yammer Advanced eDiscovery | 사용할 수 있음 |
| | Advanced eDiscovery: 최적화 보류 | 개발 중 |
| | Advanced eDiscovery: Microsoft 규정 준수 센터는 SharePoint, 비즈니스용 OneDrive, 코어의 휴지통 및 Advanced eDiscovery 항목을 검색하고 내보내기위한 지원을 확대했습니다. | 개발 중 |
| | Advanced eDiscovery: Teams 개인 채널 메시지에 대한 법적 보류 | 개발 중 |
| | Advanced eDiscovery: 새로운 예측 코딩 모듈 | 개발 중 |
| | Advanced eDiscovery: 비Office 365 섭취 | 엔지니어링 백로그에 |
| | Advanced eDiscovery: 테넌트 보고서 | 개발 중 |
| | 기본 감사 | 사용할 수 있음 |
| | 고급 감사: 중요한 이벤트에 대한 액세스(예: 메일 항목에 액세스) | 사용할 수 있음 |
| | 고급 감사: 관리 활동 API에 대한 대역폭 증가 | 사용할 수 있음 |
| | 고급 감사: 로그 보존 (1년) | 사용할 수 있음 |
| | 고급 감사: 메일 전달 및 메일 보내기 이벤트 | 사용할 수 있음 |
| | 고급 감사: 보안 및 규정 준수 센터 가용성 | 사용할 수 있음 |
| | 고급 감사: 감사 로그에 대한 장기 보존(10년) | 개발 중 |
| | 고급 감사: Exchange Online 및 SharePoint 온라인검색 기간 이벤트 | 엔지니어링 백로그에 |
| **준수 관리** | Microsoft 365 보안 및 규정 준수 센터 | 사용할 수 있음 |
| | Microsoft Cloud App Security | 개발 중 |
| | 규정 관리자 | 사용할 수 있음 |
| | 이중 바이트 문자 지원 | 사용할 수 있음 |
| **생태계** | 일자 데이터 커넥터: HR | 사용할 수 있음 |
| | 일자 데이터 커넥터: 인스턴트 블룸버그, 블룸버그 메일, 링크드 인 비즈니스 페이지, ICE 채팅 | 엔지니어링 백로그에 |
| | 타사 데이터 커넥터 | 엔지니어링 백로그에 |
| | Graph Advanced eDiscovery 위한 API | 개발 중 |
| | Graph Teams 내보내기 데이터에 대한 API | 엔지니어링 백로그에 |

<sup>1</sup> 식별된 상태는 프로젝트 계획 및 우선 순위가 재평가됨에 따라 변경될 수 있습니다.<br/>

**결정 지점**: *규정 준수 기능이 조직의 요구 사항을 충족하는지 여부를 결정합니다.*
