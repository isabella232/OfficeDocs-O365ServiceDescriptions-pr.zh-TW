---
title: 規劃 Microsoft 365 合規性 - DoD 部署
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
description: 本指南適用于在美國聯邦政府機構或其他實體中，處理政府規定和需求的 Office 365 的 IT 專業人員，其使用 Microsoft 365 政府– DoD，以符合這些需求。
ms.openlocfilehash: 6ad0f21c8cbd9cf6690af4664c958c4ffdab7746
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/24/2021
ms.locfileid: "59671613"
---
# <a name="plan-for-microsoft-365-compliance---dod-deployments"></a>規劃 Microsoft 365 合規性 - DoD 部署

本指南適用于在美國聯邦政府機構或其他實體中，處理政府規定和需求的 Office 365 的 IT 專業人員，其使用 Microsoft 365 政府– DoD，以符合這些需求。

> [!NOTE]
> 如果您的組織已符合 Microsoft 365 政府– DoD 資格需求，且已套用至程式並被公認，您可以略過步驟1和2，直接移至步驟3。

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---dod-and-meets-eligibility-requirements"></a>步驟 1. 判斷您的組織是否需要 Microsoft 365 政府 DoD 並符合資格需求

Microsoft 365 政府 DoD 環境符合美國政府對雲端服務的需求。

除了享受 Office 365 的功能之外，組織還會受益于 Microsoft 365 政府– DoD 特有的下列功能：

- 您組織的客戶內容與 Microsoft 的商業 Office 365 服務中的客戶內容有邏輯隔離。
- 組織的客戶內容儲存於美國境內。
- 只有經過篩選的 Microsoft 人員可以存取組織的客戶內容。
- Microsoft 365政府 DoD 遵循美國公開部門客戶所需的認證和資格鑒定。

