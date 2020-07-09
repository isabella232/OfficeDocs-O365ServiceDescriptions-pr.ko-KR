---
title: SharePoint 제한
ms.author: sharik
author: skjerland
audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: Microsoft 365 및 독립 실행형 계획에 대 한 SharePoint 제한 사항에 대해 알아봅니다.
ms.openlocfilehash: 2dca7a0f3cbcdfd958d325d56caf8b0656b50680
ms.sourcegitcommit: 267c5bf4467aa1d7cc34e28d355bf38f5236c231
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/08/2020
ms.locfileid: "45082260"
---
# <a name="sharepoint-limits"></a>SharePoint 제한

Microsoft 365 용 SharePoint의 서비스 제한에 대해 알아봅니다.
  
## <a name="limits-by-plan"></a>요금제 별 제한 

|||||
|:-----|:-----|:-----|:-----|
|**기능** <br/> |**Microsoft 365 Business Basic 또는 Business Premium** <br/> |**Office 365 Enterprise E1, E3 또는 E5, 또는 SharePoint 계획 1 또는 2** <br/> | **Office 365 Enterprise F3** <br/> |
|조직<sup>1, 2, 6</sup> 당 총 저장소 <br/> |1TB 및 구매한 라이선스 당 10gb  <br/> |1TB 및 구매한 라이선스 당 10gb<sup>3</sup> <br/> |1TB<sup>3</sup> <br/> |
|사이트당 최대 저장소 (사이트 모음)<sup>4</sup><br/> |25tb <br/> |25tb <br/> |25 TB<sup>5</sup> <br/> |
|조직 당 사이트 (사이트 모음)  <br/> |200만<sup>6</sup> <br/> |200만<sup>6</sup> <br/> |200만<br/> |
|사용자 수  <br/> |최대 300  <br/> |1-50만<sup>7</sup> <br/> |1-50만<sup>7</sup> <br/> |
   
