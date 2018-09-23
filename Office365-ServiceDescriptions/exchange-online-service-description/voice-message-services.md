---
title: 음성 메시지 서비스
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-voice-message-services
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a02af6e2-75c2-4e83-843e-77241072068e
ms.openlocfilehash: 98591e47ece7c59581824c6df375c41c66b7d2d1
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036580"
---
# <a name="voice-message-services"></a>음성 메시지 서비스

## <a name="voice-mail"></a>음성 사서함

Microsoft Exchange Online에서는 호스트된 음성 메일 서비스를 제공합니다. 이 서비스의 기능은 다음과 같습니다.
  
- 전화 응답(음성 사서함)
    
- Exchange에 대한 전화 접속 사용자 인터페이스(Outlook Voice Access)
    
- Exchange에 대한 전화 접속 사용자 인터페이스(Outlook Voice Access)
    
발신자용 전화 접속 인터페이스(자동 전화 교환)
  
호스트된 음성 메시징 서비스를 사용하면 기업의 온-프레미스 전화 시스템을 Exchange Online에서 제공하는 음성 메일 서비스에 연결할 수 있습니다. 음성 메일 메시지는 Exchange Online 인프라에 기록 및 저장되므로 사용자가 Outlook, Outlook Web Access 또는 휴대폰에서 음성 메시지에 액세스할 수 있습니다. Exchange Online에 대한 모든 전화 통신 연결에는 VoIP(Voice-over-IP) 프로토콜이 필요합니다. 관리자는 VoIP 미디어 게이트웨이 및 SBC(Session Border Controller)를 사용하여 온-프레미스 IP PBX 또는 PBX 전화 시스템을 연결할 수 있습니다. 고객이 IP PBX를 배포한 경우 또는 PBX가 VoIP를 직접 지원하고 Exchange 음성 메시징 서비스와 상호 운용되는 경우에는 VoIP 미디어 게이트웨이가 필요하지 않습니다. SBC는 온-프레미스 전화 통신 네트워크에 연결하기 위해 고객 네트워크 주변에 배포되며, 도청 및 침입에 대비하여 통신을 보호합니다. 또한 Microsoft Lync Server 2010 및 2013 음성 기능과의 상호 운용성도 지원됩니다.
  
- Exchange Online에서 사용할 수 있는 음성 메시징 서비스 기능은 온-프레미스 Exchange Server 2013에서 제공된 기능과 동일하며, 다음과 같습니다.
    
- Outlook 및 Outlook Web App의 전화에서 재생.
    
- 부재 중 통화 알림.
    
- 음성 메일 PIN ( [음성 메일 PIN 다시 설정](https://go.microsoft.com/fwlink/p/?LinkId=286328)참조)는 웹 및 Outlook에서 Outlook에서 다시 설정 합니다.
    
- Outlook Web App 및 Outlook에서 음성 메시지 PIN 다시 설정([음성 메시지 PIN 다시 설정](https://go.microsoft.com/fwlink/p/?LinkId=271794) 참조). 
    
- 전화 응답 규칙(자세한 내용은 [음성 사서함 사용자가 착신 전환하도록 허용](https://go.microsoft.com/fwlink/p/?LinkId=271795) 참조). 
    
- Exchange Online의 보호된 음성 메일(자세한 내용은 [Exchange Online의 보호된 음성 메일](https://go.microsoft.com/fwlink/p/?LinkId=271796) 참조). 
    
- 음성 메일 미리 보기(지원되는 언어 목록은 [사용자가 음성 메일 스크립트를 보도록 허용](https://go.microsoft.com/fwlink/p/?LinkId=271797) 참조). 
    
- 전자 메일, 음성 사서함, 일정, 개인 연락처, 개인 메일 그룹에 음성 명령으로 액세스.
    
- Outlook Voice Access 또는 자동 전화 교환을 통한 디렉터리 검색.
    
- 관리자는 EAC(Exchange 관리 센터)를 사용하여 음성 메시징 서비스 상호 운용성을 구성 및 관리합니다.
    
음성 사서함 기능에 대한 자세한 내용은 [Exchange Online의 음성 사서함](https://go.microsoft.com/fwlink/p/?LinkId=271798)을 참조하세요.
  
> [!IMPORTANT]
> Outlook Voice Access 사용자 또는 음성 명령을 사용하는 자동 전화 교환 발신자는 메뉴 탐색이나 디렉터리 검색에서 ASR(자동 음성 인식) 기능을 사용할 수 없습니다. > 고객은 VoIP 게이트웨이 및 PBX, IP PBX 또는 비즈니스용 Skype 서버 2015를 사용하여 PSTN(공중 전화망)으로부터의 전화 통신 연결을 제공해야 합니다. > 고객은 온-프레미스 SBC 하드웨어 장치를 제공하고 이 SBC가 온라인 음성 메일 서비스에 연결하도록 올바르게 구성되어 있는지 확인해야 합니다. 여기에는 인증서와 공용 및 개인 IP 인터페이스를 사용하고 온-프레미스 방화벽을 통해 올바른 TCP 포트를 사용하여 적절한 보안 수준을 구성하는 것이 포함됩니다. > 호스트된 음성 메일은 Exchange Online 계획 2 및 Office 365 Enterprise E3 구독자만 사용할 수 있습니다. 
  
## <a name="third-party-voice-mail-interoperability"></a>타사 음성 사서함 상호 운용성

타사 공급자의 온-프레미스 음성 메일 솔루션이 SMTP를 통해 음성 메시지를 전달할 수 있거나 Microsoft Exchange Web Services를 지원하는 경우 Exchange Online과 상호 운용될 수 있습니다. 음성 메일 시스템이 기본적으로 SMTP를 통한 음성 메시지 전달을 지원하지 않으면 전자 메일 서버는 온-프레미스를 유지하여 음성 메일 시스템에서 메시지를 받은 다음 SMTP를 사용하여 클라우드로 전달할 수 있습니다. 많은 타사 음성 메일 시스템은 고급 UM 기능을 위해 MAPI/CDO를 사용하여 Exchange Server와 상호 운용하므로 Exchange Online과의 상호 운용에 SMTP가 사용되는 경우 이러한 시스템의 전체 기능을 사용하지 못할 수 있습니다.
  
> [!NOTE]
> 7 월 2018에서 작동 하는 고객 Sbc에서 직접 연결을 통해 타사 PBX 시스템에 대 한 Exchange Online UM 지원 종료 됩니다. 자세한 내용은 [Exchange Online 통합 메시징에 세션 테두리 컨트롤러에 대 한 지원 한 중단](https://blogs.technet.microsoft.com/exchange/2017/07/18/discontinuation-of-support-for-session-border-controllers-in-exchange-online-unified-messaging/) 을 참조 하십시오. 
  
## <a name="skype-for-business-integration"></a>비즈니스용 Skype 통합

조직에서는 비즈니스용 Skype Online을 독립 실행형 서비스로 또는 Microsoft Office 365의 일부분으로 구입할 수 있습니다. 비즈니스용 Skype Online에 대한 자세한 내용은 [비즈니스용 Skype Online 서비스 설명](../skype-for-business-online-service-description/skype-for-business-online-service-description.md)을 참조하세요.
  
## <a name="feature-availability"></a>기능 가용성

Office 365 계획, 독립 실행형 옵션 및 온-프레미스 솔루션별로 기능 가용성을 확인하려면 [Exchange Online 서비스 설명](exchange-online-service-description.md)을 참조하세요.
  

