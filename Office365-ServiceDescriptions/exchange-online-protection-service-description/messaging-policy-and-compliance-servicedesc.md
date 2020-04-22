---
title: 메시징 정책 및 규정 준수
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- messaging-policy-and-compliance-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 1074f583-523f-4dca-9012-c9b93aae96b7
description: Microsoft EOP (Exchange Online Protection)에서는 전자 메일 데이터를 관리 하는 데 사용할 수 있는 메시징 정책 및 규정 준수 기능을 제공 합니다.
ms.openlocfilehash: 9ebfdae60eac6e646b3c1b64b13f3cbcb6612b0c
ms.sourcegitcommit: 7a68dc894dde0d06fab014c56914a78aa8cda847
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/21/2020
ms.locfileid: "43640166"
---
# <a name="messaging-policy-and-compliance"></a>메시징 정책 및 규정 준수

Microsoft EOP (Exchange Online Protection)에서는 전자 메일 데이터를 관리 하는 데 사용할 수 있는 메시징 정책 및 규정 준수 기능을 제공 합니다.

모든 EOP 기능에 대 한 정보를 찾으십니까? [Exchange Online Protection 서비스 설명을](exchange-online-protection-service-description.md)참조 하세요.

## <a name="mail-flow-rules"></a>메일 흐름 규칙

