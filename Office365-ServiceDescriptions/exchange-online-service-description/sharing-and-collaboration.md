---
title: 공유 및 공동 작업
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-sharing-and-collaboration
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 862dab54-701f-4014-a594-0b71e03772d2
ms.openlocfilehash: 13ab2163b76b5ccc4732659a64be5fcead01dc9d
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036495"
---
# <a name="sharing-and-collaboration"></a><span data-ttu-id="35e48-102">공유 및 공동 작업</span><span class="sxs-lookup"><span data-stu-id="35e48-102">Sharing and Collaboration</span></span>

## <a name="federated-sharing"></a><span data-ttu-id="35e48-103">페더레이션 공유</span><span class="sxs-lookup"><span data-stu-id="35e48-103">Federated sharing</span></span>

<span data-ttu-id="35e48-p101">페더레이션은 페더레이션 공유를 지원하는 기본 트러스트 인프라를 나타내며 Microsoft Exchange Online 사용자가 다른 외부 페더레이션 조직의 받는 사람 또는 인터넷으로 액세스하는 사용자와 약속 있음/없음 일정 데이터 및 연락처 정보를 공유할 수 있는 방법입니다. 여기에는 Exchange Online에서도 호스트되는 조직, 외부 Microsoft Exchange Server 2010 또는 Exchange Server 2013 조직이 포함됩니다. Exchange Online 관리자는 조직 관계 및 공유 정책을 사용하여 Microsoft Outlook Web App 또는 Microsoft Outlook 2010 이상 버전에서 사용자가 일정 공유 초대를 보낼 수 있도록 설정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="35e48-p101">Federation refers to the underlying trust infrastructure that supports federated sharing, a method for Microsoft Exchange Online users to share free/busy calendar data and contact information with recipients in other external federated organizations or with users that have Internet access. These include organizations that are also hosted by Exchange Online, or external Microsoft Exchange Server 2010 or Exchange Server 2013 organizations. Using organization relationships and sharing policies, Exchange Online administrators can enable users to send calendar-sharing invitations from Microsoft Outlook Web App or Microsoft Outlook 2010 or later.</span></span>
  
> [!IMPORTANT]
>  <span data-ttu-id="35e48-p102">외부 Exchange 2010 및 Exchange 2013 조직은 페더레이션 공유 구성의 일부로 Microsoft 페더레이션 게이트웨이와의 페더레이션 트러스트를 구성해야 합니다. 그러나 Exchange Online 조직의 경우에는 Office 365 테넌트가 만들어질 때 Microsoft 페더레이션 게이트웨이와의 페더레이션 트러스트가 자동으로 만들어지므로 페더레이션 트러스트를 구성할 필요가 없습니다. >  Exchange Online 조직이 페더레이션 공유를 사용하려면 조직 관계 또는 공유 정책을 구성해야 합니다. >  페더레이션 공유에서 다른 Office 365 테넌트의 Exchange Online 조직 간 GAL(전체 액세스 목록) 공유 또는 사용자 사서함 이동은 지원되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="35e48-p102">External Exchange 2010 and Exchange 2013 organizations must configure a federation trust with the Microsoft Federation Gateway as part of configuring federated sharing. Exchange Online organizations don't have to configure a federation trust—the federation trust with the Microsoft Federation Gateway is automatically created when the Office 365 tenant is created. >  Exchange Online organizations must configure either an organization relationship or a sharing policy to enable federated sharing. >  Sharing of the global access list (GAL) or moving user mailboxes between Exchange Online organizations in different Office 365 tenants is not supported in federated sharing.</span></span> 
  
