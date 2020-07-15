---
title: Exchange Online 設定與管理
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-administration-and-management
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 80c07748-ac57-4b90-97dd-a2d1115009a6
description: 本文說明可自訂 Exchange Online 設定並保持組織的 Exchange Online 環境為已啟動、執行及目前狀態的管理控制和支援。 其中包括以下相關資訊：可供組織使用的自助管理工具和功能；Microsoft 管理責任和效能承諾；以及服務和產品升級。
ms.openlocfilehash: 19ec50b3f502ee111de05e1a115d17f16fec3569
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132998"
---
# <a name="exchange-online-setup-and-administration"></a>Exchange Online 設定與管理

本文說明可自訂 Exchange Online 設定並保持組織的 Exchange Online 環境為已啟動、執行及目前狀態的管理控制和支援。 其中包括以下相關資訊：可供組織使用的自助管理工具和功能；Microsoft 管理責任和效能承諾；以及服務和產品升級。
  
## <a name="self-service-administration-tools"></a>自助系統管理工具

雖然 Microsoft 直接控制所有 Exchange Online 資料中心，並負責整體系統效能，但它只會控制結合的部分元素，以提供使用者的整體經驗。 組織須自行負責與資料中心的網路連線、客戶的廣域網路 (WAN) 以及客戶的區域網路 (LAN)。 此外，他們也負責使用者裝置和其設定。他們也須負責維護每個使用者針對任何功能所需的授權，包括 (但不限於) 管理這些功能的能力，直到使用者不需存取該功能為止。
  
因此，Exchange Online 提供客戶系統管理員下列工具 (如下所述)，以管理各種訊息相關工作：
  
- [Microsoft Office 365 入口網站](exchange-online-setup-and-administration.md#microsoft-office-365-portal)
    
- [Microsoft 365 系統管理中心](#microsoft-365-admin-center)
    
- [Exchange 系統管理中心](exchange-online-setup-and-administration.md#exchange-admin-center)
    
- [Exchange Online 的遠端 Windows PowerShell](exchange-online-setup-and-administration.md#remote-windows-powershell-for-exchange-online)
    
### <a name="microsoft-office-365-portal"></a>Microsoft Office 365 入口網站

位於 [https://portal.office.com](https://portal.office.com) 的 Microsoft Office 365 入口網站，可供系統管理員與合作夥伴購買和管理 Office 365 服務，並讓使用者存取及使用 Office 365 共同作業工具。
  
### <a name="microsoft-365-admin-center"></a>Microsoft 365 系統管理中心

Microsoft 365 系統管理中心是一個網頁入口網站，每個公司的服務管理員可以從該入口網站管理每個訂閱的 Microsoft 服務的使用者帳戶和設定。 在 Microsoft 365 系統管理中心內，管理員可以追蹤 Exchange 系統管理中心（EAC）的連結，以便在其中管理 Exchange Online 特有的設定。 如需使用 Microsoft 365 系統管理中心開始及執行的詳細資訊，請參閱下列影片： [Office 365 Enterprise 簡介](https://go.microsoft.com/fwlink/p/?LinkId=271806)。
  
### <a name="exchange-admin-center"></a>Exchange 系統管理中心

Exchange Online provides a single unified management console that allows for ease of use and is optimized for management of on-premises, online, or hybrid deployments. The Exchange admin center (EAC) is where administrators can manage Exchange-specific settings.
  
如需有關如何使用 EAC 管理 Exchange Online 的詳細資訊，請參閱 [Exchange 系統管理中心](https://go.microsoft.com/fwlink/p/?LinkId=271807)。
  
### <a name="remote-windows-powershell-for-exchange-online"></a>Exchange Online 的遠端 Windows PowerShell

Using remote Windows PowerShell, administrators can connect to Exchange Online to perform management tasks that are not available or practical using the EAC. These include the ability to automate repetitive tasks, extract data for custom reports, customize policies, and connect Exchange Online to existing infrastructure and processes. For more information, see [Connect to Exchange Online Using Remote PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=308994).
  
Exchange Online uses the same Windows PowerShell cmdlets as Exchange Server 2013, with certain commands and parameters unavailable because these features do not apply in Exchange Online. For a list of cmdlets for use with Exchange Online, see [Exchange Online cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).
  
Administrators do not need to install any Exchange Server management or migration tools to use remote Windows PowerShell. However, administrators' computers must be running the Windows Management Framework 3.0, which contains Windows PowerShell v3 and WinRM 3.0; and Windows .NET Framework 4.5. These components are already installed on computers running Windows 8 or Windows Server 2012. Administrators can manually download these components for computers that are running Windows 7 or Windows Server 2008 R2.
  
> [!IMPORTANT]
> 為防止拒絕服務 (DoS) 攻擊，您最多只能對您的 Exchange Online 組織建立三個 Windows PowerShell 連線。 
  
## <a name="self-service-capabilities-for-exchange-online"></a>Exchange Online 自助功能

Below are important capabilities that are available for managing Exchange Online by using the EAC, remote Windows PowerShell, and other tools. Many other settings can also be controlled with these tools, as described throughout this document.
  
### <a name="mobile-device-security-policies-for-exchange-online"></a>Exchange Online 的行動裝置安全性原則

Exchange Online supports the same ActiveSync policies for mobile devices as Exchange Server 2013. Administrators can enforce and customize these security policies for specific users and groups by using the EAC or remote Windows PowerShell.
  
### <a name="message-tracking-for-exchange-online"></a>Exchange Online 的郵件追蹤

透過「傳遞回報」功能進行的郵件追蹤會在下列主題中說明：[報告功能和疑難排解工具](reporting-features-and-troubleshooting-tools.md)。
  
### <a name="usage-reporting-for-exchange-online"></a>Exchange Online 的使用報告

Administrators can use remote Windows PowerShell to retrieve information about how people in their organizations use the Exchange Online service. Available information includes:
  
- 顯示組織中每個使用者的信箱大小。
    
- 顯示信箱上已設定的自訂權限，例如委派存取。
    
- 擷取有關行動裝置存取的資料，例如，哪些使用者透過 Exchange ActiveSync 進行連線、使用哪些裝置，以及最後一次的連線時間。
    
Remote Windows PowerShell cmdlets that start with "get-" can fetch data from the Exchange Online system. Administrators can export this information from Windows PowerShell in .csv format for advanced analysis or reporting.
  
如需有關可與 Exchange Online 搭配使用的 Windows PowerShell Cmdlet 的詳細資訊，請參閱 [Exchange Online Cmdlet](https://go.microsoft.com/fwlink/p/?LinkId=271808)。
  
### <a name="auditing-for-exchange-online"></a>Exchange Online 的稽核

下列主題說明「審核記錄」功能：[報告功能和疑難排解工具](reporting-features-and-troubleshooting-tools.md)。
  
## <a name="service-and-product-upgrades-for-exchange-online"></a>Exchange Online 的服務和產品升級

Exchange Online customers benefit from periodic upgrades to the latest Exchange technology, including new releases of Exchange Server. These upgrades are made available at no additional charge, and ensure that customers are always using the latest Exchange software.
  
在 Microsoft 發行 Exchange 的主要版本後，客戶必須在 12 個月內，將服務升級為新版本。
  
## <a name="feature-availability"></a>功能可用性

若要查看不同方案、獨立選項和內部部署方案中的功能可用性，請參閱[Exchange Online 服務說明](exchange-online-service-description.md)。
  