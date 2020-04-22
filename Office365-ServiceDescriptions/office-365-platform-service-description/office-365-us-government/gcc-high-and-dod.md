---
title: Office 365 GCC High 및 DoD
ms.author: danarl
author: danarl
manager: dianap
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 0821204d-5515-43de-8ed6-ab84bd1693c1
description: Office 365 상업용 환경과 비교 하 여 Office 365 GCC High 및 DoD 환경의 고유한 약정 및 차이점에 대해 알아봅니다.
ms.openlocfilehash: 8ad2ae12a58c494c72e044655e69679346118aee
ms.sourcegitcommit: 7a68dc894dde0d06fab014c56914a78aa8cda847
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/21/2020
ms.locfileid: "43639056"
---
# <a name="office-365-gcc-high-and-dod"></a>Office 365 GCC High 및 DoD

미국 방어 부서에 대 한 고유 하 고 진화 한 요구 사항과, DoD가 통제 되지 않은 정보를 보유 하거나 처리 하는 계약자, ITAR (무장 규정)의 국제 트래픽에 대 한 주체를 충족 하기 위해 Microsoft는 GCC High 및 DoD 환경을 제공 합니다. 볼륨 라이선스를 통해 제공되는 관심 있는 조직은 환경을 설정하기 전에 자격을 확인하기 위해 유효성 검사 프로세스를 거치게 됩니다. 현재는 평가판을 사용할 수 없습니다. 
  
계정 팀 또는 기본 설정 파트너에 참여해서 자세히 알아보거나 유효성 검사 프로세스를 시작하세요. 구입 방법에 대 한 자세한 내용은 [Microsoft 365 정부-구매 방법](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy)를 참조 하세요.
  
## <a name="how-to-use-this-service-description-section"></a>이 서비스 설명 섹션을 사용 하는 방법

Office 365 US 정부 서비스 설명은 일반적인 Office 365 서비스 설명에 대 한 오버레이를 제공 하도록 설계 되었습니다. Office 365 Enterprise 제품과 비교하여 고유한 확정 및 차이점을 정의합니다.
  
## <a name="compliance"></a>규정 준수

GCC High 및 DoD는 다음과 같은 인증 및 승인에 대 한 준수 요구 사항을 충족 합니다. 
  
- NIST(National Institute of Standards and Technology: 미국 표준 기술 연구소) 특별판 800-53에 설명되어 있는 보안 통제 및 통제 개선 사항을 포함하는 FedRAMP Moderate(Federal Risk and Authorization Management Program at a Moderate baseline)
    
- 영향 수준 5(L5)까지의 정보를 제공하는 미국방부 클라우드 컴퓨팅 SRG(보안 요구 사항 가이드)의 보안 통제 및 통제 개선 사항
    
Office 365에 대 한 방어 가입자의 부서는 DOD SRG L5를 충족 하는 DOD 전용 환경에서 제공 된 서비스를 수신 합니다. 비-방어 구독자는 L5에서 평가 되는 미국 정부 방어 환경에서 서비스를 받게 되지만 L4 조각화가 사용 됩니다.
  
## <a name="background-screening"></a>백그라운드 차단

Office 365 직원은 GCC High 및 DoD 프로덕션에 대 한 액세스 권한이 없습니다. 고객 콘텐츠에 액세스할 수 있도록 임시 권한 상승을 요청한 모든 직원은 먼저 다음 배경 조사를 통과해야 합니다.
  
|||
|:-----|:-----|
|**Microsoft 직원 선별 및 배경 검사**<sup>1</sup> <br/> |**설명** <br/> |
|미국 시민권  <br/> |미국 시민권 확인  <br/> |
|고용 기록 확인  <br/> |최근 7년의 고용 기록 확인  <br/> |
|교육 확인  <br/> |획득한 최종 학위 확인  <br/> |
|SSN(사회 보장 번호) 검색  <br/> |제공된 SSN이 올바른지 확인  <br/> |
|범죄 기록 확인  <br/> |최근 7년의 주, 카운티, 지방 및 연방 차원에서의 중범죄 및 경범죄 위반에 대한 범죄 기록 확인  <br/> |
|OFAC(외화 자산 통제국) 목록  <br/> |재무부에 무역이나 금융 거래가 허용되지 않는 사람들의 그룹 목록 확인  <br/> |
|BIS(산업 안보국) 목록  <br/> |상무부에 수출 활동이 허용되지 않는 개인 및 기관의 목록 확인  <br/> |
|DDTC(국방 무역 통제국)에서 금지한 개인 목록  <br/> |국무부에 국방 산업과 관련된 수출 활동이 허용되지 않는 개인 및 기관의 목록 확인  <br/> |
|지문 조사  <br/> |FBI 데이터베이스에 지문 배경 조사  <br/> |
|국방부 IT-2  <br/> |고객 데이터에 대한 관리자 권한 또는 국방부 SRG L5 서비스 기능에 대한 권한 있는 관리 액세스를 요구하는 직원은 OPM 계층 3 조사 성공을 토대로 국방부 IT-2 판결을 통과해야 합니다.  <br/> |

