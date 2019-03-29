---
title: Office 365 進階威脅防護服務說明
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 03/28/2019
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Office 365 進階威脅防護 (ATP) 是雲端式電子郵件篩選服務，可協助提供穩定的零時差保護來保護您的組織抵禦不明的惡意程式碼和病毒，並包含的功能，以保護您組織從即時有害的連結。 ATP 具有豐富報告和 URL 追蹤功能，可讓系統管理員深入了解組織中發生的攻擊的類型。
ms.openlocfilehash: e07691851cdad9bce3f2989e2e6f1665569ec2b5
ms.sourcegitcommit: de7d615d8967b1acc98a077337a0a2939c782481
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 03/29/2019
ms.locfileid: "30955752"
---
# <a name="office-365-advanced-threat-protection-service-description"></a>Office 365 進階威脅防護服務說明

Microsoft Office 365 進階威脅防護 (ATP) 是雲端式電子郵件篩選服務，可協助提供穩定的零時差保護來保護您的組織抵禦不明的惡意程式碼和病毒，並包含的功能，以保護您組織從即時有害的連結。 ATP 具有豐富報告和 URL 追蹤功能，可讓系統管理員深入了解組織中發生的攻擊的類型。
  
您可以使用 ATP 的郵件保護的主要方式如下：
  
- 在 Office 365 ATP 僅篩選案例中，ATP 會提供雲端式電子郵件保護您的內部部署 Exchange Server 環境或任何其他內部部署 SMTP 電子郵件解決方案。
    
- Office 365 ATP 可保護 Exchange Online 的雲端託管信箱。若要深入了解 Exchange Online，請參閱 [Exchange Online 服務說明](exchange-online-service-description/exchange-online-service-description.md)。
    
- 在混合部署中，當您混合使用內部部署及雲端信箱並使用 Exchange Online Protection 來進行輸入電子郵件篩選時，可將 ATP 設定為保護您的郵件環境與控制郵件路由。
    
## <a name="office-365-advanced-threat-protection-atp-availability"></a>Office 365 進階威脅防護 (ATP) 可用性

ATP 隨附於 Office 365 企業版 E5，Office 365 教育版 A5，Microsoft 365 商務版。 
  
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

我們將會繼續將新功能新增至 Office 365 ATP。 以下是幾項新功能，其中有些呼叫 ATP 原則，以供檢閱及更新的清單。 若要深入了解即將 ATP （或在一般的 Microsoft 365） 的新功能，請造訪[Microsoft 365 藍圖](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)。

