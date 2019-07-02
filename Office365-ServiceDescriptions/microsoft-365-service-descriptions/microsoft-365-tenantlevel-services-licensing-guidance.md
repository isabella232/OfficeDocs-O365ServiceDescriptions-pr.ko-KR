---
title: Microsoft 365 테 넌 트 수준 서비스 라이선스 지침
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- office-online-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 이 문서에서는 허가 되지 않은 액세스로 인 한 잠재적인 서비스 중단을 방지 하기 위해 Microsoft 365 테 넌 트 수준 서비스에 대 한 라이선스 지침을 제공 합니다.
ms.openlocfilehash: dea49f7c6ea3a0082968335586e146a33d4a76cc
ms.sourcegitcommit: 983c4e2b50177883d9369f12b43e09d51e1e5f28
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/01/2019
ms.locfileid: "35411463"
---
# <a name="microsoft-365-tenant-level-services-licensing-guidance"></a>Microsoft 365 테 넌 트 수준 서비스 라이선스 지침

이 문서를 사용 하는 경우 테 넌 트 수준 서비스는 테 넌 트의&mdash;모든 사용자에 대해 구매한 경우 (독립 실행형 또는 Office 365 또는 Microsoft 365 요금제의 일부로)&mdash;이 테 넌 트의 모든 사용자에 대해 전체에서 정품 인증을 받아야 하는 온라인 서비스입니다. 일부 허가 되지 않은 사용자는 기술적으로 서비스에 액세스할 수 있지만,이 경우 서비스에서 혜택을 받으려는 모든 사용자에 게 라이선스가 필요 합니다.

> [!NOTE]
> 일부 테 넌 트 서비스가 현재 특정 사용자에 대 한 혜택을 제한할 수 없습니다. 사용이 허가 된 사용자에 대 한 서비스 혜택을 제한 하기 위해 노력을 기울여야 합니다. 이렇게 하면 사용 가능한 기능을 사용할 수 있게 되 면 조직에 대 한 잠재적 서비스 중단을 방지 하기 위해 도움이 됩니다.

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory Id 보호

Azure Active Directory Id 보호 (AADIP)는 조직의 id에 영향을 미치는 잠재적인 취약점을 검색 하 고 의심 스러운 검색으로 자동화 된 응답을 구성 하는 데 사용할 수 있는 Azure Active Directory Premium P2 계획의 기능입니다. 조직의 id와 관련 된 작업 및 의심 스러운 문제를 조사 하 고 적절 한 조치를 수행 하 여 문제를 해결 합니다.

### <a name="which-users-benefit-from-the-service"></a>어떤 사용자가 서비스를 사용할 수 있나요?

Enterprise Mobility + Security E5, microsoft 365 E5, Microsoft 365 E5 보안 및 Azure Active Directory Premium 요금제 2의 라이선스가 있는 사용자는 AADIP을 활용할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 이용 하는 방법은 무엇 인가요?

SecOps 분석가 및 보안 전문가는 컴퓨터 학습 알고리즘에 따라 플래그가 지정 된 사용자 및 위험 이벤트를 통합 하 여 볼 수 있습니다. 최종 사용자는 위험 기반 조건부 액세스를 통해 제공 되는 자동 보호와 취약성에 따른 향상 된 보안 기능을 활용할 수 있습니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 구축/배포 됩니까?

