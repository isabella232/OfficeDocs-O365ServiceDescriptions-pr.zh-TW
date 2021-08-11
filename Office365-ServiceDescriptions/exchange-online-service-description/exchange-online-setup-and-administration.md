---
title: Exchange Online 設定與管理
ms.author: office365servicedesc
author: pamelaar
manager: gailw
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
description: 本文說明可用於自訂 Exchange Online 設定，以及讓組織的 Exchange Online 環境保持在最新狀態及目前狀態的管理控制和支援。 其中包括以下相關資訊：可供組織使用的自助管理工具和功能；Microsoft 管理責任和效能承諾；以及服務和產品升級。
ms.openlocfilehash: 24edb5a4c1855acd990ddc427e218cb601dc45aab34a5f6a83cf76cb561dbffe
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 08/06/2021
ms.locfileid: "54663946"
---
# <a name="exchange-online-setup-and-administration"></a>Exchange Online 設定與管理

本文說明可用於自訂 Exchange Online 設定，以及讓組織的 Exchange Online 環境保持在最新狀態及目前狀態的管理控制和支援。 其中包括以下相關資訊：可供組織使用的自助管理工具和功能；Microsoft 管理責任和效能承諾；以及服務和產品升級。
  
## <a name="self-service-administration-tools"></a>自助系統管理工具

雖然 Microsoft 直接控制所有的 Exchange Online 資料中心，並負責整體系統效能，但它只會控制結合的部分元素，以提供使用者的整體經驗。 組織須自行負責與資料中心的網路連線、客戶的廣域網路 (WAN) 以及客戶的區域網路 (LAN)。 此外，他們也負責使用者裝置和其設定。他們也須負責維護每個使用者針對任何功能所需的授權，包括 (但不限於) 管理這些功能的能力，直到使用者不需存取該功能為止。
  
因此，Exchange Online 提供客戶系統管理員下列工具 (如下所述)，以管理各種訊息相關工作：
  
