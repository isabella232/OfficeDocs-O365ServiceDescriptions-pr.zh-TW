---
title: Exchange Online Protection 限制
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-limits
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: f866fe3b-a183-4e6d-abd9-bbec0a0c7fae
description: Exchange Online protection 目前有下列限制。 這些限制會無法加以設定，除非另有指定。
ms.openlocfilehash: 3c96449b2694dba470f6860f8324d86bb84d3774
ms.sourcegitcommit: 68eee0c2885fd112e37eea27370c3f8c1f0831cb
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 03/07/2019
ms.locfileid: "30468140"
---
# <a name="exchange-online-protection-limits"></a><span data-ttu-id="8a03c-104">Exchange Online Protection 限制</span><span class="sxs-lookup"><span data-stu-id="8a03c-104">Exchange Online Protection Limits</span></span>

<span data-ttu-id="8a03c-105">Exchange Online protection 目前有下列限制。</span><span class="sxs-lookup"><span data-stu-id="8a03c-105">The following limits currently exist for Exchange Online Protection.</span></span> <span data-ttu-id="8a03c-106">這些限制會無法加以設定，除非另有指定。</span><span class="sxs-lookup"><span data-stu-id="8a03c-106">These limits are not configurable, unless specified otherwise.</span></span> 
  
> [!TIP]
> <span data-ttu-id="8a03c-p103">如需關於 Exchange Online 中之權限的詳細資訊，請參閱 [Exchange Online 限制](../exchange-online-service-description/exchange-online-limits.md)。傳輸規則限制也適用於獨立式 EOP 客戶。Exchange Online 的收件者流量和郵件流量限制不適用於獨立式 EOP 客戶。</span><span class="sxs-lookup"><span data-stu-id="8a03c-p103">For more information about limits in Exchange Online, see [Exchange Online Limits](../exchange-online-service-description/exchange-online-limits.md). The transport rule limits also apply to EOP standalone customers. The recipient rate and message rate limits for Exchange Online are not applicable for EOP standalone customers.</span></span> 
  
