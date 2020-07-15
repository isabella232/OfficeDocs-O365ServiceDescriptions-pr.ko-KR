---
title: Exchange Online 설치 및 관리
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-administration-and-management
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 80c07748-ac57-4b90-97dd-a2d1115009a6
description: 이 문서에서는 Exchange Online 설정을 사용자 지정 하 고 조직의 Exchange Online 환경을 최신, 실행 및 최신 상태로 유지 하는 데 사용할 수 있는 관리 제어 및 지원에 대해 설명 합니다. 내용에는 Microsoft 관리 책임 및 성능 약정, 서비스 및 제품 업그레이드와 같이 조직에서 사용할 수 있는 셀프 서비스 관리 도구 및 기능에 대한 정보가 포함되어 있습니다.
ms.openlocfilehash: 19ec50b3f502ee111de05e1a115d17f16fec3569
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45133003"
---
# <a name="exchange-online-setup-and-administration"></a>Exchange Online 설치 및 관리

이 문서에서는 Exchange Online 설정을 사용자 지정 하 고 조직의 Exchange Online 환경을 최신, 실행 및 최신 상태로 유지 하는 데 사용할 수 있는 관리 제어 및 지원에 대해 설명 합니다. 내용에는 Microsoft 관리 책임 및 성능 약정, 서비스 및 제품 업그레이드와 같이 조직에서 사용할 수 있는 셀프 서비스 관리 도구 및 기능에 대한 정보가 포함되어 있습니다.
  
## <a name="self-service-administration-tools"></a>셀프 서비스 관리 도구

Microsoft는 모든 Exchange Online 데이터 센터를 직접 제어 하 고 전반적인 시스템 성능을 담당 하지만 전체 사용자 환경을 제공 하기 위해 결합 되는 요소의 일부만 제어할 수 있습니다. 조직은 데이터 센터, 고객의 WAN (광역 네트워크) 및 고객 Lan (local area networks)에 대 한 네트워크 연결을 담당 합니다. 또한 사용자 장치 및 해당 구성에 대 한 비용이 청구 됩니다.또한 사용자가 기능에 액세스 해야 하는 경우에는 이러한 기능을 관리 하는 기능을 비롯 하 여 원하는 기능에 대해 사용자 당 필요한 라이선스를 유지 관리 해야 합니다.
  
따라서 Exchange Online은 고객 관리자에게 다양한 메시징 관련 작업을 관리할 수 있는 다음 도구를 제공합니다.
  
