---
title: Azure Information Protection 서비스 설명
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
description: Microsoft Azure AIP(정보 보호)를 사용하면 조직에서 중요한 문서 및 전자 메일을 검색, 분류, 레이블 지정 및 보호할 수 있습니다.
ms.openlocfilehash: 5fb4d05ffdfaaa2ff3e4c3743f2837c9f54f8009
ms.sourcegitcommit: abe0415471c224a3d6a1d2f1317b08f67166ba11
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/24/2022
ms.locfileid: "64403958"
---
# <a name="azure-information-protection-service-description"></a>Azure Information Protection 서비스 설명

Microsoft Azure AIP(정보 보호)를 사용하면 조직에서 중요한 문서 및 전자 메일을 검색, 분류, 레이블 지정 및 보호할 수 있습니다. 관리자는 레이블을 자동으로 적용하는 규칙 및 조건을 정의하거나, 사용자가 레이블을 수동으로 적용하거나, 두 가지 조합을 사용할 수 있습니다. 여기서 사용자에게 레이블 적용에 대한 권장 사항이 제공될 수 있습니다. 또한 사용자는 콘텐츠에 민감도 레이블을 수동으로 적용하거나 콘텐츠를 자동으로 분류하여 이점을 제공합니다. 자세한 내용은 [Azure Information Protection이란?을 참조하세요.](/azure/information-protection/what-is-information-protection)

## <a name="available-plans"></a>사용 가능한 플랜

