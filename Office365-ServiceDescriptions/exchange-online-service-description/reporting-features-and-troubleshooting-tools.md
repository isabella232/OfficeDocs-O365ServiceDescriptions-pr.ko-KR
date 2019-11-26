---
title: 보고 기능 및 문제 해결 도구
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-reporting-features-and-troubleshooting-tools
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7a89aaf4-747a-434a-a20b-ebc1ee10c742
description: Microsoft Exchange Online은 EAC (Exchange 관리 센터)에 대 한 다양 한 보고 기능을 제공 합니다.
ms.openlocfilehash: d7560a95d127731bc8354c8be73aa016ee0aecfd
ms.sourcegitcommit: 2b9f68f7731dfd6f9d3f33e31e6303e81985ebb2
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 11/26/2019
ms.locfileid: "39262711"
---
# <a name="reporting-features-and-troubleshooting-tools"></a><span data-ttu-id="d6623-103">보고 기능 및 문제 해결 도구</span><span class="sxs-lookup"><span data-stu-id="d6623-103">Reporting features and troubleshooting tools</span></span>

<span data-ttu-id="d6623-104">Microsoft Exchange Online은 EAC (Exchange 관리 센터)에 대 한 다양 한 보고 기능을 제공 합니다.</span><span class="sxs-lookup"><span data-stu-id="d6623-104">Microsoft Exchange Online offers a variety of reporting features both in and out of the Exchange admin center (EAC).</span></span>
  
## <a name="reporting-features"></a><span data-ttu-id="d6623-105">보고 기능</span><span class="sxs-lookup"><span data-stu-id="d6623-105">Reporting features</span></span>

<span data-ttu-id="d6623-106">Exchange Online 고객은 Excel 보고 통합 문서를 다운로드 하거나 웹 서비스를 사용 하 여 Microsoft 365 관리 센터의 보고서에 액세스할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d6623-106">Exchange Online customers can access reports in the Microsoft 365 admin center, by downloading an Excel reporting workbook, or by using web services.</span></span>
  
### <a name="reporting-in-the-microsoft-365-admin-center"></a><span data-ttu-id="d6623-107">Microsoft 365 관리 센터의 보고 기능</span><span class="sxs-lookup"><span data-stu-id="d6623-107">Reporting in the Microsoft 365 admin center</span></span>

<span data-ttu-id="d6623-108">Microsoft 365 관리 센터의 보고서 페이지에는 사서함 및 그룹에 대 한 요약 정보를 제공 하는 보고서가 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d6623-108">There are reports on the Reports page in the Microsoft 365 admin center that provide summary information about mailboxes and groups.</span></span> <span data-ttu-id="d6623-109">예를 들어 한 보고서에는 일, 주, 월 또는 연도에 따라 만들고 삭제 한 그룹 수가 나열 됩니다.</span><span class="sxs-lookup"><span data-stu-id="d6623-109">For example, one report lists the number of groups created and deleted by day, week, month, or year.</span></span> <span data-ttu-id="d6623-110">또한 새 사서함 및 삭제 된 우편함 및 활성 및 비활성 사서함에 대 한 요약 보고서도 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d6623-110">There are also summary reports for new and deleted mailboxes, and active and inactive mailboxes.</span></span> 
  
<span data-ttu-id="d6623-111">또한 Microsoft 365 관리 센터의 보고서 페이지에는 메시지 트래픽, 스팸 및 맬웨어 감지, Exchange 전송 규칙이 나 DLP (데이터 손실 방지)의 영향을 받는 메시지에 대 한 정보를 제공 하는 메시징 데이터 보고서가 포함 되어 있습니다. 정책도.</span><span class="sxs-lookup"><span data-stu-id="d6623-111">Additionally, the Reports page in the Microsoft 365 admin center contains messaging data reports, which provide information about message traffic, spam and malware detections, and messages affected by Exchange Transport Rules or Data Loss Prevention (DLP) policies.</span></span> <span data-ttu-id="d6623-112">보호, 규칙 및 DLP에 대한 향상된 보고서에서는 Exchange Online 관리자에게 대화형 보고 환경이 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="d6623-112">The enhanced reports for protection, rules, and DLP offer an interactive reporting experience for Exchange Online admins.</span></span> <span data-ttu-id="d6623-113">이러한 보고서에서는 개별 메시지에 대한 세부 정보로 드릴다운할 수 있는 기능과 함께 요약 데이터가 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="d6623-113">These reports provide summary data and the ability to drill down into details about individual messages.</span></span>
  
