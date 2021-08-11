---
title: 클라이언트의 Exchange Online Archiving
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- clients-and-devices-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c8d5f97a-607f-4949-a4f7-0b9e3b246851
description: 이 문서를 읽고 보관에서 사용할 수 있는 클라이언트 기능에 대해 Microsoft Exchange Online 있습니다.
ms.openlocfilehash: df71da18d5eb2304496bc72ac2556bb3cc325e50e49cccb14ba6b5191cc95b1d
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/06/2021
ms.locfileid: "54664671"
---
# <a name="client-features-in-exchange-online-archiving"></a>클라이언트의 Exchange Online Archiving

Microsoft Exchange Online 보관을 사용하면 다양한 장치 및 플랫폼에서 보관 사서함에 연결할 수 있습니다. 사용자의 보관에 대한 모든 네트워크 연결은 인터넷을 통해 발생하며 VPN(가상 사설망) 연결은 필요하지 않습니다. 조직은 사용자가 VPN 연결을 사용하지 않고도 외부에서 Outlook 사용 를 통해 기본 사서함에 액세스할 수 있도록 온-프레미스 클라이언트 액세스 서버를 게시할 수 있습니다. 온-프레미스 서버에 있는 사용자의 기본 사서함에 액세스하기 위해 VPN 액세스가 필요한 경우에도 이 요구 사항은 변경되지 않습니다.
  
> [!IMPORTANT]
> Microsoft는 Exchange Online Archiving 서비스 상태를 악화시키는 모든 클라이언트 소프트웨어로부터의 연결을 차단하거나 제한할 수 있는 권한을 보유합니다.
  
## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook은 일정, 연락처 및 작업을 지원하는 기능이 포함된 유용한 전자 메일 프로그램입니다. Exchange Online Archiving에서는 Outlook 2013, Outlook 2010 및 Outlook 2007을 지원합니다. 주요 기능은 다음과 같습니다.
  
- **Outlook anywhere** - Outlook Anywhere를 사용하면 Outlook VPN 연결 없이 Exchange Server Exchange Online Archiving 인터넷을 통해 연결할 수 있습니다. Outlook과 Exchange Online Archiving 간의 통신은 RPC-over-HTTP Windows 네트워킹 구성 요소를 사용하여 SSL 보안 터널을 통해 수행됩니다.    
- **자동 Exchange** - Exchange 자동 Outlook 자동으로 구성 Exchange Online Archiving합니다. 자동 검색을 Outlook 사용자가 전자 메일 주소와 암호로 Exchange 고정 간격으로 사용자가 필요한 프로필 설정을 직접 받을 수 있습니다. 

Outlook 2010 이상 웹용 Outlook 보관함의 전체 기능과 보존 및 보관 정책과 같은 관련 기능을 사용자에게 제공합니다.
  
Outlook 2007은 보관 사서함을 기본적으로 지원하지만 일부 보관 및 규정 준수 기능은 Outlook 2007에서 사용할 수 없습니다. 예를 들어 Outlook 2007에서는 사용자가 사서함의 항목에 보존 또는 보관 정책을 적용할 수 없습니다. 그 대신에 관리자가 프로비저닝한 정책을 사용해야 합니다. Outlook 2007 사용자의 경우 보관 사서함에 액세스하려면 2011년 2월 Office 2007 누적 업데이트가 필요합니다.
  
> [!NOTE]
> Exchange Online Archiving에서는 Outlook이 제공되지 않습니다. 엔터프라이즈용 Microsoft 365 앱(Microsoft Outlook 포함)는 일부 요금제에 포함되어 있으며 별도의 구독으로 구매할 수 있습니다. 자세한 내용은 Microsoft 365 [옵션을 참조하세요.](../office-365-platform-service-description/office-365-plan-options.md) 자세한 내용은 엔터프라이즈용 Microsoft 365 앱 응용 프로그램 Office [설명을 참조하세요.](../office-applications-service-description/office-applications-service-description.md) 
  
### <a name="clients-supported-by-exchange-online-archiving"></a>Exchange Online Archiving에서 지원하는 클라이언트

아래 표에는 Exchange Online Archiving에서 지원하는 클라이언트가 나와 있습니다.<br><br>
  
| 클라이언트 | EOA 지원 |
|:-----|:-----|
|Outlook 2013 이상  <br/> |Exchange Online Archiving의 최신 기능 지원<sup>1</sup> <br/> |
|Outlook 2010  <br/> |2020년 10월 13일까지만 Exchange Online Archiving 최신 기능 지원|
|Outlook 2007  <br/> |지원되지 않음 |
|Outlook 2003  <br/> |지원되지 않음  <br/> |
|Outlook for Mac 2011  <br/> |지원되지 않음  <br/> |
|Outlook for Mac  <br/> |지원되는 Exchange Online Archiving. <sup>3</sup> <br/> |
|Microsoft Office Entourage 2008 Web Services Edition  <br/> |지원되지 않음  <br/> |
|IMAP 및 POP  <br/> |지원되지 않음  <br/> |
|Exchange ActiveSync(모바일 장치)  <br/> |지원되지 않음  <br/> |
   
> [!NOTE]
> <sup>1</sup> Microsoft Office Standard에 포함된 Outlook은 지원되지 않습니다. 자세한 내용은 [개인 보관함 및 보존 정책에 대한 라이선스 요구 사항](https://support.office.com/article/Outlook-license-requirements-for-Exchange-features-46B6B7C5-C3CA-43E5-8424-1E2807917C99)을 참조하세요. <br/> 
<sup>2</sup> 보관을 지원하도록 설정하려면 업데이트가 필요합니다. Outlook 2007 사용자는 보관 사서함에 있는 항목에 대한 보존 또는 보관 정책을 보거나 적용할 수 없고, 관리자가 프로비저닝한 정책을 사용해야 합니다. 또한 Outlook 2007 사용자는 온-프레미스 사서함과 보관 사서함을 동시에 검색할 수 없습니다. <br/> 
<sup>3</sup> Mac용 Outlook 2016 이전에 다른 버전의 Outlook(예: Outlook 2016 Outlook for Windows)를 사용하여 폴더, 일정 항목, 연락처, 작업 또는 메모를 보관함으로 이동하거나 복사하거나 보관 사서함에서 볼 수 없습니다. 자세한 내용은 에서 온라인 보관함 사용을 [Mac용 Outlook 2016.](https://support.office.com/article/Use-your-online-archive-with-Outlook-2016-for-Mac-45b8439c-2982-4b6b-9097-eed71dbfe238) 

## <a name="outlook-on-the-web"></a>웹에서 Outlook

웹상의 Outlook은 웹 기반 버전의 Outlook 전자 메일 프로그램으로 Exchange Online과 함께 사용됩니다. 사용자가 집, 사무실 또는 출장 중 인터넷에 연결되어 있는 모든 사용자는 인터넷을 통해 전자 메일에 액세스할 &mdash; &mdash; 수 웹용 Outlook.
  
사용자는 동일한 URL을 사용하여 웹용 Outlook 로그인하여 보관함에 액세스할 수 있습니다. 보관 사서함이 기본 사서함과 함께 웹용 Outlook. 보관함에서 직접 보관에 액세스하는 명시적인 방법은 웹용 Outlook.
  
## <a name="feature-availability"></a>기능 가용성

계획, 독립 실행형 옵션 및온-프레미스 솔루션에 대한 기능 가용성을 확인하면 Exchange Online Archiving [설명을 참조하세요.](exchange-online-archiving-service-description.md)