---
title: Office 365 Advanced Threat Protection 서비스 설명
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Office 365 Advanced Threat Protection (ATP)은 강력한 제로 보호를 제공 하 여 알 수 없는 맬웨어 및 바이러스 로부터 조직을 보호 하는 클라우드 기반 전자 메일 필터링 서비스 이며, 다음을 보호 하는 기능을 포함 합니다. 실시간으로 해로운 링크에서 조직으로 구성 합니다.
ms.openlocfilehash: 5457cbe5304665f7cddc9cc068a167684cf77024
ms.sourcegitcommit: 83c602d9c498df5a2fe0095c6fb0a267c8a708b7
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/12/2020
ms.locfileid: "42609839"
---
# <a name="office-365-advanced-threat-protection-service-description"></a><span data-ttu-id="2f54e-103">Office 365 Advanced Threat Protection 서비스 설명</span><span class="sxs-lookup"><span data-stu-id="2f54e-103">Office 365 Advanced Threat Protection service description</span></span>

<span data-ttu-id="2f54e-104">Microsoft Office 365 Advanced Threat Protection (ATP)은 강력한 제로 보호를 제공 하 여 알 수 없는 맬웨어 및 바이러스 로부터 조직을 보호 하는 클라우드 기반 전자 메일 필터링 서비스 이며, 다음을 보호 하는 기능을 포함 합니다. 실시간으로 해로운 링크에서 조직으로 구성 합니다.</span><span class="sxs-lookup"><span data-stu-id="2f54e-104">Microsoft Office 365 Advanced Threat Protection (ATP) is a cloud-based email filtering service that helps protect your organization against unknown malware and viruses by providing robust zero-day protection, and includes features to safeguard your organization from harmful links in real time.</span></span> <span data-ttu-id="2f54e-105">ATP에는 조직에서 발생 하는 공격 종류를 관리자에 게 제공 하는 다양 한 보고 및 URL 추적 기능이 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2f54e-105">ATP has rich reporting and URL trace capabilities that give administrators insight into the kind of attacks happening in your organization.</span></span>

<span data-ttu-id="2f54e-106">다음은 메시지 보호에 ATP를 사용할 수 있는 기본 방법입니다.</span><span class="sxs-lookup"><span data-stu-id="2f54e-106">The following are the primary ways you can use ATP for message protection:</span></span>

- <span data-ttu-id="2f54e-107">Office 365 ATP 필터링 전용 시나리오에서 ATP는 온-프레미스 Exchange 서버 환경 또는 기타 모든 온-프레미스 SMTP 전자 메일 솔루션에 대해 클라우드 기반 전자 메일 보호 기능을 제공 합니다.</span><span class="sxs-lookup"><span data-stu-id="2f54e-107">In an Office 365 ATP filtering-only scenario, ATP provides cloud-based email protection for your on-premises Exchange Server environment or any other on-premises SMTP email solution.</span></span>

- <span data-ttu-id="2f54e-108">Office 365 ATP를 사용 하도록 설정 하 여 Exchange Online 클라우드 호스트 사서함을 보호할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2f54e-108">Office 365 ATP can be enabled to protect Exchange Online cloud-hosted mailboxes.</span></span> <span data-ttu-id="2f54e-109">Exchange Online에 대 한 자세한 내용은 [Exchange online 서비스 설명을](exchange-online-service-description/exchange-online-service-description.md)참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="2f54e-109">To learn more about Exchange Online, see the [Exchange Online service description](exchange-online-service-description/exchange-online-service-description.md).</span></span>

- <span data-ttu-id="2f54e-110">하이브리드 배포에서는 인바운드 전자 메일 필터링에 대 한 Exchange Online 보호와 함께 온-프레미스 및 클라우드 사서함을 함께 사용 하는 경우 메시징 환경을 보호 하 고 메일 라우팅을 제어 하도록 ATP를 구성할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2f54e-110">In a hybrid deployment, ATP can be configured to protect your messaging environment and control mail routing when you have a mix of on-premises and cloud mailboxes with Exchange Online Protection for inbound email filtering.</span></span>

