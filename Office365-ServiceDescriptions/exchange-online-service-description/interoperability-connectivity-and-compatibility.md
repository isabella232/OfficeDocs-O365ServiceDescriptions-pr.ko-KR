---
title: 상호 운용성, 연결 및 호환성
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-interoperability-connectivity-compatibility
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: cdfe686d-a059-4f4d-bb8d-9c2c0ebfa423
ms.openlocfilehash: b5dd2467010d4f7eb74ba356abc75ff54ad09cf0
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652722"
---
# <a name="interoperability-connectivity-and-compatibility"></a>상호 운용성, 연결 및 호환성

## <a name="interoperability-with-other-microsoft-products"></a>다른 Microsoft 제품과의 상호 운용성

### <a name="skype-for-business-online"></a>비즈니스용 Skype Online

Microsoft Lync Server 2010, Lync Server 2013 또는 Microsoft Office Communications Server 2007 R2를 온-프레미스에 배포한 고객의 경우 Exchange Web Services를 통해 Microsoft Office Communicator를 Microsoft Exchange Online에 연결하여 부재 중 메시지와 일정 데이터에 액세스할 수 있습니다.
  
온-프레미스 Lync Server 2010 및 Lync Server 2013은 그 외에도 다음 두 가지 방법으로 Exchange Online과 상호 운용될 수 있습니다.
  
- 웹용 웹 응용 Outlook IM 및 현재 상태 상호 연동성
    
- 음성 메일 상호 운용성
    
비즈니스용 Skype 서버 2015와 Exchange Online을 함께 구성하는 방법에 대한 자세한 내용은 [Exchange Online과 온-프레미스 비즈니스용 Skype Server 2015의 통합 구성](/skypeforbusiness/deploy/integrate-with-exchange-server/outlook-web-app)을 참조하세요. 하이브리드 구성은 [지원되는 비즈니스용 Skype Server 2015 하이브리드 구성](/skypeforbusiness/skype-for-business-hybrid-solutions/integration-with-exchange-and-sharepoint)을 참조하세요.
  
### <a name="microsoft-sharepoint"></a>Microsoft SharePoint

구독 계획의 일부로 Microsoft SharePoint Server 또는 SharePoint Online을 배포한 고객의 경우 SharePoint 통합 서비스에 Exchange Online 연결할 수 있습니다.
  
SharePoint를 Exchange Online에 연결하는 데 대한 자세한 내용은 [사용자 지정 도메인의 SharePoint Online을 다른 서비스와 함께 사용](https://go.microsoft.com/fwlink/?LinkId=271805)을 참조하세요.
  
## <a name="features-for-external-connectivity"></a>외부 연결 기능

Exchange Online에서는 외부 응용 프로그램과 장치에 연결하기 위해 다음과 같은 기능을 제공합니다.
  
- **MAPI over HTTP, SMTP, POP3, IMAP4 또는 Exchange Web Services와 같은 메시징 프로토콜** 온-프레미스, Azure 또는 다른 호스팅된 서비스에서 실행되는 외부 응용 프로그램은 MAPI over HTTP, SMTP, POP3, IMAPv4 등의 메시징 프로토콜을 사용하여 Exchange Online에서 저장된 데이터에 액세스할 수 있습니다. 응용 프로그램을 개발하는 경우 Exchange Web Services 또는 Exchange Web Services Managed API를 사용하는 것이 좋습니다. 
    
- **SMTP 릴레이** 팩스 게이트웨이, 네트워크 어플라이언스 및 사용자 지정 응용 프로그램에서 보내는 전자 메일 메시지를 릴레이하도록 Exchange Online을 SMTP 배달 서비스로 구성할 수 있습니다. 
    
### <a name="exchange-web-services"></a>Exchange Web Services

EWS(Exchange Web Services)는 Exchange Server 및 Exchange Online을 위한 개발 API로 적합합니다. 관리자는 EWS 또는 EWS Managed API를 사용하여 온-프레미스, Azure 또는 기타 호스트되는 서비스에서 실행되는 응용 프로그램에서 Exchange Online에 저장된 데이터에 액세스할 수 있습니다. 관리자는 EWS를 사용하여 사서함의 콘텐츠 쿼리, 일정 이벤트 게시, 작업 만들기 또는 전자 메일 메시지 내용에 따라 특정 작업을 트리거하는 등의 특수한 작업을 수행할 수 있습니다. Exchange Online에서는 고객 계정에 응용 프로그램 권한을 부여하는 방법으로 EWS 기능이 사용 가능하게 설정됩니다. 이러한 권한이 있으면 고객 응용 프로그램이 응용 프로그램 사서함에 액세스하고 콘텐츠를 추가할 수 있습니다. Exchange 가장 기능은 응용 프로그램 권한을 부여하는 데 사용되는 한 가지 방법입니다. Exchange Online에서 Exchange Web Services를 사용하는 방법에 대한 자세한 내용을 보려면 Exchange Online 개발자 센터에서 제공되는 기술 문서를 참조하십시오.
  
### <a name="smtp-relay"></a>SMTP 릴레이

Exchange Online을 SMTP 배달 서비스로 사용하여 팩스 게이트웨이, 네트워크 어플라이언스 및 사용자 지정 응용 프로그램에서 보낸 전자 메일 메시지를 릴레이할 수 있습니다. 예를 들어 LOB(기간 업무) 응용 프로그램에서 사용자에게 전자 메일 경고를 보낼 경우, Exchange Online을 메일 배달 시스템으로 사용하도록 구성할 수 있습니다. 이 경우 응용 프로그램 또는 서비스는 라이선스가 있는 유효한 Exchange Online 사서함의 사용자 이름과 암호로 인증되어야 하며 TLS(전송 계층 보안)를 사용하여 연결되어야 합니다.
  
## <a name="feature-availability"></a>기능 가용성

계획, 독립 실행형 옵션 및온-프레미스 솔루션에서 기능 가용성을 확인한 경우 서비스 [Exchange Online 참조하세요.](exchange-online-service-description.md)
