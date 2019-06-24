---
title: Office 365 進階威脅防護服務說明
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 04/04/2019
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Office 365 Advanced 威脅防護 (ATP) 是雲端式的電子郵件篩選服務, 可協助您的組織抵禦未知的惡意程式碼和病毒, 方法是提供可靠的零天保護, 並包含保護您組織從有害連結即時。 ATP 具有豐富報告和 URL 追蹤功能，可讓系統管理員深入了解組織中發生的攻擊的類型。
ms.openlocfilehash: 952dfc120f41bf9cce9ad88c33fc883d165eb8b5
ms.sourcegitcommit: 0f5ad374ff3559c10a1665d894d68665dbd1214b
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 06/21/2019
ms.locfileid: "35130987"
---
# <a name="office-365-advanced-threat-protection-service-description"></a>Office 365 進階威脅防護服務說明

Microsoft Office 365 Advanced 威脅防護 (ATP) 是雲端式的電子郵件篩選服務, 可協助您的組織抵禦未知的惡意程式碼和病毒, 方法是提供可靠的零天保護, 並包含保護您組織從有害連結即時。 ATP 具有豐富報告和 URL 追蹤功能，可讓系統管理員深入了解組織中發生的攻擊的類型。
  
以下是您可以使用 ATP 來進行郵件保護的主要方式:
  
- 在 Office 365 ATP 僅篩選案例中, ATP 會為您的內部部署 Exchange Server 環境或任何其他內部部署 SMTP 電子郵件解決方案, 提供雲端式電子郵件保護。
    
- Office 365 ATP 可保護 Exchange Online 的雲端託管信箱。若要深入了解 Exchange Online，請參閱 [Exchange Online 服務說明](exchange-online-service-description/exchange-online-service-description.md)。
    
- 在混合部署中，當您混合使用內部部署及雲端信箱並使用 Exchange Online Protection 來進行輸入電子郵件篩選時，可將 ATP 設定為保護您的郵件環境與控制郵件路由。
    
## <a name="office-365-advanced-threat-protection-atp-availability"></a>Office 365 進階威脅防護 (ATP) 可用性

ATP 隨附于 Office 365 企業版 E5、Office 365 教育版 A5 和 Microsoft 365 商務。 
  
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
  
若要比較各方案的功能, 請參閱[比較 Office 365 For Business 方案](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409)和[探索適合您的 Microsoft 365 企業版解決方案](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans)。
  
## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a>Office 365 進階威脅防護 (ATP) 的新增功能

我們繼續將新功能新增至 Office 365 ATP。 以下是幾個新功能的清單, 其中一些是用來檢查和更新 ATP 原則的。 若要深入瞭解 ATP 的新功能 (或一般的 Microsoft 365), 請造訪[microsoft 365 藍圖](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)。

