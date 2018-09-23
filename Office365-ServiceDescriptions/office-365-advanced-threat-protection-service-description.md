---
title: Office 365 進階威脅防護服務說明
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Office 365 進階威脅防護 (ATP) 是一種雲端架構電子郵件篩選服務，提供強大的零時差保護，同時也擁有即時保護組織防止有害連結的功能，可協助保護您的組織抵禦不明惡意軟體和病毒。ATP 具有豐富報告和 URL 追蹤功能，可讓系統管理員深入了解組織中發生的攻擊的類型。
ms.openlocfilehash: 6c7ce44932312b82293b19d85ebac07137716617
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035350"
---
# <a name="office-365-advanced-threat-protection-service-description"></a><span data-ttu-id="920cd-104">Office 365 進階威脅防護服務說明</span><span class="sxs-lookup"><span data-stu-id="920cd-104">Office 365 Advanced Threat Protection Service Description</span></span>

<span data-ttu-id="920cd-p102">Microsoft Office 365 進階威脅防護 (ATP) 是一種雲端架構電子郵件篩選服務，提供強大的零時差保護，同時也擁有即時保護組織防止有害連結的功能，可協助保護您的組織抵禦不明惡意軟體和病毒。ATP 具有豐富報告和 URL 追蹤功能，可讓系統管理員深入了解組織中發生的攻擊的類型。</span><span class="sxs-lookup"><span data-stu-id="920cd-p102">Microsoft Office 365 Advanced Threat Protection (ATP) is a cloud-based email filtering service that helps protect your organization against unknown malware and viruses by providing robust zero-day protection, and includes features to safeguard your organization from harmful links in real time. ATP has rich reporting and URL trace capabilities that give administrators insight into the kind of attacks happening in your organization.</span></span>
  
<span data-ttu-id="920cd-107">下列是您可以使用 ATP 來保護郵件的主要方法：</span><span class="sxs-lookup"><span data-stu-id="920cd-107">The following are the primary ways you can use ATP for messaging protection:</span></span>
  
- <span data-ttu-id="920cd-108">在 Office 365 ATP 僅篩選案例中，ATP 會針對內部部署 Exchange Server 2013 環境、舊式 Exchange Server 版本或任何其他內部部署 SMTP 電子郵件解決方案，提供雲端式電子郵件保護。</span><span class="sxs-lookup"><span data-stu-id="920cd-108">In an Office 365 ATP filtering-only scenario, ATP provides cloud-based email protection for your on-premises Exchange Server 2013 environment, legacy Exchange Server versions, or any other on-premises SMTP email solution.</span></span>
    
