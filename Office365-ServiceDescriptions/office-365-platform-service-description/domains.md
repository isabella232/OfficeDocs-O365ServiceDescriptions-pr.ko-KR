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
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 5c374309-8016-4f18-8f2a-bceeb863ca67
description: 도메인을 추가할 때 단계별 마법사를 사용하면 사용자를 추가하고 전자 메일 주소 및 기타 서비스를 비즈니스 이름으로 변환할 수 있습니다. 마법사를 완료하면 비즈니스 전자 메일이 현재 전자 메일 공급자로 전송되는 대신 Microsoft로 전송됩니다. 자세한 내용은 Microsoft에 사용자 및 도메인 추가를 참조합니다. 21Vianet에서 운영하는 Office 365를 사용하는 경우 도메인 확인을 참조하세요.
ms.openlocfilehash: 72ea4e88d659d7a6004888c45bb233832978fd34
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652572"
---
# <a name="domains"></a>도메인

도메인을 추가할 때 단계별 마법사를 사용하면 사용자를 추가하고 전자 메일 주소 및 기타 서비스를 비즈니스 이름으로 변환할 수 있습니다. 마법사를 완료하면 비즈니스 전자 메일이 현재 전자 메일 공급자로 전송되는 대신 Microsoft로 전송됩니다. 자세한 내용은 Microsoft에 사용자 [및 도메인 추가를 참조합니다.](https://support.office.com/article/6383f56d-3d09-4dcb-9b41-b5f5a5efd611) 21Vianet에서 운영하는 Office 365를 사용하는 경우 [도메인 확인](/office365/admin/setup/add-domain)을 참조하세요.
  
## <a name="custom-domains"></a>사용자 지정 도메인

구독에 최대 900개 도메인을 추가할 수 있습니다(하위 도메인 포함). 다른 Microsoft 클라우드 서비스에서 이미 사용 중이신 도메인은 Microsoft 365에 추가할 수 없습니다. 즉, 여러 구독에 동일한 도메인을 추가할 수 없습니다. 자세한 내용은 [도메인 FAQ 를 참조하세요.](https://support.office.com/article/Domains-FAQ-1272bad0-4bd4-4796-8005-67d6fb3afc5a)
  
### <a name="second-and-third-level-domains"></a>2차 및 3차 수준 도메인

Office 365 Enterprise 및 비즈니스용 Microsoft 365 앱을 사용하여 사용자 지정과 같은 세 번째 수준 도메인을 포함하여 모든 수준 도메인을 추가할 marketing.contoso.com. Microsoft에 사용자 지정 하위 도메인 또는 여러 [도메인 추가를 참조합니다.](/office365/admin/setup/domains-faq) 21Vianet에서 운영하는 Office 365를 사용하는 경우 [21Vianet에서 운영하는 Office 365에서 사용자 지정 하위 도메인 또는 여러 도메인 추가](/office365/admin/setup/domains-faq)를 참조하세요.
  
## <a name="domain-verification-and-managing-dns-records"></a>도메인 확인 및 DNS 레코드 관리

Microsoft 365를 사용하면 DNS 호스팅 공급자에서 모든 DNS 레코드를 관리하거나 Microsoft에서 도메인의 DNS 레코드를 설정하고 관리하게 할 수 있습니다. 레코드를 계속 관리하는 경우 필요한 경우 Microsoft 서비스를 설정하도록 특정 레코드를 변경합니다. 각 레코드에 사용할 특정 값을 포함하여 레코드를 추가하기 위한 단계별 지시를 제공하는 도메인 등록 기관 목록은 [DNS](/office365/admin/get-help-with-domains/create-dns-records-at-any-dns-hosting-provider) 레코드 만들기를 참조하거나, 21Vianet에서 운영하는 Office 365를 사용하는 경우 21Vianet에서 운영하는 Office 365용 공급자에서 DNS 레코드 만들기를 참조하세요. 
  
Microsoft에서 도메인의 DNS 레코드를 관리하는 경우 먼저 Microsoft를 지점으로 도메인의 이름 서버 레코드를 전환해야 합니다. 그런 다음 Microsoft에서 서비스를 설정하고 도메인의 DNS 레코드가 Microsoft에서 관리됩니다.
  
도메인이 GoDaddy에 등록되어 있는 경우 Microsoft는 GoDaddy에서 필요한 레코드를 만들 수 있습니다. 
  
DNS 레코드가 호스팅되는 위치와 상관없이 Microsoft에서 호스팅되는 공개 웹 사이트 또는 다른 호스팅 공급자와 함께 URL에 도메인을 사용하기 위해 DNS 레코드를 설정할 수 있습니다. 
  
Microsoft는 DNS 레코드를 사전적으로 확인하여 DNS 문제를 찾고 해결하는 데 도움을 제공합니다. DNS 레코드가 예상과 일치하지 않는 경우 Microsoft 365 관리 센터에서 알림과 함께 식별된 가능한 문제를 해결하는 방법을 알려 주게 됩니다.
  
자세한 내용은 [Microsoft에서 DNS](/office365/admin/setup/domains-faq) 레코드를 관리하는 방법을 참조하거나 21Vianet에서 운영하는 Office 365의 경우 DNS 레코드를 관리할 때 [Office 365용 DNS](/office365/admin/services-in-china/create-dns-records-when-you-manage-your-dns-records)레코드 만들기를 참조하세요.
  
## <a name="sharing-a-domain"></a>도메인 공유

Microsoft의 도메인에 대한 일부 전자 메일 주소와 이전 전자 메일 공급자의 전자 메일 주소를 파일럿할 수 있습니다. 이 단계는 추가 설정 단계가 필요하고 Microsoft 서비스에 대한 몇 가지 제한 사항이 있기 때문에 파일럿 중에만 사용하는 것이 좋습니다. 자세한 내용은 다음을 참조하세요.
  
- [중소기업용 Microsoft 365 파일럿](https://support.office.com/article/39cee536-6a03-40cf-b9c1-f301bb6001d7)
    
- [대기업용 Microsoft 365 파일럿(FastTrack 사용)](https://fasttrack.office.com/onboard)
    
## <a name="feature-availability"></a>기능 가용성

비즈니스용 Microsoft 365 요금제, 독립 실행형 옵션 및 사내 솔루션에서 기능 가용성을 확인하면 [Microsoft 365 및 Office 365](office-365-platform-service-description.md)플랫폼 서비스 설명을 참조하세요.