|功能更新  |動作專案  |
|---------|---------|
|[Office 365 威脅情報](https://docs.microsoft.com/office365/securitycompliance/office-365-ti)(TI) 功能現在是作為 ATP 方案2一部分的威脅調查和回應功能。 新功能 (例如[自動調查和回應](https://docs.microsoft.com/office365/securitycompliance/automated-investigation-response-office)), 以及[威脅瀏覽器](https://docs.microsoft.com/office365/securitycompliance/use-explorer-in-security-and-compliance)的增強功能都會推出。<br/><br/>如果您的組織目前沒有 ATP, 或您有 ATP (而非 TI), 您現在有數個選項可供考慮, 其可用性是 ATP 計畫1和 ATP 方案2。 若要深入瞭解, 請參閱[各種高級威脅防護 (ATP) 計畫中的功能可用性](#feature-availability-across-advanced-threat-protection-atp-plans)(本文) 和[Office 365 高級威脅防護方案和價格](https://products.office.com/exchange/advance-threat-protection)。 |請參閱貴組織的訂閱, 如有需要, 請[購買或編輯附加](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/buy-or-edit-an-add-on)元件。  |
|當使用者使用 Outlook 或 Outlook Web 應用程式 (OWA) 時, [ATP 安全連結](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links)會轉譯原始 url, 而不是重新寫入的 url。 (我們稱之為本機連結轉譯)。<br>當您的組織可以使用原生連結轉譯時, 這項功能會在 Outlook 365 (隨選即用)、OWA, 以及 Windows 和 Mac 作業系統上運作。 |無         |
|[Office 365 ATP 警告頁面](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links-warning-pages)功能新的色彩配置、更多詳細資料, 以及繼續前往網站的功能, 而不管警告和建議。 |無         |
|[ATP 安全連結](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links)保護會延伸以套用至 Office for Web 的 Url (Word for Web、Excel for Web、PowerPoint for Web 和 OneNote for web) 和 Mac 上的 Office 365 專業增強版)。   |[檢查並編輯您的 ATP 安全連結原則](https://docs.microsoft.com/office365/SecurityCompliance/set-up-atp-safe-links-policies)  |
|安全性&amp;合規性中心內的隔離功能會延伸至[SharePoint Online、商務用 OneDrive 和 Microsoft 團隊的 ATP](https://docs.microsoft.com/office365/SecurityCompliance/atp-for-spo-odb-and-teams)。 |[檢查並編輯您的 ATP 安全附件原則](https://docs.microsoft.com/office365/SecurityCompliance/set-up-atp-safe-attachments-policies) |
|[ATP 安全連結](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links)保護會延伸, 以套用至組織內的人員所寄送的電子郵件。 |[檢查並編輯您的 ATP 安全連結原則](https://docs.microsoft.com/office365/SecurityCompliance/set-up-atp-safe-links-policies) |
|[ATP 安全連結](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links)保護會延伸以套用至電子郵件中的 url, 以及 Office 365 專業增強版檔中的 url, 例如 Word、Excel、PowerPoint 和 Visio on Windows, 以及 IOS 和 Android 裝置上的 office 應用程式。  |確定您使用的是[新式的 Office 驗證](https://docs.microsoft.com/office365/enterprise/modern-auth-for-office-2013-and-2016) |

  
## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a>Office 365 進階威脅防護 (ATP) 的需求

ATP 可搭配任何 SMTP 郵件傳輸代理程式使用, 例如 Microsoft Exchange Server。 如需 ATP 所支援的作業系統、網頁瀏覽器和語言的資訊，請參閱 [Exchange Online Protection 中的 Exchange 系統管理中心](https://go.microsoft.com/fwlink/p/?LinkId=282381)中的＜支援的瀏覽器＞和＜支援語言＞小節。
  
## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a>各進階威脅防護 (ATP) 計劃中可用的功能

每項功能如下所列。提到 Exchange Online 時，通常是指 Office 365 企業版服務系列。
  
|**功能**|**ATP 計畫1**<br>(先前的 ATP 獨立)|**ATP 方案2**<br>(先前稱為威脅情報 <br>版 | Office 365 企業版 E5| 
|:-----|:-----|:-----|:-----|
| *設定、保護和偵測* | 
|安全附件 |是|是 |是|
|安全連結 |是|是 |是 | 
|反網路釣魚原則 |是 |是 |是 |
|適用于 SharePoint、OneDrive 及 Microsoft 小組的 ATP |是 |是 |是|
|小組中的安全連結 |是|是 |是 |
|即時報告 |是 |是 |是|
|*自動化、調查、修復和教育* |
|威脅追蹤工具 |否 |是 |是 |
|Explorer (高級威脅調查) |否 |是 |是 |
|自動調查及回應  |否 |是 |是 |
|攻擊模擬器 |否 |是 |是 |

   
## <a name="advanced-threat-protection-atp-capabilities"></a>進階威脅防護 (ATP) 功能

### <a name="safe-attachments"></a>安全附件

[ATP 安全附件](https://docs.microsoft.com/office365/securitycompliance/atp-safe-attachments)可防止不明的惡意程式碼和病毒, 並提供可保護郵件系統的零天防護功能。 所有沒有已知病毒/惡意軟體簽章的訊息與附件將被路由傳送至特殊的環境，其中 ATP 會使用不同的機器學習與分析技術來偵測惡意的意圖。 如果未偵測到可疑活動，即會釋出訊息傳遞到信箱。 

> [!NOTE]
> ATP 安全附件掃描會在您的 Office 365 資料所在的同一個區域中進行。 如需資料中心地理位置的詳細資訊, 請參閱[您的資料位於何處？](https://products.office.com/where-is-your-data-located?geo=All) 

### <a name="safe-links"></a>安全連結

[ATP 安全連結](https://docs.microsoft.com/Office365/SecurityCompliance/atp-safe-links)功能主動保護您的使用者, 免受郵件或 Office 檔中的惡意 url 的攻擊。 因為可動態封鎖惡意連結，允許存取無害連結，所以每次使用者按一下連結時都能受到持續保護。

### <a name="anti-phishing-policies"></a>反網路釣魚原則

[ATP 反網路釣魚](https://docs.microsoft.com/office365/securitycompliance/atp-anti-phishing)會檢查內送郵件, 以找出郵件可能是網路釣魚企圖的指示。 當使用者被 ATP 原則 (安全附件、安全連結或反網路釣魚) 所涵蓋時, 會根據所設定的原則, 由多部機器學習模型來評估內送郵件, 並採取適當的動作。
  
### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>適用於 SharePoint、OneDrive 及 Microsoft Teams 的 ATP

[ATP For SharePoint、OneDrive 及 Microsoft 團隊](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams)可協助偵測並封鎖在小組網站和文件庫中識別為惡意的檔案。

### <a name="real-time-reports"></a>即時報告

Office 365 安全性 & 合規性中心提供的監視功能包含[即時報告和洞察力](https://docs.microsoft.com/office365/securitycompliance/view-reports-for-atp), 讓您的安全性和合規性系統管理員能夠將重點放在高優先順序問題上, 例如安全性攻擊或增加可疑的活動。 除了醒目提示問題領域之外, 智慧報表和深入資訊還包含建議和連結, 以查看及探索資料, 也會快速採取動作。 
  
### <a name="threat-trackers"></a>威脅追蹤工具

[威脅](https://docs.microsoft.com/office365/securitycompliance/threat-trackers)追蹤器是資訊性的小元件和視圖, 可在可能影響您組織的 cybersecurity 問題上, 為授權的使用者提供智慧。

### <a name="explorer"></a>Explorer

[Explorer](https://docs.microsoft.com/office365/securitycompliance/use-explorer-in-security-and-compliance)(也稱為威脅瀏覽器) 是一種即時報告, 可讓授權的使用者找出並分析最近的威脅。 根據預設, 此報告會顯示過去7天的資料;不過, 您可以修改視圖, 以顯示過去30天的資料。 

### <a name="attack-simulator"></a>攻擊模擬器
  
[攻擊模擬器](https://docs.microsoft.com/office365/SecurityCompliance/attack-simulator)可讓授權的使用者在您的組織中執行實際的攻擊案例。 有幾種不同類型的攻擊可供使用, 包括顯示名稱 spear 網路釣魚攻擊、密碼噴塗攻擊, 以及強力密碼攻擊。