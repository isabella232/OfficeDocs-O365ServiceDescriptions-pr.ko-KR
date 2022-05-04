---
title: 보안 & 규정 준수에 대한 Microsoft 365 지침
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
description: 이 문서에서는 허가되지 않은 액세스로 인한 잠재적인 서비스 중단을 방지하기 위해 Microsoft 365 규정 준수에 대한 지침을 제공합니다.
ms.openlocfilehash: ce6e4ee2176d31034111f53b3d4046d8995cc0c1
ms.sourcegitcommit: c2d2064d8fbebbe9843a4e824860e214b0b54c58
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/04/2022
ms.locfileid: "65187479"
---
# <a name="microsoft-365-guidance-for-security-amp-compliance"></a>보안 &amp; 규정 준수에 대한 Microsoft 365 지침

이 문서의 목적을 위해 테넌트 수준 서비스는 테넌트 내 모든 사용자(독립 실행형 라이선스 및/또는 Microsoft 365 또는 Office 365 계획의 일부로)에 대해 부분적으로 또는 전체적으로 활성화되는 온라인 서비스입니다. 고객이 온라인 서비스 사용하려면 적절한 구독 라이선스가 필요합니다. Microsoft 365 규정 준수 기능을 활용하도록 사용자에게 라이선스를 부여하기 위한 옵션을 보려면  [Microsoft 365 비교 테이블을](https://go.microsoft.com/fwlink/?linkid=2139145) 다운로드합니다.

일부 테넌트 서비스는 현재 특정 사용자에 대한 혜택을 제한할 수 없습니다. 서비스 혜택을 사용이 허가된 사용자로 제한하기 위해 노력해야 합니다. Microsoft 라이선싱 프로그램을 통해 획득한 Microsoft 제품 및 Professional 서비스의 사용에 관한 사용 약관을 검토하려면  [TheProduct 약관](https://www.microsoft.com/Licensing/product-licensing/products)을 참조하세요.

## <a name="microsoft-purview-audit-premium"></a>Microsoft Purview 감사(프리미엄)

감사(Premium)(이전의 Microsoft 365 고급 감사)는 사용자 및 관리자 활동에 대한 감사 로그의 1년 보존을 제공하고 다른 Microsoft 365 서비스에 대한 감사 로그 보존을 관리하는 사용자 지정 감사 로그 보존 정책을 만드는 기능을 제공합니다. 또한 Office 365 관리 활동 API에 대한 조사 및 높은 대역폭 액세스를 위한 중요한 이벤트에 대한 액세스를 제공합니다. 자세한 내용은 [감사(Premium)](/microsoft-365/compliance/advanced-audit)를 참조하세요.

추가 기능 SKU를 사용하여 보존 기간 10년을 사용하도록 설정할 수도 있습니다.

### <a name="which-users-benefit-from-the-service"></a>서비스의 혜택을 받는 사용자는 무엇인가요?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 준수, Microsoft 365 F5 보안 & 규정 준수 및 Microsoft 365 E5/A5/G5 eDiscovery 및 감사의 사용이 허가된 사용자는 감사의 혜택을 누릴 수 있습니다( Premium).

감사(Premium) 및 10년 감사 로그 보존 추가 기능이 있는 라이선스 사용자는 10년 감사 로그 보존의 혜택을 누릴 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 이 서비스를 통해 어떻게 혜택을 받을 수 있나요?

Microsoft 365 서비스의 사용자 활동과 관련된 감사 레코드는 최대 1년 동안 보존할 수 있으므로 사용자는 감사(Premium)의 이점을 누릴 수 있습니다. 또한 사용자의 사서함에 있는 항목에 액세스하거나 읽는 경우와 같이 고가의 감사 이벤트가 기록됩니다. 자세한 내용은 [감사(Premium)](/microsoft-365/compliance/advanced-audit)를 참조하세요.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되는가?

기본적으로 감사(Premium)는 서비스의 혜택을 받는 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정되며, Azure Active Directory, Exchange 및 SharePoint 활동(적절한 라이선스를 가진 사용자가 수행)에 대한 감사 로그의 1년 보존을 자동으로 제공합니다. 또한 조직에서는 감사 로그 보존 정책을 사용하여 다른 Microsoft 365 서비스의 활동에 의해 생성된 감사 레코드의 보존 기간을 관리할 수 있습니다. 10년 감사 로그 보존 기능도 동일한 보존 정책을 사용하여 사용하도록 설정됩니다. 자세한 내용은 [감사 로그 보존 정책 관리](/microsoft-365/compliance/audit-log-retention-policies)를 참조하십시오.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스가 부여된 테넌트 사용자에게만 서비스를 적용하려면 어떻게 해야 할까요?

감사 로그의 1년 보존 및 중요한 이벤트의 감사는 적절한 라이선스가 있는 사용자에게만 적용됩니다. 또한 관리자는 감사 로그 보존 정책을 사용하여 특정 사용자의 감사 로그에 대해 더 짧은 보존 기간을 지정할 수 있습니다.

감사 로그의 10년 보존 기간은 적절한 추가 기능 라이선스가 있는 사용자에게만 적용됩니다. 추가 기능 SKU는 2021년 초부터 필요합니다.

## <a name="azure-active-directory-identity-governance"></a>Azure Active Directory ID 거버넌스

Azure Active Directory ID 거버넌스를 사용하면 조직의 보안 및 직원 생산성에 대한 요구 사항과 올바른 프로세스 및 가시성의 균형을 맞출 수 있습니다. 권한 관리, 액세스 검토, 권한 있는 ID 관리 및 사용 약관 정책을 사용하여 적절한 사용자가 올바른 리소스에 대한 올바른 액세스 권한을 갖도록 합니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 이 서비스를 통해 어떻게 혜택을 받을 수 있나요?

Azure Active Directory ID 거버넌스는 하나의 액세스 패키지에서 앱, 그룹 및 Microsoft Teams 대한 액세스를 더 쉽게 요청하도록 하여 사용자의 생산성을 높입니다. 사용자는 관리자를 포함하지 않고 승인자로 구성할 수도 있습니다. 액세스 검토를 위해 사용자는 스마트 권장 사항이 있는 그룹의 멤버 자격을 검토하여 정기적으로 작업을 수행할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스의 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇인가요?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5/F5 보안 및 F5 보안 & 규정 준수 및 Azure Active Directory Premium 플랜 2는 사용자가 혜택을 받을 수 있는 권한을 제공합니다. id 거버넌스를 Azure Active Directory.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되는가?

Azure AD ID 거버넌스 기능은 테넌트 수준에서 사용하도록 설정되지만 사용자별로 구현됩니다. Azure AD ID 거버넌스에 대한 자세한 내용은 [Azure AD ID 거버넌스란?을](/azure/active-directory/governance/identity-governance-overview) 참조하세요.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스가 부여된 테넌트 사용자에게만 서비스를 적용하려면 어떻게 해야 할까요?

관리자는 사용이 허가된 사용자에 대해서만 액세스 패키지, 액세스 검토 또는 권한 있는 ID 관리를 할당하여 Azure AD ID 거버넌스의 범위를 지정할 수 있습니다. Azure AD ID 거버넌스 배포의 범위를 지정하는 방법에 대한 지침은 다음을 참조하세요.

- [Azure AD 권한 관리 라이선스 요구 사항](/azure/active-directory/governance/entitlement-management-overview#license-requirements)
- [Azure AD 액세스 검토 라이선스 요구 사항](/azure/active-directory/governance/access-reviews-overview#license-requirements)
- [Privileged Identity Management 사용하기 위한 라이선스 요구 사항](/azure/active-directory/privileged-identity-management/subscription-requirements)

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory ID 보호

Azure Active Directory ID 보호 Azure Active Directory Premium P2는 조직의 ID에 영향을 주는 잠재적 취약성을 감지하고, 조직의 ID와 관련된 검색된 의심스러운 작업에 대한 자동화된 응답을 구성하고, 의심스러운 인시던트 및 적절한 조치를 취하여 해결합니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 이 서비스를 통해 어떻게 혜택을 받을 수 있나요?

SecOps 분석가 및 보안 전문가는 기계 학습 알고리즘을 기반으로 플래그가 지정된 사용자 및 위험 이벤트에 대한 통합 보기를 갖는 이점을 누릴 수 있습니다. 최종 사용자는 위험 기반 조건부 액세스를 통해 제공되는 자동 보호와 취약성에 대한 조치를 통해 제공되는 향상된 보안을 활용할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스의 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇인가요?

- Azure Active Directory 플랜 1: Microsoft 365 E3/A3/G3/F1/F3, Enterprise Mobility & Security E3 및 Microsoft 365 Business Premium
- Azure Active Directory 계획 2: Microsoft 365 E5/A5/G5, Enterprise Mobility & Security E5, Microsoft 365 E5/F5 보안 및 Microsoft 365 F5 보안 & 규정 준수

사용 가능한 다양한 계획에 포함된 기능에 대한 자세한 내용은 [id 보호에 Azure Active Directory 항목을](https://www.microsoft.com/en-us/security/business/identity-access-management/azure-ad-pricing) 참조하세요.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되는가?

기본적으로 Azure AD ID 보호 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. Azure AD ID 보호에 대한 자세한 내용은 [ID 보호란?을](/azure/active-directory/identity-protection/overview-identity-protection) 참조하세요.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스가 부여된 테넌트 사용자에게만 서비스를 적용하려면 어떻게 해야 할까요?

관리자는 암호 재설정 수준을 정의하는 위험 정책을 할당하고 사용이 허가된 사용자에 대해서만 액세스를 허용하여 Azure AD ID 보호 범위를 지정할 수 있습니다. Azure AD ID 보호 배포의 범위를 지정하는 방법에 대한 지침은 [위험 정책을 구성하고 사용하도록 설정하는 방법을](/azure/active-directory/identity-protection/howto-sign-in-risk-policy) 참조하세요.

## <a name="microsoft-purview-communication-compliance"></a>Microsoft Purview 통신 규정 준수

커뮤니케이션 규정 준수(이전의 Microsoft 365 커뮤니케이션 규정 준수)는 조직에서 부적절한 메시지를 감지, 캡처 및 수정하는 데 도움을 줌으로써 통신 위험을 최소화하는 데 도움이 됩니다. 조직에서 내부 및 외부 전자 메일, Microsoft Teams 또는 타사 통신을 캡처하는 특정 정책을 정의할 수 있습니다. 검토자는 적절한 수정 작업을 수행하여 조직의 메시지 표준을 준수하는지 확인할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 이 서비스를 통해 어떻게 혜택을 받을 수 있나요?

규정 준수 전문가는 통신 규정 준수 정책에 의해 조직 통신을 모니터링함으로써 서비스의 이점을 누릴 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스의 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇인가요?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 준수, Microsoft 365 F5 보안 & 규정 준수 및 Microsoft 365 E5/A5/G5 참가자 위험 관리는 사용자가 통신의 혜택을 누릴 수 있는 권한을 제공합니다. 준수.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되는가?

관리자 및 규정 준수 전문가는 Microsoft Purview 규정 준수 포털에서 커뮤니케이션 규정 준수 정책을 만듭니다. 이러한 정책은 조직에서 검토할 수 있는 통신 및 사용자를 정의하고, 통신이 충족해야 하는 사용자 지정 조건을 정의하고, 검토를 수행할 사용자를 지정합니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스가 부여된 테넌트 사용자에게만 서비스를 적용하려면 어떻게 해야 할까요?

관리자는 커뮤니케이션 규정 준수 정책에 포함할 특정 사용자 또는 그룹을 선택합니다. 그룹을 선택할 때 통신 준수 정책에서 제외할 그룹의 특정 사용자를 선택할 수도 있습니다. 커뮤니케이션 규정 준수 정책에 대한 자세한 내용은 [Microsoft Purview Communication Compliance에 대한 시작](/microsoft-365/compliance/communication-compliance-configure) 참조하세요.

## <a name="microsoft-purview-compliance-manager"></a>Microsoft Purview 준수 관리자

[준수 관리자는](https://compliance.microsoft.com/compliancemanager) Microsoft Purview 규정 준수 포털의 기능으로, 조직의 규정 준수 요구 사항을 보다 쉽고 편리하게 관리할 수 있습니다. 준수 관리자는 데이터 보호 위험 상세 조사부터 제어 구현의 복잡성 관리, 규정 및 인증의 최신 정보 유지, 보고 및 감사까지, 여러분의 규정 준수를 향한 여정을 도와드릴 수 있습니다.

준수 관리자는 다음을 제공하여 규정 준수를 간소화하고 위험을 줄이는 데 도움이 됩니다.

- 공통 업계 및 지역 표준과 규정에 대한 사전 구축된 평가 또는 고유한 규정 준수 요구 사항을 충족하기 위한 사용자 지정 평가입니다.
- 단일 도구를 통해 위험 평가를 효율적으로 완료할 수 있는 워크플로 기능.
- 조직에 가장 관련성이 있는 표준 및 규정을 준수하는 데 도움이 되는 제안된 개선 조치에 대한 자세한 단계별 지침입니다. Microsoft에서 관리하는 작업의 경우 구현 세부 정보 및 감사 결과가 표시됩니다.
- 개선 작업을 완료하는 진행 상황을 측정하여 규정 준수 상태를 이해하는 데 도움이 되는 위험 기반 규정 준수 점수입니다.

### <a name="who-can-access-compliance-manager"></a>Who 준수 관리자에 액세스할 수 있나요?

준수 관리자는 Office 365 및 Microsoft 365 라이선스가 있는 조직과 미국 정부 커뮤니티 클라우드(GCC), GCC High 및 국방부(DoD) 고객에게 제공됩니다. 평가 가용성 및 관리 기능은 라이선스 계약에 따라 달라집니다.

### <a name="what-are-premium-assessments"></a>프리미엄 평가란?

Premium 평가는 준수 관리자 및 도움말에 대한 추가 기능 값입니다.

- 복잡한 규정 요구 사항을 특정 컨트롤로 변환
- 권장되는 개선 작업 제안
- 규정 준수에 대한 정량화 가능한 측정값 제공

Compliance Manager에는 고객이 광범위한 글로벌, 지역 및 산업 규정 및 표준을 준수하는지 평가하는 데 사용할 수 있는 300개 이상의 프리미엄 평가가 있습니다.

Microsoft Exchange Online 라이선스가 포함된 구독을 가진 고객은 준수 관리자 프리미엄 평가를 구매할 수 있습니다.

### <a name="which-premium-assessments-are-available"></a>어떤 프리미엄 평가를 사용할 수 있나요?

[프리미엄 평가 목록은](/microsoft-365/compliance/compliance-manager-templates-list#premium-templates) 다음과 같습니다.

### <a name="which-assessments-are-included-by-default-free-of-cost"></a>기본적으로 포함되는 평가는 무엇인가요(비용 부담)?

일부 평가는 준수 관리자 및 고객 라이선스 유형에 포함됩니다. 자세한 내용은 아래 표를 참조하세요.

| 라이선스 유형 | 평가 템플릿(기본적으로 포함) |
|:-----|:-----|
|<ul><li>Microsoft 365 또는 Office 365 A1/E1/F1/G1</li><li>Microsoft 365 또는 Office 365 A3/E3/F3/G3</li></ul>|<ul><li>데이터 보호 기준</li></ul>|
|<ul><li>Microsoft 365 또는 Office 365 A5/E5/G5</li><li>Microsoft 365 A5/E5/F5/G5 규정 준수</li><li>Microsoft 365 A5/E5/F5/G5 eDiscovery 및 감사</li><li>Microsoft 365 A5/E5/F5/G5 참가자 위험 관리</li><li>Microsoft 365 A5/E5/F5/G5 Information Protection 및 거버넌스</li></ul>|<ul><li>데이터 보호 기준</li><li>EU GDPR</li><li>NIST 800-53</li><li>ISO 27001</li><li>CMMC 수준 1-5(G5에만 사용 가능)</li><li>사용자 지정 평가</li></ul>|

### <a name="what-are-custom-assessments"></a>사용자 지정 평가란?

사용자 지정 평가는 새 템플릿을 만들거나 컨트롤 추가 또는 업데이트 및 개선 작업을 포함하여 기존 평가 템플릿을 사용자 지정하는 기능을 제공하는 준수 관리자 기능입니다.

### <a name="who-can-access-custom-assessments"></a>Who 사용자 지정 평가에 액세스할 수 있나요?

사용자 지정 평가 기능은 아래 나열된 대로 E5 구독을 사용하는 고객에게 제공됩니다.

- Microsoft 365 또는 Office 365 A5/E5/G5
- Microsoft 365 A5/E5/F5/G5 규정 준수
- Microsoft 365 A5/E5/F5/G5 eDiscovery 및 감사
- Microsoft 365 A5/E5/F5/G5 참가자 위험 관리
- Microsoft 365 A5/E5/F5/G5 Information Protection 및 거버넌스

## <a name="compliance-program-for-microsoft-cloud"></a>Microsoft Cloud 규정 준수 프로그램

[Microsoft Cloud 규정 준수 프로그램은](https://aka.ms/cpmc) 맞춤형 고객 지원, 교육 및 네트워킹 기회를 제공하도록 설계되었습니다. 이 프로그램에 참여하면 고객은 보안, 규정 준수 및 개인 정보 보호 분야에서 규제 기관, 업계 동료 및 Microsoft 전문가와 직접 소통할 수 있는 특별한 기회를 얻을 수 있습니다. 이 프로그램은 2013년에 만든 기존 FSI(금융 서비스 산업) 규정 준수 프로그램을 대체합니다.

### <a name="who-can-access-the-compliance-program-for-microsoft-cloud"></a>Who Microsoft 클라우드 규정 준수 프로그램에 액세스할 수 있나요?

Microsoft 클라우드용 규정 준수 프로그램은 Microsoft 365 및 Office 365 라이선스가 있는 조직에서 사용할 수 있습니다.

현재 FSI 규정 준수 프로그램에 등록된 고객은 Microsoft Cloud용 새 규정 준수 프로그램에 대한 구독을 구매해야 합니다. 자세한 내용은 [Microsoft Cloud 규정 준수 프로그램을](https://aka.ms/cpmc) 참조하세요.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 이 서비스를 통해 어떻게 혜택을 받을 수 있나요?

위험 평가자, 규정 준수 책임자, 내부 감사자, 개인 정보 보호 책임자, 규제 업무/법률, CISO와 같은 클라우드 여정에서 Microsoft를 지원하려는 Enterprise 조직은 이 서비스를 통해 혜택을 누릴 수 있습니다. 다음은 고객이 받을 수 있는 사용 가능한 혜택의 예제 시나리오입니다.

- Microsoft 클라우드 서비스를 온보딩하고 사용하기 위한 위험 평가에 대한 지속적인 위험 및 규정 준수 지원.
- Microsoft 클라우드 서비스에 대한 Microsoft 및 고객 관리형 컨트롤 지원.
- 타사 클라우드 서비스 사용에 대한 내부 감사, 규제 기관 또는 이사회 수준 승인에 대한 지원.
- 클라우드 서비스 사용에 대한 복잡한 위험 및 규정 준수 요구 사항과 관련된 지속적인 기술 질문을 지원합니다.
- 고정된 수의 고객 위험 및 규정 준수 설문지를 작성하는 데 직접 지원합니다.
- 규정 준수 경험으로 질문을 해결하는 데 도움이 되는 규제 기관 및 업계 전문가와의 연결입니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되는가?

기본적으로 Microsoft Cloud에 대한 규정 준수 프로그램은 서비스의 혜택을 받는 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. 자세한 내용은 [Microsoft Cloud 규정 준수 프로그램을](https://aka.ms/cpmc) 참조하세요.

## <a name="microsoft-purview-data-connectors"></a>Microsoft Purview 데이터 커넥터

Microsoft는 Microsoft Purview 규정 준수 포털에서 구성할 수 있는 타사 데이터 커넥터를 제공합니다. Microsoft에서 제공하는 데이터 커넥터 목록은 [타사 데이터 커넥터](/microsoft-365/compliance/archiving-third-party-data#third-party-data-connectors) 테이블을 참조하세요. 또한 이 표에는 Microsoft 365 데이터를 가져오고 보관한 후 타사 데이터에 적용할 수 있는 규정 준수 솔루션과 각 커넥터에 대한 단계별 지침에 대한 링크가 요약되어 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 이 서비스를 통해 어떻게 혜택을 받을 수 있나요?

데이터 커넥터(이전의 Microsoft 365 Data Connectors)를 사용하여 Microsoft 365 타사 데이터를 가져오고 보관할 때의 주요 이점은 가져온 후 데이터에 다양한 Microsoft Purview 솔루션을 적용할 수 있다는 것입니다. 이렇게 하면 조직의 비 Microsoft 데이터가 조직에 영향을 주는 규정 및 표준을 준수하는지 확인할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스의 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇인가요?

다음 라이선스는 사용자가 데이터 커넥터의 혜택을 누릴 수 있는 권한을 제공합니다.

- Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5 정보 보호 &amp; 거 버 넌 스
- Microsoft 365 E5/A5/G5/F5 준수
- F5 보안 & 규정 준수 Microsoft 365
- Microsoft 365 E5/A5/G5 참가자 위험 관리
- Microsoft 365 E5/A5/G5 eDiscovery 및 감사
- Office 365 E5/A5/G5

Microsoft 파트너가 제공하는 Microsoft Purview 규정 준수 포털의 데이터 커넥터의 경우 해당 커넥터를 배포하려면 조직에서 파트너와 비즈니스 관계가 필요합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되는가?

커넥터는 Microsoft Purview 규정 준수 포털 및 커넥터 카탈로그를 사용하여 구성됩니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스가 부여된 테넌트 사용자에게만 서비스를 적용하려면 어떻게 해야 할까요?

데이터 커넥터 서비스는 테넌트 수준 값입니다. 이 서비스를 활용하려는 모든 사용자는 라이선스가 있어야 합니다.

## <a name="microsoft-purview-ediscovery"></a>Microsoft Purview eDiscovery

[Microsoft 365 전자 검색(eDiscovery) 솔루션은 Microsoft 365](/microsoft-365/compliance/ediscovery) 시스템에서 내보내기 전에 조사 또는 소송과 관련된 콘텐츠를 식별, 수집, 보존, 축소 및 검토할 수 있도록 기업 내 IT 및 법률 부서에 대한 조사 및 eDiscovery 솔루션을 제공합니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 이 서비스를 통해 어떻게 혜택을 받을 수 있나요?

[eDiscovery(Standard)(](/microsoft-365/compliance/get-started-core-ediscovery) 이전의 Core eDiscovery)는 eDiscovery 사례를 만들고 특정 사례에 eDiscovery 관리자를 할당할 수 있도록 하여 콘텐츠 검색의 기본 검색 및 내보내기 기능을 기반으로 합니다. eDiscovery 관리자는 구성원인 경우에만 액세스할 수 있습니다. eDiscovery(표준)를 사용하면 검색 및 내보내기를 사례와 연결하고 사례와 관련된 콘텐츠 위치에 eDiscovery 보류를 배치할 수 있습니다.

[eDiscovery(Premium)](/microsoft-365/compliance/overview-ediscovery-20)(이전의 Advanced eDiscovery)는 조직의 내부 및 외부 조사에 응답하는 콘텐츠를 보존, 수집, 분석, 검토 및 내보내는 엔드 투 엔드 워크플로를 제공합니다. 또한 법률팀에서 전체 법적 보류 알림 워크플로를 관리하여 사례와 관련된 보유자와 통신할 수 있게 합니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스의 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇인가요?

eDiscovery(표준): 플랜 2, Exchange Online Archiving, SharePoint Online 플랜 2, Microsoft 365 E5/A5/G5/E3/A3/G3, Office 365 E5/A5/G5/E3/G3 및 F5 규정 준수 및 F5 보안 & 규정 준수를 Exchange Online.

eDiscovery(Premium): Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 준수 및 F5 보안 & 규정 준수, Microsoft 365 E5/A5/G5 eDiscovery 및 감사, Office 365 E5/A5/G5.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되는가?

기본적으로 eDiscovery 기능은 관리자가 Microsoft Purview 규정 준수 포털에서 eDiscovery 권한을 할당할 때 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스가 부여된 테넌트 사용자에게만 서비스를 적용하려면 어떻게 해야 할까요?

eDiscovery 관리자는 [eDiscovery(Premium)](/microsoft-365/compliance/add-custodians-to-case) 사례에 보유자 추가에 설명된 대로 eDiscovery(Premium)의 기본 제공 보유자 관리 도구를 사용하여 특정 사용자를 데이터 보유자로 선택할 수 있습니다.

eDiscovery 및 비보관 데이터 원본에 대한 자세한 내용은 [eDiscovery(Premium) 사례에 비보장 데이터 원본 추가를 참조](/microsoft-365/compliance/non-custodial-data-sources)하세요.

## <a name="microsoft-purview-information-barriers"></a>Microsoft Purview 정보 장벽

정보 장벽은 개인 또는 그룹이 서로 통신하지 못하도록 관리자가 구성할 수 있는 정책입니다. 예를 들어 한 부서가 다른 부서와 공유해서는 안 되는 정보를 처리하거나 그룹이 외부 연락처와 통신하지 못하도록 해야 하는 경우에 유용합니다. 또한 정보 장벽 정책은 조회 및 검색을 방지합니다. 즉, 통신하지 않아야 하는 사람과 통신하려고 하면 사용자 선택기에서 해당 사용자를 찾을 수 없습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 이 서비스를 통해 어떻게 혜택을 받을 수 있나요?

사용자는 다른 사용자와의 통신이 제한되는 경우 정보 장벽의 고급 규정 준수 기능을 활용할 수 있습니다. 정보 장벽 정책은 특정 사용자 세그먼트가 각 세그먼트와 통신하지 못하도록 하거나 특정 세그먼트가 특정 다른 세그먼트와만 통신하도록 허용하도록 정의할 수 있습니다. 정보 장벽 정책 정의에 대한 자세한 내용은 [정보 장벽 정책 정의를](/microsoft-365/compliance/information-barriers-policies) 참조하세요. 두 그룹이 서로 통신할 수 없는 시나리오의 경우 두 그룹의 사용자는 서비스의 혜택을 누릴 수 있는 라이선스가 필요합니다(아래 예제 참조).<br><br>

| 시나리오 | Who 라이선스가 필요합니까? |
|:------|:------|
| 두 그룹(Group1&nbsp; 및 Group2&nbsp;)은 서로 통신할 수 없습니다(즉, Group1 사용자는 Group2&nbsp;&nbsp; 사용자와의 통신이 제한되고 Group2&nbsp; 사용자는 Group1&nbsp; 사용자와의 통신이 제한됩니다.) | Group1 및 Group2&nbsp;&nbsp;의 사용자 |

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스의 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇인가요?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 규정 준수 및 F5 보안 & 규정 준수, Microsoft 365 E5/A5/G5 참가자 위험 관리 및 Office 365 E5/A5/G5는 사용자가 정보 장벽의 혜택을 누릴 수 있는 권한을 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되는가?

관리자는 Microsoft Purview 규정 준수 포털에서 PowerShell cmdlet을 사용하여 정보 장벽 정책을 만들고 관리합니다. 정보 장벽 정책을 만들려면 관리자에게 Microsoft 365 Enterprise 전역 관리자, Office 365 전역 관리자 또는 규정 준수 관리자 역할이 할당되어야 합니다. 기본적으로 이러한 정책은 테넌트에 있는 모든 사용자에게 적용됩니다. 정보 장벽에 대한 자세한 내용은 [Microsoft Teams 정보 장벽을](/MicrosoftTeams/information-barriers-in-teams) 참조하세요.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스가 부여된 테넌트 사용자에게만 서비스를 적용하려면 어떻게 해야 할까요?

관리자는 Microsoft Purview 규정 준수 포털에서 위치(워크로드), 포함된 사용자 및 제외된 사용자를 사용자 지정할 수 있습니다. 자세한 내용은 [Microsoft Teams의 정보 장벽](/MicrosoftTeams/information-barriers-in-teams)을 참조하세요.

## <a name="microsoft-purview-data-lifecycle-management"></a>Microsoft Purview 데이터 수명 주기 관리

데이터 수명 주기 관리(이전의 Microsoft 정보 거버넌스)는 조직에서 데이터를 검색, 분류, 레이블 지정 및 관리하여 위험을 관리하는 데 도움이 됩니다. 데이터 수명 주기 관리를 통해 조직은 비즈니스 및 규제 요구 사항을 충족할 뿐만 아니라 Microsoft 365 및 타사 데이터에 보존 및 삭제 기능을 제공하여 공격 노출 영역을 줄일 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 이 서비스를 통해 어떻게 혜택을 받을 수 있나요?

사용자는 특정 정책 및 규정을 유지하기 위해 보존 목적으로 데이터를 분류할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스의 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇인가요?

Microsoft 365 F3/Business Premium, Office 365 E5/A5/G5/E3/A3/G3/E1/A1/G1/F3 및 독립 실행형 Exchange 계획은 사용자가 사서함 데이터에 레코드가 아닌 보존 레이블을 수동으로 적용하여 혜택을 받을 수 있는 권한을 제공합니다.

Microsoft 365 F3/F1/Business Premium, Office 365 E5/A5/G5/E3/A3/G3/F3/E1/A1/G1 및 독립 실행형 SharePoint 계획은 사용자가 SharePoint 또는 OneDrive 파일에 레코드가 아닌 보존 레이블을 수동으로 적용하여 혜택을 받을 수 있는 권한을 제공합니다.

Microsoft 365 E5/A5/G5/E3/A3/G3/Business Premium, Office 365 E5/A5/G5/E3/A3/G3, Exchange 플랜 2 및 Exchange Online Archiving 사용자가 기본 조직 전체 또는 위치 전체 사서함 보존 정책의 혜택을 누릴 수 있는 권한을 제공합니다.

Microsoft 365 E5/A5/G5/E3/A3/G3, Office 365 E5/A5/G5/E3/A3/G3 및 SharePoint 플랜 2는 사용자가 기본 SharePoint 또는 OneDrive 보존 정책의 혜택을 누릴 수 있는 권한을 제공하고/또는 파일에 비기록 보존 레이블을 수동으로 적용할 수 있는 권한을 제공합니다. SharePoint 또는 OneDrive.

조직은 보존 정책을 사용하여 정책에 따라 Teams 메시지를 유지하거나 삭제할 수 있습니다. 여기에는 Teams 채팅 및 대화에서 메시지 관리가 포함됩니다.

다음 라이선스는 사용자가 Teams 보존 정책의 혜택을 누릴 수 있는 권한을 제공합니다.

- Microsoft 365 E5/G5/A5/E3/G3/A3/F3/F1, Business Basic, Business Standard 및 Business Premium
- Office 365 E5/G5/A5/E3/G3/A3/F3/E1/G1

다음 라이선스가 있는 사용자의 경우 지원되는 최소 보존 또는 삭제 기간은 30일입니다.

- Microsoft 365 F1/F3, Business Basic, Business Standard 및 Business Premium
- Office 365 E1/G1 및 F3

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 규정 준수 및 F5 보안 & 규정 준수, Microsoft 365 Information Protection 및 거버넌스 E5/A5/G5 및 Office 365 E5 /A5는 사용자가 자동으로 보존 레이블 또는 정책을 적용하고, 기본 보존 레이블 또는 정책을 적용하고, 사용자 지정 이벤트를 기반으로 보존 레이블의 보존 기간을 시작하고, 레이블 보존 기간이 끝날 때 수동 처리 검토를 트리거하고, 네이티브 데이터 커넥터를 통해 타사 데이터를 가져오고, 파일을 레코드로 선언하는 등의 혜택을 누릴 수 있는 권한을 제공합니다.  레이블이 지정된 콘텐츠를 검색하고 레이블 지정 활동을 모니터링합니다.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 규정 준수 및 F5 보안 & 규정 준수, Microsoft 365 E5/A5/G5 Information Protection 및 거버넌스는 학습 가능한 분류자를 기반으로 보존 레이블을 자동으로 적용할 수 있는 권한을 사용자에게 제공합니다. .

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되는가?

기본적으로 데이터 수명 주기 관리 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. 사용이 허가된 사용자에 대한 자동 레이블 지정 및 정책을 적용하도록 데이터 수명 주기 관리를 구성하는 방법에 대한 자세한 내용은 [Microsoft Purview 데이터 수명 주기 관리를](/microsoft-365/compliance/manage-information-governance) 참조하세요.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스가 부여된 테넌트 사용자에게만 서비스를 적용하려면 어떻게 해야 할까요?

데이터 수명 주기 관리 기능은 특정 위치(팀 사이트, 그룹 사이트 등)에서 라이선스가 있는 사용자에게 적용할 수 있습니다. 사용이 허가된 사용자에 대한 자동 레이블 지정 및 정책을 적용하도록 데이터 수명 주기 관리를 구성하는 방법에 대한 자세한 내용은 [Microsoft Purview 데이터 수명 주기 관리를](/microsoft-365/compliance/manage-information-governance) 참조하세요.

## <a name="microsoft-purview-information-protection-customer-key"></a>Microsoft Purview Information Protection: 고객 키

고객 키(이전의 Microsoft 365 고객 키)를 사용하여 조직의 암호화 키를 제어하고 Microsoft 데이터 센터에서 미사용 데이터를 암호화하는 데 사용하도록 Microsoft 365 구성합니다. 즉, 고객 키를 사용하면 사용자 고유의 키를 사용하여 사용자에게 속한 암호화 계층을 추가할 수 있습니다. 고객 키는 Microsoft 365 Data-At-Rest 암호화 서비스를 통해 여러 [Microsoft 365 워크로드](/microsoft-365/compliance/customer-key-overview#about-data-encryption-policies)에 대한 미사용 데이터 암호화 지원을 제공합니다. 또한 고객 키는 SharePoint Online 및 비즈니스용 OneDrive 데이터에 대한 암호화뿐만 아니라 Exchange Online 사서함 수준 암호화를 제공합니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 이 서비스를 통해 어떻게 혜택을 받을 수 있나요?

사용자는 자신의 조직에서 제공, 제어 및 관리하는 암호화 키를 사용하여 애플리케이션 계층에서 미사용 데이터를 암호화함으로써 고객 키를 활용할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스의 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇인가요?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 준수, Microsoft 365 F5 보안 & 규정 준수, Microsoft 365 E5/A5/G5 Information Protection 및 거버넌스 및 Office 365 E5 /A5/G5는 사용자가 고객 키를 활용할 수 있는 권한을 제공합니다. 고객 키의 모든 혜택을 얻으려면 Azure Key Vault 대한 구독도 있어야 합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되는가?

[고객 키 설정](/microsoft-365/compliance/customer-key-set-up) 문서에서는 필요한 Azure 리소스를 만들고 구성하기 위해 수행해야 하는 단계를 설명한 다음, 고객 키를 설정하는 단계를 제공합니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스가 부여된 테넌트 사용자에게만 서비스를 적용하려면 어떻게 해야 할까요?

다중 워크로드 암호화 지원을 제공하는 미사용 데이터 Microsoft 365 서비스는 테넌트 수준 서비스입니다. 일부 허가되지 않은 사용자는 기술적으로 서비스에 액세스할 수 있지만 서비스의 혜택을 받으려는 모든 사용자에게는 라이선스가 필요합니다. Exchange Online 사서함 수준 암호화의 경우 사용자 사서함에 데이터 암호화 정책을 할당할 수 있는 라이선스가 있어야 합니다.

## <a name="microsoft-purview-information-protection-data-classification-analytics-overview-content-amp-activity-explorer"></a>Microsoft Purview Information Protection: 데이터 분류 분석: 개요 콘텐츠 &amp; 활동 탐색기

데이터 분류 분석 기능은 Microsoft Purview 규정 준수 포털 내에서 사용할 수 있습니다. 개요는 디지털 콘텐츠의 위치와 가장 일반적인 중요한 정보 유형 및 레이블을 보여 줍니다. 콘텐츠 탐색기는 중요한 데이터의 양과 형식에 대한 가시성을 제공하며 사용자가 레이블 또는 민감도 유형별로 필터링하여 중요한 데이터가 저장되는 위치를 자세히 볼 수 있도록 합니다. 활동 탐색기는 콘텐츠가 위험에 노출될 수 있는 레이블 다운그레이드 또는 외부 공유와 같은 중요한 데이터 및 레이블과 관련된 활동을 표시합니다.

활동 탐색기는 관리자가 최종 사용자가 사용하는 중요한 정보와 관련된 활동에 대한 가시성을 얻을 수 있는 단일 창 창을 제공합니다. 이러한 데이터에는 레이블 활동, DLP(데이터 손실 방지) 로그, 자동 레이블 지정, 엔드포인트 DLP 등이 포함됩니다.

콘텐츠 탐색기는 관리자에게 지원되는 Microsoft 365 워크로드 내에 저장된 중요한 문서를 인덱싱하고 저장하는 중요한 정보를 식별하는 기능을 제공합니다. 또한 콘텐츠 탐색기는 민감도 및 보존 레이블로 분류된 문서를 식별하는 데 도움이 됩니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 이 서비스를 통해 어떻게 혜택을 받을 수 있나요?

정보 보호 및 규정 준수 관리자는 서비스에 액세스하여 이러한 로그 및 인덱싱된 데이터에 액세스하여 중요한 데이터가 저장되는 위치와 이 데이터와 관련되고 최종 사용자가 수행하는 활동을 이해할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스의 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇인가요?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 준수, Microsoft 365 F5 보안 & 규정 준수, Microsoft 365 E5/A5/G5 Information Protection 거버넌스 및 Office 365 E5 &amp; 사용이 허가된 사용자  는 Microsoft 365 데이터 분류 분석을 활용할 수 있습니다.

Microsoft 365 E3/A3/G3 및 Office 365 E3/A3/G3을 사용하면 사용자가 콘텐츠 탐색기 데이터 집계의 혜택을 누릴 수 있습니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되는가?

기본적으로 개요 콘텐츠 및 활동 탐색기 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. 사용이 허가된 사용자에 대한 데이터 분류 분석을 구성하는 방법에 대한 자세한 내용은 다음을 참조하세요.

- **콘텐츠 탐색기**: [콘텐츠 탐색기를 사용하여 시작](/microsoft-365/compliance/data-classification-content-explorer).
- **활동 탐색기**: [활동 탐색기를 사용하여 시작](/microsoft-365/compliance/data-classification-activity-explorer).
- **데이터 분류 릴리스 정보**: [데이터 분류 릴리스 정보](/microsoft-365/compliance/data-classification-overview#public-preview-release-notes)입니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스가 부여된 테넌트 사용자에게만 서비스를 적용하려면 어떻게 해야 할까요?

이 기능은 Microsoft Purview 규정 준수 포털 내에서 솔루션을 적극적으로 사용하는 사용자에 대해 범위가 지정되어야 합니다.

## <a name="microsoft-purview-information-protection-data-loss-prevention-dlp-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Microsoft Purview Information Protection: Exchange Online, SharePoint Online 및 비즈니스용 OneDrive 대한 DLP(데이터 손실 방지)

Exchange Online, SharePoint Online 및 비즈니스용 OneDrive 대한 데이터 손실 방지(이전의 Microsoft Office 365 데이터 손실 방지)를 통해 조직은 전자 메일 및 파일(저장된 파일 포함)에서 중요한 정보를 식별, 모니터링 및 자동으로 보호할 수 있습니다. Microsoft Teams 파일 리포지토리).

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 이 서비스를 통해 어떻게 혜택을 받을 수 있나요?

사용자는 조직의 DLP 정책에 구성된 대로 전자 메일 및 파일이 중요한 정보를 검사할 때 Exchange Online, SharePoint Online 및 비즈니스용 OneDrive DLP의 이점을 누릴 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스의 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇인가요?

Microsoft 365 E3/A3/Business Premium, Office 365 E3/A3 및 Microsoft Purview 데이터 손실 방지 및 F5 규정 준수 및 F5 보안 & 규정 준수는 사용자가 Exchange Online, SharePoint Online 및 Microsoft Purview DLP의 혜택을 누릴 수 있는 권한을 제공합니다. 비즈니스용 OneDrive.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되는가?

기본적으로 Exchange Online 전자 메일, SharePoint 사이트 및 OneDrive 계정은 테넌트 내의 모든 사용자에 대해 이러한 DLP 기능에 대해 *사용하도록 설정된 위치(워크로드)* 입니다. DLP 정책 사용에 대한 자세한 내용은 [데이터 손실 방지 개요를](/microsoft-365/compliance/data-loss-prevention-policies) 참조하세요.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스가 부여된 테넌트 사용자에게만 서비스를 적용하려면 어떻게 해야 할까요?

관리자는 Microsoft Purview 규정 준수 포털에서 위치(워크로드)를 사용자 지정하고, 사용자를 포함하고, 사용자를 제외할 수 있습니다.

## <a name="microsoft-purview-information-protection-data-loss-prevention-dlp-for-teams"></a>Microsoft Purview Information Protection: Teams 대한 DLP(데이터 손실 방지)

Teams 통신 DLP를 사용하면 조직은 재무 정보, 개인 식별 정보, 건강 관련 정보 또는 기타 기밀 정보와 같은 중요한 정보가 포함된 채팅 및 채널 메시지를 차단할 수 있습니다.

### <a name="which-users-benefit-from-the-service"></a>서비스의 혜택을 받는 사용자는 무엇인가요?

- Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5/F5 규정 준수 및 F5 보안 & 규정 준수
- Microsoft 365 E5/A5/G5 Information Protection 및 거버넌스
- Office 365 E5/A5/G5

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 이 서비스를 통해 어떻게 혜택을 받을 수 있나요?

보낸 사람은 조직의 DLP 정책에 구성된 대로 보내는 채팅 및 채널 메시지에서 중요한 정보를 검사하여 중요한 정보를 얻을 수 있습니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되는가?

기본적으로 Teams 채팅 및 채널 메시지는 테넌트 내의 모든 사용자에 대해 이러한 DLP 기능에 대해 *활성화된 위치(워크로드)* 입니다. DLP 정책 사용에 대한 자세한 내용은 [데이터 손실 방지 개요를](/office365/securitycompliance/data-loss-prevention-policies) 참조하세요.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스가 부여된 테넌트 사용자에게만 서비스를 적용하려면 어떻게 해야 할까요?

관리자는 Microsoft Purview 규정 준수 포털에서 위치(워크로드), 포함된 사용자 및 제외된 사용자를 사용자 지정할 수 있습니다.

## <a name="microsoft-purview-information-protection-double-key-encryption"></a>Microsoft Purview Information Protection: 이중 키 암호화

이중 키 암호화(이전의 Microsoft 365 이중 키 암호화)를 사용하면 매우 중요한 데이터를 보호하여 특수 요구 사항을 충족하고 암호화 키를 완전히 제어할 수 있습니다. 이중 키 암호화는 두 개의 키를 사용하여 데이터를 보호하며, 한 키는 컨트롤에 있고 두 번째 키는 Microsoft Azure 안전하게 저장됩니다. 데이터를 보려면 두 키 모두에 대한 액세스 권한이 있어야 합니다. Microsoft는 하나의 키에만 액세스할 수 있으므로 사용자의 키와 데이터를 Microsoft에서 사용할 수 없으므로 데이터의 개인 정보 및 보안을 완전히 제어할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 이 서비스를 통해 어떻게 혜택을 받을 수 있나요?

사용자는 암호화된 데이터를 클라우드로 마이그레이션하여 키가 사용자를 제어하는 한 타사 액세스를 방지함으로써 이중 키 암호화의 이점을 누릴 수 있습니다. 사용자는 다른 민감도 레이블로 보호된 콘텐츠와 유사한 이중 키 암호화 콘텐츠를 보호하고 사용할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스의 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇인가요?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 규정 준수 및 F5 보안 & 규정 준수, Microsoft 365 E5/A5/G5 Information Protection 및 거버넌스, Office 365 E5 /A5/G5 및 EMS E5는 사용자가 이중 키 암호화의 혜택을 누릴 수 있는 권한을 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되는가?

이중 키 암호화는 Windows 데스크톱 버전의 Microsoft Office 지원합니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스가 부여된 테넌트 사용자에게만 서비스를 적용하려면 어떻게 해야 할까요?

사용이 허가된 사용자를 위해 Office 365 및/또는 Microsoft 365 조직 내의 데이터에 암호화 키를 할당하려면 Double Key Encryption 배포 지침을 따릅니다.

## <a name="information-protection-office-365-advanced-message-encryption"></a>Information Protection: Office 365 고급 메시지 암호화

Office 365 고급 메시지 암호화 고객이 외부 수신자와 암호화된 전자 메일에 대한 액세스를 보다 유연하게 제어해야 하는 규정 준수 의무를 충족하는 데 도움이 됩니다. 고급 메시지 암호화를 사용하면 관리자는 중요한 정보 유형(예: 개인 식별 정보 또는 재무 또는 상태 ID)을 검색할 수 있는 자동 정책을 사용하여 조직 외부에서 공유되는 중요한 전자 메일을 제어하거나, 키워드를 사용하여 사용자 지정 전자 메일 템플릿을 적용하고 보안 웹 포털을 통해 암호화된 전자 메일에 대한 액세스 만료를 통해 보호를 강화할 수 있습니다. 또한 관리자는 언제든지 액세스를 취소하여 보안 웹 포털을 통해 외부에서 액세스하는 암호화된 전자 메일을 추가로 제어할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 이 서비스를 통해 어떻게 혜택을 받을 수 있나요?

메시지 보낸 사람이 고급 메시지 암호화에서 제공하는 중요한 전자 메일에 대한 추가 컨트롤을 활용할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스의 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇인가요?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 규정 준수 및 F5 보안 & 규정 준수 및 Microsoft 365 E5/A5/G5 Information Protection  및 거버넌스는 사용자가 고급 메시지 암호화를 활용할 수 있는 권한을 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되는가?

관리자는 **메일 flowRules** > 의 Exchange 관리 센터에서 고급 메시지 암호화 정책을 만들고 관리 **합니다**. 기본적으로 이러한 규칙은 테넌트에 있는 모든 사용자에게 적용됩니다. 새 메시지 암호화 기능을 설정하는 방법에 대한 자세한 내용은 [새 Office 365 메시지 암호화 기능 설정을 참조하세요](/office365/securitycompliance/set-up-new-message-encryption-capabilities).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스가 부여된 테넌트 사용자에게만 서비스를 적용하려면 어떻게 해야 할까요?

관리자는 고급 메시지 암호화에 대한 메일 흐름 규칙을 라이선스가 있는 사용자에게만 적용해야 합니다. 메일 흐름 규칙 정의에 대한 자세한 내용은 [Office 365 메일 메시지를 암호화하는 메일 흐름 규칙 정의를 참조](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)하세요.

## <a name="information-protection-office-365-message-encryption"></a>Information Protection: Office 365 메시지 암호화

OME(Office 365 메시지 암호화)는 Azure RMS(권한 관리)를 기반으로 구축된 서비스로, 대상의 전자 메일 주소(Gmail, Yahoo! Mail, Outlook.com 등)에 상관없이 사용자 조직 내부 또는 외부 사람에게 암호화된 전자 메일을 보낼 수 있습니다.

암호화된 메시지를 보려면 받는 사람이 일회용 암호를 얻어 Microsoft 계정에 로그인하거나 Office 365와 연결된 회사 또는 학교 계정을 사용하여 로그인할 수 있습니다. 받는 사람은 암호화된 회신을 보낼 수도 있습니다. 암호화된 메시지를 보거나 암호화된 회신을 보내기 위해 구독이 필요하지 않습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 이 서비스를 통해 어떻게 혜택을 받을 수 있나요?

메시지 보낸 사람이 Office 365 메시지 암호화에서 제공하는 중요한 전자 메일에 대한 추가 컨트롤을 활용할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스의 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇인가요?

- Microsoft 365 F3/E3/A3/G3/E5/A5/G5 및 Microsoft Business Premium
- Office 365 A1/E3/A3/G3/E5/A5/G5
- 또한 Azure Information Protection 플랜 1은 Exchange Online Kiosk, Exchange Online 플랜 1, Exchange Online 계획에 추가된 경우 Office 365 메시지 암호화의 혜택을 누릴 수 있는 권한을 조직에 제공합니다. 플랜 2, Office 365 F3, Microsoft 365 Business Basic, Microsoft 365 Business Standard 또는 Office 365 Enterprise E1

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되는가?

관리자는 **Mail flowRules** > 의 Exchange 관리 센터에서 Office 365 메시지 암호화 정책을 만들고 관리 **합니다**. 기본적으로 이러한 규칙은 테넌트에 있는 모든 사용자에게 적용됩니다. 새 Office 365 메시지 암호화 기능을 설정하는 방법에 대한 자세한 내용은 [새 메시지 암호화 기능 설정을 참조하세요](/office365/securitycompliance/set-up-new-message-encryption-capabilities).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스가 부여된 테넌트 사용자에게만 서비스를 적용하려면 어떻게 해야 할까요?

관리자는 Office 365 메시지 암호화에 대한 메일 흐름 규칙을 사용이 허가된 사용자에게만 적용해야 합니다. 메일 흐름 규칙 정의에 대한 자세한 내용은 [메일 메시지를 암호화하는 메일 흐름 규칙 정의를 참조하세요](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email).

## <a name="microsoft-purview-information-protection-sensitivity-labeling"></a>Microsoft Purview Information Protection: 민감도 레이블 지정

Information Protection 조직은 중요한 문서 및 전자 메일을 검색, 분류, 레이블 지정 및 보호할 수 있습니다. 관리자는 레이블을 자동으로 적용하는 규칙 및 조건을 정의하거나, 사용자가 수동으로 레이블을 적용하거나, 두 가지 조합을 사용할 수 있습니다. 여기서 사용자에게 레이블 적용에 대한 권장 사항이 제공됩니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 이 서비스를 통해 어떻게 혜택을 받을 수 있나요?

사용자는 콘텐츠에 민감도 레이블을 수동으로 적용하거나 콘텐츠를 자동으로 분류하여 이점을 얻을 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스의 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇인가요?

**수동 민감도 레이블 지정** 의 경우 다음 라이선스는 사용자 권한을 제공합니다.

- Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium(Office 365 Information Protection – E5 라이선스만 할당된 경우 표준을 사용하도록 설정해야 함)
- Enterprise Mobility + Security E3/E5
- Office 365 E5/A5/E3/A3
- AIP 계획 1
- AIP 계획 2

**클라이언트 및 서비스 쪽 자동 민감도 레이블 지정** 모두에 대해 다음 라이선스는 사용자 권한을 제공합니다.

- Microsoft 365 E5/A5/G5
- F5 및 E5 규정 준수
- F5 보안 & 규정 준수
- Microsoft 365 E5/A5/G5 Information Protection 및 거버넌스
- Office 365 E5

**클라이언트 쪽 자동 민감도 레이블 지정에 대해서만** 다음 라이선스는 사용자 권한을 제공합니다.

- Enterprise Mobility + Security E5/A5/G5
- AIP 계획 2

**Power BI 민감도 레이블을 적용하고 보고 데이터를 Power BI Excel, PowerPoint 또는 PDF로 내보낼 때 데이터를 보호하기 위해** 다음 라이선스는 사용자 권한을 제공합니다.

- Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium
- Enterprise Mobility + Security E3/E5
- AIP 계획 1
- AIP 계획 2

사용자가 [AIPService](/powershell/azure/aip/overview) PowerShell 모듈을 통해 Azure Information Protection 대한 Azure Rights Management 보호 서비스를 관리하는 방법에 대한 자세한 내용은 [Azure Information Protection](/powershell/azure/aip/overview) 참조하세요.

> [!NOTE]
>
> - Power BI Microsoft 365 E5/A5/G5에 포함되어 있습니다. 다른 모든 플랜에서는 Power BI 별도로 라이선스를 받아야 합니다.
> - Machine Learning 기반 자동 분류(학습 가능한 분류자)에 대한 사용자 혜택 정보는 [정보 거버넌스](/office365/servicedescriptions/microsoft-365-service-descriptions/microsoft-365-tenantlevel-services-licensing-guidance/microsoft-365-security-compliance-licensing-guidance#information-governance) 및/또는 [레코드 관리를](/office365/servicedescriptions/microsoft-365-service-descriptions/microsoft-365-tenantlevel-services-licensing-guidance/microsoft-365-security-compliance-licensing-guidance#records-management) 참조하세요.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되는가?

기본적으로 정보 보호 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. 사용이 허가된 사용자에 대한 정책을 구성하는 방법에 대한 자세한 내용은 Azure Rights Management 활성화를 참조하세요.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스가 부여된 테넌트 사용자에게만 서비스를 적용하려면 어떻게 해야 할까요?

AIP 스캐너 기능을 사용하는 경우를 제외하고 정책 범위를 특정 그룹으로 지정할 수 있습니다. 또는 사용자 및 레지스트리를 편집하여 허가되지 않은 사용자가 분류 또는 레이블 지정 기능을 실행하지 못하도록 방지할 수 있습니다.

AIP 스캐너 기능의 경우 Microsoft는 라이선스가 없는 사용자에게 파일 분류, 레이블 지정 또는 보호 기능을 제공하지 않습니다.

자세한 내용은 [민감도 레이블 만들기 및 게시](/microsoft-365/compliance/create-sensitivity-labels#publish-sensitivity-labels-by-creating-a-label-policy) 및 [Azure Information Protection 통합 레이블 지정 스캐너 이해를](/azure/information-protection/deploy-aip-scanner) 참조하세요.

## <a name="microsoft-purview-insider-risk-management"></a>Microsoft Purview 참가자 위험 관리

내부자 위험 관리(이전의 Microsoft 365 참가자 위험 관리)는 조직의 위험한 활동을 감지, 조사 및 조치를 취하도록 하여 내부 위험을 최소화하는 데 도움이 되는 솔루션입니다.

사용자 지정 정책을 사용하면 필요한 경우 Microsoft Purview eDiscovery(Premium)(이전의 Microsoft Advanced eDiscovery)로 사례를 에스컬레이션하는 등 조직의 악의적이고 실수로 위험한 활동을 검색하고 조치를 취할 수 있습니다. 조직의 위험 분석가는 적절한 조치를 신속하게 수행하여 사용자가 조직의 규정 준수 표준을 준수하도록 할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 이 서비스를 통해 어떻게 혜택을 받을 수 있나요?

사용자는 자신의 활동을 위험에 대해 모니터링하여 이점을 얻을 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스의 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇인가요?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 규정 준수 및 F5 보안 & 규정 준수 및 Microsoft 365 E5/A5/G5 참가자 위험 관리는 사용자가 참가자 위험 관리의 혜택을 누릴 수 있는 권한을 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되는가?

참가자 위험 관리 정책은 Microsoft Purview 규정 준수 포털에서 만들고 사용자에게 할당해야 합니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스가 부여된 테넌트 사용자에게만 서비스를 적용하려면 어떻게 해야 할까요?

자세한 내용은 [내부자 위험 관리 시작](/microsoft-365/compliance/insider-risk-management-configure) 참조하세요.

## <a name="microsoft-defender-for-business"></a>비즈니스용 Microsoft Defender

비즈니스용 Microsoft Defender 중소기업(최대 300명의 직원)을 위해 설계된 새로운 엔드포인트 보안 솔루션입니다. 비즈니스용 Defender는 독립 실행형 솔루션으로 사용할 수 있으며 Microsoft 365 Business Premium 일부로도 포함됩니다. 이 엔드포인트 보안 솔루션을 사용하면 SMB(중소기업) 조직 디바이스가 랜섬웨어, 맬웨어, 피싱 및 기타 위협으로부터 더 잘 보호됩니다.

자세한 내용은 [비즈니스용 Microsoft Defender](/microsoft-365/security/defender-business) 참조하세요.

### <a name="which-licenses-provide-the-rights-for-users-to-benefit-from-the-service"></a>사용자가 서비스의 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇인가요? 

비즈니스용 Microsoft Defender Microsoft 365 Business Premium 라이선스의 일부로 포함됩니다.  

독립 실행형 버전의 비즈니스용 Defender는 최대 300명의 직원이 있는 중소기업(SMB)을 위한 옵션으로도 사용할 수 있습니다. 자세한 내용은  [비즈니스용 Microsoft Defender 다운로드하는 방법을](/microsoft-365/security/defender-business/get-defender-business) 참조하세요.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 이 서비스를 통해 어떻게 혜택을 받을 수 있나요?

[Microsoft 365 Business Premium 비즈니스용 Microsoft Defender](https://techcommunity.microsoft.com/t5/small-and-medium-business-blog/new-security-solutions-to-help-secure-small-and-medium/ba-p/3207043) 추가하면 플랫폼 간 엔드포인트 보호 및 정교한 랜섬웨어 방어와 같은 기술을 추가하여 비즈니스 Premium 기존 생산성 및 보안 제공이 강화됩니다. 엔드포인트 감지 및 응답 및 자동화된 조사 및 수정.

독립 실행형 버전의 비즈니스용 Defender는 최대 300명의 직원이 있는 중소기업이 저렴한 가격으로 엔터프라이즈급 엔드포인트 보안 기술을 얻을 수 있는 옵션을 제공합니다. 

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되는가? 

Microsoft 365 Business Premium 있는 경우 [Microsoft 365 Defender 포털](https://sip.security.microsoft.com/homepage)을 통해 비즈니스용 Defender에 액세스할 수 있습니다. 

기본적으로 비즈니스용 Microsoft Defender 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. 비즈니스용 Defender를 설정하고 구성하는 방법에 대한 자세한 내용은 [비즈니스용 Microsoft Defender 설명서 | Microsoft Docs](/microsoft-365/security/defender-business).

자세한 내용 및 추가 리소스에 대한 링크는 [비즈니스용 Microsoft Defender FAQ](/microsoft-365/security/defender-business/get-defender-business)를 검토하세요.

## <a name="microsoft-defender-for-cloud-apps"></a>Microsoft Defender for Cloud Apps

Microsoft Defender for Cloud Apps 핵심 기능을 구현하고 여러 유형의 배포를 지원하는 방법에 대한 유연성을 고객에게 제공하는 CASB(클라우드 액세스 보안 브로커) 솔루션입니다. Microsoft Defender for Cloud Apps 사용자 기반 구독 서비스입니다. 각 라이선스는 사용자별, 매월 라이선스이며 아래 나열된 대로 독립 실행형 제품 또는 여러 라이선스 계획의 일부로 라이선스가 부여될 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스의 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇인가요?

Microsoft Defender for Cloud Apps 독립 실행형 라이선스로 사용할 수 있으며 다음 계획의 일부로도 사용할 수 있습니다.

- Enterprise Mobility + Security E5
- Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 보안
- Microsoft 365 E5/A5/G5/F5 준수
- Microsoft 365 F5 보안 &amp; 준수
- Microsoft 365 Information Protection 및 거버넌스

Azure AD P1/P2는 사용자가 클라우드용 Defender 앱의 일부로 포함된 검색 기능을 활용할 수 있는 권한을 제공합니다.

클라우드용 Defender 앱의 조건부 액세스 앱 제어 기능을 활용하려면 Enterprise Mobility + Security F1/F3/E3/A3/G3에 포함된 Azure Active Directory P1에 대한 라이선스가 사용자에게 부여되어야 합니다. E5, Microsoft 365 E3/A3/G3, Microsoft 365 E5/A5/G5 및 Microsoft 365 E5/A5/G5/F5 보안 및 Microsoft 365 F5 보안 &amp; 준수를 Enterprise Mobility + Security.

자동 클라이언트 쪽 레이블 지정을 활용하려면 Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 준수에 포함된 Azure Information Protection P2에 대한 라이선스가 사용자에게 부여되어야 합니다. Microsoft 365 F5 보안 &amp; 규정 준수 및 Microsoft 365 Information Protection 및 거버넌스.

> [!NOTE]
> 자동 서버 쪽 레이블 지정에는 Office 365 Premium 라이선스(`MIP_S_CLP2` 또는 `efb0351d-3b08-4503-993d-383af8de41e3`)에 대한 Information Protection 필요합니다. 참조하려면  [라이선스에 대한 seeProduct 이름 및 서비스 계획 식별자를 참조하세요](/azure/active-directory/enterprise-users/licensing-service-plan-reference).

자세한 내용은 여기를 참조 [하세요](https://aka.ms/defender-for-cloud-apps).

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되는가?

기본적으로 Microsoft Defender for Cloud Apps 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다.

사용이 허가된 사용자에 대한 클라우드용 Defender 앱 정책을 구성하는 방법에 대한 자세한 내용은 여기를 참조[하세요](https://aka.ms/defender-for-cloud-apps).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스가 부여된 테넌트 사용자에게만 서비스를 적용하려면 어떻게 해야 할까요?

관리자는 서비스에서 사용할 수 있는 범위가 지정된 배포 기능을 사용하여 라이선스가 있는 사용자에게 Microsoft Defender for Cloud Apps 배포 범위를 지정할 수 있습니다. 자세한 내용은 [Scoped 배포](/cloud-app-security/scoped-deployment)를 참조하세요.

### <a name="what-is-the-app-governance-add-on-feature-for-microsoft-defender-for-cloud-apps"></a>Microsoft Defender for Cloud Apps 대한 앱 거버넌스 추가 기능란?

앱 거버넌스는 Microsoft Defender for Cloud Apps 추가 기능으로 사용할 수 있는 보안 및 정책 관리 기능입니다.

앱 거버넌스를 통해 고객은 Microsoft 365 플랫폼에서 타사 및 사내 개발 앱을 모니터링하고 관리하여 위험하거나 승인되지 않은 액세스, 자격 또는 권한 있는 데이터 사용을 식별, 경고 및 방지할 수 있습니다. 앱 거버넌스는 [Microsoft Graph API](/graph/use-the-api) 통해 Microsoft 365 데이터에 액세스하는 OAuth 지원 앱을 위해 설계되었습니다.

앱 거버넌스는 고객에게 다음과 같은 기능 이점을 제공합니다.

- **심층 가시성 및 인사이트:** Microsoft 365 데이터에 액세스하는 앱에 대한 [심층적인 가시성](/microsoft-365/compliance/app-governance-visibility-insights-overview)과 환경에서 앱이 구성되고 작동하는 방식에 대한 실행 가능한 인사이트를 얻습니다.
- **정책 기반 거버넌스:** 데이터 액세스에 대한 조직의 보안 및 규정 준수 태세에 따라 데이터, 사용자 및 기타 앱으로  [적절한 앱 동작을 사전에 정의하고 적용](/microsoft-365/compliance/app-governance-app-policies-overview)합니다.
- **포괄적인:** [검색 및 수정](/microsoft-365/compliance/app-governance-detect-remediate-overview): 기계 학습 모델을 사용하여 비정상적인 앱 동작을 검색하고, 자동화된 문제 및 수동 수정 작업을 해결합니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스의 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇인가요?

앱 거버넌스는 다음을 사용하여 조직에 추가 기능으로 사용할 수 있습니다.

- Microsoft Defender for Cloud Apps(독립 실행형)
- Enterprise Mobility + Security E5/A5
- Microsoft 365 E5/A5
- Microsoft 365 보안
- Microsoft 365 규정 준수 E5/A5
- Microsoft 365 E5/A5 Information Protection 및 거버넌스
- F5 보안 추가 기능 Microsoft 365
- Microsoft 365 F5 규정 준수 추가 기능
- Microsoft 365 F5 보안 + 규정 준수 추가 기능

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되는가?

기본적으로 앱 거버넌스는 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. 자세한 내용은 [앱 거버넌스를 사용한 Microsoft 365](/microsoft-365/compliance/app-governance-manage-app-governance) 및 [시작 앱 거버넌스](/microsoft-365/compliance/app-governance-get-started)를 참조하세요.

### <a name="is-it-a-requirement-for-the-apps-in-the-tenant-to-be-registered-with-azure-active-director-to-be-viewable-by-app-governance"></a>앱 거버넌스에서 볼 수 있도록 테넌트 내의 앱을 Azure Active Director에 등록해야 하는 요구 사항인가요?

예. 앱은 Azure AD 등록해야 하며 OAuth 2.0을 사용하도록 설정해야 합니다. 다른 ID 관리 시스템은 현재 지원되지 않습니다. 앱 거버넌스 추가 기능에서는 Microsoft Graph API 사용하는 Microsoft 365 OAuth 앱의 동작 및 상태를 모니터링합니다. 모든 Microsoft 365 E5/A5 라이선스에는 Azure AD 있습니다.

## <a name="microsoft-defender-for-endpoint"></a>엔드포인트용 Microsoft Defender

엔드포인트용 Microsoft Defender 다음을 포함하는 엔드포인트 보안 솔루션입니다.

- 위험 기반 취약성 관리 및 평가
- 공격 표면 감소 기능
- 동작 기반 및 클라우드 기반 차세대 보호
- 엔드포인트 검색 및 응답(EDR)
- 자동 조사 및 수정
- 관리되는 헌팅 서비스

자세한 내용은 [엔드포인트용 Microsoft Defender](/microsoft-365/security/defender-endpoint/microsoft-defender-endpoint) 참조하세요.

### <a name="which-licenses-provide-the-rights-for-users-to-benefit-from-the-service"></a>사용자가 서비스의 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇인가요?

**엔드포인트용 Microsoft Defender 플랜 1(P1)**

엔드포인트용 Microsoft Defender P1은 상용 및 교육 고객을 위한 독립 실행형 사용자 구독 라이선스로 사용할 수 있습니다. 또한 Microsoft 365 E3/A3의 일부로 포함됩니다.

**엔드포인트용 Microsoft Defender 플랜 2(P2)**

이전에 엔드포인트용 Microsoft Defender 호출된 엔드포인트용 Microsoft Defender P2는 독립 실행형 라이선스 및 다음 계획의 일부로 사용할 수 있습니다.

- Windows 11 Enterprise E5/A5
- Windows 10 Enterprise E5/A5
- Microsoft 365 E5/A5/G5(Windows 10 또는 Windows 11 Enterprise E5 포함)
- Microsoft 365 E5/A5/G5/F5 보안
- Microsoft 365 F5 보안 &amp; 준수

**엔드포인트용 Microsoft Defender Server**

서버 보안을 위해 Hero 제품은 클라우드용 Defender. 서버 및 클라우드 보호에 가장 적합한 기능을 갖추고 있으며, 2022년 4월 현재 Microsoft Defender for Servers 계획 2(계획 2는 원래 서버용 Microsoft Defender)와 함께 서버용 Microsoft Defender 계획 1을 도입했습니다. 자세한 내용은 [서버용 Microsoft Defender를 참조하세요. 이점 및 기능 | Microsoft Docs](/azure/defender-for-cloud/defender-for-servers-introduction).

엔드포인트용 Microsoft Defender 서버 사용 약관의 경우 [제품 약관](https://www.microsoft.com/licensing/terms/en-US/productoffering/MicrosoftDefenderforEndpointServer/EAEAS)의 정보를 검토하세요.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 이 서비스를 통해 어떻게 혜택을 받을 수 있나요?

**엔드포인트용 Microsoft Defender 플랜 1**

엔드포인트용 Microsoft Defender P1은 차세대 맬웨어 방지, 공격 표면 감소 규칙, 디바이스 제어, 엔드포인트 방화벽, 네트워크 보호 등과 같은 핵심 엔드포인트 보호 기능을 제공합니다. 자세한 내용은 [엔드포인트용 Microsoft Defender 플랜 1 및 플랜 2](/microsoft-365/security/defender-endpoint/defender-endpoint-plan-1-2)를 참조하세요.

**엔드포인트용 Microsoft Defender 플랜 2**

엔드포인트용 Microsoft Defender P2는 엔드포인트 감지 및 응답, 자동화된 조사 및 수정과 같은 추가 기능을 사용하여 엔드포인트용 Microsoft Defender P1의 모든 기능을 포함하여 포괄적인 엔드포인트 보호 기능을 제공합니다. 위협 및 취약성 관리, 위협 인텔리전스, 샌드박스 및 Microsoft 위협 전문가 자세한 내용은 [엔드포인트용 Microsoft Defender 설명서를 참조하세요](/microsoft-365/security/defender-endpoint).

**엔드포인트용 Microsoft Defender Server**

서버용 Microsoft Defender는 엔드포인트용 Microsoft Defender P2와 같은 기능으로 Windows 및 Linux 서버를 보호합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되는가?

기본적으로 엔드포인트용 Microsoft Defender 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. 배포에 대한 자세한 내용은 배포  [단계를 참조하세요](/microsoft-365/security/defender-endpoint/deployment-phases).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스가 부여된 테넌트 사용자에게만 서비스를 적용하려면 어떻게 해야 할까요?

엔드포인트용 Microsoft Defender 관리자는 RBAC(역할 기반 액세스 제어)를 사용하여 보안 운영 팀 내에서 역할 및 그룹을 만들어 Microsoft Defender 보안 센터 대한 적절한 액세스 권한을 부여할 수 있습니다. 자세한 내용은  [역할 기반 액세스 제어를 사용하여 포털 액세스를](/microsoft-365/security/defender-endpoint/rbac) 참조하세요.

## <a name="microsoft-defender-for-identity"></a>Microsoft Defender for Identity

Microsoft Defender for Identity(이전의 Azure Advanced Threat Protection)는 여러 유형의 고급 대상 사이버 공격 및 내부자 위협으로부터 엔터프라이즈 하이브리드 환경을 보호하는 데 도움이 되는 클라우드 서비스입니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 이 서비스를 통해 어떻게 혜택을 받을 수 있나요?

SecOp 분석가 및 보안 전문가는 고급 위협, 손상된 ID 및 악의적인 내부자 작업을 탐지하고 조사하는 Microsoft Defender for Identity 기능을 활용합니다. 최종 사용자는 Microsoft Defender for Identity 데이터를 모니터링하여 이점을 얻을 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스의 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇인가요?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 보안, Microsoft F5 보안 & 규정 준수 및 사용자를 위한 Microsoft Defender for Identity 혜택을 제공할 수 있는 권한을 제공합니다. Microsoft Defender for Identity.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되는가?

기본적으로 Microsoft Defender for Identity 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다.  Microsoft Defender for Identity 구성하는 방법에 대한 자세한 내용은 [Microsoft Defender for Identity 인스턴스 만들기를 참조하세요](/defender-for-identity/install-step1).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스가 부여된 테넌트 사용자에게만 서비스를 적용하려면 어떻게 해야 할까요?

Microsoft Defender for Identity 서비스는 현재 특정 사용자에 대한 기능을 제한할 수 없습니다. 혜택을 주려는 모든 사용자에게 라이선스를 부여해야 합니다. 한 사용자가 Active Directory에 여러 계정을 가질 수 있는 시나리오(예: 다른 도메인/포리스트에 대한 다른 관리 계정)에서는 이 한 사람에 대해 하나의 라이선스만 있어야 합니다.

마찬가지로, 서비스 계정 또는 자동화를 용이하게 하는 계정에 대한 요구 사항은 없습니다. 사용자만 라이선스를 받아야 합니다.

## <a name="microsoft-defender-for-office-365"></a>Office 365용 Microsoft Defender

Office 365용 Microsoft Defender(이전의 Office 365 Advanced Threat Protection)은 피싱 및 제로 데이 맬웨어와 같은 정교한 공격으로부터 조직을 보호하는 데 도움이 됩니다. 또한 Office 365용 Microsoft Defender 잠재적 위협을 식별하고, 우선 순위를 지정하고, 권장 사항을 제공하는 데 도움이 되도록 광범위한 데이터의 신호를 상호 연결하여 실행 가능한 인사이트를 제공합니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 이 서비스를 통해 어떻게 혜택을 받을 수 있나요?

Office 365용 Microsoft Defender 피싱 및 제로 데이 맬웨어와 같은 정교한 공격으로부터 사용자를 보호합니다. 계획 1 및 계획 2에서 제공되는 서비스의 전체 목록은 [Office 365용 Microsoft Defender](/microsoft-365/security/office-365-security/office-365-atp) 참조하세요.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스의 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇인가요? 

Office 365용 Microsoft Defender 계획 1 및 2, Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 보안, Microsoft 365 F5 보안 & 규정 준수 및 Microsoft 365 Business Premium 사용자가 Office 365용 Microsoft Defender 혜택을 누릴 수 있는 권한을 제공합니다.

이 빠른 참조는 각 Office 365용 Microsoft Defender 구독에 제공되는 기능을 이해하는 데 도움이 됩니다. 이 빠른 참조가 EOP 기능에 대한 지식과 결합될 경우, 비즈니스 의사 결정자가 자신의 요구에 가장 적합한 Office 365용 Microsoft Defender를 결정하는 데 도움이 될 수 있습니다.

#### <a name="microsoft-defender-for-office-365-plan-1-vs-plan-2-cheat-sheet"></a>Office 365용 Microsoft Defender 플랜 1과 플랜 2 치트 시트 비교

| Office 365용 Defender 플랜 1 | Office 365용 Defender 플랜 2 |
|---------|---------|
| 구성, 보호 및 검색 기능: <ul><li> 안전한 첨부 파일 </li><li> 안전한 링크 </li><li> SharePoint, OneDrive 및 Microsoft Teams를 위한 안전한 첨부 파일 </li><li> Office 365용 Defender의 피싱 방지 보호 기능 </li><li> 실시간 탐지 </li></ul> | Office 365용 Defender 플랜 1 기능 </br> --- 추가 --- </br> 자동화, 조사, 수정 및 교육 기능: <ul><li> 위협 추적기 </li><li> 위협 탐색기 </li><li> 자동화된 조사 및 응답 </li><li> 공격 시뮬레이션 교육 </li></ul> |

자세한 내용은 [Office 365용 Microsoft Defender 및 Exchange Online Protection 포함한 Office 365 보안 - Office 365 | Microsoft Docs](/microsoft-365/security/office-365-security/overview).

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되는가?

기본적으로 Office 365용 Microsoft Defender 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. 사용이 허가된 사용자에 대한 Office 365용 Microsoft Defender 정책을 구성하는 방법에 대한 자세한 내용은 [Office 365용 Microsoft Defender](/microsoft-365/security/office-365-security/office-365-atp) 참조하세요.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스가 부여된 테넌트 사용자에게만 서비스를 적용하려면 어떻게 해야 할까요?

Office 365용 Microsoft Defender 범위를 지정하려면 금고 링크 및 금고 첨부 파일 배포 정책을 따릅니다.

- 사용이 허가된 사용자에 대한 금고 링크를 구성하는 방법에 대한 자세한 내용은 [Office 365용 Microsoft Defender 금고 링크를](/microsoft-365/security/office-365-security/atp-safe-links) 참조하세요.

- 사용이 허가된 사용자에 대한 금고 첨부 파일 구성에 대한 자세한 내용은 [Office 365용 Microsoft Defender 금고 첨부 파일을](/microsoft-365/security/office-365-security/atp-safe-attachments) 참조하세요.

## <a name="microsoft-graph-apis-for-teams-data-loss-prevention-dlp-and-for-teams-export"></a>Teams DLP(데이터 손실 방지) 및 Teams 내보내기용 Microsoft Graph API

이러한 API를 통해 개발자는 거의 실시간으로 메시지를 Microsoft Teams "수신 대기"하거나 1:1/그룹 채팅 또는 Teams 채널에서 팀 메시지를 내보낼 수 있는 보안 및 규정 준수 앱을 빌드할 수 있습니다. 이러한 API를 사용하면 고객과 ISV 모두에서 DLP 및 기타 Information Protection 및 거버넌스 시나리오를 사용할 수 있습니다. 또한 Microsoft Graph Patch API를 사용하면 Teams 메시지에 DLP 작업을 적용할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 이 서비스를 통해 어떻게 혜택을 받을 수 있나요?

[DLP(데이터 손실 방지)](/microsoft-365/compliance/dlp-microsoft-teams) 기능은 특히 조직이 원격 작업으로 전환함에 따라 Microsoft Teams 널리 사용됩니다. 조직에 DLP가 있는 경우 이제 사용자가 Microsoft Teams 채널 또는 채팅 세션에서 중요한 정보를 공유하지 못하도록 하는 정책을 정의할 수 있습니다.

정보 보호 및 거버넌스 기능은 특히 조직이 원격 작업으로 전환함에 따라 Microsoft Teams 널리 사용됩니다. [Teams 내보내기 API](/microsoftteams/export-teams-content)를 사용하면 타사 eDiscovery 또는 규정 준수 보관 애플리케이션으로 데이터를 내보내서 규정 준수 사례를 충족할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스의 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇인가요?

- Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/F5/G5 준수
- Microsoft 365 E5/A5/G5 Information Protection 및 거버넌스
- F5 보안 & 규정 준수 Microsoft 365

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되는가?

API 액세스는 테넌트 수준에서 구성됩니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스가 부여된 테넌트 사용자에게만 서비스를 적용하려면 어떻게 해야 할까요?

Teams DLP 및 Teams 내보내기용 Microsoft Graph API는 테넌트 수준 값을 제공합니다. 이 서비스를 활용하려는 모든 사용자는 라이선스가 있어야 합니다. 추가 값으로, 라이선스가 부여된 사용자당 시드된 용량을 추가하고, 매월 계산되고, 테넌트 수준에서 집계됩니다. 시드된 용량을 초과하는 사용량의 경우 앱 소유자는 API 사용량에 대해 요금이 청구됩니다.

시드된 용량 및 소비 요금에 대한 자세한 내용은 [채팅 메시지에 액세스하기 위한 Graph 요구 사항을](/graph/teams-licenses) 참조하세요.

## <a name="microsoft-priva"></a>Microsoft Priva

[Microsoft Priva](https://aka.ms/privacymanagementdocs) 는 데이터 비장, 데이터 전송 및 데이터 과잉 공유와 같은 개인 정보 보호 위험을 사전에 식별하고 보호하고, 정보 근로자에게 스마트 데이터 처리 결정을 내릴 수 있도록 하고, 주체 요청을 대규모로 자동화 및 관리하여 개인 데이터를 보호하고 개인 정보 보호 복원 작업 공간을 구축할 수 있도록 지원합니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스의 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇인가요?

Priva는 Office 365 A1/E1/A3/E3/A5/E5 및 Microsoft 365 A3/E3/A5/E5 구독이 있는 조직에 추가로 제공됩니다. 

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 이 서비스를 통해 어떻게 혜택을 받을 수 있나요?

사용자는 조직에서 자신의 환경에서 개인 데이터에 대한 가시성을 확보하고, 개인 정보 보호 위험을 사전에 식별 및 보호하고, 주체 권한 요청(일반적으로 '데이터 주체 요청'이라고 함)을 대규모로 관리할 수 있는 기능을 활용합니다.

### <a name="how-can-customers-access-the-service"></a>고객은 어떻게 서비스에 액세스할 수 있나요?

Priva 솔루션은 Microsoft Purview 규정 준수 포털에 기본 제공되며 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. 서비스를 활용하고 보호하려는 모든 사용자에 대해 라이선스를 획득하는 것이 좋습니다.

고객은 조직의 필요에 따라 다음 라이선스를 구매할 수 있습니다.

**개인 정보 관리 – 위험은 Priva 개인 정보 보호 위험 관리의 라이선스 이름입니다.** 이 서비스를 통해 조직은 다음을 수행할 수 있습니다.

- Microsoft 365 환경(Microsoft Exchange Online, SharePoint, 비즈니스용 OneDrive 및 Teams)의 개인 데이터와 관련 위험에 대한 가시성을 얻습니다.
- 데이터 최소화, 데이터 과다 노출 및 데이터 전송을 비롯한 기본 개인 정보 보호 정책 템플릿을 활용하거나 고유한 조직 요구 사항에 맞게 사용자 지정합니다.
- 개인 정보 보호 위험을 완화하기 위한 권장 수정 컨트롤을 받습니다.
- 생산성 제품군 내에서 정보 근로자와 소통하고 행동 변화를 주도합니다.

**개인 정보 관리 – 주체 권한 요청은 Priva 주체 권한 요청의 라이선스 이름입니다.** 이 서비스를 통해 조직은 다음을 수행할 수 있습니다.

- 주체 권한 요청에 대한 응답을 자동화하고 대규모로 관리합니다.
- 기존 비즈니스 프로세스에서 Microsoft Power Automate 템플릿을 사용합니다(Power Automate 적절한 라이선스 필요).
- API에 대한 프로그래밍 방식 액세스를 활용합니다.
- Microsoft Teams 통합을 통해 다른 이해 관계자와 안전하게 협업합니다(Microsoft Teams 적절한 라이선스 필요).</br>

고객은 Priva 주체 권한 요청을 1,10 또는 100 블록으로 구매할 수 있습니다.

개인 정보 보호 위험 관리 및 Priva 주체 권한 요청은 서로 독립적으로 구매할 수 있습니다.

개인 정보 보호 위험 관리 및 Priva 주체 권한 요청을 획득하는 데 필요한 라이선스 필수 구성 요소에 대한 [제품 약관](https://www.microsoft.com/licensing/terms/productoffering/Microsoft365/EAEAS) 을 참조하세요.

## <a name="office-365-cloud-app-security"></a>Office 365 Cloud App Security

OCAS(Office 365 Cloud App Security)는 Microsoft Defender for Cloud Apps 하위 집합으로, 기능이 Office 365 제한되고 타사 클라우드 앱 및 IaaS 서비스에 대한 추가 보안이 없습니다.

OCAS는 조직에서 생산성 클라우드 앱 및 서비스에 대한 가시성을 제공하고, 사이버 위협을 식별하고 대처하기 위한 정교한 분석을 제공하며, Office 365 데이터가 이동하는&mdash; 방식을 제어할 수 있도록 합니다.

기능을 비교하려면 [Microsoft Defender for Cloud Apps Office 365 Cloud App Security 간의 차이점](/cloud-app-security/editions-cloud-app-security-o365)을 참조하세요.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 이 서비스를 통해 어떻게 혜택을 받을 수 있나요?

OCAS는 섀도 IT를 검색하고, Office 365 전반에 걸쳐 위협 방지를 제공하며, 데이터에 액세스할 수 있는 권한이 있는 앱을 제어할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스의 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇인가요?

Office 365 E5/A3/A5/G5는 사용자가 OCAS의 혜택을 누릴 수 있는 권한을 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되는가?

기본적으로 OCAS 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다.

서비스 구성에 대한 자세한 내용은 [클라우드용 Defender 앱에 대한 기본 설정을 참조하세요](/cloud-app-security/general-setup).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스가 부여된 테넌트 사용자에게만 서비스를 적용하려면 어떻게 해야 할까요?

관리자는 OCAS 배포의 범위를 지정하여 특정 앱에 액세스하는 방법을 적용하고 Office 365 Cloud App Security 모니터링되는 사용자 그룹을 제한할 수 있습니다. 자세한 내용은 [범위 지정 배포를](/cloud-app-security/scoped-deployment) 참조하세요.

## <a name="microsoft-purview-customer-lockbox"></a>Microsoft Purview 고객 Lockbox

고객 Lockbox(이전의 Office 365 Customer Lockbox)는 고객에게 서비스 작업에 대한 명시적 액세스 권한을 부여할 수 있는 기능을 제공하여 추가적인 제어 계층을 제공합니다. 명시적 데이터 액세스 권한 부여를 위한 절차가 마련되어 있음을 입증함으로써 고객 Lockbox는 조직이 HIPAA 및 FedRAMP와 같은 특정 규정 준수 의무를 충족하는 데 도움이 될 수도 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 이 서비스를 통해 어떻게 혜택을 받을 수 있나요?

고객 Lockbox는 Microsoft의 어느 누구도 고객의 명시적 승인 없이 서비스 작업을 수행하기 위해 고객 콘텐츠에 액세스할 수 없도록 합니다. 고객 Lockbox는 고객이 콘텐츠에 액세스하는 요청을 승인 워크플로로 가져옵니다. 경우에 따라 Microsoft 엔지니어는 고객 보고 문제를 해결하고 해결하기 위해 지원 프로세스에 참여합니다. 대부분의 경우 문제는 Microsoft가 해당 서비스에 대해 마련한 광범위한 원격 분석 및 디버깅 도구를 통해 해결됩니다. 그러나 Microsoft 엔지니어가 고객 콘텐츠에 액세스하여 근본 원인을 확인하고 문제를 해결해야 하는 경우가 있을 수 있습니다. 고객 Lockbox를 사용하려면 엔지니어가 승인 워크플로의 마지막 단계로 고객의 액세스를 요청해야 합니다. 이렇게 하면 조직에서 이러한 요청을 승인하거나 거부할 수 있는 옵션이 제공되어 Microsoft 엔지니어가 조직의 최종 사용자 데이터에 액세스할 수 있는지 여부를 직접 제어할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스의 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇인가요?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 규정 준수 및 F5 보안 & 규정 준수 및 Microsoft 365 E5/A5/G5 참가자 위험 관리는 사용자가 고객 Lockbox의 혜택을 누릴 수 있는 권한을 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되는가?

관리자는 Microsoft 365 관리 센터 고객 Lockbox를 켤 수 있습니다. 자세한 내용은 [고객 Lockbox](/microsoft-365/compliance/customer-lockbox-requests)를 참조하세요. 고객 Lockbox가 켜져 있으면 Microsoft는 콘텐츠에 액세스하기 전에 조직의 승인을 받아야 합니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스가 부여된 테넌트 사용자에게만 서비스를 적용하려면 어떻게 해야 할까요?

현재 고객 Lockbox 서비스는 특정 사용자로 제한될 수 없습니다. 테넌트 서비스는 현재 특정 사용자에 대한 혜택을 제한할 수 없지만 서비스 혜택을 사용이 허가된 사용자로 제한하기 위해 노력해야 합니다. 이렇게 하면 대상 지정 기능을 사용할 수 있게 되면 잠재적인 서비스 중단을 방지할 수 있습니다.

## <a name="privileged-access-management-in-office-365"></a>Office 365의 권한 있는 액세스 관리

[PAM(권한 있는 액세스 관리)](/microsoft-365/compliance/privileged-access-management-configuration)은 Office 365 권한 있는 관리자 작업에 대한 세부적인 액세스 제어를 제공합니다. PAM을 사용하도록 설정한 후 관리자 권한 및 권한 있는 작업을 완료하려면 사용자는 범위가 높고 시간 제한인 승인 워크플로를 통해 Just-In-Time 액세스를 요청해야 합니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 이 서비스를 통해 어떻게 혜택을 받을 수 있나요?

PAM을 사용하도록 설정하면 조직은 0개의 대기 권한으로 운영할 수 있습니다. 사용자는 데이터에 대한 자유로운 액세스를 제공하는 고정 관리 액세스로 인해 발생하는 취약성에 대한 추가 방어 계층의 이점을 누릴 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스의 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇인가요? 

Office 365 E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5/F5 규정 준수 및 F5 보안 & 규정 준수 및 Microsoft 365 E5/A5 Information Protection 및 거버넌스는 사용자가 PAM의 혜택을 누릴 수 있는 권한을 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되는가?

기본적으로 PAM 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. PAM 정책 구성에 대한 자세한 내용은 권한 있는 [액세스 관리를 사용한 시작](/microsoft-365/compliance/privileged-access-management-configuration) 참조하세요.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스가 부여된 테넌트 사용자에게만 서비스를 적용하려면 어떻게 해야 할까요?

고객은 승인자 그룹 및 액세스 정책을 통해 사용자 단위로 PAM을 관리할 수 있으며, 이 정책은 사용이 허가된 사용자에게 적용할 수 있습니다. 자세한 내용은 [Office 365 권한 있는 액세스 관리를](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751) 참조하세요.

## <a name="microsoft-purview-records-management"></a>Microsoft Purview 레코드 관리

레코드 관리를 사용하면 조직에서 Microsoft 365 및 타사 데이터에서 검색, 분류, 레이블 지정, 보존 및 방어 가능한 삭제 기능을 통해 비즈니스 및 규제 기록 보관 의무를 충족할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스의 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇인가요?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 규정 준수 및 F5 보안 & 규정 준수, Microsoft 365 Information Protection 및 거버넌스 E5/A5/G5 및 Office 365 E5 /A5/G5는 사용자가 레코드 또는 규정 레코드로 항목을 선언하고, 보존 또는 레코드 레이블을 자동으로 적용하고, 처리 검토 프로세스를 실행하는 등 레코드 관리의 혜택을 받을 수 있는 권한을 제공합니다(학습 가능한 분류자를 기반으로 보존 레이블 자동 적용 제외).

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5/F5 규정 준수 및 F5 보안 & 규정 준수 및 Microsoft 365 Information Protection 및 거버넌스는 학습 가능한 분류자를 기반으로 보존 또는 레코드 레이블을 자동으로 적용할 수 있는 권한을 사용자에게 제공합니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 이 서비스를 통해 어떻게 혜택을 받을 수 있나요?

사용자는 콘텐츠를 레코드로 선언하고 정책 정의 및 선언에서 방어 가능한 삭제를 통해 전체 레코드 프로세스를 관리할 수 있어 이점을 누릴 수 있습니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되는가?

기본적으로 레코드 관리 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. 라이선스가 부여된 사용자를 위해 적용할 레코드 관리를 구성하는 방법에 대한 자세한 내용은 [Microsoft Purview 레코드 관리에 대해 자세히 알아보세요](/microsoft-365/compliance/records-management).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스가 부여된 테넌트 사용자에게만 서비스를 적용하려면 어떻게 해야 할까요?

레코드 관리 기능은 특정 위치(팀 사이트, 그룹 사이트 등)에서 라이선스가 있는 사용자에게 적용할 수 있습니다. 라이선스가 부여된 사용자를 위해 적용할 레코드 관리를 구성하는 방법에 대한 자세한 내용은 [Microsoft Purview 레코드 관리에 대해 자세히 알아보세요](/microsoft-365/compliance/records-management).
