---
title: 미국 정부 환경용 SharePoint
ms.author: mkashman
author: kaarins
manager: mkashman
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 미국 정부 클라우드 고객을 위한 SharePoint 기능 가용성에 대해 알아봅니다.
ms.openlocfilehash: 4e09ec8fda62fb5ce7a6e886799c5f35edd32cf5
ms.sourcegitcommit: e342174df76128430dfc8c971716da5c4b2942ac
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/28/2020
ms.locfileid: "48294194"
---
# <a name="sharepoint-for-us-government-environments"></a>미국 정부 환경용 SharePoint

이 문서에서는 [SharePoint 서비스 설명](/office365/servicedescriptions/sharepoint-online-service-description/sharepoint-online-service-description)에 나와 있는 대로 US 정부 클라우드와 상업용 클라우드 간의 기능 차이에 대 한 개요를 제공 합니다. SharePoint는 GCC (정부 커뮤니티 클라우드), GCC High 및 DoD 환경에 사용할 수 있습니다. 

자격 및 구매를 비롯 한 정부 클라우드에 대 한 자세한 내용은 [Microsoft 365 정부-구매 방법](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy)를 참조 하세요. Office 365 정부 요금제를 비교 하려면 [office 365 정부 요금제](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements)를 참조 하세요.

네트워크 연결을 관리할 때 필요한 끝점에 대 한 자세한 내용은 [office 365 미국 정부 GCC High endpoints](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) 또는 [Office 365 미국 정부 DoD endpoints](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business)를 참조 하세요.

조직에서는 Office 365의 기능을 사용할 수 있을 뿐만 아니라 미국 정부 클라우드 환경에 고유한 다음과 같은 기능을 사용할 수 있습니다.

-   조직의 고객 콘텐츠는 Microsoft의 상용 Office 365 서비스에 있는 고객 콘텐츠와 논리적으로 분리 됩니다.
-   조직의 고객 콘텐츠는 미국에 보관됩니다.
-   조직 고객 콘텐츠에 대한 액세스는 선별된 Microsoft 직원으로 제한됩니다.
-   정부 클라우드 환경은 미국 공공 부문 고객에 게 필요한 인증 및 승인을 준수 합니다.

모든 SharePoint 상업용 기능과 기능을 정부 클라우드 환경에 제공 하는 것은 우리의 목표입니다. 일부 기능은 정부 클라우드 고객의 요구 사항으로 인해 사용할 수 없습니다. 다른 기능은 정부 환경에 제공 되지만 아직 사용할 수 없습니다. 정부 클라우드 환경에서의 기능 가용성에 대 한 자세한 내용은 다음 섹션을 참조 하십시오.

## <a name="developer-features"></a>개발자 기능

상업용 고객 및 정부 클라우드 고객용 개발자 기능 간에는 알려진 차이점이 없습니다.

- 추가 기능에 대 한 데이터 원본과 같은 외부 응용 프로그램에 대 한 연결은 정부 환경에서 지원 되는 시스템 보안 경계 내에 있는 원본으로 제한 됩니다.
- BCS (Business Connectivity Services) 기능은 클라우드 서비스에 대 한 보안 경계 내에서 데이터 원본을 계속 사용할 수 있는 연결 시나리오에서 지원 됩니다.

사이트에서 타사 응용 프로그램을 사용 하는 경우 조직에서 이러한 서비스의 적절 한 사용을 평가할 때 타사에서 제공 하는 개인 정보 및 규정 준수 문을 검토 합니다. 타사 응용 프로그램 및 서비스는 정부 클라우드 외부에 있는 타사 시스템에 조직의 고객 데이터를 저장, 전송 및 처리 하는 작업을 수행할 수 있으므로 준수 및 데이터 보호 약정에 포함 되지 않습니다. 

## <a name="it-admin-features"></a>IT 관리 기능

다음은 상업용 고객에 대 한 IT 관리 기능과 정부 클라우드 고객용 IT의 차이점입니다.

