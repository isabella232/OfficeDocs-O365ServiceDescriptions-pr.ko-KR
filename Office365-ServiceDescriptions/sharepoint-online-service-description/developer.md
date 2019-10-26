---
title: 개발자
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- sharepoint-online-developer-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 415c9536-ae70-4d4b-b481-5255cb03cc32
description: SharePoint Online은 조직에서 디지털 정보를 저장, 공유 및 관리 하는 데 도움이 되는 웹 기반 도구 및 기술의 모음입니다. Microsoft SharePoint Server 2013에서 기본 제공되는 이 호스트 서비스는 프로젝트 작업, 중앙 위치에 데이터 및 문서 저장, 다른 사람과의 정보 공유에 이상적입니다. 다음 기능은 SharePoint 기능을 확장하기 위해 앱과 솔루션을 빌드하려는 개발자를 지원합니다.
ms.openlocfilehash: 52b1b15dd098b6dd40a531cb5b462a7fff8b69f7
ms.sourcegitcommit: 05458701350d269dce45c9a0812d67d653c52621
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/25/2019
ms.locfileid: "37726255"
---
# <a name="developer"></a>개발자

SharePoint Online은 조직에서 디지털 정보를 저장, 공유 및 관리 하는 데 도움이 되는 웹 기반 도구 및 기술의 모음입니다. Microsoft SharePoint Server 2013에서 기본 제공되는 이 호스트 서비스는 프로젝트 작업, 중앙 위치에 데이터 및 문서 저장, 다른 사람과의 정보 공유에 이상적입니다. 다음 기능은 SharePoint 기능을 확장하기 위해 앱과 솔루션을 빌드하려는 개발자를 지원합니다.
  
## <a name="app-catalog-sharepoint"></a>앱 카탈로그 (SharePoint)

