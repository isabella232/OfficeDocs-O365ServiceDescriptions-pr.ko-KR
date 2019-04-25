---
title: 사용자 계정 관리
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-user-account-management
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: e7616079-5b13-4f1c-99ed-b20174e0808d
description: Microsoft Office 365에서는 사용자 만들기, 관리 및 인증을 위해 다음과 같은 방법을 지원 합니다.
ms.openlocfilehash: 76a47ba99c9b163c98b7370407d3390c20235ed5
ms.sourcegitcommit: 830694c729ab53fcc8518b0cdd5322b322514431
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/25/2019
ms.locfileid: "33247204"
---
# <a name="user-account-management"></a>사용자 계정 관리

Microsoft Office 365에서는 사용자 만들기, 관리 및 인증을 위해 다음과 같은 방법을 지원 합니다. 
  
> [!NOTE]
> 이 주제에는 각 Office 365 리소스(예: Microsoft Exchange Online의 역할 기반 액세스 제어 또는 Microsoft SharePoint Online의 보안 구성)에 대한 액세스를 허용 또는 금지하는 보안 기능에 대한 정보가 포함되어 있지 않습니다. 이러한 기능과 관련된 자세한 내용은 [Exchange Online 서비스 설명](../exchange-online-service-description/exchange-online-service-description.md) 및 [SharePoint Online 서비스 설명](../sharepoint-online-service-description/sharepoint-online-service-description.md)을 참조하세요. 
  