## <a name="office-365-advanced-threat-protection-atp-availability"></a><span data-ttu-id="2f54e-111">Office 365 ATP (Advanced Threat Protection) 가용성</span><span class="sxs-lookup"><span data-stu-id="2f54e-111">Office 365 Advanced Threat Protection (ATP) availability</span></span>

<span data-ttu-id="2f54e-112">ATP는 Office 365 Enterprise E5, Office 365 교육 A5 및 Microsoft 365 Business에 포함 되어 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2f54e-112">ATP is included in Office 365 Enterprise E5, Office 365 Education A5, and Microsoft 365 Business.</span></span>

<span data-ttu-id="2f54e-113">ATP를 다음 Exchange 및 Office 365 구독 계획에 추가할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2f54e-113">You can add ATP to the following Exchange and Office 365 subscription plans:</span></span>

- <span data-ttu-id="2f54e-114">Exchange Online 요금제 1</span><span class="sxs-lookup"><span data-stu-id="2f54e-114">Exchange Online Plan 1</span></span>

- <span data-ttu-id="2f54e-115">Exchange Online 계획 2</span><span class="sxs-lookup"><span data-stu-id="2f54e-115">Exchange Online Plan 2</span></span>

- <span data-ttu-id="2f54e-116">Exchange Online Kiosk</span><span class="sxs-lookup"><span data-stu-id="2f54e-116">Exchange Online Kiosk</span></span>

- <span data-ttu-id="2f54e-117">Exchange Online Protection</span><span class="sxs-lookup"><span data-stu-id="2f54e-117">Exchange Online Protection</span></span>

- <span data-ttu-id="2f54e-118">Office 365 Business Essentials</span><span class="sxs-lookup"><span data-stu-id="2f54e-118">Office 365 Business Essentials</span></span>

- <span data-ttu-id="2f54e-119">Office 365 Business Premium</span><span class="sxs-lookup"><span data-stu-id="2f54e-119">Office 365 Business Premium</span></span>

- <span data-ttu-id="2f54e-120">Office 365 Enterprise E1</span><span class="sxs-lookup"><span data-stu-id="2f54e-120">Office 365 Enterprise E1</span></span>

- <span data-ttu-id="2f54e-121">Office 365 Enterprise E3</span><span class="sxs-lookup"><span data-stu-id="2f54e-121">Office 365 Enterprise E3</span></span>

- <span data-ttu-id="2f54e-122">Office 365 Enterprise F3</span><span class="sxs-lookup"><span data-stu-id="2f54e-122">Office 365 Enterprise F3</span></span>

- <span data-ttu-id="2f54e-123">Office 365 A1</span><span class="sxs-lookup"><span data-stu-id="2f54e-123">Office 365 A1</span></span>

- <span data-ttu-id="2f54e-124">Office 365 A3</span><span class="sxs-lookup"><span data-stu-id="2f54e-124">Office 365 A3</span></span>

<span data-ttu-id="2f54e-125">Office 365 Advanced threat Protection을 구입 하려면 [office 365 Advanced Threat protection](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content)를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="2f54e-125">To buy Office 365 Advanced Threat Protection, see [Office 365 Advanced Threat Protection](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content).</span></span>

