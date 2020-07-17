---
title: 보안 & 준수에 대 한 Microsoft 365 라이선스 지침
ms.author: v-trscho
author: vtrscho
audience: ITPro
ms.topic: reference
ms.date: 7/13/2020
f1_keywords:
- office-online-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 이 문서에서는 허가 되지 않은 액세스로 인 한 잠재적인 서비스 중단을 방지 하기 위해 Microsoft 365 준수에 대 한 라이선스 지침을 제공 합니다.
ms.openlocfilehash: 18df87a9bf867c68cf4a711c1f6c9f728d2b6655
ms.sourcegitcommit: f3cf76cada0f11efc225c246fff4346910491659
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/15/2020
ms.locfileid: "45137564"
---
# <a name="microsoft-365-licensing-guidance-for-security--compliance"></a>보안 & 준수에 대 한 Microsoft 365 라이선스 지침

이 문서를 사용 하는 경우 테 넌 트 수준 서비스는 테 넌 트 &mdash; 의 모든 사용자에 대해 구매한 경우 (독립 실행형 또는 Office 365 또는 Microsoft 365 요금제의 일부로)이 테 넌 &mdash; 트의 모든 사용자에 대해 전체에서 정품 인증을 받아야 하는 온라인 서비스입니다. 일부 허가 되지 않은 사용자는 기술적으로 서비스에 액세스할 수 있지만,이 경우 서비스에서 혜택을 받으려는 모든 사용자에 게 라이선스가 필요 합니다.

> [!NOTE]
> 일부 테 넌 트 서비스가 현재 특정 사용자에 대 한 혜택을 제한할 수 없습니다. 사용이 허가 된 사용자에 대 한 서비스 혜택을 제한 하기 위해 노력을 기울여야 합니다. 이렇게 하면 사용 가능한 기능을 사용할 수 있게 되 면 조직에 대 한 잠재적 서비스 중단을 방지 하기 위해 도움이 됩니다.

사용자에 게 라이선스를 부여 하기 위한 옵션을 확인 하려면 2020 년 4 월 1 일부 터 Microsoft 365 준수 기능을 활용 하려면 자세한 Microsoft 365 준수 라이선스 비교를 다운로드 하세요. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory ID 보호

Azure Active Directory Id 보호는 조직의 id에 영향을 미치는 잠재적인 취약점을 검색 하 고, 자동화 된 응답을 구성 하 여 조직의 id와 관련 된 의심 스러운 작업을 감지 하 고, 의심 스러운 문제를 조사 하 고 문제를 해결할 수 있는 적절 한 조치를 취할 수 있도록 하는 Azure Active Directory Premium P2 계획의 기능입니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 이용 하는 방법은 무엇 인가요?

SecOps 분석가 및 보안 전문가는 컴퓨터 학습 알고리즘에 따라 플래그가 지정 된 사용자 및 위험 이벤트를 통합 하 여 볼 수 있습니다. 최종 사용자는 위험 기반 조건부 액세스를 통해 제공 되는 자동 보호와 취약성에 따른 향상 된 보안 기능을 활용할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에 게 서비스의 혜택을 받을 수 있는 권한을 제공 하는 라이선스는 무엇입니까?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/a5, Microsoft 365 E5/a5 보안 및 Azure Active Directory Premium 요금제 2는 Azure Active Directory Id 보호를 활용할 수 있는 권한을 사용자에 게 제공 합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 구축/배포 됩니까?