<span data-ttu-id="d6623-114">각 Office 365 구독에 사용할 수 있는 보고서에 대한 자세한 내용은 [보고서](../office-365-platform-service-description/reports.md)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="d6623-114">For more information about which reports are available with each Office 365 subscription, see [Reports](../office-365-platform-service-description/reports.md).</span></span> <span data-ttu-id="d6623-115">Microsoft 365 관리 센터의 보고서 페이지에 대 한 자세한 내용은 [view and download the office 365의 서비스 사용 현황에 대 한 보고서 보기 및 다운로드](https://go.microsoft.com/fwlink/p/?LinkId=401187) [365 및 맬웨어, 스팸 및 규칙 감지에 대 한 데이터 보기를](https://go.microsoft.com/fwlink/p/?LinkID=401102)참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="d6623-115">For more detailed information about the Reports page in the Microsoft 365 admin center, see [View and download reports about service usage in Office 365](https://go.microsoft.com/fwlink/p/?LinkId=401187) and [Use mail protection reports in Office 365 to view data about malware, spam, and rule detections](https://go.microsoft.com/fwlink/p/?LinkID=401102).</span></span>
  
### <a name="reporting-using-the-excel-reporting-workbook"></a><span data-ttu-id="d6623-116">Excel 보고 통합 문서를 사용하여 보고</span><span class="sxs-lookup"><span data-stu-id="d6623-116">Reporting using the Excel reporting workbook</span></span>

<span data-ttu-id="d6623-117">Excel 2013 보고 통합 문서를 사용하여 드릴다운 기능을 통해 요약 보고서를 확인할 수도 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d6623-117">You can also use the Excel 2013 reporting workbook to view summary reports with drill-down capabilities.</span></span> <span data-ttu-id="d6623-118">그러나 향상 된 Microsoft 365 관리 센터 보고서를 대신 사용 하는 것이 좋습니다.</span><span class="sxs-lookup"><span data-stu-id="d6623-118">However, we recommend using the enhanced Microsoft 365 admin center reports instead.</span></span> <span data-ttu-id="d6623-119">Excel 2013 보고 통합 문서는 향후 더 이상 사용되지 않을 예정입니다.</span><span class="sxs-lookup"><span data-stu-id="d6623-119">The Excel 2013 reporting workbook is planned to be deprecated in the future.</span></span> <span data-ttu-id="d6623-120">개요에 대한 자세한 내용과 통합 문서를 다운로드 및 설치하기 위한 링크는 다음 [다운로드 페이지](https://go.microsoft.com/fwlink/p/?LinkId=271776)를 참조하십시오.</span><span class="sxs-lookup"><span data-stu-id="d6623-120">For more overview information and links to download and install the workbook, see the following [download page](https://go.microsoft.com/fwlink/p/?LinkId=271776).</span></span> <span data-ttu-id="d6623-121">통합 문서 사용 방법에 대한 자세한 내용은 [Excel 보고 통합 문서를 사용한 메일 보호 보고서](https://go.microsoft.com/fwlink/p/?LinkId=285211)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="d6623-121">For information about how to use the workbook, see [Mail Protection Reports Using the Excel Reporting Workbook](https://go.microsoft.com/fwlink/p/?LinkId=285211).</span></span> 
  
### <a name="reporting-using-web-services"></a><span data-ttu-id="d6623-122">Reporting using web services</span><span class="sxs-lookup"><span data-stu-id="d6623-122">Reporting using web services</span></span>

<span data-ttu-id="d6623-123">사용자 지정 보고서를 만들 수 있는 프로그래밍 인터페이스인 REST/OData 테 넌 트 보고 웹 서비스를 사용 하 여 사서함, 그룹 및 메시징 데이터에 대 한 요약 및 상세 보고서에 모두 액세스할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d6623-123">Access to both summary and detailed reports about mailboxes, groups, and messaging data is available by using the REST/OData Tenant Reporting web service, which is a programmatic interface that lets you create custom reports.</span></span> <span data-ttu-id="d6623-124">자세한 내용은 [Office 365 Reporting web services](https://go.microsoft.com/fwlink/p/?LinkId=287041)를 참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="d6623-124">For more information, see [Office 365 Reporting web services](https://go.microsoft.com/fwlink/p/?LinkId=287041).</span></span>
  
## <a name="reporting-features-and-troubleshooting-tools-in-the-eac"></a><span data-ttu-id="d6623-125">EAC의 보고 기능 및 문제 해결 도구</span><span class="sxs-lookup"><span data-stu-id="d6623-125">Reporting features and troubleshooting tools in the EAC</span></span>

<span data-ttu-id="d6623-126">Exchange 관리 센터에서 다음 보고 기능 및 문제 해결 도구를 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d6623-126">The following reporting features and troubleshooting tools are available in the Exchange admin center.</span></span>
  
### <a name="trace-an-email-message"></a><span data-ttu-id="d6623-127">전자 메일 메시지 추적</span><span class="sxs-lookup"><span data-stu-id="d6623-127">Trace an email message</span></span>

<span data-ttu-id="d6623-128">메시지 추적 기능을 사용 하면 관리자가 Exchange Online 서비스를 통과 하는 전자 메일 메시지를 팔 로우 할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d6623-128">The message trace feature lets you, as an administrator, follow email messages as they pass through your Exchange Online service.</span></span> <span data-ttu-id="d6623-129">이를 통해 대상이 지정 된 전자 메일 메시지의 수신, 거부, 지연 또는 서비스에 의해 전달 되었는지 여부를 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d6623-129">It helps you determine whether a targeted email message was received, rejected, deferred, or delivered by the service.</span></span> <span data-ttu-id="d6623-130">이를 통해 사용자의 질문에 효과적으로 대답 하 고 메일 흐름 문제를 해결할 수 있으며 기술 지원 서비스에 문의 하 여 도움을 받을 필요가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="d6623-130">This lets you efficiently answer your users' questions and troubleshoot mail flow issues, and alleviates the need to contact technical support for assistance.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="d6623-p107">일반 문제 및 추세 문제를 해결하려면 보고 도구를 사용하여 해당 데이터를 가져옵니다. 메시지에 대한 세부 정보가 필요한 단일 지점에 대해서는 메시지 추적 도구를 사용합니다.</span><span class="sxs-lookup"><span data-stu-id="d6623-p107">For troubleshooting general issues and trends, use the reporting tools to obtain such data. For single point specifics where details are needed about a message, use the message trace tool.</span></span> 
  
<span data-ttu-id="d6623-133">메시지 추적 기능에 대한 자세한 내용은 [전자 메일 메시지 추적](https://go.microsoft.com/fwlink/p/?LinkId=271777)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="d6623-133">For more information about the message trace feature, see [Trace an Email Message](https://go.microsoft.com/fwlink/p/?LinkId=271777).</span></span>
  
### <a name="auditing-reports"></a><span data-ttu-id="d6623-134">감사 보고서</span><span class="sxs-lookup"><span data-stu-id="d6623-134">Auditing reports</span></span>

<span data-ttu-id="d6623-p108">감사 로깅을 사용하면 관리자가 수행한 특정 변경을 추적하여 구성 문제를 해결하고 규정, 준수 및 소송 요구 사항을 따르는 데 도움이 될 수 있습니다. Exchange Online에서는 두 가지 유형의 감사 로깅을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="d6623-p108">You can use audit logging to troubleshoot configuration issues by tracking specific changes made by administrators and to help you meet regulatory, compliance, and litigation requirements. Exchange Online provides two types of audit logging:</span></span>
  
- <span data-ttu-id="d6623-p109">관리자 감사 로깅은 관리자가 수행한 작업을 기록합니다. 따라서 구성 문제를 해결하거나 보안 관련 또는 준수 관련 문제의 원인을 파악하는 데 도움이 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d6623-p109">Administrator audit logging records any action performed by an administrator. This can help you troubleshoot configuration issues or identify the cause of security-related or compliance-related problems.</span></span> 
    
- <span data-ttu-id="d6623-p110">사서함 감사 로깅은 사서함 소유자 이외의 사용자가 사서함에 액세스할 때마다 기록합니다. 따라서 사서함에 액세스한 사용자와 해당 사용자가 수행한 작업을 확인하는 데 도움이 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d6623-p110">Mailbox audit logging records whenever a mailbox is accessed by someone other than the person who owns the mailbox. This can help you determine who has accessed a mailbox and what they've done.</span></span> 
    
<span data-ttu-id="d6623-141">감사 로깅에 대한 자세한 내용은 [감사 보고서](https://go.microsoft.com/fwlink/p/?LinkId=271779)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="d6623-141">For more information about audit logging, see [Auditing Reports](https://go.microsoft.com/fwlink/p/?LinkId=271779).</span></span>
  
### <a name="unified-messaging-reports"></a><span data-ttu-id="d6623-142">통합 메시징 보고서</span><span class="sxs-lookup"><span data-stu-id="d6623-142">Unified Messaging reports</span></span>

<span data-ttu-id="d6623-p111">이 보고서를 사용하여 Exchange Online 조직에서 UM(통합 메시징)을 모니터링하고 관련 문제를 해결할 수 있습니다. 자세한 내용은 [음성 사서함 호출에 대한 보고서 실행](https://go.microsoft.com/fwlink/p/?LinkId=287042)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="d6623-p111">You can use these reports to monitor and troubleshoot Unified Messaging (UM) in your Exchange Online organization. For more information, see [Run Reports for Voice Mail Calls](https://go.microsoft.com/fwlink/p/?LinkId=287042).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="d6623-145">기능 가용성</span><span class="sxs-lookup"><span data-stu-id="d6623-145">Feature availability</span></span>

<span data-ttu-id="d6623-146">Office 365 계획, 독립 실행형 옵션 및 온-프레미스 솔루션 별로 기능 가용성을 확인 하려면 [Exchange Online 서비스 설명을](exchange-online-service-description.md)참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="d6623-146">To view feature availability across Office 365 plans, standalone options, and on-premises solutions, see [Exchange Online service description](exchange-online-service-description.md).</span></span>
  

