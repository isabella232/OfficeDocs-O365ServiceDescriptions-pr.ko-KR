---
title: 계획 및 배포
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-planning-and-deployment
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: e44e5e61-1f5d-4e68-981d-77a42f0ea0d4
ms.openlocfilehash: 8175c34f7ab55935788d5238235ad7be66db8871
ms.sourcegitcommit: 830694c729ab53fcc8518b0cdd5322b322514431
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/25/2019
ms.locfileid: "33246344"
---
# <a name="planning-and-deployment"></a>계획 및 배포

## <a name="planning-for-service-changes-and-growth"></a>서비스 변경 및 성장 계획

조직은 원본 전자 메일 시스템, 원하는 종료 상태(완전 호스트 또는 부분 호스트), 마이그레이션할 사용자 수, 종료 상태까지 얼마나 빠르게 도달할 수 있는지를 바탕으로 마이그레이션 옵션을 선택해야 합니다.
  
## <a name="deployment-options"></a>배포 옵션

- **클라우드 전용 배포** 조직이 모든 사용자의 사서함을 Exchange Online에 호스트합니다. 
    
- **Exchange 하이브리드 배포** 조직이 일부 사용자 사서함은 온-프레미스 Exchange 조직에 호스트하고 일부는 Exchange Online에 호스트합니다. 
    
### <a name="cloud-only"></a>클라우드 전용

클라우드 전용 배포는 Exchange Online 서비스 상태의 조직이 온-프레미스 Exchange 조직에 연결되지 않는 배포입니다. 모든 사용자 및 사서함은 Exchange Online 및 Office 365에서 호스트 및 관리됩니다.
  
### <a name="hybrid"></a>하이브리드

Microsoft Exchange 2003, Exchange 2007, Exchange 2010 및 Exchange 2013 온-프레미스 조직에서 사용할 수 있는 하이브리드 배포에서는 일부 사서함을 온-프레미스에 호스트하고 일부는 Exchange Online에 호스트하는 장기적 공존 구성 또는 모든 사용자 사서함을 Exchange Online에 호스트하는 마이그레이션 경로를 제공합니다. 조직에서 하이브리드 배포를 활용하면 기존 온-프레미스 Microsoft Exchange 조직의 풍부한 기능과 관리 제어 능력을 클라우드로 확장할 수 있습니다. 하이브리드 배포 기능에는 온-프레미스와 Exchange Online 조직 간의 메시지 추적을 비롯해 보안 메일 전송, 공유 일정 약속 있음/없음 정보 등이 포함됩니다.
  
