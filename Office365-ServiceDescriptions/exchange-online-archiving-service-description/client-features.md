---
title: Exchange Online Archiving의 클라이언트 기능
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
audience: ITPro
ms.topic: reference
f1_keywords:
- clients-and-devices-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c8d5f97a-607f-4949-a4f7-0b9e3b246851
description: Microsoft Exchange Online 보관을 통해 사용자는 다양 한 장치 및 플랫폼에서 보관 사서함에 연결할 수 있습니다. 사용자의 보관 사서함에 대한 모든 네트워크 연결은 인터넷을 통해 수행되므로 VPN(가상 사설망) 연결은 필요하지 않습니다. 조직은 사용자가 VPN 연결을 사용하지 않고도 외부에서 Outlook 사용 를 통해 기본 사서함에 액세스할 수 있도록 온-프레미스 클라이언트 액세스 서버를 게시할 수 있습니다. 온-프레미스 서버에 있는 사용자의 기본 사서함에 액세스하기 위해 VPN 액세스가 필요한 경우에도 이 요구 사항은 변경되지 않습니다.
ms.openlocfilehash: 616de5cb187f74b048d14770abb8fe640d0782d3
ms.sourcegitcommit: 15e92292209454f6778bfef26ecab96bfc71ef5f
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/22/2019
ms.locfileid: "34341847"
---
# <a name="client-features-in-exchange-online-archiving"></a>Exchange Online Archiving의 클라이언트 기능

Microsoft Exchange Online 보관을 통해 사용자는 다양 한 장치 및 플랫폼에서 보관 사서함에 연결할 수 있습니다. 사용자의 보관 사서함에 대한 모든 네트워크 연결은 인터넷을 통해 수행되므로 VPN(가상 사설망) 연결은 필요하지 않습니다. 조직은 사용자가 VPN 연결을 사용하지 않고도 외부에서 Outlook 사용 를 통해 기본 사서함에 액세스할 수 있도록 온-프레미스 클라이언트 액세스 서버를 게시할 수 있습니다. 온-프레미스 서버에 있는 사용자의 기본 사서함에 액세스하기 위해 VPN 액세스가 필요한 경우에도 이 요구 사항은 변경되지 않습니다.
  
> [!IMPORTANT]
> Microsoft는 Exchange Online Archiving 서비스 상태를 악화시키는 모든 클라이언트 소프트웨어로부터의 연결을 차단하거나 제한할 수 있는 권한을 보유합니다. 
  
## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook은 일정, 연락처 및 작업을 지원하는 기능이 포함된 유용한 전자 메일 프로그램입니다. Exchange Online Archiving에서는 Outlook 2013, Outlook 2010 및 Outlook 2007을 지원합니다. 주요 기능은 다음과 같습니다.
  
- **외부에서 Outlook 사용** Outlook 사용자는 외부에서 Outlook 사용 를 통해 VPN 연결을 사용하지 않고도 인터넷에서 Exchange Server와 Exchange Online Archiving에 연결할 수 있습니다. Outlook과 Exchange Online Archiving 간의 통신은 RPC-over-HTTP Windows 네트워킹 구성 요소를 사용하여 SSL 보안 터널을 통해 수행됩니다. 
    
- **자동 검색** Exchange 자동 검색 서비스는 Outlook을 Exchange Online Archiving과 함께 자동으로 작동하도록 구성합니다. Outlook 사용자는 자동 검색을 통해 전자 메일 주소와 암호로 처음 로그인할 때, 필요한 프로필 설정을 Exchange에서 직접 받을 수 있습니다. 첫 로그인 이후에는 설정이 일정한 간격으로 수신됩니다. 
    
Outlook 2010 이상 버전과 Outlook Web App에서는 사용자에게 보관 사서함의 모든 기능은 물론 보존 및 보관 정책과 같은 관련 기능도 제공합니다.
  
Outlook 2007은 보관 사서함을 기본적으로 지원하지만 일부 보관 및 규정 준수 기능은 Outlook 2007에서 사용할 수 없습니다. 예를 들어 Outlook 2007에서는 사용자가 사서함의 항목에 보존 또는 보관 정책을 적용할 수 없습니다. 그 대신에 관리자가 프로비저닝한 정책을 사용해야 합니다. Outlook 2007 사용자의 경우 보관 사서함에 액세스하려면 2011년 2월 Office 2007 누적 업데이트가 필요합니다.
  
