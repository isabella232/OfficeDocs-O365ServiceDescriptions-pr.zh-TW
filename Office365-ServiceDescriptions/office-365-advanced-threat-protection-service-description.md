---
title: Office 365 進階威脅防護服務說明
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Office 365 Advanced 威脅防護（ATP）是一種雲端式電子郵件篩選服務，可協助您的組織抵禦未知惡意程式碼和病毒，方法是提供強健的零日保護，並包含保護您的電腦的功能。組織會即時從有害連結。
ms.openlocfilehash: 5457cbe5304665f7cddc9cc068a167684cf77024
ms.sourcegitcommit: 83c602d9c498df5a2fe0095c6fb0a267c8a708b7
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 03/12/2020
ms.locfileid: "42609834"
---
# <a name="office-365-advanced-threat-protection-service-description"></a>Office 365 進階威脅防護服務說明

Microsoft Office 365 Advanced 威脅防護（ATP）是一種雲端式電子郵件篩選服務，可協助您的組織抵禦未知惡意程式碼和病毒，方法是提供強健的零日保護，並包含保護您的電腦的功能。組織會即時從有害連結。 ATP 具有豐富報告和 URL 追蹤功能，可讓系統管理員深入了解組織中發生的攻擊的類型。

以下是您可以使用 ATP 進行郵件保護的主要方式：

- 在 Office 365 ATP 僅篩選案例中，ATP 會為您的內部部署 Exchange 伺服器環境或任何其他內部部署 SMTP 電子郵件解決方案，提供雲端式電子郵件保護。

- Office 365 ATP 可保護 Exchange Online 的雲端託管信箱。 若要深入瞭解 Exchange Online，請參閱[Exchange online 服務說明](exchange-online-service-description/exchange-online-service-description.md)。

- 在混合部署中，當您混合使用內部部署及雲端信箱並使用 Exchange Online Protection 來進行輸入電子郵件篩選時，可將 ATP 設定為保護您的郵件環境與控制郵件路由。

## <a name="office-365-advanced-threat-protection-atp-availability"></a>Office 365 進階威脅防護 (ATP) 可用性

ATP 包含在 Office 365 企業版 E5、Office 365 教育版 A5 和 Microsoft 365 商務中。

您可以將 ATP 新增至下列 Exchange 與 Office 365 訂閱計劃：

- Exchange Online Plan 1

- Exchange Online Plan 2

- Exchange Online Kiosk

- Exchange Online Protection

- Office 365 商務基本版

- Office 365 商務進階版

- Office 365 Enterprise E1

- Office 365 Enterprise E3

- Office 365 Enterprise F3

- Office 365 A1

- Office 365 A3

若要購買 Office 365 進階威脅防護，請參閱 [Office 365 進階威脅防護](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content)。

若要跨方案比較功能，請參閱[比較 Office 365 For Business 方案](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409)，並[探索適合您的 Microsoft 365 企業版解決方案](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans)。

## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a>Office 365 進階威脅防護 (ATP) 的新增功能

我們正在繼續將新功能新增至 Office 365 ATP。 若要深入瞭解即將 ATP （或一般為 Microsoft 365）的新功能，請參閱下列資源：

