---
title: Exchange Online 封存中的用戶端功能
ms.author: sharik
author: skjerland
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
description: Microsoft Exchange Online 封存可讓使用者從各種裝置和平台連線到他們的封存信箱。 所有對使用者封存進行的網路連線都是透過網際網路進行，不需要虛擬私人網路 (VPN) 連線。 組織可以發佈內部部署用戶端存取伺服器，讓使用者能夠使用 Outlook 無所不在 存取其主要信箱，而不需要 VPN 連線。 如果要求要有 VPN 連線才能存取內部部署伺服器上使用者的主要信箱，則此要求並不會變。
ms.openlocfilehash: d1f304936d184dc30826d6e60552d4e186bb2a41
ms.sourcegitcommit: 68eee0c2885fd112e37eea27370c3f8c1f0831cb
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 03/07/2019
ms.locfileid: "30467180"
---
# <a name="client-features-in-exchange-online-archiving"></a>Exchange Online 封存中的用戶端功能

Microsoft Exchange Online 封存可讓使用者從各種裝置和平台連線到他們的封存信箱。 所有對使用者封存進行的網路連線都是透過網際網路進行，不需要虛擬私人網路 (VPN) 連線。 組織可以發佈內部部署用戶端存取伺服器，讓使用者能夠使用 Outlook 無所不在 存取其主要信箱，而不需要 VPN 連線。 如果要求要有 VPN 連線才能存取內部部署伺服器上使用者的主要信箱，則此要求並不會變。
  
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
|Outlook 2003  <br/> |exExchange2k7 和更早版本  <br/> |
|Outlook for Mac 2011  <br/> |exExchange2k7 和更早版本  <br/> |
|Mac 版 Outlook  <br/> |支援搭配 Exchange Online Archiving。<sup>3</sup> <br/> |
|Microsoft Office Entourage 2008 Web Services Edition  <br/> |exExchange2k7 和更早版本  <br/> |
|IMAP 與 POP  <br/> |exExchange2k7 和更早版本  <br/> |
|Exchange ActiveSync (行動裝置)  <br/> |不支援  <br/> |
   
> [!NOTE]
> <sup>1</sup> Outlook included with Microsoft Office Standard is not supported. To learn more, see [License requirements for Personal Archive and retention policies](https://go.microsoft.com/fwlink/?LinkId=389396). > <sup>2</sup> Requires update to enable archiving support. Outlook 2007 users cannot view or apply retention or archive policies to items in their archive mailboxes; they must rely on administrator-provisioned policies. Additionally, Outlook 2007 users cannot search the on-premises mailbox and the archive at the same time. > <sup>3</sup>無法使用 Outlook 2016 for Mac 或 Outlook for Mac 來移動或複製到您封存的資料夾、 行事曆項目、 連絡人、 工作或備忘稿或檢視其封存信箱中，如果項目已先前移至該處 （例如使用任何其他版本的 OutlookOutlook 2016 for Windows)。 如需詳細資訊，請參閱[使用您的線上封存與 Outlook 2016 for Mac](https://support.office.com/en-us/article/Use-your-online-archive-with-Outlook-2016-for-Mac-45b8439c-2982-4b6b-9097-eed71dbfe238)。 
  
## <a name="outlook-web-app"></a>Outlook Web App

Outlook Web App 是網路架構版本的 Outlook 電子郵件程式，搭配 Exchange Online 使用。透過 Outlook Web App，使用者無論身在何處 (例如在家、在辦公室或出門在外)，只要連上網際網路，就能存取其電子郵件。
  
使用者可以藉由登入內部部署 Outlook Web App (使用相同 URL) 存取其封存。封存會隨主要信箱一起出現在 Outlook Web App 中。沒有直接從 Outlook Web App 存取封存的明確方式。
  
## <a name="feature-availability"></a>功能可用性

若要檢視 Office 365 計劃、獨立選項和內部部署解決方案中的功能可用性，請參閱 [Exchange Online 封存服務說明](exchange-online-archiving-service-description.md)。
  

