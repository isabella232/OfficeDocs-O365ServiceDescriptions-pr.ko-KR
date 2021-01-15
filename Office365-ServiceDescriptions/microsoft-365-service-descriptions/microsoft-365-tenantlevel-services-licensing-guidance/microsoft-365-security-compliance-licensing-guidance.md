---
title: 보안 및 규정 준수를 위한 Microsoft 365 & 지침
ms.author: office365servicedesc
author: pamelaar
ms.reviewer: v-trscho
audience: ITPro
ms.topic: reference
f1_keywords:
- office-online-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 이 문서에서는 허가되지 않은 액세스로 인한 잠재적인 서비스 중단을 방지하기 위해 Microsoft 365 규정 준수에 대한 라이선스 지침을 제공합니다.
ms.openlocfilehash: 0971b241d486180bd406c8472fa1a2dbcb9cb873
ms.sourcegitcommit: 50179fef4616ffa270d7e766d70e9c9f1379d824
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/15/2021
ms.locfileid: "49871141"
---
# <a name="microsoft-365-licensing-guidance-for-security--compliance"></a>보안 및 규정 준수를 위한 Microsoft 365 & 지침

이 문서의 목적을 위해 테넌트 수준 서비스는 테넌트의 모든 사용자(독립 실행형 또는 &mdash; Office 365 또는 Microsoft 365 계획의 일부로)에 대해 구매한 경우 테넌트의 모든 사용자에 대해 부분적으로 또는 전체적으로 활성화되는 온라인 &mdash; 서비스입니다. 기술적으로는 라이선스가 없는 일부 사용자가 서비스에 액세스할 수 있을 수도 있습니다. 그러나 서비스를 이용하려는 모든 사용자에게는 라이선스가 필요합니다.

> [!NOTE]
> 일부 테넌트 서비스는 현재 특정 사용자에 대한 혜택을 제한할 수 없습니다. 사용이 허가된 사용자에 대한 서비스 혜택을 제한하기 위해 노력해야 합니다. 이렇게 하면 대상 지정 기능을 사용할 수 있는 경우 조직에 잠재적인 서비스 중단을 방지할 수 있습니다.

