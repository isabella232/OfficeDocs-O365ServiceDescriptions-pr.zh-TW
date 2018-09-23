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
# <a name="office-365-advanced-threat-protection-service-description"></a>Office 365 進階威脅防護服務說明

Microsoft Office 365 進階威脅防護 (ATP) 是一種雲端架構電子郵件篩選服務，提供強大的零時差保護，同時也擁有即時保護組織防止有害連結的功能，可協助保護您的組織抵禦不明惡意軟體和病毒。ATP 具有豐富報告和 URL 追蹤功能，可讓系統管理員深入了解組織中發生的攻擊的類型。
  
下列是您可以使用 ATP 來保護郵件的主要方法：
  
- 在 Office 365 ATP 僅篩選案例中，ATP 會針對內部部署 Exchange Server 2013 環境、舊式 Exchange Server 版本或任何其他內部部署 SMTP 電子郵件解決方案，提供雲端式電子郵件保護。
    
- Office 365 ATP 可保護 Exchange Online 的雲端託管信箱。若要深入了解 Exchange Online，請參閱 [Exchange Online 服務說明](https://technet.microsoft.com/en-us/library/exchange-online-service-description.aspx)。
    
- 在混合部署中，當您混合使用內部部署及雲端信箱並使用 Exchange Online Protection 來進行輸入電子郵件篩選時，可將 ATP 設定為保護您的郵件環境與控制郵件路由。
    
## <a name="office-365-advanced-threat-protection-atp-availability"></a>Office 365 進階威脅防護 (ATP) 可用性

ATP 隨附於 Office 365 企業版 E5、 Office 365 教育版 A5、 及 Microsoft 365 Business。 
  
> [!NOTE]
> Microsoft 365 Business 中的用戶端相依 ATP 功能將會提供夏季 2018年。 
  
您可以將 ATP 新增至下列 Exchange 與 Office 365 訂閱計劃： 
  
- Exchange Online Plan 1
    
- Exchange Online Plan 2
    
- Exchange Online Kiosk
    
- Exchange Online Protection
    
- Office 365 商務基本版
    
- Office 365 商務進階版
    
- Office 365 Enterprise E1
    
- Office 365 Enterprise E3
    
- Office 365 企業版 F1
    
- Office 365 A1
    
- Office 365 A3
    
若要購買 Office 365 進階威脅防護，請參閱 [Office 365 進階威脅防護](https://go.microsoft.com/fwlink/p/?LinkId=294201)。
  
若要跨方案比較功能，請參閱 [比較 Office 365 for Business 方案](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409)。
  
## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a>Office 365 進階威脅防護 (ATP) 的新增功能

如需 ATP 中新功能的詳細資訊，請參閱 [Office 365 中的 ATP 安全連結](https://go.microsoft.com/fwlink/?linkid=846016)。
  
## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a>Office 365 進階威脅防護 (ATP) 的需求

ATP 可搭配任何 SMTP 郵件傳輸代理程式使用，例如 Microsoft Exchange Server 2013。如需 ATP 所支援的作業系統、網頁瀏覽器和語言的資訊，請參閱 [Exchange Online Protection 中的 Exchange 系統管理中心](https://go.microsoft.com/fwlink/p/?LinkId=282381)中的＜支援的瀏覽器＞和＜支援語言＞小節。
  
## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a>各進階威脅防護 (ATP) 計劃中可用的功能

每項功能如下所列。提到 Exchange Online 時，通常是指 Office 365 企業版服務系列。
  
|**功能**|**ATP 獨立**|**Exchange Online Protection**|
|:-----|:-----|:-----|
|安全連結  <br/> |是  <br/> |否  <br/> |
|安全附件  <br/> |是  <br/> |否  <br/> |
|詐騙智慧  <br/> |是  <br/> |否  <br/> |
|隔離區  <br/> |是  <br/> |是  <br/> |
|進階反網路釣魚功能  <br/> |是  <br/> |否  <br/> |
   
## <a name="advanced-threat-protection-atp-capabilities"></a>進階威脅防護 (ATP) 功能

### <a name="safe-links"></a>安全連結

ATP 安全連結功能主動保護您的使用者，抵禦郵件中的惡意超連結。因為可動態封鎖惡意連結，允許存取無害連結，所以每次使用者按一下連結時都能受到持續保護。
  
### <a name="safe-attachments"></a>安全附件

安全附件可防止不明的惡意軟體和病毒，並提供零時差保護來保護郵件系統。所有沒有已知病毒/惡意軟體簽章的訊息與附件將被路由傳送至特殊的環境，其中 ATP 會使用不同的機器學習與分析技術來偵測惡意的意圖。如果未偵測到可疑活動，即會釋出訊息傳遞到信箱。 
  
### <a name="spoof-intelligence"></a>詐騙智慧

詐騙智慧偵測時寄件者看起來會將代表一個或多個使用者帳戶的郵件傳送內的其中一個貴組織的網域。它可讓您檢閱所有寄件者詐騙您的網域，然後選擇 [允許繼續或封鎖的寄件者寄件者。詐騙智慧有安全性&amp;反垃圾郵件設定] 頁面上的規範中心。
  
### <a name="quarantine"></a>隔離區

由 Office 365 服務識別為垃圾郵件、大量郵件、網路釣魚郵件、包含惡意程式碼的郵件，或因為它們符合郵件流程規則的郵件都可以傳送至隔離區。根據預設，Office 365 會直接將網路釣魚郵件和包含惡意程式碼的郵件傳送至隔離區。經過授權的使用者可以檢視、刪除或管理已傳送至隔離區的電子郵件郵件。
  
### <a name="advanced-anti-phishing-capabilities"></a>進階反網路釣魚功能

這項功能會使用機器學習模型來偵測網路釣魚郵件。 
  
