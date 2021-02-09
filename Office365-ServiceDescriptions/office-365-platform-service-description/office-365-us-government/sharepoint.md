---
title: 미국 정부 환경용 SharePoint
ms.author: office365servicedesc
author: pamelaar
ms.reviewer: mkashman
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 미국 정부 클라우드 고객을 위한 SharePoint 기능 가용성에 대해 자세히 알아보습니다.
ms.openlocfilehash: 505be0509dbef718e64983377c8dc75a23adfd26
ms.sourcegitcommit: bf25a64ef2b5c1a1c1e5b94babbebf8d2eb7a1a1
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/08/2021
ms.locfileid: "50145985"
---
# <a name="sharepoint-for-us-government-environments"></a>미국 정부 환경용 SharePoint

이 문서에서는 SharePoint 서비스 설명에 나열된 미국 정부 클라우드와 상업용 클라우드 간의 기능 차이에 대한 [개요를 제공합니다.](/office365/servicedescriptions/sharepoint-online-service-description/sharepoint-online-service-description) SharePoint는 GCC(정부 커뮤니티 클라우드), GCC High 및 DoD 환경에서 사용할 수 있습니다. 

자격 및 구매를 비롯한 정부 클라우드에 대한 자세한 내용은 [Microsoft 365 Government - 구입 방법을 참조하세요.](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy) Office 365 Government 요금제 비교는 [Office 365 Government 요금제를 참조합니다.](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements)

네트워크 연결을 관리할 때 필요한 끝점에 대한 자세한 내용은 [Office 365 U.S. Government GCC High endpoints](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) or [Office 365 U.S. Government DoD endpoints](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business).

Office 365의 기능과 기능을 즐길 뿐만 아니라 조직은 미국 정부 클라우드 환경에 고유한 다음과 같은 기능을 활용합니다.

-   조직의 고객 콘텐츠는 Microsoft에서 상용 Office 365 서비스의 고객 콘텐츠와 논리적으로 나아지게 됩니다.
-   조직의 고객 콘텐츠는 미국에 보관됩니다.
-   조직 고객 콘텐츠에 대한 액세스는 선별된 Microsoft 직원으로 제한됩니다.
-   정부 클라우드 환경은 미국 공공 부문 고객에게 필요한 인증 및 인증을 준수합니다.

모든 SharePoint 상용 기능을 정부 클라우드 환경에 제공하는 것이 목표입니다. 일부 기능은 정부 클라우드 고객의 요구 사항 때문에 사용할 수 없습니다. 다른 기능은 정부 환경에 제공되지만 아직 사용할 수 없습니다. 다음 섹션에서 정부 클라우드 환경의 기능 가용성에 대해 자세히 알아보십시오.

## <a name="developer-features"></a>개발자 기능

상업용 고객용 개발자 기능과 정부 클라우드 고객용 개발자 기능 간에는 알려진 차이점이 없습니다.

- 추가 기능의 데이터 원본과 같은 외부 응용 프로그램에 대한 연결은 정부 환경에서 지원하는 시스템 보안 경계 내에 있는 원본으로 제한됩니다.
- Business Connectivity Services(BCS) 기능은 데이터 원본이 클라우드 서비스에 대한 보안 경계 내에서 연결 가능한 상태로 유지되는 연결 시나리오에서 지원됩니다.

사이트에서 타사 응용 프로그램을 사용하는 경우 조직에 이러한 서비스의 적절한 사용을 평가할 때 타사에서 제공하는 개인 정보 보호 및 규정 준수 정책을 검토합니다. 타사 응용 프로그램 및 서비스에는 정부 클라우드 외부에 있으며 규정 준수 및 데이터 보호 약정이 적용되지 않는 타사 시스템에서 조직의 고객 데이터를 저장, 전송 및 처리하는 과정이 포함됩니다. 

## <a name="it-admin-features"></a>IT 관리자 기능

다음은 상업 고객을 위한 IT 관리자 기능과 정부 클라우드 고객 간의 차이점입니다.

