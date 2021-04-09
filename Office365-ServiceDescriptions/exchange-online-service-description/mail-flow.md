---
title: 메일 흐름
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-mail-flow
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 8e5267e6-d224-485b-a081-c71a1fd0c4c3
description: 대부분의 조직에서는 사서함을 호스트하고 메일 흐름을 관리합니다. 가장 간단한 구성으로, Microsoft가 모든 사서함 및 필터링을 관리합니다. 그러나 일부 조직에는 특정 규정 또는 비즈니스적 필요성을 따르는지 확인하기 위하여 좀 더 복잡한 메일 흐름 설정이 필요합니다. 이러한 옵션은 여기에서 확인할 수 있습니다.
ms.openlocfilehash: 0fe7cf2f0e8619bce911457ba634bee41ee4e113
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653330"
---
# <a name="mail-flow"></a>메일 흐름

대부분의 조직에서는 사서함을 호스트하고 메일 흐름을 관리합니다. 가장 간단한 구성으로, Microsoft가 모든 사서함 및 필터링을 관리합니다. 그러나 일부 조직에는 특정 규정 또는 비즈니스적 필요성을 따르는지 확인하기 위하여 좀 더 복잡한 메일 흐름 설정이 필요합니다. 이러한 옵션은 여기에서 확인할 수 있습니다. 
  
## <a name="custom-routing-of-outbound-email"></a>아웃바운드 전자 메일의 사용자 지정 라우팅

Microsoft Exchange Online 서버 또는 호스팅된 서비스를 통해 조직에서 흐르는 메일을 라우팅할 수 있습니다("스마트 호스팅"이라고도 합니다). 이를 통해 조직은 DLP(데이터 손실 방지) 어플라이언스를 사용하며, 전자 메일의 사용자 지정 사후 처리를 수행하고, 개인 네트워크를 통해 비즈니스 파트너에게 전자 메일을 전달할 수 있습니다. 또한 Exchange Online에서는 주소를 수정하는 사내 게이트웨이를 통해 발신 전자 메일을 라우팅하는 주소 다시 필기도 지원됩니다. 이 기능을 사용하면 하위 도메인을 숨기거나, 다중 도메인 조직의 전자 메일을 단일 도메인으로 표시하거나, 파트너 릴레이 전자 메일이 조직 내부에서 보낸 것으로 표시될 수 있습니다. 관리자는 EAC(Exchange 관리 센터) 내에서 사용자 지정 전자 메일 라우팅을 구성합니다.
  
자세한 내용은 [Set up connectors to route mail between Microsoft and your own email servers을 참조하세요.](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail)
  
> [!IMPORTANT]
> Exchange Online은 메일 흐름을 조직 내외부로 전달할 수 있습니다. 받는 사람 도메인이 Exchange Online Protection을 지정하는 DNS MX 레코드를 사용하여 Exchange Online에서 호스팅된 경우 테넌트에서 받는 사람으로의 메일 흐름이 인터넷을 통해 이동하지 않습니다.
  
## <a name="secure-messaging-with-a-trusted-partner"></a>신뢰할 수 있는 파트너와의 보안 메시징

Exchange Online 고객은 Microsoft 커넥터를 사용하여 신뢰할 수 있는 파트너와의 보안 메일 흐름을 설정할 수 있습니다. Microsoft는 TLS(전송 계층 보안)를 통한 보안 통신을 지원하며 TLS를 통해 암호화를 적용하는 커넥터를 만들 수 있습니다. [TLS는](/office365/securitycompliance/exchange-online-uses-tls-to-secure-email-connections) 인터넷을 통해 통신하는 데 보안을 제공하는 암호화 프로토콜입니다. 커넥터를 사용하면 자체 서명된 인증서 또는 CA(인증 기관) 확인 인증서를 통해 강제로 받거나 보내는 TLS를 모두 구성할 수 있습니다. 도메인 이름 또는 파트너 조직에서 메일을 보내는 IP 주소 범위를 지정하는 것과 같은 기타 보안 제한을 적용할 수도 있습니다. 
  
자세한 내용은 [Set up connectors for secure mail flow with a partner organization](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner)을 참조하세요.
  
> [!IMPORTANT]
> CA 확인 인증서가 필요할 수 있습니다. 
  
## <a name="conditional-mail-routing"></a>조건부 메일 라우팅

커넥터와 전송 규칙을 사용하여 메일을 특정 사이트에 전송할 수 있습니다. 기준 기반 라우팅을 사용하면 특정 조건에 따라 커넥터를 선택할 수 있습니다.
  
자세한 내용은 [Scenario: Conditional mail routing](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing)을 참조하세요.
  
## <a name="incoming-mail-safe-list"></a>받는 메일 수신 허용 목록

신뢰할 수 있는 파트너의 IP 주소를 수신 허용 목록에 추가하여 해당 파트너가 보내는 메시지에 스팸 방지 필터링이 적용되지 않도록 할 수 있습니다. 이렇게 하려면 연결 필터의 IP 허용 목록을 사용하면 됩니다.
  
자세한 내용은 [Configure the connection filter policy](/office365/SecurityCompliance/configure-the-connection-filter-policy)을 참조하세요.
  
## <a name="hybrid-email-routing"></a>하이브리드 전자 메일 라우팅

조직에서 하이브리드 배포를 사용하면 기존 온-프레미스 Microsoft Exchange 조직의 다양한 기능과 관리 제어 능력을 클라우드로 확장할 수 있습니다. 하이브리드 전송을 사용하면 한 조직의 받는 사람 간에 전송된 메시지가 TLS(전송 계층 보안)를 사용하여 인증, 암호화 및 전송되며 전송 규칙, 저널링 및 스팸 방지 정책과 같은 Exchange 구성 요소에 "내부"로 표시됩니다. Exchange Server의 하이브리드 구성 마법사를 사용하여 하이브리드 전송을 구성합니다.
  
