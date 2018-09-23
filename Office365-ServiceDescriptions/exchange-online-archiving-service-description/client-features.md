---
title: Exchange Online 封存中的用戶端功能
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- clients-and-devices-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c8d5f97a-607f-4949-a4f7-0b9e3b246851
description: Microsoft Exchange Online 封存讓使用者可以從多種裝置與平台連線至封存信箱。使用者的封存的所有網路連線都發生透過網際網路，並不是必要的虛擬私人網路 (VPN) 連線。組織可以發佈可允許使用者存取其使用 「 Outlook 無所不在 」，而不需要透過 VPN 連線的主要信箱的內部部署 Client Access server。如果 VPN access 才可存取使用者的主要信箱位於內部部署伺服器上，就不會變更此需求。
ms.openlocfilehash: 90f384e990363294c8972a79e8b500d97ca4a839
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035238"
---
# <a name="client-features-in-exchange-online-archiving"></a>Exchange Online 封存中的用戶端功能

Microsoft Exchange Online 封存讓使用者可以從多種裝置與平台連線至封存信箱。使用者的封存的所有網路連線都發生透過網際網路，並不是必要的虛擬私人網路 (VPN) 連線。組織可以發佈可允許使用者存取其使用 「 Outlook 無所不在 」，而不需要透過 VPN 連線的主要信箱的內部部署 Client Access server。如果 VPN access 才可存取使用者的主要信箱位於內部部署伺服器上，就不會變更此需求。
  
> [!IMPORTANT]
> 不論什麼用戶端軟體，只要是發出會對 Exchange Online Archiving服務的健康狀況造成負面影響的連線，Microsoft 保留封鎖或調節這類連線的權利。 
  
## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook 是一款功能豐富的電子郵件程式，可支援行事曆、聯絡人與工作。Exchange Online Archiving可支援 Outlook 2013、Outlook 2010 及 Outlook 2007。其主要功能包括：
  
- **Outlook 無所不在** Outlook 無所不在 可以讓 Outlook 使用者透過網際網路連線至 Exchange Server 和 Exchange Online Archiving，而不需要 VPN 連線。Outlook 與 Exchange Online Archiving之間是透過 SSL 安全保護通道，使用 RPC-over-HTTP Windows 網路元件進行通訊。 
    
- **Autodiscover** Exchange Autodiscover 服務會自動設定 Outlook 使用Exchange Online Archiving。Autodiscover 可以讓 Outlook 使用者在第一次以電子郵件地址和密碼登入時 (以及此後的固定間隔)，直接從 Exchange 接收必要的設定檔設定。 
    
Outlook 2010 與更新版本及 Outlook Web App 可提供使用者對封存的完整功能，以及諸如保留和封存原則等相關功能。
  
Outlook 2007 可提供對封存的基本支援，但是並非所有封存和法規遵循功能都可以在 Outlook 2007 中使用。例如在 Outlook 2007，使用者無法對其信箱中的項目套用保留或封存原則，而必須仰賴管理員佈建的原則。Outlook 2007 使用者必須要有 2011 年 2 月的 Office 2007 累計更新，才能存取封存。
  
> [!NOTE]
> Exchange Online Archiving並未隨附 Outlook。Microsoft Office 365 專業增強版 (包括 Microsoft Outlook) 隨附於某些 Office 365 計劃內，但也能以單獨訂閱的方式購買。如需詳細資訊，請參閱[Office 365 方案選項](../office-365-platform-service-description/office-365-plan-options.md)。如需 Office 365 專業增強版 的詳細資訊，請參閱＜[Office 應用程式服務說明](../office-applications-service-description/office-applications-service-description.md)＞。 
  
### <a name="clients-supported-by-exchange-online-archiving"></a>Exchange Online 封存所支援的用戶端

下表列出 Exchange Online Archiving所支援的用戶端：
  
|**用戶端**|**EOA 支援**|
|:-----|:-----|
|Outlook 2010 及更新版本  <br/> |支援 Exchange Online Archiving 的最新功能。<sup>1</sup> <br/> |
|Outlook 2007  <br/> |支援搭配 Exchange Online Archiving使用。<sup>1,2</sup> <br/> |
|Outlook 2003  <br/> |不支援  <br/> |
|Outlook for Mac 2011  <br/> |不支援  <br/> |
|Mac 版 Outlook  <br/> |支援搭配 Exchange Online 封存。<sup>3</sup> <br/> |
|Microsoft Office Entourage 2008 Web Services Edition  <br/> |不支援  <br/> |
|IMAP 與 POP  <br/> |不支援  <br/> |
|Exchange ActiveSync (行動裝置)  <br/> |不支援  <br/> |
   
> [!NOTE]
> <sup>1</sup>不支援 outlook 隨附於 Microsoft Office Standard。若要深入了解，請參閱[個人封存與保留原則的授權需求](https://go.microsoft.com/fwlink/?LinkId=389396)。> <sup>2</sup>需要更新] 以啟用封存支援。Outlook 2007 使用者無法檢視或套用保留或封存原則以封存信箱 ； 中的項目他們必須依賴管理員佈建原則。此外，Outlook 2007 使用者無法搜尋的內部部署信箱和同時封存。> <sup>3</sup>您無法使用 Outlook 2016 Mac 或 Outlook for Mac 中移動或複製資料夾、 行事曆項目、 連絡人、 工作或附註您封存或檢視其封存信箱中如果項目已先前使用任何其他版本的 Outlook （那里移例如 Outlook 2016 windows)。如需詳細資訊，請參閱[使用 Outlook 2016 for Mac 與您線上封存](https://support.office.com/en-us/article/Use-your-online-archive-with-Outlook-2016-for-Mac-45b8439c-2982-4b6b-9097-eed71dbfe238)。 
  
## <a name="outlook-web-app"></a>Outlook Web App

Outlook Web App 是網路架構版本的 Outlook 電子郵件程式，搭配 Exchange Online 使用。透過 Outlook Web App，使用者無論身在何處 (例如在家、在辦公室或出門在外)，只要連上網際網路，就能存取其電子郵件。
  
使用者可以藉由登入內部部署 Outlook Web App (使用相同 URL) 存取其封存。封存會隨主要信箱一起出現在 Outlook Web App 中。沒有直接從 Outlook Web App 存取封存的明確方式。
  
## <a name="feature-availability"></a>功能可用性

若要檢視 Office 365 計劃、獨立選項和內部部署解決方案中的功能可用性，請參閱 [Exchange Online 封存服務說明](exchange-online-archiving-service-description.md)。
  