您可以在[Office 365 政府版方案](https://products.office.com/government/compare-office-365-government-plans)（包括資格要求）中找到 Microsoft 365 政府 DoD 產品的詳細資訊。

[Office 365 美國政府服務描述](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md)說明平臺的優點，其位於美國的符合規範需求。

> [!TIP]
> 您可能想要將服務描述中的資訊表傳送至 Excel 活頁簿，並新增兩欄：適用 **于我的組織的 y/n** ，並 **符合我的組織的需求**。 然後您可以與同事一起查看此清單，以確認此服務符合您組織的需求。

**決策點**：<br/>
- *決定是否 Microsoft 365 政府 DoD 適用于您的組織。*
- *確認您的組織符合資格的需求。*

> [!NOTE]
> Microsoft 365僅在美國提供政府 DoD。 非美國政府客戶可以選擇許多[Office 365 政府版方案](https://products.office.com/government/compare-office-365-government-plans)。

## <a name="step-2-apply-for-microsoft-365-government---dod"></a>步驟 2. 適用于 Microsoft 365 政府 DoD

確定此服務對您的組織而言是正確的，請啟動 [此服務的應用程式](https://products.office.com/government/eligibility-validation)。

## <a name="step-3-understand-microsoft-365-government---dod-default-security-settings"></a>步驟 3. 瞭解 Microsoft 365 政府 DoD 預設安全性設定

建議您在修改系統管理員和安全性設定之前，請先仔細檢查您的系統管理員和安全性設定，並考慮對規範的影響，再變更預設安全性設定。

**決策點**：*決定是否要修改任何預設的 Microsoft 365 政府 DoD 安全性設定，並解決以先瞭解可能進行的任何變更的影響。*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--dodsup1sup"></a>步驟 4. 瞭解 Microsoft 365 政府– DoD<sup>1</sup>中目前無法使用或已停用的功能。

為了符合政府雲端客戶的需求，Microsoft 365 政府 DoD 與企業方案之間有一些差異。 請參閱下表，以查看哪些功能可供使用。 請參閱[這兒](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent)，以取得 Microsoft 365 藍圖發佈的最新規範產品更新。<br><br>

| 區域  | 功能  | DoD 狀態  |
|-------|----------|-------------|
| **資訊保護**  | | |
| 敏感性資訊類型  | 完全相符的資料  | 可以使用  |
| 敏感度標籤  | Exchange Online、SharePoint 線上及商務用 OneDrive 的自動分類和標籤  | 可以使用 |
| | Office 應用程式的自動分類及標籤 (Word、Excel、PowerPoint、Outlook 跨平臺) 網頁、 (和 Mac Windows  | 可以使用  |
| | Office 用戶端的自動分類及標籤-行動電話  | 在工程處理積壓工作  |
| | Teams、Microsoft 365 群組和 SharePoint 網站的自動分類和標籤  | 可以使用  |
| | 必要標籤  | 可以使用  |
| | Office 應用程式中的手動敏感度標籤 (iOS、Android、Windows)   | 可以使用  |
| | Outlook 郵件上只加密保護的敏感度標籤設定  | 可以使用  |
| | 統一的標籤用戶端和掃描器  | 可以使用  |
| 分析  | 資料分類：綜述和內容瀏覽器  | 逐步推出  |
| | 分析：在 Office app/用戶端上具有自動標籤的機器學習分類器  | 在開發 |
| 加密  | 基本 Office 365 郵件加密 (E3)   | 可以使用  |
| | Advanced Office 365 郵件加密 (E5)   | 可以使用  |
| | 為客戶管理的金鑰布建生命週期提供您自己的金鑰 (BYOK)   | 可以使用  |
| | Office 365 的客戶金鑰  | 可以使用  |
| | Microsoft 365 多工作負載加密的客戶金鑰 | 在開發  |
| | 線上和商務用 OneDrive SharePoint 的客戶金鑰 | 可以使用 |
| | 雙重金鑰加密  | 可以使用  |
| 資料外洩防護  | 資料遺失防護 (檔和電子郵件的 DLP)   | 可以使用  |
| | DLP：提醒儀表板及警示經驗  | 可以使用  |
| | DLP 用於 Teams 聊天與通道交談  | 可以使用  |
| | DLP 端點 (公開預覽)   | 公開預覽 |
| | DLP 概覽頁面  | 逐步推出  |
| **資訊控管**  | | |
| 資訊控管  | 資訊管理：保留及標記原則的自我調整範圍 | 在工程處理積壓工作  |
| | 資訊管理：套用 Exchange 收件匣的預設標籤  | 可以使用  |
| | 資訊管理：電子郵件封存  | 可以使用  |
| | 資訊管理：匯入 PST  | 可以使用  |
| | 資訊管理：保留鎖定  | 可以使用  |
| | 資訊管理：具有 trainable 分類器的保留原則  | 在開發  |
| | 資訊管理： Teams 聊天的保留原則  | 可以使用  |
| | 資訊管理： Teams 會議錄製的保留原則  | 可以使用  |
| | 資訊管理： Teams 私人通道郵件的保留原則  | 在開發  |
| | 資訊管理：保留及標記原則自我調整範圍  | 在開發  |
| 記錄管理  | 記錄管理：手動套用記錄標籤  | 可以使用  |
| | 記錄管理：套用預設的 SharePoint 記錄標籤、商務用 OneDrive 庫、資料夾及檔集;和 Office 365 群組  | 可以使用  |
| | 記錄管理：根據特定條件自動記錄原則 (例如關鍵字或機密資訊) ;根據事件  | 可以使用  |
| | 記錄管理：處置評審  | 可以使用  |
| | 記錄管理：檔案計畫管理員  | 可以使用  |
| | 記錄管理：多階段處置評審  | 在開發  |
| | 記錄管理：雲端附件的保留和自動標記  | 在開發  |
| | 記錄管理：處置證明  | 可以使用  |
| | 記錄管理：記錄版本設定  | 可以使用  |
| | 記錄管理：法規記錄  | 可以使用  |
| **風險管理**  | | |
| 客戶加密箱 | 客戶加密箱  | 可以使用  |
| 通訊合規性  | 通訊相容性：能夠為通訊相容性原則設定保留期間 (公開預覽)   | 在工程處理積壓工作  |
| | 通訊相容性：存取警示;通知範本;通訊原則儀表板  | 可以使用  |
| | 通訊相容性：分析具有部署信箱之使用者的 Teams 聊天資料  | 可以使用  |
| | 通訊相容性：利益範本衝突  | 可以使用  |
| | 通訊相容性：建立客戶原則，3預先設定  | 可以使用  |
| | 通訊相容性：偵測成人內容  | 在工程處理積壓工作  |
| | 通訊相容性：偵測一段時間的重複行為違規代碼  | 可以使用  |
| | 通訊相容性：呈報 Advanced eDiscovery 以進行調查  | 可以使用  |
| | 通訊相容性：利用光學字元辨識 (OCR) 提取和評估郵件  | 可以使用  |
| | 通訊相容性： Microsoft Teams 整合  | 在開發  |
| | 通訊相容性：原則狀況檢查和暫停原則的功能  | 在開發  |
| | 通訊相容性： Power Automate 整合  | 在工程處理積壓工作  |
| | 通訊相容性：每個位置的敏感資訊類型報告  | 在開發  |
| | 通訊相容性：支援 Teams、Exchange 和移除 Teams 郵件  | 可以使用  |
| | 通訊相容性：支援更細微的許可權  | 可以使用  |
| | 通訊相容性：支援7種威脅、目標騷擾和 profanities 分類程式的語言  | 可以使用  |
| | 通訊相容性：在調查期間翻譯健康情況內容  | 在開發  |
| 資訊障礙  | 資訊障礙  | 逐步推出  |
| 測試人員風險管理  | 有問必答風險管理：審核記錄檔  | 公開預覽  |
| | 有問必答風險管理：案例儀表板  | 可以使用  |
| | 有問必答風險管理：活動瀏覽器中呈現的資料  | 公開預覽  |
| | 有問必答風險管理：內容瀏覽器中呈現的資料  | 在開發  |
| | 內部使用者風險管理：透過使用者竊取資料  | 可以使用  |
| | 有問必答風險管理： Windows 10 端點上之活動的裝置指示器  | 在開發  |
| | 有問必答風險管理：針對 Advanced eDiscovery 逐級提升  | 可以使用  |
| | 有問必答風險管理：匯出提醒  | 公開預覽  |
| | 有問必答風險管理：一般資料洩漏  | 可以使用  |
| | 內部人員風險管理：對有問必答風險管理中的網域設定的智慧支援  | 公開預覽  |
| | 有問必答風險管理： Microsoft Defender for Endpoint 警示的標記  | 在工程處理積壓工作  |
| | 有問必答風險管理：違反安全性原則的標記  | 在開發  |
| | 有問必答風險管理： Windows 10 端點活動的指示器 | 公開預覽  |
| | 有問必答風險管理：調查有問必答風險管理提醒  | 可以使用  |
| | 內部人員風險管理： Microsoft Teams 和 Power Automate 整合  | 在開發  |
| | 有問必答風險管理：本機觸發器支援 Azure Active Directory 帳戶刪除 | 公開預覽  |
| | 有問必答風險管理：公告範本  | 可以使用  |
| | 有問必答風險管理： Teams、SharePoint 網站、電子郵件訊息的 Office 指示器  | 可以使用  |
| | 有問必答風險管理：不滿使用者的資料洩漏原則範本  | 在工程處理積壓工作  |
| | 有問必答風險管理：按優先順序的使用者的資料洩漏原則範本  | 公開預覽  |
| | 有問必答風險管理：一般安全性原則違規的原則範本  | 在工程處理積壓工作  |
| | 內部人員風險管理：原則使用者和使用者間的安全性原則違規原則範本 | 公開預覽 |
| | 有問必答風險管理：因不滿使用者的安全性原則違規原則範本 | 在工程處理積壓工作  |
| | 內幕風險管理：原則自訂、原則狀況檢查及增強型原則建立嚮導  | 公開預覽  |
| | 有問必答風險管理：優先順序使用者群組  | 公開預覽  |
| | 有問必答風險管理：支援 Azure Active Directory 帳戶刪除的原生觸發器 | 公開預覽  |
| | 有問必答風險管理：「觀賞觀察程式」審核記錄 | 公開預覽  |
| **探索 & 回應**  | | |
| 電子文件探索 | 核心電子檔探索：審計  | 可以使用  |
| | 核心 eDiscovery：案例管理  | 可以使用  |
| | 核心 eDiscovery：商務用 OneDrive 中的規範界限  | 可以使用  |
| | 核心 eDiscovery：匯出  | 可以使用  |
| | 核心 eDiscovery：就地保留  | 可以使用  |
| | 核心 eDiscovery：原生匯出  | 可以使用  |
| | 核心 eDiscovery： RMS 解密  | 可以使用  |
| | 核心電子檔探索：搜尋  | 可以使用  |
| | Advanced eDiscovery：高級處理  | 可以使用  |
| | Advanced eDiscovery：保管人 to 工作負載對應  | 可以使用  |
| | Advanced eDiscovery：保管人通訊  | 可以使用  |
| | Advanced eDiscovery：儀表板  | 可以使用  |
| | Advanced eDiscovery： Microsoft Teams 的資料清除功能  | 在工程處理積壓工作  |
| | Advanced eDiscovery：深入編目/索引  | 可以使用  |
| | Advanced eDiscovery：中文、日文和韓文的雙位元組支援  | 可以使用  |
| | Advanced eDiscovery：電子郵件執行緒  | 可以使用  |
| | Advanced eDiscovery：匯出 (下載、匯出、新增至另一個評審集)   | 可以使用  |
| | Advanced eDiscovery：篩選  | 可以使用  |
| | Advanced eDiscovery：保留優化  | 在開發  |
| | Advanced eDiscovery： Teams 私人通道郵件的法律封存  | 在開發  |
| | Advanced eDiscovery： Microsoft 規範中心擴充支援，以在核心和 Advanced eDiscovery 的 SharePoint、商務用 OneDrive、回收 Bin 中搜尋及匯出專案  | 在開發  |
| | Advanced eDiscovery：接近重複識別  | 可以使用  |
| | Advanced eDiscovery：新的預測編碼模組  | 在開發  |
| | Advanced eDiscovery：非 custodial 資料來源  | 可以使用  |
| | Advanced eDiscovery：非 Office 365 攝取  | 在工程處理積壓工作  |
| | Advanced eDiscovery：預測編碼  | 可以使用  |
| | Advanced eDiscovery：以載入檔案處理的匯出  | 可以使用  |
| | Advanced eDiscovery：密文  | 可以使用  |
| | Advanced eDiscovery：複查集  | 可以使用  |
| | Advanced eDiscovery：檢查資料 (查詢資料、智慧標籤、儀表板) 和批註 (密文)   | 可以使用  |
| | Advanced eDiscovery：搜尋字詞報告  | 可以使用  |
| | Advanced eDiscovery：從 OneDrive 和 SharePoint 線上 (新式附件的支援連結的內容)   | 可以使用  |
| | Advanced eDiscovery：支援 Teams 反應  | 在工程處理積壓工作  |
| | Advanced eDiscovery：標記  | 可以使用  |
| | Advanced eDiscovery：承租人報告  | 可以使用  |
| | Advanced eDiscovery：主題  | 可以使用  |
| | Advanced eDiscovery：檢視器  | 可以使用  |
| | Advanced eDiscovery：在 Microsoft 規範中心內 Yammer Advanced eDiscovery  | 可以使用  |
| 稽核  | 基本稽核  | 可以使用  |
| | 高級審核：對重要事件的存取 (例如，mailitemsaccessed)   | 可以使用  |
| | 高級審核：增加管理活動 API 的頻寬  | 可以使用  |
| | 高級審核：記錄保留 (1 年)   | 可以使用  |
| | 高級審核：審核記錄的字詞保留時間 (10 年)   | 逐步推出  |
| | 高級審計：郵件轉寄和郵件傳送事件  | 可以使用  |
| | 高級審核：安全性與合規性中心可用性  | 可以使用  |
| | 高級審計： Exchange Online 和 SharePoint Online 中的搜尋字詞事件  | 在開發  |
| | 高級審計：對郵件 Teams 反應  | 在工程處理積壓工作  |
| **規範管理** | | |
| 合規性管理  | Microsoft 365 合規性中心  | 可以使用  |
| | Microsoft 雲端 App 安全性  | 可以使用  |
| | 合規性管理員  | 可以使用  |
| | 雙位元組字元支援  | 可以使用  |
| **生態** | | |
| 生態  | 第一方資料連線器： HR  | 在開發 |
| | 第一方資料連線器：實體聲譽徽章授予  | 在開發  |
| | GraphAdvanced eDiscovery 的 APIs  | 在工程處理積壓工作  |

<sup>1</sup> 識別的狀態視專案方案和優先順序重新評估而變更。<br/>

**決策點**： *決定相容性功能是否符合貴組織的需求。*
