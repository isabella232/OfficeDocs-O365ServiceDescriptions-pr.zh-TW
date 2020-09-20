---
title: 規劃 Microsoft 365 合規性 - GCC
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 本指南適用于在美國聯邦、state、local、部落或 territorial 政府機構或其他實體中，處理政府法規和需求之相關資料的 IT 專業365人員，其使用 Microsoft 365 政府-GCC，以符合這些需求。
ms.openlocfilehash: af09151b0ab1060c5a00c60d0b05bbd69c3300c0
ms.sourcegitcommit: 638bacac9e663444f7a094d5887476d8a87e3b58
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/18/2020
ms.locfileid: "47962132"
---
# <a name="plan-for-microsoft-365-compliance--gcc"></a>規劃 Microsoft 365 合規性– GCC

本指南適用于在美國聯邦、state、local、部落或 territorial 政府機構或其他實體中，處理政府法規和需求之相關資料的 IT 專業365人員，其使用 Microsoft 365 政府-GCC，以符合這些需求。

> [!NOTE]
> 如果您的組織已符合 Microsoft 365 政府-GCC 和 the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the the

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---gcc-and-meets-eligibility-requirements"></a>步驟 1： 判斷您的組織是否需要 Microsoft 365 政府-GCC 和符合資格的需求

Microsoft 365 政府版的環境符合美國政府對雲端服務的需求，包括 FedRAMP 適中，以及刑事審判和聯邦稅收資訊系統的需求 (CJI 及 FTI 資料類型) 。

除了享有 Office 365 的功能之外，組織還受益于 Microsoft 365 政府版-GCC 所獨有的下列功能：

- 您組織的客戶內容與 Microsoft 的商業 Office 365 服務中的客戶內容有邏輯隔離。

- 組織的客戶內容儲存於美國境內。

- 只有經過篩選的 Microsoft 人員可以存取組織的客戶內容。

- Microsoft 365 政府版-GCC 遵循美國公開部門客戶所需的認證和資格鑒定。

