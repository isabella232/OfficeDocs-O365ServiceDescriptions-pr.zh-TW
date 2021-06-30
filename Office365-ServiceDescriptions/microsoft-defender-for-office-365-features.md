---
title: Microsoft Defender Office 365 功能服務說明
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: ''
description: 深入瞭解 Microsoft Defender 中可用於 Office 365 的功能。
ms.openlocfilehash: 620639a2c40d589123ebda33446411533798d2ec
ms.sourcegitcommit: 7ee8775831fd481ab2ef477245d2ae2af98ac2d7
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 06/30/2021
ms.locfileid: "53204861"
---
# <a name="microsoft-defender-for-office-365-features-service-description"></a>Microsoft Defender Office 365 功能服務說明

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>Microsoft Defender Office 365 的新功能

我們會繼續為 Office 365 的 Defender 新增新功能。 若要深入瞭解 Office 365 (或 Microsoft 365 一般) 中的新功能，請參閱下列資源：

- [Microsoft 365 藍圖](https://www.microsoft.com/microsoft-365/roadmap)

- [Microsoft Defender 的新增功能 Office 365-Office 365 |Microsoft 檔](/microsoft-365/security/office-365-security/whats-new-in-defender-for-office-365)

## <a name="defender-for-office-365-capabilities"></a>Office 365 功能的 Defender

### <a name="safe-attachments"></a>安全附件

[保管庫附件](/microsoft-365/security/office-365-security/atp-safe-attachments)可保護未知的惡意程式碼和病毒，並提供零的保護來保護郵件系統。 所有沒有已知病毒/惡意程式碼簽章的郵件和附件，都是路由傳送至特殊的環境，其中 Office 365 的 Defender 會使用各種機器學習和分析技術來偵測惡意目的。 如果未偵測到可疑活動，即會釋出訊息傳遞到信箱。

> [!NOTE]
> 保管庫附件掃描會在您的 Office 365 資料所在的相同區域中進行。 如需資料中心地理位置的詳細資訊，請參閱[您的資料位於何處？](/microsoft-365/enterprise/o365-data-locations)

### <a name="safe-links"></a>安全連結

[保管庫連結](/microsoft-365/security/office-365-security/atp-safe-links)功能會主動保護您的使用者免受郵件中或 Office 檔中的惡意 URLs。 因為可動態封鎖惡意連結，允許存取無害連結，所以每次使用者選取連結時都能受到持續保護。

下列應用程式的 URL 可使用安全連結：

- Windows 或 Mac 上的 Microsoft 365 Apps 企業版

- Office 網頁版 (Word 網頁版、Excel 網頁版、PowerPoint 網頁版和 OneNote 網頁版)

- Windows 上的 Word、Excel 及 PowerPoint

- Microsoft Teams 頻道與聊天

> [!NOTE]
> 使用者必須已取得 Office 365 的 Defender 授權 <sup>\*</sup> ，必須包含在保管庫連結原則中，而且必須登入其裝置上，才可進行保護。
>
> <sup>\*</sup>針對 Office 365 授權的整個組織的 Defender (例如，ATP_ENTERPRISE_FACULTY) ，您不需要為個別使用者指派 Office 365 授權的 Defender。
>
> 如需保管庫連結保護的詳細資訊，請參閱[保管庫 Microsoft Defender for Office 365 中的連結](/microsoft-365/security/office-365-security/atp-safe-links)。

### <a name="safe-documents"></a>安全文件

[保管庫檔](/microsoft-365/security/office-365-security/safe-docs)功能使用[Microsoft Defender for 端點](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection)掃描在[受保護的檢視](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)中開啟的檔和檔案。

開始之前有哪些須知？

- 保管庫檔現在一般可供使用者使用 Office 版本 2004 (12730) 或以上！ 此功能預設為關閉，必須由安全性管理員啟用。

- 此功能僅適用于具有 Microsoft 365 E5 或 Microsoft 365 E5 安全性授權 (的使用者，但不會包含在 Office 365 方案) 的 Defender 中。

- Windows 上的 Word、Excel 及 PowerPoint

- Microsoft Teams 頻道與聊天

> [!NOTE]
> 使用者必須要有 Microsoft 365 E5 或 Microsoft 365 E5 安全性的授權 <sup>\*</sup> ，必須包含在保管庫檔原則中，且必須登入其裝置，才可進行保護。
>
> 如需保管庫檔案保護的詳細資訊，請參閱[Microsoft 365 E5 中的保管庫檔](/microsoft-365/security/office-365-security/safe-docs)。

### <a name="protection-for-sharepoint-onedrive-and-microsoft-teams"></a>保護 SharePoint、OneDrive 及 Microsoft Teams

[保護 SharePoint、OneDrive 及 Microsoft Teams](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)可協助偵測和封鎖在小組網站和文件庫中識別為惡意的檔案。 此外，保管庫的連結保護現在也可用於 Microsoft Teams 通道和聊天。

### <a name="anti-phishing-policies"></a>防網路釣魚原則

[反網路釣魚](/microsoft-365/security/office-365-security/atp-anti-phishing) 檢查內送郵件中是否有郵件可能是網路釣魚企圖。 當使用者在 Office 365 原則中涵蓋時 (保管庫附件、保管庫連結或反網路釣魚) 時，會透過分析郵件的多部機器教學模型評估內送郵件，並根據設定的原則採取適當的動作。

### <a name="real-time-reports"></a>即時報告

[安全性 & 合規性中心](https://protection.office.com)內可用的監控功能包括[即時報告和深入](/microsoft-365/security/office-365-security/view-reports-for-atp)資訊，讓您的安全性和合規性系統管理員關注高優先順序的問題，例如安全性攻擊或增加的可疑活動。 除了醒目提示問題之外，智慧報告和洞察力也包含建議和連結，以查看及流覽資料，也會快速採取動作。

### <a name="threat-explorer"></a>威脅總管

威脅瀏覽器 (也稱為 Explorer) 是即時報告，可讓授權的使用者識別及分析最近的威脅。 根據預設，此報告會顯示過去7天的資料;不過，您可以修改視圖，以顯示過去30天的資料。

Explorer 包含一些視圖，例如電子郵件和內容) 、提交、網路釣魚和所有電子郵件的惡意程式碼 (。 若要查看 Explorer 如何與即時偵測相比較，請 [下載此 PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)。

如需 microsoft defender for a Office 365 plan 2) 和即時偵測 (的 microsoft defender 中的 Explorer (的詳細資訊，請參閱 Office 365 plan 1) 的[威脅瀏覽器和即時](/microsoft-365/security/office-365-security/threat-explorer)偵測。

### <a name="real-time-detections"></a>即時偵測

即時偵測是即時的報告，可讓授權的使用者識別並分析最近的威脅。 類似 Explorer，依預設，此報告會顯示過去7天的資料。

即時偵測包含諸如電子郵件和內容) 、報送和網路釣魚的惡意程式碼 (的視圖。 若要查看即時檢測與瀏覽器的比較方式，請 [下載此 PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)。

如需 microsoft defender for a Office 365 plan 2) 和即時偵測 (的 microsoft defender 中的 Explorer (的詳細資訊，請參閱 Office 365 plan 1) 的[威脅瀏覽器和即時](/microsoft-365/security/office-365-security/threat-explorer)偵測。

### <a name="threat-trackers"></a>威脅追蹤工具

[威脅](/microsoft-365/security/office-365-security/threat-trackers) 追蹤器是資訊性的小元件和視圖，可讓授權的使用者在可能影響組織的 cybersecurity 問題上使用情報。

### <a name="automated-investigation--response"></a>自動調查 & 回應

[自動調查 & 回應](/microsoft-365/security/office-365-security/office-365-air) (適用于 Office 365 計畫2的 AIR) 功能，可讓您執行自動調查程式，以回應目前存在的已知威脅。 透過自動化某些調查任務，您的安全性運作小組可以更有效率地運作。 修正動作（如刪除惡意電子郵件訊息）是由您的安全性運作小組核准。 若要深入瞭解，請參閱[Office 365 中的 AIR 的運作方式](/microsoft-365/security/office-365-security/automated-investigation-response-office)。

### <a name="attack-simulation-training"></a>攻擊模擬訓練

[攻擊模擬訓練](/microsoft-365/security/office-365-security/attack-simulation-training-get-started) 是一種可自動建立及管理網路釣魚模擬的智慧社交風險管理工具。 模擬會使用實際的世界釣魚網絡 lures 和超目標訓練來協助客戶偵測、設定優先順序和修正網路釣魚風險，以變更員工的行為。

- 現在，WW 已提供攻擊模擬訓練，GCC (將會從6月21日) GCC。
- 如需如何開始的詳細資訊，請參閱 [使用攻擊模擬訓練](/microsoft-365/security/office-365-security/attack-simulation-training-get-started)。
- 可以使用各種套用取消 weaponized、真實世界網路釣魚負載的攻擊技術，以複製真實世界的攻擊者行為，以進行網路釣魚模擬。
- 這項服務可供有 Microsoft 365 E5、Office 365 E5 或[Microsoft Defender Office 365 方案2授權的](/microsoft-365/security/office-365-security/defender-for-office-365#microsoft-defender-for-office-365-plan-1-and-plan-2)組織使用。 將功能的子集提供給 E3 客戶以進行試用。
- 若要深入瞭解和嘗試類比，請參閱 [模擬網路釣魚攻擊](/microsoft-365/security/office-365-security/attack-simulation-training)。