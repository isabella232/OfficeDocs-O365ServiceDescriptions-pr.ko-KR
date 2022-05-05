---
title: 미국 정부 환경에 대한 Exchange Online
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
description: 이 문서에서는 Exchange Online 서비스 설명에 나열된 미국 정부 클라우드와 상용 클라우드 간의 기능 차이점에 대한 개요를 제공합니다.
ms.openlocfilehash: 5885a10d1018fead185f373d1b24139c4765c410
ms.sourcegitcommit: e4bf187c926340f4afb68bfe51d38b303664ae00
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/05/2022
ms.locfileid: "65218174"
---
# <a name="exchange-online-for-us-government-environments"></a>미국 정부 환경에 대한 Exchange Online

이 문서에서는 [Exchange Online 서비스 설명](../../exchange-online-service-description/exchange-online-service-description.md)에 나열된 미국 정부 클라우드와 상용 클라우드 간의 기능 차이점에 대한 개요를 제공합니다. Exchange Online 정부 커뮤니티 클라우드(GCC), GCC High 및 국방부(DoD) 환경에서 사용할 수 있습니다.

자격 및 구매를 포함한 정부 클라우드에 대한 자세한 내용은 [Microsoft 365 정부 - 구매 방법을](./microsoft-365-government-how-to-buy.md) 참조하세요. Office 365 Government 계획을 비교하려면 [Office 365 Government 계획을](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements) 참조하세요.

네트워크 연결을 관리할 때 필요한 엔드포인트에 대해 알아보려면 [Office 365 미국 정부 GCC 하이 엔드포인트](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) 또는 [Office 365 미국 정부 DoD 엔드포인트](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business)를 참조하세요.

조직은 Office 365 기능과 기능을 즐기는 것 외에도 미국 정부 클라우드 환경에 고유한 다음과 같은 기능을 활용할 수 있습니다.

- 조직의 고객 콘텐츠는 상업적 Office 365 서비스의 고객 콘텐츠와 논리적으로 분리됩니다.

- 조직의 고객 콘텐츠는 미국 내에 저장됩니다.

- 조직 고객 콘텐츠에 대한 액세스는 선별된 Microsoft 직원으로 제한됩니다.

- 정부 클라우드 환경은 종종 미국 공공 부문 고객에게 필요한 인증 및 인증을 준수합니다.

모든 Exchange 상업용 기능 및 기능을 정부 클라우드 환경에 제공하는 것이 일반적인 의도입니다. 즉, 정부 클라우드 고객의 요구 사항 때문에 일부 기능을 사용할 수 없습니다. 다른 기능은 정부 환경에 제공되지만 아직 사용할 수 없습니다. 정부 클라우드 환경의 기능 가용성에 대해 알아보려면 다음 섹션을 참조하세요.

## <a name="exchange-online-features"></a>Exchange Online 기능 

다음 표에서는 GCC, GCC High 및 DoD 환경에서 지정된 Exchange Online 기능을 사용할 수 있는지 여부를 간략하게 설명합니다. 지원 진술(또는 부족)에 대한 뉘앙스가 있는 경우 추가 컨텍스트가 제공됩니다.<br><br>

