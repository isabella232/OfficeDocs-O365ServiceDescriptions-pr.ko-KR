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
ms.localizationpriority: medium
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 7a83da3c-3b6d-4f86-ad4d-6104707cd0ec
description: Exchange Online 포함하는 구독의 기능 비교를 찾고 있나요? 그렇다면 Exchange Online 서비스 설명 문서가 필요할 것입니다. 저장소 및 받는 사람 요구 사항 뿐 아니라 시스템 요구 사항에 대해서도 알 수 있습니다.
ms.openlocfilehash: 9bd7516e126af8b656ef8af1c6386adaaaa2a4eb
ms.sourcegitcommit: 97f6183334bb103e7b0171cb0ceebcddac25e24f
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/21/2022
ms.locfileid: "65019310"
---
# <a name="exchange-online-service-description"></a>Exchange Online 서비스 설명

Microsoft Exchange Online PC, 웹 및 모바일 디바이스에서 전자 메일, 일정, 연락처 및 작업을 제공하는 호스팅된 메시징 솔루션입니다. Azure Active Directory 완전히 통합되므로 관리자는 그룹 정책 및 기타 관리 도구를 사용하여 환경 전체에서 Exchange Online 기능을 관리할 수 있습니다.

Exchange Online 구독하는 조직은 사용자에게 제공하는 메시징 서비스에 대한 제어권을 유지합니다. 이 문서에서 설명한 Exchange Online 호스트 계획을 사용하여, 다중 고객을 동시에 지원하는 서버에서 전자 메일이 호스트됩니다. 이러한 서버는 Microsoft 데이터 센터에 저장되며 회사 네트워크 내부 또는 인터넷을 통해 광범위한 디바이스에서 사용자가 액세스할 수 있습니다.

## <a name="available-plans-for-exchange-online"></a>Exchange Online 사용 가능한 계획

