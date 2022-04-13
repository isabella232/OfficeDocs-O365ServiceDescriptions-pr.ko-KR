---
title: User account management
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-user-account-management
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: e7616079-5b13-4f1c-99ed-b20174e0808d
description: Microsoft는 사용자를 만들고, 관리하고, 인증하는 다음 방법을 지원합니다.
ms.openlocfilehash: 914b88ba0e4d003d2df2bda362a8169f41029c01
ms.sourcegitcommit: 4b02d2d928d24a68ff7b0e1c4c5a1bde056ef69c
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/13/2022
ms.locfileid: "64819803"
---
# <a name="user-account-management"></a>User account management

Microsoft는 사용자를 만들고, 관리하고, 인증하는 다음 방법을 지원합니다. 
  
> [!NOTE]
> 이 항목에는 개별 Microsoft 리소스에 대한 액세스를 허용하거나 금지하는 보안 기능에 대한 정보가 포함되어 있지 않습니다(예: Microsoft Exchange Online 역할 기반 액세스 제어 또는 Microsoft Office SharePoint Online 보안 구성). 이러한 기능에 대한 자세한 내용은 [Exchange Online 서비스 설명](../exchange-online-service-description/exchange-online-service-description.md) 및 [SharePoint Online 서비스 설명을 참조하세요](../sharepoint-online-service-description/sharepoint-online-service-description.md). 
  
관리 작업을 수행하는 데 도움이 되는 도구에 대한 정보가 필요한 경우 [Microsoft 계정을 관리하는 도구를 참조하세요](/office365/enterprise/manage-office-365-accounts). 일상적인 관리 작업을 수행하는 방법을 알아보려면 [일반적인 관리 작업을 참조하세요](/office365/admin/manage/manage).
  
## <a name="need-help-with-signing-in-installing-or-uninstalling-or-canceling-your-subscription"></a>구독 로그인, 설치 또는 제거 또는 취소에 대한 도움이 필요하세요?

