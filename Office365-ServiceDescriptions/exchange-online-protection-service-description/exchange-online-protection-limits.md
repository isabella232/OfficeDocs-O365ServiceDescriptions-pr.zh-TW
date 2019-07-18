---
title: Exchange Online Protection 限制
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-limits
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: f866fe3b-a183-4e6d-abd9-bbec0a0c7fae
description: Exchange Online protection 目前有下列限制。 這些限制會無法加以設定，除非另有指定。
ms.openlocfilehash: badfa1684b9843cfa2aec41d42ccd742f0184c00
ms.sourcegitcommit: 96dc758c790ddaf05f5c2b836451b417729cf119
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/18/2019
ms.locfileid: "35776704"
---
# <a name="exchange-online-protection-limits"></a>Exchange Online Protection 限制

Exchange Online protection 目前有下列限制。 這些限制會無法加以設定，除非另有指定。 
  
> [!TIP]
> 如需關於 Exchange Online 中之權限的詳細資訊，請參閱 [Exchange Online 限制](../exchange-online-service-description/exchange-online-limits.md)。傳輸規則限制也適用於獨立式 EOP 客戶。Exchange Online 的收件者流量和郵件流量限制不適用於獨立式 EOP 客戶。 
  
- **網域限制** 您可以為每位租用戶新增多達 900 個網域。子網域可以納入這項 900 個網域的限制內，或者視需要做為 catch-all 選項相符子網域的一部分。如需詳細資訊，請參閱 [管理 EOP 中公認的網域](https://go.microsoft.com/fwlink/p/?LinkId=282239)。
    
- **郵件大小限制** 獨立式 EOP 客戶的郵件大小上限 (包括附件) 為 150 MB。 
    
- **傳送的外寄郵件數目** 透過 EOP 傳送的外寄郵件數目限制夠高，可確保不會將正常電子郵件通訊視為垃圾郵件。如果您要傳送大量商業電子郵件，而非經由 EOP 傳送輸出郵件，建議您使用協力廠商電子郵件服務提供者 (ESP) 或透過內部部署電子郵件伺服器進行傳送。 
    
- **收件者限制** 只要傳送主機可以將訊息分割為少於 500 個收件者的「區塊」，就沒有明確定義的限制。不過，每個「區塊」有效地被視為新的訊息。短時間內太多訊息、訊息來自不良聲譽的主機，或者訊息包含有問題的內容，都可能被節流或封鎖。 
    
- **IP 允許或 IP 封鎖清單限制** 在連線篩選器中設定 IP 允許清單或 IP 封鎖清單時，您最多可以指定 1273 個項目，而一個項目就是一個 IP 位址或 CIDR 範圍的 IP 位址 (從 /24 到 /32)。 
    
- **郵件延期限制** 延期的郵件會保留在我們的佇列中 2 天。郵件重試次數是以從收件者的郵件系統收到的錯誤類型為基礎。郵件會每隔 15 分鐘重試一次。 
    
- **垃圾郵件隔離保留期限** 根據預設，傳送至隔離區的垃圾郵件會保留 15 天。系統管理員可以透過內容篩選原則降低這個值。 
    
- **使用者垃圾郵件隔離通知** 如果啟用，預設會每隔 3 天傳送一次使用者垃圾郵件隔離通知。可以將它們設定為每隔 1 到 15 天傳送一次。 
    
- **報告和郵件追蹤限制** 如需報告和郵件追蹤限制，請參閱 [Exchange Online Protection 的報告與郵件追蹤](https://go.microsoft.com/fwlink/?LinkId=394248) 中的＜報告和郵件追蹤資料的可用性與延遲＞。
    
### <a name="limits-across-eop-options"></a>不同 EOP 選項的限制

|**功能**|****獨立式 EOP****|****EOP 功能 -Exchange Online****|****Exchange Enterprise CAL with Services****|
|:-----|:-----|:-----|:-----|
|網域限制  <br/> |900  <br/> |900  <br/> |900  <br/> |
|郵件大小限制 (包括附件)  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|收件者限制  <br/> |請參閱上方的「收件者限制」  <br/> |從裝載的信箱中傳送時的 500 個收件者；請參閱上方的「收件者限制」以取得其他案例  <br/> |請參閱上方的「收件者限制」  <br/> |
|安全寄件者限制  <br/> |1024 個項目  <br/> |1024 個項目  <br/> ||
|封鎖的寄件者限制  <br/> |1024 個項目  <br/> |1024 個項目  <br/> ||
|IP 允許或 IP 封鎖清單限制  <br/> |1273 個項目  <br/> |1273 個項目  <br/> |1273 個項目  <br/> |
|郵件延期限制  <br/> |2 天，每隔 15 分鐘重試一次  <br/> |2 天，每隔 15 分鐘重試一次  <br/> |2 天，每隔 15 分鐘重試一次  <br/> |
|垃圾郵件隔離保留期限  <br/> |預設為 15 天但是可以降低  <br/> |預設為 15 天但是可以降低  <br/> |預設為 15 天但是可以降低  <br/> |
|使用者垃圾郵件隔離通知  <br/> |預設為 3 天，可設定為 1 到 15 天  <br/> |預設為 3 天，可設定為 1 到 15 天  <br/> |預設為 3 天，可設定為 1 到 15 天  <br/> |
   

