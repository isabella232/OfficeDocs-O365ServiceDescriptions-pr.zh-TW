---
title: Exchange Online 封存中的用戶端功能
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- clients-and-devices-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c8d5f97a-607f-4949-a4f7-0b9e3b246851
description: Microsoft Exchange Online 封存可讓使用者從各種裝置和平臺連接至其封存信箱。 所有與使用者封存的網路連線都會透過網際網路進行，而且不需要虛擬私人網路（VPN）連線。 組織可以發佈內部部署用戶端存取伺服器，讓使用者能夠使用 Outlook 無所不在 存取其主要信箱，而不需要 VPN 連線。 如果要求要有 VPN 連線才能存取內部部署伺服器上使用者的主要信箱，則此要求並不會變。
ms.openlocfilehash: 8dc4c065792b89a8a11f620b1493b91574e2013d
ms.sourcegitcommit: 7a68dc894dde0d06fab014c56914a78aa8cda847
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 04/21/2020
ms.locfileid: "43639721"
---
# <a name="client-features-in-exchange-online-archiving"></a>Exchange Online 封存中的用戶端功能

Microsoft Exchange Online 封存可讓使用者從各種裝置和平臺連接至其封存信箱。 所有與使用者封存的網路連線都會透過網際網路進行，而且不需要虛擬私人網路（VPN）連線。 組織可以發佈內部部署用戶端存取伺服器，讓使用者能夠使用 Outlook 無所不在 存取其主要信箱，而不需要 VPN 連線。 如果要求要有 VPN 連線才能存取內部部署伺服器上使用者的主要信箱，則此要求並不會變。
  
> [!IMPORTANT]
> 不論什麼用戶端軟體，只要是發出會對 Exchange Online Archiving服務的健康狀況造成負面影響的連線，Microsoft 保留封鎖或調節這類連線的權利。
  
## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook 是一款功能豐富的電子郵件程式，可支援行事曆、聯絡人與工作。Exchange Online Archiving可支援 Outlook 2013、Outlook 2010 及 Outlook 2007。其主要功能包括：
  
- **Outlook Anywhere**「Outlook 無所不在」可讓 Outlook 使用者透過網際網路連線到 Exchange Server 和 Exchange Online 封存，而不需要 VPN 連線。 Outlook 與 Exchange Online Archiving之間是透過 SSL 安全保護通道，使用 RPC-over-HTTP Windows 網路元件進行通訊。    
- **Autodiscover** Exchange Autodiscover 服務會自動設定 Outlook 使用Exchange Online Archiving。 自動探索可讓 Outlook 使用者在第一次（和此後的固定間隔）以其電子郵件地址和密碼登入，以直接從 Exchange 取得其必要的設定檔設定。 

Outlook 2010 和更新版本和網頁版 Outlook 為使用者提供封存的完整功能，以及保留和封存原則等相關功能。
  
Outlook 2007 可提供對封存的基本支援，但是並非所有封存和法規遵循功能都可以在 Outlook 2007 中使用。例如在 Outlook 2007，使用者無法對其信箱中的項目套用保留或封存原則，而必須仰賴管理員佈建的原則。Outlook 2007 使用者必須要有 2011 年 2 月的 Office 2007 累計更新，才能存取封存。
  
> [!NOTE]
> Exchange Online Archiving並未隨附 Outlook。 適用于企業的 Microsoft 365 應用程式（包括 Microsoft Outlook）包含在某些方案中，而且可以以個別訂閱形式購買。 如需詳細資訊，請參閱[Microsoft 365 plan options](../office-365-platform-service-description/office-365-plan-options.md)。 如需適用于企業的 Microsoft 365 應用程式的詳細資訊，請參閱[Office 應用程式服務說明](../office-applications-service-description/office-applications-service-description.md)。 
  
### <a name="clients-supported-by-exchange-online-archiving"></a>Exchange Online 封存所支援的用戶端

下表列出 Exchange Online Archiving所支援的用戶端：
  
|**用戶端**|**EOA 支援**|
|:-----|:-----|
|Outlook 2010 及更新版本  <br/> |支援 Exchange Online Archiving 的最新功能。<sup>1</sup> <br/> |
|Outlook 2007  <br/> |支援搭配 Exchange Online Archiving使用。<sup>1,2</sup> <br/> |
|Outlook 2003  <br/> |不支援  <br/> |
|Outlook for Mac 2011  <br/> |不支援  <br/> |
|Mac 版 Outlook  <br/> |支援與 Exchange Online 封存搭配使用。<sup>3</sup> <br/> |
|Microsoft Office Entourage 2008 Web Services Edition  <br/> |不支援  <br/> |
|IMAP 與 POP  <br/> |不支援  <br/> |
|Exchange ActiveSync （行動裝置）  <br/> |不支援  <br/> |
   
> [!NOTE]
> <sup>1</sup> Outlook included with Microsoft Office Standard is not supported. To learn more, see [License requirements for Personal Archive and retention policies](https://support.office.com/article/Outlook-license-requirements-for-Exchange-features-46B6B7C5-C3CA-43E5-8424-1E2807917C99). <br/> 
<sup>2</sup> Requires update to enable archiving support. Outlook 2007 users cannot view or apply retention or archive policies to items in their archive mailboxes; they must rely on administrator-provisioned policies. Additionally, Outlook 2007 users cannot search the on-premises mailbox and the archive at the same time. <br/> 
<sup>3</sup>您不能使用 outlook 2016 for Mac 或 Outlook for mac，將資料夾、行事曆專案、連絡人、工作或附注移動或複製到封存，或在封存信箱中查看這些專案（如 outlook 2016 for Windows）。 如需詳細資訊，請參閱[使用適用于 Mac 的 Outlook 2016 的線上](https://support.office.com/article/Use-your-online-archive-with-Outlook-2016-for-Mac-45b8439c-2982-4b6b-9097-eed71dbfe238)封存。 

## <a name="outlook-on-the-web"></a>Outlook 網頁版

Outlook 網頁版是網路架構版本的 Outlook 電子郵件程式，搭配 Exchange Online 使用。 不論使用者在家、辦公室或旅途&mdash;&mdash;中的任何使用者連線到網際網路，都可以透過網頁上的 Outlook 來存取其電子郵件。
  
使用者可以使用相同的 URL，在內部部署上登入 Outlook，以存取其封存。 封存會出現在網頁上 Outlook 中的主要信箱旁。 沒有直接從 Outlook 網頁版存取封存的明確方式。
  
## <a name="feature-availability"></a>功能可用性

若要查看不同方案、獨立選項和內部部署方案中的功能可用性，請參閱[Exchange Online 封存服務說明](exchange-online-archiving-service-description.md)。