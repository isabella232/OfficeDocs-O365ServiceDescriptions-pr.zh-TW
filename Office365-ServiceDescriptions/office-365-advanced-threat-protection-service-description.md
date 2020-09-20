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
ms.openlocfilehash: 3a611a3a7158586010f877bd88d0ec21aecc78f4
ms.sourcegitcommit: 5bad2698c44963874c993181ef7f2e468ea7fb16
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/19/2020
ms.locfileid: "48134040"
---
# <a name="office-365-advanced-threat-protection-service-description"></a><span data-ttu-id="e7e40-103">Office 365 進階威脅防護服務說明</span><span class="sxs-lookup"><span data-stu-id="e7e40-103">Office 365 Advanced Threat Protection service description</span></span>

<span data-ttu-id="e7e40-104">Microsoft Office 365 Advanced 威脅防護 (ATP) 是雲端式的電子郵件篩選服務，可協助您的組織抵禦未知的惡意程式碼和病毒，方法是提供強健的零日保護，並包含即時保護組織不受有害連結的功能。</span><span class="sxs-lookup"><span data-stu-id="e7e40-104">Microsoft Office 365 Advanced Threat Protection (ATP) is a cloud-based email filtering service that helps protect your organization against unknown malware and viruses by providing robust zero-day protection, and includes features to safeguard your organization from harmful links in real time.</span></span> <span data-ttu-id="e7e40-105">ATP 具有豐富報告和 URL 追蹤功能，可讓系統管理員深入了解組織中發生的攻擊的類型。</span><span class="sxs-lookup"><span data-stu-id="e7e40-105">ATP has rich reporting and URL trace capabilities that give administrators insight into the kind of attacks happening in your organization.</span></span>

<span data-ttu-id="e7e40-106">下列是您可以使用 ATP 來保護郵件的主要方法：</span><span class="sxs-lookup"><span data-stu-id="e7e40-106">The following are the primary ways you can use ATP for message protection:</span></span>

- <span data-ttu-id="e7e40-107">在 Office 365 ATP 僅篩選案例中，ATP 會針對內部部署 Exchange Server 環境或任何其他內部部署 SMTP 電子郵件解決方案，提供雲端式電子郵件保護。</span><span class="sxs-lookup"><span data-stu-id="e7e40-107">In an Office 365 ATP filtering-only scenario, ATP provides cloud-based email protection for your on-premises Exchange Server environment or any other on-premises SMTP email solution.</span></span>