Microsoft 365 조직의 요구 사항을 가장 잘 충족하기 위한 다양한 계획에서 사용할 수 있습니다. 사용자가 Exchange Online 수 있도록 하는 구독에 대한 자세한 계획 정보는 [전체 구독 비교 테이블을 참조하세요](https://go.microsoft.com/fwlink/?linkid=2139145).

> [!NOTE]
> Exchange Online 서비스에 액세스하는 각 사용자는 구독 계획을 선택해야 하며, 각 사용자 구독에는 자체 사서함이 있습니다. 이러한 사서함의 폴더 및 메시지는 Microsoft 데이터 센터에 상주합니다. 회의실 및 공유 사서함에는 사용자 구독이 필요하지 않습니다. 이러한 특수 사서함 유형에는 로그인 자격 증명이 없으며, 대신 적절한 권한이 있는 라이선스가 있는 사용자가 위임을 통해 관리하고 액세스합니다. Microsoft 365 F1 Exchange 사서함에 대한 권한이 포함되지 않습니다. 전체 Teams 환경을 사용하도록 설정하기 위해 Microsoft 365 F1 라이선스에 Exchange Online K1 서비스 계획을 사용하도록 설정할 수 있습니다. Exchange Online K1 서비스 계획은 사용자의 사서함을 프로비전하지만 Microsoft 365 F1 사용자는 사서함을 사용할 수 없습니다. [이러한 단계를](/exchange/recipients-in-exchange-online/manage-user-mailboxes/enable-or-disable-outlook-web-app) 통해 Outlook na Web 사용하지 않도록 설정하고 사용자에게 다른 방법을 통해 Exchange 사서함에 액세스하지 않도록 요청하는 것이 좋습니다.

## <a name="feature-availability-including-standalone-plans"></a>기능 가용성(독립 실행형 계획 포함)

다음 표에서는 계획에서 사용할 수 있는 주요 Exchange Online 기능을 나열합니다(특정 주의 사항이 적용됩니다. 자세한 내용은 각주를 참조하세요. 이 테이블은 예고 없이 변경될 수 있음). 계획 전반에 걸친 최신 기능의 전체 목록은 [엔터프라이즈를 지원하는 강력한 도구를 참조하세요](https://products.office.com/business/compare-more-office-365-for-business-plans). Microsoft 365 비즈니스 계획(기본, 표준 및 프리미엄)의 기능 가용성은 [Microsoft 365 비즈니스 플랜](https://aka.ms/M365BusinessPlans)을 참조하거나 Microsoft 365 관리 센터 메시지 센터를 방문하거나 공급자에게 문의하여 새 Microsoft 365 应用版 계획이 사용자에게 미치는 영향에 대한 자세한 내용을 확인하세요.

### <a name="features-available-to-all-plans"></a>모든 플랜에서 사용할 수 있는 기능

이러한 기능은 모든 비즈니스(기본, 표준 및 프리미엄), Enterprise(E1, E3, E5 및 F3) 및 Exchange Online 플랜(1, 2 및 키오스크)에 사용할 수 있습니다. 주의 사항은 각주를 참조하여 자세한 내용을 참조하세요.

- [**스팸 방지 및 맬웨어 방지 보호**](/exchange/antispam-and-antimalware/antispam-and-antimalware)(Exchange 관리 센터 관리 인터페이스에 직접 액세스를 통해)**:** 기본 제공 스팸 방지 및 맬웨어 방지 보호(여러 맬웨어 방지 엔진을 사용하여 맬웨어에 대한 인바운드, 아웃바운드 및 내부 메시지 검색), 사용자 지정된 스팸 방지 및 맬웨어 방지 정책, 격리 - 관리자 관리 및 격리 - 최종 사용자 자체 관리.
- [**Exchange Online 설정 및 관리**](/exchange/architecture/client-access/exchange-admin-center)**:** Microsoft 365 포털 및 관리 센터 액세스, Exchange 관리 센터 액세스, 원격 Windows PowerShell 액세스, 모바일 디바이스에 대한 ActiveSync 정책, [사용 현황 보고](/exchange/monitoring/monitoring)
- [**고가용성 및 비즈니스 연속성**](/exchange/high-availability/high-availability)**:** 데이터 센터의 사서함 복제, 단일 항목 복구(F3 및 키오스크 계획에 사용할 수 없음) [사서함을 삭제하고 항목 복구를 삭제](/exchange/recipients/disconnected-mailboxes/restore-deleted-mailboxes)했습니다.
- [**상호 운용성, 연결 및 호환성**](/exchange/security-and-compliance/interoperability-connectivity-and-compatiblity)**:** OWA 및 Outlook Skype for Business 현재 상태, SharePoint 상호 운용성, EWS 연결 지원(가장에 적용된 EWS 앱 지원), SMTP 릴레이 지원.
- [**메일 흐름**](/exchange/security-and-compliance/mail-flow-rules/mail-flow-rules)**:** 아웃바운드 메일의 사용자 지정 라우팅, 신뢰할 수 있는 파트너와의 보안 메시징, 인바운드 안전 목록에 파트너 추가, 조건부 메일 및 하이브리드 전자 메일 라우팅(CAL 또는 Enterprise SKU로 업그레이드하면 액세스 권한을 제공함).
- [**계획 및 배포**](/exchange/plan-and-deploy/plan-and-deploy)**:** [하이브리드 배포](/exchange/hybrid-deployment/hybrid-deployment) 지원(CAL 또는 Enterprise SKU로 업그레이드하면 비즈니스 및 F3 계획에 대한 액세스 권한 제공), [IMAP](/exchange/mailbox-migration/migrating-imap-mailboxes/migrating-imap-mailboxes), 중단 및 [단계적 마이그레이션](/exchange/mailbox-migration/what-to-know-about-a-staged-migration)이 지원됩니다.
- [**보고 기능 및 문제 해결 도구**](/office365/servicedescriptions/exchange-online-service-description/reporting-features-and-troubleshooting-tools)**:** Microsoft 365 관리 센터 보고서, Excel 보고 통합 문서, 웹 서비스 보고서, 통합 메시징 보고서(E3/E5 및 계획 2만 해당). 메시지 추적 및 [감사 보고서는](/exchange/exchange-auditing-reports-exchange-2013-help) EAC(Exchange 관리 센터) 관리 인터페이스에 직접 액세스하여 액세스할 수 있습니다.
- [**받는 사람**](/exchange/recipients-in-exchange-online/recipients-in-exchange-online)**:** 용량 경고, 낮은 우선 순위, 메일 설명서, 받은 편지함 규칙, 오프라인 주소록, 주소록 정책, 메일 그룹, 외부 연락처(전역), 유니버설 연락처 카드, 소셜 네트워크와의 연락처 연결, 리소스 사서함, 회의실 관리, 부재 중 회신, 일정 공유(키오스크 일정은 OWA를 통해서만 액세스하거나 공유할 수 있음).
- [**공유 및 공동 작업**](/exchange/sharing/sharing)**:** 페더레이션된 공유(일정 게시 포함), 사이트 사서함(SharePoint Online을 포함 및 배포해야 함) 및 공용 폴더(F3 및 키오스크 플랜에는 사용할 수 없음).
- [**음성 메시지 서비스**](/exchange/plan-and-deploy/integration-with-sharepoint-and-skype/integration-with-sharepoint-and-skype)**:** Skype for Business 통합 타사 음성 메일 상호 운용성. E3/E5 및 플랜 2만 음성 메일 및 타사 음성 메일/팩스 통합을 제공합니다. 직접 연결을 통한 타사 PBX 시스템의 경우 [Exchange Online 통합 메시징에서 세션 테두리 컨트롤러에 대한 지원 중단을 참조하세요](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/New-date-for-discontinuation-of-support-for-Session-Border/ba-p/607853).

## <a name="features-available-to-some-plans"></a>일부 플랜에서 사용할 수 있는 기능

이러한 기능은 일부 플랜에서 사용할 수 있습니다. 자세한 내용은 각주를 참조하세요(이 표는 예고 없이 변경될 수 있음).

| 기능 | 설명 | Microsoft 365 Business Basic, Business Standard | Microsoft 365 Business Premium | Office 365 E1 | Microsoft 365 E3/E5 & Office 365 E3/E5 | Microsoft 365 F3 & Office 365 F3 | Exchange Online 계획 2 | Exchange Online 요금제 1 | Exchange Online Kiosk |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**[클라이언트 및 모바일 장치](/exchange/clients-and-mobile-in-exchange-online/clients-and-mobile-in-exchange-online)**|iOS 및 <sup>Android1</sup>, Exchange ActiveSync 및 SMTP용 Outlook Outlook na Web <sup>1</sup>|예|예|예|예|예|예|예|예|
||POP 및 IMAP|예|예|예|예|예<sup>2</sup>|예|예|예<sup>2</sup>|
||EWS 애플리케이션 지원, Windows <sup>1</sup>용 Outlook, Outlook til Mac <sup>1</sup>|예|예|예|예|아니요|예|예|아니요|
||Microsoft 365 기본 모바일 및 보안|예|예|예|예|예||||
|**[메시지 정책 및 규정 준수](/exchange/policy-and-compliance/policy-and-compliance)**|[Exchange Online용 Exchange Online Archiving](/office365/servicedescriptions/exchange-online-archiving-service-description/archive-features)|아니요|아니요|아니요|예|아니요|예|아니요|아니요|
||[Exchange Server용 Exchange Online Archiving](/office365/servicedescriptions/exchange-online-archiving-service-description/archive-features)|아니요|아니요|아니요|예|아니요|예|아니요|아니요|
||[수동 보존 정책, 레이블 및 태그](/exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies)|아니오|예|예|예|예|예|예|예|
||[Azure Information Protection을 사용한 IRM](/exchange/policy-and-compliance/in-place-archiving/in-place-archiving)|아니요|아니요|아니요|예|아니요|아니요|아니요|아니요|
||기본 메시지 암호화|예|예|예|예|예|예|예|예|
||고급 메시지 암호화|아니요|아니요|아니요|예|아니요|아니요|아니요|아니요|
||고객 키|아니요|아니요|아니요|예|아니요|아니요|아니요|아니요|
||In-Place 보류, 소송 보존|아니요|예|아니요|예|아니요|예|아니요|아니요|
||Data loss prevention|아니오|예|아니요|예|아니요|아니요|아니요|아니요|
||미사용 데이터 암호화(BitLocker), MRM(메시징 레코드 관리), S/MIME, 저널링, eDiscovery 콘텐츠 검색<sup>3</sup>, 전송 규칙<sup>4</sup>|예|예|예|예|예|예|예|예|
||Windows Server AD <sup>RMS5</sup>를 사용하는 IRM 지원|예|예|예|예|예|예|예|예|
|**[사용 권한](/exchange/permissions-exo/permissions-exo)**|역할 기반 권한, 역할 그룹 및 역할 할당 정책|예|예|예|예|아니요|예|예|아니요|
|**[받는 사람](/exchange/recipients-in-exchange-online/recipients-in-exchange-online)**|액세스 및 계층 구조 주소록 위임|예|예|예|예|아니요|예|예|아니요|
||비활성 사서함|아니요|아니요|아니요|예|아니요|예|아니요|아니요|
||Microsoft 365 그룹|예|예|예|예|예|예<sup>6</sup>|예<sup>6</sup>|아니요|

<sup>1</sup> 일부 타사 웹 파트 및 추가 기능을 사용할 수 없습니다.<br/>
<sup>2</sup> POP는 지원되지만 IMAP는 지원되지 않습니다.<br/>
<sup>3</sup> eDiscovery의 경우 온-프레미스와 클라우드에 대한 별도의 쿼리가 필요합니다.<br/>
<sup>4</sup> 전송 규칙은 조건 및 예외를 정의할 수 있는 유연한 조건과 조건에 따라 수행할 작업으로 구성됩니다. 사용 가능한 조건 및 작업 목록은 각 제품에 대한 해당 조건 및 작업 항목을 참조하세요. <br/>
<sup>5</sup> Windows Server AD RMS는 지원되는 IRM 기능을 사용하도록 설정하기 위해 별도로 구매하고 관리해야 하는 온-프레미스 서버입니다.<br/>
<sup>6</sup>개 Microsoft 365 组 기능이 감소된 상태에서 사용할 수 있습니다.<br/>

## <a name="additional-services"></a>추가 서비스

### <a name="scheduler-for-microsoft-365"></a>Microsoft 365용 스케줄러

Microsoft 365 스케줄러는 사용자가 일정 요구 사항을 디지털 개인 비서에 위임할 수 있는 Exchange Online 대한 추가 기능입니다. 도우미는 조직 내부 및 외부 사용자와 약속 및 모임을 예약하고 일정을 조정할 수 있습니다. 도우미 사서함은 테넌트에 의해 설정되고 제어됩니다. Scheduler를 사용하도록 설정하려면 관리자가 PowerShell cmdlet을 통해 도우미의 사서함을 설정하고 모임 이끌이를 위한 라이선스를 구매해야 합니다. Scheduler 및 작동 방식에 대한 자세한 내용은 [Microsoft 365 Scheduler 시작](/microsoft-365/scheduler/scheduler-overview#how-does-scheduler-for-microsoft-365-work) 을 참조하세요. Scheduler 가격 책정 및 라이선스는 [Microsoft 365 라이선스에 대한 Scheduler를](https://www.microsoft.com/microsoft-365/meeting-scheduler-pricing) 참조하세요.

## <a name="learn-more"></a>자세한 정보

Exchange Online 대한 자세한 내용은 다음 리소스를 확인하세요.

- **Exchange Server:** Exchange Server 대한 자세한 내용은 [Exchange Server 기능 가용성](/Exchange/new-features/feature-availability) 테이블로 이동합니다.
- [**전자 메일**](https://support.office.com/article/Email-94275804-7147-4332-9ccd-5d421760a9ed) 을 만들고 보내는 데 도움이 되는 전자 메일입니다.
- [**전자 메일 및 일정 관리**](/office365/admin/email/email)
- [**Microsoft 지원 및 복구 도우미 정보**](https://diagnostics.office.com/)
- [**Exchange Online의 전자 메일 배달 못 함 보고서(NDR)**](/Exchange/mail-flow-best-practices/non-delivery-reports-in-exchange-online/non-delivery-reports-in-exchange-online)
- [**Exchange Online 도움말**](/exchange/exchange-online)
- 계획 전반의 기능에 대한 자세한 내용은 [엔터프라이즈를 지원하는 강력한 도구를 참조하세요](https://products.office.com/business/compare-more-office-365-for-business-plans).
- Microsoft 서비스 설명에서 페이지를 내보내고 저장하고 인쇄할 수 있습니다. [**콘텐츠 검색 결과를 내보내**](/office365/securitycompliance/export-search-results)는 방법을 알아봅니다.
- **Exchange 관리 센터의 새로운 기능:** Exchange 관리 센터의 새로운 기능에 대한 자세한 내용은 [Exchange 관리 센터의 새로운](/exchange/whats-new) 기능을 참조하세요.
- **Exchange Online 대한 시스템 요구 사항:** 시스템 요구 사항의 경우 비즈니스, 교육 및 정부 조직에서 사용할 수 있는 월간 구독 기반 서비스는 [Microsoft 365 및 Office 리소스를 참조하세요](https://products.office.com/office-system-requirements/#Office365forBEG).
- Exchange Online 대한 Storage 및 받는 사람 제한: Exchange Online 구독 계획에서 사용할 수 있는 스토리지 및 받는 사람 제한에 대한 자세한 내용은 [Exchange Online 제한을 참조하세요](/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits).
- **메시징:** 새로운 기능과 변경된 기능, 계획된 유지 관리 또는 기타 중요한 공지를 포함하여 예정된 변경 사항에 대한 정보를 유지하려면 메시지 센터를 방문하세요. 자세한 내용은 [메시지 센터](/microsoft-365/admin/manage/message-center)를 참조하세요.
- 라이선스 조건: Microsoft 상업용 볼륨 라이선싱 프로그램을 통해 구매한 제품 및 서비스에 대한 사용 약관은 [제품 사용 약관 사이트를 참조하세요](https://www.microsoft.com/licensing/terms/).
- **접근성:** Microsoft는 데이터의 보안과 서비스의 [접근성](https://www.microsoft.com/trust-center/compliance/accessibility) 을 위해 최선을 다하고 있습니다. 자세한 내용은 [Microsoft 보안 센터](https://www.microsoft.com/trust-center) 및 [Office 접근성 센터](https://support.office.com/article/ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d)를 참조하세요.
