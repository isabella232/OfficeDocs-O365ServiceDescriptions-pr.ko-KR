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
ms.openlocfilehash: 2eadbb9481dc803863c5053a26cd42c7afab6976
ms.sourcegitcommit: 1de205ecf7df78abe558d71f1c225087501382b4
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/10/2022
ms.locfileid: "62523163"
---
# <a name="microsoft-365-guidance-for-security-amp-compliance"></a>Microsoft 365 규정 준수를 위한 지침 &amp;

이 문서의 목적을 위해 테넌트 수준 서비스는 테넌트의 모든 사용자에 대해 부분적으로 또는 전체적으로 활성화되는 온라인 서비스입니다(독립 실행형 라이선스 및/또는 Microsoft 365 또는 Office 365 계획의 일부로). 온라인 서비스를 사용하려면 적절한 구독 라이선스가 필요합니다. 사용자 라이선스를 사용자에게 라이선스를 주어 규정 준수 기능을 Microsoft 365 옵션을 확인하려면Microsoft 365  [비교 표를 다운로드하세요](https://go.microsoft.com/fwlink/?linkid=2139145).

일부 테넌트 서비스는 현재 특정 사용자로 혜택을 제한할 수 없습니다. 사용이 허가된 사용자에 대한 서비스 혜택을 제한하기 위해 노력해야 합니다. Microsoft 라이선싱 프로그램을 통해 획득한 Microsoft 제품 및 Professional 서비스 사용에 대한 사용 약관을 검토하기 위해 사용 약관 [을 참조합니다](https://www.microsoft.com/Licensing/product-licensing/products).


## <a name="advanced-audit"></a>고급 감사

Microsoft 365 감사는 사용자 및 관리자 활동에 대한 감사 로그의 1년 보존을 제공하며, 사용자 지정 감사 로그 보존 정책을 만들어 다른 Microsoft 365 서비스에 대한 감사 로그 보존을 관리하는 기능을 제공합니다. 또한 조사를 위한 중요한 이벤트에 대한 액세스와 데이터 관리 활동 API에 대한 Office 365 액세스할 수 있습니다. 자세한 내용은 고급 감사 [in Microsoft 365](/microsoft-365/compliance/advanced-audit).

추가 기능 SKU를 사용하여 10년의 보존 기간을 사용하도록 설정할 수 있습니다.

### <a name="which-users-benefit-from-the-service"></a>어떤 사용자가 서비스를 혜택을 받을 수 있나요?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 규정 준수, Microsoft 365 F5 보안 & 규정 준수 및 Microsoft 365 E5/A5/G5 eDiscovery 및 감사의 사용이 허가된 사용자는 고급 감사를 통해 혜택을 받을 수 있습니다.

고급 감사 및 10년 감사 로그 보존 추가 기능을 사용이 허가된 사용자는 10년 감사 로그 보존을 통해 혜택을 받을 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

사용자는 고급 감사를 통해 혜택을 받을 수 있습니다. Microsoft 365 서비스의 사용자 활동과 관련된 감사 레코드는 최대 1년 동안 보존할 수 있습니다. 또한 사용자 사서함의 항목에 액세스하거나 읽은 경우와 같은 고가치 감사 이벤트가 기록됩니다. 자세한 내용은 고급 감사 [in Microsoft 365](/microsoft-365/compliance/advanced-audit).

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 고급 감사는 서비스를 통해 혜택을 받은 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정되며, Azure Active Directory, Exchange 및 서비스에서 활동에 대한 감사 로그(적절한 라이선스가 있는 사용자가 수행)에 대한 1년 보존을 자동으로 SharePoint. 또한 조직은 감사 로그 보존 정책을 사용하여 다른 Microsoft 365 서비스의 활동으로 생성된 감사 레코드의 보존 기간을 관리할 수 있습니다. 10년 감사 로그 보존 기능은 동일한 보존 정책을 사용하여 사용하도록 설정됩니다. 자세한 내용은 [감사 로그 보존 정책 관리](/microsoft-365/compliance/audit-log-retention-policies)를 참조하십시오.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

감사 로그의 1년 보존 및 중요한 이벤트 감사는 해당 라이선스가 있는 사용자에게만 적용됩니다. 또한 관리자는 감사 로그 보존 정책을 사용하여 특정 사용자의 감사 로그에 대한 더 짧은 보존 기간을 지정할 수 있습니다.

감사 로그의 10년 보존은 적절한 추가 기능 라이선스가 있는 사용자에게만 적용됩니다. 추가 기능 SKU는 2021년 초부터 필요합니다.

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory ID 보호

Azure Active Directory ID 보호는 조직의 ID에 영향을 주는 잠재적인 취약점을 감지하고, 조직의 ID와 관련된 의심스러운 작업에 대해 자동화된 응답을 구성하고, 의심스러운 사고를 조사할 수 있는 Azure Active Directory Premium P2 계획의 기능입니다. 적절한 조치를 취하여 해결합니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

SecOps 분석가 및 보안 전문가는 기계 학습 알고리즘을 기반으로 플래그가 지정된 사용자 및 위험 이벤트에 대한 통합된 보기를 사용할 수 있습니다. 최종 사용자는 위험 기반 조건부 액세스를 통해 제공되는 자동 보호와 취약성에 대해 행동하여 제공되는 향상된 보안을 통해 혜택을 받을 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

- Azure Active Directory 계획 1: Microsoft 365 E3/A3/G3/F1/F3, Enterprise Mobility & Security E3 및 Microsoft 365 Business Premium
- Azure Active Directory 계획 2: Microsoft 365 E5/A5/G5, Enterprise Mobility & Security E5, Microsoft 365 E5/F5 Security 및 Microsoft 365 F5 Security & Compliance

사용 가능한 여러 계획에 포함된 기능에 대한 자세한 내용은 ID 보호가 [Azure Active Directory 참조하세요.](/azure/active-directory/identity-protection/overview-identity-protection#license-requirements)

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 Azure AD ID 보호 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. Azure AD ID 보호에 대한 자세한 내용은 ID 보호란? [을 참조하세요.](/azure/active-directory/identity-protection/overview-identity-protection)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

관리자는 암호 재설정 수준을 정의하는 위험 정책을 할당하고 라이선스가 있는 사용자에 한해 액세스를 허용하여 Azure AD ID 보호의 범위를 지정할 수 있습니다. Azure AD ID 보호 배포의 범위를 지정하는 방법에 대한 지침은 위험 정책을 구성하고 사용하도록 설정 [하는 방법을 참조하세요](/azure/active-directory/identity-protection/howto-sign-in-risk-policy).

## <a name="azure-active-directory-identity-governance"></a>Azure Active Directory ID 거버넌스

Azure Active Directory ID 거버넌스를 사용하면 보안 및 직원 생산성에 대한 조직의 요구를 올바른 프로세스 및 가시성과 균형을 맞출 수 있습니다. 권한 관리, 액세스 검토, 권한 있는 ID 관리 및 사용 약관 정책을 사용하여 올바른 사용자가 올바른 리소스에 액세스할 수 있도록 합니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

Azure Active Directory ID 거버넌스를 통해 한 액세스 패키지에서 앱, 그룹 및 그룹에 대한 액세스를 Microsoft Teams 수 있도록 하여 사용자의 생산성을 향상시킵니다. 관리자가 개소하지 않고도 사용자를 승인자로 구성할 수도 있습니다. 액세스 검토를 위해 사용자는 스마트 권장 사항이 있는 그룹의 구성원 자격을 검토하여 정기적으로 작업을 수행 할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5/F5 보안 및 F5 보안 & 규정 준수 및 Azure Active Directory Premium 계획 2는 사용자가 혜택을 받을 수 있는 권한을 제공합니다. Azure Active Directory ID 거버넌스를 관리합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

Azure AD ID 거버넌스 기능은 테넌트 수준에서 사용하도록 설정되지만 사용자당 구현됩니다. Azure AD ID 거버넌스에 대한 자세한 내용은 Azure AD ID 거버넌스 [란?을 참조하세요.](/azure/active-directory/governance/identity-governance-overview)

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

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 규정 준수, Microsoft 365 F5 보안 & 규정 준수 및 Microsoft 365 E5/A5/G5 내부자 위험 관리는 사용자가 통신을 통해 혜택을 받을 수 있는 권한을 제공합니다. compliance.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

관리자 및 규정 준수 전문가는 2016년 8월 2일부로 Microsoft 365 규정 준수 센터. 이러한 정책은 조직에서 검토할 통신 및 사용자를 정의하고, 통신이 충족해야 하는 사용자 지정 조건을 정의하고, 검토를 수행할 사용자를 지정합니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

관리자는 통신 준수 정책에 포함할 특정 사용자 또는 그룹을 선택합니다. 그룹을 선택할 때 그룹에서 통신 준수 정책에서 제외할 특정 사용자를 선택할 수도 있습니다. 통신 준수 정책에 대한 자세한 내용은 [Get started with communication compliance in Microsoft 365](/microsoft-365/compliance/communication-compliance-configure).

## <a name="compliance-manager"></a>규정 관리자

[Microsoft 준수 관리자는](https://compliance.microsoft.com/compliancemanager) 조직의 규정 Microsoft 365 규정 준수 센터 보다 간편 [](/microsoft-365/compliance/microsoft-365-compliance-center) 하고 쉽게 관리할 수 있도록 하여 조직의 규정 준수 요구 사항을 관리하는 데 도움이 되는 조직의 기능입니다. 준수 관리자는 데이터 보호 위험 상세 조사부터 제어 구현의 복잡성 관리, 규정 및 인증의 최신 정보 유지, 보고 및 감사까지, 여러분의 규정 준수를 향한 여정을 도와드릴 수 있습니다.

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

다음은 프리미엄 [평가 목록입니다](/microsoft-365/compliance/compliance-manager-templates-list#premium-templates).

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

## <a name="compliance-program-for-microsoft-cloud"></a>Microsoft 클라우드를 위한 규정 준수 프로그램

[Microsoft 클라우드용 규정 준수 프로그램은](https://aka.ms/cpmc) 개인 설정된 고객 지원, 교육 및 네트워킹 기회를 제공하도록 고안된 것입니다. 이 프로그램에 참여하면 고객은 보안, 규정 준수 및 개인 정보 보호 영역에서 규제 기관, 업계 동료 및 Microsoft 전문가와 직접 참여할 수 있는 고유한 기회를 받게 됩니다. 이 프로그램은 2013에서 만든 기존 FSI(금융 서비스 산업) 준수 프로그램을 대체합니다.

### <a name="who-can-access-the-compliance-program-for-microsoft-cloud"></a>Who Microsoft 클라우드 규정 준수 프로그램에 액세스할 수 있나요?

Microsoft 클라우드에 대한 규정 준수 프로그램은 라이선스가 Microsoft 365 Office 365 있습니다.

현재 FSI 준수 프로그램에 등록된 고객은 Microsoft 클라우드에 대한 새 준수 프로그램의 구독을 구입해야 합니다. 자세한 내용은 [Microsoft 클라우드용 준수 프로그램을 참조하세요](https://aka.ms/cpmc).

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

Enterprise, 규정 준수 책임자, 내부 감사자, 개인 정보 보호 책임자, 규제 업무/법률, CISOS 등 클라우드 여정을 지원하기 위해 Microsoft를 찾고 있는 조직이 이 서비스를 통해 혜택을 받을 수 있습니다. 다음은 고객이 받을 수 있는 사용 가능한 혜택의 예제 시나리오입니다.

- Microsoft 클라우드 서비스를 온보드하고 사용하기 위한 위험 평가에 대한 지속적인 위험 및 규정 준수 지원
- Microsoft 클라우드 서비스에 대한 Microsoft 및 고객 관리 컨트롤 지원
- 타사 클라우드 서비스를 사용하는 내부 감사, 규제 기관 또는 보드 수준 승인에 대한 지원
- 클라우드 서비스 사용 시 복잡한 위험 및 규정 준수 요구 사항과 관련된 지속적인 기술 질문에 대한 지원
- 고정된 수의 고객 위험 및 규정 준수 설문지 작성에 대한 직접적인 지원.
- 규정 준수 여정을 통해 질문을 해결하는 데 도움이 되는 규제 기관 및 업계 전문가와의 연결입니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 Microsoft 클라우드에 대한 준수 프로그램은 서비스를 통해 혜택을 받을 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. 자세한 내용은 [Microsoft 클라우드용 준수 프로그램을 참조하세요](https://aka.ms/cpmc).

## <a name="data-connectors"></a>데이터 커넥터

Microsoft는 Microsoft에서 구성할 수 있는 타사 데이터 커넥터를 Microsoft 365 규정 준수 센터. Microsoft에서 제공하는 데이터 커넥터 목록은 타사 데이터 커넥터 테이블 [을 참조](/microsoft-365/compliance/archiving-third-party-data#third-party-data-connectors) 하세요. 또한 이 표에는 데이터 가져오기 및 보관 후 타사 데이터에 적용할 수 있는 규정 Microsoft 365 각 커넥터에 대한 단계별 지침에 대한 링크도 요약되어 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

데이터 커넥터를 사용하여 타사 데이터를 가져오고 Microsoft 365 가장 큰 이점은 데이터를 가져온 후 데이터에 다양한 Microsoft 365 규정 준수 솔루션을 적용할 수 있는 것입니다. 이를 통해 조직의 비 Microsoft 데이터가 조직에 영향을 주는 규정 및 표준을 준수하는지 보장할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

다음 라이선스는 사용자가 데이터 커넥터를 혜택을 받을 수 있는 권한을 제공합니다.

- Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5 정보 보호 &amp; 거버넌스
- Microsoft 365 E5/A5/G5/F5 규정 준수
- Microsoft 365 F5 보안 및 & 준수
- Microsoft 365 E5/A5/G5 내부자 위험 관리
- Microsoft 365 E5/A5/G5 eDiscovery 및 감사
- Office 365 E5/A5/G5

Microsoft 파트너가 제공하는 Microsoft 365 보안 &amp; 및 준수 센터의 데이터 커넥터의 경우 조직에서 해당 커넥터를 배포하려면 먼저 파트너와의 비즈니스 관계가 필요합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

커넥터는 보안 및 &amp; 준수 센터 및 커넥터 카탈로그를 사용하여 구성됩니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

데이터 커넥터 서비스는 테넌트 수준 값입니다. 이 서비스를 이용하려는 모든 사용자는 사용이 허가되어야 합니다.

## <a name="ediscovery"></a>eDiscovery

eDiscovery는 기업 내 IT 및 법률 부서를 위해 조사 및 eDiscovery 솔루션을 제공하여 Microsoft 365 시스템에서 내보내기 전에 조사 또는 소송과 관련된 콘텐츠를 식별, 수집, 보존, 축소 및 검토합니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

사용자는 Advanced eDiscovery 데이터 관리자(문서 또는 전자 파일에 대한 관리 제어권이 있는 사용자)로 선택될 때 사용자의 이점을 누리게 됩니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Exchange Online 계획 2, Exchange Online Archiving, SharePoint Online 계획 2, Microsoft 365 E5/A5/G5/E3/A3/G3, Office 365 E5/A5/G5/E3/A3/G3 및 F5 규정 준수 및 F5 준수 및 F5 보안 & 규정 준수는 사용자가 혜택을 받을 수 있는 권한을 제공합니다. Core eDiscovery.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 규정 준수 및 F5 보안 & 규정 준수, Microsoft 365 E5/A5/G5 eDiscovery 및 감사, Office 365 E5/A5/G5는 사용자가 Advanced eDiscovery.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 Advanced eDiscovery 보안 및 준수 센터에서 eDiscovery &amp; 권한을 할당할 때 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용자 지정 기능이 사용하도록 설정됩니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

eDiscovery 관리자는 Advanced eDiscovery 사례에 관리자 추가에 설명된 바와 같이 기본 제공 관리 도구를 사용하여 특정 사용자를 사례에 대한 데이터 관리자로 선택할 [수 Advanced eDiscovery 있습니다](/microsoft-365/compliance/add-custodians-to-case).

## <a name="information-protection-customer-key-for-microsoft-365"></a>정보 보호: 사용자에 대한 Microsoft 365

고객 키를 사용하여 조직의 암호화 키를 제어하고 microsoft Microsoft 365 센터에서 휴지의 데이터를 암호화하는 데 사용하도록 암호화 키를 구성할 수 있습니다. 즉, 고객 키를 사용하면 자체 키를 사용하여 자신에 속한 암호화 계층을 추가할 수 있습니다. 고객 키는 데이터 저장 암호화 서비스를 통해 여러 Microsoft 365 암호화를 [](/microsoft-365/compliance/customer-key-overview#about-data-encryption-policies) Microsoft 365 암호화를 제공합니다. 또한 고객 키는 SharePoint 온라인 및 비즈니스용 OneDrive 및 사서함 수준 Exchange Online 암호화를 제공합니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

사용자는 조직에서 제공, 제어 및 관리하는 암호화 키를 사용하여 응용 프로그램 계층에서 미사용 데이터를 암호화할 수 있도록 하여 고객 키의 이점을 활용합니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 규정 준수, Microsoft 365 F5 보안 & 규정 준수, Microsoft 365 E5/A5/G5 정보 보호 및 거버넌스, Office 365 E5/A5/G5는 사용자가 혜택을 받을 수 있는 권한을 제공합니다. 고객 키. 고객 키를 완전하게 이용하려면 Azure Key Vault 구독도 있어야 합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

고객 [키 설정 문서](/microsoft-365/compliance/customer-key-set-up) 에서는 필요한 Azure 리소스를 만들고 구성하기 위해 따라야 하는 단계에 대해 설명한 다음 고객 키 설정 단계를 제공합니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

Microsoft 365 암호화 지원을 제공하는 미사용 데이터 저장 서비스는 테넌트 수준 서비스입니다. 기술적으로는 라이선스가 없는 일부 사용자가 서비스에 액세스할 수 있을 수 있을지언정 서비스에서 혜택을 제공하려는 사용자에게는 라이선스가 필요합니다. 사서함 Exchange Online 암호화의 경우 데이터 암호화 정책을 할당하기 위해 사용자 사서함에 사용이 허가되어야 합니다.

## <a name="information-protection-data-classification-analytics-overview-content-amp-activity-explorer"></a>정보 보호: 데이터 분류 분석: 콘텐츠 활동 탐색기 &amp; 개요

데이터 분류 분석 기능은 사용자 환경 내에서 Microsoft 365 규정 준수 센터 있습니다. 개요는 디지털 콘텐츠의 위치와 가장 일반적인 중요한 정보 유형 및 레이블이 있는 위치를 보여줍니다. 콘텐츠 탐색기를 사용하면 중요한 데이터의 양과 유형을 볼 수 있으며 사용자가 레이블 또는 민감도 유형별로 필터링하여 중요한 데이터가 저장된 위치를 자세히 볼 수 있습니다. 활동 탐색기에는 콘텐츠를 위험에 노출할 수 있는 레이블 다운그레드 또는 외부 공유와 같은 중요한 데이터 및 레이블과 관련된 활동이 표시됩니다.

활동 탐색기는 관리자가 최종 사용자가 사용하는 중요한 정보와 관련된 활동에 대한 가시성을 확보할 수 있는 단일 창을 제공합니다. 이러한 데이터에는 레이블 활동, DLP(데이터 손실 방지) 로그, 자동 레이블 지정, 끝점 DLP 등이 포함됩니다.

콘텐츠 탐색기는 지원되는 작업 부하 내에 저장된 중요한 문서를 인덱싱하고 Microsoft 365 중요한 정보를 식별하는 기능을 관리자에게 제공합니다. 또한 콘텐츠 탐색기는 민감도 및 보존 레이블로 분류된 문서를 식별하는 데 도움이 됩니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

정보 보호 및 규정 준수 관리자는 서비스에 액세스하여 이러한 로그 및 인덱싱된 데이터에 액세스하여 중요한 데이터가 저장되는 위치와 이 데이터와 관련된 활동 및 최종 사용자가 수행한 활동을 이해할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 준수, Microsoft 365 F5 보안 & 규정 준수, Microsoft 365 E5/A5/G5 &amp; 정보 보호 거버넌스 및 Office 365 E5 혜택을 받을 수 있는 사용자 Microsoft 365 분류 분석을 제공합니다.

Microsoft 365 E3/A3/G3 및 Office 365 E3/A3/G3을 사용하면 사용자가 콘텐츠 탐색기 데이터 집계만 사용할 수 있습니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 콘텐츠 및 활동 탐색기 개요 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. 라이선스가 있는 사용자에 대한 데이터 분류 분석을 구성하는 데 대한 자세한 내용은 다음을 참조하세요.

- **콘텐츠 탐색기**: [콘텐츠 탐색기를 시작할 수 있습니다](/microsoft-365/compliance/data-classification-content-explorer).
- **활동 탐색기**: [활동 탐색기를 시작할 수 있습니다](/microsoft-365/compliance/data-classification-activity-explorer).
- **데이터 분류 릴리스 정보**: [데이터 분류 릴리스 정보.](/microsoft-365/compliance/data-classification-pub-preview-relnotes)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

이 기능은 규정 준수 포털 내에서 솔루션을 적극적으로 사용하는 Microsoft 365 합니다.

## <a name="information-protection-data-loss-prevention-for-teams"></a>정보 보호: 데이터 손실 Teams

조직에서는 통신 DLP를 사용하여 Teams 정보, 개인 식별 정보, 상태 관련 정보 또는 기타 기밀 정보와 같은 중요한 정보를 포함하는 채팅 및 채널 메시지를 차단할 수 있습니다.

### <a name="which-users-benefit-from-the-service"></a>어떤 사용자가 서비스를 혜택을 받을 수 있나요?

- Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5/F5 규정 준수 및 F5 보안 & 규정 준수
- Microsoft 365 E5/A5/G5 정보 보호 및 거버넌스
- Office 365 E5/A5/G5

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

보낸 사람이 조직의 DLP 정책에 구성된 중요한 정보를 검사한 보내는 채팅 및 채널 메시지에 중요한 정보를 제공하면 도움이 됩니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 Teams 및 채널 메시지는 테넌트 내의 모든 사용자에  대해 이러한 DLP 기능에 대해 사용하도록 설정된 위치(작업량)입니다. DLP 정책 사용에 대한 자세한 내용은 데이터 손실 방지 [개요를 참조하세요](/office365/securitycompliance/data-loss-prevention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

관리자는 데이터 손실 방지 **Locations** 에서 보안 및 준수 센터에서 위치(작업),  > &amp; 포함된 사용자 및 제외된 사용자를 사용자 지정할 수 있습니다.

## <a name="information-protection-data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>정보 보호: Exchange Online, SharePoint Online 및 비즈니스용 OneDrive

Office 365, SharePoint Online 및 비즈니스용 OneDrive에 대한 D Exchange Online LP(데이터 손실 방지)를 사용하여 조직은 전자 메일 및 파일(Microsoft Teams 파일에 저장된 파일 포함)에서 중요한 정보를 식별, 모니터링 및 자동으로 보호할 수 있습니다. 리포지토리)

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

사용자는 조직의 DLP 정책에 구성된 Exchange Online, SharePoint Online 및 비즈니스용 OneDrive 파일에서 중요한 정보를 검사할 때 DLP를 사용할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 E3/A3/Business Premium, Office 365 E3/A3 및 Office 365 데이터 손실 방지 및 F5 준수 및 F5 보안 & 규정 준수는 사용자에게 Office 365 DLP의 혜택을 받을 수 있는 권한을 Exchange Online. SharePoint Online 및 비즈니스용 OneDrive.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 Exchange Online, SharePoint 사이트 및 OneDrive 계정은 테넌트 내의 모든 사용자에 대해 이러한 DLP 기능의 위치(작업)를 사용하도록 설정됩니다. DLP 정책 사용에 대한 자세한 내용은 데이터 손실 방지 [개요를 참조하세요](/microsoft-365/compliance/data-loss-prevention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

관리자는 데이터 손실 방지 **Locations** 에서 보안 및 준수 센터에서 위치(작업),  > &amp; 포함된 사용자 및 제외된 사용자를 사용자 지정할 수 있습니다.

## <a name="information-protection-double-key-encryption-for-microsoft-365"></a>정보 보호: 사용자에 대한 이중 키 Microsoft 365

이중 키 암호화를 Microsoft 365 요구 사항을 충족하고 암호화 키에 대한 모든 제어를 유지 관리하기 위해 매우 중요한 데이터를 보호할 수 있습니다. 이중 키 암호화는 두 개의 키를 사용하여 데이터를 보호합니다. 이 키는 컨트롤에 있는 키 하나와 두 번째 키를 사용하여 안전하게 Microsoft Azure. 데이터를 보기 위해 두 키에 모두 액세스할 수 있어야 합니다. Microsoft는 하나의 키에만 액세스할 수 있으며 키와 데이터도 Microsoft에서 사용할 수 없게 하여 데이터의 개인 정보 및 보안을 완전하게 제어할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

사용자는 암호화된 데이터를 클라우드로 마이그레이션할 수 있게 하여 키가 사용자의 제어에 남아 있는 한 타사 액세스를 방지하여 이중 키 암호화를 사용할 수 있습니다. 사용자는 다른 민감도 레이블로 보호된 콘텐츠와 유사한 이중 키 암호화된 콘텐츠를 보호하고 사용할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 규정 준수 및 F5 보안 & 규정 준수, Microsoft 365 E5/A5/G5 정보 보호 및 거버넌스, Office 365 E5/A5/G5 및 EMS E5는 사용자가 이중 키 암호화를 혜택을 받을 수 있는 권한을 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

이중 키 암호화는 사용자용 데스크톱 Microsoft Office Windows.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

라이선스가 있는 사용자에 대해 Office 365 및/또는 Microsoft 365 조직 내의 데이터에 암호화 키를 할당하기 위해 이중 키 암호화 배포 지침을 따릅니다.

## <a name="information-protection-office-365-advanced-message-encryption"></a>정보 보호: Office 365 고급 메시지 암호화

Office 365 고급 메시지 암호화 통해 고객은 외부 받는 사람에 대한 보다 유연한 제어와 암호화된 전자 메일 액세스에 대한 규정 준수 의무를 충족할 수 있습니다. 관리자는 고급 메시지 암호화를 사용하여 중요한 정보 유형(예: 개인 식별 정보 또는 재무 또는 상태 식별)을 검색할 수 있는 자동 정책을 사용하여 조직 외부에서 공유되는 중요한 전자 메일을 제어하거나, 키워드를 사용하여 사용자 지정 전자 메일 서식 파일을 적용하고 보안 웹 포털을 통해 암호화된 전자 메일에 대한 액세스를 만료하여 보호를 강화할 수 있습니다. 또한 관리자는 보안 웹 포털을 통해 외부에서 액세스하는 암호화된 전자 메일을 제어할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

메시지 보낸 사람이 고급 메시지 암호화에서 제공하는 중요한 전자 메일에 대한 추가 제어를 통해 혜택을 받을 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 규정 준수 및 F5 보안 & 규정 준수 및 Microsoft 365 E5/A5/G5 정보 보호 및 거버넌스를 통해 고급 메시지 암호화를 사용할 수 있는 권한을 사용자에게 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

관리자는 메일 흐름Rules의 Exchange 관리 센터에서 고급 메시지 암호화 **정책을** >  만들고 **관리합니다**. 기본적으로 이러한 규칙은 테넌트의 모든 사용자에게 적용됩니다. 새 메시지 암호화 기능을 설정하는 자세한 내용은 [Set up new Office 365 메시지 암호화 참조하세요](/office365/securitycompliance/set-up-new-message-encryption-capabilities).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

관리자는 고급 메시지 암호화에 대한 메일 흐름 규칙을 사용이 허가된 사용자에게만 적용해야 합니다. 메일 흐름 규칙을 정의하는 데 대한 자세한 내용은 [Define mail flow rules to encrypt email messages in Office 365](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email).

## <a name="information-protection-office-365-message-encryption"></a>정보 보호: Office 365 메시지 암호화

OME(Office 365 메시지 암호화)는 Azure RMS(권한 관리)를 기반으로 구축된 서비스로, 대상의 전자 메일 주소(Gmail, Yahoo! Mail, Outlook.com 등)에 상관없이 사용자 조직 내부 또는 외부 사람에게 암호화된 전자 메일을 보낼 수 있습니다.

암호화된 메시지를 보려면 받는 사람이 일회용 암호를 얻어 Microsoft 계정에 로그인하거나 Office 365와 연결된 회사 또는 학교 계정을 사용하여 로그인할 수 있습니다. 받는 사람은 암호화된 회신을 보낼 수도 있습니다. 암호화된 메시지를 보거나 암호화된 답신을 보내기 위해 구독이 필요하지 않습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

메시지 보낸 사람에 의해 제공된 중요한 전자 메일에 대한 추가된 제어를 통해 Office 365 메시지 암호화.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 E3/A3/G3, Office 365 E3/A3/G3 및 Azure Information Protection 요금제 1은 사용자가 Office 365 메시지 암호화.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

관리자는 메일 흐름 Office 365 메시지 암호화 관리 센터에서 Exchange 정책을  >  만들고 **관리합니다**. 기본적으로 이러한 규칙은 테넌트의 모든 사용자에게 적용됩니다. 새 메시지 암호화 기능을 설정하는 Office 365 메시지 암호화 자세한 내용은 [Set up new Message Encryption capabilities을 참조하십시오](/office365/securitycompliance/set-up-new-message-encryption-capabilities).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

관리자는 사용이 허가된 사용자에게만 Office 365 메시지 암호화 메일 흐름 규칙을 적용해야 합니다. 메일 흐름 규칙을 정의하는 데 대한 자세한 내용은 [Define mail flow rules to encrypt email messages를 참조하십시오](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email).

## <a name="information-protection-sensitivity-labeling"></a>정보 보호: 민감도 레이블 지정

정보 보호는 조직에서 중요한 문서 및 전자 메일을 검색, 분류, 레이블 지정 및 보호하는 데 도움이 됩니다. 관리자는 레이블을 자동으로 적용하는 규칙 및 조건을 정의하거나, 사용자가 레이블을 수동으로 적용하거나, 두 가지 조합을 사용할 수 있습니다. 여기서 사용자에게 레이블 적용에 대한 권장 사항이 제공될 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

사용자는 민감도 레이블을 콘텐츠에 수동으로 적용하거나 콘텐츠를 자동으로 분류하여 혜택을 받을 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

수동 **민감도 레이블 지정의** 경우 다음 라이선스가 사용자 권한을 제공합니다.

- Microsoft 365 E5/A5/G5/E3/A3/F1/F3/Business Premium(Office 365용 정보 보호 - E5 라이선스만 할당된 경우 표준을 사용하도록 설정해야 합니다.
- Enterprise Mobility + Security E3/E5
- Office 365 E5/A5/E3/A3/F3
- AIP 계획 1
- AIP 계획 2

클라이언트 및 **서비스** 쪽 자동 민감도 레이블 지정 모두에 대해 다음 라이선스는 사용자 권한을 제공합니다.

- Microsoft 365 E5/A5/G5
- F5 및 E5 규정 준수
- F5 보안 & 규정 준수
- Microsoft 365 E5/A5/G5 정보 보호 및 거버넌스
- Office 365 E5

클라이언트 **쪽** 자동 민감도 레이블 지정에만 대해 다음 라이선스는 사용자 권한을 제공합니다.

- Enterprise Mobility + Security E5/A5/G5
- AIP 계획 2

Power BI 레이블을 적용하고 보고, Power BI, Excel, PowerPoint 또는 **PDF** 로 내보낼 때 데이터를 보호하기 위해 다음 라이선스는 사용자 권한을 제공합니다.

- Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium
- Enterprise Mobility + Security E3/E5
- AIP 계획 1
- AIP 계획 2

사용자가 [AIPServicePowerShell](/powershell/azure/aip/overview)  모듈을 사용하여 Azure Information Protection에 대한 Azure Rights Management Protection 서비스를 관리할 수 있도록 다음 라이선스에서 사용자 권한을 제공합니다.

- Microsoft 365 Business Premium 및 Enterprise 모바일

> [!NOTE]
> Power BI/Microsoft 365 E5/A5/G5에 포함되어 있습니다. 다른 모든 계획에서는 Power BI 사용이 허가되어야 합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 정보 보호 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. 라이선스가 있는 사용자에 대한 정책을 구성하는 데 대한 자세한 내용은 Azure 권한 관리 활성화를 참조하세요.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

AIP 스캐너 기능을 사용하는 경우를 제외하고 정책의 범위를 특정 그룹 또는 사용자로 지정하거나 레지스트리를 편집하여 라이선스가 없는 사용자가 분류 또는 레이블 지정 기능을 실행하지 못하도록 할 수 있습니다.

AIP 스캐너 기능의 경우 Microsoft는 라이선스가 없는 사용자에게 파일 분류, 레이블 지정 또는 보호 기능을 제공하지 않습니다.

자세한 내용은 [민감](/microsoft-365/compliance/create-sensitivity-labels#publish-sensitivity-labels-by-creating-a-label-policy) 도 레이블 만들기 및 게시 및 Azure Information Protection 통합 레이블 지정 스캐너 [이해를 참조하세요](/azure/information-protection/deploy-aip-scanner).

## <a name="information-barriers"></a>정보 장벽

정보 장벽은 개인 또는 그룹이 서로 통신하지 못하도록 관리자가 구성할 수 있는 정책입니다. 예를 들어 한 부서에서 다른 부서와 공유하면 안되는 정보를 처리하거나 그룹이 외부 연락처와 통신하지 못하게 해야 하는 경우 유용합니다. 정보 장벽 정책은 또한 검색 및 검색을 방지합니다. 즉, 다른 사용자와 통신하지 말아야 하는 경우 사용자 선택에서 해당 사용자를 찾을 수 없습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

사용자는 다른 사용자와의 통신이 제한될 때 정보 장벽의 고급 규정 준수 기능을 통해 혜택을 받을 수 있습니다. 정보 장벽 정책을 정의하여 특정 사용자 세그먼트가 각각과 통신하지 못하도록 방지하거나 특정 세그먼트가 다른 특정 세그먼트와만 통신하도록 허용할 수 있습니다. 정보 장벽 정책 정의에 대한 자세한 내용은 정보 장벽 정책 [정의를 참조하세요](/microsoft-365/compliance/information-barriers-policies). 두 그룹이 서로 통신할 수 없는 시나리오의 경우 두 그룹의 사용자가 서비스를 이용하려면 라이선스가 필요합니다(아래 예제 참조).<br><br>

| 시나리오 | Who 라이선스가 필요한가요? |
|:------|:------|
| 두 그룹(Group1&nbsp; 및 Group2&nbsp;)이 서로 통신할 수 없습니다( 즉, Group1&nbsp; 사용자는 Group2&nbsp; 사용자와의 통신이 제한되고, Group2&nbsp; 사용자는 Group1&nbsp; 사용자와의 통신이 제한됩니다. | Group1 및 Group2&nbsp;의 사용자&nbsp; |

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 규정 준수 및 F5 보안 & 규정 준수, Microsoft 365 E5/A5/G5 내부자 위험 관리 및 Office 365 E5/A5/G5는 사용자가 정보 장벽을 혜택을 받을 수 있는 권한을 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

관리자는 보안 및 준수 센터에서 PowerShell cmdlet을 사용하여 정보 장벽 정책을 &amp; 만들고 관리합니다. 관리자에게 정보 장벽 정책을 만들 Microsoft 365 Enterprise 전역 관리자, Office 365 관리자 역할 또는 준수 관리자 역할이 할당되어야 합니다. 기본적으로 이러한 정책은 테넌트의 모든 사용자에게 적용됩니다. 정보 장벽에 대한 자세한 내용은 정보 장벽을 [Microsoft Teams.](/MicrosoftTeams/information-barriers-in-teams)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

관리자는 보안 및 준수 센터에서 위치(작업), 포함된 사용자 및 제외된 사용자를 사용자 지정할 &amp; 수 있습니다. 예를 들어 모든 사용자에게 Office 365 E3 및 Office 365 Advanced Compliance/E5에 대한 라이선스가 없는 경우 조직에 대한 정보 장벽 정책을 만들 필요가 없습니다. 자세한 내용은 [Microsoft Teams의 정보 장벽](/MicrosoftTeams/information-barriers-in-teams)을 참조하세요.

## <a name="information-governance"></a>정보 거버넌스

정보 거버넌스를 통해 조직은 데이터를 검색, 분류, 레이블 지정 및 관리하여 위험을 관리할 수 있습니다. 정보 거버넌스를 통해 조직은 비즈니스 및 규정 요구 사항을 충족하고, 조직 및 타사 데이터 전반에 걸쳐 보존 및 삭제 기능을 제공하여 공격 Microsoft 365 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

사용자는 특정 정책 및 규정을 준수하기 위해 보존 목적으로 데이터를 분류할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 F3/Business Premium, Office 365 E5/A5/G5/E3/A3/G3/E1/A1/G1/F3 및 독립 실행형 Exchange 계획은 사용자가 사서함 데이터에 레코드가 아닌 보존 레이블을 수동으로 적용하여 혜택을 받을 수 있는 권한을 제공합니다.

Microsoft 365 F3/F1/Business Premium, Office 365 E5/A5/G5/E3/A3/G3/F3/E1/A1/G1 및 독립 실행형 SharePoint 요금제는 사용자가 레코드가 아닌 보존 레이블을 SharePoint 또는 파일의 파일에 수동으로 적용할 수 있는 권한을 OneDrive.

Microsoft 365 E5/A5/G5/E3/A3/Business Premium, Office 365 E5/A5/G5/E3/A3, Exchange 계획 2 및 Exchange Online Archiving 조직 전체 또는 위치 전체 사서함 보존 정책의 혜택을 받을 수 있는 권한을 사용자에게 제공합니다.

Microsoft 365 E5/A5/G5/E3/A3, Office 365 E5/A5/G5/E3/A3 및 SharePoint 계획 2는 사용자가 기본 SharePoint 또는 OneDrive 보존 정책을 통해 혜택을 받을 수 있는 권한을 제공하고, 또는 파일에 기록되지 않은 보존 레이블을 수동으로 적용할 수 있는 권한을 제공합니다. SharePoint OneDrive.

조직은 보존 정책을 사용하여 정책에 따라 Teams 보존하거나 삭제할 수 있습니다. 여기에는 채팅 및 대화에서 Teams 관리가 포함됩니다.

다음 라이선스는 사용자가 보존 정책의 혜택을 받을 Teams 제공합니다.

- Microsoft 365 E5/G5/A5/E3/G3/A3/F1, Business Basic, Business Standard 및 Business Premium
- Office 365 E5/G5/A5/E3/G3/A3/F3/E1/G1

다음 라이선스가 있는 사용자의 경우 지원되는 최소 보존 또는 삭제 기간은 30일입니다.

- Microsoft 365 F1/F3, Business Basic, Business Standard 및 Business Premium
- Office 365 E1/G1 및 F3

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 규정 준수 및 F5 보안 & 준수, Microsoft 365 정보 보호 및 거버넌스 E5/A5/G5 및 Office 365 E5 /A5는 보존 레이블 또는 정책을 자동으로 적용하고, 기본 보존 레이블 또는 정책을 적용하고, 사용자 지정 이벤트에 따라 보존 레이블의 보존 기간을 시작하고, 레이블의 보존 기간이 끝나면 수동 처리 검토를 트리거하고, 네이티브 데이터 커넥터를 통해 타사 데이터를 가져오고, 파일 레코드를 선언할 수 있는 권한을 사용자에게 제공합니다.  레이블이 있는 콘텐츠 검색 및 레이블 지정 활동 모니터링

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 규정 준수 및 F5 보안 & 규정 준수, Microsoft 365 E5/A5/G5 정보 보호 및 거버넌스에서는 학습 가능한 분류자를 기반으로 보존 레이블을 자동으로 적용하는 이점을 사용자에게 제공할 수 있는 권한을 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 정보 거버넌스 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. 사용이 허가된 사용자에 대한 자동레이블 및 정책을 적용하기 위해 정보 거버넌스를 구성하는 데 대한 자세한 내용은 microsoft [Information Governance in Microsoft 365](/microsoft-365/compliance/manage-information-governance).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

특정 위치(팀 사이트, 그룹 사이트 등)의 사용이 허가된 사용자에게 정보 거버넌스 기능을 적용할 수 있습니다. 사용이 허가된 사용자에 대한 자동레이블 및 정책을 적용하기 위해 정보 거버넌스를 구성하는 데 대한 자세한 내용은 microsoft [Information Governance in Microsoft 365](/microsoft-365/compliance/manage-information-governance).

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

Microsoft 365 규정 준수 센터 정책을 만들 때 사용자 및 그룹 선택 페이지에서 사용자 또는 그룹 선택  을 선택하여 사용이 허가된 사용자  만 선택하거나 모든 사용자에게 라이선스가 부여된 경우 모든 사용자 및 메일 사용 가능 그룹 확인란을 선택할 수 있습니다. 자세한 내용은 내부자 위험 관리 [시작을 참조하세요](/microsoft-365/compliance/insider-risk-management-configure).

## <a name="microsoft-defender-for-identity"></a>Microsoft Defender for Identity

Id용 Microsoft Defender(이전의 Azure Advanced Threat Protection)는 여러 유형의 고급 대상 사이버 공격 및 내부자 위협으로부터 엔터프라이즈 하이브리드 환경을 보호하는 데 도움이 되는 클라우드 서비스입니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

SecOp 분석가 및 보안 전문가는 ID에 대한 Microsoft Defender의 기능을 통해 고급 위협, 손상된 ID 및 악의적인 내부자 작업을 감지하고 조사할 수 있습니다. 최종 사용자는 Microsoft Defender에서 ID를 모니터링하여 데이터를 모니터링할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 보안, Microsoft F5 보안 & 규정 준수 및 사용자를 위한 Microsoft Defender for Users는 ID에 대한 Microsoft Defender의 혜택을 받을 수 있는 권한을 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 Id에 대한 Microsoft Defender 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. Azure ATP 구성에 대한 자세한 내용은 [Create your Microsoft Defender for Identity instance를 참조하세요](/defender-for-identity/install-step1).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

Microsoft Defender for Identity Services는 현재 특정 사용자로 기능을 제한할 수 없습니다. 혜택을 제공하려는 모든 사용자에게 라이선스를 부여해야 합니다.

## <a name="microsoft-defender-for-office-365"></a>Office 365용 Microsoft Defender

Microsoft Defender for Office 365(이전의 Advanced Threat Protection Office 365)는 피싱 및 제로 데이 맬웨어와 같은 정교한 공격으로부터 조직을 보호하는 데 도움이 됩니다. 또한 Microsoft Defender for Office 365 광범위한 데이터의 신호와 상호 관련하여 잠재적인 위협을 해결 하는 방법에 대한 권장 사항을 식별, 우선 순위 지정 및 제공하는 데 도움이 되는 실행 가능한 인사이트를 제공합니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

Microsoft Defender for Office 365 피싱 및 제로 데이 맬웨어와 같은 정교한 공격으로부터 사용자를 보호합니다. 계획 1 및 계획 2에 제공된 전체 서비스 목록은 Microsoft [Defender for Office 365](/microsoft-365/security/office-365-security/office-365-atp).

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까? 

Microsoft Defender for Office 365 요금제 1 및 2, Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/F5 보안, Microsoft 365 F5 보안 & 규정 준수 및 Microsoft 365 Business Premium Microsoft Defender를 통해 혜택을 받을 수 있는 권한을 사용자에게 Office 365.

이 빠른 참조는 각 Microsoft Defender 구독에 제공된 기능을 Office 365 도움이 됩니다. 이 빠른 참조가 EOP 기능에 대한 지식과 결합될 경우, 비즈니스 의사 결정자가 자신의 요구에 가장 적합한 Office 365용 Microsoft Defender를 결정하는 데 도움이 될 수 있습니다.

#### <a name="microsoft-defender-for-office-365-plan-1-vs-plan-2-cheat-sheet"></a>Microsoft Defender for Office 365 요금제 1과 계획 2 치트시트 비교

| Office 365용 Defender 플랜 1 | Office 365용 Defender 플랜 2 |
|---------|---------|
| 구성, 보호 및 검색 기능: <ul><li> 안전한 첨부 파일 </li><li> 안전한 링크 </li><li> SharePoint, OneDrive 및 Microsoft Teams를 위한 안전한 첨부 파일 </li><li> Office 365용 Defender의 피싱 방지 보호 기능 </li><li> 실시간 탐지 </li></ul> | Office 365용 Defender 플랜 1 기능 </br> --- 추가 --- </br> 자동화, 조사, 수정 및 교육 기능: <ul><li> 위협 추적기 </li><li> 위협 탐색기 </li><li> 자동화된 조사 및 응답 </li><li> 공격 시뮬레이션 교육 </li></ul> |

자세한 내용은 microsoft [Defender for Office 365 및 Office 365 보안 - Exchange Online Protection 로 Office 365 | Microsoft Docs](/microsoft-365/security/office-365-security/overview).

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 microsoft Defender for Office 365 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. 라이선스가 있는 사용자에 대해 Microsoft Defender를 구성하는 Office 365 내용은 Microsoft [Defender for Office 365](/microsoft-365/security/office-365-security/office-365-atp).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

Microsoft Defender에서 Office 365 범위 지정을 금고 첨부 파일 배포 금고 따라야 합니다.

- 라이선스가 있는 사용자에 대해 금고 링크를 구성하는 자세한 내용은 Microsoft [Defender에서 금고 링크를 Office 365](/microsoft-365/security/office-365-security/atp-safe-links).

- 라이선스가 있는 사용자에 대해 금고 첨부 파일을 구성하는 금고 [Microsoft Defender](/microsoft-365/security/office-365-security/atp-safe-attachments)의 첨부 파일을 Office 365.

## <a name="microsoft-defender-for-cloud-apps"></a>Microsoft Defender for Cloud Apps

클라우드 앱용 Microsoft Defender는 고객에게 핵심 기능을 구현하고 여러 유형의 배포를 지원하는 방법에 대한 유연성을 제공하는 CASB(클라우드 액세스 보안 브로커) 솔루션입니다. 클라우드 앱용 Microsoft Defender는 사용자 기반 구독 서비스입니다. 각 라이선스는 사용자별, 월별 라이선스로, 아래 나열된 독립 실행형 제품 또는 여러 라이선스 계획의 일부로 라이선스가 부여될 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

클라우드 앱용 Microsoft Defender는 독립 실행형 라이선스로 사용할 수 있으며 다음 계획의 일부로도 사용할 수 있습니다.

- Enterprise Mobility + Security E5
- Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 보안
- Microsoft 365 E5/A5/G5/F5 규정 준수
- Microsoft 365 F5 보안 &amp; 규정 준수
- Microsoft 365 보호 및 거버넌스

Azure AD P1/P2는 사용자가 클라우드 앱용 Defender의 일부로 포함된 검색 기능을 사용할 수 있는 권한을 제공합니다.

Cloud Apps용 Defender의 조건부 액세스 앱 제어 기능을 활용하려면 사용자에게 Enterprise Mobility + Security F1/F1/F3/E3/A3/G3, Enterprise Mobility + Security E5에 포함된 Azure Active Directory P1에 대한 라이선스도 있어야 합니다. Microsoft 365 E3/A3/G3, Microsoft 365 E5/A5/G5 및 Microsoft 365 E5/A5/G5/F5 보안 및 Microsoft 365 F5 &amp; 보안 규정 준수.

자동 클라이언트 쪽 레이블 지정을 사용하려면 사용자에게 Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 규정 준수, Microsoft 365 F5 보안에 포함된 Azure Information Protection P2에 대한 라이선스가 있어야 합니다. &amp; 규정 준수 및 Microsoft 365 보호 및 거버넌스를 준수합니다.

> [!NOTE]
> 자동 서버 쪽 레이블 지정을 사용하려면 Office 365- Premium(또는)에 대한`MIP_S_CLP2`  정보 보호가 필요합니다 `efb0351d-3b08-4503-993d-383af8de41e3`. 참조는 라이선스에  [대한Product 이름 및 서비스 계획 식별자를 참조하세요](/azure/active-directory/enterprise-users/licensing-service-plan-reference).

자세한 내용은 여기를 참조 [하세요](https://aka.ms/defender-for-cloud-apps).

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 클라우드 앱용 Microsoft Defender 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다.

라이선스가 있는 사용자를 위해 Cloud Apps용 Defender 정책을 구성하는 자세한 내용은 여기를 참조 [하세요](https://aka.ms/defender-for-cloud-apps).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

관리자는 서비스에서 사용할 수 있는 범위가 지정한 배포 기능을 사용하여 라이선스가 있는 사용자로 Microsoft Defender for Cloud Apps 배포 범위를 지정합니다. 자세한 내용은 [Scoped deployment를 참조하십시오](/cloud-app-security/scoped-deployment).

### <a name="what-is-the-app-governance-add-on-feature-for-microsoft-defender-for-cloud-apps"></a>클라우드 앱용 Microsoft Defender의 앱 거버넌스 추가 기능이란?

앱 거버넌스는 클라우드 앱용 Microsoft Defender의 추가 기능 기능으로 사용할 수 있는 보안 및 정책 관리 기능입니다.

앱 거버넌스를 통해 고객은 Microsoft 365 플랫폼에서 타사 및 사내 개발 앱을 모니터링하고 제어하여 위험하거나 승인되지 않은 액세스, 권리 또는 권한 있는 데이터 사용을 식별, 경고 및 방지할 수 있습니다. 앱 거버넌스는 Microsoft Microsoft 365 API를 통해 데이터에 액세스하는 OAuth 사용 Graph [사용하도록 디자인되었습니다](/graph/use-the-api).

앱 거버넌스를 통해 고객에게 다음과 같은 기능 이점이 있습니다.

- **심도** 깊은 가시성 및 인사이트: [Microsoft 365](/microsoft-365/compliance/app-governance-visibility-insights-overview) 데이터에 액세스하는 앱에 대한 심층적인 가시성과 앱이 환경에서 구성 및 동작하는 방법에 대한 실행 가능한 인사이트를 얻습니다.
- **정책 기반** [](/microsoft-365/compliance/app-governance-app-policies-overview) 거버넌스: 데이터 액세스에 대한 조직의 보안 및 규정 준수 자세에 따라 데이터, 사용자 및 기타 앱에 대한 적절한 앱 동작을 사전 예방적으로 정의하고 적용합니다.
- **포괄적:** [감지](/microsoft-365/compliance/app-governance-detect-remediate-overview) 및 수정: 기계 학습 모델을 통해 악성 앱 동작을 감지하고, 자동화된 문제를 해결하고, 수동 수정 작업을 처리합니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

앱 거버넌스를 다음을 통해 조직에 추가 기능으로 사용할 수 있습니다.

- 클라우드 앱용 Microsoft Defender(독립 실행형)
- Enterprise Mobility + Security E5/A5
- Microsoft 365 E5/A5
- Microsoft 365 보안
- Microsoft 365 준수 E5/A5
- Microsoft 365 E5/A5 Information Protection 및 거버넌스
- Microsoft 365 F5 보안 추가 기능
- Microsoft 365 F5 규정 준수 추가 기능
- Microsoft 365 F5 보안 + 규정 준수 추가 기능

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 앱 거버넌스는 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. 자세한 내용은 [앱 거버](/microsoft-365/compliance/app-governance-manage-app-governance)넌스를 Microsoft 365 시작 [참조하세요](/microsoft-365/compliance/app-governance-get-started).

### <a name="is-it-a-requirement-for-the-apps-in-the-tenant-to-be-registered-with-azure-active-director-to-be-viewable-by-app-governance"></a>테넌트의 앱을 앱 거버넌스에서 볼 수 있는 Azure Active Director에 등록해야 하는 요구 사항인가요?

예. 앱은 Azure AD에 등록해야 합니다. OAuth 2.0을 사용하도록 설정해야 합니다. 다른 ID 관리 시스템은 현재 지원되지 않습니다. 앱 거버넌스 추가 기능 기능은 Microsoft Microsoft 365 API를 사용하는 OAuth 앱의 Graph 모니터링합니다. 모든 Microsoft 365 E5/A5 라이선스에는 Azure AD가 있습니다.

## <a name="microsoft-defender-for-endpoint"></a>엔드포인트용 Microsoft Defender 

끝점용 Microsoft Defender는 다음을 포함하는 끝점 보안 솔루션입니다.

- 위험 기반 취약성 관리 및 평가
- 공격 표면 감소 기능
- 동작 기반 및 클라우드 기반 차세대 보호
- 끝점 검색 및 응답(EDR)
- 자동 조사 및 수정
- 관리되는 헌팅 서비스

자세한 내용은  [Endpoint용Microsoft Defender를 참조하세요](/microsoft-365/security/defender-endpoint/microsoft-defender-endpoint).

### <a name="which-licenses-provide-the-rights-for-users-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

**끝점 계획 1(P1)에 대한 Microsoft Defender**

Microsoft Defender for Endpoint P1은 상업 및 교육 고객을 위한 독립 실행형 사용자 구독 라이선스로 사용할 수 있습니다. 또한 이 패키지는 Microsoft 365 E3/A3의 일부로 포함되어 있습니다.

**Microsoft Defender for Endpoint Plan 2(P2)**

이전에 Endpoint용 Microsoft Defender로 불리던 Endpoint P2용 Microsoft Defender는 독립 실행형 라이선스로 사용할 수 있으며 다음 계획의 일부로 사용할 수 있습니다.

- Windows 11 Enterprise E5/A5
- Windows 10 Enterprise E5/A5
- Microsoft 365 E5/A5/G5(Windows 10 또는 E5 Windows 11 Enterprise 포함)
- Microsoft 365 E5/A5/G5/F5 보안
- Microsoft 365 F5 보안 &amp; 규정 준수

**Endpoint Server용 Microsoft Defender**

Endpoint Server용 Microsoft Defender는 최소 50개 이상의 끝점용 Microsoft Defender 라이선스를 결합한 고객을 위한 추가 기능입니다.

끝점용 Microsoft Defender의 사용 약관은 제품 약관 [을 참조합니다](https://www.microsoft.com/Licensing/product-licensing/products).

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

**엔드포인트용 Microsoft Defender 플랜 1**

Microsoft Defender for Endpoint P1은 차세대 맬웨어 방지, 공격 표면 감소 규칙, 장치 제어, 끝점 방화벽, 네트워크 보호 등의 핵심 끝점 보호 기능을 제공합니다. 자세한 내용은 [Microsoft Defender for Endpoint Plan 1 및 Plan 2를 참조합니다](/microsoft-365/security/defender-endpoint/defender-endpoint-plan-1-2).

**엔드포인트용 Microsoft Defender 플랜 2**

Microsoft Defender for Endpoint P2는 끝점 감지 및 대응, 자동화된 조사 및 수정, 위협 및 취약성 관리 위협 인텔리전스, 샌드박스 및 Microsoft 위협 전문가와 같은 추가 기능이 있는 끝점 P1용 Microsoft Defender의 모든 기능을 비롯한 포괄적인 끝점 보호 기능을 제공합니다. 자세한 내용은 끝점용 [Microsoft Defender 설명서를 참조하세요](/microsoft-365/security/defender-endpoint).

**Endpoint Server용 Microsoft Defender**

서버용 Microsoft Defender는 Windows P2용 Microsoft Defender와 같은 기능을 통해 서버 및 Linux 서버를 보호합니다.  

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 Microsoft Defender for Endpoint 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. 배포에 대한 자세한 내용은 [Deployment 단계를 참조하세요](/microsoft-365/security/defender-endpoint/deployment-phases).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

끝점용 Microsoft Defender 관리자는 RBAC(역할 기반 액세스 제어)를 사용하여 보안 운영 팀 내에서 역할 및 그룹을 만들어 해당 역할에 적절한 액세스 권한을 부여할 수 Microsoft Defender 보안 센터. 자세한 내용은 역할 기반 액세스 제어를  [사용하여 포털 액세스 관리 기능을 참조하세요](/microsoft-365/security/defender-endpoint/rbac).

## <a name="microsoft-graph-apis-for-teams-data-loss-prevention-dlp-and-for-teams-export"></a>Microsoft Graph DLP(Teams 손실 방지) 및 데이터 내보내기용 TEAMS API

이러한 API를 통해 개발자는 거의 실시간으로 메시지를 듣거나 1:1/group 채팅 또는 Teams 채널에서 팀 메시지를 내보낼 Microsoft Teams 보안 및 규정 준수 앱을 빌드할 수 있습니다. 이러한 API를 통해 고객과 ISV 모두에 대해 DLP 및 기타 정보 보호 및 거버넌스 시나리오를 사용할 수 있습니다. 또한 Microsoft Graph 패치 API를 사용하면 메시지에 DLP Teams 적용할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

[DLP(데이터 손실 방지)](/microsoft-365/compliance/dlp-microsoft-teams) 기능은 특히 조직이 원격 작업으로 Microsoft Teams 조직에서 널리 사용됩니다. 조직에 DLP가 있는 경우 이제 사용자가 특정 채널 또는 채팅 세션에서 중요한 정보를 공유하지 못하게 하는 Microsoft Teams 수 있습니다.

정보 보호 및 거버넌스 기능은 특히 조직이 원격 작업으로 Microsoft Teams 조직에서 널리 사용됩니다. 내보내[기 Teams](/microsoftteams/export-teams-content) 사용하여 타사 eDiscovery 또는 준수 보관 응용 프로그램으로 데이터를 내보내 규정 준수 사례를 충족할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

- Microsoft 365 E5/A5
- Microsoft 365 E5/A5 규정 준수
- E5/A5 보안 Microsoft 365
- Microsoft 365 E5/A5 Information Protection 및 거버넌스

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

API 액세스는 테넌트 수준에서 구성됩니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

Microsoft Graph DLP Teams 및 Teams 내보내기용 API는 테넌트 수준 값을 제공합니다. 이 서비스를 이용하려는 모든 사용자는 사용이 허가되어야 합니다. 추가 가치로, 라이선스가 있는 사용자당 시드 용량, 월별 계산 및 테넌트 수준에서 집계되는 시드 용량을 추가합니다. 시드된 용량을 초과하는 사용량의 경우 앱 소유자에게 API 사용에 대한 대금이 청구됩니다.

시드된 용량 및 사용 요금에 대한 자세한 내용은 채팅 [메시지 액세스에 Graph 요구 사항을 참조하세요](/graph/teams-licenses).

## <a name="office-365-cloud-app-security"></a>Office 365 Cloud App Security

Office 365 Cloud App Security(OCAS)는 클라우드 앱용 Microsoft Defender의 하위 집합으로, 타사 클라우드 앱 및 IaaS 서비스에 대한 추가 Office 365 없는 기능으로 제한됩니다.

OCAS는 조직이 생산성 클라우드 앱 및 서비스를 볼 수 있도록 하여 사이버 위협을 식별하고 퇴치하기 위한 정교한 분석을 제공하며,&mdash; 데이터가 이동하는 방법을 제어할 수 Office 365.

기능을 비교하기 위해 [클라우드 앱용 Microsoft Defender](/cloud-app-security/editions-cloud-app-security-o365)와 클라우드 앱 간의 차이점을 Office 365 Cloud App Security.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

OCAS는 섀도 IT를 검색하고, 여러 Office 365 보호를 제공하며, 데이터에 액세스할 수 있는 권한이 있는 앱을 제어할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Office 365 E5/A3/A5/G5는 사용자가 OCAS를 혜택을 받을 수 있는 권한을 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 OCAS 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다.

서비스 구성에 대한 자세한 내용은 [Cloud Apps용 Defender에 대한 기본 설정을 참조하세요](/cloud-app-security/general-setup).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

관리자는 OCAS 배포 범위를 지정하여 특정 앱에 액세스하는 방법을 적용하고 관리자가 모니터링하는 사용자 그룹을 제한할 Office 365 Cloud App Security. 자세한 내용은 [범위가 지정한 배포를 참조하세요](/cloud-app-security/scoped-deployment).

## <a name="office-365-customer-lockbox"></a>Office 365 고객 Lockbox

고객 Lockbox는 고객에게 서비스 작업에 대한 명시적 액세스 권한 부여를 제공하는 기능을 제공하여 추가적인 제어 계층을 제공합니다. 고객 Lockbox는 명시적 데이터 액세스 권한 부여를 위한 절차가 준비 중이기 때문에 조직이 HIPAA 및 FedRAMP와 같은 특정 규정 준수 의무를 이행하는 데에도 도움이 될 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

Customer Lockbox는 Microsoft의 어느 누구도 고객의 명시적 승인 없이도 고객 콘텐츠에 액세스하여 서비스 작업을 수행할 수 있도록 합니다. Customer Lockbox는 고객에게 콘텐츠에 액세스하기 위한 요청에 대한 승인 워크플로로 고객을 유치합니다. 경우에 따라 Microsoft 엔지니어가 지원 프로세스 중에 관련되어 고객이 보고한 문제를 해결합니다. 대부분의 경우 문제는 Microsoft가 서비스에 대해 준비한 광범위한 원격 분석 및 디버깅 도구를 통해 해결됩니다. 그러나 Microsoft 엔지니어가 고객 콘텐츠에 액세스하여 근본 원인을 파악하고 문제를 해결해야 하는 경우도 있을 수 있습니다. 고객 Lockbox를 사용하려면 엔지니어가 승인 워크플로의 마지막 단계로 고객의 액세스를 요청해야 합니다. 이를 통해 조직은 Microsoft 엔지니어가 조직의 최종 사용자 데이터에 액세스할 수 있는지 여부를 직접 제어할 수 있도록 이러한 요청을 승인하거나 거부할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 규정 준수 및 F5 보안 & 규정 준수 및 Microsoft 365 E5/A5/G5 내부자 위험 관리는 사용자가 고객 Lockbox를 혜택을 받을 수 있는 권한을 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

관리자는 사용자 계정에서 고객 Lockbox를 Microsoft 365 관리 센터. 자세한 내용은 2013[의 고객 Lockbox를 Office 365](/microsoft-365/compliance/customer-lockbox-requests). Customer Lockbox가 켜져 있는 경우 Microsoft는 콘텐츠에 액세스하기 전에 조직의 승인을 얻어야 합니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

현재 고객 Lockbox 서비스는 특정 사용자로 제한될 수 없습니다. 테넌트 서비스가 현재 특정 사용자로 혜택을 제한할 수 없는 경우 라이선스가 있는 사용자로 서비스 혜택을 제한하기 위해 노력해야 합니다. 이렇게 하면 대상 지정 기능을 사용할 수 있는 경우 잠재적인 서비스 중단을 방지할 수 있습니다.

## <a name="microsoft-priva"></a>Microsoft Priva

[Microsoft Priva](https://aka.ms/privacymanagementdocs) 는 정보 근로자가 현명한 데이터 처리 결정을 내릴 수 있도록 지원하고 주체 요청을 대규모로 자동화 및 관리하여 데이터 수리, 데이터 전송 및 데이터 공유와 같은 개인 정보 보호 위험을 사전 예방적으로 식별하고 보호하여 회사가 개인 데이터를 보호하고 개인 정보 보호를 강화하는 데 도움이 됩니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Priva는 Office 365 A1/E1/A3/E3/A5/E5 및 Microsoft 365 A3/E3/A5/E5 구독이 있는 조직에 추가하여 사용할 수 있습니다. 

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

사용자는 조직이 자신의 환경에서 개인 데이터를 파악하고, 개인 정보 위험을 능동적으로 식별 및 보호하고, 주체 권한 요청(일반적으로 '데이터 주체 요청')을 대규모로 관리할 수 있는 기능을 통해 혜택을 얻습니다.

### <a name="how-can-customers-access-the-service"></a>고객이 서비스에 액세스하는 방법

Priva 솔루션은 기본 제공 Microsoft 365 규정 준수 센터 테 [](https://compliance.microsoft.com/homepage) 넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. 서비스로 혜택을 받을 수 있도록 보호하려는 모든 사용자에 대해 라이선스를 취득하는 것이 좋습니다.

고객은 조직의 필요에 따라 다음 라이선스를 구입할 수 있습니다.

**개인 정보 관리 – 위험은 Priva 개인 정보 보호 위험 관리의 라이선스 이름입니다.** 이 서비스를 통해 조직은 다음을 할 수 있습니다.

- Microsoft 365 환경의 개인 데이터(Microsoft Exchange Online, SharePoint, 비즈니스용 OneDrive 및 Teams)에 대한 가시성을 확보합니다.
- 데이터 최소화, 데이터 과부하, 데이터 전송을 비롯한 기본 개인 정보 취급 방침 템플릿을 활용하거나 고유한 조직 요구에 맞게 사용자 지정합니다.
- 개인 정보 위험을 완화하기 위해 권장되는 수정 제어를 수신합니다.
- 생산성 제품군 내에서 정보 근로자의 참여를 유도하고 행동 변경을 주도합니다.

**개인 정보 관리 – 주체 권한 요청은 Priva 주체 권한 요청의 라이선스 이름입니다.** 이 서비스를 통해 조직은 다음을 할 수 있습니다.

- 주체 권한 요청에 대한 응답을 자동화하고 대규모로 관리합니다.
- 기존 비즈니스 Power Automate Microsoft Power Automate 템플릿을 사용합니다.
- API에 프로그래밍된 액세스를 활용합니다.
- Microsoft Teams 통합을 통해 다른 이해 관계자와 안전하게 공동 작업을 할 수 있습니다(사용하려면 적절한 라이선스가 Microsoft Teams).</br>

고객은 1,10 또는 100 블록으로 Priva Subject Rights Requests를 구매할 수 있습니다.

개인 정보 보호 위험 관리 및 Priva 주체 권한 요청은 서로 독립적으로 구매할 수 있습니다.

개인 [정보 보호](https://www.microsoft.com/licensing/terms/productoffering/Microsoft365/EAEAS) 위험 관리 및 Priva 주체 권리 요청을 획득하는 데 필요한 라이선스 선행 조건에 대한 제품 약관을 참조합니다.

## <a name="privileged-access-management-in-office-365"></a>Office 365의 권한 있는 액세스 관리

[PAM(](/microsoft-365/compliance/privileged-access-management-configuration)권한 있는 액세스 관리)은 팜의 권한 있는 관리 작업에 대한 세부적인 액세스 제어를 Office 365. PAM을 사용하도록 설정한 후 권한이 상승된 작업을 완료하려면 사용자는 범위가 넓고 시간이 제한적인 승인 워크플로를 통해 적시 액세스를 요청해야 합니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

PAM을 사용하도록 설정하면 조직이 제로 스탬드 권한으로 작동할 수 있습니다. 사용자는 데이터에 대한 불안정한 액세스를 제공하는 상시 관리 액세스로 부터의 취약성에 대한 추가 방어 계층을 통해 혜택을 받을 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까? 

Office 365 E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5/F5 규정 준수 및 F5 보안 & 규정 준수 및 Microsoft 365 E5/A5 정보 보호 및 거버넌스를 통해 사용자가 PAM을 혜택을 받을 수 있는 권한을 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 PAM 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. PAM 정책 구성에 대한 자세한 내용은 권한 있는 액세스 관리 시작 [을 참조하세요](/microsoft-365/compliance/privileged-access-management-configuration).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

고객은 승인자 그룹 및 액세스 정책을 통해 사용자 기준으로 PAM을 관리할 수 있으며, 이 정책은 라이선스가 있는 사용자에게 적용할 수 있습니다. 자세한 내용은 Access[의 권한 있는 액세스 관리를 Office 365](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751).

## <a name="records-management"></a>레코드 관리

레코드 관리는 조직이 타사 및 타사 데이터에서 검색, 분류, 레이블 지정, 보존 및 방어할 수 있는 삭제 기능을 Microsoft 365 및 규정 기록 보존 의무를 충족하는 데 도움이 됩니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 규정 준수 및 F5 보안 & 준수, Microsoft 365 정보 보호 및 거버넌스 E5/A5/G5 및 Office 365 E5 /A5/G5는 레코드 또는 규정 레코드로 항목을 선언하고, 보존 또는 레코드 레이블을 자동으로 적용하고, 처리 검토 프로세스를 실행하는(학습 가능한 분류자를 기반으로 보존 레이블 자동 적용 제외)를 포함하여 사용자가 레코드 관리를 통해 혜택을 받을 수 있는 권한을 제공합니다.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 규정 준수 및 F5 보안 & 규정 준수 및 Microsoft 365 정보 보호 및 거버넌스를 통해 학습 가능한 분류자를 기반으로 보존 또는 기록 레이블을 자동으로 적용하여 혜택을 받을 수 있는 권한을 사용자에게 제공합니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

사용자는 콘텐츠를 레코드로 선언하고 정책 정의 및 선언을 통해 방어할 수 있는 폐기로 전체 레코드 프로세스를 관리할 수 있습니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 레코드 관리 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. 사용이 허가된 사용자에 대해 적용할 레코드 관리를 구성하는 데 대한 자세한 내용은 [Learn about records Management in Microsoft 365](/microsoft-365/compliance/records-management).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 사용이 허가된 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법

레코드 관리 기능은 특정 위치(팀 사이트, 그룹 사이트 등)의 사용이 허가된 사용자에게 적용할 수 있습니다. 사용이 허가된 사용자에 대해 적용할 레코드 관리를 구성하는 데 대한 자세한 내용은 [Learn about records Management in Microsoft 365](/microsoft-365/compliance/records-management).
