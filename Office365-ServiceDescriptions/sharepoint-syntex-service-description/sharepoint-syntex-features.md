---
title: SharePoint Syntex 기능
ms.author: office365servicedesc
author: pamelaar
manager: gailw
ms.audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
description: 적격 SharePoint, Office 365 온라인 계획에서 사용할 수 있는 주요 Office 365 Syn Microsoft 365 tex 기능에 대해 자세히 SharePoint 있습니다.
ms.openlocfilehash: 2ffc3ccb52d074434c89424a151e63c7698b62c2
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/09/2021
ms.locfileid: "51651033"
---
# <a name="sharepoint-syntex-features"></a>SharePoint Syntex 기능 

다음 섹션에서는 적합한 SharePoint, Office 365 및 온라인 계획에서 사용할 수 있는 주요 Office 365 [Syn Microsoft 365 tex](sharepoint-syntex-service-description.md) 기능에 SharePoint 대해 설명합니다. 사용 가능한 기능은 예고 없이 변경될 수 있습니다. 최신의 전체 기능 목록은 syntex 요금제 및 가격 SharePoint 페이지를 [참조하세요.](https://www.microsoft.com/microsoft-365/enterprise/sharepoint-syntex)

## <a name="syntex-content-center"></a>Syntex 콘텐츠 센터

Syntex는 대규모로 콘텐츠를 관리하고 메타데이터 및 워크플로를 통합하며 준수 자동화를 제공하기 위한 콘텐츠 센터라는 사이트 서식 &mdash;  &mdash; 파일을 제공합니다. 콘텐츠 센터는 클라우드에서 수동으로 문서를 읽고 처리하는 방법을 설명하는 기능을 제공합니다. Syntex는 이러한 정보를 사용하여 콘텐츠를 자동으로 인식하고, 중요한 정보를 추출하고, 메타데이터 태그를 적용합니다. 또한 통합 시각적 분석을 사용하여 모델의 효율성을 추적할 수 있습니다.

콘텐츠 센터 및 콘텐츠 센터를 만드는 방법에 대한 자세한 내용은 [Create a content center in SharePoint Syntex 를 참조하세요.](/microsoft-365/contentunderstanding/create-a-content-center)

## <a name="object-recognition"></a>개체 인식

Syntex는 일반적으로 인식되는 수천 개의 개체가 있는 새 시각적 사전을 사용하여 이미지에 자동으로 태그를 지정합니다. 또한 Syntex는 필기한 텍스트를 인식하고 검색 및 추가 처리를 위해 태그로 변환할 수 있습니다.

Syntex의 개체 인식 및 이미지 태그 지정을 구성하는 방법에 대한 자세한 내용은 [Syntex의](/microsoft-365/contentunderstanding/image-tagging)이미지 태그 SharePoint 참조합니다.

## <a name="document-understanding"></a>문서 이해

Syntex에서 기계 교육을 사용하여 코드가 없는 인공 지능(AI) 모델을 빌드하는 방식으로 콘텐츠를 읽는 방법을 교육할 수 있습니다. Syntex는 메타데이터를 자동으로 제안하거나 만들고, 사용자 지정 Power Automate 워크플로를 호출하고, 준수 레이블을 첨부하여 보존 또는 기록 관리 정책을 적용할 수 있습니다.

문서 이해 모델은 Azure 인지 서비스의 언어 이해 모델을 기반으로 합니다. 이러한 모델은 Syntex 콘텐츠 센터에서 만들어 관리하며, Syntex를 통해 모든 콘텐츠 센터의 모든 라이브러리에 모델을 게시하고 업데이트할 수 있습니다.

문서 이해에 대한 자세한 내용은 문서 이해 [개요를 참조하세요.](/microsoft-365/contentunderstanding/document-understanding-overview)

## <a name="form-processing"></a>양식 처리

Syntex에는 날짜, 그림, 이름 또는 주소와 같은 반구조적 문서나 구조화된 문서에서 공통 값을 자동으로 인식하고 추출할 수 있는 AI Builder를 기반으로 하는 강력한 양식 처리 엔진이 포함되어 있습니다. 이러한 모델은 코드 없이 만들어지며 신뢰할 수 있는 결과를 위해 몇 가지 문서만 요구합니다.

양식 처리에 대한 자세한 내용은 양식 처리 [개요를 참조하세요.](/microsoft-365/contentunderstanding/form-processing-overview)

## <a name="microsoft-graph-content-connectors"></a>Microsoft Graph 커넥터

Syntex는 Microsoft Graph 커넥터를 사용하여 파일 공유, Azure SQL 또는 Box 및 IBM FileNet과 같은 타사 소스를 Microsoft Graph Microsoft Graph 통합하여 전체적으로 검색하고 사용할 수 &mdash; &mdash; Microsoft 365.

Microsoft Graph 커넥터를 사용하여 고객은 Microsoft Search 결과에 포함하기 위해 외부 리포지토리의 항목을 인덱싱할 수 있습니다. Microsoft 365 E5 및 Office 365 E5에는 Microsoft Search용 Microsoft Graph 커넥터를 사용하여 최대 500개 항목을 인덱싱하는 기능을 포함합니다(A5에 포함되지 않음). SharePoint 또는 OneDrive 라이선스가 포함된 제품군 또는 독립 실행형 라이선스가 있는 사용자는 Microsoft Search용 Microsoft Graph 커넥터의 검색 결과를 볼 수 있습니다.

현재 Microsoft 또는 파트너 중 하나에서 130개가 넘는 소스에 대한 커넥터를 사용할 수 있습니다. 자세한 내용은 Microsoft Graph [커넥터 개요를 참조하세요.](/MicrosoftSearch/connectors-overview)

## <a name="advanced-taxonomy-services"></a>고급 세분화 서비스

Syntex에는 전체적으로 용어 만들기 및 사용을 보고 분석할 수 있는 기능이 Microsoft 365. 이러한 보고서는 SharePoint 관리 센터에서 전달됩니다.

공유 콘텐츠 형식은 허브 사이트를 통해 SharePoint Microsoft Teams SharePoint [있습니다.](/sharepoint/dev/features/hub-site/hub-site-overview) 중앙 갤러리에서 허브 사이트로 콘텐츠 형식을 게시하면 일반적으로 사용되는 콘텐츠 형식(콘텐츠 이해를 향상)을 필요한 경우 아키텍처의 광범위한 섹션에 신속하게 배포 및 업그레이드할 수 있습니다. 허브에 연결된 사이트는 게시되고 업데이트된 콘텐츠 형식을 자동으로 받게 됩니다.