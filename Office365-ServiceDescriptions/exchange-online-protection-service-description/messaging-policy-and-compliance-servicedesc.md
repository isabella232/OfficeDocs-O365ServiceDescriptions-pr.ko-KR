---
title: 메시징 정책 및 준수 Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- messaging-policy-and-compliance-in-eop
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
ms.assetid: 1074f583-523f-4dca-9012-c9b93aae96b7
description: 이 문서를 읽고 EOP(Microsoft Exchange Online 보호)의 메시징 정책 및 규정 준수 기능에 대해 자세히 알아보습니다.
ms.openlocfilehash: 8bd7b752191f6304d95f079984a281b25169352f
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/24/2021
ms.locfileid: "59672309"
---
# <a name="messaging-policy-and-compliance-in-exchange-online-protection"></a>메시징 정책 및 준수 Exchange Online Protection

Microsoft Exchange Online EOP(보호)는 전자 메일 데이터를 관리하는 데 도움이 되는 메시징 정책 및 규정 준수 기능을 제공합니다.

모든 EOP 기능에 대한 정보를 찾고 있나요? 자세한 [내용은 Exchange Online Protection 설명을 참조하세요.](exchange-online-protection-service-description.md)

## <a name="mail-flow-rules"></a>메일 흐름 규칙

메일 흐름 규칙(전송 규칙)을 사용하면 회사별 정책을 전자 메일에 유연하게 적용할 수 있습니다. 메일 흐름 규칙은 조건을 기반으로 수행할 조건, 예외 및 작업을 정의할 수 있는 유연한 기준으로 구성됩니다. 자세한 내용은 에서 메일 흐름 [규칙(전송 규칙)을 Exchange Online Protection.](/microsoft-365/security/office-365-security/mail-flow-rules-transport-rules-0)

## <a name="audit-logging"></a>감사 로깅

감사 로깅을 통해 관리자가 조직에 수행한 특정 변경 내용을 추적할 수 있습니다. 이러한 보고서를 사용하면 규정, 준수 및 소송 요구 사항을 충족하는 데 도움을 받을 수 있습니다. 자세한 내용은 [EOP의 감사 보고서](/microsoft-365/security/office-365-security/auditing-reports-in-eop)를 참조하세요.

## <a name="data-loss-prevention-dlp"></a>DLP(데이터 손실 방지)

EOP 독립 실행형 고객에게는 제공되지 않습니다. DLP(데이터 손실 방지)는 콘텐츠를 심층 분석하여 조직에 중요한 정보를 식별, 모니터링하고 보호하는 데 도움을 줍니다. 업무상 중요한 전자 메일에는 보호해야 할 중요한 데이터가 포함되어 있으므로, 엔터프라이즈 메시지 시스템에서 DLP의 중요성이 갈수록 높아지고 있습니다. DLP 기능을 사용하면 작업자 생산성에 영향을 주지 않고 중요한 데이터를 보호할 수 있습니다.

EAC에서 DLP 정책을 구성하면 다음과 같은 작업이 가능합니다.

- PCI-DSS 데이터, 금융서비스 현대화법(Gramm-Leach-Bliley Act) 데이터 같이 특정 형식의 중요한 정보 또는 또는 로캘별 PII(개인 식별 정보)를 검색하는 데 도움을 받을 수 있는, 미리 구성된 정책 템플릿으로 시작합니다.

- 기존 메일 흐름 규칙 조건 및 작업의 모든 기능을 사용하여 새 메일 흐름 규칙을 추가합니다.

- DLP 정책의 효율성을 테스트한 후에 완전히 적용합니다.

- 자신의 사용자 지정 DLP 정책 템플릿과 중요한 정보 형식을 통합합니다.

- 메시지 첨부 파일, 본문 텍스트 또는 제목 줄에서 중요한 정보를 검색하고, 서비스에서 작업을 수행하는 신뢰 수준을 조정합니다.

