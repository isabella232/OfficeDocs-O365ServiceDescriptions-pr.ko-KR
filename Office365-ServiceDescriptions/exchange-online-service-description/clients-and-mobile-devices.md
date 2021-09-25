---
title: 클라이언트 및 모바일 장치
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-clients-and-mobile-devices
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
ms.assetid: fce4ac03-f30a-4152-9145-4a9ce564c966
description: Exchange Online 데스크톱 및 모바일 버전의 Outlook 사용할 수 있으며, 웹용 Outlook.
ms.openlocfilehash: 97d25b505afcdc4effb145b28eda5aab1275ce81
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/24/2021
ms.locfileid: "59672088"
---
# <a name="clients-and-mobile-devices"></a>클라이언트 및 모바일 장치

## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook 일정, 연락처, 작업 및 다음과 같은 주요 기능에 대한 지원이 포함된 전자 메일 프로그램입니다.
  
- **HTTP를** 사용하는 MAPI - HTTP를 통해 MAPI(Messaging Application Program Interface)를 사용하면 Outlook 방화벽 외부에서 인터넷을 통해 Exchange Online 사서함에 연결할 수 있습니다. HTTP를 통해 MAPI, "anywhere"를 Outlook 대체합니다. 이 연결 방법은 향상된 연결 탄력성, 더 안전한 로그인, 확장성 및 IT 및 지원에 대한 향상된 기능을 제공합니다. 자세한 내용은 [RPC over HTTP 에서](/exchange/troubleshoot/administration/rpc-over-http-end-of-support) 지원 종료에 도달한 Office 365 [HTTP를 통해 MAPI를 참조합니다.](/exchange/mapi-over-http-exchange-2013-help)

- **Autodiscover** - 자동 Outlook 기능에서 작동하도록 자동으로 Exchange Online. Outlook 사용자는 처음 전자 메일 주소와 암호를 통해 로그인했을 때 Exchange Online에서 바로 필요한 프로필 설정을 받을 수 있습니다. 이러한 설정은 사용자의 프로필을 만들고 유지하는 데 필요한 정보를 가지고 Outlook 클라이언트를 자동으로 업데이트합니다. 자동 검색 서비스를 사용하려면 SSL 인증서를 필요합니다. 이 SSL 인증서는 하나의 기본 SSL 도메인으로 제한됩니다. 

- **캐시된** Exchange 모드 - 캐시된 Exchange 모드 기능을 사용하면 Outlook 인터넷에 연결되지 않은 Exchange Online 사서함의 로컬 복사본에 액세스할 수 있습니다. 캐시된 Exchange 모드는 사용자의 Exchange 사서함의 클라이언트 쪽 복사본을 Outlook 이 복사본을 전자 메일 서버와 자동으로 동기화합니다. 캐시된 Outlook 모드로 Exchange 클라이언트와 서버 간의 네트워크 조건이 이상적이지 않은 경우에도 오프라인 액세스를 제공하고 응답성 있는 사용자 환경을 제공하는 데 도움이 되어 캐시된 Exchange 모드에서 사용하는 것이 좋습니다. 

기본적으로 Outlook 액세스는 모든 사용자에 대해 사용하도록 설정되어 있습니다. 관리자는 Windows Powershell을 통해 특정 사용자 또는 그룹의 액세스를 사용하지 않도록 설정할 수 있습니다. Exchange Online에 액세스하려면 최신 서비스 팩이 설치된 Outlook 최신 버전을 사용하는 것이 좋습니다. 
  