하이브리드 배포의 메일 라우팅에 대한 자세한 내용은 [Exchange 하이브리드 배포의 전송 라우팅](/exchange/transport-routing)을 참조하세요.
  
[Microsoft Exchange Server 배포 도우미](/exchange/exchange-deployment-assistant) 또한 자세한 하이브리드 배포 프로비전 및 하이브리드 메시지 전송 지침을 제공합니다. 
  
### <a name="shared-address-space-with-on-premises-routing-control-mx-points-to-on-premises"></a>온-프레미스 라우팅 제어를 사용하는 공유 주소 공간(MX가 온-프레미스를 가리킴)

MX가 On-Premises Routing Control을 사용하여 공유 주소 공간(MX가 On-Premises를 연결함)은 사서함이 Exchange Online에서 부분적으로 호스트되고, 들어오는 인터넷 메일 흐름과 들어오는 인터넷 메일 흐름이 사내 Exchange 조직을 통해 라우팅되는 하이브리드 배포 메일 라우팅 시나리오입니다. 이 시나리오는 중앙 집중식 메일 전송이라고도 합니다. 이 시나리오에서는 Exchange Online이 EOP를 통해 프로비전되고 받는 인터넷 메일이 EOP로 라우팅되기 전에, 그리고 마지막으로 Exchange Online에서 호스트되는 사서함으로 라우팅됩니다. 또한 Exchange Online 사서함에서 보내는 메일의 경우 외부의 받는 사람에게 보내는 메시지는 온-프레미스 Exchange 조직을 통해 라우팅됩니다. 이 구성을 사용하면 온-프레미스 Exchange 조직과 Exchange Online 조직의 모든 사서함에 대해 단일 SMTP 도메인 네임스페이스를 사용할 수 있습니다. 
  
하이브리드 배포의 전송 옵션에 대한 자세한 내용은 [Exchange 하이브리드 배포에서의 전송 옵션](/exchange/transport-options)을 참조하세요.
  
### <a name="shared-address-space-without-on-premises-routing-control-mx-points-to-eop"></a>온-프레미스 라우팅 제어를 사용하지 않는 공유 주소 공간(MX가 EOP를 가리킴)

온-프레미스 라우팅 제어를 사용하지 않는 공유 주소 공간(MX가 EOP를 가리킴)은 사서함이 Exchange Online을 통해 클라우드에서 일부 호스트 되고 온-프레미스로도 일부 호스트되는 하이브리드 메일 라우팅 시나리오로, MX 레코드는 EOP를 가리킵니다. 이 시나리오는 Microsoft를 사용하여 조직의 사서함 중 일부를 호스팅하고 EOP가 사용자 사서함과 클라우드 사서함을 모두 보호하려는 경우에 적절합니다. 이 시나리오에서 조직 내의 받는 사람에게 보낸 메일은 온-프레미스 사서함 및 클라우드 사서함에 도달하기 전에 먼저 스팸 및 정책 필터링이 적용되는 EOP를 통해 라우팅 됩니다. 
  
하이브리드 배포의 전송 옵션에 대한 자세한 내용은 [Exchange 하이브리드 배포에서의 전송 옵션](/exchange/transport-options)을 참조하세요.
  
### <a name="troubleshooting-a-deployment-with-the-hybrid-configuration-wizard"></a>하이브리드 구성 마법사를 사용하여 배포 문제 해결

하이브리드 구성 마법사를 사용하여 Microsoft Exchange Server에서 하이브리드 배포를 구성하면 하이브리드 배포 관련 문제가 발생할 가능성이 최소화됩니다. 그러나 잘못 구성될 경우 하이브리드 배포에서 문제를 일으킬 수 있는, 하이브리드 구성 마법사의 범위를 벗어난 영역이 몇 군데 있습니다. 적절한 클라이언트 액세스 서버 구성과 적절한 인증서 설치 및 구성이 여기에 해당합니다.
  
하이브리드 구성 마법사를 사용하여 배포 문제를 해결하는 방법에 대한 자세한 내용은 [하이브리드 배포 문제 해결](/exchange/hybrid-deployment/troubleshoot-a-hybrid-deployment)을 참조하세요.
  
### <a name="managing-a-hybrid-configuration"></a>하이브리드 구성 관리

하이브리드 구성 마법사에서 설정을 변경하여 기존 하이브리드 구성을 수정할 수 있습니다. 예를 들면, 중앙 집중식 전송을 사용하지 않도록 설정하거나 보안 메일 전송을 사용하지 않도록 설정하는 것입니다.
  
하이브리드 배포 구성 관리에 대한 자세한 내용은 [하이브리드 배포 관리](/previous-versions/exchange-server/exchange-150/jj200791(v=exchg.150))를 참조하세요.
  
### <a name="hybrid-deployment-requirements"></a>하이브리드 배포 요구 사항

하이브리드 배포 요구 사항에 대한 자세한 내용은 [하이브리드 배포 필수 구성 요소](/exchange/hybrid-deployment-prerequisites)를 참조하세요.
  
> [!IMPORTANT]
> 일부 하이브리드 구성에서는 온-프레미스 사서함에 대해 Exchange Online Protection 라이선스를 구입해야 할 수 있습니다. 
  
## <a name="feature-availability"></a>기능 가용성

계획, 독립 실행형 옵션 및온-프레미스 솔루션에서 기능 가용성을 확인 내용은 Exchange Online 서비스 [설명 을 참조하세요.](exchange-online-service-description.md)
