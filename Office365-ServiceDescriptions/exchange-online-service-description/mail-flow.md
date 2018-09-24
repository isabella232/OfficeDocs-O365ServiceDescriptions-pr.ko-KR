---
title: 메일 흐름
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-mail-flow
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 8e5267e6-d224-485b-a081-c71a1fd0c4c3
description: 'Microsoft는 Office 365를 사용하는 대다수 조직의 사서함을 호스트하고 메일 흐름을 관리합니다. 이것은 가장 단순한 구성으로, Office 365가 모든 사서함을 관리하고 필터링한다는 것을 의미합니다. 그러나 일부 조직에는 특정 규정 또는 비즈니스적 필요성을 따르는지 확인하기 위하여 좀 더 복잡한 메일 흐름 설정이 필요합니다. 이러한 옵션은 여기에서 확인할 수 있습니다. '
ms.openlocfilehash: 3decc04fb4c426e161541c1d24480cc0344b0a00
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036542"
---
# <a name="mail-flow"></a><span data-ttu-id="794e6-106">메일 흐름</span><span class="sxs-lookup"><span data-stu-id="794e6-106">Mail Flow</span></span>

<span data-ttu-id="794e6-p102">Microsoft는 Office 365를 사용하는 대다수 조직의 사서함을 호스트하고 메일 흐름을 관리합니다. 이것은 가장 단순한 구성으로, Office 365가 모든 사서함을 관리하고 필터링한다는 것을 의미합니다. 그러나 일부 조직에는 특정 규정 또는 비즈니스적 필요성을 따르는지 확인하기 위하여 좀 더 복잡한 메일 흐름 설정이 필요합니다. 이러한 옵션은 여기에서 확인할 수 있습니다. </span><span class="sxs-lookup"><span data-stu-id="794e6-p102">For most organizations using Office 365, we host your mailboxes and take care of mail flow. It's the simplest configuration and means that Office 365 manages all mailboxes and filtering. However, some organizations need more complex mail flow setups to make sure that they comply with specific regulatory or business needs. You can find out about those options here.</span></span> 
  
## <a name="custom-routing-of-outbound-email"></a><span data-ttu-id="794e6-111">아웃바운드 전자 메일의 사용자 지정 라우팅</span><span class="sxs-lookup"><span data-stu-id="794e6-111">Custom routing of outbound email</span></span>

<span data-ttu-id="794e6-p103">Microsoft Exchange Online은 온-프레미스 서버 또는 호스트 서비스("스마트 호스팅"이라고도 함)를 통해 조직에서 메일 흐름을 라우팅할 수 있습니다. 이를 통해 조직은 DLP(데이터 손실 방지) 어플라이언스를 사용하여 보내는 전자 메일에 대한 사용자 지정 사후 처리를 수행하고 사설 네트워크를 통해 비즈니스 파트너에게 전자 메일을 배달합니다. Exchange Online은 또한 주소 다시 쓰기를 지원합니다. 이 기능은 보내는 전자 메일을 주소가 수정되는 온-프레미스 게이트웨이를 통해 라우팅합니다. 이 기능을 사용하면 하위 도메인을 숨겨 다중 도메인 조직의 전자 메일을 단일 도메인으로 나타나게 하거나, 파트너 릴레이 전자 메일을 조직 내부에서 보내진 것처럼 표시할 수 있습니다. 관리자는 EAC(Exchange 관리 센터) 내에서 사용자 지정 전자 메일 라우팅을 구성합니다.</span><span class="sxs-lookup"><span data-stu-id="794e6-p103">Microsoft Exchange Online can route mail flowing from your organization through an on-premises server or a hosted service (sometimes called "smart hosting"). This enables your organization to use data loss prevention (DLP) appliances, perform custom post-processing of outgoing email, and deliver email to business partners through private networks. Exchange Online also supports Address Rewrite, which routes outgoing email through an on-premises gateway that modifies the addresses. This feature enables you to hide sub-domains, make email from a multi-domain organization appear as a single domain, or make partner-relayed email appear as if it were sent from inside your organization. Administrators configure custom email routing within the Exchange admin center (EAC).</span></span>
  