하이브리드 배포에 대한 자세한 내용은 [Exchange Server 2013 하이브리드 배포](https://go.microsoft.com/fwlink/p/?LinkId=287035)를 참조하세요. 21Vianet에서 운영하는 Office 365를 사용하는 경우 [21Vianet에서 운영하는 Office 365에서 Exchange 하이브리드 배포 기능 구성](http://go.microsoft.com/fwlink/?LinkID=733373&amp;clcid=0x409)을 참조하세요.
  
> [!IMPORTANT]
> 온-프레미스 Exchange 2003 조직은 반드시 적어도 하나의 Exchange 2010 클라이언트 액세스/사서함 서버를 설치하여 Exchange Online과 함께 하이브리드 배포를 구성해야 합니다. 온-프레미스 Exchange 2007 조직은 반드시 적어도 하나의 Exchange 2010 또는 Exchange 2013 클라이언트 액세스 및 사서함 서버를 설치하여 Exchange Online과 함께 하이브리드 배포를 구성해야 합니다. 온-프레미스 Exchange 2010 및 Exchange 2013 조직은 기본적으로 Exchange Online과 함께 하이브리드 배포를 지원합니다. 하이브리드 배포의 Exchange Server 호환성에 대한 자세한 내용은 [하이브리드 배포 필수 구성 요소](https://go.microsoft.com/fwlink/p/?LinkId=243541)를 참조하세요. > 온-프레미스 Exchange 조직은 반드시 하이브리드 배포에 맞게 조직을 구성해야 합니다. 관리자는 Exchange Server 배포 도우미 및 하이브리드 구성 마법사를 사용하여 하이브리드 배포를 구성하는 것이 가장 좋습니다. 자세한 내용은 [Exchange Server 배포 도우미](https://go.microsoft.com/fwlink/p/?LinkId=287036)를 참조하세요.
  
## <a name="migration-options"></a>마이그레이션 옵션

조직은 원본 전자 메일 시스템, 원하는 종료 상태(완전 호스트 또는 부분 호스트), 마이그레이션할 사용자 수, 종료 상태까지 얼마나 빠르게 도달할 수 있는지를 바탕으로 마이그레이션 옵션을 선택해야 합니다. 가능한 마이그레이션 옵션은 다음과 같습니다.
  
- **IMAP 마이그레이션** IMAP 기반 전자 메일 시스템에서 Exchange Online으로 사서함 데이터를 마이그레이션합니다. 
    
- **단독형 Exchange 마이그레이션** 한 번의 단독형 마이그레이션을 통해 Exchange Server 2003, Exchange Server 2007, Exchange Server 2010, Exchange 2013 및 Hosted Exchange 시스템에서 Exchange Online으로 사서함을 마이그레이션합니다. 
    
- **미리 구성된 Exchange 마이그레이션** 미리 구성된 마이그레이션을 수행하여 웹 기반 마이그레이션 도구를 사용해 변경을 최소화하면서 Exchange Server 2003 또는 Exchange Server 2007에서 온-프레미스 인프라로 사서함을 마이그레이션합니다. 
    
- **원격 이동 마이그레이션** Exchange 하이브리드 배포 환경에서 온-프레미스 Exchange 사서함을 Exchange Online으로 마이그레이션합니다. 원격 이동 마이그레이션을 사용하려면 Exchange 하이브리드 배포 환경에 있어야 합니다. 
    
Exchange Online으로의 전자 메일 및 사서함 마이그레이션에 대한 자세한 내용은 [Exchange Online으로의 사서함 마이그레이션](https://support.office.com/en-us/article/-a3e3bddb-582e-4133-8670-e61b9f58627e)을 참조하세요.
  
### <a name="imap-migration"></a>IMAP 마이그레이션

Exchange Online은 IMAP를 지원하는 전자 메일 시스템에서 사서함 데이터를 마이그레이션하는 데 필요한 웹 기반 도구를 제공합니다. 관리자에게는 다음 마이그레이션 단계가 안내됩니다. 
  
1. 조직 내 사용자를 위한 사서함을 클라우드에 만듭니다. 일반적으로 .csv 파일을 업로드하거나 원격 Windows PowerShell을 사용해 수행할 수 있습니다.
    
2. 원격 서버 연결 설정을 입력합니다.
    
3. CSV 파일을 사용해 Exchange Online 사서함으로 마이그레이션할 사서함의 데이터를 지정합니다.
    
4. 정보가 입력되면 Exchange Online은 IMAP을 통해 사서함 콘텐츠를 마이그레이션합니다. 일정 항목, 연락처, 작업 및 기타 메일이 아닌 항목은 마이그레이션되지 않습니다.
    
IMAP 마이그레이션에 대한 자세한 내용은 [IMAP 서버에서 Exchange Online 사서함으로 전자 메일 마이그레이션](https://support.office.com/en-ie/article/Migrate-your-IMAP-mailboxes-to-Office-365-3fe19996-29bc-4879-aab9-5a622b2f1481) 및 [다른 유형의 IMAP 사서함 마이그레이션](https://support.office.com/en-ie/article/Migrate-other-types-of-IMAP-mailboxes-to-Office-365-58890ccd-ce5e-4d94-be75-560a3b70a706)을 참조하세요.
  
> [!IMPORTANT]
> 마이그레이션 중 원격 서버의 리소스 및 대역폭을 과도하게 사용하지 않기 위해 Exchange Online은 IMAP 서버에 10개 미만의 연결을 만듭니다. 
  
### <a name="cutover-exchange-migration"></a>단독형 Exchange 마이그레이션

Exchange Online은 온-프레미스 Exchange Server 2003, Exchange Server 2007 또는 Exchange Server 2010 환경에서 데이터를 마이그레이션하는 데 필요한 웹 기반 도구를 제공합니다. 관리자에게는 다음 마이그레이션 단계가 안내됩니다.
  
1. 온-프레미스 관리자 계정의 전자 메일 주소 및 자격 증명을 사용하여 자동 검색 서비스를 통해 Exchange Online을 온-프레미스 전자 메일 조직에 연결합니다.
    
2. Exchange Online은 RPC/HTTP 연결을 사용해 원격 서버에서 디렉터리 정보를 읽고 Exchange Online에 사서함을 만듭니다.
    
3. Exchange Online은 사서함 콘텐츠를 클라우드 사서함에 동기화합니다. Exchange Online으로 데이터가 마이그레이션되는 동안 사용자는 원래 사서함에 연결된 상태로 유지됩니다.
    
4. 초기 마이그레이션이 완료되면 관리자가 마이그레이션 일괄 처리를 중지하거나 삭제할 때까지 모든 변경 내용이 24시간마다 클라우드로 동기화됩니다.
    
사용자를 사용자의 사서함으로 전환하려면 관리자는 MX 기록이 Office 365를 가리키도록 구성하고 Outlook의 사용자 프로필을 다시 구성합니다. 사용자가 클라우드 사서함으로 전환하며 사용자의 로컬 오프라인 폴더(.ost 파일)이 다시 동기화되고, 클라이언트 워크스테이션에 마이그레이션된 전자 메일이 다운로드됩니다. 사용자는 마이그레이션이 완료되면 사서함의 기존 메시지를 회신할 수 있습니다.
  
단독형 Exchange 마이그레이션에 대한 자세한 내용은 [Office 365로 단독형 전자 메일 마이그레이션에 대해 알아야 할 사항](https://support.office.com/en-us/article/What-you-need-to-know-about-a-cutover-email-migration-to-Office-365-961978ef-f434-472d-a811-1801733869da)을 참조하세요.
  
> [!IMPORTANT]
> 조직에서는 단독 Exchange 마이그레이션을 사용하여 최대 2,000개의 Exchange 2003, Exchange 2007, Exchange 2010 또는 Exchange 2013 사서함을 클라우드로 마이그레이션할 수 있습니다. > Exchange Online이 온-프레미스 Exchange Server에 연결되어 온-프레미스 서버에 신뢰할 수 있는 인증 기관에서 발행한 인증서와 공용 IP 주소가 있어야 합니다. 
  
### <a name="staged-exchange-migration"></a>미리 구성된 Exchange 마이그레이션

미리 구성된 마이그레이션을 사용할 경우 웹 기반 Exchange 마이그레이션 도구 및 디렉터리 동기화 도구를 사용해 사용자를 클라우드로 마이그레이션할 수 있습니다. 관리자는 단독형 Exchange 마이그레이션처럼 모든 사용자를 한 번에 마이그레이션하지 않고 마이그레이션 일괄 처리할 수 있습니다. .csv 파일을 업로드하여 마이그레이션할 사용자의 부분 목록을 지정하는 방식으로 수행됩니다. 미리 구성된 마이그레이션에서는 조직의 모든 사용자가 동일한 도메인 이름을 공유합니다.
  
미리 구성된 Exchange 마이그레이션에서는 관리자가 Online Services의 디렉터리 동기화 도구를 사용해야 합니다. 이 도구는 온라인 환경이 지속적으로 온-프레미스 환경과 동기화되는 통합 전체 주소 목록(GAL)을 사용자에게 제공합니다.
  
미리 구성된 Exchange 마이그레이션에 대한 자세한 내용은 [Office 365로 미리 구성된 전자 메일 마이그레이션에 대해 알아야 할 사항](https://support.office.com/en-ie/article/What-you-need-to-know-about-a-staged-email-migration-to-Office-365-7e2c82be-5f3d-4e36-bc6b-e5b4d411e207)을 참조하세요.
  
> [!IMPORTANT]
> 조직에서는 Exchange 2010 및 Exchange 2013 사서함을 마이그레이션하는 데 단계별 Exchange 마이그레이션을 사용할 수 없습니다. 조직의 Exchange 2010 또는 Exchange 2013 사서함 수가 2,000개 미만이라면 단독 Exchange 마이그레이션을 사용할 수 있습니다. Exchange 2010 또는 Exchange 2013 사서함이 2,000개를 넘는 경우에는 하이브리드 배포를 구현할 수 있습니다. > 마이그레이션 중 관리자는 반드시 Online Services 디렉터리 동기화 도구를 사용해 온라인 환경이 지속적으로 온-프레미스 환경과 동기화되는 통합 전체 주소 목록을 사용자에게 제공해야 합니다. 
  
## <a name="migration-tools"></a>마이그레이션 도구

Microsoft는 기존 전자 메일 환경에서 Exchange Online으로 마이그레이션하는 데 도움이 되는 다양한 도구를 제공하고 있습니다. 조직의 현재 환경 및 배포 목표에 따라 적합한 도구를 사용하는 것이 좋습니다.
  
- **마이그레이션 대시보드** 관리자는 Exchange Online에 대한 단독 또는 단계별 Exchange 마이그레이션 수행 시 Exchange 관리 센터의 마이그레이션 대시보드를 사용하여 사서함 마이그레이션을 관리할 수 있습니다. 관리자는 대시보드를 사용하여 온-프레미스 IMAP 서버 사용자 사서함의 콘텐츠를 기존 Exchange Online 사서함으로 마이그레이션할 수도 있습니다. 관리자는 대시보드를 통해 다음 기능을 사용할 수 있습니다. 
    
  - **여러 마이그레이션 일괄 처리 만들기 및 시작** 관리자는 최대 100개의 마이그레이션 일괄 처리를 만들고 큐에 넣을 수 있습니다. 한 번에 하나의 마이그레이션 일괄 처리만 실행되지만, 관리자는 여러 일괄 처리를 대기시켜 하나의 마이그레이션 일괄 처리 실행이 완료되면 큐에 있는 다음 일괄 처리가 시작되게 할 수 있습니다. 
    
  - **실패한 마이그레이션 일괄 처리 다시 시작** 마이그레이션 일괄 처리에 대한 초기 동기화 후 각 사용자에 대한 마이그레이션 일괄 처리의 항목이 온-프레미스 사서함에서 클라우드 사서함으로 복사될 때 일부 사서함은 동기화에 실패할 수 있습니다. 관리자는 마이그레이션 일괄 처리가 실패한 사서함과 동기화하도록 다시 시작할 수 있습니다. 
    
  - **건너뛴 항목에 대한 세부 정보 얻기** IMAP 마이그레이션의 경우 마이그레이션 대시보드에는 건너뛴 특정 항목에 대한 정보가 이유 및 사용자 사서함 내 항목의 위치와 함께 표시됩니다. 
    
  - **마이그레이션 보고서 열기** 관리자는 마이그레이션 일괄 처리에 대한 마이그레이션 통계 또는 마이그레이션 오류 보고서를 대시보드에서 바로 열 수 있습니다. 
    
  - **마이그레이션 일괄 처리 편집** 미리 구성된 Exchange 마이그레이션 또는 IMAP 마이그레이션에 대한 마이그레이션 일괄 처리가 마이그레이션 큐에 있지만 현재 실행 중이 아닐 경우 관리자는 해당 마이그레이션 일괄 처리를 편집할 수 있습니다. 
    
- **Azure Active Directory 동기화 도구**Azure Active Directory 동기화 도구는 Exchange Online과 온-프레미스 Exchange Server를 모두 사용하는 하이브리드 전자 메일로 마이그레이션할 때 매우 중요한 역할을 수행합니다. 이 도구는 온-프레미스 Active Directory에서 Exchange Online으로 단방향 동기화를 수행합니다. 마이그레이션이 완료된 후 관리자는 Exchange Online만 사용하면 Active Directory 사용자 및 그룹을 관리할 수 있습니다. 또한 이 도구는 온라인 환경이 지속적으로 온-프레미스 환경과 동기화되는 통합 전체 주소 목록을 사용자에게 제공합니다. 
    
    Azure Active Directory 동기화 도구에 대한 자세한 내용은 [디렉터리 동기화 로드맵](https://go.microsoft.com/fwlink/p/?LinkId=287034)을 참조하세요.
    
- **하이브리드 구성 마법사** 하이브리드 구성 마법사는 온-프레미스 및 Exchange Online 기능 및 서비스에 대한 구성을 단순화하여 하이브리드 배포 프로세스를 원활하게 만들어 줍니다. Exchange Server 2010 서비스 팩 2의 일부로 소개된 하이브리드 구성 마법사는 온-프레미스 조직에서만 실행되며, 다음 구성 요소를 포함하고 있습니다. 
    
  - EAC(Exchange 관리 센터) 마법사가 관리자를 하이브리드 배포 구성을 위한 종단 간 프로세스로 안내합니다.
    
  - 일련의 Exchange 관리 셸(EMS) 명령이 구성 프로세스를 조정합니다.
    
    하이브리드 구성 마법사에 대한 자세한 내용은 [하이브리드 구성 마법사](https://go.microsoft.com/fwlink/p/?LinkId=271734)를 참조하세요.
    
- **원격 Windows PowerShell** Exchange Online 2011 12월 서비스 업데이트의 일환으로 원격 Windows PowerShell을 마이그레이션 오류를 해결하는 데 도움이 되도록 사용할 수 있게 되었습니다. 예를 들면 관리자는 기본 SMTP 주소를 기반으로 사용자에 대한 마이그레이션 통계 및 진단 정보 뿐만 아니라 마이그레이션 일괄 처리에 대한 진단 정보도 표시할 수 있습니다. 
    
## <a name="feature-availability"></a>기능 가용성

Office 365 계획, 독립 실행형 옵션 및 온-프레미스 솔루션별로 기능 가용성을 확인하려면 [Exchange Online 서비스 설명](exchange-online-service-description.md)을 참조하세요.
  

