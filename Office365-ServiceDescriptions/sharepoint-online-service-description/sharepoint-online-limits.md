---
title: SharePoint Online 제한 사항
ms.author: sharik
author: skjerland
audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: Office 365 Enterprise 요금제 및 독립 실행형 요금제의 SharePoint Online 제한 사항에 대해 알아봅니다.
ms.openlocfilehash: 5c89f7fa92a91a780be9350e16be87e537370586
ms.sourcegitcommit: 15e92292209454f6778bfef26ecab96bfc71ef5f
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/22/2019
ms.locfileid: "34342537"
---
# <a name="sharepoint-online-limits"></a>SharePoint Online 제한 사항

Office 365 요금제 및 SharePoint Online 독립 실행형 계획에 대 한 SharePoint 제한을 확인 합니다.
  
## <a name="limits-by-plan"></a>요금제 별 제한

|||||
|:-----|:-----|:-----|:-----|
|**기능** <br/> |**Office 365 Business Essentials 또는 Business Premium** <br/> |**Office 365 Enterprise E1, E3 또는 E5, 또는 SharePoint Online 계획 1 또는 2** <br/> | **Office 365 Enterprise F1** <br/> |
|저장소<sup>1, 2</sup> <br/> |조직 당 1TB 및 구매한 라이선스 당 10gb  <br/> |조직 당 1TB 및 구매한 라이선스 당 10gb<sup>3</sup> <br/> |조직 당 1TB 1 <sup></sup> 개 <br/> |
|사이트 모음에 대 한 저장소  <br/> |사이트 모음 또는 그룹<sup>4</sup> 당 최대 25tb <br/> |사이트 모음 또는 그룹<sup>4</sup> 당 최대 25tb <br/> |사이트 모음 또는 그룹<sup>5</sup> 당 최대 25tb <br/> |
|조직 당 사이트 모음 수  <br/> |50만<sup>6</sup> <br/> |50만<sup>6</sup> <br/> |500,000<br/> |
|사용자 수  <br/> |최대 300  <br/> |1-50만<sup>7</sup> <br/> |1-50만<sup>7</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> 무제한의 추가 SharePoint Online 저장소를 구입할 수 있습니다. [구독에 대 한 저장소 공간 변경](https://support.office.com/article/96EA3533-DE64-4B01-839A-C560875A662C)를 참조 하세요. 
<br/><sup>2</sup> 휴지통을 모니터링 하 고 정기적으로 비우는 것이 좋습니다. 휴지통에서 사용하는 저장소 공간은 조직이 사용하는 총 파일 저장소 한도의 일부입니다. 
<br/> <sup>3</sup> Office 365 구독 및 SharePoint Online 독립 실행형 요금제가 있는 경우 저장 금액이 추가 됩니다. 
<br/><sup>4</sup> SharePoint Online 관리자는 사이트 모음 및 사이트에 대 한 저장 제한을 설정할 수 있습니다.
<br/> <sup>5</sup> Kiosk Worker는 SharePoint Online 사이트 모음을 관리할 수 없습니다. 키오스크 사이트 모음을 관리 하려면 최소한 하나의 Enterprise 사용자 라이선스가 필요 합니다. 
<br/> <sup>6</sup> 사용이 허가 된 각 사용자에 대해 만들어진 비즈니스용 OneDrive 사이트 모음을 포함 하지 않습니다. 
<br/><sup>7</sup> 사용자가 50만 명 이상인 경우 Microsoft 담당자에 게 문의 하세요. 
  

  
## <a name="service-limits-for-all-plans"></a>모든 계획에 대 한 서비스 제한

- 목록 **및 라이브러리의 항목** -목록은 최대 3000만 개의 항목을 포함할 수 있으며 라이브러리에는 파일 및 폴더를 최대 3000만 개까지 포함할 수 있습니다. 100 이면 목록, 라이브러리 또는 폴더에 00 개의 항목이 추가 되 고, 목록, 라이브러리 또는 폴더에 대 한 사용 권한 상속은 변경할 수 없습니다. 큰 목록 보기의 다른 제한 사항에 대한 자세한 내용은 [Office 365에서 큰 목록 및 라이브러리 관리](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784)를 참조하세요. 파일 이름에 사용할 수 없는 문자에 대 한 자세한 내용은 [파일 및 폴더 이름에서 잘못 된 문자](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa)를 참조 하세요.

- **파일 크기 및 파일 경로 길이** -15gb 새 OneDrive 동기화 클라이언트 (OneDrive)를 사용할 때의 제한 및 제한 사항에 대 한 자세한 내용은 [onedrive, 비즈니스용 onedrive 및 SharePoint에서 잘못 된 파일 이름 및 파일 형식을](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa)참조 하세요.

- **사이트 모음 간에 이동 및 복사** -100 GB입니다. 웹 브라우저가 열린 상태를 유지 해야 합니다.

- **Sync** -최적의 성능을 위해 단일 OneDrive 또는 팀 사이트 라이브러리에 30만 개 이하의 파일을 저장 하는 것이 좋습니다. SharePoint Online은 라이브러리 마다 3000만 문서를 저장할 수 있지만 최적의 성능을 위해 모든 문서 라이브러리에서 30만 개 이하의 파일을 동기화 하는 것이 좋습니다. 또한 이러한 라이브러리의 모든 항목을 동기화 하는 것이 아니더라도 동기화 중인 모든 라이브러리에 30만 개 항목이 있는 경우에도 동일한 성능 문제가 발생할 수 있습니다. 이전 비즈니스용 OneDrive 동기화 클라이언트 (Groove)를 사용 하는 경우 라이브러리 당 동기화 제한은 2만 항목 (팀 사이트 당 5000 항목 포함)입니다.

- **버전** -5만 주 버전 및 511 부 버전

- **SharePoint 그룹** -사용자가 5000 그룹에 속할 수 있으며, 각 그룹은 최대 5000 명의 사용자를 포함할 수 있습니다. 사이트 모음당 최대 10,000개의 그룹까지 허용됩니다.

- **관리 되는 메타 데이터** -용어 저장소의 20만 용어, 1000 전역 용어 집합, 1000 그룹.

- **하위** 사이트-사이트 모음 당 최대 2000

- **SharePoint에서 호스트 하는 응용 프로그램** -조직 당 2만 인스턴스

- **목록 또는 라이브러리인 라이브러리-5000의 고유한 보안 범위** 큰 목록의 경우에는 가능한 한 한 가지 고유한 사용 권한을 갖도록 디자인 합니다.

- **사용자** -사이트 모음 당 200만

> [!NOTE]
> SharePoint Online 사이트 모음에 초대할 수 있는 외부 사용자의 수에는 제한이 없습니다. 자세한 내용은 [SharePoint Online 환경에 대한 외부 공유 관리](/sharepoint/external-sharing-overview)를 참조하세요.

## <a name="see-also"></a>참고 항목

[SharePoint Online에 대 한 검색 제한](/sharepoint/search-limits)