您可以在 [Office 365 政府版方案](https://products.office.com/government/compare-office-365-government-plans)（包括資格要求）中，找到有關適用于美國政府客戶的 Microsoft 365 政府版服務的詳細資訊。

[Office 365 US 政府服務描述](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government)說明平臺的優點，其位於美國的符合規範需求。

> [!TIP]
> 您可能想要將服務描述中的資訊表格傳輸到 Excel 活頁簿中，並新增兩欄： **適用于我的組織，y/n**   及 **符合我的組織的需求**。 然後您可以與同事一起查看此清單，以確認此服務符合您組織的需求。

> [!NOTE]
> Microsoft 365 政府版-GCC 僅適用于美國。 非美國政府客戶可以選擇許多 [Office 365 政府方案](https://products.office.com/government/compare-office-365-government-plans)。

**決策點**： <br/>
- *決定 Microsoft 365 政府版-GCC 是否適用于您的組織。*
- *確認您的組織符合資格的需求。*

## <a name="step-2-apply-for-microsoft-365-government---gcc"></a>步驟 2： 適用于 Microsoft 365 政府-GCC

確定此服務對您的組織而言是正確的，請啟動 [此服務的應用程式](https://products.office.com/government/eligibility-validation)。

## <a name="step-3-understand-microsoft-365-government---gcc-default-security-settings"></a>步驟 3： 瞭解 Microsoft 365 政府-GCC 預設安全性設定

建議您在修改系統管理員和安全性設定之前，請先仔細檢查您的系統管理員和安全性設定，並考慮對規範的影響，再變更預設安全性設定。

**決策點**： *決定是否要修改任何預設的 Microsoft 365 政府-GCC 安全性設定，以先瞭解可能進行的任何變更的影響。*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gccsup1sup"></a>步驟 4： 瞭解 Microsoft 365 政府中目前哪些功能目前無法使用或已停用（GCC<sup>1</sup> ）

為了符合政府雲端客戶的需求，Microsoft 365 政府版與企業版方案中有一些差異。 請參閱下表，以查看哪些功能可供使用。

|                                         | **功能**                                     | **GCC 狀態**         |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **資訊保護**              | 統一的標記和敏感度標籤         | 可以使用              |
|                                         | Sharepoint Online、Office 群組的容器標籤          | 正在推出              |
|                                         | 根據 Excel Online 的敏感資料類型自動標記，SharePoint 線上，商務 OneDrive                      | 正在推出              |
|                                         | 以 Win32 和 Mac Office 用戶端的敏感資料類型為基礎的標籤            | 在工程處理積壓工作 |
|                                         | 根據適用于 Win 32，Mac 的敏感資料類型自動標籤 |  在工程處理積壓工作              |
|                                         | 根據小組的敏感資料類型自動標籤                                       |在工程處理積壓工作              |
|                                         | 根據行動的敏感資料類型自動標籤                            |在工程處理積壓工作 |
|                                         | 以查詢為基礎的標籤和相關聯原則                            | 可以使用 |
|                                         | 標籤活動總管                           | 在工程處理積壓工作  |
|                                         | 可訓練分類器                              | 在工程處理積壓工作              |
|                                         | 基本 Office 365 郵件加密 (E3)                             | 可以使用              |
|                                         | Advanced Office 365 郵件加密 (E5)   | 可以使用              |
|                                         | Office 365 的客戶金鑰    | 可以使用 |
|                                         | 為客戶管理的金鑰布建生命週期提供您自己的金鑰 (BYOK)                             | 可以使用 |
|                                         | 存放您自己的金鑰 (HYOK) ，以跨越 Azure 資訊保護和 Active Directory () 高管制案例的 AD 版權管理 (預覽)                          | 可以使用 |
|                                         | 雙金鑰加密                           | 在工程處理積壓工作 |
|                                         | 資料遺失防護 (檔和電子郵件的 DLP)          | 可以使用 |
|                                         | DLP 用於小組聊天及通道交談         | 正在推出 |
|                                         | DLP 確切資料符合 | 在工程處理積壓工作 |
|                                         | DLP 端點 | 在工程處理積壓工作 |
| **資訊管理** | 電子郵件封存                                       | 可以使用              |
|                                         | 保留鎖定          | 可以使用              |
|                                         | 匯入 PST                      | 可以使用              |
|                                         | 手動非記錄保留標籤            | 可以使用 |
|                                         | 商務文件庫、資料夾及檔組的 SharePoint/OneDrive 的預設保留標籤。Exchange 收件匣;和 Office 365 群組 | 可以使用              |
|                                         | 保留原則給整個組織;特定位置或使用者。而且會根據特定狀況 (，例如關鍵字或機密資訊)                                        | 可以使用              |
|                                         | 具有 trainable 分類器的保留原則                            | 在工程處理積壓工作 |
|                                         | Yammer 及小組的保留原則                            | 在工程處理積壓工作 |
|                                         | 手動錄製標籤                           | 可以使用              |
|                                         | SharePoint 的預設記錄標籤、商務庫 OneDrive、資料夾及檔組;和 Office 365 群組                              | 可以使用              |
|                                         | 根據特定條件自動記錄原則 (例如關鍵字或機密資訊) ;根據事件                            | 可以使用              |
|                                         | 處置檢閱  | 可以使用              |
|                                         | 檔案計劃管理員    | 可以使用 |
|                                         | 處置證明                            | 可以使用 |
|                                         | 法規記錄                         | 在工程處理積壓工作 |
|                                         | 記錄管理授權強制執行                           | 在工程處理積壓工作 |
|                                         | 記錄管理多階段處置評審 | 在工程處理積壓工作 |
|                                         | 標籤活動總管 | 在工程處理積壓工作 |
|                                         | 可訓練分類器 | 在工程處理積壓工作 |
|                                         | 統一的標記和敏感度標籤         | 在工程處理積壓工作 |
| **測試人員風險管理**             | 客戶加密箱                                | 可以使用            |
|                                         | 用於小組、SharePoint 網站、電子郵件訊息的 Office 指示器                         | 正在推出 |
|                                         | 由去聲使用者竊取資料                        | 正在推出 |
|                                         | 一般資料洩漏                                | 正在推出              |
|                                         | 調查有問必答風險管理提醒                                   | 正在推出              
|                                         | 內幕風險管理案例儀表板、內容瀏覽器和通知範本 | 正在推出 |
|                                         | 針對高級電子檔探索進行升級以進行調查 | 正在推出|
|                                         | 依優先順序的使用者 (預覽的資料洩漏)  | 在工程處理積壓工作 |
|                                         | 因不滿使用者 (預覽的資料洩漏)  | 在工程處理積壓工作 |
|                                         |  (預覽的一般安全性原則違規)  | 在工程處理積壓工作 |
|                                         | 依優先順序的使用者、去聲使用者、不滿使用者 (預覽的安全性原則違規)  | 在工程處理積壓工作 |
|                                         |  (預覽的原則自訂)  | 在工程處理積壓工作 |
|                                         | 匯出提醒 (預覽)  | 在工程處理積壓工作 |
|                                         |  (預覽的優先順序使用者群組)  | 在工程處理積壓工作 |
|                                         | 建立客戶原則，3預先為通訊規範 (預先設定（包括）。監察原則)   | 正在推出 |
|                                         | 通訊相容性 (包括。監察原則) 支援小組、Exchange 及移除小組郵件 | 正在推出 |
|                                         | 通訊相容性 (包括。監察原則) 存取警示;通知範本;通訊原則儀表板 | 正在推出  |
|                                         | 通訊相容性 (包括。監察原則) 上報以進行「高級 eDiscovery」調查 | 正在推出 |
|                                         | 通訊相容性 (包括。監督原則) 偵測成人內容 | 正在推出 |
|                                         | 資訊屏障 | 在工程處理積壓工作 |
|                                         | 特殊權限存取管理                    | 在工程處理積壓工作 |
| **探索 & 回應**                  | 核心 eDiscovery：就地保留                            | 可以使用              |
|                                         | 核心 eDiscovery：案例管理                                 | 可以使用              |
|                                         | 核心電子檔探索：搜尋                                          | 可以使用              |
|                                         | 核心 eDiscovery：匯出                                          | 可以使用              |
|                                         | 核心 eDiscovery： RMS 解密                                  | 可以使用              |
|                                         | 核心 eDiscovery：原生匯出                                   | 可以使用              |
|                                         | 核心電子檔探索：審計                                        | 可以使用              |
|                                         | Advanced eDiscovery：高級處理                             | 可以使用 |
|                                         | Advanced eDiscovery：電子郵件執行緒                                 | 可以使用 |
|                                         | Advanced eDiscovery：接近重複識別                   | 可以使用 |
|                                         | Advanced eDiscovery：主題                                          | 可以使用 |
|                                         | Advanced eDiscovery：預測編碼                               | 可以使用 |
|                                         | Advanced eDiscovery：已使用載入檔案處理匯出                 | 可以使用 |
|                                         | Advanced eDiscovery：標記                                         | 可以使用 |
|                                         | Advanced eDiscovery： Viewer                                         | 可以使用 |
|                                         | Advanced eDiscovery：密文                                      | 可以使用 |
|                                         | Advanced eDiscovery：篩選                                       | 可以使用 |
|                                         | Advanced eDiscovery：保管人 to 工作負載對應                   | 可以使用 |
|                                         | Advanced eDiscovery：保管人通訊                        | 可以使用 |
|                                         | Advanced eDiscovery：複查集                                     | 可以使用 |
|                                         | Advanced eDiscovery：回顧和批註                             | 可以使用 |
|                                         | Advanced eDiscovery：非 Office 365 攝取                        | 可以使用 |
|                                         | Advanced eDiscovery：搜尋字詞報告                              | 可以使用 |
|                                         | 基本審核                              | 可以使用 |
|                                         | 高級審核：存取重要事件 (例如 mailitemsaccessed)                               | 正在推出 |
|                                         |  (1 年的高級審計記錄保留)                                | 正在推出 |
|                                         | 高級審核增加管理活動 API 的頻寬                              | 正在推出 |
|    **規範管理**            | 合規性管理員和分數                              | 在工程處理積壓工作 |




<sup>1</sup> 識別的狀態視專案方案和優先順序重新評估而變更。<br/>
<sup>2</sup> 手動應用程式標籤需要 [Azure 資訊保護 (AIP) 用戶端版本 1](https://docs.microsoft.com/azure/information-protection/rms-client/client-version-release-history)。


**決策點**： *決定相容性功能是否符合貴組織的需求。*
