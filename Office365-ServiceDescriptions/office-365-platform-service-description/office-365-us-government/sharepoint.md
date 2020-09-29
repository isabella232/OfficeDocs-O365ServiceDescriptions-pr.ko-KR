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
# <a name="sharepoint-for-us-government-environments"></a><span data-ttu-id="4520e-103">미국 정부 환경용 SharePoint</span><span class="sxs-lookup"><span data-stu-id="4520e-103">SharePoint for US government environments</span></span>

<span data-ttu-id="4520e-104">이 문서에서는 [SharePoint 서비스 설명](/office365/servicedescriptions/sharepoint-online-service-description/sharepoint-online-service-description)에 나와 있는 대로 US 정부 클라우드와 상업용 클라우드 간의 기능 차이에 대 한 개요를 제공 합니다.</span><span class="sxs-lookup"><span data-stu-id="4520e-104">This article provides an overview of feature differences between the US government cloud and the commercial cloud as listed in the [SharePoint service description](/office365/servicedescriptions/sharepoint-online-service-description/sharepoint-online-service-description).</span></span> <span data-ttu-id="4520e-105">SharePoint는 GCC (정부 커뮤니티 클라우드), GCC High 및 DoD 환경에 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="4520e-105">SharePoint is available for the Government Community Cloud (GCC), GCC High, and DoD environments.</span></span> 

<span data-ttu-id="4520e-106">자격 및 구매를 비롯 한 정부 클라우드에 대 한 자세한 내용은 [Microsoft 365 정부-구매 방법](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy)를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="4520e-106">For more info about the government cloud, including eligibility and purchasing, see [Microsoft 365 Government - how to buy](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy).</span></span> <span data-ttu-id="4520e-107">Office 365 정부 요금제를 비교 하려면 [office 365 정부 요금제](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements)를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="4520e-107">To compare Office 365 Government plans, see [Office 365 Government plans](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements).</span></span>

<span data-ttu-id="4520e-108">네트워크 연결을 관리할 때 필요한 끝점에 대 한 자세한 내용은 [office 365 미국 정부 GCC High endpoints](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) 또는 [Office 365 미국 정부 DoD endpoints](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business)를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="4520e-108">To learn about required endpoints when managing network connectivity, see the [Office 365 U.S. Government GCC High endpoints](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) or [Office 365 U.S. Government DoD endpoints](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business).</span></span>

<span data-ttu-id="4520e-109">조직에서는 Office 365의 기능을 사용할 수 있을 뿐만 아니라 미국 정부 클라우드 환경에 고유한 다음과 같은 기능을 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="4520e-109">In addition to enjoying the features and capabilities of Office 365, organizations benefit from the following features that are unique to the US government cloud environments:</span></span>

-   <span data-ttu-id="4520e-110">조직의 고객 콘텐츠는 Microsoft의 상용 Office 365 서비스에 있는 고객 콘텐츠와 논리적으로 분리 됩니다.</span><span class="sxs-lookup"><span data-stu-id="4520e-110">Your organization’s customer content is logically segregated from customer content in the commercial Office 365 services from Microsoft.</span></span>
-   <span data-ttu-id="4520e-111">조직의 고객 콘텐츠는 미국에 보관됩니다.</span><span class="sxs-lookup"><span data-stu-id="4520e-111">Your organization’s customer content is stored within the United States.</span></span>
-   <span data-ttu-id="4520e-112">조직 고객 콘텐츠에 대한 액세스는 선별된 Microsoft 직원으로 제한됩니다.</span><span class="sxs-lookup"><span data-stu-id="4520e-112">Access to your organization’s customer content is restricted to screened Microsoft personnel.</span></span>
-   <span data-ttu-id="4520e-113">정부 클라우드 환경은 미국 공공 부문 고객에 게 필요한 인증 및 승인을 준수 합니다.</span><span class="sxs-lookup"><span data-stu-id="4520e-113">The government cloud environments comply with certifications and accreditations that are required for US Public Sector customers.</span></span>

<span data-ttu-id="4520e-114">모든 SharePoint 상업용 기능과 기능을 정부 클라우드 환경에 제공 하는 것은 우리의 목표입니다.</span><span class="sxs-lookup"><span data-stu-id="4520e-114">It's our goal to deliver all SharePoint commercial features and functionality to the government cloud environments.</span></span> <span data-ttu-id="4520e-115">일부 기능은 정부 클라우드 고객의 요구 사항으로 인해 사용할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="4520e-115">Some features aren't available because of the requirements of government cloud customers.</span></span> <span data-ttu-id="4520e-116">다른 기능은 정부 환경에 제공 되지만 아직 사용할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="4520e-116">Other features are coming to the government environments, but not yet available.</span></span> <span data-ttu-id="4520e-117">정부 클라우드 환경에서의 기능 가용성에 대 한 자세한 내용은 다음 섹션을 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="4520e-117">Refer to the following sections to learn about feature availability in the government cloud environments.</span></span>

