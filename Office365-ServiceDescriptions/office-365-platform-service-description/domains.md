---
title: 도메인
ms.author: office365servicedesc
author: pamelaar
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
description: 도메인을 추가 하면 단계별 마법사가 사용자를 추가 하 고 전자 메일 주소 및 기타 서비스를 회사 이름으로 변환 하도록 도와줍니다. 마법사를 완료 하면 회사 전자 메일이 현재 전자 메일 공급자로 이동 하는 대신 Microsoft에 전송 됩니다. 자세한 내용은 Microsoft에 사용자 및 도메인 추가를 참조 하세요. 21Vianet에서 운영하는 Office 365를 사용하는 경우 도메인 확인을 참조하세요.
ms.openlocfilehash: 109dd15af75c8e3e04406a63c8868e010c12b9c5
ms.sourcegitcommit: 6a9c3c47e7526de046787ad0f02b9c008e541c34
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/31/2020
ms.locfileid: "46531221"
---
# <a name="domains"></a>도메인

도메인을 추가 하면 단계별 마법사가 사용자를 추가 하 고 전자 메일 주소 및 기타 서비스를 회사 이름으로 변환 하도록 도와줍니다. 마법사를 완료 하면 회사 전자 메일이 현재 전자 메일 공급자로 이동 하는 대신 Microsoft에 전송 됩니다. 자세한 내용은 [Microsoft에 사용자 및 도메인 추가](https://support.office.com/article/6383f56d-3d09-4dcb-9b41-b5f5a5efd611)를 참조 하세요. 21Vianet에서 운영하는 Office 365를 사용하는 경우 [도메인 확인](https://docs.microsoft.com/office365/admin/setup/add-domain)을 참조하세요.
  
## <a name="custom-domains"></a>사용자 지정 도메인

하위 도메인을 포함 하 여 구독에 도메인을 최대 900 개까지 추가할 수 있습니다. 다른 Microsoft 클라우드 서비스에서 이미 사용 중인 Microsoft 365에는 도메인을 추가할 수 없습니다. 즉, 동일한 도메인을 여러 구독에 추가할 수 없습니다. 자세한 내용은 [도메인 FAQ](https://support.office.com/article/Domains-FAQ-1272bad0-4bd4-4796-8005-67d6fb3afc5a)를 참조 하세요.
  
### <a name="second-and-third-level-domains"></a>2차 및 3차 수준 도메인

Office 365 엔터프라이즈 및 비즈니스용 Microsoft 365 앱을 사용 하 여 marketing.contoso.com 등의 3 차 수준 도메인을 비롯 한 모든 수준의 도메인을 추가할 수 있습니다. [Microsoft에 사용자 지정 하위 도메인 또는 여러 도메인 추가를](https://docs.microsoft.com/office365/admin/setup/domains-faq)참조 하세요. 21Vianet에서 운영하는 Office 365를 사용하는 경우 [21Vianet에서 운영하는 Office 365에서 사용자 지정 하위 도메인 또는 여러 도메인 추가](https://docs.microsoft.com/office365/admin/setup/domains-faq)를 참조하세요.
  
## <a name="domain-verification-and-managing-dns-records"></a>도메인 확인 및 DNS 레코드 관리

Microsoft 365를 사용 하 여 DNS 호스팅 공급자에서 모든 DNS 레코드를 관리 하거나 Microsoft에 도메인의 DNS 레코드를 설정 하 고 관리 하도록 선택할 수 있습니다. 계속 해 서 레코드를 관리 하는 경우 필요에 따라 Microsoft 서비스를 가리키도록 특정 레코드를 변경 합니다. 각 레코드에 사용할 특정 값을 포함 하 여 레코드를 추가 하는 단계별 지침을 제공 하는 도메인 등록 기관 목록을 보려면 [CREATE dns records](https://docs.microsoft.com/office365/admin/get-help-with-domains/create-dns-records-at-any-dns-hosting-provider) 를 참조 하 고, 21vianet에서 운영 하는 office 365을 사용 하는 경우 365에는 모든 공급자에서 Dns 레코드 만들기를 참조 하세요. 
  
Microsoft에서 도메인의 DNS 레코드를 관리 하는 경우 먼저 도메인의 이름 서버 레코드를 전환 하 여 Microsoft를 가리킨 다음 Microsoft에서 서비스를 설정 하 고 도메인의 DNS 레코드를 Microsoft에서 관리 해야 합니다.
  
도메인이 GoDaddy에 등록 되어 있는 경우 Microsoft는 GoDaddy에 필요한 레코드를 만들 수 있습니다. 
  
DNS 레코드가 호스트 되는 위치에 관계 없이 Microsoft 또는 다른 호스팅 공급자를 사용 하 여 호스트 되는 공개 웹 사이트의 URL에 대해 도메인을 사용 하도록 DNS 레코드를 설정할 수 있습니다. 
  
Microsoft는 DNS 레코드를 사전 검사 하 여 DNS 문제를 찾아 해결 합니다. DNS 레코드가 예상 대로 일치 하지 않으면 식별 된 가능한 문제를 해결 하는 방법을 설명 하는 정보와 함께 Microsoft 365 관리 센터에서 알림을 받게 됩니다.
  
자세한 내용은 [Microsoft에서 dns 레코드를 관리 하는 방법](https://docs.microsoft.com/office365/admin/setup/domains-faq) 또는 21vianet에서 운영 하는 office 365의 경우 [dns 레코드를 관리할 때 office 365에 대 한 dns 레코드 만들기](https://docs.microsoft.com/office365/admin/services-in-china/create-dns-records-when-you-manage-your-dns-records)를 참조 하세요.
  
## <a name="sharing-a-domain"></a>도메인 공유

Microsoft의 도메인 및 이전 전자 메일 공급자의 일부 전자 메일 주소를 파일럿으로 사용할 수 있습니다. 이 기능은 추가 설치 단계가 필요 하며 Microsoft 서비스에 대 한 몇 가지 제한이 있기 때문에 파일럿 중에 사용할 때만 사용 하는 것이 좋습니다. 자세한 내용은 다음을 참조하세요.
  
- [중소 기업에 대 한 파일럿 Microsoft 365](https://support.office.com/article/39cee536-6a03-40cf-b9c1-f301bb6001d7)
    
- [대규모 기업에 대 한 파일럿 Microsoft 365 (FastTrack 사용)](https://fasttrack.office.com/onboard)
    
## <a name="feature-availability"></a>기능 가용성

비즈니스 계획, 독립 실행형 옵션 및 온-프레미스 솔루션에 대 한 Microsoft 365의 기능 가용성을 확인 하려면 [microsoft 365 및 Office 365 platform service description](office-365-platform-service-description.md)을 참조 하세요.
  

