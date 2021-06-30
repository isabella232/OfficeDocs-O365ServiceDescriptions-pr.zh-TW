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
# <a name="microsoft-defender-for-office-365-features-service-description"></a><span data-ttu-id="61398-103">Microsoft Defender Office 365 功能服務說明</span><span class="sxs-lookup"><span data-stu-id="61398-103">Microsoft Defender for Office 365 Features service description</span></span>

## <a name="whats-new-in-microsoft-defender-for-office-365"></a><span data-ttu-id="61398-104">Microsoft Defender Office 365 的新功能</span><span class="sxs-lookup"><span data-stu-id="61398-104">What's new in Microsoft Defender for Office 365</span></span>

<span data-ttu-id="61398-105">我們會繼續為 Office 365 的 Defender 新增新功能。</span><span class="sxs-lookup"><span data-stu-id="61398-105">We are continuing to add new features to Defender for Office 365.</span></span> <span data-ttu-id="61398-106">若要深入瞭解 Office 365 (或 Microsoft 365 一般) 中的新功能，請參閱下列資源：</span><span class="sxs-lookup"><span data-stu-id="61398-106">To learn more about new features coming to Defender for Office 365 (or Microsoft 365 in general), see the following resources:</span></span>

- [<span data-ttu-id="61398-107">Microsoft 365 藍圖</span><span class="sxs-lookup"><span data-stu-id="61398-107">Microsoft 365 Roadmap</span></span>](https://www.microsoft.com/microsoft-365/roadmap)

- [<span data-ttu-id="61398-108">Microsoft Defender 的新增功能 Office 365-Office 365 |Microsoft 檔</span><span class="sxs-lookup"><span data-stu-id="61398-108">What's new in Microsoft Defender for Office 365 - Office 365 | Microsoft Docs</span></span>](/microsoft-365/security/office-365-security/whats-new-in-defender-for-office-365)

## <a name="defender-for-office-365-capabilities"></a><span data-ttu-id="61398-109">Office 365 功能的 Defender</span><span class="sxs-lookup"><span data-stu-id="61398-109">Defender for Office 365 capabilities</span></span>

### <a name="safe-attachments"></a><span data-ttu-id="61398-110">安全附件</span><span class="sxs-lookup"><span data-stu-id="61398-110">Safe Attachments</span></span>

<span data-ttu-id="61398-111">[保管庫附件](/microsoft-365/security/office-365-security/atp-safe-attachments)可保護未知的惡意程式碼和病毒，並提供零的保護來保護郵件系統。</span><span class="sxs-lookup"><span data-stu-id="61398-111">[Safe Attachments](/microsoft-365/security/office-365-security/atp-safe-attachments) protects against unknown malware and viruses, and provides zero-day protection to safeguard your messaging system.</span></span> <span data-ttu-id="61398-112">所有沒有已知病毒/惡意程式碼簽章的郵件和附件，都是路由傳送至特殊的環境，其中 Office 365 的 Defender 會使用各種機器學習和分析技術來偵測惡意目的。</span><span class="sxs-lookup"><span data-stu-id="61398-112">All messages and attachments that don't have a known virus/malware signature are routed to a special environment where Defender for Office 365 uses a variety of machine learning and analysis techniques to detect malicious intent.</span></span> <span data-ttu-id="61398-113">如果未偵測到可疑活動，即會釋出訊息傳遞到信箱。</span><span class="sxs-lookup"><span data-stu-id="61398-113">If no suspicious activity is detected, the message is released for delivery to the mailbox.</span></span>

> [!NOTE]
> <span data-ttu-id="61398-114">保管庫附件掃描會在您的 Office 365 資料所在的相同區域中進行。</span><span class="sxs-lookup"><span data-stu-id="61398-114">Safe Attachments scanning takes place in the same region where your Office 365 data resides.</span></span> <span data-ttu-id="61398-115">如需資料中心地理位置的詳細資訊，請參閱[您的資料位於何處？](/microsoft-365/enterprise/o365-data-locations)</span><span class="sxs-lookup"><span data-stu-id="61398-115">For more information about data center geography, see [Where is your data located?](/microsoft-365/enterprise/o365-data-locations)</span></span>

### <a name="safe-links"></a><span data-ttu-id="61398-116">安全連結</span><span class="sxs-lookup"><span data-stu-id="61398-116">Safe Links</span></span>

<span data-ttu-id="61398-117">[保管庫連結](/microsoft-365/security/office-365-security/atp-safe-links)功能會主動保護您的使用者免受郵件中或 Office 檔中的惡意 URLs。</span><span class="sxs-lookup"><span data-stu-id="61398-117">The [Safe Links](/microsoft-365/security/office-365-security/atp-safe-links) feature proactively protects your users from malicious URLs in a message or in an Office document.</span></span> <span data-ttu-id="61398-118">因為可動態封鎖惡意連結，允許存取無害連結，所以每次使用者選取連結時都能受到持續保護。</span><span class="sxs-lookup"><span data-stu-id="61398-118">The protection remains every time they select the link, as malicious links are dynamically blocked while good links can be accessed.</span></span>

<span data-ttu-id="61398-119">下列應用程式的 URL 可使用安全連結：</span><span class="sxs-lookup"><span data-stu-id="61398-119">Safe Links is available for URLs in the following apps:</span></span>

- <span data-ttu-id="61398-120">Windows 或 Mac 上的 Microsoft 365 Apps 企業版</span><span class="sxs-lookup"><span data-stu-id="61398-120">Microsoft 365 Apps for enterprise on Windows or Mac</span></span>

- <span data-ttu-id="61398-121">Office 網頁版 (Word 網頁版、Excel 網頁版、PowerPoint 網頁版和 OneNote 網頁版)</span><span class="sxs-lookup"><span data-stu-id="61398-121">Office for the web (Word for the web, Excel for the web, PowerPoint for the web, and OneNote for the web)</span></span>

- <span data-ttu-id="61398-122">Windows 上的 Word、Excel 及 PowerPoint</span><span class="sxs-lookup"><span data-stu-id="61398-122">Word, Excel, and PowerPoint on Windows</span></span>

- <span data-ttu-id="61398-123">Microsoft Teams 頻道與聊天</span><span class="sxs-lookup"><span data-stu-id="61398-123">Microsoft Teams channels and chats</span></span>

> [!NOTE]
> <span data-ttu-id="61398-124">使用者必須已取得 Office 365 的 Defender 授權 <sup>\*</sup> ，必須包含在保管庫連結原則中，而且必須登入其裝置上，才可進行保護。</span><span class="sxs-lookup"><span data-stu-id="61398-124">Users must be licensed for Defender for Office 365<sup>\*</sup>, must be included in Safe Links policies, and must be signed in on their devices for protection to be in place.</span></span>
>
> <span data-ttu-id="61398-125"><sup>\*</sup>針對 Office 365 授權的整個組織的 Defender (例如，ATP_ENTERPRISE_FACULTY) ，您不需要為個別使用者指派 Office 365 授權的 Defender。</span><span class="sxs-lookup"><span data-stu-id="61398-125"><sup>\*</sup> For organization-wide Defender for Office 365 licenses (for example, ATP_ENTERPRISE_FACULTY), you don't need to assign Defender for Office 365 licenses to individual users.</span></span>
>
> <span data-ttu-id="61398-126">如需保管庫連結保護的詳細資訊，請參閱[保管庫 Microsoft Defender for Office 365 中的連結](/microsoft-365/security/office-365-security/atp-safe-links)。</span><span class="sxs-lookup"><span data-stu-id="61398-126">For more information about Safe Links protection, see [Safe Links in Microsoft Defender for Office 365](/microsoft-365/security/office-365-security/atp-safe-links).</span></span>

### <a name="safe-documents"></a><span data-ttu-id="61398-127">安全文件</span><span class="sxs-lookup"><span data-stu-id="61398-127">Safe Documents</span></span>

<span data-ttu-id="61398-128">[保管庫檔](/microsoft-365/security/office-365-security/safe-docs)功能使用[Microsoft Defender for 端點](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection)掃描在[受保護的檢視](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)中開啟的檔和檔案。</span><span class="sxs-lookup"><span data-stu-id="61398-128">The [Safe Documents](/microsoft-365/security/office-365-security/safe-docs) feature uses [Microsoft Defender for Endpoint](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) to scan documents and files that are opened in [Protected View](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653).</span></span>

<span data-ttu-id="61398-129">開始之前有哪些須知？</span><span class="sxs-lookup"><span data-stu-id="61398-129">What do you need to know before you begin?</span></span>

- <span data-ttu-id="61398-130">保管庫檔現在一般可供使用者使用 Office 版本 2004 (12730) 或以上！</span><span class="sxs-lookup"><span data-stu-id="61398-130">Safe Documents is now generally available to users with Office Version 2004 (12730.x) or greater!</span></span> <span data-ttu-id="61398-131">此功能預設為關閉，必須由安全性管理員啟用。</span><span class="sxs-lookup"><span data-stu-id="61398-131">This feature is off by default and will need to be enabled by the Security Administrator.</span></span>

- <span data-ttu-id="61398-132">此功能僅適用于具有 Microsoft 365 E5 或 Microsoft 365 E5 安全性授權 (的使用者，但不會包含在 Office 365 方案) 的 Defender 中。</span><span class="sxs-lookup"><span data-stu-id="61398-132">This feature is only available to users with the Microsoft 365 E5 or Microsoft 365 E5 Security license (not included in Defender for Office 365 plans).</span></span>

- <span data-ttu-id="61398-133">Windows 上的 Word、Excel 及 PowerPoint</span><span class="sxs-lookup"><span data-stu-id="61398-133">Word, Excel, and PowerPoint on Windows</span></span>

- <span data-ttu-id="61398-134">Microsoft Teams 頻道與聊天</span><span class="sxs-lookup"><span data-stu-id="61398-134">Microsoft Teams channels and chats</span></span>

> [!NOTE]
> <span data-ttu-id="61398-135">使用者必須要有 Microsoft 365 E5 或 Microsoft 365 E5 安全性的授權 <sup>\*</sup> ，必須包含在保管庫檔原則中，且必須登入其裝置，才可進行保護。</span><span class="sxs-lookup"><span data-stu-id="61398-135">Users must be licensed for Microsoft 365 E5 or Microsoft 365 E5 Security<sup>\*</sup>, must be included in Safe Documents policies, and must be signed in on their devices for protection to be in place.</span></span>
>
> <span data-ttu-id="61398-136">如需保管庫檔案保護的詳細資訊，請參閱[Microsoft 365 E5 中的保管庫檔](/microsoft-365/security/office-365-security/safe-docs)。</span><span class="sxs-lookup"><span data-stu-id="61398-136">For more information about Safe Documents protection, see [Safe Documents in Microsoft 365 E5](/microsoft-365/security/office-365-security/safe-docs).</span></span>

### <a name="protection-for-sharepoint-onedrive-and-microsoft-teams"></a><span data-ttu-id="61398-137">保護 SharePoint、OneDrive 及 Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="61398-137">Protection for SharePoint, OneDrive, and Microsoft Teams</span></span>

<span data-ttu-id="61398-138">[保護 SharePoint、OneDrive 及 Microsoft Teams](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)可協助偵測和封鎖在小組網站和文件庫中識別為惡意的檔案。</span><span class="sxs-lookup"><span data-stu-id="61398-138">[Protection for SharePoint, OneDrive, and Microsoft Teams](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams) helps detect and block files that are identified as malicious in team sites and document libraries.</span></span> <span data-ttu-id="61398-139">此外，保管庫的連結保護現在也可用於 Microsoft Teams 通道和聊天。</span><span class="sxs-lookup"><span data-stu-id="61398-139">In addition, Safe Links protection is now available in Microsoft Teams channels and chats.</span></span>

### <a name="anti-phishing-policies"></a><span data-ttu-id="61398-140">防網路釣魚原則</span><span class="sxs-lookup"><span data-stu-id="61398-140">Anti-phishing policies</span></span>

<span data-ttu-id="61398-141">[反網路釣魚](/microsoft-365/security/office-365-security/atp-anti-phishing) 檢查內送郵件中是否有郵件可能是網路釣魚企圖。</span><span class="sxs-lookup"><span data-stu-id="61398-141">[Anti-phishing](/microsoft-365/security/office-365-security/atp-anti-phishing) checks incoming messages for indicators that a message might be a phishing attempt.</span></span> <span data-ttu-id="61398-142">當使用者在 Office 365 原則中涵蓋時 (保管庫附件、保管庫連結或反網路釣魚) 時，會透過分析郵件的多部機器教學模型評估內送郵件，並根據設定的原則採取適當的動作。</span><span class="sxs-lookup"><span data-stu-id="61398-142">When users are covered by Defender for Office 365 policies (Safe Attachments, Safe Links, or anti-phishing), incoming messages are evaluated by multiple machine learning models that analyze messages and the appropriate action is taken, based on the configured policies.</span></span>

### <a name="real-time-reports"></a><span data-ttu-id="61398-143">即時報告</span><span class="sxs-lookup"><span data-stu-id="61398-143">Real-time reports</span></span>

<span data-ttu-id="61398-144">[安全性 & 合規性中心](https://protection.office.com)內可用的監控功能包括[即時報告和深入](/microsoft-365/security/office-365-security/view-reports-for-atp)資訊，讓您的安全性和合規性系統管理員關注高優先順序的問題，例如安全性攻擊或增加的可疑活動。</span><span class="sxs-lookup"><span data-stu-id="61398-144">Monitoring capabilities available in the [Security & Compliance Center](https://protection.office.com) include [real-time reports and insights](/microsoft-365/security/office-365-security/view-reports-for-atp) that let your security and compliance administrators focus on high-priority issues, such as security attacks or increased suspicious activity.</span></span> <span data-ttu-id="61398-145">除了醒目提示問題之外，智慧報告和洞察力也包含建議和連結，以查看及流覽資料，也會快速採取動作。</span><span class="sxs-lookup"><span data-stu-id="61398-145">In addition to highlighting problem areas, smart reports and insights include recommendations and links to view and explore data and also take quick actions.</span></span>

### <a name="threat-explorer"></a><span data-ttu-id="61398-146">威脅總管</span><span class="sxs-lookup"><span data-stu-id="61398-146">Threat Explorer</span></span>

<span data-ttu-id="61398-147">威脅瀏覽器 (也稱為 Explorer) 是即時報告，可讓授權的使用者識別及分析最近的威脅。</span><span class="sxs-lookup"><span data-stu-id="61398-147">Threat Explorer (also referred to as Explorer) is a real-time report that lets authorized users identify and analyze recent threats.</span></span> <span data-ttu-id="61398-148">根據預設，此報告會顯示過去7天的資料;不過，您可以修改視圖，以顯示過去30天的資料。</span><span class="sxs-lookup"><span data-stu-id="61398-148">By default, this report shows data for the past seven days; however, views can be modified to show data for the past 30 days.</span></span>

<span data-ttu-id="61398-149">Explorer 包含一些視圖，例如電子郵件和內容) 、提交、網路釣魚和所有電子郵件的惡意程式碼 (。</span><span class="sxs-lookup"><span data-stu-id="61398-149">Explorer contains views, such as Malware (for email and content), Submissions, Phish, and All Email.</span></span> <span data-ttu-id="61398-150">若要查看 Explorer 如何與即時偵測相比較，請 [下載此 PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)。</span><span class="sxs-lookup"><span data-stu-id="61398-150">To see how Explorer compares with real-time detections, [download this PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).</span></span>

<span data-ttu-id="61398-151">如需 microsoft defender for a Office 365 plan 2) 和即時偵測 (的 microsoft defender 中的 Explorer (的詳細資訊，請參閱 Office 365 plan 1) 的[威脅瀏覽器和即時](/microsoft-365/security/office-365-security/threat-explorer)偵測。</span><span class="sxs-lookup"><span data-stu-id="61398-151">For more information about Explorer (in Microsoft Defender for Office 365 Plan 2) and real-time detections (in Microsoft Defender for Office 365 Plan 1), see [Threat Explorer and real-time detections](/microsoft-365/security/office-365-security/threat-explorer).</span></span>

### <a name="real-time-detections"></a><span data-ttu-id="61398-152">即時偵測</span><span class="sxs-lookup"><span data-stu-id="61398-152">Real-time detections</span></span>

<span data-ttu-id="61398-153">即時偵測是即時的報告，可讓授權的使用者識別並分析最近的威脅。</span><span class="sxs-lookup"><span data-stu-id="61398-153">Real-time detections is a real-time report that lets authorized users identify and analyze recent threats.</span></span> <span data-ttu-id="61398-154">類似 Explorer，依預設，此報告會顯示過去7天的資料。</span><span class="sxs-lookup"><span data-stu-id="61398-154">Similar to Explorer, by default, this report shows data for the past seven days.</span></span>

<span data-ttu-id="61398-155">即時偵測包含諸如電子郵件和內容) 、報送和網路釣魚的惡意程式碼 (的視圖。</span><span class="sxs-lookup"><span data-stu-id="61398-155">Real-time detections contain views, such as Malware (for email and content), Submissions, and Phish.</span></span> <span data-ttu-id="61398-156">若要查看即時檢測與瀏覽器的比較方式，請 [下載此 PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)。</span><span class="sxs-lookup"><span data-stu-id="61398-156">To see how real-time detections compare with Explorer, [download this PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).</span></span>

<span data-ttu-id="61398-157">如需 microsoft defender for a Office 365 plan 2) 和即時偵測 (的 microsoft defender 中的 Explorer (的詳細資訊，請參閱 Office 365 plan 1) 的[威脅瀏覽器和即時](/microsoft-365/security/office-365-security/threat-explorer)偵測。</span><span class="sxs-lookup"><span data-stu-id="61398-157">For more information about Explorer (in Microsoft Defender for Office 365 Plan 2) and real-time detections (in Microsoft Defender for Office 365 Plan 1), see [Threat Explorer and real-time detections](/microsoft-365/security/office-365-security/threat-explorer).</span></span>

### <a name="threat-trackers"></a><span data-ttu-id="61398-158">威脅追蹤工具</span><span class="sxs-lookup"><span data-stu-id="61398-158">Threat Trackers</span></span>

<span data-ttu-id="61398-159">[威脅](/microsoft-365/security/office-365-security/threat-trackers) 追蹤器是資訊性的小元件和視圖，可讓授權的使用者在可能影響組織的 cybersecurity 問題上使用情報。</span><span class="sxs-lookup"><span data-stu-id="61398-159">[Threat Trackers](/microsoft-365/security/office-365-security/threat-trackers) are informative widgets and views that provide authorized users with intelligence on cybersecurity issues that might impact your organization.</span></span>

### <a name="automated-investigation--response"></a><span data-ttu-id="61398-160">自動調查 & 回應</span><span class="sxs-lookup"><span data-stu-id="61398-160">Automated investigation & response</span></span>

<span data-ttu-id="61398-161">[自動調查 & 回應](/microsoft-365/security/office-365-security/office-365-air) (適用于 Office 365 計畫2的 AIR) 功能，可讓您執行自動調查程式，以回應目前存在的已知威脅。</span><span class="sxs-lookup"><span data-stu-id="61398-161">[Automated investigation & response](/microsoft-365/security/office-365-security/office-365-air) (AIR) capabilities available in Defender for Office 365 Plan 2 let you run automated investigation processes in response to well-known threats that exist today.</span></span> <span data-ttu-id="61398-162">透過自動化某些調查任務，您的安全性運作小組可以更有效率地運作。</span><span class="sxs-lookup"><span data-stu-id="61398-162">By automating certain investigation tasks, your security operations team can operate more efficiently and effectively.</span></span> <span data-ttu-id="61398-163">修正動作（如刪除惡意電子郵件訊息）是由您的安全性運作小組核准。</span><span class="sxs-lookup"><span data-stu-id="61398-163">Remediation actions, such as deleting malicious email messages, are taken upon approval by your security operations team.</span></span> <span data-ttu-id="61398-164">若要深入瞭解，請參閱[Office 365 中的 AIR 的運作方式](/microsoft-365/security/office-365-security/automated-investigation-response-office)。</span><span class="sxs-lookup"><span data-stu-id="61398-164">To learn more, see [How AIR works in Office 365](/microsoft-365/security/office-365-security/automated-investigation-response-office).</span></span>

### <a name="attack-simulation-training"></a><span data-ttu-id="61398-165">攻擊模擬訓練</span><span class="sxs-lookup"><span data-stu-id="61398-165">Attack simulation training</span></span>

<span data-ttu-id="61398-166">[攻擊模擬訓練](/microsoft-365/security/office-365-security/attack-simulation-training-get-started) 是一種可自動建立及管理網路釣魚模擬的智慧社交風險管理工具。</span><span class="sxs-lookup"><span data-stu-id="61398-166">[Attack simulation training](/microsoft-365/security/office-365-security/attack-simulation-training-get-started) is an intelligent social risk management tool that automates the creation and management of phishing simulations.</span></span> <span data-ttu-id="61398-167">模擬會使用實際的世界釣魚網絡 lures 和超目標訓練來協助客戶偵測、設定優先順序和修正網路釣魚風險，以變更員工的行為。</span><span class="sxs-lookup"><span data-stu-id="61398-167">Simulations help customers detect, prioritize, and remediate phishing risks by using real world phish lures and hyper-targeted training to change employee behaviors.</span></span>

- <span data-ttu-id="61398-168">現在，WW 已提供攻擊模擬訓練，GCC (將會從6月21日) GCC。</span><span class="sxs-lookup"><span data-stu-id="61398-168">Attack simulation training is now available in WW and GCC (will be in GCC from June 21).</span></span>
- <span data-ttu-id="61398-169">如需如何開始的詳細資訊，請參閱 [使用攻擊模擬訓練](/microsoft-365/security/office-365-security/attack-simulation-training-get-started)。</span><span class="sxs-lookup"><span data-stu-id="61398-169">For more information on how to get started, see [Get started using Attack simulation training](/microsoft-365/security/office-365-security/attack-simulation-training-get-started).</span></span>
- <span data-ttu-id="61398-170">可以使用各種套用取消 weaponized、真實世界網路釣魚負載的攻擊技術，以複製真實世界的攻擊者行為，以進行網路釣魚模擬。</span><span class="sxs-lookup"><span data-stu-id="61398-170">Various attack techniques that apply de-weaponized, real-world phish payloads are available that replicate real world attacker behavior to make phishing simulations relevant.</span></span>
- <span data-ttu-id="61398-171">這項服務可供有 Microsoft 365 E5、Office 365 E5 或[Microsoft Defender Office 365 方案2授權的](/microsoft-365/security/office-365-security/defender-for-office-365#microsoft-defender-for-office-365-plan-1-and-plan-2)組織使用。</span><span class="sxs-lookup"><span data-stu-id="61398-171">This service is available to organizations that have either Microsoft 365 E5, Office 365 E5, or [Microsoft Defender for Office 365 Plan 2](/microsoft-365/security/office-365-security/defender-for-office-365#microsoft-defender-for-office-365-plan-1-and-plan-2) licenses.</span></span> <span data-ttu-id="61398-172">將功能的子集提供給 E3 客戶以進行試用。</span><span class="sxs-lookup"><span data-stu-id="61398-172">A subset of capabilities is offered to E3 customers as a trial.</span></span>
- <span data-ttu-id="61398-173">若要深入瞭解和嘗試類比，請參閱 [模擬網路釣魚攻擊](/microsoft-365/security/office-365-security/attack-simulation-training)。</span><span class="sxs-lookup"><span data-stu-id="61398-173">To learn more and try out a simulation, see [Simulate a phishing attack](/microsoft-365/security/office-365-security/attack-simulation-training).</span></span>