---
title: 보고 기능 및 문제 해결 도구
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-reporting-features-and-troubleshooting-tools
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7a89aaf4-747a-434a-a20b-ebc1ee10c742
description: Microsoft Exchange Online에서는 다양 한 Exchange 관리 센터 (EAC) 및 로그 아웃 기능을 보고 합니다.
ms.openlocfilehash: b95ab58d2ec09f5e6bae32a3902e92deb75d789f
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036488"
---
# <a name="reporting-features-and-troubleshooting-tools"></a><span data-ttu-id="7bb43-103">보고 기능 및 문제 해결 도구</span><span class="sxs-lookup"><span data-stu-id="7bb43-103">Reporting Features and Troubleshooting Tools</span></span>

<span data-ttu-id="7bb43-104">Microsoft Exchange Online에서는 다양 한 Exchange 관리 센터 (EAC) 및 로그 아웃 기능을 보고 합니다.</span><span class="sxs-lookup"><span data-stu-id="7bb43-104">Microsoft Exchange Online offers a variety of reporting features both in and out of the Exchange admin center (EAC).</span></span>
  
## <a name="reporting-features"></a><span data-ttu-id="7bb43-105">보고 기능</span><span class="sxs-lookup"><span data-stu-id="7bb43-105">Reporting features</span></span>

<span data-ttu-id="7bb43-106">Exchange Online 고객은 Excel 보고 통합 문서를 다운로드하거나 웹 서비스를 사용하여 Office 365 관리 센터의 보고서에 액세스할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7bb43-106">Exchange Online customers can access reports in the Office 365 admin center, by downloading an Excel reporting workbook, or by using Web services.</span></span>
  
### <a name="reporting-in-the-office-365-admin-center"></a><span data-ttu-id="7bb43-107">Office 365 관리 센터에서 보고</span><span class="sxs-lookup"><span data-stu-id="7bb43-107">Reporting in the Office 365 admin center</span></span>

<span data-ttu-id="7bb43-p101">Microsoft Office 365 관리 센터의 보고서 페이지에는 사서함 및 그룹에 대한 요약 정보를 제공하는 보고서가 있습니다. 예를 들면, 만들어지고 삭제된 그룹의 수를 일, 주, 월 또는 연도별로 나열하는 보고서와 새 사서함과 삭제된 사서함, 활성 사서함과 비활성 사서함에 대한 요약 보고서가 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7bb43-p101">There are reports on the Reports page in the Microsoft Office 365 admin center that provide summary information about mailboxes and groups. For example, one report lists the number of groups created and deleted by day, week, month, or year. There are also summary reports for new and deleted mailboxes, and active and inactive mailboxes.</span></span> 
  
<span data-ttu-id="7bb43-p102">그뿐만 아니라 Microsoft Office 365 관리 센터의 보고서 페이지에는 메시지 트래픽, 스팸 및 맬웨어 검색, Exchange 전송 규칙이나 DLP(데이터 손실 방지)로 영향을 받는 메시지에 대한 정보가 제공되는 메시징 데이터 보고서가 있습니다. 보호, 규칙 및 DLP에 대한 향상된 보고서에서는 Exchange Online 관리자에게 대화형 보고 환경이 제공됩니다. 이러한 보고서에서는 개별 메시지에 대한 세부 정보로 드릴다운할 수 있는 기능과 함께 요약 데이터가 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="7bb43-p102">Additionally, the Reports page in the Microsoft Office 365 admin center contains messaging data reports, which provide information about message traffic, spam and malware detections, and messages affected by Exchange Transport Rules or Data Loss Prevention (DLP) policies. The enhanced reports for protection, rules, and DLP offer an interactive reporting experience for Exchange Online admins. These reports provide summary data and the ability to drill down into details about individual messages.</span></span>
  