- <span data-ttu-id="8a03c-p104">**網域限制** 您可以為每位租用戶新增多達 900 個網域。子網域可以納入這項 900 個網域的限制內，或者視需要做為 catch-all 選項相符子網域的一部分。如需詳細資訊，請參閱 [管理 EOP 中公認的網域](https://go.microsoft.com/fwlink/p/?LinkId=282239)。</span><span class="sxs-lookup"><span data-stu-id="8a03c-p104">**Domain limit** You can add up to 900 domains per tenant. Subdomains can be included in this 900 limit, or if necessary, as part of a catch-all option, match subdomains. For more information, see [Manage Accepted Domains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).</span></span>
    
- <span data-ttu-id="8a03c-113">**郵件大小限制** 獨立式 EOP 客戶的郵件大小上限 (包括附件) 為 150 MB。</span><span class="sxs-lookup"><span data-stu-id="8a03c-113">**Message size limit** The maximum message size for EOP standalone customers, including attachments, is 150 MB.</span></span> 
    
- <span data-ttu-id="8a03c-p105">**傳送的外寄郵件數目** 透過 EOP 傳送的外寄郵件數目限制夠高，可確保不會將正常電子郵件通訊視為垃圾郵件。如果您要傳送大量商業電子郵件，而非經由 EOP 傳送輸出郵件，建議您使用協力廠商電子郵件服務提供者 (ESP) 或透過內部部署電子郵件伺服器進行傳送。</span><span class="sxs-lookup"><span data-stu-id="8a03c-p105">**Number of outbound messages sent** The limit for the number of outbound messages sent through EOP is high enough to ensure that normal email communication is not treated as spam. If you want to send commercial bulk email messages, rather than sending outbound messages through EOP, we recommend that you either use a third-party email service provider (ESP) or send them through your on-premises email servers.</span></span> 
    
- <span data-ttu-id="8a03c-p106">**收件者限制** 只要傳送主機可以將訊息分割為少於 500 個收件者的「區塊」，就沒有明確定義的限制。不過，每個「區塊」有效地被視為新的訊息。短時間內太多訊息、訊息來自不良聲譽的主機，或者訊息包含有問題的內容，都可能被節流或封鎖。</span><span class="sxs-lookup"><span data-stu-id="8a03c-p106">**Recipient limit** As long as the sending host can split the message into "chunks" of fewer than 500 recipients, no explicit limit is defined. However, each "chunk" is effectively treated as a new message. Too many messages in a short period, messages from a host with a poor reputation, or messages with questionable content could be throttled or blocked.</span></span> 
    
- <span data-ttu-id="8a03c-119">**IP 允許或 IP 封鎖清單限制** 在連線篩選器中設定 IP 允許清單或 IP 封鎖清單時，您最多可以指定 1273 個項目，而一個項目就是一個 IP 位址或 CIDR 範圍的 IP 位址 (從 /24 到 /32)。</span><span class="sxs-lookup"><span data-stu-id="8a03c-119">**IP Allow or IP Block list limit** When configuring an IP Allow list or an IP Block list in the connection filter, you can specify a maximum of 1273 entries, where an entry is either a single IP address or a CIDR range of IP addresses from /24 to /32.</span></span> 
    
- <span data-ttu-id="8a03c-p107">**郵件延期限制** 延期的郵件會保留在我們的佇列中 2 天。郵件重試次數是以從收件者的郵件系統收到的錯誤類型為基礎。郵件會每隔 15 分鐘重試一次。</span><span class="sxs-lookup"><span data-stu-id="8a03c-p107">**Message deferral limit** Messages in deferral will remain in our queues for 2 days. Message retry attempts are based on the error type received from the recipient's mail system. Messages are retried every 15 minutes.</span></span> 
    
- <span data-ttu-id="8a03c-p108">**垃圾郵件隔離保留期限** 根據預設，傳送至隔離區的垃圾郵件會保留 15 天。系統管理員可以透過內容篩選原則降低這個值。</span><span class="sxs-lookup"><span data-stu-id="8a03c-p108">**Spam quarantine retention period** By default, spam messages sent to the quarantine are retained for 15 days. Administrators can lower this value via content filter policies.</span></span> 
    
- <span data-ttu-id="8a03c-p109">**使用者垃圾郵件隔離通知** 如果啟用，預設會每隔 3 天傳送一次使用者垃圾郵件隔離通知。可以將它們設定為每隔 1 到 15 天傳送一次。</span><span class="sxs-lookup"><span data-stu-id="8a03c-p109">**End-user spam quarantine notifications** By default, if enabled, end-user spam quarantine notifications are sent every 3 days. They can be configured to be sent every 1 to 15 days.</span></span> 
    
- <span data-ttu-id="8a03c-127">**報告和郵件追蹤限制** 如需報告和郵件追蹤限制，請參閱 [Exchange Online Protection 的報告與郵件追蹤](https://go.microsoft.com/fwlink/?LinkId=394248) 中的＜報告和郵件追蹤資料的可用性與延遲＞。</span><span class="sxs-lookup"><span data-stu-id="8a03c-127">**Reporting and message trace limits** For reporting and message trace limits, see the "Reporting and message trace data availability and latency" section in [Reporting and Message Trace in Exchange Online Protection](https://go.microsoft.com/fwlink/?LinkId=394248).</span></span>
    
### <a name="limits-across-eop-options"></a><span data-ttu-id="8a03c-128">不同 EOP 選項的限制</span><span class="sxs-lookup"><span data-stu-id="8a03c-128">Limits across EOP options</span></span>

|<span data-ttu-id="8a03c-129">**功能**</span><span class="sxs-lookup"><span data-stu-id="8a03c-129">**Feature**</span></span>|<span data-ttu-id="8a03c-130">\*\*\*\*獨立式 EOP\*\*\*\*</span><span class="sxs-lookup"><span data-stu-id="8a03c-130">\*\*\*\*EOP Standalone\*\*\*\*</span></span>|<span data-ttu-id="8a03c-131">\*\*\*\*EOP 功能 -Exchange Online\*\*\*\*</span><span class="sxs-lookup"><span data-stu-id="8a03c-131">\*\*\*\*EOP features in Exchange Online\*\*\*\*</span></span>|<span data-ttu-id="8a03c-132">\*\*\*\*Exchange Enterprise CAL with Services\*\*\*\*</span><span class="sxs-lookup"><span data-stu-id="8a03c-132">\*\*\*\*Exchange Enterprise CAL with Services\*\*\*\*</span></span>|
|:-----|:-----|:-----|:-----|
|<span data-ttu-id="8a03c-133">網域限制</span><span class="sxs-lookup"><span data-stu-id="8a03c-133">Domain limit</span></span>  <br/> |<span data-ttu-id="8a03c-134">900</span><span class="sxs-lookup"><span data-stu-id="8a03c-134">900</span></span>  <br/> |<span data-ttu-id="8a03c-135">900</span><span class="sxs-lookup"><span data-stu-id="8a03c-135">900</span></span>  <br/> |<span data-ttu-id="8a03c-136">900</span><span class="sxs-lookup"><span data-stu-id="8a03c-136">900</span></span>  <br/> |
|<span data-ttu-id="8a03c-137">郵件大小限制 (包括附件)</span><span class="sxs-lookup"><span data-stu-id="8a03c-137">Message size limit (including attachments)</span></span>  <br/> |<span data-ttu-id="8a03c-138">150 MB</span><span class="sxs-lookup"><span data-stu-id="8a03c-138">150 MB</span></span>  <br/> |<span data-ttu-id="8a03c-139">150 MB </span><span class="sxs-lookup"><span data-stu-id="8a03c-139">150 MB</span></span>  <br/> |<span data-ttu-id="8a03c-140">150 MB</span><span class="sxs-lookup"><span data-stu-id="8a03c-140">150 MB</span></span>  <br/> |
|<span data-ttu-id="8a03c-141">收件者限制</span><span class="sxs-lookup"><span data-stu-id="8a03c-141">Recipient limit</span></span>  <br/> |<span data-ttu-id="8a03c-142">請參閱上方的「收件者限制」</span><span class="sxs-lookup"><span data-stu-id="8a03c-142">See "Recipient limit" above</span></span>  <br/> |<span data-ttu-id="8a03c-143">從裝載的信箱中傳送時的 500 個收件者；請參閱上方的「收件者限制」以取得其他案例</span><span class="sxs-lookup"><span data-stu-id="8a03c-143">500 recipients when sending from a hosted mailbox; see "Recipient limit" above for other scenarios</span></span>  <br/> |<span data-ttu-id="8a03c-144">請參閱上方的「收件者限制」</span><span class="sxs-lookup"><span data-stu-id="8a03c-144">See "Recipient limit" above</span></span>  <br/> |
|<span data-ttu-id="8a03c-145">安全寄件者限制</span><span class="sxs-lookup"><span data-stu-id="8a03c-145">Safe sender limit</span></span>  <br/> |<span data-ttu-id="8a03c-146">1024 個項目</span><span class="sxs-lookup"><span data-stu-id="8a03c-146">1024 entries</span></span>  <br/> |<span data-ttu-id="8a03c-147">1024 個項目</span><span class="sxs-lookup"><span data-stu-id="8a03c-147">1024 entries</span></span>  <br/> ||
|<span data-ttu-id="8a03c-148">封鎖的寄件者限制</span><span class="sxs-lookup"><span data-stu-id="8a03c-148">Blocked sender limit</span></span>  <br/> |<span data-ttu-id="8a03c-149">1024 個項目</span><span class="sxs-lookup"><span data-stu-id="8a03c-149">1024 entries</span></span>  <br/> |<span data-ttu-id="8a03c-150">1024 個項目</span><span class="sxs-lookup"><span data-stu-id="8a03c-150">1024 entries</span></span>  <br/> ||
|<span data-ttu-id="8a03c-151">IP 允許或 IP 封鎖清單限制</span><span class="sxs-lookup"><span data-stu-id="8a03c-151">IP Allow or IP Block list limit</span></span>  <br/> |<span data-ttu-id="8a03c-152">1273 個項目</span><span class="sxs-lookup"><span data-stu-id="8a03c-152">1273 entries</span></span>  <br/> |<span data-ttu-id="8a03c-153">1273 個項目</span><span class="sxs-lookup"><span data-stu-id="8a03c-153">1273 entries</span></span>  <br/> |<span data-ttu-id="8a03c-154">1273 個項目</span><span class="sxs-lookup"><span data-stu-id="8a03c-154">1273 entries</span></span>  <br/> |
|<span data-ttu-id="8a03c-155">郵件延期限制</span><span class="sxs-lookup"><span data-stu-id="8a03c-155">Message deferral limit</span></span>  <br/> |<span data-ttu-id="8a03c-156">2 天，每隔 15 分鐘重試一次</span><span class="sxs-lookup"><span data-stu-id="8a03c-156">2 days, retried every 15 minutes</span></span>  <br/> |<span data-ttu-id="8a03c-157">2 天，每隔 15 分鐘重試一次</span><span class="sxs-lookup"><span data-stu-id="8a03c-157">2 days, retried every 15 minutes</span></span>  <br/> |<span data-ttu-id="8a03c-158">2 天，每隔 15 分鐘重試一次</span><span class="sxs-lookup"><span data-stu-id="8a03c-158">2 days, retried every 15 minutes</span></span>  <br/> |
|<span data-ttu-id="8a03c-159">垃圾郵件隔離保留期限</span><span class="sxs-lookup"><span data-stu-id="8a03c-159">Spam quarantine retention period</span></span>  <br/> |<span data-ttu-id="8a03c-160">預設為 15 天但是可以降低</span><span class="sxs-lookup"><span data-stu-id="8a03c-160">15 days by default but can be lowered</span></span>  <br/> |<span data-ttu-id="8a03c-161">預設為 15 天但是可以降低</span><span class="sxs-lookup"><span data-stu-id="8a03c-161">15 days by default but can be lowered</span></span>  <br/> |<span data-ttu-id="8a03c-162">預設為 15 天但是可以降低</span><span class="sxs-lookup"><span data-stu-id="8a03c-162">15 days by default but can be lowered</span></span>  <br/> |
|<span data-ttu-id="8a03c-163">使用者垃圾郵件隔離通知</span><span class="sxs-lookup"><span data-stu-id="8a03c-163">End-user spam quarantine notifications</span></span>  <br/> |<span data-ttu-id="8a03c-164">預設為 3 天，可設定為 1 到 15 天</span><span class="sxs-lookup"><span data-stu-id="8a03c-164">3 days by default, configurable from 1 to 15 days</span></span>  <br/> |<span data-ttu-id="8a03c-165">預設為 3 天，可設定為 1 到 15 天</span><span class="sxs-lookup"><span data-stu-id="8a03c-165">3 days by default, configurable from 1 to 15 days</span></span>  <br/> |<span data-ttu-id="8a03c-166">預設為 3 天，可設定為 1 到 15 天</span><span class="sxs-lookup"><span data-stu-id="8a03c-166">3 days by default, configurable from 1 to 15 days</span></span>  <br/> |
   

