---
title: SharePoint 제한
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: 독립 실행형 SharePoint 및 Microsoft 365 제한에 대해 자세히 알아보습니다.
ms.openlocfilehash: e48ce75a9656ca173ef74ddb32df619509629e27
ms.sourcegitcommit: c3cdb8074129fd7dff942a10a4fe8604fca563b6
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/14/2021
ms.locfileid: "51767478"
---
# <a name="sharepoint-limits"></a>SharePoint 제한

자세한 내용은 SharePoint 서비스 제한을 Microsoft 365.
  
## <a name="limits-by-plan"></a>계획에 따라 제한 

| 기능 | Microsoft 365 Business Basic, Business Standard 또는 Business Premium | Microsoft 365 E3 또는 E5, Office 365 E1, E3 또는 E5 또는 SharePoint 플랜 1 또는 2 | Microsoft 365 F1 또는 F3, Office 365 F3 |
|:-----|:-----|:-----|:-----|
|조직당 총 저장소<sup>수 1, 2, 6</sup> <br/> |구매한 라이선스당 1 TB 및<sup>10GB 추가 3개</sup>  <br/> |구매한 라이선스당 1 TB 및<sup>10GB 추가 3개</sup> <br/> |1 TB<sup>3</sup> <br/> |
|사이트당 최대 저장소(사이트 모음)<sup>4</sup><br/> |25 TB <br/> |25 TB <br/> |25 TB<sup>5</sup> <br/> |
|조직당 사이트(사이트 모음)  <br/> |2백만<sup>개 6</sup> <br/> |2백만<sup>개 6</sup> <br/> |200만 개<br/> |
|사용자 수  <br/> |최대 300개  <br/> |1- 500,000<sup>7</sup> <br/> |1- 500,000<sup>7</sup> <br/> |
   
