---
title: 음성 메시지 서비스
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-voice-message-services
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a02af6e2-75c2-4e83-843e-77241072068e
ms.openlocfilehash: a6245acdeaeda173f1a675d1ce34d9086e3f077a
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132552"
---
# <a name="voice-message-services"></a>음성 메시지 서비스

## <a name="voice-mail"></a>음성 사서함

Microsoft Exchange Online에서는 호스트된 음성 메일 서비스를 제공합니다. 이 서비스의 기능은 다음과 같습니다.
  
- Microsoft Exchange Online에서는 호스트된 음성 메일 서비스를 제공합니다. 이 서비스의 기능은 다음과 같습니다.
    
- 전화 응답(음성 사서함)
    
- Exchange에 대한 전화 접속 사용자 인터페이스(Outlook Voice Access)
    
Hosted voice messaging services allow a company to connect its on-premises phone system to voice mail services provided by Exchange Online. Voice mail messages are recorded and stored in the Exchange Online infrastructure, allowing users to access their voice messages from Outlook, Outlook on the web, or mobile phones. All telephony connections to Exchange Online require voice-over-IP (VoIP) protocols. Administrators can connect on-premises IP PBXs or PBX phone systems using VoIP media gateways and session border controllers (SBCs) to Exchange Online. A VoIP media gateway is not required if the customer has deployed an IP PBX or if a PBX supports VoIP directly and is interoperable with Exchange voice messaging services. SBCs are deployed in the perimeter of the customer network to connect an on-premises telephony network and help secure the communications (and the customer network) against eavesdropping and intrusion. Interoperability with the voice capabilities of Microsoft Lync Server 2010 and 2013 is also supported.
  
The voice messaging services features available in Exchange Online are similar to those offered in on-premises Exchange Server 2016. These include:
  
- Exchange Online에서 사용할 수 있는 음성 메시징 서비스 기능은 온-프레미스 Exchange Server 2013에서 제공된 기능과 동일하며, 다음과 같습니다.
    
- Outlook 및 Outlook Web App의 전화에서 재생.
    
- 부재 중 통화 알림.
    
- Voice mail PIN reset from Outlook on the web and Outlook (see [Reset a Voice Mail PIN](https://go.microsoft.com/fwlink/p/?LinkId=286328)).
    
- Outlook Web App 및 Outlook에서 음성 메시지 PIN 다시 설정([음성 메시지 PIN 다시 설정](https://go.microsoft.com/fwlink/p/?LinkId=271794) 참조). 
    
- 전화 응답 규칙 (자세한 내용은 [음성 메일 사용자가 통화를 전달 하도록 허용을](https://go.microsoft.com/fwlink/p/?LinkId=271795) 참조 하세요.)
    
- Exchange Online의 보호 된 음성 메일 (자세한 내용은 [Exchange online에서 음성 메일 보호](https://go.microsoft.com/fwlink/p/?LinkId=271796) 를 참조 하세요.)
    
- 음성 메일 미리 보기 (지원 되는 언어 목록에 대 한 [음성 메일 성적을 사용자가 볼 수 있도록 허용](https://go.microsoft.com/fwlink/p/?LinkId=271797) 참조)
    
- Speech access to email, voice mail, calendar, personal contacts, and personal contact groups.
    
- 전자 메일, 음성 사서함, 일정, 개인 연락처, 개인 메일 그룹에 음성 명령으로 액세스.
    
- Outlook Voice Access 또는 자동 전화 교환을 통한 디렉터리 검색.
    
음성 메일 기능에 대 한 자세한 내용은 [Exchange Online의 음성 메일](https://go.microsoft.com/fwlink/p/?LinkId=271798)을 참조 하십시오.
  
> [!IMPORTANT]
> The Automatic Speech Recognition (ASR) feature isn't available in menu navigation or directory search for Outlook Voice Access users or auto attendant callers using voice commands. 
>
> 고객은 VoIP 게이트웨이 및 PBX, IP PBX 또는 비즈니스용 Skype 서버 2015을 사용 하 여 공중 전화망 (PSTN)에서 전화 통신 연결을 제공 해야 합니다. 
>
> The customer must provide the on-premises SBC hardware devices and ensure that the SBCs are correctly configured to connect to the online voice mail services. This includes configuring the appropriate level of security by using certificates and public and private IP interfaces and by enabling the correct TCP ports through their on-premises firewalls. 
>
> 호스트 된 음성 메일은 Exchange Online 계획 2 및 Office 365 Enterprise E3 구독자만 사용할 수 있습니다. 
  
## <a name="third-party-voice-mail-interoperability"></a>타사 음성 사서함 상호 운용성

On-premises voice mail solutions from third-party providers can interoperate with Exchange Online if they can forward voice messages through SMTP or if they support Microsoft Exchange Web Services. If the voice mail system does not natively support forwarding voice messages through SMTP, an email server can be kept on-premises to receive messages from the voice mail system and then forward them to the cloud using SMTP. Because many third-party voice mail systems use MAPI/CDO to interoperate with Exchange Server for advanced UM features, the full capabilities of these systems may not be available when SMTP is used for interoperability with Exchange Online.
  
> [!NOTE]
> Exchange Online UM support for third-party PBX systems via direct connections from customer operated SBCs will end in July 2018. Please see [Discontinuation of support for Session Border Controllers in Exchange Online Unified Messaging](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/Discontinuation-of-support-for-Session-Border-Controllers-in/ba-p/607117) for more information. 
  
## <a name="skype-for-business-integration"></a>비즈니스용 Skype 통합

조직에서는 비즈니스용 Skype Online을 독립 실행형 서비스로 또는 Microsoft Office 365의 일부분으로 구입할 수 있습니다. 비즈니스용 Skype 2015 온-프레미스도 지원 됩니다. 비즈니스용 Skype Online에 대 한 자세한 내용은 [비즈니스용 Skype online 서비스 설명을](../skype-for-business-online-service-description/skype-for-business-online-service-description.md)참조 하세요.
  
## <a name="feature-availability"></a>기능 가용성

계획, 독립 실행형 옵션 및 온-프레미스 솔루션 별로 기능 가용성을 확인 하려면 [Exchange Online 서비스 설명을](exchange-online-service-description.md)참조 하세요.
  

