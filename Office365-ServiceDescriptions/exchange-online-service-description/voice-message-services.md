---
title: 음성 메시지 서비스
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-voice-message-services
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a02af6e2-75c2-4e83-843e-77241072068e
ms.openlocfilehash: 23cc82d51d1afcbd2662e86dd6bc2aeebfb22346
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652682"
---
# <a name="voice-message-services"></a><span data-ttu-id="185d8-102">음성 메시지 서비스</span><span class="sxs-lookup"><span data-stu-id="185d8-102">Voice message services</span></span>

## <a name="voice-mail"></a><span data-ttu-id="185d8-103">음성 사서함</span><span class="sxs-lookup"><span data-stu-id="185d8-103">Voice mail</span></span>

<span data-ttu-id="185d8-104">Microsoft Exchange Online에서는 호스트된 음성 메일 서비스를 제공합니다. 이 서비스의 기능은 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="185d8-104">Microsoft Exchange Online offers hosted voice mail services, which provide:</span></span>
  
- <span data-ttu-id="185d8-105">Microsoft Exchange Online에서는 호스트된 음성 메일 서비스를 제공합니다. 이 서비스의 기능은 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="185d8-105">Call answering (voice mail)</span></span>
    
- <span data-ttu-id="185d8-106">전화 응답(음성 사서함)</span><span class="sxs-lookup"><span data-stu-id="185d8-106">Dial-in user interface to Exchange (Outlook Voice Access)</span></span>
    
- <span data-ttu-id="185d8-107">Exchange에 대한 전화 접속 사용자 인터페이스(Outlook Voice Access)</span><span class="sxs-lookup"><span data-stu-id="185d8-107">Dial-in interface for callers (auto attendant)</span></span>
    
<span data-ttu-id="185d8-p101">발신자용 전화 접속 인터페이스(자동 전화 교환)</span><span class="sxs-lookup"><span data-stu-id="185d8-p101">Hosted voice messaging services allow a company to connect its on-premises phone system to voice mail services provided by Exchange Online. Voice mail messages are recorded and stored in the Exchange Online infrastructure, allowing users to access their voice messages from Outlook, Outlook on the web, or mobile phones. All telephony connections to Exchange Online require voice-over-IP (VoIP) protocols. Administrators can connect on-premises IP PBXs or PBX phone systems using VoIP media gateways and session border controllers (SBCs) to Exchange Online. A VoIP media gateway is not required if the customer has deployed an IP PBX or if a PBX supports VoIP directly and is interoperable with Exchange voice messaging services. SBCs are deployed in the perimeter of the customer network to connect an on-premises telephony network and help secure the communications (and the customer network) against eavesdropping and intrusion. Interoperability with the voice capabilities of Microsoft Lync Server 2010 and 2013 is also supported.</span></span>
  
<span data-ttu-id="185d8-p102">호스트된 음성 메시징 서비스를 사용하면 기업의 온-프레미스 전화 시스템을 Exchange Online에서 제공하는 음성 메일 서비스에 연결할 수 있습니다. 음성 메일 메시지는 Exchange Online 인프라에 기록 및 저장되므로 사용자가 Outlook, Outlook Web Access 또는 휴대폰에서 음성 메시지에 액세스할 수 있습니다. Exchange Online에 대한 모든 전화 통신 연결에는 VoIP(Voice-over-IP) 프로토콜이 필요합니다. 관리자는 VoIP 미디어 게이트웨이 및 SBC(Session Border Controller)를 사용하여 온-프레미스 IP PBX 또는 PBX 전화 시스템을 연결할 수 있습니다. 고객이 IP PBX를 배포한 경우 또는 PBX가 VoIP를 직접 지원하고 Exchange 음성 메시징 서비스와 상호 운용되는 경우에는 VoIP 미디어 게이트웨이가 필요하지 않습니다. SBC는 온-프레미스 전화 통신 네트워크에 연결하기 위해 고객 네트워크 주변에 배포되며, 도청 및 침입에 대비하여 통신을 보호합니다. 또한 Microsoft Lync Server 2010 및 2013 음성 기능과의 상호 운용성도 지원됩니다.</span><span class="sxs-lookup"><span data-stu-id="185d8-p102">The voice messaging services features available in Exchange Online are similar to those offered in on-premises Exchange Server 2016. These include:</span></span>
  
- <span data-ttu-id="185d8-117">Exchange Online에서 사용할 수 있는 음성 메시징 서비스 기능은 온-프레미스 Exchange Server 2013에서 제공된 기능과 동일하며, 다음과 같습니다.</span><span class="sxs-lookup"><span data-stu-id="185d8-117">Play on phone from Outlook and Outlook on the web.</span></span>
    
