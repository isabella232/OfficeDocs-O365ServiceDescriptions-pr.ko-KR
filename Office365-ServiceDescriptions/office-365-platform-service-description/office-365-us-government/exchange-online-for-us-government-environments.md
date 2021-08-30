---
title: Exchange Online 미국 정부 환경용 데이터
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 이 문서에서는 서비스 설명에 나열된 미국 정부 클라우드와 상업용 클라우드 간의 기능 Exchange Online 제공합니다.
ms.openlocfilehash: caae2f98eb21bc640be33044448ce94746b3a449
ms.sourcegitcommit: e3b492f18443921ed33776b2db51b888bd3bc230
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/30/2021
ms.locfileid: "58702310"
---
# <a name="exchange-online-for-us-government-environments"></a>Exchange Online 미국 정부 환경용 데이터

이 문서에서는 서비스 설명 에 나열된 미국 정부 클라우드와 상업용 클라우드 간의 기능 Exchange Online [제공합니다.](../../exchange-online-service-description/exchange-online-service-description.md) Exchange Online(정부 커뮤니티 클라우드), GCC GCC High 및 DoD(국방부) 환경에서 사용할 수 있습니다.

자격 및 구매를 비롯한 정부 클라우드에 대한 자세한 내용은 Microsoft 365 정부 - 구입 [방법을 참조하세요.](./microsoft-365-government-how-to-buy.md) 요금제와 Office 365 Government 요금제 [비교는 Office 365 Government 참조합니다.](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements)

네트워크 연결을 관리할 때 필요한 끝점에 대한 자세한 내용은 Office 365 [U.S. Government GCC High endpoints](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) or [Office 365 U.S. Government DoD endpoints를](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business)참조합니다.

조직은 조직의 기능과 기능을 Office 365 미국 정부 클라우드 환경에 고유한 다음과 같은 기능을 활용합니다.

- 조직의 고객 콘텐츠는 상업용 서비스에서 고객 콘텐츠와 논리적으로 Office 365 있습니다.

- 조직의 고객 콘텐츠는 미국 내 휴지 상태의 위치에 저장됩니다.

- 조직 고객 콘텐츠에 대한 액세스는 선별된 Microsoft 직원으로 제한됩니다.

- 정부 클라우드 환경은 미국 공공 부문 고객에게 필요한 인증 및 인증을 준수합니다.

이는 모든 상업용 Exchange 기능을 정부 클라우드 환경에 제공하는 것이 일반적인 의도입니다. 즉, 정부 클라우드 고객의 요구 사항 때문에 일부 기능을 사용할 수 없습니다. 다른 기능은 정부 환경에 제공될 예정이지만 아직 사용할 수 없습니다. 다음 섹션을 참조하여 정부 클라우드 환경의 기능 가용성에 대해 자세히 알아보십시오.

## <a name="exchange-online-features"></a>Exchange Online 기능 

다음 표에서는 지정된 Exchange Online 기능의 사용 가능 여부에 대해 간략하게 설명하고 GCC, GCC 및 DoD 환경에서 사용할 수 있는지 여부를 간략하게 설명하고 있습니다. 지원 설명(또는 지원 설명이 부족)에 관한 미미한 뉘앙스가 있는 경우 추가 컨텍스트가 제공됩니다.<br><br>

