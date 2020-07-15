---
title: 메일 흐름
ms.author: office365servicedesc
author: pamelaar
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
description: 대부분의 조직에서는 사서함을 호스트 하 고 메일 흐름을 관리 합니다. 가장 간단한 구성 이며 Microsoft에서 모든 사서함과 필터링을 관리 하는 것을 의미 합니다. 그러나 일부 조직에는 특정 규정 또는 비즈니스적 필요성을 따르는지 확인하기 위하여 좀 더 복잡한 메일 흐름 설정이 필요합니다. 이러한 옵션은 여기에서 확인할 수 있습니다.
ms.openlocfilehash: 1ada5a3199e6ae65c6aaa99873f13a4025366a8d
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132722"
---
# <a name="mail-flow"></a>메일 흐름

대부분의 조직에서는 사서함을 호스트 하 고 메일 흐름을 관리 합니다. 가장 간단한 구성 이며 Microsoft에서 모든 사서함과 필터링을 관리 하는 것을 의미 합니다. 그러나 일부 조직에는 특정 규정 또는 비즈니스적 필요성을 따르는지 확인하기 위하여 좀 더 복잡한 메일 흐름 설정이 필요합니다. 이러한 옵션은 여기에서 확인할 수 있습니다. 
  
## <a name="custom-routing-of-outbound-email"></a>아웃바운드 전자 메일의 사용자 지정 라우팅

Microsoft Exchange Online은 온-프레미스 서버 또는 호스팅된 서비스 ("스마트 호스팅"이 라고도 함)를 통해 조직의 메일 흐름을 라우팅할 수 있습니다. 이를 통해 조직은 DLP (데이터 손실 방지) 기기를 사용 하 고, 보내는 전자 메일의 사용자 지정 사후 처리를 수행 하 고, 개인 네트워크를 통해 비즈니스 파트너에 게 전자 메일을 배달할 수 있습니다. 또한 Exchange Online에서는 주소를 수정 하는 온-프레미스 게이트웨이를 통해 보내는 전자 메일을 라우팅하는 주소 다시 쓰기도 지원 합니다. 이 기능을 사용 하면 하위 도메인을 숨기 거 나, 다중 도메인 조직의 전자 메일을 단일 도메인으로 표시 하거나, 파트너 릴레이 된 전자 메일을 조직 내부에서 보낸 것 처럼 표시 되도록 할 수 있습니다. 관리자는 EAC (Exchange 관리 센터) 내에서 사용자 지정 전자 메일 라우팅을 구성 합니다.
  
자세한 내용은 [커넥터를 설정 하 여 Microsoft와 자체 전자 메일 서버 간에 메일 라우팅를](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail)참조 하세요.
  
> [!IMPORTANT]
> Exchange Online은 메일 흐름을 조직 내외부로 전달할 수 있습니다. 받는 사람 도메인이 Exchange online에서 호스트 되는 경우 DNS MX 레코드를 사용 하 여 받는 사람에 대 한 메일 흐름은 인터넷을 통해 전송 되지 않습니다.
  
## <a name="secure-messaging-with-a-trusted-partner"></a>신뢰할 수 있는 파트너와의 보안 메시징

