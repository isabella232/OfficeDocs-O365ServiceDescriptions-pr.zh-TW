---
title: Office 365 進階威脅防護服務說明
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 02/08/2019
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Office 365 進階威脅防護 (ATP) 是一種雲端架構電子郵件篩選服務，提供強大的零時差保護，同時也擁有即時保護組織防止有害連結的功能，可協助保護您的組織抵禦不明惡意軟體和病毒。ATP 具有豐富報告和 URL 追蹤功能，可讓系統管理員深入了解組織中發生的攻擊的類型。
ms.openlocfilehash: aeddc27c0275cb21ec257878e0978961356e7a85
ms.sourcegitcommit: 30a452b9b9a0d8fc288e5911235454cc8f1907be
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 02/11/2019
ms.locfileid: "29884194"
---
# <a name="office-365-advanced-threat-protection-service-description"></a>Office 365 進階威脅防護服務說明

Microsoft Office 365 進階威脅防護 (ATP) 是一種雲端架構電子郵件篩選服務，提供強大的零時差保護，同時也擁有即時保護組織防止有害連結的功能，可協助保護您的組織抵禦不明惡意軟體和病毒。ATP 具有豐富報告和 URL 追蹤功能，可讓系統管理員深入了解組織中發生的攻擊的類型。
  
您可以使用 ATP 的郵件保護的主要方法如下：
  
- 在 Office 365 ATP 僅篩選案例 ATP 提供雲端式電子郵件保護內部部署 Exchange Server 環境或任何其他內部部署 SMTP 電子郵件解決方案。
    
- Office 365 ATP 可保護 Exchange Online 的雲端託管信箱。若要深入了解 Exchange Online，請參閱 [Exchange Online 服務說明](exchange-online-service-description/exchange-online-service-description.md)。
    
- 在混合部署中，當您混合使用內部部署及雲端信箱並使用 Exchange Online Protection 來進行輸入電子郵件篩選時，可將 ATP 設定為保護您的郵件環境與控制郵件路由。
    
## <a name="office-365-advanced-threat-protection-atp-availability"></a>Office 365 進階威脅防護 (ATP) 可用性

ATP 隨附於 Office 365 企業版 E5、 Office 365 教育版 A5、 及 Microsoft 365 Business。 
  
您可以將 ATP 新增至下列 Exchange 與 Office 365 訂閱計劃： 
  
- Exchange Online Plan 1
    
- Exchange Online Plan 2
    
- Exchange Online Kiosk
    
- Exchange Online Protection
    
- Office 365 商務基本版
    
- Office 365 商務進階版
    
- Office 365 企業版 E1
    
- Office 365 Enterprise E3
    
- Office 365 企業版 F1
    
- Office 365 A1
    
- Office 365 A3
    
若要購買 Office 365 進階威脅防護，請參閱 [Office 365 進階威脅防護](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content)。
  
若要跨方案比較功能，請參閱 [比較 Office 365 for Business 方案](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409)。
  
## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a>Office 365 進階威脅防護 (ATP) 的新增功能