| 기능 | GCC | GCC 높음 | DoD | 주요 고려 사항 |
|:-----|:-----|:-----|:-----|:-----|
|**[계획 및 배포](../../exchange-online-service-description/planning-and-deployment.md)**|||||
|하이브리드 배포 지원|예|예|예|Exchange Server 함께 사용하려면 Microsoft는 하나 이상의 Exchange Server 2013 클라이언트 액세스 서버(또는 Exchange Server 2016)를 설치해야 합니다. Exchange Server 2010 이전 버전은 지원되지 않습니다.|
|IMAP 마이그레이션 지원|예|예|예||
|지원되는 단독형 마이그레이션|예|예|예||
|미리 구성된 마이그레이션 지원|예|예|예|High 및 DoD에 대해 GSuite GCC 지원되지 않습니다. 자세한 내용은 <a href="/exchange/mailbox-migration/perform-g-suite-migration">Perform a GSuite migration을 참조하십시오.</a>|
|**[사용 권한](../../exchange-online-service-description/permissions.md)**|**GCC**|**GCC High**|**DoD**|**주요 고려 사항**|
|역할 기반 사용 권한|예|예|예||
|역할 그룹|예|예|예||
|역할 할당 정책|예|예|예||
|**[메시지 정책 및 규정 준수](../../exchange-online-service-description/message-policy-and-compliance.md)**|**GCC**|**GCC High**|**DoD**|**주요 고려 사항**|
|Exchange Online 기반 사서함 보관|예|예|예||
|온-프레미스 사서함의 클라우드 기반 보관|예|예|예||
|MRM(메시징 레코드 관리) |예|예|예||
|수동 보존 정책, 레이블 및 태그 |예|예|예||
|보관된 데이터 암호화(BitLocker)|예|예|예||
|Azure Information Protection을 사용한 IRM|예|예|예|High 및 DoD의 AIP 제한에 대한 자세한 GCC Azure Information Protection Premium Government 서비스 설명을 <a href="/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description">참조하세요.</a><br><br>Azure Information Protection은 G1/F3에 포함되어 있지 않지만 별도의 추가 기능으로 구입할 수 있으며 지원되는 IRM(정보 권한 관리) 기능을 사용하도록 설정할 수 있습니다. 일부 Azure Information Protection 기능을 사용하려면 F3 또는 Office 365 ProPlus 포함되어 있지 않은 구독이 Office 365 Government G1 Office 365 Government 있습니다.|
|Windows Server AD RMS를 사용한 IRM|예|예|예|Windows Server AD RMS는 지원되는 IRM 기능을 사용하려면 별도로 구입 및 관리해야 하는 사내 서버입니다.|
|Office 365 메시지 암호화|예|예|예|이 문서의 Office 365 메시지 암호화 [High/DoD](#office-365-message-encryptionbehavior-across-gcc-highdod-boundary) 경계에 대한 Office 365 메시지 암호화 GCC 동작 및 Office 365 메시지 암호화 GCC High/Do GCC D 사용자 간에 메시지를 보낼 때 Office 365 메시지 암호화 동작의 미미를 문서화하는 Office 365 메시지 암호화 <a href="/microsoft-365/compliance/ome-version-comparison#unique-characteristics-of-office-365-message-encryption-in-a-gcc-high-deployment">GCC</a>High/DoD의 고유한 특성을 참조하세요.|
|고객 키|예|예|예|G5 서비스 계획이 필요합니다.|
|S/MIME|예|예|예||
|원본 위치 유지 및 소송 보존|예|예|예|G3 또는 G5 서비스 플랜이 필요합니다.|
|원본 위치 eDiscovery|예|예|예||
|메일 흐름 규칙|예|예|예||
|데이터 손실 방지|예|예|예|G3 또는 G5 서비스 플랜이 필요합니다.|
|저널링|예|예|예||
|**[스팸 방지 및 맬웨어 방지 보호](../../exchange-online-service-description/anti-spam-and-anti-malware-protection.md)**|**GCC**|**GCC High**|**DoD**|**주요 고려 사항**|
|기본 제공 스팸 방지 보호 기능|예|예|예||
|Customize anti-spam policies|예|예|예||
|기본 제공 맬웨어 방지 보호 기능|예|예|예||
|Customize anti-malware policies|예|예|예||
|격리 - 관리자 관리|예|예|예||
|격리 - 최종 사용자 자기 관리|예|예|예||
|Office 365용 Microsoft Defender|예|예|예|G5 서비스 계획(또는 추가 기능 구매)이 필요합니다.<br><br>사용자 및 도메인 가장 및 스푸핑 인텔리전스에 대한 피싱 방지는 High 및 DoD에서 GCC 없습니다.|
|**[메일 흐름](../../exchange-online-service-description/mail-flow.md)**|**GCC**|**GCC High**|**DoD**|**주요 고려 사항**|
|아웃바운드 메일의 사용자 지정 라우팅|예|예|예||
|Secure messaging with a trusted partner|예|예|예||
|Conditional mail routing|예|예|예||
|인바운드 안전한 목록에 파트너 추가|예|예|예||
|하이브리드 전자 메일 라우팅|예|예|예||
|**[받는 사람](../../exchange-online-service-description/recipients.md)**|**GCC**|**GCC High**|**DoD**|**주요 고려 사항**|
|용량 경고|예|예|예||
|Clutter|예|예|예||
|메일 설명|예|예|예||
|위임 액세스|예|예|예||
|받은 편지함 규칙|예|예|예||
|연결된 계정|예|아니요|아니요|이 기능은 타사 서비스에 대한 아웃바운드 GCC 때문에 High 또는 DoD에서 지원되지 않습니다. 영향을 미치는 기능에 대한 자세한 내용은 이 문서의 타사 서비스와의 [연결을](#connectivity-with-third-party-services) 참조하세요.|
|비활성 사서함|예|예|예|G3 또는 G5 서비스 플랜이 필요합니다.|
|오프라인 주소록|예|예|예||
|주소록 정책|예|예|예||
|계층적 주소부|예|예|예||
|주소 목록 및 전체 주소 목록|예|예|예||
|Office 365 그룹|예|예|예|고급 및 Office 365 환경에서는 GCC 그룹에 대한 게스트 액세스가 지원되지 않습니다. 자세한 내용은 <a href="/azure/azure-government/documentation-government-services-securityandidentity">Azure Government Security + Identity를 참조하세요.</a>|
|메일 그룹|예|예|예||
|외부 연락처(전체)|예|예|예|High 및 DoD 환경에서는 GCC 관계 공동 작업 제한이 적용될 수 있습니다. |
|소셜 네트워크와의 연락처 연결|예|아니요|아니요|이 기능은 High 또는 DoD에서 GCC 지원되지 않습니다.|
|리소스 사서함|예|예|예||
|회의실 관리|예|예|예||
|부재 중 회신|예|예|예||
|인터넷 일정 공유|예|아니요|아니요|GCC 높음에서 인터넷 일정 게시/공유는 GCC High 사용자가 공유하는 일정에 대한 인바운드 연결에 사용할 수 있지만 GCC High 외부의 공유 일정에 아웃바운드를 연결하는 GCC 없습니다.<br><br>DoD-Internet 일정 공유는 해당 환경의 인바운드/아웃바운드 연결 허용 목록에 대한 요구 사항으로 인해 지원되지 않습니다.|
|**[보고 기능 및 문제 해결 도구](../../exchange-online-service-description/reporting-features-and-troubleshooting-tools.md)**|**GCC**|**GCC High**|**DoD**|**주요 고려 사항**|
|Microsoft 365 관리 센터 보고서|예|예|아니요|DoD에 사용할 수 없는 보고서입니다. 업데이트/현재 <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features"></a> 가용성에 대한 Office 365 미국 정부 서비스 설명의 플랫폼 기능 섹션을 참조하세요.|
|웹 서비스 보고서|예|예|아니요|DoD에 사용할 수 없는 보고서입니다. 업데이트/현재 <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features"></a> 가용성에 대한 Office 365 미국 정부 서비스 설명의 플랫폼 기능 섹션을 참조하세요.|
|Message trace|예|예|예||
|감사 보고서|예|예|아니요|DoD에 사용할 수 없는 보고서입니다. 업데이트/현재 <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features"></a> 가용성에 대한 Office 365 미국 정부 서비스 설명의 플랫폼 기능 섹션을 참조하세요.|
|통합 메시징 보고서|예|아니요|아니요||
|**[공유 및 공동 작업](../../exchange-online-service-description/sharing-and-collaboration.md)**|**GCC**|**GCC High**|**DoD**|**주요 고려 사항**|
|페더링 공유(일정 게시 포함)|예|예|예|High 및 DoD에는 GCC 제한이 있습니다. 이 문서의 사용 [중/사용 중 페더ation을](#freebusy-federation) 참조하세요.|
|사이트 사서함|예|예|예||
|공용 폴더|예|예|예||
|**[클라이언트 및 모바일 장치](../../exchange-online-service-description/clients-and-mobile-devices.md)**|**GCC**|**GCC High**|**DoD**|**주요 고려 사항**|
|To Do 웹에서 사용|예|아니요|아니요||
|Windows용 Outlook|예|예|예|높은 GCC DoD 규정 준수 요구 사항을 충족하려면 최소 1803 버전의 1803 이상을 실행하고 Office 365 ProPlus. Office 365 ProPlus G1 또는 F3에 포함되어 있지 않습니다.|
|웹용 Outlook<sup>1</sup>|예|예|예||
|Outlook for Mac|예|예|예|높은 GCC DoD 규정 준수 요구 사항을 충족하려면 최소 1803 버전의 1803 이상을 실행하고 Office 365 ProPlus. Office 365 ProPlus G1 또는 F3에 포함되어 있지 않습니다.|
|iOS 및 Android용 Outlook|예|예|예||
|Exchange ActiveSync|예|예|예||
|기본 모바일 및 보안 for Microsoft 365|예|아니요|아니요||
|POP 및 IMAP|예|예|예||
|SMTP|예|예|예||
|EWS 응용 프로그램 지원|예|예|예||
|**[음성 메시지 서비스](../../exchange-online-service-description/voice-message-services.md)**|**GCC**|**GCC High**|**DoD**|**주요 고려 사항**|
|음성 사서함|아니요|아니요|아니요|통합 메시징과의 Exchange Online IP-PBX 시스템 통합은 지원되지 않습니다.|
|음성 메일과 타사 팩스 간의 통합|아니요|아니요|아니요|통합 메시징과의 Exchange Online IP-PBX 시스템 통합은 지원되지 않습니다.|
|타사 음성 사서함 상호 운용성|아니요|아니요|아니요|통합 메시징과의 Exchange Online IP-PBX 시스템 통합은 지원되지 않습니다.|
|비즈니스용 Skype 통합|예|예|예||
|**[고가용성 및 비즈니스 연속성](../../exchange-online-service-description/high-availability-and-business-continuity.md)**|**GCC**|**GCC High**|**DoD**|**주요 고려 사항**|
|데이터 센터에서 사서함 복제|예|예|예||
|삭제된 사서함 복구|예|예|예||
|삭제된 항목 복구|예|예|예||
|단일 항목 복구|예|예|예||
|**[상호 운용성, 연결 및 호환성](../../exchange-online-service-description/interoperability-connectivity-and-compatibility.md)**|**GCC**|**GCC High**|**DoD**|**주요 고려 사항**|
|OWA 및 Outlook|예|예|예||
|SharePoint 상호 연산|예|예|예||
|EWS 연결 지원|예|예|예||
|SMTP 릴레이 지원|예|예|예||
|**[Exchange Online 설치 및 관리](../../exchange-online-service-description/exchange-online-setup-and-administration.md)**|**GCC**|**GCC High**|**DoD**|**주요 고려 사항**|
|Microsoft Office 365 포털 액세스|예|예|아니요|DoD에 사용할 수 없는 보고서입니다. 업데이트/현재 <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features"></a> 가용성에 대한 Office 365 미국 정부 서비스 설명의 플랫폼 기능 섹션을 참조하세요.|
|Microsoft 365 관리 센터 액세스|예|예|아니요|DoD에 사용할 수 없는 보고서입니다. 업데이트/현재 <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features"></a> 가용성에 대한 Office 365 미국 정부 서비스 설명의 플랫폼 기능 섹션을 참조하세요.|
|Exchange 관리 센터 액세스|예|예|예||
|원격 Windows PowerShell 액세스|예|예|예||
|모바일 장치에 대한 ActiveSync 정책|예|예|예||
|사용 현황 보고|예|예|아니요|DoD에 사용할 수 없는 보고서입니다. 업데이트/현재 <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features"></a> 가용성에 대한 Office 365 미국 정부 서비스 설명의 플랫폼 기능 섹션을 참조하세요.|
|**[서비스 확장 - 사용자 지정, 추가 기능 및 리소스](../../exchange-online-service-description/exchange-online-service-description.md)**|**GCC**|**GCC High**|**DoD**|**주요 고려 사항**|
|Outlook 추가 기능 및 MAPI Outlook 추가 기능|예|예|예|일부 OWA 및 Outlook 추가 기능만 High 및 DoD에서 GCC 있습니다. 이 [문서의 추가](#add-insin-outlook-and-outlook-web-app) Outlook Outlook Web App 참조하세요.|

<sup>1</sup> Outlook 경계 제한(높음/비영구)으로 인해 Outlook Windows IRM으로 보호된 메시지를 표시할 수 없는 시나리오에서는 웹에서 사용할 수 있습니다(GCC 높음/비이용성 GCC).

## <a name="feature-nuances-within-gcc-high-and-dod-environments"></a>High 및 DoD 환경 GCC 기능의 미정

### <a name="connectivity-with-third-party-services"></a>타사 서비스와의 연결  

높은 GCC DoD 환경은 모두 아웃바운드 연결의 명시적 승인 및 구성이 필요한 제한된 환경입니다. 또한 Microsoft는 이러한 환경에서 상업용 클라우드 서비스(상업용 클라우드 서비스Office 365 Google GSuite, Amazon Web Services 등)로의 아웃바운드 액세스를 허용하는 요청을 수용할 수 없습니다.

이러한 제한으로 인해 다음과 같은 GCC High/DoD 환경에서 이 아웃바운드 연결을 적용하는 기능은 일반적으로 지원되지 않습니다.

- 연결된 계정 - 사용자가 계정(Google, POP/IMAP 등)을 추가/동기화할 수 없습니다.

- 타사 파일 저장소 공급자 지원 - 파일 첨부/공유를 위해 다양한 Outlook GCC 클라이언트 내에서 비즈니스용 OneDrive *High/DoD* 내의 사용자 Outlook 계정에 액세스할 수 있습니다. 타사 저장소 계정(Dropbox, Box, Google 드라이브)을 추가할 수 없습니다.

- Facebook 또는 LinkedIn과 같은 소셜 네트워크와의 연결

### <a name="azure-active-directory-b2b-collaboration"></a>Azure Active Directory B2B 공동 작업

Azure Active Directory B2B 공동 작업은 현재 Azure 미국 정부 클라우드 내에 있으며 B2B 공동 작업을 모두 지원하는 조직 간에만 지원됩니다.

또한 고급 및 DoD 환경에서는 Office 365 B2B 사용자가 GCC 지원되지 않습니다. 

자세한 정보 및 최신 업데이트는 [Azure Government Security + Identity 를 참조하세요.](/azure/azure-government/documentation-government-services-securityandidentity)

### <a name="office-365-message-encryption-behavior-across-gcc-highdod-boundary"></a>Office 365 메시지 암호화/DoD 경계에서 GCC 동작

높은 환경에서 Office 365 메시지 암호화 사용 GCC 받는 사람 환경에 대한 고유한 특성을 알고 있어야 합니다.  

- 동일한 환경의 받는 사람에게 GCC High 또는 DoD에서 암호화된 전자 메일을 보내는 경우:
    
    - 보낸 사람이 PC 및 Mac 및 Outlook 및 웹용 Outlook 메일 흐름 규칙을 사용하여 전자 메일을 암호화하는 정책을 Exchange 수 있습니다.
    
    - 고급/GCC 내 받는 사람은 PC 및 Mac용 Outlook 및 웹용 Outlook 사용자와 동일한 인라인 읽기 Office 365 받게 됩니다.

<!-- end list -->

- DoD, GCC 및 Commercial을 포함하여 암호화된 전자 메일을 이 환경 외부의 받는 사람에게 GCC 경우:

    - High 내부의 GCC 높은 경계 외부로 암호화된 전자 메일을 GCC 수 있습니다.
    - DoD GCC 상용 Office 365 사용자, Outlook.com 사용자 및 기타 전자 메일 공급자의 기타 사용자를 비롯한 높음 외부의 모든 받는 사람은 래퍼 메일을 받게 됩니다. 이 래퍼 메일은 받는 사람이 메시지를 읽고 회신할 수 있는 OME 포털로 받는 사람을 리디렉션합니다.

자세한 내용은 OME 버전 [비교를 참조하세요.](/microsoft-365/compliance/ome-version-comparison)

### <a name="freebusy-federation"></a>사용/사용 중 페더ation

현재 DoD 환경에서는 무료/사용 중인 정보를 포함한 페더링 공유에 몇 가지 중요한 제한 사항이 있습니다.

고급 GCC 환경:

- GCC High 내의 테넌트, GCC 및 상업용 클라우드의 테넌트, 하이브리드 공존성(Exchange 2013 이상)을 통해 페더링 트러스트(양방향 사용 가능/사용 중 공유 포함)가 지원됩니다.

DoD 환경에서는 다음을 할 수 있습니다.

  - 현재는 DoD 환경 내의 테넌트 간에만 페더링 트러스트(무료/사용 중 공유 포함)가 지원됩니다. DoD 테넌트와 높은 테넌트, GCC, GCC 테넌트 간에 지원되지 않습니다.

### <a name="client-configuration"></a>클라이언트 구성

추가 단계는 ProPlus를 배포하고 구성하는 Office(추가 Outlook). 이러한 단계에 대한 자세한 내용은 High 또는 DoD 환경에서 엔터프라이즈용 Microsoft 365 앱 배포하기 위한 GCC [지침을 참조하세요.](/deployoffice/deploy-microsoft-365-apps-gcc-high-dod)

Outlook 및 DoD 환경에서는 iOS 및 Android용 GCC 사용할 수 있습니다. 이러한 환경의 기능 제한 사항 및 관리에 대한 자세한 내용은 Outlook iOS 및 [Android용](/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud)정부 커뮤니티 클라우드.

### <a name="add-ins-in-outlook-and-outlook-web-app"></a>추가 기능 및 Outlook 추가 Outlook Web App  

일부 OWA 및 Outlook 추가 기능만 High 및 DoD에서 GCC 있습니다. 내 서식 파일 및 제안된 모임을 사용할 수 있으며 작동할 것으로 예상됩니다. 5개의 기본 OWA 추가 기능만 지원됩니다. 타사 응용 프로그램과의 통합은 가능하나 이러한 통합은 High 또는 DoD에 대한 Microsoft 규정 GCC 적용되지 않습니다. 고객은 조직에 대한 추가 기능을 구성하기 전에 타사 데이터 처리 관행 및 규정 준수 약속을 잘 알고 있습니다.

## <a name="feature-nuances-within-gcc-environments-for-microsoft-to-do"></a>GCC 환경 내의 기능 Microsoft To Do

| 기능 | 설명 | WW | 2016년 GCC |
|:-----|:-----|:-----|:-----|
|지원되는 플랫폼|웹, Android, iOS, Mac, Windows|모두|웹만|
|M365 허브 지원|Planner, Outlook, Teams 통합|모두|Outlook Planner(Teams 작업 앱에서 사용할 Teams 수 있습니다.|
|Wunderlist 마이그레이션|wunderlist 사용자가 웹에서 데이터를 To Do 수 있도록 허용|예|아니요|
|푸시 알림|미리 알림 등을 위해 최종 사용자에게 푸시 알림을 전송합니다.|예|아니요|
|도움말 기술 지원|도움말 표시 인터페이스를 사용하여 지원 요청 만들기|예|아니요|
|My Day|하루 계획|예|예|
|계획된 목록|기한이 있는 모든 작업 보기|예|예|
|사용자 목록에 할당|공유 목록, Planner 또는 WXP(미래)에서 할당된 모든 작업|예|예|
|플래그가 지정한 전자 메일|Outlook에서 작업으로 플래그가 지정된 전자 메일 보기|예|예|
|다중 계정 지원|한 창에서 홈 및 사무실 계정 사용|예|예|
|목록 공유|같은 조직의 동료와 목록 공유|예|예|
|크로스 테넌트 공유|조직 외부의 작업 목록 공유|예|아니요|
|미리 알림 및 재발|작업에 대한 미리 알림 설정 |예|예|

*언급되지 않은 다른 기능은 두 환경에서 모두 사용할 수 있습니다.