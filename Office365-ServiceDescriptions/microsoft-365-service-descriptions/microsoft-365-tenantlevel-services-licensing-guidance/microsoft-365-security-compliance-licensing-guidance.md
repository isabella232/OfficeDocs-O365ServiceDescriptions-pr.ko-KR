---
title: 보안 & 규정 준수를 위한 Microsoft 365 라이선스 지침
ms.author: office365servicedesc
author: pamelaar
manager: gailw
ms.reviewer: v-trscho
audience: ITPro
ms.topic: reference
f1_keywords:
- office-online-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 이 문서에서는 허가되지 않은 액세스로 인한 잠재적인 서비스 중단을 방지하기 위해 Microsoft 365 규정 준수에 대한 라이선스 지침을 제공합니다.
ms.openlocfilehash: d4ddb9c492cccef13c86e450c64a2eb6efe61eaa
ms.sourcegitcommit: adcacf68ac75c4db2229ebf55be9c75aecd3070b
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52546015"
---
# <a name="microsoft-365-licensing-guidance-for-security-amp-compliance"></a>보안 준수를 위한 Microsoft 365 라이선스 지침 &amp;

이 문서의 목적을 위해 테넌트 수준의 서비스는 &mdash; 테넌트의 모든 사용자(독립 실행형 또는 Office 365 또는 Microsoft 365 계획의 일부로)를 구매할 때 &mdash; 테넌트의 모든 사용자에 대해 부분적으로 또는 전체로 활성화되는 온라인 서비스입니다. 일부 무면허 사용자는 기술적으로 서비스에 액세스할 수 있지만 서비스 혜택을 받고자 하는 모든 사용자에게는 라이선스가 필요합니다.

> [!NOTE]
> 일부 테넌트 서비스는 현재 특정 사용자에게 혜택을 제한할 수 없습니다. 서비스 혜택을 라이선스가 부여된 사용자로 제한하기 위한 노력을 기울여야 합니다. 이렇게 하면 타게팅 기능을 사용할 수 있는 경우 조직에 잠재적인 서비스 중단을 방지할 수 있습니다.