> [!NOTE]
> Exchange Online Archiving에서는 Outlook이 제공되지 않습니다. 일부 Office 365 계획에는 Microsoft Office 365 ProPlus(Microsoft Outlook 포함)가 포함되어 있고, 별도의 구독을 구입할 수도 있습니다. 자세한 내용은 [Office 365 계획 옵션](../office-365-platform-service-description/office-365-plan-options.md)을 참조하세요. Office 365 ProPlus에 대한 자세한 내용은 [Office 응용 프로그램 서비스 설명](../office-applications-service-description/office-applications-service-description.md)을 참조하세요. 
  
### <a name="clients-supported-by-exchange-online-archiving"></a>Exchange Online Archiving에서 지원하는 클라이언트

아래 표에는 Exchange Online Archiving에서 지원하는 클라이언트가 나와 있습니다.
  
|**클라이언트**|**EOA 지원**|
|:-----|:-----|
|Outlook 2010 이상  <br/> |Exchange Online Archiving의 최신 기능 지원<sup>1</sup> <br/> |
|Outlook 2007  <br/> |Exchange Online Archiving과 함께 사용할 수 있도록 지원<sup>1,2</sup> <br/> |
|Outlook 2003  <br/> |지원되지 않음  <br/> |
|Outlook for Mac 2011  <br/> |지원되지 않음  <br/> |
|Outlook for Mac  <br/> |Exchange Online 보관에 사용할 수 있도록 지원 됩니다. <sup>3</sup> <br/> |
|Microsoft Office Entourage 2008 Web Services Edition  <br/> |지원되지 않음  <br/> |
|IMAP 및 POP  <br/> |지원되지 않음  <br/> |
|Exchange ActiveSync(모바일 장치)  <br/> |지원되지 않음  <br/> |
   
> [!NOTE]
> <sup>1</sup> Microsoft Office Standard에 포함된 Outlook은 지원되지 않습니다. 자세한 내용은 [개인 보관함 및 보존 정책에 대한 라이선스 요구 사항](https://go.microsoft.com/fwlink/?LinkId=389396)을 참조하세요. > <sup>2</sup> 보관을 지원하도록 설정하려면 업데이트가 필요합니다. Outlook 2007 사용자는 보관 사서함에 있는 항목에 대한 보존 또는 보관 정책을 보거나 적용할 수 없고, 관리자가 프로비저닝한 정책을 사용해야 합니다. 또한 Outlook 2007 사용자는 온-프레미스 사서함과 보관 사서함을 동시에 검색할 수 없습니다. > <sup>3</sup> 다른 outlook 버전을 사용 하 여 이전에 항목을 이동한 적이 있는 경우에는 Mac 용 outlook 2016 또는 Mac 용 outlook을 사용 하 여 폴더, 일정 항목, 연락처, 작업 또는 메모를 보관 사서함으로 이동 하거나 복사할 수 있습니다. Outlook 2016 for Windows) 자세한 내용은 [Mac 용 Outlook 2016에서 온라인 보관 함 사용](https://support.office.com/en-us/article/Use-your-online-archive-with-Outlook-2016-for-Mac-45b8439c-2982-4b6b-9097-eed71dbfe238)을 참조 하세요. 
  
## <a name="outlook-web-app"></a>Outlook Web App

Outlook Web App은 Exchange Online과 함께 사용되는 웹 기반 버전의 Outlook 전자 메일 프로그램입니다. 사용자는 인터넷에 연결하는 위치(집, 사무실, 외부)에 관계없이 어디서나 Outlook Web App을 통해 전자 메일에 액세스할 수 있습니다.
  
사용자는 온-프레미스에서 같은 URL을 사용하여 Outlook Web App에 로그인해 보관 사서함에 액세스할 수 있습니다. 보관 사서함은 Outlook Web App에서 기본 사서함 옆에 표시됩니다. Outlook Web App에서 보관 사서함에 직접 액세스하는 명시적인 방법은 없습니다.
  
## <a name="feature-availability"></a>기능 가용성

Office 365 계획, 독립 실행형 옵션 및 온-프레미스 솔루션별로 기능 가용성을 확인하려면 [Exchange Online Archiving 서비스 설명](exchange-online-archiving-service-description.md)을 참조하세요.
  