2020년 4월 1일 현재 Microsoft 365 규정 준수 기능을 이용하기 위해 사용자의 라이선스를 라이선스로 설정하는 옵션을 확인하려면 자세한 Microsoft 365 규정 준수 라이선싱 비교를 다운로드하세요. [(PDF)](https://www.microsoft.com/download/details.aspx?id=102403)  |  [(Excel)](https://www.microsoft.com/download/details.aspx?id=102427)

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory ID 보호

Azure Active Directory ID 보호는 조직의 ID에 영향을 주는 잠재적인 취약점을 감지하고, 조직의 ID와 관련된 의심스러운 작업에 대해 자동화된 응답을 구성하고, 의심스러운 인시던트 조사 및 문제 해결을 위한 적절한 조치를 취할 수 있는 Azure Active Directory Premium P2 계획의 기능입니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

SecOps 분석가 및 보안 전문가는 기계 학습 알고리즘을 기반으로 플래그가 지정된 사용자 및 위험 이벤트에 대한 통합 보기를 사용할 수 있습니다. 최종 사용자는 위험 기반 조건부 액세스를 통해 제공되는 자동 보호와 취약성에 대해 행동하여 제공되는 향상된 보안을 통해 혜택을 받을 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에게 서비스 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Security 및 Azure Active Directory Premium 요금제 2는 Azure Active Directory ID 보호를 사용할 수 있는 권한을 사용자에게 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 Azure AD ID 보호 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. Azure AD ID 보호에 대한 자세한 내용은 [ID 보호란?](https://docs.microsoft.com/azure/active-directory/identity-protection/overview-identity-protection)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스를 사용이 허가된 테넌트의 사용자에게만 서비스를 적용하는 방법

관리자는 암호 재설정 수준을 정의하는 위험 정책을 할당하고 라이선스가 있는 사용자에 한해 액세스를 허용하여 Azure AD ID 보호 범위를 지정할 수 있습니다. Azure AD ID 보호 배포의 범위를 지정하는 방법에 대한 지침은 위험 정책을 구성하고 사용하도록 [설정하는 방법을 참조하세요.](https://docs.microsoft.com/azure/active-directory/identity-protection/howto-sign-in-risk-policy)

## <a name="azure-active-directory-identity-governance"></a>Azure Active Directory ID 거버넌스

Azure Active Directory ID 거버넌스를 사용하면 조직의 보안 및 직원 생산성에 대한 요구를 올바른 프로세스 및 가시성과 균형을 맞출 수 있습니다. 권한 관리, 액세스 검토, 권한 있는 ID 관리 및 사용 약관 정책을 사용하여 올바른 사용자가 올바른 리소스에 액세스할 수 있도록 합니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

Azure Active Directory ID 거버넌스를 통해 하나의 액세스 패키지에서 앱, 그룹 및 Microsoft Teams에 대한 액세스를 더 쉽게 요청하여 사용자의 생산성을 향상시킵니다. 관리자가 개소하지 않고도 사용자를 승인자로 구성할 수도 있습니다. 액세스 검토의 경우 사용자는 스마트 권장 사항이 있는 그룹의 구성원 자격을 검토하여 정기적으로 작업을 수행 할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에게 서비스 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Security 및 Azure Active Directory Premium 요금제 2는 Azure Active Directory ID 거버넌스를 사용할 수 있는 권한을 사용자에게 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

Azure AD ID 거버넌스 기능은 테넌트 수준에서 사용하도록 설정되지만 사용자당 구현됩니다. Azure AD ID 거버넌스에 대한 자세한 내용은 [Azure AD ID](https://docs.microsoft.com/azure/active-directory/governance/identity-governance-overview) 거버넌스란?

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스를 사용이 허가된 테넌트의 사용자에게만 서비스를 적용하는 방법

관리자는 액세스 패키지, 액세스 검토 또는 사용이 허가된 사용자에 한해 권한 있는 ID 관리를 할당하여 Azure AD ID 거버넌스 범위를 지정할 수 있습니다. Azure AD ID 거버넌스 배포 범위를 지정하는 방법에 대한 지침은 다음을 참조하세요.

- [Azure AD 권리 관리 라이선스 요구 사항](https://docs.microsoft.com/azure/active-directory/governance/entitlement-management-overview#license-requirements)
- [Azure AD 액세스 검토 라이선스 요구 사항](https://docs.microsoft.com/azure/active-directory/governance/access-reviews-overview#license-requirements)
- [Privileged Identity Management를 사용하기 위한 라이선스 요구 사항](https://docs.microsoft.com/azure/active-directory/privileged-identity-management/subscription-requirements)

## <a name="microsoft-defender-for-identity"></a>ID용 Microsoft Defender

Id용 Microsoft Defender(이전의 Azure Advanced Threat Protection)는 여러 유형의 고급 대상 사이버 공격 및 내부자 위협으로부터 엔터프라이즈 하이브리드 환경을 보호하는 데 도움이 되는 클라우드 서비스입니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

SecOp 분석가 및 보안 전문가는 고급 위협, 손상된 ID 및 악의적인 내부자 작업을 감지하고 조사하는 ID용 Microsoft Defender의 기능을 통해 이점을 제공합니다. 최종 사용자는 Microsoft Defender에서 ID를 위해 데이터를 모니터링하여 혜택을 받을 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에게 서비스 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Security 및 사용자를 위한 Microsoft Defender for Users는 ID에 대한 Microsoft Defender의 혜택을 받을 수 있는 권한을 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 Microsoft Defender for Identity 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. Azure ATP 구성에 대한 자세한 내용은 Id에 대한 [Microsoft Defender 인스턴스 만들기를 참조하세요.](https://docs.microsoft.com/defender-for-identity/install-step1)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스를 사용이 허가된 테넌트의 사용자에게만 서비스를 적용하는 방법

Microsoft Defender for Identity Services는 현재 특정 사용자로 기능을 제한할 수 없습니다. 혜택을 제공하려는 모든 사용자에게 라이선스를 부여해야 합니다.

## <a name="microsoft-defender-for-office-365"></a>Office 365용 Microsoft Defender

Office 365용 Microsoft Defender(이전의 Office 365 Advanced Threat Protection)는 피싱 및 제로 데이 맬웨어와 같은 정교한 공격으로부터 조직을 보호하는 데 도움이 됩니다. 또한 Office 365용 Microsoft Defender는 광범위한 데이터의 신호와 상호 관련하여 잠재적인 위협을 식별하고, 우선 순위를 지정하고, 잠재적인 위협을 해결하기 위한 방법에 대한 권장 사항을 제공하는 실행 가능한 인사이트를 제공합니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

Microsoft Defender for Office 365는 피싱 및 제로 데이 맬웨어와 같은 정교한 공격으로부터 사용자를 보호합니다. 계획 1 및 계획 2에 제공된 서비스의 전체 목록은 [Office 365용 Microsoft Defender를 참조하세요.](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp)

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에게 서비스 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까? 

Microsoft Defender for Office 365 요금제 1 및 2, Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 보안 및 Microsoft 365 Business Premium은 사용자가 Office 365용 Microsoft Defender의 혜택을 받을 수 있는 권한을 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 Microsoft Defender for Office 365 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. 라이선스가 있는 사용자에 대해 Microsoft Defender for Office 365 정책을 구성하는 데 대한 자세한 내용은 [Office 365용 Microsoft Defender를 참조하세요.](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp)


### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스를 사용이 허가된 테넌트의 사용자에게만 서비스를 적용하는 방법

Office 365용 Microsoft Defender의 범위를 지정하기 위해 안전한 링크 및 안전한 첨부 파일 배포 정책을 따르는 것이 좋습니다.

- 사용이 허가된 사용자에 대해 안전한 링크를 구성하는 데 대한 자세한 내용은 [Office 365용 Microsoft Defender의](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links)안전한 링크를 참조하세요.

- 사용이 허가된 사용자에 대해 안전한 첨부 파일을 구성하는 데 대한 자세한 내용은 [Microsoft Defender for Office 365의](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments)안전 첨부 파일을 참조하세요.

## <a name="office-365-cloud-app-security"></a>Office 365 Cloud App Security

Office 365 Cloud App Security(OCAS)는 Microsoft Cloud App Security의 하위 집합으로, Office 365로 제한되는 기능으로 타사 클라우드 앱 및 IaaS 서비스에 대한 추가 보안 없이도 사용할 수 있습니다.

OCAS는 조직이 생산성 클라우드 앱 및 서비스에 대한 가시성을 제공하며, 사이버 위협을 식별하고 퇴치하기 위한 정교한 분석을 제공하며, Office 365에서 데이터가 이동하는 방법을 제어할 수 &mdash; 있도록 합니다.

기능을 비교하기 위해 [Microsoft Cloud App Security와 Office 365 Cloud App Security의 차이점을 참조하세요.](https://docs.microsoft.com/cloud-app-security/editions-cloud-app-security-o365)

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

OCAS는 섀도 IT를 검색하고 Office 365에서 위협 방지 기능을 제공하며 데이터에 액세스할 수 있는 권한이 있는 앱을 제어할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에게 서비스 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Office 365 E5/A3/A5/G5는 사용자가 OCAS를 사용할 수 있는 권한을 제공합니다.
자세한 내용은 Microsoft [Cloud App Security Licensing Datasheet을 참조하세요.](https://www.aka.ms/mcaslicensing)

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 OCAS 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다.

서비스 구성에 대한 자세한 내용은 Cloud App Security에 대한 기본 [설치를 참조하세요.](https://docs.microsoft.com/cloud-app-security/general-setup)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스를 사용이 허가된 테넌트의 사용자에게만 서비스를 적용하는 방법

관리자는 OCAS 배포 범위를 지정하여 특정 앱에 액세스하는 방법을 적용하고 Office 365 Cloud App Security에서 모니터링하는 사용자 그룹을 제한할 수 있습니다. 자세한 내용은 [범위가 지정한 배포를 참조하십시오.](https://docs.microsoft.com/cloud-app-security/scoped-deployment)

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

MCAS(Microsoft Cloud App Security)는 조직이 클라우드 앱 및 서비스에 대한 가시성을 제공하고, 사이버 위협을 식별하고 퇴치하는 정교한 분석을 제공하는 CASB(Cloud Access Security Broker) 솔루션으로, 모든 클라우드 앱 전체에서 데이터가 이동하는 방법을 제어할 수 있도록 &mdash; 합니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

MCAS는 섀도 IT를 검색 및 평가하고, 첫 번째 및 타사 클라우드 앱에서 위협 방지를 제공하며, 첫 번째 및 타사 클라우드 앱의 정보를 보호합니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에게 서비스 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

MCAS, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security, Microsoft 365 E5/A5/G5 Compliance 및 Microsoft 365 Information Protection and Governance는 사용자가 MCAS를 혜택을 받을 수 있는 권한을 제공합니다.

Azure AD P1은 사용자가 MCAS의 검색 기능을 사용할 수 있는 권한을 제공합니다.

MCAS의 조건부 액세스 앱 제어 기능을 사용하려면 사용자에게 Enterprise Mobility + Security E3/A3/G3, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E3/A3/G3, Microsoft 365 E5/A5/G5 및 Microsoft 365 E5/A5/G5 보안에 포함된 Azure Active Directory P1에 대한 라이선스도 있어야 합니다.

자동 레이블 지정을 사용하려면 사용자에게 Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 규정 준수 및 Microsoft 365 정보 보호 및 거버넌스에 포함된 Azure Information Protection P2에 대한 라이선스가 있어야 합니다.

자세한 내용은 Microsoft [Cloud App Security Licensing Datasheet을 참조하세요.](https://www.aka.ms/mcaslicensing)

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 MCAS 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다.

라이선스가 있는 사용자에 대해 Microsoft Cloud App Security 정책을 구성하는 데 대한 자세한 내용은 [Microsoft Cloud App Security 개요를 참조하세요.](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스를 사용이 허가된 테넌트의 사용자에게만 서비스를 적용하는 방법

관리자는 서비스에서 사용할 수 있는 범위가 지정한 배포 기능을 사용하여 MCAS 배포 범위를 사용이 허가된 사용자로 제한할 수 있습니다. 자세한 내용은 [범위가 지정한 배포를 참조하십시오.](https://docs.microsoft.com/cloud-app-security/scoped-deployment)

## <a name="compliance-manager"></a>규정 관리자

준수 관리자를 통해 규정 준수를 간소화하고 위험을 줄입니다. 규정 준수 관리자는 조직이 규정, 표준, 회사 정책 또는 기타 원하는 제어 프레임워크의 요구 사항을 충족하도록 지원합니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

준수 관리자 서비스의 사용자에게는 다음과 같은 이점이 있습니다.

- 복잡한 규정, 표준, 회사 정책 또는 기타 원하는 제어 프레임워크를 간단한 언어로 변환
- 고유한 규정 준수 요구를 충족하기 위해 첫 사용 평가 및 사용자 지정 평가의 방대한 라이브러리에 대한 액세스를 제공합니다.
- 규정 컨트롤을 권장 개선 작업에 매핑
- 규정 요구 사항을 충족하기 위해 솔루션을 구현하는 방법에 대한 단계별 지침을 제공합니다.
- 사용자가 각 작업과 점수를 연결하여 조직 규정 준수에 가장 큰 영향을 줄 작업의 우선 순위를 지정하는 데 도움이 됩니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에게 서비스 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

E1 및 E3 라이선스가 있는 고객은 기본 데이터 보호 기준 평가에만 액세스할 수 있습니다. Office 365 E5/A5 및 Microsoft 365 E5/A5 라이선스(규정 준수, Info Protection 거버넌스 및 eDiscovery 및 SKUS 포함)가 있는 고객은 데이터 보호 &amp; 기준, GDPR, NIST 800-53 및 ISO 27001 기본 평가에 액세스할 수 있습니다. 사용자 지정 평가 기능 및 프리미엄 평가는 Office 365 E5/A5 및 Microsoft 365 E5/A5 고객을 위해 예약되어 있습니다. 프리미엄 평가는 2021년 상반기 VL, CSP 및 WebDirect를 통해 구매할 수 있습니다. 

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

준수 관리자는 테넌트에 대해 기본적으로 프로비전됩니다. 관리자는 조직의 관리자가 아닌 사용자가 준수 관리자 사용을 시작할 수 있도록 사용자 권한을 설정하고 역할을 할당합니다. 자세한 내용은 준수 관리자 시작: 사용자 권한 설정 및 [역할 할당을 참조하세요.](https://docs.microsoft.com/microsoft-365/compliance/compliance-manager-setup#set-user-permissions-and-assign-roles)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스를 사용이 허가된 테넌트의 사용자에게만 서비스를 적용하는 방법

준수 관리자에 대한 액세스는 사용자 권한을 설정하고 역할을 할당하여 제어합니다. 자세한 내용은 준수 관리자 시작: 사용자 권한 설정 및 [역할 할당을 참조하세요.](https://docs.microsoft.com/microsoft-365/compliance/compliance-manager-setup#set-user-permissions-and-assign-roles)

## <a name="microsoft-defender-for-endpoint"></a>엔드포인트용 Microsoft Defender

끝점용 Microsoft Defender(이전의 Microsoft Defender ATP)는 위험 기반 취약점 관리 및 평가를 포함하는 끝점 보안 솔루션입니다. 공격 표면 축소 기능; 동작 기반 및 클라우드 기반 차세대 보호 끝점 검색 및 응답(EDR) 자동 조사 및 수정 및 관리되는 헌팅 서비스. 자세한 [내용은 끝점용 Microsoft Defender](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) 페이지를 참조하세요.

### <a name="which-users-benefit-from-the-service"></a>서비스에서 혜택을 받을 수 있는 사용자

Windows 10 Enterprise E5, Windows 10 Education A5, Microsoft 365 E5(M365 E5) 사용이 허가된 사용자는 Windows 10 Enterprise E5, Microsoft 365 E5 보안, Microsoft 365 A5(M365 A5)를 포함하는 Microsoft 365 E5를 통해 끝점용 Microsoft Defender를 사용할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

SecOps 분석가 및 보안 전문가는 끝점용 Microsoft Defender의 끝점 보안 기능을 통해 예방 보호, 위반 후 탐지, 자동화된 조사 및 고급 위협에 대한 대응을 제공합니다. 최종 사용자는 끝점용 Microsoft Defender에서 악성 이벤트를 모니터링하여 이점을 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 Microsoft Defender for Endpoint 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. 배포에 대한 자세한 내용은 배포 [단계를 참조하십시오.](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/deployment-phases)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스를 사용이 허가된 테넌트의 사용자에게만 서비스를 적용하는 방법

끝점용 Microsoft Defender 관리자는 RBAC(역할 기반 액세스 제어)를 사용하여 보안 작업 팀 내에서 역할 및 그룹을 만들어 Microsoft Defender 보안 센터에 대한 적절한 액세스 권한을 부여할 수 있습니다. 자세한 내용은 역할 기반 액세스 [제어를 사용하여 포털 액세스 관리를 참조하세요.](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/rbac)

## <a name="information-protection"></a>정보 보호

정보 보호는 조직에서 중요한 문서와 전자 메일을 검색, 분류, 레이블 지정 및 보호하는 데 도움이 됩니다. 관리자는 레이블을 자동으로 적용하는 규칙 및 조건을 정의하거나, 사용자가 레이블을 수동으로 적용하거나, 두 가지를 조합하여 사용할 수 있습니다. 여기서 사용자에게 레이블 적용에 대한 권장 사항이 부여됩니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

사용자는 콘텐츠에 민감도 레이블을 수동으로 적용하거나 콘텐츠를 자동으로 분류할 수 있는 기능을 통해 이점을 제공합니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에게 서비스 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 E5/A5/E3/A3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, Office 365 E5/A5/E3/F3, AIP 계획 1 및 AIP 계획 2는 사용자가 수동 민감도 레이블 지정을 사용할 수 있는 권한을 제공합니다.

Microsoft 365 E5/A5/E3/A3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, AIP 계획 1 및 AIP 계획 2는 Power BI에서 민감도 레이블을 적용 및 보고 Power BI에서 Excel, PowerPoint 또는 PDF로 내보낼 때 데이터를 보호할 수 있는 권한을 사용자에게 제공합니다. 

> [!NOTE]
> Power BI는 Microsoft 365 E5/A5/G5에 포함되어 있습니다. 다른 모든 계획에서 Power BI는 별도로 사용이 허가되어야 합니다.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 규정 준수, Microsoft 365 정보 보호 및 거버넌스, Office 365 E5, Office 365 Advanced Compliance, Enterprise Mobility + Security E5 및 AIP 계획 2는 사용자가 자동 민감도 레이블 지정을 사용할 수 있는 권한을 제공합니다.

라이선스별 특정 권한은 자세한 Microsoft 365 규정 준수 라이선싱 비교를 참조합니다. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx) 기계 학습(학습 가능한 분류자)에 따라 자동 분류에 대한 권한을 포함하지 않습니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 정보 보호 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. 라이선스가 부여된 사용자에 대한 정책을 구성하는 데 대한 자세한 내용은 Azure 권한 관리 활성화를 참조하세요.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스를 사용이 허가된 테넌트의 사용자에게만 서비스를 적용하는 방법

AIP 스캐너 기능을 사용하는 경우를 제외하고 정책을 특정 그룹 또는 사용자로 지정하여 라이선스가 없는 사용자가 분류 또는 레이블 지정 기능을 실행하지 못하도록 할 수 있습니다. AIP 배포 범위를 지정하는 방법에 대한 지침은 Azure Information Protection 정책 [구성을 참조하세요.](https://docs.microsoft.com/azure/information-protection/configure-policy)

AIP 스캐너 기능의 경우 Microsoft는 라이선스가 없는 사용자에게 파일 분류, 레이블 지정 또는 보호 기능을 제공하지 않습니다.

## <a name="information-governance"></a>정보 거버넌스

정보 거버넌스를 통해 조직은 데이터를 검색, 분류, 레이블 지정 및 관리하여 위험을 관리할 수 있습니다. 정보 거버넌스를 통해 조직은 Microsoft 365 및 타사 데이터 전체에서 보존 및 삭제 기능을 제공하여 비즈니스 및 규정 요구 사항을 충족하고 공격 표면을 줄일 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

사용자는 특정 정책 및 규정을 유지하기 위해 보존을 위해 데이터를 분류할 수 있는 이점이 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에게 서비스 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 F3/Business Premium, Office 365 E1/A1/F3 및 독립 실행형 Exchange 요금제는 사용자가 사서함 데이터에 기록되지 않은 보존 레이블을 수동으로 적용하여 혜택을 받을 수 있는 권한을 제공합니다.

Microsoft 365 F3/F1/Business Premium, Office 365 E1/A1/F3 및 독립 실행형 SharePoint 요금제는 사용자가 SharePoint 또는 OneDrive의 파일에 기록되지 않은 보존 레이블을 수동으로 적용할 수 있는 권한을 제공합니다. 

Microsoft 365 E5/A5/E3/A3/Business Premium, Office 365 E5/A5/E3/A3, Exchange 계획 2 및 Exchange Online Archiving는 사용자가 기본 조직 전체 또는 위치 전체 사서함 보존 정책을 혜택을 받을 수 있는 권한을 제공하고 사서함 데이터에 기록되지 않은 보존 레이블을 수동으로 적용할 수 있는 권한을 제공합니다.

Microsoft 365 E5/A5/E3/A3, Office 365 E5/A5/E3/A3 및 SharePoint 계획 2는 사용자가 기본 SharePoint 또는 OneDrive 보존 정책의 혜택을 받을 수 있는 권한을 제공하고 SharePoint 또는 OneDrive의 파일에 기록되지 않은 보존 레이블을 수동으로 적용할 수 있는 권한을 제공합니다.

Microsoft 365 E5/A5/E3/A3 및 Office 365 E5/A5/E3/A3는 사용자가 Teams 보존 정책의 혜택을 받을 수 있는 권한을 제공합니다.

Microsoft 365 E5/A5, Microsoft 365 E5/A5 규정 준수, Microsoft 365 정보 보호 및 거버넌스, Office 365 E5/A5, Office 365 고급 규정 준수는 보존 레이블 또는 정책을 자동으로 적용하고, 기본 보존 레이블 또는 정책을 적용하고, 사용자 지정 이벤트에 따라 보존 레이블의 보존 기간을 시작하고, 레이블의 보존 기간이 끝나면 수동 처리 검토를 트리거하고, 기본 데이터 커넥터를 통해 타사 데이터를 가져오고, 파일 선언, 레이블이 지정된 콘텐츠 검색 및 레이블 지정 활동 모니터링에서 혜택을 받을 수 있는 권한을 제공합니다.

Microsoft 365 E5/A5, Microsoft 365 E5/A5 규정 준수, Microsoft 365 정보 보호 및 거버넌스는 학습 가능한 분류자를 기반으로 보존 레이블을 자동으로 적용하는 이점을 사용자에게 제공합니다.

라이선스별 특정 권한은 자세한 Microsoft 365 규정 준수 라이선싱 비교를 참조합니다. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 정보 거버넌스 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. 자동 표시 및 라이선스가 있는 사용자에 대한 정책을 적용하기 위한 정보 거버넌스 구성에 대한 자세한 내용은 [Microsoft 365의 Microsoft 정보 거버넌스를 참조하세요.](https://docs.microsoft.com/microsoft-365/compliance/manage-information-governance)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스를 사용이 허가된 테넌트의 사용자에게만 서비스를 적용하는 방법

특정 위치(팀 사이트, 그룹 사이트 등)의 사용이 허가된 사용자에게 정보 거버넌스 기능을 적용할 수 있습니다. 자동 표시 및 라이선스가 있는 사용자에 대한 정책을 적용하기 위한 정보 거버넌스 구성에 대한 자세한 내용은 [Microsoft 365의 Microsoft 정보 거버넌스를 참조하세요.](https://docs.microsoft.com/microsoft-365/compliance/manage-information-governance)

## <a name="records-management"></a>레코드 관리

레코드 관리를 통해 조직은 Microsoft 365 및 타사 데이터에서 검색, 분류, 레이블 지정, 보존 및 방어할 수 있는 삭제 기능을 통해 비즈니스 및 규정 보존 의무를 충족할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에게 서비스 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 규정 준수, Microsoft 365 정보 보호 및 거버넌스, Office 365 E5/A5/G5, Office 365 고급 준수는 레코드 또는 규정 레코드로 항목을 선언하고, 보존 또는 레코드 레이블을 자동으로 적용하고, 처리 검토 프로세스(학습 가능한 분류자를 기반으로 보존 레이블을 자동으로 적용하는 제외)를 포함하여 레코드 관리를 사용할 수 있는 권한을 제공합니다.

Microsoft 365 E5/A5, Microsoft 365 E5/A5 규정 준수 및 Microsoft 365 정보 보호 및 거버넌스는 학습 가능한 분류자에 따라 보존 또는 기록 레이블을 자동으로 적용하는 이점을 사용자에게 제공할 수 있는 권한을 제공합니다.

라이선스별 특정 권한은 자세한 Microsoft 365 규정 준수 라이선싱 비교를 참조합니다. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

사용자는 콘텐츠를 레코드로 선언하고 정책 정의 및 선언에서 방어할 수 있는 폐기 과정을 통해 전체 레코드 프로세스를 관리할 수 있습니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 레코드 관리 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. 사용이 허가된 사용자에 대해 적용할 레코드 관리를 구성하는 데 대한 자세한 내용은 [Microsoft 365의](https://docs.microsoft.com/microsoft-365/compliance/records-management)레코드 관리에 대해 자세히를 참조하십시오.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스를 사용이 허가된 테넌트의 사용자에게만 서비스를 적용하는 방법

레코드 관리 기능은 특정 위치(팀 사이트, 그룹 사이트 등)의 사용이 허가된 사용자에게 적용할 수 있습니다. 사용이 허가된 사용자에 대해 적용할 레코드 관리를 구성하는 데 대한 자세한 내용은 [Microsoft 365의](https://docs.microsoft.com/microsoft-365/compliance/records-management)레코드 관리에 대해 자세히를 참조하십시오.

## <a name="data-connectors"></a>데이터 커넥터 

Microsoft는 Microsoft 365 규정 준수 센터에서 구성할 수 있는 타사 데이터 커넥터를 제공합니다. Microsoft에서 제공하는 데이터 커넥터 목록은 타사 데이터 커넥터 [테이블을 참조하세요.](https://docs.microsoft.com/microsoft-365/compliance/archiving-third-party-data#third-party-data-connectors) 이 표에는 Microsoft 365에서 데이터를 가져와 보관한 후 타사 데이터에 적용할 수 있는 준수 솔루션과 각 커넥터에 대한 단계별 지침에 대한 링크도 요약됩니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

데이터 커넥터를 사용하여 Microsoft 365에서 타사 데이터를 가져오고 보관할 때의 주요 이점은 데이터를 가져온 후 데이터에 다양한 Microsoft 365 규정 준수 솔루션을 적용할 수 있는 것입니다. 이렇게 하면 조직의 비 Microsoft 데이터가 조직에 영향을 주는 규정 및 표준을 준수하는 데 도움이 됩니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에게 서비스 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

다음 라이선스는 사용자가 Data Connectors를 사용할 수 있는 권한을 제공합니다.

- Microsoft 365 E5/A5
- Microsoft 365 E5/A5 정보 보호 및 거버넌스
- Microsoft 365 E5/A5 규정 준수
- Microsoft 365 E5/A5 내부자 위험 관리
- Microsoft 365 E5/A5 eDiscovery 및 감사
- Office 365 E5/A5
- Office 365 Advanced Compliance

Microsoft 파트너가 제공하는 M365 보안 및 & 준수 센터의 데이터 커넥터의 경우 조직에서 해당 커넥터를 배포하려면 먼저 파트너와의 비즈니스 관계가 필요합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

커넥터는 보안 및 준수 센터 & 카탈로그를 사용하여 구성됩니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스를 사용이 허가된 테넌트의 사용자에게만 서비스를 적용하는 방법

Data Connectors 서비스는 테넌트 수준 값입니다. 이 서비스를 이용하려는 모든 사용자는 사용이 허가되어야 합니다.

## <a name="microsoft-graph-apis-for-teams-data-loss-prevention-dlp"></a>Teams DLP(데이터 손실 방지)를 위한 Microsoft Graph API

올해 초 Teams의 메시지에 대한 Microsoft Graph 변경 알림 API의 공개 미리 [보기를 발표했습니다.](https://go.microsoft.com/fwlink/?linkid=2143888) 이 API를 통해 개발자는 거의 실시간으로 Microsoft Teams 메시지를 들을 수 있는 앱을 빌드하고 고객과 ISV 모두에 대해 DLP 시나리오 구현을 사용하도록 설정할 수 있습니다. 또한 Microsoft Graph 패치 API를 사용하면 Teams 메시지에 DLP 작업을 적용할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

[DLP(데이터](https://docs.microsoft.com/microsoft-365/compliance/dlp-microsoft-teams) 손실 방지) 기능은 특히 조직이 원격 작업으로 전환할 때 Microsoft Teams에서 널리 사용됩니다. 조직에 DLP가 있는 경우 이제 사용자가 Microsoft Teams 채널 또는 채팅 세션에서 중요한 정보를 공유하지 못하게 하는 정책을 정의할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에게 서비스 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Teams 채팅에서 DLP 보호를 지원하려면 다음 E5 라이선스 중 하나가 필요합니다.

- Microsoft 365 E5/A5
- Microsoft 365 E5/A5 규정 준수
- Microsoft 365 E5/A5 정보 보호 및 거버넌스
- Office 365 E5/A5 

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

API 액세스는 테넌트 수준에서 구성됩니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스를 사용이 허가된 테넌트의 사용자에게만 서비스를 적용하는 방법

Teams DLP용 Microsoft Graph API는 테넌트 수준 값입니다. 이 서비스를 이용하려는 모든 사용자는 사용이 허가되어야 합니다.

## <a name="ediscovery"></a>eDiscovery

eDiscovery는 Microsoft 365 시스템에서 내보내기 전에 조사 또는 소송과 관련된 콘텐츠를 식별, 수집, 보존, 축소 및 검토하기 위한 조사 및 eDiscovery 솔루션을 기업 내의 IT 및 법률 부서에 제공합니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

사용자가 사례에 대한 데이터 관리자(문서 또는 전자 파일의 관리 제어를 갖는 사람)로 선택된 경우 Advanced eDiscovery의 이점을 누리게 됩니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에게 서비스 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 E5/A5/G5/E3/G3, Office 365 E5/A5/E3/A3/G3 및 Office 365 Advanced Compliance는 사용자가 Core eDiscovery를 사용할 수 있는 권한을 제공합니다.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 규정 준수, Microsoft 365 E5/A5 eDiscovery 및 감사, Office 365 E5/A5/G5 및 Office 365 고급 준수는 고급 eDiscovery의 혜택을 받을 수 있는 권한을 사용자에게 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 Advanced eDiscovery 기능은 관리자가 보안 및 준수 센터에서 eDiscovery 권한을 할당할 때 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 & 사용됩니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스를 사용이 허가된 테넌트의 사용자에게만 서비스를 적용하는 방법

eDiscovery 관리자는 고급 eDiscovery 사례에 대한 관리자 추가에 설명된 바와 같이 Advanced eDiscovery의 기본 제공 관리 도구를 사용하여 특정 사용자를 사례에 대한 데이터 관리자로 선택할 수 [있습니다.](https://docs.microsoft.com/microsoft-365/compliance/add-custodians-to-case)

## <a name="office-365-customer-key"></a>Office 365 고객 키

고객 키를 사용하면 조직의 암호화 키를 제어하고 Office 365를 구성하여 Microsoft 데이터 센터의 미사용 데이터를 암호화할 수 있습니다. 즉, 고객 키를 사용하면 자체 키를 사용하여 자신에 속하는 암호화 계층을 추가할 수 있습니다. 미사용 데이터에는 SharePoint Online 및 비즈니스용 OneDrive 내의 사서함 및 파일에 저장된 Exchange Online 및 비즈니스용 Skype의 데이터가 포함됩니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

사용자는 조직에서 제공, 제어 및 관리하는 암호화 키를 사용하여 응용 프로그램 계층에서 미사용 데이터를 암호화하여 고객 키를 활용합니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에게 서비스 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 E5/A5, Microsoft 365 E5/A5 규정 준수, Microsoft 365 정보 보호 및 거버넌스, Office 365 E5/A5 및 Office 365 고급 규정 준수는 사용자가 고객 키를 혜택을 받을 수 있는 권한을 제공합니다. 고객 키를 모두 사용하려면 Azure Key Vault 구독도 있어야 합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

Exchange Online 및 비즈니스용 Skype 사서함, SharePoint Online, 비즈니스용 OneDrive 및 Teams 파일에 저장된 모든 데이터에 대해 Office 365 고객 키 암호화 키를 사용할 수 있습니다. 시작하는 방법을 포함하여 Office 365 고객 키에 대한 자세한 내용은 고객 키를 사용하여 서비스 [암호화를 참조하세요.](https://docs.microsoft.com/microsoft-365/compliance/customer-key-overview)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스를 사용이 허가된 테넌트의 사용자에게만 서비스를 적용하는 방법

Exchange Online 및 비즈니스용 Skype의 경우 고객 키를 사용하여 사서함을 암호화할 수 있습니다. Office 365에 대한 고객 키를 사용하려면 먼저 Azure를 설정해야 합니다. 필요한 [Azure](https://docs.microsoft.com/microsoft-365/compliance/customer-key-set-up) 리소스를 만들고 구성하기 위해 따라야 하는 단계와 Office 365에서 고객 키를 설정하는 단계는 고객 키 설정을 참조하세요. Azure 설치를 완료한 후 조직의 사서함 및 파일에 할당할 정책 및 키를 결정하십시오. 정책을 할당하지 않는 사서함 및 파일은 Microsoft에서 제어 및 관리하는 암호화 정책을 사용합니다. 고객 키에 대한 자세한 내용은 고객 키를 사용하여 서비스 암호화를 [참조하세요.](https://docs.microsoft.com/microsoft-365/compliance/customer-key-overview)

## <a name="office-365-customer-lockbox"></a>Office 365 고객 Lockbox

고객 Lockbox는 고객에게 서비스 작업에 대한 명시적 액세스 권한을 부여하는 기능을 제공하여 추가적인 제어 계층을 제공합니다. 고객 Lockbox는 명시적 데이터 액세스 권한 부여를 위한 절차가 수락된 것 또한 조직이 HIPAA 및 FEDRAMP와 같은 특정 준수 의무를 충족하는 데 도움이 될 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

고객 Lockbox는 Microsoft의 어느 누구도 고객의 명시적 승인 없이 고객 콘텐츠에 액세스하여 서비스 작업을 수행할 수 있도록 합니다. Customer Lockbox는 고객에게 콘텐츠에 액세스하기 위한 요청에 대한 승인 워크플로를 제공합니다. 경우에 따라 Microsoft 엔지니어는 지원 프로세스 중에 고객이 보고한 문제를 해결하고 해결합니다. 대부분의 경우 문제는 Microsoft가 서비스에 대해 준비한 광범위한 원격 분석 및 디버깅 도구를 통해 해결됩니다. 그러나 Microsoft 엔지니어가 고객 콘텐츠에 액세스하여 근본 원인을 파악하고 문제를 해결해야 하는 경우도 있습니다. 고객 Lockbox를 사용하려면 엔지니어가 승인 워크플로의 최종 단계로 고객의 액세스를 요청해야 합니다. 이를 통해 조직은 Microsoft 엔지니어가 조직의 최종 사용자 데이터에 액세스할 수 있는지 여부를 직접 제어할 수 있도록 이러한 요청을 승인하거나 거부할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에게 서비스 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 규정 준수, Microsoft 365 Insider Risk Management 및 Office 365 Advanced Compliance는 사용자가 고객 Lockbox를 혜택을 받을 수 있는 권한을 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

관리자는 Microsoft 365 관리 센터에서 고객 Lockbox를 켜도 됩니다. 자세한 내용은 [Office 365의 고객 Lockbox를 참조하세요.](https://docs.microsoft.com/microsoft-365/compliance/customer-lockbox-requests) 고객 Lockbox가 켜져 있는 경우 Microsoft는 콘텐츠에 액세스하기 전에 조직의 승인을 얻어야 합니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스를 사용이 허가된 테넌트의 사용자에게만 서비스를 적용하는 방법

현재 고객 Lockbox 서비스는 특정 사용자로 제한될 수 없습니다. 혜택을 제공하려는 모든 사용자에게 라이선스를 부여해야 합니다.

## <a name="privileged-access-management-in-office-365"></a>Office 365의 권한 있는 액세스 관리

[PAM(권한](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-configuration) 있는 액세스 관리)은 Office 365의 권한 있는 관리 작업에 대한 세부적인 액세스 제어를 제공합니다. PAM을 사용하도록 설정한 후 권한 있는 작업을 완료하려면 사용자는 범위가 넓고 시간이 제한적인 승인 워크플로를 통해 적시 액세스를 요청해야 합니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

PAM을 사용하도록 설정하면 조직은 제로 스탬딩 권한으로 운영할 수 있습니다. 사용자는 데이터에 대한 무단 액세스를 제공하는 관리자 액세스로 인하여 증가하는 취약성에 대한 추가 방어 계층을 통해 이점을 받습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에게 서비스 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까? 

Office 365 E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 규정 준수 및 Microsoft 365 E5/A5 정보 보호 및 거버넌스는 사용자가 PAM을 혜택을 받을 수 있는 권한을 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 PAM 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다. PAM 정책 구성에 대한 자세한 내용은 권한 있는 액세스 관리 시작을 [참조하세요.](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-configuration)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스를 사용이 허가된 테넌트의 사용자에게만 서비스를 적용하는 방법

고객은 승인자 그룹 및 액세스 정책을 통해 사용자 기준으로 PAM을 관리할 수 있으며, 이 정책은 라이선스가 있는 사용자에게 적용할 수 있습니다. 자세한 내용은 [Office 365의 Privileged 액세스 관리를 참조하세요.](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751)

## <a name="double-key-encryption-for-microsoft-365"></a>Microsoft 365용 이중 키 암호화 

Microsoft 365의 이중 키 암호화를 사용하면 특수한 요구 사항을 충족하고 암호화 키에 대한 모든 제어를 유지 관리하기 위해 매우 중요한 데이터를 보호할 수 있습니다. 이중 키 암호화는 두 개의 키를 사용하여 데이터를 보호하며 컨트롤에 키 한 개와 Microsoft Azure에 의해 안전하게 저장된 두 번째 키로 데이터를 보호합니다. 데이터를 보기 위해 두 키에 모두 액세스할 수 있어야 합니다. Microsoft는 하나의 키에만 액세스할 수 있으며 키와 데이터도 Microsoft에서 사용할 수 없게 하여 데이터의 개인 정보 및 보안을 완전하게 제어할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

사용자는 암호화된 데이터를 클라우드로 마이그레이션할 수 있게 하여 키가 사용자 제어에 남아 있는 한 타사 액세스를 차단하여 이중 키 암호화를 사용할 수 있습니다. 사용자는 다른 민감도 레이블로 보호된 콘텐츠와 유사한 이중 키 암호화 콘텐츠를 보호하고 사용할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에게 서비스 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 E5/A5, Microsoft 365 E5/A5 규정 준수, Microsoft 365 정보 보호 및 거버넌스, Office 365 E5/A5 및 Office 365 고급 규정 준수는 사용자가 이중 키 암호화를 사용할 수 있는 권한을 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

이중 키 암호화는 Windows용 데스크톱 Microsoft Office 지원됩니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스를 사용이 허가된 테넌트의 사용자에게만 서비스를 적용하는 방법

라이선스가 있는 사용자를 위해 Office 365 및/또는 Microsoft 365 조직 내의 데이터에 암호화 키를 할당하기 위해 이중 키 암호화 배포 지침을 따릅니다.

## <a name="office-365-data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Exchange Online, SharePoint Online 및 비즈니스용 OneDrive에 대한 Office 365 데이터 손실 방지

Exchange Online, SharePoint Online 및 비즈니스용 OneDrive에 대한 Office 365 DLP(데이터 손실 방지)를 사용하여 조직은 전자 메일 및 파일(Microsoft Teams 파일 저장소에 저장된 파일 포함)에서 중요한 정보를 식별, 모니터링 및 자동으로 보호할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

조직의 DLP 정책에 구성된 전자 메일 및 파일이 중요한 정보를 검사할 때 사용자는 Exchange Online, SharePoint Online 및 비즈니스용 OneDrive에 대한 DLP를 사용할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에게 서비스 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 E3/A3/Business Premium, Office 365 E3/A3 및 Office 365 데이터 손실 방지는 Exchange Online, SharePoint Online 및 비즈니스용 OneDrive에 대한 Office 365 DLP의 혜택을 받을 수 있는 권한을 사용자에게 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 Exchange Online 전자 메일, SharePoint 사이트 및 OneDrive 계정은 테넌트 *내의* 모든 사용자에 대해 이러한 DLP 기능의 위치(작업)를 사용하도록 설정됩니다. DLP 정책 사용에 대한 자세한 내용은 데이터 손실 방지 [개요를 참조하십시오.](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스를 사용이 허가된 테넌트의 사용자에게만 서비스를 적용하는 방법

관리자는 데이터 손실 방지 위치 아래에서 보안 & 준수 센터에서 위치(작업), 포함된 사용자 및 제외된 사용자를 사용자 지정할 **수**  >  **있습니다.**

## <a name="communication-data-loss-prevention-for-teams"></a>Teams에 대한 통신 데이터 손실 방지

Teams용 통신 DLP를 사용하여 조직은 재무 정보, 개인 식별 정보, 상태 관련 정보 또는 기타 기밀 정보와 같은 중요한 정보를 포함하는 채팅 및 채널 메시지를 차단할 수 있습니다.

### <a name="which-users-benefit-from-the-service"></a>서비스에서 혜택을 받을 수 있는 사용자

Office 365 E5/A5, Microsoft 365 E5/A5, Microsoft 365 정보 보호 및 거버넌스 및 Office 365 고급 규정 준수의 라이선스가 있는 사용자는 Teams용 통신 DLP를 사용할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

보낸 사람이 조직의 DLP 정책에 구성된 중요한 정보를 검사하는 보내는 채팅 및 채널 메시지에 중요한 정보를 제공하면 도움이 됩니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 Teams 채팅 및 채널 메시지는 테넌트 *내의* 모든 사용자에 대해 이러한 DLP 기능에 대해 사용하도록 설정된 위치(작업량)입니다. DLP 정책 사용에 대한 자세한 내용은 데이터 손실 방지 [개요를 참조하십시오.](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스를 사용이 허가된 테넌트의 사용자에게만 서비스를 적용하는 방법

관리자는 데이터 손실 방지 위치 아래에서 보안 & 준수 센터에서 위치(작업), 포함된 사용자 및 제외된 사용자를 사용자 지정할 **수**  >  **있습니다.**

## <a name="information-barriers"></a>정보 장벽

정보 장벽은 관리자가 개인 또는 그룹이 서로 통신하지 못하도록 구성할 수 있는 정책입니다. 예를 들어 한 부서에서 다른 부서와 공유하지 말아야 하는 정보를 처리하거나 그룹이 외부 연락처와 통신하지 못하게 해야 하는 경우 유용합니다. 정보 장벽 정책은 또한 검색 및 검색을 방지합니다. 즉, 통신하지 말아야 하는 다른 사용자와 통신하려고 할 경우 사용자 선택에서 해당 사용자를 찾을 수 없습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

사용자는 다른 사용자와의 통신이 제한될 때 정보 장벽의 고급 규정 준수 기능을 통해 혜택을 받을 수 있습니다. 예를 들면 다음과 같습니다.<br><br>

| 시나리오 | 라이선스가 필요한 사용자 |
|:------|:------|:------|
| 두 그룹(그룹 1 및 그룹 2)이 서로 통신할 수 없습니다( 즉, 그룹 1 사용자는 그룹 2 사용자와 통신할 수 없습니다. 그룹 2 사용자는 그룹 1 사용자와 통신할 수 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 없습니다. | 그룹 1 및 &nbsp; 그룹 &nbsp; 2의 사용자 |

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에게 서비스 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 E5/A5, Microsoft 365 E5/A5 규정 준수, Microsoft 365 내부자 위험 관리, Office 365 E5/A5 및 Office 365 고급 규정 준수는 사용자가 정보 장벽을 혜택을 받을 수 있는 권한을 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

관리자는 보안 및 준수 센터에서 PowerShell cmdlet을 사용하여 정보 장벽 정책을 & 관리합니다. 정보 장벽 정책을 만들 수 있도록 관리자에게 Microsoft 365 Enterprise 전역 관리자, Office 365 전역 관리자 또는 준수 관리자 역할이 할당되어야 합니다. 기본적으로 이러한 정책은 테넌트의 모든 사용자에게 적용됩니다. 정보 장벽에 대한 자세한 내용은 Microsoft Teams의 정보 [장벽을 참조하세요.](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스를 사용이 허가된 테넌트의 사용자에게만 서비스를 적용하는 방법

관리자는 보안 및 준수 센터에서 위치(작업), 포함된 사용자 및 제외된 사용자를 & 수 있습니다. 예를 들어 모든 사용자에게 Office 365 E3 라이선스가 부여된 경우 Office 365 Advanced Compliance/E5에 대한 라이선스가 없는 경우 조직에 대한 정보 장벽 정책을 만들 필요가 없습니다. 자세한 내용은 Microsoft Teams의 정보 [장벽을 참조하세요.](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams)

## <a name="office-365-message-encryption"></a>Office 365 메시지 암호화

OME(Office 365 메시지 암호화)는 Azure RMS(권한 관리)를 기반으로 구축된 서비스로, 대상의 전자 메일 주소(Gmail, Yahoo! Mail, Outlook.com 등)에 상관없이 사용자 조직 내부 또는 외부 사람에게 암호화된 전자 메일을 보낼 수 있습니다.

암호화된 메시지를 보려면 받는 사람이 일회용 암호를 얻어 Microsoft 계정에 로그인하거나 Office 365와 연결된 회사 또는 학교 계정을 사용하여 로그인할 수 있습니다. 받는 사람은 암호화된 회신을 보낼 수도 있습니다. 암호화된 메시지를 보거나 암호화된 답신을 보내기 위해 구독이 필요하지 않습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

메시지 보낸 사람이 Office 365 메시지 암호화에서 제공하는 중요한 전자 메일에 대한 추가 제어를 통해 혜택을 받을 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에게 서비스 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 E3/A3, Office 365 E3/A3 및 Azure Information Protection 요금제 1은 사용자가 Office 365 메시지 암호화를 사용할 수 있는 권한을 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

관리자는 메일 흐름 규칙에 따라 Exchange 관리 센터에서 Office 365 메시지 암호화 **정책을** 만들고  >  **관리합니다.** 기본적으로 이러한 규칙은 테넌트의 모든 사용자에게 적용됩니다. 새 Office 365 메시지 암호화 기능을 설정하는 자세한 내용은 새 메시지 암호화 기능 [설정을 참조하십시오.](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스를 사용이 허가된 테넌트의 사용자에게만 서비스를 적용하는 방법

관리자는 Office 365 메시지 암호화에 대한 메일 흐름 규칙을 사용이 허가된 사용자에게만 적용해야 합니다. 메일 흐름 규칙을 정의하는 데 대한 자세한 내용은 전자 메일 메시지를 암호화하는 메일 흐름 규칙 [정의를 참조하십시오.](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)

## <a name="office-365-advanced-message-encryption"></a>Office 365 고급 메시지 암호화

Office 365 고급 메시지 암호화는 고객이 외부 받는 사람에 대한 보다 유연한 제어 및 암호화된 전자 메일에 대한 액세스가 필요한 준수 의무를 충족하는 데 도움이 됩니다. 관리자는 고급 메시지 암호화를 사용하여 중요한 정보 유형(예: 개인 식별 정보 또는 재무/상태 식별)을 검색할 수 있는 자동 정책을 사용하여 조직 외부에서 공유되는 중요한 전자 메일을 제어하거나, 키워드를 사용하여 보안 웹 포털을 통해 사용자 지정 전자 메일 서식 파일을 적용하고 암호화된 전자 메일에 대한 액세스 권한을 만료하여 보호를 강화할 수 있습니다. 또한 관리자는 액세스 권한을 해지하여 보안 웹 포털을 통해 외부에서 액세스하는 암호화된 전자 메일을 추가로 제어할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

메시지 보낸 사람이 고급 메시지 암호화에서 제공하는 중요한 전자 메일에 대한 추가된 컨트롤을 통해 혜택을 받을 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에게 서비스 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Office 365 E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 규정 준수, Microsoft 365 정보 보호 및 거버넌스 및 Office 365 고급 규정 준수는 사용자가 고급 메시지 암호화를 사용할 수 있는 권한을 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

관리자는 메일 흐름 규칙에 따라 Exchange 관리 센터에서 고급 메시지 암호화 **정책을** 만들고  >  **관리합니다.** 기본적으로 이러한 규칙은 테넌트의 모든 사용자에게 적용됩니다. 새 메시지 암호화 기능을 설정하는 자세한 내용은 [새 Office 365](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities)메시지 암호화 기능 설정을 참조하십시오.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스를 사용이 허가된 테넌트의 사용자에게만 서비스를 적용하는 방법

관리자는 고급 메시지 암호화에 대한 메일 흐름 규칙을 사용이 허가된 사용자에게만 적용해야 합니다. 메일 흐름 규칙을 정의하는 데 대한 자세한 내용은 [Office 365에서](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)전자 메일 메시지를 암호화하는 메일 흐름 규칙 정의를 참조하세요.

## <a name="communication-compliance"></a>커뮤니케이션 규정 준수

Microsoft 365의 통신 규정 준수는 조직에서 부적절한 메시지를 검색, 캡처 및 수정하는 데 도움을 주어 통신 위험을 최소화하는 데 도움이 됩니다. 조직에서 내부 및 외부 전자 메일, Microsoft Teams 또는 타사 통신을 캡처하는 특정 정책을 정의할 수 있습니다. 검토자는 조직의 메시지 표준을 준수하는지 확인하도록 적절한 수정 조치를 취할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

규정 준수 전문가는 커뮤니케이션 규정 준수 정책에 의해 조직 통신을 모니터링하도록 하여 이 서비스의 이점을 제공합니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에게 서비스 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Office 365 E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 규정 준수 및 Microsoft 365 내부자 위험 관리는 사용자가 통신 규정 준수를 혜택을 받을 수 있는 권한을 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

관리자 및 규정 준수 전문가는 Microsoft 365 규정 준수 센터에서 커뮤니케이션 규정 준수 정책을 생성합니다. 이러한 정책은 조직에서 검토할 통신 및 사용자를 정의하고, 커뮤니케이션이 충족해야 하는 사용자 지정 조건을 정의하고, 검토를 수행할 사용자를 지정합니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스를 사용이 허가된 테넌트의 사용자에게만 서비스를 적용하는 방법

관리자는 통신 준수 정책에 포함할 특정 사용자 또는 그룹을 선택 합니다. 그룹을 선택할 때 그룹에서 통신 준수 정책에서 제외할 특정 사용자를 선택할 수도 있습니다. 통신 준수 정책에 대한 자세한 내용은 [Microsoft 365에서](https://docs.microsoft.com/microsoft-365/compliance/communication-compliance-configure)통신 규정 준수 시작을 참조하세요.

## <a name="insider-risk-management"></a>내부자 위험 관리

내부자 위험 관리는 조직에서 위험한 활동을 감지, 조사 및 조치를 취할 수 있도록 하여 내부 위험을 최소화하는 데 도움이 되는 Microsoft 365의 솔루션입니다.

사용자 지정 정책을 사용하면 필요한 경우 사례를 Microsoft Advanced eDiscovery로 에스컬레이터하는 등 조직에서 악성 및 부수적으로 위험한 활동을 감지하고 조치를 취할 수 있습니다. 조직의 위험 분석가가 신속하게 적절한 조치를 취하여 사용자가 조직의 규정 준수 표준을 준수하도록 할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

사용자는 자신의 활동을 위험에 대해 모니터링하여 혜택을 받을 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에게 서비스 혜택을 받을 수 있는 권한을 제공하는 라이선스는 무엇입니까?

Microsoft 365 E5/A5, Microsoft 365 E5/A5 규정 준수 및 Microsoft 365 내부자 위험 관리는 사용자가 내부자 위험 관리를 혜택을 받을 수 있는 권한을 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

내부자 위험 관리 정책은 Microsoft 365 규정 준수 센터에서 만들어 사용자에게 할당해야 합니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스를 사용이 허가된 테넌트의 사용자에게만 서비스를 적용하는 방법

Microsoft 365 규정 준수 센터에서 정책을 만들 때 사용자 및  그룹 선택 페이지에서 사용자 또는 그룹 선택을 선택하여 사용이 허가된 사용자만  선택하거나 모든 사용자에게 라이선스가 부여된 경우 모든 사용자 및 메일 사용이 가능한 그룹 확인란을 선택할 수 있습니다.  자세한 내용은 내부자 위험 관리 [시작을 참조하세요.](https://docs.microsoft.com/microsoft-365/compliance/insider-risk-management-configure)

## <a name="conditional-access-policies"></a>조건부 액세스 정책

조건부 액세스는 Azure Active Directory에서 신호를 함께 가져오고, 의사 결정을 내리고, 조직 정책을 적용하는 데 사용하는 도구입니다. 조건부 액세스는 ID 기반 제어의 핵심입니다. 가장 간단한 조건부 액세스 정책은 if-then 문입니다. 사용자가 리소스에 액세스하려는 경우 작업을 완료해야 합니다. 예: 급여 관리자는 급여 응용 프로그램에 액세스하고 다단계 인증을 수행하여 해당 응용 프로그램에 액세스해야 합니다.

### <a name="which-users-benefit-from-the-service"></a>서비스에서 혜택을 받을 수 있는 사용자

Enterprise Mobility + Security E3/A3, Microsoft 365 F3/E3/A3/Business Premium 및 Azure Active Directory Premium 요금제 1의 사용이 허가된 사용자는 조건부 액세스 정책을 사용할 수 있습니다. Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5, Microsoft E5 Security 및 Azure Active Directory Premium 요금제 2의 사용이 허가된 사용자는 ID 보호(위험 기반 조건부 액세스 정책)를 사용할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

보안 운영 분석가 및 보안 전문가는 사용자에게 조직 정책을 적용하여 회사 콘텐츠에 대한 액세스 권한을 부여하기 전에 특정 기준을 충족하도록 요구하는 기능을 통해 이점을 제공합니다. 최종 사용자는 조직의 자산을 보호하면서 선택할 때마다 자신의 업무에 액세스할 수 있는 이점을 제공합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 조건부 액세스 기능은 테넌트 내의 모든 사용자에 대해 테넌트 수준에서 사용하도록 설정됩니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스를 사용이 허가된 테넌트의 사용자에게만 서비스를 적용하는 방법

특히 ID 보호 및 조건부 액세스의 경우 사용자를 그룹에 포함하거나 조건부 액세스 정책에 추가해야 합니다. 사용자 및 그룹 조건은 조건부 액세스 정책에서 필수입니다. 정책에서 모든 사용자 또는 특정 **사용자** 및 그룹을 선택할 수 있습니다. 적절한 사용이 허가된 사용자 및 그룹만 선택해야 합니다. 자세한 내용은 [조건부 액세스: 조건부를 참조하십시오.](https://docs.microsoft.com/azure/active-directory/conditional-access/conditions)

## <a name="advanced-audit"></a>고급 감사

Microsoft 365의 고급 감사는 사용자 및 관리자 활동에 대한 감사 로그의 1년 보존을 제공하며, 사용자 지정 감사 로그 보존 정책을 만들어 다른 Microsoft 365 서비스에 대한 감사 로그 보존을 관리하는 기능을 제공합니다. 또한 조사를 위한 중요한 이벤트에 대한 액세스와 Office 365 관리 활동 API에 대한 높은 대역폭 액세스를 제공합니다. 자세한 내용은 [Microsoft 365의 고급 감사를 참조하세요.](https://docs.microsoft.com/microsoft-365/compliance/advanced-audit)

추가 기능 SKU를 사용하여 10년의 보존 기간을 사용하도록 설정할 수 있습니다. 추가 기능 SKU는 2021년 초부터 필요합니다.

### <a name="which-users-benefit-from-the-service"></a>서비스에서 혜택을 받을 수 있는 사용자

Office 365 E5, Microsoft 365 E5, Microsoft 365 E5 규정 준수 및 Microsoft 365 eDiscovery 및 감사의 사용이 허가된 사용자는 고급 감사를 통해 혜택을 받을 수 있습니다.

고급 감사 및 10년 감사 로그 보존 추가 기능을 사용할 수 있는 라이선스가 있는 사용자는 10년 감사 로그 보존을 사용할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 통해 어떤 혜택을 받을 수 있나요?

Microsoft 365 서비스의 사용자 활동과 관련된 감사 레코드는 최대 1년 동안 보존할 수 있기 때문에 고급 감사의 이점이 있습니다. 또한 사용자 사서함의 항목에 액세스하거나 읽는 경우와 같이 고가치 감사 이벤트가 기록됩니다. 자세한 내용은 [Microsoft 365의 고급 감사를 참조하세요.](https://docs.microsoft.com/microsoft-365/compliance/advanced-audit)

### <a name="how-is-the-service-provisioneddeployed"></a>서비스가 프로비전/배포되는 방식

기본적으로 고급 감사는 Office 365 또는 Microsoft 365 E5 구독이 있는 모든 조직에 대해 테넌트 수준에서 사용하도록 설정되며 Azure Active Directory, Exchange 및 SharePoint에서 활동에 대한 감사 로그의 1년 보존(적절한 라이선스가 있는 사용자가 수행)을 자동으로 제공합니다. 또한 조직은 감사 로그 보존 정책을 사용하여 다른 Microsoft 365 서비스의 활동으로 생성된 감사 레코드의 보존 기간을 관리할 수 있습니다. 10년 감사 로그 보존 기능은 동일한 보존 정책을 사용하여 사용하도록 설정됩니다. 자세한 내용은 [감사 로그 보존 정책 관리](https://docs.microsoft.com/microsoft-365/compliance/audit-log-retention-policies)를 참조하십시오.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스를 사용이 허가된 테넌트의 사용자에게만 서비스를 적용하는 방법

감사 로그의 1년 보존 및 중요한 이벤트 감사는 해당 라이선스가 있는 사용자에게만 적용됩니다. 또한 관리자는 감사 로그 보존 정책을 사용하여 특정 사용자의 감사 로그에 대한 더 짧은 보존 기간을 지정할 수 있습니다.

감사 로그의 10년 보존은 적절한 추가 기능 라이선스가 있는 사용자에게만 적용됩니다. 추가 기능 SKU는 2021년 초부터 필요합니다.
