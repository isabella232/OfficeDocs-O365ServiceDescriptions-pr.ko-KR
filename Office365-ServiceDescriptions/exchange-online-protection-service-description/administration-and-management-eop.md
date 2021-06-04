---
title: 관리 및 관리 Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- administration-and-management-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: b9448f39-5e8a-48a4-80bc-b12b6fb72544
description: 이 문서에서는 EOP(Microsoft Exchange Online 보호) 관리자가 사용할 수 있는 관리 인터페이스에 대해 설명합니다.
ms.openlocfilehash: f4b1aa1e9345740528763ff45a3fc99858fbd71a
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653070"
---
# <a name="administration-and-management-in-exchange-online-protection"></a><span data-ttu-id="a9f46-103">관리 및 관리 Exchange Online Protection</span><span class="sxs-lookup"><span data-stu-id="a9f46-103">Administration and management in Exchange Online Protection</span></span>

<span data-ttu-id="a9f46-104">이 문서에서는 EOP(Microsoft Exchange Online 보호) 관리자가 사용할 수 있는 관리 인터페이스에 대해 설명합니다.</span><span class="sxs-lookup"><span data-stu-id="a9f46-104">This article describes management interfaces that are available to Microsoft Exchange Online Protection (EOP) administrators.</span></span>
  
<span data-ttu-id="a9f46-105">모든 EOP 기능에 대한 정보를 찾고 있나요?</span><span class="sxs-lookup"><span data-stu-id="a9f46-105">Looking for information about all EOP features?</span></span> <span data-ttu-id="a9f46-106">자세한 [내용은 Exchange Online Protection 설명을 참조하세요.](exchange-online-protection-service-description.md)</span><span class="sxs-lookup"><span data-stu-id="a9f46-106">See the [Exchange Online Protection service description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="access-to-the-microsoft-365-admin-center"></a><span data-ttu-id="a9f46-107">Microsoft 365 관리 센터에 액세스</span><span class="sxs-lookup"><span data-stu-id="a9f46-107">Access to the Microsoft 365 admin center</span></span>

<span data-ttu-id="a9f46-108">Microsoft 365 관리 센터는 각 회사의 서비스 관리자가 구독하는 각 조직의 사용자 계정 및 설정을 관리할 Microsoft 서비스 웹 포털입니다.</span><span class="sxs-lookup"><span data-stu-id="a9f46-108">The Microsoft 365 admin center is the web portal from which each company's service administrator can manage user accounts and settings for each of the Microsoft services to which they subscribe.</span></span> <span data-ttu-id="a9f46-109">관리자는 Microsoft 365 관리 센터 내에서 EAC에 대한 링크를 따라 이동하여 EOP 관련 설정을 관리할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="a9f46-109">From within the Microsoft 365 admin center, administrators can follow links to the EAC, where they can manage settings specific to EOP.</span></span>
  
## <a name="access-to-the-exchange-admin-center"></a><span data-ttu-id="a9f46-110">Exchange 관리 센터 액세스</span><span class="sxs-lookup"><span data-stu-id="a9f46-110">Access to the Exchange admin center</span></span>

<span data-ttu-id="a9f46-111">EAC(Exchange 관리 센터)는 쉽게 사용할 수 있는 단일 통합형 관리 콘솔로, 모든 유형의 배포에 최적화되어 있습니다.</span><span class="sxs-lookup"><span data-stu-id="a9f46-111">The Exchange admin center (EAC) is a single unified management console that allows for ease of use and is optimized for all types of deployments.</span></span> <span data-ttu-id="a9f46-112">새롭게 개선된 EAC는 Forefront Online Protection for Exchange 관리 센터를 대체합니다.</span><span class="sxs-lookup"><span data-stu-id="a9f46-112">The new and improved EAC replaces the Forefront Online Protection for Exchange Administration Center.</span></span> <span data-ttu-id="a9f46-113">EAC는 Microsoft 365 제품(Microsoft Exchange Online 및 Microsoft Exchange Server)에서 일관되고 원활한 Exchange UI 환경을 Microsoft Exchange Online 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="a9f46-113">EAC provides a tighter integration with Microsoft 365 and a consistent, seamless UI experience across Exchange products (Microsoft Exchange Online and Microsoft Exchange Server 2013).</span></span> <span data-ttu-id="a9f46-114">EAC에 대한 자세한 내용은 [Exchange Online Protection의 Exchange 관리 센터](/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="a9f46-114">For more information about the EAC, see [Exchange Admin Center in Exchange Online Protection](/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop).</span></span>
  
## <a name="remote-windows-powershell-access"></a><span data-ttu-id="a9f46-115">원격 Windows PowerShell 액세스</span><span class="sxs-lookup"><span data-stu-id="a9f46-115">Remote Windows PowerShell access</span></span>

 <span data-ttu-id="a9f46-p104">관리자는 원격 Windows PowerShell을 사용하여 명령줄에서 관리 작업을 수행할 수 있습니다. 원격 Shell 세션 만들기와 각 cmdlet 설명서 관련 정보 등 Windows PowerShell의 사용 방법에 대한 자세한 내용은 [Exchange Online PowerShell](/powershell/exchange/exchange-online-powershell)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="a9f46-p104">Administrators can use Remote Windows PowerShell to perform management tasks from the command line. For more information about how to use Windows PowerShell, including information about creating a remote Shell session and documentation about each cmdlet, see [Exchange Online PowerShell](/powershell/exchange/exchange-online-powershell).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="a9f46-118">기능 가용성</span><span class="sxs-lookup"><span data-stu-id="a9f46-118">Feature availability</span></span>

<span data-ttu-id="a9f46-119">계획, 독립 실행형 옵션 및온-프레미스 솔루션에 대한 기능 가용성을 확인 내용은 Exchange Online Protection [설명을 참조하세요.](exchange-online-protection-service-description.md)</span><span class="sxs-lookup"><span data-stu-id="a9f46-119">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online Protection service description](exchange-online-protection-service-description.md).</span></span>
