---
title: Exchange Online 封存中的用戶端功能
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- clients-and-devices-in-exchange-online-archiving
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
ms.assetid: c8d5f97a-607f-4949-a4f7-0b9e3b246851
description: 請閱讀本文以瞭解 Microsoft Exchange Online 封存中可用的用戶端功能。
ms.openlocfilehash: 5cb9e43ecf20aeca4bcec1c6c76c7ef56bb6e557
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/24/2021
ms.locfileid: "59670835"
---
# <a name="client-features-in-exchange-online-archiving"></a>Exchange Online 封存中的用戶端功能

Microsoft Exchange Online封存可讓使用者從各種裝置和平臺連接至其封存信箱。 所有與使用者封存的網路連線都會透過網際網路進行，而且不需要虛擬私人網路 (VPN) 連線。 組織可以發佈內部部署用戶端存取伺服器，讓使用者能夠使用 Outlook 無所不在 存取其主要信箱，而不需要 VPN 連線。 如果要求要有 VPN 連線才能存取內部部署伺服器上使用者的主要信箱，則此要求並不會變。
  
> [!IMPORTANT]
> 不論什麼用戶端軟體，只要是發出會對 Exchange Online Archiving服務的健康狀況造成負面影響的連線，Microsoft 保留封鎖或調節這類連線的權利。
  
## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook 是一款功能豐富的電子郵件程式，可支援行事曆、聯絡人與工作。Exchange Online Archiving可支援 Outlook 2013、Outlook 2010 及 Outlook 2007。其主要功能包括：
  
- **Outlook** 無所不在-Outlook anywhere 可讓 Outlook 使用者透過網際網路連線到 Exchange Server 及 Exchange Online 封存，而不需要 VPN 連線。 Outlook 與 Exchange Online Archiving之間是透過 SSL 安全保護通道，使用 RPC-over-HTTP Windows 網路元件進行通訊。    
- **自動** 探索-Exchange 自動探索服務會自動設定 Outlook 以搭配 Exchange Online 封存使用。 自動探索可讓 Outlook 使用者在第一次 Exchange (時，) 以其電子郵件地址和密碼登入時，直接從接收其必要的設定檔設定。 

Outlook 2010 和更新版本，Outlook 網頁版為使用者提供封存的完整功能，以及保留和封存原則等相關功能。
  
Outlook 2007 可提供對封存的基本支援，但是並非所有封存和法規遵循功能都可以在 Outlook 2007 中使用。例如在 Outlook 2007，使用者無法對其信箱中的項目套用保留或封存原則，而必須仰賴管理員佈建的原則。Outlook 2007 使用者必須要有 2011 年 2 月的 Office 2007 累計更新，才能存取封存。
  
> [!NOTE]
> Exchange Online Archiving並未隨附 Outlook。 包含 Microsoft Outlook) 的 Microsoft 365 Apps 企業版 (包含在某些方案中，而且可以以個別訂閱形式購買。 如需詳細資訊，請參閱[Microsoft 365 plan 選項](../office-365-platform-service-description/office-365-plan-options.md)。 如需 Microsoft 365 Apps 企業版的詳細資訊，請參閱[Office 應用程式服務說明](../office-applications-service-description/office-applications-service-description.md)。 
  
### <a name="clients-supported-by-exchange-online-archiving"></a>Exchange Online 封存所支援的用戶端

下表列出 Exchange Online Archiving所支援的用戶端：<br><br>
  
| 用戶端 | EOA 支援 |
|:-----|:-----|
|Outlook 2013 和更新版本  <br/> |支援 Exchange Online Archiving 的最新功能。<sup>1</sup> <br/> |
|Outlook 2010  <br/> |僅支援 Exchange Online 封存直到10月13日2020的最新功能|
|Outlook 2007  <br/> |不支援 |
|Outlook 2003  <br/> |不支援  <br/> |
|Outlook for Mac 2011  <br/> |不支援  <br/> |
|Mac 版 Outlook  <br/> |支援與 Exchange Online 封存搭配使用。<sup>3</sup> <br/> |
|Microsoft Office Entourage 2008 Web Services Edition  <br/> |不支援  <br/> |
|IMAP 與 POP  <br/> |不支援  <br/> |
|Exchange ActiveSync (行動裝置)   <br/> |不支援  <br/> |
   
> [!NOTE]
> <sup>1</sup> Outlook included with Microsoft Office Standard is not supported. To learn more, see [License requirements for Personal Archive and retention policies](https://support.office.com/article/Outlook-license-requirements-for-Exchange-features-46B6B7C5-C3CA-43E5-8424-1E2807917C99). <br/> 
<sup>2</sup> Requires update to enable archiving support. Outlook 2007 users cannot view or apply retention or archive policies to items in their archive mailboxes; they must rely on administrator-provisioned policies. Additionally, Outlook 2007 users cannot search the on-premises mailbox and the archive at the same time. <br/> 
<sup>3</sup>您無法使用 Mac 版 Outlook 2016 或 Mac 版 Outlook，將資料夾、行事曆專案、連絡人、工作或附注移動或複製到封存，或在封存信箱中查看這些專案（如果這些專案先前是使用 Outlook 2016 的任何其他 (Outlook 版本移至該位置 Windows) 。 如需詳細資訊，請參閱[使用您的線上](https://support.office.com/article/Use-your-online-archive-with-Outlook-2016-for-Mac-45b8439c-2982-4b6b-9097-eed71dbfe238)封存搭配 Mac 版 Outlook 2016。 

## <a name="outlook-on-the-web"></a>Outlook 網頁版

Outlook 網頁版是網路架構版本的 Outlook 電子郵件程式，搭配 Exchange Online 使用。 任何使用者在家裡、辦公室或旅途中連線到網際網路的地方 &mdash; ， &mdash; 都可以透過 Outlook 網頁版存取其電子郵件。
  
使用者可以使用相同的 URL) ，登入 Outlook 網頁版內部部署 (來存取其封存。 封存會顯示在 Outlook 網頁版中的主要信箱旁。 沒有直接從 Outlook 網頁版存取封存的明確方式。
  
## <a name="feature-availability"></a>功能可用性

若要查看不同方案、獨立選項和內部部署方案中的功能可用性，請參閱[Exchange Online 封存服務描述](exchange-online-archiving-service-description.md)。