- [Microsoft Office 365 入口網站](exchange-online-setup-and-administration.md#microsoft-office-365-portal)
    
- [Microsoft 365 系統管理中心](#microsoft-365-admin-center)
    
- [Exchange 系統管理中心](exchange-online-setup-and-administration.md#exchange-admin-center)
    
- [Exchange Online 的遠端 Windows PowerShell](exchange-online-setup-and-administration.md#remote-windows-powershell-for-exchange-online)
    
### <a name="microsoft-office-365-portal"></a>Microsoft Office 365 入口網站

位於 [https://portal.office.com](https://portal.office.com) 的 Microsoft Office 365 入口網站，可供系統管理員與合作夥伴購買和管理 Office 365 服務，並讓使用者存取及使用 Office 365 共同作業工具。
  
### <a name="microsoft-365-admin-center"></a>Microsoft 365 系統管理中心

Microsoft 365 系統管理中心是一個網頁入口網站，每個公司的服務管理員都可以管理其所訂閱之每個 Microsoft 服務的使用者帳戶和設定。 在 Microsoft 365 系統管理中心內，管理員可以追蹤 Exchange 系統管理中心 (EAC) 的連結，以便在其中管理 Exchange Online 的專用設定。 如需使用 Microsoft 365 系統管理中心來開始及執行的詳細資訊，請參閱下列影片：[引入 Office 365 企業版](https://go.microsoft.com/fwlink/p/?LinkId=271806)。
  
### <a name="exchange-admin-center"></a>Exchange 系統管理中心

Exchange Online 提供單一整合的管理主控台，讓使用者更方便使用且最佳化內部部署、線上或混合部署的管理。Exchange 系統管理中心 (EAC) 是管理員管理 Exchange 專屬設定的地方。
  
如需有關如何使用 EAC 管理 Exchange Online 的詳細資訊，請參閱 [Exchange 系統管理中心](/exchange/exchange-admin-center)。
  
### <a name="remote-windows-powershell-for-exchange-online"></a>Exchange Online 的遠端 Windows PowerShell

管理員可以使用遠端 Windows PowerShell 連線至 Exchange Online，以執行使用 EAC 無法提供或無法實際執行的管理工作。這些包括能夠自動執行重複性工作、擷取用於自訂報告的資料、自訂原則，以及連線 Exchange Online 至現有基礎結構和程序。如需詳細資訊，請參閱[使用遠端 PowerShell 連線到 Exchange Online](/powershell/exchange/connect-to-exchange-online-powershell)。
  
Exchange Online 使用的 Windows PowerShell cmdlet 與 Exchange Server 2013 相同，但某些命令和參數無法使用，因為在 Exchange Online 中這些功能並不適用。如需可與 Exchange Online 搭配使用的 Cmdlet 清單，請參閱 [Exchange Online Cmdlet](/powershell/exchange/exchange-online-powershell)。
  
系統管理員無須安裝任何 Exchange Server 管理或移轉工具，即可使用遠端 Windows PowerShell。不過，系統管理員的電腦必須執行 Windows Management Framework 3.0 (其包含 Windows PowerShell v3 和 WinRM 3.0) 以及 Windows .NET Framework 4.5。執行 Windows 8 或 Windows Server 2012 的電腦上已安裝有這些元件。系統管理員可針對執行 Windows 7 或 Windows Server 2008 R2 的電腦，手動下載這些元件。
  
> [!IMPORTANT]
> 為防止拒絕服務 (DoS) 攻擊，您最多只能對您的 Exchange Online 組織建立三個 Windows PowerShell 連線。 
  
## <a name="self-service-capabilities-for-exchange-online"></a>Exchange Online 自助功能

以下是使用 EAC、遠端 Windows PowerShell 及其他工具管理 Exchange Online 時可用的重要功能。您也可以使用這些工具來控制其他許多設定，如本文所述。
  
### <a name="mobile-device-security-policies-for-exchange-online"></a>Exchange Online 的行動裝置安全性原則

Exchange Online 針對行動裝置所支援的 ActiveSync 原則與 Exchange Server 2013 相同。管理員可以使用 EAC 或遠端 Windows PowerShell，為特定使用者和群組強制執行及自訂這些安全性原則。
  
### <a name="message-tracking-for-exchange-online"></a>Exchange Online 的郵件追蹤

透過「傳遞回報」功能進行的郵件追蹤會在下列主題中說明： [報告功能和疑難排解工具](reporting-features-and-troubleshooting-tools.md)。
  
### <a name="usage-reporting-for-exchange-online"></a>Exchange Online 的使用報告

系統管理員可以使用遠端 Windows PowerShell 擷取組織中人員的 Exchange Online 服務使用情況相關資訊。可用的資訊包含：
  
- 顯示組織中每個使用者的信箱大小。
    
- 顯示信箱上已設定的自訂權限，例如委派存取。
    
- 擷取有關行動裝置存取的資料，例如，哪些使用者透過 Exchange ActiveSync 進行連線、使用哪些裝置，以及最後一次的連線時間。
    
開頭為「get-」的遠端 Windows PowerShell Cmdlet 可以從 Exchange Online 系統擷取資料。系統管理員可以透過 Windows PowerShell 以 .csv 格式匯出此資訊，以進行進階分析或報告。
  
如需有關可與 Exchange Online 搭配使用的 Windows PowerShell Cmdlet 的詳細資訊，請參閱 [Exchange Online Cmdlet](/powershell/exchange/exchange-online-powershell)。
  
### <a name="auditing-for-exchange-online"></a>Exchange Online 的稽核

下列主題說明「審核記錄」功能： [報告功能和疑難排解工具](reporting-features-and-troubleshooting-tools.md)。
  
## <a name="service-and-product-upgrades-for-exchange-online"></a>Exchange Online 的服務和產品升級

Exchange Online 客戶享有定期升級至最新 Exchange 技術的權益，包括新版本的 Exchange Server。這些升級會免費提供，可確保客戶始終使用最新的 Exchange 軟體。
  
在 Microsoft 發行 Exchange 的主要版本後，客戶必須在 12 個月內，將服務升級為新版本。
  
## <a name="feature-availability"></a>功能可用性

若要查看不同方案、獨立選項和內部部署方案中的功能可用性，請參閱[Exchange Online 服務描述](exchange-online-service-description.md)。
