---
title: Exchange Online 보관의 클라이언트 기능
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
description: Microsoft Exchange Online 보관을 통해 사용자는 다양 한 장치 및 플랫폼에서 보관 사서함에 연결할 수 있습니다. 사용자의 보관 사서함에 대 한 모든 네트워크 연결은 인터넷을 통해 수행 되며 VPN (가상 사설망) 연결은 필요 하지 않습니다. 조직은 사용자가 VPN 연결을 사용하지 않고도 외부에서 Outlook 사용 를 통해 기본 사서함에 액세스할 수 있도록 온-프레미스 클라이언트 액세스 서버를 게시할 수 있습니다. 온-프레미스 서버에 있는 사용자의 기본 사서함에 액세스하기 위해 VPN 액세스가 필요한 경우에도 이 요구 사항은 변경되지 않습니다.
ms.openlocfilehash: b460938b4ce9e0aeb2c0eb4ab99fe7f3fa8a8ea4
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132062"
---
# <a name="client-features-in-exchange-online-archiving"></a>Exchange Online 보관의 클라이언트 기능

Microsoft Exchange Online 보관을 통해 사용자는 다양 한 장치 및 플랫폼에서 보관 사서함에 연결할 수 있습니다. 사용자의 보관 사서함에 대 한 모든 네트워크 연결은 인터넷을 통해 수행 되며 VPN (가상 사설망) 연결은 필요 하지 않습니다. 조직은 사용자가 VPN 연결을 사용하지 않고도 외부에서 Outlook 사용 를 통해 기본 사서함에 액세스할 수 있도록 온-프레미스 클라이언트 액세스 서버를 게시할 수 있습니다. 온-프레미스 서버에 있는 사용자의 기본 사서함에 액세스하기 위해 VPN 액세스가 필요한 경우에도 이 요구 사항은 변경되지 않습니다.
  
> [!IMPORTANT]
> Microsoft는 Exchange Online Archiving 서비스 상태를 악화시키는 모든 클라이언트 소프트웨어로부터의 연결을 차단하거나 제한할 수 있는 권한을 보유합니다.
  
## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook is a rich email program that includes support for calendaring, contacts, and tasks. Exchange Online Archiving supports Outlook 2013, Outlook 2010, and Outlook 2007. Key features include:
  
- **외부에서 Outlook** 사용 Outlook Anywhere를 사용 하면 Outlook 사용자가 VPN 연결을 사용 하지 않아도 인터넷을 통해 Exchange 서버 및 Exchange Online 보관에 연결할 수 있습니다. Outlook과 Exchange Online Archiving 간의 통신은 RPC-over-HTTP Windows 네트워킹 구성 요소를 사용하여 SSL 보안 터널을 통해 수행됩니다.    
- **자동 검색** Exchange 자동 검색 서비스는 Exchange Online 보관용으로 작동 하도록 Outlook을 구성 합니다. 자동 검색을 사용 하면 Outlook 사용자가 전자 메일 주소 및 암호를 사용 하 여 로그인 하는 처음으로 Exchange에서 직접 필요한 프로필 설정을 받을 수 있습니다. 

Outlook 2010 이상 및 웹용 Outlook에서는 보존 및 보관 정책과 같은 관련 기능 뿐 아니라 보관 함의 모든 기능을 사용자에 게 제공 합니다.
  
Outlook 2007 provides basic support for the archive, but not all archiving and compliance features are available in Outlook 2007. For example, with Outlook 2007, users cannot apply retention or archive policies to items in their mailboxes. They must rely on administrator-provisioned policies instead. Outlook 2007 users require the Office 2007 Cumulative Update for February 2011 to access the archive.
  
> [!NOTE]
> Exchange Online Archiving에서는 Outlook이 제공되지 않습니다. Microsoft 365 for enterprise (Microsoft Outlook 포함)는 일부 계획에 포함 되어 있으며 별도의 구독으로 구매할 수 있습니다. 자세한 내용은 [Microsoft 365 계획 옵션](../office-365-platform-service-description/office-365-plan-options.md)을 참조 하세요. Microsoft 365 for enterprise 용 앱에 대 한 자세한 내용은 [Office 응용 프로그램 서비스 설명을](../office-applications-service-description/office-applications-service-description.md)참조 하세요. 
  
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
|Exchange ActiveSync (모바일 장치)  <br/> |지원되지 않음  <br/> |
   
> [!NOTE]
> <sup>1</sup> Microsoft Office Standard에 포함된 Outlook은 지원되지 않습니다. 자세한 내용은 [개인 보관함 및 보존 정책에 대한 라이선스 요구 사항](https://support.office.com/article/Outlook-license-requirements-for-Exchange-features-46B6B7C5-C3CA-43E5-8424-1E2807917C99)을 참조하세요. <br/> 
<sup>2</sup> 보관을 지원하도록 설정하려면 업데이트가 필요합니다. Outlook 2007 사용자는 보관 사서함에 있는 항목에 대한 보존 또는 보관 정책을 보거나 적용할 수 없고, 관리자가 프로비저닝한 정책을 사용해야 합니다. 또한 Outlook 2007 사용자는 온-프레미스 사서함과 보관 사서함을 동시에 검색할 수 없습니다. <br/> 
<sup>3</sup> outlook 2016 for Windows와 같은 다른 outlook 버전을 사용 하 여 이전에 항목을 이동한 적이 있는 경우에는 Mac 용 outlook 2016 또는 Mac 용 outlook을 사용 하 여 폴더, 일정 항목, 연락처, 작업 또는 메모를 보관 사서함으로 이동 하거나 복사할 수 있습니다. 자세한 내용은 [Mac 용 Outlook 2016에서 온라인 보관 함 사용](https://support.office.com/article/Use-your-online-archive-with-Outlook-2016-for-Mac-45b8439c-2982-4b6b-9097-eed71dbfe238)을 참조 하세요. 

## <a name="outlook-on-the-web"></a>웹에서 Outlook

웹상의 Outlook은 웹 기반 버전의 Outlook 전자 메일 프로그램으로 Exchange Online과 함께 사용됩니다. 사용자가 집, 사무실 또는 이동 시에 인터넷에 연결 되어 있는 경우에는 어디 &mdash; 에서 나 &mdash; 웹에서 Outlook을 통해 전자 메일에 액세스할 수 있습니다.
  
사용자는 온-프레미스에 웹에서 Outlook에 로그인 하 여 해당 보관 사서함에 액세스할 수 있습니다 (동일한 URL 사용). 보관은 웹에서 Outlook의 기본 사서함 옆에 표시 됩니다. 웹에서 Outlook을 통해 보관 사서함에 직접 액세스 하는 명시적인 방법은 없습니다.
  
## <a name="feature-availability"></a>기능 가용성

계획, 독립 실행형 옵션 및 온-프레미스 솔루션 별로 기능 가용성을 확인 하려면 [Exchange Online 보관 서비스 설명을](exchange-online-archiving-service-description.md)참조 하세요.