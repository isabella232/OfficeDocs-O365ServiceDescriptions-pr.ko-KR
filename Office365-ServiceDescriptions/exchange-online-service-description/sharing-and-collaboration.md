---
title: 공유 및 공동 작업
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-sharing-and-collaboration
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 862dab54-701f-4014-a594-0b71e03772d2
ms.openlocfilehash: 114812240efb18573ed7defaa88010bebfdac0bd
ms.sourcegitcommit: 96dc758c790ddaf05f5c2b836451b417729cf119
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/18/2019
ms.locfileid: "35776919"
---
# <a name="sharing-and-collaboration"></a>공유 및 공동 작업

## <a name="federated-sharing"></a>페더레이션 공유

페더레이션은 페더레이션 공유를 지원하는 기본 트러스트 인프라를 나타내며 Microsoft Exchange Online 사용자가 다른 외부 페더레이션 조직의 받는 사람 또는 인터넷으로 액세스하는 사용자와 약속 있음/없음 일정 데이터 및 연락처 정보를 공유할 수 있는 방법입니다. 여기에는 Exchange Online에서도 호스트되는 조직, 외부 Microsoft Exchange Server 2010 또는 Exchange Server 2013 조직이 포함됩니다. Exchange Online 관리자는 조직 관계 및 공유 정책을 사용하여 Microsoft Outlook Web App 또는 Microsoft Outlook 2010 이상 버전에서 사용자가 일정 공유 초대를 보낼 수 있도록 설정할 수 있습니다.
  
> [!IMPORTANT]
>  외부 Exchange 2010 및 Exchange 2013 조직은 페더레이션 공유 구성의 일부로 Microsoft 페더레이션 게이트웨이와의 페더레이션 트러스트를 구성해야 합니다. 그러나 Exchange Online 조직의 경우에는 Office 365 테넌트가 만들어질 때 Microsoft 페더레이션 게이트웨이와의 페더레이션 트러스트가 자동으로 만들어지므로 페더레이션 트러스트를 구성할 필요가 없습니다. >  Exchange Online 조직이 페더레이션 공유를 사용하려면 조직 관계 또는 공유 정책을 구성해야 합니다. >  페더레이션 공유에서 다른 Office 365 테넌트의 Exchange Online 조직 간 GAL(전체 액세스 목록) 공유 또는 사용자 사서함 이동은 지원되지 않습니다. 
  
