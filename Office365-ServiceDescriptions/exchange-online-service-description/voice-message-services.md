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
ms.openlocfilehash: fe1d1f5a58012498e5b0f71c9a4299e61a4456ad
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173393"
---
# <a name="voice-message-services"></a>음성 메시지 서비스

## <a name="voice-mail"></a>음성 사서함

Microsoft Exchange Online에서는 호스트된 음성 메일 서비스를 제공합니다. 이 서비스의 기능은 다음과 같습니다.
  
- Microsoft Exchange Online에서는 호스트된 음성 메일 서비스를 제공합니다. 이 서비스의 기능은 다음과 같습니다.
    
- 전화 응답(음성 사서함)
    
- Exchange에 대한 전화 접속 사용자 인터페이스(Outlook Voice Access)
    
발신자용 전화 접속 인터페이스(자동 전화 교환)
  
호스트된 음성 메시징 서비스를 사용하면 기업의 온-프레미스 전화 시스템을 Exchange Online에서 제공하는 음성 메일 서비스에 연결할 수 있습니다. 음성 메일 메시지는 Exchange Online 인프라에 기록 및 저장되므로 사용자가 Outlook, Outlook Web Access 또는 휴대폰에서 음성 메시지에 액세스할 수 있습니다. Exchange Online에 대한 모든 전화 통신 연결에는 VoIP(Voice-over-IP) 프로토콜이 필요합니다. 관리자는 VoIP 미디어 게이트웨이 및 SBC(Session Border Controller)를 사용하여 온-프레미스 IP PBX 또는 PBX 전화 시스템을 연결할 수 있습니다. 고객이 IP PBX를 배포한 경우 또는 PBX가 VoIP를 직접 지원하고 Exchange 음성 메시징 서비스와 상호 운용되는 경우에는 VoIP 미디어 게이트웨이가 필요하지 않습니다. SBC는 온-프레미스 전화 통신 네트워크에 연결하기 위해 고객 네트워크 주변에 배포되며, 도청 및 침입에 대비하여 통신을 보호합니다. 또한 Microsoft Lync Server 2010 및 2013 음성 기능과의 상호 운용성도 지원됩니다.
  
- Exchange Online에서 사용할 수 있는 음성 메시징 서비스 기능은 온-프레미스 Exchange Server 2013에서 제공된 기능과 동일하며, 다음과 같습니다.
    
- Outlook 및 Outlook Web App의 전화에서 재생.
    
- 부재 중 통화 알림.
    
- Voice mail PIN reset from Outlook on the web and Outlook (see [Reset a Voice Mail PIN](/exchange/voice-mail-unified-messaging/set-outlook-voice-access-pin-security/reset-a-voice-mail-pin)).
    
- Outlook Web App 및 Outlook에서 음성 메시지 PIN 다시 설정([음성 메시지 PIN 다시 설정](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/mwi-in-exchange-online) 참조). 
    
- 전화 응답 규칙(자세한 내용은 음성 메일 사용자가 통화를 전달할 수 [있도록 허용](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/allow-voice-mail-users-to-forward-calls) 참조)
    
- Exchange Online의 보호된 음성 메일(자세한 내용은 [Exchange Online에서](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/protect-voice-mail) 음성 메일 보호 참조).
    
- 음성 메일 미리 [보기(지원되는](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/allow-users-to-see-a-voice-mail-transcript) 언어 목록은 사용자가 음성 메일 설명을 볼 수 있도록 허용 참조).
    
- Speech access to email, voice mail, calendar, personal contacts, and personal contact groups.
    
- 전자 메일, 음성 사서함, 일정, 개인 연락처, 개인 메일 그룹에 음성 명령으로 액세스.
    
- Outlook Voice Access 또는 자동 전화 교환을 통한 디렉터리 검색.
    
음성 메일 기능에 대한 자세한 내용은 [Exchange Online의 음성 메일을 참조하세요.](/exchange/voice-mail-unified-messaging/voice-mail-unified-messaging)
  
> [!IMPORTANT]
> The Automatic Speech Recognition (ASR) feature isn't available in menu navigation or directory search for Outlook Voice Access users or auto attendant callers using voice commands. 
>
> 고객은 VoIP 게이트웨이와 PBX, IP PBX 또는 비즈니스용 Skype 서버 2015를 사용하여 PSTN(Public Switched Telephone Network)에서 전화 통신 연결을 제공해야 합니다. 
>
> 고객은 온-프레미스 SBC 하드웨어 장치를 제공하고 이 SBC가 온라인 음성 메일 서비스에 연결하도록 올바르게 구성되어 있는지 확인해야 합니다. 여기에는 인증서와 공용 및 개인 IP 인터페이스를 사용하고 온-프레미스 방화벽을 통해 올바른 TCP 포트를 사용하여 적절한 보안 수준을 구성하는 것이 포함됩니다. 
>
> 호스팅된 음성 메일은 Exchange Online 계획 2 및 Office 365 Enterprise E3 구독자만 사용할 수 있습니다. 
  
## <a name="third-party-voice-mail-interoperability"></a>타사 음성 사서함 상호 운용성

타사 음성 사서함 상호 운용성
  
> [!NOTE]
> Exchange Online UM support for third-party PBX systems via direct connections from customer operated SBCs will end in July 2018. Please see [Discontinuation of support for Session Border Controllers in Exchange Online Unified Messaging](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/Discontinuation-of-support-for-Session-Border-Controllers-in/ba-p/607117) for more information. 
  
## <a name="skype-for-business-integration"></a>비즈니스용 Skype 통합

조직에서는 비즈니스용 Skype Online을 독립 실행형 서비스로 또는 Microsoft Office 365의 일부분으로 구입할 수 있습니다. 비즈니스용 Skype 2015 사내도 지원됩니다. 비즈니스용 Skype Online에 대한 자세한 내용은 비즈니스용 Skype Online 서비스 [설명을 참조하세요.](../skype-for-business-online-service-description/skype-for-business-online-service-description.md)
  
## <a name="feature-availability"></a>기능 가용성

계획, 독립 실행형 옵션 및온-프레미스 솔루션에서 기능 가용성을 확인하면 Exchange Online 서비스 [설명을 참조하세요.](exchange-online-service-description.md)
