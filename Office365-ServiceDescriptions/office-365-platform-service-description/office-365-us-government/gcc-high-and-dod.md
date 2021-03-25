---
title: Office 365 GCC High 및 DoD
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 0821204d-5515-43de-8ed6-ab84bd1693c1
description: Office 365 상용 환경과 비교한 Office 365 GCC High 및 DoD 환경의 고유한 약정 및 차이점에 대해 자세히 알아보십시오.
ms.openlocfilehash: c4dfdabde7090a7a0b89975eb329eb92016e22f2
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173963"
---
# <a name="office-365-gcc-high-and-dod"></a>Office 365 GCC High 및 DoD

Microsoft는 계약자 보유 또는 처리 DoD CUI(제어 미분 분석 정보)의 고유하고 진화된 요구 사항을 충족하거나 ITAR(International Traffic in Arms Regulations)을 준수하기 위해 GCC High 및 DoD 환경을 제공합니다. 볼륨 라이선스를 통해 제공되는 관심 있는 조직은 환경을 설정하기 전에 자격을 확인하기 위해 유효성 검사 프로세스를 거치게 됩니다. 현재는 평가판을 사용할 수 없습니다. 
  
계정 팀 또는 기본 설정 파트너에 참여하여 자세한 내용을 알아보거나 유효성 검사 프로세스를 시작하세요. 구입 방법에 대한 자세한 내용은 [Microsoft 365 Government - 구입 방법을 참조하세요.](./microsoft-365-government-how-to-buy.md)
  
## <a name="how-to-use-this-service-description"></a>서비스 설명 사용 방법

Office 365 Government 서비스 설명은 일반 Office 365 서비스 설명에 대한 오버레이로 제공하도록 디자인됩니다. 엔터프라이즈용 Office 365 제품과 비교할 때 고유한 확정 및 차이점을 정의합니다.
  
## <a name="compliance"></a>규정 준수

GCC High 및 DoD는 다음 인증 및 인증에 대한 규정 준수 요구 사항을 충족합니다. 
  
- NIST(National Institute of Standards and Technology) 특별 발행물 800-53에 설명된 보안 제어 및 제어 향상을 포함하여 FedRAMP High의 Federal Risk and Authorization Management Program
    
- 영향 수준 5(L5)까지의 정보를 제공하는 미국방부 클라우드 컴퓨팅 SRG(보안 요구 사항 가이드)의 보안 통제 및 통제 개선 사항
    
Office 365에 대한 국방부 구독자는 DOD SRG L5를 충족하는 DOD 배타적 환경에서 제공되는 서비스를 받게 됩니다. 국방부 이 외 구독자는 L5에서 평가되지만 L4 분할을 사용하는 미 국방부 환경에서 서비스를 받게 됩니다.
  
## <a name="background-screening"></a>배경 화면

Office 365 직원은 GCC High 및 DoD 프로덕션에 대한 정식 액세스 권한이 없습니다. 고객 콘텐츠에 대한 액세스 권한을 부여하는 임시 권한 상승을 요청하는 모든 직원은 먼저 다음 배경 검사를 통과해야 합니다.<br><br>
  
| Microsoft 직원 심사 및 배경 검사<sup>1</sup> | 설명 |
|:-----|:-----|
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

<sup>1</sup> Office 365 US GCC-High 또는 DOD 클라우드에서 호스팅되는 고객 콘텐츠에 대한 임시 또는 영구 액세스 권한이 있는 직원에게만 적용됩니다.
## <a name="feature-nuances-based-on-compliant-cloud-architecture"></a>규격 클라우드 아키텍처 기반의 기능 미정

GCC High 및 DoD 환경의 구독에는 핵심 Exchange Online, SharePoint 및 비즈니스용 Skype 기능이 포함됩니다. 인프라의 인증 및 인증이 증가한 경우 일반 상용 Office 365 제품과 GCC High 및 DoD에서 사용할 수 있는 제품 간에 몇 가지 기능 차이가 있습니다.
  