Exchange Online 고객은 Microsoft 커넥터를 사용 하 여 신뢰할 수 있는 파트너와 보안 메일 흐름을 설정 하는 것이 가능 합니다. Microsoft는 TLS (전송 계층 보안)를 통한 보안 통신을 지원 하며 TLS를 통해 암호화를 적용 하는 커넥터를 만들 수 있습니다. [TLS](https://docs.microsoft.com/office365/securitycompliance/exchange-online-uses-tls-to-secure-email-connections) 는 인터넷을 통한 통신에 보안을 제공 하는 암호화 프로토콜입니다. 커넥터를 사용하면 자체 서명된 인증서 또는 CA(인증 기관) 확인 인증서를 통해 강제로 받거나 보내는 TLS를 모두 구성할 수 있습니다. 도메인 이름 또는 파트너 조직에서 메일을 보내는 IP 주소 범위를 지정하는 것과 같은 기타 보안 제한을 적용할 수도 있습니다. 
  
자세한 내용은 [Set up connectors for secure mail flow with a partner organization](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner)을 참조하세요.
  
> [!IMPORTANT]
> CA 확인 인증서가 필요할 수 있습니다. 
  
## <a name="conditional-mail-routing"></a>조건부 메일 라우팅

You can direct mail to specific sites by using connectors and transport rules. With criteria-based routing, you can choose a connector based on specific conditions.
  
자세한 내용은 [Scenario: Conditional mail routing](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing)을 참조하세요.
  
## <a name="incoming-mail-safe-list"></a>받는 메일 수신 허용 목록

You can add a trusted partner's IP address to a safe list to ensure that messages the partner sends to you are not subject to anti-spam filtering. To do this, you can use the connection filter's IP Allow list.
  
자세한 내용은 [Configure the connection filter policy](https://docs.microsoft.com/office365/SecurityCompliance/configure-the-connection-filter-policy)을 참조하세요.
  
## <a name="hybrid-email-routing"></a>하이브리드 전자 메일 라우팅

A hybrid deployment gives organizations the ability to extend the feature-rich experience and administrative control they have with their existing on-premises Microsoft Exchange organization to the cloud. With hybrid transport, messages sent between recipients in either organization are authenticated, encrypted, and transferred using Transport Layer Security (TLS), and appear as "internal" to Exchange components such as transport rules, journaling, and anti-spam policies. You configure hybrid transport by using the Hybrid Configuration Wizard in Exchange Server.
  
하이브리드 배포의 메일 라우팅에 대한 자세한 내용은 [Exchange 하이브리드 배포의 전송 라우팅](https://go.microsoft.com/fwlink/p/?LinkId=271757)을 참조하세요.
  
[Microsoft Exchange Server 배포 도우미](https://go.microsoft.com/fwlink/p/?LinkId=287036) 또한 자세한 하이브리드 배포 프로비전 및 하이브리드 메시지 전송 지침을 제공합니다. 
  
### <a name="shared-address-space-with-on-premises-routing-control-mx-points-to-on-premises"></a>온-프레미스 라우팅 제어를 사용하는 공유 주소 공간(MX가 온-프레미스를 가리킴)

온-프레미스 라우팅 제어를 사용 하는 공유 주소 공간 (MX to 온-프레미스)은 사서함이 Exchange Online 및 일부 온-프레미스에서 부분적으로 호스트 되 고 들어오고 나가는 인터넷 메일 흐름이 온-프레미스 Exchange 조직을 통해 라우팅되는 하이브리드 배포 메일 라우팅 시나리오입니다. 이 시나리오는 중앙 집중식 메일 전송이라고도 합니다. 이 시나리오에서 Exchange Online은 EOP을 사용 하 여 구축 되 고, 들어오는 인터넷 메일은 EOP로 라우팅되고 Exchange Online에서 호스트 되는 사서함으로 라우팅되도록 하기 전에 온-프레미스 메일 서버로 라우팅됩니다. 또한 Exchange Online 사서함에서 보내는 메일의 경우 외부의 받는 사람에게 보내는 메시지는 온-프레미스 Exchange 조직을 통해 라우팅됩니다. 이 구성을 사용하면 온-프레미스 Exchange 조직과 Exchange Online 조직의 모든 사서함에 대해 단일 SMTP 도메인 네임스페이스를 사용할 수 있습니다. 
  
하이브리드 배포의 전송 옵션에 대한 자세한 내용은 [Exchange 하이브리드 배포에서의 전송 옵션](https://go.microsoft.com/fwlink/p/?LinkID=271758)을 참조하세요.
  
### <a name="shared-address-space-without-on-premises-routing-control-mx-points-to-eop"></a>온-프레미스 라우팅 제어를 사용하지 않는 공유 주소 공간(MX가 EOP를 가리킴)

온-프레미스 라우팅 제어를 사용하지 않는 공유 주소 공간(MX가 EOP를 가리킴)은 사서함이 Exchange Online을 통해 클라우드에서 일부 호스트 되고 온-프레미스로도 일부 호스트되는 하이브리드 메일 라우팅 시나리오로, MX 레코드는 EOP를 가리킵니다. 이 시나리오는 Microsoft를 사용 하 여 조직의 사서함 일부를 호스트 하 고 EOP에서 온-프레미스 및 클라우드 사서함을 모두 보호 하려는 경우에 적합 합니다. 이 시나리오에서 조직 내의 받는 사람에게 보낸 메일은 온-프레미스 사서함 및 클라우드 사서함에 도달하기 전에 먼저 스팸 및 정책 필터링이 적용되는 EOP를 통해 라우팅 됩니다. 
  
하이브리드 배포의 전송 옵션에 대한 자세한 내용은 [Exchange 하이브리드 배포에서의 전송 옵션](https://go.microsoft.com/fwlink/p/?LinkID=271758)을 참조하세요.
  
### <a name="troubleshooting-a-deployment-with-the-hybrid-configuration-wizard"></a>하이브리드 구성 마법사를 사용하여 배포 문제 해결

Using the Hybrid Configuration Wizard to configure a hybrid deployment in Microsoft Exchange Server greatly minimizes the potential that the hybrid deployment will experience problems. However, there are some typical areas outside the scope of the Hybrid Configuration Wizard that, if misconfigured, may present problems in a hybrid deployment. These include proper Client Access server configuration and proper certificate installation and configuration.
  
하이브리드 구성 마법사를 사용하여 배포 문제를 해결하는 방법에 대한 자세한 내용은 [하이브리드 배포 문제 해결](https://go.microsoft.com/fwlink/p/?LinkId=271040)을 참조하세요.
  
### <a name="managing-a-hybrid-configuration"></a>하이브리드 구성 관리

You can modify an existing hybrid configuration by changing settings in the Hybrid Configuration Wizard. Scenarios include disabling centralized transport or disabling secure mail transport.
  
하이브리드 배포 구성 관리에 대한 자세한 내용은 [하이브리드 배포 관리](https://go.microsoft.com/fwlink/p/?LinkId=271044)를 참조하세요.
  
### <a name="hybrid-deployment-requirements"></a>하이브리드 배포 요구 사항

하이브리드 배포 요구 사항에 대한 자세한 내용은 [하이브리드 배포 필수 구성 요소](https://go.microsoft.com/fwlink/p/?LinkId=271759)를 참조하세요.
  
> [!IMPORTANT]
> 일부 하이브리드 구성에서는 온-프레미스 사서함에 대해 Exchange Online Protection 라이선스를 구입해야 할 수 있습니다. 
  
## <a name="feature-availability"></a>기능 가용성

계획, 독립 실행형 옵션 및 온-프레미스 솔루션 별로 기능 가용성을 확인 하려면 [Exchange Online 서비스 설명을](exchange-online-service-description.md)참조 하세요.
  