<span data-ttu-id="7bb43-p103">각 Office 365 구독에 사용할 수 있는 보고서에 대한 자세한 내용은 [보고서](../office-365-platform-service-description/reports.md)를 참조하세요. Office 365 관리 센터의 보고서 페이지에 대한 자세한 내용은 [Office 365에서 서비스 사용에 대한 보고서 보기 및 다운로드](https://go.microsoft.com/fwlink/p/?LinkId=401187) 및 [Office 365의 메일 보호 보고서를 사용하여 맬웨어, 스팸 및 규칙 감지에 대한 데이터 보기](https://go.microsoft.com/fwlink/p/?LinkID=401102)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="7bb43-p103">For more information about which reports are available with each Office 365 subscription, see [Reports](../office-365-platform-service-description/reports.md). For more detailed information about the Reports page in the Office 365 admin center, see [View and download reports about service usage in Office 365](https://go.microsoft.com/fwlink/p/?LinkId=401187) and [Use mail protection reports in Office 365 to view data about malware, spam, and rule detections](https://go.microsoft.com/fwlink/p/?LinkID=401102).</span></span>
  
### <a name="reporting-using-the-excel-reporting-workbook"></a><span data-ttu-id="7bb43-116">Excel 보고 통합 문서를 사용하여 보고</span><span class="sxs-lookup"><span data-stu-id="7bb43-116">Reporting using the Excel reporting workbook</span></span>

<span data-ttu-id="7bb43-p104">Excel 2013 보고 통합 문서를 사용하여 드릴다운 기능을 통해 요약 보고서를 확인할 수도 있습니다. 그러나 이 보고서 대신 향상된 Office 365 관리 센터 보고서를 사용하는 것이 좋습니다. Excel 2013 보고 통합 문서는 향후 더 이상 사용되지 않을 예정입니다. 개요에 대한 자세한 내용과 통합 문서를 다운로드 및 설치하기 위한 링크는 다음 [다운로드 페이지](https://go.microsoft.com/fwlink/p/?LinkId=271776)를 참조하십시오. 통합 문서 사용 방법에 대한 자세한 내용은 [Excel 보고 통합 문서를 사용한 메일 보호 보고서](https://go.microsoft.com/fwlink/p/?LinkId=285211)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="7bb43-p104">You can also use the Excel 2013 reporting workbook to view summary reports with drill-down capabilities. However, we recommend using the enhanced Office 365 admin center reports instead. The Excel 2013 reporting workbook is planned to be deprecated in the future. For more overview information and links to download and install the workbook, see the following [download page](https://go.microsoft.com/fwlink/p/?LinkId=271776). For information about how to use the workbook, see [Mail Protection Reports Using the Excel Reporting Workbook](https://go.microsoft.com/fwlink/p/?LinkId=285211).</span></span> 
  
### <a name="reporting-using-web-services"></a><span data-ttu-id="7bb43-122">웹 서비스를 사용하여 보고</span><span class="sxs-lookup"><span data-stu-id="7bb43-122">Reporting using Web services</span></span>

<span data-ttu-id="7bb43-p105">사용자 지정 보고서를 만들 수 있는 프로그래밍 인터페이스인 REST/OData 테넌트 보고 웹 서비스를 사용하여 사서함, 그룹 및 메시징 데이터에 대한 요약 보고서와 세부 보고서에 모두 액세스할 수 있습니다. 자세한 내용은 [Office 365 보고 웹 서비스](https://go.microsoft.com/fwlink/p/?LinkId=287041)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="7bb43-p105">Access to both summary and detailed reports about mailboxes, groups, and messaging data is available by using the REST/OData Tenant Reporting Web service, which is a programmatic interface that enables you to create custom reports. For more information, see [Office 365 Reporting Web Services](https://go.microsoft.com/fwlink/p/?LinkId=287041).</span></span>
  
## <a name="reporting-features-and-troubleshooting-tools-in-the-eac"></a><span data-ttu-id="7bb43-125">EAC의 보고 기능 및 문제 해결 도구</span><span class="sxs-lookup"><span data-stu-id="7bb43-125">Reporting features and troubleshooting tools in the EAC</span></span>

<span data-ttu-id="7bb43-126">Exchange 관리 센터에서 다음 보고 기능 및 문제 해결 도구를 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7bb43-126">The following reporting features and troubleshooting tools are available in the Exchange admin center.</span></span>
  
### <a name="trace-an-email-message"></a><span data-ttu-id="7bb43-127">전자 메일 메시지 추적</span><span class="sxs-lookup"><span data-stu-id="7bb43-127">Trace an email message</span></span>

<span data-ttu-id="7bb43-p106">메시지 추적 기능을 사용하면 전자 메일 메시지가 Exchange Online 서비스를 통과할 때 관리자로서 이를 추적할 수 있습니다. 이렇게 하면 서비스에서 대상 전자 메일 메시지를 수신, 거부, 지연 또는 배달했는지 여부를 확인하는 데 도움이 되며, 사용자의 질문에 효과적으로 답변하고, 메일 흐름 문제를 해결하고, 기술 지원팀에 문의해야 하는 수고를 덜어 줍니다.</span><span class="sxs-lookup"><span data-stu-id="7bb43-p106">The message trace feature enables you as an administrator to follow email messages as they pass through your Exchange Online service. It helps you determine whether a targeted email message was received, rejected, deferred, or delivered by the service. This lets you efficiently answer your users' questions and troubleshoot mail flow issues, and alleviates the need to contact technical support for assistance.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="7bb43-p107">일반 문제 및 추세 문제를 해결하려면 보고 도구를 사용하여 해당 데이터를 가져옵니다. 메시지에 대한 세부 정보가 필요한 단일 지점에 대해서는 메시지 추적 도구를 사용합니다.</span><span class="sxs-lookup"><span data-stu-id="7bb43-p107">For troubleshooting general issues and trends, use the reporting tools to obtain such data. For single point specifics where details are needed about a message, use the message trace tool.</span></span> 
  
<span data-ttu-id="7bb43-133">메시지 추적 기능에 대한 자세한 내용은 [전자 메일 메시지 추적](https://go.microsoft.com/fwlink/p/?LinkId=271777)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="7bb43-133">For more information about the message trace feature, see [Trace an Email Message](https://go.microsoft.com/fwlink/p/?LinkId=271777).</span></span>
  
### <a name="auditing-reports"></a><span data-ttu-id="7bb43-134">감사 보고서</span><span class="sxs-lookup"><span data-stu-id="7bb43-134">Auditing reports</span></span>

<span data-ttu-id="7bb43-p108">감사 로깅을 사용하면 관리자가 수행한 특정 변경을 추적하여 구성 문제를 해결하고 규정, 준수 및 소송 요구 사항을 따르는 데 도움이 될 수 있습니다. Exchange Online에서는 두 가지 유형의 감사 로깅을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7bb43-p108">You can use audit logging to troubleshoot configuration issues by tracking specific changes made by administrators and to help you meet regulatory, compliance, and litigation requirements. Exchange Online provides two types of audit logging:</span></span>
  
- <span data-ttu-id="7bb43-p109">관리자 감사 로깅은 관리자가 수행한 작업을 기록합니다. 따라서 구성 문제를 해결하거나 보안 관련 또는 준수 관련 문제의 원인을 파악하는 데 도움이 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7bb43-p109">Administrator audit logging records any action performed by an administrator. This can help you troubleshoot configuration issues or identify the cause of security-related or compliance-related problems.</span></span> 
    
- <span data-ttu-id="7bb43-p110">사서함 감사 로깅은 사서함 소유자 이외의 사용자가 사서함에 액세스할 때마다 기록합니다. 따라서 사서함에 액세스한 사용자와 해당 사용자가 수행한 작업을 확인하는 데 도움이 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7bb43-p110">Mailbox audit logging records whenever a mailbox is accessed by someone other than the person who owns the mailbox. This can help you determine who has accessed a mailbox and what they've done.</span></span> 
    
<span data-ttu-id="7bb43-141">감사 로깅에 대한 자세한 내용은 [감사 보고서](https://go.microsoft.com/fwlink/p/?LinkId=271779)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="7bb43-141">For more information about audit logging, see [Auditing Reports](https://go.microsoft.com/fwlink/p/?LinkId=271779).</span></span>
  
### <a name="unified-messaging-reports"></a><span data-ttu-id="7bb43-142">통합 메시징 보고서</span><span class="sxs-lookup"><span data-stu-id="7bb43-142">Unified Messaging reports</span></span>

<span data-ttu-id="7bb43-p111">이 보고서를 사용하여 Exchange Online 조직에서 UM(통합 메시징)을 모니터링하고 관련 문제를 해결할 수 있습니다. 자세한 내용은 [음성 사서함 호출에 대한 보고서 실행](https://go.microsoft.com/fwlink/p/?LinkId=287042)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="7bb43-p111">You can use these reports to monitor and troubleshoot Unified Messaging (UM) in your Exchange Online organization. For more information, see [Run Reports for Voice Mail Calls](https://go.microsoft.com/fwlink/p/?LinkId=287042).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="7bb43-145">기능 가용성</span><span class="sxs-lookup"><span data-stu-id="7bb43-145">Feature Availability</span></span>

<span data-ttu-id="7bb43-146">Office 365 계획, 독립 실행형 옵션 및 온-프레미스 솔루션별로 기능 가용성을 확인하려면 [Exchange Online 서비스 설명](exchange-online-service-description.md)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="7bb43-146">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