기본적으로 Azure AD Id 보호 기능은 테 넌 트 내의 모든 사용자에 대 한 테 넌 트 수준에서 사용 하도록 설정 됩니다. Azure AD Id 보호에 대 한 자세한 내용은 [Azure Active Directory Id 보호 란?](https://docs.microsoft.com/azure/active-directory/identity-protection/overview-identity-protection) 를 참조 하세요.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대해 사용이 허가 된 테 넌 트의 사용자 에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

관리자는 암호 재설정에 대 한 수준을 정의 하 고 라이선스가 있는 사용자 에게만 액세스를 허용 하는 위험 정책을 할당 하 여 Azure AD Id 보호 범위를 지정할 수 있습니다. Azure AD Id 보호 배포의 범위를 설정 하는 방법에 대 한 자세한 내용은 [로그인 위험 정책 구성을](https://docs.microsoft.com/azure/active-directory/identity-protection/howto-sign-in-risk-policy)참조 하십시오.

## <a name="azure-advanced-threat-protection"></a>Azure Advanced Threat Protection

Azure ATP (Advanced Threat Protection)는 여러 유형의 고급 대상 사이버 공격 및 참가자 위협 으로부터 기업 하이브리드 환경을 보호 하는 클라우드 서비스입니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 이용 하는 방법은 무엇 인가요?

SecOp 분석가 및 보안 전문가는 Azure ATP가 고급 위협, 손상 된 id 및 악의적인 참가자 작업을 검색 하 고 조사 하는 기능을 활용 합니다. 최종 사용자는 Azure ATP에서 데이터를 모니터링 하는 이점이 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에 게 서비스의 혜택을 받을 수 있는 권한을 제공 하는 라이선스는 무엇입니까?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/a5, Microsoft 365 E5/, a5 보안 및 Azure Advanced Threat Protection for Users는 Azure ATP의 혜택을 받을 수 있는 권한을 제공 합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 구축/배포 됩니까?

기본적으로 Azure ATP 기능은 테 넌 트 내의 모든 사용자에 대 한 테 넌 트 수준에서 사용 하도록 설정 됩니다. Azure ATP 구성에 대 한 자세한 내용은 [AZURE atp 인스턴스 만들기](https://docs.microsoft.com/azure-advanced-threat-protection/install-atp-step1)를 참조 하세요.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대해 사용이 허가 된 테 넌 트의 사용자 에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

Azure ATP 서비스가 현재 특정 사용자에 게 기능을 제한할 수 없습니다. 혜택을 받을 모든 사용자에 게 라이선스를 사용 하도록 허가 해야 합니다.

## <a name="office-365-advanced-threat-protection"></a>Office 365 Advanced Threat Protection

ATP (Advanced Threat Protection)를 사용 하면 피싱 및 제로 일 멀웨어와 같은 정교한 공격 으로부터 조직을 보호할 수 있습니다. 또한 ATP는 다양 한 데이터를 식별 하 고 우선 순위를 지정 하 고 잠재적 위협을 해결 하는 방법에 대 한 권장 사항을 제공 하는 데 도움을 주는 일련의 조치를 제공 합니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 이용 하는 방법은 무엇 인가요?

ATP는 피싱 및 제로 일 멀웨어와 같은 복잡 한 공격 으로부터 사용자를 보호 합니다. 계획 1 및 계획 2에 제공 된 서비스의 전체 목록은 [Office 365 Advanced Threat Protection](https://products.office.com/exchange/advance-threat-protection)를 참조 하세요.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에 게 서비스의 혜택을 받을 수 있는 권한을 제공 하는 라이선스는 무엇입니까? 

Office 365 Advanced Threat Protection, Office 365 E5/A5/G5, Microsoft 365 E5/a5/G5, microsoft 365 E5/A5/G5 보안, Microsoft 365 Business Premium 및 2는 Advanced Threat Protection의 혜택을 받을 수 있는 사용자의 권한을 제공 합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 구축/배포 됩니까?

기본적으로 ATP 기능은 테 넌 트 내의 모든 사용자에 대 한 테 넌 트 수준에서 사용 하도록 설정 됩니다. 라이선스가 부여 된 사용자에 대 한 ATP 정책을 구성 하는 방법에 대 한 자세한 내용은 [Office 365 Advanced Threat Protection](https://docs.microsoft.com/office365/securitycompliance/office-365-atp)를 참조 하세요.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대해 사용이 허가 된 테 넌 트의 사용자 에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

ATP 범위를 적용 하려면 안전한 링크 및 안전한 첨부 파일 배포 정책을 따릅니다.

- 라이선스가 부여 된 사용자에 대 한 안전한 링크를 구성 하는 방법에 대 한 자세한 내용은 [Office 365 ATP 안전한 링크 정책 설정을](https://docs.microsoft.com/microsoft-365/security/office-365-security/set-up-atp-safe-links-policies)참조 하십시오.

- 라이선스가 있는 사용자에 대 한 안전한 첨부 파일을 구성 하는 방법에 대 한 자세한 내용은 [Office 365 ATP 안전 첨부 파일 정책 설정을](https://docs.microsoft.com/microsoft-365/security/office-365-security/set-up-atp-safe-attachments-policies)참조 하십시오.

## <a name="office-365-cloud-app-security"></a>Office 365 Cloud App Security

Office 365 Cloud App Security (OCAS)는 Office 365로 제한 되는 기능과 타사 클라우드 앱 및 IaaS 서비스에 대 한 추가 보안을 사용 하지 않고 Microsoft Cloud App Security의 하위 집합입니다.

OCAS 조직이 생산성 클라우드 앱 및 서비스를 확인할 수 있도록 하 고, 사이버 위협을 식별 하 고 해결 하는 정교한 분석을 제공 하며, Office 365에서 데이터를 전송 하는 방법을 제어할 수 있습니다 &mdash; .

기능을 비교 하려면 [Microsoft Cloud App security 및 Office 365 Cloud App security의 차이점](https://docs.microsoft.com/cloud-app-security/editions-cloud-app-security-o365)을 참조 하세요.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 이용 하는 방법은 무엇 인가요?

OCAS 섀도를 검색 하 고, Office 365에서 위협 보호를 제공 하며, 데이터 액세스 권한이 있는 앱을 제어할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에 게 서비스의 혜택을 받을 수 있는 권한을 제공 하는 라이선스는 무엇입니까?

Office 365 E5/A5/G5 사용자가 OCAS의 혜택을 받을 수 있는 권한을 제공 합니다.
자세한 내용은 [Microsoft Cloud App Security License Datasheet](https://www.aka.ms/mcaslicensing)를 참조 하세요.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 구축/배포 됩니까?

기본적으로 OCAS 테 넌 트 내의 모든 사용자에 대 한 테 넌 트 수준에서 사용 하도록 설정 됩니다.

서비스 구성에 대 한 자세한 내용은 [Cloud App Security에 대 한 기본 설정을](https://docs.microsoft.com/cloud-app-security/general-setup)참조 하십시오.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대해 사용이 허가 된 테 넌 트의 사용자 에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

관리자는 특정 앱에 액세스 하는 방법을 적용 하 고 Office 365 Cloud App Security에서 모니터링 되는 사용자 그룹을 제한 하기 위해 OCAS 범위를 배포할 수 있습니다. 자세한 내용은 범위가 지정 된 [배포](https://docs.microsoft.com/cloud-app-security/scoped-deployment)를 참조 하세요.

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

Microsoft Cloud App Security (MCAS)는 조직에 클라우드 앱 및 서비스를 표시 하는 방법을 제공 하는 사이버 (Cloud Access Security Broker) 솔루션으로, 복잡 한 분석을 제공 하 여 모든 클라우드 앱에서 데이터를 전송 하는 방법을 제어할 수 있도록 &mdash; 합니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 이용 하는 방법은 무엇 인가요?

MCAS는 섀도 IT를 감지 및 평가 하 고, 첫 번째 및 타사 클라우드 앱에서의 위협 보호를 제공 하며, 첫 번째 및 타사 클라우드 앱에서 정보를 보호 합니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에 게 서비스의 혜택을 받을 수 있는 권한을 제공 하는 라이선스는 무엇입니까?

MCAS, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/a5/G5, Microsoft 365 E5/a5/G5 Security, microsoft 365 E5/a5/G5 준수, microsoft 365 Information Protection 및 관리 방식 사용자에 게 MCAS에서 혜택을 얻을 수 있는 권한을 제공 합니다.

Azure AD P1은 사용자에 게 MCAS의 검색 기능을 활용할 수 있는 권한을 제공 합니다.

MCAS에서 조건부 Access 앱 제어 기능을 활용 하려면 사용자에 게 Enterprise Mobility + Security E3/A3/G3, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E3/A3/G3, microsoft 365 E5/a5/G5 및 Microsoft 365 E5/a5/G5 Security에 포함 된 Azure Active Directory P1에 대 한 라이선스가 있어야 합니다.

자동 레이블 기능의 이점을 얻으려면 사용자에 게 Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 준수 및 Microsoft 365 정보 보호 및 관리 방식에 포함 된 Azure Information Protection P2에 대 한 라이선스가 있어야 합니다.

자세한 내용은 [Microsoft Cloud App Security License Datasheet](https://www.aka.ms/mcaslicensing)를 참조 하세요.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 구축/배포 됩니까?

기본적으로 MCAS 기능은 테 넌 트 내의 모든 사용자에 대 한 테 넌 트 수준에서 사용 하도록 설정 됩니다.

라이선스가 부여 된 사용자에 대 한 Microsoft Cloud App 보안 정책을 구성 하는 방법에 대 한 자세한 내용은 [Microsoft Cloud App security overview](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security)를 참조 하세요.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대해 사용이 허가 된 테 넌 트의 사용자 에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

관리자는 서비스에서 사용할 수 있는 범위가 지정 된 배포 기능을 사용 하 여 라이선스 사용자에 게 MCAS 배포의 범위를 지정할 수 있습니다. 자세한 내용은 범위가 지정 된 [배포](https://docs.microsoft.com/cloud-app-security/scoped-deployment)를 참조 하세요.

## <a name="microsoft-defender-atp"></a>Microsoft Defender ATP

Microsoft Defender ATP는 위험 기반 취약성 관리 및 평가를 포함 하는 끝점 보안 솔루션입니다. 공격 표면 축소 기능 동작 기반 차세대 차세대 보호 기능 EDR (끝점 검색 및 응답); 자동 조사 및 수정 및 관리 되는 구하기 서비스 자세한 내용은 [Microsoft DEFENDER ATP](https://www.microsoft.com/microsoft-365/windows/microsoft-defender-atp?rtc=1) 페이지를 참조 하세요.

### <a name="which-users-benefit-from-the-service"></a>어떤 사용자가 서비스를 사용할 수 있나요?

Windows 10 Enterprise E5, Windows 10 교육 A5, microsoft 365 E5 (M365 E5), windows 10 Enterprise E5, Microsoft 365 E5 Security, microsoft 365 A5 (M365 A5)를 포함 하 여 microsoft Defender ATP가 혜택을 받을 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 이용 하는 방법은 무엇 인가요?

SecOps 분석가 및 보안 전문가는 Microsoft Defender ATP의 끝점 보안 기능을 통해 예방 기능 보호, 위반 감지, 자동 조사 및 고급 위협에 대 한 응답을 수행 합니다. 최종 사용자는 Microsoft Defender ATP에 의해 모니터링 되는 악성 이벤트를 통해 혜택을 얻을 수 있습니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 구축/배포 됩니까?

기본적으로 Microsoft Defender ATP 기능은 테 넌 트 내의 모든 사용자에 대 한 테 넌 트 수준에서 사용 하도록 설정 됩니다. 배포에 대 한 자세한 내용은 [배포 가이드](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/deployment-phases)를 참조 하세요.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대해 사용이 허가 된 테 넌 트의 사용자 에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

Microsoft Defender ATP 관리자는 [RBAC (역할 기반 액세스 제어)](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/rbac) 를 사용 하 여 보안 운영 팀 내의 역할 및 그룹을 만들어 Microsoft Defender 보안 센터에 적절 한 액세스 권한을 부여할 수 있습니다.

## <a name="information-protection"></a>정보 보호

정보 보호는 조직에서 중요 한 문서와 전자 메일을 검색, 분류, 레이블 지정 하 고 보호 하는 데 도움이 됩니다. 관리자는 레이블을 자동으로 적용 하는 규칙과 조건을 정의 하 고 사용자가 레이블을 적용할 때 권장 사항을 제공 하는 경우에는 레이블을 수동으로 적용 하거나 두 가지를 조합 하 여 사용할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 이용 하는 방법은 무엇 인가요?

사용자는 콘텐츠에 자동으로 민감도 레이블을 적용 하거나 콘텐츠를 자동적으로 분류 하 여 사용할 수 있는 이점을 제공 합니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에 게 서비스의 혜택을 받을 수 있는 권한을 제공 하는 라이선스는 무엇입니까?

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/t/f e t/t/t/f o m/e m t/i m/a m/1/3, Enterprise Mobility + Security F3/E3/E5, Office 365 E5/A5/E3/A3/F3, AIP 요금제 1

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, AIP 계획 1 및 AIP 요금제 2는 power bi에서 민감도 레이블을 적용 및 확인 하 고 Power BI에서 Excel, PowerPoint 또는 PDF로 내보낼 때 데이터를 보호 하는 데 도움이 되는 사용자의 권한을 제공 합니다. 

> [!NOTE]
> Power BI는 Microsoft 365 E5/A5/G5에 포함 되어 있습니다. 다른 모든 계획에서 Power BI는 별도로 사용이 허가 되어야 합니다.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 규정 준수, Microsoft 365 정보 보호 및 관리 방식, office 365 E5, 사무 365 고급 규정 준수, Enterprise Mobility + Security E5 및 AIP 요금제 2는 사용자가 자동 민감도 레이블을 통해 혜택을 얻을 수 있는 권한을 제공 합니다.

라이선스 별 특정 권한에 대 한 자세한 내용은 Microsoft 365 준수 라이선스 비교를 참조 하세요. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx) 기계 학습 (trainable 분류자)을 기반으로 하는 자동 분류에 대 한 권한을 포함 하지 않습니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 구축/배포 됩니까?

기본적으로 정보 보호 기능은 테 넌 트 내의 모든 사용자에 대 한 테 넌 트 수준에서 사용 하도록 설정 됩니다. 라이선스가 있는 사용자에 대 한 정책을 구성 하는 방법에 대 한 자세한 내용은 Azure 권한 관리 활성화를 참조 하십시오.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대해 사용이 허가 된 테 넌 트의 사용자 에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

AIP 스캐너 기능을 사용 하는 경우를 제외 하 고, 특정 그룹 또는 사용자에 게 정책을 지정할 수 있으며, 허가 되지 않은 사용자가 분류 또는 레이블 기능을 실행 하지 못하도록 하기 위해 레지스트리를 편집할 수 있습니다. IP 배포의 범위를 결정 하는 방법에 대 한 자세한 내용은 [Azure Information Protection Policy 구성을](https://docs.microsoft.com/azure/information-protection/configure-policy)참조 하십시오.

AIP 스캐너 기능의 경우 Microsoft는 라이선스가 없는 사용자에 게 파일 분류, 레이블 지정 또는 보호 기능을 제공 하기 위해 커밋하지 않습니다.

## <a name="information-governance"></a>정보 거 버 넌 스

정보 관리 조직은 조직에서 데이터를 검색, 분류, 레이블 지정 하 고 관리 하는 방법으로 위험을 관리할 수 있도록 지원 합니다. 정보 거 버 넌 스에서는 조직이 비즈니스 및 규정 요구 사항을 충족 하 고 Microsoft 365 및 타사 데이터에 보존 및 삭제 기능을 제공 하 여 공격 허점을 줄일 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 이용 하는 방법은 무엇 인가요?

사용자는 보존 목적으로 데이터를 분류 하 여 아래 맞춤 특정 정책 및 규정을 활용할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에 게 서비스의 혜택을 받을 수 있는 권한을 제공 하는 라이선스는 무엇입니까?

Microsoft 365 F3/Business Premium, Office 365 E1/A1/F3 및 독립 실행형 Exchange 계획은 사서함 데이터에 레코드가 아닌 보존 레이블을 수동으로 적용 하 여 이점을 얻을 수 있는 권한을 제공 합니다.

Microsoft 365 F3/F1/Business Premium, Office 365 E1/A1/F3 및 독립 실행형 SharePoint 계획은 SharePoint 또는 OneDrive의 파일에 레코드가 아닌 보존 레이블을 수동으로 적용 하 여 이점을 얻을 수 있는 권한을 제공 합니다. 

Microsoft 365 E5/A5/E3/A3/Business Premium, Office 365 E5/A5/E3/A3, Exchange Online 보관은 사용자에 게 기본 조직 전체 또는 위치 전체 사서함 보존 정책을 통해 혜택을 얻을 수 있는 권한을 제공 하 고, 사서함 데이터에 레코드 없는 보존 레이블을 수동으로 적용 하는 데 사용 됩니다.

Microsoft 365 E5/A5/E3/A3, Office 365 E5/A5/E3/A3, SharePoint 계획 2는 사용자가 기본 SharePoint 또는 OneDrive 보존 정책을 통해 혜택을 얻을 수 있는 권한을 제공 하 고, SharePoint 또는 OneDrive의 파일에 레코드 없는 보존 레이블을 수동으로 적용할 수 있습니다.

Microsoft 365 E5/A5/E3/A3, Office 365 E5/A5/E3/A3은 팀 보존 정책을 활용할 수 있는 권한을 사용자에 게 제공 합니다.

Microsoft 365 E5/A5, Microsoft 365 E5/A5 규정 준수, Microsoft 365 정보 보호 및 관리 방식, Office 365 E5/A5, Office 365 고급 규정은 사용자가 보존 레이블 또는 정책을 자동으로 적용 하 여 혜택을 얻을 수 있는 권한을 제공 합니다. 기본 보존 레이블 또는 정책을 적용 하 고, 사용자 지정 이벤트를 기반으로 보존 레이블의 보존 기간을 시작 하 고, 기본 데이터 커넥터를 통해 타사 데이터를 가져오고, 파일 a 레코드를 선언 하 고, 레이블이 지정 된 콘텐츠를 검색 하 고, 레이블 작업을 모니터링 합니다.

Microsoft 365 E5/A5, Microsoft 365 E5/A5 준수, Microsoft 365 정보 보호 및 관리 방식에서는 trainable 분류자에 따라 보존 레이블을 자동으로 적용 하 여 혜택을 얻을 수 있는 권한을 제공 합니다.

라이선스 별 특정 권한에 대 한 자세한 내용은 Microsoft 365 준수 라이선스 비교를 참조 하세요. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 구축/배포 됩니까?

기본적으로 정보 관리 기능은 테 넌 트 내의 모든 사용자에 대 한 테 넌 트 수준에서 사용 하도록 설정 됩니다. 사용이 허가 된 사용자에 대 한 자동 레이블 및 정책을 적용 하기 위한 정보 관리 기능을 구성 하는 방법에 대 한 자세한 내용은 [Manage Information 지배](https://docs.microsoft.com/microsoft-365/compliance/manage-information-governance)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대해 사용이 허가 된 테 넌 트의 사용자 에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

정보 거 버 넌 스는 특정 위치 (팀 사이트, 그룹 사이트 등)의 사용이 허가 된 사용자에 게 적용할 수 있습니다. 사용이 허가 된 사용자에 대 한 자동 레이블 및 정책을 적용 하기 위한 정보 관리 기능을 구성 하는 방법에 대 한 자세한 내용은 [Manage Information 지배](https://docs.microsoft.com/microsoft-365/compliance/manage-information-governance)

## <a name="records-management"></a>레코드 관리

레코드 관리 조직에서는 Microsoft 365 및 타사 데이터에 대해 검색, 분류, 레이블 지정, 보존 및 defensible 삭제 기능을 통해 비즈니스 및 규정을 준수 하는 책임을 지 원하는 조직을 지원 합니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에 게 서비스의 혜택을 받을 수 있는 권한을 제공 하는 라이선스는 무엇입니까?

Microsoft 365 E5/A5, Microsoft 365 E5/A5 규정 준수, Microsoft 365 정보 보호 및 관리, office 365 E5/a5, Office 365 고급 규정은 사용자에 게 항목을 레코드로 선언, 자동으로 보존을 적용 하 고, 처리 검토 프로세스를 실행 (trainable 분류자를 기반으로 보존 레이블 자동 적용 제외) 하 여 레코드 관리를 활용할 수 있는 권한을 제공 합니다.

Microsoft 365 E5/A5, Microsoft 365 E5/A5 준수, Microsoft 365 정보 보호 및 관리 방식에서는 trainable 분류자에 따라 자동으로 보존을 적용 하거나 레이블을 녹음할 때 혜택을 받을 수 있는 권한을 사용자에 게 제공 합니다.

라이선스 별 특정 권한에 대 한 자세한 내용은 Microsoft 365 준수 라이선스 비교를 참조 하세요. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 이용 하는 방법은 무엇 인가요?

사용자는 콘텐츠를 레코드로 선언 하 고 defensible 삭제를 통해 정책 정의 및 선언 으로부터 전체 레코드 프로세스를 관리할 수 있습니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 구축/배포 됩니까?

기본적으로 레코드 관리 기능은 테 넌 트 내의 모든 사용자에 대 한 테 넌 트 수준에서 사용 하도록 설정 됩니다. 라이선스가 있는 사용자에 대해 적용할 레코드 관리 구성에 대 한 자세한 내용은 [Microsoft 365의 레코드 관리](https://docs.microsoft.com/microsoft-365/compliance/records-management)를 참조 하세요.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대해 사용이 허가 된 테 넌 트의 사용자 에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

레코드 관리 기능은 특정 위치 (팀 사이트, 그룹 사이트 등)의 사용이 허가 된 사용자에 게 적용할 수 있습니다. 라이선스가 있는 사용자에 대해 적용할 레코드 관리 구성에 대 한 자세한 내용은 [Microsoft 365의 레코드 관리](https://docs.microsoft.com/microsoft-365/compliance/records-management)를 참조 하세요.

## <a name="ediscovery"></a>eDiscovery

eDiscovery는 Microsoft 365 시스템에서 수출 하기 전에 조사 또는 소송에 관련 된 콘텐츠를 식별, 수집, 보존, 절감 및 검토 하기 위한 IT 및 법률 부서를 위한 조사 및 eDiscovery 솔루션을 제공 합니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 이용 하는 방법은 무엇 인가요?

사용자가 사례에 대 한 데이터 custodian (문서 또는 전자 파일을 관리 하는 사용자가 있는 사람)로 선택 된 경우 고급 eDiscovery의 이점이 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에 게 서비스의 혜택을 받을 수 있는 권한을 제공 하는 라이선스는 무엇입니까?

Microsoft 365 E5/A5/G5/E3/A3/G3, Office 365 E5/a5/G5/E3/A3/G3 및 Office 365 Advanced 준수는 사용자에 게 핵심 eDiscovery를 활용할 수 있는 권한을 제공 합니다.
Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 규정 준수, Microsoft 365 E5/A5 eDiscovery 및 감사, Office 365 E5/a5/G5 및 Office 365 Advanced 준수는 고급 eDiscovery에서 혜택을 받을 수 있는 권한을 사용자에 게 제공 합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 구축/배포 됩니까?

기본적으로 고급 eDiscovery 기능은 관리자가 보안 & 준수 센터에서 eDiscovery 권한을 할당할 때 테 넌 트 내의 모든 사용자에 대 한 테 넌 트 수준에서 사용 하도록 설정 됩니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대해 사용이 허가 된 테 넌 트의 사용자 에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

eDiscovery 관리자는 [고급 ediscovery에 Custodians 추가](https://docs.microsoft.com/microsoft-365/compliance/add-custodians-to-case)에 설명 된 대로 고급 ediscovery의 기본 제공 custodian 관리 도구를 사용 하 여 특정 사용자를 대/소문자를 구분 하는 데이터 custodians으로 선택할 수 있습니다.

## <a name="office-365-customer-key"></a>Office 365 고객 키

고객 키를 사용 하 여 조직의 암호화 키를 제어 하 고 Microsoft 데이터 센터의 휴지 상태에서 데이터를 암호화 하는 데 사용할 수 있도록 Office 365를 구성 합니다. 즉, 고객 키를 사용 하 여 사용자가 자신의 키를 통해 자신에 게 속하는 암호화 계층을 추가할 수 있습니다. 휴지 상태의 데이터에는 SharePoint Online 및 비즈니스용 OneDrive 내의 사서함 및 파일에 저장 된 Exchange Online 및 비즈니스용 Skype의 데이터가 포함 됩니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 이용 하는 방법은 무엇 인가요?

사용자는 자체 조직에서 제공, 제어 및 관리 되는 암호화 키를 사용 하 여 응용 프로그램 계층에서 데이터를 보관 된 상태로 유지 하 여 고객 키를 활용할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에 게 서비스의 혜택을 받을 수 있는 권한을 제공 하는 라이선스는 무엇입니까?

Microsoft 365 E5/A5, Microsoft 365 E5/A5 규정 준수, Microsoft 365 정보 보호 및 관리 방식, Office 365 E5/A5, Office 365 고급 규정은 사용자에 게 고객 키를 활용할 수 있는 권한을 제공 합니다. 고객 키의 모든 이점을 얻으려면 Azure Key Vault 용 구독도 있어야 합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 구축/배포 됩니까?

Office 365 고객 키 암호화 키를 Exchange Online 및 비즈니스용 Skype 사서함, SharePoint Online, 비즈니스용 OneDrive 및 팀 파일에 저장 된 모든 데이터에 대해 사용 하도록 설정할 수 있습니다. 시작 하는 방법을 포함 하 여 Office 365 고객 키에 대 한 자세한 내용은 [office 365의 고객 키를 사용한 서비스 암호화](https://docs.microsoft.com/microsoft-365/compliance/customer-key-overview)를 참조 하세요.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대해 사용이 허가 된 테 넌 트의 사용자 에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

사용이 허가 된 사용자에 대해 Office 365 및/또는 Microsoft 365 조직 내의 데이터에 암호화 키를 할당 하려면 고객 키 암호화 키 배포 지침을 따릅니다.

- SharePoint Online, 비즈니스용 OneDrive 및 팀 파일의 경우 하나 이상의 사이트에 있는 파일을 고객 키를 사용 하 여 암호화할 수 있습니다.

- Exchange Online 및 비즈니스용 Skype의 경우에는 고객 키를 사용 하 여 사서함을 암호화할 수 있습니다.

## <a name="office-365-customer-lockbox"></a>Office 365 고객 Lockbox

고객 Lockbox는 서비스 작업에 대 한 명시적 액세스 권한 부여를 제공 하는 기능을 고객에 게 제공 하 여 추가 제어 계층을 제공할 수 있습니다. 고객 Lockbox는 명시적 데이터 액세스 권한 부여를 위한 절차를 마련 하 여 조직이 HIPAA 및 FEDRAMP와 같은 특정 준수 의무를 충족 하는 데도 도움이 될 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 이용 하는 방법은 무엇 인가요?

사용자는 고객 Lockbox의 혜택을 통해 고객의 명시적 승인 없이 서비스 작업을 수행 하기 위해 Microsoft의 콘텐츠에 액세스할 수 없도록 합니다. 고객 Lockbox는 고객에 게 콘텐츠에 액세스 하기 위한 요청에 대 한 승인 워크플로를 제공 합니다. 때로는 지원 프로세스 중에 Microsoft 엔지니어가 고객이 보고 한 문제를 해결 하 고 문제를 해결 하는 데 사용 되는 경우가 있습니다. 대부분의 경우 문제는 Microsoft에서 서비스를 위해 마련 된 광범위 한 원격 분석 및 디버깅 도구를 통해 수정 됩니다. 그러나 Microsoft 엔지니어가 고객 콘텐츠에 액세스 하 여 근본적인 원인을 확인 하 고 문제를 해결 해야 하는 경우가 있을 수 있습니다. 고객 Lockbox에 게는 승인 워크플로의 최종 단계로 고객의 액세스를 요청 하는 엔지니어가 필요 합니다. 이를 통해 조직에서는 이러한 요청을 승인 하거나 거부 하는 옵션을 제공 하므로 Microsoft 엔지니어가 조직의 최종 사용자 데이터에 액세스할 수 있는지 여부를 직접 제어할 수도 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에 게 서비스의 혜택을 받을 수 있는 권한을 제공 하는 라이선스는 무엇입니까?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 준수, microsoft 365 참가자 위험 관리 및 Office 365 고급 규정은 사용자에 게 고객 Lockbox의 혜택을 받을 수 있는 권한을 제공 합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 구축/배포 됩니까?

관리자는 Microsoft 365 관리 센터에서 고객 Lockbox 컨트롤을 켤 수 있습니다. 자세한 내용은 [Office 365의 고객 Lockbox](https://docs.microsoft.com/microsoft-365/compliance/customer-lockbox-requests)를 참조 하세요. 고객 Lockbox가 설정 된 경우 Microsoft는 해당 콘텐츠에 액세스 하기 전에 조직의 승인을 받아야 합니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대해 사용이 허가 된 테 넌 트의 사용자 에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

Microsoft는 조직의 사용자에 대 한 고객 Lockbox 액세스 제어 승인 요청을 제공 합니다.

## <a name="privileged-access-management-in-office-365"></a>Office 365의 권한 있는 액세스 관리

[PAM (권한 부여 관리)](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-configuration) 기능은 Office 365의 권한 있는 관리 작업에 대 한 세부적인 액세스 제어를 제공 합니다. PAM을 사용 하도록 설정한 후에는 사용자가 상승 및 권한 작업을 완료 하기 위해 범위가 높고 시간이 제한 된 승인 워크플로를 통해 just-in-time 액세스를 요청 해야 합니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 이용 하는 방법은 무엇 인가요?

PAM을 사용 하도록 설정 하면 조직에서 권한이 없는 상태로 작동할 수 있습니다. 사용자는 unfettered에 대 한 액세스를 제공 하는 관리 액세스에서 발생 하는 취약성에 대해 추가 된 방어 계층을 활용할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에 게 서비스의 혜택을 받을 수 있는 권한을 제공 하는 라이선스는 무엇입니까? 

Office 365 E5/A5, Microsoft 365 E5/a5, Microsoft 365 E5/a5 준수, Microsoft 365 E5/A5 정보 보호 및 거 버 넌 사용자에 게 PAM의 혜택을 받을 수 있는 권한을 제공 합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 구축/배포 됩니까?

기본적으로 PAM 기능은 테 넌 트 내의 모든 사용자에 대 한 테 넌 트 수준에서 사용 하도록 설정 됩니다. PAM 정책 구성에 대 한 자세한 내용은 [권한이 부여 된 액세스 관리 시작](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-configuration)을 참조 하세요.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대해 사용이 허가 된 테 넌 트의 사용자 에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

고객은 승인자 그룹 및 액세스 정책을 통해 사용자 단위로 PAM을 관리할 수 있으며,이는 라이선스가 있는 사용자에 게 적용할 수 있습니다. 자세한 내용은 [Office 365의 권한이 부여 된 액세스 관리](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751)를 참조 하세요.

## <a name="office-365-data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Exchange Online, SharePoint Online 및 비즈니스용 OneDrive에 대 한 Office 365 데이터 손실 방지

Exchange Online, SharePoint Online 및 비즈니스용 OneDrive에 대 한 Office 365 DLP (데이터 손실 방지)를 사용 하면 조직에서 전자 메일 및 파일 (Microsoft 팀 파일 리포지토리에 저장 된 파일 포함) 간의 중요 한 정보를 식별, 모니터링 및 자동으로 보호할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 이용 하는 방법은 무엇 인가요?

사용자는 Exchange Online, SharePoint Online 및 비즈니스용 OneDrive (조직의 DLP 정책에 구성 된 대로 중요 한 정보에 대 한 전자 메일 및 파일을 검사 하는 경우)에 대 한 DLP를 활용할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에 게 서비스의 혜택을 받을 수 있는 권한을 제공 하는 라이선스는 무엇입니까?

Microsoft 365 A1/E3/A3/Business, Office 365 E3/A3 및 Office 365 데이터 손실 방지는 사용자에 게 Exchange Online, SharePoint Online 및 비즈니스용 OneDrive에 대 한 Office 365 DLP의 혜택을 받을 수 있는 권한을 제공 합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 구축/배포 됩니까?

기본적으로 Exchange Online 전자 메일, SharePoint 사이트 및 OneDrive 계정은 테 넌 트 내의 모든 사용자에 대 한 이러한 DLP 기능에 대해 *사용 하도록 설정 된 위치 (작업)* 입니다. DLP 정책을 사용 하는 방법에 대 한 자세한 내용은 [Overview For data 손실 방지](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies)를 참조 하십시오.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대해 사용이 허가 된 테 넌 트의 사용자 에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

관리자는 보안 & 준수 센터의 **데이터 손실 방지**위치에서 위치 (작업), 포함 된 사용자 및 제외 된 사용자를 사용자 지정할 수 있습니다  >  **Locations**.

## <a name="communication-data-loss-prevention-for-teams"></a>팀에 대 한 통신 데이터 손실 방지

팀에 대 한 통신 DLP를 사용 하면 조직에서 금융 정보, 개인 식별 정보, 상태 관련 정보 또는 기타 기밀 정보와 같은 중요 한 정보를 포함 하는 채팅 및 채널 메시지를 차단할 수 있습니다.

### <a name="which-users-benefit-from-the-service"></a>어떤 사용자가 서비스를 사용할 수 있나요?

Office 365 E5/A5, Microsoft 365 E5/A5, Microsoft 365, 정보 보호 및 관리 및 Office 365 Advanced 준수를 사용 하도록 허가 된 사용자는 팀에 대 한 통신 DLP를 활용할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 이용 하는 방법은 무엇 인가요?

보내는 채팅 및 채널 메시지에 중요 한 정보가 조직의 DLP 정책에 구성 된 대로 중요 한 정보를 검사 하 여 보낸 사람 혜택을 받을 수 있습니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 구축/배포 됩니까?

팀 채팅 및 채널 메시지는 기본적으로 테 넌 트 내의 모든 사용자에 대 한 이러한 DLP 기능에 대해 *사용 하도록 설정 된 위치 (작업)* 입니다. DLP 정책을 사용 하는 방법에 대 한 자세한 내용은 [Overview For data 손실 방지](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)를 참조 하십시오.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대해 사용이 허가 된 테 넌 트의 사용자 에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

관리자는 보안 & 준수 센터의 **데이터 손실 방지**위치에서 위치 (작업), 포함 된 사용자 및 제외 된 사용자를 사용자 지정할 수 있습니다  >  **Locations**.

## <a name="information-barriers"></a>정보 장벽

정보 장애물은 관리자가 개인 또는 그룹이 서로 통신 하지 못하도록 하기 위해 구성할 수 있는 정책입니다. 예를 들어, 한 부서가 다른 부서와 공유 하지 않아야 하는 정보를 처리 하거나, 그룹이 외부 대화 상대와 통신 하지 못하도록 해야 하는 경우에 유용 합니다. 정보 장벽 정책 역시 조회 및 검색을 방지 합니다. 즉, 통신 하지 않아야 하는 사람과 통신을 시도 하는 경우 사용자 선택에 해당 사람이 검색 되지 않습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 이용 하는 방법은 무엇 인가요?

사용자가 다른 사람과 통신 하지 못하도록 제한 되 면 정보 장벽에 대 한 고급 규정 준수 기능의 이점을 활용할 수 있습니다. 예시:

| 시나리오 | 라이선스가 필요한 사용자 |
|:-------|:------|
| 두 그룹 (그룹 1 및 그룹 2)은 서로 통신할 수 없으며, 그룹 1 사용자는 그룹 2 명의 사용자와 통신 하지 못하도록 제한 되며, 그룹 2 사용자는 그룹 1 명의 사용자와 통신 하는 것이 제한 됩니다. | 그룹 1 및 그룹 2의 사용자 ||

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에 게 서비스의 혜택을 받을 수 있는 권한을 제공 하는 라이선스는 무엇입니까?

Microsoft 365 E5/A5, Microsoft 365 E5/A5 준수, Microsoft 365 참가자 위험 관리, Office 365 E5/A5 및 Office 365 고급 규정은 정보 장벽에서 혜택을 얻을 수 있는 권한을 사용자에 게 제공 합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 구축/배포 됩니까?

관리자 보안 & 준수 센터에서 PowerShell cmdlet을 사용 하 여 정보 장벽 정책을 만들고 관리 합니다. 정보 장벽 정책을 만들려면 관리자에 게 Microsoft 365 Enterprise Global Administrator, Office 365 전역 관리자 또는 준수 관리자 역할을 할당 받아야 합니다. 기본적으로이 정책은 테 넌 트의 모든 사용자에 게 적용 됩니다. 정보 장벽에 대 한 자세한 내용은 [Microsoft 팀의 정보 장벽](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams)를 참조 하세요.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대해 사용이 허가 된 테 넌 트의 사용자 에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

관리자는 보안 & 준수 센터에서 위치 (작업), 포함 된 사용자 및 제외 된 사용자를 사용자 지정할 수 있습니다. 예를 들어 모든 사용자에 게 Office 365 E3에 대 한 라이선스가 있고 아무도 Office 365 Advanced 규정 준수/E5에 대 한 사용이 허가 되지 않은 경우 조직에 대 한 정보 장벽 정책을 만들 필요가 없습니다. 자세한 내용은 [Microsoft 팀의 정보 장벽](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams)를 참조 하세요.

## <a name="office-365-message-encryption"></a>Office 365 메시지 암호화

OME(Office 365 메시지 암호화)는 Azure RMS(권한 관리)를 기반으로 구축된 서비스로, 대상의 전자 메일 주소(Gmail, Yahoo! Mail, Outlook.com 등)에 상관없이 사용자 조직 내부 또는 외부 사람에게 암호화된 전자 메일을 보낼 수 있습니다.

암호화된 메시지를 보려면 받는 사람이 일회용 암호를 얻어 Microsoft 계정에 로그인하거나 Office 365와 연결된 회사 또는 학교 계정을 사용하여 로그인할 수 있습니다. 받는 사람은 암호화된 회신을 보낼 수도 있습니다. 암호화 된 메시지를 보거나 암호화 된 회신을 보내기 위해 구독을 할 필요가 없습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 이용 하는 방법은 무엇 인가요?

메시지 보낸 사람이 Office 365 메시지 암호화에서 제공 하는 중요 한 전자 메일에 대 한 추가 된 제어 혜택을 받을 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에 게 서비스의 혜택을 받을 수 있는 권한을 제공 하는 라이선스는 무엇입니까?

Microsoft 365 E3/A3, Office 365 E3/A3 및 Azure Information Protection 계획 1 사용자에 게 Office 365 메시지 암호화의 혜택을 받을 수 있는 권한을 제공 합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 구축/배포 됩니까?

관리자 **메일 흐름**규칙 아래의 Exchange 관리 센터에서 Office 365 메시지 암호화 정책을 만들고 관리  >  **Rules**합니다. 기본적으로이 규칙은 테 넌 트의 모든 사용자에 게 적용 됩니다. 새 Office 365 메시지 암호화 기능을 설정 하는 방법에 대 한 자세한 내용은 [Set Up office 365 Message encryption capabilities](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities)를 참조 하십시오.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대해 사용이 허가 된 테 넌 트의 사용자 에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

관리자는 라이선스가 있는 사용자 에게만 Office 365 메시지 암호화에 대 한 메일 흐름 규칙을 적용 해야 합니다. 메일 흐름 규칙을 정의 하는 방법에 대 한 자세한 내용은 [Office 365에서 전자 메일 메시지를 암호화 하는 메일 흐름 규칙 정의](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)를 참조 하십시오.

## <a name="office-365-advanced-message-encryption"></a>Office 365 고급 메시지 암호화

Office 365 고급 메시지 암호화는 외부 받는 사람에 대 한 보다 유연한 제어 및 암호화 된 전자 메일에 대 한 액세스를 필요로 하는 규정 준수 의무를 충족 하도록 지원 합니다 고급 메시지 암호화를 사용 하면 관리자가 중요 한 정보 유형 (예: 개인 식별 정보 또는 재무/건강 Id)을 검색할 수 있는 자동 정책을 사용 하 여 조직 외부에서 공유 되는 중요 한 전자 메일을 제어 하거나, 키워드를 사용 하 여 사용자 지정 전자 메일 템플릿과 안전한 웹 포털을 통해 암호화 된 전자 프로그램에 대 한 액세스 만료를 적용 함으로써 보호 기능을 향상 또한 관리자는 언제 든 지 액세스를 해지 하 여 보안 웹 포털을 통해 외부에서 액세스 하는 암호화 된 전자 메일을 제어할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 이용 하는 방법은 무엇 인가요?

메시지 보낸 사람은 고급 메시지 암호화에서 제공 하는 중요 한 전자 메일에 대 한 추가 된 제어를 활용할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에 게 서비스의 혜택을 받을 수 있는 권한을 제공 하는 라이선스는 무엇입니까?

Office 365 E5/A5, Microsoft 365 E5/a5, Microsoft 365 E5/A5 준수, Microsoft 365 Information Protection and 거 버 넌 스 및 Office 365 고급 규정 준수 고급 메시지 암호화를 활용할 수 있는 권한을 사용자에 게 제공 합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 구축/배포 됩니까?

관리자 메일 흐름 규칙 아래의 Exchange 관리 센터에서 고급 메시지 암호화 정책을 만들고 관리 합니다. 기본적으로이 규칙은 테 넌 트의 모든 사용자에 게 적용 됩니다. 새 메시지 암호화 기능을 설정 하는 방법에 대 한 자세한 내용은 [Set Up Office 365 Message Encryption capabilities](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities)를 참조 하십시오.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대해 사용이 허가 된 테 넌 트의 사용자 에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

관리자는 라이선스가 있는 사용자 에게만 고급 메시지 암호화에 대 한 메일 흐름 규칙을 적용 해야 합니다. 메일 흐름 규칙을 정의 하는 방법에 대 한 자세한 내용은 [Office 365에서 전자 메일 메시지를 암호화 하는 메일 흐름 규칙 정의](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)를 참조 하십시오.

## <a name="communication-compliance"></a>커뮤니케이션 규정 준수

Microsoft 365의 통신 준수 기능은 조직의 부적절 한 메시지에 대 한 검색, 캡처 및 수정 작업 수행을 지원 하 여 통신 위험을 최소화 하는 데 도움이 됩니다. 조직의 내부 및 외부 전자 메일, Microsoft 팀 또는 타사 통신을 캡처하는 특정 정책을 정의할 수 있습니다. 검토자가 조직의 메시지 표준을 준수 하는지 확인 하기 위해 적절 한 수정 작업을 수행할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 이용 하는 방법은 무엇 인가요?

준수 전문가는 통신 준수 정책에 따라 조직 통신을 모니터링 하는 방식으로 서비스를 활용할 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에 게 서비스의 혜택을 받을 수 있는 권한을 제공 하는 라이선스는 무엇입니까?

Office 365 E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 준수, Microsoft 365 Insider it 관리에서는 사용자에 게 통신 준수를 활용할 수 있는 권한을 제공 합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 구축/배포 됩니까?

관리자 및 규정 준수 전문가는 Microsoft 365 준수 센터에서 통신 준수 정책을 만듭니다. 이러한 정책은 조직의 검토 대상이 되는 통신 및 사용자를 정의 하 고, 통신이 충족 해야 하는 사용자 지정 조건을 정의 하 고, 검토를 수행할 사용자를 지정 합니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대해 사용이 허가 된 테 넌 트의 사용자 에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

관리자 통신 준수 정책에 포함할 특정 사용자 또는 그룹을 선택 합니다. 그룹을 선택 하는 경우에는 그룹의 특정 사용자를 통신 준수 정책에서 제외할 수도 있습니다. 통신 준수 정책에 대 한 자세한 내용은 [Microsoft 365의 통신 준수](https://docs.microsoft.com/microsoft-365/compliance/communication-compliance-configure)를 참조 하세요.

## <a name="insider-risk-management"></a>내부자 위험 관리

참가자 위험 관리는 조직에서 위험한 활동을 감지 하 고 조사 하며 조치를 취할 수 있도록 하 여 내부 위험을 최소화 하는 Microsoft 365의 솔루션입니다.
사용자 지정 정책을 사용 하면 필요한 경우 Microsoft Advanced eDiscovery로 사례를 확대 하는 것을 포함 하 여 조직에서 악의적이 고 실수로 위험한 활동을 검색 하 고 작업을 수행할 수 있습니다. 조직의 위험 분석가는 사용자가 조직의 규정 준수 표준을 준수 하도록 하기 위해 적절 한 조치를 취할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 이용 하는 방법은 무엇 인가요?

사용자는 위험에 대 한 활동을 모니터링 하 여 이점을 누릴 수 있습니다.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>사용자에 게 서비스의 혜택을 받을 수 있는 권한을 제공 하는 라이선스는 무엇입니까?

Microsoft 365 E5/A5, Microsoft 365 E5/A5 준수, Microsoft 365 참가자 위험 관리를 통해 사용자에 게 참가자 위험 관리의 이점을 누릴 수 있는 권한을 제공 합니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 구축/배포 됩니까?

참가자 위험 관리 정책을 Microsoft 365 준수 센터에서 만들고 사용자에 게 할당 해야 합니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대해 사용이 허가 된 테 넌 트의 사용자 에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

Microsoft 365 준수 센터에서 정책을 만들 때 **사용자 및 그룹 선택** 페이지에서 **사용자 또는 그룹** 선택을 선택 하 여 허가 된 사용자만 선택 하거나, 모든 사용자에 게 라이선스가 부여 되어 있는 경우 **모든 사용자 및 메일 사용 가능 그룹** 확인란을 선택할 수 있습니다. 자세한 내용은 [참가자 위험 관리 시작 하기](https://docs.microsoft.com/microsoft-365/compliance/insider-risk-management-configure)를 참조 하세요.

## <a name="conditional-access-policies"></a>조건부 액세스 정책

조건부 액세스는 Azure Active Directory에서 신호를 함께 가져오고 결정을 내리고 조직 정책을 적용 하는 데 사용 되는 도구입니다. 조건부 액세스는 id 기반 제어 평면의 핵심입니다. 조건부 액세스 정책 가장 간단한 방법은 if 문으로 사용 하는 것입니다. 사용자가 리소스에 액세스 하려는 경우에는 작업을 완료 해야 합니다. 예: 급여 관리자가 급여 응용 프로그램에 액세스 하려는 경우에는 다단계 인증을 수행 하 여 액세스 하는 데 필요 합니다.

### <a name="which-users-benefit-from-the-service"></a>어떤 사용자가 서비스를 사용할 수 있나요?

Enterprise Mobility + Security E3/A3, Microsoft 365 F3/E3/A3/Business Premium 및 Azure Active Directory Premium 요금제 1의 라이선스가 있는 사용자는 조건부 액세스 정책이 도움이 될 수 있습니다. Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5, Microsoft E5 Security 및 Azure Active Directory Premium 요금제 2의 라이선스가 있는 사용자는 Id 보호 (위험 기반 조건부 액세스 정책)를 활용할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 이용 하는 방법은 무엇 인가요?

보안 작업 분석가 및 보안 전문가는 회사 콘텐츠에 대 한 액세스 권한을 부여 하기 전에 특정 기준을 충족 해야 하는 조직 정책을 사용자에 게 적용할 수 있는 기능을 통해 혜택을 제공 합니다. 최종 사용자는 조직의 자산을 보호 하면서 언제 어디서 나 언제 든 지 작업에 액세스할 수 있게 됩니다.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 구축/배포 됩니까?

기본적으로 조건부 액세스 기능은 테 넌 트 내의 모든 사용자에 대 한 테 넌 트 수준에서 사용 하도록 설정 됩니다.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대해 사용이 허가 된 테 넌 트의 사용자 에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

Id 보호 및 조건부 액세스에 대 한 구체적인 경우 사용자를 그룹에 포함 하거나 조건부 액세스 정책에 추가 해야 합니다. 조건부 액세스 정책에서 사용자 및 그룹 조건은 필수입니다. 정책에서 **모든 사용자** 또는 특정 사용자 및 그룹을 선택할 수 있습니다. 적절 하 게 허가 된 사용자 및 그룹만 선택 해야 합니다. 자세한 내용은 [Azure Active Directory 조건부 액세스의 조건](https://docs.microsoft.com/azure/active-directory/conditional-access/conditions)를 참조 하세요.

## <a name="advanced-audit"></a>고급 감사

Microsoft 365의 고급 감사는 사용자 및 관리 작업에 대 한 감사 로그를 1 년 동안 보존 하 고, 다른 Microsoft 365 서비스에 대 한 감사 로그 보존을 관리 하기 위한 사용자 지정 감사 로그 보존 정책을 만들 수 있는 기능을 제공 합니다. 또한 Office 365 관리 활동 API에 대 한 조사 및 고대역폭 액세스에 대 한 중요 한 이벤트에 대 한 액세스를 제공 합니다. 자세한 내용은 [Microsoft 365의 고급 감사](https://docs.microsoft.com/microsoft-365/compliance/advanced-audit)를 참조 하세요.

### <a name="which-users-benefit-from-the-service"></a>어떤 사용자가 서비스를 사용할 수 있나요?

Office 365 E5, microsoft 365 E5, Microsoft 365 E5 규정 준수 및 Microsoft 365 eDiscovery 및 감사의 라이선스가 있는 사용자가 고급 감사를 활용할 수 있습니다.

### <a name="how-do-users-benefit-from-the-service"></a>사용자가 서비스를 이용 하는 방법은 무엇 인가요?

Microsoft 365 서비스의 사용자 작업과 관련 된 감사 레코드를 최대 1 년까지 보유할 수 있으므로 고급 감사의 사용자에 게는 장점이 있습니다. 또한 높은 값 감사 이벤트는 사용자 사서함의 항목에 액세스 하거나 읽을 때와 같이 기록 됩니다. 자세한 내용은 [Microsoft 365의 고급 감사](https://docs.microsoft.com/microsoft-365/compliance/advanced-audit)를 참조 하세요.

### <a name="how-is-the-service-provisioneddeployed"></a>서비스는 어떻게 구축/배포 됩니까?

기본적으로 고급 감사는 Office 365 또는 Microsoft 365 E5 구독이 있는 모든 조직에 대 한 테 넌 트 수준에서 사용 하도록 설정 되며, Azure Active Directory, Exchange 및 SharePoint에서 해당 라이선스가 있는 사용자가 수행 하는 작업에 대 한 감사 로그를 1 년 동안 자동으로 보존 합니다. 또한 조직에서는 감사 로그 보존 정책을 사용 하 여 다른 Microsoft 365 서비스의 활동에 의해 생성 된 감사 레코드의 보존 기간을 관리할 수 있습니다. 자세한 내용은 [감사 로그 보존 정책 관리](https://docs.microsoft.com/microsoft-365/compliance/audit-log-retention-policies)를 참조하십시오.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>서비스에 대해 사용이 허가 된 테 넌 트의 사용자 에게만 서비스를 적용할 수 있는 방법은 무엇입니까?

1 년의 감사 로그 보존 및 중요 한 이벤트 감사는 해당 라이선스가 있는 사용자 에게만 적용 됩니다. 또한 관리자는 감사 로그 보존 정책을 사용 하 여 특정 사용자의 감사 로그에 대해 더 짧은 보존 기간을 지정할 수 있습니다.