開始在年 2 月 2019年和後續的幾個月內啟用、 威脅智慧功能會被新增至 ATP。此外，如果您的組織目前沒有 ATP，您必須考量，新的選項包括 ATP 計劃 1 和 ATP 計劃 2。如需詳細資訊，請參閱[Office 365 進階威脅保護計劃和價格](https://products.office.com/en-us/exchange/advance-threat-protection#pmg-allup-content)和[不同進階威脅保護 (ATP) 計劃中可用的功能](#feature-availability-across-advanced-threat-protection-atp-plans)。

ATP 中的新功能的相關資訊，請參閱[ATP 中的新功能](https://docs.microsoft.com/office365/securitycompliance/office-365-atp#new-features-are-continually-being-added-to-atp)。
  
## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a>Office 365 進階威脅防護 (ATP) 的需求

ATP 可搭配任何 SMTP 郵件傳輸代理程式使用，例如 Microsoft Exchange Server 2013。如需 ATP 所支援的作業系統、網頁瀏覽器和語言的資訊，請參閱 [Exchange Online Protection 中的 Exchange 系統管理中心](https://go.microsoft.com/fwlink/p/?LinkId=282381)中的＜支援的瀏覽器＞和＜支援語言＞小節。
  
## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a>各進階威脅防護 (ATP) 計劃中可用的功能

每項功能如下所列。提到 Exchange Online 時，通常是指 Office 365 企業版服務系列。
  
|**功能**|**ATP 計劃 1**<br>（前身為 ATP 獨立版）|**ATP 計劃 2**<br>（前身為威脅智慧 <br>獨立版） | Office 365 企業版 E5| 
|:-----|:-----|:-----|:-----|
| *設定、 保護及偵測* | 
|安全附件 |是|有 |可以|
|安全連結 |是|有 |可以 | 
|反網路釣魚原則 |是 |有 |可以 |
|SharePoint、 OneDrive 及 Microsoft 小組 ATP |是 |有 |可以|
|小組中的安全連結 |是|有 |可以 |
|即時報告 |是 |有 |可以|
|*自動化、 調查、 修復及教育* |
|威脅追蹤者 |否 |是 |可以 |
|Explorer （進階威脅調查） |否 |是 |可以 |
|將正在調查自動化及回應  |否 |是 |可以 |
|攻擊模擬器 |否 |是 |可以 |

   
## <a name="advanced-threat-protection-atp-capabilities"></a>進階威脅防護 (ATP) 功能

### <a name="safe-attachments"></a>安全附件

[ATP 安全附件](https://docs.microsoft.com/office365/securitycompliance/atp-safe-attachments)提供保護，避免未知的惡意程式碼及病毒，並提供零時差保護功能可保護您的訊息系統。所有的訊息與附件沒有已知的病毒/惡意程式碼簽章會路由傳送給其中 ATP 會使用各種機器學習與分析的技術來偵測惡意的特殊環境。如果偵測不到任何可疑的活動時，郵件已傳遞至信箱的發行。 

### <a name="safe-links"></a>安全連結

[ATP 安全連結](https://docs.microsoft.com/Office365/SecurityCompliance/atp-safe-links)功能主動會從一則訊息或 Office 文件中的惡意 Url 保護您的使用者。保護仍會保留每次他們按一下連結，如時可以存取良好的連結以動態方式會封鎖惡意的連結。

### <a name="anti-phishing-policies"></a>反網路釣魚原則

[ATP 反網路釣魚](https://docs.microsoft.com/office365/securitycompliance/atp-anti-phishing)會檢查內送郵件訊息可能是網路釣魚嘗試的指標。涵蓋使用者的內送郵件評估的多部機器學習分析訊息的模型 ATP 原則 （安全附件、 安全的連結或反網路釣魚），並採取適當的動作，根據設定的原則。
  
### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>適用於 SharePoint、OneDrive 及 Microsoft Teams 的 ATP

[SharePoint、 OneDrive 及 Microsoft 小組 ATP](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams)協助偵測和封鎖識別為惡意小組網站和文件庫中的檔案。

### <a name="real-time-reports"></a>即時報告

監視功能可在 Office 365 安全性 & 規範中心包括[提供及即時報告](https://docs.microsoft.com/office365/securitycompliance/view-reports-for-atp)可讓您以專注於高優先順序的問題，例如安全性攻擊的安全性和規範系統管理員或增加可疑的活動。除了反白顯示問題區域、 智慧報表及前瞻包括建議及檢視及探索資料及也採取快速連結。 
  
### <a name="threat-trackers"></a>威脅追蹤者

[威脅追蹤者](https://docs.microsoft.com/office365/securitycompliance/threat-trackers)為資訊性 widget 及授權的使用者提供 cybersecurity 問題可能會影響您的組織上的智慧的檢視。

### <a name="explorer"></a>瀏覽器

[瀏覽器](https://docs.microsoft.com/office365/securitycompliance/use-explorer-in-security-and-compliance)（也稱為威脅 Explorer） 是即時報告可讓授權的使用者來識別和分析最近的威脅。根據預設，這份報告顯示資料的過去 7 天;不過，可以修改檢視顯示過去 30 天的資料。 

### <a name="attack-simulator"></a>攻擊模擬器
  
[攻擊模擬器](https://docs.microsoft.com/office365/SecurityCompliance/attack-simulator)可讓組織中執行真實感化的攻擊案例的授權的使用者。數個不同的攻擊可用，包括顯示名稱矛網路釣魚攻擊、 密碼噴灑攻擊，與暴力密碼攻擊。