- [Microsoft 365 藍圖](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Office 365 ATP 中的新功能](https://docs.microsoft.com/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a>Office 365 進階威脅防護 (ATP) 的需求

ATP 可搭配任何 SMTP 郵件傳輸代理程式使用，例如 Microsoft Exchange Server。 如需 ATP 所支援的作業系統、網頁瀏覽器和語言的資訊，請參閱 [Exchange Online Protection 中的 Exchange 系統管理中心](https://go.microsoft.com/fwlink/p/?LinkId=282381)中的＜支援的瀏覽器＞和＜支援語言＞小節。

## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a>各進階威脅防護 (ATP) 計劃中可用的功能

每項功能如下所列。提到 Exchange Online 時，通常是指 Office 365 企業版服務系列。

|**功能**|**ATP 方案1**<br>（先前是 ATP 獨立）|**ATP 方案2**<br>（以前稱為威脅情報 <br>單獨| Office 365 企業版 E5|
|:-----|:-----|:-----|:-----|
|*設定、保護及偵測*|
|[安全附件](#safe-attachments)|是|是|是|
|小組中的安全附件|是|是|是|
|[安全連結](#safe-links)|是|是|是|
|小組中的安全連結|否|否|否|
|[SharePoint、OneDrive 和 Microsoft 小組的 ATP](#atp-for-sharepoint-onedrive-and-microsoft-teams)|是|是|是|
|[反網路釣魚原則](#anti-phishing-policies)|是|是|是|
|[即時報告](#real-time-reports)|是|是|是|
|*自動化、調查、修正及教育*|
|[威脅追蹤工具](#threat-trackers)|否|是|是|
|[Explorer](#explorer) （高級威脅調查）|否|是|是|
|[自動化的事件回應](#automated-incident-response)|否|是|是|
|[攻擊模擬器](#attack-simulator)|否|是|是|

## <a name="advanced-threat-protection-atp-capabilities"></a>高級威脅防護（ATP）功能

### <a name="safe-attachments"></a>安全附件

[ATP 安全附件](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments)可防止未知的惡意程式碼和病毒，並提供零天的保護來保護您的郵件系統。 所有沒有已知病毒/惡意軟體簽章的訊息與附件將被路由傳送至特殊的環境，其中 ATP 會使用不同的機器學習與分析技術來偵測惡意的意圖。 如果未偵測到可疑活動，即會釋出訊息傳遞到信箱。

> [!NOTE]
> ATP 安全附件掃描會在您的 Office 365 資料所在的同一個區域中進行。 如需資料中心地理位置的詳細資訊，請參閱[您的資料位於何處？](https://products.office.com/where-is-your-data-located?geo=All)

### <a name="safe-links"></a>安全連結

[ATP 安全連結](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links)功能主動保護您的使用者免受郵件中或 Office 檔中的惡意 URLs。 保護會在每次選取連結時保留，因為在存取好的連結時，會動態封鎖惡意連結。

安全連結可用於下列應用程式中的 URLs：

- Windows 或 Mac 上的 Office 365 ProPlus

- Office for web （適用于網頁的 Word、網頁版、網頁 PowerPoint 和 OneNote 網頁）

- Windows 上的 Word、Excel、PowerPoint 和 Visio，以及 iOS 和 Android 裝置上的 Office 應用程式

> [!NOTE]
> 使用者必須是 ATP<sup>\*</sup>的授權，必須包含在 Atp 安全連結原則中，且必須在裝置上登入，以進行保護。
>
> <sup>\*</sup>若為全組織的 ATP 授權（例如，ATP_ENTERPRISE_FACULTY），您不需要將 ATP 授權指派給個別使用者。
>
> 如需有關 ATP 安全連結保護的詳細資訊，請參閱[Atp 安全連結如何與 Office 檔中的 URLs 搭配運作](https://docs.microsoft.com/microsoft-365/security/office-365-security/how-atp-safe-links-works#how-atp-safe-links-works-with-urls-in-office-documents)。

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>適用於 SharePoint、OneDrive 及 Microsoft Teams 的 ATP

[SharePoint、OneDrive 和 Microsoft 團隊的 ATP](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)可協助偵測和封鎖在小組網站和文件庫中識別為惡意的檔案。

### <a name="anti-phishing-policies"></a>反網路釣魚原則

[ATP 反網路釣魚](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing)檢查內送郵件的指示，郵件可能是網路釣魚企圖。 當使用者在 ATP 原則（安全的附件、安全連結或反網路釣魚）涵蓋時，會透過分析郵件的多部機器教學模型評估內送郵件，並根據設定的原則採取適當的動作。

### <a name="real-time-reports"></a>即時報告

Office 365 安全性 & 規範中心提供的監控功能包含[即時報告和深入](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp)資訊，讓您的安全性和合規性系統管理員關注高優先順序的問題，例如安全性攻擊或增加的可疑活動。 除了醒目提示問題之外，智慧報告和洞察力也包含建議和連結，以查看及流覽資料，也會快速採取動作。

### <a name="threat-trackers"></a>威脅追蹤工具

[威脅](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers)追蹤器是資訊性的小元件和視圖，可讓授權的使用者在可能影響組織的 cybersecurity 問題上使用情報。

### <a name="explorer"></a>探險 家

瀏覽器（也稱為威脅瀏覽器）是一種即時報告，可讓授權的使用者識別及分析最近的威脅。 根據預設，此報告會顯示過去7天的資料;不過，您可以修改視圖，以顯示過去30天的資料。

如需 Explorer （Office 365 Advanced 威脅防護方案2）和即時偵測（位於 Office 365 高級威脅防護方案1）中的詳細資訊，請參閱[威脅瀏覽器（和即時偵測）](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)。

### <a name="automated-incident-response"></a>自動化的事件回應

Office 365 ATP 方案2中可用的[自動事件回應](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air)（AIR）功能可讓您執行自動調查處理程式，以回應目前存在的已知威脅。 透過自動化某些調查任務，您的安全性運作小組可以更有效率地運作。 修正動作（如刪除惡意電子郵件訊息）是由您的安全性運作小組核准。 若要深入瞭解，請參閱[Office 365 中的 AIR 運作方式](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office)。

### <a name="attack-simulator"></a>攻擊模擬器

[攻擊模擬器](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator)可讓授權使用者在您的組織中執行現實的攻擊案例。 有幾種不同的攻擊可供使用，包括顯示名稱 spear 網路釣魚攻擊、密碼噴塗攻擊和強力密碼攻擊。
