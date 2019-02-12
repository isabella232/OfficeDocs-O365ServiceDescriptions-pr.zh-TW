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
# <a name="office-365-advanced-threat-protection-service-description"></a><span data-ttu-id="11d37-104">Office 365 進階威脅防護服務說明</span><span class="sxs-lookup"><span data-stu-id="11d37-104">Office 365 Advanced Threat Protection Service Description</span></span>

<span data-ttu-id="11d37-p102">Microsoft Office 365 進階威脅防護 (ATP) 是一種雲端架構電子郵件篩選服務，提供強大的零時差保護，同時也擁有即時保護組織防止有害連結的功能，可協助保護您的組織抵禦不明惡意軟體和病毒。ATP 具有豐富報告和 URL 追蹤功能，可讓系統管理員深入了解組織中發生的攻擊的類型。</span><span class="sxs-lookup"><span data-stu-id="11d37-p102">Microsoft Office 365 Advanced Threat Protection (ATP) is a cloud-based email filtering service that helps protect your organization against unknown malware and viruses by providing robust zero-day protection, and includes features to safeguard your organization from harmful links in real time. ATP has rich reporting and URL trace capabilities that give administrators insight into the kind of attacks happening in your organization.</span></span>
  
<span data-ttu-id="11d37-107">您可以使用 ATP 的郵件保護的主要方法如下：</span><span class="sxs-lookup"><span data-stu-id="11d37-107">The following are the primary ways you can use ATP for message protection:</span></span>
  
- <span data-ttu-id="11d37-108">在 Office 365 ATP 僅篩選案例 ATP 提供雲端式電子郵件保護內部部署 Exchange Server 環境或任何其他內部部署 SMTP 電子郵件解決方案。</span><span class="sxs-lookup"><span data-stu-id="11d37-108">In an Office 365 ATP filtering-only scenario, ATP provides cloud-based email protection for your on-premises Exchange Server environment or any other on-premises SMTP email solution.</span></span>
    