도움말 보기: [로그인 또는](https://support.office.com/article/where-to-sign-in-to-office-365-for-business-e9eb7d51-5430-4929-91ab-6157c5a050b4) |  제거 [Office](https://support.office.com/article/download-and-install-or-reinstall-office-365-or-office-2019-on-a-pc-or-mac-4414eaaf-0478-48be-9c42-23adc4716658) |  [Canceling Office 365](https://support.office.com/article/Cancel-Office-365-for-business-b1bc0bef-4608-4601-813a-cdd9f746709a)
  
기타 문제는 [Microsoft 지원 센터를](https://support.microsoft.com/contactus/) 방문하세요. 중국의 21Vianet에서 운영하는 Office 365에 대한 지원을 받으려면 [21Vianet 지원팀](https://support.office.com/article/Get-technical-billing-and-subscription-support-for-Office-365-operated-by-21Vianet-671FB12E-F5D8-4CDF-B3E9-E8068A9AA496)에 문의하세요.
  
## <a name="sign-in-options"></a>로그인 옵션

Microsoft에는 사용자 ID에 사용할 수 있는 두 가지 시스템이 있습니다.
  
- **회사 또는 학교 계정(클라우드 ID)** - 사용자는 Microsoft 클라우드 서비스에 로그인하기 위해 다른 데스크톱 또는 회사 자격 증명과는 별도로 Azure Active Directory 클라우드 자격 증명을 받습니다. 이것은 기본 ID로, 배포 복잡성을 최소화하는 데 권장됩니다. 회사 또는 학교용 암호는 Azure Active Directory [암호 정책](/previous-versions/azure/jj943764(v=azure.100))을 사용합니다.
    
- **페더레이션 계정(페더레이션 ID)** - SSO(Single Sign-On)를 사용하는 온-프레미스 Active Directory 있는 조직의 모든 구독의 경우 사용자는 Active Directory 자격 증명을 사용하여 Microsoft 서비스 로그인할 수 있습니다. 기업 Active Directory는 암호 정책을 저장하고 제어합니다. SSO에 대한 자세한 내용은 [Single Sign-On 로드맵](/previous-versions/azure/azure-services/hh967643(v=azure.100))을 참조하세요.
    
ID 유형은 사용자 환경 및 사용자 계정 관리 옵션을 비롯해 하드웨어 및 소프트웨어 요구 사항과 기타 배포에 관한 고려 사항에 영향을 줍니다.
  
### <a name="custom-domains-and-identity-options"></a>사용자 지정 도메인 및 ID 옵션

새 사용자를 만들면 Microsoft 365 관리 센터 설정된 대로 사용자의 로그인 이름 및 전자 메일 주소가 기본 도메인에 할당됩니다. 자세한 내용은 [사용자 및 도메인 추가를 참조하세요](https://support.office.com/article/Add-your-users-and-domain-to-Office-365-6383f56d-3d09-4dcb-9b41-b5f5a5efd611). 
  
기본적으로 구독은 계정으로 만든 <*회사* **name.onmicrosoft.com**> 도메인을 사용합니다. 중국의 21Vianet에서 운영하는 Office 365 사용하는 경우 기본 도메인은 *companyname.onmsChina.cn*> <. **onmicrosoft.com** 도메인을 유지하는 대신 하나 이상의 사용자 지정 도메인을 Microsoft에 추가할 수 있으며 유효성이 검사된 도메인으로 로그인하도록 사용자를 할당할 수 있습니다. 각 사용자의 할당된 도메인은 보내고 받은 전자 메일 메시지에 표시되는 전자 메일 주소입니다.
  
각각 다른 네임스페이스로 표시되는 등록된 인터넷 도메인을 최대 900개까지 호스트할 수 있습니다. 
  
Single Sign-On을 사용하는 조직의 경우 도메인의 모든 사용자가 동일한 ID 시스템(클라우드 ID 또는 페더레이션 ID)을 사용해야 합니다. 예를 들어 온-프레미스 시스템에 액세스하지 않기 때문에 클라우드 ID만 필요한 사용자 그룹과 Microsoft 및 온-프레미스 시스템을 사용하는 다른 사용자 그룹이 있을 수 있습니다. contractors.contoso.com 및 staff.contoso.com 같은 두 개의 도메인을 **Office 365** 추가하고 그 중 하나에 대해서만 SSO를 설정합니다. 전체 도메인을 클라우드 ID에서 페더레이션 ID로 변환하거나 페더레이션 ID에서 클라우드 ID로 변환할 수 있습니다.
  
Office 365의 도메인에 대한 자세한 내용은 [도메인](domains.md) 서비스 설명을 참조하십시오. 
  
## <a name="authentication"></a>인증

SharePoint Online을 사용하여 만든 익명 액세스를 위한 인터넷 사이트를 제외하고 Microsoft 서비스 액세스할 때 사용자를 인증해야 합니다. 
  
- **최신 인증** - 최신 인증은 플랫폼 간에 클라이언트 앱을 Office Microsoft 인증 라이브러리 기반 로그인을 제공합니다. 이를 통해 MFA(다단계 인증), Office 클라이언트 응용 프로그램이 있는 SAML 기반 타사 ID 공급자, 스마트 카드 및 인증서 기반 인증과 같은 로그인 기능을 사용할 수 있습니다. 또한 Microsoft Outlook이 없어도 기본 인증 프로토콜을 사용할 수 있습니다. Office 애플리케이션에서 최신 인증의 가용성을 포함한 자세한 내용은 [Office 2013 및 Office 2016 클라이언트 앱에서 최신 인증이 작동하는 방식을 참조하세요](/office365/enterprise/modern-auth-for-office-2013-and-2016).
    
    최신 인증은 Exchange Online 대해 기본적으로 켜져 있습니다. 켜거나 끄는 방법을 알아보려면 [Exchange Online 최신 인증 사용을](/exchange/clients-and-mobile-in-exchange-online/enable-or-disable-modern-authentication-in-exchange-online) 참조하세요.
    
- **클라우드 ID 인증** - 클라우드 ID를 가진 사용자는 기존의 과제/응답을 사용하여 인증됩니다. 웹 브라우저는 회사 또는 학교 계정의 사용자 이름 및 암호를 입력하는 Microsoft 로그인 서비스로 리디렉션됩니다. 로그인 서비스는 자격 증명을 인증하고 웹 브라우저가 요청된 서비스를 게시하고 사용자를 로그인하는 서비스 토큰을 생성합니다. 
    
- **페더레이션 ID 인증** - 페더레이션 ID를 가진 사용자는 Active Directory Federation Services(AD FS) 2.0 또는 기타 보안 토큰 서비스를 사용하여 인증됩니다. 웹 브라우저는 Microsoft 로그인 서비스로 리디렉션됩니다. 여기서 UPN(사용자 계정 이름) 형식으로 회사 ID를 입력합니다(예: *isabel@contoso.com*). 로그인 서비스는 페더레이션 도메인의 일부인지를 결정하고 인증을 위한 온-프레미스 페더레이션 서버로 리디렉션합니다. 데스크톱(도메인 가입)에 로그온한 경우 인증되고(Kerberos 또는 NTLMv2 사용) 온-프레미스 보안 토큰 서비스는 웹 브라우저가 Microsoft 로그인 서비스에 게시하는 로그온 토큰을 생성합니다. 로그인 서비스는 로그온 토큰을 사용하여 웹 브라우저가 요청된 서비스를 게시하고 사용자를 로그인하는 서비스 토큰을 생성합니다. 사용 가능한 보안 토큰 서비스의 목록은 [Single Sign-On 로드맵](/previous-versions/azure/azure-services/hh967643(v=azure.100))을 참조하세요.
    
Microsoft는 양식 기반 인증을 사용하며 네트워크를 통한 인증 트래픽은 항상 포트 443을 사용하여 TLS/SSL로 암호화됩니다. 인증 트래픽은 Microsoft 서비스 대해 무시할 수 있는 대역폭 비율을 사용합니다. 
  
### <a name="multi-factor-authentication"></a>다단계 인증

Multi-Factor Authentication을 사용하면 사용자가 암호를 올바르게 입력한 후 스마트폰에서 전화 통화, 문자 메시지 또는 앱 알림을 승인해야 합니다. 이 두 번째 인증 과정을 거쳐야만 로그인 할 수 있습니다. Microsoft 관리자는 Microsoft 365 관리 센터 다단계 인증을 위해 사용자를 등록할 수 있습니다. [Multi-Factor Authentication](/office365/admin/security-and-compliance/set-up-multi-factor-authentication)에 대해 자세히 알아봅니다.
  
### <a name="rich-client-authentication"></a>리치 클라이언트 인증

Microsoft Office 데스크톱 응용 프로그램과 같은 리치 클라이언트의 경우, 2가지 방법으로 인증이 수행됩니다.
  
- **Microsoft Online Services Sign-In Assistant** - 데스크톱 설치 프로그램에서 설치되는 로그인 도우미에는 로그인 서비스에서 서비스 토큰을 가져와 리치 클라이언트로 반환하는 클라이언트 서비스가 포함되어 있습니다. 
    
  - 클라우드 ID가 있는 경우 인증을 위해 클라이언트 서비스가 로그인 서비스(WS-Trust 사용)로 보내는 자격 증명에 대한 프롬프트가 표시됩니다.
    
  - 페더레이션 ID가 있는 경우 클라이언트 서비스는 먼저 AD FS 2.0 서버에 연결하여 자격 증명(Kerberos 또는 NTLMv2 사용)을 인증하고 로그인 서비스(WS-Federation 및 WS-Trust 사용)로 전송되는 로그온 토큰을 가져옵니다.
    
- **SSL을 통한 기본/프록시 인증** - Outlook 클라이언트는 SSL을 통해 기본 인증 자격 증명을 Exchange Online 전달합니다. Exchange Online 인증 요청을 ID 플랫폼에 프록시한 다음, 페더레이션 서버(SSO용)온-프레미스 Active Directory. 
    
Microsoft 서비스 적절한 검색 및 인증을 보장하려면 관리자는 풍부한 클라이언트(예: Microsoft Office 2010)를 사용하고 Office 365 연결하는 각 워크스테이션에 구성 요소 및 업데이트 집합을 적용해야 합니다. 데스크톱 설정은 필요한 업데이트로 워크스테이션을 구성하는 자동화된 도구입니다. 자세한 내용은 [현재 Office 데스크톱 앱 사용을 참조하세요](https://support.office.com/article/3324b8b8-dceb-45e2-ac24-c642720108f7).
  
### <a name="sign-in-experience"></a>로그인 환경

로그인 환경은 사용 중인 ID 유형에 따라 변경됩니다.<br><br>
  
| 서비스 | 클라우드 ID | 페더레이션 ID |
|:-----|:-----|:-----|
|Outlook 2016  <br/> |각 세션에 로그인 <sup>1</sup> <br/> |각 세션에 로그인 <sup>2</sup> <br/> |
|Outlook 2013  <br/> |각 세션에 로그인 <sup>1</sup> <br/> |각 세션에 로그인 <sup>2</sup> <br/> |
|Windows 7의 Outlook 2010 또는 Office 2007  <br/> |각 세션에 로그인 <sup>1</sup> <br/> |각 세션에 로그인 <sup>2</sup> <br/> |
|Windows Vista의 Outlook 2010 또는 Office Outlook 2007  <br/> |각 세션에 로그인 <sup>1</sup> <br/> |각 세션에 로그인 <sup>2</sup> <br/> |
|Microsoft Exchange ActiveSync  <br/> |각 세션에 로그인 <sup>1</sup> <br/> |각 세션에 로그인 <sup>2</sup> <br/> |
|POP, IMAP, Outlook for Mac  <br/> |각 세션에 로그인 <sup>1</sup> <br/> |각 세션에 로그인 <sup>2</sup> <br/> |
|웹 환경: Microsoft 365 관리 센터/웹용 Outlook/SharePoint Online/웹용 Office  <br/> |각 브라우저 세션에 로그인<sup>4</sup> <br/> |각 세션에 로그인 <sup>3</sup> <br/> |
|SharePoint Online을 사용한 Office 2010 또는 Office 2007  <br/> |각 SharePoint Online 세션에 로그인 <sup>4</sup> <br/> |각 SharePoint Online 세션에 로그인<sup>3</sup> <br/> |
|비즈니스용 Skype 온라인  <br/> |각 세션에 로그인 <sup>1</sup> <br/> |표시되지 않음  <br/> |
|Outlook for Mac  <br/> |각 세션에 로그인 <sup>1</sup> <br/> |각 세션에 로그인 <sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> 처음 메시지가 표시되면 나중에 사용하기 위해 암호를 저장할 수 있습니다. 암호를 변경할 때까지 다른 프롬프트가 표시되지 않습니다. <br/> 
<sup>2</sup> 회사 자격 증명을 입력합니다. 암호를 저장할 수 있으며 암호가 변경될 때까지 다시 메시지가 표시되지 않습니다. <br/> 
<sup>3</sup> 모든 앱을 사용하려면 로그인할 사용자 이름을 입력하거나 선택해야 합니다. 컴퓨터가 도메인에 가입되어 있는 경우 암호를 묻는 메시지가 표시되지 않습니다. **로그인 유지** 를 선택하면 로그아웃할 때까지 다시 메시지가 표시되지 않습니다. <br/> 
<sup>4</sup> **로그인 유지** 를 선택하면 로그아웃할 때까지 다시 메시지가 표시되지 않습니다. 
  
## <a name="create-user-accounts"></a>Create user accounts

사용자를 추가하는 방법에는 여러 가지가 있습니다. 자세한 내용은 [개별적으로 또는 대량으로 사용자 추가 - 관리자 도움말](/office365/admin/add-users/add-users) 및 [Microsoft 365 관리 센터 미리 보기에서 사용자 추가, 제거 및 관리를](https://support.office.com/article/6e80db58-c36b-4add-b1c8-cc5135f111f3) 참조하세요. 중국의 21Vianet에서 운영하는 Office 365를 사용하는 경우 [21Vianet에서 운영하는 Office 365에서 사용자 계정 만들기 또는 편집 - 관리자 도움말](/office365/admin/add-users/add-users)을 참조하세요.
  
## <a name="delete-user-accounts"></a>사용자 계정 삭제

계정 삭제 방법은 디렉터리 동기화의 사용 여부에 따라 달라집니다. 
  
- 디렉터리 동기화를 사용하지 않는 경우 관리자 페이지를 사용하거나 Windows PowerShell 사용하여 계정을 삭제할 수 있습니다.
    
- 디렉터리 동기화를 사용할 경우에는 반드시 Office 365가 아닌 로컬 Active Directory에서 사용자를 삭제해야 합니다.
    
계정은 삭제 후 비활성화됩니다. 삭제 후 약 30일이 지나면 계정을 복원할 수 있습니다. 계정 삭제 및 복원에 대한 자세한 내용은 [사용자 삭제](/office365/admin/add-users/delete-a-user) 및 [사용자 복원](/office365/admin/add-users/restore-user)을 참조하거나, 중국의 21Vianet에서 운영하는 Office 365 사용하는 경우 [21Vianet - 관리자 도움말에서 운영하는 Office 365 사용자 계정 만들기 또는 편집](/office365/admin/add-users/add-users)을 참조하세요.
  
## <a name="password-management"></a>암호 관리

암호 관리에 대한 정책 및 절차는 ID 시스템에 따라 다릅니다.
  
### <a name="cloud-identity-password-management"></a>클라우드 ID 암호 관리
  
클라우드 ID를 사용할 경우 계정을 만들면 암호가 자동으로 생성됩니다.
  
- 클라우드 ID 암호 보안 강도 요구 사항에 대한 자세한 내용은 [암호 정책](/previous-versions/azure/jj943764(v=azure.100))을 참조하세요.
    
- 보안을 강화하려면 사용자가 Microsoft 서비스 처음 액세스할 때 암호를 변경해야 합니다. 따라서 사용자가 Microsoft 서비스 액세스하려면 먼저 Microsoft 365 관리 센터 로그인해야 합니다. 여기서 암호를 변경하라는 메시지가 표시됩니다.
    
- 관리자가 암호 만료 정책을 설정할 수 있습니다. 자세한 내용은 [사용자의 암호 만료 정책 설정을](/office365/admin/manage/set-password-expiration-policy) 참조하세요.
    
클라우드 ID와 함께 사용자 암호를 다시 설정할 수 있는 다양한 도구는 다음과 같습니다.
  
- **관리자는 암호를 재설정합니다**. 사용자가 암호를 분실하거나 잊어버린 경우 관리자는 관리 센터에서 또는 Windows PowerShell 사용하여 사용자의 암호를 재설정할 수 있습니다. 사용자가 기존 암호를 아는 경우에만 암호를 변경할 수 있습니다. 
    
    엔터프라이즈 계획의 경우 관리자가 암호를 분실하거나 잊어버린 경우 전역 관리자 역할이 있는 다른 관리자는 Microsoft 365 관리 센터 또는 Windows PowerShell 사용하여 관리자의 암호를 재설정할 수 있습니다. 자세한 내용은 [관리자 암호 다시 설정](/office365/admin/add-users/reset-passwords)을 참조하세요. 중국의 21Vianet에서 운영하는 Office 365를 사용하는 경우 [21Vianet에서 운영하는 Office 365에서 암호 변경 또는 재설정](https://support.office.com/article/change-or-reset-your-password-in-office-365-operated-by-21vianet-d8eb5b62-9d0e-4267-a9bf-2aa491ee6d0b)을 참조하세요.
    
- **사용자가 웹용 Outlook 사용하여 암호를 변경합니다**. 웹용 Outlook 옵션 페이지에는 암호 변경 페이지로 사용자를 리디렉션하는 암호 **변경** 하이퍼링크가 포함되어 있습니다. 사용자가 이전 암호를 알고 있어야 합니다. 자세한 내용은 [암호 변경](https://support.office.com/article/change-password-in-outlook-web-app-50bb1309-6f53-4c24-8bfd-ed24ca9e872c)을 참조하세요. 중국의 21Vianet에서 운영하는 Office 365를 사용하는 경우 [21Vianet에서 운영하는 Office 365에서 암호 변경 또는 재설정](https://support.office.com/article/change-or-reset-your-password-in-office-365-operated-by-21vianet-d8eb5b62-9d0e-4267-a9bf-2aa491ee6d0b)을 참조하세요.
    
- **역할 기반 암호 재설정 권한** - 엔터프라이즈 계획의 경우 기술 지원팀 직원과 같은 권한 있는 사용자에게 **암호 재설정** 사용자 권한 및 전체 서비스 관리자가 되지 않고 미리 정의된 또는 사용자 지정 역할을 사용하여 암호를 변경할 수 있는 권한을 할당할 수 있습니다. 기본적으로 엔터프라이즈 계획에서 전역 관리자, 암호 관리자 또는 사용자 관리 관리자 역할이 있는 관리자는 암호를 변경할 수 있습니다. 자세한 내용은 [관리 역할 지정](/office365/admin/add-users/assign-admin-roles)을 참조하세요.
    
- **Windows PowerShell 사용하여 암호 재설정** - 서비스 관리자는 Windows PowerShell 사용하여 암호를 재설정할 수 있습니다. 
    
### <a name="federated-identity-password-management"></a>페더레이션 ID 암호 관리
  
페더레이션 ID를 사용할 경우 암호는 Active Directory에서 관리됩니다. 온-프레미스 보안 토큰 서비스는 인터넷을 통해 사용자의 로컬 Active Directory 암호를 Office 365 전달하지 않고 페더레이션 게이트웨이와 인증을 협상합니다. 로컬 암호 정책이 사용되거나 웹 클라이언트의 경우에는 2단계 식별이 사용됩니다. 웹용 Outlook 암호 변경 하이퍼링크를 포함하지 않습니다. 사용자는 표준 온-프레미스 도구 또는 데스크톱 PC 로그온 옵션을 통해 암호를 변경할 수 있습니다.
  
조직 환경에서 [SSO(Single Sign-On)를 사용하도록 설정된 디렉터리 동기화](/previous-versions/azure/azure-services/dn441213(v=azure.100)) 가 있고 페더레이션 ID 공급자에 영향을 주는 중단이 있는 경우 페더레이션 로그인용 암호 동기화 백업은 도메인을 암호 동기화로 수동으로 전환하는 옵션을 제공합니다. 암호 동기화를 사용하면 중단이 해결되는 동안 사용자가 액세스할 수 있습니다. [단일 Sign-On 암호 동기화로 전환하는 방법을](https://go.microsoft.com/fwlink/p/?LinkId=509832) 알아봅니다.
  
## <a name="license-management"></a>라이선스 관리

라이선스는 사용자에게 Microsoft 서비스 집합에 대한 액세스 권한을 부여합니다. 관리자는 사용자가 액세스해야 하는 각 서비스에 대한 라이선스를 각 사용자에게 할당합니다. 예를 들어 비즈니스용 Skype 온라인에 대한 액세스 권한은 할당할 수 있지만 SharePoint Online에 대한 액세스 권한은 할당할 수 없습니다.
  
Microsoft 청구 관리자는 사용자 라이선스 수 및 회사에서 사용하는 추가 서비스 수와 같은 구독 세부 정보를 변경할 수 있습니다. [라이선스 할당 또는 제거를](/office365/admin/subscriptions-and-billing/assign-licenses-to-users) 확인하세요. 21Vianet에서 운영하는 Office 365를 사용하는 경우 [21Vianet에서 운영하는 Office 365에서 라이선스 할당 또는 제거](/office365/admin/subscriptions-and-billing/assign-licenses-to-users)를 참조하세요.
  
## <a name="group-management"></a>그룹 관리

SharePoint Online에서는 사이트 액세스 제어를 위해 보안 그룹을 사용합니다. Microsoft 365 관리 센터 보안 그룹을 만들 수 있습니다. 보안 그룹에 대한 자세한 내용은 [보안 그룹 만들기, 편집 또는 삭제](/office365/admin/email/create-edit-or-delete-a-security-group)를 참조하세요.
  
## <a name="administrator-roles"></a>관리자 역할

엔터프라이즈용 Office 365 RBAC(역할 기반 액세스 제어) 모델을 따릅니다. 권한 및 기능은 관리 역할에 의해 정의됩니다. 조직에 Office 365 등록하는 사람은 자동으로 전역 관리자 또는 최상위 관리자가 됩니다. 전역 관리자, 청구 관리자, 암호 관리자, 서비스 관리자 및 사용자 관리 관리자의 5가지 관리자 역할이 있습니다. Exchange Online, SharePoint Online 및 비즈니스용 Skype Online 관리에 적용하는 방법을 포함하여 엔터프라이즈용 Office 365 관리자 역할에 대한 자세한 내용은 [관리자 역할 할당을](/previous-versions/windows/it-pro/windows-server-2012-R2-and-2012/jj878348(v=ws.11)) 참조하세요. 중국의 21Vianet에서 운영하는 Office 365 사용하는 경우 [비즈니스용 Office 365 관리자 역할 할당을](/office365/admin/add-users/assign-admin-roles) 참조하세요.
  
## <a name="delegated-administration-and-support-for-partners"></a>위임된 관리 및 파트너에 대한 지원

파트너는 고객을 대신하여 계정을 관리할 수 있는 권한을 받을 수 있습니다. 고객은 파트너가 사용하는 사용자 계정이 필요하지 않으며 위임된 관리 권한을 부여할 때 라이선스를 사용하지 않습니다. 파트너는 조직 내 사용자에게 전체 또는 제한된 액세스를 할당할 수 있습니다. 제한된 액세스에는 암호 다시 설정, 서비스 요청 관리 및 서비스 상태 모니터링을 수행할 수 있는 권한이 포함됩니다. 
  
> [!NOTE]
> 파트너를 사용하고 위임된 관리자로 지정하는 기능은 지역별로 다릅니다. 
  
## <a name="azure-active-directory-services"></a>Azure Active Directory 서비스

Azure AD(Active Directory)는 Office 365에 포괄적인 ID 및 액세스 관리 기능을 제공합니다. 또한 디렉터리 서비스, 고급 ID 거버넌스, 응용 프로그램 액세스 관리 및 개발자를 위한 풍부한 표준 기반 플랫을 결합합니다. Office 365의 AD 기능에 대한 자세한 내용은 [로그인 페이지 브랜딩 및 클라우드 사용자 셀프 서비스 암호 재설정](https://go.microsoft.com/fwlink/?linkid=2144147)을 참조하세요. [Azure Active Directory Free, Basic 및 Premium 버전](/previous-versions/azure/dn532272(v=azure.100))에 대해 자세히 알아보세요. 
  
## <a name="feature-availability"></a>기능 가용성

계획, 독립 실행형 옵션 및 온-프레미스 솔루션에서 기능 가용성을 보려면 [Microsoft 365 및 Office 365 플랫폼 서비스 설명을](office-365-platform-service-description.md) 참조하세요.
