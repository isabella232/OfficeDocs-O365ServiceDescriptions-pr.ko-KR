---
title: Exchange Online 서비스 설명
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 7a83da3c-3b6d-4f86-ad4d-6104707cd0ec
description: 구독이 포함된 기능 비교를 Exchange Online? 그렇다면 Exchange Online 서비스 설명 문서가 필요할 것입니다. 저장소 및 받는 사람 요구 사항 뿐 아니라 시스템 요구 사항에 대해서도 알 수 있습니다.
ms.openlocfilehash: 596d0663c91a7ed3c2e423301a90fddaee7908b5d1da04e4d04f860c0c31ae14
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/06/2021
ms.locfileid: "54663991"
---
# <a name="exchange-online-service-description"></a>Exchange Online 서비스 설명

구독이 포함된 기능 비교를 Exchange Online? 그렇다면 Exchange Online 서비스 설명 문서가 필요할 것입니다. 저장소 및 받는 사람 요구 사항 뿐 아니라 시스템 요구 사항에 대해서도 알 수 있습니다.
  
> [!NOTE]
> 작업에 대한 도움이 필요하거나 문제를 해결하는 경우 다음 리소스가 도움이 될 수 있습니다. <br/>
[전자](https://support.office.com/article/Email-94275804-7147-4332-9ccd-5d421760a9ed) 메일을 만들고 보내는 데 도움이 되는 전자 메일입니다. <br/> 
[전자 메일 및 일정 관리](/office365/admin/email/email)<br/> 
[Microsoft 지원 및 복구 도우미](https://diagnostics.office.com/)<br/> 
[전자 메일 배달되지 않은 보고서 Exchange Online](/Exchange/mail-flow-best-practices/non-delivery-reports-in-exchange-online/non-delivery-reports-in-exchange-online)<br/> 
[Exchange Online 도움말](/exchange/exchange-online)
  
Microsoft Exchange Online은 Microsoft Exchange Server의 기능을 클라우드 기반 서비스로 전달하는 호스트 메시징 솔루션입니다. 이 솔루션은 PC, 웹, 모바일 장치로부터 전자 메일, 일정, 연락처 및 작업에 액세스할 수 있도록 하며, Active Directory와 완전히 통합되어 관리자가 그룹 정책과 다른 관리 도구를 통해 환경 전반에서 Exchange Online 기능을 관리할 수 있도록 합니다.
  
Exchange Online을 구독한 조직은 사용자에게 제공하는 메시징 서비스에 대한 제어 권한은 유지하면서도 온-프레미스 서버 소프트웨어에 대한 작업 부담을 덜 수 있습니다. 이 문서에서 설명한 Exchange Online 호스트 계획을 사용하여, 다중 고객을 동시에 지원하는 서버에서 전자 메일이 호스트됩니다. 이러한 서버는 Microsoft 데이터 센터에 있으며 회사 네트워크 내부 또는 인터넷을 통해 광범위한 디바이스의 사용자가 액세스할 수 있습니다.
  
계획에서 기능을 비교하는 데 필요한 강력한 도구는 [엔터프라이즈를 지원하기 위한 강력한 도구를 참조합니다.](https://products.office.com/business/compare-more-office-365-for-business-plans) Office 365 Germany의 요금제를 비교하려면 [Office 365 Germany 구독 요금제](https://go.microsoft.com/fwlink/?linkid=839016)를 참조하세요.
  
> [!TIP]
> Microsoft 서비스 설명에서 페이지를 내보내고 저장하고 인쇄할 수 있습니다. 콘텐츠 검색 결과를 [내보내는 방법에 대해 자세히 알아보겠습니다.](/office365/securitycompliance/export-search-results) 
  
## <a name="whats-new-in-exchange-admin-center"></a>Exchange 관리 센터의 새로운 기능

Exchange 관리 센터의 새로운 기능에 대한 자세한 내용은 Exchange 관리 센터의 새로운 [기능을 참조하세요.](/exchange/whats-new)
  
## <a name="plans-for-exchange-online"></a>Exchange Online

Microsoft 365 요구 사항을 가장 잘 충족하기 위해 다양한 계획으로 사용할 수 있습니다. 사용자가 구독을 사용하도록 설정하는 구독에 대한 자세한 Exchange Online 전체 구독 비교 표를 [참조하세요.](https://go.microsoft.com/fwlink/?linkid=2139145)
  
Exchange Online 서비스에 액세스하는 각 사용자는 구독 계획을 선택해야 하며, 각 사용자 구독에는 자체 사서함이 있습니다. 이러한 사서함의 폴더와 메시지는 Microsoft 데이터 센터에서 Exchange Server를 실행하는 컴퓨터에 있습니다.
  
회의실 및 공유 사서함에 대해서는 사용자의 구독이 필요하지 않습니다. 이러한 특수 사서함 유형은 로그인 자격 증명이 없는 대신, 위임을 통해 적절한 권한을 가진 정식 사용자가 이를 관리 및 액세스합니다.

**Microsoft 365 F1 사용자 사서함 사용 권한** <br/>
Microsoft 365 F1 사서함에 대한 권한을 포함하지 Exchange 않습니다. 전체 Teams 사용하려면 M365 F1 라이선스에 K1 서비스 Exchange Online 사용할 수 있습니다. Exchange Online K1 서비스 계획에서 사용자를 위해 사서함을 프로비전하기는 하지만 M365 F1 사용자는 사서함을 사용할 수 없습니다. 이러한 단계를 통해 웹용 Outlook 사용하지 [](/exchange/recipients-in-exchange-online/manage-user-mailboxes/enable-or-disable-outlook-web-app) 않도록 설정하고 사용자에게 다른 방법을 통해 Exchange 사서함에 액세스하지 않도록 요청하는 것이 좋습니다.
  
## <a name="system-requirements-for-exchange-online"></a>Exchange Online에 대한 시스템 요구 사항

시스템 요구 사항, 비즈니스, 교육 및 정부 조직에서 사용할 수 있는 월별 구독 기반 서비스는 Microsoft 365 및 Office [리소스를 참조하세요.](https://products.office.com/office-system-requirements/#Office365forBEG)
  
## <a name="storage-and-recipient-limits-for-exchange-online"></a>Storage 제한 및 받는 사람 Exchange Online

Exchange Online 구독 계획에서 사용할 수 있는 저장소 및 받는 사람 제한에 대한 자세한 내용은 Exchange Online [참조하세요.](exchange-online-limits.md)
  
## <a name="feature-availability"></a>기능 가용성

조직에 현재 Office 365 Small Business, Office 365 Small Business Premium 또는 Office 365 Midsize Business 구독이 있는 경우 Microsoft 365 관리 센터 메시지 센터를 방문하거나 공급자에게 문의하여 새 Microsoft 365 앱 계획이 미치는 영향에 대한 자세한 내용을 확인하십시오. 새로운 계획 패밀리에 대한 Microsoft 365 앱 자세한 내용은 중소기업을 위한 새 [요금제 를 참조합니다.](https://blogs.microsoft.com/blog/2014/10/02/new-office-365-plans-small-mid-sized-businesses-available-today)

서비스 가용성에 대한 자세한 Microsoft 365 Business Premium 서비스 [Microsoft 365 Business Premium 참조하세요.](../microsoft-365-service-descriptions/microsoft-365-business-service-description.md)<br/><br/>
  
| 기능 | Exchange Server 2013 | Exchange Server 2016 | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**[계획 및 배포](planning-and-deployment.md)**|||||||||
|하이브리드 배포 지원|예|예|예<sup>16</sup>|예<sup>16</sup>|예|예|예|예<sup>16</sup>|
|IMAP 마이그레이션 지원|예|예|예|예|예|예|예|예|
|지원되는 단독형 마이그레이션|예|예|예|예|예|예|예|예|
|미리 구성된 마이그레이션 지원|아니요|아니요|예|예|예|예|예|예|
|**[사용 권한](permissions.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Microsoft 365 Business Basic**|**Microsoft 365 Business Standard**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F3**|
|역할 기반 사용 권한|예|예|예|예|예|예|예|아니요|
|역할 그룹|예|예|예|예|예|예|예|아니요|
|역할 할당 정책|예|예|예|예|예|예|예|아니요|
|**[메시지 정책 및 규정 준수](message-policy-and-compliance.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Microsoft 365 Business Basic**|**Microsoft 365 Business Standard**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F3**|
|Exchange Online 기반 사서함 보관| 아니요|아니요|예|예<sup>9</sup>|예<sup>9</sup>|예<sup>9</sup>|예<sup>9</sup>|아니요|
|온-프레미스 사서함의 클라우드 기반 보관|예 <sup>1</sup>|예<sup>1</sup>|아니요|아니요|예|예|예|아니요|
|MRM(메시징 레코드 관리) |예|예|예|예|예|예|예|예|
|수동 보존 정책, 레이블 및 태그 |아니요|아니요|아니요|아니요|예|예|예|예|
|보관된 데이터 암호화(BitLocker)|예<sup>15</sup>|예<sup>15</sup>|예|예|예|예|예|예|
|Azure Information Protection을 사용한 IRM|아니요|예|아니요<sup>2</sup>|아니요<sup>2</sup>|아니요<sup>2</sup>|예|예|아니요<sup>2</sup>|
|Windows Server AD RMS를 사용한 IRM|예<sup>3</sup>|예<sup>3</sup>|예<sup>3</sup>|예<sup>3</sup>|예<sup>3</sup>|예<sup>3</sup>|예<sup>3</sup>|예<sup>3</sup>|
|Office 365 메시지 암호화|예<sup>13</sup>|예<sup>13</sup>|아니요<sup>2</sup>|아니요<sup>2</sup>|아니요<sup>2</sup>|예|예|아니요<sup>2</sup>|
|고객 키<sup>22</sup>|아니요|아니요|아니요|아니요|아니요|아니요|예|아니요|
|S/MIME|예<sup>15</sup>|예<sup>15</sup>|예|예|예|예|예|예|
|원본 위치 유지 및 소송 보존|예|예|아니요|아니요|아니요|예|예|아니요|
|원본 위치 eDiscovery|예<sup>20</sup>|예<sup>20</sup>|예<sup>20</sup>|예<sup>20</sup>|예<sup>20</sup>|예<sup>20</sup>|예<sup>20</sup>|예|
|Transport rules|예 <sup>4</sup>|예<sup>4</sup>|예<sup>4</sup>|예<sup>4</sup>|예<sup>4</sup>|예<sup>4</sup>|예<sup>4</sup>|예<sup>4</sup>|
|데이터 손실 방지|예 <sup>5, 14</sup>|예 <sup>5, 14</sup>|아니요|아니요|아니요|예|예|아니요|
|저널링|예|예|예|예|예|예|예|예|
|**[스팸 방지 및 맬웨어 방지 보호](anti-spam-and-anti-malware-protection.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Microsoft 365 Business Basic**|**Microsoft 365 Business Standard**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F3**|
|기본 제공 스팸 방지 보호 기능|예 <sup>6</sup>|예 <sup>6</sup>|예|예|예|예|예|예|
|Customize anti-spam policies|예. 단, PowerShell을 통해서만 가능|예. 단, PowerShell을 통해서만 가능|예|예|예|예|예|예 <sup>7</sup>|
|기본 제공 맬웨어 방지 보호 기능|예 <sup>8</sup>|예 <sup>8</sup>|예<sup>8</sup>|예<sup>8</sup>|예<sup>8</sup>|예<sup>8</sup>|예<sup>8</sup>|예<sup>8</sup>|
|Customize anti-malware policies|예|예|예|예|예|예|예|예 <sup>7</sup>|
|격리 - 관리자 관리|예|예|예|예|예|예|예|예 <sup>7</sup>|
|격리 - 최종 사용자 자기 관리|아니요|아니요|예|예|예|예|예|예|
|Office 365용 Microsoft Defender|아니요|아니요|아니요|아니요|아니요|아니요|예|아니요|
|**[메일 흐름](mail-flow.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Microsoft 365 Business Basic**|**Microsoft 365 Business Standard**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F3**|
|아웃바운드 메일의 사용자 지정 라우팅|예|예|예|예|예|예|예|예|
|Secure messaging with a trusted partner|예|예|예|예|예|예|예|예|
|Conditional mail routing|아니요|아니요|예|예|예|예|예|예|
|인바운드 안전한 목록에 파트너 추가|아니요|아니요|예|예|예|예|예|예|
|하이브리드 전자 메일 라우팅|예|예|예<sup>16</sup>|예<sup>16</sup>|예|예|예|예|
|**[받는 사람](recipients.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Microsoft 365 Business Basic**|**Microsoft 365 Business Standard**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F3**|
|용량 경고|예|예|예|예|예|예|예|예|
|Clutter|예|아니요|예|예|예|예|예|예|
|메일 설명|예|예|예|예|예|예|예|예|
|위임 액세스|예|예|예|예|예|예|예|아니요|
|받은 편지함 규칙|예|예|예|예|예|예|예|예|
|연결된 계정|예|예|예|예|예<sup>17</sup>|예<sup>17</sup>|예<sup>17</sup>|예<sup>17</sup>|
|비활성 사서함|아니요|아니요|아니요<sup>9</sup>|아니요<sup>9</sup>|아니요<sup>9</sup>|예|예|아니요 <sup>9</sup>|
|오프라인 주소록|예|예|예|예|예|예|예|예|
|주소록 정책|예|예|예|예|예|예|예|예|
|계층적 주소부|예|예|예|예|예|예|예|아니요|
|주소 목록 및 전체 주소 목록|예|예|예|예|예<sup>18</sup>|예<sup>18</sup>|예<sup>18</sup>|예<sup>18</sup>|
|Microsoft 365 그룹|아니요|아니요|예|예|예|예|예|예|
|메일 그룹|예|예|예|예|예|예|예|예|
|외부 연락처(전체)|예|예|예|예|예|예|예|예|
|유니버설 연락처 카드|예|예|예|예|예|예|예|예|
|소셜 네트워크와의 연락처 연결|예|예|예|예|예|예|예|예|
|리소스 사서함|예|예|예|예|예|예|예|예|
|회의실 관리|예|예|예|예|예|예|예|예|
|부재 중 회신|예|예|예|예|예|예|예|예|
|일정 공유|예|예|예|예|예|예|예|예|
|**[보고 기능 및 문제 해결 도구](reporting-features-and-troubleshooting-tools.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Microsoft 365 Business Basic**|**Microsoft 365 Business Standard**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F3**|
|Microsoft 365 관리 센터 보고서|아니요|아니요|예|예|예|예|예|예|
|Excel 통합 문서|아니요|아니요|예|예|예|예|예|예|
|웹 서비스 보고서|아니요|아니요|예|예|예|예|예|예|
|Message trace|아니요|예|예|예|예|예|예|예|
|감사 보고서|예|예|예|예|예|예|예|예 <sup>3</sup>|
|통합 메시징 보고서|예|예|아니요|아니요|아니요|예|예|아니요|
|**[공유 및 공동 작업](sharing-and-collaboration.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Microsoft 365 Business Basic**|**Microsoft 365 Business Standard**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F3**|
|페더링 공유(일정 게시 포함)|예|예|예|예|예|예|예|예|
|사이트 사서함|예<sup>10</sup>|예<sup>10</sup>|예<sup>11</sup>|예<sup>11</sup>|예<sup>11</sup>|예<sup>11</sup>|예<sup>11</sup>|예<sup>11</sup>|
|공용 폴더|예|예|예|예|예|예|예|아니요|
|**[클라이언트 및 모바일 장치](clients-and-mobile-devices.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Microsoft 365 Business Basic**|**Microsoft 365 Business Standard**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F3**|
|Windows용 Outlook <sup>21</sup>|예|예|예|예|예|예|예| 아니요|
|웹용 Outlook<sup>21</sup>|예|예|예|예|예|예|예|예|
|Outlook for Mac<sup>21</sup>|예|예|예|예|예|예|예| 아니요|
|iOS 및 Android용 Outlook<sup>21</sup>|예<sup>24</sup>|예<sup>24</sup>|예|예|예|예|예|예|
|Exchange ActiveSync|예|예|예|예|예|예|예|예|
|기본 모바일 및 보안 for Microsoft 365|아니요|아니요|예|예|예|예|예|예|
|POP 및 IMAP|예|예|예|예|예|예|예|예 <sup>12</sup>|
|SMTP|예|예|예|예|예|예|예|예|
|EWS 응용 프로그램 지원|예|예|예|예|예|예|예|아니요|
|**[음성 메시지 서비스](voice-message-services.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Microsoft 365 Business Basic**|**Microsoft 365 Business Standard**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F3**|
|음성 메일<sup>23</sup>|예|예|아니요|아니요|아니요|예|예|아니요|
|음성 메일과 타사 팩스<sup>23 간의 통합</sup>|예|예|아니요|아니요|아니요|예|예|아니요|
|타사 음성 메일 상호<sup>연결성 23</sup>|예|예|예|예|예|예|예|예|
|비즈니스용 Skype 통합|예|예|예|예|예|예|예|예|
|**[고가용성 및 비즈니스 연속성](high-availability-and-business-continuity.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Microsoft 365 Business Basic**|**Microsoft 365 Business Standard**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F3**|
|데이터 센터의 사서함 복제|아니요|아니요|예|예|예|예|예|예|
|삭제된 사서함 복구|예|예|예|예|예|예|예|예|
|삭제된 항목 복구|예|예|예|예|예|예|예|예|
|단일 항목 복구|예|예|예|예|예|예|예|아니요|
|**[상호 운용성, 연결 및 호환성](interoperability-connectivity-and-compatibility.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Microsoft 365 Business Basic**|**Microsoft 365 Business Standard**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F3**|
|비즈니스용 Skype OWA 및 Outlook|예|예|예|예|예|예|예|예|
|SharePoint 상호 연산|예|예|예|예|예|예|예|예|
|EWS 연결 지원<sup>25</sup>|예|예|예|예|예|예|예|예|
|SMTP 릴레이 지원|예|예|예|예|예|예|예|예|
|**[Exchange Online 설치 및 관리](exchange-online-setup-and-administration.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Microsoft 365 Business Basic**|**Microsoft 365 Business Standard**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F3**|
|Microsoft Office 365 포털 액세스|아니요|아니요|예|예|예|예|예|예|
|Microsoft 365 관리 센터 액세스|아니요|아니요|예|예|예|예|예|예|
|Exchange 관리 센터 액세스|예|예|예|예|예|예|예|예|
|원격 Windows PowerShell 액세스|예|예|예|예|예|예|예|예|
|모바일 장치에 대한 ActiveSync 정책|예|예|예|예|예|예|예|예|
|사용 현황 보고|예|예|예|예|예|예|예|예|
|**서비스 확장 - 사용자 지정, 추가 기능 및 리소스**|**Exchange Server 2013**|**Exchange Server 2016**|**Microsoft 365 Business Basic**|**Microsoft 365 Business Standard**|**Office 365 Enterprise E1**|**Office 365 Enterprise E3**|**Office 365 Enterprise E5**|**Office 365 Enterprise F3**|
|Outlook 추가 기능 및 MAPI Outlook 추가 기능|예<sup>19</sup>|예|예<sup>19</sup>|예<sup>19</sup>|예<sup>19</sup>|예<sup>19</sup>|예<sup>19</sup>|아니요|

<sup>1</sup> 클라우드 Exchange Online Archiving 보관 사서함이 있는 각 사서함 사용자에 대해 Exchange Online Archiving 구독이 필요합니다. <br/>
<sup>2</sup> Azure Information Protection은 포함되어 있지 않지만 별도의 추가 기능으로 구매할 수 있으며 지원되는 IRM(정보 권한 관리) 기능을 사용하도록 설정할 수 있습니다. 일부 Azure Information Protection 기능을 사용하려면 엔터프라이즈용 Microsoft 365 앱 구독이 필요합니다. Microsoft 365 Business Basic, Microsoft 365 Business Standard, Office 365 Enterprise E1, Office 365 Education 또는 F3에 Office 365 Enterprise 포함되어 있지 않습니다. <br/>
<sup>3</sup> Windows Server AD RMS는 지원되는 IRM 기능을 사용하기 위해 별도로 구입하여 관리해야 하는 온-프레미스 서버입니다. <br/>
<sup>4</sup> 전송 규칙은 유연한 기준으로 구성됩니다. 이 조건을 기반으로 조건 및 예외 및 수행할 작업을 정의할 수 있습니다. 사용 가능한 조건 및 작업은 2013과 Exchange Online Microsoft Exchange Server 다릅니다. 사용 가능한 기준 및 작업 목록은 각 제품에 대한 해당 조건 및 작업 항목을 참조하세요. <br/>
<sup>5</sup> Exchange 2013의 경우 DLP를 사용하려면 EXCHANGE ENTERPRISE CAL(클라이언트 액세스 라이선스)이 필요합니다. CA 및 서버 라이선스에 대한 자세한 내용은 라이선스 [EXCHANGE FAQ를 참조하세요.](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business) <br/>
<sup>6</sup> Exchange Server 2013에는 2010과 동일한 기본 제공 스팸 방지 기능이 Exchange Server 있습니다. Exchange 호스팅된 스팸 필터링의 이점에 대한 자세한 내용은 [Benefits of Anti-Spam Features in Exchange Online Protection Over Exchange Server 2013을](/exchange/benefits-of-anti-spam-features-in-exchange-online-protection-over-exchange-server-2013-exchange-2013-help)참조하십시오. <br/>
<sup>7</sup> EAC(Exchange 관리 인터페이스에 대한 직접 액세스를 통해서만 액세스할 수 있습니다. <br/>
<sup>8</sup> Exchange Server 2013에서는 Microsoft 맬웨어 방지 엔진만 사용 합니다. Exchange Online에서는 여러 맬웨어 방지 엔진을 사용하여 인바운드, 아웃바운드 및 내부 메시지에서 맬웨어를 검사합니다. <br/>
<sup>9</sup> 비활성 사서함 또는 보관 기능이 필요한 각 사서함에 대해 EOA 구독을 별도로 구매할 수 있습니다.<br/>
<sup>10 SharePoint</sup> 조직에 배포해야 Exchange 합니다. <br/>
<sup>11</sup> SharePoint Online이 구독 계획에 포함되어야 합니다. <br/>
<sup>12</sup> POP가 지원되지만 IMAP는 지원되지 않습니다. <br/>
<sup>13</sup> Azure Information Protection을 Exchange Server 2013의 프레미스 고객에게 지원됩니다. Office 365 메시지 암호화 전자 메일 필터링을 위해 Exchange Online 또는 하이브리드 메일 흐름을 설정하여 Exchange Online Protection 전자 메일을 라우팅해야 합니다. <br/>
<sup>14</sup> Exchange Server 2013 고객은 OWA 및 장치용 OWA의 문서 지문 및 정책 팁 액세스하려면 SP1을 다운로드하여 설치해야 합니다. <br/>
<sup>15</sup> BitLocker 드라이브 암호화는 Exchange Server 2013에서 지원되지만 관리자는 이 기능을 사용하도록 설정해야 합니다. <br/>
<sup>16</sup> Microsoft 365 Business Basic, Microsoft 365 Business Standard 및 Office 365 Enterprise F3은프레미스 서버와의 사용에 대한 액세스 권한을 제공하지 않습니다. 규정을 준수하려면 고객은 적절한 CA를 구매했거나 이전에 이러한 액세스 권한을 제공하는 Enterprise SKU로 업그레이드해야 합니다. <br/>
<sup>17</sup> 연결된 계정은 POP IMAP 계정에 대해 &amp; 지원되지만 Outlook.com(Hotmail)에서는 사용하지 않도록 설정됩니다. <br/>
<sup>18</sup> Exchange Online PowerShell에서 cmdlet을 사용하여 기본 주소 목록을 사용자 지정하고 기본 GAL(전체 주소 목록)은 지원되지 않습니다. <br/>
<sup>19</sup> 일부 타사 웹 파트 및 추가 기능을 사용할 수 없습니다. <br/>
<sup>20</sup> eDiscovery의 경우, 클라우드와의 별도 쿼리가 필요합니다. <br/>
<sup>21</sup> 이 표는 클라이언트가 연결된 계획에서 작동하는지 여부를 나타냅니다. 이러한 계획 구매에 클라이언트가 반드시 포함되어야 하는 것을 의미하지는 않습니다. <br/>
<sup>22</sup> 자세한 내용은 고객 키를 사용하여 [서비스 암호화를 참조하세요.](/office365/securitycompliance/controlling-your-data-using-customer-key) <br/>
<sup>23</sup> Exchange Online 운영 SBC에서 직접 연결을 통해 타사 PBX 시스템에 대한 UM 지원은 2019년 4월에 종료됩니다. 자세한 내용은 Exchange 통합 메시징에서 세션 경계 컨트롤러에 대한 지원 중단을 Exchange Online [참조하세요.](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/New-date-for-discontinuation-of-support-for-Session-Border/ba-p/607853) <br/>
<sup>24</sup> 엔터프라이즈용 Microsoft 365 앱 2013 및 Exchange Server 2016의 경우 구독이 Exchange Server 필요합니다.<br/>
<sup>EWS</sup> 응용 프로그램 가장에 적용된 25 EWS 응용 프로그램 지원<br/>

## <a name="feature-availability-across-exchange-online-standalone-plans"></a>Exchange Online 독립 실행형 계획에서의 기능 가용성

| 기능 | Exchange Server 2013 | Exchange Server 2016 | Exchange Online 계획 &nbsp; 1 | Exchange Online 계획 &nbsp; 2 | Exchange Online Kiosk |
|:-----|:-----|:-----|:-----|:-----|:-----|
|**[계획 및 배포](planning-and-deployment.md)**||||||
|하이브리드 배포 지원|예|예|예|예|예<sup>23</sup>|
|IMAP 마이그레이션 지원|예|예|예|예|예|
|지원되는 단독형 마이그레이션|예|예|예|예|예|
|미리 구성된 마이그레이션 지원|아니요|아니요|예|예|예|
|**[사용 권한](permissions.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Exchange Online 계획 1**|**Exchange Online 계획 2**|**Exchange Online Kiosk**|
|역할 기반 사용 권한|예|예|예|예|아니요|
|역할 그룹|예|예|예|예|아니요|
|역할 할당 정책|예|예|예|예|아니요|
|**[메시지 정책 및 규정 준수](message-policy-and-compliance.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Exchange Online 계획 &nbsp; 1**|**Exchange Online 계획 &nbsp; 2**|**Exchange Online Kiosk**|
|Exchange Online 기반 사서함 보관|예|아니요|예|예|아니요|
|온-프레미스 사서함의 클라우드 기반 보관|예 <sup>5</sup>|예 <sup>5</sup>|아니요|예|아니요|
|MRM(메시징 레코드 관리) |예|예|예|예|예|
|수동 보존 정책, 레이블 및 태그|아니요|아니요|예|예|예|
|보관된 데이터 암호화(BitLocker)|예<sup>16</sup>|예<sup>16</sup>|예|예|예|
|Azure Information Protection을 사용한 IRM|아니요|예|아니요<sup>11</sup>|아니요<sup>11</sup>|아니요<sup>11</sup>|
|Windows Server AD RMS를 사용한 IRM|예<sup>12</sup>|예<sup>12</sup>|예<sup>12</sup>|예<sup>12</sup>|예<sup>12</sup>|
|Office 365 메시지 암호화|예<sup>13</sup>|예<sup>13</sup>|아니요<sup>11</sup>|아니요<sup>11</sup>|아니요<sup>11</sup>|
|S/MIME|예<sup>15</sup>|예<sup>15</sup>|예|예|예|
|원본 위치 유지 및 소송 보존|예|예|<sup>아니요 17</sup>|예|아니요|
|원본 위치 eDiscovery|예<sup>22</sup>|예<sup>22</sup>|예<sup>22</sup>|예<sup>22</sup>|예<sup>22</sup>|
|전송 규칙|예 <sup>1</sup>|예 <sup>1</sup>|예 <sup>1</sup>|예 <sup>1</sup>|예 <sup>1</sup>|
|데이터 손실 방지|예 <sup>10, 14</sup>|예 <sup>10, 14</sup>|아니요|예|아니요|
|저널링|예|예|예|예|예|
|**[스팸 방지 및 맬웨어 방지 보호](anti-spam-and-anti-malware-protection.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Exchange Online 계획 &nbsp; 1**|**Exchange Online 계획 &nbsp; 2**|**Exchange Online Kiosk**|
|기본 제공 스팸 방지 보호 기능|예 <sup>2</sup>|예 <sup>2</sup>|예|예|예|
|Customize anti-spam policies|예. 단, PowerShell을 통해서만 가능|예. 단, PowerShell을 통해서만 가능|예|예|예 <sup>8</sup>|
|기본 제공 맬웨어 방지 보호 기능|예 <sup>7</sup>|예 <sup>7</sup>|예<sup>7</sup>|예<sup>7</sup>|예<sup>7</sup>|
|Customize anti-malware policies|예|예|예|예|예 <sup>8</sup>|
|격리 - 관리자 관리|예|예|예|예|예 <sup>8</sup>|
|격리 - 최종 사용자 자기 관리|아니요|아니요|예|예|예|
|**[메일 흐름](mail-flow.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Exchange Online 계획 &nbsp; 1**|**Exchange Online 계획 &nbsp; 2**|**Exchange Online Kiosk**|
|아웃바운드 메일의 사용자 지정 라우팅|예|예|예|예|예|
|Secure messaging with a trusted partner|예|예|예|예|예|
|Conditional mail routing|아니요|아니요|예|예|예|
|인바운드 안전한 목록에 파트너 추가|아니요|아니요|예|예|예|
|하이브리드 전자 메일 라우팅|예|예|예|예|예|
|**[받는 사람](recipients.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Exchange Online 계획 &nbsp; 1**|**Exchange Online 계획 &nbsp; 2**|**Exchange Online Kiosk**|
|용량 경고|예|예|예|예|예|
|Clutter|아니요|아니요|예|예|예|
|메일 설명|예|예|예|예|예|
|위임 액세스|예|예|예|예|아니요|
|받은 편지함 규칙|예|예|예|예|예|
|연결된 계정|예|예|예<sup>19</sup>|예<sup>19</sup>|예<sup>19</sup>|
|비활성 사서함|아니요|아니요|아니요 <sup>6</sup>|예|아니요 <sup>6</sup>|
|오프라인 주소록|예|예|예|예|예|
|주소록 정책|예|예|예|예|예|
|계층적 주소부|예|예|예|예|아니요|
|주소 목록 및 전체 주소 목록|예|예|예<sup>20</sup>|예<sup>20</sup>|예<sup>20</sup>|
|Office 365 그룹|아니요|아니요|예<sup>24</sup>|예<sup>24</sup>|아니요|
|메일 그룹|예|예|예|예|예|
|외부 연락처(전체)|예|예|예|예|예|
|유니버설 연락처 카드|예|예|예|예|예|
|소셜 네트워크와의 연락처 연결|예|예|예|예|예|
|리소스 사서함|예|예|예|예|예|
|회의실 관리|예|예|예|예|예|
|부재 중 회신|예|예|예|예|예|
|일정 공유|예|예|예|예|예 <sup>18</sup>|
|**[보고 기능 및 문제 해결 도구](reporting-features-and-troubleshooting-tools.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Exchange Online 계획 &nbsp; 1**|**Exchange Online 계획 &nbsp; 2**|**Exchange Online Kiosk**|
|Microsoft 365 관리 센터 보고서|아니요|아니요|예|예|예|
|Excel 통합 문서|아니요|아니요|예|예|예|
|웹 서비스 보고서|아니요|아니요|예|예|예|
|Message trace|아니요|예|예|예|예 <sup>8</sup>|
|감사 보고서|예|예|예|예|예 <sup>8</sup>|
|통합 메시징 보고서|예|예|아니요|예|아니요|
|**[공유 및 공동 작업](sharing-and-collaboration.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Exchange Online 계획 &nbsp; 1**|**Exchange Online 계획 &nbsp; 2**|**Exchange Online Kiosk**|
|페더레이션 공유|예|예|예|예|예|
|사이트 사서함|예 <sup>3</sup>|예 <sup>3</sup>|예 <sup>4</sup>|예 <sup>4</sup>|예 <sup>4</sup>|
|공용 폴더|예|예|예|예|아니요|
|**[클라이언트 및 모바일 장치](clients-and-mobile-devices.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Exchange Online 계획 &nbsp; 1**|**Exchange Online 계획 &nbsp; 2**|**Exchange Online Kiosk**|
|Microsoft Outlook|예|예|예|예|아니요|
|웹용 Outlook|예|예|예|예|예|
|Exchange ActiveSync|예|예|예|예|예|
|POP 및 IMAP|예|예|예|예|예 <sup>9</sup>|
|SMTP|예|예|예|예|예|
|EWS 응용 프로그램 지원|예|예|예|예|아니요|
|Outlook for Mac|예|예|예|예|아니요|
|iOS 및 Android용 Outlook<sup>21</sup>|예<sup>25</sup>|예<sup>25</sup>|예|예|예|
|**[음성 메시지 서비스](voice-message-services.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Exchange Online 계획 &nbsp; 1**|**Exchange Online 계획 &nbsp; 2**|**Exchange Online Kiosk**|
|음성 사서함|예|예|아니요|예|아니요|
|타사 음성 메일 상호 연결성|예|예|예|예|예|
|비즈니스용 Skype 통합|예|예|예|예|예|
|**[고가용성 및 비즈니스 연속성](high-availability-and-business-continuity.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Exchange Online 계획 &nbsp; 1**|**Exchange Online 계획 &nbsp; 2**|**Exchange Online Kiosk**|
|데이터 센터에서 사서함 복제|아니요|아니요|예|예|예|
|삭제된 사서함 복구|예|예|예|예|예|
|삭제된 항목 복구|예|예|예|예|예|
|단일 항목 복구|예|예|예|예|아니요|
|**[상호 운용성, 연결 및 호환성](interoperability-connectivity-and-compatibility.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Exchange Online 계획 &nbsp; 1**|**Exchange Online 계획 &nbsp; 2**|**Exchange Online Kiosk**|
|비즈니스용 Skype OWA 및 Outlook|예|예|예|예|예|
|SharePoint 상호 연산|예|예|예|예|예|
|EWS 연결 지원<sup>26</sup>|예|예|예|예|예|
|SMTP 릴레이 지원|예|예|예|예|예|
|**[Exchange Online 설치 및 관리](exchange-online-setup-and-administration.md)**|**Exchange Server 2013**|**Exchange Server 2016**|**Exchange Online 계획 &nbsp; 1**|**Exchange Online 계획 &nbsp; 2**|**Exchange Online Kiosk**|
|Microsoft Office 365 포털 액세스|아니요|아니요|예|예|예|
|Microsoft 365 관리 센터 액세스|아니요|아니요|예|예|예|
|Exchange 관리 센터 액세스|예|예|예|예|예 <sup>8</sup>|
|원격 Windows PowerShell 액세스|예|예|예|예|예|
|모바일 장치에 대한 ActiveSync 정책|예|예|예|예|예|
|사용 현황 보고|예|예|예|예|예|
|**Extending the Service - Customization, Add-ins, and Resources**|**Exchange Server 2013**|**Exchange Server 2016**|**Exchange Online 계획 &nbsp; 1**|**Exchange Online 계획 &nbsp; 2**|**Exchange Online Kiosk**|
|웹용 Outlook 웹 파트|예|예|예|예|예|
|Outlook 추가 기능 및 MAPI Outlook 추가 기능|예|예|예<sup>21</sup>|예<sup>21</sup>|아니요|

<sup>1</sup> 전송 규칙은 유연한 기준으로 구성됩니다. 이 조건을 기반으로 조건 및 예외 및 수행할 작업을 정의할 수 있습니다. 사용 가능한 조건 및 작업은 2013과 Exchange Online Microsoft Exchange Server 다릅니다. 사용 가능한 기준 및 작업 목록은 각 제품에 대한 해당 조건 및 작업 항목을 참조하세요. <br/>
<sup>2</sup> 프레미스 제품에서 호스팅되는 스팸 Exchange 이점에 대한 자세한 내용은 [Exchange Online Protection Over Exchange Server 2013의](/exchange/benefits-of-anti-spam-features-in-exchange-online-protection-over-exchange-server-2013-exchange-2013-help)스팸 방지 기능의 이점을 참조하세요. <br/>
<sup>3</sup> SharePoint 조직에 배포해야 Exchange 합니다. <br/>
<sup>4</sup> SharePoint Online이 구독 계획에 포함되어야 합니다. <br/>
<sup>5</sup> 클라우드 Exchange Online Archiving 보관 사서함이 있는 각 사서함 사용자에 대해 Exchange Online Archiving 구독이 필요합니다. <br/>
<sup>6</sup> Exchange Online Archiving 사서함 기능이 필요한 각 사서함에 대해 별도 구독을 구입할 수 있습니다. <br/>
<sup>7</sup> Exchange Server 2013에서는 Microsoft 맬웨어 방지 엔진만 사용 합니다. Exchange Online에서는 여러 맬웨어 방지 엔진을 사용하여 인바운드, 아웃바운드 및 내부 메시지에서 맬웨어를 검사합니다. <br/>
<sup>8</sup> EAC(Exchange 관리 인터페이스)에 직접 액세스할 수만 있습니다. <br/>
<sup>9</sup> IMAP는 지원되지 않습니다. <br/>
<sup>10</sup> Exchange 2013 이상에서는 DLP에 EXCHANGE ENTERPRISE CAL(클라이언트 액세스 라이선스)이 필요합니다. CA 및 서버 라이선스에 대한 자세한 내용은 라이선스 [EXCHANGE FAQ를 참조하세요.](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business) <br/>
<sup>11</sup> Azure Information Protection은 포함되어 있지 않지만 별도의 추가 기능으로 구매할 수 있으며 지원되는 IRM(정보 권한 관리) 기능을 사용하도록 설정할 수 있습니다. 일부 Azure Information Protection 기능을 사용하려면 엔터프라이즈용 Microsoft 365 앱 구독이 필요합니다. Microsoft 365 Business Basic, Microsoft 365 Business Standard, Office 365 Enterprise E1, Office 365 Education 또는 F3에 Office 365 Enterprise 포함되어 있지 않습니다. Office 365 메시지 암호화 Azure Information Protection에 따라 다를 수 있습니다. <br/>
<sup>12</sup> Windows Server AD RMS는 지원되는 IRM 기능을 사용하려면 별도로 구입하고 관리해야 하는 사내 서버입니다. <br/>
<sup>13</sup> Azure Information Protection을 Exchange Server 2013 이상을 실행하는 고객에게 지원됩니다. Office 365 메시지 암호화 전자 메일 필터링을 위해 Exchange Online 또는 하이브리드 메일 흐름을 설정하여 Exchange Online Protection 전자 메일을 라우팅해야 합니다. <br/>
<sup>14</sup> Exchange Server 2013 이상을 실행하는 고객은 OWA 및 장치용 OWA의 문서 지문 및 정책 팁 액세스하려면 최신 CU(누적 업데이트) 또는 바로 이전 CU를 다운로드하여 설치해야 합니다. <br/>
<sup>15</sup> 2013 이상을 Exchange Server 고객이 사용할 수 있습니다. <br/>
<sup>16</sup> BitLocker 드라이브 암호화는 Exchange Server 2013에서 지원되지만 관리자는 이 기능을 사용하도록 설정해야 합니다. <br/>
<sup>17</sup> Exchange Online 계획 1의 사서함 및 보관에 대한 크기 [제한이 있습니다.](./exchange-online-limits.md) Exchange Online용 Exchange Online Archiving 추가 기능에서는 무제한 클라우드 기반 보관 및 [In-Place Hold를 추가합니다.](../exchange-online-archiving-service-description/compliance-and-security-features.md#in-place-hold-and-litigation-hold) <br/>
<sup>18</sup> Exchange Online Kiosk OWA를 통해서만 일정에 액세스하거나 공유할 수 있습니다. <br/>
<sup>19</sup> 연결된 계정은 POP IMAP 계정에 대해 &amp; 지원되지만 Outlook.com(Hotmail)에는 사용하지 않도록 설정됩니다. <br/>
<sup>20</sup> Exchange Online PowerShell에서 cmdlet을 사용하여 기본 주소 목록을 사용자 지정하고 기본 GAL(전체 주소 목록)은 지원되지 않습니다. <br/>
<sup>21</sup> 일부 타사 웹 파트 및 추가 기능을 사용할 수 없습니다. <br/>
<sup>22</sup> eDiscovery의 경우, 사내 및 클라우드에 대한 별도의 쿼리가 필요합니다. <br/>
<sup>23</sup> Exchange Online Kiosk 서버의 사용에 대한 액세스 권한을 제공하지 않습니다. 규정을 준수하려면 고객은 적절한 CA를 구매했거나 이전에 이러한 액세스 권한을 제공하는 Enterprise SKU로 업그레이드해야 합니다. <br/>
<sup>24 Microsoft 365</sup> 기능이 있는 그룹을 사용할 수 있습니다.<br/>
<sup>25</sup> 2013 및 엔터프라이즈용 Microsoft 365 앱 2016의 경우 Exchange Server 구독이 Exchange Server 합니다.<br/>
<sup>EWS</sup> 응용 프로그램 가장에 적용되는 26 EWS 응용 프로그램 지원