### <a name="exchange-online"></a>Exchange Online

 **Exchange Online IP-PBX에** 대한 Exchange Online 통합 메시징 지원 - GCC High 및 DoD 구독에서는 Exchange Online 통합 메시징과의 사내 IP-PBX 시스템 통합 지원이 지원되지 않습니다. 
  
### <a name="file-sharing"></a>파일 공유

사용자는 SharePoint 및 OneDrive에서 파일 및 폴더를 공유할 수 있는 여러 옵션을 사용할 수 있습니다. 모든 옵션은 GCC High 및 DoD 환경에서 사용할 수 있습니다. 이러한 옵션을 관리하는 데 대한 자세한 내용은 공유 설정 [관리를 참조하세요.](/sharepoint/turn-external-sharing-on-or-off) 조직의 GCC-High GCC-High의 다른 조직과만 공유할 수 있습니다. 또한 사용자 프로필에 첨부된 비 GCC High 전자 메일 주소는 지원되지 않습니다. 경고 전자 메일이 전송되는 것은 허용되지 않습니다. 예를 들어, On premises User A is assigned a Gmail email address and then synced to an Azure GCC High organization. 사용자 A는 라이브러리로 이동하여 변경 내용에 대한 알림을 만듭니다. 알림이 Gmail 주소로 전송되지 않습니다.

> [!NOTE]
> 현재 GCC-High 사용자가 GCC High가 아닌 조직의 사용자와 공유할 수 없습니다.

[](https://support.office.com/article/f54aa7f8-2589-4421-b351-d415fc3b83af) Office 365 Government에서는 파일 요청을 사용할 수 없습니다.

### <a name="skype-for-business-online"></a>비즈니스용 Skype Online

 **PSTN 통화 &amp; PSTN** 회의 - 전화 통신 중심 서비스에 PSTN(Public Switched Telephone Network)을 사용할 요구 사항으로 인해 PSTN 통화 PSTN 회의 서비스는 현재 GCC High 및 DoD에서 사용할 수 &amp; 없습니다.

### <a name="microsoft-teams"></a>Microsoft Teams

전화 시스템 및 오디오 회의(직접 라우팅을 **통해)** - GCC High 및 DoD 환경에 대한 전화 시스템 및 오디오 회의는 직접 라우팅을 통해 전달됩니다. 자세한 내용은 서비스 수준 설명서를 참조하세요.

- [직접 라우팅을 통한 전화 시스템](/microsoftteams/here-s-what-you-get-with-phone-system)
- [GCC High 및 DoD를 위해 직접 라우팅으로 오디오 회의](/microsoftteams/audio-conferencing-with-direct-routing-for-gcch-and-dod)

### <a name="identity"></a>ID

페더레이션 ID 모델을 사용하는 다단계 인증은 PIV 및 CAC 카드를 사용할 수 있도록 합니다.
  
### <a name="yammer"></a>Yammer

Yammer 엔터프라이즈용 에디터는 GCC High 및 DoD 환경에서 사용할 수 없습니다.
  
## <a name="customer-support"></a>고객 지원

Microsoft는 적어도 지원 에이전트가 이러한 데이터를 보거나 액세스할 수 있는 권한을 확인할 때까지 지원 인시던트의 일부로 제어, 중요 또는 기밀 정보를 지원 인시던트의 일부로 고객 지원 담당자와 공유하지 않을 것을 미리 알리고 있습니다.

Microsoft는 개인 정보를 보호하기 위해 최선을 [다하고 있습니다.](https://privacy.microsoft.com/privacystatement) 그러나 Office 365 GCC High/DoD 지원은 서비스 인증 경계에 포함되지 않습니다. 또한 FedRAMP, DOD SRG, ITAR, IRS 1075 또는 CJIS 데이터 처리 준수 보장은 제공하지 않습니다.