<sup>1</sup> 은 OFFICE 365 US GCC-HIGH 또는 DOD 클라우드에서 호스트 되는 고객 콘텐츠에 대 한 일시적인 또는 동등한 액세스 권한을 가진 사용자 에게만 적용 됩니다.
## <a name="feature-nuances-based-on-compliant-cloud-architecture"></a>준수 클라우드 아키텍처를 기반으로 하는 기능 nuances

GCC High 및 DoD 환경의 구독에는 핵심 Exchange Online, SharePoint 및 비즈니스용 Skype 기능이 포함 되어 있습니다. 인프라의 인증 및 인정이 증가 함에 따라 일반 상업용 Office 365 제품 및 GCC High 및 DoD에서 사용 가능한 몇 가지 기능 차이가 있습니다.
  
### <a name="exchange-online"></a>Exchange Online

 온 **-프레미스 IP pbx에 대 한 Exchange Online 통합 메시징 지원** -GCC High 및 DoD 구독에서는 온-프레미스 ip pbx 시스템을 Exchange Online 통합 메시징과 통합 하는 기능이 지원 되지 않습니다. 
  
### <a name="file-sharing"></a>파일 공유

사용자는 SharePoint 및 OneDrive에서 파일 및 폴더를 공유 하기 위한 여러 옵션을 사용할 수 있습니다. 모든 옵션은 GCC High 및 DoD 환경에서 사용할 수 있습니다. 이러한 옵션을 관리 하는 방법에 대 한 자세한 내용은 [Manage sharing settings](/sharepoint/turn-external-sharing-on-or-off)를 참조 하십시오. 사용자가 "특정 사용자" 옵션을 사용 하 여 공유 하 고 조직 외부의 사용자를 선택 하면 일반적으로 SharePoint에서 인증 코드가 전자 메일로 전송 됩니다. 받는 사람은 공유 항목에 액세스 하기 위한 코드를 입력 해야 합니다. 이는 GCC 상위 조직의 사용자가 GCC 이외의 조직에 있는 사람들과 공유 하 고 그 반대의 경우도 마찬가지입니다. 외부 공유 환경에 대 한 자세한 내용은 [사용자가 공유할 때 수행 되는 작업](/sharepoint/external-sharing-overview#what-happens-when-users-share)을 참조 하십시오. 그러나 한 GCC 최고 조직에 있는 사용자가 다른 GCC-고가용성 조직의 사람과 공유 하는 경우 Azure AD에서 받는 사람에 대 한 게스트 계정이 만들어지고 사용자 이름 및 암호를 사용 하 여 로그인 됩니다. 

Office 365 정부에는 [파일 요청](https://support.office.com/article/f54aa7f8-2589-4421-b351-d415fc3b83af) 을 사용할 수 없습니다.

또한 사용자 프로필에 첨부 되는 비 GCC 높은 전자 메일 주소는 지원 되지 않으며 경고 전자 메일이 전송 될 수 없습니다. 예를 들어 온-프레미스 사용자 A에 Gmail 전자 메일 주소가 할당 되 고 Azure GCC High 조직과 동기화 됩니다. 사용자 A가 라이브러리를 탐색 하 고 변경 사항에 대 한 알림을 만듭니다. 이 경고는 Gmail 주소로 전송 되지 않습니다.
  

### <a name="skype-for-business-online"></a>비즈니스용 Skype Online

 **Pstn &amp; 회의** pstn 전화-통신 지향 서비스에 pstn (공중 전화망)을 사용 해야 하는 요구 사항으로 인해 현재 GCC High 및 &amp; DoD에서는 pstn 회의 서비스를 호출 하는 것이 가능 하지 않습니다.

### <a name="microsoft-teams"></a>Microsoft Teams

**전화 시스템 및 오디오 회의 (직접 라우팅 통해)**: GCC High 및 DoD 환경에 대 한 전화 시스템 및 오디오 회의는 직접 라우팅을 통해 제공 됩니다. 자세한 내용은 여기에서 서비스 수준 설명서를 참조 하세요.

- [직접 라우팅를 통한 전화 시스템](https://docs.microsoft.com/microsoftteams/here-s-what-you-get-with-phone-system)
- [GCC High 및 DoD를 위해 직접 라우팅으로 오디오 회의](https://docs.microsoft.com/microsoftteams/audio-conferencing-with-direct-routing-for-gcch-and-dod)

### <a name="identity"></a>ID

페더레이션 ID 모델을 사용하는 다단계 인증은 PIV 및 CAC 카드를 사용할 수 있도록 합니다.
  
### <a name="yammer"></a>Yammer

Yammer Enterprise는 GCC High 및 DoD 환경에서는 사용할 수 없습니다.
  
## <a name="customer-support"></a>고객 지원

Microsoft는 Office 365 GCC High/DOD를 사용 하는 경우 지원 센터에서 이러한 데이터를 보거나 액세스 하기 위한 인증을 확인할 때까지 고객 지원 담당자에 게 제어, 중요 또는 기밀 정보를 공유 하지 않도록 합니다.

Microsoft는 사용자의 [개인 정보](https://privacy.microsoft.com/privacystatement)보호를 위해 최선을 다하고 있습니다. 그러나 Office 365 GCC High/DoD 지원은 서비스 인정 경계에 포함 되지 않으며 FedRAMP, DOD SRG, ITAR, IRS 1075 또는 CJIS 데이터 처리 준수 보장을 제공 하지 않습니다.
