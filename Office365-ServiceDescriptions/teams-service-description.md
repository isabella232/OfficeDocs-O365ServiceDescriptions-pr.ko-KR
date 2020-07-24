---
title: Microsoft Teams 서비스 설명
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
description: Microsoft 팀은 인스턴트 메시징, 파일 및 데이터 공동 작업, 오디오 및 비디오 통화, 리치 온라인 모임, 모바일 환경 및 광범위 한 웹 회의 기능을 제공 합니다.
ms.openlocfilehash: e017d2ee8291bab0edf7c866b0d53b02dcfe7371
ms.sourcegitcommit: d4025c73f14b663ffcaa1ef8db4174b51debdae7
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/23/2020
ms.locfileid: "45388094"
---
# <a name="microsoft-teams-service-description"></a>Microsoft Teams 서비스 설명

Microsoft 팀은 Microsoft 365의 팀 작업에 대 한 허브입니다. 팀 서비스를 사용 하면 인스턴트 메시징, 오디오 및 비디오 통화, 풍부한 온라인 모임, 모바일 환경 및 광범위 한 웹 회의 기능을 사용할 수 있습니다. 또한 팀에서는 파일 및 데이터 공동 작업 및 확장성 기능을 제공 하 고 Microsoft 365 및 기타 Microsoft 및 파트너 앱과 통합 합니다.

