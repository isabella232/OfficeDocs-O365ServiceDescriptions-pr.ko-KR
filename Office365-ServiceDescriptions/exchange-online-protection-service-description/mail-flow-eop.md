---
title: Exchange Online Protection의 메일 흐름
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: 이 문서를 읽고 EOP(Microsoft Exchange Online 보호)의 메일 흐름에 대해 자세히 알아보습니다.
ms.openlocfilehash: 0923f31ccb639271303654cbdccf4890b2a55062
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653140"
---
# <a name="mail-flow-in-exchange-online-protection"></a>Exchange Online Protection의 메일 흐름

Microsoft를 사용하는 대부분의 조직에서는 사서함을 호스트하고 메일 흐름을 관리합니다. 가장 간단한 구성으로, Microsoft가 모든 사서함 및 필터링을 관리합니다. 그러나 일부 조직에서는 모든 사서함을 온-프레미스로 유지해야 할 비즈니스적 필요성을 느낍니다. EOP(Exchange Online Protection)를 사용하면 이 작업을 할 수 있으며 클라우드에서 바이러스 백신 및 스팸 방지 메일 처리를 제공합니다. EOP에 대한 자세한 내용과 구매 정보는 [Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection)을 참조하세요.
  
도메인 관리 또는 DBEB(디렉터리 기반 Edge 차단)에 대한 정보를 찾고 있나요? 받는 [사람, 도메인 및 회사 관리를 참조합니다.](recipient-domain-and-company-management.md) 모든 EOP 기능에 대한 자세한 내용은 [Exchange Online Protection 서비스 설명 을 참조하세요.](exchange-online-protection-service-description.md)
  
## <a name="routing-email-between-microsoft-and-your-own-email-servers"></a>Microsoft와 자체 전자 메일 서버 간의 전자 메일 라우팅

Microsoft(Exchange Online 또는 EOP 포함)와 Exchange와 같은 SMTP 기반 전자 메일 서버 간의 메일 흐름을 사용하도록 커넥터를 구성할 수 있습니다. 이에 대한 자세한 정보는 [Do I need a connector](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/do-i-need-to-create-a-connector)? 또한 [커넥터를 설정하여 Microsoft와](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail)자체 전자 메일 서버 간에 메일을 라우팅합니다.
  
## <a name="secure-messaging-with-a-trusted-partner"></a>신뢰할 수 있는 파트너와의 보안 메시징

EOP 고객은 Microsoft 커넥터를 사용하여 신뢰할 수 있는 파트너와의 보안 메일 흐름을 설정할 수 있습니다. Microsoft는 TLS(전송 계층 보안)를 통한 보안 통신을 지원하며 TLS를 통해 암호화를 적용하는 커넥터를 만들 수 있습니다. [TLS는](/microsoft-365/compliance/exchange-online-uses-tls-to-secure-email-connections) 인터넷을 통해 통신하는 데 보안을 제공하는 암호화 프로토콜입니다. 커넥터를 사용하면 자체 서명된 인증서 또는 CA(인증 기관) 확인 인증서를 통해 강제로 받거나 보내는 TLS를 모두 구성할 수 있습니다. 도메인 이름 또는 파트너 조직에서 메일을 보내는 IP 주소 범위를 지정하는 것과 같은 기타 보안 제한을 적용할 수도 있습니다. 
  
자세한 내용은 [Set up connectors for secure mail flow with a partner organization](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner)을 참조하세요.
  
## <a name="safe-listing-a-partners-ip-address"></a>수신 허용 목록에 파트너의 IP 주소 추가

신뢰할 수 있는 파트너의 IP 주소를 수신 허용 목록에 추가하여 해당 파트너가 보내는 메시지에 스팸 필터링이 적용되지 않도록 할 수 있습니다. 이렇게 하려면 연결 필터의 IP 허용 목록을 사용하면 됩니다. 자세한 내용은 [연결 필터 정책 구성](/microsoft-365/security/office-365-security/configure-the-connection-filter-policy)을 참조하세요.
  
## <a name="conditional-mail-routing"></a>조건부 메일 라우팅

조건에 따라 메일을 특정 사이트로 라우팅하는 전송 규칙을 사용하여 커넥터를 구성할 수 있습니다. 자세한 내용은 [Scenario: Conditional email routing](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing)을 참조하세요.
  
## <a name="hybrid-mail-routing"></a>하이브리드 메일 라우팅

하이브리드란 사서함의 일부분을 온-프레미스에서, 다른 일부분은 클라우드(Exchange Online)에서 호스트하는 것을 의미합니다. 독립 실행형(온-프레미스) 배포에서 하이브리드 배포로 이동할 수 있습니다.
  
하이브리드 배포를 사용하는 경우 EOP를 통해 클라우드 및 온-프레미스 사서함을 보호할 수 있습니다. EOP를 통해 보호되는 온-프레미스 사서함에는 독립 실행형 라이선스가 필요합니다. 하이브리드 배포의 메일 라우팅에 대한 자세한 내용은 [Exchange 하이브리드 배포의 전송 라우팅](/exchange/transport-routing)을 참조하세요.
  
[Microsoft Exchange Server 배포 도우미](/exchange/exchange-deployment-assistant) 또한 자세한 하이브리드 배포 프로비전 및 하이브리드 메시지 전송 지침을 제공합니다. 
  
## <a name="feature-availability"></a>기능 가용성

계획, 독립 실행형 옵션 및온-프레미스 솔루션에서 기능 가용성을 확인하면 Exchange Online Protection 서비스 [설명을 참조하세요.](exchange-online-protection-service-description.md)