- <span data-ttu-id="920cd-p103">Office 365 ATP 可保護 Exchange Online 的雲端託管信箱。若要深入了解 Exchange Online，請參閱 [Exchange Online 服務說明](https://technet.microsoft.com/en-us/library/exchange-online-service-description.aspx)。</span><span class="sxs-lookup"><span data-stu-id="920cd-p103">Office 365 ATP can be enabled to protect Exchange Online cloud-hosted mailboxes. To learn more about Exchange Online, see the [Exchange Online Service Description](https://technet.microsoft.com/en-us/library/exchange-online-service-description.aspx).</span></span>
    
- <span data-ttu-id="920cd-111">在混合部署中，當您混合使用內部部署及雲端信箱並使用 Exchange Online Protection 來進行輸入電子郵件篩選時，可將 ATP 設定為保護您的郵件環境與控制郵件路由。</span><span class="sxs-lookup"><span data-stu-id="920cd-111">In a hybrid deployment, ATP can be configured to protect your messaging environment and control mail routing when you have a mix of on-premises and cloud mailboxes with Exchange Online Protection for inbound email filtering.</span></span>
    
## <a name="office-365-advanced-threat-protection-atp-availability"></a><span data-ttu-id="920cd-112">Office 365 進階威脅防護 (ATP) 可用性</span><span class="sxs-lookup"><span data-stu-id="920cd-112">Office 365 Advanced Threat Protection (ATP) availability</span></span>

<span data-ttu-id="920cd-113">ATP 隨附於 Office 365 企業版 E5、 Office 365 教育版 A5、 及 Microsoft 365 Business。</span><span class="sxs-lookup"><span data-stu-id="920cd-113">ATP is included in Office 365 Enterprise E5, Office 365 Education A5, and Microsoft 365 Business.</span></span> 
  
> [!NOTE]
> <span data-ttu-id="920cd-114">Microsoft 365 Business 中的用戶端相依 ATP 功能將會提供夏季 2018年。</span><span class="sxs-lookup"><span data-stu-id="920cd-114">Client-dependent ATP features in Microsoft 365 Business will be available Summer 2018.</span></span> 
  
<span data-ttu-id="920cd-115">您可以將 ATP 新增至下列 Exchange 與 Office 365 訂閱計劃：</span><span class="sxs-lookup"><span data-stu-id="920cd-115">You can add ATP to the following Exchange and Office 365 subscription plans:</span></span> 
  
- <span data-ttu-id="920cd-116">Exchange Online Plan 1</span><span class="sxs-lookup"><span data-stu-id="920cd-116">Exchange Online Plan 1</span></span>
    
- <span data-ttu-id="920cd-117">Exchange Online Plan 2</span><span class="sxs-lookup"><span data-stu-id="920cd-117">Exchange Online Plan 2</span></span>
    
- <span data-ttu-id="920cd-118">Exchange Online Kiosk</span><span class="sxs-lookup"><span data-stu-id="920cd-118">Exchange Online Kiosk</span></span>
    
- <span data-ttu-id="920cd-119">Exchange Online Protection</span><span class="sxs-lookup"><span data-stu-id="920cd-119">Exchange Online Protection</span></span>
    
- <span data-ttu-id="920cd-120">Office 365 商務基本版</span><span class="sxs-lookup"><span data-stu-id="920cd-120">Office 365 Business Essentials</span></span>
    
- <span data-ttu-id="920cd-121">Office 365 商務進階版</span><span class="sxs-lookup"><span data-stu-id="920cd-121">Office 365 Business Premium</span></span>
    
- <span data-ttu-id="920cd-122">Office 365 Enterprise E1</span><span class="sxs-lookup"><span data-stu-id="920cd-122">Office 365 Enterprise E1</span></span>
    
- <span data-ttu-id="920cd-123">Office 365 Enterprise E3</span><span class="sxs-lookup"><span data-stu-id="920cd-123">Office 365 Enterprise E3</span></span>
    
- <span data-ttu-id="920cd-124">Office 365 企業版 F1</span><span class="sxs-lookup"><span data-stu-id="920cd-124">Office 365 Enterprise F1</span></span>
    
- <span data-ttu-id="920cd-125">Office 365 A1</span><span class="sxs-lookup"><span data-stu-id="920cd-125">Office 365 A1</span></span>
    
- <span data-ttu-id="920cd-126">Office 365 A3</span><span class="sxs-lookup"><span data-stu-id="920cd-126">Office 365 A3</span></span>
    
<span data-ttu-id="920cd-127">若要購買 Office 365 進階威脅防護，請參閱 [Office 365 進階威脅防護](https://go.microsoft.com/fwlink/p/?LinkId=294201)。</span><span class="sxs-lookup"><span data-stu-id="920cd-127">To buy Office 365 Advanced Threat Protection, see [Office 365 Advanced Threat Protection](https://go.microsoft.com/fwlink/p/?LinkId=294201).</span></span>
  
<span data-ttu-id="920cd-128">若要跨方案比較功能，請參閱 [比較 Office 365 for Business 方案](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409)。</span><span class="sxs-lookup"><span data-stu-id="920cd-128">To compare features across plans, see [Compare Office 365 for Business plans](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409).</span></span>
  
## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a><span data-ttu-id="920cd-129">Office 365 進階威脅防護 (ATP) 的新增功能</span><span class="sxs-lookup"><span data-stu-id="920cd-129">What's new in Office 365 Advanced Threat Protection (ATP)</span></span>

<span data-ttu-id="920cd-130">如需 ATP 中新功能的詳細資訊，請參閱 [Office 365 中的 ATP 安全連結](https://go.microsoft.com/fwlink/?linkid=846016)。</span><span class="sxs-lookup"><span data-stu-id="920cd-130">For information about new features in ATP, see [ATP safe links in Office 365](https://go.microsoft.com/fwlink/?linkid=846016).</span></span>
  
## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a><span data-ttu-id="920cd-131">Office 365 進階威脅防護 (ATP) 的需求</span><span class="sxs-lookup"><span data-stu-id="920cd-131">Requirements for Office 365 Advanced Threat Protection (ATP)</span></span>

<span data-ttu-id="920cd-p104">ATP 可搭配任何 SMTP 郵件傳輸代理程式使用，例如 Microsoft Exchange Server 2013。如需 ATP 所支援的作業系統、網頁瀏覽器和語言的資訊，請參閱 [Exchange Online Protection 中的 Exchange 系統管理中心](https://go.microsoft.com/fwlink/p/?LinkId=282381)中的＜支援的瀏覽器＞和＜支援語言＞小節。</span><span class="sxs-lookup"><span data-stu-id="920cd-p104">ATP can be used with any SMTP mail transfer agent, such as Microsoft Exchange Server 2013. For information about the operating systems, web browsers, and languages that are supported by ATP, see the "Supported browsers" and "Supported languages" sections in [Exchange Admin Center in Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).</span></span>
  
## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a><span data-ttu-id="920cd-134">各進階威脅防護 (ATP) 計劃中可用的功能</span><span class="sxs-lookup"><span data-stu-id="920cd-134">Feature availability across Advanced Threat Protection (ATP) plans</span></span>

<span data-ttu-id="920cd-p105">每項功能如下所列。提到 Exchange Online 時，通常是指 Office 365 企業版服務系列。</span><span class="sxs-lookup"><span data-stu-id="920cd-p105">Each feature is listed below. When Exchange Online is mentioned, it typically refers to the Office 365 Enterprise service family.</span></span>
  
|<span data-ttu-id="920cd-137">**功能**</span><span class="sxs-lookup"><span data-stu-id="920cd-137">**Feature**</span></span>|<span data-ttu-id="920cd-138">**ATP 獨立**</span><span class="sxs-lookup"><span data-stu-id="920cd-138">**ATP standalone**</span></span>|<span data-ttu-id="920cd-139">**Exchange Online Protection**</span><span class="sxs-lookup"><span data-stu-id="920cd-139">**Exchange Online Protection**</span></span>|
|:-----|:-----|:-----|
|<span data-ttu-id="920cd-140">安全連結</span><span class="sxs-lookup"><span data-stu-id="920cd-140">Safe Links</span></span>  <br/> |<span data-ttu-id="920cd-141">是</span><span class="sxs-lookup"><span data-stu-id="920cd-141">Yes</span></span>  <br/> |<span data-ttu-id="920cd-142">否</span><span class="sxs-lookup"><span data-stu-id="920cd-142">No</span></span>  <br/> |
|<span data-ttu-id="920cd-143">安全附件</span><span class="sxs-lookup"><span data-stu-id="920cd-143">Safe Attachments</span></span>  <br/> |<span data-ttu-id="920cd-144">是</span><span class="sxs-lookup"><span data-stu-id="920cd-144">Yes</span></span>  <br/> |<span data-ttu-id="920cd-145">否</span><span class="sxs-lookup"><span data-stu-id="920cd-145">No</span></span>  <br/> |
|<span data-ttu-id="920cd-146">詐騙智慧</span><span class="sxs-lookup"><span data-stu-id="920cd-146">Spoof intelligence</span></span>  <br/> |<span data-ttu-id="920cd-147">是</span><span class="sxs-lookup"><span data-stu-id="920cd-147">Yes</span></span>  <br/> |<span data-ttu-id="920cd-148">否</span><span class="sxs-lookup"><span data-stu-id="920cd-148">No</span></span>  <br/> |
|<span data-ttu-id="920cd-149">隔離區</span><span class="sxs-lookup"><span data-stu-id="920cd-149">Quarantine</span></span>  <br/> |<span data-ttu-id="920cd-150">是</span><span class="sxs-lookup"><span data-stu-id="920cd-150">Yes</span></span>  <br/> |<span data-ttu-id="920cd-151">是</span><span class="sxs-lookup"><span data-stu-id="920cd-151">Yes</span></span>  <br/> |
|<span data-ttu-id="920cd-152">進階反網路釣魚功能</span><span class="sxs-lookup"><span data-stu-id="920cd-152">Advanced anti-phishing capabilities</span></span>  <br/> |<span data-ttu-id="920cd-153">是</span><span class="sxs-lookup"><span data-stu-id="920cd-153">Yes</span></span>  <br/> |<span data-ttu-id="920cd-154">否</span><span class="sxs-lookup"><span data-stu-id="920cd-154">No</span></span>  <br/> |
   
## <a name="advanced-threat-protection-atp-capabilities"></a><span data-ttu-id="920cd-155">進階威脅防護 (ATP) 功能</span><span class="sxs-lookup"><span data-stu-id="920cd-155">Advanced Threat Protection (ATP) Capabilities</span></span>

### <a name="safe-links"></a><span data-ttu-id="920cd-156">安全連結</span><span class="sxs-lookup"><span data-stu-id="920cd-156">Safe Links</span></span>

<span data-ttu-id="920cd-p106">ATP 安全連結功能主動保護您的使用者，抵禦郵件中的惡意超連結。因為可動態封鎖惡意連結，允許存取無害連結，所以每次使用者按一下連結時都能受到持續保護。</span><span class="sxs-lookup"><span data-stu-id="920cd-p106">The ATP Safe Links feature proactively protects your users from malicious hyperlinks in a message. The protection remains every time they click the link, as malicious links are dynamically blocked while good links can be accessed.</span></span>
  
### <a name="safe-attachments"></a><span data-ttu-id="920cd-159">安全附件</span><span class="sxs-lookup"><span data-stu-id="920cd-159">Safe Attachments</span></span>

<span data-ttu-id="920cd-p107">安全附件可防止不明的惡意軟體和病毒，並提供零時差保護來保護郵件系統。所有沒有已知病毒/惡意軟體簽章的訊息與附件將被路由傳送至特殊的環境，其中 ATP 會使用不同的機器學習與分析技術來偵測惡意的意圖。如果未偵測到可疑活動，即會釋出訊息傳遞到信箱。</span><span class="sxs-lookup"><span data-stu-id="920cd-p107">Safe Attachments protects against unknown malware and viruses, and provides zero-day protection to safeguard your messaging system. All messages and attachments that don't have a known virus/malware signature are routed to a special environment where ATP uses a variety of machine learning and analysis techniques to detect malicious intent. If no suspicious activity is detected, the message is released for delivery to the mailbox.</span></span> 
  
### <a name="spoof-intelligence"></a><span data-ttu-id="920cd-163">詐騙智慧</span><span class="sxs-lookup"><span data-stu-id="920cd-163">Spoof intelligence</span></span>

<span data-ttu-id="920cd-p108">詐騙智慧偵測時寄件者看起來會將代表一個或多個使用者帳戶的郵件傳送內的其中一個貴組織的網域。它可讓您檢閱所有寄件者詐騙您的網域，然後選擇 [允許繼續或封鎖的寄件者寄件者。詐騙智慧有安全性&amp;反垃圾郵件設定] 頁面上的規範中心。</span><span class="sxs-lookup"><span data-stu-id="920cd-p108">Spoof intelligence detects when a sender appears to be sending mail on behalf of one or more user accounts within one of your organization's domains. It enables you to review all senders who are spoofing your domain, and then choose to allow the sender to continue or block the sender. Spoof intelligence is available in the Security &amp; Compliance Center on the Anti-spam settings page.</span></span>
  
### <a name="quarantine"></a><span data-ttu-id="920cd-167">隔離區</span><span class="sxs-lookup"><span data-stu-id="920cd-167">Quarantine</span></span>

<span data-ttu-id="920cd-p109">由 Office 365 服務識別為垃圾郵件、大量郵件、網路釣魚郵件、包含惡意程式碼的郵件，或因為它們符合郵件流程規則的郵件都可以傳送至隔離區。根據預設，Office 365 會直接將網路釣魚郵件和包含惡意程式碼的郵件傳送至隔離區。經過授權的使用者可以檢視、刪除或管理已傳送至隔離區的電子郵件郵件。</span><span class="sxs-lookup"><span data-stu-id="920cd-p109">Messages identified by the Office 365 service as spam, bulk mail, phishing mail, containing malware, or because they matched a mail flow rule can be sent to quarantine. By default, Office 365 sends phishing messages and messages containing malware directly to quarantine. Authorized users can review, delete, or manage email messages sent to quarantine.</span></span>
  
### <a name="advanced-anti-phishing-capabilities"></a><span data-ttu-id="920cd-171">進階反網路釣魚功能</span><span class="sxs-lookup"><span data-stu-id="920cd-171">Advanced anti-phishing capabilities</span></span>

<span data-ttu-id="920cd-172">這項功能會使用機器學習模型來偵測網路釣魚郵件。</span><span class="sxs-lookup"><span data-stu-id="920cd-172">This feature uses machine learning models to detect phishing messages.</span></span> 
  
