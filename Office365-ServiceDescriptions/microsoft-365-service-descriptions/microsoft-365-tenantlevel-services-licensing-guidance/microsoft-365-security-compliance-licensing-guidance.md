---
title: Microsoft 365 규정 준수를 위한 & 지침
ms.author: office365servicedesc
author: pamelaar
manager: gailw
ms.reviewer: v-trscho
audience: ITPro
ms.topic: reference
f1_keywords:
- office-online-service-description
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
description: 이 문서에서는 사용이 Microsoft 365 액세스로 인한 잠재적인 서비스 중단을 방지하는 데 도움이 되는 규정 준수에 대한 지침을 제공합니다.
ms.openlocfilehash: e889cdbfe23bbea76fcaf66596dad202be4918fd
ms.sourcegitcommit: 0107453467d2f1b4971118273631248432d0aa28
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/02/2021
ms.locfileid: "60082858"
---
# <a name="microsoft-365-guidance-for-security-amp-compliance"></a>Microsoft 365 규정 준수를 위한 &amp; 지침

이 문서의 목적을 위해 테넌트 수준 서비스는 테넌트의 모든 사용자(독립 실행형 또는 Office 365 또는 Microsoft 365 계획의 일부로)를 구매할 때 테넌트의 모든 사용자에 대해 부분적으로 또는 전체적으로 활성화되는 온라인 &mdash; &mdash; 서비스입니다. 기술적으로는 라이선스가 없는 일부 사용자가 서비스에 액세스할 수 있을 수 있을지언정 서비스에서 혜택을 제공하려는 사용자에게는 라이선스가 필요합니다.

> [!NOTE]
> 일부 테넌트 서비스는 현재 특정 사용자로 혜택을 제한할 수 없습니다. 사용이 허가된 사용자에 대한 서비스 혜택을 제한하기 위해 노력해야 합니다. 이렇게 하면 대상 지정 기능을 사용할 수 있는 경우 조직에 대한 잠재적인 서비스 중단을 방지할 수 있습니다.

