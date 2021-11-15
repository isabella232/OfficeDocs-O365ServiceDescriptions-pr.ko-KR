---
title: SharePoint 제한
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: article
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: Microsoft 365 및 독립 실행형 계획에 대한 SharePoint 제한에 대해 알아보세요.
ms.openlocfilehash: 34d9dfa84991fb5842a3778f52c26c9c3f2a7ecf
ms.sourcegitcommit: d8df217b7511b1d7ceb8a66a27a552f4503c4c40
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 11/15/2021
ms.locfileid: "60963516"
---
# <a name="sharepoint-limits"></a>SharePoint 제한

Microsoft 365 SharePoint의 서비스 제한에 대해 알아보세요.
  
## <a name="limits-by-plan"></a>플랜별 제한 사항 

| 기능 | Microsoft 365 Business Basic, Business Standard 또는 Business Premium | Microsoft 365 E3 또는 E5, Office 365 E1, E3 또는 E5 또는 SharePoint 플랜 1 또는 2 | Microsoft 365 F1 또는 F3, Office 365 F3 |
|:-----|:-----|:-----|:-----|
|조직당 총 저장소<sup>1, 2, 6</sup> <br/> |1TB + 구매한 라이선스당 10GB<sup>3</sup>  <br/> |1TB + 구매한 라이선스당 10GB<sup>3</sup> <br/> |1TB<sup>3</sup> <br/> |
|사이트당 최대 저장소(사이트 모음)<sup>4</sup><br/> |25TB <br/> |25TB <br/> |25TB<sup>5</sup> <br/> |
|조직당 사이트(사이트 모음)  <br/> |2백만<sup>6</sup> <br/> |2백만<sup>6</sup> <br/> |2백만<br/> |
|사용자 수  <br/> |최대 300  <br/> |1- 500,000<sup>7</sup> <br/> |1- 500,000<sup>7</sup> <br/> |
   
