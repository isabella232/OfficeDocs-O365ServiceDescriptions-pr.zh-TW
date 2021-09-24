---
title: Exchange Online Protection 限制
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-limits
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
ms.assetid: f866fe3b-a183-4e6d-abd9-bbec0a0c7fae
description: Exchange Online Protection 目前已存在下列限制。 除非另有指定，否則無法設定這些限制。
ms.openlocfilehash: 93afb5b4c3ab44703f8f77e3bb61d1d822feba9f
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/24/2021
ms.locfileid: "59670683"
---
# <a name="exchange-online-protection-limits"></a>Exchange Online Protection 限制

Exchange Online Protection 目前已存在下列限制。 除非另有指定，否則無法設定這些限制。 
  
> [!TIP]
> 如需 Exchange Online 中限制的詳細資訊，請參閱[Exchange Online 限制](../exchange-online-service-description/exchange-online-limits.md)。 傳輸規則限制也適用於獨立式 EOP 客戶。 Exchange Online 的收件者流量和郵件流量限制不適用於獨立式 EOP 客戶。 
  
- **網域限制** -您最多可以針對每個承租人新增900個網域。 子網域可以納入這項 900 個網域的限制內，或者視需要做為 catch-all 選項相符子網域的一部分。 如需詳細資訊，請參閱 [管理 EOP 中公認的網域](/microsoft-365/security/office-365-security/exchange-online-protection-overview)。

- **遠端網域限制** -您每個租使用者最多可以新增200個遠端網域。
    
- **郵件大小限制** -EOP 獨立客戶（包括附件）的郵件大小上限為 150 MB。 
    
- **已傳送的輸出郵件數目** -透過 EOP 傳送的輸出郵件數目限制，會足以確保一般電子郵件通訊不會被視為垃圾郵件。 如果您要傳送大量商業電子郵件，而非經由 EOP 傳送輸出郵件，建議您使用協力廠商電子郵件服務提供者 (ESP) 或透過內部部署電子郵件伺服器進行傳送。 
    
- **收件者限制** -只要傳送主機可以將郵件分割成 "區塊" 少於500收件者，則不會定義明確限制。 不過，每個「區塊」有效地被視為新的訊息。 短時間內太多訊息、訊息來自不良聲譽的主機，或者訊息包含有問題的內容，都可能被節流或封鎖。 
    
- **Ip allow 或 Ip 封鎖清單限制** -當您在連線篩選器中設定 ip 允許清單或 ip 封鎖清單時，您可以指定最多1273個專案，其中一個專案是單一 ip 位址或從/24 到/32 的 CIDR 範圍的 ip 位址。 
    
- **郵件延期限制** -延期的郵件會保留在佇列中24小時。 郵件重試次數是以從收件者的郵件系統收到的錯誤類型為基礎。 郵件會每隔 15 分鐘重試一次。 
    
- **垃圾郵件隔離保留期間** -依預設，傳送至隔離區的垃圾郵件會保留30天。 系統管理員可以透過內容篩選原則降低這個值。 
    
- **使用者垃圾郵件隔離通知** -依預設，如果啟用，則每3天會傳送一次使用者垃圾郵件隔離通知。 可以將它們設定為每隔 1 到 15 天傳送一次。 
    
- **報告和郵件追蹤限制**-若為報告和郵件追蹤限制，請參閱 Exchange Online Protection 中的 [報告和郵件追蹤](/microsoft-365/security/office-365-security/reporting-and-message-trace-in-exchange-online-protection)中的「報告和郵件追蹤資料可用性和延遲」一節。
    
### <a name="limits-across-eop-options"></a>不同 EOP 選項的限制

| 功能 | 獨立 EOP | Exchange Online 中的 EOP 功能 | Exchange Enterprise CAL with Services |
|:-----|:-----|:-----|:-----|
|網域限制  <br/> |900  <br/> |900  <br/> |900  <br/> |
|遠端網域限制  <br/> |200  <br/> |200  <br/> |200  <br/> |
|郵件大小限制 (包括附件)  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|收件者限制  <br/> |請參閱上方的「收件者限制」  <br/> |從裝載的信箱中傳送時的 500 個收件者；請參閱上方的「收件者限制」以取得其他案例  <br/> |請參閱上方的「收件者限制」  <br/> |
|安全寄件者限制  <br/> |1024 個項目  <br/> |1024 個項目  <br/> ||
|每個原則封鎖的寄件者限制  <br/> |1024 個項目  <br/> |1024 個項目  <br/> ||
|IP 允許或 IP 封鎖清單限制  <br/> |1273 個項目  <br/> |1273 個項目  <br/> |1273 個項目  <br/> |
|郵件延期限制  <br/> |1天，每15分鐘重試一次  <br/> |1天，每15分鐘重試一次  <br/> |1天，每15分鐘重試一次  <br/> |
|垃圾郵件隔離保留期限  <br/> |預設為30天，但可降低  <br/> |預設為30天，但可降低  <br/> |預設為30天，但可降低  <br/> |
|使用者垃圾郵件隔離通知  <br/> |預設為 3 天，可設定為 1 到 15 天  <br/> |預設為 3 天，可設定為 1 到 15 天  <br/> |預設為 3 天，可設定為 1 到 15 天  <br/> |