메일 흐름 규칙 (전송 규칙이 라고도 함)을 사용 하면 고유한 회사 관련 정책을 전자 메일에 적용할 수 있습니다. 메일 흐름 규칙은 조건에 따라 수행할 조건, 예외 및 작업을 정의 하는 데 사용할 수 있는 다양 한 기준으로 구성 됩니다. 자세한 내용은 [Exchange Online Protection의 메일 흐름 규칙 (전송 규칙)](https://docs.microsoft.com/microsoft-365/security/office-365-security/mail-flow-rules-transport-rules-0)을 참조 하세요.

## <a name="audit-logging"></a>감사 로깅

감사 로깅을 통해 관리자가 조직에 수행한 특정 변경 내용을 추적할 수 있습니다. 이러한 보고서를 사용하면 규정, 준수 및 소송 요구 사항을 충족하는 데 도움을 받을 수 있습니다. 자세한 내용은 [EOP의 감사 보고서](https://docs.microsoft.com/microsoft-365/security/office-365-security/auditing-reports-in-eop)를 참조하세요.

## <a name="data-loss-prevention-dlp"></a>DLP(데이터 손실 방지)

EOP 독립 실행형 고객에게는 제공되지 않습니다. DLP(데이터 손실 방지)는 콘텐츠를 심층 분석하여 조직에 중요한 정보를 식별, 모니터링하고 보호하는 데 도움을 줍니다. 업무상 중요한 전자 메일에는 보호해야 할 중요한 데이터가 포함되어 있으므로, 엔터프라이즈 메시지 시스템에서 DLP의 중요성이 갈수록 높아지고 있습니다. DLP 기능을 사용 하면 작업자 생산성에 영향을 주지 않고 중요 한 데이터를 보호할 수 있습니다.

EAC에서 DLP 정책을 구성하면 다음과 같은 작업이 가능합니다.

- PCI-DSS 데이터, 금융서비스 현대화법(Gramm-Leach-Bliley Act) 데이터 같이 특정 형식의 중요한 정보 또는 또는 로캘별 PII(개인 식별 정보)를 검색하는 데 도움을 받을 수 있는, 미리 구성된 정책 템플릿으로 시작합니다.

- 기존 메일 흐름 규칙 조건 및 작업의 전체 기능을 사용 하 고 새 메일 흐름 규칙을 추가 합니다.

- DLP 정책의 효율성을 테스트한 후에 완전히 적용합니다.

- 자신의 사용자 지정 DLP 정책 템플릿과 중요한 정보 형식을 통합합니다.

- 메시지 첨부 파일, 본문 텍스트 또는 제목 줄에서 중요한 정보를 검색하고, 서비스에서 작업을 수행하는 신뢰 수준을 조정합니다.

- 문서 지문을 사용하여 중요한 양식 데이터를 감지합니다. 문서 지문을에서는 메일 흐름 규칙 및 DLP 정책을 정의 하는 데 사용할 수 있는 텍스트 기반 양식을 기반으로 사용자 지정 중요 한 정보 유형을 쉽게 만드는 데 도움이 됩니다.

- Outlook 2013, 웹용 Outlook 및 장치용 OWA에 알림을 표시 하 여 데이터 손실을 줄이는 데 도움이 되는 정책 팁을 추가 하 고 가양성 보고를 허용 하 여 정책의 효율성을 향상 시킬 수 있습니다.

- DLP 보고서의 문제 데이터를 검토하거나, 문제 보고서 생성 작업을 사용하여 자체 보고서를 추가합니다.

> [!NOTE]
> DLP 정책은 조직을 드나드는 메일에만 적용됩니다. DLP 온-프레미스가 포함된 Exchange Server 2013을 실행하는 경우 외에는 조직 내(내부) 메일에 DLP 정책이 적용되지 않습니다. 이는 중요한 데이터를 권한이 없는 받는 사람에게 실수로 보내기 전에 정책 위반 가능성을 사용자에게 알려주는 DLP 정책 팁의 경우에도 마찬가지입니다.

DLP에 대 한 자세한 내용은 [Exchange Online의 데이터 손실 방지](https://docs.microsoft.com/exchange/security-and-compliance/data-loss-prevention/data-loss-prevention)를 참조 하세요.

## <a name="office-365-message-encryption"></a>Office 365 메시지 암호화

Office 365 메시지 암호화는 Azure Information Protection의 일부로, 전자 메일 사용자가 모든 사용자에 게 암호화 된 전자 메일 메시지를 보낼 수 있도록 하는 온라인 서비스입니다. 온-프레미스 고객은 Azure Information Protection을 구입 하 고 Exchange Online Protection을 사용 하 여 Exchange Online을 통한 메일 흐름을 설정 하 여 Office 365 메시지 암호화에 액세스할 수 있습니다. Exchange Online의 Office 365 메시지 암호화에 대 한 자세한 내용은 Exchange Online 서비스 설명의 [office 365 메시지 암호화](../exchange-online-service-description/message-policy-and-compliance.md#office-365-message-encryption) 를 참조 하세요.

## <a name="messaging-policy-and-compliance-features-across-eop-options"></a>EOP 옵션별 메시징 정책 및 규정 준수 기능

|**기능**|**EOP 독립 실행형**|**Exchange Online의 <br/> EOP 기능**|**Exchange Enterprise <br/> CAL (서비스 포함)**|
|:-----|:-----|:-----|:-----|
|메일 흐름 규칙|예<sup>1</sup>|예<sup>1</sup>|예<sup>1, 3</sup>|
|감사 로깅|예<sup>2</sup>|예|예|
|DLP(데이터 손실 방지)|아니요|있음|예<sup>3</sup>|
|Office 365 메시지 암호화|예<sup>4</sup>|예|예<sup>4</sup>|

> [!NOTE]
> <sup>1</sup> EOP와 Exchange Online의 사용 가능한 메일 흐름 규칙 조건, 예외 및 작업은 약간씩 다릅니다. Exchange online의 메일 [흐름 규칙 조건 및 예외 (조건자)](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/conditions-and-exceptions) 에서는 exchange online의 메일 흐름 [규칙 동작](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/mail-flow-rule-actions)에 나와 있습니다. <br/>
> <sup>2</sup> EOP 감사 보고서는 사서함에 대한 정보가 제외된, Exchange Online 감사 보고서의 하위 집합입니다. <br/>
> <sup>3</sup> Exchange Enterprise CAL with Services 고객은 DLP 정책 팁을 사용할 수 없습니다. <br/>
> <sup>4</sup> Azure Information Protection 추가 기능을 구입 하 고 Exchange online Protection을 사용 하 여 exchange online을 통해 전자 메일을 라우팅하는 온-프레미스 고객에 게 지원 됩니다. 데스크톱 환경에서 Azure Information Protection 추가 기능 외에도, 엔터프라이즈 용 Microsoft 365 앱을 구입 해야 합니다. <br/>