- 문서 지문을 사용하여 중요한 양식 데이터를 감지합니다. 문서 지문을 사용하면 메일 흐름 규칙 및 DLP 정책을 정의하는 데 사용할 수 있는 텍스트 기반 양식을 기반으로 사용자 지정 중요한 정보 유형을 쉽게 만들 수 있습니다.

- 장치 Outlook 팁 2013, 웹용 Outlook 및 장치용 OWA 사용자에게 공지를 표시하여 데이터 손실을 줄일 수 있으며 가음성 보고를 허용하여 정책의 효율성을 향상시킬 수 있는 정책 정책을 추가합니다.

- DLP 보고서의 문제 데이터를 검토하거나, 문제 보고서 생성 작업을 사용하여 자체 보고서를 추가합니다.

> [!NOTE]
> DLP 정책은 조직을 드나드는 메일에만 적용됩니다. DLP 온-프레미스가 포함된 Exchange Server 2013을 실행하는 경우 외에는 조직 내(내부) 메일에 DLP 정책이 적용되지 않습니다. 이는 중요한 데이터를 권한이 없는 받는 사람에게 실수로 보내기 전에 정책 위반 가능성을 사용자에게 알려주는 DLP 정책 팁의 경우에도 마찬가지입니다.

DLP에 대한 자세한 내용은 에서 [데이터 손실 방지를 Exchange Online.](/exchange/security-and-compliance/data-loss-prevention/data-loss-prevention)

## <a name="office-365-message-encryption"></a>Office 365 메시지 암호화

Office 365 메시지 암호화 Azure Information Protection의 일부인 이 서비스는 전자 메일 사용자가 누구에게나 암호화된 전자 메일 메시지를 보낼 수 있도록 하는 온라인 서비스입니다. 프레미스 고객은 Azure Information Protection을 Office 365 메시지 암호화 Azure Information Protection을 사용하여 Exchange Online Protection 통해 메일 흐름을 설정할 수 Exchange Online. Office 365 메시지 암호화 서비스 Exchange Online 자세한 내용은 Office 365 메시지 암호화 [서비스](../exchange-online-service-description/message-policy-and-compliance.md#office-365-message-encryption) 설명에서 Exchange Online 참조하세요.

## <a name="messaging-policy-and-compliance-features-across-eop-options"></a>EOP 옵션별 메시징 정책 및 규정 준수 기능

| 기능 | EOP 독립 실행형 | EOP 기능 <br/> Exchange Online | Exchange Enterprise <br/> CAL with Services |
|:-----|:-----|:-----|:-----|
|메일 흐름 규칙|예<sup>1</sup>|예<sup>1</sup>|예<sup>1, 3</sup>|
|감사 로깅|예<sup>2</sup>|예|예|
|DLP(데이터 손실 방지)|아니요|예|예<sup>3</sup>|
|Office 365 메시지 암호화|예<sup>4</sup>|예|예<sup>4</sup>|

> [!NOTE]
> <sup>1</sup> 사용 가능한 메일 흐름 규칙 조건, 예외 및 작업은 EOP와 규칙 간의 Exchange Online. 이러한 차이점은 Exchange Online 및 메일 흐름 규칙 작업의 메일 흐름 규칙 조건 및 예외(조건자)에 [Exchange Online.](/Exchange/security-and-compliance/mail-flow-rules/mail-flow-rule-actions) [](/Exchange/security-and-compliance/mail-flow-rules/conditions-and-exceptions) <br/>
> <sup>2</sup> EOP 감사 보고서는 사서함에 대한 정보가 제외된, Exchange Online 감사 보고서의 하위 집합입니다.<br/>
> <sup>3</sup> Exchange Enterprise CAL with Services 고객은 DLP 정책 팁을 사용할 수 없습니다.<br/>
> <sup>4</sup> Azure Information Protection 추가 기능을 구입하고 Azure Information Protection 추가 기능을 사용하여 Exchange Online Protection 전자 메일을 라우팅하는 Exchange Online. 데스크톱 환경의 경우 Azure Information Protection 추가 기능 외에 엔터프라이즈용 Microsoft 365 앱 구입해야 합니다. <br/>