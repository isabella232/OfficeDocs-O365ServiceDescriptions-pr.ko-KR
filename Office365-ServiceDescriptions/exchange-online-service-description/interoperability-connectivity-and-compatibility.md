---
title: 상호 운용성, 연결 및 호환성
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-interoperability-connectivity-compatibility
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: cdfe686d-a059-4f4d-bb8d-9c2c0ebfa423
ms.openlocfilehash: 38ab8f7baf16c5bf837bca9310a0d34a5e25469f
ms.sourcegitcommit: 96dc758c790ddaf05f5c2b836451b417729cf119
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/18/2019
ms.locfileid: "35776799"
---
# <a name="interoperability-connectivity-and-compatibility"></a><span data-ttu-id="1ce47-102">상호 운용성, 연결 및 호환성</span><span class="sxs-lookup"><span data-stu-id="1ce47-102">Interoperability, Connectivity, and Compatibility</span></span>

## <a name="interoperability-with-other-microsoft-products"></a><span data-ttu-id="1ce47-103">다른 Microsoft 제품과의 상호 운용성</span><span class="sxs-lookup"><span data-stu-id="1ce47-103">Interoperability with other Microsoft products</span></span>

### <a name="skype-for-business-online"></a><span data-ttu-id="1ce47-104">비즈니스용 Skype Online</span><span class="sxs-lookup"><span data-stu-id="1ce47-104">Skype for Business Online</span></span>

<span data-ttu-id="1ce47-105">Microsoft Lync Server 2010, Lync Server 2013 또는 Microsoft Office Communications Server 2007 R2를 온-프레미스에 배포한 고객의 경우 Exchange Web Services를 통해 Microsoft Office Communicator를 Microsoft Exchange Online에 연결하여 부재 중 메시지와 일정 데이터에 액세스할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="1ce47-105">For customers who have deployed Microsoft Lync Server 2010, Lync Server 2013 or Microsoft Office Communications Server 2007 R2 on-premises, Microsoft Office Communicator can connect to Microsoft Exchange Online by using Exchange Web Services to access out-of-office messages and calendar data.</span></span>
  
<span data-ttu-id="1ce47-106">온-프레미스 Lync Server 2010 및 Lync Server 2013은 그 외에도 다음 두 가지 방법으로 Exchange Online과 상호 운용될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="1ce47-106">On-premises Lync Server 2010 and Lync Server 2013 can interoperate with Exchange Online in two additional ways:</span></span>
  
- <span data-ttu-id="1ce47-107">Outlook Web App에서의 IM 및 현재 상태 상호 운용성</span><span class="sxs-lookup"><span data-stu-id="1ce47-107">IM and presence interoperability in Outlook Web App</span></span>
    
- <span data-ttu-id="1ce47-108">음성 메일 상호 운용성</span><span class="sxs-lookup"><span data-stu-id="1ce47-108">Voice mail interoperability</span></span>
    