사용자 라이선스를 사용자에게 라이선스를 설정하여 규정 준수 기능을 Microsoft 365 옵션을 확인하려면 Microsoft 365 [비교 표를 다운로드하세요.](https://go.microsoft.com/fwlink/?linkid=2139145)

## <a name="advanced-audit"></a>고급 감사

Microsoft 365 감사는 사용자 및 관리자 활동에 대한 감사 로그의 1년 보존을 제공하며, 사용자 지정 감사 로그 보존 정책을 만들어 다른 Microsoft 365 서비스에 대한 감사 로그 보존을 관리하는 기능을 제공합니다. 또한 조사를 위한 중요한 이벤트에 대한 액세스와 데이터 관리 활동 API에 대한 Office 365 액세스할 수 있습니다. 자세한 내용은 에서 [고급 감사를 Microsoft 365.](/microsoft-365/compliance/advanced-audit)

추가 기능 SKU를 사용하여 10년의 보존 기간을 사용하도록 설정할 수 있습니다.

### <a name="which-users-benefit-from-the-service"></a>어떤 사용자가 서비스를 혜택을 받을 수 있나요?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 규정 준수, Microsoft 365 F5 보안 & 규정 준수 및 Microsoft 365 E5/A5/G5 eDiscovery 및 감사의 사용이 허가된 사용자는 고급 감사를 통해 혜택을 받을 수 있습니다.

고급 감사 및 10년 감사 로그 보존 추가 기능을 사용이 허가된 사용자는 10년 감사 로그 보존을 통해 혜택을 받을 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

사용자는 고급 감사를 통해 혜택을 받을 수 있습니다. Microsoft 365 서비스의 사용자 활동과 관련된 감사 레코드는 최대 1년 동안 보존할 수 있습니다. 또한 사용자 사서함의 항목에 액세스하거나 읽은 경우와 같은 고가치 감사 이벤트가 기록됩니다. 자세한 내용은 에서 [고급 감사를 Microsoft 365.](/microsoft-365/compliance/advanced-audit)

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 고급 감사는 서비스를 통해 혜택을 받은 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정되며, Azure Active Directory, Exchange 및 서비스에서 활동에 대한 감사 로그(적절한 라이선스가 있는 사용자가 수행)에 대한 1년 보존을 자동으로 SharePoint. 또한 조직은 감사 로그 보존 정책을 사용하여 다른 Microsoft 365 서비스의 활동으로 생성된 감사 레코드의 보존 기간을 관리할 수 있습니다. 10년 감사 로그 보존 기능은 동일한 보존 정책을 사용하여 사용하도록 설정됩니다. 자세한 내용은 [감사 로그 보존 정책 관리](/microsoft-365/compliance/audit-log-retention-policies)를 참조하십시오.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

감사 로그의 1년 보존 및 중요한 이벤트 감사는 해당 라이선스가 있는 사용자에게만 적용됩니다. 또한 관리자는 감사 로그 보존 정책을 사용하여 특정 사용자의 감사 로그에 대한 더 짧은 보존 기간을 지정할 수 있습니다.

감사 로그의 10년 보존은 적절한 추가 기능 라이선스가 있는 사용자에게만 적용됩니다. 추가 기능 SKU는 2021년 초부터 필요합니다.

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory ID 보호

Azure Active Directory ID 보호는 조직의 ID에 영향을 주는 잠재적인 취약점을 감지하고, 조직의 ID와 관련된 의심스러운 작업에 대한 자동화된 응답을 구성하고, 의심스러운 인시던트에 대해 조사하고 적절한 조치를 취하여 문제를 해결할 수 있도록 하는 Azure Active Directory Premium P2 계획의 기능입니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

SecOps 분석가 및 보안 전문가는 기계 학습 알고리즘을 기반으로 플래그가 지정된 사용자 및 위험 이벤트에 대한 통합된 보기를 사용할 수 있습니다. 최종 사용자는 위험 기반 조건부 액세스를 통해 제공되는 자동 보호와 취약성에 대해 행동하여 제공되는 향상된 보안을 통해 혜택을 받을 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

- Azure Active Directory 계획 1: Microsoft 365 E3/A3/G3/F1/F3, Enterprise Mobility & E3 및 Microsoft 365 Business Premium
- Azure Active Directory 계획 2: Microsoft 365 E5/A5/G5, Enterprise Mobility & Security E5, Microsoft 365 E5/F5 Security and Microsoft 365 F5 Security & Compliance

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 Azure AD ID 보호 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. Azure AD ID 보호에 대한 자세한 내용은 ID [보호란?을 참조하세요.](/azure/active-directory/identity-protection/overview-identity-protection)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

관리자는 암호 재설정 수준을 정의하는 위험 정책을 할당하고 라이선스가 있는 사용자에 한해 액세스를 허용하여 Azure AD ID 보호의 범위를 지정할 수 있습니다. Azure AD ID 보호 배포의 범위를 지정하는 방법에 대한 지침은 위험 정책을 구성하고 사용하도록 설정하는 [방법을 참조하세요.](/azure/active-directory/identity-protection/howto-sign-in-risk-policy)

## <a name="azure-active-directory-identity-governance"></a>Azure Active Directory ID 거버넌스

Azure Active Directory ID 거버넌스를 사용하면 보안 및 직원 생산성에 대한 조직의 요구를 올바른 프로세스 및 가시성과 균형을 맞출 수 있습니다. 권한 관리, 액세스 검토, 권한 있는 ID 관리 및 사용 약관 정책을 사용하여 올바른 사용자가 올바른 리소스에 액세스할 수 있도록 합니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

Azure Active Directory ID 거버넌스를 통해 한 액세스 패키지에서 앱, 그룹 및 그룹에 대한 액세스를 Microsoft Teams 생산성이 향상됩니다. 관리자가 개소하지 않고도 사용자를 승인자로 구성할 수도 있습니다. 액세스 검토를 위해 사용자는 스마트 권장 사항이 있는 그룹의 구성원 자격을 검토하여 정기적으로 작업을 수행 할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5/F5 보안 및 F5 보안 & 규정 준수 및 Azure Active Directory Premium 계획 2는 사용자가 Azure Active Directory ID 거버넌스를 사용할 수 있는 권한을 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

Azure AD ID 거버넌스 기능은 테넌트 수준에서 사용하도록 설정되지만 사용자당 구현됩니다. Azure AD ID 거버넌스에 대한 자세한 내용은 [Azure AD ID 거버넌스란?을 참조하세요.](/azure/active-directory/governance/identity-governance-overview)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

관리자는 액세스 패키지, 액세스 검토 또는 권한 있는 ID 관리를 라이선스가 있는 사용자에 한해 할당하여 Azure AD ID 거버넌스 범위를 지정할 수 있습니다. Azure AD ID 거버넌스 배포 범위를 지정하는 방법에 대한 지침은 다음을 참조하세요.

- [Azure AD 권리 관리 라이선스 요구 사항](/azure/active-directory/governance/entitlement-management-overview#license-requirements)
- [Azure AD 액세스 검토 라이선스 요구 사항](/azure/active-directory/governance/access-reviews-overview#license-requirements)
- [라이선스를 사용하기 위한 라이선스 Privileged Identity Management](/azure/active-directory/privileged-identity-management/subscription-requirements)

## <a name="communication-compliance"></a>커뮤니케이션 규정 준수

조직의 Microsoft 365 규정 준수는 조직에서 부적절한 메시지를 검색, 캡처 및 수정하는 데 도움을 주어 통신 위험을 최소화하는 데 도움이 됩니다. 조직에서 내부 및 외부 전자 메일, Microsoft Teams 또는 타사 통신을 캡처하는 특정 정책을 정의할 수 있습니다. 검토자는 조직의 메시지 표준을 준수하는지 확인하도록 적절한 수정 조치를 취할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

규정 준수 전문가는 커뮤니케이션 규정 준수 정책에 따라 조직 통신을 모니터링하도록 하여 서비스의 이점을 제공합니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 규정 준수, Microsoft 365 F5 보안 & 규정 준수 및 Microsoft 365 E5/A5/G5 내부자 위험 관리는 사용자가 통신 규정 준수를 혜택을 받을 수 있는 권한을 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

관리자 및 규정 준수 전문가는 2016년 8월 2일부로 Microsoft 365 규정 준수 센터. 이러한 정책은 조직에서 검토할 통신 및 사용자를 정의하고, 통신이 충족해야 하는 사용자 지정 조건을 정의하고, 검토를 수행할 사용자를 지정합니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

관리자는 통신 준수 정책에 포함할 특정 사용자 또는 그룹을 선택합니다. 그룹을 선택할 때 그룹에서 통신 준수 정책에서 제외할 특정 사용자를 선택할 수도 있습니다. 통신 준수 정책에 대한 자세한 내용은 에서 통신 규정 준수 [시작을 Microsoft 365.](/microsoft-365/compliance/communication-compliance-configure)

## <a name="compliance-manager"></a>규정 관리자

[Microsoft 준수 관리자는](https://compliance.microsoft.com/compliancemanager) 조직의 [](/microsoft-365/compliance/microsoft-365-compliance-center) 규정 Microsoft 365 규정 준수 센터 보다 간편하고 쉽게 관리할 수 있도록 하여 조직의 규정 준수 요구 사항을 관리하는 데 도움이 되는 조직의 기능입니다. 준수 관리자는 데이터 보호 위험 상세 조사부터 제어 구현의 복잡성 관리, 규정 및 인증의 최신 정보 유지, 보고 및 감사까지, 여러분의 규정 준수를 향한 여정을 도와드릴 수 있습니다.

준수 관리자는 규정 준수를 간소화하고, 제공함으로써 위험을 줄일 수 있도록 합니다.

- 공통 업계 및 지역 표준과 규정에 대한 사전 구축된 평가 또는 고유한 규정 준수 요구 사항을 충족하기 위한 사용자 지정 평가입니다.
- 단일 도구를 통해 위험 평가를 효율적으로 완료할 수 있는 워크플로 기능.
- 조직에 가장 관련성이 높은 표준 및 규정을 준수하는 데 도움이 되는 제안된 개선 작업에 대한 세부 단계별 지침입니다. Microsoft에서 관리하는 작업의 경우 구현 세부 정보 및 감사 결과를 볼 수 있습니다.
- 개선 작업을 완료하는 진행 상황을 측정하여 규정 준수 상황을 이해하는 데 도움이 되는 위험 기반 준수 점수입니다.

### <a name="who-can-access-compliance-manager"></a>Who 관리자에 액세스할 수 있나요?

준수 관리자는 Office 365 및 Microsoft 365 라이선스가 있는 조직과 미국 정부 커뮤니티 클라우드(GCC), GCC High 및 DoD(국방부) 고객에게 제공됩니다. 평가 가용성 및 관리 기능은 사용권 계약에 따라 달라집니다.

### <a name="what-are-premium-assessments"></a>프리미엄 평가란?

Premium 평가는 준수 관리자 및 도움말에 대한 추가 기능 값입니다.

- 복잡한 규정 요구 사항을 특정 컨트롤로 변환
- 권장 개선 작업 제안
- 규정에 대한 수량화 가능한 규정 준수 측정 제공

준수 관리자는 고객이 광범위한 전역, 지역 및 산업 규정 및 표준에 대한 규정 준수를 평가하는 데 사용할 수 있는 300개 이상의 프리미엄 평가를 제공합니다.

Microsoft Exchange Online 라이선스가 포함된 모든 고객은 준수 관리자 프리미엄 평가를 구매할 수 있습니다.

### <a name="which-premium-assessments-are-available"></a>어떤 프리미엄 평가를 사용할 수 있나요?

다음은 프리미엄 [평가 목록입니다.](/microsoft-365/compliance/compliance-manager-templates-list#premium-templates)

### <a name="which-assessments-are-included-by-default-free-of-cost"></a>기본적으로 포함되어 있는 평가(비용 무료)는 무엇입니까?

일부 평가는 준수 관리자 및 고객 라이선스 유형의 일부로 포함됩니다. 자세한 내용은 아래 표를 참조하세요.

| 라이선스 유형 | 평가 템플릿(기본적으로 포함) |
|:-----|:-----|
|<ul><li>Microsoft 365 또는 Office 365 A1/E1/F1/G1</li><li>Microsoft 365 또는 Office 365 A3/E3/F3/G3</li></ul>|<ul><li>데이터 보호 기준</li></ul>|
|<ul><li>Microsoft 365 또는 Office 365 A5/E5/G5</li><li>Microsoft 365 A5/E5/F5/G5 규정 준수</li><li>Microsoft 365 A5/E5/F5/G5 eDiscovery 및 감사</li><li>Microsoft 365 A5/E5/F5/G5 내부자 위험 관리</li><li>Microsoft 365 A5/E5/F5/G5 정보 보호 및 거버넌스</li></ul>|<ul><li>데이터 보호 기준</li><li>EU GDPR</li><li>NIST 800-53</li><li>ISO 27001</li><li>CMMC 수준 1-5(G5에만 사용 가능)</li><li>사용자 지정 평가</li></ul>|

### <a name="what-are-custom-assessments"></a>사용자 지정 평가란?

사용자 지정 평가는 새 템플릿을 만들거나 컨트롤 및 개선 작업을 추가하거나 업데이트하는 등의 기존 평가 템플릿을 사용자 지정할 수 있는 기능을 제공하는 준수 관리자 기능입니다.

### <a name="who-can-access-custom-assessments"></a>Who 평가에 액세스할 수 있나요?

아래 나열된 E5 구독이 있는 고객은 사용자 지정 평가 기능을 사용할 수 있습니다.

- Microsoft 365 또는 Office 365 A5/E5/G5
- Microsoft 365 A5/E5/F5/G5 규정 준수
- Microsoft 365 A5/E5/F5/G5 eDiscovery 및 감사
- Microsoft 365 A5/E5/F5/G5 내부자 위험 관리
- Microsoft 365 A5/E5/F5/G5 정보 보호 및 거버넌스

## <a name="customer-key-for-microsoft-365"></a>고객용 Microsoft 365

고객 키를 사용하여 조직의 암호화 키를 제어하고 microsoft Microsoft 365 센터에서 휴지의 데이터를 암호화하는 데 사용하도록 암호화 키를 구성할 수 있습니다. 즉, 고객 키를 사용하면 자체 키를 사용하여 자신에 속한 암호화 계층을 추가할 수 있습니다. 고객 키는 데이터 저장 암호화 서비스를 [](/microsoft-365/compliance/customer-key-overview#about-data-encryption-policies) 통해 여러 Microsoft 365 데이터 Microsoft 365 암호화 지원을 제공합니다. 또한 고객 키는 SharePoint 온라인 및 비즈니스용 OneDrive 및 사서함 수준 Exchange Online 암호화를 제공합니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

사용자는 조직에서 제공, 제어 및 관리하는 암호화 키를 사용하여 응용 프로그램 계층에서 미사용 데이터를 암호화할 수 있도록 하여 고객 키의 이점을 활용합니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 규정 준수, Microsoft 365 F5 보안 & 규정 준수, Microsoft 365 E5/A5/G5 정보 보호 및 거버넌스 및 Office 365 E5/A5/G5는 사용자가 고객 키를 혜택을 받을 수 있는 권한을 제공합니다. 고객 키를 완전하게 이용하려면 Azure Key Vault 구독도 있어야 합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

고객 키 설정 [문서에서는](/microsoft-365/compliance/customer-key-set-up) 필요한 Azure 리소스를 만들고 구성하기 위해 따라야 하는 단계에 대해 설명한 다음 고객 키 설정 단계를 제공합니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

Microsoft 365 암호화 지원을 제공하는 미사용 데이터 저장 서비스는 테넌트 수준 서비스입니다. 기술적으로는 라이선스가 없는 일부 사용자가 서비스에 액세스할 수 있을 수 있을지언정 서비스에서 혜택을 제공하려는 사용자에게는 라이선스가 필요합니다. 사서함 Exchange Online 암호화의 경우 데이터 암호화 정책을 할당하기 위해 사용자 사서함에 사용이 허가되어야 합니다.

## <a name="data-connectors"></a>데이터 커넥터

Microsoft는 Microsoft에서 구성할 수 있는 타사 데이터 커넥터를 Microsoft 365 규정 준수 센터. Microsoft에서 제공하는 데이터 커넥터 목록은 타사 데이터 커넥터 [테이블을 참조하세요.](/microsoft-365/compliance/archiving-third-party-data#third-party-data-connectors) 또한 이 표에는 데이터 가져오기 및 보관 후 타사 데이터에 적용할 수 있는 규정 Microsoft 365 각 커넥터에 대한 단계별 지침에 대한 링크도 요약되어 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

데이터 커넥터를 사용하여 타사 데이터를 가져오고 Microsoft 365 가장 큰 이점은 데이터를 가져온 후 데이터에 다양한 Microsoft 365 규정 준수 솔루션을 적용할 수 있는 것입니다. 이를 통해 조직의 비 Microsoft 데이터가 조직에 영향을 주는 규정 및 표준을 준수하는지 보장할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

다음 라이선스는 사용자가 데이터 커넥터를 혜택을 받을 수 있는 권한을 제공합니다.

- Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5 정보 보호 &amp; 거버넌스
- Microsoft 365 E5/A5/G5/F5 규정 준수
- Microsoft 365 F5 보안 & 규정 준수
- Microsoft 365 E5/A5/G5 내부자 위험 관리
- Microsoft 365 E5/A5/G5 eDiscovery 및 감사
- Office 365 E5/A5/G5

Microsoft 파트너가 제공하는 Microsoft 365 보안 및 준수 센터의 데이터 커넥터의 경우 조직에서 해당 커넥터를 배포하려면 먼저 파트너와의 비즈니스 &amp; 관계가 필요합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

커넥터는 보안 및 준수 센터 및 커넥터 &amp; 카탈로그를 사용하여 구성됩니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

데이터 커넥터 서비스는 테넌트 수준 값입니다. 이 서비스를 이용하려는 모든 사용자는 사용이 허가되어야 합니다.

## <a name="data-classification-analytics-overview-content-amp-activity-explorer"></a>데이터 분류 분석: 콘텐츠 &amp; 활동 탐색기 개요

데이터 분류 분석 기능은 사용자 환경 내에서 Microsoft 365 규정 준수 센터 있습니다. 개요는 디지털 콘텐츠의 위치와 가장 일반적인 중요한 정보 유형 및 레이블이 있는 위치를 보여줍니다. 콘텐츠 탐색기를 사용하면 중요한 데이터의 양과 유형을 볼 수 있으며 사용자가 레이블 또는 민감도 유형별로 필터링하여 중요한 데이터가 저장된 위치를 자세히 볼 수 있습니다. 활동 탐색기에는 콘텐츠를 위험에 노출할 수 있는 레이블 다운그레드 또는 외부 공유와 같은 중요한 데이터 및 레이블과 관련된 활동이 표시됩니다.

활동 탐색기는 관리자가 최종 사용자가 사용하는 중요한 정보와 관련된 활동에 대한 가시성을 확보할 수 있는 단일 창을 제공합니다. 이러한 데이터에는 레이블 활동, DLP(데이터 손실 방지) 로그, 자동 레이블 지정, 끝점 DLP 등이 포함됩니다.

콘텐츠 탐색기는 지원되는 작업 부하 내에 저장된 중요한 문서를 인덱싱하고 Microsoft 365 중요한 정보를 식별하는 기능을 관리자에게 제공합니다. 또한 콘텐츠 탐색기는 민감도 및 보존 레이블로 분류된 문서를 식별하는 데 도움이 됩니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

정보 보호 및 규정 준수 관리자는 서비스에 액세스하여 이러한 로그 및 인덱싱된 데이터에 액세스하여 중요한 데이터가 저장되는 위치와 이 데이터와 관련된 활동 및 최종 사용자가 수행한 활동을 이해할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 규정 준수, Microsoft 365 F5 보안 & 규정 준수, Microsoft 365 E5/A5/G5 정보 보호 거버넌스 및 Office 365 E5 허가된 사용자는 Microsoft 365 데이터 분류 분석을 통해 혜택을 받을 수 &amp; 있습니다.

Microsoft 365 E3/A3/G3 및 Office 365 E3/A3/G3을 사용하면 사용자가 콘텐츠 탐색기 데이터 집계만 사용할 수 있습니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 콘텐츠 및 활동 탐색기 개요 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. 라이선스가 있는 사용자에 대한 데이터 분류 분석을 구성하는 데 대한 자세한 내용은 다음을 참조하세요.

- **콘텐츠 탐색기**: 콘텐츠 탐색기 시작 - Microsoft 365 [준수 | Microsoft Docs.](/microsoft-365/compliance/data-classification-content-explorer)
- **활동 탐색기**: 활동 탐색기 시작 - Microsoft 365 [준수 | Microsoft Docs.](/microsoft-365/compliance/data-classification-activity-explorer)
- **데이터 분류 릴리스 정보:** 데이터 분류 릴리스 정보 - Microsoft 365 [준수 | Microsoft Docs.](/microsoft-365/compliance/data-classification-pub-preview-relnotes)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

이 기능은 규정 준수 포털 내에서 솔루션을 적극적으로 사용하는 Microsoft 365 합니다.

## <a name="data-loss-prevention-for-teams"></a>데이터 손실 방지를 Teams

조직에서는 통신 DLP를 사용하여 Teams 정보, 개인 식별 정보, 상태 관련 정보 또는 기타 기밀 정보와 같은 중요한 정보를 포함하는 채팅 및 채널 메시지를 차단할 수 있습니다.

### <a name="which-users-benefit-from-the-service"></a>어떤 사용자가 서비스를 혜택을 받을 수 있나요?

- Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5/F5 규정 준수 및 F5 보안 & 규정 준수
- Microsoft 365 E5/A5/G5 정보 보호 및 거버넌스
- Office 365 E5/A5/G5

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

보낸 사람이 조직의 DLP 정책에 구성된 중요한 정보를 검사한 보내는 채팅 및 채널 메시지에 중요한 정보를 제공하면 도움이 됩니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 Teams 및 채널 메시지는 테넌트  내의 모든 사용자에 대해 이러한 DLP 기능에 대해 사용하도록 설정된 위치(작업량)입니다. DLP 정책 사용에 대한 자세한 내용은 데이터 손실 방지 [개요를 참조하세요.](/office365/securitycompliance/data-loss-prevention-policies)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

관리자는 데이터 손실 방지 위치에서 보안 및 준수 센터의 위치(작업), 포함된 사용자 및 제외된 사용자를 사용자 &amp; **지정할 수**  >  **있습니다.**

## <a name="data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Exchange Online, SharePoint Online 및 비즈니스용 OneDrive

Office 365, SharePoint Online 및 비즈니스용 OneDrive에 대한 D Exchange Online LP(데이터 손실 방지)를 사용하여 조직은 전자 메일 및 파일(Microsoft Teams 파일에 저장된 파일 포함)에서 중요한 정보를 식별, 모니터링 및 자동으로 보호할 수 있습니다. 리포지토리)

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

사용자는 조직의 DLP 정책에 구성된 Exchange Online, SharePoint Online 및 비즈니스용 OneDrive 파일에서 중요한 정보를 검사할 때 DLP를 사용할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 E3/A3/Business Premium, Office 365 E3/A3 및 Office 365 데이터 손실 방지 및 F5 준수 및 F5 보안 & 규정 준수는 Office 365, SharePoint Online 및 Office 365 D Exchange Online LP의 혜택을 받을 수 있는 권한을 비즈니스용 OneDrive.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 Exchange Online, SharePoint 사이트 및 OneDrive 계정은 테넌트 내의 모든  사용자에 대해 이러한 DLP 기능의 위치(작업)를 사용하도록 설정됩니다. DLP 정책 사용에 대한 자세한 내용은 데이터 손실 방지 [개요를 참조하세요.](/microsoft-365/compliance/data-loss-prevention-policies)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

관리자는 데이터 손실 방지 위치에서 보안 및 준수 센터의 위치(작업), 포함된 사용자 및 제외된 사용자를 사용자 &amp; **지정할 수**  >  **있습니다.**

## <a name="double-key-encryption-for-microsoft-365"></a>이중 키 암호화 Microsoft 365

이중 키 암호화를 Microsoft 365 요구 사항을 충족하고 암호화 키에 대한 모든 제어를 유지 관리하기 위해 매우 중요한 데이터를 보호할 수 있습니다. 이중 키 암호화는 두 개의 키를 사용하여 데이터를 보호합니다. 이 키는 컨트롤에 있는 키 하나와 두 번째 키를 사용하여 안전하게 Microsoft Azure. 데이터를 보기 위해 두 키에 모두 액세스할 수 있어야 합니다. Microsoft는 하나의 키에만 액세스할 수 있으며 키와 데이터도 Microsoft에서 사용할 수 없게 하여 데이터의 개인 정보 및 보안을 완전하게 제어할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

사용자는 암호화된 데이터를 클라우드로 마이그레이션할 수 있게 하여 키가 사용자의 제어에 남아 있는 한 타사 액세스를 방지하여 이중 키 암호화를 사용할 수 있습니다. 사용자는 다른 민감도 레이블로 보호된 콘텐츠와 유사한 이중 키 암호화된 콘텐츠를 보호하고 사용할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 규정 준수 및 F5 보안 & 규정 준수, Microsoft 365 E5/A5/G5 정보 보호 및 거버넌스, Office 365 E5/A5/G5 및 EMS E5는 사용자가 이중 키 암호화를 혜택을 받을 수 있는 권한을 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

이중 키 암호화는 사용자용 데스크톱 Microsoft Office Windows.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

라이선스가 있는 사용자에 대해 Office 365 및/또는 Microsoft 365 조직 내의 데이터에 암호화 키를 할당하기 위해 이중 키 암호화 배포 지침을 따릅니다.

## <a name="ediscovery"></a>eDiscovery

eDiscovery는 기업 내 IT 및 법률 부서를 위해 조사 및 eDiscovery 솔루션을 제공하여 Microsoft 365 시스템에서 내보내기 전에 조사 또는 소송과 관련된 콘텐츠를 식별, 수집, 보존, 축소 및 검토합니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

사용자는 Advanced eDiscovery 데이터 관리자(문서 또는 전자 파일에 대한 관리 제어권이 있는 사용자)로 선택될 때 사용자의 이점을 누리게 됩니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 E5/A5/G5/E3/A3/G3, Office 365 E5/A5/G5/E3/A3/G3 및 F5 준수 및 F5 보안 & 규정 준수는 사용자가 Core eDiscovery의 혜택을 받을 수 있는 권한을 제공합니다.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 규정 준수 및 F5 보안 & 규정 준수, Microsoft 365 E5/A5/G5 eDiscovery 및 감사, Office 365 E5/A5/G5는 사용자가 Advanced eDiscovery.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 Advanced eDiscovery 보안 및 준수 센터에서 eDiscovery 권한을 할당할 때 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용자 지정 기능이 사용하도록 &amp; 설정됩니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

eDiscovery 관리자는 add [custodians to an Advanced eDiscovery에](/microsoft-365/compliance/add-custodians-to-case)설명된 바와 같이 Advanced eDiscovery 기본 제공 관리 도구를 사용하여 특정 사용자를 사례에 대한 데이터 관리자로 선택할 수 있습니다.

## <a name="information-barriers"></a>정보 장벽

정보 장벽은 개인 또는 그룹이 서로 통신하지 못하도록 관리자가 구성할 수 있는 정책입니다. 예를 들어 한 부서에서 다른 부서와 공유하면 안되는 정보를 처리하거나 그룹이 외부 연락처와 통신하지 못하게 해야 하는 경우 유용합니다. 정보 장벽 정책은 또한 검색 및 검색을 방지합니다. 즉, 다른 사용자와 통신하지 말아야 하는 경우 사용자 선택에서 해당 사용자를 찾을 수 없습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

사용자는 다른 사용자와의 통신이 제한될 때 정보 장벽의 고급 규정 준수 기능을 통해 혜택을 받을 수 있습니다. 정보 장벽 정책을 정의하여 특정 사용자 세그먼트가 각각과 통신하지 못하도록 방지하거나 특정 세그먼트가 다른 특정 세그먼트와만 통신하도록 허용할 수 있습니다. 정보 장벽 정책 정의에 대한 자세한 내용은 정보 장벽 정책 [정의를 참조하세요.](/microsoft-365/compliance/information-barriers-policies) 두 그룹이 서로 통신할 수 없는 시나리오의 경우 두 그룹의 사용자가 서비스를 이용하려면 라이선스가 필요합니다(아래 예제 참조).<br><br>

| 시나리오 | Who 라이선스가 필요한가요? |
|:------|:------|
| 두 그룹(그룹 1 및 그룹 2)이 서로 통신할 수 없습니다. 즉, 그룹 1 사용자는 그룹 2 사용자와 통신할 수 없습니다. 그룹 2 사용자는 그룹 1 사용자와 통신할 수 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 없습니다. | 그룹 1 및 &nbsp; 그룹 &nbsp; 2의 사용자 |

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 규정 준수 및 F5 보안 & 규정 준수, Microsoft 365 E5/A5/G5 내부자 위험 관리 및 Office 365 E5/A5/G5는 사용자가 정보 장벽을 혜택을 받을 수 있는 권한을 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

관리자는 보안 및 준수 센터에서 PowerShell cmdlet을 사용하여 정보 장벽 정책을 만들고 &amp; 관리합니다. 관리자에게 정보 장벽 정책을 만들 Microsoft 365 Enterprise 전역 관리자, Office 365 관리자 역할 또는 준수 관리자 역할이 할당되어야 합니다. 기본적으로 이러한 정책은 테넌트의 모든 사용자에게 적용됩니다. 정보 장벽에 대한 자세한 내용은 에서 정보 장벽을 [Microsoft Teams.](/MicrosoftTeams/information-barriers-in-teams)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

관리자는 보안 및 준수 센터에서 위치(작업), 포함된 사용자 및 제외된 사용자를 사용자 지정할 &amp; 수 있습니다. 예를 들어 모든 사용자에게 Office 365 E3 및 Office 365 Advanced Compliance/E5에 대한 라이선스가 없는 경우 조직에 대한 정보 장벽 정책을 만들 필요가 없습니다. 자세한 내용은 [Microsoft Teams의 정보 장벽](/MicrosoftTeams/information-barriers-in-teams)을 참조하세요.

## <a name="information-protection"></a>Information Protection

정보 보호는 조직에서 중요한 문서 및 전자 메일을 검색, 분류, 레이블 지정 및 보호하는 데 도움이 됩니다. 관리자는 레이블을 자동으로 적용하는 규칙 및 조건을 정의하거나, 사용자가 레이블을 수동으로 적용하거나, 두 가지 조합을 사용할 수 있습니다. 여기서 사용자에게 레이블 적용에 대한 권장 사항이 제공될 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

사용자는 민감도 레이블을 콘텐츠에 수동으로 적용하거나 콘텐츠를 자동으로 분류하여 혜택을 받을 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium, F5 규정 준수 및 F5 보안 & 규정 준수, Enterprise Mobility + Security E3/E5, M365 E5/A5/G5, Office 365 E5/A5/E3/A3/F3, AIP 계획 1 및 AIP 계획 2는 사용자가 수동 민감도 레이블 지정을 사용할 수 있는 권한을 제공합니다.

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium 및 Enterprise Mobility + Security E3/E5, AIP 계획 1 및 AIP 계획 2 및 F5 규정 준수 및 F5 보안 & 규정 준수는 사용자가 Power BI에서 민감도 레이블을 적용하고 볼 수 있는 이점을 제공하고 데이터가 보호되는 경우 데이터를 보호할 수 있는 권한을 제공합니다. 내보낼 Power BI, Excel, PowerPoint 또는 PDF로 내보낼 수 있습니다.

Microsoft 365 Business Premium 및 Enterprise Mobility은 [AIPService](/powershell/azure/aip/overview#aipservice) PowerShell 모듈을 사용하여 Azure Information Protection에 대한 Azure 권한 관리 보호 서비스를 관리할 수 있는 권한을 제공합니다.

> [!NOTE]
> Power BI/Microsoft 365 E5/A5/G5에 포함되어 있습니다. 다른 모든 계획에서는 Power BI 사용이 허가되어야 합니다.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 준수 및 F5 보안 & 규정 준수, Microsoft 365 E5/A5/G5 정보 보호 및 거버넌스, Office 365 E5, Enterprise Mobility + Security E5/A5/G5 및 AIP 계획 2는 사용자가 자동 민감도 레이블 지정을 사용할 수 있는 권한을 제공합니다.

정보 보호에는 정보 보호 기능(교육 가능한 분류자)에 기반한 Machine Learning 권리가 포함되어 있지 않습니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 정보 보호 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. 라이선스가 있는 사용자에 대한 정책을 구성하는 데 대한 자세한 내용은 Azure 권한 관리 활성화를 참조하세요.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

AIP 스캐너 기능을 사용하는 경우를 제외하고 정책의 범위를 특정 그룹 또는 사용자로 지정하거나 레지스트리를 편집하여 라이선스가 없는 사용자가 분류 또는 레이블 지정 기능을 실행하지 못하도록 할 수 있습니다.

AIP 스캐너 기능의 경우 Microsoft는 라이선스가 없는 사용자에게 파일 분류, 레이블 지정 또는 보호 기능을 제공하지 않습니다.

자세한 내용은 [민감도](/microsoft-365/compliance/create-sensitivity-labels#publish-sensitivity-labels-by-creating-a-label-policy) 레이블 만들기 및 게시 및 Azure Information Protection 통합 레이블 지정 스캐너 [이해를 참조하세요.](/azure/information-protection/deploy-aip-scanner)

## <a name="information-governance"></a>정보 거버넌스

정보 거버넌스를 통해 조직은 데이터를 검색, 분류, 레이블 지정 및 관리하여 위험을 관리할 수 있습니다. 정보 거버넌스를 통해 조직은 비즈니스 및 규정 요구 사항을 충족하고, 조직 및 타사 데이터 전반에 걸쳐 보존 및 삭제 기능을 제공하여 공격 Microsoft 365 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

사용자는 특정 정책 및 규정을 준수하기 위해 보존 목적으로 데이터를 분류할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 F3/Business Premium, Office 365 E5/A5/G5/E3/A3/G3/E1/A1/G1/F3 및 독립 실행형 Exchange 계획은 사용자가 사서함 데이터에 레코드가 아닌 보존 레이블을 수동으로 적용하여 혜택을 받을 수 있는 권한을 제공합니다.

Microsoft 365 F3/F1/Business Premium, Office 365 E5/A5/G5/E3/A3/G3/F3/E1/A1/G1 및 독립 실행형 SharePoint 요금제는 사용자가 레코드가 아닌 보존 레이블을 SharePoint 또는 파일의 파일에 수동으로 적용할 수 있는 권한을 OneDrive.

Microsoft 365 E5/A5/G5/E3/A3/Business Premium, Office 365 E5/A5/G5/E3/A3, Exchange 계획 2 및 Exchange Online Archiving 조직 전체 또는 위치 전체 사서함 보존 정책의 혜택을 받을 수 있는 권한을 사용자에게 제공합니다.

Microsoft 365 E5/A5/G5/E3/A3, Office 365 E5/A5/G5/E3/A3 및 SharePoint 요금제 2는 사용자가 기본 SharePoint 또는 OneDrive 보존 정책을 통해 혜택을 받을 수 있는 권한을 제공하고SharePoint 또는 OneDrive.

조직은 보존 정책을 사용하여 정책에 따라 Teams 보존하거나 삭제할 수 있습니다. 여기에는 채팅 및 대화에서 Teams 관리가 포함됩니다.

다음 라이선스는 사용자가 보존 정책의 혜택을 받을 Teams 제공합니다.

- Microsoft 365 E5/G5/A5/E3/G3/A3/F1, Business Basic, Business Standard 및 Business Premium
- Office 365 E5/G5/A5/E3/G3/A3/F3/E1/G1

다음 라이선스가 있는 사용자의 경우 지원되는 최소 보존 또는 삭제 기간은 30일입니다.

- Microsoft 365 F1/F3, Business Basic, Business Standard 및 Business Premium
- Office 365 E1/G1 및 F3

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 규정 준수 및 F5 보안 & 규정 준수, Microsoft 365 정보 보호 및 거버넌스 E5/A5/G5 및 Office 365 E5/A5는 보존 레이블 또는 정책을 자동으로 적용하고 기본 보존을 적용하여 사용자에게 혜택을 받을 수 있는 권한을 제공합니다. 레이블 또는 정책, 사용자 지정 이벤트를 기반으로 보존 레이블의 보존 기간을 시작하고, 레이블 보존 기간이 끝나면 수동 처리 검토를 트리거하고, 네이티브 데이터 커넥터를 통해 타사 데이터를 가져오고, 파일 레코드를 선언하고, 레이블이 지정된 콘텐츠를 검색하고, 레이블 지정 활동을 모니터링합니다.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 규정 준수 및 F5 보안 & 규정 준수, Microsoft 365 E5/A5/G5 정보 보호 및 거버넌스에서는 학습 가능한 분류자를 기반으로 보존 레이블을 자동으로 적용하는 이점을 사용자에게 제공할 수 있는 권한을 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 정보 거버넌스 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. 라이선스가 있는 사용자에 대해 자동레이블 및 정책을 적용하기 위해 정보 거버넌스를 구성하는 데 대한 자세한 내용은 에서 [Microsoft 정보 거버넌스를 Microsoft 365.](/microsoft-365/compliance/manage-information-governance)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

특정 위치(팀 사이트, 그룹 사이트 등)의 사용이 허가된 사용자에게 정보 거버넌스 기능을 적용할 수 있습니다. 라이선스가 있는 사용자에 대해 자동레이블 및 정책을 적용하기 위해 정보 거버넌스를 구성하는 데 대한 자세한 내용은 에서 [Microsoft 정보 거버넌스를 Microsoft 365.](/microsoft-365/compliance/manage-information-governance)

## <a name="insider-risk-management"></a>내부자 위험 관리

내부자 위험 관리는 조직에서 Microsoft 365 활동을 감지, 조사 및 조치를 취할 수 있도록 하여 내부 위험을 최소화하는 데 도움이 되는 솔루션입니다.

사용자 지정 정책을 사용하면 필요한 경우 Microsoft로 사례를 에스컬레이터하는 등 조직에서 악의적이고 부적당하게 위험한 활동을 감지하고 조치를 Advanced eDiscovery 수 있습니다. 조직의 위험 분석가가 신속하게 적절한 조치를 취하여 사용자가 조직의 규정 준수 표준을 준수하도록 할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

사용자는 자신의 활동을 위험에 대해 모니터링하여 혜택을 받을 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 규정 준수 및 F5 보안 & 규정 준수 및 Microsoft 365 E5/A5/G5 내부자 위험 관리는 내부자 위험 관리를 통해 사용자에게 권한을 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

내부자 위험 관리 정책은 내부자 Microsoft 365 규정 준수 센터 만들어 사용자에게 할당해야 합니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

Microsoft 365 규정 준수 센터 정책을 만들 때 사용자 및 그룹  선택 페이지에서 사용자  또는 그룹 선택을 선택하여 사용이 허가된 사용자만 선택하거나 모든 사용자에게 라이선스가 부여된 경우 모든 사용자 및 메일 사용 가능 그룹 확인란을 선택할 수 있습니다.  자세한 내용은 내부자 위험 관리 [시작을 참조하세요.](/microsoft-365/compliance/insider-risk-management-configure)

## <a name="microsoft-defender-for-identity"></a>ID용 Microsoft Defender

Id용 Microsoft Defender(이전의 Azure Advanced Threat Protection)는 여러 유형의 고급 대상 사이버 공격 및 내부자 위협으로부터 엔터프라이즈 하이브리드 환경을 보호하는 데 도움이 되는 클라우드 서비스입니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

SecOp 분석가 및 보안 전문가는 ID에 대한 Microsoft Defender의 기능을 통해 고급 위협, 손상된 ID 및 악의적인 내부자 작업을 감지하고 조사할 수 있습니다. 최종 사용자는 Microsoft Defender에서 ID를 모니터링하여 데이터를 모니터링할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 보안, Microsoft F5 보안 & 규정 준수 및 사용자 ID에 대한 Microsoft Defender는 ID에 대한 Microsoft Defender의 혜택을 받을 수 있는 권한을 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 Id에 대한 Microsoft Defender 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. Azure ATP 구성에 대한 자세한 내용은 [Create your Microsoft Defender for Identity instance를 참조하세요.](/defender-for-identity/install-step1)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

Microsoft Defender for Identity Services는 현재 특정 사용자로 기능을 제한할 수 없습니다. 혜택을 제공하려는 모든 사용자에게 라이선스를 부여해야 합니다.

## <a name="microsoft-defender-for-office-365"></a>Office 365용 Microsoft Defender

Microsoft Defender for Office 365(이전의 Advanced Threat Protection Office 365)는 피싱 및 제로 데이 맬웨어와 같은 정교한 공격으로부터 조직을 보호하는 데 도움이 됩니다. 또한 Microsoft Defender for Office 365 광범위한 데이터의 신호와 상호 관련하여 잠재적인 위협을 해결 하는 방법에 대한 권장 사항을 식별, 우선 순위 지정 및 제공하는 데 도움이 되는 실행 가능한 인사이트를 제공합니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

Microsoft Defender for Office 365 피싱 및 제로 데이 맬웨어와 같은 정교한 공격으로부터 사용자를 보호합니다. 계획 1 및 계획 2에 제공된 전체 서비스 목록은 Microsoft [Defender for Office 365.](/microsoft-365/security/office-365-security/office-365-atp)

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까? 

Microsoft Defender for Office 365 요금제 1 및 2, Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 보안, Microsoft 365 F5 보안 & 규정 준수 및 Microsoft 365 Business Premium Microsoft Defender의 혜택을 받을 수 있는 권한을 Office 365.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 microsoft Defender for Office 365 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. 라이선스가 있는 사용자에 대해 Microsoft Defender를 Office 365 정책에 대한 자세한 내용은 Microsoft [Defender for Office 365.](/microsoft-365/security/office-365-security/office-365-atp)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

Microsoft Defender에서 Office 365 범위 지정을 금고 첨부 파일 배포 금고 따라야 합니다.

- 라이선스가 있는 사용자에 대한 금고 링크 구성에 대한 자세한 내용은 microsoft [Defender에서](/microsoft-365/security/office-365-security/atp-safe-links)금고 링크를 Office 365.

- 라이선스가 있는 사용자에 대해 금고 첨부 파일을 구성하는 금고 [Microsoft Defender의](/microsoft-365/security/office-365-security/atp-safe-attachments)첨부 파일을 Office 365.

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

Microsoft Cloud App Security(MCAS)는 조직이 클라우드 앱 및 서비스를 볼 수 있도록 해주며 사이버 위협을 식별하고 퇴치하기 위한 정교한 분석을 제공하는 CASB(Cloud Access Security Broker) 솔루션으로, 모든 클라우드 앱을 통해 데이터가 이동하는 방법을 제어할 수 있도록 &mdash; 합니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

MCAS는 섀도 IT를 검색 및 평가하고, 첫 번째 및 타사 클라우드 앱에서 위협 방지를 제공하며, 첫 번째 및 타사 클라우드 앱의 정보를 보호합니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Enterprise Mobility + Security E5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 보안, Microsoft 365 E5/A5/G5/F5 규정 준수, Microsoft 365 F5 보안 & 규정 준수 및 Microsoft 365 정보 보호 및 거버넌스를 통해 사용자가 MCAS를 혜택을 받을 수 있는 권한을 제공합니다.

Azure AD P1은 사용자가 MCAS의 검색 기능을 사용할 수 있는 권한을 제공합니다.

MCAS의 조건부 액세스 앱 제어 기능을 사용하려면 Enterprise Mobility + Security F1/F1/E3/A3/G3, Enterprise Mobility + Security E5, Microsoft 365 E3/A3/G3, Microsoft 365 E5/A5/G5 및 Microsoft 365 E5/A5/G5 보안 및 Microsoft 365 F5 보안 & 규정 준수에 포함된 Azure Active Directory P1에 대한 사용이 허가되어야 합니다.

자동 클라이언트 쪽 레이블 지정을 사용하려면 사용자에게 Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 준수, Microsoft 365 F5 보안 정책에 포함된 Azure Information Protection P2에 대한 라이선스가 & 규정 준수 및 Microsoft 365 보호 및 거버넌스를 준수합니다.

> [!NOTE]
> 자동 서버 쪽 레이블 지정을 사용하려면 Office 365 -Premium(또는 )에 대한 정보 보호가 `MIP_S_CLP2` `efb0351d-3b08-4503-993d-383af8de41e3` 필요합니다. 참조는 라이선스에 대한 제품 이름 및 서비스 [계획 식별자를 참조하세요.](/azure/active-directory/enterprise-users/licensing-service-plan-reference)

자세한 내용은 라이선스 [데이터시트의 Microsoft Cloud App Security 참조하세요.](https://www.aka.ms/mcaslicensing)

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 MCAS 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다.

라이선스가 있는 사용자에 대한 Microsoft Cloud App Security 정책 구성에 대한 자세한 내용은 Microsoft Cloud App Security [개요를 참조하세요.](/cloud-app-security/what-is-cloud-app-security)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

관리자는 서비스에서 사용할 수 있는 범위가 지정한 배포 기능을 사용하여 사용이 허가된 사용자로 MCAS 배포 범위를 지정합니다. 자세한 내용은 [범위가 지정한 배포를 참조하세요.](/cloud-app-security/scoped-deployment)

## <a name="microsoft-defender-for-endpoint"></a>끝점용 Microsoft Defender

끝점용 Microsoft Defender(이전의 Microsoft Defender ATP)는 위험 기반 보안 솔루션으로, 위험 기반 취약성 관리 솔루션입니다. 공격 표면 감소 기능 동작 기반 및 클라우드 기반 차세대 보호 끝점 검색 및 응답(EDR); 자동 조사 및 수정 및 관리되는 헌팅 서비스. 자세한 [내용은 끝점용 Microsoft Defender 페이지를](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) 참조하세요.

### <a name="which-users-benefit-from-the-service"></a>어떤 사용자가 서비스를 혜택을 받을 수 있나요?

Windows 10 Enterprise E5, Windows 10 Education A5, Microsoft 365 E5/G5의 사용이 허가된 사용자는 Windows 10 Enterprise E5, Microsoft 365 E5/A5/G5/F5 보안 및 Microsoft 365 F5 보안 & 준수가 끝점용 Microsoft Defender의 혜택을 받을 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

SecOps 분석가 및 보안 전문가는 끝점용 Microsoft Defender의 끝점 보안 기능을 통해 예방 보호, 사후 위반 감지, 자동화된 조사 및 고급 위협에 대한 대응을 제공합니다. 최종 사용자는 끝점용 Microsoft Defender에서 악성 이벤트를 모니터링하여 이점을 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 Microsoft Defender for Endpoint 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. 배포에 대한 자세한 내용은 [배포 단계를 참조하세요.](/windows/security/threat-protection/microsoft-defender-atp/deployment-phases)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

끝점용 Microsoft Defender 관리자는 RBAC(역할 기반 액세스 제어)를 사용하여 보안 운영 팀 내에서 역할 및 그룹을 만들어 해당 역할에 적절한 액세스 권한을 부여할 수 Microsoft Defender 보안 센터. 자세한 내용은 역할 기반 액세스 제어를 사용하여 포털 액세스 [관리를 참조하세요.](/windows/security/threat-protection/microsoft-defender-atp/rbac)

## <a name="microsoft-graph-apis-for-teams-data-loss-prevention-dlp-and-for-teams-export"></a>Microsoft Graph DLP(Teams 손실 방지) 및 데이터 내보내기용 TEAMS API

이러한 API를 통해 개발자는 거의 실시간으로 메시지를 듣거나 1:1/group 채팅 또는 Teams 채널에서 팀 메시지를 내보낼 Microsoft Teams 보안 및 규정 준수 앱을 빌드할 수 있습니다. 이러한 API를 통해 고객과 ISV 모두에 대해 DLP 및 기타 정보 보호 및 거버넌스 시나리오를 사용할 수 있습니다. 또한 Microsoft Graph 패치 API를 사용하면 메시지에 DLP Teams 적용할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

[DLP(데이터 손실 방지)](/microsoft-365/compliance/dlp-microsoft-teams) 기능은 특히 조직이 원격 작업으로 Microsoft Teams 조직에서 널리 사용됩니다. 조직에 DLP가 있는 경우 이제 사용자가 특정 채널 또는 채팅 세션에서 중요한 정보를 공유하지 못하게 하는 Microsoft Teams 수 있습니다.

정보 보호 및 거버넌스 기능은 특히 조직이 원격 작업으로 Microsoft Teams 조직에서 널리 사용됩니다. 내보내기 [Teams](/microsoftteams/export-teams-content)사용하여 데이터를 타사 eDiscovery 또는 준수 보관 응용 프로그램으로 내보내 규정 준수 사례를 충족할 수 있습니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

API 액세스는 테넌트 수준에서 구성됩니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

Microsoft Graph DLP Teams 및 Teams 내보내기용 API는 테넌트 수준 값을 제공합니다. 이 서비스를 이용하려는 모든 사용자는 사용이 허가되어야 합니다. 추가 가치로, 라이선스가 있는 사용자당 시드 용량, 월별 계산 및 테넌트 수준에서 집계되는 시드 용량을 추가합니다. 시드된 용량을 초과하는 사용량의 경우 앱 소유자에게 API 사용에 대한 대금이 청구됩니다.

시드된 용량 및 소비 요금에 대한 자세한 내용은 채팅 메시지 액세스에 Graph 요구 [사항을 참조하세요.](/graph/teams-licenses)

## <a name="office-365-advanced-message-encryption"></a>Office 365 고급 메시지 암호화

Office 365 고급 메시지 암호화 통해 고객은 외부 받는 사람에 대한 보다 유연한 제어와 암호화된 전자 메일 액세스에 대한 규정 준수 의무를 충족할 수 있습니다. 관리자는 고급 메시지 암호화를 사용하여 중요한 정보 유형(예: 개인 식별 정보 또는 재무 또는 상태 식별)을 검색할 수 있는 자동 정책을 사용하여 조직 외부에서 공유되는 중요한 전자 메일을 제어하거나, 키워드를 사용하여 사용자 지정 전자 메일 서식 파일을 적용하고 보안 웹 포털을 통해 암호화된 전자 메일에 대한 액세스를 만료하여 보호를 강화할 수 있습니다. 또한 관리자는 보안 웹 포털을 통해 외부에서 액세스하는 암호화된 전자 메일을 제어할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

메시지 보낸 사람이 고급 메시지 암호화에서 제공하는 중요한 전자 메일에 대한 추가 제어를 통해 혜택을 받을 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 규정 준수 및 F5 보안 & 규정 준수 및 Microsoft 365 E5/A5/G5 정보 보호 및 거버넌스를 통해 고급 메시지 암호화를 사용할 수 있는 권한을 사용자에게 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

관리자는 메일 흐름 규칙의 Exchange 관리 센터에서 고급 메시지 암호화 **정책을** 만들고  >  **관리합니다.** 기본적으로 이러한 규칙은 테넌트의 모든 사용자에게 적용됩니다. 새 메시지 암호화 기능을 설정하는 자세한 내용은 [Set up new Office 365 메시지 암호화 capabilities을 참조하십시오.](/office365/securitycompliance/set-up-new-message-encryption-capabilities)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

관리자는 고급 메시지 암호화에 대한 메일 흐름 규칙을 사용이 허가된 사용자에게만 적용해야 합니다. 메일 흐름 규칙을 정의하는 데 대한 자세한 내용은 [Define mail flow rules to encrypt email messages in Office 365.](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)

## <a name="office-365-cloud-app-security"></a>Office 365 Cloud App Security

Office 365 Cloud App Security(OCAS)는 Microsoft Cloud App Security 클라우드 앱 및 IaaS 서비스에 대한 추가 보안 없이 Office 365 기능으로 제한됩니다.

OCAS는 조직이 생산성 클라우드 앱 및 서비스를 볼 수 있도록 하여 사이버 위협을 식별하고 퇴치하기 위한 정교한 분석을 제공하며, 조직에서 데이터를 이동하는 방법을 제어할 &mdash; 수 Office 365.

기능을 비교하기 위해 의 차이점을 [Microsoft Cloud App Security Office 365 Cloud App Security.](/cloud-app-security/editions-cloud-app-security-o365)

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

OCAS는 섀도 IT를 검색하고, 여러 Office 365 보호를 제공하며, 데이터에 액세스할 수 있는 권한이 있는 앱을 제어할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Office 365 E5/A3/A5/G5는 사용자가 OCAS를 혜택을 받을 수 있는 권한을 제공합니다.
자세한 내용은 라이선스 [데이터시트의 Microsoft Cloud App Security 참조하세요.](https://www.aka.ms/mcaslicensing)

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 OCAS 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다.

서비스 구성에 대한 자세한 내용은 에 대한 기본 설정을 [Cloud App Security.](/cloud-app-security/general-setup)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

관리자는 OCAS 배포 범위를 지정하여 특정 앱에 액세스하는 방법을 적용하고 관리자가 모니터링하는 사용자 그룹을 제한할 Office 365 Cloud App Security. 자세한 내용은 [범위가 지정한 배포를 참조하세요.](/cloud-app-security/scoped-deployment)

## <a name="office-365-customer-lockbox"></a>Office 365 고객 Lockbox

고객 Lockbox는 고객에게 서비스 작업에 대한 명시적 액세스 권한 부여를 제공하는 기능을 제공하여 추가적인 제어 계층을 제공합니다. 고객 Lockbox는 명시적 데이터 액세스 권한 부여를 위한 절차가 준비 중이기 때문에 조직이 HIPAA 및 FedRAMP와 같은 특정 규정 준수 의무를 이행하는 데에도 도움이 될 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

Customer Lockbox는 Microsoft의 어느 누구도 고객의 명시적 승인 없이도 고객 콘텐츠에 액세스하여 서비스 작업을 수행할 수 있도록 합니다. Customer Lockbox는 고객에게 콘텐츠에 액세스하기 위한 요청에 대한 승인 워크플로로 고객을 유치합니다. 경우에 따라 Microsoft 엔지니어가 지원 프로세스 중에 관련되어 고객이 보고한 문제를 해결합니다. 대부분의 경우 문제는 Microsoft가 서비스에 대해 준비한 광범위한 원격 분석 및 디버깅 도구를 통해 해결됩니다. 그러나 Microsoft 엔지니어가 고객 콘텐츠에 액세스하여 근본 원인을 파악하고 문제를 해결해야 하는 경우도 있을 수 있습니다. 고객 Lockbox를 사용하려면 엔지니어가 승인 워크플로의 마지막 단계로 고객의 액세스를 요청해야 합니다. 이를 통해 조직은 Microsoft 엔지니어가 조직의 최종 사용자 데이터에 액세스할 수 있는지 여부를 직접 제어할 수 있도록 이러한 요청을 승인하거나 거부할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 규정 준수 및 F5 보안 & 규정 준수 및 Microsoft 365 E5/A5/G5 내부자 위험 관리는 사용자가 고객 Lockbox를 혜택을 받을 수 있는 권한을 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

관리자는 사용자 계정에서 고객 Lockbox를 Microsoft 365 관리 센터. 자세한 내용은 에서 [Customer Lockbox in Office 365.](/microsoft-365/compliance/customer-lockbox-requests) Customer Lockbox가 켜져 있는 경우 Microsoft는 콘텐츠에 액세스하기 전에 조직의 승인을 얻어야 합니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

현재 고객 Lockbox 서비스는 특정 사용자로 제한될 수 없습니다. 테넌트 서비스가 현재 특정 사용자로 혜택을 제한할 수 없는 경우 라이선스가 있는 사용자로 서비스 혜택을 제한하기 위해 노력해야 합니다. 이렇게 하면 대상 지정 기능을 사용할 수 있는 경우 잠재적인 서비스 중단을 방지할 수 있습니다.

## <a name="office-365-message-encryption"></a>Office 365 메시지 암호화

OME(Office 365 메시지 암호화)는 Azure RMS(권한 관리)를 기반으로 구축된 서비스로, 대상의 전자 메일 주소(Gmail, Yahoo! Mail, Outlook.com 등)에 상관없이 사용자 조직 내부 또는 외부 사람에게 암호화된 전자 메일을 보낼 수 있습니다.

암호화된 메시지를 보려면 받는 사람이 일회용 암호를 얻어 Microsoft 계정에 로그인하거나 Office 365와 연결된 회사 또는 학교 계정을 사용하여 로그인할 수 있습니다. 받는 사람은 암호화된 회신을 보낼 수도 있습니다. 암호화된 메시지를 보거나 암호화된 답신을 보내기 위해 구독이 필요하지 않습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

메시지 보낸 사람에 의해 제공된 중요한 전자 메일에 대한 추가된 제어를 통해 Office 365 메시지 암호화.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 E3/A3/G3, Office 365 E3/A3/G3 및 Azure Information Protection 요금제 1은 사용자가 Office 365 메시지 암호화.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

관리자는 메일 흐름 규칙의 Office 365 메시지 암호화 관리 센터에서 Exchange 정책을 **만들고**  >  **관리합니다.** 기본적으로 이러한 규칙은 테넌트의 모든 사용자에게 적용됩니다. 새 메시지 암호화 기능을 설정하는 Office 365 메시지 암호화 자세한 내용은 [Set up new Message Encryption capabilities을 참조하십시오.](/office365/securitycompliance/set-up-new-message-encryption-capabilities)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

관리자는 사용이 허가된 사용자에게만 Office 365 메시지 암호화 메일 흐름 규칙을 적용해야 합니다. 메일 흐름 규칙을 정의하는 데 대한 자세한 내용은 [Define mail flow rules to encrypt email messages를 참조하십시오.](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)

## <a name="privileged-access-management-in-office-365"></a>Office 365의 권한 있는 액세스 관리

[PAM(권한](/microsoft-365/compliance/privileged-access-management-configuration) 있는 액세스 관리)은 팜의 권한 있는 관리 작업에 대한 세부적인 액세스 제어를 Office 365. PAM을 사용하도록 설정한 후 권한이 상승된 작업을 완료하려면 사용자는 범위가 넓고 시간이 제한적인 승인 워크플로를 통해 적시 액세스를 요청해야 합니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

PAM을 사용하도록 설정하면 조직이 제로 스탬드 권한으로 작동할 수 있습니다. 사용자는 데이터에 대한 불안정한 액세스를 제공하는 상시 관리 액세스로 부터의 취약성에 대한 추가 방어 계층을 통해 혜택을 받을 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까? 

Office 365 E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5/F5 규정 준수 및 F5 보안 & 규정 준수 및 Microsoft 365 E5/A5 정보 보호 및 거버넌스를 통해 사용자가 PAM을 혜택을 받을 수 있는 권한을 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 PAM 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. PAM 정책 구성에 대한 자세한 내용은 권한 있는 액세스 관리 [시작을 참조하세요.](/microsoft-365/compliance/privileged-access-management-configuration)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

고객은 승인자 그룹 및 액세스 정책을 통해 사용자 기준으로 PAM을 관리할 수 있으며, 이 정책은 라이선스가 있는 사용자에게 적용할 수 있습니다. 자세한 내용은 에서 권한 있는 액세스 관리를 [Office 365.](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751)

## <a name="records-management"></a>레코드 관리

레코드 관리는 조직이 타사 및 타사 데이터에서 검색, 분류, 레이블 지정, 보존 및 방어할 수 있는 삭제 기능을 Microsoft 365 및 규정 기록 보존 의무를 충족하는 데 도움이 됩니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 규정 준수 및 F5 보안 & 규정 준수, Microsoft 365 정보 보호 및 거버넌스 E5/A5/G5 및 Office 365 E5/A5/G5는 사용자가 레코드 또는 규정 레코드로 항목을 선언하는 등 레코드 관리의 혜택을 받을 수 있는 권한을 제공합니다. 보존 또는 레코드 레이블을 자동으로 적용하고 처리 검토 프로세스를 실행합니다(학습 가능한 분류자에 따라 보존 레이블을 자동으로 적용하는 경우 제외).

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 규정 준수 및 F5 보안 & 규정 준수 및 Microsoft 365 정보 보호 및 거버넌스를 통해 학습 가능한 분류자를 기반으로 보존 또는 기록 레이블을 자동으로 적용하여 혜택을 받을 수 있는 권한을 사용자에게 제공합니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

사용자는 콘텐츠를 레코드로 선언하고 정책 정의 및 선언을 통해 방어할 수 있는 폐기로 전체 레코드 프로세스를 관리할 수 있습니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 레코드 관리 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. 라이선스가 있는 사용자에 대해 적용할 레코드 관리를 구성하는 데 대한 자세한 내용은 [에서 레코드 관리에 대한 Microsoft 365.](/microsoft-365/compliance/records-management)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

레코드 관리 기능은 특정 위치(팀 사이트, 그룹 사이트 등)의 사용이 허가된 사용자에게 적용할 수 있습니다. 라이선스가 있는 사용자에 대해 적용할 레코드 관리를 구성하는 데 대한 자세한 내용은 [에서 레코드 관리에 대한 Microsoft 365.](/microsoft-365/compliance/records-management)