규정 준수 기능을 Microsoft 365 활용할 수 있는 라이선스 옵션을 보려면 자세한 Microsoft 365 규정 준수 라이선스 비교를 다운로드하세요. [(PDF)](https://www.microsoft.com/download/details.aspx?id=103010)  |  [(Excel)](https://www.microsoft.com/download/details.aspx?id=103006)

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory ID 보호

Azure Active Directory ID 보호는 조직의 ID에 영향을 미치는 잠재적인 취약점을 감지하고, 조직의 ID와 관련된 의심스러운 작업에 대한 자동화된 응답을 구성하고, 의심스러운 사건을 조사하고 이를 해결하기 위해 적절한 조치를 취할 수 있는 Azure Active Directory Premium P2 계획의 기능입니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 서비스에서 어떻게 이익을 얻을 수 있습니까?

SecOps 분석가와 보안 전문가는 기계 학습 알고리즘을 기반으로 플래그가 지정된 사용자 및 위험 이벤트에 대한 통합 된 견해를 갖는 혜택을 누릴 수 있습니다. 최종 사용자는 위험 기반 조건부 액세스를 통해 제공되는 자동 보호와 취약점에 따라 수행하여 제공되는 향상된 보안의 이점을 누릴 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 활용할 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 보안 및 Azure Active Directory Premium 플랜 2는 사용자가 Azure Active Directory 신원 보호의 혜택을 누릴 수 있는 권리를 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되나요?

기본적으로 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 Azure AD ID 보호 기능이 활성화됩니다. Azure AD ID 보호에 대한 자세한 내용은 [ID 보호란 무엇입니까?](/azure/active-directory/identity-protection/overview-identity-protection)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스를 받은 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

관리자는 암호 재설정 수준을 정의하는 위험 정책을 할당하고 라이선스가 부여된 사용자에 대해서만 액세스하도록 허용하는 위험 정책을 할당하여 Azure AD ID 보호의 범위를 지정할 수 있습니다. Azure AD ID 보호 배포의 범위를 설정하는 방법에 대한 지침은 [위험 정책을 구성하고 활성화하는 방법을](/azure/active-directory/identity-protection/howto-sign-in-risk-policy)참조하십시오.

## <a name="azure-active-directory-identity-governance"></a>Azure Active Directory ID 거버넌스

Azure Active Directory ID 거버넌스를 사용하면 조직의 보안 및 직원 생산성에 대한 필요성과 올바른 프로세스 및 가시성의 균형을 맞출 수 있습니다. 권한 관리, 액세스 검토, 권한 있는 ID 관리 및 사용 약관 정책을 사용하여 적절한 사람이 올바른 리소스에 액세스할 수 있도록 합니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 서비스에서 어떻게 이익을 얻을 수 있습니까?

Azure Active Directory ID 거버넌스는 하나의 액세스 패키지에서 앱, 그룹 및 Microsoft Teams 쉽게 액세스하도록 하여 사용자의 생산성을 향상시킵니다. 관리자는 관리자를 포함하지 않고 승인자로 구성할 수도 있습니다. 액세스 검토의 경우 사용자는 스마트 권장 사항이 있는 그룹의 구성원을 검토하여 정기적으로 조치를 취할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 활용할 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 보안 및 Azure Active Directory Premium 플랜 2는 사용자가 Azure Active Directory ID 거버넌스의 혜택을 누릴 수 있는 권리를 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되나요?

Azure AD ID 거버넌스 기능은 테넌트 수준에서 활성화되지만 사용자당 구현됩니다. Azure AD ID 거버넌스에 대한 자세한 내용은 [Azure AD ID 거버넌스란 무엇입니까?](/azure/active-directory/governance/identity-governance-overview)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스를 받은 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

관리자는 액세스 패키지, 액세스 검토 또는 권한이 있는 ID 관리를 라이선스받은 사용자에 대해서만 할당하여 Azure AD ID 거버넌스의 범위를 지정할 수 있습니다. Azure AD ID 거버넌스 배포의 범위를 조정하는 방법에 대한 지침은 다음을 참조하십시오.

- [Azure AD 권한 관리 라이센스 요구 사항](/azure/active-directory/governance/entitlement-management-overview#license-requirements)
- [Azure AD 액세스 검토 라이센스 요구 사항](/azure/active-directory/governance/access-reviews-overview#license-requirements)
- [Privileged Identity Management 사용 하려면 라이센스 요구 사항](/azure/active-directory/privileged-identity-management/subscription-requirements)

## <a name="microsoft-defender-for-identity"></a>ID용 Microsoft Defender

Microsoft Defender for Identity(이전 Azure Advanced Threat Protection)는 여러 유형의 고급 표적 사이버 공격과 내부자 위협으로부터 엔터프라이즈 하이브리드 환경을 보호하는 데 도움이 되는 클라우드 서비스입니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 서비스에서 어떻게 이익을 얻을 수 있습니까?

SecOp 분석가와 보안 전문가는 Microsoft Defender가 지능형 위협, 손상된 ID 및 악의적인 내부자 행동을 감지하고 조사할 수 있는 기능을 활용할 수 있습니다. 최종 사용자는 Microsoft Defender에서 ID를 모니터링하는 데 이점을 누릴 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 활용할 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 보안, 사용자를 위한 신원 에 대한 Microsoft 수비수는 신원에 대한 Microsoft 수비수로부터 혜택을 받을 수 있는 권리를 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되나요?

기본적으로 테넌트 내의 모든 사용자에 대한 테넌트 수준에서 ID에 대한 Microsoft Defender 기능이 활성화됩니다. Azure ATP 구성에 대한 자세한 내용은 [ID에 대한 Microsoft Defender 만들기 를](/defender-for-identity/install-step1)참조하십시오.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스를 받은 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

ID 서비스에 대한 Microsoft Defender는 현재 특정 사용자에게 기능을 제한할 수 없습니다. 혜택을 원하는 모든 사용자에게 라이선스를 부여해야 합니다.

## <a name="microsoft-defender-for-office-365"></a>Office 365용 Microsoft Defender

Office 365 대한 Microsoft Defender(이전의 Office 365 고급 위협 보호)는 피싱 및 제로 데이 악성 코드와 같은 정교한 공격으로부터 조직을 보호하는 데 도움이 됩니다. 또한 Microsoft Defender for Office 365 광범위한 데이터에서 신호를 상호 연관하여 잠재적 위협을 식별하는 방법에 대한 권장 사항을 식별, 우선 순위를 지정하고 권장 사항을 제공함으로써 실행 가능한 통찰력을 제공합니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 서비스에서 어떻게 이익을 얻을 수 있습니까?

Office 365 대한 Microsoft Defender는 피싱 및 제로 데이 악성 코드와 같은 정교한 공격으로부터 사용자를 보호합니다. 계획 1 및 계획 2에서 제공되는 전체 서비스 목록은 [Office 365 microsoft defender를](/microsoft-365/security/office-365-security/office-365-atp)참조하십시오.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 활용할 수 있는 권한을 제공하는 라이선스는 무엇입니까? 

Office 365 계획 1 및 2, Office 365 E5 /A5 / G5, Microsoft 365 E5 / A5 / G5, Microsoft 365 E5 / A5 / G5 보안, Microsoft 365 Business Premium Office 365 대한 마이크로 소프트 디펜더의 혜택을 받을 수있는 권한을 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되나요?

기본적으로 Office 365 기능에 대한 Microsoft Defender는 테넌트 내의 모든 사용자에 대한 테넌트 수준에서 활성화됩니다. 라이센스가 있는 사용자에 대한 microsoft Defender Office 365 정책을 구성하는 방법에 대한 자세한 내용은 [microsoft defender를 참조하여 Office 365.](/microsoft-365/security/office-365-security/office-365-atp)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스를 받은 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

microsoft defender의 Office 365 범위를 보려면 보안 링크 및 안전한 첨부 파일 배포 정책을 따르십시오.

- 라이센스가 있는 사용자를 위한 안전한 링크 구성에 대한 자세한 내용은 [microsoft 수비수의 안전한 링크를 참조하여 Office 365.](/microsoft-365/security/office-365-security/atp-safe-links)

- 라이선스가 부여된 사용자에 대한 안전한 첨부 파일을 구성하는 방법에 대한 자세한 내용은 [microsoft defender의 Office 365 대한 안전 첨부 파일을](/microsoft-365/security/office-365-security/atp-safe-attachments)참조하십시오.

## <a name="office-365-cloud-app-security"></a>Office 365 Cloud App Security

Office 365 Cloud App Security(OCAS)는 Microsoft Cloud App Security 하위 집합으로, Office 365 제한되며 타사 클라우드 앱 및 IaaS 서비스에 대한 추가 보안이 없는 기능입니다.

OCAS는 조직이 생산성 클라우드 앱 및 서비스에 대한 가시성을 제공하고, 사이버 위협을 식별하고 방지하기 위한 정교한 분석을 제공하며, 데이터가 Office 365 전역으로 이동하는 방식을 제어할 수 있도록 &mdash; 합니다.

피처를 비교하려면 [Microsoft Cloud App Security Office 365 Cloud App Security 간의 차이점을](/cloud-app-security/editions-cloud-app-security-o365)참조하십시오.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 서비스에서 어떻게 이익을 얻을 수 있습니까?

OCAS는 섀도우 IT를 발견하고, Office 365 걸쳐 위협 보호를 제공하며, 데이터에 액세스할 수 있는 권한이 있는 앱을 제어할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 활용할 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Office 365 E5/A3/A5/G5는 사용자가 OCAS의 혜택을 받을 수 있는 권리를 제공합니다.
자세한 내용은 Microsoft Cloud App Security [라이선싱 데이터시트를](https://www.aka.ms/mcaslicensing)참조하십시오.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되나요?

기본적으로 OCAS 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 활성화됩니다.

서비스 구성에 대한 자세한 내용은 [Cloud App Security 기본 설정을](/cloud-app-security/general-setup)참조하십시오.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스를 받은 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

관리자는 OCAS 배포의 범위를 이동하여 특정 앱에 액세스하는 방법을 적용하고 Office 365 Cloud App Security 모니터링하는 사용자 그룹을 제한할 수 있습니다. 자세한 내용은 [범위 배포를](/cloud-app-security/scoped-deployment)참조하십시오.

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

MICROSOFT CLOUD APP SECURITY(MCAS)는 조직이 클라우드 앱 및 서비스에 대한 가시성을 제공하고, 사이버 위협을 식별하고 방지하기 위한 정교한 분석을 제공하고, 데이터가 모든 클라우드 앱에서 이동하는 방식을 제어할 수 있는 CASB(클라우드 액세스 보안 브로커) &mdash; 솔루션입니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 서비스에서 어떻게 이익을 얻을 수 있습니까?

MCAS는 섀도우 IT를 검색 및 평가하고, 타사 및 타사 클라우드 앱에서 위협 보호를 제공하며, 타사 및 타사 클라우드 앱에서 정보를 보호합니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 활용할 수 있는 권한을 제공하는 라이선스는 무엇입니까?

MCAS, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 보안, Microsoft 365 E5/A5/G5 규정 준수, Microsoft 365 정보 보호 및 거버넌스는 사용자가 MCAS로부터 혜택을 받을 수 있는 권리를 제공합니다.

Azure AD P1은 사용자가 MCAS의 검색 기능으로부터 혜택을 받을 수 있는 권한을 제공합니다.

MCAS의 조건부 액세스 앱 제어 기능을 활용하려면 Enterprise Mobility + Security E3/A3/G3, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E3/A3/G3, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 보안에 포함된 Azure Active Directory P1에 대한 라이선스를 받아야 합니다.

자동 클라이언트 측 라벨링을 활용하려면 Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 규정 준수, 정보 보호 및 거버넌스 Microsoft 365 포함된 Azure 정보 보호 P2에 대한 라이선스를 받아야 합니다.

> [!NOTE]
> 자동 서버 측 라벨링에는 Office 365 대한 정보 보호가 필요합니다- Premium `MIP_S_CLP2` `efb0351d-3b08-4503-993d-383af8de41e3` 라이선스(또는). 참고로 [라이선스에 대한 제품 이름 및 서비스 계획 식별자를](/azure/active-directory/enterprise-users/licensing-service-plan-reference)참조하십시오.

자세한 내용은 Microsoft Cloud App Security [라이선싱 데이터시트를](https://www.aka.ms/mcaslicensing)참조하십시오.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되나요?

기본적으로 MCAS 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 활성화됩니다.

라이선스가 부여된 사용자에 대한 Microsoft Cloud App Security 정책 구성에 대한 자세한 내용은 [Microsoft Cloud App Security 개요를 참조하십시오.](/cloud-app-security/what-is-cloud-app-security)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스를 받은 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

관리자는 서비스에서 사용할 수 있는 범위별 배포 기능을 사용하여 MCAS 배포를 라이선스된 사용자에게 범위를 만들 수 있습니다. 자세한 내용은 [범위 배포를](/cloud-app-security/scoped-deployment)참조하십시오.

## <a name="compliance-manager"></a>규정 관리자

규정 준수를 간소화하고 규정 준수 관리자의 위험을 줄이는 데 도움이 됩니다. 규정 준수 관리자는 조직이 규정, 표준, 회사 정책 또는 기타 원하는 제어 프레임워크의 요구 사항을 충족하는 데 도움을 줍니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 서비스에서 어떻게 이익을 얻을 수 있습니까?

다음은 규정 준수 관리자 서비스에서 사용자에게 이점을 제공합니다.

- 복잡한 규정, 표준, 회사 정책 또는 기타 원하는 제어 프레임워크를 간단한 언어로 변환합니다.
- 고유한 규정 준수 요구를 충족하기 위해 방대한 즉시 수행 가능한 평가 및 사용자 지정 평가 라이브러리에 대한 액세스를 제공합니다.
- 권장 개선 조치에 대한 지도 규제 통제
- 규제 요구 사항을 충족하는 솔루션을 구현하는 방법에 대한 단계별 지침 제공
- 사용자가 각 작업과 점수를 연결하여 조직 규정 준수에 가장 큰 영향을 미치는 작업의 우선 순위를 지정할 수 있도록 지원합니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 활용할 수 있는 권한을 제공하는 라이선스는 무엇입니까?

E1 및 E3/G3 라이선스를 보유한 고객은 기본 데이터 보호 기준 평가에만 액세스할 수 있습니다. Office 365 E5/A5 및 Microsoft 365 E5/A5 라이선스(규정 준수, 정보 보호 & 거버넌스 및 eDiscovery 및 감사 SkUs 포함)를 보유한 고객은 데이터 보호 기준, GDPR, NIST 800-53 및 ISO 27001 기본 설정 평가에 액세스할 수 있습니다. Office 365 G5 및 Microsoft 365 G5를 보유한 고객은 데이터 보호 기준, GDPR, NIST 800-53, ISO 27001 및 사이버 보안 성숙모델 인증(CMMC) 레벨 1에서 5레벨까지 액세스할 수 있습니다. 사용자 지정 평가 기능 및 프리미엄 평가는 Office 365 E5/A5/G5 및 Microsoft 365 E5/A5/G5 고객을 위해 예약되어 있습니다. FedRAMP 보통, FedRAMP High 등과 같은 Premium 평가는 2021년 상반기 VL, CSP 및 WebDirect를 통해 E5/A5/G5 라이선스를 보유한 고객에게 구매할 수 있습니다. Microsoft 판매자 또는 Microsoft 파트너에게 연락하여 VL 또는 CSP 채널을 통해 구매하십시오. WebDirect를 통해 구입하려면 [WebDirect를](https://aka.ms/ComplianceManager/WebDirect)참조하십시오.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되나요?

규정 준수 관리자는 기본적으로 테넌트에 대해 프로비전됩니다. 관리자는 사용자 권한을 설정하고 조직의 관리자가 아닌 사용자가 규정 준수 관리자를 사용할 수 있도록 역할을 할당합니다. 자세한 내용은 [규정 준수 관리자로 시작: 사용자 사용 권한 설정 및 역할 할당을](/microsoft-365/compliance/compliance-manager-setup#set-user-permissions-and-assign-roles)참조하십시오.

## <a name="microsoft-defender-for-endpoint"></a>끝점용 Microsoft Defender

엔드포인트에 대한 Microsoft Defender(이전 Microsoft Defender ATP)는 위험 기반 취약성 관리 및 평가를 포함하는 엔드포인트 보안 솔루션입니다. 공격 표면 감소 기능; 행동 기반 및 클라우드 기반 차세대 보호; 엔드포인트 감지 및 응답(EDR); 자동 조사 및 치료; 및 관리 사냥 서비스. 자세한 내용은 엔드포인트 페이지에 [대한 Microsoft Defender를](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) 참조하십시오.

### <a name="which-users-benefit-from-the-service"></a>어떤 사용자가 서비스 혜택을 누릴 수 있습니까?

Windows 10 Enterprise E5, Windows 10 Education A5, Microsoft 365 E5/G5의 라이선스 사용자는 Windows 10 Enterprise E5, Microsoft 365 E5/A5/G5 보안을 포함한 엔드포인트에 대한 Microsoft Defender의 혜택을 누릴 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 서비스에서 어떻게 이익을 얻을 수 있습니까?

SecOps 분석가와 보안 전문가는 Microsoft Defender의 엔드포인트 보안 기능을 통해 예방 보호, 위반 후 탐지, 자동화된 조사 및 고급 위협에 대한 대응을 수행할 수 있습니다. 최종 사용자는 엔드포인트에 대한 Microsoft Defender에서 모니터링하는 악의적인 이벤트를 통해 이점을 누릴 수 있습니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되나요?

기본적으로 엔드포인트 기능에 대한 Microsoft Defender는 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 활성화됩니다. 배포에 대한 자세한 내용은 [배포 단계를](/windows/security/threat-protection/microsoft-defender-atp/deployment-phases)참조하십시오.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스를 받은 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

엔드포인트 관리자를 위한 Microsoft Defender는 RBAC(역할 기반 액세스 제어)를 사용하여 보안 운영 팀 내에서 역할및 그룹을 만들어 Microsoft Defender 보안 센터 적절한 액세스 권한을 부여할 수 있습니다. 자세한 내용은 [역할 기반 액세스 제어를 사용하여 포털 액세스 관리를](/windows/security/threat-protection/microsoft-defender-atp/rbac)참조하십시오.

## <a name="microsoft-365-data-classification-analytics-overview-content-amp-activity-explorer"></a>데이터 분류 분석 Microsoft 365: 콘텐츠 &amp; 활동 탐색기 개요

데이터 분류 분석 기능은 규정 준수 센터 환경 Microsoft 365 내에서 사용할 수 있습니다. 개요는 디지털 콘텐츠의 위치와 가장 일반적인 중요한 정보 유형 및 레이블이 있는 위치를 보여줍니다. Content Explorer는 중요한 데이터의 양과 유형에 대한 가시성을 제공하며 사용자가 레이블 또는 감도 유형별로 필터링하여 중요한 데이터가 저장되는 위치를 자세히 볼 수 있습니다. 활동 탐색기는 라벨 다운그레이드 또는 콘텐츠가 위험에 노출될 수 있는 외부 공유와 같은 중요한 데이터 및 레이블과 관련된 활동을 보여 줍니다.

활동 탐색기는 관리자가 최종 사용자가 사용하는 중요한 정보와 관련된 활동에 대한 가시성을 얻을 수 있도록 단일 유리 창을 제공합니다. 이러한 데이터에는 라벨 활동, DLP(데이터 손실 방지) 로그, 자동 라벨링, 엔드포인트 DLP 등이 포함됩니다.

Content Explorer는 관리자에게 지원되는 Microsoft 365 워크로드 내에 저장된 중요한 문서를 인덱싱하고 저장중인 중요한 정보를 식별할 수 있는 기능을 제공합니다. 또한 Content Explorer는 감도 및 보존 레이블로 분류된 문서를 식별하는 데 도움이 됩니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 서비스에서 어떻게 이익을 얻을 수 있습니까?

정보 보호 및 규정 준수 관리자는 서비스에 액세스하여 이러한 로그 및 인덱싱된 데이터에 액세스하여 중요한 데이터가 저장되는 위치와 이 데이터와 관련이 있고 최종 사용자가 수행하는 활동을 파악할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 활용할 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 규정 준수, Microsoft 365 E5/A5/G5/G5 정보 보호 거버넌스 및 Office 365 E5의 라이선스 사용자는 &amp; 데이터 분류 분석을 Microsoft 365 혜택을 누릴 수 있습니다. 

Microsoft 365 E3/A3/G3 및 Office 365 E3/A3/G3을 사용하면 콘텐츠 탐색기 데이터 집계만 활용할 수 있습니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되나요?

기본적으로 테넌트 내의 모든 사용자에 대한 테넌트 수준에서 개요 콘텐츠 및 활동 탐색기 기능이 활성화됩니다. 라이선스가 부여된 사용자를 위한 데이터 분류 분석 구성에 대한 자세한 내용은 다음을 참조하십시오.

- **콘텐츠 탐색기**: [콘텐츠 탐색기로 시작 - 규정 준수 | Microsoft 365 마이크로 소프트 문서](/microsoft-365/compliance/data-classification-content-explorer).
- **활동 탐색기**: [활동 탐색기로 시작 - 컴플라이언스 | Microsoft 365 마이크로 소프트 문서](/microsoft-365/compliance/data-classification-activity-explorer).
- **데이터 분류 릴리스 노트**: [데이터 분류 릴리스 노트 - Microsoft 365 규정 준수 | 마이크로 소프트 문서](/microsoft-365/compliance/data-classification-pub-preview-relnotes).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스를 받은 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

이 기능은 규정 준수 포털 내에서 솔루션을 적극적으로 사용하는 사용자를 위해 Microsoft 365 범위 조정해야 합니다.

## <a name="information-protection"></a>Information Protection

정보 보호는 조직이 중요한 문서와 이메일을 검색, 분류, 라벨 및 보호하는 데 도움이 됩니다. 관리자는 라벨을 자동으로 적용하기 위해 규칙과 조건을 정의하거나, 사용자가 수동으로 라벨을 적용할 수 있거나, 두 가지 조합을 사용할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 서비스에서 어떻게 이익을 얻을 수 있습니까?

사용자는 콘텐츠에 감도 라벨을 수동으로 적용하거나 콘텐츠를 자동으로 분류함으로써 이점을 누릴 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 활용할 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 E5/A5/G5/E3/A3/A3/F1/F3/비즈니스 Premium, Enterprise Mobility + Security F3/E3/E5, Office 365 E5/A5/E3/A3/F3, AIP 플랜 1, AIP 플랜 2는 사용자가 수동 감도 라벨링을 활용할 수 있는 권리를 제공합니다.

Microsoft 365 E5/A5/G5/E3/A3/F1/F3/비즈니스 Premium, Enterprise Mobility + Security F3/E3/E5, AIP 플랜 1, AIP Plan 2는 사용자가 Power BI 감도 라벨을 적용 및 볼 수 있고 Power BI Power BI Excel, PowerPoint 또는 PDF로 수출될 때 데이터를 보호할 수 있는 권리를 제공합니다. 

> [!NOTE]
> Power BI Microsoft 365 E5/A5/G5에 포함되어 있습니다. 다른 모든 계획에서는 Power BI 별도로 라이선스를 받아야 합니다.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 규정 준수, Microsoft 365 E5/A5/G5 정보 보호 및 거버넌스, Office 365 E5, Enterprise Mobility + Security E5/A5/G5, AIP Plan 2는 사용자가 자동 감도 라벨링을 활용할 수 있는 권리를 제공합니다.

라이선스별 특정 권한의 경우 자세한 Microsoft 365 규정 준수 라이선스 비교를 참조하십시오. [(PDF)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx) Machine Learning(훈련 가능한 분류자)에 근거한 자동 분류에 대한 권한은 포함되지 않습니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되나요?

기본적으로 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 정보 보호 기능이 활성화됩니다. 라이선스가 부여된 사용자에 대한 정책 구성에 대한 자세한 내용은 Azure 권한 관리 활성화를 참조하십시오.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스를 받은 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

AIP 스캐너 기능을 사용하는 경우를 제외하고 특정 그룹또는 사용자 및 레지스트리에 대한 정책을 범위별로 조정하여 허가되지 않은 사용자가 분류 또는 레이블 지정 기능을 실행하지 못하도록 할 수 있습니다. AIP 배포범위에 대한 지침은 [Azure 정보 보호 정책 구성을](/azure/information-protection/configure-policy)참조하십시오.

AIP 스캐너 기능의 경우 Microsoft는 라이선스가 부여되지 않은 사용자에게 파일 분류, 라벨 링 또는 보호 기능을 제공하지 않습니다.

## <a name="information-governance"></a>정보 거버넌스

정보 거버넌스를 통해 조직은 데이터를 검색, 분류, 라벨링 및 관리하여 위험을 관리할 수 있습니다. 정보 거버넌스를 통해 조직은 비즈니스 및 규제 요구 사항을 충족할 뿐만 아니라 Microsoft 365 및 타사 데이터 전반에 걸쳐 보존 및 삭제 기능을 제공하여 공격 표면을 줄일 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 서비스에서 어떻게 이익을 얻을 수 있습니까?

사용자는 특정 정책 및 규정을 유지하기 위해 보존 목적으로 데이터를 분류할 수 있게 됨으로써 이점을 누릴 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 활용할 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 F3/비즈니스 Premium, Office 365 E1/A1/F3 및 독립 실행형 Exchange 플랜은 사용자가 사서함 데이터에 레코드 가 아닌 보존 레이블을 수동으로 적용하여 혜택을 받을 수 있는 권한을 제공합니다.

Microsoft 365 F3/F1/비즈니스 Premium, Office 365 E1/A1/F3, 독립실행형 SharePoint 플랜은 사용자가 SharePoint 또는 OneDrive 파일에 레코드 가 아닌 보존 라벨을 수동으로 적용하여 혜택을 받을 수 있는 권한을 제공합니다. 

Microsoft 365 E5/A5/G5/E3/A3/비즈니스 Premium, Office 365 E5/A5/G5/E3/A3, Exchange 플랜 2, Exchange Online Archiving 기본 조직 전체 또는 위치 전체 사서함 보존 정책 및/또는 사서함 데이터에 비레코드 보존 라벨을 수동으로 적용할 수 있는 권한을 제공합니다.

Microsoft 365 E5/A5/G5/E3/A3, Office 365 E5/A5/G5/E3/A3, SharePoint 플랜 2는 사용자가 기본 SharePoint 또는 OneDrive 보존 정책을 활용하거나 SharePoint 또는 OneDrive 파일에 비레코드 보존 라벨을 수동으로 적용할 수 있는 권리를 제공합니다.

Microsoft 365 E5/A5/G5/E3/A3 및 Office 365 E5/A5/G5/E3/A3는 사용자가 Teams 보존 정책의 혜택을 받을 수 있는 권리를 제공합니다.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 규정 준수, Microsoft 365 정보 보호 및 거버넌스 E5/A5/G5, Office 365 E5/A5는 사용자가 보존 라벨 또는 정책을 자동으로 적용하고, 기본 보존 레이블 또는 정책을 적용하고, 사용자 지정 이벤트를 기반으로 보존 레이블의 보존 기간을 시작하고, 레이블 보존 기간이 끝날 때 수동 처리 검토를 트리거하고, 네이티브 데이터 커넥터를 통해 타사 데이터를 가져오고, 파일을 선언하고, 레이블을 검색하는 등의 혜택을 누릴 수 있는 권한을 제공합니다.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 규정 준수, Microsoft 365 E5/A5/G5/G5 정보 보호 및 거버넌스는 사용자가 열차 사용 가능한 분류기를 기반으로 보존 라벨을 자동으로 적용하는 혜택을 누릴 수 있는 권리를 제공합니다.

라이선스별 특정 권한의 경우 자세한 Microsoft 365 규정 준수 라이선스 비교를 참조하십시오. [(PDF)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되나요?

기본적으로 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 정보 거버넌스 기능이 활성화됩니다. 정보 거버넌스를 구성하여 라이선스가 부여된 사용자에 대한 자동 라벨 지정 및 정책을 적용하는 방법에 대한 자세한 내용은 [Microsoft 365 Microsoft 정보 거버넌스를](/microsoft-365/compliance/manage-information-governance)참조하십시오.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스를 받은 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

정보 거버넌스 기능은 특정 위치(팀 사이트, 그룹 사이트 등)의 라이선스가 부여된 사용자에게 적용할 수 있습니다. 정보 거버넌스를 구성하여 라이선스가 부여된 사용자에 대한 자동 라벨 지정 및 정책을 적용하는 방법에 대한 자세한 내용은 [Microsoft 365 Microsoft 정보 거버넌스를](/microsoft-365/compliance/manage-information-governance)참조하십시오.

## <a name="records-management"></a>레코드 관리

레코드 관리는 조직이 Microsoft 365 및 타사 데이터 에서 발견, 분류, 라벨링, 보존 및 방어 가능한 삭제 기능을 통해 비즈니스 및 규제 기록 보관 의무를 충족하는 데 도움이 됩니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 활용할 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 규정 준수, Microsoft 365 정보 보호 및 거버넌스 E5/A5/G5, Office 365 E5/A5/G5는 사용자가 레코드 또는 규제 기록으로 항목을 선언하고, 보존 또는 레코드 레이블을 자동으로 적용하고, 처분 검토 프로세스를 실행하는 등 레코드 관리의 혜택을 누릴 수 있는 권리를 제공합니다(클래스 적용 기준 자동 적용 제외).

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 규정 준수 및 Microsoft 365 정보 보호 및 거버넌스는 사용자가 교육 가능한 분류기를 기반으로 보존 또는 레코드 레이블을 자동으로 적용하여 혜택을 받을 수 있는 권리를 제공합니다.

라이선스별 특정 권한의 경우 자세한 Microsoft 365 규정 준수 라이선스 비교를 참조하십시오. [(PDF)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 서비스에서 어떻게 이익을 얻을 수 있습니까?

사용자는 콘텐츠를 레코드로 신고하고 정책 정의 및 선언에서 방어 가능한 처리를 통해 전체 레코드 프로세스를 관리할 수 있는 이점을 누릴 수 있습니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되나요?

기본적으로 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 레코드 관리 기능이 활성화됩니다. 라이선스가 부여된 사용자를 신청할 레코드 관리 구성에 대한 자세한 내용은 [Microsoft 365 레코드 관리에 대해 알아보세요.](/microsoft-365/compliance/records-management)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스를 받은 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

레코드 관리 기능은 특정 위치(팀 사이트, 그룹 사이트 등)의 라이선스가 부여된 사용자에게 적용할 수 있습니다. 라이선스가 부여된 사용자를 신청할 레코드 관리 구성에 대한 자세한 내용은 [Microsoft 365 레코드 관리에 대해 알아보세요.](/microsoft-365/compliance/records-management)

## <a name="data-connectors"></a>데이터 커넥터 

Microsoft는 Microsoft 365 규정 준수 센터에서 구성할 수 있는 타사 데이터 커넥터를 제공합니다. Microsoft에서 제공하는 데이터 커넥터 목록은 [타사 데이터 커넥터](/microsoft-365/compliance/archiving-third-party-data#third-party-data-connectors) 테이블을 참조하십시오. 또한 이 표에서는 Microsoft 365 데이터를 가져오고 보관한 후 타사 데이터에 적용할 수 있는 규정 준수 솔루션과 각 커넥터의 단계별 지침에 대한 링크도 요약되어 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 서비스에서 어떻게 이익을 얻을 수 있습니까?

데이터 커넥터를 사용하여 Microsoft 365 타사 데이터를 가져오고 보관하는 주요 이점은 데이터를 가져온 후 데이터에 다양한 Microsoft 365 규정 준수 솔루션을 적용할 수 있다는 것입니다. 이렇게 하면 조직의 Microsoft 이외의 데이터가 조직에 영향을 주는 규정 및 표준을 준수하는지 확인할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 활용할 수 있는 권한을 제공하는 라이선스는 무엇입니까?

다음 라이선스는 사용자가 데이터 커넥터의 혜택을 받을 수 있는 권한을 제공합니다.

- Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5 정보 보호 &amp; 거버넌스
- Microsoft 365 E5/A5/G5 규정 준수
- Microsoft 365 E5/A5/G5 내부자 위험 관리
- Microsoft 365 E5/A5/G5 e디스커버리 및 감사
- Office 365 E5/A5/G5

Microsoft 파트너가 제공하는 Microsoft 365 보안 규정 준수 센터의 데이터 커넥터의 경우 &amp; 조직에서 이러한 커넥터를 배포하려면 파트너와 비즈니스 관계가 필요합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되나요?

커넥터는 보안 규정 준수 &amp; 센터 및 커넥터 카탈로그를 사용하여 구성됩니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스를 받은 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

데이터 커넥터 서비스는 테넌트 수준 값입니다. 이 서비스의 혜택을 누리려는 모든 사용자는 라이선스를 받아야 합니다.

## <a name="microsoft-graph-apis-for-teams-data-loss-prevention-dlp"></a>Teams 데이터 손실 방지(DLP)를 위한 Microsoft Graph API

올해 초 우리는 [Teams 메시지에 대한 Microsoft Graph 변경 알림 API의 공개 미리보기를 발표했다.](https://go.microsoft.com/fwlink/?linkid=2143888) 이 API를 사용하면 개발자가 거의 실시간으로 Microsoft Teams 메시지를 수신 대기하고 고객과 ISV 모두에 대한 DLP 시나리오 구현을 활성화할 수 있는 앱을 빌드할 수 있습니다. 또한 Microsoft Graph 패치 API를 사용하면 Teams 메시지에 DLP 작업을 적용할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 서비스에서 어떻게 이익을 얻을 수 있습니까?

[데이터 손실 방지(DLP)](/microsoft-365/compliance/dlp-microsoft-teams) 기능은 특히 조직이 원격 작업으로 전환함에 따라 Microsoft Teams 널리 사용됩니다. 이제 조직에 DLP가 있는 경우 Microsoft Teams 채널 또는 채팅 세션에서 중요한 정보를 공유하지 못하도록 하는 정책을 정의할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 활용할 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Teams 채팅에서 DLP 보호에 대한 지원을 받으려면 다음 라이선스 중 하나가 필요합니다.

- Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5 규정 준수
- Microsoft 365 E5/A5/G5 정보 보호 및 거버넌스
- Office 365 E5/A5/G5 

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되나요?

API 액세스는 테넌트 수준에서 구성됩니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스를 받은 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

Teams DLP에 대한 Microsoft Graph API는 테넌트 수준 값입니다. 이 서비스의 혜택을 누리려는 모든 사용자는 라이선스를 받아야 합니다.

## <a name="ediscovery"></a>eDiscovery

eDiscovery는 Microsoft 365 시스템에서 내보내기 전에 조사 또는 소송과 관련된 콘텐츠를 식별, 수집, 보존, 축소 및 검토할 수 있도록 기업 내 IT 및 법률 부서에 대한 조사 및 eDiscovery 솔루션을 제공합니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 서비스에서 어떻게 이익을 얻을 수 있습니까?

사용자는 사용자가 사례에 대해 데이터 관리자(문서 또는 전자 파일을 관리 제어하는 사람)로 선택될 때 Advanced eDiscovery 이점을 누릴 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 활용할 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 E5/A5/G5/E3/A3/G3, Office 365 E5/A5/G5/E3/A3/G3/G3는 사용자가 코어 eDiscovery의 혜택을 누릴 수 있는 권리를 제공합니다.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 준수, Microsoft 365 E5/A5/G5 eDiscovery 및 감사, Office 365 E5/A5/G5는 사용자가 Advanced eDiscovery 혜택을 받을 수 있는 권리를 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되나요?

기본적으로 관리자가 보안 규정 준수 센터에서 eDiscovery 권한을 할당할 때 테넌트 내의 모든 사용자에 대해 Advanced eDiscovery 기능이 테넌트 수준에서 &amp; 활성화됩니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스를 받은 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

eDiscovery 관리자는 Advanced eDiscovery 사례에 대한 추가 관리인에 설명된 대로 Advanced eDiscovery 기본 제공 관리자 관리 도구를 사용하여 특정 사용자를 사례에 대한 데이터 관리자로 선택할 [수 있습니다.](/microsoft-365/compliance/add-custodians-to-case)

## <a name="customer-key-for-microsoft-365"></a>Microsoft 365 위한 고객 키

고객 키를 사용하면 조직의 암호화 키를 제어하고 Microsoft 365 사용하여 Microsoft 데이터 센터에서 나머지 데이터를 암호화하도록 구성합니다. 즉, 고객 키를 사용하면 고유한 키를 사용하여 자신에게 속한 암호화 계층을 추가할 수 있습니다. 나머지는 온라인 및 비즈니스용 OneDrive SharePoint 내의 사서함과 파일에 저장된 Exchange Online 및 비즈니스용 Skype 데이터가 포함됩니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 서비스에서 어떻게 이익을 얻을 수 있습니까?

사용자는 자체 조직에서 제공, 제어 및 관리하는 암호화 키를 사용하여 응용 프로그램 계층에서 데이터를 암호화하여 고객 키의 이점을 누릴 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 활용할 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 규정 준수, Microsoft 365 E5/A5/G5 정보 보호 및 거버넌스, Office 365 E5/A5/G5는 사용자가 고객 키의 혜택을 누릴 수 있는 권리를 제공합니다. 고객 키의 모든 이점을 얻으려면 Azure Key Vault에 대한 구독도 있어야 합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되나요?

Microsoft 365 암호화 키에 대한 고객 키는 Exchange Online 및 비즈니스용 Skype 사서함에 저장된 모든 데이터와 온라인, 비즈니스용 OneDrive 및 Teams 파일에 SharePoint 사용할 수 있습니다. 시작하는 방법을 포함하여 고객 키에 대한 자세한 내용은 [고객 키를 사용한 서비스 암호화를](/microsoft-365/compliance/customer-key-overview)참조하십시오.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스를 받은 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

Exchange Online 및 비즈니스용 Skype 경우 고객 키를 사용하여 사서함을 암호화할 수 있습니다. Microsoft 365 위해 고객 키를 사용하려면 먼저 Azure를 설정해야 합니다. 필요한 Azure 리소스를 만들고 구성하기 위해 따라야 하는 단계에 대한 [고객 키 설정](/microsoft-365/compliance/customer-key-set-up) 과 Microsoft 365 고객 키 설정 단계를 참조하십시오. Azure 설정을 완료한 후 조직의 사서함과 파일에 할당할 키와 어떤 정책을 결정합니다. 고객 키 및 Exchange Online, 비즈니스용 Skype, SharePoint 온라인, 비즈니스용 OneDrive 및 Teams 데이터에 대한 콘텐츠에 대한 자세한 내용은 [고객 키를 사용한 서비스 암호화를](/microsoft-365/compliance/customer-key-overview)참조하십시오.

## <a name="office-365-customer-lockbox"></a>Office 365 고객 Lockbox

고객 잠금 장치는 고객에게 서비스 작업에 대한 명시적 액세스 권한을 부여할 수 있는 기능을 제공하여 추가 제어 계층을 제공합니다. 고객 Lockbox는 명시적 데이터 액세스 권한 부여에 대한 절차가 마련되어 있음을 입증함으로써 조직이 HIPAA 및 FedRAMP와 같은 특정 규정 준수 의무를 충족하는 데 도움이 될 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 서비스에서 어떻게 이익을 얻을 수 있습니까?

고객 잠금 상자는 Microsoft의 누구도 고객의 명시적 승인 없이 고객 콘텐츠에 액세스하여 서비스 작업을 수행할 수 없도록 합니다. 고객 잠금 장치는 고객이 콘텐츠에 액세스하는 요청에 대한 승인 워크플로우에 제공합니다. 경우에 따라 Microsoft 엔지니어는 지원 프로세스 중에 고객보고 문제를 해결하고 해결합니다. 대부분의 경우 Microsoft가 서비스에 대해 마련한 광범위한 원격 분석 및 디버깅 도구를 통해 문제가 해결됩니다. 그러나 Microsoft 엔지니어가 고객 콘텐츠에 액세스하여 근본 원인을 파악하고 문제를 해결해야 하는 경우가 있을 수 있습니다. 고객 Lockbox를 사용하려면 엔지니어가 승인 워크플로의 마지막 단계로 고객의 액세스를 요청해야 합니다. 이렇게 하면 조직에서 이러한 요청을 승인하거나 거부할 수 있는 옵션이 제공되므로 Microsoft 엔지니어가 조직의 최종 사용자 데이터에 액세스할 수 있는지 직접 제어할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 활용할 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 컴플라이언스, Microsoft 365 E5/A5/G5 내부자 위험 관리는 사용자가 고객 잠금함으로부터 혜택을 받을 수 있는 권리를 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되나요?

관리자는 Microsoft 365 관리자 센터에서 고객 잠금 상자를 켤 수 있습니다. 자세한 내용은 [Office 365 고객 잠금 상자를](/microsoft-365/compliance/customer-lockbox-requests)참조하십시오. 고객 잠금 상자가 켜져 있으면 Microsoft는 콘텐츠에 액세스하기 전에 조직의 승인을 받아야 합니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스를 받은 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

현재 고객 잠금 상자 서비스는 특정 사용자로 제한될 수 없습니다. 혜택을 원하는 모든 사용자에게 라이선스를 부여해야 합니다.

## <a name="privileged-access-management-in-office-365"></a>Office 365의 권한 있는 액세스 관리

[권한 있는 액세스 관리(PAM)는](/microsoft-365/compliance/privileged-access-management-configuration) Office 365 권한 있는 관리자 작업에 대한 세분화된 액세스 제어를 제공합니다. PAM을 활성화한 후 높은 권한 있는 작업을 완료하려면 범위가 높고 시간 바인딩된 승인 워크플로를 통해 적시에 액세스를 요청해야 합니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 서비스에서 어떻게 이익을 얻을 수 있습니까?

PAM을 사용하도록 설정하면 조직은 스탠딩 권한이 없는 것으로 작동할 수 있습니다. 사용자는 데이터에 대한 자유로운 액세스를 제공하는 관리 액세스 서에서 발생하는 취약점에 대한 추가 된 방어 계층의 이점을 누릴 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 활용할 수 있는 권한을 제공하는 라이선스는 무엇입니까? 

Office 365 E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 규정 준수, Microsoft 365 E5/A5 정보 보호 및 거버넌스는 사용자가 PAM의 혜택을 누릴 수 있는 권리를 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되나요?

기본적으로 PAM 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 활성화됩니다. PAM 정책 구성에 대한 자세한 내용은 [권한 있는 액세스 관리로 시작하세요.](/microsoft-365/compliance/privileged-access-management-configuration)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스를 받은 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

고객은 승인자 그룹 및 액세스 정책을 통해 사용자별로 PAM을 관리할 수 있으며, 이는 라이선스가 부여된 사용자에게 적용할 수 있습니다. 자세한 내용은 [Office 365 권한 있는 액세스 관리를](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751)참조하십시오.

## <a name="double-key-encryption-for-microsoft-365"></a>Microsoft 365 위한 이중 키 암호화 

Microsoft 365 대한 이중 키 암호화를 사용하면 고도로 민감한 데이터를 보호하여 특수 한 요구 사항을 충족하고 암호화 키를 완전히 제어 할 수 있습니다. 이중 키 암호화는 두 개의 키를 사용하여 데이터를 보호하며, 컨트롤의 키 하나와 Microsoft Azure 의해 안전하게 저장된 두 번째 키를 사용합니다. 데이터를 보려면 두 키에 액세스할 수 있어야 합니다. Microsoft는 하나의 키에만 액세스할 수 있으므로 키와 데이터를 Microsoft에서 사용할 수 없으므로 데이터의 개인 정보 보호 및 보안을 완전히 제어할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 서비스에서 어떻게 이익을 얻을 수 있습니까?

사용자는 암호화된 데이터를 클라우드로 마이그레이션할 수 있어 키가 사용자를 제어하는 한 타사 액세스를 방지할 수 있습니다. 사용자는 다른 감도 레이블 보호 콘텐츠와 유사한 이중 키 암호화 된 콘텐츠를 보호하고 사용할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 활용할 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 규정 준수, Microsoft 365 E5/A5/G5 정보 보호 및 거버넌스, Office 365 E5/A5/G5는 사용자가 이중 키 암호화의 혜택을 누릴 수 있는 권리를 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되나요?

이중 키 암호화는 Windows 대한 데스크톱 버전의 Microsoft Office 지원합니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스를 받은 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

Office 365 및/또는 Microsoft 365 조직 내의 데이터에 암호화 키를 할당하려면 이중 키 암호화 배포 지침을 따르십시오.

## <a name="office-365-data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Exchange Online, SharePoint 온라인 및 비즈니스용 OneDrive 대한 데이터 손실 방지 Office 365

Exchange Online, SharePoint 온라인 및 비즈니스용 OneDrive 대한 Office 365 데이터 손실 방지(DLP)를 통해 조직은 이메일 및 파일(Microsoft Teams 파일 저장소에 저장된 파일 포함)에서 중요한 정보를 식별, 모니터링 및 자동으로 보호할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 서비스에서 어떻게 이익을 얻을 수 있습니까?

사용자는 조직의 DLP 정책에서 구성된 바와 같이 중요한 정보를 위해 이메일과 파일을 검사할 때 Exchange Online, SharePoint 온라인 및 비즈니스용 OneDrive DLP의 이점을 누릴 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 활용할 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 E3/A3/비즈니스 Premium, Office 365 E3/A3 및 Office 365 데이터 손실 방지는 사용자가 Exchange Online, SharePoint 온라인 및 비즈니스용 OneDrive 대한 Office 365 DLP의 혜택을 누릴 수 있는 권리를 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되나요?

기본적으로 Exchange Online 이메일, SharePoint 사이트 및 OneDrive 계정은 테넌트 내의 모든 사용자에 대해 이러한 DLP 기능에 대한 *사용 가능한 위치(워크로드)입니다.* DLP 정책 사용에 대한 자세한 내용은 [데이터 손실 방지 개요를](/microsoft-365/compliance/data-loss-prevention-policies)참조하십시오.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스를 받은 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

관리자는 데이터 손실 방지 위치에서 위치(워크로드), 포함된 사용자 및 보안 규정 준수 센터에서 제외된 사용자를 사용자 지정할 수 &amp;   >  **있습니다.**

## <a name="communication-data-loss-prevention-for-teams"></a>Teams 위한 통신 데이터 손실 방지

Teams 위한 통신 DLP를 통해 조직은 금융 정보, 개인 식별 정보, 건강 관련 정보 또는 기타 기밀 정보와 같은 중요한 정보가 포함된 채팅 및 채널 메시지를 차단할 수 있습니다.

### <a name="which-users-benefit-from-the-service"></a>어떤 사용자가 서비스 혜택을 누릴 수 있습니까?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 정보 보호 및 거버넌스의 라이선스 사용자는 Teams 통신 DLP의 혜택을 누릴 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 서비스에서 어떻게 이익을 얻을 수 있습니까?

발신자는 조직의 DLP 정책에 구성된 중요한 정보를 검사하는 나가는 채팅 및 채널 메시지에 중요한 정보를 제공함으로써 이점을 누릴 수 있습니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되나요?

기본적으로 Teams 채팅 및 채널 메시지는 테넌트 내의 모든 사용자에 대해 이러한 DLP 기능에 대한 *사용 가능한 위치(워크로드)입니다.* DLP 정책 사용에 대한 자세한 내용은 [데이터 손실 방지 개요를](/office365/securitycompliance/data-loss-prevention-policies)참조하십시오.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스를 받은 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

관리자는 데이터 손실 방지 위치에서 위치(워크로드), 포함된 사용자 및 보안 규정 준수 센터에서 제외된 사용자를 사용자 지정할 수 &amp;   >  **있습니다.**

## <a name="information-barriers"></a>정보 장벽

정보 장벽은 개인이나 그룹이 서로 통신하지 못하도록 관리자가 구성할 수 있는 정책입니다. 예를 들어 한 부서가 다른 부서와 공유해서는 안 되는 정보를 처리하거나 그룹이 외부 연락처와 통신하지 못하도록 해야 하는 경우에 유용합니다. 정보 장벽 정책은 조회 및 검색을 방지합니다. 즉, 통신하지 말아야 할 사람과 통신을 시도하면 피플 피커에서 해당 사용자를 찾을 수 없습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 서비스에서 어떻게 이익을 얻을 수 있습니까?

사용자는 다른 사람과통신이 제한될 때 정보 장벽의 고급 규정 준수 기능을 활용할 수 있습니다. 정보 장벽 정책을 정의하여 특정 사용자 세그먼트가 각 사용자와 통신하지 못하도록 하거나 특정 세그먼트가 특정 다른 세그먼트와만 통신할 수 있도록 할 수 있습니다. 정보 장벽 정책 정의에 대한 자세한 내용은 [정보 장벽 정의 정책을](/microsoft-365/compliance/information-barriers-policies)참조하십시오. 두 그룹이 서로 통신할 수 없는 시나리오의 경우 두 그룹의 사용자는 서비스의 이점을 누릴 수 있는 라이선스가 필요합니다(아래 예 참조).<br><br>

| 시나리오 | Who 라이센스가 필요합니까? |
|:------|:------|
| 그룹 &nbsp; 1과 그룹 &nbsp; 2의 두 그룹(즉, 그룹 &nbsp; 1 사용자는 그룹 2 사용자와의 통신이 &nbsp; 제한되며 그룹 2 사용자는 그룹 &nbsp; 1 사용자와의 통신이 &nbsp; 제한됩니다) | 그룹 &nbsp; 1과 그룹 &nbsp; 2의 사용자 |

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 활용할 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 준수, Microsoft 365 E5/A5/G5 내부자 위험 관리 및 Office 365 E5/A5/G5는 사용자가 정보 장벽을 활용할 수 있는 권리를 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되나요?

관리자는 보안 규정 준수 센터에서 PowerShell cmdlet을 사용하여 정보 장벽 정책을 만들고 &amp; 관리합니다. 관리자는 정보 장벽 정책을 만들기 위해 글로벌 관리자, Office 365 글로벌 관리자 또는 규정 준수 관리자 역할을 Microsoft 365 Enterprise 할당해야 합니다. 기본적으로 이러한 정책은 테넌트의 모든 사용자에게 적용됩니다. 정보 장벽에 대한 자세한 내용은 [Microsoft Teams 정보 장벽을](/MicrosoftTeams/information-barriers-in-teams)참조하십시오.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스를 받은 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

관리자는 보안 규정 준수 센터에서 위치(워크로드), 포함된 사용자 및 제외된 사용자를 사용자 지정할 수 &amp; 있습니다. 예를 들어 모든 사용자가 Office 365 E3에 대한 라이선스를 부여받았으며 Office 365 Advanced Compliance/E5에 대한 라이선스가 없는 경우 조직에 대한 정보 장벽 정책을 만들 필요가 없습니다. 자세한 내용은 [Microsoft Teams의 정보 장벽](/MicrosoftTeams/information-barriers-in-teams)을 참조하세요.

## <a name="office-365-message-encryption"></a>Office 365 메시지 암호화

OME(Office 365 메시지 암호화)는 Azure RMS(권한 관리)를 기반으로 구축된 서비스로, 대상의 전자 메일 주소(Gmail, Yahoo! Mail, Outlook.com 등)에 상관없이 사용자 조직 내부 또는 외부 사람에게 암호화된 전자 메일을 보낼 수 있습니다.

암호화된 메시지를 보려면 받는 사람이 일회용 암호를 얻어 Microsoft 계정에 로그인하거나 Office 365와 연결된 회사 또는 학교 계정을 사용하여 로그인할 수 있습니다. 받는 사람은 암호화된 회신을 보낼 수도 있습니다. 암호화된 메시지를 보거나 암호화된 회신을 전송하기 위해 구독이 필요하지 않습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 서비스에서 어떻게 이익을 얻을 수 있습니까?

메시지 발신자는 Office 365 메시지 암호화 제공하는 중요한 전자 메일에 대한 추가 제어의 이점을 누릴 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 활용할 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 E3/A3/G3, Office 365 E3/A3/G3, Azure 정보 보호 계획 1은 사용자가 Office 365 메시지 암호화 혜택을 받을 수 있는 권한을 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되나요?

관리자는 **메일 흐름** 규칙에 따라 Exchange 관리 센터에서 Office 365 메시지 암호화 정책을 만들고  >  **관리합니다.** 기본적으로 이러한 규칙은 테넌트의 모든 사용자에게 적용됩니다. 새 Office 365 메시지 암호화 기능 설정에 대한 자세한 내용은 [새 메시지 암호화 기능 설정을](/office365/securitycompliance/set-up-new-message-encryption-capabilities)참조하십시오.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스를 받은 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

관리자는 Office 365 메시지 암호화 대한 메일 흐름 규칙을 라이선스가 부여된 사용자에게만 적용해야 합니다. 메일 흐름 규칙 정의에 대한 자세한 내용은 [메일 흐름 규칙 정의 규칙을 참조하여 전자 메일 메시지를 암호화합니다.](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)

## <a name="office-365-advanced-message-encryption"></a>Office 365 고급 메시지 암호화

Office 365 고급 메시지 암호화 고객이 외부 수신자에 대한 보다 유연한 제어와 암호화된 이메일에 대한 액세스를 필요로 하는 규정 준수 의무를 충족할 수 있도록 지원합니다. 고급 메시지 암호화를 사용하면 관리자는 중요한 정보 유형(예: 개인 식별 정보 또는 재무 또는 건강 아이디)을 감지할 수 있는 자동 정책을 사용하여 조직 외부에서 공유되는 중요한 이메일을 제어하거나 키워드를 사용하여 사용자 지정 이메일 템플릿을 적용하고 보안 웹 포털을 통해 암호화된 이메일에 대한 액세스 만료를 통해 보호를 강화할 수 있습니다. 또한 관리자는 언제든지 액세스를 취소하여 보안 웹 포털을 통해 외부에서 액세스하는 암호화된 전자 메일을 추가로 제어할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 서비스에서 어떻게 이익을 얻을 수 있습니까?

메시지 발신자는 고급 메시지 암호화에서 제공하는 중요한 전자 메일에 대한 추가 제어의 이점을 누릴 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 활용할 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 규정 준수, Microsoft 365 E5/A5/G5 정보 보호 및 거버넌스는 사용자가 고급 메시지 암호화의 혜택을 받을 수 있는 권리를 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되나요?

관리자는 **메일 흐름** 규칙에 따라 Exchange 관리자 센터에서 고급 메시지 암호화 정책을 만들고  >  **관리합니다.** 기본적으로 이러한 규칙은 테넌트의 모든 사용자에게 적용됩니다. 새 메시지 암호화 기능 설정에 대한 자세한 내용은 [새 Office 365 메시지 암호화 기능 설정을](/office365/securitycompliance/set-up-new-message-encryption-capabilities)참조하십시오.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스를 받은 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

관리자는 고급 메시지 암호화에 대한 메일 흐름 규칙을 라이선스가 부여된 사용자에게만 적용해야 합니다. 메일 흐름 규칙 정의에 대한 자세한 내용은 [메일 흐름 규칙 정의를 참조하여 Office 365 이메일 메시지를 암호화합니다.](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)

## <a name="communication-compliance"></a>커뮤니케이션 규정 준수

Microsoft 365 통신 규정 준수는 조직의 부적절한 메시지에 대한 수정 조치를 탐지, 캡처 및 수행할 수 있도록 지원하여 통신 위험을 최소화하는 데 도움이 됩니다. 조직의 내부 및 외부 전자 메일, Microsoft Teams 또는 타사 통신을 캡처하는 특정 정책을 정의할 수 있습니다. 검토자는 조직의 메시지 표준을 준수하는지 확인하기 위해 적절한 수정 조치를 취할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 서비스에서 어떻게 이익을 얻을 수 있습니까?

규정 준수 전문가는 통신 규정 준수 정책에 따라 조직 커뮤니케이션을 모니터링함으로써 서비스의 이점을 누릴 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 활용할 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 규정 준수, Microsoft 365 E5/A5/G5/G5 내부자 위험 관리는 사용자가 통신 규정 준수의 혜택을 누릴 수 있는 권리를 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되나요?

관리자 및 규정 준수 전문가는 Microsoft 365 규정 준수 센터에서 통신 규정 준수 정책을 만듭니다. 이러한 정책은 조직에서 검토할 대상 통신 및 사용자를 정의하고, 통신이 충족해야 하는 사용자 지정 조건을 정의하고, 검토를 수행할 사용자를 지정합니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스를 받은 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

관리자는 통신 규정 준수 정책에 포함할 특정 사용자 또는 그룹을 선택합니다. 그룹을 선택할 때 그룹의 특정 사용자를 선택하여 통신 규정 준수 정책에서 제외할 수도 있습니다. 통신 규정 준수 정책에 대한 자세한 내용은 [Microsoft 365 통신 규정 준수시작을](/microsoft-365/compliance/communication-compliance-configure)참조하십시오.

## <a name="insider-risk-management"></a>내부자 위험 관리

내부자 위험 관리는 조직의 위험한 활동을 탐지, 조사 및 조치를 취함으로써 내부 위험을 최소화하는 데 도움이 되는 Microsoft 365 솔루션입니다.

사용자 지정 정책을 사용하면 필요한 경우 Microsoft Advanced eDiscovery 서비스 확대를 포함하여 조직에서 악의적이고 실수로 위험한 활동을 감지하고 조치를 취할 수 있습니다. 조직의 위험 분석가는 사용자가 조직의 규정 준수 표준을 준수하도록 적절한 조치를 신속하게 수행할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 서비스에서 어떻게 이익을 얻을 수 있습니까?

사용자는 위험을 위해 자신의 활동을 모니터링함으로써 이점을 누릴 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자가 서비스를 활용할 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 규정 준수, Microsoft 365 E5/A5/G5/G5 내부자 위험 관리는 사용자가 내부자 위험 관리의 혜택을 받을 수 있는 권리를 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되나요?

내부자 위험 관리 정책은 Microsoft 365 규정 준수 센터에서 작성하여 사용자에게 할당해야 합니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스를 받은 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

Microsoft 365 규정 준수 센터에서 정책을 만들 때 **사용자 및 그룹 선택** 페이지에서 사용자 또는 그룹을 **선택하여** 라이선스가 부여된 사용자만 선택하거나 모든 사용자가 라이선스를 받은 경우 **모든 사용자 및 메일 지원 그룹** 확인란을 선택할 수 있습니다. 자세한 내용은 [내부자 위험 관리로 시작하기를](/microsoft-365/compliance/insider-risk-management-configure)참조하십시오.

## <a name="conditional-access-policies"></a>조건부 액세스 정책

조건부 액세스는 Azure Active Directory에서 신호를 모으고, 결정을 내리고, 조직 정책을 시행하기 위해 사용하는 도구입니다. 조건부 액세스는 ID 기반 제어의 핵심입니다. 조건부 액세스 정책은 가장 간단하게 다음과 같은 명령문입니다. 사용자가 리소스에 액세스하려는 경우 작업을 완료해야 합니다. 예: 급여 관리자는 급여 응용 프로그램에 액세스하려고 하며 다단계 인증을 수행하여 액세스해야 합니다.

### <a name="which-users-benefit-from-the-service"></a>어떤 사용자가 서비스 혜택을 누릴 수 있습니까?

Enterprise Mobility + Security E3/A3, Microsoft 365 F3/E3/A3/비즈니스 Premium 및 Azure Active Directory Premium 플랜 1의 라이선스 사용자는 조건부 액세스 정책의 혜택을 누릴 수 있습니다. Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft E5/G5 보안 및 Azure Active Directory Premium 플랜 2의 라이선스 사용자는 ID 보호(위험 기반 조건부 액세스 정책)의 혜택을 누릴 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 서비스에서 어떻게 이익을 얻을 수 있습니까?

보안 운영 분석가와 보안 전문가는 사용자에 대한 조직 정책을 시행할 수 있는 기능을 갖추어 기업 콘텐츠에 대한 액세스를 부여하기 전에 특정 기준을 충족하도록 요구함으로써 이점을 누릴 수 있습니다. 최종 사용자는 조직의 자산을 보호하면서 언제 어디서나 자신의 작업에 액세스할 수 있게 함으로써 이점을 누릴 수 있습니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되나요?

기본적으로 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 조건부 액세스 기능이 활성화됩니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스를 받은 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

특히 ID 보호 및 조건부 액세스의 경우 사용자를 그룹에 포함하거나 조건부 액세스 정책에 추가해야 합니다. 조건부 액세스 정책에서는 사용자 및 그룹 조건이 필수입니다. 정책에서 **모든 사용자** 또는 특정 사용자 및 그룹을 선택할 수 있습니다. 적절한 라이선스를 부여받은 사용자와 그룹만 선택해야 합니다. 자세한 내용은 [조건부 액세스: 조건을](/azure/active-directory/conditional-access/conditions)참조하십시오.

## <a name="advanced-audit"></a>고급 감사

Microsoft 365 고급 감사는 사용자 및 관리자 활동에 대한 감사 로그를 1년 보존하고 사용자 지정 감사 로그 보존 정책을 만들어 다른 Microsoft 365 서비스에 대한 감사 로그 보존을 관리할 수 있는 기능을 제공합니다. 또한 Office 365 관리 활동 API에 대한 조사 및 고대역폭 액세스를 위한 중요한 이벤트에 대한 액세스를 제공합니다. 자세한 내용은 [Microsoft 365 고급 감사를](/microsoft-365/compliance/advanced-audit)참조하십시오.

추가 기능 SKU를 사용하여 10년의 보존 기간을 활성화할 수도 있습니다. 추가 기능 SKU는 2021년 초부터 필요합니다.

### <a name="which-users-benefit-from-the-service"></a>어떤 사용자가 서비스 혜택을 누릴 수 있습니까?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 규정 준수, Microsoft 365 E5/A5/G5 eDiscovery 및 감사의 라이선스를 받은 사용자는 고급 감사의 혜택을 누릴 수 있습니다.

고급 감사 와 10 년 감사 로그 보존 추가 기능을 가진 라이센스 사용자는 10 년 감사 로그 보존혜택을 누릴 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자는 서비스에서 어떻게 이익을 얻을 수 있습니까?

Microsoft 365 서비스의 사용자 활동과 관련된 감사 기록을 최대 1년 동안 보관할 수 있으므로 사용자는 고급 감사의 이점을 누릴 수 있습니다. 또한 사용자의 사서함에 있는 항목에 액세스하거나 읽을 때와 같이 고부가가치 감사 이벤트가 기록됩니다. 자세한 내용은 [Microsoft 365 고급 감사를](/microsoft-365/compliance/advanced-audit)참조하십시오.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 프로비전/배포되나요?

기본적으로 고급 감사는 Office 365 Microsoft 365 E5/A5/G5 구독이 있는 모든 조직에 대한 테넌트 수준에서 활성화되며, Azure Active Directory, Exchange 및 SharePoint 활동에 대한 감사 로그를 1년 보존하는 것을 자동으로 제공합니다. 또한 조직은 감사 로그 보존 정책을 사용하여 다른 Microsoft 365 서비스의 활동에 의해 생성된 감사 레코드의 보존 기간을 관리할 수 있습니다. 동일한 보존 정책을 사용하여 10년 감사 로그 보존 기능도 활성화됩니다. 자세한 내용은 [감사 로그 보존 정책 관리](/microsoft-365/compliance/audit-log-retention-policies)를 참조하십시오.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대한 라이선스를 받은 테넌트의 사용자에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

감사 로그의 1년 보존 및 중요한 이벤트의 감사는 적절한 라이선스를 가진 사용자에게만 적용됩니다. 또한 관리자는 감사 로그 보존 정책을 사용하여 특정 사용자의 감사 로그에 대한 보존 기간을 단축지정할 수 있습니다.

감사 로그의 10년 보존은 적절한 추가 기능 라이선스를 가진 사용자에게만 적용됩니다. 추가 기능 SKU는 2021년 초부터 필요합니다.