---
title: Office 365 進階威脅防護服務說明
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Office 365 Advanced 威脅防護 (ATP) 是雲端式的電子郵件篩選服務，可協助您的組織抵禦未知的惡意程式碼和病毒，方法是提供強健的零日保護，並包含即時保護組織不受有害連結的功能。
ms.openlocfilehash: 9a735338dc1cf99c35058ec7f1ae829d2c081936
ms.sourcegitcommit: 8d17d5df1427a817df15d45eae5f2f3e48d7b12d
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/23/2020
ms.locfileid: "48214362"
---
# <a name="office-365-advanced-threat-protection-service-description"></a>Office 365 進階威脅防護服務說明

Microsoft Office 365 Advanced 威脅防護 (ATP) 是雲端式的電子郵件篩選服務，可協助您的組織抵禦未知的惡意程式碼和病毒，方法是提供強健的零日保護，並包含即時保護組織不受有害連結的功能。 ATP 具有豐富報告和 URL 追蹤功能，可讓系統管理員深入了解組織中發生的攻擊的類型。

下列是您可以使用 ATP 來保護郵件的主要方法：

- 在 Office 365 ATP 僅篩選案例中，ATP 會針對內部部署 Exchange Server 環境或任何其他內部部署 SMTP 電子郵件解決方案，提供雲端式電子郵件保護。

- 您可以啟用 Office 365 ATP 來保護 Exchange Online 雲端託管信箱。 若要深入瞭解 Exchange Online，請參閱 [Exchange online 服務說明](exchange-online-service-description/exchange-online-service-description.md)。

- 在混合部署中，當您混合使用內部部署及雲端信箱並使用 Exchange Online Protection 來進行輸入電子郵件篩選時，可將 ATP 設定為保護您的郵件環境與控制郵件路由。

## <a name="office-365-advanced-threat-protection-atp-availability"></a>Office 365 進階威脅防護 (ATP) 可用性

Office 365 ATP 方案 2 包含在 Office 365 E5、Office 365 A5 和 Microsoft 365 E5 中。 Office 365 ATP 方案 1 包含在 Microsoft 365 商務進階版中。

您可以將 ATP 新增至下列 Exchange 和 Microsoft 365 訂閱計畫：

- Exchange Online Plan 1

- Exchange Online Plan 2

- Exchange Online Kiosk

- Exchange Online Protection

- Microsoft 365 商務基本版

- Microsoft 365 商務標準版

- Office 365 企業版 E1

- Office 365 企業版 E3

- Office 365 企業版 F3

- Office 365 A1

- Office 365 A3

若要購買 Office 365 進階威脅防護，請參閱 [Office 365 進階威脅防護](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content)。

若要跨方案比較功能，請參閱 [強大的工具來支援您的企業](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) ，並 [使用 Microsoft 365 轉換您的企業](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans)。

## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a>Office 365 進階威脅防護 (ATP) 的新增功能

