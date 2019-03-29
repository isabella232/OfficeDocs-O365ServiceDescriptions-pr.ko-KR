---
title: Exchange Online 설치 및 관리
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-administration-and-management
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 80c07748-ac57-4b90-97dd-a2d1115009a6
description: 이 섹션에서는 exchange online 설정을 사용자 지정 하 고 조직의 exchange online 환경을 최신, 실행 및 최신 상태로 유지 하는 데 사용할 수 있는 관리 제어 및 지원에 대해 설명 합니다. 내용에는 Microsoft 관리 책임 및 성능 약정, 서비스 및 제품 업그레이드와 같이 조직에서 사용할 수 있는 셀프 서비스 관리 도구 및 기능에 대한 정보가 포함되어 있습니다.
ms.openlocfilehash: 45707cbba47af8076312049686cb01beb6825d9e
ms.sourcegitcommit: de7d615d8967b1acc98a077337a0a2939c782481
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/29/2019
ms.locfileid: "30955747"
---
# <a name="exchange-online-setup-and-administration"></a>Exchange Online 설치 및 관리

이 섹션에서는 exchange online 설정을 사용자 지정 하 고 조직의 exchange online 환경을 최신, 실행 및 최신 상태로 유지 하는 데 사용할 수 있는 관리 제어 및 지원에 대해 설명 합니다. 내용에는 Microsoft 관리 책임 및 성능 약정, 서비스 및 제품 업그레이드와 같이 조직에서 사용할 수 있는 셀프 서비스 관리 도구 및 기능에 대한 정보가 포함되어 있습니다.
  
## <a name="self-service-administration-tools"></a>셀프 서비스 관리 도구

Microsoft에서 모든 Exchange Online 데이터 센터를 직접 제어하고 전체 시스템 성능을 책임지고는 있지만, Office 365 사용자의 전체 환경을 제공하기 위한 구성 요소의 일부만 관리할 수 있습니다. 조직은 자체적으로 데이터 센터, 고객의 WAN(광역 네트워크) 및 고객의 LAN(Local Area Network)에 대한 연결을 담당합니다. 또한 조직은 사용자 장치 및 구성을 책임지며, 사용자가 해당 기능에 액세스해야 하는 경우, 원하는 기능을 관리하는 능력을 포함하여 이에 국한되지 않는 기능 제공을 위해 사용자 기준 라이선스를 유지 관리해야 합니다.
  
따라서 Exchange Online은 고객 관리자에게 다양한 메시징 관련 작업을 관리할 수 있는 다음 도구를 제공합니다.
  