- <span data-ttu-id="11d37-p103">Office 365 ATP 可保護 Exchange Online 的雲端託管信箱。若要深入了解 Exchange Online，請參閱 [Exchange Online 服務說明](exchange-online-service-description/exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="11d37-p103">Office 365 ATP can be enabled to protect Exchange Online cloud-hosted mailboxes. To learn more about Exchange Online, see the [Exchange Online Service Description](exchange-online-service-description/exchange-online-service-description.md).</span></span>
    
- <span data-ttu-id="11d37-111">在混合部署中，當您混合使用內部部署及雲端信箱並使用 Exchange Online Protection 來進行輸入電子郵件篩選時，可將 ATP 設定為保護您的郵件環境與控制郵件路由。</span><span class="sxs-lookup"><span data-stu-id="11d37-111">In a hybrid deployment, ATP can be configured to protect your messaging environment and control mail routing when you have a mix of on-premises and cloud mailboxes with Exchange Online Protection for inbound email filtering.</span></span>
    
## <a name="office-365-advanced-threat-protection-atp-availability"></a><span data-ttu-id="11d37-112">Office 365 進階威脅防護 (ATP) 可用性</span><span class="sxs-lookup"><span data-stu-id="11d37-112">Office 365 Advanced Threat Protection (ATP) availability</span></span>

<span data-ttu-id="11d37-113">ATP 隨附於 Office 365 企業版 E5、 Office 365 教育版 A5、 及 Microsoft 365 Business。</span><span class="sxs-lookup"><span data-stu-id="11d37-113">ATP is included in Office 365 Enterprise E5, Office 365 Education A5, and Microsoft 365 Business.</span></span> 
  
<span data-ttu-id="11d37-114">您可以將 ATP 新增至下列 Exchange 與 Office 365 訂閱計劃：</span><span class="sxs-lookup"><span data-stu-id="11d37-114">You can add ATP to the following Exchange and Office 365 subscription plans:</span></span> 
  
- <span data-ttu-id="11d37-115">Exchange Online Plan 1</span><span class="sxs-lookup"><span data-stu-id="11d37-115">Exchange Online Plan 1</span></span>
    
- <span data-ttu-id="11d37-116">Exchange Online Plan 2</span><span class="sxs-lookup"><span data-stu-id="11d37-116">Exchange Online Plan 2</span></span>
    
- <span data-ttu-id="11d37-117">Exchange Online Kiosk</span><span class="sxs-lookup"><span data-stu-id="11d37-117">Exchange Online Kiosk</span></span>
    
- <span data-ttu-id="11d37-118">Exchange Online Protection</span><span class="sxs-lookup"><span data-stu-id="11d37-118">Exchange Online Protection</span></span>
    
- <span data-ttu-id="11d37-119">Office 365 商務基本版</span><span class="sxs-lookup"><span data-stu-id="11d37-119">Office 365 Business Essentials</span></span>
    
- <span data-ttu-id="11d37-120">Office 365 商務進階版</span><span class="sxs-lookup"><span data-stu-id="11d37-120">Office 365 Business Premium</span></span>
    
- <span data-ttu-id="11d37-121">Office 365 企業版 E1</span><span class="sxs-lookup"><span data-stu-id="11d37-121">Office 365 Enterprise E1</span></span>
    
- <span data-ttu-id="11d37-122">Office 365 Enterprise E3</span><span class="sxs-lookup"><span data-stu-id="11d37-122">Office 365 Enterprise E3</span></span>
    
- <span data-ttu-id="11d37-123">Office 365 企業版 F1</span><span class="sxs-lookup"><span data-stu-id="11d37-123">Office 365 Enterprise F1</span></span>
    
- <span data-ttu-id="11d37-124">Office 365 A1</span><span class="sxs-lookup"><span data-stu-id="11d37-124">Office 365 A1</span></span>
    
- <span data-ttu-id="11d37-125">Office 365 A3</span><span class="sxs-lookup"><span data-stu-id="11d37-125">Office 365 A3</span></span>
    
<span data-ttu-id="11d37-126">若要購買 Office 365 進階威脅防護，請參閱 [Office 365 進階威脅防護](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content)。</span><span class="sxs-lookup"><span data-stu-id="11d37-126">To buy Office 365 Advanced Threat Protection, see [Office 365 Advanced Threat Protection](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content).</span></span>
  
<span data-ttu-id="11d37-127">若要跨方案比較功能，請參閱 [比較 Office 365 for Business 方案](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409)。</span><span class="sxs-lookup"><span data-stu-id="11d37-127">To compare features across plans, see [Compare Office 365 for Business plans](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409).</span></span>
  
## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a><span data-ttu-id="11d37-128">Office 365 進階威脅防護 (ATP) 的新增功能</span><span class="sxs-lookup"><span data-stu-id="11d37-128">What's new in Office 365 Advanced Threat Protection (ATP)</span></span>

<span data-ttu-id="11d37-p104">開始在年 2 月 2019年和後續的幾個月內啟用、 威脅智慧功能會被新增至 ATP。此外，如果您的組織目前沒有 ATP，您必須考量，新的選項包括 ATP 計劃 1 和 ATP 計劃 2。如需詳細資訊，請參閱[Office 365 進階威脅保護計劃和價格](https://products.office.com/en-us/exchange/advance-threat-protection#pmg-allup-content)和[不同進階威脅保護 (ATP) 計劃中可用的功能](#feature-availability-across-advanced-threat-protection-atp-plans)。</span><span class="sxs-lookup"><span data-stu-id="11d37-p104">Beginning in February 2019 and rolling out over the next several months, Threat Intelligence capabilities are being added to ATP. In addition, if your organization does not currently have ATP, you'll have new options to consider, including ATP Plan 1 and ATP Plan 2. For more details, see [Office 365 Advanced Threat Protection plans and pricing](https://products.office.com/en-us/exchange/advance-threat-protection#pmg-allup-content) and [Feature availability across Advanced Threat Protection (ATP) plans](#feature-availability-across-advanced-threat-protection-atp-plans).</span></span>

<span data-ttu-id="11d37-132">ATP 中的新功能的相關資訊，請參閱[ATP 中的新功能](https://docs.microsoft.com/office365/securitycompliance/office-365-atp#new-features-are-continually-being-added-to-atp)。</span><span class="sxs-lookup"><span data-stu-id="11d37-132">For information about new features in ATP, see [New features in ATP](https://docs.microsoft.com/office365/securitycompliance/office-365-atp#new-features-are-continually-being-added-to-atp).</span></span>
  
## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a><span data-ttu-id="11d37-133">Office 365 進階威脅防護 (ATP) 的需求</span><span class="sxs-lookup"><span data-stu-id="11d37-133">Requirements for Office 365 Advanced Threat Protection (ATP)</span></span>

<span data-ttu-id="11d37-p105">ATP 可搭配任何 SMTP 郵件傳輸代理程式使用，例如 Microsoft Exchange Server 2013。如需 ATP 所支援的作業系統、網頁瀏覽器和語言的資訊，請參閱 [Exchange Online Protection 中的 Exchange 系統管理中心](https://go.microsoft.com/fwlink/p/?LinkId=282381)中的＜支援的瀏覽器＞和＜支援語言＞小節。</span><span class="sxs-lookup"><span data-stu-id="11d37-p105">ATP can be used with any SMTP mail transfer agent, such as Microsoft Exchange Server 2013. For information about the operating systems, web browsers, and languages that are supported by ATP, see the "Supported browsers" and "Supported languages" sections in [Exchange Admin Center in Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).</span></span>
  
## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a><span data-ttu-id="11d37-136">各進階威脅防護 (ATP) 計劃中可用的功能</span><span class="sxs-lookup"><span data-stu-id="11d37-136">Feature availability across Advanced Threat Protection (ATP) plans</span></span>

<span data-ttu-id="11d37-p106">每項功能如下所列。提到 Exchange Online 時，通常是指 Office 365 企業版服務系列。</span><span class="sxs-lookup"><span data-stu-id="11d37-p106">Each feature is listed below. When Exchange Online is mentioned, it typically refers to the Office 365 Enterprise service family.</span></span>
  
|<span data-ttu-id="11d37-139">**功能**</span><span class="sxs-lookup"><span data-stu-id="11d37-139">**Feature**</span></span>|<span data-ttu-id="11d37-140">**ATP 計劃 1**</span><span class="sxs-lookup"><span data-stu-id="11d37-140">**ATP Plan 1**</span></span><br><span data-ttu-id="11d37-141">（前身為 ATP 獨立版）</span><span class="sxs-lookup"><span data-stu-id="11d37-141">(formerly ATP standalone)</span></span>|<span data-ttu-id="11d37-142">**ATP 計劃 2**</span><span class="sxs-lookup"><span data-stu-id="11d37-142">**ATP Plan 2**</span></span><br><span data-ttu-id="11d37-143">（前身為威脅智慧</span><span class="sxs-lookup"><span data-stu-id="11d37-143">(formerly Threat Intelligence</span></span> <br><span data-ttu-id="11d37-144">獨立版）</span><span class="sxs-lookup"><span data-stu-id="11d37-144">standalone)</span></span> | <span data-ttu-id="11d37-145">Office 365 企業版 E5</span><span class="sxs-lookup"><span data-stu-id="11d37-145">Office 365 Enterprise E5</span></span>| 
|:-----|:-----|:-----|:-----|
| <span data-ttu-id="11d37-146">*設定、 保護及偵測*</span><span class="sxs-lookup"><span data-stu-id="11d37-146">*Configuration, Protection, and Detection*</span></span> | 
|<span data-ttu-id="11d37-147">安全附件</span><span class="sxs-lookup"><span data-stu-id="11d37-147">Safe Attachments</span></span> |<span data-ttu-id="11d37-148">是</span><span class="sxs-lookup"><span data-stu-id="11d37-148">Yes</span></span>|<span data-ttu-id="11d37-149">有</span><span class="sxs-lookup"><span data-stu-id="11d37-149">Yes</span></span> |<span data-ttu-id="11d37-150">可以</span><span class="sxs-lookup"><span data-stu-id="11d37-150">Yes</span></span>|
|<span data-ttu-id="11d37-151">安全連結</span><span class="sxs-lookup"><span data-stu-id="11d37-151">Safe Links</span></span> |<span data-ttu-id="11d37-152">是</span><span class="sxs-lookup"><span data-stu-id="11d37-152">Yes</span></span>|<span data-ttu-id="11d37-153">有</span><span class="sxs-lookup"><span data-stu-id="11d37-153">Yes</span></span> |<span data-ttu-id="11d37-154">可以</span><span class="sxs-lookup"><span data-stu-id="11d37-154">Yes</span></span> | 
|<span data-ttu-id="11d37-155">反網路釣魚原則</span><span class="sxs-lookup"><span data-stu-id="11d37-155">Anti-Phishing Policies</span></span> |<span data-ttu-id="11d37-156">是</span><span class="sxs-lookup"><span data-stu-id="11d37-156">Yes</span></span> |<span data-ttu-id="11d37-157">有</span><span class="sxs-lookup"><span data-stu-id="11d37-157">Yes</span></span> |<span data-ttu-id="11d37-158">可以</span><span class="sxs-lookup"><span data-stu-id="11d37-158">Yes</span></span> |
|<span data-ttu-id="11d37-159">SharePoint、 OneDrive 及 Microsoft 小組 ATP</span><span class="sxs-lookup"><span data-stu-id="11d37-159">ATP for SharePoint, OneDrive and Microsoft Teams</span></span> |<span data-ttu-id="11d37-160">是</span><span class="sxs-lookup"><span data-stu-id="11d37-160">Yes</span></span> |<span data-ttu-id="11d37-161">有</span><span class="sxs-lookup"><span data-stu-id="11d37-161">Yes</span></span> |<span data-ttu-id="11d37-162">可以</span><span class="sxs-lookup"><span data-stu-id="11d37-162">Yes</span></span>|
|<span data-ttu-id="11d37-163">小組中的安全連結</span><span class="sxs-lookup"><span data-stu-id="11d37-163">Safe Links in Teams</span></span> |<span data-ttu-id="11d37-164">是</span><span class="sxs-lookup"><span data-stu-id="11d37-164">Yes</span></span>|<span data-ttu-id="11d37-165">有</span><span class="sxs-lookup"><span data-stu-id="11d37-165">Yes</span></span> |<span data-ttu-id="11d37-166">可以</span><span class="sxs-lookup"><span data-stu-id="11d37-166">Yes</span></span> |
|<span data-ttu-id="11d37-167">即時報告</span><span class="sxs-lookup"><span data-stu-id="11d37-167">Real-time reports</span></span> |<span data-ttu-id="11d37-168">是</span><span class="sxs-lookup"><span data-stu-id="11d37-168">Yes</span></span> |<span data-ttu-id="11d37-169">有</span><span class="sxs-lookup"><span data-stu-id="11d37-169">Yes</span></span> |<span data-ttu-id="11d37-170">可以</span><span class="sxs-lookup"><span data-stu-id="11d37-170">Yes</span></span>|
|<span data-ttu-id="11d37-171">*自動化、 調查、 修復及教育*</span><span class="sxs-lookup"><span data-stu-id="11d37-171">*Automation, Investigation, Remediation and Education*</span></span> |
|<span data-ttu-id="11d37-172">威脅追蹤者</span><span class="sxs-lookup"><span data-stu-id="11d37-172">Threat Trackers</span></span> |<span data-ttu-id="11d37-173">否</span><span class="sxs-lookup"><span data-stu-id="11d37-173">No</span></span> |<span data-ttu-id="11d37-174">是</span><span class="sxs-lookup"><span data-stu-id="11d37-174">Yes</span></span> |<span data-ttu-id="11d37-175">可以</span><span class="sxs-lookup"><span data-stu-id="11d37-175">Yes</span></span> |
|<span data-ttu-id="11d37-176">Explorer （進階威脅調查）</span><span class="sxs-lookup"><span data-stu-id="11d37-176">Explorer (advanced threat investigation)</span></span> |<span data-ttu-id="11d37-177">否</span><span class="sxs-lookup"><span data-stu-id="11d37-177">No</span></span> |<span data-ttu-id="11d37-178">是</span><span class="sxs-lookup"><span data-stu-id="11d37-178">Yes</span></span> |<span data-ttu-id="11d37-179">可以</span><span class="sxs-lookup"><span data-stu-id="11d37-179">Yes</span></span> |
|<span data-ttu-id="11d37-180">將正在調查自動化及回應</span><span class="sxs-lookup"><span data-stu-id="11d37-180">Automated investigation and response</span></span>  |<span data-ttu-id="11d37-181">否</span><span class="sxs-lookup"><span data-stu-id="11d37-181">No</span></span> |<span data-ttu-id="11d37-182">是</span><span class="sxs-lookup"><span data-stu-id="11d37-182">Yes</span></span> |<span data-ttu-id="11d37-183">可以</span><span class="sxs-lookup"><span data-stu-id="11d37-183">Yes</span></span> |
|<span data-ttu-id="11d37-184">攻擊模擬器</span><span class="sxs-lookup"><span data-stu-id="11d37-184">Attack Simulator</span></span> |<span data-ttu-id="11d37-185">否</span><span class="sxs-lookup"><span data-stu-id="11d37-185">No</span></span> |<span data-ttu-id="11d37-186">是</span><span class="sxs-lookup"><span data-stu-id="11d37-186">Yes</span></span> |<span data-ttu-id="11d37-187">可以</span><span class="sxs-lookup"><span data-stu-id="11d37-187">Yes</span></span> |

   
## <a name="advanced-threat-protection-atp-capabilities"></a><span data-ttu-id="11d37-188">進階威脅防護 (ATP) 功能</span><span class="sxs-lookup"><span data-stu-id="11d37-188">Advanced Threat Protection (ATP) Capabilities</span></span>

### <a name="safe-attachments"></a><span data-ttu-id="11d37-189">安全附件</span><span class="sxs-lookup"><span data-stu-id="11d37-189">Safe Attachments</span></span>

<span data-ttu-id="11d37-p107">[ATP 安全附件](https://docs.microsoft.com/office365/securitycompliance/atp-safe-attachments)提供保護，避免未知的惡意程式碼及病毒，並提供零時差保護功能可保護您的訊息系統。所有的訊息與附件沒有已知的病毒/惡意程式碼簽章會路由傳送給其中 ATP 會使用各種機器學習與分析的技術來偵測惡意的特殊環境。如果偵測不到任何可疑的活動時，郵件已傳遞至信箱的發行。</span><span class="sxs-lookup"><span data-stu-id="11d37-p107">[ATP Safe Attachments](https://docs.microsoft.com/office365/securitycompliance/atp-safe-attachments) protects against unknown malware and viruses, and provides zero-day protection to safeguard your messaging system. All messages and attachments that don't have a known virus/malware signature are routed to a special environment where ATP uses a variety of machine learning and analysis techniques to detect malicious intent. If no suspicious activity is detected, the message is released for delivery to the mailbox.</span></span> 

### <a name="safe-links"></a><span data-ttu-id="11d37-193">安全連結</span><span class="sxs-lookup"><span data-stu-id="11d37-193">Safe Links</span></span>

<span data-ttu-id="11d37-p108">[ATP 安全連結](https://docs.microsoft.com/Office365/SecurityCompliance/atp-safe-links)功能主動會從一則訊息或 Office 文件中的惡意 Url 保護您的使用者。保護仍會保留每次他們按一下連結，如時可以存取良好的連結以動態方式會封鎖惡意的連結。</span><span class="sxs-lookup"><span data-stu-id="11d37-p108">The [ATP Safe Links](https://docs.microsoft.com/Office365/SecurityCompliance/atp-safe-links) feature proactively protects your users from malicious URLs in a message or in an Office document. The protection remains every time they click the link, as malicious links are dynamically blocked while good links can be accessed.</span></span>

### <a name="anti-phishing-policies"></a><span data-ttu-id="11d37-196">反網路釣魚原則</span><span class="sxs-lookup"><span data-stu-id="11d37-196">Anti-phishing policies</span></span>

<span data-ttu-id="11d37-p109">[ATP 反網路釣魚](https://docs.microsoft.com/office365/securitycompliance/atp-anti-phishing)會檢查內送郵件訊息可能是網路釣魚嘗試的指標。涵蓋使用者的內送郵件評估的多部機器學習分析訊息的模型 ATP 原則 （安全附件、 安全的連結或反網路釣魚），並採取適當的動作，根據設定的原則。</span><span class="sxs-lookup"><span data-stu-id="11d37-p109">[ATP anti-phishing](https://docs.microsoft.com/office365/securitycompliance/atp-anti-phishing) checks incoming messages for indicators that a message might be a phishing attempt. When users are covered by ATP policies (safe attachments, safe links or anti-phishing), incoming messages are evaluated by multiple machine learning models that analyze messages and the appropriate action is taken, based on the configured policies.</span></span>
  
### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a><span data-ttu-id="11d37-199">適用於 SharePoint、OneDrive 及 Microsoft Teams 的 ATP</span><span class="sxs-lookup"><span data-stu-id="11d37-199">ATP for SharePoint, OneDrive, and Microsoft Teams</span></span>

<span data-ttu-id="11d37-200">[SharePoint、 OneDrive 及 Microsoft 小組 ATP](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams)協助偵測和封鎖識別為惡意小組網站和文件庫中的檔案。</span><span class="sxs-lookup"><span data-stu-id="11d37-200">[ATP for SharePoint, OneDrive, and Microsoft Teams](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams)  helps detect and block files that are identified as malicious in team sites and document libraries.</span></span>

### <a name="real-time-reports"></a><span data-ttu-id="11d37-201">即時報告</span><span class="sxs-lookup"><span data-stu-id="11d37-201">Real-time reports</span></span>

<span data-ttu-id="11d37-p110">監視功能可在 Office 365 安全性 & 規範中心包括[提供及即時報告](https://docs.microsoft.com/office365/securitycompliance/view-reports-for-atp)可讓您以專注於高優先順序的問題，例如安全性攻擊的安全性和規範系統管理員或增加可疑的活動。除了反白顯示問題區域、 智慧報表及前瞻包括建議及檢視及探索資料及也採取快速連結。</span><span class="sxs-lookup"><span data-stu-id="11d37-p110">Monitoring capabilities available in the Office 365 Security & Compliance Center include [real-time reports and insights](https://docs.microsoft.com/office365/securitycompliance/view-reports-for-atp) that enable your security and compliance administrators to focus on high-priority issues, such as security attacks or increased suspicious activity. In addition to highlighting problem areas, smart reports and insights include recommendations and links to view and explore data and also take quick actions.</span></span> 
  
### <a name="threat-trackers"></a><span data-ttu-id="11d37-204">威脅追蹤者</span><span class="sxs-lookup"><span data-stu-id="11d37-204">Threat Trackers</span></span>

<span data-ttu-id="11d37-205">[威脅追蹤者](https://docs.microsoft.com/office365/securitycompliance/threat-trackers)為資訊性 widget 及授權的使用者提供 cybersecurity 問題可能會影響您的組織上的智慧的檢視。</span><span class="sxs-lookup"><span data-stu-id="11d37-205">[Threat Trackers](https://docs.microsoft.com/office365/securitycompliance/threat-trackers) are informative widgets and views that provide authorized users with intelligence on cybersecurity issues that might impact your organization.</span></span>

### <a name="explorer"></a><span data-ttu-id="11d37-206">瀏覽器</span><span class="sxs-lookup"><span data-stu-id="11d37-206">Explorer</span></span>

<span data-ttu-id="11d37-p111">[瀏覽器](https://docs.microsoft.com/office365/securitycompliance/use-explorer-in-security-and-compliance)（也稱為威脅 Explorer） 是即時報告可讓授權的使用者來識別和分析最近的威脅。根據預設，這份報告顯示資料的過去 7 天;不過，可以修改檢視顯示過去 30 天的資料。</span><span class="sxs-lookup"><span data-stu-id="11d37-p111">[Explorer](https://docs.microsoft.com/office365/securitycompliance/use-explorer-in-security-and-compliance) (also referred to as Threat Explorer) is a real-time report that enables authorized users to identify and analyze recent threats. By default, this report shows data for the past 7 days; however, views can be modified to show data for the past 30 days.</span></span> 

### <a name="attack-simulator"></a><span data-ttu-id="11d37-209">攻擊模擬器</span><span class="sxs-lookup"><span data-stu-id="11d37-209">Attack Simulator</span></span>
  
<span data-ttu-id="11d37-p112">[攻擊模擬器](https://docs.microsoft.com/office365/SecurityCompliance/attack-simulator)可讓組織中執行真實感化的攻擊案例的授權的使用者。數個不同的攻擊可用，包括顯示名稱矛網路釣魚攻擊、 密碼噴灑攻擊，與暴力密碼攻擊。</span><span class="sxs-lookup"><span data-stu-id="11d37-p112">[Attack Simulator](https://docs.microsoft.com/office365/SecurityCompliance/attack-simulator) enables authorized users to run realistic attack scenarios in your organization. Several different kinds of attacks are available, including a display name spear-phishing attack, a password-spray attack, and a brute-force password attack.</span></span>