<sup>1</sup> [조직에서 사용할 수 있는 총 및 사용 가능한 저장소를 찾는 방법을 알아봅니다](/sharepoint/manage-site-collection-storage-limits). 무제한의 추가 SharePoint 저장소를 구입할 수 있습니다. [구독에 대 한 저장소 공간 변경](/office365/admin/subscriptions-and-billing/add-storage-space)를 참조 하세요. 
<br/><sup>2</sup> 휴지통을 모니터링 하 고 정기적으로 비우는 것이 좋습니다. 사용 하는 저장소 공간은 조직의 총 저장 용량 한도의 일부입니다. 
<br/> <sup>3</sup> Microsoft 365 구독 및 Office 365 추가 파일 저장소 추가 기능을 사용 하는 경우 저장소 금액이 추가 됩니다. 
<br/> <sup>4</sup> 이 값은 각 사이트에 대해 *제공 되* 는 저장 용량에 해당 하지 않고 단일 사이트 (이전에는 "사이트 모음")에 대 한 저장소 *제한* 입니다. 이 제한은 Office 365 그룹에 연결 된 팀 사이트 및 OneDrive를 포함 하 여 모든 유형의 사이트에 적용 됩니다. SharePoint 관리자가 [더 낮은 저장 제한을 수동으로 설정할](/sharepoint/manage-site-collection-storage-limits#manage-individual-site-storage-limits)수 있습니다. 
<br/> <sup>5</sup> firstline Worker는 SharePoint 사이트를 관리할 수 없습니다. 
<br/> <sup>6</sup> 사용 허가 된 각 사용자에 대해 만들어진 OneDrive를 포함 하지 않습니다. 
<br/> <sup>7</sup> 사용자가 50만 명 이상인 경우 Microsoft 담당자에 게 문의 하세요. 
  
## <a name="service-limits-for-all-plans"></a>모든 계획에 대 한 서비스 제한

### <a name="items-in-lists-and-libraries"></a>목록 및 라이브러리의 항목

목록에 항목이 최대 3000만 개까지 포함 될 수 있으며 라이브러리에는 파일 및 폴더를 최대 3000만 개까지 포함할 수 있습니다. 목록, 라이브러리 또는 폴더에 포함 된 항목이 10만 개 보다 많은 경우 목록, 라이브러리 또는 폴더에서 사용 권한 상속을 중단할 수 없습니다. 또한 사용 권한을 다시 상속할 수 없습니다. 그러나 해당 목록, 라이브러리 또는 폴더 내의 개별 항목에 대 한 상속을 목록 또는 라이브러리의 최대 고유 사용 권한 수까지 계속 나눌 수 있습니다 (다음 섹션 참조). 큰 목록 보기의 다른 제한 사항에 대한 자세한 내용은 [Office 365에서 큰 목록 및 라이브러리 관리](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784)를 참조하세요. 

> [!NOTE]
> 사이트에 포함할 수 있는 문서 라이브러리의 수에는 제한이 없습니다.

### <a name="unique-permissions-for-items-in-a-list-or-library"></a>목록 또는 라이브러리의 항목에 대 한 고유 권한

지원 되는 제한은 5만 고유 고유한 항목 이지만 권장 되는 일반적인 제한은 5000입니다. 5000 개 보다 많은 고유한 항목을 한 번에 변경 하는 것이 더 오래 걸립니다. 큰 목록의 경우에는 가능한 한 한 가지 고유한 사용 권한을 갖도록 디자인 합니다.

다른 제한은 고유 고유한 수 있는 항목 별로 5000 역할 할당입니다. 

### <a name="file-size-and-file-path-length"></a>파일 크기 및 파일 경로 길이

100 GB입니다. 목록 항목에 첨부 되는 파일의 최대 크기는 250입니다. 새 OneDrive 동기화 앱을 사용 하는 경우의 제한 사항에 대 한 자세한 내용은 [잘못 된 파일 이름 및 파일 형식](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa)OneDrive.exe를 참조 하세요.

### <a name="moving-and-copying-across-sites"></a>사이트 간 이동 및 복사

단일 작업에서 여러 파일을 복사/이동 하면 다음과 같은 세 가지 요구 사항이 있습니다. 

- 총 파일 크기 100 GB 이상 
- 3만 개 이하의 파일
- 각 파일은 2gb 미만 이어야 합니다.

### <a name="sync"></a>동기화

**새 OneDrive 동기화 앱** -최적의 성능을 위해, 주문형 파일을 사용 하거나 라이브러리 내에서 동기화 할 일부 폴더만 선택 해도 동기화 된 모든 문서 라이브러리에서 파일을 30만 개 이하로 저장 하는 것이 좋습니다.

**이전 비즈니스용 OneDrive 동기화 앱 (Groove.exe)** -동기화 된 모든 라이브러리에서 최대 2만 항목 합계를 동기화 할 수 있습니다. 여기에는 OneDrive 라이브러리, 팀 사이트 라이브러리 또는 둘 다 포함 됩니다. 전체 동기화 제한과 별도로, 각 라이브러리 유형에 대해 동기화 할 수 있는 항목 수에 제한이 있습니다.

   - OneDrive 라이브러리에서 최대 2만 개의 항목을 동기화 할 수 있습니다. 여기에는 폴더 및 파일이 포함 됩니다. 
   - SharePoint 라이브러리에서 최대 5000 개의 항목을 동기화 할 수 있습니다. 여기에는 폴더 및 파일이 포함 됩니다. 이 라이브러리는 팀 사이트 및 커뮤니티 사이트, 다른 사용자가 만들었거나 만든 라이브러리 또는 사이트 페이지에서 만든 라이브러리가 있는 다양 한 SharePoint 사이트에서 찾을 수 있습니다. 여러 SharePoint 라이브러리를 동기화 할 수 있습니다. 동기화 하는 모든 팀 사이트는 모든 동기화 된 라이브러리의 전체 2만 항목 제한에 대해서도 계산 됩니다.

> [!NOTE]
> 사용자가 수백 개의 파일을 포함 하는 문서 라이브러리의 파일을 동기화 해야 하는 경우 폴더의 사용 권한 수준을 "제한 된 읽기"로 설정 하 여 동기화 앱에서 폴더를 "숨길" 수 있습니다. 

### <a name="versions"></a>버전

5만 주 버전 및 511 부 버전

### <a name="sharepoint-groups"></a>SharePoint 그룹

사용자는 5000 그룹에 속할 수 있으며, 각 그룹은 최대 5000 명의 사용자를 포함할 수 있습니다. 사이트 (사이트 모음) 당 최대 1만 개의 그룹을 포함할 수 있습니다.

> [!NOTE]
> Azure AD 그룹 제한에 대 한 내용은 [AZURE ad 서비스 제한 및 제한을](/azure/active-directory/users-groups-roles/directory-service-limits-restrictions) 참조 하세요. 이러한 제한은 공용 및 개인 그룹 사이트 구성원 관리에 영향을 줄 수 있습니다. 

### <a name="managed-metadata"></a>관리되는 메타데이터

용어 저장소의 20만 용어, 1000 전역 용어 집합, 1000 그룹.

### <a name="overall-site-metadata"></a>전체 사이트 메타 데이터

사이트당 1000 (메타 데이터는이 크기에 거의 도달 하지 않음)

### <a name="subsites"></a>하위 

사이트 당 2000 개 (사이트 모음) 하위 사이트를 만드는 것이 아닌 위치를 만들어 허브로 구성 하는 것이 좋습니다. 하위 사이트를 사용 하는 경우에는 해당 번호를 제한 하는 것이 좋습니다 (특히 트래픽이 더 적은 사이트가 높은 경우).

### <a name="sharepoint-hosted-applications"></a>SharePoint 호스팅된 응용 프로그램

조직 당 2만 인스턴스

### <a name="people-editing-a-document-at-the-same-time"></a>문서를 한 번에 편집 하는 사용자

99 사용자는 문서를 편집 하기 위해 동시에 열 수 있습니다. 사용자가 10 명 넘게 동시에 문서를 편집 하는 경우 편집 내용이 충돌할 가능성이 더 향상 되 고 사용자 환경이 점차적으로 저하 됩니다.

### <a name="users"></a>사용자

사이트 당 200만 개 (사이트 모음)
   
> [!NOTE]
> SharePoint 사이트에 초대할 수 있는 게스트 수에는 제한이 없습니다. 외부 공유에 대 한 자세한 내용은 [외부 공유 개요](/sharepoint/external-sharing-overview)를 참조 하세요.

## <a name="see-also"></a>참고 항목

[SharePoint에 대 한 검색 제한](/sharepoint/search-limits)
