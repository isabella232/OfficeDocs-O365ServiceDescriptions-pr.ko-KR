---
title: Exchange Online Protection 서비스 설명
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c9127cb4-689c-43b0-b224-a44ebf4374c8
description: Exchange Online Protection의 기능 및 요구 사항에 대해 알아봅니다. 포함된 계획 목록은 Exchange Online Protection 계획의 기능 비교를 제공합니다.
ms.openlocfilehash: 2a7f5bd6c2750d4ce5d348e7fc8438a335533a46466fccc16318a133e1639e4e
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/06/2021
ms.locfileid: "54664231"
---
# <a name="exchange-online-protection-service-description"></a>Exchange Online Protection 서비스 설명

Exchange Online Protection의 기능 및 요구 사항에 대해 알아봅니다. 포함된 계획 목록은 Exchange Online Protection 계획의 기능 비교를 제공합니다.

Microsoft Exchange Online EOP(보호)는 스팸 및 맬웨어로부터 조직을 보호하는 클라우드 기반 전자 메일 필터링 서비스로, 메시징 정책 위반으로부터 조직을 보호하는 기능을 포함합니다. EOP를 사용하면 메시징 환경을 쉽게 관리하고 온 - 프레미스 하드웨어  및 소프트웨어 유지 관리 시의 부담을 대부분 완화할 수 있습니다.

다음 목록에서는 메시징 보호를 위해 EOP를 사용할 수 있는 기본 방법에 대해 설명하고 있습니다.

- **독립 실행형** 시나리오: EOP는 클라우드 기반 전자 메일 환경(Exchange Server 또는 기타 사내 SMTP 전자 메일 솔루션)에 대해 클라우드 기반 전자 메일 보호 기능을 제공합니다.

- **다음의 일부로 Microsoft Exchange Online:** 기본적으로 EOP는 클라우드 호스트 Exchange Online 보호합니다. 자세한 내용은 Exchange Online 서비스 [설명을 Exchange Online 참조하세요.](../exchange-online-service-description/exchange-online-service-description.md)

- **하이브리드 배포에서:** EOP를 구성하여 메시징 환경을 보호하고, 전자 메일 라우팅을 제어할 수 있습니다(사내 사서함과 클라우드 사서함이 혼합된 경우).

## <a name="available-plans"></a>사용 가능한 계획