## <a name="developer-features"></a><span data-ttu-id="4520e-118">개발자 기능</span><span class="sxs-lookup"><span data-stu-id="4520e-118">Developer features</span></span>

<span data-ttu-id="4520e-119">상업용 고객 및 정부 클라우드 고객용 개발자 기능 간에는 알려진 차이점이 없습니다.</span><span class="sxs-lookup"><span data-stu-id="4520e-119">There are no known differences between the developer features for commercial customers and those for government cloud customers.</span></span>

- <span data-ttu-id="4520e-120">추가 기능에 대 한 데이터 원본과 같은 외부 응용 프로그램에 대 한 연결은 정부 환경에서 지원 되는 시스템 보안 경계 내에 있는 원본으로 제한 됩니다.</span><span class="sxs-lookup"><span data-stu-id="4520e-120">Connections to external applications such as data sources for add-ins are limited to sources that are located within the system security boundaries supported by your government environment.</span></span>
- <span data-ttu-id="4520e-121">BCS (Business Connectivity Services) 기능은 클라우드 서비스에 대 한 보안 경계 내에서 데이터 원본을 계속 사용할 수 있는 연결 시나리오에서 지원 됩니다.</span><span class="sxs-lookup"><span data-stu-id="4520e-121">Business Connectivity Services (BCS) functionality is supported for connectivity scenarios in which the data sources remain reachable within the security boundary for your cloud service.</span></span>

<span data-ttu-id="4520e-122">사이트에서 타사 응용 프로그램을 사용 하는 경우 조직에서 이러한 서비스의 적절 한 사용을 평가할 때 타사에서 제공 하는 개인 정보 및 규정 준수 문을 검토 합니다.</span><span class="sxs-lookup"><span data-stu-id="4520e-122">If you use third-party applications on sites, review the privacy and compliance statements provided by the third parties when assessing the appropriate use of these services for your organization.</span></span> <span data-ttu-id="4520e-123">타사 응용 프로그램 및 서비스는 정부 클라우드 외부에 있는 타사 시스템에 조직의 고객 데이터를 저장, 전송 및 처리 하는 작업을 수행할 수 있으므로 준수 및 데이터 보호 약정에 포함 되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="4520e-123">Third-party applications and services might involve storing, transmitting, and processing your organization's customer data on third-party systems that are outside of the government cloud and therefore not covered by its compliance and data protection commitments.</span></span> 

## <a name="it-admin-features"></a><span data-ttu-id="4520e-124">IT 관리 기능</span><span class="sxs-lookup"><span data-stu-id="4520e-124">IT admin features</span></span>

<span data-ttu-id="4520e-125">다음은 상업용 고객에 대 한 IT 관리 기능과 정부 클라우드 고객용 IT의 차이점입니다.</span><span class="sxs-lookup"><span data-stu-id="4520e-125">Here are the differences between the IT admin features for commercial customers and those for government cloud customers.</span></span>