<sup>1</sup> [조직 전체의 사용 가능한 저장소 찾는 방법 알아보기](/sharepoint/manage-site-collection-storage-limits). 추가 SharePoint 저장소를 무제한으로 구입할 수 있습니다. [구독에 대한 저장소 공간 추가](/office365/admin/subscriptions-and-billing/add-storage-space)를 참조하세요. 
<br/><sup>2</sup> 휴지통을 모니터링하며 정기적으로 비우는 것이 좋습니다. 휴지통에서 사용하는 저장소 공간은 조직이 사용하는 총 저장소 한도의 일부입니다. 
<br/> <sup>3</sup> Microsoft 365 구독 및 Office 365 Extra File Storage 추가 기능이 있는 경우 저장소 용량이 추가됩니다. 
<br/> <sup>4</sup> 이것은 각 사이트에 *제공되는* 저장소 양이 아니라 단일 사이트(이전의 "사이트 모음")에 대한 저장소 *제한* 입니다. 이 제한은 Office 365 그룹에 연결된 팀 사이트 및 OneDrive를 비롯한 모든 유형의 사이트에 적용됩니다. SharePoint 관리자는 [더 낮은 저장소 제한](/sharepoint/manage-site-collection-storage-limits#manage-individual-site-storage-limits)을 수동으로 설정할 수 있습니다. 
<br/> <sup>5</sup> 일선 직원들은 사이트와 같은 사이트를 관리할 SharePoint 없습니다. 
<br/> <sup>6</sup> 사용이 허가된 각 사용자에 대해 만든 OneDrive를 포함하지 않습니다. 
<br/> <sup>7</sup> 사용자가 500,000명 이상인 경우 Microsoft 담당자에게 문의하세요. 
  
## <a name="service-limits-for-all-plans"></a>모든 플랜에 대한 서비스 제한

### <a name="file-size-and-file-path-length"></a>파일 크기 및 파일 경로 길이

- **250 GB - 파일 업로드 제한입니다.** Microsoft Teams 파일 탭, SharePoint 문서 라이브러리, OneDrive 폴더 및 Yammer 대화에 업로드된 각 개별 파일에 적용됩니다.

- **250MB - 목록 항목에 첨부된 파일입니다.** 동일한 목록 플랫폼을 기반으로 하는 Microsoft 목록 및 SharePoint 목록에 적용됩니다.

- 파일 이름을 포함하여 디코딩된 전체 파일 경로는 400자 이상을 포함할 수 없습니다OneDrive OneDrive 또는 학교의 경우 SharePoint Microsoft 365. 이 제한은 디코딩 후 폴더 경로와 파일 이름의 조합에 적용됩니다. 자세한 내용은 파일 이름 및 경로 [길이로 이동하세요.](https://support.microsoft.com/office/restrictions-and-limitations-in-onedrive-and-sharepoint-64883a5d-228e-48f5-b3d2-eb39e07630fa#filenamepathlengths)

새 OneDrive 동기화 앱(OneDrive.exe)을 사용할 때의 제약사항 및 제한에 대한 자세한 내용은 [잘못된 파일 이름 및 파일 형식](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa)을 참조하세요.

### <a name="items-in-lists-and-libraries"></a>목록 및 라이브러리의 항목

목록의 항목 수는 최대 3천만 개이며 라이브러리의 파일 및 폴더 수는 최대 3천만 개입니다. 목록, 라이브러리 또는 폴더에 100,000개 이상의 항목이 포함된 경우 목록, 라이브러리 또는 폴더에 대한 사용 권한 상속을 중단할 수 없습니다. 또한 사용 권한을 다시 상속할 수 없습니다. 그러나 목록이나 라이브러리의 최대 고유 권한 수까지 해당 목록, 라이브러리 또는 폴더 내의 개별 항목에 대한 상속을 중단할 수 있습니다(다음 섹션 참조). 큰 목록 보기의 다른 제한 사항에 대한 자세한 내용은 [Office 365에서 큰 목록 및 라이브러리 관리](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784)를 참조하세요.

### <a name="managed-metadata"></a>관리되는 메타데이터

총 200만 개의 용어 레이블과 100만 개의 용어 속성이 있는 총 100만 개의 용어가 있습니다(이 제한은 전역 및 사이트 수준 용어를 합한 것입니다). 글로벌 용어 집합 1,000개 및 글로벌 그룹 1,000개입니다.

### <a name="moving-and-copying-across-sites"></a>사이트 간 이동 및 복사

단일 작업에서 여러 파일을 복사/이동하려는 경우, 다음 세 가지 요구 사항이 있습니다.

- 총 파일 크리 100GB 이하
- 30,000개 이하의 파일
- 각 파일은 15GB 미만이어야 함

### <a name="overall-site-metadata"></a>전체 사이트 메타데이터

사이트당 1000GB(메타데이터는 이 크기에 거의 도달하지 않습니다).

### <a name="sharepoint-groups"></a>SharePoint 그룹

사용자는 사이트(사이트 모음)당 5,000개의 그룹에 가입할 수 있으며 각 그룹에 허용되는 사용자 수는 최대 5,000명입니다. 사이트(사이트 모음)당 최대 10,000개의 그룹까지 허용됩니다.

> [!NOTE]
> Azure AD 그룹 제한은 [Azure AD 서비스 제한 및 제약사항](/azure/active-directory/users-groups-roles/directory-service-limits-restrictions)을 참조하세요. 이러한 제한은 공개 및 비공개 그룹 사이트 멤버 자격 관리에 영향을 미칠 수 있습니다.

### <a name="sharepoint-hosted-applications"></a>SharePoint 호스팅 응용 프로그램

조직당 20,000개의 인스턴스입니다.

### <a name="sharepoint-workflow"></a>SharePoint 워크플로

SharePoint 또는 명시적 중지 작업이 없는 경우 2013 워크플로를 디자인에 따라 계속 실행할 수 있습니다.

### <a name="subsites"></a>하위 사이트

사이트(사이트 모음)당 2,000개입니다. 하위 사이트를 만드는 대신 사이트를 만들고 허브로 구성하는 것이 좋습니다. 하위 사이트를 사용하는 경우 (특히 많이 손상된 사이트에서) 해당 수를 제한하는 것이 좋습니다.

> [!NOTE]
> 조직은 2,000개의 허브 사이트로 제한됩니다. 일부 기능에는 허브 사이트가 필요하지 않을 수 있으며 허브를 만들기 전에 몇 가지 계획을 세우는 것이 중요합니다. 자세한 내용은 [SharePoint 허브 사이트 계획을 참조하세요.](/sharepoint/planning-hub-sites)

### <a name="lists-and-libraries"></a>목록 및 라이브러리

사이트 모음당 결합된 목록 및 라이브러리 2,000개(주 사이트 및 모든 하위 사이트 포함)

### <a name="sync"></a>동기화

최적의 성능을 위해 단일 OneDrive 또는 팀 사이트 라이브러리에는 파일을 300,000개 이상 저장하지 않는 것이 좋습니다. SharePoint Online에서는 라이브러리당 3천만 개 문서를 저장할 수 있지만, 최적의 성능을 위해 모든 문서 라이브러리에서 파일을 300,000개 이상 동기화하지 않는 것이 좋습니다. 또한 동기화하는 모든 라이브러리에서 항목이 300,000개 이상인 경우, 해당 라이브러리의 항목을 일부만 동기화하는 경우에도 동일한 성능 문제가 발생할 수 있습니다. 비즈니스용 OneDrive 동기화 클라이언트의 이전 버전(Groove.exe)을 사용하는 경우 라이브러리당 동기화 한도는 20,000개 항목입니다(팀 사이트당 5,000개 항목 포함).

### <a name="unique-security-scopes-per-list-or-library"></a>목록 또는 라이브러리당 고유한 보안 범위

큰 목록의 경우 고유한 권한을 최대한 적게 갖고 총 5,000개 미만으로 유지하도록 설계합니다.

### <a name="users"></a>사용자

사이트 모음당 2백만 명

> [!NOTE]
> SharePoint 사이트에 초대할 수 있는 게스트 수에는 고유한 제한이 없습니다. 외부 공유에 대한 자세한 내용은 [외부 공유 개요](/sharepoint/external-sharing-overview)를 참조하세요.

### <a name="versions"></a>버전

주 버전 50,000개 및 부 버전 511개.

## <a name="see-also"></a>참고 항목

[SharePoint의 검색 제한](/sharepoint/search-limits)
