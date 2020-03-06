---
title: 관리 [EOP]
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- administration-and-management-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: b9448f39-5e8a-48a4-80bc-b12b6fb72544
description: 이 섹션에서는 Microsoft EOP (Exchange Online Protection) 관리자가 사용할 수 있는 관리 인터페이스에 대해 설명 합니다.
ms.openlocfilehash: a0489e781238dd5e52fada58897bafd35e3bd7b4
ms.sourcegitcommit: b957054b6d0a96dbb2b9ced39b5c9935aa07111c
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/05/2020
ms.locfileid: "42545831"
---
# <a name="administration-and-managementeop"></a><span data-ttu-id="baea4-103">관리 [EOP]</span><span class="sxs-lookup"><span data-stu-id="baea4-103">Administration and management[EOP]</span></span>

<span data-ttu-id="baea4-104">이 섹션에서는 Microsoft EOP (Exchange Online Protection) 관리자가 사용할 수 있는 관리 인터페이스에 대해 설명 합니다.</span><span class="sxs-lookup"><span data-stu-id="baea4-104">This section describes management interfaces that are available to Microsoft Exchange Online Protection (EOP) administrators.</span></span>
  
<span data-ttu-id="baea4-105">모든 EOP 기능에 대 한 정보를 찾으십니까?</span><span class="sxs-lookup"><span data-stu-id="baea4-105">Looking for information about all EOP features?</span></span> <span data-ttu-id="baea4-106">[Exchange Online Protection 서비스 설명을](exchange-online-protection-service-description.md)참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="baea4-106">See the [Exchange Online Protection service description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="access-to-the-microsoft-365-admin-center"></a><span data-ttu-id="baea4-107">Microsoft 365 관리 센터에 대 한 액세스 권한</span><span class="sxs-lookup"><span data-stu-id="baea4-107">Access to the Microsoft 365 admin center</span></span>

<span data-ttu-id="baea4-108">Microsoft 365 관리 센터는 각 회사의 서비스 관리자가 구독 하는 각 Office 365 서비스에 대 한 사용자 계정 및 설정을 관리할 수 있는 웹 포털입니다.</span><span class="sxs-lookup"><span data-stu-id="baea4-108">The Microsoft 365 admin center is the web portal from which each company's service administrator can manage user accounts and settings for each of the Office 365 services to which they subscribe.</span></span> <span data-ttu-id="baea4-109">Microsoft 365 관리 센터 내에서 관리자는 EAC에 대 한 링크를 팔 로우 하 여 EOP 관련 설정을 관리할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="baea4-109">From within the Microsoft 365 admin center, administrators can follow links to the EAC, where they can manage settings specific to EOP.</span></span>
  
## <a name="access-to-the-exchange-admin-center"></a><span data-ttu-id="baea4-110">Exchange 관리 센터 액세스</span><span class="sxs-lookup"><span data-stu-id="baea4-110">Access to the Exchange admin center</span></span>

<span data-ttu-id="baea4-p103">EAC(Exchange 관리 센터)는 쉽게 사용할 수 있는 단일 통합형 관리 콘솔로, 모든 유형의 배포에 최적화되어 있습니다. 새롭게 개선된 EAC는 Forefront Online Protection for Exchange 관리 센터를 대체합니다. EAC는 Office 365와 더욱 긴밀하게 통합되며, 여러 Exchange 제품(Microsoft Exchange Online 및 Microsoft Exchange Server 2013) 전반에 걸쳐 원활하고 일관된 UI 환경을 제공합니다. EAC에 대한 자세한 내용은 [Exchange Online Protection의 Exchange 관리 센터](https://go.microsoft.com/fwlink/p/?LinkId=282381)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="baea4-p103">The Exchange admin center (EAC) is a single unified management console that allows for ease of use and is optimized for all types of deployments. The new and improved EAC replaces the Forefront Online Protection for Exchange Administration Center. EAC provides a tighter integration with Office 365 and a consistent, seamless UI experience across Exchange products (Microsoft Exchange Online and Microsoft Exchange Server 2013). For more information about the EAC, see [Exchange Admin Center in Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).</span></span>
  
## <a name="remote-windows-powershell-access"></a><span data-ttu-id="baea4-115">원격 Windows PowerShell 액세스</span><span class="sxs-lookup"><span data-stu-id="baea4-115">Remote Windows PowerShell access</span></span>

 <span data-ttu-id="baea4-p104">관리자는 원격 Windows PowerShell을 사용하여 명령줄에서 관리 작업을 수행할 수 있습니다. 원격 Shell 세션 만들기와 각 cmdlet 설명서 관련 정보 등 Windows PowerShell의 사용 방법에 대한 자세한 내용은 [Exchange Online PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=282266)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="baea4-p104">Administrators can use Remote Windows PowerShell to perform management tasks from the command line. For more information about how to use Windows PowerShell, including information about creating a remote Shell session and documentation about each cmdlet, see [Exchange Online PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=282266).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="baea4-118">기능 가용성</span><span class="sxs-lookup"><span data-stu-id="baea4-118">Feature availability</span></span>

<span data-ttu-id="baea4-119">Office 365 계획, 독립 실행형 옵션 및 온-프레미스 솔루션 별로 기능 가용성을 확인 하려면 [Exchange Online Protection 서비스 설명을](exchange-online-protection-service-description.md)참조 하세요.</span><span class="sxs-lookup"><span data-stu-id="baea4-119">To view feature availability across Office 365 plans, standalone options, and on-premises solutions, see [Exchange Online Protection service description](exchange-online-protection-service-description.md).</span></span>
  