<sup>1</sup> 조직에 대한 총 저장소 및 사용 가능한 저장소를 [찾는 방법에 대해 자세히 알아보습니다.](/sharepoint/manage-site-collection-storage-limits) 무제한으로 추가 저장소를 구입할 SharePoint 있습니다. 구독에 [대한 저장소 공간 추가를 참조하세요.](/office365/admin/subscriptions-and-billing/add-storage-space) 
<br/><sup>2</sup> 재활용란을 모니터링하고 정기적으로 비우는 것이 좋습니다. 사용하는 저장소 공간은 조직의 총 저장소 제한에 해당합니다. 
<br/> <sup>3</sup> 구독이 Microsoft 365 추가 Office 365 Extra File Storage 저장소 금액이 추가됩니다. 
<br/> <sup>4</sup> 단일 사이트(이전의 "사이트 모음")에 대한 저장소 제한으로, 각 사이트에 대해 제공된 저장소 양이 아니라 저장 용량입니다.   이 제한은 그룹에 연결된 팀 사이트 및 Office 365 사이트를 포함하여 모든 유형의 사이트에 OneDrive. SharePoint 관리자가 더 낮은 저장소 제한을 [수동으로 설정할 수 있습니다.](/sharepoint/manage-site-collection-storage-limits#manage-individual-site-storage-limits) 
<br/> <sup>5</sup> 일선 직원들은 사이트 내 사이트를 관리할 SharePoint 없습니다. 
<br/> <sup>6</sup> 사용이 허가된 OneDrive 대해 만든 정보를 포함하지 않습니다. 
<br/> <sup>7</sup> 사용자가 50만 명 이상인 경우 Microsoft 담당자에게 문의합니다. 
  
## <a name="service-limits-for-all-plans"></a>모든 계획에 대한 서비스 제한

### <a name="items-in-lists-and-libraries"></a>목록 및 라이브러리의 항목

목록에는 최대 3천만 개 항목이 저장될 수 있으며 라이브러리에는 최대 3,000만 개 파일 및 폴더가 저장될 수 있습니다. 목록, 라이브러리 또는 폴더에 100,000개가 넘는 항목이 포함되어 있는 경우 목록, 라이브러리 또는 폴더에 대한 사용 권한 상속을 중단할 수 없습니다. 또한 사용 권한을 다시 상속할 수 없습니다. 그러나 해당 목록, 라이브러리 또는 폴더 내의 개별 항목에 대한 상속을 목록 또는 라이브러리의 최대 고유 권한 수까지 중단할 수 있습니다(다음 섹션 참조). 큰 목록 보기의 다른 제한 사항에 대한 자세한 내용은 [Office 365에서 큰 목록 및 라이브러리 관리](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784)를 참조하세요.

### <a name="unique-security-scopes-per-list-or-library"></a>목록 또는 라이브러리당 고유 보안 범위

큰 목록의 경우 고유한 사용 권한을 최대한 적게 가지고 총 5,000개 미만으로 유지해야 합니다.

### <a name="file-size-and-file-path-length"></a>파일 크기 및 파일 경로 길이

250GB 새 OneDrive 동기화 앱(OneDrive.exe)을 사용할 때의 제한에 대한 자세한 내용은 잘못된 파일 이름 및 파일 형식을 [참조하세요.](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa)

### <a name="moving-and-copying-across-sites"></a>사이트 전체 이동 및 복사

단일 작업으로 여러 파일을 복사/이동하려면 다음 세 가지 요구 사항이 있습니다.

- 총 파일 크기가 100GB를 넘지 않습니다.
- 파일 30,000개 이상
- 각 파일은 15GB 미만이 되어야 합니다.

### <a name="sync"></a>동기화

최적의 성능을 유지하려면 단일 사이트 또는 팀 사이트 라이브러리에 300,000개 OneDrive 저장하는 것이 좋습니다. SharePoint Online에서는 라이브러리당 3,000만 개 문서를 저장할 수 있습니다. 최적의 성능을 위해 모든 문서 라이브러리에서 300,000개 파일을 동기화하는 것이 좋습니다. 또한 동기화하는 모든 라이브러리에 항목이 30만 개 이상 있는 경우 해당 라이브러리의 모든 항목을 동기화하지 않는 경우에도 동일한 성능 문제가 발생할 수 있습니다. 이전 비즈니스용 OneDrive 동기화 클라이언트(Groove.exe)를 사용하는 경우 라이브러리당 동기화 제한은 20,000개 항목(팀 사이트당 항목 5,000개 포함)입니다.

### <a name="versions"></a>버전

주 버전 50,000개와 부 버전 511개

### <a name="sharepoint-groups"></a>SharePoint 그룹

사용자는 사이트당 5,000개 그룹(사이트 모음)에 속할 수 있으며 각 그룹은 최대 5,000명까지 사용할 수 있습니다. 사이트당 최대 10,000개 그룹(사이트 모음)을 사용할 수 있습니다.

> [!NOTE]
> Azure AD 그룹 제한에 대한 자세한 내용은 [Azure AD](/azure/active-directory/users-groups-roles/directory-service-limits-restrictions) 서비스 제한 및 제한을 참조하세요. 이러한 제한은 공용 및 개인 그룹 사이트 구성원 관리에 영향을 줄 수 있습니다.

### <a name="managed-metadata"></a>관리되는 메타데이터

총 용어 수가 1백만 개로, 용어 레이블이 총 200만 개와 용어 속성이 1백만 개 있습니다(이러한 제한은 사이트 수준 용어의 전역 & 수임). 전역 용어 집합 1,000개와 전역 그룹 1,000개

### <a name="overall-site-metadata"></a>전체 사이트 메타데이터

사이트당 1,000GB(메타데이터가 이 크기에 도달하는 경우는 거의 없습니다.)

### <a name="subsites"></a>하위사이트

사이트당 2,000개(사이트 모음) 사이트를 만들고 하위 사이트를 만드는 대신 허브로 구성하는 것이 좋습니다. 하위 사이트를 사용하는 경우 해당 수를 제한하는 것이 좋습니다(특히 트래픽이 많은 사이트에서).

> [!NOTE]
> 조직은 2,000개 허브 사이트로 제한됩니다. 일부 기능에는 허브 사이트가 필요하지 않을 수 있으며 허브를 만들기 전에 몇 가지 계획을 세우는 것이 중요합니다. 자세한 내용은 SharePoint [허브 사이트 계획을 방문하세요.](/sharepoint/planning-hub-sites)

### <a name="sharepoint-hosted-applications"></a>SharePoint 응용 프로그램 관리

조직당 인스턴스 수가 20,000개입니다.

### <a name="users"></a>사용자

사이트 모음당 2,000만 개

> [!NOTE]
> 사이트에 초대할 수 있는 게스트 수에는 고유한 제한이 SharePoint 없습니다. 외부 공유에 대한 자세한 내용은 외부 공유 [개요 를 참조하세요.](/sharepoint/external-sharing-overview)

## <a name="see-also"></a>참고 항목

[검색에 대한 SharePoint](/sharepoint/search-limits)