- <span data-ttu-id="4520e-126">GCC 최고 고객은 사이트 주소를 변경할 수 없음</span><span class="sxs-lookup"><span data-stu-id="4520e-126">Changing a site address is not available for GCC High customers</span></span>
- <span data-ttu-id="4520e-127">모든 정부 클라우드 고객은 하이브리드 SharePoint Server를 사용할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="4520e-127">Hybrid SharePoint Server is not available for all government cloud customers</span></span>
- <span data-ttu-id="4520e-128">SharePoint 마이그레이션 도구와 마이그레이션 관리자는 구성을 변경 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="4520e-128">The SharePoint Migration Tool and Migration Manager require a configuration change.</span></span> <span data-ttu-id="4520e-129">자세한 내용은 [Spmt 정부 클라우드 지원을](/sharepointmigration/spmt-install-issues#government-cloud-support)참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="4520e-129">For info, see [SPMT government cloud support](/sharepointmigration/spmt-install-issues#government-cloud-support).</span></span>
- <span data-ttu-id="4520e-130">Mover.io은 아직 지원 되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="4520e-130">Mover.io is not yet supported</span></span>
- <span data-ttu-id="4520e-131">일부 정부 클라우드 고객은 다중 geo를 사용할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="4520e-131">Multi-geo is not available for all government cloud customers</span></span>

<span data-ttu-id="4520e-132">FastTrack 마이그레이션에 대 한 자세한 내용은 [Office 365 US 정부 서비스 설명을](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#data-migrations-performed-by-fasttrack)참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="4520e-132">For info about FastTrack migration, see the [Office 365 US Government service description](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#data-migrations-performed-by-fasttrack).</span></span>

## <a name="security-and-compliance-features"></a><span data-ttu-id="4520e-133">보안 및 규정 준수 기능</span><span class="sxs-lookup"><span data-stu-id="4520e-133">Security and compliance features</span></span>

<span data-ttu-id="4520e-134">상업용 고객의 보안 및 규정 준수 기능과 정부 클라우드 고객용에 대 한 알려진 차이점은 없습니다.</span><span class="sxs-lookup"><span data-stu-id="4520e-134">There are no known differences between the security and compliance features for commercial customers and those for government cloud customers.</span></span>

<span data-ttu-id="4520e-135">다음 기능에 대 한 자세한 내용은 [Office 365 US 정부 서비스 설명을](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features)참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="4520e-135">For info about the following features, see the [Office 365 US Government service description](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features):</span></span>
- <span data-ttu-id="4520e-136">고객 Lockbox</span><span class="sxs-lookup"><span data-stu-id="4520e-136">Customer Lockbox</span></span>
- <span data-ttu-id="4520e-137">DLP(데이터 손실 방지)</span><span class="sxs-lookup"><span data-stu-id="4520e-137">Data loss prevention (DLP)</span></span>
- <span data-ttu-id="4520e-138">eDiscovery (콘텐츠 검색, 보류, 내보내기)</span><span class="sxs-lookup"><span data-stu-id="4520e-138">eDiscovery (Content Search, hold, export)</span></span>
- <span data-ttu-id="4520e-139">Office 365 Advanced Threat Protection (ATP)</span><span class="sxs-lookup"><span data-stu-id="4520e-139">Office 365 Advanced Threat Protection (ATP)</span></span>
- <span data-ttu-id="4520e-140">민감도 레이블</span><span class="sxs-lookup"><span data-stu-id="4520e-140">Sensitivity labels</span></span>

<span data-ttu-id="4520e-141">정부용 Azure Active Directory 기능에 대 한 자세한 내용은 [Azure 정부 보안 + Identity 설명서](/azure/azure-government/documentation-government-services-securityandidentity#azure-active-directory)를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="4520e-141">For info about Azure Active Directory features for government, see [Azure Government Security + Identity documentation](/azure/azure-government/documentation-government-services-securityandidentity#azure-active-directory).</span></span> 

<span data-ttu-id="4520e-142">정부용 Azure Information Protection 기능에 대 한 자세한 내용은 [Azure Information Protection Premium 정부 서비스 설명](/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description) 를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="4520e-142">For info about Azure Information Protection features for government, see the [Azure Information Protection Premium Government Service Description](/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description)</span></span> 

## <a name="sites-and-content"></a><span data-ttu-id="4520e-143">사이트 및 콘텐츠</span><span class="sxs-lookup"><span data-stu-id="4520e-143">Sites and content</span></span>

<span data-ttu-id="4520e-144">다음은 상업용 고객에 대 한 사이트 및 콘텐츠 기능과 정부 클라우드 고객용의 차이점입니다.</span><span class="sxs-lookup"><span data-stu-id="4520e-144">Here are the differences between the sites and content features for commercial customers and those for government cloud customers:</span></span>

- <span data-ttu-id="4520e-145">Amazon Kindle fire, Bing 지도, Twitter 및 YouTube 웹 파트와 같은 인터넷 서비스에 대 한 연결을 사용 하는 웹 파트가 예상 대로 작동 하지 않음</span><span class="sxs-lookup"><span data-stu-id="4520e-145">Web parts that rely on connections to Internet services, such as the Amazon Kindle, Bing Maps, Twitter, and YouTube web parts, won't work as expected</span></span>
- <span data-ttu-id="4520e-146">조직 자산 라이브러리를 사용할 수 없음</span><span class="sxs-lookup"><span data-stu-id="4520e-146">Organization assets library is not available</span></span>
- <span data-ttu-id="4520e-147">GCC High 및 DoD 고객은 팀에 목록 및 페이지를 추가할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="4520e-147">Adding lists and pages to Teams isn't available for GCC High and DoD customers</span></span>

## <a name="search-features"></a><span data-ttu-id="4520e-148">검색 기능</span><span class="sxs-lookup"><span data-stu-id="4520e-148">Search features</span></span>

<span data-ttu-id="4520e-149">다음은 상업용 고객에 대 한 검색 기능과 정부 클라우드 고객만 수행 하는 차이점입니다.</span><span class="sxs-lookup"><span data-stu-id="4520e-149">Here are the differences between the search features for commercial customers and those for government cloud customers:</span></span>

- <span data-ttu-id="4520e-150">Microsoft 검색 통합을 사용할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="4520e-150">Microsoft Search integration is not available.</span></span>

## <a name="sharing-and-sync"></a><span data-ttu-id="4520e-151">공유 및 동기화</span><span class="sxs-lookup"><span data-stu-id="4520e-151">Sharing and sync</span></span>

<span data-ttu-id="4520e-152">상업용 클라우드와 정부 클라우드 환경 간의 기능 차이는 [파일 공유](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/gcc-high-and-dod#file-sharing)를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="4520e-152">For feature differences between the commercial cloud and the government cloud environments, see [File sharing](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/gcc-high-and-dod#file-sharing).</span></span>

## <a name="plan-for-governance"></a><span data-ttu-id="4520e-153">관리 방식 계획</span><span class="sxs-lookup"><span data-stu-id="4520e-153">Plan for governance</span></span>

<span data-ttu-id="4520e-154">클라우드로의 이동은 기본 제공 관리 컨트롤을 사용 하 여 했으며, 근 환경을 제공 합니다.</span><span class="sxs-lookup"><span data-stu-id="4520e-154">Your move to the cloud offers transformative experiences with built-in admin controls.</span></span> <span data-ttu-id="4520e-155">거 버 넌 스 및이를 충족 하는 방법에 대 한 요구 사항을 결정 합니다.</span><span class="sxs-lookup"><span data-stu-id="4520e-155">Determine your requirements for governance and how you can meet them.</span></span> <span data-ttu-id="4520e-156">자세한 내용은 [Microsoft 365을 사용 하 여 팀 작업을 변환 하는 관리 계획](https://resources.techcommunity.microsoft.com/teamwork-governance/) 으로 이동 합니다.</span><span class="sxs-lookup"><span data-stu-id="4520e-156">Go to [Plan for governance to transform teamwork with Microsoft 365](https://resources.techcommunity.microsoft.com/teamwork-governance/) for more information.</span></span> <span data-ttu-id="4520e-157">Office 365 그룹, SharePoint 및 팀에 대 한 지침을 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="4520e-157">You will find guidance about Office 365 Groups, SharePoint, Teams and more.</span></span>

## <a name="deploy-sharepoint-for-collaboration"></a><span data-ttu-id="4520e-158">공동 작업용 SharePoint 배포</span><span class="sxs-lookup"><span data-stu-id="4520e-158">Deploy SharePoint for collaboration</span></span>

<span data-ttu-id="4520e-159">Microsoft US 정부 클라우드에서 조직을 설정한 후에는 [SharePoint 채택 리소스 센터](https://resources.techcommunity.microsoft.com/resources/SharePoint-adoption/)에 나와 있는 권장 배포 경로를 따르세요.</span><span class="sxs-lookup"><span data-stu-id="4520e-159">After you set up your organization in the Microsoft US government cloud, follow the recommended deployment path outlined in the [SharePoint adoption resource center](https://resources.techcommunity.microsoft.com/resources/SharePoint-adoption/).</span></span> <span data-ttu-id="4520e-160">채택 및 변경 관리 champions에 참여 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="4520e-160">Be sure to engage with your Adoption and Change Management champions.</span></span>
<span data-ttu-id="4520e-161">[Fasttrack](https://www.microsoft.com/fasttrack) 또는 선택한 파트너와 함께 작업 하 여 사용자에 게 서비스를 롤아웃할 수도 있습니다.</span><span class="sxs-lookup"><span data-stu-id="4520e-161">You can also work with [FastTrack](https://www.microsoft.com/fasttrack) or your chosen partner to roll out the service to your users.</span></span>
<span data-ttu-id="4520e-162">Microsoft 보안 [센터](https://www.microsoft.com/trust-center) 를 방문 하 여 조직이 고객을 지원 하도록 하는 방식에 대해 microsoft가 security, 개인정보, 규정 준수, 핵심 tenets에 접근 하는지 자세히 알아보세요.</span><span class="sxs-lookup"><span data-stu-id="4520e-162">Visit the [Microsoft Trust Center](https://www.microsoft.com/trust-center) to learn more about how Microsoft approaches security, privacy, and compliance, core tenets for how we empower organizations to serve their customers.</span></span>