Outlook 2016 및 Exchange 클라이언트에서 지원하는 Exchange Online 클라이언트에 대한 자세한 내용은 [System Requirements for Office.](https://products.office.com/office-system-requirements) 

Microsoft 365 최신 브라우저 및 버전의 웹 사이트와 함께 작동하도록 Office. 기본 지원에 없는 이전 브라우저 및 Office 버전을 사용하는 경우:

- Microsoft는 사용자가 서비스에 연결하지 못하게 고의적으로 차단하지 않지만 시간이 지날 때 환경의 품질이 희미해질 수 있습니다.
- Microsoft는 비보안 관련 문제를 해결하기 위한 소프트웨어 업데이트를 제공하지 않습니다.

> [!IMPORTANT]
> Outlook은 Exchange Online 구독 가격에 포함되어 제공되지 않습니다. 엔터프라이즈용 Microsoft 365 앱(Microsoft Outlook 포함)는 일부 요금제에 포함되어 있으며 별도의 구독으로 구매할 수 있습니다. POP을 사용해서 Exchange Online 전자 메일 계정에 연결하면 다음 제한 사항이 표시됩니다.
> - 일정 정보 없음
>- 약속 있음/없음 정보 없음
>- 전체 주소 목록 없음
>- 전자 메일 푸시 없음
>- POP를 통해 연결하면 모든 메시지가 클라이언트로 다운로드되며, 여러 컴퓨터 또는 장치 간에 동기화가 수행되지 않습니다(예: 랩톱과 전화 간). 
  
## <a name="outlook-on-the-web"></a>웹에서 Outlook

웹상의 Outlook은 웹 기반 버전의 Outlook 전자 메일 프로그램으로 Exchange Online과 함께 사용됩니다. 사용자는 인터넷에 연결하는 모든 곳에서 웹 브라우저를 통해 전자 메일, 일정 및 연락처에 액세스할 수 있습니다. 지원되는 브라우저에 대한 자세한 내용은 [비즈니스용 웹상의 Outlook에 대해 지원되는 브라우저](https://support.office.com/article/Supported-browsers-for-Outlook-Web-App-c89774d6-0722-4c93-a547-ef45e693e006)를 참조하세요.
  
웹상의 Outlook에는 2가지 클라이언트 버전이 있으며, 모두 Exchange Online과 함께 사용할 수 있습니다.
  
- **웹용 Outlook** - 표준 버전의 웹용 Outlook Exchange Online 사용자와 가장 유사한 메시징 환경을 Outlook 제공합니다. 대부분의 최신 웹 브라우저를 지원하며 데스크톱 및 랩톱 뿐만 아니라 태블릿 및 스마트폰 사용에 최적화되어 있습니다. 사용자는 메시지 읽기 및 보내기, 연락처 구성, 약속 및 모임 예약 등의 작업을 수행할 수 있습니다. 기본 작업 기반 시간 제한은 6시간으로 설정되지만 [Windows PowerShell에서 관리자가 5분에서 8시간 사이로 구성](/powershell/module/exchange/set-organizationconfig)할 수 있습니다. 이 시간 아웃은 단추 선택 또는 메시지 선택과 같은 웹 앱 내의 사용자 상호 작용에 따라 달라 습니다. 또한 구성할 수 없으며 사용자 작업에 상관없이 발생하는 별도의 보안 기반 시간 제한도 있습니다. 사용자가 8시간 동안 로그인되어 있는 경우 OWA는 사용자를 자동으로 로그아웃하고 다시 인증하라는 메시지를 표시합니다. 

- **light version of 웹용 Outlook** - light version of 웹용 Outlook Exchange Online 사용자가 거의 모든 웹 브라우저를 사용하여 사서함에 액세스할 수 있도록 합니다. 사용자는 메시지 읽기 및 보내기, 연락처 구성, 약속 및 모임 예약 등의 작업을 수행할 수 있습니다. 기본 작업 기반 시간 제한은 6시간으로 설정되지만 [Windows PowerShell에서 관리자가 5분에서 8시간 사이로 구성](/powershell/module/exchange/set-organizationconfig)할 수 있습니다. 이 시간 아웃은 단추 선택 또는 메시지 선택과 같은 웹 앱 내의 사용자 상호 작용에 따라 달라 습니다. 또한 구성할 수 없으며 사용자 작업에 상관없이 발생하는 별도의 보안 기반 시간 제한도 있습니다. 사용자가 8시간 동안 로그인되어 있는 경우 라이트 버전의 OWA는 사용자를 자동으로 로그아웃하고 다시 인증하라는 메시지를 표시합니다. 

웹상의 Outlook은 모바일 버전으로도 사용할 수 있습니다. 자세한 내용은 [이 페이지](https://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409)를 참조하세요.
  
## <a name="outlook-for-mac"></a>Outlook for Mac

Exchange Online, 일정Outlook 작업 목록 및 메모 목록을 제공하는 Mac용 Microsoft Outlook 지원
  
## <a name="outlook-for-ios-android-and-windows-phone"></a>Outlook, Android 및 iOS용 Windows Phone

Exchange Online iOS, Android 및 Outlook 사용할 수 있는 앱과 함께 Windows Phone. 이러한 디바이스에서 앱 스토어를 사용하여 앱 Outlook 있습니다. 다음은 모바일 OS에 대한 분석입니다.<br><br>
  
| 디바이스 | Android | iOS | Windows Phone |
|:-----|:-----|:-----|:-----|
|Outlook 앱 가용성 확인  <br/> |예  <br/> [Android용 Outlook 다운로드](https://go.microsoft.com/fwlink/?linkid=863380) <br/> |예  <br/> [iOS용 Outlook 사용](https://go.microsoft.com/fwlink/?linkid=863382) <br/> |기본 제공  <br/> |
|사용자와 호환되는 기본 제공 전자 메일 Exchange Online  <br/> |Gmail 앱/Samsung 전자 메일 앱  <br/> |iOS 메일 앱  <br/> |Outlook 메일, 일정, 연락처  <br/> |
|추가 정보  <br/> |[Android 모바일 설정](https://go.microsoft.com/fwlink/?linkid=525632) <br/> |[iPhone 또는 iPad 설정](https://go.microsoft.com/fwlink/?linkid=396655) <br/> |[Windows Phone 설정](https://go.microsoft.com/fwlink/?linkid=831342) <br/> |

Blackberry를 포함하여 디바이스에서 Exchange Online 옵션도 있습니다.
  
### <a name="feature-availability"></a>기능 가용성

Outlook 최신 모바일 앱에서 기대하는 빠르고 직관적인 전자 메일 및 일정 환경을 제공하는 동시에 최상의 기능에 대한 지원을 제공하는 유일한 앱입니다. 전체 Microsoft 환경을 지원하도록 특별히 디자인된 유일한 전자 메일 앱으로, 사용자에게 데스크톱에서 모바일로의 일직선 환경을 제공합니다. Outlook 및 사용자를 안전하게 유지하기 위해 Intune, 엔터프라이즈 이동성 및 Exchange 제어와 통합되어 있습니다.
  
이 Outlook 사용자는 다음을 할 수 있습니다.
  
- 모바일 장치에서 하루 전체를 관리합니다.

- 커넥트 개인 정보를 분리하고 안전하게 유지하면서 생산성을 유지하는 데 필요한 앱 및 서비스에 대한 정보를 제공합니다.

iOS용 Outlook, android용 Outlook 또는 Outlook Windows Phone 수 있습니다. 
  
- 중요한 전자 메일의 우선 순위를 지정하는 중요 받은 편지함의 이점

- 고유한 전자 메일 습관에 맞게 스와이프 제스처 사용자 지정

- 주요 정보를 한눈에 볼 수 있는 일정에 직접 추가할 수 있는 여행 일정 만들기

- 받은 편지함에서 모임으로의 RSVP

- 전자 메일 및 일정 약속에 직관적인 아이콘을 사용하여 정보를 빠르게 처리

- 모든 장치에서 일관되고 친숙한 Outlook 환경 사용

- 일정에서 Skype 쉽게 시작하고 모임에 참가

- 암호화 및 보호된 IRM 전자 메일 읽기 및 응답

- 파일에 저장된 파일 비즈니스용 OneDrive

- 탭하여 자동 응답 설정

- 공유 및 위임된 일정 보기 및 관리

- 몇 번의 탭으로 회사의 전체 주소 목록 검색

- 동료의 가용성을 보고 모든 사람이 사용할 수 있는 모임 시간 예약

- 초대를 수락, 미정 및 거절 상태 확인

- 휴대폰에서 바로 일정 공유

- 일정에서 Skype 모임 시작 및 참가

- 앱을 전환하지 않고 한 장소에서 작업 및 개인 일정에 액세스
    
## <a name="exchange-activesync"></a>Exchange ActiveSync

Exchange Online은 모바일 장치와 Exchange Online 간에 사서함 데이터를 동기화하는 Microsoft Exchange ActiveSync 프로토콜을 지원합니다. 따라서 사용자는 자신의 전자 메일, 연락처 및 작업을 이동 중에도 액세스할 수 있습니다.
  
Exchange ActiveSync는 Microsoft Windows Phone, Apple iPhone 및 iPad, Android 휴대폰 및 태블릿 등을 비롯한 매우 다양한 유형의 모바일 장치에서 작동합니다. 휴대폰 및 장치 외에도 Windows Phone 메일 응용 프로그램은 Exchange ActiveSync 사용하여 Exchange Online. 현재 Exchange ActiveSync 라이선스 실시권자 전체 목록은 Exchange ActiveSync 라이선싱 사이트에서 확인할 수 있습니다.
  
자세한 내용은 Exchange ActiveSync 을 [Exchange ActiveSync.](/exchange/clients-and-mobile-in-exchange-online/clients-and-mobile-in-exchange-online)
  
> [!IMPORTANT]
> 사서함당 Exchange ActiveSync 장치 수는 최대 100개입니다. 
  
## <a name="applications-developed-with-exchange-web-services-ews"></a>Exchange 웹 서비스(EWS)로 개발된 응용 프로그램

 EWS(Exchange 웹 서비스) 또는 EWS Managed API로 개발된 응용 프로그램을 사용하여 관리자는 온-프레미스, Azure 또는 기타 호스트된 서비스에서 실행되는 응용 프로그램에서 Exchange Online에 저장된 데이터에 액세스할 수 있습니다. 
  
Exchange 웹 서비스로 개발된 응용 프로그램에 대한 자세한 내용은 [Exchange의 웹 서비스](/exchange/client-developer/exchange-web-services/explore-the-ews-managed-api-ews-and-web-services-in-exchange)를 참조하세요.
  
## <a name="pop-and-imap"></a>POP 및 IMAP

Exchange Online은 POP3 및 IMAP4 프로토콜을 통해 사서함 액세스를 지원합니다. POP 및 IMAP 액세스에는 SSL를 사용한 암호화가 필요합니다. POP는 기본적으로 모든 사용자에 대해 사용하도록 설정되어 있습니다. 사용자는 자신의 POP 및 IMAP 연결 설정을 웹상의 Outlook에서 볼 수 있습니다. 관리자는 POP 및 IMAP 액세스를 각 사용자별로 사용하지 않도록 설정할 수 있습니다.
  
POP3 및 IMAP4 연결에 대한 자세한 내용은 [POP3 및 IMAP4](/exchange/pop3-and-imap4-in-exchange-server-2013-exchange-2013-help)를 참조하세요.
  
## <a name="smtp"></a>SMTP

SMTP(Simple Mail Transfer Protocol)은 IMAP 또는 POP를 통해 Exchange Online에 연결하는 클라이언트의 아웃바운드 메일을 보내는 데 사용됩니다. Exchange Server를 통한 배달 및 라우팅의 기본 프로토콜입니다. Exchange Online은 SMTP 메일 전송에 필요한 승인된 내부 고객 응용 프로그램에 대해 2가지 유형의 SMTP 릴레이 서비스를 지원합니다.
  
- 관리 환경 내부 사용자에 대한 SMTP 메시지 전송.

- 관리 환경 외부의 주소에 대한 인증된 SMTP 메시지 릴레이.

> [!IMPORTANT]
> SMTP 릴레이를 허용하려면 승인된 원본 서버에 대한 IP 주소가 필요합니다. SMTP를 사용해 전자 메일을 보낼 때는 전송 계층 보안(TLS) 암호화 및 인증이 필요합니다. 
  
## <a name="blackberry-devices"></a>BlackBerry 장치

Email is available on BlackBerry &reg; devices via Exchange ActiveSync. 옵션에 대한 자세한 내용은 다음 항목을 참조하세요.
  
- [BlackBerry 장치에서 전자 메일 설정](https://go.microsoft.com/fwlink/?linkid=863394)

- [BlackBerry 장치 7.1 OS 이전 버전에서 전자 메일 설정](https://go.microsoft.com/fwlink/?linkid=863403)

자세한 내용은 [BlackBerry](../office-365-platform-service-description/blackberry.md)를 참고하세요.
  
> [!NOTE]
> 중국의 21Vianet에서 운영하는 Office 365를 사용하는 경우 BlackBerry Business Cloud Services를 사용할 수 없지만 Exchange ActiveSync 장치 또는 RIM(Research in Motion, BlackBerry 무선 전자 메일 솔루션)의 기능을 사용하여 BES(Blackberry Enterprise Server)를 실행할 수 있습니다. 
  
## <a name="feature-availability"></a>기능 가용성

계획, 독립 실행형 옵션 및온-프레미스 솔루션에서 기능 가용성을 확인한 경우 서비스 [Exchange Online 참조하세요.](exchange-online-service-description.md)
