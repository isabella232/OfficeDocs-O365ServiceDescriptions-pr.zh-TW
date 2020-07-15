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
description: Microsoft Office 365 Advanced 威脅防護（ATP）是一種雲端式電子郵件篩選服務，可協助您的組織抵禦未知的惡意程式碼和病毒，方法是提供強健的零日保護，並提供一些功能，以即時保護您的組織不受有害連結。
ms.openlocfilehash: 53e80f635485594f95c62dfa5452ef5352b5a4d7
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132360"
---
# <a name="office-365-advanced-threat-protection-service-description"></a><span data-ttu-id="38487-103">Office 365 進階威脅防護服務說明</span><span class="sxs-lookup"><span data-stu-id="38487-103">Office 365 Advanced Threat Protection service description</span></span>

<span data-ttu-id="38487-104">Microsoft Office 365 Advanced 威脅防護（ATP）是一種雲端式電子郵件篩選服務，可協助您的組織抵禦未知的惡意程式碼和病毒，方法是提供強健的零日保護，並提供一些功能，以即時保護您的組織不受有害連結。</span><span class="sxs-lookup"><span data-stu-id="38487-104">Microsoft Office 365 Advanced Threat Protection (ATP) is a cloud-based email filtering service that helps protect your organization against unknown malware and viruses by providing robust zero-day protection, and includes features to safeguard your organization from harmful links in real time.</span></span> <span data-ttu-id="38487-105">ATP 具有豐富報告和 URL 追蹤功能，可讓系統管理員深入了解組織中發生的攻擊的類型。</span><span class="sxs-lookup"><span data-stu-id="38487-105">ATP has rich reporting and URL trace capabilities that give administrators insight into the kind of attacks happening in your organization.</span></span>

<span data-ttu-id="38487-106">下列是您可以使用 ATP 來保護郵件的主要方法：</span><span class="sxs-lookup"><span data-stu-id="38487-106">The following are the primary ways you can use ATP for message protection:</span></span>

- <span data-ttu-id="38487-107">在 Office 365 ATP 僅篩選案例中，ATP 會針對內部部署 Exchange Server 環境或任何其他內部部署 SMTP 電子郵件解決方案，提供雲端式電子郵件保護。</span><span class="sxs-lookup"><span data-stu-id="38487-107">In an Office 365 ATP filtering-only scenario, ATP provides cloud-based email protection for your on-premises Exchange Server environment or any other on-premises SMTP email solution.</span></span>

