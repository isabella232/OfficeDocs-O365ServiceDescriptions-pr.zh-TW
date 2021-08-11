---
title: 適用於 Office 365 的 Microsoft Defender 服務描述
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
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Defender for Office 365 是一種雲端式電子郵件篩選服務，可協助您的組織抵禦未知惡意程式碼和病毒，方法是提供強健的零日保護，並提供功能，以即時保護您的組織不受有害連結。
ms.openlocfilehash: 823527f1ef0fbd0284fb1b703d3c6e9f7dfdad440138b6d724077ad5badb9bca
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 08/06/2021
ms.locfileid: "54663096"
---
# <a name="microsoft-defender-for-office-365-service-description"></a>適用於 Office 365 的 Microsoft Defender 服務描述

Microsoft Defender for Office 365 是一種雲端式電子郵件篩選服務，可協助您的組織抵禦電子郵件和共同作業工具的高級威脅，例如網路釣魚、商務電子郵件洩漏和惡意程式碼攻擊。 Office 365 的 Defender 也提供調查、搜尋和修正功能，以協助安全性小組有效識別、優先考慮威脅，以及回應威脅。

以下是您可以使用 Defender 進行郵件保護 Office 365 的主要方式：

- 在 Office 365 僅限篩選的案例中，Office 365 的 defender 為您的內部部署 Exchange Server 環境或任何其他內部部署 SMTP 電子郵件解決方案，提供雲端式電子郵件保護。

- 您可以啟用 Office 365 的 Defender 以保護 Exchange Online 雲端主控信箱。 若要深入瞭解 Exchange Online，請參閱[Exchange Online 服務描述](exchange-online-service-description/exchange-online-service-description.md)。

- 在混合式部署中，當您混合使用內部部署和雲端信箱與輸入電子郵件篩選的 Exchange Online Protection 時，可將 Office 365 的 Defender 設定為保護您的郵件環境和控制郵件路由。

## <a name="available-plans"></a>可用規劃

如需可讓使用者使用 Microsoft Defender Office 365 的訂閱詳細的計畫資訊，請參閱[完整訂閱比較表](https://go.microsoft.com/fwlink/?linkid=2139145)。

## <a name="feature-availability"></a>功能可用性

下表列出適用于各種方案 Office 365 功能的主要 Microsoft Defender。 適用某些注意事項。 如需進一步資訊，請參閱註腳。 此表格可能會變更而不另行通知。 如需跨方案 Office 365 功能的最新完整清單，請參閱[microsoft defender for Office 365 features service description](microsoft-defender-for-office-365-features.md)。

| 功能 | 適用於 Office 365 的 Defender 方案 1 | 適用於 Office 365 的 Defender 方案 2 | Microsoft 365 E5/A5 安全性 |
|---------|--------------------------------|--------------------------------|--------------------------------|
| *設定、保護及偵測* | | | |
| 預設的安全性原則和設定分析器 | 是 | 是 | 是 |
| [安全附件](microsoft-defender-for-office-365-features.md#safe-attachments) (部分機器翻譯) | 是 | 是 | 是 |
| 保管庫Teams 中的附件 | 是 | 是 | 是 |
| [安全連結](microsoft-defender-for-office-365-features.md#safe-links) | 是 | 是 | 是 |
| [安全文件](microsoft-defender-for-office-365-features.md#safe-documents) | 否 | 否 | 是 |
| Teams 中的安全連結 | 是 | 是 | 是 |
| 報告郵件 Add-In | 是 | 是 | 是 |
| [保護 SharePoint、OneDrive 及 Microsoft Teams](microsoft-defender-for-office-365-features.md#protection-for-sharepoint-onedrive-and-microsoft-teams) | 是 | 是 | 是 |
| [防網路釣魚原則](microsoft-defender-for-office-365-features.md#anti-phishing-policies) | 是 | 是 | 是 |
| [即時報告](microsoft-defender-for-office-365-features.md#real-time-reports) | 是 | 是 | 是 |
| 內部郵件的高級保護 | 是 | 是 | 是 |
| *自動化、調查、修正及教育* | | | |
| [威脅追蹤工具](microsoft-defender-for-office-365-features.md#threat-trackers) | 否 | 是 | 是 |
| 行銷活動檢視 | 否 | 是 | 是 |
| 威脅調查 (高級威脅調查)  | [即時偵測](microsoft-defender-for-office-365-features.md#real-time-detections) | [總管](microsoft-defender-for-office-365-features.md#threat-explorer) | [總管](microsoft-defender-for-office-365-features.md#threat-explorer) |
| [自動調查 & 回應](microsoft-defender-for-office-365-features.md#automated-investigation--response) | 否 | 是 | 是 |
| [攻擊模擬訓練](microsoft-defender-for-office-365-features.md#attack-simulation-training) | 否 | 是 | 是 |
| *與 [Microsoft 365 Defender](/microsoft-365/security/defender/microsoft-365-defender)整合* | 否 | 是 | 是 |

> [!NOTE]
> Office 365 的 Microsoft Defender 是 Microsoft 365 Defender 的元件。 如需 Microsoft 365 Defender 的自動化跨網域安全性的詳細資訊，請參閱[Microsoft 365 Defender 需求](/microsoft-365/security/mtp/prerequisites)。

## <a name="learn-more"></a>深入了解

如需適用于 Office 365 的 Microsoft Defender 的詳細資訊，請參閱下列資源：

- [microsoft 檔上的 microsoft Defender for Office 365](/microsoft-365/security/office-365-security/defender-for-office-365)
- [Microsoft Office 365 網站的 Defender](https://www.microsoft.com/security/business/threat-protection/office-365-defender)
- [用於 Office 365 博客的 Microsoft Defender](https://techcommunity.microsoft.com/t5/microsoft-defender-for-office/bg-p/MicrosoftDefenderforOffice365Blog)
- [Office 365 論壇的 Microsoft Defender](https://techcommunity.microsoft.com/t5/microsoft-defender-for-office/bd-p/MicrosoftDefenderforOffice365)

### <a name="licensing-terms"></a>授權條款

如需透過 Microsoft 商用大量授權方案購買的產品和服務的授權條款及條件，請參閱[產品條款網站](https://www.microsoft.com/licensing/terms/)。

### <a name="messaging"></a>訊息

若要瞭解即將進行的變更，包括新增及變更的功能、規劃的維護或其他重要宣告，請造訪郵件中心。 如需詳細資訊，請參閱[訊息中心](/microsoft-365/admin/manage/message-center)。

### <a name="accessibility"></a>協助工具

Microsoft 持續致力於您的資料安全性，以及我們服務的[協助工具](https://www.microsoft.com/trust-center/compliance/accessibility)。 如需詳細資訊，請參閱 [Microsoft 信任中心](https://www.microsoft.com/trust-center)和 [Office 協助工具中心](https://support.office.com/article/ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d)。
