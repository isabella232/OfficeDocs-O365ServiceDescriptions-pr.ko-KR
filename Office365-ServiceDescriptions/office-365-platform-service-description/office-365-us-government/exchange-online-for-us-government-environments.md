---
title: 미국 정부 환경용 Exchange Online
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 이 문서에서는 Exchange Online 서비스 설명에 나와 있는 미국 정부 클라우드와 상업용 클라우드 간의 기능 차이에 대 한 개요를 제공 합니다.
ms.openlocfilehash: 6eae6379120b91697edf6e1cb631e8acf57e30a9
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/14/2020
ms.locfileid: "45131932"
---
# <a name="exchange-online-for-us-government-environments"></a>미국 정부 환경용 Exchange Online

이 문서에서는 [Exchange Online 서비스 설명](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-service-description)에 나와 있는 미국 정부 클라우드와 상업용 클라우드 간의 기능 차이에 대 한 개요를 제공 합니다. Exchange Online은 GCC (정부 커뮤니티 클라우드), GCC 최고 및 DoD (방어 부서) 환경에 사용할 수 있습니다.

자격 및 구매를 비롯 한 정부 클라우드에 대 한 자세한 내용은 [Microsoft 365 정부-구매 방법](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy)를 참조 하세요. Office 365 정부 요금제를 비교 하려면 [office 365 정부 요금제](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements)를 참조 하세요.