- [Microsoft Office 365 포털](exchange-online-setup-and-administration.md#microsoft-office-365-portal)
    
- [Microsoft 365 관리 센터](#microsoft-365-admin-center)
    
- [Exchange 관리 센터](exchange-online-setup-and-administration.md#exchange-admin-center)
    
- [Exchange Online용 원격 Windows PowerShell](exchange-online-setup-and-administration.md#remote-windows-powershell-for-exchange-online)
    
### <a name="microsoft-office-365-portal"></a>Microsoft Office 365 포털
<a name="BKMK_MicrosoftOnlineServicesPortal"> </a>

[https://portal.office.com](https://portal.office.com)의 Microsoft Office 365 포털은 관리자와 파트너가 Office 365 서비스를 구입 및 관리하고, 사용자가 Office 365 공동 작업 도구에 액세스하여 사용할 수 있는 웹 사이트입니다.
  
### <a name="microsoft-365-admin-center"></a>Microsoft 365 관리 센터
<a name="BKMK_Office365admincenterl"> </a>

Microsoft 365 관리 센터는 각 회사의 서비스 관리자가 구독 하는 각 Office 365 서비스에 대 한 사용자 계정 및 설정을 관리할 수 있는 웹 포털입니다. Microsoft 365 관리 센터에서 관리자는 EAC (exchange 관리 센터)에 대 한 링크를 팔 로우 하 여 exchange Online과 관련 된 설정을 관리할 수 있습니다. Microsoft 365 관리 센터를 사용 하 여 작업을 수행 하 고 실행 하는 방법에 대 한 자세한 내용은 [Office 365 Enterprise 소개](https://go.microsoft.com/fwlink/p/?LinkId=271806)비디오를 참조 하세요.
  
### <a name="exchange-admin-center"></a>Exchange 관리 센터
<a name="BKMK_ExchangeAdministrationCenter"> </a>

Exchange Online은 온-프레미스, 온라인 또는 하이브리드 배포의 관리에 최적화된 편리한 단일 통합 관리 콘솔을 제공합니다. EAC(Exchange 관리 센터)를 통해 관리자는 Exchange 관련 설정을 관리할 수 있습니다.
  
EAC를 사용하여 Exchange Online을 관리하는 방법에 대한 자세한 내용은 [Exchange 관리 센터](https://go.microsoft.com/fwlink/p/?LinkId=271807)를 참조하세요.
  
### <a name="remote-windows-powershell-for-exchange-online"></a>Exchange Online용 원격 Windows PowerShell
<a name="BKMK_RemoteWindowsPowerShell"> </a>

원격 Windows PowerShell을 사용하면 관리자는 Exchange Online에 연결하여 EAC에서는 사용할 수 없거나 타당하지 않은 관리 작업을 수행할 수 없습니다. 여기에는 반복 작업 자동화, 사용자 지정 보고서용 데이터 추출, 정책 사용자 지정 및 기존 인프라와 프로세스에 Exchange Online 연결 기능이 포함됩니다. 자세한 내용은 [원격 PowerShell을 사용하여 Exchange Online에 연결](https://go.microsoft.com/fwlink/p/?LinkId=308994)을 참조하세요.
  
Exchange Online에서는 Exchange Server 2013과 동일한 Windows PowerShell cmdlet을 사용합니다. 그러나 Exchange Online에 적용되지 않는 특정 명령과 매개 변수는 사용할 수 없습니다. Exchange Online에서 사용할 수 있는 cmdlet 목록은 [Exchange Online cmdlet](https://go.microsoft.com/fwlink/p/?LinkId=271808)을 참조하세요.
  
원격 Windows PowerShell을 사용하기 위해 관리자가 Exchange Server 관리 또는 마이그레이션 도구를 설치할 필요가 없습니다. 그러나 관리자의 컴퓨터는 Windows PowerShell v3 및 WinRM 3.0, Windows .NET Framework 4.5가 포함된 Windows Management Framework 3.0을 실행 중이어야 합니다. 이러한 구성 요소는 Windows 8 또는 Windows Server 2012를 실행 중인 컴퓨터에 이미 설치되어 있습니다. Windows 7 또는 Windows Server 2008 R2를 실행 중인 컴퓨터에 대해서는 관리자가 이러한 구성 요소를 수동으로 다운로드할 수 있습니다.
  
> [!IMPORTANT]
> DoS(서비스 거부) 공격을 방지하려면 Exchange Online 조직에 대해 세 가지 개방형 Windows PowerShell 연결만을 사용해야 합니다. 
  
## <a name="self-service-capabilities-for-exchange-online"></a>Exchange Online에 대한 셀프 서비스 기능

EAC, 원격 Windows PowerShell 및 기타 도구를 통해 Exchange Online을 관리하는 데 사용할 수 있는 다음 기능은 중요한 기능입니다. 이 문서에서 설명하는 다른 많은 설정 또한 이러한 도구로 제어할 수 있습니다.
  
### <a name="mobile-device-security-policies-for-exchange-online"></a>Exchange Online에 대한 모바일 장치 보안 정책

Exchange Online에서는 모바일 장치에 대해 Exchange Server 2013과 동일한 ActiveSync 정책을 지원합니다. 관리자는 EAC 또는 원격 Windows PowerShell을 통해 이러한 보안 정책을 특정 사용자 및 그룹에 대해 적용하고 사용자 지정할 수 있습니다.
  
### <a name="message-tracking-for-exchange-online"></a>Exchange Online에 대한 메시지 추적

배달 보고서를 통한 메시지 추적은 다음 항목에서 설명합니다. [보고 기능 및 문제 해결 도구](reporting-features-and-troubleshooting-tools.md).
  
### <a name="usage-reporting-for-exchange-online"></a>Exchange Online에 대한 사용 현황 보고

관리자는 원격 Windows PowerShell을 사용하여 조직 내 사람들이 Exchange Online 서비스를 사용하는 방식에 대한 정보를 검색할 수 있습니다. 사용할 수 있는 정보는 다음과 같습니다.
  
- 조직 내 각 사용자에 대한 사서함 크기 표시.
    
- 사서함에 설정되는 사용자 지정 사용 권한(예: 대리인 액세스 권한) 표시.
    
- Exchange ActiveSync를 통해 연결 중인 사용자, 이러한 사용자가 사용 중인 장치 및 마지막으로 연결한 시간과 같은 모바일 장치 액세스에 대한 데이터 추출.
    
"get-"으로 시작하는 원격 Windows PowerShell cmdlet은 Exchange Online 시스템에서 데이터를 가져올 수 있습니다. 관리자는 고급 분석 또는 보고를 위해 Windows PowerShell에서 이 정보를 .csv 형식으로 내보낼 수 있습니다.
  
Exchange Online에서 사용할 수 있는 Windows PowerShell cmdlet에 대한 자세한 내용은 [Exchange Online cmdlet](https://go.microsoft.com/fwlink/p/?LinkId=271808)을 참조하세요.
  
### <a name="auditing-for-exchange-online"></a>Exchange Online에 대한 감사

감사 로깅 기능은 다음 항목에서 설명합니다. [보고 기능 및 문제 해결 도구](reporting-features-and-troubleshooting-tools.md).
  
## <a name="service-and-product-upgrades-for-exchange-online"></a>Exchange Online에 대한 서비스 및 제품 업그레이드

Exchange Online 고객은 Exchange Server의 새 릴리스를 비롯하여 최신 Exchange 기술에 대한 정기 업그레이드를 통해 혜택을 얻을 수 있습니다. 이러한 업그레이드는 추가 비용 없이 가능하며, 고객은 항상 최신 Exchange 소프트웨어를 사용하고 있는지 확인해야 합니다.
  
고객은 Microsoft에서 주요 Exchange 버전을 릴리스한 후 12개월 이내에 서비스를 새 릴리스로 업그레이드할 수 있습니다.
  
## <a name="feature-availability"></a>기능 가용성

Office 365 계획, 독립 실행형 옵션 및 온-프레미스 솔루션별로 기능 가용성을 확인하려면 [Exchange Online 서비스 설명](exchange-online-service-description.md)을 참조하세요.
  

