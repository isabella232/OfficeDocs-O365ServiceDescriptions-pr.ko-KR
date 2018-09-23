---
title: 메시징 정책 및 규정 준수[ServiceDesc]
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- messaging-policy-and-compliance-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 1074f583-523f-4dca-9012-c9b93aae96b7
description: Microsoft Exchange Online Protection (EOP) 제공 메시징 정책 및 규정 준수 기능 하는데 도움이 되는 전자 메일 데이터를 관리 합니다.
ms.openlocfilehash: f88cd016586384f4617cd4899708c811a32af980
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036471"
---
# <a name="messaging-policy-and-complianceservicedesc"></a>메시징 정책 및 규정 준수[ServiceDesc]

Microsoft Exchange Online Protection (EOP) 제공 메시징 정책 및 규정 준수 기능 하는데 도움이 되는 전자 메일 데이터를 관리 합니다.
  
모든 EOP 기능에 대한 자세한 내용은 [Exchange Online Protection 서비스 설명](exchange-online-protection-service-description.md)을 참조하세요.
  
## <a name="transport-rules"></a>전송 규칙
<a name="BKMK_transportrules"> </a>

전송 규칙을 통해 자체 회사별 정책을 전자 메일에 유동적으로 적용할 수 있습니다. 전송 규칙은 유연한 기준으로 구성됩니다. 이러한 기준을 기반으로 조건 및 예외를 정의하고, 수행할 작업을 정의합니다. EOP의 전송 규칙에 대한 자세한 내용은 [전송 규칙](https://go.microsoft.com/fwlink/p/?LinkId=320399)을 참조하세요.
  
## <a name="audit-logging"></a>감사 로깅
<a name="BKMK_auditlogging"> </a>

감사 로깅을 통해 관리자가 조직에 수행한 특정 변경 내용을 추적할 수 있습니다. 이러한 보고서를 사용하면 규정, 준수 및 소송 요구 사항을 충족하는 데 도움을 받을 수 있습니다. 자세한 내용은 [EOP의 감사 보고서](https://go.microsoft.com/fwlink/p/?LinkId=314258)를 참조하세요.
  
## <a name="data-loss-prevention-dlp"></a>DLP(데이터 손실 방지)
<a name="BKMK_datalossprevention"> </a>

EOP 독립 실행형 고객에게는 제공되지 않습니다. DLP(데이터 손실 방지)는 콘텐츠를 심층 분석하여 조직에 중요한 정보를 식별, 모니터링하고 보호하는 데 도움을 줍니다. 업무상 중요한 전자 메일에는 보호해야 할 중요한 데이터가 포함되어 있으므로, 엔터프라이즈 메시지 시스템에서 DLP의 중요성이 갈수록 높아지고 있습니다. DLP 기능을 사용하면 직원 생산성에 영향을 주지 않으면서도 중요한 데이터를 보호할 수 있습니다.
  
EAC에서 DLP 정책을 구성하면 다음과 같은 작업이 가능합니다.
  
- PCI-DSS 데이터, 금융서비스 현대화법(Gramm-Leach-Bliley Act) 데이터 같이 특정 형식의 중요한 정보 또는 또는 로캘별 PII(개인 식별 정보)를 검색하는 데 도움을 받을 수 있는, 미리 구성된 정책 템플릿으로 시작합니다.
    
- 기존 전송 규칙 조건 및 작업을 완벽하게 활용하고 새 전송 규칙을 추가합니다.
    
- DLP 정책의 효율성을 테스트한 후에 완전히 적용합니다.
    
- 자신의 사용자 지정 DLP 정책 템플릿과 중요한 정보 형식을 통합합니다.
    
- 메시지 첨부 파일, 본문 텍스트 또는 제목 줄에서 중요한 정보를 검색하고, 서비스에서 작업을 수행하는 신뢰 수준을 조정합니다.
    
- 문서 지문을 사용하여 중요한 양식 데이터를 감지합니다. 문서 지문을 사용하면 전송 규칙 및 DLP 정책을 정의하는 데 사용할 수 있는 텍스트 기반 양식의 중요한 사용자 지정 정보 유형을 손쉽게 만들 수 있습니다.
    
- Outlook 2013, Outlook Web App 및 장치용 OWA 사용자에게 알림을 표시하여 데이터 손실을 줄일 수 있고, 가양성 보고를 허용하여 정책의 효율성도 향상시킬 수 있는 정책 팁을 추가합니다.
    
- DLP 보고서의 문제 데이터를 검토하거나, 문제 보고서 생성 작업을 사용하여 자체 보고서를 추가합니다.
    
> [!NOTE]
> DLP 정책은 조직을 드나드는 메일에만 적용됩니다. DLP 온-프레미스가 포함된 Exchange Server 2013을 실행하는 경우 외에는 조직 내(내부) 메일에 DLP 정책이 적용되지 않습니다. 이는 중요한 데이터를 권한이 없는 받는 사람에게 실수로 보내기 전에 정책 위반 가능성을 사용자에게 알려주는 DLP 정책 팁의 경우에도 마찬가지입니다. 
  
DLP에 대한 자세한 내용은 [데이터 손실 방지](https://go.microsoft.com/fwlink/p/?LinkId=320398)를 참조하세요.
  
## <a name="office-365-message-encryption"></a>Office 365 메시지 암호화
<a name="BKMK_OME_in_EOP"> </a>

Office 365 메시지 암호화, Azure 정보 보호의 일부에는 모든 사용자에 게 암호화 된 전자 메일 메시지를 보낼 전자 메일 사용자를 허용 하는 온라인 서비스입니다. 온-프레미스 고객 Azure 정보 보호를 구입 하 고 Exchange Online 보호를 사용 하 여 Exchange Online을 통한 메일 흐름을 설정 하 여 Office 365 메시지 암호화에 액세스할 수 있습니다. 자세한 내용은 Office 365 메시지 암호화에 대 한 Exchange Online, Exchange Online 서비스 설명에서 [Office 365 메시지 암호화](../exchange-online-service-description/message-policy-and-compliance.md#office-365-message-encryption) 참조 하십시오. 
  
## <a name="messaging-policy-and-compliance-features-across-eop-options"></a>EOP 옵션별 메시징 정책 및 규정 준수 기능
<a name="BKMK_OME_in_EOP"> </a>

|**기능**|**EOP 독립 실행형**|**Exchange Online의 EOP 기능**|**Exchange Enterprise CAL(서비스 포함)**|
|:-----|:-----|:-----|:-----|
|전송 규칙  <br/> |예<sup>1</sup> <br/> |예<sup>1</sup> <br/> |예  <br/> |
|감사 로깅  <br/> |예<sup>2</sup> <br/> |예  <br/> |예  <br/> |
|DLP(데이터 손실 방지)  <br/> |아니요  <br/> |예  <br/> |예<sup>3</sup> <br/> |
|Office 365 메시지 암호화  <br/> |예<sup>4</sup> <br/> |예  <br/> |예<sup>4</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> 사용할 수 있는 조건 및 동작 EOP 및 Exchange Online 간에 서로 다릅니다. 사용 가능한 조건 및 EOP의 작업 목록, [전송 규칙 조건](https://go.microsoft.com/fwlink/p/?LinkId=320392) 및 [전송 규칙 동작](https://go.microsoft.com/fwlink/p/?LinkId=320393)을 참조 하십시오. 사용 가능한 조건 및 Exchange Online에서 작업 목록, [전송 규칙 조건](https://go.microsoft.com/fwlink/p/?LinkId=320394) 및 [전송 규칙 동작](https://go.microsoft.com/fwlink/p/?LinkId=320395)을 참조 하십시오. > <sup>2</sup> EOP 감사 보고서는 Exchange Online의 하위 집합 감사 보고서는 사서함에 대 한 정보를 제외 합니다. > <sup>3</sup> DLP 정책 팁은 서비스 고객과 Exchange Enterprise CAL 사용할 수 없습니다. > <sup>4</sup> 지원 되 는 온-프레미스 고객에 게 Azure 정보 보호 추가 기능을 구매 하 고 Exchange Online Protection Exchange Online을 통해 전자 메일 라우팅에 사용 합니다. Azure 정보 보호 추가 기능 외에도 데스크톱 경험을 위해 Office 365 ProPlus 구입 해야 합니다. 
  