<span data-ttu-id="1ce47-p101">비즈니스용 Skype 서버 2015와 Exchange Online을 함께 구성하는 방법에 대한 자세한 내용은 [Exchange Online과 온-프레미스 비즈니스용 Skype Server 2015의 통합 구성](https://go.microsoft.com/fwlink/p/?LinkId=271804)을 참조하세요. 하이브리드 구성은 [지원되는 비즈니스용 Skype Server 2015 하이브리드 구성](https://go.microsoft.com/fwlink/?LinkID=513084)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="1ce47-p101">For more information about how to configure Skype for Business Server 2015 with Exchange Online, see [Configuring On-premises Skype for Business Server 2015 Integration with Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271804). For hybrid configurations, see [Supported Skype for Business Server 2015 hybrid configurations](https://go.microsoft.com/fwlink/?LinkID=513084).</span></span>
  
### <a name="microsoft-sharepoint"></a><span data-ttu-id="1ce47-111">Microsoft SharePoint</span><span class="sxs-lookup"><span data-stu-id="1ce47-111">Microsoft SharePoint</span></span>

<span data-ttu-id="1ce47-112">Office 365 구독 계획의 일부로 Microsoft SharePoint Server나 SharePoint Online을 배포한 고객의 경우 통합 서비스를 위해 SharePoint를 Exchange Online에 연결할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="1ce47-112">For customers who have deployed Microsoft SharePoint Server or SharePoint Online as part of an Office 365 subscription plan, SharePoint can connect to Exchange Online for integrated services.</span></span>
  
<span data-ttu-id="1ce47-113">SharePoint를 Exchange Online에 연결하는 데 대한 자세한 내용은 [사용자 지정 도메인의 SharePoint Online을 다른 서비스와 함께 사용](https://go.microsoft.com/fwlink/?LinkId=271805)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="1ce47-113">For more information about connecting SharePoint to Exchange Online, see [Use SharePoint Online on a custom domain together with other services](https://go.microsoft.com/fwlink/?LinkId=271805).</span></span>
  
## <a name="features-for-external-connectivity"></a><span data-ttu-id="1ce47-114">외부 연결 기능</span><span class="sxs-lookup"><span data-stu-id="1ce47-114">Features for external connectivity</span></span>

<span data-ttu-id="1ce47-115">Exchange Online에서는 외부 응용 프로그램과 장치에 연결하기 위해 다음과 같은 기능을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="1ce47-115">Exchange Online offers the following features for connecting with external applications and devices:</span></span>
  
- <span data-ttu-id="1ce47-p102">**MAPI over HTTP, SMTP, POP3, IMAP4 또는 Exchange Web Services와 같은 메시징 프로토콜** 온-프레미스, Azure 또는 다른 호스팅된 서비스에서 실행되는 외부 응용 프로그램은 MAPI over HTTP, SMTP, POP3, IMAPv4 등의 메시징 프로토콜을 사용하여 Exchange Online에서 저장된 데이터에 액세스할 수 있습니다. 응용 프로그램을 개발하는 경우 Exchange Web Services 또는 Exchange Web Services Managed API를 사용하는 것이 좋습니다.</span><span class="sxs-lookup"><span data-stu-id="1ce47-p102">**Through messaging protocols such as MAPI over HTTP, SMTP, POP3, IMAP4, or Exchange Web Services** External applications that are running on-premises, in Azure, or in other hosted services can access data stored with Exchange Online by using messaging protocols such as MAPI over HTTP, SMTP, POP3, and IMAPv4. Exchange Web Services or the Exchange Web Services Managed API is recommended for application development.</span></span> 
    
- <span data-ttu-id="1ce47-118">**SMTP 릴레이** 팩스 게이트웨이, 네트워크 어플라이언스 및 사용자 지정 응용 프로그램에서 보내는 전자 메일 메시지를 릴레이하도록 Exchange Online을 SMTP 배달 서비스로 구성할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="1ce47-118">**As an SMTP relay** Exchange Online can be set up as an SMTP delivery service to relay email messages sent from fax gateways, network appliances, and custom applications.</span></span> 
    
### <a name="exchange-web-services"></a><span data-ttu-id="1ce47-119">Exchange Web Services</span><span class="sxs-lookup"><span data-stu-id="1ce47-119">Exchange Web Services</span></span>

<span data-ttu-id="1ce47-p103">EWS(Exchange Web Services)는 Exchange Server 및 Exchange Online을 위한 개발 API로 적합합니다. 관리자는 EWS 또는 EWS Managed API를 사용하여 온-프레미스, Azure 또는 기타 호스트되는 서비스에서 실행되는 응용 프로그램에서 Exchange Online에 저장된 데이터에 액세스할 수 있습니다. 관리자는 EWS를 통해 사서함의 콘텐츠를 쿼리하거나, 일정 이벤트를 게시하거나, 작업을 생성하거나, 전자 메일 메시지의 콘텐츠를 기반으로 특정 작업을 트리거하는 것과 같은 특수한 작업을 수행할 수 있습니다. Exchange Online에서는 고객 계정에 응용 프로그램 권한을 부여하는 방법으로 EWS 기능이 사용 가능하게 설정됩니다. 이러한 권한이 있으면 고객 응용 프로그램이 응용 프로그램 사서함에 액세스하고 콘텐츠를 추가할 수 있습니다. Exchange 가장 기능은 응용 프로그램 권한을 부여하는 데 사용되는 한 가지 방법입니다. Exchange Online에서 Exchange Web Services를 사용하는 방법에 대한 자세한 내용을 보려면 Exchange Online 개발자 센터에서 제공되는 기술 문서를 참조하십시오.</span><span class="sxs-lookup"><span data-stu-id="1ce47-p103">Exchange Web Services (EWS) is the preferred development API for Exchange Server and Exchange Online. Using EWS or the EWS Managed API, administrators can access data stored with Exchange Online from applications that are running on-premises, in Azure, or in other hosted services. EWS enables administrators to perform specialized actions, such as querying the contents of a mailbox, posting a calendar event, creating a task, or triggering a specific action based on the content of an email message. Exchange Online enables EWS functionality by granting application permissions to customer accounts. These permissions allow the customer application to access the application mailbox and add content. Exchange Impersonation is one method used to grant application permissions. For details about how to use Exchange Web Services with Exchange Online, refer to the technical articles at the Exchange Online Developer Center.</span></span>
  
### <a name="smtp-relay"></a><span data-ttu-id="1ce47-127">SMTP 릴레이</span><span class="sxs-lookup"><span data-stu-id="1ce47-127">SMTP relay</span></span>

<span data-ttu-id="1ce47-p104">Exchange Online을 SMTP 배달 서비스로 사용하여 팩스 게이트웨이, 네트워크 어플라이언스 및 사용자 지정 응용 프로그램에서 보낸 전자 메일 메시지를 릴레이할 수 있습니다. 예를 들어 LOB(기간 업무) 응용 프로그램에서 사용자에게 전자 메일 경고를 보낼 경우, Exchange Online을 메일 배달 시스템으로 사용하도록 구성할 수 있습니다. 이 경우 응용 프로그램 또는 서비스는 라이선스가 있는 유효한 Exchange Online 사서함의 사용자 이름과 암호로 인증되어야 하며 TLS(전송 계층 보안)를 사용하여 연결되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="1ce47-p104">Exchange Online can be used as an SMTP delivery service to relay email messages sent from fax gateways, network appliances, and custom applications. For example, if a line-of-business application sends email alerts to users, it can be configured to use Exchange Online as the mail delivery system. The application or service must authenticate with the username and password of a valid, licensed Exchange Online mailbox, and connect by using Transport Layer Security (TLS).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="1ce47-131">기능 가용성</span><span class="sxs-lookup"><span data-stu-id="1ce47-131">Feature Availability</span></span>

<span data-ttu-id="1ce47-132">Office 365 계획, 독립 실행형 옵션 및 온-프레미스 솔루션별로 기능 가용성을 확인하려면 [Exchange Online 서비스 설명](exchange-online-service-description.md)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="1ce47-132">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