네트워크 연결을 관리할 때 필요한 끝점에 대 한 자세한 내용은 [office 365 미국 정부 GCC High endpoints](https://docs.microsoft.com/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business)   또는 [Office 365 미국 정부 DoD endpoints](https://docs.microsoft.com/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business)를 참조 하세요.

조직에서는 Office 365의 기능과 기능을 제공 하는 것 외에도 미국 정부 클라우드 환경에 고유한 다음과 같은 기능을 활용할 수 있습니다.

- 조직의 고객 콘텐츠는 상용 Office 365 서비스의 고객 콘텐츠와 논리적으로 분리 됩니다.

- 조직의 고객 콘텐츠는 미국 내에서 rest에 저장 됩니다.

- 조직 고객 콘텐츠에 대한 액세스는 선별된 Microsoft 직원으로 제한됩니다.

- 정부 클라우드 환경은 종종 미국 공공 부문 고객에 게 필요한 인증 및 승인을 준수 합니다.

이는 모든 Exchange 상업용 기능과 기능을 정부 클라우드 환경에 제공 하는 일반적인 의도입니다. 즉, 정부 클라우드 고객의 요구 사항으로 인해 일부 기능을 사용할 수 없습니다. 다른 기능은 정부 환경에 제공 되지만 아직 사용할 수 없습니다. 정부 클라우드 환경에서의 기능 가용성에 대 한 자세한 내용은 다음 섹션을 참조 하십시오.

## <a name="exchange-online-features"></a>Exchange Online 기능 

다음 표에는 GCC, GCC High 및 DoD 환경 내에서 지정 된 Exchange Online 기능을 사용할 수 있는지에 대 한 개요가 나와 있습니다. 지원 nuances 관련 된 추가 컨텍스트 (또는 해당 없음)가 제공 됩니다.

|**기능 영역**|**GCC**|**GCC 최고**|**여기서**|**주요 고려 사항**|
|:-----|:-----|:-----|:-----|:-----|
|**[계획 및 배포](../../exchange-online-service-description/planning-and-deployment.md)**|||||
|하이브리드 배포 지원|예|예|예|온-프레미스 Exchange Server와의 공존을 위해 Microsoft에서는 하나 이상의 Exchange Server 2013 클라이언트 액세스 서버 (또는 Exchange Server 2016)를 설치 해야 합니다. Exchange Server 2010이 하 버전은 지원 되지 않습니다.|
|IMAP 마이그레이션 지원|예|예|예||
|지원되는 단독형 마이그레이션|예|예|예||
|미리 구성된 마이그레이션 지원|예|예|예|GSuite 마이그레이션은 GCC High 및 DoD에 대해서는 지원 되지 않습니다. 자세한 내용은 <a href="https://docs.microsoft.com/exchange/mailbox-migration/perform-g-suite-migration">GSuite 마이그레이션 수행</a>을 참조 하십시오.|
|**[사용 권한](../../exchange-online-service-description/permissions.md)**|**GCC**|**GCC 최고**|**여기서**|**주요 고려 사항**|
|역할 기반 권한|예|예|예||
|역할 그룹|예|예|예||
|역할 할당 정책|예|예|예||
|**[메시지 정책 및 규정 준수](../../exchange-online-service-description/message-policy-and-compliance.md)**|**GCC**|**GCC 최고**|**여기서**|**주요 고려 사항**|
|Exchange Online 기반 사서함 보관|예|예|예||
|온-프레미스 사서함의 클라우드 기반 보관|예|예|예||
|MRM (메시징 레코드 관리) |예|예|예||
|수동 보존 정책, 레이블 및 태그 |예|예|예||
|보관된 데이터 암호화(BitLocker)|예|예|예||
|Azure Information Protection을 사용한 IRM|예|예|예|GCC High 및 DoD의 IP 제한 사항에 대 한 자세한 내용은 <a href="https://docs.microsoft.com/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description">Azure Information Protection Premium 정부 서비스 설명을</a>참조 하세요.<br><br>Azure Information Protection은 G1/F3에 포함 되어 있지 않지만 별도의 추가 기능으로 구입할 수 있으며, 지원 되는 IRM (정보 권한 관리) 기능을 사용 하도록 설정 됩니다. 일부 Azure Information Protection 기능을 사용 하려면 Office 365 정부 G1 또는 Office 365 정부 F3에 포함 되지 않은 Office 365 ProPlus에 대 한 구독이 필요 합니다.|
|Windows Server AD RMS를 사용한 IRM|예|예|예|Windows Server AD RMS는 지원 되는 IRM 기능을 사용 하기 위해 별도로 구입 하 여 관리 해야 하는 온-프레미스 서버입니다.|
|Office 365 메시지 암호화|예|예|예|GCC high/DoD 및 GCC High/dod 사용자 간에 메시지를 보낼 때 Office 365 메시지 암호화를 문서화 하는 gcc high 배포의 경우 [office 365 메시지 암호화 동작 (gcc high/dod 경계를 통해](#office-365-message-encryptionbehavior-across-gcc-highdod-boundary) Office <a href="https://docs.microsoft.com/microsoft-365/compliance/ome-version-comparison?view=o365-worldwide#unique-characteristics-of-office-365-message-encryption-in-a-gcc-high-deployment">365 메시지 암호화의 특징</a>및 nuances을 참조 하십시오.|
|고객 키|예|예|예|G5 서비스 계획이 필요 합니다.|
|S/MIME|예|예|예||
|원본 위치 유지 및 소송 보존|예|예|예|G3 또는 G5 서비스 계획이 필요 합니다.|
|원본 위치 eDiscovery|예|예|예||
|메일 흐름 규칙|예|예|예||
|데이터 손실 방지|예|예|예|G3 또는 G5 서비스 계획이 필요 합니다.|
|저널링|예|예|예||
|**[스팸 방지 및 맬웨어 방지 보호](../../exchange-online-service-description/anti-spam-and-anti-malware-protection.md)**|**GCC**|**GCC 최고**|**여기서**|**주요 고려 사항**|
|스팸 방지 보호 기능 내장|예|예|예||
|Customize anti-spam policies|예|예|예||
|맬웨어 방지 보호 기능 내장|예|예|예||
|Customize anti-malware policies|예|예|예||
|격리 - 관리자 관리|예|예|예||
|격리 - 최종 사용자 자기 관리|예|예|예||
|고급 위협 방지|예|예|예|G5 서비스 계획 (또는 추가 기능 구입)이 필요 합니다.<br><br>사용자 및 도메인 가장을 위한 피싱 방지 및 스푸핑 지능은 GCC High 및 DoD에서는 아직 사용할 수 없습니다.|
|**[메일 흐름](../../exchange-online-service-description/mail-flow.md)**|**GCC**|**GCC 최고**|**여기서**|**주요 고려 사항**|
|아웃 바운드 메일의 사용자 지정 라우팅|예|예|예||
|Secure messaging with a trusted partner|예|예|예||
|Conditional mail routing|예|예|예||
|인바운드 수신 허용 목록에 파트너 추가|예|예|예||
|하이브리드 전자 메일 라우팅|예|예|예||
|**[받는 사람](../../exchange-online-service-description/recipients.md)**|**GCC**|**GCC 최고**|**여기서**|**주요 고려 사항**|
|용량 경고|예|예|예||
|Clutter|예|예|예||
|메일 설명|예|예|예||
|위임 액세스|예|예|예||
|받은 편지함 규칙|예|예|예||
|연결된 계정|예|아니요|아니요|이 기능은 타사 서비스에 대 한 아웃 바운드 연결의 제한으로 인해 GCC High 또는 DoD에서 지원 되지 않습니다. 영향을 받는 기능에 대 한 자세한 내용은이 문서의 [타사 서비스와 연결](#connectivity-with-third-party-services) 을 참조 하십시오.|
|비활성 사서함|예|예|예|G3 또는 G5 서비스 계획이 필요 합니다.|
|오프라인 주소록|예|예|예||
|주소록 정책|예|예|예||
|계층 구조 주소록|예|예|예||
|주소 목록 및 전체 주소 목록|예|예|예||
|Office 365 그룹|예|예|예|Office 365 그룹에 대 한 게스트 액세스는 GCC High 및 DoD 환경에서는 지원 되지 않습니다. 자세한 내용은 <a href="https://docs.microsoft.com/azure/azure-government/documentation-government-services-securityandidentity">Azure 정부 보안 + id</a>를 참조 하세요.|
|메일 그룹|예|예|예||
|외부 연락처(전체)|예|예|예|GCC High 및 DoD 환경의 조직 관계 공동 작업 제한 사항에 따라 달라 집니다. |
|소셜 네트워크와 연결 된 연락처|예|아니요|아니요|이 기능은 GCC High 또는 DoD에서는 지원 되지 않습니다.|
|리소스 사서함|예|예|예||
|회의실 관리|예|예|예||
|부재 중 회신|예|예|예||
|인터넷 일정 공유|예|아니요|아니요|GCC high에서는 인터넷 일정 게시/공유가 GCC high 사용자가 공유 하는 일정에 대 한 인바운드 연결에 작동 하지만, 아웃 바운드를 GCC high users 외부에 연결 하는 경우에는 gcc high 사용자에 게 적합 하지 않습니다.<br><br>DoD-인터넷 일정 공유는 해당 환경의 인바운드/아웃 바운드 연결 허용 목록에 대 한 요구 사항으로 인해 지원 되지 않습니다.|
|**[보고 기능 및 문제 해결 도구](../../exchange-online-service-description/reporting-features-and-troubleshooting-tools.md)**|**GCC**|**GCC 최고**|**여기서**|**주요 고려 사항**|
|Microsoft 365 관리 센터 보고서|예|예|아니요|DoD에 대 한 보고서를 사용할 수 없습니다. 업데이트/현재 가용성에 대 한 Office 365 US 정부 서비스 설명의 <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">플랫폼 기능</a> 섹션을 참조 하세요.|
|웹 서비스 보고서|예|예|아니요|DoD에 대 한 보고서를 사용할 수 없습니다. 업데이트/현재 가용성에 대 한 Office 365 US 정부 서비스 설명의 <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">플랫폼 기능</a> 섹션을 참조 하세요.|
|Message trace|예|예|예||
|감사 보고서|예|예|아니요|DoD에 대 한 보고서를 사용할 수 없습니다. 업데이트/현재 가용성에 대 한 Office 365 US 정부 서비스 설명의 <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">플랫폼 기능</a> 섹션을 참조 하세요.|
|통합 메시징 보고서|예|아니요|아니요||
|**[공유 및 공동 작업](../../exchange-online-service-description/sharing-and-collaboration.md)**|**GCC**|**GCC 최고**|**여기서**|**주요 고려 사항**|
|페더레이션 공유 (일정 게시 포함)|예|예|예|GCC High 및 DoD에는 제한이 있습니다. 이 문서에서는 [약속 있음/없음 페더레이션](#freebusy-federation) 을 참조 하십시오.|
|사이트 사서함|예|예|예||
|공용 폴더|예|예|예||
|**[클라이언트 및 모바일 장치](../../exchange-online-service-description/clients-and-mobile-devices.md)**|**GCC**|**GCC 최고**|**여기서**|**주요 고려 사항**|
| Windows용 Outlook|예|예|예|GCC High 및 DoD 준수 요구 사항을 충족 하려면 최소 버전 1803의 Office 365 ProPlus를 실행 해야 합니다. Office 365 ProPlus는 G1 또는 F3에 포함 되지 않습니다.|
|웹용 Outlook|예|예|예||
|Outlook for Mac|예|예|예|GCC High 및 DoD 준수 요구 사항을 충족 하려면 최소 버전 1803의 Office 365 ProPlus를 실행 해야 합니다. Office 365 ProPlus는 G1 또는 F3에 포함 되지 않습니다.|
|iOS 및 Android용 Outlook|예|예|예||
|Exchange ActiveSync|예|예|예||
|Microsoft 365에 대 한 기본 모바일 및 보안|예|예|예||
|POP 및 IMAP|예|예|예||
|SMTP|예|예|예||
|EWS 응용 프로그램 지원|예|예|예||
|**[음성 메시지 서비스](../../exchange-online-service-description/voice-message-services.md)**|**GCC**|**GCC 최고**|**여기서**|**주요 고려 사항**|
|음성 사서함|아니요|아니요|아니요|Exchange Online 통합 메시징과 함께 온-프레미스 IP PBX 시스템 통합은 지원 되지 않습니다.|
|음성 사서함과 타사 팩스 통합|아니요|아니요|아니요|Exchange Online 통합 메시징과 함께 온-프레미스 IP PBX 시스템 통합은 지원 되지 않습니다.|
|타사 음성 사서함 상호 운용성|아니요|아니요|아니요|Exchange Online 통합 메시징과 함께 온-프레미스 IP PBX 시스템 통합은 지원 되지 않습니다.|
|비즈니스용 Skype 통합|예|예|예||
|**[고가용성 및 비즈니스 연속성](../../exchange-online-service-description/high-availability-and-business-continuity.md)**|**GCC**|**GCC 최고**|**여기서**|**주요 고려 사항**|
|데이터 센터에서의 사서함 복제|예|예|예||
|삭제된 사서함 복구|예|예|예||
|삭제된 항목 복구|예|예|예||
|단일 항목 복구|예|예|예||
|**[상호 운용성, 연결 및 호환성](../../exchange-online-service-description/interoperability-connectivity-and-compatibility.md)**|**GCC**|**GCC 최고**|**여기서**|**주요 고려 사항**|
|OWA 및 Outlook의 현재 상태|예|예|예||
|SharePoint 상호 운용성|예|예|예||
|EWS 연결 지원|예|예|예||
|SMTP 릴레이 지원|예|예|예||
|**[Exchange Online 설치 및 관리](../../exchange-online-service-description/exchange-online-setup-and-administration.md)**|**GCC**|**GCC 최고**|**여기서**|**주요 고려 사항**|
|Microsoft Office 365 포털 액세스|예|예|아니요|DoD에 대 한 보고서를 사용할 수 없습니다. 업데이트/현재 가용성에 대 한 Office 365 US 정부 서비스 설명의 <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">플랫폼 기능</a> 섹션을 참조 하세요.|
|Microsoft 365 관리 센터 액세스|예|예|아니요|DoD에 대 한 보고서를 사용할 수 없습니다. 업데이트/현재 가용성에 대 한 Office 365 US 정부 서비스 설명의 <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">플랫폼 기능</a> 섹션을 참조 하세요.|
|Exchange 관리 센터 액세스|예|예|예||
|원격 Windows PowerShell 액세스|예|예|예||
|모바일 장치에 대 한 ActiveSync 정책|예|예|예||
|사용 현황 보고|예|예|아니요|DoD에 대 한 보고서를 사용할 수 없습니다. 업데이트/현재 가용성에 대 한 Office 365 US 정부 서비스 설명의 <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">플랫폼 기능</a> 섹션을 참조 하세요.|
|**[서비스-사용자 지정, 추가 기능 및 리소스 확장](../../exchange-online-service-description/exchange-online-service-description.md)**|**GCC**|**GCC 최고**|**여기서**|**주요 고려 사항**|
|Outlook 추가 기능 및 Outlook MAPI|예|예|예|일부 OWA 및 Outlook 추가 기능만 GCC High 및 DoD에서 사용할 수 있습니다. 이 문서에서 [outlook 및 Outlook Web App의 추가 기능](#add-insin-outlook-and-outlook-web-app) 을 참조 하세요.|

## <a name="feature-nuances-within-gcc-high-and-dod-environment"></a>GCC High 및 DoD 환경 내의 기능 nuances

### <a name="connectivity-with-third-party-services"></a>타사 서비스와의 연결  

GCC High 및 DoD 환경 둘 다는 아웃 바운드 연결을 명시적으로 승인 하 고 구성 해야 하는 제한 된 환경입니다. 또한 Microsoft는 이러한 환경에서 상업용 클라우드 서비스 (상업용 Office 365, Google GSuite, Amazon Web Services 등)로의 아웃 바운드 액세스를 허용 하기 위한 요청을 수용할 수 없습니다.     

이러한 제한으로 인해 다음과 같은 GCC High/DoD 환경에서 이러한 아웃 바운드 연결을 사용 하는 기능은 일반적으로 지원 되지 않습니다. 

- 연결 된 계정 &mdash; 사용자는 계정 (Google, POP/IMAP 등)을 추가/동기화 할 수 없습니다. 

- 타사 파일 저장소 공급자 지원 &mdash;  *GCC High/DoD 내*에서 사용자의 비즈니스용 OneDrive 계정에는   파일 연결/공유를 위해 다양 한 Outlook 클라이언트 내에서 액세스할 수 있습니다. 타사 저장소 계정 (Dropbox, Box, Google Drive)은 추가할 수 없습니다. 

- Facebook 또는 LinkedIn과 같은 공유 네트워크와의 연결 

### <a name="azure-active-directoryb2b-collaboration"></a>Azure Active Directory B2B 공동 작업 

Azure Active Directory B2B 공동 작업은 현재 Azure US 정부 클라우드 내에 있고 모두 B2B 공동 작업을 지 원하는 조직 간에만 지원 됩니다.

또한 GCC High 및 DoD 환경에서는 B2B 사용자가 Office 365 그룹의 게스트로 지원 되지 않습니다. 

최신 업데이트에 대 한 자세한 내용은 [Azure 정부 보안 + id](https://docs.microsoft.com/azure/azure-government/documentation-government-services-securityandidentity)를 참조 하세요. 

### <a name="office-365-message-encryptionbehavior-across-gcc-highdod-boundary"></a>GCC High/DoD 경계에 걸친 Office 365 메시지 암호화 동작 

GCC High 환경에서 Office 365 메시지 암호화를 사용 하려면 받는 사람 환경에 대 한 다음과 같은 고유한 특성을 알고 있어야 합니다.  

- 동일 환경의 GCC High 또는 DoD에서 받는 사람에 게 암호화 된 전자 메일을 보낼 때:
    
    - 보낸 사람은 Outlook for PC 및 Mac 및 웹용 Outlook에서 전자 메일을 수동으로 암호화할 수 있으며, 조직에서 Exchange 메일 흐름 규칙을 사용 하 여 전자 메일을 암호화 하는 정책을 설정할 수 있습니다. 
    
    - GCC High/DoD 내부의 받는 사람은 Outlook for PC 및 Mac 및 웹용 Outlook의 다른 모든 Office 365 사용자와 동일한 인라인 읽기 환경을 수신 합니다. 

<!-- end list -->

- Gcc High 또는 DoD에서 해당 환경의 외부에 있는 받는 사람에 게 암호화 된 전자 메일을 보낼 때 (GCC 및 상업용 포함) 다음을 수행 합니다.
    
    - GCC High/DoD 내부의 보낸 사람은 GCC High/DoD 경계 외부에서 암호화 된 전자 메일을 보낼 수 있습니다. 
    
    - 상업용 Office 365 사용자, Outlook.com 사용자 및 다른 전자 메일 공급자의 기타 사용자를 포함 하 여 GCC High/DoD를 제외한 모든 받는 사람은 래퍼 메일을 받습니다. 이 래퍼 메일은 받는 사람이 메시지를 읽고 회신할 수 있는 OME 포털에 받는 사람을 리디렉션합니다. 

최신 업데이트에 대 한 자세한 내용은 [Compare VERSIONS OME](https://docs.microsoft.com/microsoft-365/compliance/ome-version-comparison?view=o365-worldwide)을 참조 하십시오.

### <a name="freebusy-federation"></a>약속 있음/없음 페더레이션

약속 있음/없음 정보를 비롯 한 페더레이션 공유는 현재 GCC High 및 DoD 환경의 몇 가지 중요 한 제한에 따라 달라 집니다.

GCC High 환경에서 다음을 수행 합니다.

- 양방향 약속 있음/없음 공유를 비롯 한 페더레이션 트러스트는 GCC High 및 하이브리드 동시 사용 (Exchange 2013 이상) 내에서의 테 넌 트 사이에서 지원 됩니다.

- 페더레이션 공유는 GCC High 및 GCC 또는 Office 365 상업용의 테 넌 트 사이에서 지원 되지 않습니다. GCC High 환경에서 상업용 클라우드 (GCC 및 Office 365 상업용 포함)로의 아웃 바운드 연결이 현재 허용 되지 않습니다. 따라서 GCC 최고 사용자는 변경 된 일정 정보에 액세스 하기 위해 GCC/상업용에 필요한 아웃 바운드 요청을 만들 수 없습니다.

DoD 환경에서 다음을 수행 합니다.

  - 페더레이션 트러스트 (약속 있음/없음 공유 포함)는 현재 DoD 환경 내의 테 넌 트 간에만 지원 됩니다. DoD 테 넌 트와 GCC 또는 상용 테 넌 트 사이에서는 지원 되지 않습니다.

### <a name="client-configuration"></a>클라이언트 구성 

추가 단계는 Office ProPlus (Outlook 포함)를 배포 하 고 구성 하는 데 수반 됩니다. 이러한 단계에 대 한 자세한 내용은 [GCC High 또는 DoD 환경에서 Microsoft 365 Apps for enterprise 배포에 대 한 지침 ](https://docs.microsoft.com/deployoffice/deploy-microsoft-365-apps-gcc-high-dod)을 참조 하십시오.

또한 GCC High 및 DoD 환경 에서도 iOS 및 Android 용 Outlook을 사용할 수 있습니다. 이러한 환경에서의 기능 제한 및 관리에 대 한 자세한 내용은 [정부 커뮤니티 클라우드에서 iOS 및 Android 용 Outlook 사용](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud)을 참조 하십시오.

### <a name="add-insin-outlook-and-outlook-web-app"></a>Outlook 및 Outlook Web App의 추가 기능  

일부 OWA 및 Outlook 추가 기능만 GCC High 및 DoD에서 사용할 수 있습니다. 내 서식 파일 및 제안 된 모임이 사용 가능 하 고 정상적으로 작동 합니다. 다섯 개의 기본 OWA 추가 기능만 지원 됩니다. 타사 응용 프로그램과 통합 하는 것이 가능 하지만, 이러한 통합은 GCC High 또는 DoD에 대 한 Microsoft 규정 준수에 포함 되지 않습니다. 고객은 조직에 대 한 추가 기능을 구성 하기 전에 타사 데이터 처리 방법과 규정 준수를 숙지 해야 합니다.