비즈니스용 Skype Online은 2021 년 7 월 31 일, 2019에 [발표](https://techcommunity.microsoft.com/t5/Microsoft-Teams-Blog/Skype-for-Business-Online-to-Be-Retired-in-2021/ba-p/777833) 되었습니다. Microsoft 팀은 Microsoft의 Azure 및 기타 서비스 혁신을 활용 하 여 처음부터 클라우드를 기반으로 구축 되는 완전히 새로운 서비스입니다. Microsoft 팀은 microsoft 365 그룹, Microsoft Graph 및 Office 365의 나머지와 같은 엔터프라이즈 수준의 보안, 규정 준수 및 관리 용이성을 기반으로 구축 됩니다. 팀은 azure Active Directory (Azure AD)에 저장 된 id를 활용 합니다. 이러한 서비스는 Microsoft 데이터 센터에서 제공 되며 회사 네트워크 내부 또는 인터넷을 통해 광범위 한 장치에서 사용자가 액세스할 수 있습니다. 자세한 내용은 [Microsoft 팀 IT 아키텍처 및 전화 통신 솔루션 포스터](https://docs.microsoft.com/microsoftteams/teams-architecture-solutions-posters)를 참조 하세요.

Microsoft는 데이터의 보안 및 서비스의 [내게 필요한 옵션](https://www.microsoft.com/trust-center/compliance/accessibility) 에 대 한 커밋된 상태를 유지 합니다. 자세한 내용은 [Microsoft 보안 센터](https://www.microsoft.com/trust-center) 및 [Office 접근성 센터](https://support.office.com/article/Office-Accessibility-Center-Resources-for-people-with-disabilities-ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d)를 참조 하세요.

여기에는 Microsoft 팀을 위해 사용자를 사용할 수 있도록 하는 구독에 대 한이 마스터 테이블이 포함 되어 있습니다. 자세한 계획 정보는 [비즈니스에 적합 한 Microsoft 팀을 찾으십시오](https://www.microsoft.com/microsoft-365/microsoft-teams/compare-microsoft-teams-options?rtc=1).를 참조 하세요. 정부 계획의 추가 Office 365에 대 한 자세한 내용은 [office 365 정부 요금제](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans)를 참조 하세요. Office 365 G1 to G5에는 팀 기능에 대 한 액세스 권한이 포함 됩니다.

|||||||||
|:-----|:-----|:-----|:-----|
|**소규모 기업 계획** <br/> |**엔터프라이즈 계획** <br/> |**교육 계획** <br/> |**개발자 계획** <br/> |
|Microsoft 365 Business Basic <br/> |Office 365 E1 <br/> |Office 365 A1 <br/> |Office 365 개발자 <br/> |
|Microsoft 365 Business Standard <br/> |Office 365 E3 <br/> |Office 365 A3 <br/>|   <br/> |
|Microsoft 365 Business Premium <br/> | Office 365 E5<br/> |Office 365 A5 <br/>  |  <br/> |
|  <br/> |Office 365 F3 <br/> |  Microsoft 365 A3<br/> |  <br/> |
|  <br/> |Microsoft 365 F1 <br/> |  Microsoft 365 A5<br/> |  <br/> |
|  <br/> |Microsoft 365 F3 <br/> |  <br/> |  <br/> |
|  <br/> |Microsoft 365 E3 <br/> |  <br/> |  <br/> |
|  <br/> |Microsoft 365 E5 <br/> |  <br/> |  <br/> |

자세한 제품 기능 구현 지침은 [Microsoft 팀 관리 설명서](https://docs.microsoft.com/MicrosoftTeams)를 참조 하십시오. 이 서비스 설명은 다양 한 클라우드 설치에서 제공 되는 서비스 간의 주요 차이점에 대해 자세히 설명 합니다. Microsoft 팀 핵심 기능은 구독 간에 차이가 없습니다. 준수 기능의 가용성은 구독 수준에 따라 달라 집니다. 자세한 내용은 [Microsoft 팀의 보안 및 규정 준수](https://docs.microsoft.com/microsoftteams/security-compliance-overview)를 참조 하세요. 각 구독에서 사용할 수 있는 기능에 대 한 자세한 목록은 [Microsoft 365 및 Office 365 platform service description](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-platform-service-description)을 참조 하십시오.

**클라우드 음성 기능**: 오디오 회의의 경우 조직에서 전화 접속 회의를 설정할 각 사용자에 게 오디오 회의 라이선스를 구입 하 여 할당 해야 합니다. 요금제를 호출 해야 하는 팀 기능의 경우 각 사용자에 게 전화 시스템과 국내 또는 국내/국제 통화 요금제가 필요 합니다. 자세한 내용은 [Microsoft 팀 추가 기능 라이선스](https://docs.microsoft.com/microsoftteams/teams-add-on-licensing/microsoft-teams-add-on-licensing)를 참조 하세요.

**라이브 이벤트**: Office 365의이 제공은 만료 된 Skype 모임 브로드캐스트를 대체 합니다. 라이브 이벤트 기능은 Stream service 내에 자세히 설명 된 대로 라이선스 계획에 사용할 수 있습니다. [여기에서 Microsoft Stream license details](https://docs.microsoft.com/stream/license-overview)를 검토 하세요. 라이브 이벤트 서비스는 Stream, Yammer 또는 Microsoft 팀을 통해 액세스할 수 있습니다. 라이브 이벤트 기능에 대 한 자세한 내용은 [Yammer, Microsoft 팀 및 Microsoft Stream의 microsoft 365에서 라이브 이벤트](https://docs.microsoft.com/stream/live-event-m365)를 참조 하세요.

지원 되는 모든 구독 계획은 Microsoft 팀 웹 클라이언트, 데스크톱 클라이언트 및 모바일 앱에 대 한 액세스에 적합 합니다.

Microsoft 팀은 독립 실행형 서비스로 사용할 수 없습니다.

## <a name="feature-category-reference"></a>기능 범주 참조 

이 표에는 라이선스 계획 또는 클라우드 인스턴스에서의 Microsoft 팀 기능 사용 가능 여부가 나와 있습니다. 특정 주의 사항이 적용 됩니다. 자세한 내용은 각주를 참조 하세요. 이 표는 예 고 없이 변경 될 수 있습니다. 핵심 서비스 변경 메시지 및 [microsoft 라이선스 용어 참조 설명서](https://www.microsoft.com/licensing/product-licensing/products)에 대 한 자세한 내용은 Microsoft 365 메시지 센터 알림을 참조 하십시오.

|||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
| <br/>|**소규모 기업** <br/> |**엔터프라이즈 계획** <br/> |**GCC** <br/> |**GCC-고가용성** <br/> |**여기서** <br/> |**교육** <br/> |
|채팅  <br/> |예  <br/> |예  <br/> |예  <br/> |예  <br/> |예  <br/> |예  <br/> |
|Teams  <br/> |예 <br/> |예 <br/> |예 <br/> |예<sup>1</sup>  <br/> |예<sup>1</sup>  <br/> |예  <br/> |
|채널-표준  <br/> |예  <br/> |예  <br/> |예  <br/> |예  <br/> |예  <br/> |예  <br/> |
|채널-개인  <br/> |예  <br/> |예<sup>2</sup>  <br/> |아니요  <br/> |아니요  <br/> |아니요 <br/> |지원  <br/> |
|모임  <br/> |예  <br/> |예  <br/> |예  <br/> |예  <br/> |예  <br/> |예  <br/> |
|화면 공유 PowerPoint Audio/Video Desktop <br/> |예  <br/> |예  <br/> |예  <br/> |예  <br/> |예  <br/> |예  <br/> |
|음성  <br/> |예  <br/> |예  <br/> |예  <br/> |예  <br/> |예  <br/> |예  <br/> |
|오디오 회의  <br/> |예  <br/> |예  <br/> |예  <br/> |예  <br/> |예  <br/> |예  <br/> |
|앱, Bot, & 커넥터  <br/> |예  <br/> |예  <br/> |예<sup>3</sup>  <br/> |예<sup>3</sup>  <br/> |예<sup>3</sup>  <br/> |예  <br/> |
|라이브 이벤트  <br/> |아니요  <br/> |예  <br/> |예  <br/> |<sup>4</sup> 없음  <br/> |<sup>4</sup> 없음  <br/> |예  <br/> |

<sup>1</sup> 개별 팀에서 GCC-고가용성 및 DOD 지원 2500 구성원의 Microsoft 팀<br/>
<sup>2</sup> Microsoft Planner는 현재 개인 채널에서 액세스 하는 데 사용할 수 없습니다.<br/>
<sup>3</sup> Microsoft ONENOTE는 DOD 클라우드에서 사용할 수 없습니다. 지금은이 클라우드에서 응용 프로그램 및 응용 프로그램 게시를 사용할 수 없습니다.<br/>
<sup>4</sup> 현재는 GCC-HIGH 또는 DOD에서 Live 이벤트를 사용할 수 없습니다.<br/>

## <a name="next-steps"></a>다음 단계

Microsoft 팀 [기술 설명서](https://aka.ms/SuccessWithTeams)를 방문 하 여 microsoft 팀 배포 계획을 시작 합니다. [커뮤니티에 가입 하 고 Microsoft 팀 블로그를 방문](https://aka.ms/TeamsBlog)하 여 팀의 기능을 최신 상태로 유지 합니다.