<span data-ttu-id="2f54e-126">계획 간에 기능을 비교 하려면 [Office 365 For Business 요금제 비교](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) 및 [적절 한 Microsoft 365 Enterprise 솔루션 검색](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans)을 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="2f54e-126">To compare features across plans, see [Compare Office 365 for Business plans](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) and [Discover the Microsoft 365 Enterprise solution that's right for you](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans).</span></span>

## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a><span data-ttu-id="2f54e-127">Office 365의 새로운 기능 (Advanced Threat Protection (ATP)</span><span class="sxs-lookup"><span data-stu-id="2f54e-127">What's new in Office 365 Advanced Threat Protection (ATP)</span></span>

<span data-ttu-id="2f54e-128">계속 해 서 Office 365 ATP에 새로운 기능을 추가 하 고 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2f54e-128">We are continuing to add new features to Office 365 ATP.</span></span> <span data-ttu-id="2f54e-129">ATP에 게 제공 되는 새로운 기능 (또는 일반적인 경우 Microsoft 365)에 대 한 자세한 내용은 다음 리소스를 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="2f54e-129">To learn more about new features coming to ATP (or Microsoft 365 in general), see the following resources:</span></span>

- [<span data-ttu-id="2f54e-130">Microsoft 365 로드맵</span><span class="sxs-lookup"><span data-stu-id="2f54e-130">Microsoft 365 Roadmap</span></span>](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [<span data-ttu-id="2f54e-131">Office 365 ATP의 새로운 기능</span><span class="sxs-lookup"><span data-stu-id="2f54e-131">What's new in Office 365 ATP</span></span>](https://docs.microsoft.com/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a><span data-ttu-id="2f54e-132">Office 365의 ATP (Advanced Threat Protection)에 대 한 요구 사항</span><span class="sxs-lookup"><span data-stu-id="2f54e-132">Requirements for Office 365 Advanced Threat Protection (ATP)</span></span>

<span data-ttu-id="2f54e-133">ATP는 Microsoft Exchange Server와 같은 SMTP 메일 전송 에이전트와 함께 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2f54e-133">ATP can be used with any SMTP mail transfer agent, such as Microsoft Exchange Server.</span></span> <span data-ttu-id="2f54e-134">ATP에서 지원되는 운영 체제, 웹 브라우저, 언어에 대한 자세한 내용은 [Exchange Online Protection의 Exchange 관리 센터](https://go.microsoft.com/fwlink/p/?LinkId=282381)의 "지원되는 브라우저" 및 "지원되는 언어" 섹션을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="2f54e-134">For information about the operating systems, web browsers, and languages that are supported by ATP, see the "Supported browsers" and "Supported languages" sections in [Exchange Admin Center in Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).</span></span>

## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a><span data-ttu-id="2f54e-135">ATP (Advanced Threat Protection) 계획에서의 기능 가용성</span><span class="sxs-lookup"><span data-stu-id="2f54e-135">Feature availability across Advanced Threat Protection (ATP) plans</span></span>

<span data-ttu-id="2f54e-p105">각 기능은 아래와 같습니다. Exchange Online은 대개 Office 365 Enterprise 서비스 제품군을 지칭하는 것입니다.</span><span class="sxs-lookup"><span data-stu-id="2f54e-p105">Each feature is listed below. When Exchange Online is mentioned, it typically refers to the Office 365 Enterprise service family.</span></span>

|<span data-ttu-id="2f54e-138">**기능**</span><span class="sxs-lookup"><span data-stu-id="2f54e-138">**Feature**</span></span>|<span data-ttu-id="2f54e-139">**ATP 계획 1**</span><span class="sxs-lookup"><span data-stu-id="2f54e-139">**ATP Plan 1**</span></span><br><span data-ttu-id="2f54e-140">(이전의 ATP 독립 실행형)</span><span class="sxs-lookup"><span data-stu-id="2f54e-140">(formerly ATP standalone)</span></span>|<span data-ttu-id="2f54e-141">**ATP 계획 2**</span><span class="sxs-lookup"><span data-stu-id="2f54e-141">**ATP Plan 2**</span></span><br><span data-ttu-id="2f54e-142">(이전의 위협 인텔리전스</span><span class="sxs-lookup"><span data-stu-id="2f54e-142">(formerly Threat Intelligence</span></span> <br><span data-ttu-id="2f54e-143">독립</span><span class="sxs-lookup"><span data-stu-id="2f54e-143">standalone)</span></span>| <span data-ttu-id="2f54e-144">Office 365 Enterprise E5</span><span class="sxs-lookup"><span data-stu-id="2f54e-144">Office 365 Enterprise E5</span></span>|
|:-----|:-----|:-----|:-----|
|<span data-ttu-id="2f54e-145">*구성, 보호 및 검색*</span><span class="sxs-lookup"><span data-stu-id="2f54e-145">*Configuration, protection, and detection*</span></span>|
|[<span data-ttu-id="2f54e-146">안전한 첨부 파일</span><span class="sxs-lookup"><span data-stu-id="2f54e-146">Safe Attachments</span></span>](#safe-attachments)|<span data-ttu-id="2f54e-147">예</span><span class="sxs-lookup"><span data-stu-id="2f54e-147">Yes</span></span>|<span data-ttu-id="2f54e-148">예</span><span class="sxs-lookup"><span data-stu-id="2f54e-148">Yes</span></span>|<span data-ttu-id="2f54e-149">예</span><span class="sxs-lookup"><span data-stu-id="2f54e-149">Yes</span></span>|
|<span data-ttu-id="2f54e-150">팀의 안전한 첨부 파일</span><span class="sxs-lookup"><span data-stu-id="2f54e-150">Safe Attachments in Teams</span></span>|<span data-ttu-id="2f54e-151">예</span><span class="sxs-lookup"><span data-stu-id="2f54e-151">Yes</span></span>|<span data-ttu-id="2f54e-152">예</span><span class="sxs-lookup"><span data-stu-id="2f54e-152">Yes</span></span>|<span data-ttu-id="2f54e-153">예</span><span class="sxs-lookup"><span data-stu-id="2f54e-153">Yes</span></span>|
|[<span data-ttu-id="2f54e-154">안전한 링크</span><span class="sxs-lookup"><span data-stu-id="2f54e-154">Safe Links</span></span>](#safe-links)|<span data-ttu-id="2f54e-155">예</span><span class="sxs-lookup"><span data-stu-id="2f54e-155">Yes</span></span>|<span data-ttu-id="2f54e-156">예</span><span class="sxs-lookup"><span data-stu-id="2f54e-156">Yes</span></span>|<span data-ttu-id="2f54e-157">예</span><span class="sxs-lookup"><span data-stu-id="2f54e-157">Yes</span></span>|
|<span data-ttu-id="2f54e-158">팀의 안전한 링크</span><span class="sxs-lookup"><span data-stu-id="2f54e-158">Safe Links in Teams</span></span>|<span data-ttu-id="2f54e-159">아니요</span><span class="sxs-lookup"><span data-stu-id="2f54e-159">No</span></span>|<span data-ttu-id="2f54e-160">아니요</span><span class="sxs-lookup"><span data-stu-id="2f54e-160">No</span></span>|<span data-ttu-id="2f54e-161">아니요</span><span class="sxs-lookup"><span data-stu-id="2f54e-161">No</span></span>|
|[<span data-ttu-id="2f54e-162">SharePoint, OneDrive 및 Microsoft 팀에 대 한 ATP</span><span class="sxs-lookup"><span data-stu-id="2f54e-162">ATP for SharePoint, OneDrive and Microsoft Teams</span></span>](#atp-for-sharepoint-onedrive-and-microsoft-teams)|<span data-ttu-id="2f54e-163">예</span><span class="sxs-lookup"><span data-stu-id="2f54e-163">Yes</span></span>|<span data-ttu-id="2f54e-164">예</span><span class="sxs-lookup"><span data-stu-id="2f54e-164">Yes</span></span>|<span data-ttu-id="2f54e-165">예</span><span class="sxs-lookup"><span data-stu-id="2f54e-165">Yes</span></span>|
|[<span data-ttu-id="2f54e-166">피싱 방지 정책</span><span class="sxs-lookup"><span data-stu-id="2f54e-166">Anti-phishing policies</span></span>](#anti-phishing-policies)|<span data-ttu-id="2f54e-167">예</span><span class="sxs-lookup"><span data-stu-id="2f54e-167">Yes</span></span>|<span data-ttu-id="2f54e-168">예</span><span class="sxs-lookup"><span data-stu-id="2f54e-168">Yes</span></span>|<span data-ttu-id="2f54e-169">예</span><span class="sxs-lookup"><span data-stu-id="2f54e-169">Yes</span></span>|
|[<span data-ttu-id="2f54e-170">실시간 보고서</span><span class="sxs-lookup"><span data-stu-id="2f54e-170">Real-time reports</span></span>](#real-time-reports)|<span data-ttu-id="2f54e-171">예</span><span class="sxs-lookup"><span data-stu-id="2f54e-171">Yes</span></span>|<span data-ttu-id="2f54e-172">예</span><span class="sxs-lookup"><span data-stu-id="2f54e-172">Yes</span></span>|<span data-ttu-id="2f54e-173">예</span><span class="sxs-lookup"><span data-stu-id="2f54e-173">Yes</span></span>|
|<span data-ttu-id="2f54e-174">*자동화, 조사, 수정 및 교육*</span><span class="sxs-lookup"><span data-stu-id="2f54e-174">*Automation, investigation, remediation, and education*</span></span>|
|[<span data-ttu-id="2f54e-175">위협 트래커</span><span class="sxs-lookup"><span data-stu-id="2f54e-175">Threat Trackers</span></span>](#threat-trackers)|<span data-ttu-id="2f54e-176">아니요</span><span class="sxs-lookup"><span data-stu-id="2f54e-176">No</span></span>|<span data-ttu-id="2f54e-177">예</span><span class="sxs-lookup"><span data-stu-id="2f54e-177">Yes</span></span>|<span data-ttu-id="2f54e-178">예</span><span class="sxs-lookup"><span data-stu-id="2f54e-178">Yes</span></span>|
|<span data-ttu-id="2f54e-179">[Explorer](#explorer) (advanced threat 조사의)</span><span class="sxs-lookup"><span data-stu-id="2f54e-179">[Explorer](#explorer) (advanced threat investigation)</span></span>|<span data-ttu-id="2f54e-180">아니요</span><span class="sxs-lookup"><span data-stu-id="2f54e-180">No</span></span>|<span data-ttu-id="2f54e-181">예</span><span class="sxs-lookup"><span data-stu-id="2f54e-181">Yes</span></span>|<span data-ttu-id="2f54e-182">예</span><span class="sxs-lookup"><span data-stu-id="2f54e-182">Yes</span></span>|
|[<span data-ttu-id="2f54e-183">자동 인시던트 대응</span><span class="sxs-lookup"><span data-stu-id="2f54e-183">Automated incident response</span></span>](#automated-incident-response)|<span data-ttu-id="2f54e-184">아니요</span><span class="sxs-lookup"><span data-stu-id="2f54e-184">No</span></span>|<span data-ttu-id="2f54e-185">예</span><span class="sxs-lookup"><span data-stu-id="2f54e-185">Yes</span></span>|<span data-ttu-id="2f54e-186">예</span><span class="sxs-lookup"><span data-stu-id="2f54e-186">Yes</span></span>|
|[<span data-ttu-id="2f54e-187">공격 시뮬레이터</span><span class="sxs-lookup"><span data-stu-id="2f54e-187">Attack Simulator</span></span>](#attack-simulator)|<span data-ttu-id="2f54e-188">아니요</span><span class="sxs-lookup"><span data-stu-id="2f54e-188">No</span></span>|<span data-ttu-id="2f54e-189">예</span><span class="sxs-lookup"><span data-stu-id="2f54e-189">Yes</span></span>|<span data-ttu-id="2f54e-190">예</span><span class="sxs-lookup"><span data-stu-id="2f54e-190">Yes</span></span>|

## <a name="advanced-threat-protection-atp-capabilities"></a><span data-ttu-id="2f54e-191">ATP (Advanced Threat Protection) 기능</span><span class="sxs-lookup"><span data-stu-id="2f54e-191">Advanced Threat Protection (ATP) capabilities</span></span>

### <a name="safe-attachments"></a><span data-ttu-id="2f54e-192">안전한 첨부 파일</span><span class="sxs-lookup"><span data-stu-id="2f54e-192">Safe Attachments</span></span>

<span data-ttu-id="2f54e-193">[ATP 안전한 첨부 파일](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments) 은 알 수 없는 맬웨어 및 바이러스 로부터 보호 하 고, 메시징 시스템을 보호 하기 위한 제로 일 보호를 제공 합니다.</span><span class="sxs-lookup"><span data-stu-id="2f54e-193">[ATP Safe Attachments](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments) protects against unknown malware and viruses, and provides zero-day protection to safeguard your messaging system.</span></span> <span data-ttu-id="2f54e-194">알려진 바이러스/맬웨어 서명이 없는 모든 메시지와 첨부 파일은 ATP가 여러 가지 기계 학습 및 분석 기술을 사용하여 악의적인 의도를 감지하는 특수한 환경으로 라우팅됩니다.</span><span class="sxs-lookup"><span data-stu-id="2f54e-194">All messages and attachments that don't have a known virus/malware signature are routed to a special environment where ATP uses a variety of machine learning and analysis techniques to detect malicious intent.</span></span> <span data-ttu-id="2f54e-195">의심스러운 활동이 감지되지 않으면 메시지가 사서함 배달을 위해 릴리스됩니다.</span><span class="sxs-lookup"><span data-stu-id="2f54e-195">If no suspicious activity is detected, the message is released for delivery to the mailbox.</span></span>

> [!NOTE]
> <span data-ttu-id="2f54e-196">ATP 안전한 첨부 파일 검사는 Office 365 데이터가 있는 동일한 지역에서 발생 합니다.</span><span class="sxs-lookup"><span data-stu-id="2f54e-196">ATP Safe Attachments scanning takes place in the same region where your Office 365 data resides.</span></span> <span data-ttu-id="2f54e-197">데이터 센터 지역에 대 한 자세한 내용은 [어디에 있습니까?](https://products.office.com/where-is-your-data-located?geo=All) 를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="2f54e-197">For more information about data center geography, see [Where is your data located?](https://products.office.com/where-is-your-data-located?geo=All)</span></span>

### <a name="safe-links"></a><span data-ttu-id="2f54e-198">안전한 링크</span><span class="sxs-lookup"><span data-stu-id="2f54e-198">Safe Links</span></span>

<span data-ttu-id="2f54e-199">[ATP Safe Links](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links) 기능은 메시지나 Office 문서의 악의적인 url 로부터 사용자를 사전에 보호 합니다.</span><span class="sxs-lookup"><span data-stu-id="2f54e-199">The [ATP Safe Links](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links) feature proactively protects your users from malicious URLs in a message or in an Office document.</span></span> <span data-ttu-id="2f54e-200">악성 링크에 액세스할 수 있는 경우 악의적인 링크가 동적으로 차단 되므로이 기능은 링크를 선택할 때마다 유지 됩니다.</span><span class="sxs-lookup"><span data-stu-id="2f54e-200">The protection remains every time they select the link, as malicious links are dynamically blocked while good links can be accessed.</span></span>

<span data-ttu-id="2f54e-201">다음과 같은 앱의 Url에 대해 안전한 링크를 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2f54e-201">Safe Links is available for URLs in the following apps:</span></span>

- <span data-ttu-id="2f54e-202">Windows 또는 Mac의 Office 365 ProPlus</span><span class="sxs-lookup"><span data-stu-id="2f54e-202">Office 365 ProPlus on Windows or Mac</span></span>

- <span data-ttu-id="2f54e-203">웹 (웹의 Word, 웹의 경우 Excel, 웹의 경우 PowerPoint, 웹의 OneNote)에 대 한 Office</span><span class="sxs-lookup"><span data-stu-id="2f54e-203">Office for the web (Word for the web, Excel for the web, PowerPoint for the web, and OneNote for the web)</span></span>

- <span data-ttu-id="2f54e-204">IOS 및 Android 장치의 Office 앱은 물론 Word, Excel, PowerPoint, Visio의 Windows</span><span class="sxs-lookup"><span data-stu-id="2f54e-204">Word, Excel, PowerPoint, and Visio on Windows, as well as Office apps on iOS and Android devices</span></span>

> [!NOTE]
> <span data-ttu-id="2f54e-205">사용자에 게 ATP<sup>\*</sup>라이선스가 있어야 하 고, Atp 안전한 링크 정책에 포함 되어야 하며, 보호를 위해 해당 장치에 로그인 되어 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="2f54e-205">Users must be licensed for ATP<sup>\*</sup>, must be included in ATP Safe Links policies, and must be signed in on their devices for protection to be in place.</span></span>
>
> <span data-ttu-id="2f54e-206"><sup>\*</sup>조직 전반의 ATP 라이선스 (예: ATP_ENTERPRISE_FACULTY)의 경우에는 개별 사용자에 게 ATP 라이선스를 할당할 필요가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="2f54e-206"><sup>\*</sup> For organization-wide ATP licenses (for example, ATP_ENTERPRISE_FACULTY), you don't need to assign ATP licenses to individual users.</span></span>
>
> <span data-ttu-id="2f54e-207">ATP 안전한 링크 보호에 대 한 자세한 내용은 [How To Safe 링크가 Office 문서의 url과 함께 작동 하는 방식을](https://docs.microsoft.com/microsoft-365/security/office-365-security/how-atp-safe-links-works#how-atp-safe-links-works-with-urls-in-office-documents)참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="2f54e-207">For more information about ATP Safe Links protection, see [How ATP Safe Links works with URLs in Office documents](https://docs.microsoft.com/microsoft-365/security/office-365-security/how-atp-safe-links-works#how-atp-safe-links-works-with-urls-in-office-documents).</span></span>

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a><span data-ttu-id="2f54e-208">SharePoint, OneDrive 및 Microsoft Teams에 대한 ATP</span><span class="sxs-lookup"><span data-stu-id="2f54e-208">ATP for SharePoint, OneDrive, and Microsoft Teams</span></span>

<span data-ttu-id="2f54e-209">[SharePoint, OneDrive 및 Microsoft 팀의 ATP](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams) 는 팀 사이트 및 문서 라이브러리에서 악의적으로 식별 된 파일을 검색 하 고 차단 하는 데 도움이 됩니다.</span><span class="sxs-lookup"><span data-stu-id="2f54e-209">[ATP for SharePoint, OneDrive, and Microsoft Teams](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)  helps detect and block files that are identified as malicious in team sites and document libraries.</span></span>

### <a name="anti-phishing-policies"></a><span data-ttu-id="2f54e-210">피싱 방지 정책</span><span class="sxs-lookup"><span data-stu-id="2f54e-210">Anti-phishing policies</span></span>

<span data-ttu-id="2f54e-211">[ATP 피싱 방지](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing) 는 메시지가 피싱 인 경우 메시지에 대 한 표시기를 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="2f54e-211">[ATP anti-phishing](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing) checks incoming messages for indicators that a message might be a phishing attempt.</span></span> <span data-ttu-id="2f54e-212">사용자에 게 ATP 정책 (안전한 첨부 파일, 안전한 링크 또는 피싱 방지)이 포함 되어 있는 경우 들어오는 메시지는 메시지를 분석 하는 여러 기계 학습 모델에 의해 평가 되며 구성 된 정책에 따라 적절 한 조치를 취할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2f54e-212">When users are covered by ATP policies (Safe Attachments, Safe Links, or anti-phishing), incoming messages are evaluated by multiple machine learning models that analyze messages and the appropriate action is taken, based on the configured policies.</span></span>

### <a name="real-time-reports"></a><span data-ttu-id="2f54e-213">실시간 보고서</span><span class="sxs-lookup"><span data-stu-id="2f54e-213">Real-time reports</span></span>

<span data-ttu-id="2f54e-214">Office 365 보안 & 준수 센터에서 사용할 수 있는 모니터링 기능 보안 및 준수 관리자가 보안 공격이 나 향상 된 수상한 작업과 같은 우선 순위가 높은 문제에 집중할 수 있도록 하는 [실시간 보고서와 정보](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp) 를 포함 합니다.</span><span class="sxs-lookup"><span data-stu-id="2f54e-214">Monitoring capabilities available in the Office 365 Security & Compliance Center include [real-time reports and insights](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp) that let your security and compliance administrators focus on high-priority issues, such as security attacks or increased suspicious activity.</span></span> <span data-ttu-id="2f54e-215">문제 영역을 강조 표시 하는 것 외에도 smart reports 및 insights에는 데이터를 보고 탐색 하 고 빠른 작업도 수행할 수 있는 권장 사항과 링크가 포함 되어 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2f54e-215">In addition to highlighting problem areas, smart reports and insights include recommendations and links to view and explore data and also take quick actions.</span></span>

### <a name="threat-trackers"></a><span data-ttu-id="2f54e-216">위협 트래커</span><span class="sxs-lookup"><span data-stu-id="2f54e-216">Threat Trackers</span></span>

<span data-ttu-id="2f54e-217">[위협 추적기](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers) 는 권한 있는 사용자에 게 조직에 영향을 줄 수 있는 cybersecurity 문제에 대 한 정보를 제공 하는 정보와 관련 된 위젯 및 뷰입니다.</span><span class="sxs-lookup"><span data-stu-id="2f54e-217">[Threat Trackers](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers) are informative widgets and views that provide authorized users with intelligence on cybersecurity issues that might impact your organization.</span></span>

### <a name="explorer"></a><span data-ttu-id="2f54e-218">Explorer</span><span class="sxs-lookup"><span data-stu-id="2f54e-218">Explorer</span></span>

<span data-ttu-id="2f54e-219">Explorer (위협 탐색기 라고도 함)는 승인 된 사용자가 최근 위협을 식별 하 고 분석할 수 있도록 하는 실시간 보고서입니다.</span><span class="sxs-lookup"><span data-stu-id="2f54e-219">Explorer (also referred to as Threat Explorer) is a real-time report that lets authorized users identify and analyze recent threats.</span></span> <span data-ttu-id="2f54e-220">기본적으로이 보고서에는 최근 7 일간의 데이터가 표시 됩니다. 그러나 보기를 수정 하 여 최근 30 일간의 데이터를 표시할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2f54e-220">By default, this report shows data for the past 7 days; however, views can be modified to show data for the past 30 days.</span></span>

<span data-ttu-id="2f54e-221">Explorer (Office 365 Advanced Threat Protection 계획 2) 및 실시간 검색 (Office 365 Advanced Threat Protection 계획 1)에 대 한 자세한 내용은 [Threat Explorer 및 실시간](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)검색을 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="2f54e-221">For more information about Explorer (in Office 365 Advanced Threat Protection Plan 2) and real-time detections (in Office 365 Advanced Threat Protection Plan 1), see [Threat Explorer (and real-time detections)](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer).</span></span>

### <a name="automated-incident-response"></a><span data-ttu-id="2f54e-222">자동 인시던트 대응</span><span class="sxs-lookup"><span data-stu-id="2f54e-222">Automated incident response</span></span>

<span data-ttu-id="2f54e-223">Office 365에서 사용할 수 있는 [자동화 된 문제 대응](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air) (AIR) 기능 현재로 서는 잘 알려진 위협에 대응 하 여 자동 조사 프로세스를 실행할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2f54e-223">[Automated incident response](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air) (AIR) capabilities available in Office 365 ATP Plan 2 enable you to run automated investigation processes in response to well known threats that exist today.</span></span> <span data-ttu-id="2f54e-224">자동화 된 특정 조사 작업을 통해 보안 운영 팀이 보다 효율적이 고 효율적으로 작동할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2f54e-224">By automated certain investigation tasks, your security operations team can operate more efficiently and effectively.</span></span> <span data-ttu-id="2f54e-225">악의적인 전자 메일 메시지 삭제와 같은 수정 작업은 보안 운영 팀의 승인에 따라 수행 됩니다.</span><span class="sxs-lookup"><span data-stu-id="2f54e-225">Remediation actions, such as deleting malicious email messages, are taken upon approval by your security operations team.</span></span> <span data-ttu-id="2f54e-226">자세한 내용은 [Office 365에서 AIR works](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office)를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="2f54e-226">To learn more, see [How AIR works in Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office).</span></span>

### <a name="attack-simulator"></a><span data-ttu-id="2f54e-227">공격 시뮬레이터</span><span class="sxs-lookup"><span data-stu-id="2f54e-227">Attack Simulator</span></span>

<span data-ttu-id="2f54e-228">[공격 시뮬레이터](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator) 를 사용 하면 권한 있는 사용자가 조직에서 현실적인 공격 시나리오를 실행할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2f54e-228">[Attack Simulator](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator) lets authorized users run realistic attack scenarios in your organization.</span></span> <span data-ttu-id="2f54e-229">표시 이름 스피어 피싱 공격, 암호 분무 공격, 무작위 암호 공격 등 다양 한 유형의 공격을 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2f54e-229">Several different kinds of attacks are available, including a display name spear-phishing attack, a password-spray attack, and a brute-force password attack.</span></span>
