---
title: Exchange Online Protection 限制
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-limits
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: f866fe3b-a183-4e6d-abd9-bbec0a0c7fae
description: Exchange Online Protection 目前已存在下列限制。 除非另有指定，否則無法設定這些限制。
ms.openlocfilehash: 3c5a8e0c5f9a19c9cae81b3bc1e39bb153af0137
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/14/2020
ms.locfileid: "45133007"
---
# <a name="exchange-online-protection-limits"></a>Exchange Online Protection 限制

Exchange Online Protection 目前已存在下列限制。 除非另有指定，否則無法設定這些限制。 
  
> [!TIP]
> 如需 Exchange Online 中限制的相關資訊，請參閱[Exchange Online 限制](../exchange-online-service-description/exchange-online-limits.md)。 傳輸規則限制也適用於獨立式 EOP 客戶。 Exchange Online 的收件者流量和郵件流量限制不適用於獨立式 EOP 客戶。 
  
- **Domain limit** You can add up to 900 domains per tenant. Subdomains can be included in this 900 limit, or if necessary, as part of a catch-all option, match subdomains. For more information, see [Manage Accepted Domains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).
    
- **郵件大小限制** 獨立式 EOP 客戶的郵件大小上限 (包括附件) 為 150 MB。 
    
- **Number of outbound messages sent** The limit for the number of outbound messages sent through EOP is high enough to ensure that normal email communication is not treated as spam. If you want to send commercial bulk email messages, rather than sending outbound messages through EOP, we recommend that you either use a third-party email service provider (ESP) or send them through your on-premises email servers. 
    
- **Recipient limit** As long as the sending host can split the message into "chunks" of fewer than 500 recipients, no explicit limit is defined. However, each "chunk" is effectively treated as a new message. Too many messages in a short period, messages from a host with a poor reputation, or messages with questionable content could be throttled or blocked. 
    
- **IP 允許或 IP 封鎖清單限制** 在連線篩選器中設定 IP 允許清單或 IP 封鎖清單時，您最多可以指定 1273 個項目，而一個項目就是一個 IP 位址或 CIDR 範圍的 IP 位址 (從 /24 到 /32)。 
    
- **郵件延遲限制**延遲中的郵件會保留在佇列中24小時內。 郵件重試次數是以從收件者的郵件系統收到的錯誤類型為基礎。 郵件會每隔 15 分鐘重試一次。 
    
- **垃圾郵件隔離保留期間**傳送至隔離區的垃圾郵件預設會保留30天。 系統管理員可以透過內容篩選原則降低這個值。 
    
- **End-user spam quarantine notifications** By default, if enabled, end-user spam quarantine notifications are sent every 3 days. They can be configured to be sent every 1 to 15 days. 
    
- **報告和郵件追蹤限制**如需報告和郵件追蹤限制，請參閱[Exchange Online Protection 中報告和郵件追蹤](https://go.microsoft.com/fwlink/?LinkId=394248)中的「報告和郵件追蹤資料可用性和延遲」一節。
    
### <a name="limits-across-eop-options"></a>不同 EOP 選項的限制

|**功能**|****獨立式 EOP****|****EOP 功能 -Exchange Online****|****Exchange Enterprise CAL with Services****|
|:-----|:-----|:-----|:-----|
|網域限制  <br/> |900  <br/> |900  <br/> |900  <br/> |
|郵件大小限制 (包括附件)  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|收件者限制  <br/> |請參閱上方的「收件者限制」  <br/> |從裝載的信箱中傳送時的 500 個收件者；請參閱上方的「收件者限制」以取得其他案例  <br/> |請參閱上方的「收件者限制」  <br/> |
|安全寄件者限制  <br/> |1024 個項目  <br/> |1024 個項目  <br/> ||
|每個原則封鎖的寄件者限制  <br/> |1024 個項目  <br/> |1024 個項目  <br/> ||
|IP 允許或 IP 封鎖清單限制  <br/> |1273 個項目  <br/> |1273 個項目  <br/> |1273 個項目  <br/> |
|郵件延期限制  <br/> |1天，每15分鐘重試一次  <br/> |1天，每15分鐘重試一次  <br/> |1天，每15分鐘重試一次  <br/> |
|垃圾郵件隔離保留期限  <br/> |預設為30天，但可降低  <br/> |預設為30天，但可降低  <br/> |預設為30天，但可降低  <br/> |
|使用者垃圾郵件隔離通知  <br/> |預設為 3 天，可設定為 1 到 15 天  <br/> |預設為 3 天，可設定為 1 到 15 天  <br/> |預設為 3 天，可設定為 1 到 15 天  <br/> |
   