관리 작업을 수행하는 데 도움이 되는 도구에 대한 자세한 내용은 [Office 365 계정 관리 도구](https://go.microsoft.com/fwlink/?linkid=847777)를 참조하세요. 일 단위 관리 작업을 수행하는 방법은 [Office 365의 일반적인 관리 작업](https://go.microsoft.com/fwlink/?linkid=847778)을 참조하세요.
  
## <a name="need-help-signing-in-installing-or-uninstalling-or-canceling-your-subscription"></a>로그인, 설치 또는 제거, 구독 취소에 대해 도움이 필요한가요?

[Office 365에 로그인](http://go.microsoft.com/fwlink/?LinkID=529144&amp;clcid=0x409) | [Office 설치 또는 제거](http://go.microsoft.com/fwlink/?LinkID=827202&amp;clcid=0x409) | [Office 365 취소](https://support.office.com/en-us/article/Cancel-Office-365-for-business-b1bc0bef-4608-4601-813a-cdd9f746709a)에 대한 도움말 보기
  
Office 365에 대해 다른 문제가 있는 경우 [Microsoft 지원 센터](https://go.microsoft.com/fwlink/?LinkID=808783)를 방문하세요. 중국의 21Vianet에서 운영하는 Office 365에 대한 지원을 받으려면 [21Vianet 지원팀](https://support.office.com/en-US/article/Get-technical-billing-and-subscription-support-for-Office-365-operated-by-21Vianet-671FB12E-F5D8-4CDF-B3E9-E8068A9AA496)에 문의하세요. Office 365 Germany에 대해서는 [Office 365 Germany 지원팀](https://support.office.com/en-us/article/Get-technical-and-billing-support-for-Office-365-Germany-83ef2266-2543-48d7-a41a-1b56b403a8e9?ui=en-US&amp;rs=en-US&amp;ad=US&amp;fromAR=1)에 문의하세요. 
  
## <a name="sign-in-options"></a>로그인 옵션

Office 365에는 사용자 ID에 사용할 수 있는 시스템이 2개 있습니다.
  
- **회사 또는 학교 계정(클라우드 ID)** 사용자는 Office 365 및 기타 Microsoft 클라우드 서비스에 로그인하기 위해 다른 데스크톱 또는 회사 자격 증명과는 별도로 Azure Active Directory 클라우드 자격 증명을 받습니다. 이것은 기본 ID로, 배포 복잡성을 최소화하는 데 권장됩니다. 회사 또는 학교용 암호는 Azure Active Directory [암호 정책](http://go.microsoft.com/fwlink/?LinkID=730689&amp;clcid=0x409)을 사용합니다.
    
- **페더레이션 계정(페더레이션 ID)** 모든 구독에 SSO(Single Sign-On)를 사용하는 온-프레미스 Active Directory가 있는 조직에서는 사용자가 Active Directory 자격 증명을 사용하여 Office 365 서비스에 로그인할 수 있습니다. 기업 Active Directory는 암호 정책을 저장하고 제어합니다. SSO에 대한 자세한 내용은 [Single Sign-On 로드맵](https://go.microsoft.com/fwlink/p/?LinkID=270015)을 참조하세요.
    
ID 유형은 사용자 환경 및 사용자 계정 관리 옵션을 비롯해 하드웨어 및 소프트웨어 요구 사항과 기타 배포에 관한 고려 사항에 영향을 줍니다.
  
### <a name="custom-domains-and-identity-options"></a>사용자 지정 도메인 및 ID 옵션

새 사용자를 만들 때 사용자의 로그인 이름과 전자 메일 주소는 Microsoft 365 관리 센터에 설정 된 대로 기본 도메인에 할당 됩니다. 자세한 내용은 [Office 365에 사용자 및 도메인 추가](https://support.office.com/en-us/article/Add-your-users-and-domain-to-Office-365-6383f56d-3d09-4dcb-9b41-b5f5a5efd611)를 참조하세요. 
  
기본적으로 Office 365 구독은 계정과 함께 만들어진 \< _company name_\> **.onmicrosoft.com** 도메인을 사용합니다.\* onmicrosoft.com 도메인을 유지하지 않고 Office 365 에 하나 이상의 사용자 지정 도메인을 추가할 수 있으며, 사용자를 확인된 도메인 중 어디에서나 로그인할 수 있도록 할당할 수 있습니다. 각 사용자의 할당된 도메인은 보내고 받은 전자 메일 메시지에 표시되는 전자 메일 주소입니다. 
  
Office 365에서는 각각 다른 네임스페이스로 표시되는 등록된 인터넷 도메인을 900개까지 호스트할 수 있습니다. 
  
single sign-on을 사용 하는 조직의 경우 도메인의 모든 사용자가 동일한 id 시스템 (클라우드 id 또는 페더레이션 id)을 사용 해야 합니다. 예를 들어 온-프레미스 시스템에 액세스 하지 않고 Office 365 및 온-프레미스 시스템을 사용 하는 다른 사용자 그룹에만 클라우드 id만 필요한 경우에는 한 명의 사용자 그룹을 사용할 수 있습니다. contractors.contoso.com 및 staff.contoso.com와 같은 두 개의 도메인을 Office 365에 추가 하 고이 중 하나에 대해서만 SSO를 설정 하는 것이 좋습니다. 전체 도메인을 클라우드 id에서 페더레이션 id로 또는 페더레이션 id에서 클라우드 id로 변환할 수 있습니다.
  
Office 365의 도메인에 대한 자세한 내용은 [도메인](domains.md) 서비스 설명을 참조하십시오. 
  
\* 중국의 21Vianet에서 운영되는 Office 365를 사용하는 경우 기본 도메인은 \<companyname\> **.onmsChina.cn**입니다. Office 365 Germany를 사용하는 경우 기본 도메인은 \<companyname\> **.onmicrosoft.de**입니다.
  
## <a name="authentication"></a>인증

SharePoint Online으로 만들어진 익명 액세스에 대한 인터넷 사이트의 경우를 제외하고, 사용자는 Office 365 서비스에 액세스할 때 반드시 인증 절차를 거쳐야 합니다. 
  
- **최신 인증** 최신 인증은 여러 플랫폼의 Office 클라이언트 앱에 대해 ADAL(Active Directory 인증 라이브러리) 기반 로그인을 제공합니다. 이를 통해 MFA(다단계 인증), Office 클라이언트 응용 프로그램이 있는 SAML 기반 타사 ID 공급자, 스마트 카드 및 인증서 기반 인증과 같은 로그인 기능을 사용할 수 있습니다. 또한 Microsoft Outlook이 없어도 기본 인증 프로토콜을 사용할 수 있습니다. Office 응용 프로그램의 최신 인증 가용성을 비롯한 자세한 내용은 [최신 인증이 Office 2013 및 Office 2016 클라이언트 앱에 작동하는 방식](http://go.microsoft.com/fwlink/?LinkID=717892&amp;clcid=0x409) 및 [Office 클라이언트에서 Office 365 최신 인증 사용](http://go.microsoft.com/fwlink/?LinkID=717893&amp;clcid=0x409)을 참조하세요.
    
    Exchange Online의 경우 기본적으로 최신 인증이 사용되도록 설정되어 있지 않습니다. 최신 인증을 사용하도록 설정하는 방법에 대한 자세한 내용은 [Exchange Online에서 최신 인증 사용](http://go.microsoft.com/fwlink/?LinkID=717894&amp;clcid=0x409)을 참조하세요.
    
- **클라우드 ID 인증** 클라우드 ID를 가진 사용자는 기존의 시도/응답을 통한 인증 과정을 거칩니다. 웹 브라우저는 Office 365 로그인 서비스로 리디렉션되며, 여기서 회사 또는 학교 계정에 대한 사용자 이름과 암호를 입력합니다. 로그인 서비스는 자격 증명을 인증하고 웹 브라우저가 요청된 서비스를 게시하고 사용자를 로그인하는 서비스 토큰을 생성합니다. 
    
- **페더레이션 ID 인증** 페더레이션 ID를 가진 사용자는 AD FS(Active Directory Federation Services) 2.0 또는 기타 보안 토큰 서비스를 통한 인증 절차를 거칩니다. 웹 브라우저는 Office 365 로그인 서비스로 리디렉션되며, 여기서 isabel@contoso.com과 같이 UPN(사용자 계정 이름) 형식으로 된 기업 ID를 입력합니다. 로그인 서비스는 페더레이션 도메인의 일부인지를 결정하고 인증을 위한 온-프레미스 페더레이션 서버로 리디렉션합니다. 도메인에 가입된 데스크톱에 로그인한 경우, Kerberos 또는 NTLMv2를 통한 인증 절차를 거치며 온-프레미스 보안 토큰 서비스는 웹 브라우저가 Office 365 로그인 서비스에 게시하는 로그온 토큰을 생성합니다. 로그인 서비스는 로그온 토큰을 사용하여 웹 브라우저가 요청된 서비스를 게시하고 사용자를 로그인하는 서비스 토큰을 생성합니다. 사용 가능한 보안 토큰 서비스의 목록은 [Single Sign-On 로드맵](https://go.microsoft.com/fwlink/p/?LinkID=270015)을 참조하세요.
    
Office 365는 양식 기반 인증을 사용하며, 네트워크의 인증 트래픽은 443 포트를 사용하여 항상 TLS/SSL로 암호화됩니다. 인증 트래픽은 Office 365 서비스를 위해 대역폭 중 미미한 비율만 사용합니다. 
  
### <a name="multi-factor-authentication-for-office-365"></a>Office 365에 대한 다단계 인증

Office 365에 대한 다단계 인증을 사용하는 경우 올바른 암호를 입력한 후 스마트폰으로 전화 통화를 하거나 문자 메시지 또는 앱 알림을 확인해야 합니다. 이 두 번째 인증 과정을 거쳐야만 로그인 할 수 있습니다. Office 365 관리자는 Microsoft 365 관리 센터에서 사용자를 다단계 인증을 위해 등록할 수 있습니다. 자세한 내용은 [Office 365에 대한 다단계 인증 사용](https://go.microsoft.com/fwlink/p/?LinkId=392429)을 참조하세요.
  
### <a name="rich-client-authentication"></a>리치 클라이언트 인증

Microsoft Office 데스크톱 응용 프로그램과 같은 리치 클라이언트의 경우, 2가지 방법으로 인증이 수행됩니다.
  
- **Microsoft Online Services 로그인 도우미** Office 365 데스크톱 설치가 설치한 로그인 도우미에는 Office 365 로그인 서비스에서 서비스 토큰을 받아 리치 클라이언트에게 반환하는 클라이언트 서비스가 포함되어 있습니다. 
    
  - 클라우드 ID를 가지고 있을 경우, WS-Trust를 사용한 인증을 위해 클라이언트 서비스가 Office 365 로그인 서비스에 보내는 자격 증명을 입력하라는 메시지가 표시됩니다.
    
  - 페더레이션 ID를 가지고 있을 경우, 클라이언트 서비스는 먼저 AD FS 2.0 서버와 연락하여 Kerberos 또는 NTLMv2을 사용하는 자격 증명을 인증하고, WS-Federation 및 WS-Trust를 사용하는 Office 365 로그인 서비스로 보낸 로그온 토큰을 받습니다.
    
- **SSL을 통한 기본/프록시 인증** Outlook 클라이언트에서는 SSL을 통해 기본 인증 자격 증명을 Exchange Online으로 전달합니다. Exchange Online에서는 인증 요청을 Office 365 ID 플랫폼에 프록시 처리한 다음 SSO용 온-프레미스 Active Directory 페더레이션 서버에 프록시 처리합니다. 
    
Office 365 서비스의 올바른 인증과 검색을 보장하려면 관리자는 반드시 Microsoft Office 2010 등의 리치 클라이언트를 사용하는 각각의 워크스테이션에 일련의 구성 요소를 적용하고 워크스테이션을 업데이트해야 하며 Office 365에 연결해야 합니다. Office 365 데스크톱 설정은 자동 도구로 필요한 업데이트로 워크스테이션을 자동으로 업데이트합니다. 자세한 내용은 [Office 365와 함께 내 현재 Office 데스크톱 앱 사용](https://go.microsoft.com/fwlink/p/?LinkID=270049)을 참조하세요.
  
### <a name="sign-in-experience"></a>로그인 환경

사용하는 Office 365 ID 유형에 따라 로그인 환경이 변경됩니다.
  
||**클라우드 ID**|**페더레이션 ID**|
|:-----|:-----|:-----|
|Outlook 2016  <br/> |각 세션에 로그인 <sup>1</sup> <br/> |각 세션에 로그인 <sup>2</sup> <br/> |
|Outlook 2013  <br/> |각 세션에 로그인 <sup>1</sup> <br/> |각 세션에 로그인 <sup>2</sup> <br/> |
|Windows 7의 Outlook 2010 또는 Office 2007  <br/> |각 세션에 로그인 <sup>1</sup> <br/> |각 세션에 로그인 <sup>2</sup> <br/> |
|Windows Vista의 Outlook 2010 또는 Office Outlook 2007  <br/> |각 세션에 로그인 <sup>1</sup> <br/> |각 세션에 로그인 <sup>2</sup> <br/> |
|Microsoft Exchange ActiveSync  <br/> |각 세션에 로그인 <sup>1</sup> <br/> |각 세션에 로그인 <sup>2</sup> <br/> |
|POP, IMAP, Outlook for Mac  <br/> |각 세션에 로그인 <sup>1</sup> <br/> |각 세션에 로그인 <sup>2</sup> <br/> |
|웹 환경: Office 365 포털/Outlook Web App/SharePoint Online/Office Online  <br/> |각 브라우저 세션에 로그인<sup>4</sup> <br/> |각 세션에 로그인 <sup>3</sup> <br/> |
|SharePoint Online을 사용한 Office 2010 또는 Office 2007  <br/> |각 SharePoint Online 세션에 로그인 <sup>4</sup> <br/> |각 SharePoint Online 세션에 로그인<sup>3</sup> <br/> |
|비즈니스용 Skype 온라인  <br/> |각 세션에 로그인 <sup>1</sup> <br/> |표시되지 않음  <br/> |
|Outlook for Mac  <br/> |각 세션에 로그인 <sup>1</sup> <br/> |각 세션에 로그인 <sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> 처음 표시될 때 나중에 사용할 수 있도록 암호를 저장할 수 있습니다. 암호를 변경할 때까지 다시 암호를 물어보지 않습니다. > <sup>2</sup> 기업 자격 증명을 입력합니다. 암호를 저장하면 암호를 변경할 때까지 다시 물어보지 않습니다. > <sup>3</sup> 모든 응용 프로그램을 사용하려면 사용자 이름을 입력하거나 로그인을 클릭해야 합니다. 도메인에 가입된 컴퓨터일 경우 암호를 물어보지 않습니다. **로그인 유지**를 클릭하면 로그아웃할 때까지 다시 물어보지 않습니다. > <sup>4</sup> **로그인 유지**를 클릭하면 로그아웃할 때까지 다시 물어보지 않습니다. 
  
## <a name="creating-user-accounts"></a>사용자 계정 만들기

여러 가지 방법으로 Office 365에 사용자를 추가할 수 있습니다. 자세한 내용은 [사용자를 개별적으로 또는 대량으로 Office 365-admin 도움말을 추가](https://go.microsoft.com/fwlink/p/?linkid=860006) 하 고 [Microsoft 365 관리 센터 미리 보기에서 사용자 추가, 제거 및 관리](http://go.microsoft.com/fwlink/?LinkID=624101&amp;clcid=0x409)를 참조 하세요. 중국의 21Vianet에서 운영하는 Office 365를 사용하는 경우 [21Vianet에서 운영하는 Office 365에서 사용자 계정 만들기 또는 편집 - 관리자 도움말](http://go.microsoft.com/fwlink/?LinkID=730724&amp;clcid=0x409)을 참조하세요.
  
## <a name="deleting-accounts"></a>계정 삭제

계정 삭제 방법은 디렉터리 동기화의 사용 여부에 따라 달라집니다. 
  
- 디렉터리 동기화를 사용하지 않을 경우 Office 365 관리 페이지 또는 Windows PowerShell을 통해 계정을 삭제할 수 있습니다.
    
- 디렉터리 동기화를 사용할 경우에는 반드시 Office 365가 아닌 로컬 Active Directory에서 사용자를 삭제해야 합니다.
    
계정은 삭제 후 비활성화됩니다. 삭제 후 약 30일이 지나면 계정을 복원할 수 있습니다. 계정 삭제 및 복원에 대한 자세한 내용은 [Office 365에서 사용자 삭제 또는 복원](https://go.microsoft.com/fwlink/p/?LinkID=270053)을 참조하고, 중국의 21Vianet에서 운영하는 Office 365를 사용하는 경우 [21Vianet에서 운영하는 Office 365에서 사용자 계정 만들기 또는 편집 - 관리자 도움말](http://go.microsoft.com/fwlink/?LinkID=730724&amp;clcid=0x409)을 참조하세요.
  
## <a name="password-management"></a>암호 관리

암호 관리에 대한 정책 및 절차는 ID 시스템에 따라 다릅니다.
  
 **클라우드 ID 암호 관리:**
  
클라우드 ID를 사용할 경우 계정을 만들면 암호가 자동으로 생성됩니다.
  
- 클라우드 ID 암호 보안 강도 요구 사항에 대한 자세한 내용은 [암호 정책](http://go.microsoft.com/fwlink/?LinkID=730689&amp;clcid=0x409)을 참조하세요.
    
- 보안을 강화하려면 사용자는 처음 Office 365 서비스에 액세스했을 때 암호를 변경해야 합니다. 따라서 사용자는 Office 365 서비스에 액세스하기 전에 Office 365 포털에 로그인하여 암호를 변경해야 합니다.
    
- 관리자가 암호 만료 정책을 설정할 수 있습니다. 자세한 내용은 [사용자의 암호 만료 정책 설정을](https://go.microsoft.com/fwlink/p/?LinkID=285381)참조 하십시오.
    
클라우드 ID와 함께 사용자 암호를 다시 설정할 수 있는 다양한 도구는 다음과 같습니다.
  
- **관리자가 암호 다시 설정** 사용자가 암호를 분실하거나 기억하지 못하는 경우 관리자가 Office 365 포털 또는 Windows PowerShell을 통해 사용자 암호를 다시 설정할 수 있습니다. 사용자가 기존 암호를 아는 경우에만 암호를 변경할 수 있습니다. 
    
    엔터프라이즈 요금제의 경우 관리자가 암호를 분실 하거나 잊은 경우 전역 관리자 역할이 있는 다른 관리자가 Microsoft 365 관리 센터에서 또는 Windows PowerShell을 사용 하 여 관리자의 암호를 다시 설정할 수 있습니다. 자세한 내용은 [관리자 암호 다시 설정](https://go.microsoft.com/fwlink/p/?LinkID=270062)을 참조하세요. 중국의 21Vianet에서 운영하는 Office 365를 사용하는 경우 [21Vianet에서 운영하는 Office 365에서 암호 변경 또는 재설정](http://go.microsoft.com/fwlink/?LinkID=730731&amp;clcid=0x409)을 참조하세요.
    
- **사용자가 Outlook Web App을 사용하여 암호 변경**Outlook Web App 옵션 페이지에는 사용자를 **암호 변경** 페이지로 리디렉션하는 암호 변경 하이퍼링크가 포함되어 있습니다. 사용자가 이전 암호를 알고 있어야 합니다. 자세한 내용은 [암호 변경](https://go.microsoft.com/fwlink/p/?LinkID=270063)을 참조하세요. 중국의 21Vianet에서 운영하는 Office 365를 사용하는 경우 [21Vianet에서 운영하는 Office 365에서 암호 변경 또는 재설정](http://go.microsoft.com/fwlink/?LinkID=730731&amp;clcid=0x409)을 참조하세요.
    
- **역할 기반 암호 다시 설정 권한** Enterprise 계획의 경우 기술 지원팀 직원과 같은 권한 있는 사용자에게는 완전한 서비스 관리자가 될 필요 없이 **암호 다시 설정** 사용자 권한 및 Office 365 사전 정의된 역할 또는 사용자 지정 역할을 통한 암호 변경 권한을 할당할 수 있습니다. 기본적으로 Enterprise 계획에서는 전역 관리자, 암호 관리자 또는 사용자 관리 관리자 역할을 가진 사용자가 암호를 변경할 수 있습니다. 자세한 내용은 [관리 역할 지정](https://go.microsoft.com/fwlink/p/?LinkID=270061)을 참조하세요.
    
- **Windows PowerShell을 사용한 암호 다시 설정** 서비스 관리자는 Windows PowerShell을 사용하며 암호를 재설정할 수 있습니다. 
    
 **페더레이션 ID 암호 관리:**
  
페더레이션 ID를 사용할 경우 암호는 Active Directory에서 관리됩니다. 온-프레미스 보안 토큰 서비스는 사용자의 로컬 Active Directory 암호를 인터넷을 통해 Office 365에 전달하지 않고 Office 365 Federation Gateway에 인증을 시도합니다. 로컬 암호 정책이 사용되거나 웹 클라이언트의 경우에는 2단계 식별이 사용됩니다. Outlook Web App에는 암호 변경 하이퍼링크가 포함되지 않습니다. 사용자는 표준 온-프레미스 도구 또는 데스크톱 PC 로그온 옵션을 통해 암호를 변경할 수 있습니다.
  
Office 365 환경에서 [SSO(Single Sign-On)를 사용한 디렉터리 동기화](https://go.microsoft.com/fwlink/p/?LinkId=509831)가 사용되도록 설정되어 있고 페더레이션 ID 공급자에 영향을 주는 중단 상황이 발생하면 페더레이션 로그인을 위한 암호 동기화 백업은 수동으로 도메인을 암호 동기화로 전환하기 위한 옵션을 제공합니다. 암호 동기화를 사용하면 중단 상황이 해결되는 동안에도 사용자가 Office 365에 액세스할 수 있습니다. [SSO(Single Sign-On)에서 암호 동기화로 전환하는 방법](https://go.microsoft.com/fwlink/p/?LinkId=509832)을 알아보세요.
  
## <a name="license-management"></a>라이선스 관리

Office 365 라이선스는 Office 365 서비스 집합에 대한 액세스 권한을 부여합니다. 관리자는 사용자가 액세스해야 하는 각 서비스에 대한 라이선스를 각 사용자에게 할당합니다. 예를 들어 비즈니스용 Skype 온라인에 대한 액세스 권한은 할당할 수 있지만 SharePoint Online에 대한 액세스 권한은 할당할 수 없습니다.
  
Office 365 대금 청구 관리자는 사용자 라이선스의 수 및 회사에서 사용하는 추가 서비스의 수와 같은 구독 세부 정보를 변경할 수 있습니다. 자세한 내용은 [Office 365에서 라이선스 할당 또는 제거](https://go.microsoft.com/fwlink/p/?LinkID=270069)를 참조하세요. 21Vianet에서 운영하는 Office 365를 사용하는 경우 [21Vianet에서 운영하는 Office 365에서 라이선스 할당 또는 제거](http://go.microsoft.com/fwlink/?LinkID=730747&amp;clcid=0x409)를 참조하세요.
  
## <a name="group-management"></a>그룹 관리

SharePoint Online에서는 사이트 액세스 제어를 위해 보안 그룹을 사용합니다. 보안 그룹은 Microsoft 365 관리 센터에서 만들 수 있습니다. 보안 그룹에 대한 자세한 내용은 [보안 그룹 만들기, 편집 또는 삭제](http://go.microsoft.com/fwlink/?LinkID=733611&amp;clcid=0x409)를 참조하세요.
  
## <a name="administrator-roles"></a>관리자 역할

Office 365 Enterprise는 RBAC (역할 기반 액세스 제어) 모델을 따르고 관리 역할에 의해 사용 권한 및 기능이 정의 됩니다. 조직에 대해 Office 365에 등록 하는 사람은 자동으로 전역 관리자 또는 최상위 관리자가 됩니다. 관리자 역할에는 전역 관리자, 청구 관리자, 암호 관리자, 서비스 관리자 및 사용자 관리 관리자의 다섯 가지가 있습니다. Office 365 Enterprise의 관리자 역할에 대 한 자세한 내용은 Exchange Online, SharePoint online 및 비즈니스용 Skype online 관리에 적용 되는 방법을 비롯 하 여 [관리자 역할 할당](https://go.microsoft.com/fwlink/p/?LinkID=282732)을 참조 하세요. 중국에서 21vianet에서 운영 하는 Office 365을 사용 하는 경우에는 [office 365의 비즈니스용 관리자 역할 할당](https://go.microsoft.com/fwlink/p/?linkid=270061)을 참조 하세요.
  
## <a name="delegated-administration-and-support-for-partners"></a>위임된 관리 및 파트너에 대한 지원

파트너는 고객을 대신하여 계정을 관리할 수 있는 권한을 받을 수 있습니다. 고객에게는 파트너 사용을 위한 사용자 계정이 필요하지 않으며, 관리 권한의 위임을 허용할 때 Office 365 라이선스를 사용하지 않습니다. 파트너는 조직 내 사용자에게 전체 또는 제한된 액세스를 할당할 수 있습니다. 제한된 액세스에는 암호 다시 설정, 서비스 요청 관리 및 서비스 상태 모니터링을 수행할 수 있는 권한이 포함됩니다. 
  
> [!NOTE]
> 파트너를 사용하고 위임된 관리자로 지정하는 기능은 지역별로 다릅니다. 
  
## <a name="azure-active-directory-services"></a>Azure Active Directory 서비스

Azure AD(Active Directory)는 Office 365에 포괄적인 ID 및 액세스 관리 기능을 제공합니다. 또한 디렉터리 서비스, 고급 ID 거버넌스, 응용 프로그램 액세스 관리 및 개발자를 위한 풍부한 표준 기반 플랫을 결합합니다. Office 365의 AD 기능에 대한 자세한 내용은 [로그인 페이지 브랜딩 및 클라우드 사용자 셀프 서비스 암호 재설정](https://blogs.office.com/2015/02/17/sign-page-branding-cloud-user-self-service-password-reset-office-365/)을 참조하세요. [Azure Active Directory Free, Basic 및 Premium 버전](https://msdn.microsoft.com/en-us/library/azure/dn532272.aspx)에 대해 자세히 알아보세요. 
  
## <a name="feature-availability"></a>기능 가용성

Office 365 계획, 독립 실행형 옵션 및 온-프레미스 솔루션 간의 기능 가용성을 확인하려면 [Office 365 플랫폼 서비스 설명](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx)을 참조하세요.
  