- <span data-ttu-id="38487-108">您可以啟用 Office 365 ATP 來保護 Exchange Online 雲端託管信箱。</span><span class="sxs-lookup"><span data-stu-id="38487-108">Office 365 ATP can be enabled to protect Exchange Online cloud-hosted mailboxes.</span></span> <span data-ttu-id="38487-109">若要深入瞭解 Exchange Online，請參閱[Exchange online 服務說明](exchange-online-service-description/exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="38487-109">To learn more about Exchange Online, see the [Exchange Online service description](exchange-online-service-description/exchange-online-service-description.md).</span></span>

- <span data-ttu-id="38487-110">在混合部署中，當您混合使用內部部署及雲端信箱並使用 Exchange Online Protection 來進行輸入電子郵件篩選時，可將 ATP 設定為保護您的郵件環境與控制郵件路由。</span><span class="sxs-lookup"><span data-stu-id="38487-110">In a hybrid deployment, ATP can be configured to protect your messaging environment and control mail routing when you have a mix of on-premises and cloud mailboxes with Exchange Online Protection for inbound email filtering.</span></span>

## <a name="office-365-advanced-threat-protection-atp-availability"></a><span data-ttu-id="38487-111">Office 365 進階威脅防護 (ATP) 可用性</span><span class="sxs-lookup"><span data-stu-id="38487-111">Office 365 Advanced Threat Protection (ATP) availability</span></span>

<span data-ttu-id="38487-112">ATP 包含在 Office 365 企業版 E5、Office 365 教育版 A5 和 Microsoft 365 商務版。</span><span class="sxs-lookup"><span data-stu-id="38487-112">ATP is included in Office 365 Enterprise E5, Office 365 Education A5, and Microsoft 365 Business Premium.</span></span>

<span data-ttu-id="38487-113">您可以將 ATP 新增至下列 Exchange 和 Microsoft 365 訂閱計畫：</span><span class="sxs-lookup"><span data-stu-id="38487-113">You can add ATP to the following Exchange and Microsoft 365 subscription plans:</span></span>

- <span data-ttu-id="38487-114">Exchange Online Plan 1</span><span class="sxs-lookup"><span data-stu-id="38487-114">Exchange Online Plan 1</span></span>

- <span data-ttu-id="38487-115">Exchange Online Plan 2</span><span class="sxs-lookup"><span data-stu-id="38487-115">Exchange Online Plan 2</span></span>

- <span data-ttu-id="38487-116">Exchange Online Kiosk</span><span class="sxs-lookup"><span data-stu-id="38487-116">Exchange Online Kiosk</span></span>

- <span data-ttu-id="38487-117">Exchange Online Protection</span><span class="sxs-lookup"><span data-stu-id="38487-117">Exchange Online Protection</span></span>

- <span data-ttu-id="38487-118">Microsoft 365 商務基本版</span><span class="sxs-lookup"><span data-stu-id="38487-118">Microsoft 365 Business Basic</span></span>

- <span data-ttu-id="38487-119">Microsoft 365 商務標準版</span><span class="sxs-lookup"><span data-stu-id="38487-119">Microsoft 365 Business Standard</span></span>

- <span data-ttu-id="38487-120">Office 365 企業版 E1</span><span class="sxs-lookup"><span data-stu-id="38487-120">Office 365 Enterprise E1</span></span>

- <span data-ttu-id="38487-121">Office 365 Enterprise E3</span><span class="sxs-lookup"><span data-stu-id="38487-121">Office 365 Enterprise E3</span></span>

- <span data-ttu-id="38487-122">Office 365 企業版 F3</span><span class="sxs-lookup"><span data-stu-id="38487-122">Office 365 Enterprise F3</span></span>

- <span data-ttu-id="38487-123">Office 365 A1</span><span class="sxs-lookup"><span data-stu-id="38487-123">Office 365 A1</span></span>

- <span data-ttu-id="38487-124">Office 365 A3</span><span class="sxs-lookup"><span data-stu-id="38487-124">Office 365 A3</span></span>

<span data-ttu-id="38487-125">若要購買 Office 365 進階威脅防護，請參閱 [Office 365 進階威脅防護](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content)。</span><span class="sxs-lookup"><span data-stu-id="38487-125">To buy Office 365 Advanced Threat Protection, see [Office 365 Advanced Threat Protection](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content).</span></span>

<span data-ttu-id="38487-126">若要跨方案比較功能，請參閱[強大的工具來支援您的企業](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409)，並[使用 Microsoft 365 轉換您的企業](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans)。</span><span class="sxs-lookup"><span data-stu-id="38487-126">To compare features across plans, see [Powerful tools to support your enterprise](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) and [Transform your enterprise with Microsoft 365](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans).</span></span>

## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a><span data-ttu-id="38487-127">Office 365 進階威脅防護 (ATP) 的新增功能</span><span class="sxs-lookup"><span data-stu-id="38487-127">What's new in Office 365 Advanced Threat Protection (ATP)</span></span>

<span data-ttu-id="38487-128">我們正在繼續將新功能新增至 Office 365 ATP。</span><span class="sxs-lookup"><span data-stu-id="38487-128">We are continuing to add new features to Office 365 ATP.</span></span> <span data-ttu-id="38487-129">若要深入瞭解即將 ATP （或一般為 Microsoft 365）的新功能，請參閱下列資源：</span><span class="sxs-lookup"><span data-stu-id="38487-129">To learn more about new features coming to ATP (or Microsoft 365 in general), see the following resources:</span></span>

- [<span data-ttu-id="38487-130">Microsoft 365 藍圖</span><span class="sxs-lookup"><span data-stu-id="38487-130">Microsoft 365 Roadmap</span></span>](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [<span data-ttu-id="38487-131">Office 365 ATP 中的新功能</span><span class="sxs-lookup"><span data-stu-id="38487-131">What's new in Office 365 ATP</span></span>](https://docs.microsoft.com/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a><span data-ttu-id="38487-132">Office 365 進階威脅防護 (ATP) 的需求</span><span class="sxs-lookup"><span data-stu-id="38487-132">Requirements for Office 365 Advanced Threat Protection (ATP)</span></span>

<span data-ttu-id="38487-133">ATP 可搭配任何 SMTP 郵件傳輸代理程式使用，例如 Microsoft Exchange Server。</span><span class="sxs-lookup"><span data-stu-id="38487-133">ATP can be used with any SMTP mail transfer agent, such as Microsoft Exchange Server.</span></span> <span data-ttu-id="38487-134">如需 ATP 所支援的作業系統、網頁瀏覽器及語言的相關資訊，請參閱[Exchange Online Protection 中 exchange 系統管理中心](https://go.microsoft.com/fwlink/p/?LinkId=282381)的「支援的瀏覽器」和「支援的語言」一節。</span><span class="sxs-lookup"><span data-stu-id="38487-134">For information about the operating systems, web browsers, and languages that are supported by ATP, see the "Supported browsers" and "Supported languages" sections in [Exchange admin center in Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).</span></span>

## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a><span data-ttu-id="38487-135">各進階威脅防護 (ATP) 計劃中可用的功能</span><span class="sxs-lookup"><span data-stu-id="38487-135">Feature availability across Advanced Threat Protection (ATP) plans</span></span>

<span data-ttu-id="38487-136">Each feature is listed below.</span><span class="sxs-lookup"><span data-stu-id="38487-136">Each feature is listed below.</span></span> <span data-ttu-id="38487-137">When Exchange Online is mentioned, it typically refers to the Office 365 Enterprise service family.</span><span class="sxs-lookup"><span data-stu-id="38487-137">When Exchange Online is mentioned, it typically refers to the Office 365 Enterprise service family.</span></span>

|<span data-ttu-id="38487-138">**功能**</span><span class="sxs-lookup"><span data-stu-id="38487-138">**Feature**</span></span>|<span data-ttu-id="38487-139">**ATP 方案1**</span><span class="sxs-lookup"><span data-stu-id="38487-139">**ATP Plan 1**</span></span><br><span data-ttu-id="38487-140">（先前是 ATP 獨立）</span><span class="sxs-lookup"><span data-stu-id="38487-140">(formerly ATP standalone)</span></span>|<span data-ttu-id="38487-141">**ATP 方案2**</span><span class="sxs-lookup"><span data-stu-id="38487-141">**ATP Plan 2**</span></span><br><span data-ttu-id="38487-142">（以前稱為威脅情報</span><span class="sxs-lookup"><span data-stu-id="38487-142">(formerly Threat Intelligence</span></span> <br><span data-ttu-id="38487-143">單獨</span><span class="sxs-lookup"><span data-stu-id="38487-143">standalone)</span></span>| <span data-ttu-id="38487-144">Office 365 企業版 E5</span><span class="sxs-lookup"><span data-stu-id="38487-144">Office 365 Enterprise E5</span></span>|
|:-----|:-----|:-----|:-----|
|<span data-ttu-id="38487-145">*設定、保護及偵測*</span><span class="sxs-lookup"><span data-stu-id="38487-145">*Configuration, protection, and detection*</span></span>|
|[<span data-ttu-id="38487-146">安全附件</span><span class="sxs-lookup"><span data-stu-id="38487-146">Safe Attachments</span></span>](#safe-attachments)|<span data-ttu-id="38487-147">是</span><span class="sxs-lookup"><span data-stu-id="38487-147">Yes</span></span>|<span data-ttu-id="38487-148">是</span><span class="sxs-lookup"><span data-stu-id="38487-148">Yes</span></span>|<span data-ttu-id="38487-149">是</span><span class="sxs-lookup"><span data-stu-id="38487-149">Yes</span></span>|
|<span data-ttu-id="38487-150">小組中的安全附件</span><span class="sxs-lookup"><span data-stu-id="38487-150">Safe Attachments in Teams</span></span>|<span data-ttu-id="38487-151">是</span><span class="sxs-lookup"><span data-stu-id="38487-151">Yes</span></span>|<span data-ttu-id="38487-152">是</span><span class="sxs-lookup"><span data-stu-id="38487-152">Yes</span></span>|<span data-ttu-id="38487-153">是</span><span class="sxs-lookup"><span data-stu-id="38487-153">Yes</span></span>|
|[<span data-ttu-id="38487-154">安全連結</span><span class="sxs-lookup"><span data-stu-id="38487-154">Safe Links</span></span>](#safe-links)|<span data-ttu-id="38487-155">是</span><span class="sxs-lookup"><span data-stu-id="38487-155">Yes</span></span>|<span data-ttu-id="38487-156">是</span><span class="sxs-lookup"><span data-stu-id="38487-156">Yes</span></span>|<span data-ttu-id="38487-157">是</span><span class="sxs-lookup"><span data-stu-id="38487-157">Yes</span></span>|
|<span data-ttu-id="38487-158">Teams 中的安全連結</span><span class="sxs-lookup"><span data-stu-id="38487-158">Safe Links in Teams</span></span>|<span data-ttu-id="38487-159">是</span><span class="sxs-lookup"><span data-stu-id="38487-159">Yes</span></span>|<span data-ttu-id="38487-160">是</span><span class="sxs-lookup"><span data-stu-id="38487-160">Yes</span></span>|<span data-ttu-id="38487-161">是</span><span class="sxs-lookup"><span data-stu-id="38487-161">Yes</span></span>|
|[<span data-ttu-id="38487-162">SharePoint、OneDrive 和 Microsoft 小組的 ATP</span><span class="sxs-lookup"><span data-stu-id="38487-162">ATP for SharePoint, OneDrive and Microsoft Teams</span></span>](#atp-for-sharepoint-onedrive-and-microsoft-teams)|<span data-ttu-id="38487-163">是</span><span class="sxs-lookup"><span data-stu-id="38487-163">Yes</span></span>|<span data-ttu-id="38487-164">是</span><span class="sxs-lookup"><span data-stu-id="38487-164">Yes</span></span>|<span data-ttu-id="38487-165">是</span><span class="sxs-lookup"><span data-stu-id="38487-165">Yes</span></span>|
|[<span data-ttu-id="38487-166">防網路釣魚原則</span><span class="sxs-lookup"><span data-stu-id="38487-166">Anti-phishing policies</span></span>](#anti-phishing-policies)|<span data-ttu-id="38487-167">是</span><span class="sxs-lookup"><span data-stu-id="38487-167">Yes</span></span>|<span data-ttu-id="38487-168">是</span><span class="sxs-lookup"><span data-stu-id="38487-168">Yes</span></span>|<span data-ttu-id="38487-169">是</span><span class="sxs-lookup"><span data-stu-id="38487-169">Yes</span></span>|
|[<span data-ttu-id="38487-170">即時報告</span><span class="sxs-lookup"><span data-stu-id="38487-170">Real-time reports</span></span>](#real-time-reports)|<span data-ttu-id="38487-171">是</span><span class="sxs-lookup"><span data-stu-id="38487-171">Yes</span></span>|<span data-ttu-id="38487-172">是</span><span class="sxs-lookup"><span data-stu-id="38487-172">Yes</span></span>|<span data-ttu-id="38487-173">是</span><span class="sxs-lookup"><span data-stu-id="38487-173">Yes</span></span>|
|<span data-ttu-id="38487-174">*自動化、調查、修正及教育*</span><span class="sxs-lookup"><span data-stu-id="38487-174">*Automation, investigation, remediation, and education*</span></span>|
|[<span data-ttu-id="38487-175">威脅追蹤工具</span><span class="sxs-lookup"><span data-stu-id="38487-175">Threat Trackers</span></span>](#threat-trackers)|<span data-ttu-id="38487-176">否</span><span class="sxs-lookup"><span data-stu-id="38487-176">No</span></span>|<span data-ttu-id="38487-177">是</span><span class="sxs-lookup"><span data-stu-id="38487-177">Yes</span></span>|<span data-ttu-id="38487-178">是</span><span class="sxs-lookup"><span data-stu-id="38487-178">Yes</span></span>|
|<span data-ttu-id="38487-179">威脅調查（高級威脅調查）</span><span class="sxs-lookup"><span data-stu-id="38487-179">Threat investigation  (advanced threat investigation)</span></span>|[<span data-ttu-id="38487-180">即時偵測</span><span class="sxs-lookup"><span data-stu-id="38487-180">Real-time detections</span></span>](#real-time-detections)|[<span data-ttu-id="38487-181">總管</span><span class="sxs-lookup"><span data-stu-id="38487-181">Explorer</span></span>](#explorer)|[<span data-ttu-id="38487-182">總管</span><span class="sxs-lookup"><span data-stu-id="38487-182">Explorer</span></span>](#explorer)|
|[<span data-ttu-id="38487-183">自動化的事件回應</span><span class="sxs-lookup"><span data-stu-id="38487-183">Automated incident response</span></span>](#automated-incident-response)|<span data-ttu-id="38487-184">否</span><span class="sxs-lookup"><span data-stu-id="38487-184">No</span></span>|<span data-ttu-id="38487-185">是</span><span class="sxs-lookup"><span data-stu-id="38487-185">Yes</span></span>|<span data-ttu-id="38487-186">是</span><span class="sxs-lookup"><span data-stu-id="38487-186">Yes</span></span>|
|[<span data-ttu-id="38487-187">攻擊模擬器</span><span class="sxs-lookup"><span data-stu-id="38487-187">Attack Simulator</span></span>](#attack-simulator)|<span data-ttu-id="38487-188">否</span><span class="sxs-lookup"><span data-stu-id="38487-188">No</span></span>|<span data-ttu-id="38487-189">是</span><span class="sxs-lookup"><span data-stu-id="38487-189">Yes</span></span>|<span data-ttu-id="38487-190">是</span><span class="sxs-lookup"><span data-stu-id="38487-190">Yes</span></span>|

> [!TIP]
> <span data-ttu-id="38487-191">需要 Office 365 ATP 方案1與方案2之間的差異的可供下載的清單嗎？</span><span class="sxs-lookup"><span data-stu-id="38487-191">Want a downloadable list of differences between Office 365 ATP Plan 1 and Plan 2?</span></span> <span data-ttu-id="38487-192">[取得 PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)。</span><span class="sxs-lookup"><span data-stu-id="38487-192">[Get the PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).</span></span> 

## <a name="advanced-threat-protection-atp-capabilities"></a><span data-ttu-id="38487-193">進階威脅防護 (ATP) 功能</span><span class="sxs-lookup"><span data-stu-id="38487-193">Advanced Threat Protection (ATP) capabilities</span></span>

### <a name="safe-attachments"></a><span data-ttu-id="38487-194">安全附件</span><span class="sxs-lookup"><span data-stu-id="38487-194">Safe Attachments</span></span>

<span data-ttu-id="38487-195">[ATP 安全附件](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments)可防止未知的惡意程式碼和病毒，並提供零天的保護來保護您的郵件系統。</span><span class="sxs-lookup"><span data-stu-id="38487-195">[ATP Safe Attachments](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments) protects against unknown malware and viruses, and provides zero-day protection to safeguard your messaging system.</span></span> <span data-ttu-id="38487-196">所有沒有已知病毒/惡意軟體簽章的訊息與附件將被路由傳送至特殊的環境，其中 ATP 會使用不同的機器學習與分析技術來偵測惡意的意圖。</span><span class="sxs-lookup"><span data-stu-id="38487-196">All messages and attachments that don't have a known virus/malware signature are routed to a special environment where ATP uses a variety of machine learning and analysis techniques to detect malicious intent.</span></span> <span data-ttu-id="38487-197">如果未偵測到可疑活動，即會釋出訊息傳遞到信箱。</span><span class="sxs-lookup"><span data-stu-id="38487-197">If no suspicious activity is detected, the message is released for delivery to the mailbox.</span></span>

> [!NOTE]
> <span data-ttu-id="38487-198">ATP 安全附件掃描會在您的 Office 365 資料所在的同一個區域中進行。</span><span class="sxs-lookup"><span data-stu-id="38487-198">ATP Safe Attachments scanning takes place in the same region where your Office 365 data resides.</span></span> <span data-ttu-id="38487-199">如需資料中心地理位置的詳細資訊，請參閱[您的資料位於何處？](https://products.office.com/where-is-your-data-located?geo=All)</span><span class="sxs-lookup"><span data-stu-id="38487-199">For more information about data center geography, see [Where is your data located?](https://products.office.com/where-is-your-data-located?geo=All)</span></span>

### <a name="safe-links"></a><span data-ttu-id="38487-200">安全連結</span><span class="sxs-lookup"><span data-stu-id="38487-200">Safe Links</span></span>

<span data-ttu-id="38487-201">[ATP 安全連結](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links)功能主動保護您的使用者免受郵件中或 Office 檔中的惡意 URLs。</span><span class="sxs-lookup"><span data-stu-id="38487-201">The [ATP Safe Links](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links) feature proactively protects your users from malicious URLs in a message or in an Office document.</span></span> <span data-ttu-id="38487-202">因為可動態封鎖惡意連結，允許存取無害連結，所以每次使用者選取連結時都能受到持續保護。</span><span class="sxs-lookup"><span data-stu-id="38487-202">The protection remains every time they select the link, as malicious links are dynamically blocked while good links can be accessed.</span></span>

<span data-ttu-id="38487-203">安全連結可用於下列應用程式中的 URLs：</span><span class="sxs-lookup"><span data-stu-id="38487-203">Safe Links is available for URLs in the following apps:</span></span>

- <span data-ttu-id="38487-204">Microsoft 365 Windows 或 Mac 版企業版應用程式</span><span class="sxs-lookup"><span data-stu-id="38487-204">Microsoft 365 Apps for enterprise on Windows or Mac</span></span>

- <span data-ttu-id="38487-205">Office for web （適用于網頁的 Word、網頁版、網頁 PowerPoint 和 OneNote 網頁）</span><span class="sxs-lookup"><span data-stu-id="38487-205">Office for the web (Word for the web, Excel for the web, PowerPoint for the web, and OneNote for the web)</span></span>

- <span data-ttu-id="38487-206">Windows 上的 Word、Excel、PowerPoint 和 Visio，以及 iOS 和 Android 裝置上的 Office 應用程式</span><span class="sxs-lookup"><span data-stu-id="38487-206">Word, Excel, PowerPoint, and Visio on Windows, as well as Office apps on iOS and Android devices</span></span>

- <span data-ttu-id="38487-207">Microsoft 小組通道和聊天</span><span class="sxs-lookup"><span data-stu-id="38487-207">Microsoft Teams channels and chats</span></span>

> [!NOTE]
> <span data-ttu-id="38487-208">使用者必須是 ATP 的授權，必須 <sup>\*</sup> 包含在 Atp 安全連結原則中，且必須在裝置上登入，以進行保護。</span><span class="sxs-lookup"><span data-stu-id="38487-208">Users must be licensed for ATP<sup>\*</sup>, must be included in ATP Safe Links policies, and must be signed in on their devices for protection to be in place.</span></span>
>
> <span data-ttu-id="38487-209"><sup>\*</sup>若為全組織的 ATP 授權（例如，ATP_ENTERPRISE_FACULTY），您不需要將 ATP 授權指派給個別使用者。</span><span class="sxs-lookup"><span data-stu-id="38487-209"><sup>\*</sup> For organization-wide ATP licenses (for example, ATP_ENTERPRISE_FACULTY), you don't need to assign ATP licenses to individual users.</span></span>
>
> <span data-ttu-id="38487-210">如需有關 ATP 安全連結保護的詳細資訊，請參閱[Atp 安全連結如何與 Office 檔中的 URLs 搭配運作](https://docs.microsoft.com/microsoft-365/security/office-365-security/how-atp-safe-links-works#how-atp-safe-links-works-with-urls-in-office-documents)。</span><span class="sxs-lookup"><span data-stu-id="38487-210">For more information about ATP Safe Links protection, see [How ATP Safe Links works with URLs in Office documents](https://docs.microsoft.com/microsoft-365/security/office-365-security/how-atp-safe-links-works#how-atp-safe-links-works-with-urls-in-office-documents).</span></span>

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a><span data-ttu-id="38487-211">適用於 SharePoint、OneDrive 及 Microsoft Teams 的 ATP</span><span class="sxs-lookup"><span data-stu-id="38487-211">ATP for SharePoint, OneDrive, and Microsoft Teams</span></span>

<span data-ttu-id="38487-212">[SharePoint、OneDrive 和 Microsoft 團隊的 ATP](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)可協助偵測和封鎖在小組網站和文件庫中識別為惡意的檔案。</span><span class="sxs-lookup"><span data-stu-id="38487-212">[ATP for SharePoint, OneDrive, and Microsoft Teams](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)  helps detect and block files that are identified as malicious in team sites and document libraries.</span></span> <span data-ttu-id="38487-213">此外，在 Microsoft 小組通道和聊天中，現在還提供 ATP 安全連結保護。</span><span class="sxs-lookup"><span data-stu-id="38487-213">In addition, ATP Safe Links protection is now available in Microsoft Teams channels and chats.</span></span>

### <a name="anti-phishing-policies"></a><span data-ttu-id="38487-214">防網路釣魚原則</span><span class="sxs-lookup"><span data-stu-id="38487-214">Anti-phishing policies</span></span>

<span data-ttu-id="38487-215">[ATP 反網路釣魚](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing)檢查內送郵件的指示，郵件可能是網路釣魚企圖。</span><span class="sxs-lookup"><span data-stu-id="38487-215">[ATP anti-phishing](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing) checks incoming messages for indicators that a message might be a phishing attempt.</span></span> <span data-ttu-id="38487-216">當使用者受 ATP 原則 (安全附件、安全連結或反網路釣魚) 保護時，系統會根據已設定的原則，以多個可分析郵件的電腦學習模型來評估傳入的郵件，並採取適當動作。</span><span class="sxs-lookup"><span data-stu-id="38487-216">When users are covered by ATP policies (Safe Attachments, Safe Links, or anti-phishing), incoming messages are evaluated by multiple machine learning models that analyze messages and the appropriate action is taken, based on the configured policies.</span></span>

### <a name="real-time-reports"></a><span data-ttu-id="38487-217">即時報告</span><span class="sxs-lookup"><span data-stu-id="38487-217">Real-time reports</span></span>

<span data-ttu-id="38487-218">安全性 & 合規性中心內可用的監控功能包括[即時報告和深入](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp)資訊，讓您的安全性和合規性系統管理員關注高優先順序的問題，例如安全性攻擊或增加的可疑活動。</span><span class="sxs-lookup"><span data-stu-id="38487-218">Monitoring capabilities available in the Security & Compliance Center include [real-time reports and insights](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp) that let your security and compliance administrators focus on high-priority issues, such as security attacks or increased suspicious activity.</span></span> <span data-ttu-id="38487-219">除了醒目提示問題之外，智慧報告和洞察力也包含建議和連結，以查看及流覽資料，也會快速採取動作。</span><span class="sxs-lookup"><span data-stu-id="38487-219">In addition to highlighting problem areas, smart reports and insights include recommendations and links to view and explore data and also take quick actions.</span></span>

### <a name="explorer"></a><span data-ttu-id="38487-220">總管</span><span class="sxs-lookup"><span data-stu-id="38487-220">Explorer</span></span>

<span data-ttu-id="38487-221">總管 (也稱為威脅總管) 是即時的報告，可讓授權的使用者識別並分析最近的威脅。</span><span class="sxs-lookup"><span data-stu-id="38487-221">Explorer (also referred to as Threat Explorer) is a real-time report that lets authorized users identify and analyze recent threats.</span></span> <span data-ttu-id="38487-222">根據預設，此報告會顯示過去 7 天的資料；不過，您可以修改檢視畫面以顯示過去 30 天的資料。</span><span class="sxs-lookup"><span data-stu-id="38487-222">By default, this report shows data for the past 7 days; however, views can be modified to show data for the past 30 days.</span></span>

<span data-ttu-id="38487-223">Explorer 包含一些視圖，例如惡意程式碼（適用于電子郵件和內容）、提交、網路釣魚和所有電子郵件。</span><span class="sxs-lookup"><span data-stu-id="38487-223">Explorer contains views, such as Malware (for email and content), Submissions, Phish, and All Email.</span></span> <span data-ttu-id="38487-224">若要查看 Explorer 如何與即時偵測相比較，請[下載此 PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)。</span><span class="sxs-lookup"><span data-stu-id="38487-224">To see how Explorer compares with real-time detections, [download this PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).</span></span>

<span data-ttu-id="38487-225">如需 Explorer （Office 365 Advanced 威脅防護方案2）和即時偵測（位於 Office 365 高級威脅防護方案1）中的詳細資訊，請參閱[威脅瀏覽器和即時](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)偵測。</span><span class="sxs-lookup"><span data-stu-id="38487-225">For more information about Explorer (in Office 365 Advanced Threat Protection Plan 2) and real-time detections (in Office 365 Advanced Threat Protection Plan 1), see [Threat Explorer and real-time detections](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer).</span></span>

### <a name="real-time-detections"></a><span data-ttu-id="38487-226">即時偵測</span><span class="sxs-lookup"><span data-stu-id="38487-226">Real-time detections</span></span>

<span data-ttu-id="38487-227">即時偵測是即時的報告，可讓授權的使用者識別並分析最近的威脅。</span><span class="sxs-lookup"><span data-stu-id="38487-227">Real-time detections is a real-time report that lets authorized users identify and analyze recent threats.</span></span> <span data-ttu-id="38487-228">與 [總管] 類似，根據預設，此報告顯示過去 7 天的資料。</span><span class="sxs-lookup"><span data-stu-id="38487-228">Similar to Explorer, by default, this report shows data for the past 7 days.</span></span>

<span data-ttu-id="38487-229">即時偵測包含一些視圖，例如惡意程式碼（適用于電子郵件和內容）、提交郵件和網路釣魚。</span><span class="sxs-lookup"><span data-stu-id="38487-229">Real-time detections contain views, such as Malware (for email and content), Submissions, and Phish.</span></span> <span data-ttu-id="38487-230">若要查看即時檢測與瀏覽器的比較方式，請[下載此 PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)。</span><span class="sxs-lookup"><span data-stu-id="38487-230">To see how real-time detections compare with Explorer, [download this PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).</span></span>

<span data-ttu-id="38487-231">如需 Explorer （Office 365 Advanced 威脅防護方案2）和即時偵測（位於 Office 365 高級威脅防護方案1）中的詳細資訊，請參閱[威脅瀏覽器（和即時偵測）](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)。</span><span class="sxs-lookup"><span data-stu-id="38487-231">For more information about Explorer (in Office 365 Advanced Threat Protection Plan 2) and real-time detections (in Office 365 Advanced Threat Protection Plan 1), see [Threat Explorer (and real-time detections)](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer).</span></span>

### <a name="threat-trackers"></a><span data-ttu-id="38487-232">威脅追蹤工具</span><span class="sxs-lookup"><span data-stu-id="38487-232">Threat Trackers</span></span>

<span data-ttu-id="38487-233">[威脅](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers)追蹤器是資訊性的小元件和視圖，可讓授權的使用者在可能影響組織的 cybersecurity 問題上使用情報。</span><span class="sxs-lookup"><span data-stu-id="38487-233">[Threat Trackers](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers) are informative widgets and views that provide authorized users with intelligence on cybersecurity issues that might impact your organization.</span></span>

### <a name="automated-incident-response"></a><span data-ttu-id="38487-234">自動化的事件回應</span><span class="sxs-lookup"><span data-stu-id="38487-234">Automated incident response</span></span>

<span data-ttu-id="38487-235">Office 365 ATP 方案2中可用的[自動事件回應](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air)（AIR）功能可讓您執行自動調查處理程式，以回應目前存在的已知威脅。</span><span class="sxs-lookup"><span data-stu-id="38487-235">[Automated incident response](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air) (AIR) capabilities available in Office 365 ATP Plan 2 enable you to run automated investigation processes in response to well known threats that exist today.</span></span> <span data-ttu-id="38487-236">透過自動化某些調查任務，您的安全性運作小組可以更有效率地運作。</span><span class="sxs-lookup"><span data-stu-id="38487-236">By automated certain investigation tasks, your security operations team can operate more efficiently and effectively.</span></span> <span data-ttu-id="38487-237">修正動作（如刪除惡意電子郵件訊息）是由您的安全性運作小組核准。</span><span class="sxs-lookup"><span data-stu-id="38487-237">Remediation actions, such as deleting malicious email messages, are taken upon approval by your security operations team.</span></span> <span data-ttu-id="38487-238">若要深入瞭解，請參閱[Office 365 中的 AIR 運作方式](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office)。</span><span class="sxs-lookup"><span data-stu-id="38487-238">To learn more, see [How AIR works in Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office).</span></span>

### <a name="attack-simulator"></a><span data-ttu-id="38487-239">攻擊模擬器</span><span class="sxs-lookup"><span data-stu-id="38487-239">Attack Simulator</span></span>

<span data-ttu-id="38487-240">[攻擊模擬器](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator)可讓授權使用者在您的組織中執行現實的攻擊案例。</span><span class="sxs-lookup"><span data-stu-id="38487-240">[Attack Simulator](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator) lets authorized users run realistic attack scenarios in your organization.</span></span> <span data-ttu-id="38487-241">有幾種不同的攻擊可供使用，包括顯示名稱 spear 網路釣魚攻擊、密碼噴塗攻擊和強力密碼攻擊。</span><span class="sxs-lookup"><span data-stu-id="38487-241">Several different kinds of attacks are available, including a display name spear-phishing attack, a password-spray attack, and a brute-force password attack.</span></span>