- GCC 최고 고객은 사이트 주소를 변경할 수 없음
- 모든 정부 클라우드 고객은 하이브리드 SharePoint Server를 사용할 수 없습니다.
- SharePoint 마이그레이션 도구와 마이그레이션 관리자는 구성을 변경 해야 합니다. 자세한 내용은 [Spmt 정부 클라우드 지원을](/sharepointmigration/spmt-install-issues#government-cloud-support)참조 하십시오.
- Mover.io은 아직 지원 되지 않습니다.
- 일부 정부 클라우드 고객은 다중 geo를 사용할 수 없습니다.

FastTrack 마이그레이션에 대 한 자세한 내용은 [Office 365 US 정부 서비스 설명을](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#data-migrations-performed-by-fasttrack)참조 하세요.

## <a name="security-and-compliance-features"></a>보안 및 규정 준수 기능

상업용 고객의 보안 및 규정 준수 기능과 정부 클라우드 고객용에 대 한 알려진 차이점은 없습니다.

다음 기능에 대 한 자세한 내용은 [Office 365 US 정부 서비스 설명을](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features)참조 하세요.
- 고객 Lockbox
- DLP(데이터 손실 방지)
- eDiscovery (콘텐츠 검색, 보류, 내보내기)
- Office 365 Advanced Threat Protection (ATP)
- 민감도 레이블

정부용 Azure Active Directory 기능에 대 한 자세한 내용은 [Azure 정부 보안 + Identity 설명서](/azure/azure-government/documentation-government-services-securityandidentity#azure-active-directory)를 참조 하세요. 

정부용 Azure Information Protection 기능에 대 한 자세한 내용은 [Azure Information Protection Premium 정부 서비스 설명](/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description) 를 참조 하세요. 

## <a name="sites-and-content"></a>사이트 및 콘텐츠

다음은 상업용 고객에 대 한 사이트 및 콘텐츠 기능과 정부 클라우드 고객용의 차이점입니다.

- Amazon Kindle fire, Bing 지도, Twitter 및 YouTube 웹 파트와 같은 인터넷 서비스에 대 한 연결을 사용 하는 웹 파트가 예상 대로 작동 하지 않음
- 조직 자산 라이브러리를 사용할 수 없음
- GCC High 및 DoD 고객은 팀에 목록 및 페이지를 추가할 수 없습니다.

## <a name="search-features"></a>검색 기능

다음은 상업용 고객에 대 한 검색 기능과 정부 클라우드 고객만 수행 하는 차이점입니다.

- Microsoft 검색 통합을 사용할 수 없습니다.

## <a name="sharing-and-sync"></a>공유 및 동기화

상업용 클라우드와 정부 클라우드 환경 간의 기능 차이는 [파일 공유](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/gcc-high-and-dod#file-sharing)를 참조 하세요.

## <a name="plan-for-governance"></a>관리 방식 계획

클라우드로의 이동은 기본 제공 관리 컨트롤을 사용 하 여 했으며, 근 환경을 제공 합니다. 거 버 넌 스 및이를 충족 하는 방법에 대 한 요구 사항을 결정 합니다. 자세한 내용은 [Microsoft 365을 사용 하 여 팀 작업을 변환 하는 관리 계획](https://resources.techcommunity.microsoft.com/teamwork-governance/) 으로 이동 합니다. Office 365 그룹, SharePoint 및 팀에 대 한 지침을 확인할 수 있습니다.

## <a name="deploy-sharepoint-for-collaboration"></a>공동 작업용 SharePoint 배포

Microsoft US 정부 클라우드에서 조직을 설정한 후에는 [SharePoint 채택 리소스 센터](https://resources.techcommunity.microsoft.com/resources/SharePoint-adoption/)에 나와 있는 권장 배포 경로를 따르세요. 채택 및 변경 관리 champions에 참여 해야 합니다.
[Fasttrack](https://www.microsoft.com/fasttrack) 또는 선택한 파트너와 함께 작업 하 여 사용자에 게 서비스를 롤아웃할 수도 있습니다.
Microsoft 보안 [센터](https://www.microsoft.com/trust-center) 를 방문 하 여 조직이 고객을 지원 하도록 하는 방식에 대해 microsoft가 security, 개인정보, 규정 준수, 핵심 tenets에 접근 하는지 자세히 알아보세요.
