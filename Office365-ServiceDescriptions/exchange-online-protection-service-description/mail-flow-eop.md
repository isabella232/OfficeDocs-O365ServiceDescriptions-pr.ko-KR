---
title: 메일 흐름[EOP]
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: Microsoft는 Office 365를 사용하는 대다수 조직의 사서함을 호스트하고 메일 흐름을 관리합니다. 이것은 가장 단순한 구성으로, Office 365가 모든 사서함을 관리하고 필터링한다는 것을 의미합니다. 그러나 일부 조직에서는 모든 사서함을 온-프레미스로 유지해야 할 비즈니스적 필요성을 느낍니다. EOP(Exchange Online Protection)를 사용하면 이러한 필요성이 충족되며 클라우드에서 바이러스 백신과 스팸 메일 방지 처리까지 합니다. EOP에 대한 자세한 내용과 구매 정보는 Exchange Online Protection을 참조하세요.
ms.openlocfilehash: 5a581c8004bcdc001160a2499cd623c6eee772f2
ms.sourcegitcommit: 3d180fb603896239b30d9db6ba865843c29801b0
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/10/2019
ms.locfileid: "37442733"
---
# <a name="mail-floweop"></a><span data-ttu-id="824a3-107">메일 흐름[EOP]</span><span class="sxs-lookup"><span data-stu-id="824a3-107">Mail Flow[EOP]</span></span>

<span data-ttu-id="824a3-108">Microsoft는 Office 365를 사용하는 대다수 조직의 사서함을 호스트하고 메일 흐름을 관리합니다.</span><span class="sxs-lookup"><span data-stu-id="824a3-108">For most organizations that use Office 365, we host your mailboxes and take care of mail flow.</span></span> <span data-ttu-id="824a3-109">이것은 가장 단순한 구성으로, Office 365가 모든 사서함을 관리하고 필터링한다는 것을 의미합니다.</span><span class="sxs-lookup"><span data-stu-id="824a3-109">It's the simplest configuration and means that Office 365 manages all mailboxes and filtering.</span></span> <span data-ttu-id="824a3-110">그러나 일부 조직에서는 모든 사서함을 온-프레미스로 유지해야 할 비즈니스적 필요성을 느낍니다.</span><span class="sxs-lookup"><span data-stu-id="824a3-110">However, some organizations have a business need to keep all their mailboxes on premises.</span></span> <span data-ttu-id="824a3-111">EOP(Exchange Online Protection)를 사용하면 이러한 필요성이 충족되며 클라우드에서 바이러스 백신과 스팸 메일 방지 처리까지 합니다.</span><span class="sxs-lookup"><span data-stu-id="824a3-111">Exchange Online Protection (EOP) enables you to do that and provides antivirus and anti-spam mail processing in the cloud.</span></span> <span data-ttu-id="824a3-112">EOP에 대한 자세한 내용과 구매 정보는 [Exchange Online Protection](https://products.office.com/en-us/exchange/exchange-email-security-spam-protection)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="824a3-112">For more information and to purchase EOP, go to [Exchange Online Protection](https://products.office.com/en-us/exchange/exchange-email-security-spam-protection).</span></span>
  