Microsoft Azure Information Protection은 독립 실행형 또는 다음 Microsoft 라이선스 제품군 중 하나를 통해 구입할 수 있습니다. Microsoft 365 Enterprise 계획, Microsoft 365 준수 계획(Azure Information Protection P2 포함), Microsoft 365  비즈니스(Azure Information Protection P1 포함), Enterprise Mobility + Security 요금제. 다음 Azure Information Protection 계획은 사용자 구독 라이선스로 제공됩니다. 계획 1(Microsoft 365 A3, Enterprise Mobility + Security A3 및 Microsoft 365 Business Premium) 및 계획 2(Microsoft 365 A5, Enterprise Mobility + Security A5) 및 AIP(Office 365 A3/A5) 사용자가 Azure Information Protection을 사용할 수 있도록 하는 구독에 대한 자세한 계획 정보는 Microsoft 365 요금제 [비교, Microsoft 365 Enterprise](https://aka.ms/M365BusinessPlans) 계획 비교 및 계획 비교 [](https://aka.ms/M365EnterprisePlans) 페이지를 Microsoft 365 Education [참조](https://aka.ms/EDU-Plan-Comparison)하세요.

## <a name="feature-availability"></a>기능 가용성

아래 표에는 계획에서 사용할 수 있는 Azure Information Protection 기능이 나열됩니다(특정 주의 사항은 적용됩니다. 자세한 내용은 각주 참조). 표가 예고 없이 변경될 수 있습니다. 계획 [에 대한 Azure](https://go.microsoft.com/fwlink/?linkid=2139145)  Information Protection 기능의 기본 목록은 전체 구독 비교 표로 이동하세요.

| 기능 | Azure Information Protection for Office 365 | Azure Information Protection Premium P1 | Azure Information Protection Premium P2 |
|---------|---------|---------|---------|
| AIP 정책 인식 앱 및 서비스의 직장 또는 학교 계정을 사용하여 Azure Information Protection 콘텐츠 사용 | 예 | 예 | 예 |
| 고객 관리 키 프로비전 수명 주기를 위해 BYOK(Bring Your Own Key)<sup>를 가져오기2</sup>     | 예 | 예 | 예 |
| 부서 템플릿을 포함한 사용자 지정 서식 파일 | 예 | 예 | 예 |
| 권한 관리 커넥터를 통한 Exchange SharePoint 콘텐츠 보호 | 예 | 예 | 예 |
| 직장 또는 학교 계정을 사용하여 Azure Information Protection 콘텐츠 만들기 | 예 | 예 | 예 |
| 통합 Office 365 메시지 암호화 | 예 | 예 | 예 |
| 관리 컨트롤<sup>3</sup> | 예 | 예 | 예 |
| PTXT Microsoft Office PJPG 및 PFILE을 비롯한 비보안 파일 형식 보호(일반 보호) | 아니요 | 예 | 예 |
| 수동, 기본 및 필수 문서 분류 | 아니요 | 예 | 예 |
| 중요한 정보 유형과 일치하는 On-프레미스 파일의 콘텐츠 검색을 위한 Azure Information Protection 스캐너 | 아니요 | 예 | 예 |
| Azure Information Protection 스캐너를 사용하여 레이블을 사내 파일 서버 또는 리포지토리의 모든 파일에 적용 | 아니요 | 예 | 예 |
| 문서 추적 및 해지 | 아니요 | 예 | 예 |
| Microsoft Information Protection SDK(소프트웨어 개발자 키트)를 사용하여 모든 플랫폼(Windows, iOS, Mac OSX, Android 및 Linux)의 전자 메일 및 파일에 레이블 및 보호를 적용합니다. | 아니요 | 예 | 예 |
| 자동 및 권장 분류에 대한 조건 구성 | 아니요 | 아니요 | 예 |
| 레이블을 설정하여 2016년 8월에 미리 구성된 S/MIME 보호를 Outlook | 아니요 | 아니요 | 예 |
| 전자 메일 사용 시 정보 Outlook 제어(전자 메일 경고, 정당화 또는 차단) | 아니요 | 아니요 | 예 |
| 높은 규제 시나리오를 위한 Azure AD(정보 보호 및 Active Directory) 권한 관리에 걸쳐 있는 HYOK(사용자 소유 키)를 보유합니다. | 아니요 | 아니요 | 예 |
| 이중 키 암호화(DKE) | 아니요 | 아니요 | 예 |
| 지원되는 사내 파일의 자동화된 분류, 레이블 지정 및 보호를 위한 Azure Information Protection 스캐너 | 아니요 | 아니요 | 예 |

> <sup>1</sup> 일부 Office 365 정보 보호를 사용하는 데이터 보호도 Microsoft Azure 포함됩니다. 이러한 구독 및 Office 365 데이터 보호 기능에 대한 자세한 내용은 [Azure Information Protection 라이선싱 데이터시트를 참조하세요](https://download.microsoft.com/download/E/C/F/ECF42E71-4EC0-48FF-AA00-577AC14D5B5C/Azure_Information_Protection_licensing_datasheet_EN-US.pdf).
<br/><sup>2</sup> BYOK(Bring Your Own Key)에 대해 구성된 키를 사용하는 데 Azure 구독이 필요합니다.
<br/><sup>3</sup> 서비스 활성화/비활성화, 단계적 배포용 온보드 컨트롤, 사용 현황 로깅, eDiscovery 및 데이터 복구를 위한 Super User 기능, 파일의 대량 보호/보호를 포함합니다.

## <a name="free"></a>무료

무료 요금제에 사용할 수 있는 기능은 AIP 정책 인식 앱 및 서비스의 직장 또는 학교 계정을 사용하여 Azure Information Protection 콘텐츠 사용뿐입니다. Azure Information Protection에 의해 보호된 중요한 파일을 전송했지만 사용자의 IT 부서에서 해당 사용자의 계정을 관리하지 않는 경우(예: IT 부서에서 Azure 서비스를 사용하지 않는 경우) 인증할 수 없는 조직의 사용자에 대한 셀프 서비스 구독입니다Office 365.

## <a name="learn-more"></a>자세한 정보

### <a name="azure-information-protection-details"></a>Azure Information Protection 세부 정보

- **Azure RMS**: [Azure RMS(Azure 권한 관리](/azure/information-protection/what-is-azure-rms) 서비스)는 Azure Information Protection에 대한 데이터 보호 기술을 제공합니다. Azure RMS는 분류 및 레이블 지정과 함께 또는 자체적으로 사용할 수 있습니다.
- **AIP 스캐너 또는 클라이언트**: Azure Information Protection 스캐너 또는 클라이언트를 사용하여 분류, 레이블 지정 및 보호를 위한 Azure Information Protection 계획이 있어야 합니다. 자세한 내용은 다음을 참조[하세요. Microsoft 365](/office365/servicedescriptions/microsoft-365-service-descriptions/microsoft-365-tenantlevel-services-licensing-guidance/microsoft-365-security-compliance-licensing-guidance#information-protection) 규정 준수를 위한 [& 라이선](https://go.microsoft.com/fwlink/?linkid=2139145)싱 지침, 최신 작업 계획 비교(PDF [다운로드), Azure Active Directory 가격 책정 | Microsoft 보안](https://www.microsoft.com/security/business/identity-access-management/azure-ad-pricing).
- [**계산기**](https://azure.microsoft.com/pricing/calculator/?service=information-protection): Azure 서비스에 대한 월별 비용을 예측합니다.
- [**설명서**](/azure/information-protection/): 기술 자습서, 비디오 및 추가 리소스를 검토합니다.
- **Azure Information Protection** 에는 사용자 지정(교육 가능한 분류자)을 기반으로 하는 Machine Learning 권한은 포함되어 있지 않습니다.
- **이중 키 암호화**: 이중 키 암호화에 대한 자세한 내용은 Microsoft 365 [Protection: Double Key Encryption for Microsoft 365.](/office365/servicedescriptions/microsoft-365-service-descriptions/microsoft-365-tenantlevel-services-licensing-guidance/microsoft-365-security-compliance-licensing-guidance#information-protection-double-key-encryption-for-microsoft-365)
- **Power BI**/Microsoft 365 E5/A5/G5에 포함되어 있습니다. 다른 모든 계획에서는 Power BI 사용이 허가되어야 합니다.
- [**제품 세부 정보**](https://azure.microsoft.com/services/information-protection/): Azure Information Protection에 대해 자세히 알아보하세요.
- [**구매 FAQ**](https://azure.microsoft.com/pricing/faq/): Azure 가격 책정 질문과 대답을 검토합니다.
- **범위**: AIP 스캐너 기능을 사용하는 경우를 제외하고 정책의 범위를 특정 그룹 또는 사용자로 지정하거나 레지스트리를 편집하여 라이선스가 없는 사용자가 분류 또는 레이블 지정 기능을 실행하지 못하도록 할 수 있습니다.
- **민감도 레이블** 지정: 자세한 내용은 정보 보호: 민감도 [레이블](/office365/servicedescriptions/microsoft-365-service-descriptions/microsoft-365-tenantlevel-services-licensing-guidance/microsoft-365-security-compliance-licensing-guidance#information-protection-sensitivity-labeling) 지정으로 이동하거나 최신 작업 계획 비교 [를 확인하세요](https://go.microsoft.com/fwlink/?linkid=2139145).
- **구독 계획**: Azure Information Protection을 구입하거나 평가하는 방법 및 구독 계획에 사용할 수 있는 다양한 기능에 대한 자세한 내용은 [Azure Information Protectionsite](https://www.microsoft.com/cloud-platform/azure-information-protection) 를 참조하세요.

### <a name="general-information"></a>일반 정보

- **접근성**: Microsoft는  사용자의 데이터 보안 및 서비스에 대한 접근성을 [위해 계속 최선을](https://www.microsoft.com/trust-center/compliance/accessibility) 다하고 있습니다. 자세한 내용은 [Microsoft 보안](https://www.microsoft.com/trust-center)  센터 및 Office  [센터를 참조하세요](https://support.office.com/article/ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d).
- 질문과 대답이 없는 경우 분류 및 레이블 지정과 관련이 있는 [AIP(Azure Information Protection](/azure/information-protection/faqs))에 대한 질문과 대답을 검토하거나, 분류 및 레이블 지정을 위한 [FAQ](/azure/information-protection/faqs-infoprotect), 데이터 보호를 위한 [FAQ](/azure/information-protection/faqs-rms), 클래식 클라이언트용 [FAQ](/azure/information-protection/faqs-classic)만) 또는  [Azure Information Protection](/azure/information-protection/information-support)에 대한 정보 보호 지원에 나열된 링크 및 리소스를 참조하세요.  또는 Microsoft 계정 관리자 또는 Microsoft 지원에 [문의하세요](/azure/information-protection/information-support#to-contact-microsoft-support).
- **사용 조건**: Microsoft 상업용 볼륨 라이선스 프로그램을 통해 구매한 제품 및 서비스에 대한 사용 조건은 제품 사용 약관 [사이트를 참조하세요](https://www.microsoft.com/licensing/terms/).
- **메시징**: 새 기능 및 변경된 기능, 계획된 유지 관리 또는 기타 중요한 공지 사항을 포함하여 예정된 변경 내용을 계속 확인하기 위해 메시지 센터를 방문합니다. 자세한 내용은 [메시지 센터](/microsoft-365/admin/manage/message-center)를 참조하세요.
- **SLA &** 지원: 질문이나 도움이 필요한 경우  [Azure Support](https://azure.microsoft.com/support/options) 를 방문하고 자가 지원 서비스 또는 기타 방법을 선택하여 지원 서비스에 문의하세요. 최종 사용자가 시간의 99.9%에 달하는 IRM 문서 및 전자 메일을 만들고 사용할 수 있도록 보장합니다. 자세한 내용은 [SLApage를](/learn/modules/choose-azure-services-sla-lifecycle)  방문합니다. Sovereign 클라우드의 지원 및 SLA에 대한 자세한 내용은 로컬 계정에 문의하세요.
