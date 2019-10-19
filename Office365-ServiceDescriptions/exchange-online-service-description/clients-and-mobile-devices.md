---
title: 클라이언트 및 모바일 장치
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-clients-and-mobile-devices
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: fce4ac03-f30a-4152-9145-4a9ce564c966
ms.openlocfilehash: 0b5768720514572299814dd5ecd9c3a200f1958a
ms.sourcegitcommit: 19591e97b35c1b2a99e04a496d83af27dc6530d6
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/18/2019
ms.locfileid: "37581924"
---
# <a name="clients-and-mobile-devices"></a>클라이언트 및 모바일 장치

## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook은 일정, 연락처, 작업 및 다음 주요 기능에 대 한 지원을 포함 하는 전자 메일 프로그램입니다.
  
- **HTTP를 통한 MAPI** HTTP를 통한 MAPI (메시징 응용 프로그램 인터페이스)를 사용 하면 Outlook 사용자가 조직의 방화벽 외부에서 인터넷을 통해 Exchange Online 사서함에 연결할 수 있습니다. HTTP를 통한 MAPI, 외부에서 Outlook 사용에 대 한 장기간 교체 이 연결 방법은 향상 된 연결 복구, 보다 안전한 로그인, 확장성 및 IT 및 지원에 대 한 향상을 제공 합니다. 자세한 내용은 Office 365 및 [MAPI OVER http](https://go.microsoft.com/fwlink/?linkid=393041) [에서 RPC over http 지원의 끝에 도달 하는 방법에 대](https://go.microsoft.com/fwlink/?linkid=863890) 한 자세한 내용을 참조 하세요.

- **자동 검색** 자동 검색 서비스 기능은 자동으로 Outlook을 Exchange Online과 함께 작동하도록 구성합니다. Outlook 사용자는 처음 전자 메일 주소와 암호를 통해 로그인했을 때 Exchange Online에서 바로 필요한 프로필 설정을 받을 수 있습니다. 이러한 설정은 사용자의 프로필을 만들고 유지하는 데 필요한 정보를 가지고 Outlook 클라이언트를 자동으로 업데이트합니다. 자동 검색 서비스를 사용하려면 SSL 인증서를 필요합니다. 이 SSL 인증서는 하나의 기본 SSL 도메인으로 제한됩니다. 

- **캐시 된 Exchange 모드** 캐시 된 Exchange 모드 기능을 사용 하면 Outlook 사용자가 인터넷에 연결 되어 있지 않을 때 Exchange Online 사서함의 로컬 복사본에 액세스할 수 있습니다. 캐시 된 Exchange 모드는 Outlook에서 사용자 Exchange 사서함의 클라이언트 쪽 복사본을 유지 하며이 복사본을 전자 메일 서버와 자동으로 동기화 합니다. Outlook은 캐시 된 Exchange 모드에서 오프 라인 액세스를 제공 하 고 클라이언트와 서버 간의 네트워크 조건이 적합 하지 않은 경우에도 응답성이 뛰어난 사용자 환경을 제공 하는 것이 좋습니다. 

기본적으로 Outlook 액세스는 모든 사용자에 대해 사용하도록 설정되어 있습니다. 관리자는 Windows Powershell을 통해 특정 사용자 또는 그룹의 액세스를 사용하지 않도록 설정할 수 있습니다. Exchange Online에 액세스하려면 최신 서비스 팩이 설치된 Outlook 최신 버전을 사용하는 것이 좋습니다. 
  
Exchange 2016 및 Exchange Online에서 지원되는 Outlook 클라이언트에 대한 자세한 내용은 [Exchange 2016 시스템 요구 사항](https://go.microsoft.com/fwlink/?LinkID=828972)에서 "지원되는 클라이언트"를 참조하세요.
  
> [!IMPORTANT]
>  Outlook은 Exchange Online 구독 가격에 포함되어 제공되지 않습니다. 일부 Office 365 계획에는 Microsoft Office Pro Plus(Microsoft Outlook 포함)가 포함되어 있으며, 별도의 구독을 구매할 수도 있습니다. POP를 사용 하 여 Exchange Online 전자 메일 계정에 연결 하는 경우에는 일정 정보 없이 > > 모든 메시지를 표시 하지 않습니다 > > > 전자 메일을 보낼 때 POP를 통해 연결할 수 없습니다. o 클라이언트와 여러 컴퓨터 또는 장치 간에 동기화가 제공 되지 않습니다 (예: 랩톱과 전화 간). 
  
## <a name="outlook-on-the-web"></a>웹에서 Outlook

웹상의 Outlook은 웹 기반 버전의 Outlook 전자 메일 프로그램으로 Exchange Online과 함께 사용됩니다. 이를 통해 사용자는 인터넷에 연결 된 모든 위치에서 웹 브라우저를 통해 전자 메일, 일정 및 연락처에 액세스할 수 있습니다. 지원되는 브라우저에 대한 자세한 내용은 [비즈니스용 웹상의 Outlook에 대해 지원되는 브라우저](https://support.office.com/article/Supported-browsers-for-Outlook-Web-App-c89774d6-0722-4c93-a547-ef45e693e006)를 참조하세요.
  
웹상의 Outlook에는 2가지 클라이언트 버전이 있으며, 모두 Exchange Online과 함께 사용할 수 있습니다.
  
- **웹상의 Outlook** 웹상의 Outlook 표준 버전으로 Exchange Online 사용자에게 Outlook 사용자와 가장 유사한 메시지 환경을 제공합니다. 대부분의 최신 웹 브라우저를 지원하며 데스크톱 및 랩톱 뿐만 아니라 태블릿 및 스마트폰 사용에 최적화되어 있습니다. 사용자는 메시지 읽기 및 보내기, 연락처 구성, 약속 및 모임 예약 등의 작업을 수행할 수 있습니다. 기본 작업 기반 시간 제한은 6시간으로 설정되지만 [Windows PowerShell에서 관리자가 5분에서 8시간 사이로 구성](https://go.microsoft.com/fwlink/p/?LinkId=399155)할 수 있습니다. 이 시간 제한은 단추를 선택 하거나 메시지를 선택 하는 것과 같은 웹 응용 프로그램 내의 사용자 상호 작용에 따라 달라 집니다. 또한 구성할 수 없으며 사용자 작업에 상관없이 발생하는 별도의 보안 기반 시간 제한도 있습니다. 사용자가 8시간 동안 로그인되어 있는 경우 OWA는 사용자를 자동으로 로그아웃하고 다시 인증하라는 메시지를 표시합니다. 

- **웹상의 Outlook 라이트 버전** 웹상의 Outlook 라이트 버전은 Exchange Online 사용자에게 거의 모든 웹 브라우저를 통한 사서함 액세스를 제공합니다. 사용자는 메시지 읽기 및 보내기, 연락처 구성, 약속 및 모임 예약 등의 작업을 수행할 수 있습니다. 기본 작업 기반 시간 제한은 6시간으로 설정되지만 [Windows PowerShell에서 관리자가 5분에서 8시간 사이로 구성](https://go.microsoft.com/fwlink/p/?LinkId=399155)할 수 있습니다. 이 시간 제한은 단추를 선택 하거나 메시지를 선택 하는 것과 같은 웹 응용 프로그램 내의 사용자 상호 작용에 따라 달라 집니다. 또한 구성할 수 없으며 사용자 작업에 상관없이 발생하는 별도의 보안 기반 시간 제한도 있습니다. 사용자가 8시간 동안 로그인되어 있는 경우 라이트 버전의 OWA는 사용자를 자동으로 로그아웃하고 다시 인증하라는 메시지를 표시합니다. 

웹상의 Outlook은 모바일 버전으로도 사용할 수 있습니다. 자세한 내용은 [이 페이지](http://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409)를 참조하세요.
  
## <a name="outlook-for-mac"></a>Outlook for Mac

Exchange Online은 전자 메일, 일정, 주소록, 작업 목록 및 메모 목록을 제공 하는 Mac 용 Microsoft Outlook을 지원 합니다.
  
## <a name="outlook-for-ios-android-and-windows-phone"></a>IOS, Android 및 Windows Phone 용 Outlook

Exchange Online은 iOS, Android 및 Windows Phone에 사용할 수 있는 Outlook 앱과 함께 작동 합니다. 이러한 장치에서 앱 스토어를 사용 하 여 Outlook 앱을 찾습니다. 다음은 모바일 OS에서 분석 한 사항입니다.
  
|||||
|:-----|:-----|:-----|:-----|
|디바이스  <br/> |Android  <br/> |iOS  <br/> |Windows Phone  <br/> |
|Outlook 모바일 앱 가용성  <br/> |예  <br/> [Android 용 Outlook 받기](https://go.microsoft.com/fwlink/?linkid=863380) <br/> |예  <br/> [IOS 용 Outlook 받기](https://go.microsoft.com/fwlink/?linkid=863382) <br/> |기본 제공  <br/> |
|Exchange Online과 호환 되는 기본 제공 전자 메일 앱  <br/> |Gmail 앱/Samsung Email 응용 프로그램  <br/> |iOS 메일 앱  <br/> |Outlook 메일, 일정, 연락처  <br/> |
|추가 정보  <br/> |[Android 모바일 설정](https://go.microsoft.com/fwlink/?linkid=525632) <br/> |[iPhone 또는 iPad 설치](https://go.microsoft.com/fwlink/?linkid=396655) <br/> |[Windows Phone 설정](https://go.microsoft.com/fwlink/?linkid=831342) <br/> |

또한 Blackberry를 포함 하 여 Exchange Online과 장치를 함께 사용 하기 위한 옵션도 있습니다.
  
### <a name="feature-availability"></a>기능 가용성

Outlook에서는 최신 모바일 앱에서 기대할 수 있는 빠르고 직관적인 전자 메일 및 일정 환경을 제공 하며, Office 365의 최상의 기능을 지원 하기 위한 유일한 앱입니다. 이 전자 메일 응용 프로그램은 전체 Office 365 환경을 지원 하도록 특별히 설계 된 것으로, 데스크톱에서 모바일으로 사용자에 게 일관 된 환경을 제공 합니다. Outlook은 Intune, enterprise mobility and security 및 Exchange 컨트롤을 사용 하 여 데이터와 사용자를 안전 하 게 유지 합니다.
  
Outlook에서는 사용자가 다음 작업을 수행할 수 있습니다.
  
- 모바일 장치에서 전체 날짜를 관리 합니다.

- 업무와 개인 정보를 별도로 유지 하 고 보호 하면서도 생산성을 높이는 데 필요한 앱 및 서비스에 연결 합니다.

IOS, Android 용 Outlook 또는 Windows Phone 용 outlook을 사용 하 여 사용자는 다음을 수행할 수 있습니다. 
  
- 중요 받은 편지함의 우선 순위를 지정 하는 혜택

- 고유한 전자 메일 습관과 일치 하도록 살짝 밀기 제스처 사용자 지정

- 주요 정보를 한눈에 볼 수 있도록 일정에 직접 추가할 수 있는 여행 일정 만들기

- 받은 편지함의 모임에 RSVP를 배달 합니다.

- 전자 메일 및 일정 약속의 직관적인 아이콘을 사용 하 여 정보를 빠르게 처리할 수 있도록 합니다.

- 모든 장치에서 일관 되 고 익숙한 Outlook 환경 사용

- 일정에서 Skype 모임을 간편 하 게 시작 및 참가

- IRM 암호화 및 보호 된 전자 메일 읽기 및 응답

- 비즈니스용 OneDrive에 저장 된 파일 공유

- 탭을 사용 하 여 자동 회신 설정

- 공유 및 위임 된 일정 보기 및 관리

- 회사의 전체 주소 목록에서 몇 번의 탭으로 검색

- 동료의 가용성 보기 및 모든 사용자에 대해 작동 하는 모임 시간 예약

- 초대 대 상자 수락, 미정 및 거절 상태 보기

- 휴대폰에서 바로 일정 공유

- 일정에서 바로 Skype 모임 시작 및 참가

- 앱을 전환 하지 않고 한 곳에서 작업 및 개인 일정에 액세스
    
## <a name="exchange-activesync"></a>Exchange ActiveSync

Exchange Online은 모바일 장치와 Exchange Online 간에 사서함 데이터를 동기화하는 Microsoft Exchange ActiveSync 프로토콜을 지원합니다. 따라서 사용자는 자신의 전자 메일, 연락처 및 작업을 이동 중에도 액세스할 수 있습니다.
  
Exchange ActiveSync는 Microsoft Windows Phone, Apple iPhone 및 iPad, Android 휴대폰 및 태블릿 등을 비롯한 매우 다양한 유형의 모바일 장치에서 작동합니다. 휴대폰 및 장치 외에도 Windows Phone의 메일 응용 프로그램은 Exchange ActiveSync를 사용 하 여 Exchange Online에 연결 합니다. 현재 Exchange ActiveSync 라이선스 실시권자 전체 목록은 Exchange ActiveSync 라이선싱 사이트에서 확인할 수 있습니다.
  
Exchange ActiveSync에 대 한 자세한 내용은 [Exchange activesync](https://go.microsoft.com/fwlink/p/?LinkId=271792)를 참조 하십시오.
  
> [!IMPORTANT]
> 사서함당 Exchange ActiveSync 장치 수는 최대 100개입니다. 
  
## <a name="applications-developed-with-exchange-web-services-ews"></a>Exchange 웹 서비스(EWS)로 개발된 응용 프로그램

 EWS(Exchange 웹 서비스) 또는 EWS Managed API로 개발된 응용 프로그램을 사용하여 관리자는 온-프레미스, Azure 또는 기타 호스트된 서비스에서 실행되는 응용 프로그램에서 Exchange Online에 저장된 데이터에 액세스할 수 있습니다. 
  
Exchange 웹 서비스로 개발된 응용 프로그램에 대한 자세한 내용은 [Exchange의 웹 서비스](https://go.microsoft.com/fwlink/?LinkId=325346)를 참조하세요.
  
## <a name="pop-and-imap"></a>POP 및 IMAP

Exchange Online은 POP3 및 IMAP4 프로토콜을 통해 사서함 액세스를 지원합니다. POP 및 IMAP 액세스에는 SSL를 사용한 암호화가 필요합니다. POP는 기본적으로 모든 사용자에 대해 사용하도록 설정되어 있습니다. 사용자는 자신의 POP 및 IMAP 연결 설정을 웹상의 Outlook에서 볼 수 있습니다. 관리자는 POP 및 IMAP 액세스를 각 사용자별로 사용하지 않도록 설정할 수 있습니다.
  
POP3 및 IMAP4 연결에 대한 자세한 내용은 [POP3 및 IMAP4](https://go.microsoft.com/fwlink/p/?LinkId=272070)를 참조하세요.
  
## <a name="smtp"></a>SMTP

SMTP(Simple Mail Transfer Protocol)은 IMAP 또는 POP를 통해 Exchange Online에 연결하는 클라이언트의 아웃바운드 메일을 보내는 데 사용됩니다. Exchange Server를 통한 배달 및 라우팅의 기본 프로토콜입니다. Exchange Online은 SMTP 메일 전송에 필요한 승인된 내부 고객 응용 프로그램에 대해 2가지 유형의 SMTP 릴레이 서비스를 지원합니다.
  
- 관리 환경 내부 사용자에 대한 SMTP 메시지 전송.

- 관리 환경 외부의 주소에 대한 인증된 SMTP 메시지 릴레이.

> [!IMPORTANT]
> SMTP 릴레이를 허용하려면 승인된 원본 서버에 대한 IP 주소가 필요합니다. SMTP를 사용해 전자 메일을 보낼 때는 전송 계층 보안(TLS) 암호화 및 인증이 필요합니다. 
  
## <a name="blackberry-devices"></a>BlackBerry® 장치

Office 365 전자 메일은 Exchange ActiveSync를 통해 BlackBerry® 장치에서 사용할 수 있습니다. 옵션에 대 한 자세한 내용은 다음 항목을 참조 하십시오.
  
- [BlackBerry 장치에서 전자 메일 설정](https://go.microsoft.com/fwlink/?linkid=863394)

- [BlackBerry 장치에서 전자 메일 설정 7.1 OS 및 이전 버전](https://go.microsoft.com/fwlink/?linkid=863403)

자세한 내용은 [BlackBerry](../office-365-platform-service-description/blackberry.md)를 참고하세요.
  
> [!NOTE]
> 중국의 21Vianet에서 운영하는 Office 365를 사용하는 경우 BlackBerry Business Cloud Services를 사용할 수 없지만 Exchange ActiveSync 장치 또는 RIM(Research in Motion, BlackBerry 무선 전자 메일 솔루션)의 기능을 사용하여 BES(Blackberry Enterprise Server)를 실행할 수 있습니다. 
  
## <a name="feature-availability"></a>기능 가용성

Office 365 계획, 독립 실행형 옵션 및 온-프레미스 솔루션 별로 기능 가용성을 확인 하려면 [Exchange Online 서비스 설명을](exchange-online-service-description.md)참조 하세요.
  