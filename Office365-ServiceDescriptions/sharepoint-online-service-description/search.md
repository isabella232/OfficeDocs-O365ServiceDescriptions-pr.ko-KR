---
title: 검색
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 06/05/2019
audience: ITPro
ms.topic: reference
f1_keywords:
- sharepoint-online-search-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: cb36484c-0e8f-480e-be88-5daa8bf2d47d
description: SharePoint Online은 조직에서 디지털 정보를 저장, 공유 및 관리 하는 데 도움이 되는 웹 기반 도구 및 기술의 모음입니다. Microsoft SharePoint Server 2013을 기반으로 구축된 이 호스트된 서비스는 프로젝트를 진행하고, 데이터와 문서를 중앙 위치에 저장하며 다른 사용자들과 정보를 공유하는 데 이상적입니다. 다음의 검색 기능은 업무 처리에 필요한 정보를 찾을 수 있게 도와 줍니다. 검색은 관련성, 구체화 및 사용자 검색의 조합입니다.
ms.openlocfilehash: 512ebe26388ed4fdfb49f5a55c7a2adfe2b64cd7
ms.sourcegitcommit: 02cceb48c46295b2c75835b872a5bda17ba1a424
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/06/2019
ms.locfileid: "34742167"
---
# <a name="search"></a>검색

SharePoint Online은 조직에서 디지털 정보를 저장, 공유 및 관리 하는 데 도움이 되는 웹 기반 도구 및 기술의 모음입니다. Microsoft SharePoint Server 2013을 기반으로 구축된 이 호스트된 서비스는 프로젝트를 진행하고, 데이터와 문서를 중앙 위치에 저장하며 다른 사용자들과 정보를 공유하는 데 이상적입니다. 다음의 검색 기능은 업무 처리에 필요한 정보를 찾을 수 있게 도와 줍니다. 검색은 관련성, 구체화 및 사용자 검색의 조합입니다.
  
## <a name="continuous-crawls"></a>연속 크롤링
<a name="bkmk_ContinuousCrawl"> </a>