| 기능 | GCC | GCC 높음 | DoD | 주요 고려 사항 |
|:-----|:-----|:-----|:-----|:-----|
|**[계획 및 배포](/exchange/plan-and-deploy/plan-and-deploy)**|||||
|하이브리드 배포 지원|예|예|예|Exchange Server 온-프레미스와 공존하려면 Microsoft에서 하나 이상의 Exchange Server 2013 클라이언트 액세스 서버(또는 Exchange Server 2016)를 설치해야 합니다. Exchange Server 2010 및 이전 버전이 지원되지 않습니다.|
|IMAP 마이그레이션 지원|예|예|예||
|지원되는 단독형 마이그레이션|예|예|예||
|미리 구성된 마이그레이션 지원|예|예|예|GSuite 마이그레이션은 GCC High 및 DoD에서 지원되지 않습니다. 자세한 내용은 <a href="/exchange/mailbox-migration/perform-g-suite-migration">GSuite 마이그레이션 수행을</a> 참조하세요.|
|**[사용 권한](/exchange/permissions-exo/permissions-exo)**|**GCC**|**GCC High**|**DoD**|**주요 고려 사항**|
|역할 기반 권한|예|예|예||
|역할 그룹|예|예|예||
|역할 할당 정책|예|예|예||
|**[메시지 정책 및 규정 준수](/exchange/policy-and-compliance/policy-and-compliance)**|**GCC**|**GCC High**|**DoD**|**주요 고려 사항**|
|Exchange Online 기반 사서함 보관|예|예|예||
|온-프레미스 사서함의 클라우드 기반 보관|예|예|예||
|MRM(메시징 레코드 관리) |예|예|예||
|수동 보존 정책, 레이블 및 태그 |예|예|예||
|보관된 데이터 암호화(BitLocker)|예|예|예||
|Azure Information Protection을 사용한 IRM|예|예|예|GCC High 및 DoD의 AIP 제한 사항에 대한 자세한 내용은 <a href="/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description">Azure Information Protection Premium Government 서비스 설명을 참조하세요</a>.<br><br>Azure Information Protection G1/F3에 포함되지 않지만 별도의 추가 기능으로 구매할 수 있으며 지원되는 IRM(정보 권한 관리) 기능을 사용하도록 설정합니다. 일부 Azure Information Protection 기능에는 Office 365 Government G1 또는 Office 365 Government F3에 포함되지 않은 Office 365 ProPlus 구독이 필요합니다.|
|Windows Server AD RMS를 사용한 IRM|예|예|예|Windows Server AD RMS는 지원되는 IRM 기능을 사용하도록 설정하기 위해 별도로 구매하고 관리해야 하는 온-프레미스 서버입니다.|
|Office 365 메시지 암호화|예|예|예|이 문서의 [GCC High/DoD 경계에서 Office 365 메시지 암호화 동작](#office-365-message-encryptionbehavior-across-gcc-highdod-boundary) 및 <a href="/microsoft-365/compliance/ome-version-comparison#unique-characteristics-of-office-365-message-encryption-in-a-gcc-high-deployment">GCC 높음 배포에서 Office 365 메시지 암호화의 고유한 특징</a>을 참조하세요. 이 특성은 GCC High/DoD와 비-doD 간에 메시지를 보낼 때 Office 365 메시지 암호화의 동작 뉘앙스를 문서화합니다. High/DoD 사용자를 GCC.|
|고객 키|예|예|예|G5 서비스 계획이 필요합니다.|
|S/MIME|예|예|예||
|원본 위치 유지 및 소송 보존|예|예|예|G3 또는 G5 서비스 계획이 필요합니다.|
|원본 위치 eDiscovery|예|예|예||
|메일 흐름 규칙|예|예|예||
|데이터 손실 방지|예|예|예|G3 또는 G5 서비스 계획이 필요합니다.|
|저널링|예|예|예||
|**[스팸 방지 및 맬웨어 방지 보호](/exchange/antispam-and-antimalware/antispam-and-antimalware)**|**GCC**|**GCC High**|**DoD**|**주요 고려 사항**|
|기본 제공 스팸 방지 보호|예|예|예||
|Customize anti-spam policies|예|예|예||
|기본 제공 맬웨어 방지 보호|예|예|예||
|Customize anti-malware policies|예|예|예||
|격리 - 관리자 관리|예|예|예||
|격리 - 최종 사용자 자기 관리|예|예|예||
|Office 365용 Microsoft Defender|예|예|예|G5 서비스 계획(또는 추가 기능 구매)이 필요합니다.<br><br>사용자 및 도메인 가장 및 스푸핑 인텔리전스에 대한 피싱 방지는 GCC High 및 DoD에서 아직 사용할 수 없습니다.|
|**[메일 흐름](/exchange/security-and-compliance/mail-flow-rules/mail-flow-rules)**|**GCC**|**GCC High**|**DoD**|**주요 고려 사항**|
|아웃바운드 메일의 사용자 지정 라우팅|예|예|예||
|Secure messaging with a trusted partner|예|예|예||
|Conditional mail routing|예|예|예||
|인바운드 안전 목록에 파트너 추가|예|예|예||
|하이브리드 전자 메일 라우팅|예|예|예||
|**[받는 사람](/exchange/recipients-in-exchange-online/recipients-in-exchange-online)**|**GCC**|**GCC High**|**DoD**|**주요 고려 사항**|
|용량 경고|예|예|예||
|Clutter|예|예|예||
|메일 설명|예|예|예||
|위임 액세스|예|예|예||
|받은 편지함 규칙|예|예|예||
|연결된 계정|예|아니요|아니요|이 기능은 타사 서비스에 대한 아웃바운드 연결 제한으로 인해 GCC High 또는 DoD에서 지원되지 않습니다. 영향을 받은 기능에 대한 자세한 내용은 이 문서의 [타사 서비스와의 연결을](#connectivity-with-third-party-services) 참조하세요.|
|비활성 사서함|예|예|예|G3 또는 G5 서비스 계획이 필요합니다.|
|오프라인 주소록|예|예|예||
|주소록 정책|예|예|예||
|계층적 주소록|예|예|예||
|주소 목록 및 전역 주소 목록|예|예|예||
|Office 365 그룹|예|예|예|Office 365 그룹에 대한 게스트 액세스는 GCC High 및 DoD 환경에서 지원되지 않습니다. 자세한 내용은 <a href="/azure/azure-government/documentation-government-services-securityandidentity">Azure Government 보안 + ID를 참조하세요</a>.|
|메일 그룹|예|예|예||
|외부 연락처(전체)|예|예|예|GCC High 및 DoD 환경에서 조직 관계 공동 작업 제한 사항이 적용됩니다. |
|소셜 네트워크와의 연결 연결|예|아니요|아니요|이 기능은 GCC High 또는 DoD에서 지원되지 않습니다.|
|리소스 사서함|예|예|예||
|회의실 관리|예|예|예||
|부재 중 회신|예|예|예||
|인터넷 일정 공유|예|아니요|아니요|GCC High에서 인터넷 일정 게시/공유는 GCC High 사용자가 공유하는 일정에 대한 인바운드 연결에서 작동하지만 GCC High 사용자가 GCC High 외부의 공유 일정에 아웃바운드를 연결하는 것은 아닙니다.<br><br>DoD에서 인터넷 일정 공유는 해당 환경에서 인바운드/아웃바운드 연결 허용 목록에 대한 요구 사항으로 인해 지원되지 않습니다.|
|**[보고 기능 및 문제 해결 도구](../../exchange-online-service-description/reporting-features-and-troubleshooting-tools.md)**|**GCC**|**GCC High**|**DoD**|**주요 고려 사항**|
|Microsoft 365 관리 센터 보고서|예|예|아니요|DoD에 사용할 수 없는 보고서입니다. 업데이트/현재 가용성에 대한 Office 365 미국 정부 서비스 설명의 <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">플랫폼 기능</a> 섹션을 참조하세요.|
|웹 서비스 보고서|예|예|아니요|DoD에 사용할 수 없는 보고서입니다. 업데이트/현재 가용성에 대한 Office 365 미국 정부 서비스 설명의 <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">플랫폼 기능</a> 섹션을 참조하세요.|
|Message trace|예|예|예||
|감사 보고서|예|예|아니요|DoD에 사용할 수 없는 보고서입니다. 업데이트/현재 가용성에 대한 Office 365 미국 정부 서비스 설명의 <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">플랫폼 기능</a> 섹션을 참조하세요.|
|통합 메시징 보고서|예|아니요|아니요||
|**[공유 및 공동 작업](/exchange/sharing/sharing)**|**GCC**|**GCC High**|**DoD**|**주요 고려 사항**|
|페더레이션된 공유(일정 게시 포함)|예|예|예|GCC High 및 DoD 모두에 제한이 있습니다. 이 문서에서 [약속 있음/없음 페더레이션](#freebusy-federation) 을 참조하세요.|
|사이트 사서함|예|예|예||
|공용 폴더|예|예|예||
|**[클라이언트 및 모바일 장치](/exchange/clients-and-mobile-in-exchange-online/clients-and-mobile-in-exchange-online)**|**GCC**|**GCC High**|**DoD**|**주요 고려 사항**|
|웹에서 To Do|예|아니요|아니요||
|Windows용 Outlook|예|예|예|GCC High 및 DoD 규정 준수 요구 사항을 충족하려면 Office 365 ProPlus 버전 1803 이상을 실행해야 합니다. Office 365 ProPlus G1 또는 F3에 포함되지 않습니다.|
|웹용 Outlook <sup>1</sup>|예|예|예||
|Outlook for Mac|예|예|예|GCC High 및 DoD 규정 준수 요구 사항을 충족하려면 Office 365 ProPlus 버전 1803 이상을 실행해야 합니다. Office 365 ProPlus G1 또는 F3에 포함되지 않습니다.|
|iOS 및 Android용 Outlook|예|예|예||
|Exchange ActiveSync|예|예|예||
|Microsoft 365 기본 모바일 및 보안|예|아니요|아니요||
|POP 및 IMAP|예|예|예||
|SMTP|예|예|예||
|EWS 애플리케이션 지원<sup>2</sup>|예|예|예||
|**[음성 메시지 서비스](/exchange/plan-and-deploy/integration-with-sharepoint-and-skype/integration-with-sharepoint-and-skype)**|**GCC**|**GCC High**|**DoD**|**주요 고려 사항**|
|음성 사서함|아니요|아니요|아니요|온-프레미스 IP-PBX 시스템과 Exchange Online 통합 메시징의 통합은 지원되지 않습니다.|
|음성 메일과 타사 FAX 간의 통합|아니요|아니요|아니요|온-프레미스 IP-PBX 시스템과 Exchange Online 통합 메시징의 통합은 지원되지 않습니다.|
|타사 음성 사서함 상호 운용성|아니요|아니요|아니요|온-프레미스 IP-PBX 시스템과 Exchange Online 통합 메시징의 통합은 지원되지 않습니다.|
|비즈니스용 Skype 통합|예|예|예||
|**[고가용성 및 비즈니스 연속성](/exchange/high-availability/high-availability)**|**GCC**|**GCC High**|**DoD**|**주요 고려 사항**|
|데이터 센터의 사서함 복제|예|예|예||
|삭제된 사서함 복구|예|예|예||
|삭제된 항목 복구|예|예|예||
|단일 항목 복구|예|예|예||
|**[상호 운용성, 연결 및 호환성](/exchange/security-and-compliance/interoperability-connectivity-and-compatiblity)**|**GCC**|**GCC High**|**DoD**|**주요 고려 사항**|
|OWA 및 Outlook 현재 상태|예|예|예||
|SharePoint 상호 운용성|예|예|예||
|EWS 연결 지원|예|예|예||
|SMTP 릴레이 지원|예|예|예||
|**[Exchange Online 설치 및 관리](/exchange/architecture/client-access/exchange-admin-center)**|**GCC**|**GCC High**|**DoD**|**주요 고려 사항**|
|Microsoft Office 365 포털 액세스|예|예|아니요|DoD에 사용할 수 없는 보고서입니다. 업데이트/현재 가용성에 대한 Office 365 미국 정부 서비스 설명의 <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">플랫폼 기능</a> 섹션을 참조하세요.|
|액세스 Microsoft 365 관리 센터|예|예|아니요|DoD에 사용할 수 없는 보고서입니다. 업데이트/현재 가용성에 대한 Office 365 미국 정부 서비스 설명의 <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">플랫폼 기능</a> 섹션을 참조하세요.|
|Exchange 관리 센터 액세스|예|예|예||
|원격 Windows PowerShell 액세스|예|예|예||
|모바일 디바이스에 대한 ActiveSync 정책|예|예|예||
|사용 현황 보고|예|예|아니요|DoD에 사용할 수 없는 보고서입니다. 업데이트/현재 가용성에 대한 Office 365 미국 정부 서비스 설명의 <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">플랫폼 기능</a> 섹션을 참조하세요.|
|**[서비스 확장 - 사용자 지정, 추가 기능 및 리소스](../../exchange-online-service-description/exchange-online-service-description.md)**|**GCC**|**GCC High**|**DoD**|**주요 고려 사항**|
|추가 기능 및 Outlook MAPI Outlook|예|예|예|일부 OWA 및 Outlook 추가 기능만 GCC High 및 DoD에서 사용할 수 있습니다. 이 문서의 [Outlook 및 Outlook Web App 추가](#add-insin-outlook-and-outlook-web-app) 기능을 참조하세요.|

경계 간 제한(GCC 높음/GCC 높음 시나리오)으로 인해 Windows 대한 Outlook IRM 보호 메시지를 표시할 수 없는 경우 웹에서 <sup>1</sup>개의 Outlook 사용할 수 있습니다.</br>
<sup>2</sup> 고객이 소유하고 있음을 증명할 수 있는 특정 주소 공간으로의 송신만 허용되므로 모바일 디바이스에서 사용하는 타사 서비스 및 광범위한 IP 범위를 배제합니다.

## <a name="feature-nuances-within-gcc-high-and-dod-environments"></a>GCC High 및 DoD 환경 내의 뉘앙스 기능

### <a name="connectivity-with-third-party-services"></a>타사 서비스와 연결  

GCC High 및 DoD 환경은 모두 아웃바운드 연결의 명시적 승인 및 구성이 필요한 제한된 환경입니다. 또한 Microsoft는 이러한 환경에서 상용 클라우드 서비스(상업용 Office 365, Google GSuite, Amazon Web Services 등)로의 아웃바운드 액세스를 허용하는 요청을 수용할 수 없습니다.

이러한 제한으로 인해 GCC High/DoD 환경에서 이 아웃바운드 연결을 사용하는 기능은 일반적으로 다음을 포함하여 지원되지 않습니다.

- 연결된 계정 - 사용자는 계정을 추가/동기화할 수 없습니다(Google, POP/IMAP 등).

- 타사 파일 스토리지 공급자 지원 - 파일 첨부/공유를 위해 다양한 Outlook 클라이언트 내에서 *GCC High/DoD 내* 의 사용자의 비즈니스용 OneDrive 계정에만 액세스할 수 있습니다. 타사 스토리지 계정(Dropbox, Box, Google 드라이브)을 추가할 수 없습니다.

- Facebook 또는 LinkedIn과 같은 소셜 네트워크와의 연결

### <a name="azure-active-directory-b2b-collaboration"></a>B2B 협업 Azure Active Directory

Azure Active Directory B2B 협업은 현재 Azure 미국 정부 클라우드 내에 있고 둘 다 B2B 협업을 지원하는 조직 간에만 지원됩니다.

또한 Office 365 그룹의 게스트인 B2B 사용자는 GCC High 및 DoD 환경에서 지원되지 않습니다. 

자세한 내용 및 최신 업데이트는 [Azure Government 보안 + ID를 참조하세요](/azure/azure-government/documentation-government-services-securityandidentity).

### <a name="office-365-message-encryption-behavior-across-gcc-highdod-boundary"></a>GCC High/DoD 경계에서 메시지 암호화 동작 Office 365

GCC 높은 환경에서 Office 365 메시지 암호화를 사용하려는 경우 받는 사람 환경에 대한 다음과 같은 고유한 특성을 알고 있어야 합니다.  

- GCC High 또는 DoD에서 동일한 환경의 받는 사람에게 암호화된 전자 메일을 보내는 경우:
    
    - 보낸 사람이 PC 및 Mac 및 웹용 Outlook Outlook 전자 메일을 수동으로 암호화하거나 조직에서 Exchange 메일 흐름 규칙을 사용하여 전자 메일을 암호화하는 정책을 설정할 수 있습니다.
    - GCC High/DoD 내의 받는 사람은 PC 및 Mac 및 웹용 Outlook Outlook 다른 모든 Office 365 사용자와 동일한 인라인 읽기 환경을 받습니다.

<!-- end list -->

- GCC High에서 해당 환경 외부의 받는 사람에게 암호화된 전자 메일을 보내는 경우(DoD, GCC 및 상업용 포함):

    - GCC High 내의 보낸 사람이 GCC 높음 경계 외부에서 암호화된 전자 메일을 보낼 수 있습니다.
    - DoD, 상업용 Office 365 사용자, Outlook.com 사용자 및 기타 전자 메일 공급자의 다른 사용자를 포함하여 GCC High 외부의 모든 받는 사람은 알림 메일을 받습니다. 이 알림 메일은 받는 사람이 메시지를 읽고 회신할 수 있는 암호화된 메시지 포털로 받는 사람을 리디렉션합니다.
    - 현재 상업용 클라우드의 사용자와 문서 및 다운로드한 전자 메일 첨부 파일을 공유할 수 없습니다.  암호화된 첨부 파일은 암호화된 메시지 포털에서만 미리 볼 수 있습니다.

### <a name="freebusy-federation"></a>약속 있음/없음 페더레이션

약속 있음/없음 정보를 포함하여 페더레이션된 공유는 현재 DoD 환경에서 몇 가지 중요한 제한 사항이 적용됩니다.

GCC 높은 환경에서:

- 페더레이션 트러스트(양방향 무료/없음 공유 포함)는 GCC High 내의 테넌트 간, GCC 및 상용 클라우드의 테넌트 간, 하이브리드 공존(2013년 Exchange 이상)을 통해 지원됩니다.

DoD 환경에서 다음을 수행합니다.

  - 페더레이션 트러스트(약속 있음/없음 공유 포함)는 현재 DoD 환경 내의 테넌트 간에만 지원됩니다. DoD 테넌트와 GCC, GCC High 또는 상업용 테넌트 간에는 지원되지 않습니다.

### <a name="client-configuration"></a>클라이언트 구성

Office ProPlus(Outlook 포함)를 배포하고 구성하는 데 추가 단계가 포함됩니다. 이러한 단계에 대한 자세한 설명은 [GCC High 또는 DoD 환경에서 엔터프라이즈용 Microsoft 365 앱 배포하기 위한 지침을 참조하세요](/deployoffice/deploy-microsoft-365-apps-gcc-high-dod).

iOS 및 Android용 Outlook GCC High 및 DoD 환경에서도 사용할 수 있습니다. 이러한 환경의 기능 제한 사항 및 관리에 대한 자세한 내용은 [정부 커뮤니티 클라우드 iOS 및 Android용 Outlook 사용을](/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud) 참조하세요.

### <a name="add-ins-in-outlook-and-outlook-web-app"></a>Outlook 및 Outlook Web App 추가 기능  

일부 OWA 및 Outlook 추가 기능만 GCC High 및 DoD에서 사용할 수 있습니다. 내 서식 파일 및 제안된 모임을 사용할 수 있으며 작동할 것으로 예상됩니다. 5개의 기본 OWA 추가 기능만 지원됩니다. 타사 애플리케이션과의 통합은 가능할 수 있지만 이러한 통합에는 GCC High 또는 DoD에 대한 Microsoft 규정 준수 약속이 적용되지 않습니다. 고객은 조직에 대한 추가 기능을 구성하기 전에 타사 데이터 처리 사례 및 규정 준수 약속을 숙지해야 합니다.

## <a name="feature-nuances-within-gcc-environments-for-microsoft-to-do"></a>Microsoft To Do 대한 GCC 환경 내의 뉘앙스 기능

| 기능 | 설명 | WW | GCC 가용성 |
|:-----|:-----|:-----|:-----|
|지원되는 플랫폼|웹, Android, iOS, Mac, Windows|모두|웹만|
|M365 허브 지원|Outlook, Teams, Planner와의 통합|모두|Outlook, Planner(Teams 작업 앱에서 사용할 수 Teams)|
|Wunderlist 마이그레이션|wunderlist 사용자가 웹에서 To Do 데이터를 마이그레이션하도록 허용|예|아니요|
|푸시 알림|미리 알림 등을 위해 최종 사용자에게 푸시 알림을 보냅니다.|예|아니요|
|Helpshift 지원|helpshift 인터페이스를 사용하여 지원 요청 만들기|예|아니요|
|나의 하루|하루 계획|예|예|
|계획된 목록|기한이 있는 모든 작업 보기|예|예|
|목록에 할당됨|공유 목록, Planner 또는 WXP에서 할당된 모든 작업(미래)|예|예|
|플래그가 지정된 전자 메일|Outlook에서 작업으로 플래그가 지정된 전자 메일 보기|예|예|
|다중 계정 지원|한 창에서 홈 및 사무실 계정 사용|예|예|
|목록 공유|동일한 조직의 동료와 목록 공유|예|예|
|테넌트 간 공유|조직 외부 작업 목록 공유|예|아니요|
|미리 알림 및 되풀이|작업에 대한 미리 알림 설정 |예|예|

*언급되지 않은 다른 모든 기능은 두 환경에서 모두 사용할 수 있습니다.