SharePoint 배포에 대한 액세스 권한을 가진 사용자가 사용할 수 있도록 해당 SharePoint 배포에서 호스트되는 내부 회사 카탈로그에 앱을 게시합니다. 자세한 내용은 [Office 및 SharePoint용 앱 게시](https://docs.microsoft.com/office/dev/store/submit-to-the-office-store)를 참조하세요.
  
## <a name="app-deployment-cloud-hosted-apps"></a>앱 배포: 클라우드 호스트 앱

SharePoint용 클라우드 호스트 앱은 원격 구성 요소를 하나 이상 포함하며, SharePoint 호스트 구성 요소도 포함할 수 있습니다. 자세한 내용은 [SharePoint용 앱의 호스팅 옵션](https://docs.microsoft.com/sharepoint/dev/sp-add-ins/choose-patterns-for-developing-and-hosting-your-sharepoint-add-in)을 참조하세요. 
  
## <a name="app-deployment-sharepoint-hosted-apps"></a>앱 배포: SharePoint 호스트 앱

SharePoint 호스트 앱을 사용 하면 목록 및 웹 파트와 같은 일반적인 SharePoint 아티팩트를 다시 사용할 수 있습니다. 이 접근 방식을 선택할 경우 JavaScript만 사용할 수 있으며, 다른 서버 쪽 코드는 사용할 수 없습니다. 자세한 내용은 [SharePoint용 앱의 호스팅 옵션](https://docs.microsoft.com/sharepoint/dev/sp-add-ins/choose-patterns-for-developing-and-hosting-your-sharepoint-add-in)을 참조하세요.
  
## <a name="app-management-service"></a>앱 관리 서비스

App Management Service 데이터베이스는 모든 SharePoint용 앱에 대한 라이선스 정보를 저장합니다. 
  
## <a name="bcs-app-scoped-external-content-types-ects"></a>BCS: 앱 범위가 지정 된 Ect (외부 콘텐츠 형식)

SharePoint에서 새 앱 모델을 추가 하면 BCS (Business Connectivity Services)에서 팜 수준이 아니라 앱 수준에서 외부 콘텐츠 형식의 범위를 지정할 수 있습니다. 이렇게 하면 앱 개발자가 자신의 앱 내에서 외부 데이터를 사용할 수 있으므로 유연성이 뛰어납니다. [앱 범위 외부 콘텐츠 형식](https://docs.microsoft.com/sharepoint/dev/general-development/add-in-scoped-external-content-types-in-sharepoint)에 대해 자세히 알아보세요.
  
## <a name="bcs-business-data-web-parts"></a>BCS: 비즈니스 데이터 웹 파트

비즈니스 데이터 웹 파트는 외부 데이터로 작업 하는 특수 한 웹 파트입니다. 표준 SharePoint 웹 파트처럼 사용되지만, 외부 데이터에 대한 연결의 XML 설명인 외부 콘텐츠 형식을 기반으로 합니다. 
  
## <a name="bcs-external-list"></a>BCS: 외부 목록

외부 목록은 외부 데이터 원본으로부터 데이터를 표시하는 특수한 종류의 SharePoint 목록입니다. 외부 목록은 데이터 원본을 설명하는 외부 콘텐츠 형식을 기반으로 하며, 사용자가 익숙한 SharePoint 인터페이스에서 데이터로 작업할 수 있도록 합니다. 자세한 내용은 [외부 콘텐츠 형식](https://docs.microsoft.com/SharePoint/administration/deploy-an-on-premises-solution)을 참조하세요. 
  
## <a name="bcs-odata-connector"></a>BCS: OData 커넥터

OData 커넥터는 SharePoint의 새로운 기능입니다. 이를 통해 BCS (Business Connectivity Services)에서 RESTful OData 끝점을 외부 목록, 비즈니스 데이터 웹 파트 및 사용자 지정 사용자 인터페이스에 대 한 데이터 원본으로 사용할 수 있습니다.
  
## <a name="bcs-rich-client-integration"></a>BCS: 리치 클라이언트 통합

SharePoint Online 고객은 사용할 수 없습니다. BCS(Business Connectivity Services)는 Outlook 및 Excel과 같이 Office 클라이언트가 외부 콘텐츠 형식으로 SharePoint에 노출되는 외부 데이터로 직접 작업할 수 있도록 하는 서버 쪽 아키텍처 및 무료 클라이언트를 사용합니다. 자세한 내용은 [Business Connectivity Services 클라이언트 런타임](https://docs.microsoft.com/previous-versions/office/developer/sharepoint-2010/ee559310(v=office.14))을 참조하세요.
  
## <a name="client-object-model-om"></a>클라이언트 개체 모델 (OM)

SharePoint 2013에는 세 가지 관리 코드용 클라이언트 개체 모델인 .NET, Silverlight 및 모바일이 있습니다. 또한 SharePoint에는 JavaScript 클라이언트 개체 모델이 포함됩니다. 자세한 내용은 [SharePoint 2013에서 올바른 API 집합 선택](https://docs.microsoft.com/sharepoint/dev/general-development/choose-the-right-api-set-in-sharepoint)을 참조하세요.
  
## <a name="custom-site-provisioning-page"></a>사용자 지정 사이트 프로 비전 페이지

SharePoint Online 고객은 사용할 수 없습니다. SharePoint Server 2013 고객은 사용자가 사이트 요청을 만들고 자신의 사이트를 사용하여 신속하게 시작하기 위한 간편한 방법을 제공합니다.
  
## <a name="developer-site"></a>개발자 사이트

Office 365 개발자 사이트를 개발 및 테스트 환경으로 사용 하 여 설정 시간을 단축 하 고 SharePoint 용 앱 작성, 테스트 및 배포를 시작 합니다. [Office 365 개발자 사이트에 등록 하는](https://docs.microsoft.com/sharepoint/dev/sp-add-ins/create-a-developer-site-on-an-existing-office-365-subscription)방법에 대해 자세히 알아보세요.
  
## <a name="forms-based-applications"></a>폼 기반 응용 프로그램

폼 보기는 기본적으로 컨트롤을 포함하는 보기입니다. 폼 기반 응용 프로그램을 사용 하면 사용자가 응용 프로그램 내에서 하나 이상의 폼을 만들고 사용할 수 있습니다. 자세한 내용은 [폼 기반 응용 프로그램](https://docs.microsoft.com/previous-versions/visualstudio/visual-studio-6.0/aa733955(v=vs.60))을 참고 하세요.
  
## <a name="full-trust-solutions"></a>완전 신뢰 솔루션

SharePoint Online 고객은 사용할 수 없습니다. SharePoint Server 2013 고객은 완전 신뢰 솔루션 (팜 솔루션이 라고도 함)을 만들 수 있습니다. SharePoint용 앱과는 달리, 팜 솔루션에는 SharePoint 서버에 배포되고 SharePoint의 서버 개체 모델을 호출하는 코드가 포함되어 있습니다. 이러한 어셈블리는 항상 완전 신뢰 상태로 실행됩니다. 팜 솔루션은 사용자 지정 타이머 작업, 사용자 지정 Windows PowerShell cmdlet, 중앙 관리의 확장과 같은 SharePoint 관리 기능의 사용자 지정에 사용되어야 합니다. 자세한 내용은 [SharePoint 2013에서 팜 솔루션 구축](https://docs.microsoft.com/sharepoint/dev/general-development/build-farm-solutions-in-sharepoint)을 참조하세요.
  
## <a name="infopath-forms-services"></a>InfoPath Forms Services

Forms Service는 InfoPath에서 디자인 된 양식 서식 파일을 기반으로 SharePoint에서 웹 브라우저 양식 채우기 환경을 제공 합니다. 자세한 내용은 [InfoPath Forms Services](https://docs.microsoft.com/previous-versions/office/developer/sharepoint-2007/ms540731(v=office.12))를 참조하세요.
  
## <a name="javascript-object-model"></a>JavaScript 개체 모델

SharePoint는 인라인 스크립트 또는 별도의 .js 파일에 사용할 JavaScript 모델을 제공합니다. 여기에는 .NET Framework 및 Silverlight 클라이언트 개체 모델과 동일한 기능이 모두 포함되어 있습니다. JavaScript 개체 모델은 앱에 사용자 지정 SharePoint 코드를 포함할 수 있는 유용한 방법입니다. 또한 웹 개발자가 기존 JavaScript 기술을 사용 하 여 최소한의 학습 곡선을 사용 하 여 SharePoint 응용 프로그램을 만들 수 있습니다. 자세한 내용은 [SharePoint 2013에 대한 JavaScript API 참조](https://docs.microsoft.com/previous-versions/office/sharepoint-visio/jj193034(v=office.15))를 참조하세요.
  
## <a name="remote-event-receiver"></a>원격 이벤트 수신기

SharePoint용 앱에서 이벤트를 처리하려면 개발자는 원격 이벤트 수신기 및 앱 이벤트 수신기를 만들 수 있습니다. 원격 이벤트 수신기는 목록, 목록 항목 또는 웹 같은 앱의 항목에 발생하는 이벤트를 처리합니다. 자세한 내용은 [SharePoint용 앱에서 이벤트 처리](https://docs.microsoft.com/sharepoint/dev/sp-add-ins/handle-events-in-sharepoint-add-ins)를 참조하세요. 
  
## <a name="rest-apis"></a>REST Api

SharePoint 2013은 OData 프로토콜을 사용하여 SharePoint 목록 데이터에서 CRUD 작업을 수행하는 REST(REpresentational State Transfer) 웹 서비스의 구현을 제공합니다. JavaScript를 사용하지 않고 .NET Framework 또는 Microsoft Silverlight 플랫폼에서 구축되지 않은 클라이언트 기술로부터 SharePoint 데이터에 액세스해야 하는 경우 이 API를 사용합니다. 자세한 내용은 [SharePoint 2013 REST 서비스를 사용한 프로그래밍](https://docs.microsoft.com/sharepoint/dev/sp-add-ins/use-odata-query-operations-in-sharepoint-rest-requests)을 참조하세요.
  
## <a name="sharepoint-design-manager"></a>SharePoint 디자인 관리자

디자인 관리자를 사용하면 브랜드 사이트에 사용할 수 있는 설계 자산을 만들기 위한 단계별 접근이 가능합니다. 이미지, HTML, CSS와 같은 설계 자산을 업로드한 다음 마스터 페이지와 페이지 레이아웃을 만듭니다. 자세한 내용은 [SharePoint 2013 사이트 배포](https://docs.microsoft.com/sharepoint/dev/general-development/what-s-new-with-sharepoint-site-development)를 참조하세요.
  
## <a name="sharepoint-designer-2013"></a>SharePoint Designer 2013

고급 사용자 및 개발자는 SharePoint Designer를 사용 하 여 비즈니스 요구 사항에 따라 SharePoint 솔루션을 신속 하 게 만들 수 있습니다. 자세한 내용은 [개발자용 SharePoint Designer](https://go.microsoft.com/fwlink/?LinkId=271294)를 참조하세요.
  
## <a name="sharepoint-framework"></a>SharePoint 프레임워크

SPFx(SharePoint Framework)는 클라이언트 쪽 SharePoint 개발에 대한 모든 지원, SharePoint 데이터와의 쉬운 통합 및 오픈 소스 도구에 대한 지원을 제공하는 페이지 및 웹 파트 모델입니다. [SharePoint Framework](https://docs.microsoft.com/sharepoint/dev/spfx/sharepoint-framework-overview)에 대해 자세히 알아보세요.
  
## <a name="sharepoint-2010-workflows-out-of-the-box"></a>SharePoint 2010 워크플로 (이 상자에서 제외 됨)

SharePoint에 포함된 특별 워크플로를 사용하여 공통 비즈니스 프로세스를 모델링합니다.
  
## <a name="sharepoint-2013-and-sharepoint-2016-workflows"></a>SharePoint 2013 및 SharePoint 2016 워크플로

SharePoint 2013 및 SharePoint 2016 워크플로는 WF (Windows Workflow Foundation 4)에 의해 구동 되며 이전 버전에서 크게 다시 디자인 되었습니다. 새 워크플로 인프라에서 가장 두드러진 특징은 워크플로 실행 호스트로 Azure를 도입 하는 것입니다. 자세한 내용은 [SharePoint 용 워크플로의 새로운 기능](https://docs.microsoft.com/sharepoint/dev/general-development/what-s-new-in-workflows-for-sharepoint)을 참고 하세요.
  
## <a name="feature-availability"></a>기능 가용성

Office 365 계획, 독립 실행형 옵션 및 온-프레미스 솔루션 별로 기능 가용성을 확인 하려면 [SharePoint Online 서비스 설명을](sharepoint-online-service-description.md)참조 하세요.
  