- GCC High 고객은 사이트 주소를 변경할 수 없습니다.
- 일부 정부 클라우드 고객은 하이브리드 SharePoint Server를 사용할 수 없습니다.
- SharePoint 마이그레이션 도구 및 마이그레이션 관리자를 사용하려면 구성을 변경해야 합니다. 자세한 내용은 [SPMT 정부 클라우드 지원을 참조하세요.](/sharepointmigration/spmt-install-issues#government-cloud-support)
- Mover.io 지원되지 않습니다.
- Multi-Geo는 모든 정부 클라우드 고객에 대해 사용할 수 없습니다.

FastTrack 마이그레이션에 대한 자세한 내용은 [Office 365 Government 서비스 설명을 참조하세요.](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#data-migrations-performed-by-fasttrack)

## <a name="security-and-compliance-features"></a>보안 및 규정 준수 기능

상업용 고객용 보안 및 규정 준수 기능과 정부 클라우드 고객의 보안 및 규정 준수 기능은 알려진 차이가 없습니다.

보안 및 규정 준수 기능에 대한 자세한 내용은 보안 및 준수 [& 참조하세요.](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-securitycompliance-center)

정부용 Azure Active Directory 기능에 대한 자세한 내용은 Azure Government 보안 + ID 설명서를 [참조하세요.](/azure/azure-government/documentation-government-services-securityandidentity#azure-active-directory) 

정부용 Azure Information Protection 기능에 대한 자세한 내용은 Azure Information Protection Premium 정부 서비스 [설명을 참조하세요.](/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description) 

## <a name="sites-and-content"></a>사이트 및 콘텐츠

다음은 상업용 고객용 사이트 및 콘텐츠 기능과 정부 클라우드 고객용 콘텐츠 기능의 차이점입니다.

- Amazon Kindle, Bing 지도, Twitter 및 YouTube 웹 파트와 같은 인터넷 서비스에 대한 연결을 사용 하는 웹 파트는 예상대로 작동하지 않습니다.
- 조직 자산 라이브러리를 사용할 수 없습니다.
- GCC High 및 DoD 고객은 Teams에 목록 및 페이지 추가를 사용할 수 없습니다.
- GCC High용 SharePoint Online의 그래프 기능은 현재 사용하지 않도록 설정되어 있습니다. Microsoft Graph를 사용 하는 모든 서비스를 현재 사용할 수 없습니다.
- 주식 이미지 탭과 같은 인터넷 서비스에 대한 연결을 사용 하는 기능은 예상대로 작동하지 않습니다.

## <a name="search-features"></a>검색 기능

다음은 상업용 고객용 검색 기능과 정부 클라우드 고객용 검색 기능의 차이점입니다.

- Microsoft Search 통합을 사용할 수 없습니다.

## <a name="sharing-and-sync"></a>공유 및 동기화

상업용 클라우드와 정부 클라우드 환경 간의 기능 차이는 파일 [공유를 참조하세요.](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/gcc-high-and-dod#file-sharing)

## <a name="plan-for-governance"></a>거버넌스 계획

클라우드로의 전환은 기본 제공 관리자 컨트롤을 사용하여 혁신적 환경을 제공합니다. 거버넌스에 대한 요구 사항과 충족 방법을 확인합니다. 자세한 내용은 [거버넌스 계획으로 이동하여 Microsoft 365로](https://resources.techcommunity.microsoft.com/teamwork-governance/) 팀워크를 변환합니다. Office 365 그룹, SharePoint, Teams 등에 대한 지침을 찾을 수 있습니다.

## <a name="deploy-sharepoint-for-collaboration"></a>공동 작업을 위해 SharePoint 배포

Microsoft 미국 정부 클라우드에서 조직을 설정한 후 SharePoint 채택 리소스 센터에 설명된 권장 배포 [경로를 따르는 것이 좋습니다.](https://resources.techcommunity.microsoft.com/resources/SharePoint-adoption/) 채택 및 변경 관리 챔피언과 함께 참여해야 합니다.
[FastTrack](https://www.microsoft.com/fasttrack) 또는 선택한 파트너와 협력하여 사용자에게 서비스를 롤아웃할 수도 있습니다.
Microsoft 보안 센터를 방문하여 [Microsoft가](https://www.microsoft.com/trust-center) 어떻게 보안, 개인 정보 보호 및 규정 준수에 접근하는지, 조직이 고객에게 서비스를 제공하도록 지원할 수 있는 핵심 테넌트에 대해 자세히 알아보세요.