|功能更新  |動作項目  |
|---------|---------|
|[Office 365 威脅情報](https://docs.microsoft.com/office365/securitycompliance/office-365-ti)(TI) 功能現在是威脅調查及回應能力 ATP 計劃 2 的一部分。 新功能，例如[自動化的調查及回應](https://docs.microsoft.com/office365/securitycompliance/automated-investigation-response-office)，和[威脅總管](https://docs.microsoft.com/office365/securitycompliance/use-explorer-in-security-and-compliance)] 中，增強功能已推出。<br/>如果您的組織目前不具有 ATP，或如果您有 ATP，但不是 TI，您現在可以有數個選項，需要考慮使用 ATP 計劃 1 和 ATP 計劃 2 的可用性。 若要深入了解，請參閱[進階威脅防護 (ATP) 計劃的功能可用性](#feature-availability-across-advanced-threat-protection-atp-plans)（本文） and [Office 365 進階威脅防護方案和價格](https://products.office.com/exchange/advance-threat-protection)。 |檢閱您的組織訂閱，並如有需要[購買或編輯附加元件](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/buy-or-edit-an-add-on)。  |
|當人員使用 Outlook 或 Outlook Web 應用程式 (OWA)、 [ATP 安全連結](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links)轉譯原始 Url 時，不會進行修正 Url。 （我們稱此原生連結轉譯）。<br>原生連結轉譯適用於您的組織時，這項功能正常 Outlook 365 （按一下 [-隨選即用），OWA，且在 Windows 和 Mac 作業系統。 |無         |
|[Office 365 ATP 警告頁面](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links-warning-pages)功能的新的色彩配置、 詳細資訊，以及能夠繼續而不管網站指定警告和建議。 |無         |
|[ATP 安全連結](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links)保護會延伸至適用於 Office Online （線上 Word、 Excel Online、 PowerPoint Online，以及 OneNote Online） 和 Office 365 專業增強版在 mac 上的 Url   |[檢閱並編輯您的 ATP 安全連結原則](https://docs.microsoft.com/office365/SecurityCompliance/set-up-atp-safe-links-policies)  |
|隔離中的安全性功能&amp;合規性中心會擴充至[的 SharePoint Online、 商務用 OneDrive 和 Microsoft Teams 的 ATP](https://docs.microsoft.com/office365/SecurityCompliance/atp-for-spo-odb-and-teams)。 |[檢閱並編輯您的 ATP 安全附件原則](https://docs.microsoft.com/office365/SecurityCompliance/set-up-atp-safe-attachments-policies) |
|[ATP 安全連結](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links)保護會延伸至套用到組織內人員之間傳送的電子郵件。 |[檢閱並編輯您的 ATP 安全連結原則](https://docs.microsoft.com/office365/SecurityCompliance/set-up-atp-safe-links-policies) |
|[ATP 安全連結](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links)保護會延伸至套用至 Url 中的電子郵件，以及您在 Url 中 Office 365 專業增強版的文件，例如 Word、 Excel、 PowerPoint 及 Visio 在 Windows 中，為 Office iOS 和 Android 裝置上的應用程式。  |請確定您使用[Office 的新式驗證](https://docs.microsoft.com/office365/enterprise/modern-auth-for-office-2013-and-2016) |

  
## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a>Office 365 進階威脅防護 (ATP) 的需求

ATP 可搭配任何 SMTP 郵件傳輸代理程式，例如 Microsoft Exchange Server。 如需 ATP 所支援的作業系統、網頁瀏覽器和語言的資訊，請參閱 [Exchange Online Protection 中的 Exchange 系統管理中心](https://go.microsoft.com/fwlink/p/?LinkId=282381)中的＜支援的瀏覽器＞和＜支援語言＞小節。
  
## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a>各進階威脅防護 (ATP) 計劃中可用的功能

每項功能如下所列。提到 Exchange Online 時，通常是指 Office 365 企業版服務系列。
  
|**功能**|**ATP 計劃 1**<br>（先前稱為 ATP 獨立版）|**ATP 計劃 2**<br>（先前稱為威脅情報 <br>獨立版） | Office 365 企業版 E5| 
|:-----|:-----|:-----|:-----|
| *設定、 保護及偵測* | 
|安全附件 |是|是 |是|
|安全連結 |是|是 |是 | 
|反網路釣魚原則 |是 |是 |是 |
|SharePoint、 OneDrive 及 Microsoft Teams 的 ATP |是 |是 |是|
|Teams 中的安全連結 |是|是 |是 |
|即時報告 |是 |是 |是|
|*自動化、 調查、 修復和教育版* |
|威脅追蹤工具 |否 |是 |是 |
|檔案總管] （進階威脅調查） |否 |是 |是 |
|自動調查及回應  |否 |是 |是 |
|攻擊模擬器 |否 |是 |是 |

   
## <a name="advanced-threat-protection-atp-capabilities"></a>進階威脅防護 (ATP) 功能

### <a name="safe-attachments"></a>安全附件

[ATP 安全附件](https://docs.microsoft.com/office365/securitycompliance/atp-safe-attachments)抵禦不明的惡意程式碼和病毒，並提供零時差保護來保護郵件系統。 所有沒有已知病毒/惡意軟體簽章的訊息與附件將被路由傳送至特殊的環境，其中 ATP 會使用不同的機器學習與分析技術來偵測惡意的意圖。 如果未偵測到可疑活動，即會釋出訊息傳遞到信箱。 

### <a name="safe-links"></a>安全連結

[ATP 安全連結](https://docs.microsoft.com/Office365/SecurityCompliance/atp-safe-links)功能主動保護您的使用者從郵件中或在 Office 文件中的惡意 Url。 因為可動態封鎖惡意連結，允許存取無害連結，所以每次使用者按一下連結時都能受到持續保護。

### <a name="anti-phishing-policies"></a>反網路釣魚原則

[ATP 防網路釣魚](https://docs.microsoft.com/office365/securitycompliance/atp-anti-phishing)檢查內送郵件的郵件可能是網路釣魚嘗試的指標。 當使用者將會涵蓋 ATP 原則 （安全附件、 安全連結或反網路釣魚），內送郵件會由多部機器學習模型來分析郵件和評估採取適當的動作，根據設定的原則。
  
### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>適用於 SharePoint、OneDrive 及 Microsoft Teams 的 ATP

[適用於 SharePoint、 OneDrive 及 Microsoft Teams ATP](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams)可協助偵測並封鎖會被識別為惡意小組網站和文件庫中的檔案。

### <a name="real-time-reports"></a>即時報告

監控 Office 365 安全性中的可用功能 & 合規性中心包含[即時報表和深入解析](https://docs.microsoft.com/office365/securitycompliance/view-reports-for-atp)，可讓您專注於高優先順序的問題，例如安全性攻擊的安全性與合規性系統管理員或增加可疑活動。 除了醒目提示的問題領域，智慧型報表和深入解析包括建議以及檢視和瀏覽資料和也需要快速動作的連結。 
  
### <a name="threat-trackers"></a>威脅追蹤工具

[威脅追蹤器](https://docs.microsoft.com/office365/securitycompliance/threat-trackers)是指 widget 和授權的使用者提供智慧 cybersecurity 問題可能會影響您的組織上的檢視。

### <a name="explorer"></a>檔案總管

[檔案總管](https://docs.microsoft.com/office365/securitycompliance/use-explorer-in-security-and-compliance)（也稱為威脅總管） 是即時報告可讓授權的使用者來識別和分析最近的潛在威脅。 根據預設，此報告會顯示資料過去 7 天內;不過，您可以修改檢視顯示過去 30 天的資料。 

### <a name="attack-simulator"></a>攻擊模擬器
  
[攻擊模擬器](https://docs.microsoft.com/office365/SecurityCompliance/attack-simulator)可讓經過授權的使用者，在您的組織中執行真實的攻擊案例。 數個不同的幾種類型的攻擊可供使用，包括顯示名稱矛網路釣魚攻擊、 密碼噴灑攻擊，與暴力密碼攻擊。