다음 표에는 조직의 요구에 가장 Exchange Online Protection 솔루션을 선택할 수 있도록 이러한 계획에 대한 설명이 포함되어 있습니다. 자세한 계획 정보는 [를](https://products.office.com/exchange/exchange-email-security-spam-protection)Exchange Online Protection.

사용자가 구독을 사용하도록 설정하는 구독에 대한 자세한 Exchange Online Protection 전체 구독 비교 [표를 참조하세요.](https://www.microsoft.com/microsoft-365/compare-microsoft-365-enterprise-plans)

### <a name="exchange-enterprise-cal-with-services-features"></a>Exchange Enterprise CAL with Services 기능

Microsoft Exchange Enterprise CAL with Services는 EOP의 전자 메일 보호 기능과 다음과 같은 추가 클라우드 기반 기능을 제공합니다.

- [데이터 손실 방지](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)

- [웹 서비스를 사용하여 보고](reporting-and-message-trace.md#reporting-using-web-services)

서비스 라이선스가 있는 EXCHANGE ENTERPRISE 대한 자세한 내용은 Exchange [FAQ를 참조하세요.](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business)

CAL with Services Exchange Enterprise 있는 경우 EOP를 프로비전하려는 경우 EOP 서비스 설정의 [지침을 따릅니다.](/microsoft-365/security/office-365-security/set-up-your-eop-service) 설정 단계는 EOP 독립 실행형 설정 단계와 동일합니다.

> [!NOTE]
> Exchange Enterprise CAL with Services의 새 기능은 EOP 독립 실행형이 아닌 Exchange Online과 같은 시기에 배포됩니다. EOP 독립 실행형과 Exchange Online/Exchange Enterprise CAL with Services의 배포 일정은 약간 다를 수도 있습니다.

## <a name="requirements-for-exchange-online-protection-eop"></a>EOP(Exchange Online Protection)에 대한 요구 사항

EOP는 SMTP 메일 전송 에이전트와 함께 사용할 수 Microsoft Exchange Server. EOP에서 지원하는 운영 체제, 웹 브라우저 및 언어에 대한 자세한 내용은 Exchange 관리 센터의 "지원되는 브라우저" 및 "지원되는 언어" [섹션을 Exchange Online Protection.](/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop)

## <a name="limits"></a>제한

EOP의 제한은 제한 [Exchange Online Protection 참조합니다.](exchange-online-protection-limits.md)

## <a name="feature-availability"></a>기능 가용성

다음 표에는 계획에서 사용할 Exchange Online Protection 주요 기능 목록이 나열되어 있습니다. 특정 경고가 적용됩니다. 자세한 내용은 각주를 참조하세요. 이 표는 통지 없이 변경될 수 있습니다. 최신의 전체 기능 목록은 엔터프라이즈를 지원하는 강력한 도구를 [참조하세요.](https://products.office.com/business/compare-more-office-365-for-business-plans)

| 기능 | 독립 실행형 EOP | EE CAL w/ 서비스의 EOP | Exchange Online의 EOP 기능 |
|:-----|:-----|:-----|:-----|
|**보호**||||
|맬웨어 방지 정책(기본 제공 및 사용자 지정)|예|예|예|
|인바운드 스팸 방지 정책(기본 제공 및 사용자 지정)|예|예|예|
|아웃바운드 스팸 방지 정책(기본 제공 및 사용자 지정)|예|예|예|
|연결 필터링(IP 허용 목록 및 IP 차단 목록)|예|예|예|
|피싱 방지 정책(기본 제공 및 사용자 지정)|예|예|예|
|스푸핑 방지 보호(기본 제공 및 사용자 지정)|예|예|예|
|배달된 맬웨어, 스팸 및 피싱 메시지에 대한 ZAP(제로 아워 자동<sup>제거) 10</sup>|아니요|아니요|예|
|보안 정책 미리조정|예|예|예|
|보호 정책에 대한 구성 분석기|예|예|예|
|테넌트 허용/차단 목록|예|예|예|
|메시지 보낸 사람에 대한 차단 목록|예|예|예|
|메시지 보낸 사람에 대한 목록 허용|예|예|예|
|Edge 차단|예|예|예|
|없는 받는 사람에 대한 DBEB(디렉터리 기반 Edge 차단)|예|예|예|
|**Quarantine and submissions**||||
|관리자 제출<sup>10</sup>|아니요|아니요|예|
|사용자 제출(사용자 지정 사서함)<sup>10</sup>|아니요|아니요|예|
|관리자 검란|예|예|예|
|최종 사용자 검지|예|예|예|
|보고서 메시지 추가 기능 및 보고서 피싱 추가 Outlook|예|예|예|
|**메일 흐름**||||
|메일 흐름 규칙(전송 규칙)<sup>4</sup>|예|예<sup>6</sup>|예|
|허용 도메인<sup>3</sup> |예|예|예|
|커넥터|예|예|예|
|커넥터에 대한 향상된 필터링(목록 건너뛰기)|예|예|예|
|**모니터링**||||
|Message trace|예|예|예|
|전자 메일 및 보안 보고서의 Microsoft 365 관리 센터|예<sup>7</sup>|예<sup>7,8</sup>|예<sup>8</sup>|
|보안 센터의 Microsoft 365 보고서|예<sup>7</sup>|예<sup>7,8</sup>|예<sup>8</sup>|
|EAC의 전자 메일 보고서|예<sup>7</sup>|예<sup>7,8</sup>|예<sup>8</sup>|
|관리자 감사 로깅<sup>5</sup>|예|예|예|
|**사용자**||||
|메일 사용자 및 메일 연락처<sup>1</sup>|예|예|예|
|사서함|아니요|아니요|예<sup>1a</sup>|
|RBAC(역할 기반 액세스 제어)<sup>2</sup>|예|예|예|
|**규정 준수**||||
|전자 메일에 대한 데이터 손실 방지|아니요|예|예|
|Office 365 메시지 암호화|아니요<sup>9</sup>|아니요<sup>9</sup>|예|
|**관리**||||
|Microsoft 365 관리 센터|예|예|예|
|Exchange 관리 센터|예|예|예|
|Microsoft 365 보안 센터|예|예|예|
|독립 실행형 Exchange Online Protection PowerShell|예|아니요|아니요|
|Exchange Online PowerShell|아니요|예|예|

<sup>1</sup> EAC에서 메일 사용자 및 메일 연락처를 만들고 제거하고 편집합니다. <br/>
<sup>1a</sup> 사서함의 사서함을 만들고 Microsoft 365 관리 센터. EAC에서 기존 사서함을 편집할 수 있습니다. <br/>
<sup>2</sup> 독립 실행형 EOP 및 EE CAL에서는 최종 사용자 역할 또는 역할 할당 정책이 없습니다.<br/>
<sup>3</sup> 새 도메인에서 도메인을 추가하고 Microsoft 365 관리 센터.  EAC에서 도메인을 권한 있는 도메인 또는 권한이 없는 도메인으로 구성합니다.<br/>
<sup>4</sup> 일부 규칙 조건, 예외 및 작업은 독립 실행형 EOP 또는 EE CAL with Services에서 사용할 수 없습니다. 이러한 차이점은 메일 흐름 규칙 Exchange Online 명확하게 설명되어 있습니다. <br/>
<sup>5</sup> 독립 실행형 EOP 및 EE CAL with Services:

- 사서함 감사 보고서를 사용할 수 없습니다.
- 관리자 역할 그룹 보고서 및 관리자 감사 로그 보고서는 EAC에서 유일한 관리자 감사 보고서입니다.
- 감사 로그 내보내기 PowerShell을 통해서만 사용할 수 있습니다. <br/>

<sup>6</sup> DLP 정책 팁은 EE 서비스에서 사용할 수 없습니다. <br/>
<sup>7</sup> 독립 실행형 EOP 및 EE CAL with Services의 보고서는 사서함을 다루는 Exchange Online 보고서의 하위 집합입니다.<br/>
<sup>8</sup> DLP 보고서가 포함됩니다. <br/>
<sup>9</sup> Azure Information Protection을 추가 기능 구독으로 구매하고 EOP를 통해 인터넷으로 전자 메일을 라우팅하도록 OME를 구성하는 경우 OME를 사용할 수 있습니다. <br/>
<sup>10</sup> 이 기능을 사용하려면 Exchange Online 필요합니다. <br/>

## <a name="learn-more"></a>자세한 정보

사용에 대한 기술 Exchange Online Protection 다음 리소스를 참조하십시오.

이 [Microsoft 365](https://office.microsoft.com/products/office-365-roadmap-FX104343353.aspx) 로드맵은 예정된 새 기능에 대한 정보를 찾는 데 좋은 리소스입니다.

### <a name="licensing-terms"></a>사용 조건

Microsoft 상업용 볼륨 라이선싱 프로그램을 통해 구매한 제품 및 서비스에 대한 사용 조건은 [제품 조건 사이트](https://www.microsoft.com/licensing/terms/)를 참조하세요.

### <a name="messaging"></a>메시지

새로운 기능 및 변경된 기능, 계획된 유지 관리 또는 기타 중요한 공지 사항을 포함하여 예정된 변경 내용을 추적하려면 메시지 센터를 방문하세요. 자세한 내용은 [메시지 센터](/microsoft-365/admin/manage/message-center)를 참조하세요.

### <a name="accessibility"></a>접근성

Microsoft는 데이터의 보안과 서비스의 [접근성](https://www.microsoft.com/trust-center/compliance/accessibility)에 최선을 다하고 있습니다. 자세한 내용은 [Microsoft 보안 센터](https://www.microsoft.com/trust-center) 및 [Office 접근성 센터](https://support.office.com/article/ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d)를 참조하세요.