- <span data-ttu-id="185d8-118">Outlook 및 Outlook Web App의 전화에서 재생.</span><span class="sxs-lookup"><span data-stu-id="185d8-118">Missed call notifications.</span></span>
    
- <span data-ttu-id="185d8-119">부재 중 통화 알림.</span><span class="sxs-lookup"><span data-stu-id="185d8-119">Caller ID (using information in the Global Address List, users' personal contacts, custom Contacts folder, and contacts from external social networks).</span></span>
    
- <span data-ttu-id="185d8-120">Voice mail PIN reset from Outlook on the web and Outlook (see [Reset a Voice Mail PIN](/exchange/voice-mail-unified-messaging/set-outlook-voice-access-pin-security/reset-a-voice-mail-pin)).</span><span class="sxs-lookup"><span data-stu-id="185d8-120">Voice mail PIN reset from Outlook on the web and Outlook (see [Reset a Voice Mail PIN](/exchange/voice-mail-unified-messaging/set-outlook-voice-access-pin-security/reset-a-voice-mail-pin)).</span></span>
    
- <span data-ttu-id="185d8-121">Outlook Web App 및 Outlook에서 음성 메시지 PIN 다시 설정([음성 메시지 PIN 다시 설정](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/mwi-in-exchange-online) 참조).</span><span class="sxs-lookup"><span data-stu-id="185d8-121">Message Waiting Indicator (see [MWI in Exchange Online](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/mwi-in-exchange-online) for details).</span></span> 
    
- <span data-ttu-id="185d8-122">전화 응답 규칙(자세한 내용은 음성 메일 사용자가 통화를 전달할 수 [있도록 허용](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/allow-voice-mail-users-to-forward-calls) 참조)</span><span class="sxs-lookup"><span data-stu-id="185d8-122">Call answering rules (see [Allow voice mail users to forward calls](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/allow-voice-mail-users-to-forward-calls) for details).</span></span>
    
- <span data-ttu-id="185d8-123">보안 서버의 보호된 음성 [Exchange Online(자세한](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/protect-voice-mail) 내용은 Exchange Online 음성 메일 보호 참조).</span><span class="sxs-lookup"><span data-stu-id="185d8-123">Protected voice mail in Exchange Online (see [Protect voice mail in Exchange Online](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/protect-voice-mail) for details).</span></span>
    
- <span data-ttu-id="185d8-124">음성 메일 미리 [보기(지원되는](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/allow-users-to-see-a-voice-mail-transcript) 언어 목록은 사용자가 음성 메일 설명을 볼 수 있도록 허용 참조).</span><span class="sxs-lookup"><span data-stu-id="185d8-124">Voice mail preview (see [Allow users to see a voice mail transcript](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/allow-users-to-see-a-voice-mail-transcript) for a list of supported languages).</span></span>
    
- <span data-ttu-id="185d8-125">Speech access to email, voice mail, calendar, personal contacts, and personal contact groups.</span><span class="sxs-lookup"><span data-stu-id="185d8-125">Speech access to email, voice mail, calendar, personal contacts, and personal contact groups.</span></span>
    
- <span data-ttu-id="185d8-126">전자 메일, 음성 사서함, 일정, 개인 연락처, 개인 메일 그룹에 음성 명령으로 액세스.</span><span class="sxs-lookup"><span data-stu-id="185d8-126">Directory search through Outlook Voice Access or an auto attendant.</span></span>
    
- <span data-ttu-id="185d8-127">Outlook Voice Access 또는 자동 전화 교환을 통한 디렉터리 검색.</span><span class="sxs-lookup"><span data-stu-id="185d8-127">Administrators configure and manage voice messaging services interoperability by using the Exchange admin center (EAC).</span></span>
    
<span data-ttu-id="185d8-128">음성 메일 기능에 대한 자세한 내용은 에서 [음성 메일을 Exchange Online.](/exchange/voice-mail-unified-messaging/voice-mail-unified-messaging)</span><span class="sxs-lookup"><span data-stu-id="185d8-128">For more information about voice mail features, see [Voice mail in Exchange Online](/exchange/voice-mail-unified-messaging/voice-mail-unified-messaging).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="185d8-129">The Automatic Speech Recognition (ASR) feature isn't available in menu navigation or directory search for Outlook Voice Access users or auto attendant callers using voice commands.</span><span class="sxs-lookup"><span data-stu-id="185d8-129">The Automatic Speech Recognition (ASR) feature isn't available in menu navigation or directory search for Outlook Voice Access users or auto attendant callers using voice commands.</span></span> 
>
> <span data-ttu-id="185d8-130">고객은 VoIP 게이트웨이와 PBX, IP PBX 또는 2015를 사용하여 PSTN(공용 전화망)에서 전화 통신 연결을 비즈니스용 Skype 서버 합니다.</span><span class="sxs-lookup"><span data-stu-id="185d8-130">The customer must provide a telephony connection from the public switched telephone network (PSTN) using a VoIP gateway and PBX, IP PBX, or Skype for Business Server 2015.</span></span> 
>
> <span data-ttu-id="185d8-p103">고객은 온-프레미스 SBC 하드웨어 장치를 제공하고 이 SBC가 온라인 음성 메일 서비스에 연결하도록 올바르게 구성되어 있는지 확인해야 합니다. 여기에는 인증서와 공용 및 개인 IP 인터페이스를 사용하고 온-프레미스 방화벽을 통해 올바른 TCP 포트를 사용하여 적절한 보안 수준을 구성하는 것이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="185d8-p103">The customer must provide the on-premises SBC hardware devices and ensure that the SBCs are correctly configured to connect to the online voice mail services. This includes configuring the appropriate level of security by using certificates and public and private IP interfaces and by enabling the correct TCP ports through their on-premises firewalls.</span></span> 
>
> <span data-ttu-id="185d8-133">호스팅된 음성 메일은 요금제 2 및 Exchange Online E3 구독자만 Office 365 Enterprise 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="185d8-133">Hosted voice mail is available only to Exchange Online Plan 2 and Office 365 Enterprise E3 subscribers.</span></span> 
  
## <a name="third-party-voice-mail-interoperability"></a><span data-ttu-id="185d8-134">타사 음성 사서함 상호 운용성</span><span class="sxs-lookup"><span data-stu-id="185d8-134">Third-party voice mail interoperability</span></span>

<span data-ttu-id="185d8-p104">타사 음성 사서함 상호 운용성</span><span class="sxs-lookup"><span data-stu-id="185d8-p104">On-premises voice mail solutions from third-party providers can interoperate with Exchange Online if they can forward voice messages through SMTP or if they support Microsoft Exchange Web Services. If the voice mail system does not natively support forwarding voice messages through SMTP, an email server can be kept on-premises to receive messages from the voice mail system and then forward them to the cloud using SMTP. Because many third-party voice mail systems use MAPI/CDO to interoperate with Exchange Server for advanced UM features, the full capabilities of these systems may not be available when SMTP is used for interoperability with Exchange Online.</span></span>
  
> [!NOTE]
> <span data-ttu-id="185d8-p105">Exchange Online UM support for third-party PBX systems via direct connections from customer operated SBCs will end in July 2018. Please see [Discontinuation of support for Session Border Controllers in Exchange Online Unified Messaging](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/Discontinuation-of-support-for-Session-Border-Controllers-in/ba-p/607117) for more information.</span><span class="sxs-lookup"><span data-stu-id="185d8-p105">Exchange Online UM support for third-party PBX systems via direct connections from customer operated SBCs will end in July 2018. Please see [Discontinuation of support for Session Border Controllers in Exchange Online Unified Messaging](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/Discontinuation-of-support-for-Session-Border-Controllers-in/ba-p/607117) for more information.</span></span> 
  
## <a name="skype-for-business-integration"></a><span data-ttu-id="185d8-140">비즈니스용 Skype 통합</span><span class="sxs-lookup"><span data-stu-id="185d8-140">Skype for Business integration</span></span>

<span data-ttu-id="185d8-141">조직에서는 비즈니스용 Skype Online을 독립 실행형 서비스로 또는 Microsoft Office 365의 일부분으로 구입할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="185d8-141">Organizations can purchase Skype for Business Online as a standalone service or as part of Microsoft Office 365.</span></span> <span data-ttu-id="185d8-142">비즈니스용 Skype 2015 On-premises도 지원됩니다.</span><span class="sxs-lookup"><span data-stu-id="185d8-142">Skype for Business 2015 on-premises is also supported.</span></span> <span data-ttu-id="185d8-143">온라인 비즈니스용 Skype 자세한 내용은 비즈니스용 Skype [서비스 설명을 참조하세요.](../skype-for-business-online-service-description/skype-for-business-online-service-description.md)</span><span class="sxs-lookup"><span data-stu-id="185d8-143">To learn more about Skype for Business Online, see [Skype for Business Online service description](../skype-for-business-online-service-description/skype-for-business-online-service-description.md).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="185d8-144">기능 가용성</span><span class="sxs-lookup"><span data-stu-id="185d8-144">Feature availability</span></span>

<span data-ttu-id="185d8-145">계획, 독립 실행형 옵션 및온-프레미스 솔루션에서 기능 가용성을 확인한 경우 서비스 [Exchange Online 참조하세요.](exchange-online-service-description.md)</span><span class="sxs-lookup"><span data-stu-id="185d8-145">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online service description](exchange-online-service-description.md).</span></span>
