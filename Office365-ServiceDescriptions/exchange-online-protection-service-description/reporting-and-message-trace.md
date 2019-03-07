---
title: 보고 및 메시지 추적
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- reporting-and-message-trace-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: b9263f99-5921-44fd-bb4c-0d487b59a656
description: Microsoft EOP(Exchange Online Protection)에서는 조직의 전체 상태를 확인할 수 있는 다양한 보고서를 제공합니다. 일부 보고서는 Microsoft 365 관리 센터에서 사용할 수 있고, 일부는 EAC (Exchange 관리 센터)에서 사용할 수 있습니다.
ms.openlocfilehash: 9ad043776baf9c9a2e5ea8ca7cead0811ca66d3a
ms.sourcegitcommit: 68eee0c2885fd112e37eea27370c3f8c1f0831cb
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/07/2019
ms.locfileid: "30466825"
---
# <a name="reporting-and-message-trace"></a><span data-ttu-id="7121b-104">보고 및 메시지 추적</span><span class="sxs-lookup"><span data-stu-id="7121b-104">Reporting and Message Trace</span></span>

<span data-ttu-id="7121b-105">Microsoft EOP(Exchange Online Protection)에서는 조직의 전체 상태를 확인할 수 있는 다양한 보고서를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7121b-105">Microsoft Exchange Online Protection (EOP) offers many different reports that can help you determine the overall status and health of your organization.</span></span> <span data-ttu-id="7121b-106">일부 보고서는 Microsoft 365 관리 센터에서 사용할 수 있고, 일부는 EAC (Exchange 관리 센터)에서 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7121b-106">Some reports are available in the Microsoft 365 admin center, while others are available in the Exchange admin center (EAC).</span></span>
  