<span data-ttu-id="824a3-p103">도메인 관리 또는 DBEB(디렉터리 기반 Edge 차단)에 대한 정보를 확인하려면 [받는 사람, 도메인 및 회사 관리](recipient-domain-and-company-management.md)을 참조하세요. 모든 EOP 기능에 대한 자세한 내용은 [Exchange Online Protection 서비스 설명](exchange-online-protection-service-description.md)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="824a3-p103">Looking for information about domain management or Directory Based Edge Blocking (DBEB)? See [Recipient, Domain, and Company Management](recipient-domain-and-company-management.md). To learn more about all EOP features, see the [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="routing-email-between-office-365-and-your-own-email-servers"></a><span data-ttu-id="824a3-116">Office 365와 자체 메일 서버 간의 이메일 라우팅</span><span class="sxs-lookup"><span data-stu-id="824a3-116">Routing email between Office 365 and your own email servers</span></span>

<span data-ttu-id="824a3-p104">Office 365(Exchange Online 또는 EOP 포함)와 SMTP 기반 메일 서버(예: Exchange) 간에 메일 흐름을 사용하도록 커넥터를 구성할 수 있습니다. 이에 대한 자세한 정보는 [Do I need a connector](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/do-i-need-to-create-a-connector)? 및 [Set up connectors to route mail between Office 365 and your own email servers](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="824a3-p104">You can configure a connector to enable mail flow between Office 365 (including Exchange Online or EOP) and an SMTP-based email server such as Exchange. For details about this, see [Do I need a connector](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/do-i-need-to-create-a-connector)? And [Set up connectors to route mail between Office 365 and your own email servers](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail).</span></span>
  
## <a name="secure-messaging-with-a-trusted-partner"></a><span data-ttu-id="824a3-120">신뢰할 수 있는 파트너와의 보안 메시징</span><span class="sxs-lookup"><span data-stu-id="824a3-120">Secure messaging with a trusted partner</span></span>

<span data-ttu-id="824a3-121">EOP 고객은 Office 365 커넥터를 사용하여 신뢰할 수 있는 파트너와 보안 메일 흐름을 설정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="824a3-121">As an EOP customer, you can set up secure mail flow with a trusted partner by using Office 365 connectors.</span></span> <span data-ttu-id="824a3-122">Office 365는 TLS(전송 계층 보안)을 통한 보안 통신을 지원합니다.</span><span class="sxs-lookup"><span data-stu-id="824a3-122">Office 365 supports secure communication through Transport Layer Security (TLS), and you can create a connector to enforce encryption via TLS.</span></span> <span data-ttu-id="824a3-123">[TLS](https://docs.microsoft.com/microsoft-365/compliance/exchange-online-uses-tls-to-secure-email-connections) 는 인터넷을 통한 통신에 보안을 제공 하는 암호화 프로토콜입니다.</span><span class="sxs-lookup"><span data-stu-id="824a3-123">[TLS](https://docs.microsoft.com/microsoft-365/compliance/exchange-online-uses-tls-to-secure-email-connections) is a cryptographic protocol that provides security for communications over the internet.</span></span> <span data-ttu-id="824a3-124">커넥터를 사용하면 자체 서명된 인증서 또는 CA(인증 기관) 확인 인증서를 통해 강제로 받거나 보내는 TLS를 모두 구성할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="824a3-124">By using connectors, you can configure both forced incoming and outgoing TLS using self-signed or certification authority (CA)-validated certificates.</span></span> <span data-ttu-id="824a3-125">도메인 이름 또는 파트너 조직에서 메일을 보내는 IP 주소 범위를 지정하는 것과 같은 기타 보안 제한을 적용할 수도 있습니다.</span><span class="sxs-lookup"><span data-stu-id="824a3-125">You can also apply other security restrictions, such as specifying domain names or IP address ranges from which your partner organization sends mail.</span></span> 
  
<span data-ttu-id="824a3-126">자세한 내용은 [Set up connectors for secure mail flow with a partner organization](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="824a3-126">For more information, see [Set up connectors for secure mail flow with a partner organization](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner).</span></span>
  
## <a name="safe-listing-a-partners-ip-address"></a><span data-ttu-id="824a3-127">수신 허용 목록에 파트너의 IP 주소 추가</span><span class="sxs-lookup"><span data-stu-id="824a3-127">Safe listing a partner's IP address</span></span>

<span data-ttu-id="824a3-p106">신뢰할 수 있는 파트너의 IP 주소를 수신 허용 목록에 추가하여 해당 파트너가 보내는 메시지에 스팸 필터링이 적용되지 않도록 할 수 있습니다. 이렇게 하려면 연결 필터의 IP 허용 목록을 사용하면 됩니다. 자세한 내용은 [연결 필터 정책 구성](https://go.microsoft.com/fwlink/p/?LinkID=287108)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="824a3-p106">You can add a trusted partner's IP address to a safe list to ensure that messages they send to you are not subject to spam filtering. To do this, you can use the connection filter's IP Allow list. For more information, see [Configure the connection filter policy](https://go.microsoft.com/fwlink/p/?LinkID=287108).</span></span>
  
## <a name="conditional-mail-routing"></a><span data-ttu-id="824a3-131">조건부 메일 라우팅</span><span class="sxs-lookup"><span data-stu-id="824a3-131">Conditional mail routing</span></span>

<span data-ttu-id="824a3-p107">조건에 따라 메일을 특정 사이트로 라우팅하는 전송 규칙을 사용하여 커넥터를 구성할 수 있습니다. 자세한 내용은 [Scenario: Conditional email routing](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="824a3-p107">You can configure a connector with a Transport rule that routes mail to a specific site, based on conditions. For more information, see [Scenario: Conditional email routing](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing).</span></span>
  
## <a name="hybrid-mail-routing"></a><span data-ttu-id="824a3-134">하이브리드 메일 라우팅</span><span class="sxs-lookup"><span data-stu-id="824a3-134">Hybrid mail routing</span></span>

<span data-ttu-id="824a3-p108">하이브리드란 사서함의 일부분을 온-프레미스에서, 다른 일부분은 클라우드(Exchange Online)에서 호스트하는 것을 의미합니다. 독립 실행형(온-프레미스) 배포에서 하이브리드 배포로 이동할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="824a3-p108">Hybrid means that you host a portion of your mailboxes on premises, and a portion in the cloud (Exchange Online). You can move from a standalone (on-premises) deployment to a hybrid deployment.</span></span>
  
<span data-ttu-id="824a3-p109">하이브리드 배포를 사용하는 경우 EOP를 통해 클라우드 및 온-프레미스 사서함을 보호할 수 있습니다. EOP를 통해 보호되는 온-프레미스 사서함에는 독립 실행형 라이선스가 필요합니다. 하이브리드 배포의 메일 라우팅에 대한 자세한 내용은 [Exchange 하이브리드 배포의 전송 라우팅](https://go.microsoft.com/fwlink/p/?LinkId=271757)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="824a3-p109">If you have a hybrid deployment, you can protect your cloud and on-premises mailboxes with EOP. Standalone licenses are required for on-premises mailboxes, when they are protected by EOP. For more information about mail routing in a hybrid deployment, see [Transport routing in Exchange hybrid deployments](https://go.microsoft.com/fwlink/p/?LinkId=271757).</span></span>
  
<span data-ttu-id="824a3-140">[Microsoft Exchange Server 배포 도우미](https://go.microsoft.com/fwlink/p/?LinkId=287036) 또한 자세한 하이브리드 배포 프로비전 및 하이브리드 메시지 전송 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="824a3-140">The [Microsoft Exchange Server Deployment Assistant](https://go.microsoft.com/fwlink/p/?LinkId=287036) also provides detailed hybrid deployment provisioning and hybrid message transport guidance.</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="824a3-141">기능 가용성</span><span class="sxs-lookup"><span data-stu-id="824a3-141">Feature Availability</span></span>

<span data-ttu-id="824a3-142">Office 365 계획, 독립 실행형 옵션 및 온-프레미스 솔루션별로 기능 가용성을 확인하려면 [Exchange Online Protection 서비스 설명](exchange-online-protection-service-description.md)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="824a3-142">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
