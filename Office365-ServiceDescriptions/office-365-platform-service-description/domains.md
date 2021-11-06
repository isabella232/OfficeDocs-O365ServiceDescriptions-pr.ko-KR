---
title: 도메인
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-domains
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 5c374309-8016-4f18-8f2a-bceeb863ca67
description: 도메인을 추가할 때 단계별 마법사를 사용하면 사용자를 추가하고 전자 메일 주소 및 기타 서비스를 비즈니스 이름으로 변환할 수 있습니다. 마법사를 완료하면 비즈니스 전자 메일이 현재 전자 메일 공급자로 전송되는 대신 Microsoft로 전송됩니다.
ms.openlocfilehash: 4f34a220e475a14dda3dba73aea3a6f843aed1c7
ms.sourcegitcommit: 9a20cfc11c8202f2d95c7545d0a599934bcc3a1e
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 11/06/2021
ms.locfileid: "60805076"
---
# <a name="domains"></a>도메인

도메인을 추가할 때 단계별 마법사를 사용하면 사용자를 추가하고 전자 메일 주소 및 기타 서비스를 비즈니스 이름으로 변환할 수 있습니다. 마법사를 완료하면 비즈니스 전자 메일이 현재 전자 메일 공급자로 전송되는 대신 Microsoft로 전송됩니다. 자세한 내용은 Microsoft에 사용자 [및 도메인 추가를 참조합니다.](https://support.office.com/article/6383f56d-3d09-4dcb-9b41-b5f5a5efd611) 21Vianet에서 운영하는 Office 365를 사용하는 경우 [도메인 확인](/office365/admin/setup/add-domain)을 참조하세요.
  
## <a name="custom-domains"></a>사용자 지정 도메인

구독에 최대 5,000개 도메인을 추가할 수 있습니다(하위 도메인 포함). 다른 Microsoft 클라우드 서비스에서 이미 Microsoft 365 도메인을 추가할 수 없습니다. 또한 이 제한은 동일한 도메인을 여러 구독에 추가할 수 없다는 의미입니다. 자세한 내용은 [도메인 FAQ 를 참조하세요.](https://support.office.com/article/Domains-FAQ-1272bad0-4bd4-4796-8005-67d6fb3afc5a)
  
### <a name="second-and-third-level-domains"></a>2차 및 3차 수준 도메인

이 Office 365 Enterprise 비즈니스용 Microsoft 365 앱 사용하여 수준 도메인과 같은 세 번째 수준 도메인을 포함하여 모든 수준 도메인을 추가할 marketing.contoso.com. Microsoft에 사용자 지정 하위 도메인 또는 여러 [도메인 추가를 참조합니다.](/office365/admin/setup/domains-faq) 21Vianet에서 운영하는 Office 365를 사용하는 경우 [21Vianet에서 운영하는 Office 365에서 사용자 지정 하위 도메인 또는 여러 도메인 추가](/office365/admin/setup/domains-faq)를 참조하세요.
  
## <a name="domain-verification-and-managing-dns-records"></a>도메인 확인 및 DNS 레코드 관리

이 Microsoft 365 DNS 호스팅 공급자에서 모든 DNS 레코드를 관리하거나 Microsoft에서 도메인의 DNS 레코드를 설정 및 관리하게 할 수 있습니다. 레코드를 계속 관리하는 경우 필요한 경우 레코드를 지정하도록 Microsoft 서비스 변경합니다. 각 레코드에 사용할 특정 값을 포함하여 레코드를 추가하기 위한 단계별 지시를 제공하는 도메인 등록 기관 목록은 DNS 레코드 만들기를 참조하고, 21Vianet에서 운영하는 Office 365 사용하는 경우 21Vianet에서 운영하는 Office 365 모든 공급자에서 [DNS](/office365/admin/get-help-with-domains/create-dns-records-at-any-dns-hosting-provider) 레코드 만들기를 참조하세요. 
  
Microsoft에서 도메인의 DNS 레코드를 관리하는 경우 먼저 Microsoft를 지점으로 도메인의 이름 서버 레코드를 전환해야 합니다. 그런 다음 Microsoft에서 서비스를 설정하고 도메인의 DNS 레코드가 Microsoft에서 관리됩니다.
  
도메인이 GoDaddy에 등록되어 있는 경우 Microsoft는 GoDaddy에서 필요한 레코드를 만들 수 있습니다. 
  
DNS 레코드가 호스팅되는 위치와 상관없이 Microsoft에서 호스팅되는 공개 웹 사이트 또는 다른 호스팅 공급자와 함께 URL에 도메인을 사용하기 위해 DNS 레코드를 설정할 수 있습니다. 
  
Microsoft는 DNS 레코드를 사전적으로 확인하여 DNS 문제를 찾고 해결하는 데 도움을 제공합니다. DNS 레코드가 예상한 레코드와 일치하지 않는 경우 확인된 가능한 문제를 해결하는 방법을 알려 Microsoft 365 관리 센터 DNS 레코드에 알림이 표시됩니다.
  
자세한 내용은 [Microsoft에서 DNS](/office365/admin/setup/domains-faq) 레코드를 관리하는 방법을 참조하거나 21Vianet에서 Office 365 운영하는 Office 365 DNS 레코드 만들기를 [참조하세요.](/office365/admin/services-in-china/create-dns-records-when-you-manage-your-dns-records)
  
## <a name="sharing-a-domain"></a>도메인 공유

Microsoft의 도메인에 대한 일부 전자 메일 주소와 이전 전자 메일 공급자의 전자 메일 주소를 파일럿할 수 있습니다. 이 설정은 추가 설정 단계가 필요하고 파일럿 작업의 경우 몇 가지 제한이 있기 때문에 파일럿 동안에만 Microsoft 서비스. 자세한 내용은 다음을 참조하세요.
  
- [중소 Microsoft 365 파일럿 테스트](https://support.office.com/article/39cee536-6a03-40cf-b9c1-f301bb6001d7)
    
- [대기업용 Microsoft 365 파일럿 FastTrack)](https://fasttrack.office.com/onboard)
    
## <a name="feature-availability"></a>기능 가용성

비즈니스용 계획Microsoft 365 독립 실행형 옵션 및 Microsoft 365 플랫폼 서비스 설명에서 기능 가용성을 Microsoft 365 Office 365 [참조하세요.](office-365-platform-service-description.md)