연속 크롤링을 통해 SharePoint 사이트의 콘텐츠를 자주 크롤링하여 검색 결과를 최신 상태로 유지할 수 있습니다. SharePoint Online에서는 연속 크롤링을 사용할 수 있고, 크롤링 빈도는 Microsoft에서 관리합니다. SharePoint Server 2013에서는 관리자가 연속 크롤링을 사용하도록 설정하고 연속 크롤링 빈도를 관리할 수 있습니다. 자세한 내용은 [SharePoint의 크롤링되는 기본 파일 이름 확장명 및 구문 분석되는 파일 형식](https://docs.microsoft.com/sharepoint/technical-reference/default-crawled-file-name-extensions-and-parsed-file-types)을 참조하세요. 자세한 내용은 [SharePoint Server 2013에서 연속 크롤링 관리](https://docs.microsoft.com/SharePoint/search/manage-continuous-crawls)를 참조하세요.
  
## <a name="deep-links"></a>딥 링크
<a name="bkmk_DeepLink"> </a>

검색 시스템에서는 자주 방문하는 기본 페이지의 하위 섹션에 직접 연결되는 링크를 자동으로 만듭니다. 이러한 링크를 "딥 링크"라고 합니다. 자세한 내용은 [SharePoint 검색 시스템](https://docs.microsoft.com/sharepoint/dev/general-development/search-in-sharepoint)을 참조하세요.
  
## <a name="event-based-relevancy"></a>이벤트 기반 관련성
<a name="bkmk_EventBasedRelevancy"> </a>

검색 시스템은 콘텐츠가 연결된 방법, 검색 결과에서 항목이 나타나는 빈도 및 사용자가 클릭하는 검색 결과를 기준으로 검색 결과의 관련성을 결정합니다. 분석 구성 요소는 이 정보를 추적하고 분석하여 관련성을 계속해서 향상시킵니다. [분석 처리](https://docs.microsoft.com/SharePoint/search/overview-of-analytics-processing)에 대해 더 자세히 알아보세요.
  
## <a name="expertise-search"></a>전문 검색
<a name="bkmk_ExpertiseSearch"> </a>

SharePoint에서는 사용자 검색 범주에서 특정 기술이나 전문성을 갖춘 사람을 더 쉽게 찾을 수 있습니다. 이와 같은 검색 결과는 사용자가 자신의 개인 사이트에 입력한 개인 소개 메타데이터 및 해당 사용자들이 작성한 콘텐츠의 정보에 기반합니다. 자세한 내용은 [검색 범주 설정 변경](https://docs.microsoft.com/sharepoint/search/configure-properties-of-the-search-navigation-web-part)을 참조하세요.
  
## <a name="graphical-refiners"></a>그래픽 구체화
<a name="bkmk_GraphicalRefiners"> </a>

새로운 그래픽 구체화 기능을 사용하면 보다 시각적인 방식으로 검색 결과를 필터링할 수 있습니다. [구체화 웹 파트 구성](https://support.office.com/article/About-configuring-the-Refinement-Web-Part-7cef67e8-b992-4659-b21a-ba534eea102e)에 대해 더 자세히 알아보세요.
  
## <a name="hybrid-search"></a>Hybrid search
<a name="bkmk_HybridSearch"> </a>

하이브리드 방식으로 SharePoint를 배포한 경우에는 SharePoint Online과 SharePoint Server 2013 온-프레미스 사이트 둘 모두에서 검색 결과 콘텐츠를 가져올 수 있습니다. 하이브리드 SharePoint 환경에 대한 자세한 내용은 [하이브리드 SharePoint Server 2013](https://docs.microsoft.com/SharePoint/hybrid/hybrid)을 참조하세요.
  
## <a name="manage-search-schema"></a>검색 스키마 관리
<a name="bkmk_manage_search_schema"> </a>

사용자가 SharePoint 사이트에서 콘텐츠를 검색할 때에는 검색 인덱스에 따라 검색할 콘텐츠가 결정됩니다. 해당 사이트의 모든 문서와 페이지 정보가 포함되어 있는 검색 인덱스는 SharePoint 사이트의 콘텐츠를 크롤링하여 만듭니다. 검색 스키마는 크롤러가 선택할 콘텐츠와 메타데이터 및 인덱싱 방법을 결정하는 데 도움을 줍니다. 검색 스키마를 변경하여 사용자에게 알맞게 사용자 지정된 검색 환경을 만들 수 있습니다. 자세한 내용은 [SharePoint Online에서 검색 스키마 관리](https://docs.microsoft.com/sharepoint/manage-search-schema)를 참조하세요.
  
## <a name="on-hover-preview"></a>대화형 미리 보기
<a name="bkmk_Quickpreview"> </a>

검색 결과 위로 포인터를 가져가서 결과 오른쪽에 있는 호버 패널에서 문서 또는 사이트 콘텐츠를 미리 보고 상호 작용할 수 있습니다. 이 미리 보기에는 다양한 메타데이터가 표시되며 문서나 사이트의 기본 섹션으로 연결되는 딥 링크가 포함됩니다. 자세한 내용은 [검색 팁](https://support.office.com/article/Not-getting-the-search-results-you-re-looking-for-in-SharePoint-D80687F7-1010-4E6D-ADD9-584B423289D9)을 참조하세요.
  
## <a name="phonetic-name-matching"></a>발음 표시 일치
<a name="bkmk_PhoneticNameMatching"> </a>

향상된 발음 표시 일치 기능은 John 또는 Jon 같이 발음이 비슷한 검색 결과를 찾습니다. 자세한 내용은 [결과 원본 관리](https://docs.microsoft.com/sharepoint/manage-result-sources)를 참조하세요.
  
## <a name="query-rulesadd-promoted-results"></a>쿼리 규칙 - 승격된 결과 추가
<a name="bkmk_QueryRulesAddpromotedresults"> </a>

쿼리 규칙에 조건 및 상호 관련 작업을 지정할 수 있습니다. 쿼리가 쿼리 규칙에 정의된 조건을 충족하면 규칙에 지정된 작업이 수행됩니다. "승격된 결과 추가" 작업을 사용하면 개별 결과가 검색 결과 맨 위에 표시되도록 결과를 승격시킬 수 있습니다. 자세한 내용은 [쿼리 규칙 관리](https://docs.microsoft.com/SharePoint/search/manage-query-rules)를 참조하세요.
  
## <a name="query-rulesadvanced-actions"></a>쿼리 규칙 - 고급 작업
<a name="bkmk_UserRulesAdvancedActions"> </a>

쿼리 규칙에 조건 및 상호 관련 작업을 지정할 수 있습니다. "결과 블록 추가" 작업을 사용하여 검색 결과의 하위 집합을 그룹으로 표시할 수 있습니다. "쿼리를 변경하여 순위가 지정된 결과 변경" 작업을 사용하여 반환된 검색 결과의 순위를 변경할 수 있습니다. 자세한 내용은 [쿼리 규칙 관리](https://docs.microsoft.com/SharePoint/search/manage-query-rules)를 참조하세요.
  
## <a name="query-spelling-correction"></a>쿼리 맞춤법 교정
<a name="bkmk_QuerySpellingCorrection"> </a>

제외 목록 및 포함 목록을 편집하여 결과 페이지에 쿼리 맞춤법 교정을 대신 표시할 쿼리를 결정할 수 있습니다. 이 기능을 "다음 항목을 찾으려고 했습니까?" 기능이라고도 합니다. [쿼리 맞춤법 교정](https://docs.microsoft.com/sharepoint/search/manage-query-spelling-correction)에 대해 더 자세히 알아보세요.
  
## <a name="query-suggestions"></a>쿼리 추천 단어
<a name="bkmk_Querysuggestions"> </a>

쿼리 추천 단어는 사용자가 이미 검색했던 구에서 추천됩니다. 추천 단어는 사용자가 쿼리를 입력할 때 검색 상자 아래에 나열됩니다. 쿼리 추천 단어는 자동으로 생성되며, 구를 시스템에 추천 단어로 추가할지 여부를 "항상" 또는 "사용 안 함"으로 설정할 수 있습니다. 자세한 내용은 [쿼리 추천 단어 관리](https://docs.microsoft.com/sharepoint/search/manage-query-suggestions)를 참조하세요.
  
## <a name="ranking-models"></a>순위 모델
<a name="bkmk_Ranking_Models"> </a>

SharePoint에서는 순위 모델을 사용하여 가장 연관 있는 항목이 먼저 표시되도록 검색 결과에 값을 할당합니다. 순위 모델은 특정 항목의 순위 점수를 계산하는 순위 요소 집합입니다. SharePoint Online과 SharePoint Server 2013에는 모두 추가로 사용자 지정하지 않고도 순위를 효과적으로 제공하는 순위 모델이 여러 개 포함됩니다. 그러나 최종 사용자에게 훨씬 더 연관성 있는 검색 결과가 필요한 경우 순위 모델을 사용자 지정할 수 있습니다. 순위 모델 조정 앱을 통해 SharePoint Online 고객은 사용자 지정 순위 모델을 만들 수 있습니다. 이 앱에서는 기존 순위 모델을 복사하고, 쿼리 집합의 결과를 평가하며, 순위 기능을 추가하거나 제거한 후 해당 기능의 비중을 조정함으로써 순위 모델을 "조정"할 수 있는 사용자 인터페이스를 제공합니다. 자세한 내용은 [검색 결과 순위](https://docs.microsoft.com/sharepoint/search/overview-of-search-result-ranking)를 참조하세요.
  
## <a name="refiners"></a>구체화
<a name="bkmk_Refiners"> </a>

구체화 기능은 사용자가 검색 결과를 필터링할 수 있도록 SharePoint Server 검색 결과의 인기 문서를 그룹으로 분류합니다. [구체화 웹 파트 구성](https://support.office.com/article/About-configuring-the-Refinement-Web-Part-7cef67e8-b992-4659-b21a-ba534eea102e)에 대해 더 자세히 알아보세요.
  
## <a name="restful-query-apiquery-om"></a>RESTful 쿼리 API/쿼리 OM
<a name="bkmk_RESTfulQueryAPI"> </a>

개발자는 공용 검색 개체 모델에 액세스하기 위한 .NET 코드를 작성할 수 있습니다. 이 작업에는 검색 관리 작업뿐 아니라 검색 쿼리를 전송하는 과정도 포함됩니다. 서비스 쪽 개체 모델과 상호 작용하기 위해서는 팜에 속해 있는 웹 서버에서 .NET 코드가 실행되어야 합니다. CSOM(클라이언트 쪽 개체 모델)을 사용하면 원격 컴퓨터에서도 개체 모델의 일부에 액세스할 수 있습니다. CSOM의 기능에 액세스하려면 REST 기반 웹 서비스나 oData를 사용해야 합니다. 이렇게 하면 개발자가 보편적으로 사용되는 웹 개발 도구를 통해 SharePoint Server 2013 팜에 쿼리를 전송할 수 있습니다.
  
## <a name="search-results-sorting"></a>검색 결과 정렬
<a name="bkmk_Searchresultssorting"> </a>

관련성, 날짜 및 사회적 거리(사용자 이름)와 같이 다양한 기준으로 검색 결과를 정렬할 수 있습니다. 자세한 내용은 [검색 결과 정렬](https://support.office.com/article/change-settings-for-the-search-results-web-part-40ff85b3-bc5e-4230-b1dd-f088188e487e)을 참조하세요.
  
## <a name="this-list-searches"></a>"현재 목록" 검색
<a name="bkmk_ThisListSearches"> </a>

SharePoint Online과 SharePoint Server 2013에서는 검색을 수행하는 목록이나 라이브러리로 검색을 제한할 수 있습니다. SharePoint Foundation 2013에서 검색을 수행하면 검색을 수행하는 사이트 또는 그 하위의 모든 목록과 라이브러리에서 결과가 반환됩니다.
  
## <a name="feature-availability"></a>기능 가용성
<a name="bkmk_ThisListSearches"> </a>

Office 365 계획, 독립 실행형 옵션 및 온-프레미스 솔루션별로 기능 가용성을 확인하려면 [SharePoint Online 서비스 설명](sharepoint-online-service-description.md)을 참조하세요.
  