기본적으로 AADIP 기능은 테 넌 트 내의 모든 사용자에 대 한 테 넌 트 수준에서 사용 하도록 설정 됩니다. AADIP을 구성 하는 방법에 대 한 자세한 내용은 [Azure Active Directory Id 보호 사용](https://docs.microsoft.com/azure/active-directory/identity-protection/enable)을 참조 하십시오.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대해 사용이 허가 된 테 넌 트의 사용자 에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

관리자는 암호 재설정 수준을 정의 하 고 허가 된 사용자 에게만 액세스를 허용 하는 위험 정책을 할당 하 여 AADIP의 범위를 지정할 수 있습니다. AADIP 배포의 범위를 결정 하는 방법에 대 한 자세한 내용은 [로그인 위험 정책 구성을](https://docs.microsoft.com/azure/active-directory/identity-protection/howto-sign-in-risk-policy)참조 하십시오.

## <a name="azure-advanced-threat-protection"></a>Azure Advanced Threat Protection

Azure ATP (Advanced Threat Protection)는 여러 유형의 고급 대상 사이버 공격 및 참가자 위협 으로부터 기업 하이브리드 환경을 보호 하는 클라우드 서비스입니다.

### <a name="which-users-benefit-from-the-service"></a>어떤 사용자가 서비스를 사용할 수 있나요?

Enterprise Mobility + Security E5, Microsoft 365 E5, Microsoft 365 E5 보안 및 Azure Advanced Threat Protection을 사용 하는 라이선스가 있는 사용자가 Azure ATP의 혜택을 받을 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 이용 하는 방법은 무엇 인가요?

SecOp 분석가 및 보안 전문가는 Azure ATP가 고급 위협, 손상 된 id 및 악의적인 참가자 작업을 검색 하 고 조사 하는 기능을 활용 합니다. 최종 사용자는 Azure ATP에서 데이터를 모니터링 하는 이점이 있습니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 구축/배포 됩니까?

기본적으로 Azure ATP 기능은 테 넌 트 내의 모든 사용자에 대 한 테 넌 트 수준에서 사용 하도록 설정 됩니다. Azure ATP 구성에 대 한 자세한 내용은 [AZURE atp 인스턴스 만들기](https://docs.microsoft.com/azure-advanced-threat-protection/install-atp-step1)를 참조 하세요.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대해 사용이 허가 된 테 넌 트의 사용자 에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

Microsoft는 라이선스가 없는 사용자에 게 위협 검색 기능을 제공 하기 위해 커밋하지 않습니다. 시간이 지남에 따라 라이선스 검사 또는 대상 도구를 Azure ATP에 추가 하 여 Azure ATP 기능을 라이선스가 있는 사용자 에게만 적용할 수 있도록 합니다.

## <a name="azure-information-protection"></a>Azure 정보 보호

AIP (Azure Information Protection)를 사용 하면 조직에서 중요 한 문서 및 전자 메일을 검색, 분류, 레이블 지정 하 고 보호할 수 있습니다. 관리자는 레이블을 자동으로 적용 하는 규칙 및 조건을 정의 하거나, 사용자가 레이블을 수동으로 적용할 수 있으며, 사용자에 게 레이블&mdash;적용에 대 한 권장 사항이 제공 되는 경우이 두 가지를 조합 하 여 사용할 수 있습니다.

### <a name="which-users-benefit-from-the-service"></a>어떤 사용자가 서비스를 사용할 수 있나요?

Microsoft 365 F1, Microsoft 365 E3 및 AIP 요금제 1의 라이선스가 부여 된 사용자는 IP 요금제 1을 활용할 수 있습니다. Microsoft 365 E5, Microsoft 365 E5 규정 준수 및 AIP 요금제 2의 라이선스가 있는 사용자는 IP 요금제 2를 활용할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 이용 하는 방법은 무엇 인가요?

AIP 스캐너 기능은 온-프레미스 파일 저장소에 있는 파일을 자동으로 분류, 레이블 및 보호 합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 구축/배포 됩니까?

기본적으로 테 넌 트 내의 모든 사용자에 대 한 테 넌 트 수준에서 AIP 기능이 사용 되도록 설정 됩니다. 라이선스 사용자에 대 한 AIP 정책을 구성 하는 방법에 대 한 자세한 내용은 [Azure 권한 관리 활성화](https://docs.microsoft.com/azure/information-protection/activate-service)를 참조 하십시오.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대해 사용이 허가 된 테 넌 트의 사용자 에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

검색 기능을 제외한 나머지 IP 기능 정책은 특정 그룹이 나 사용자에 게 범위 지정 될 수 있습니다. 라이선스가 없는 사용자가 AIP 분류 또는 레이블 기능을 실행 하지 못하도록 레지스트리를 편집할 수 있습니다. IP 배포의 범위를 결정 하는 방법에 대 한 자세한 내용은 [Azure Information Protection Policy 구성을](https://docs.microsoft.com/azure/information-protection/configure-policy)참조 하십시오.

AIP 스캐너 기능의 경우 Microsoft는 라이선스가 없는 사용자에 게 파일 분류, 레이블 지정 또는 보호 기능을 제공 하기 위해 커밋하지 않습니다. 사용이 허가 된 사용자에 게 스캐너 기능을 할당할 수 있도록 하려면 시간이 지남에 따라 라이선스 검사 또는 대상 지정 도구가 IP에 추가 됩니다.

## <a name="office-365-advanced-threat-protection"></a>Office 365 Advanced Threat Protection

ATP (Advanced Threat Protection)를 사용 하면 피싱 및 제로 일 멀웨어와 같은 정교한 공격 으로부터 조직을 보호할 수 있습니다. 또한 다양 한 데이터를 식별 하 고 우선 순위를 지정 하 여 잠재적 위협을 해결 하는 방법에 대 한 권장 사항을 제공 하는 데 도움을 주는 유효한 통찰력을 제공 합니다.

### <a name="which-users-benefit-from-the-service"></a>어떤 사용자가 서비스를 사용할 수 있나요?

Office 365 E5, microsoft 365 E5, microsoft 365 E5 Security, microsoft 365 Business, Office 365 ATP 계획 1 및 2의 라이선스가 있는 사용자는 ATP의 혜택을 받을 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 이용 하는 방법은 무엇 인가요?

ATP는 피싱 및 제로 일 멀웨어와 같은 복잡 한 공격 으로부터 사용자를 보호 합니다. 계획 1 및 계획 2에 제공 된 서비스의 전체 목록은 [Office 365 Advanced Threat Protection](https://products.office.com/exchange/advance-threat-protection)를 참조 하세요.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 구축/배포 됩니까?

기본적으로 ATP 기능은 테 넌 트 내의 모든 사용자에 대 한 테 넌 트 수준에서 사용 하도록 설정 됩니다. 라이선스가 부여 된 사용자에 대 한 ATP 정책을 구성 하는 방법에 대 한 자세한 내용은 [Office 365 Advanced Threat Protection](https://docs.microsoft.com/office365/securitycompliance/office-365-atp)를 참조 하세요.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대해 사용이 허가 된 테 넌 트의 사용자 에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

ATP 범위를 적용 하려면 안전한 링크 및 안전한 첨부 파일 배포 정책을 따릅니다.

  - 라이선스가 부여 된 사용자에 대 한 안전한 링크를 구성 하는 방법에 대 한 자세한 내용은 [Office 365 ATP 안전한 링크 정책 설정을](https://docs.microsoft.com/office365/securitycompliance/set-up-atp-safe-links-policies)참조 하십시오.

  - 라이선스가 있는 사용자에 대 한 안전한 첨부 파일을 구성 하는 방법에 대 한 자세한 내용은 [Office 365 ATP 안전 첨부 파일 정책 설정을](https://docs.microsoft.com/office365/securitycompliance/set-up-atp-safe-attachments-policies)참조 하십시오.

## <a name="office-365-cloud-app-security"></a>Office 365 Cloud App Security

Office 365 Cloud App Security (OCAS)는 Office 365로 제한 되는 기능과 타사 클라우드 앱 및 IaaS 서비스에 대 한 추가 보안을 사용 하지 않고 Microsoft Cloud App Security의 하위 집합입니다.

OCAS 조직이 생산성 클라우드 앱 및 서비스를 확인할 수 있도록 하 고, 사이버 위협을 식별 하 고 해결 하는 정교한 분석을 제공 하며, Office&mdash;365에서 데이터를 전송 하는 방법을 제어할 수 있습니다.

기능을 비교 하려면 [Microsoft Cloud App security 및 Office 365 Cloud App security의 차이점](https://docs.microsoft.com/cloud-app-security/editions-cloud-app-security-o365)을 참조 하세요.

### <a name="which-users-benefit-from-the-service"></a>어떤 사용자가 서비스를 사용할 수 있나요?

Office 365 E5의 라이선스가 있는 사용자는 OCAS 같이 이점을 누릴 수 있습니다.

자세한 내용은 [Microsoft Cloud App Security License Datasheet](http://www.aka.ms/mcaslicensing)를 참조 하세요.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 이용 하는 방법은 무엇 인가요?

OCAS 섀도를 검색 하 고, Office 365에서 위협을 보호 하며, Office 365 데이터에 액세스 하는 데 필요한 권한이 있는 앱을 제어할 수 있습니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 구축/배포 됩니까?

기본적으로 OCAS 테 넌 트 내의 모든 사용자에 대 한 테 넌 트 수준에서 사용 하도록 설정 됩니다.

서비스 구성에 대 한 자세한 내용은 [Cloud App Security에 대 한 기본 설정을](https://docs.microsoft.com/cloud-app-security/general-setup)참조 하십시오.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대해 사용이 허가 된 테 넌 트의 사용자 에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

관리자는 특정 앱에 액세스 하는 방법을 적용 하 고 Office 365 Cloud App Security에서 모니터링 되는 사용자 그룹을 제한 하기 위해 OCAS 범위를 배포할 수 있습니다. 자세한 내용은 범위가 지정 된 [배포](https://docs.microsoft.com/cloud-app-security/scoped-deployment)를 참조 하세요.

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

Microsoft Cloud App Security (MCAS)는 조직에 클라우드 앱 및 서비스를 표시 하는 방법을 제공 하는 사이버 (클라우드 액세스 보안 브로커) 솔루션 이며, 문제를 식별 하 고 해결 하는 정교한 분석 기능을 제공 하며 데이터를 제어 하는 데 사용할 수 있습니다. 모든&mdash;클라우드 앱에서 이동 합니다.

### <a name="which-users-benefit-from-the-service"></a>어떤 사용자가 서비스를 사용할 수 있나요?

MCAS의 라이선스가 있는 사용자, Enterprise Mobility + Security E5, Microsoft 365 E5 및 Microsoft 365 E5 보안은 MCAS의 혜택을 받을 수 있습니다.

Azure AD P1의 라이선스가 있는 사용자는 MCAS의 검색 기능을 활용할 수 있습니다.

MCAS에서 [조건부 액세스 앱 제어](https://docs.microsoft.com/cloud-app-security/proxy-intro-aad) 기능을 활용 하려면 사용자에 게 enterprise Mobility + security E3, enterprise Mobility + security E5, Microsoft 365 E3, microsoft 365에 포함 된 Azure Active Directory P1에 대 한 라이선스가 있어야 합니다. E5 및 Microsoft 365 E5 보안

[자동 레이블](https://docs.microsoft.com/cloud-app-security/data-protection-policies)기능의 혜택을 얻으려면 사용자에 게 Enterprise Mobility + Security E5, Microsoft 365 E5 및 Microsoft 365 e5 준수에 포함 된 Azure Information Protection P2에 대 한 라이선스가 있어야 합니다.

자세한 내용은 [Microsoft Cloud App Security License Datasheet](http://www.aka.ms/mcaslicensing)를 참조 하세요.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 이용 하는 방법은 무엇 인가요?

MCAS는 섀도 IT를 감지 및 평가 하 고, 첫 번째 및 타사 클라우드 앱에서의 위협 보호를 제공 하며, 첫 번째 및 타사 클라우드 앱에서 정보를 보호 합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 구축/배포 됩니까?

기본적으로 MCAS 기능은 테 넌 트 내의 모든 사용자에 대 한 테 넌 트 수준에서 사용 하도록 설정 됩니다.

라이선스가 부여 된 사용자에 대 한 Microsoft Cloud App 보안 정책을 구성 하는 방법에 대 한 자세한 내용은 [Microsoft Cloud App security overview](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security)를 참조 하세요.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대해 사용이 허가 된 테 넌 트의 사용자 에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

관리자는 서비스에서 사용할 수 있는 범위가 지정 된 배포 기능을 사용 하 여 라이선스 사용자에 게 MCAS 배포의 범위를 지정할 수 있습니다. 자세한 내용은 범위가 지정 된 [배포](https://docs.microsoft.com/cloud-app-security/scoped-deployment)를 참조 하세요.

## <a name="office-365-advanced-data-governance"></a>Office 365 고급 데이터 거버넌스

ADG (고급 데이터 관리)-조직이 보존 및 삭제를 사용 하도록 설정 하는 정책과 함께 정보 거 버 넌 스 요구 사항을 충족 합니다. ADG를 사용 하면 조직에서 중요 한 정보 유형을 기반으로 콘텐츠의 자동 레이블을 지정 하 고 해당 콘텐츠에 거 버 넌 스 정책을 적용할 수 있습니다.

### <a name="which-users-benefit-from-the-service"></a>어떤 사용자가 서비스를 사용할 수 있나요?

Office 365 E5, microsoft 365 E5, Microsoft 365 E5 규정 준수 및 Office 365 Advanced 준수에 대 한 라이선스가 있는 사용자가 ADG를 활용할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 이용 하는 방법은 무엇 인가요?

ADG를 사용 하면 특정 데이터에 레이블을 적용 하 여 특정 정책을 아래 맞춤 콘텐츠에 자동으로 레이블을 기록 하 고 전체 레코드 프로세스를 선언에서 삭제로 관리할 수 있습니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 구축/배포 됩니까?

기본적으로, ADG 기능은 테 넌 트 내의 모든 사용자에 대 한 테 넌 트 수준에서 사용 하도록 설정 됩니다. 사용이 허가 된 사용자에 대 한 자동 레이블 및 정책을 적용 하기 위해 ADG를 구성 하는 방법에 대 한 자세한 내용은 [보존 레이블 개요](https://docs.microsoft.com/office365/securitycompliance/labels)를 참조 하세요.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대해 사용이 허가 된 테 넌 트의 사용자 에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

ADG 보존 정책은 특정 위치 (팀 사이트, 그룹 사이트 등)의 사용이 가능한 사용자에 게 자동 분류를 통해 적용할 수 있습니다. ADG 보존 정책을 적용 하는 방법에 대 한 자세한 내용은 [전체 조직이 나 특정 위치에 보존 정책 적용](https://docs.microsoft.com/office365/securitycompliance/retention-policies#applying-a-retention-policy-to-an-entire-organization-or-specific-locations)을 참조 하십시오.

## <a name="office-365-advanced-ediscovery"></a>Office 365 고급 eDiscovery

Advanced eDiscovery는 조직 내 IT 및 법적 부서에 대해 조사 및 eDiscovery 솔루션을 제공 하 여 Office 365에서 수출 하기 전에 조사 또는 소송에 관련 된 콘텐츠를 식별, 수집, 보존, 절감 및 검토 합니다. 컴퓨터.

### <a name="which-users-benefit-from-the-service"></a>어떤 사용자가 서비스를 사용할 수 있나요?

Office 365 E5, microsoft 365 E5, Microsoft 365 E5 규정 준수 및 Office 365 Advanced 준수에 대 한 라이선스가 있는 사용자가 고급 eDiscovery를 활용할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 이용 하는 방법은 무엇 인가요?

사용자는 소송 또는 조사를 진행 하는 동안 콘텐츠가 보존 되는 경우 고급 eDiscovery를 활용할 수 있습니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 구축/배포 됩니까?

기본적으로 고급 eDiscovery 기능은 관리자가 보안 & 준수 센터에서 eDiscovery 권한을 할당할 때 테 넌 트 내의 모든 사용자에 대 한 테 넌 트 수준에서 사용 하도록 설정 됩니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대해 사용이 허가 된 테 넌 트의 사용자 에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

조직은 사용자별로 고급 eDiscovery를 관리 하 고 고급 eDiscovery 사례에 사용자를 추가할 수 있을 뿐만 아니라 eDiscovery 권한을 통해 공유 위치에 대 한 편집 권한을 사용자에 게 제공 합니다. 라이선스가 있는 사용자에 게 고급 eDiscovery 권한을 적용 하는 방법에 대 한 자세한 내용은 [Security & 준수 센터에서 eDiscovery 사용 권한 할당](https://docs.microsoft.com/office365/securitycompliance/assign-ediscovery-permissions)을 참조 하십시오.

## <a name="office-365-customer-key"></a>Office 365 고객 키

고객 키를 사용 하 여 조직의 암호화 키를 제어 하 고 Microsoft 데이터 센터의 휴지 상태에서 데이터를 암호화 하는 데 사용할 수 있도록 Office 365를 구성 합니다. 즉, 고객 키를 사용 하 여 사용자가 자신의 키를 통해 자신에 게 속하는 암호화 계층을 추가할 수 있습니다. 휴지 상태의 데이터에는 SharePoint Online 및 비즈니스용 OneDrive 내의 사서함 및 파일에 저장 된 Exchange Online 및 비즈니스용 Skype의 데이터가 포함 됩니다.

### <a name="which-users-benefit-from-the-service"></a>어떤 사용자가 서비스를 사용할 수 있나요?

Office 365 E5, microsoft 365 E5, Microsoft 365 E5 규정 준수 및 Office 365 Advanced 규정을 사용 하도록 허가 된 사용자는 고객 키를 통해 혜택을 받을 수 있습니다. 고객 키의 모든 이점을 얻으려면 Azure Key Vault 용 구독도 있어야 합니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 이용 하는 방법은 무엇 인가요?

사용자는 자체 조직에서 제공, 제어 및 관리 되는 암호화 키를 사용 하 여 응용 프로그램 계층에서 데이터를 보관 된 상태로 유지 하 여 고객 키를 활용할 수 있습니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 구축/배포 됩니까?

Office 365 고객 키 암호화 키를 Exchange Online 및 비즈니스용 Skype 사서함, SharePoint Online 및 비즈니스용 OneDrive 파일에 저장 된 모든 데이터에 대해 사용 하도록 설정할 수 있습니다. 데이터를 보관 하기 위해 Office 365 고객 키를 구성 하는 방법에 대 한 자세한 내용은 [고객 키를 사용 하 여 office 365에서 데이터 제어](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key)를 참조 하세요.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대해 사용이 허가 된 테 넌 트의 사용자 에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

사용이 허가 된 사용자에 대해 Office 365 및/또는 Microsoft 365 테 넌 트 내의 데이터에 암호화 키를 할당 하려면 고객 키 암호화 키 배포 정책을 따릅니다.

  - SharePoint Online의 경우 하나 이상의 사이트에 있는 파일을 여기에 설명 된 대로 고객 키를 사용 하 여 암호화할 수 있습니다. [Sharepoint online 및 비즈니스용 OneDrive에 대 한 고객 키 설정](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key#office-365-setting-up-customer-key-for-sharepoint-online-and-onedrive-for-business)

  - Exchange Online 및 비즈니스용 Skype Online의 경우 여기에 설명 된 대로 고객 키를 사용 하 여 사서함을 암호화할 수 있습니다. [Exchange online 및 비즈니스용 skype에 대 한 고객 키 설정](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key#office-365-setting-up-customer-key-for-exchange-online-and-skype-for-business)

## <a name="office-365-customer-lockbox"></a>Office 365 고객 Lockbox

고객 Lockbox는 서비스 작업에 대 한 명시적 액세스 권한 부여를 제공 하는 기능을 고객에 게 제공 하 여 추가 제어 계층을 제공할 수 있습니다. 고객 Lockbox는 명시적 데이터 액세스 권한 부여를 위한 절차를 마련 하 여 조직이 HIPAA 및 FEDRAMP와 같은 특정 준수 의무를 충족 하는 데도 도움이 될 수 있습니다.

### <a name="which-users-benefit-from-the-service"></a>어떤 사용자가 서비스를 사용할 수 있나요?

Office 365 E5, Microsoft 365 E5, Microsoft 365 E5 규정 준수 및 Office 365 Advanced 준수는 고객 Lockbox의 혜택을 받을 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 이용 하는 방법은 무엇 인가요?

사용자는 고객 Lockbox의 혜택을 통해 고객의 명시적 승인 없이 서비스 작업을 수행 하기 위해 Microsoft의 콘텐츠에 액세스할 수 없도록 합니다. 고객 Lockbox는 고객에 게 콘텐츠에 액세스 하기 위한 요청에 대 한 승인 워크플로를 제공 합니다. 때로는 지원 프로세스 중에 Microsoft 엔지니어가 고객이 보고 한 문제를 해결 하 고 문제를 해결 하는 데 사용 되는 경우가 있습니다. 대부분의 경우 문제는 Microsoft에서 서비스를 위해 마련 된 광범위 한 원격 분석 및 디버깅 도구를 통해 수정 됩니다. 그러나 Microsoft 엔지니어가 고객 콘텐츠에 액세스 하 여 근본적인 원인을 확인 하 고 문제를 해결 해야 하는 경우가 있을 수 있습니다. 고객 Lockbox에 게는 승인 워크플로의 최종 단계로 고객의 액세스를 요청 하는 엔지니어가 필요 합니다. 이를 통해 조직에서는 이러한 요청을 승인 하거나 거부 하는 옵션을 제공 하므로 Microsoft 엔지니어가 조직의 최종 사용자 데이터에 액세스할 수 있는지 여부를 직접 제어할 수도 있습니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 구축/배포 됩니까?

관리자는 Microsoft 365 관리 센터에서 고객 Lockbox 컨트롤을 켤 수 있습니다. 자세한 내용은 [Office 365의 고객 Lockbox](https://docs.microsoft.com/Office365/Admin/manage/customer-lockbox-requests)를 참조 하세요. 고객 Lockbox가 설정 된 경우 Microsoft는 해당 콘텐츠에 액세스 하기 전에 조직의 승인을 받아야 합니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대해 사용이 허가 된 테 넌 트의 사용자 에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

라이선스가 없는 사용자에 대해 고객 Lockbox 액세스 제어 승인 요청을 제공 하기 위해 Microsoft는 커밋하지 않습니다. 시간에 따라 라이선스 확인 또는 대상 지정 된 도구는 고객 Lockbox에 추가 되어 고객 Lockbox가 라이선스 사용자에 게 할당할 수 있도록 합니다.

## <a name="privileged-access-management-in-office-365"></a>Office 365의 권한이 부여 된 액세스 관리

PAM (권한 부여 관리) 기능은 Office 365의 권한 있는 관리 작업에 대 한 세부적인 액세스 제어를 제공 합니다. 권한 있는 액세스 관리를 사용 하도록 설정한 후에는 사용자가 상승 된 권한 및 권한 작업을 완료 하기 위해 범위가 높고 시간이 제한 된 승인 워크플로를 통해 just-in-time 액세스를 요청 해야 합니다.

### <a name="which-users-benefit-from-the-service"></a>어떤 사용자가 서비스를 사용할 수 있나요?

Office 365 E5, microsoft 365 E5, Microsoft 365 E5 규정 준수 및 Office 365 Advanced 준수에 대 한 라이선스가 있는 사용자가 PAM을 활용할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 이용 하는 방법은 무엇 인가요?

PAM을 사용 하도록 설정 하면 조직에서 권한이 없는 상태로 작동할 수 있습니다. 사용자는 unfettered에 대 한 액세스를 제공 하는 관리 액세스에서 발생 하는 취약성에 대해 추가 된 방어 계층을 활용할 수 있습니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 구축/배포 됩니까?

기본적으로 PAM 기능은 테 넌 트 내의 모든 사용자에 대 한 테 넌 트 수준에서 사용 하도록 설정 됩니다. PAM 정책 구성에 대 한 자세한 내용은 [Office 365에서 권한이 부여 된 액세스 관리 구성을](https://docs.microsoft.com/office365/securitycompliance/privileged-access-management-configuration)참조 하십시오.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대해 사용이 허가 된 테 넌 트의 사용자 에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

고객은 승인자 그룹 및 액세스 정책을 통해 사용자 단위로 PAM을 관리할 수 있으며,이는 라이선스가 있는 사용자에 게 적용할 수 있습니다. 자세한 내용은 [Office 365의 권한이 부여 된 액세스 관리](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751)를 참조 하세요.

## <a name="data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Exchange Online, SharePoint Online 및 비즈니스용 OneDrive에 대 한 데이터 손실 방지

조직에서는 Exchange Online, SharePoint Online 및 비즈니스용 OneDrive에 대해 DLP (데이터 손실 방지)를 사용 하 여 전자 메일 및 파일 (Microsoft 팀 파일에 저장 된 파일 포함)에서 중요 한 정보를 식별, 모니터링 및 자동으로 보호할 수 있습니다. 리포지토리).

### <a name="which-users-benefit-from-the-service"></a>어떤 사용자가 서비스를 사용할 수 있나요?

Office 365 E3, Microsoft 365 E3 및 Office 365의 라이선스가 부여 된 사용자는 Exchange Online, SharePoint Online 및 비즈니스용 OneDrive에서 DLP를 활용할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 이용 하는 방법은 무엇 인가요?

사용자는 Exchange Online, SharePoint Online 및 비즈니스용 OneDrive (조직의 DLP 정책에 구성 된 대로 중요 한 정보에 대 한 전자 메일 및 파일을 검사 하는 경우)에 대 한 DLP를 활용할 수 있습니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 구축/배포 됩니까?

기본적으로 Exchange Online 전자 메일, SharePoint 사이트 및 OneDrive 계정은 테 넌 트 내의 모든 사용자에 대 한 이러한 DLP 기능에 대해 *사용 하도록 설정 된 위치 (작업)* 입니다. DLP 정책을 사용 하는 방법에 대 한 자세한 내용은 [Overview For data 손실 방지](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)를 참조 하십시오.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대해 사용이 허가 된 테 넌 트의 사용자 에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

관리자는 **데이터 손실 방지** > **위치**아래의 Office 365 보안 & 준수 센터에서 위치 (작업), 포함 된 사용자 및 제외 된 사용자를 사용자 지정할 수 있습니다.

## <a name="data-loss-prevention-for-teams-chat-and-channel-conversations"></a>팀 채팅 및 채널 대화에 대 한 데이터 손실 방지

조직에서는 팀 채팅 및 채널 대화에 대 한 DLP (데이터 손실 방지)를 통해 금융 정보, 개인 식별 정보 등 중요 한 정보가 포함 된 채팅 및 채널 대화에서 메시지를 차단할 수 있습니다. 상태 관련 정보 또는 기타 기밀 정보

### <a name="which-users-benefit-from-the-service"></a>어떤 사용자가 서비스를 사용할 수 있나요?

Office 365 E5, microsoft 365 E5, Microsoft 365 E5 규정 준수 및 Office 365 Advanced 규정을 사용 하는 라이선스가 있는 사용자는 팀 채팅 및 채널 대화에 대 한 DLP를 활용할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 이용 하는 방법은 무엇 인가요?

보내는 채팅 및 채널 대화 메시지에 조직의 DLP 정책에 구성 된 대로 중요 한 정보를 검사 하 여 보낸 사람 혜택을 받을 수 있습니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 구축/배포 됩니까?

기본적으로 팀 채팅 및 채널 채팅은 테 넌 트 내의 모든 사용자에 대 한 이러한 DLP 기능에 대 한 *사용 가능한 위치 (작업)* 입니다. DLP 정책을 사용 하는 방법에 대 한 자세한 내용은 [Overview For data 손실 방지](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)를 참조 하십시오.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대해 사용이 허가 된 테 넌 트의 사용자 에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

관리자는 **데이터 손실 방지** > **위치**아래의 Office 365 보안 & 준수 센터에서 위치 (작업), 포함 된 사용자 및 제외 된 사용자를 사용자 지정할 수 있습니다.

## <a name="information-barriers"></a>정보 장벽

정보 장애물은 관리자가 개인 또는 그룹이 서로 통신 하지 못하도록 하기 위해 구성할 수 있는 정책입니다. 예를 들어, 한 부서가 다른 부서와 공유 하지 않아야 하는 정보를 처리 하거나, 그룹이 외부 대화 상대와 통신 하지 못하도록 해야 하는 경우에 유용 합니다. 정보 장벽 정책 역시 조회 및 검색을 방지 합니다. 즉, 통신 하지 않아야 하는 사람과 통신을 시도 하는 경우 사용자 선택에 해당 사람이 검색 되지 않습니다.

### <a name="which-users-benefit-from-the-service"></a>어떤 사용자가 서비스를 사용할 수 있나요?

Office 365 E5, microsoft 365 E5, Microsoft 365 E5 규정 준수 및 Office 365 Advanced 준수에 대 한 라이선스가 있는 사용자는 정보 장벽에 따라 이점을 누릴 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 이용 하는 방법은 무엇 인가요?

사용자가 다른 사람과 통신 하지 못하도록 제한 되 면 정보 장벽에 대 한 고급 규정 준수 기능의 이점을 활용할 수 있습니다. 예를 들면 다음과 같습니다.

| 시나리오                                                                                                                                                                                                              | 라이선스가 필요한 사용자 |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- |
| 두 그룹 (그룹 1 및 그룹 2)은 서로 통신할 수 없으며, 그룹 1 사용자는 그룹 2 명의 사용자와 통신 하지 못하도록 제한 되며, 그룹 2 사용자는 그룹 1 명의 사용자와 통신 하는 것이 제한 됩니다. | 그룹 1 및 그룹 2의 사용자                    |
| 그룹 1의 사용자는 회사의 나머지와 통신 하지 못하도록 제한 됩니다.                                                                                                                                       | 그룹 1의 사용자만                                |
| 회사의 나머지는 그룹 1과의 통신으로 제한 됩니다.                                                                                                                                                 | 그룹 1의 경우를 제외한 모든 사용자                    |
| 그룹 1 사용자는 그룹 2 사용자와의 통신을 제한 하지만 그룹 2 사용자는 그룹 1 사용자와 통신할 수 있습니다.                                                                                              | 그룹 1의 사용자만                                |

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 구축/배포 됩니까?

관리자 보안 & 준수 센터에서 PowerShell cmdlet을 사용 하 여 정보 장벽 정책을 만들고 관리 합니다. 정보 장벽 정책을 만들려면 관리자에 게 Microsoft 365 Enterprise Global Administrator, Office 365 전역 관리자 또는 준수 관리자 역할을 할당 받아야 합니다. 기본적으로이 정책은 테 넌 트의 모든 사용자에 게 적용 됩니다. 정보 장벽에 대 한 자세한 내용은 [Microsoft 팀의 정보 장벽](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams)를 참조 하세요.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대해 사용이 허가 된 테 넌 트의 사용자 에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

관리자는 Office 365 보안 & 준수 센터에서 위치 (작업), 포함 된 사용자 및 제외 된 사용자를 사용자 지정할 수 있습니다. 예를 들어 모든 사용자에 게 Office 365 E3에 대 한 라이선스가 있고 아무도 Office 365 Advanced 규정 준수/E5에 대 한 사용이 허가 되지 않은 경우 조직에 대 한 정보 장벽 정책을 만들 필요가 없습니다. 자세한 내용은 [Microsoft 팀의 정보 장벽](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams)를 참조 하세요.

## <a name="office-365-advanced-message-encryption"></a>Office 365 고급 메시지 암호화

고급 메시지 암호화는 외부 받는 사람에 대 한 보다 유연한 제어 및 암호화 된 전자 메일에 대 한 액세스를 필요로 하는 규정 준수 의무를 충족 합니다. 고급 메시지 암호화를 사용 하는 경우 관리자는 중요 한 정보 유형을 검색할 수 있는 자동 정책 (예: 개인 식별 정보 또는 재무/건강 Id)을 사용 하 여 조직 외부에서 공유 되는 중요 한 전자 메일을 제어할 수 있습니다. 키워드를 사용 하 여 사용자 지정 전자 메일 서식 파일을 적용 하 고 보안 웹 포털을 통해 암호화 된 전자 메일에 대 한 액세스 만료 권한을 적용할 수 있습니다. 또한 관리자는 언제 든 지 액세스를 해지 하 여 보안 웹 포털을 통해 외부에서 액세스 하는 암호화 된 전자 메일을 제어할 수 있습니다.

### <a name="which-users-benefit-from-the-service"></a>어떤 사용자가 서비스를 사용할 수 있나요?

Office 365 E5, microsoft 365 E5, Microsoft 365 E5 규정 준수 및 Office 365 Advanced 준수에 대 한 라이선스가 있는 사용자가 고급 메시지 암호화를 활용할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 이용 하는 방법은 무엇 인가요?

메시지 보낸 사람은 고급 메시지 암호화에서 제공 하는 중요 한 전자 메일에 대 한 추가 된 제어를 활용할 수 있습니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 구축/배포 됩니까?

관리자 메일 흐름 규칙 아래의 Exchange 관리 센터에서 고급 메시지 암호화 정책을 만들고 관리 합니다. 기본적으로이 규칙은 테 넌 트의 모든 사용자에 게 적용 됩니다. 새 메시지 암호화 기능을 설정 하는 방법에 대 한 자세한 내용은 [Set Up Office 365 Message Encryption capabilities](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities)를 참조 하십시오.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대해 사용이 허가 된 테 넌 트의 사용자 에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

관리자는 라이선스가 있는 사용자 에게만 고급 메시지 암호화에 대 한 메일 흐름 규칙을 적용 해야 합니다. 메일 흐름 규칙을 정의 하는 방법에 대 한 자세한 내용은 [Office 365에서 전자 메일 메시지를 암호화 하는 메일 흐름 규칙 정의](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)를 참조 하십시오.