- <span data-ttu-id="e7e40-108">您可以啟用 Office 365 ATP 來保護 Exchange Online 雲端託管信箱。</span><span class="sxs-lookup"><span data-stu-id="e7e40-108">Office 365 ATP can be enabled to protect Exchange Online cloud-hosted mailboxes.</span></span> <span data-ttu-id="e7e40-109">若要深入瞭解 Exchange Online，請參閱 [Exchange online 服務說明](exchange-online-service-description/exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="e7e40-109">To learn more about Exchange Online, see the [Exchange Online service description](exchange-online-service-description/exchange-online-service-description.md).</span></span>

- <span data-ttu-id="e7e40-110">在混合部署中，當您混合使用內部部署及雲端信箱並使用 Exchange Online Protection 來進行輸入電子郵件篩選時，可將 ATP 設定為保護您的郵件環境與控制郵件路由。</span><span class="sxs-lookup"><span data-stu-id="e7e40-110">In a hybrid deployment, ATP can be configured to protect your messaging environment and control mail routing when you have a mix of on-premises and cloud mailboxes with Exchange Online Protection for inbound email filtering.</span></span>

## <a name="office-365-advanced-threat-protection-atp-availability"></a><span data-ttu-id="e7e40-111">Office 365 進階威脅防護 (ATP) 可用性</span><span class="sxs-lookup"><span data-stu-id="e7e40-111">Office 365 Advanced Threat Protection (ATP) availability</span></span>

<span data-ttu-id="e7e40-112">Office 365 ATP 方案 2 包含在 Office 365 E5、Office 365 A5 和 Microsoft 365 E5 中。</span><span class="sxs-lookup"><span data-stu-id="e7e40-112">Office 365 ATP Plan 2 is included in Office 365 E5, Office 365 A5, and Microsoft 365 E5.</span></span> <span data-ttu-id="e7e40-113">Office 365 ATP 方案 1 包含在 Microsoft 365 商務進階版中。</span><span class="sxs-lookup"><span data-stu-id="e7e40-113">Office 365 ATP Plan 1 is included in Microsoft 365 Business Premium.</span></span>

<span data-ttu-id="e7e40-114">您可以將 ATP 新增至下列 Exchange 和 Microsoft 365 訂閱計畫：</span><span class="sxs-lookup"><span data-stu-id="e7e40-114">You can add ATP to the following Exchange and Microsoft 365 subscription plans:</span></span>

- <span data-ttu-id="e7e40-115">Exchange Online Plan 1</span><span class="sxs-lookup"><span data-stu-id="e7e40-115">Exchange Online Plan 1</span></span>

- <span data-ttu-id="e7e40-116">Exchange Online Plan 2</span><span class="sxs-lookup"><span data-stu-id="e7e40-116">Exchange Online Plan 2</span></span>

- <span data-ttu-id="e7e40-117">Exchange Online Kiosk</span><span class="sxs-lookup"><span data-stu-id="e7e40-117">Exchange Online Kiosk</span></span>

- <span data-ttu-id="e7e40-118">Exchange Online Protection</span><span class="sxs-lookup"><span data-stu-id="e7e40-118">Exchange Online Protection</span></span>

- <span data-ttu-id="e7e40-119">Microsoft 365 商務基本版</span><span class="sxs-lookup"><span data-stu-id="e7e40-119">Microsoft 365 Business Basic</span></span>

- <span data-ttu-id="e7e40-120">Microsoft 365 商務標準版</span><span class="sxs-lookup"><span data-stu-id="e7e40-120">Microsoft 365 Business Standard</span></span>

- <span data-ttu-id="e7e40-121">Office 365 企業版 E1</span><span class="sxs-lookup"><span data-stu-id="e7e40-121">Office 365 Enterprise E1</span></span>

- <span data-ttu-id="e7e40-122">Office 365 企業版 E3</span><span class="sxs-lookup"><span data-stu-id="e7e40-122">Office 365 Enterprise E3</span></span>

- <span data-ttu-id="e7e40-123">Office 365 企業版 F3</span><span class="sxs-lookup"><span data-stu-id="e7e40-123">Office 365 Enterprise F3</span></span>

- <span data-ttu-id="e7e40-124">Office 365 A1</span><span class="sxs-lookup"><span data-stu-id="e7e40-124">Office 365 A1</span></span>

- <span data-ttu-id="e7e40-125">Office 365 A3</span><span class="sxs-lookup"><span data-stu-id="e7e40-125">Office 365 A3</span></span>

<span data-ttu-id="e7e40-126">若要購買 Office 365 進階威脅防護，請參閱 [Office 365 進階威脅防護](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content)。</span><span class="sxs-lookup"><span data-stu-id="e7e40-126">To buy Office 365 Advanced Threat Protection, see [Office 365 Advanced Threat Protection](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content).</span></span>

<span data-ttu-id="e7e40-127">若要跨方案比較功能，請參閱 [強大的工具來支援您的企業](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) ，並 [使用 Microsoft 365 轉換您的企業](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans)。</span><span class="sxs-lookup"><span data-stu-id="e7e40-127">To compare features across plans, see [Powerful tools to support your enterprise](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) and [Transform your enterprise with Microsoft 365](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans).</span></span>

## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a><span data-ttu-id="e7e40-128">Office 365 進階威脅防護 (ATP) 的新增功能</span><span class="sxs-lookup"><span data-stu-id="e7e40-128">What's new in Office 365 Advanced Threat Protection (ATP)</span></span>

<span data-ttu-id="e7e40-129">我們正在繼續將新功能新增至 Office 365 ATP。</span><span class="sxs-lookup"><span data-stu-id="e7e40-129">We are continuing to add new features to Office 365 ATP.</span></span> <span data-ttu-id="e7e40-130">若要深入瞭解在一般) 中的 ATP (或 Microsoft 365 的新功能，請參閱下列資源：</span><span class="sxs-lookup"><span data-stu-id="e7e40-130">To learn more about new features coming to ATP (or Microsoft 365 in general), see the following resources:</span></span>

- [<span data-ttu-id="e7e40-131">Microsoft 365 藍圖</span><span class="sxs-lookup"><span data-stu-id="e7e40-131">Microsoft 365 Roadmap</span></span>](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [<span data-ttu-id="e7e40-132">Office 365 ATP 中的新功能</span><span class="sxs-lookup"><span data-stu-id="e7e40-132">What's new in Office 365 ATP</span></span>](https://docs.microsoft.com/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a><span data-ttu-id="e7e40-133">Office 365 進階威脅防護 (ATP) 的需求</span><span class="sxs-lookup"><span data-stu-id="e7e40-133">Requirements for Office 365 Advanced Threat Protection (ATP)</span></span>

<span data-ttu-id="e7e40-134">ATP 可搭配任何 SMTP 郵件傳輸代理程式使用，例如 Microsoft Exchange Server。</span><span class="sxs-lookup"><span data-stu-id="e7e40-134">ATP can be used with any SMTP mail transfer agent, such as Microsoft Exchange Server.</span></span> <span data-ttu-id="e7e40-135">如需 ATP 所支援的作業系統、網頁瀏覽器及語言的相關資訊，請參閱 [Exchange Online Protection 中 exchange 系統管理中心](https://go.microsoft.com/fwlink/p/?LinkId=282381)的「支援的瀏覽器」和「支援的語言」一節。</span><span class="sxs-lookup"><span data-stu-id="e7e40-135">For information about the operating systems, web browsers, and languages that are supported by ATP, see the "Supported browsers" and "Supported languages" sections in [Exchange admin center in Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).</span></span>

## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a><span data-ttu-id="e7e40-136">各進階威脅防護 (ATP) 計劃中可用的功能</span><span class="sxs-lookup"><span data-stu-id="e7e40-136">Feature availability across Advanced Threat Protection (ATP) plans</span></span>

<span data-ttu-id="e7e40-p106">每項功能如下所列。提到 Exchange Online 時，通常是指 Office 365 企業版服務系列。</span><span class="sxs-lookup"><span data-stu-id="e7e40-p106">Each feature is listed below. When Exchange Online is mentioned, it typically refers to the Office 365 Enterprise service family.</span></span>

|<span data-ttu-id="e7e40-139">**功能**</span><span class="sxs-lookup"><span data-stu-id="e7e40-139">**Feature**</span></span>|<span data-ttu-id="e7e40-140">**ATP 方案1**</span><span class="sxs-lookup"><span data-stu-id="e7e40-140">**ATP Plan 1**</span></span><br><span data-ttu-id="e7e40-141"> (先前的 ATP 獨立) </span><span class="sxs-lookup"><span data-stu-id="e7e40-141">(formerly ATP standalone)</span></span>|<span data-ttu-id="e7e40-142">**ATP 方案2**</span><span class="sxs-lookup"><span data-stu-id="e7e40-142">**ATP Plan 2**</span></span><br><span data-ttu-id="e7e40-143"> (先前的威脅情報</span><span class="sxs-lookup"><span data-stu-id="e7e40-143">(formerly Threat Intelligence</span></span> <br><span data-ttu-id="e7e40-144">獨立) </span><span class="sxs-lookup"><span data-stu-id="e7e40-144">standalone)</span></span>| <span data-ttu-id="e7e40-145">Microsoft 365 E5/E5 Security</span><span class="sxs-lookup"><span data-stu-id="e7e40-145">Microsoft 365 E5 / E5 Security</span></span>|
|:-----|:-----|:-----|:-----|
|<span data-ttu-id="e7e40-146">*設定、保護及偵測*</span><span class="sxs-lookup"><span data-stu-id="e7e40-146">*Configuration, protection, and detection*</span></span>|
|[<span data-ttu-id="e7e40-147">安全附件</span><span class="sxs-lookup"><span data-stu-id="e7e40-147">Safe Attachments</span></span>](#safe-attachments)|<span data-ttu-id="e7e40-148">是</span><span class="sxs-lookup"><span data-stu-id="e7e40-148">Yes</span></span>|<span data-ttu-id="e7e40-149">是</span><span class="sxs-lookup"><span data-stu-id="e7e40-149">Yes</span></span>|<span data-ttu-id="e7e40-150">是</span><span class="sxs-lookup"><span data-stu-id="e7e40-150">Yes</span></span>|
|<span data-ttu-id="e7e40-151">小組中的安全附件</span><span class="sxs-lookup"><span data-stu-id="e7e40-151">Safe Attachments in Teams</span></span>|<span data-ttu-id="e7e40-152">是</span><span class="sxs-lookup"><span data-stu-id="e7e40-152">Yes</span></span>|<span data-ttu-id="e7e40-153">是</span><span class="sxs-lookup"><span data-stu-id="e7e40-153">Yes</span></span>|<span data-ttu-id="e7e40-154">是</span><span class="sxs-lookup"><span data-stu-id="e7e40-154">Yes</span></span>|
|[<span data-ttu-id="e7e40-155">安全連結</span><span class="sxs-lookup"><span data-stu-id="e7e40-155">Safe Links</span></span>](#safe-links)|<span data-ttu-id="e7e40-156">是</span><span class="sxs-lookup"><span data-stu-id="e7e40-156">Yes</span></span>|<span data-ttu-id="e7e40-157">是</span><span class="sxs-lookup"><span data-stu-id="e7e40-157">Yes</span></span>|<span data-ttu-id="e7e40-158">是</span><span class="sxs-lookup"><span data-stu-id="e7e40-158">Yes</span></span>|
|[<span data-ttu-id="e7e40-159">安全檔</span><span class="sxs-lookup"><span data-stu-id="e7e40-159">Safe Documents</span></span>](#safe-documents)|<span data-ttu-id="e7e40-160">否</span><span class="sxs-lookup"><span data-stu-id="e7e40-160">No</span></span>|<span data-ttu-id="e7e40-161">否</span><span class="sxs-lookup"><span data-stu-id="e7e40-161">No</span></span>|<span data-ttu-id="e7e40-162">是</span><span class="sxs-lookup"><span data-stu-id="e7e40-162">Yes</span></span>|
|<span data-ttu-id="e7e40-163">Teams 中的安全連結</span><span class="sxs-lookup"><span data-stu-id="e7e40-163">Safe Links in Teams</span></span>|<span data-ttu-id="e7e40-164">是</span><span class="sxs-lookup"><span data-stu-id="e7e40-164">Yes</span></span>|<span data-ttu-id="e7e40-165">是</span><span class="sxs-lookup"><span data-stu-id="e7e40-165">Yes</span></span>|<span data-ttu-id="e7e40-166">是</span><span class="sxs-lookup"><span data-stu-id="e7e40-166">Yes</span></span>|
|[<span data-ttu-id="e7e40-167">SharePoint、OneDrive 和 Microsoft 小組的 ATP</span><span class="sxs-lookup"><span data-stu-id="e7e40-167">ATP for SharePoint, OneDrive and Microsoft Teams</span></span>](#atp-for-sharepoint-onedrive-and-microsoft-teams)|<span data-ttu-id="e7e40-168">是</span><span class="sxs-lookup"><span data-stu-id="e7e40-168">Yes</span></span>|<span data-ttu-id="e7e40-169">是</span><span class="sxs-lookup"><span data-stu-id="e7e40-169">Yes</span></span>|<span data-ttu-id="e7e40-170">是</span><span class="sxs-lookup"><span data-stu-id="e7e40-170">Yes</span></span>|
|[<span data-ttu-id="e7e40-171">防網路釣魚原則</span><span class="sxs-lookup"><span data-stu-id="e7e40-171">Anti-phishing policies</span></span>](#anti-phishing-policies)|<span data-ttu-id="e7e40-172">是</span><span class="sxs-lookup"><span data-stu-id="e7e40-172">Yes</span></span>|<span data-ttu-id="e7e40-173">是</span><span class="sxs-lookup"><span data-stu-id="e7e40-173">Yes</span></span>|<span data-ttu-id="e7e40-174">是</span><span class="sxs-lookup"><span data-stu-id="e7e40-174">Yes</span></span>|
|[<span data-ttu-id="e7e40-175">即時報告</span><span class="sxs-lookup"><span data-stu-id="e7e40-175">Real-time reports</span></span>](#real-time-reports)|<span data-ttu-id="e7e40-176">是</span><span class="sxs-lookup"><span data-stu-id="e7e40-176">Yes</span></span>|<span data-ttu-id="e7e40-177">是</span><span class="sxs-lookup"><span data-stu-id="e7e40-177">Yes</span></span>|<span data-ttu-id="e7e40-178">是</span><span class="sxs-lookup"><span data-stu-id="e7e40-178">Yes</span></span>|
|<span data-ttu-id="e7e40-179">*自動化、調查、修正及教育*</span><span class="sxs-lookup"><span data-stu-id="e7e40-179">*Automation, investigation, remediation, and education*</span></span>|
|[<span data-ttu-id="e7e40-180">威脅追蹤工具</span><span class="sxs-lookup"><span data-stu-id="e7e40-180">Threat Trackers</span></span>](#threat-trackers)|<span data-ttu-id="e7e40-181">否</span><span class="sxs-lookup"><span data-stu-id="e7e40-181">No</span></span>|<span data-ttu-id="e7e40-182">是</span><span class="sxs-lookup"><span data-stu-id="e7e40-182">Yes</span></span>|<span data-ttu-id="e7e40-183">是</span><span class="sxs-lookup"><span data-stu-id="e7e40-183">Yes</span></span>|
|<span data-ttu-id="e7e40-184">威脅調查 (高級威脅調查) </span><span class="sxs-lookup"><span data-stu-id="e7e40-184">Threat investigation  (advanced threat investigation)</span></span>|[<span data-ttu-id="e7e40-185">即時偵測</span><span class="sxs-lookup"><span data-stu-id="e7e40-185">Real-time detections</span></span>](#real-time-detections)|[<span data-ttu-id="e7e40-186">總管</span><span class="sxs-lookup"><span data-stu-id="e7e40-186">Explorer</span></span>](#explorer)|[<span data-ttu-id="e7e40-187">總管</span><span class="sxs-lookup"><span data-stu-id="e7e40-187">Explorer</span></span>](#explorer)|
|[<span data-ttu-id="e7e40-188">自動化的事件回應</span><span class="sxs-lookup"><span data-stu-id="e7e40-188">Automated incident response</span></span>](#automated-incident-response)|<span data-ttu-id="e7e40-189">否</span><span class="sxs-lookup"><span data-stu-id="e7e40-189">No</span></span>|<span data-ttu-id="e7e40-190">是</span><span class="sxs-lookup"><span data-stu-id="e7e40-190">Yes</span></span>|<span data-ttu-id="e7e40-191">是</span><span class="sxs-lookup"><span data-stu-id="e7e40-191">Yes</span></span>|
|[<span data-ttu-id="e7e40-192">攻擊模擬器</span><span class="sxs-lookup"><span data-stu-id="e7e40-192">Attack Simulator</span></span>](#attack-simulator)|<span data-ttu-id="e7e40-193">否</span><span class="sxs-lookup"><span data-stu-id="e7e40-193">No</span></span>|<span data-ttu-id="e7e40-194">是</span><span class="sxs-lookup"><span data-stu-id="e7e40-194">Yes</span></span>|<span data-ttu-id="e7e40-195">是</span><span class="sxs-lookup"><span data-stu-id="e7e40-195">Yes</span></span>|

> [!TIP]
> <span data-ttu-id="e7e40-196">需要 Office 365 ATP 方案1與方案2之間的差異的可供下載的清單嗎？</span><span class="sxs-lookup"><span data-stu-id="e7e40-196">Want a downloadable list of differences between Office 365 ATP Plan 1 and Plan 2?</span></span> <span data-ttu-id="e7e40-197">[取得 PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)。</span><span class="sxs-lookup"><span data-stu-id="e7e40-197">[Get the PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).</span></span> 

## <a name="advanced-threat-protection-atp-capabilities"></a><span data-ttu-id="e7e40-198">進階威脅防護 (ATP) 功能</span><span class="sxs-lookup"><span data-stu-id="e7e40-198">Advanced Threat Protection (ATP) capabilities</span></span>

### <a name="safe-attachments"></a><span data-ttu-id="e7e40-199">安全附件</span><span class="sxs-lookup"><span data-stu-id="e7e40-199">Safe Attachments</span></span>

<span data-ttu-id="e7e40-200">[ATP 安全附件](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments) 可防止未知的惡意程式碼和病毒，並提供零天的保護來保護您的郵件系統。</span><span class="sxs-lookup"><span data-stu-id="e7e40-200">[ATP Safe Attachments](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments) protects against unknown malware and viruses, and provides zero-day protection to safeguard your messaging system.</span></span> <span data-ttu-id="e7e40-201">所有沒有已知病毒/惡意軟體簽章的訊息與附件將被路由傳送至特殊的環境，其中 ATP 會使用不同的機器學習與分析技術來偵測惡意的意圖。</span><span class="sxs-lookup"><span data-stu-id="e7e40-201">All messages and attachments that don't have a known virus/malware signature are routed to a special environment where ATP uses a variety of machine learning and analysis techniques to detect malicious intent.</span></span> <span data-ttu-id="e7e40-202">如果未偵測到可疑活動，即會釋出訊息傳遞到信箱。</span><span class="sxs-lookup"><span data-stu-id="e7e40-202">If no suspicious activity is detected, the message is released for delivery to the mailbox.</span></span>

> [!NOTE]
> <span data-ttu-id="e7e40-203">ATP 安全附件掃描會在您的 Office 365 資料所在的同一個區域中進行。</span><span class="sxs-lookup"><span data-stu-id="e7e40-203">ATP Safe Attachments scanning takes place in the same region where your Office 365 data resides.</span></span> <span data-ttu-id="e7e40-204">如需資料中心地理位置的詳細資訊，請參閱[您的資料位於何處？](https://products.office.com/where-is-your-data-located?geo=All)</span><span class="sxs-lookup"><span data-stu-id="e7e40-204">For more information about data center geography, see [Where is your data located?](https://products.office.com/where-is-your-data-located?geo=All)</span></span>

### <a name="safe-links"></a><span data-ttu-id="e7e40-205">安全連結</span><span class="sxs-lookup"><span data-stu-id="e7e40-205">Safe Links</span></span>

<span data-ttu-id="e7e40-206">[ATP 安全連結](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links)功能主動保護您的使用者免受郵件中或 Office 檔中的惡意 URLs。</span><span class="sxs-lookup"><span data-stu-id="e7e40-206">The [ATP Safe Links](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links) feature proactively protects your users from malicious URLs in a message or in an Office document.</span></span> <span data-ttu-id="e7e40-207">因為可動態封鎖惡意連結，允許存取無害連結，所以每次使用者選取連結時都能受到持續保護。</span><span class="sxs-lookup"><span data-stu-id="e7e40-207">The protection remains every time they select the link, as malicious links are dynamically blocked while good links can be accessed.</span></span>

<span data-ttu-id="e7e40-208">安全連結可用於下列應用程式中的 URLs：</span><span class="sxs-lookup"><span data-stu-id="e7e40-208">Safe Links is available for URLs in the following apps:</span></span>

- <span data-ttu-id="e7e40-209">Microsoft 365 Windows 或 Mac 版企業版應用程式</span><span class="sxs-lookup"><span data-stu-id="e7e40-209">Microsoft 365 Apps for enterprise on Windows or Mac</span></span>

- <span data-ttu-id="e7e40-210">Office for web (Word、網頁版 Excel、網頁的 PowerPoint，及 OneNote 網頁) </span><span class="sxs-lookup"><span data-stu-id="e7e40-210">Office for the web (Word for the web, Excel for the web, PowerPoint for the web, and OneNote for the web)</span></span>

- <span data-ttu-id="e7e40-211">Windows 上的 Word、Excel 及 PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e7e40-211">Word, Excel, and PowerPoint on Windows</span></span>

- <span data-ttu-id="e7e40-212">Microsoft 小組通道和聊天</span><span class="sxs-lookup"><span data-stu-id="e7e40-212">Microsoft Teams channels and chats</span></span>

> [!NOTE]
> <span data-ttu-id="e7e40-213">使用者必須是 ATP 的授權，必須 <sup>\*</sup> 包含在 Atp 安全連結原則中，且必須在裝置上登入，以進行保護。</span><span class="sxs-lookup"><span data-stu-id="e7e40-213">Users must be licensed for ATP<sup>\*</sup>, must be included in ATP Safe Links policies, and must be signed in on their devices for protection to be in place.</span></span>
>
> <span data-ttu-id="e7e40-214"><sup>\*</sup> 若為全組織的 ATP 授權 (例如，ATP_ENTERPRISE_FACULTY) ，您不需要將 ATP 授權指派給個別使用者。</span><span class="sxs-lookup"><span data-stu-id="e7e40-214"><sup>\*</sup> For organization-wide ATP licenses (for example, ATP_ENTERPRISE_FACULTY), you don't need to assign ATP licenses to individual users.</span></span>
>
> <span data-ttu-id="e7e40-215">如需有關 ATP 安全連結保護的詳細資訊，請參閱 [Atp 安全連結如何與 Office 檔中的 URLs 搭配運作](https://docs.microsoft.com/microsoft-365/security/office-365-security/how-atp-safe-links-works#how-atp-safe-links-works-with-urls-in-office-documents)。</span><span class="sxs-lookup"><span data-stu-id="e7e40-215">For more information about ATP Safe Links protection, see [How ATP Safe Links works with URLs in Office documents](https://docs.microsoft.com/microsoft-365/security/office-365-security/how-atp-safe-links-works#how-atp-safe-links-works-with-urls-in-office-documents).</span></span>

### <a name="safe-documents"></a><span data-ttu-id="e7e40-216">安全檔</span><span class="sxs-lookup"><span data-stu-id="e7e40-216">Safe Documents</span></span>

<span data-ttu-id="e7e40-217">[ATP 安全](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs)檔功能使用「 [Microsoft Defender 高級威脅防護](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection)」來掃描在[受保護的檢視](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)中開啟的檔和檔案。</span><span class="sxs-lookup"><span data-stu-id="e7e40-217">The [ATP Safe Documents](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs) feature uses [Microsoft Defender Advanced Threat Protection](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) to scan documents and files that are opened in [Protected View](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653).</span></span>

<span data-ttu-id="e7e40-218">開始之前有哪些須知？</span><span class="sxs-lookup"><span data-stu-id="e7e40-218">What do you need to know before you begin?</span></span>

- <span data-ttu-id="e7e40-219">12730 Office 版本2004的使用者通常可使用安全檔， () 或更高！</span><span class="sxs-lookup"><span data-stu-id="e7e40-219">Safe Documents is now generally available to users with Office Version 2004 (12730.x) or greater!</span></span> <span data-ttu-id="e7e40-220">此功能預設為關閉，必須由安全性管理員啟用。</span><span class="sxs-lookup"><span data-stu-id="e7e40-220">This feature is off by default and will need to be enabled by the Security Administrator.</span></span>

- <span data-ttu-id="e7e40-221">此功能僅適用于使用 Microsoft 365 E5 或 Microsoft 365 E5 安全性授權 (未包含在 Office 365 ATP 計畫) 中的使用者。</span><span class="sxs-lookup"><span data-stu-id="e7e40-221">This feature is only available to users with the Microsoft 365 E5 or Microsoft 365 E5 Security license (not included in Office 365 ATP plans).</span></span>

- <span data-ttu-id="e7e40-222">Windows 上的 Word、Excel、PowerPoint 和 Visio，以及 iOS 和 Android 裝置上的 Office 應用程式</span><span class="sxs-lookup"><span data-stu-id="e7e40-222">Word, Excel, PowerPoint, and Visio on Windows, as well as Office apps on iOS and Android devices</span></span>

- <span data-ttu-id="e7e40-223">Microsoft 小組通道和聊天</span><span class="sxs-lookup"><span data-stu-id="e7e40-223">Microsoft Teams channels and chats</span></span>

> [!NOTE]
> <span data-ttu-id="e7e40-224">使用者必須是 Microsoft 365 E5 或 Microsoft 365 E5 Security 的授權 <sup>\*</sup> ，必須包含在 ATP 安全檔原則中，且必須在裝置上登入，以進行保護。</span><span class="sxs-lookup"><span data-stu-id="e7e40-224">Users must be licensed for Microsoft 365 E5 or Microsoft 365 E5 Security<sup>\*</sup>, must be included in ATP Safe Documents policies, and must be signed in on their devices for protection to be in place.</span></span>
>
> <span data-ttu-id="e7e40-225">如需 ATP 安全檔案保護的詳細資訊，請參閱 [Microsoft 365 E5 中的安全檔](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs)。</span><span class="sxs-lookup"><span data-stu-id="e7e40-225">For more information about ATP Safe Documents protection, see [Safe Documents in Microsoft 365 E5](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs).</span></span>

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a><span data-ttu-id="e7e40-226">適用於 SharePoint、OneDrive 及 Microsoft Teams 的 ATP</span><span class="sxs-lookup"><span data-stu-id="e7e40-226">ATP for SharePoint, OneDrive, and Microsoft Teams</span></span>

<span data-ttu-id="e7e40-227">[SharePoint、OneDrive 和 Microsoft 團隊的 ATP](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)  可協助偵測和封鎖在小組網站和文件庫中識別為惡意的檔案。</span><span class="sxs-lookup"><span data-stu-id="e7e40-227">[ATP for SharePoint, OneDrive, and Microsoft Teams](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)  helps detect and block files that are identified as malicious in team sites and document libraries.</span></span> <span data-ttu-id="e7e40-228">此外，在 Microsoft 小組通道和聊天中，現在還提供 ATP 安全連結保護。</span><span class="sxs-lookup"><span data-stu-id="e7e40-228">In addition, ATP Safe Links protection is now available in Microsoft Teams channels and chats.</span></span>

### <a name="anti-phishing-policies"></a><span data-ttu-id="e7e40-229">防網路釣魚原則</span><span class="sxs-lookup"><span data-stu-id="e7e40-229">Anti-phishing policies</span></span>

<span data-ttu-id="e7e40-230">[ATP 反網路釣魚](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing) 檢查內送郵件的指示，郵件可能是網路釣魚企圖。</span><span class="sxs-lookup"><span data-stu-id="e7e40-230">[ATP anti-phishing](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing) checks incoming messages for indicators that a message might be a phishing attempt.</span></span> <span data-ttu-id="e7e40-231">當使用者受 ATP 原則 (安全附件、安全連結或反網路釣魚) 保護時，系統會根據已設定的原則，以多個可分析郵件的電腦學習模型來評估傳入的郵件，並採取適當動作。</span><span class="sxs-lookup"><span data-stu-id="e7e40-231">When users are covered by ATP policies (Safe Attachments, Safe Links, or anti-phishing), incoming messages are evaluated by multiple machine learning models that analyze messages and the appropriate action is taken, based on the configured policies.</span></span>

### <a name="real-time-reports"></a><span data-ttu-id="e7e40-232">即時報告</span><span class="sxs-lookup"><span data-stu-id="e7e40-232">Real-time reports</span></span>

<span data-ttu-id="e7e40-233">安全性 & 合規性中心內可用的監控功能包括 [即時報告和深入](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp) 資訊，讓您的安全性和合規性系統管理員關注高優先順序的問題，例如安全性攻擊或增加的可疑活動。</span><span class="sxs-lookup"><span data-stu-id="e7e40-233">Monitoring capabilities available in the Security & Compliance Center include [real-time reports and insights](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp) that let your security and compliance administrators focus on high-priority issues, such as security attacks or increased suspicious activity.</span></span> <span data-ttu-id="e7e40-234">除了醒目提示問題之外，智慧報告和洞察力也包含建議和連結，以查看及流覽資料，也會快速採取動作。</span><span class="sxs-lookup"><span data-stu-id="e7e40-234">In addition to highlighting problem areas, smart reports and insights include recommendations and links to view and explore data and also take quick actions.</span></span>

### <a name="explorer"></a><span data-ttu-id="e7e40-235">總管</span><span class="sxs-lookup"><span data-stu-id="e7e40-235">Explorer</span></span>

<span data-ttu-id="e7e40-236">總管 (也稱為威脅總管) 是即時的報告，可讓授權的使用者識別並分析最近的威脅。</span><span class="sxs-lookup"><span data-stu-id="e7e40-236">Explorer (also referred to as Threat Explorer) is a real-time report that lets authorized users identify and analyze recent threats.</span></span> <span data-ttu-id="e7e40-237">根據預設，此報告會顯示過去 7 天的資料；不過，您可以修改檢視畫面以顯示過去 30 天的資料。</span><span class="sxs-lookup"><span data-stu-id="e7e40-237">By default, this report shows data for the past 7 days; however, views can be modified to show data for the past 30 days.</span></span>

<span data-ttu-id="e7e40-238">Explorer 包含一些視圖，例如電子郵件和內容) 、提交、網路釣魚和所有電子郵件的惡意程式碼 (。</span><span class="sxs-lookup"><span data-stu-id="e7e40-238">Explorer contains views, such as Malware (for email and content), Submissions, Phish, and All Email.</span></span> <span data-ttu-id="e7e40-239">若要查看 Explorer 如何與即時偵測相比較，請 [下載此 PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)。</span><span class="sxs-lookup"><span data-stu-id="e7e40-239">To see how Explorer compares with real-time detections, [download this PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).</span></span>

<span data-ttu-id="e7e40-240">如需 office 365 advanced 威脅防護方案 2) 和即時偵測 () 365 中的 Explorer (的詳細資訊，請參閱 [威脅 Explorer 和即時](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)偵測。</span><span class="sxs-lookup"><span data-stu-id="e7e40-240">For more information about Explorer (in Office 365 Advanced Threat Protection Plan 2) and real-time detections (in Office 365 Advanced Threat Protection Plan 1), see [Threat Explorer and real-time detections](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer).</span></span>

### <a name="real-time-detections"></a><span data-ttu-id="e7e40-241">即時偵測</span><span class="sxs-lookup"><span data-stu-id="e7e40-241">Real-time detections</span></span>

<span data-ttu-id="e7e40-242">即時偵測是即時的報告，可讓授權的使用者識別並分析最近的威脅。</span><span class="sxs-lookup"><span data-stu-id="e7e40-242">Real-time detections is a real-time report that lets authorized users identify and analyze recent threats.</span></span> <span data-ttu-id="e7e40-243">與 [總管] 類似，根據預設，此報告顯示過去 7 天的資料。</span><span class="sxs-lookup"><span data-stu-id="e7e40-243">Similar to Explorer, by default, this report shows data for the past 7 days.</span></span>

<span data-ttu-id="e7e40-244">即時偵測包含諸如電子郵件和內容) 、報送和網路釣魚的惡意程式碼 (的視圖。</span><span class="sxs-lookup"><span data-stu-id="e7e40-244">Real-time detections contain views, such as Malware (for email and content), Submissions, and Phish.</span></span> <span data-ttu-id="e7e40-245">若要查看即時檢測與瀏覽器的比較方式，請 [下載此 PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)。</span><span class="sxs-lookup"><span data-stu-id="e7e40-245">To see how real-time detections compare with Explorer, [download this PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).</span></span>

<span data-ttu-id="e7e40-246">如需 office 365 advanced 威脅防護方案 2) 和即時偵測 () 365 中的 Explorer (的詳細資訊，請參閱 [威脅 Explorer (和即時偵測) ](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)。</span><span class="sxs-lookup"><span data-stu-id="e7e40-246">For more information about Explorer (in Office 365 Advanced Threat Protection Plan 2) and real-time detections (in Office 365 Advanced Threat Protection Plan 1), see [Threat Explorer (and real-time detections)](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer).</span></span>

### <a name="threat-trackers"></a><span data-ttu-id="e7e40-247">威脅追蹤工具</span><span class="sxs-lookup"><span data-stu-id="e7e40-247">Threat Trackers</span></span>

<span data-ttu-id="e7e40-248">[威脅](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers) 追蹤器是資訊性的小元件和視圖，可讓授權的使用者在可能影響組織的 cybersecurity 問題上使用情報。</span><span class="sxs-lookup"><span data-stu-id="e7e40-248">[Threat Trackers](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers) are informative widgets and views that provide authorized users with intelligence on cybersecurity issues that might impact your organization.</span></span>

### <a name="automated-incident-response"></a><span data-ttu-id="e7e40-249">自動化的事件回應</span><span class="sxs-lookup"><span data-stu-id="e7e40-249">Automated incident response</span></span>

<span data-ttu-id="e7e40-250">[自動事件回應](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air) (OFFICE 365 ATP 方案2中可用的 AIR) 功能，可讓您執行自動化調查程式，以回應目前存在的已知威脅。</span><span class="sxs-lookup"><span data-stu-id="e7e40-250">[Automated incident response](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air) (AIR) capabilities available in Office 365 ATP Plan 2 enable you to run automated investigation processes in response to well known threats that exist today.</span></span> <span data-ttu-id="e7e40-251">透過自動化某些調查任務，您的安全性運作小組可以更有效率地運作。</span><span class="sxs-lookup"><span data-stu-id="e7e40-251">By automated certain investigation tasks, your security operations team can operate more efficiently and effectively.</span></span> <span data-ttu-id="e7e40-252">修正動作（如刪除惡意電子郵件訊息）是由您的安全性運作小組核准。</span><span class="sxs-lookup"><span data-stu-id="e7e40-252">Remediation actions, such as deleting malicious email messages, are taken upon approval by your security operations team.</span></span> <span data-ttu-id="e7e40-253">若要深入瞭解，請參閱 [Office 365 中的 AIR 運作方式](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office)。</span><span class="sxs-lookup"><span data-stu-id="e7e40-253">To learn more, see [How AIR works in Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office).</span></span>

### <a name="attack-simulator"></a><span data-ttu-id="e7e40-254">攻擊模擬器</span><span class="sxs-lookup"><span data-stu-id="e7e40-254">Attack Simulator</span></span>

<span data-ttu-id="e7e40-255">[攻擊模擬器](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator) 可讓授權使用者在您的組織中執行現實的攻擊案例。</span><span class="sxs-lookup"><span data-stu-id="e7e40-255">[Attack Simulator](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator) lets authorized users run realistic attack scenarios in your organization.</span></span> <span data-ttu-id="e7e40-256">有幾種不同的攻擊可供使用，包括顯示名稱 spear 網路釣魚攻擊、密碼噴塗攻擊和強力密碼攻擊。</span><span class="sxs-lookup"><span data-stu-id="e7e40-256">Several different kinds of attacks are available, including a display name spear-phishing attack, a password-spray attack, and a brute-force password attack.</span></span>