페더레이션 공유에 대한 자세한 내용은 [Exchange Online의 공유](https://go.microsoft.com/fwlink/p/?LinkId=271774)를 참조하세요.
  
## <a name="site-mailboxes"></a>사이트 사서함

전자 메일과 문서는 일반적으로 두 가지 고유한 별도의 데이터 리포지토리에 보관됩니다. 대부분의 팀은 전자 메일과 문서를 사용하여 공동 작업을 수행합니다. 문제는 전자 메일과 문서가 여러 가지 클라이언트를 사용하여 액세스된다는 점입니다. 이에 따라 사용자 생산성이 감소하고 사용자 환경이 저하되는 경우가 많습니다.
  
사이트 사서함은 이 문제를 해결하기 위해 시도되는 Exchange 2013의 새로운 개념입니다. 사이트 사서함은 동일한 클라이언트를 사용하여 Microsoft SharePoint 2013 문서와 Exchange 전자 메일에 대한 액세스를 허용하므로 공동 작업의 능률과 사용자 생산성을 향상합니다. 사이트 사서함의 기능은 SharePoint 2013 사이트 구성원(소유자 및 구성원), 전자 메일 메시지용 Exchange 2013 사서함 및 문서용 SharePoint 2013 사이트를 통한 공유 저장소, 프로비저닝 및 수명 주기 요구를 처리하는 관리 인터페이스 등으로 구성됩니다.
  
> [!IMPORTANT]
> Office 365 계획에 SharePoint가 포함되어야 합니다. 사이트 사서함을 사용하려면 사용자에게 SharePoint와 Exchange 라이선스가 둘 다 있어야 합니다. 
  
사이트 사서함에 대한 자세한 내용은 [사이트 사서함](https://go.microsoft.com/fwlink/p/?LinkId=271789)을 참조하세요.
  
## <a name="public-folders"></a>공용 폴더

Exchange Online의 공용 폴더는 사서함 데이터베이스의 기존 고가용성 및 저장소 기술을 활용하도록 새롭게 바뀌었습니다. 공용 폴더 아키텍처에서는 특별히 설계된 사서함을 사용하여 계층 구조와 공용 폴더 내용을 모두 저장합니다. 이는 별도의 공용 폴더 데이터베이스가 더 이상 존재하지 않음을 의미합니다. 공용 폴더 복제에서는 이제 연속 복제 모델을 사용합니다. 계층 및 콘텐츠 사서함에 대한 고가용성은 데이터 센터의 DAG(데이터베이스 사용 가능 그룹)를 통해 제공됩니다. Exchange Online에서 공용 폴더 사서함은 1000 개로 제한 됩니다. 또한 각 공용 폴더 사서함에는 최대 저장소 크기가 있습니다. 자세한 내용은 [Exchange Online 제한](exchange-online-limits.md)의 "사서함 폴더 제한" 섹션을 참조하십시오. 공용 폴더 사서함의 경우 메시지, 받는 사람 및 용량 경고 제한은 일반 사서함과 같습니다. 자세한 내용은 [받는 사람](recipients.md)을 참조하십시오. 
  
공용 폴더에 대한 자세한 내용은 [공용 폴더](https://go.microsoft.com/fwlink/p/?LinkId=271790)를 참조하세요.
  
## <a name="group-and-shared-mailboxes"></a>그룹 및 공유 사서함

그룹 및 공유 사서함을 사용하면 특정 사용자 그룹이 공용 전자 메일 주소와 같은 공통 계정(예: info@contoso.com 또는 contact@contoso.com)에서 손쉽게 전자 메일을 보내고 모니터링할 수 있습니다. 그룹의 한 사람이 공유 사서함에 보낸 메시지에 회신하면 전자 메일은 개인 사용자가 아니라 공유 사서함에서 보내는 것으로 표시됩니다.
  
일반적으로 그룹 또는 공유 사서함에는 별도의 사용자 라이선스가 필요하지 않습니다. 그러나 그룹 또는 공유 사서함에 대해 원본 위치 보관을 사용하도록 설정하려면 Exchange Online 계획 1 또는 Exchange Online 계획 2 라이선스를 할당해야 합니다. 이러한 라이선스가 할당되면 사서함 크기가 라이선스 계획에 따라 증가합니다. 공유 사서함에 원본 위치 보관을 적용하려면 Exchange Online 계획 2 라이선스를 할당해야 합니다. 현재는 그룹 사서함을 할당할 수 없으나 총 라이선스 수를 고려해야 합니다.
  
원본 위치 보관은 라이선스가 적용된 단일 사용자나 엔터티의 메일을 보관하는 경우(예: 공유 사서함)에만 사용할 수 있습니다. 여러사용자나 엔터티의 메일을 저장하는 목적으로 원본 위치 보관함을 사용할 수는 없습니다. 예를 들어 IT 관리자는 공유 사서함을 만들 수 없고, 사용자가 명백히 보관을 목적으로 참조, 숨은 참조 필드 또는 전송 규칙을 통해 복사하도록 할 수 없습니다. 여러 사람이 사용하는 공유 사서함은 실제로 해당 개별 사용자의 전자 메일을 저장하지 않습니다. 여러 사용자에게 액세스 권한이 있으며 이러한 사용자는 공유 사서함으로 전자 메일을 보냅니다. 따라서 공유 사서함에 저장된 전자 메일은 공유 사서함으로서 이 사서함에서 주고받은 메일 뿐입니다.
  
## <a name="feature-availability"></a>기능 가용성

Office 365 계획, 독립 실행형 옵션 및 온-프레미스 솔루션별로 기능 가용성을 확인하려면 [Exchange Online 서비스 설명](exchange-online-service-description.md)을 참조하세요.
  