<span data-ttu-id="794e6-117">자세한 내용은 [Set up connectors to route mail between Office 365 and your own email servers](http://technet.microsoft.com/library/2e93fd60-a5ef-4e64-8e62-2b862b2d1033.aspx)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="794e6-117">For more information, see [Set up connectors to route mail between Office 365 and your own email servers](http://technet.microsoft.com/library/2e93fd60-a5ef-4e64-8e62-2b862b2d1033.aspx).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="794e6-118">Exchange Online은 메일 흐름을 조직 내외부로 전달할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="794e6-118">Exchange Online can deliver mail flowing into and out of your organization.</span></span> 
  
## <a name="secure-messaging-with-a-trusted-partner"></a><span data-ttu-id="794e6-119">신뢰할 수 있는 파트너와의 보안 메시징</span><span class="sxs-lookup"><span data-stu-id="794e6-119">Secure messaging with a trusted partner</span></span>

<span data-ttu-id="794e6-p104">Exchange Online 고객은 Office 365 커넥터를 사용하여 신뢰할 수 있는 파트너와 보안 메일 흐름을 설정할 수 있습니다. Office 365는 TLS(전송 계층 보안)을 통한 보안 통신을 지원합니다. TLS를 통해 암호화를 적용하기 위해 커넥터를 만들 수 있습니다.[TLS](https://technet.microsoft.com/en-us/library/mt163898.aspx)는 인터넷을 통한 통신에 보안을 제공하는 암호화 프로토콜입니다. 커넥터를 사용하면 자체 서명된 인증서 또는 CA(인증 기관) 확인 인증서를 통해 강제로 받거나 보내는 TLS를 모두 구성할 수 있습니다. 도메인 이름 또는 파트너 조직에서 메일을 보내는 IP 주소 범위를 지정하는 것과 같은 기타 보안 제한을 적용할 수도 있습니다.</span><span class="sxs-lookup"><span data-stu-id="794e6-p104">As an Exchange Online customer, you can set up secure mail flow with a trusted partner by using Office 365 connectors. Office 365 supports secure communication through Transport Layer Security (TLS), and you can create a connector to enforce encryption via TLS. [TLS](https://technet.microsoft.com/en-us/library/mt163898.aspx) is a cryptographic protocol that provides security for communications over the Internet. By using connectors, you can configure both forced incoming and outgoing TLS using self-signed or certification authority (CA)-validated certificates. You can also apply other security restrictions, such as specifying domain names or IP address ranges from which your partner organization sends mail.</span></span> 
  
<span data-ttu-id="794e6-125">자세한 내용은 [Set up connectors for secure mail flow with a partner organization](http://technet.microsoft.com/library/1ce4d6a4-41ba-4d1e-9ca9-e826252c1041.aspx)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="794e6-125">For more information, see [Set up connectors for secure mail flow with a partner organization](http://technet.microsoft.com/library/1ce4d6a4-41ba-4d1e-9ca9-e826252c1041.aspx).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="794e6-126">CA 확인 인증서가 필요할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="794e6-126">A CA-validated certificate may be required.</span></span> 
  
## <a name="conditional-mail-routing"></a><span data-ttu-id="794e6-127">조건부 메일 라우팅</span><span class="sxs-lookup"><span data-stu-id="794e6-127">Conditional mail routing</span></span>

<span data-ttu-id="794e6-p105">커넥터와 전송 규칙을 사용하여 메일을 특정 사이트에 전송할 수 있습니다. 기준 기반 라우팅을 사용하면 특정 조건에 따라 커넥터를 선택할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="794e6-p105">You can direct mail to specific sites by using connectors and transport rules. With criteria-based routing, you can choose a connector based on specific conditions.</span></span>
  
<span data-ttu-id="794e6-130">자세한 내용은 [Scenario: Conditional mail routing](http://technet.microsoft.com/library/82d105e2-e955-4e03-99c3-3314a5d21a4c.aspx)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="794e6-130">For more information, see [Scenario: Conditional mail routing](http://technet.microsoft.com/library/82d105e2-e955-4e03-99c3-3314a5d21a4c.aspx).</span></span>
  
## <a name="incoming-mail-safe-list"></a><span data-ttu-id="794e6-131">받는 메일 수신 허용 목록</span><span class="sxs-lookup"><span data-stu-id="794e6-131">Incoming mail safe list</span></span>

<span data-ttu-id="794e6-p106">신뢰할 수 있는 파트너의 IP 주소를 수신 허용 목록에 추가하여 해당 파트너가 보내는 메시지에 스팸 방지 필터링이 적용되지 않도록 할 수 있습니다. 이렇게 하려면 연결 필터의 IP 허용 목록을 사용하면 됩니다.</span><span class="sxs-lookup"><span data-stu-id="794e6-p106">You can add a trusted partner's IP address to a safe list to ensure that messages the partner sends to you are not subject to anti-spam filtering. To do this, you can use the connection filter's IP Allow list.</span></span>
  
<span data-ttu-id="794e6-134">자세한 내용은 [Configure the connection filter policy](http://technet.microsoft.com/library/6ae78c12-7bbe-44fa-ab13-c3768387d0e3.aspx)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="794e6-134">For more information, see [Configure the connection filter policy](http://technet.microsoft.com/library/6ae78c12-7bbe-44fa-ab13-c3768387d0e3.aspx).</span></span>
  
## <a name="hybrid-email-routing"></a><span data-ttu-id="794e6-135">하이브리드 전자 메일 라우팅</span><span class="sxs-lookup"><span data-stu-id="794e6-135">Hybrid email routing</span></span>

<span data-ttu-id="794e6-p107">조직에서 하이브리드 배포를 사용하면 기존 온-프레미스 Microsoft Exchange 조직의 다양한 기능과 관리 제어 능력을 클라우드로 확장할 수 있습니다. 하이브리드 전송을 사용하면 한 조직의 받는 사람 간에 전송된 메시지가 TLS(전송 계층 보안)를 사용하여 인증, 암호화 및 전송되며 전송 규칙, 저널링 및 스팸 방지 정책과 같은 Exchange 구성 요소에 "내부"로 표시됩니다. Exchange Server의 하이브리드 구성 마법사를 사용하여 하이브리드 전송을 구성합니다.</span><span class="sxs-lookup"><span data-stu-id="794e6-p107">A hybrid deployment gives organizations the ability to extend the feature-rich experience and administrative control they have with their existing on-premises Microsoft Exchange organization to the cloud. With hybrid transport, messages sent between recipients in either organization are authenticated, encrypted, and transferred using Transport Layer Security (TLS), and appear as "internal" to Exchange components such as transport rules, journaling, and anti-spam policies. You configure hybrid transport by using the Hybrid Configuration Wizard in Exchange Server.</span></span>
  
<span data-ttu-id="794e6-139">하이브리드 배포의 메일 라우팅에 대한 자세한 내용은 [Exchange 하이브리드 배포의 전송 라우팅](https://go.microsoft.com/fwlink/p/?LinkId=271757)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="794e6-139">For more information about mail routing in a hybrid deployment, see [Transport routing in Exchange hybrid deployments](https://go.microsoft.com/fwlink/p/?LinkId=271757).</span></span>
  
<span data-ttu-id="794e6-140">[Microsoft Exchange Server 배포 도우미](https://go.microsoft.com/fwlink/p/?LinkId=287036) 또한 자세한 하이브리드 배포 프로비전 및 하이브리드 메시지 전송 지침을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="794e6-140">The [Microsoft Exchange Server Deployment Assistant](https://go.microsoft.com/fwlink/p/?LinkId=287036) also provides detailed hybrid deployment provisioning and hybrid message transport guidance.</span></span> 
  
### <a name="shared-address-space-with-on-premises-routing-control-mx-points-to-on-premises"></a><span data-ttu-id="794e6-141">온-프레미스 라우팅 제어를 사용하는 공유 주소 공간(MX가 온-프레미스를 가리킴)</span><span class="sxs-lookup"><span data-stu-id="794e6-141">Shared Address Space with On-Premises Routing Control (MX Points to On-Premises)</span></span>

<span data-ttu-id="794e6-p108">온-프레미스 라우팅 제어를 사용하는 공유 주소 공간(MX가 온-프레미스를 가리킴)은 사서함이 Exchange Online에서 일부 호스트 되고 온-프레미스로도 일부 호스트되며, 받거나 보내는 인터넷 메일 흐름이 온-프레미스 Exchange 조직을 통해 라우팅되는 하이브리드 배포 메일 라우팅 시나리오입니다. 이 시나리오는 중앙 집중식 메일 전송이라고도 합니다. 이 시나리오에서 Exchange Online은 EOP를 사용하여 프로비전되며, 받는 인터넷 메일은 EOP에 라우팅되기 전에 온-프레미스 메일 서버로 라우팅되었다가 Exchange Online에서 호스트되는 사서함으로 최종 라우팅 됩니다. 또한 Exchange Online 사서함에서 보내는 메일의 경우 외부의 받는 사람에게 보내는 메시지는 온-프레미스 Exchange 조직을 통해 라우팅됩니다. 이 구성을 사용하면 온-프레미스 Exchange 조직과 Exchange Online 조직의 모든 사서함에 대해 단일 SMTP 도메인 네임스페이스를 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="794e6-p108">Shared Address Space with On-Premises Routing Control (MX Points to On-Premises) is a hybrid deployment mail-routing scenario in which your mailboxes are hosted partially in Exchange Online and partially on-premises, and incoming and outgoing Internet mail flow is routed through the on-premises Exchange organization. This scenario is also called centralized mail transport. In this scenario, Exchange Online is provisioned with EOP and incoming Internet mail is routed to your on-premises mail server before being routed to EOP and finally to mailboxes hosted in Exchange Online. Additionally, outgoing mail from Exchange Online mailboxes is routed through the on-premises Exchange organization for messages sent to external recipients. With this configuration, you can use a single SMTP domain namespace for all mailboxes in both your on-premises Exchange organization and your Exchange Online organization.</span></span> 
  
<span data-ttu-id="794e6-147">하이브리드 배포의 전송 옵션에 대한 자세한 내용은 [Exchange 하이브리드 배포에서의 전송 옵션](https://go.microsoft.com/fwlink/p/?LinkID=271758)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="794e6-147">For more information about transport options in a hybrid deployment, see [Transport options in Exchange hybrid deployments](https://go.microsoft.com/fwlink/p/?LinkID=271758).</span></span>
  
### <a name="shared-address-space-without-on-premises-routing-control-mx-points-to-eop"></a><span data-ttu-id="794e6-148">온-프레미스 라우팅 제어를 사용하지 않는 공유 주소 공간(MX가 EOP를 가리킴)</span><span class="sxs-lookup"><span data-stu-id="794e6-148">Shared Address Space without On-Premises Routing Control (MX Points to EOP)</span></span>

<span data-ttu-id="794e6-p109">온-프레미스 라우팅 제어를 사용하지 않는 공유 주소 공간(MX가 EOP를 가리킴)은 사서함이 Exchange Online을 통해 클라우드에서 일부 호스트 되고 온-프레미스로도 일부 호스트되는 하이브리드 메일 라우팅 시나리오로, MX 레코드는 EOP를 가리킵니다. 이 시나리오는 Office 365 서비스를 사용하여 조직의 사서함 일부를 호스트하고 EOP로 온-프레미스 및 클라우드 사서함을 모두 보호하려는 경우에 적절합니다. 이 시나리오에서 조직 내의 받는 사람에게 보낸 메일은 온-프레미스 사서함 및 클라우드 사서함에 도달하기 전에 먼저 스팸 및 정책 필터링이 적용되는 EOP를 통해 라우팅 됩니다.</span><span class="sxs-lookup"><span data-stu-id="794e6-p109">Shared Address Space without On-Premises Routing Control (MX Points to EOP) is a hybrid mail-routing scenario in which your mailboxes are hosted partially in the cloud using Exchange Online and partially on-premises, and your MX record points to EOP. This scenario is appropriate when you use the Office 365 service to host some of your organization's mailboxes and you want EOP to protect both your on-premises and cloud mailboxes. In this scenario, mail sent to recipients within your organization is initially routed through EOP, where spam and policy filtering occurs, before it reaches your on-premises mailboxes and cloud mailboxes.</span></span> 
  
<span data-ttu-id="794e6-152">하이브리드 배포의 전송 옵션에 대한 자세한 내용은 [Exchange 하이브리드 배포에서의 전송 옵션](https://go.microsoft.com/fwlink/p/?LinkID=271758)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="794e6-152">For more information about transport options in a hybrid deployment, see [Transport options in Exchange hybrid deployments](https://go.microsoft.com/fwlink/p/?LinkID=271758).</span></span>
  
### <a name="troubleshooting-a-deployment-with-the-hybrid-configuration-wizard"></a><span data-ttu-id="794e6-153">하이브리드 구성 마법사를 사용하여 배포 문제 해결</span><span class="sxs-lookup"><span data-stu-id="794e6-153">Troubleshooting a deployment with the Hybrid Configuration Wizard</span></span>

<span data-ttu-id="794e6-p110">하이브리드 구성 마법사를 사용하여 Microsoft Exchange Server에서 하이브리드 배포를 구성하면 하이브리드 배포 관련 문제가 발생할 가능성이 최소화됩니다. 그러나 잘못 구성될 경우 하이브리드 배포에서 문제를 일으킬 수 있는, 하이브리드 구성 마법사의 범위를 벗어난 영역이 몇 군데 있습니다. 적절한 클라이언트 액세스 서버 구성과 적절한 인증서 설치 및 구성이 여기에 해당합니다.</span><span class="sxs-lookup"><span data-stu-id="794e6-p110">Using the Hybrid Configuration Wizard to configure a hybrid deployment in Microsoft Exchange Server greatly minimizes the potential that the hybrid deployment will experience problems. However, there are some typical areas outside the scope of the Hybrid Configuration Wizard that, if misconfigured, may present problems in a hybrid deployment. These include proper Client Access server configuration and proper certificate installation and configuration.</span></span>
  
<span data-ttu-id="794e6-157">하이브리드 구성 마법사를 사용하여 배포 문제를 해결하는 방법에 대한 자세한 내용은 [하이브리드 배포 문제 해결](https://go.microsoft.com/fwlink/p/?LinkId=271040)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="794e6-157">For more information about troubleshooting a deployment with the Hybrid Configuration Wizard, see [Troubleshoot a hybrid deployment](https://go.microsoft.com/fwlink/p/?LinkId=271040).</span></span>
  
### <a name="managing-a-hybrid-configuration"></a><span data-ttu-id="794e6-158">하이브리드 구성 관리</span><span class="sxs-lookup"><span data-stu-id="794e6-158">Managing a hybrid configuration</span></span>

<span data-ttu-id="794e6-p111">하이브리드 구성 마법사에서 설정을 변경하여 기존 하이브리드 구성을 수정할 수 있습니다. 예를 들면, 중앙 집중식 전송을 사용하지 않도록 설정하거나 보안 메일 전송을 사용하지 않도록 설정하는 것입니다.</span><span class="sxs-lookup"><span data-stu-id="794e6-p111">You can modify an existing hybrid configuration by changing settings in the Hybrid Configuration Wizard. Scenarios include disabling centralized transport or disabling secure mail transport.</span></span>
  
<span data-ttu-id="794e6-161">하이브리드 배포 구성 관리에 대한 자세한 내용은 [하이브리드 배포 관리](https://go.microsoft.com/fwlink/p/?LinkId=271044)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="794e6-161">For more information about managing a hybrid deployment configuration, see [Manage a hybrid deployment](https://go.microsoft.com/fwlink/p/?LinkId=271044).</span></span>
  
### <a name="hybrid-deployment-requirements"></a><span data-ttu-id="794e6-162">하이브리드 배포 요구 사항</span><span class="sxs-lookup"><span data-stu-id="794e6-162">Hybrid deployment requirements</span></span>

<span data-ttu-id="794e6-163">하이브리드 배포 요구 사항에 대한 자세한 내용은 [하이브리드 배포 필수 구성 요소](https://go.microsoft.com/fwlink/p/?LinkId=271759)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="794e6-163">For more information about hybrid deployment requirements, see [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/p/?LinkId=271759).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="794e6-164">일부 하이브리드 구성에서는 온-프레미스 사서함에 대해 Exchange Online Protection 라이선스를 구입해야 할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="794e6-164">In some hybrid configurations, you may need to purchase Exchange Online Protection licenses for your on-premises mailboxes.</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="794e6-165">기능 가용성</span><span class="sxs-lookup"><span data-stu-id="794e6-165">Feature Availability</span></span>

<span data-ttu-id="794e6-166">Office 365 계획, 독립 실행형 옵션 및 온-프레미스 솔루션별로 기능 가용성을 확인하려면 [Exchange Online 서비스 설명](exchange-online-service-description.md)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="794e6-166">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see the [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  