<span data-ttu-id="35e48-111">페더레이션 공유에 대한 자세한 내용은 [Exchange Online의 공유](https://go.microsoft.com/fwlink/p/?LinkId=271774)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="35e48-111">For more information about federated sharing, see [Sharing in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271774).</span></span>
  
## <a name="site-mailboxes"></a><span data-ttu-id="35e48-112">사이트 사서함</span><span class="sxs-lookup"><span data-stu-id="35e48-112">Site mailboxes</span></span>

<span data-ttu-id="35e48-p103">전자 메일과 문서는 일반적으로 두 가지 고유한 별도의 데이터 리포지토리에 보관됩니다. 대부분의 팀은 전자 메일과 문서를 사용하여 공동 작업을 수행합니다. 문제는 전자 메일과 문서가 여러 가지 클라이언트를 사용하여 액세스된다는 점입니다. 이에 따라 사용자 생산성이 감소하고 사용자 환경이 저하되는 경우가 많습니다.</span><span class="sxs-lookup"><span data-stu-id="35e48-p103">Email and documents are traditionally kept in two unique and separate data repositories. Most teams collaborate by using both email and documents. The challenge is that email and documents are accessed by using different clients. This usually results in a reduction in user productivity and a degraded user experience.</span></span>
  
<span data-ttu-id="35e48-p104">사이트 사서함은 이 문제를 해결하기 위해 시도되는 Exchange 2013의 새로운 개념입니다. 사이트 사서함은 동일한 클라이언트를 사용하여 Microsoft SharePoint 2013 문서와 Exchange 전자 메일에 대한 액세스를 허용하므로 공동 작업의 능률과 사용자 생산성을 향상합니다. 사이트 사서함의 기능은 SharePoint 2013 사이트 구성원(소유자 및 구성원), 전자 메일 메시지용 Exchange 2013 사서함 및 문서용 SharePoint 2013 사이트를 통한 공유 저장소, 프로비저닝 및 수명 주기 요구를 처리하는 관리 인터페이스 등으로 구성됩니다.</span><span class="sxs-lookup"><span data-stu-id="35e48-p104">The site mailbox is a new concept in Exchange 2013 that attempts to solve this problem. Site mailboxes improve collaboration and user productivity by using the same client interface to allow access to both Microsoft SharePoint 2013 documents and Exchange email. A site mailbox functionally consists of SharePoint 2013 site membership (owners and members), shared storage through an Exchange 2013 mailbox for email messages and a SharePoint 2013 site for documents, and a management interface that addresses provisioning and life cycle needs.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="35e48-p105">Office 365 계획에 SharePoint가 포함되어야 합니다. 사이트 사서함을 사용하려면 사용자에게 SharePoint와 Exchange 라이선스가 둘 다 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="35e48-p105">Your Office 365 plan must include SharePoint. Site mailboxes require that users have both SharePoint and Exchange licenses.</span></span> 
  
<span data-ttu-id="35e48-122">사이트 사서함에 대한 자세한 내용은 [사이트 사서함](https://go.microsoft.com/fwlink/p/?LinkId=271789)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="35e48-122">For more information about site mailboxes, see [Site Mailboxes](https://go.microsoft.com/fwlink/p/?LinkId=271789).</span></span>
  
## <a name="public-folders"></a><span data-ttu-id="35e48-123">공용 폴더</span><span class="sxs-lookup"><span data-stu-id="35e48-123">Public folders</span></span>

<span data-ttu-id="35e48-p106">Exchange Online의 공용 폴더는 기존 높은 가용성 및 저장소 기술 사서함 데이터베이스의 활용 하기 위해 현대화 된가 있습니다. 공용 폴더 아키텍처 특별히 디자인 된 사서함을 사용 하 여 계층 구조와 공용 폴더 콘텐츠를 저장 합니다. 이 별도 공용 폴더 데이터베이스를 더 이상 인지 것을 의미 합니다. 공용 폴더 복제 지금 연속 복제 모델을 사용 합니다. 계층 구조 및 콘텐츠 사서함에 대 한 고가용성 데이터 센터에서 데이터베이스 가용성 그룹 (DAG)에서 제공 됩니다. Exchange Online에서 공용 폴더 사서함 1, 000 개로 제한 됩니다. 각 공용 폴더 사서함에는 최대 저장소 크기는도 있습니다. 자세한 내용은 [Exchange Online 제한](exchange-online-limits.md)의 "사서함 폴더 제한" 섹션을 참조 하십시오. 공용 폴더 사서함 일반 사서함으로 동일한 메시지, 받는 사람 및 용량 경고 제한을 포함 됩니다. 자세한 내용은 [받는 사람](recipients.md)을 참조 하십시오.</span><span class="sxs-lookup"><span data-stu-id="35e48-p106">Public folders in Exchange Online have been modernized to take advantage of the existing high availability and storage technologies of the mailbox database. The public folder architecture uses specially designed mailboxes to store both the hierarchy and the public folder content. This means that there's no longer a separate public folder database. Public folder replication now uses the continuous replication model. High availability for the hierarchy and content mailboxes is provided by a database availability group (DAG) in the data center. In Exchange Online, you are limited to 1000 public folder mailboxes. Each public folder mailbox also has a maximum storage size. For more information, see the "Mailbox folder limits" section in [Exchange Online Limits](exchange-online-limits.md). Public folder mailboxes have the same message, recipient, and capacity alert limits as regular mailboxes. For more information, see [Recipients](recipients.md).</span></span> 
  
<span data-ttu-id="35e48-134">공용 폴더에 대한 자세한 내용은 [공용 폴더](https://go.microsoft.com/fwlink/p/?LinkId=271790)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="35e48-134">For more information about public folders, see [Public Folders](https://go.microsoft.com/fwlink/p/?LinkId=271790).</span></span>
  
## <a name="group-and-shared-mailboxes"></a><span data-ttu-id="35e48-135">그룹 및 공유 사서함</span><span class="sxs-lookup"><span data-stu-id="35e48-135">Group and Shared mailboxes</span></span>

<span data-ttu-id="35e48-p107">그룹 및 공유 사서함을 사용하면 특정 사용자 그룹이 공용 전자 메일 주소와 같은 공통 계정(예: info@contoso.com 또는 contact@contoso.com)에서 손쉽게 전자 메일을 보내고 모니터링할 수 있습니다. 그룹의 한 사람이 공유 사서함에 보낸 메시지에 회신하면 전자 메일은 개인 사용자가 아니라 공유 사서함에서 보내는 것으로 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="35e48-p107">Group and Shared mailboxes make it easy for a specific group of people to monitor and send email from a common account, like public email addresses (for example, info@contoso.com or contact@contoso.com). When a person in the group replies to a message sent to the Shared mailbox, the email appears to be from the Shared mailbox, not from the individual user.</span></span>
  
<span data-ttu-id="35e48-p108">일반적으로 그룹 또는 공유 사서함에는 별도의 사용자 라이선스가 필요하지 않습니다. 그러나 그룹 또는 공유 사서함에 대해 원본 위치 보관을 사용하도록 설정하려면 Exchange Online 계획 1 또는 Exchange Online 계획 2 라이선스를 할당해야 합니다. 이러한 라이선스가 할당되면 사서함 크기가 라이선스 계획에 따라 증가합니다. 공유 사서함에 원본 위치 보관을 적용하려면 Exchange Online 계획 2 라이선스를 할당해야 합니다. 현재는 그룹 사서함을 할당할 수 없으나 총 라이선스 수를 고려해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="35e48-p108">Typically, Group or Shared mailboxes don't require a separate user license. However, To enable In-Place Archive for a Group or Shared mailbox, you must assign an Exchange Online Plan 1 or Exchange Online Plan 2 license to it. After the license is assigned, the mailbox size increases to that of the licensed plan. To put a Shared mailbox on In-Place Hold, you must assign an Exchange Online Plan 2 license to it. Please note that Group mailboxes cannot be assigned at this time but should be accounted for in your total licenses.</span></span>
  
<span data-ttu-id="35e48-p109">원본 위치 보관은 라이선스가 적용된 단일 사용자나 엔터티의 메일을 보관하는 경우(예: 공유 사서함)에만 사용할 수 있습니다. 여러사용자나 엔터티의 메일을 저장하는 목적으로 원본 위치 보관함을 사용할 수는 없습니다. 예를 들어 IT 관리자는 공유 사서함을 만들 수 없고, 사용자가 명백히 보관을 목적으로 참조, 숨은 참조 필드 또는 전송 규칙을 통해 복사하도록 할 수 없습니다. 여러 사람이 사용하는 공유 사서함은 실제로 해당 개별 사용자의 전자 메일을 저장하지 않습니다. 여러 사용자에게 액세스 권한이 있으며 이러한 사용자는 공유 사서함으로 전자 메일을 보냅니다. 따라서 공유 사서함에 저장된 전자 메일은 공유 사서함으로서 이 사서함에서 주고받은 메일 뿐입니다.</span><span class="sxs-lookup"><span data-stu-id="35e48-p109">In-Place Archive can only be used to archive mail for a single user or entity (such as a Shared mailbox) for which a license has been applied. Using an In-Place Archive as a means of storing mail from multiple users or entities is prohibited. For example, an IT administrator can't create a Shared mailbox and have users copy it (through the Cc or Bcc field, or through a transport rule) for the explicit purpose of archiving. Note that a Shared mailbox that multiple people use does not actually store email for those individual users. Multiple users have access, and they send email as the Shared mailbox. Therefore, the only emails stored in the Shared mailbox are those sent to or from it, as the Shared mailbox.</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="35e48-149">기능 가용성</span><span class="sxs-lookup"><span data-stu-id="35e48-149">Feature Availability</span></span>

<span data-ttu-id="35e48-150">Office 365 계획, 독립 실행형 옵션 및 온-프레미스 솔루션별로 기능 가용성을 확인하려면 [Exchange Online 서비스 설명](exchange-online-service-description.md)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="35e48-150">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  