- [Microsoft Office 365 포털](exchange-online-setup-and-administration.md#microsoft-office-365-portal)
    
- [Microsoft 365 관리 센터](#microsoft-365-admin-center)
    
- [Exchange 관리 센터](exchange-online-setup-and-administration.md#exchange-admin-center)
    
- [Exchange Online용 원격 Windows PowerShell](exchange-online-setup-and-administration.md#remote-windows-powershell-for-exchange-online)
    
### <a name="microsoft-office-365-portal"></a>Microsoft Office 365 포털

[https://portal.office.com](https://portal.office.com)의 Microsoft Office 365 포털은 관리자와 파트너가 Office 365 서비스를 구입 및 관리하고, 사용자가 Office 365 공동 작업 도구에 액세스하여 사용할 수 있는 웹 사이트입니다.
  
### <a name="microsoft-365-admin-center"></a>Microsoft 365 관리 센터

Microsoft 365 관리 센터는 각 회사의 서비스 관리자가 구독 하는 각 Microsoft 서비스에 대 한 사용자 계정 및 설정을 관리할 수 있는 웹 포털입니다. Microsoft 365 관리 센터에서 관리자는 EAC (Exchange 관리 센터)에 대 한 링크를 팔 로우 하 여 Exchange Online과 관련 된 설정을 관리할 수 있습니다. Microsoft 365 관리 센터를 사용 하 여 작업을 수행 하 고 실행 하는 방법에 대 한 자세한 내용은 [Office 365 Enterprise 소개](https://go.microsoft.com/fwlink/p/?LinkId=271806)비디오를 참조 하세요.
  
### <a name="exchange-admin-center"></a>Exchange 관리 센터

Exchange Online provides a single unified management console that allows for ease of use and is optimized for management of on-premises, online, or hybrid deployments. The Exchange admin center (EAC) is where administrators can manage Exchange-specific settings.
  
EAC를 사용하여 Exchange Online을 관리하는 방법에 대한 자세한 내용은 [Exchange 관리 센터](https://go.microsoft.com/fwlink/p/?LinkId=271807)를 참조하세요.
  
### <a name="remote-windows-powershell-for-exchange-online"></a>Exchange Online용 원격 Windows PowerShell

Using remote Windows PowerShell, administrators can connect to Exchange Online to perform management tasks that are not available or practical using the EAC. These include the ability to automate repetitive tasks, extract data for custom reports, customize policies, and connect Exchange Online to existing infrastructure and processes. For more information, see [Connect to Exchange Online Using Remote PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=308994).
  
Exchange Online uses the same Windows PowerShell cmdlets as Exchange Server 2013, with certain commands and parameters unavailable because these features do not apply in Exchange Online. For a list of cmdlets for use with Exchange Online, see [Exchange Online cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).
  
Administrators do not need to install any Exchange Server management or migration tools to use remote Windows PowerShell. However, administrators' computers must be running the Windows Management Framework 3.0, which contains Windows PowerShell v3 and WinRM 3.0; and Windows .NET Framework 4.5. These components are already installed on computers running Windows 8 or Windows Server 2012. Administrators can manually download these components for computers that are running Windows 7 or Windows Server 2008 R2.
  
> [!IMPORTANT]
> DoS(서비스 거부) 공격을 방지하려면 Exchange Online 조직에 대해 세 가지 개방형 Windows PowerShell 연결만을 사용해야 합니다. 
  
## <a name="self-service-capabilities-for-exchange-online"></a>Exchange Online에 대한 셀프 서비스 기능

Below are important capabilities that are available for managing Exchange Online by using the EAC, remote Windows PowerShell, and other tools. Many other settings can also be controlled with these tools, as described throughout this document.
  
### <a name="mobile-device-security-policies-for-exchange-online"></a>Exchange Online에 대한 모바일 장치 보안 정책

Exchange Online supports the same ActiveSync policies for mobile devices as Exchange Server 2013. Administrators can enforce and customize these security policies for specific users and groups by using the EAC or remote Windows PowerShell.
  
### <a name="message-tracking-for-exchange-online"></a>Exchange Online에 대한 메시지 추적

배달 보고서 기능을 통한 메시지 추적은 [보고 기능 및 문제 해결 도구](reporting-features-and-troubleshooting-tools.md)항목에 설명 되어 있습니다.
  
### <a name="usage-reporting-for-exchange-online"></a>Exchange Online에 대한 사용 현황 보고

Administrators can use remote Windows PowerShell to retrieve information about how people in their organizations use the Exchange Online service. Available information includes:
  
- 조직 내 각 사용자에 대한 사서함 크기 표시.
    
- 사서함에 설정되는 사용자 지정 사용 권한(예: 대리인 액세스 권한) 표시.
    
- Exchange ActiveSync를 통해 연결 중인 사용자, 이러한 사용자가 사용 중인 장치 및 마지막으로 연결한 시간과 같은 모바일 장치 액세스에 대한 데이터 추출.
    
Remote Windows PowerShell cmdlets that start with "get-" can fetch data from the Exchange Online system. Administrators can export this information from Windows PowerShell in .csv format for advanced analysis or reporting.
  
Exchange Online에서 사용할 수 있는 Windows PowerShell cmdlet에 대한 자세한 내용은 [Exchange Online cmdlet](https://go.microsoft.com/fwlink/p/?LinkId=271808)을 참조하세요.
  
### <a name="auditing-for-exchange-online"></a>Exchange Online에 대한 감사

감사 로깅 기능은 [보고 기능 및 문제 해결 도구](reporting-features-and-troubleshooting-tools.md)항목에 설명 되어 있습니다.
  
## <a name="service-and-product-upgrades-for-exchange-online"></a>Exchange Online에 대한 서비스 및 제품 업그레이드

Exchange Online customers benefit from periodic upgrades to the latest Exchange technology, including new releases of Exchange Server. These upgrades are made available at no additional charge, and ensure that customers are always using the latest Exchange software.
  
고객은 Microsoft에서 주요 Exchange 버전을 릴리스한 후 12개월 이내에 서비스를 새 릴리스로 업그레이드할 수 있습니다.
  
## <a name="feature-availability"></a>기능 가용성

계획, 독립 실행형 옵션 및 온-프레미스 솔루션 별로 기능 가용성을 확인 하려면 [Exchange Online 서비스 설명을](exchange-online-service-description.md)참조 하세요.
  