<span data-ttu-id="7121b-107">모든 EOP 기능에 대 한 정보를 찾으십니까?</span><span class="sxs-lookup"><span data-stu-id="7121b-107">Looking for information about all EOP features?</span></span> <span data-ttu-id="7121b-108">[Exchange Online Protection 서비스 설명을](exchange-online-protection-service-description.md)참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="7121b-108">See the [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="microsoft-365-admin-center-reports"></a><span data-ttu-id="7121b-109">Microsoft 365 관리 센터 보고서</span><span class="sxs-lookup"><span data-stu-id="7121b-109">Microsoft 365 admin center reports</span></span>
<span data-ttu-id="7121b-110"><a name="BKMK_office365admincenterreports"> </a></span><span class="sxs-lookup"><span data-stu-id="7121b-110"></span></span>

<span data-ttu-id="7121b-111">Microsoft 365 관리 센터의 보고서 페이지에서는 메시지 트래픽, 스팸 및 맬웨어 감지, Exchange 전송 규칙이 나 DLP (데이터 손실 방지) 정책의 영향을 받는 메시지에 대 한 정보를 제공 합니다.</span><span class="sxs-lookup"><span data-stu-id="7121b-111">The Reports page in the Microsoft 365 admin center provides information about message traffic, spam and malware detections, and messages affected by Exchange Transport Rules or Data Loss Prevention (DLP) policies.</span></span> <span data-ttu-id="7121b-112">보호, 규칙 및 DLP에 대한 향상된 보고서에서는 EOP 관리자에게 대화형 보고 환경이 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="7121b-112">The enhanced reports for protection, rules, and DLP offer an interactive reporting experience for EOP admins.</span></span> <span data-ttu-id="7121b-113">이러한 보고서에서는 개별 메시지에 대한 세부 정보로 드릴다운할 수 있는 기능과 함께 요약 데이터가 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="7121b-113">These reports provide summary data and the ability to drill down into details about individual messages.</span></span>
  
<span data-ttu-id="7121b-114">이러한 보고서에 대한 자세한 내용은 [Office 365의 메일 보호 보고서를 사용하여 맬웨어, 스팸 및 규칙 감지에 대한 데이터 보기](https://go.microsoft.com/fwlink/p/?LinkID=401102)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="7121b-114">For more detailed information about these reports, see [Use mail protection reports in Office 365 to view data about malware, spam and rule detections](https://go.microsoft.com/fwlink/p/?LinkID=401102).</span></span>
  
## <a name="excel-download-application-reports"></a><span data-ttu-id="7121b-115">Excel download application reports</span><span class="sxs-lookup"><span data-stu-id="7121b-115">Excel download application reports</span></span>
<span data-ttu-id="7121b-116"><a name="BKMK_exceldownloadapplicationreports"> </a></span><span class="sxs-lookup"><span data-stu-id="7121b-116"></span></span>

<span data-ttu-id="7121b-117">드릴다운 기능이 있는 요약 보고서가 제공되는 Excel 2013 보호 통합 문서에서도 전자 메일 보호 보고서를 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7121b-117">Email protection reports are also available in the Excel 2013 reporting workbook, which provides summary reports with drill-down capabilities.</span></span> <span data-ttu-id="7121b-118">그러나 향상 된 Microsoft 365 관리 센터 보고서를 대신 사용 하는 것이 좋습니다.</span><span class="sxs-lookup"><span data-stu-id="7121b-118">However, we recommend using the enhanced Microsoft 365 admin center reports instead.</span></span> <span data-ttu-id="7121b-119">Excel 2013 보고 통합 문서는 향후 더 이상 사용되지 않을 예정입니다.</span><span class="sxs-lookup"><span data-stu-id="7121b-119">The Excel 2013 reporting workbook is planned to be deprecated in the future.</span></span> 
  
<span data-ttu-id="7121b-p106">개요에 대한 자세한 내용과 통합 문서를 다운로드 및 설치하기 위한 링크는 [Office 365용 메일 보호 보고서](https://go.microsoft.com/fwlink/p/?LinkId=271776)를 참조하세요. 통합 문서 사용 방법에 대한 자세한 내용은 [Excel 보고 통합 문서를 사용한 메일 보호 보고서](https://go.microsoft.com/fwlink/p/?LinkId=285211)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="7121b-p106">For more overview information and links to download and install the workbook, see [Mail Protection Reports for Office 365](https://go.microsoft.com/fwlink/p/?LinkId=271776). For information about how to use the workbook, see [Mail Protection Reports Using the Excel Reporting Workbook](https://go.microsoft.com/fwlink/p/?LinkId=285211).</span></span>
  
## <a name="reporting-using-web-services"></a><span data-ttu-id="7121b-122">Reporting using web services</span><span class="sxs-lookup"><span data-stu-id="7121b-122">Reporting using web services</span></span>
<span data-ttu-id="7121b-123"><a name="BKMK_reportingusingwebservices"> </a></span><span class="sxs-lookup"><span data-stu-id="7121b-123"></span></span>

<span data-ttu-id="7121b-p107">EOP 독립 실행형 고객에게는 제공되지 않습니다. REST/OData 테넌트 보고 웹 서비스를 사용하여 메시징 데이터에 대한 요약 및 상세 보고서를 프로그래밍 방식으로 수집할 수 있으며, 사용자 지정 관리 웹 포털의 웹 페이지에 데이터를 표시할 수 있습니다. 자세한 내용은 [Office 365 보고 웹 서비스](https://go.microsoft.com/fwlink/?LinkId=279926)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="7121b-p107">Not available to EOP standalone customers. You can use the REST/OData Tenant Reporting Web service to programmatically collect summary and detailed reports about messaging data, and you can display the data on a web page in a custom management Web portal. For more information, see [Office 365 Reporting Web Services](https://go.microsoft.com/fwlink/?LinkId=279926).</span></span>
  
## <a name="message-trace"></a><span data-ttu-id="7121b-127">Message trace</span><span class="sxs-lookup"><span data-stu-id="7121b-127">Message trace</span></span>
<span data-ttu-id="7121b-128"><a name="BKMK_messagetrace"> </a></span><span class="sxs-lookup"><span data-stu-id="7121b-128"></span></span>

<span data-ttu-id="7121b-p108">관리자는 EAC의 메시지 추적 기능을 사용하여 EOP를 통과하는 전자 메일 메시지를 추적할 수 있습니다. 이렇게 하면 서비스에서 대상 전자 메일 메시지를 수신, 거부, 지연 또는 배달했는지 여부를 확인하는 데 도움이 되며, 또한 메시지가 최종 상태에 도달하기 전 메시지에 수행된 작업을 확인할 수 있습니다. 특정 메시지에 대한 자세한 정보를 파악하면 사용자 질문에 효과적으로 대답하고, 메일 흐름 문제를 해결하며, 정책 변경 사항의 유효성을 검사할 수 있을 뿐만 아니라 기술 지원 서비스에 지원을 문의해야 하는 수고를 덜 수 있습니다. 자세한 내용은 [전자 메일 메시지 추적](https://go.microsoft.com/fwlink/p/?LinkID=282262)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="7121b-p108">The message trace feature in the EAC enables you as an administrator to follow email messages as they pass through the EOP. It helps you determine whether a targeted email message was received, rejected, deferred, or delivered by the service. It also shows what actions have occurred to the message before reaching its final status. Obtaining detailed information about a specific message lets you efficiently answer your user's questions, troubleshoot mail flow issues, validate policy changes, and alleviates the need to contact technical support for assistance. For more information, see [Trace an Email Message](https://go.microsoft.com/fwlink/p/?LinkID=282262).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="7121b-134">기능 가용성</span><span class="sxs-lookup"><span data-stu-id="7121b-134">Feature Availability</span></span>
<span data-ttu-id="7121b-135"><a name="BKMK_messagetrace"> </a></span><span class="sxs-lookup"><span data-stu-id="7121b-135"></span></span>

<span data-ttu-id="7121b-136">Office 365 계획, 독립 실행형 옵션 및 온-프레미스 솔루션별로 기능 가용성을 확인하려면 [Exchange Online Protection 서비스 설명](exchange-online-protection-service-description.md)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="7121b-136">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  