我們正在繼續將新功能新增至 Office 365 ATP。 若要深入瞭解在一般) 中的 ATP (或 Microsoft 365 的新功能，請參閱下列資源：

- [Microsoft 365 藍圖](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Office 365 ATP 中的新功能](https://docs.microsoft.com/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a>Office 365 進階威脅防護 (ATP) 的需求

ATP 可搭配任何 SMTP 郵件傳輸代理程式使用，例如 Microsoft Exchange Server。 如需 ATP 所支援的作業系統、網頁瀏覽器及語言的相關資訊，請參閱 [Exchange Online Protection 中 exchange 系統管理中心](https://go.microsoft.com/fwlink/p/?LinkId=282381)的「支援的瀏覽器」和「支援的語言」一節。

## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a>各進階威脅防護 (ATP) 計劃中可用的功能

每項功能如下所列。提到 Exchange Online 時，通常是指 Office 365 企業版服務系列。

|**功能**|**ATP 方案1**<br> (先前的 ATP 獨立) |**ATP 方案2**<br> (先前的威脅情報 <br>獨立) | Microsoft 365 E5/E5 Security|
|:-----|:-----|:-----|:-----|
|*設定、保護及偵測*|
|[安全附件](#safe-attachments)|是|是|是|
|小組中的安全附件|是|是|是|
|[安全連結](#safe-links)|是|是|是|
|[安全檔](#safe-documents)|否|否|是|
|Teams 中的安全連結|是|是|是|
|[SharePoint、OneDrive 和 Microsoft 小組的 ATP](#atp-for-sharepoint-onedrive-and-microsoft-teams)|是|是|是|
|[防網路釣魚原則](#anti-phishing-policies)|是|是|是|
|[即時報告](#real-time-reports)|是|是|是|
|*自動化、調查、修正及教育*|
|[威脅追蹤工具](#threat-trackers)|否|是|是|
|威脅調查 (高級威脅調查) |[即時偵測](#real-time-detections)|[總管](#explorer)|[總管](#explorer)|
|[自動化的事件回應](#automated-incident-response)|否|是|是|
|[攻擊模擬器](#attack-simulator)|否|是|是|
|*與 Microsoft 威脅防護的整合*|否|否|是|

> [!TIP]
> 需要 Office 365 ATP 方案1與方案2之間的差異的可供下載的清單嗎？ [取得 PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)。 

## <a name="advanced-threat-protection-atp-capabilities"></a>進階威脅防護 (ATP) 功能

### <a name="safe-attachments"></a>安全附件

[ATP 安全附件](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments) 可防止未知的惡意程式碼和病毒，並提供零天的保護來保護您的郵件系統。 所有沒有已知病毒/惡意軟體簽章的訊息與附件將被路由傳送至特殊的環境，其中 ATP 會使用不同的機器學習與分析技術來偵測惡意的意圖。 如果未偵測到可疑活動，即會釋出訊息傳遞到信箱。

> [!NOTE]
> ATP 安全附件掃描會在您的 Office 365 資料所在的同一個區域中進行。 如需資料中心地理位置的詳細資訊，請參閱[您的資料位於何處？](https://products.office.com/where-is-your-data-located?geo=All)

### <a name="safe-links"></a>安全連結

[ATP 安全連結](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links)功能主動保護您的使用者免受郵件中或 Office 檔中的惡意 URLs。 因為可動態封鎖惡意連結，允許存取無害連結，所以每次使用者選取連結時都能受到持續保護。

下列應用程式的 URL 可使用安全連結：

- Microsoft 365 Windows 或 Mac 版企業版應用程式

- Office 網頁版 (Word 網頁版、Excel 網頁版、PowerPoint 網頁版和 OneNote 網頁版)

- Windows 上的 Word、Excel 及 PowerPoint

- Microsoft Teams 頻道與聊天

> [!NOTE]
> 使用者必須是 ATP 的授權，必須 <sup>\*</sup> 包含在 Atp 安全連結原則中，且必須在裝置上登入，以進行保護。
>
> <sup>\*</sup> 若為全組織的 ATP 授權 (例如，ATP_ENTERPRISE_FACULTY) ，您不需要將 ATP 授權指派給個別使用者。
>
> 如需有關 ATP 安全連結保護的詳細資訊，請參閱 [Atp 安全連結如何與 Office 檔中的 URLs 搭配運作](https://docs.microsoft.com/microsoft-365/security/office-365-security/how-atp-safe-links-works#how-atp-safe-links-works-with-urls-in-office-documents)。

### <a name="safe-documents"></a>安全檔

[ATP 安全](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs)檔功能使用「 [Microsoft Defender 高級威脅防護](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection)」來掃描在[受保護的檢視](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)中開啟的檔和檔案。

開始之前有哪些須知？

- 12730 Office 版本2004的使用者通常可使用安全檔， () 或更高！ 此功能預設為關閉，必須由安全性管理員啟用。

- 此功能僅適用于使用 Microsoft 365 E5 或 Microsoft 365 E5 安全性授權 (未包含在 Office 365 ATP 計畫) 中的使用者。

- Windows 上的 Word、Excel 及 PowerPoint

- Microsoft Teams 頻道與聊天

> [!NOTE]
> 使用者必須是 Microsoft 365 E5 或 Microsoft 365 E5 Security 的授權 <sup>\*</sup> ，必須包含在 ATP 安全檔原則中，且必須在裝置上登入，以進行保護。
>
> 如需 ATP 安全檔案保護的詳細資訊，請參閱 [Microsoft 365 E5 中的安全檔](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs)。

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>適用於 SharePoint、OneDrive 及 Microsoft Teams 的 ATP

[SharePoint、OneDrive 和 Microsoft 團隊的 ATP](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)  可協助偵測和封鎖在小組網站和文件庫中識別為惡意的檔案。 此外，在 Microsoft 小組通道和聊天中，現在還提供 ATP 安全連結保護。

### <a name="anti-phishing-policies"></a>防網路釣魚原則

[ATP 反網路釣魚](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing) 檢查內送郵件的指示，郵件可能是網路釣魚企圖。 當使用者受 ATP 原則 (安全附件、安全連結或反網路釣魚) 保護時，系統會根據已設定的原則，以多個可分析郵件的電腦學習模型來評估傳入的郵件，並採取適當動作。

### <a name="real-time-reports"></a>即時報告

安全性 & 合規性中心內可用的監控功能包括 [即時報告和深入](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp) 資訊，讓您的安全性和合規性系統管理員關注高優先順序的問題，例如安全性攻擊或增加的可疑活動。 除了醒目提示問題之外，智慧報告和洞察力也包含建議和連結，以查看及流覽資料，也會快速採取動作。

### <a name="explorer"></a>總管

總管 (也稱為威脅總管) 是即時的報告，可讓授權的使用者識別並分析最近的威脅。 根據預設，此報告會顯示過去 7 天的資料；不過，您可以修改檢視畫面以顯示過去 30 天的資料。

Explorer 包含一些視圖，例如電子郵件和內容) 、提交、網路釣魚和所有電子郵件的惡意程式碼 (。 若要查看 Explorer 如何與即時偵測相比較，請 [下載此 PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)。

如需 office 365 advanced 威脅防護方案 2) 和即時偵測 () 365 中的 Explorer (的詳細資訊，請參閱 [威脅 Explorer 和即時](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)偵測。

### <a name="real-time-detections"></a>即時偵測

即時偵測是即時的報告，可讓授權的使用者識別並分析最近的威脅。 與 [總管] 類似，根據預設，此報告顯示過去 7 天的資料。

即時偵測包含諸如電子郵件和內容) 、報送和網路釣魚的惡意程式碼 (的視圖。 若要查看即時檢測與瀏覽器的比較方式，請 [下載此 PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)。

如需 office 365 advanced 威脅防護方案 2) 和即時偵測 () 365 中的 Explorer (的詳細資訊，請參閱 [威脅 Explorer (和即時偵測) ](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)。

### <a name="threat-trackers"></a>威脅追蹤工具

[威脅](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers) 追蹤器是資訊性的小元件和視圖，可讓授權的使用者在可能影響組織的 cybersecurity 問題上使用情報。

### <a name="automated-incident-response"></a>自動化的事件回應

[自動事件回應](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air) (OFFICE 365 ATP 方案2中可用的 AIR) 功能，可讓您執行自動化調查程式，以回應目前存在的已知威脅。 透過自動化某些調查任務，您的安全性運作小組可以更有效率地運作。 修正動作（如刪除惡意電子郵件訊息）是由您的安全性運作小組核准。 若要深入瞭解，請參閱 [Office 365 中的 AIR 運作方式](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office)。

### <a name="attack-simulator"></a>攻擊模擬器

[攻擊模擬器](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator) 可讓授權使用者在您的組織中執行現實的攻擊案例。 有幾種不同的攻擊可供使用，包括顯示名稱 spear 網路釣魚攻擊、密碼噴塗攻擊和強力密碼攻擊。
