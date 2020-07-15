---
title: 規劃 Microsoft 365 合規性 - GCC High
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: 本指南適用于促進美國聯邦政府機構中的 Office 365 部署的 IT 專業人員，或是處理政府規定和需求之資料的其他實體，其使用 Microsoft 365 政府– GCC 高的方式，都適用于符合這些需求。
ms.openlocfilehash: 6e5e8fb9001adb873e07ce50f084bb80a3b28808
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132497"
---
# <a name="plan-for-microsoft-365-compliance--gcc-high"></a>規劃 Microsoft 365 合規性– GCC 高

本指南適用于促進美國聯邦政府機構中的 Office 365 部署的 IT 專業人員，或是處理政府規定和需求之資料的其他實體，其使用 Microsoft 365 政府– GCC 高的方式，都適用于符合這些需求。

> [!NOTE]
>如果您的組織已符合 Microsoft 365 政府– GCC 的高資格需求，且已套用至程式並被公認，您可以略過步驟1和2，直接移至步驟3。
 
## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government--gcc-high-and-meets-eligibility-requirements"></a>步驟 1： 判斷您的組織是否需要 Microsoft 365 政府– GCC 高並符合資格需求

Microsoft 365 政府版高環境符合美國政府對雲端服務的需求。 除了享受 Office 365 的功能之外，組織還會受益于 Microsoft 365 政府（GCC 高）特有的下列功能：

- 您組織的客戶內容與 Microsoft 的商業 Office 365 服務中的客戶內容有邏輯隔離。
- 組織的客戶內容儲存於美國境內。
- 只有經過篩選的 Microsoft 人員可以存取組織的客戶內容。
- Microsoft 365 政府– GCC 高遵循美國公開部門客戶所需的認證和資格鑒定。

您可以在[Office 365 政府版方案](https://products.office.com/government/compare-office-365-government-plans)（包括資格要求）中找到有關 Microsoft 365 政府– GCC 優質產品的詳細資訊。

[Office 365 US 政府服務描述](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government)說明平臺的優點，其位於美國的符合規範需求。

> [!TIP]
> 您可能想要將服務描述中的資訊表格傳輸到 Excel 活頁簿中，並新增兩欄： **適用于我的組織，y/n**   及 **符合我的組織的需求**。 然後您可以與同事一起查看此清單，以確認此服務符合您組織的需求。

**決策點**：<br/>
- *決定 Microsoft 365 政府– GCC-高是否適用于您的組織。*
- *確認您的組織符合資格的需求。*

> [!NOTE]
> Microsoft 365 政府-GCC High 僅限美國境內。 非美國政府客戶可以選擇許多[Office 365 政府方案](https://products.office.com/government/compare-office-365-government-plans)。

## <a name="step-2-apply-for-microsoft-365-government--gcc-high"></a>步驟 2： 適用于 Microsoft 365 政府– GCC-高

確定此服務對您的組織而言是正確的，請啟動[此服務的應用程式](https://products.office.com/government/eligibility-validation)。
 
## <a name="step-3-understand-microsoft-365-government--gcc-high-default-security-settings"></a>步驟 3： 瞭解 Microsoft 365 政府– GCC-高預設安全性設定

建議您在修改系統管理員和安全性設定之前，請先仔細檢查您的系統管理員和安全性設定，並考慮對規範的影響，再變更預設安全性設定。

**決策點**：*決定是否要修改任何預設的 Microsoft 365 政府– GCC-高安全性設定，並解決以先瞭解可能進行的任何變更的影響。*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gcc-highsup1sup"></a>步驟 4： 瞭解 Microsoft 365 政府中目前可使用或已停用的功能為何功能-GCC-高<sup>1</sup>

為了符合我們政府雲端客戶的需求，Microsoft 365 政府– GCC-優質和 enterprise 方案之間有一些差異。 請參閱下表，以查看哪些功能可供使用。

|                                         | 功能                                         | GCC 高狀態        |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **資訊保護 & 控管** | 封存                                       | 可以使用              |
|                                         | 手動標籤和原則<sup>2</sup>          | 可以使用              |
|                                         | 標籤的自動應用程式                      | 在工程處理積壓工作 |
|                                         | 以敏感資料類型為基礎的標籤            | 在工程處理積壓工作 |
|                                         | 以查詢為基礎的標籤和相關聯原則 | 在工程處理積壓工作 |
|                                         | 檔案計畫                                       | 在工程處理積壓工作 |
|                                         | 建議原則                            | 在工程處理積壓工作 |
|                                         | 智慧匯入篩選                            | 在工程處理積壓工作 |
|                                         | 事件型保留                           | 在工程處理積壓工作 |
|                                         | 處置評審                              | 在工程處理積壓工作 |
|                                         | 資訊屏障                            | 可以使用              |
|                                         | 檔和電子郵件的資料遺失防護（DLP）  | 可以使用              |
|                                         | DLP 用於小組聊天及通道交談    | 在工程處理積壓工作 |
|                                         | DLP 確切資料符合                            | 在工程處理積壓工作 |
|                                         | 標籤活動總管                         | 在工程處理積壓工作 |
|                                         | Trainable 分類器                           | 在工程處理積壓工作 |
|                                         | 統一的標記和敏感度標籤         | 在工程處理積壓工作 |
| **測試人員風險管理**             | 高級郵件加密                     | 可以使用              |
|                                         | 測試人員風險管理                         | 在工程處理積壓工作 |
|                                         | 通訊合規性                        | 在工程處理積壓工作 |
|                                         | 客戶加密箱                                | 可以使用              |
|                                         | 客戶金鑰                                    | 可以使用              |
|                                         | 特殊權限存取管理                    | 在工程處理積壓工作 |
| **探索 & 回應**                  | 就地保留                            | 可以使用              |
|                                         | 案例管理                                 | 可以使用              |
|                                         | 搜尋                                          | 可以使用              |
|                                         | 匯出                                          | 可以使用              |
|                                         | RMS 解密                                  | 可以使用              |
|                                         | 原生匯出                                   | 可以使用              |
|                                         | 高級處理                             | 可以使用              |
|                                         | 電子郵件執行緒                                 | 在工程處理積壓工作 |
|                                         | 接近重複識別                   | 在工程處理積壓工作 |
|                                         | 佈景主題                                          | 在工程處理積壓工作 |
|                                         | 預測編碼                               | 在工程處理積壓工作 |
|                                         | 使用 load file 處理匯出                 | 在工程處理積壓工作 |
|                                         | 標記                                         | 在工程處理積壓工作 |
|                                         | 檢視者                                         | 在工程處理積壓工作 |
|                                         | 密文                                      | 在工程處理積壓工作 |
|                                         | 篩選                                       | 在工程處理積壓工作 |
|                                         | 管理員進行工作負載對應                   | 在工程處理積壓工作 |
|                                         | 管理員通訊                        | 在工程處理積壓工作 |
|                                         | 檢查集合                                     | 在工程處理積壓工作 |
|                                         | 審閱和批註                             | 在工程處理積壓工作 |
|                                         | 非 Office 365 攝取                        | 在工程處理積壓工作 |
|                                         | 搜尋字詞報告                              | 在工程處理積壓工作 |
| **規範管理**               | 合規性分數                                | 在工程處理積壓工作 |

<sup>1</sup>識別的狀態視專案方案和優先順序重新評估而變更。<br/>
<sup>2</sup>手動應用程式標籤需要[Azure 資訊保護（AIP）用戶端版本 1](https://docs.microsoft.com/azure/information-protection/rms-client/client-version-release-history)。 


**決策點**：*決定相容性功能是否符合貴組織的需求。*
