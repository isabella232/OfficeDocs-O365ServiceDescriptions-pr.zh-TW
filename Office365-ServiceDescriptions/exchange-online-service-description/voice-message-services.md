---
title: 語音訊息服務
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-voice-message-services
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a02af6e2-75c2-4e83-843e-77241072068e
ms.openlocfilehash: 42a92a444a49b19d4589dd733426505c92c59e563776728f2ecf02aef53a7b36
ms.sourcegitcommit: fe808bb97ad09a91576aca8b733e3d2b75cb72e6
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 08/06/2021
ms.locfileid: "54663586"
---
# <a name="voice-message-services"></a>語音訊息服務

## <a name="voice-mail"></a>語音信箱

Microsoft Exchange Online 提供託管語音信箱服務，可提供：
  
- 自動答錄服務 (語音信箱)
    
- Exchange 的撥入使用者介面 (Outlook 語音存取)
    
- 來電者的撥入介面 (自動語音應答)
    
託管語音訊息服務可讓公司將其內部部署電話系統連線至 Exchange Online 提供的語音信箱服務。 語音信箱訊息會記錄並儲存在 Exchange Online 基礎結構中，允許使用者從 Outlook、Outlook 網頁版或行動電話存取其語音訊息。 電話與 Exchange Online 之間的所有連線都需要 Voice-over-IP (VoIP) 通訊協定。 系統管理員可使用 VoIP 媒體閘道和工作階段邊界控制器 (SBC)，將內部部署 IP PBX 或 PBX 電話系統連線至 Exchange Online。 如果客戶已部署 IP PBX 或者 PBX 直接支援 VoIP，且可與 Exchange 語音訊息服務互通，則不需要 VoIP 媒體閘道。 SBC 會部署在客戶網路的周圍，以連接內部部署電話網路並協助保護通訊 (和客戶網路)，防止遭到竊聽和入侵。 此外，也支援與 Microsoft Lync Server 2010 和 2013 語音功能的互通性。
  
Exchange Online 中所提供的語音訊息服務功能，與內部部署 Exchange Server 2016 中提供的功能類似。 包括：
  
- 在電話上播放 Outlook 和 Outlook 網頁版。
    
- 未接來電通知。
    
- 來電顯示 (使用全域通訊清單、使用者個人連絡人、自訂 [連絡人] 資料夾及來自外部社交網路之連絡人中的資訊)。
    
- 從 Outlook 網頁版和 Outlook 重設語音信箱 pin (請參閱[重設語音信箱 pin](/exchange/voice-mail-unified-messaging/set-outlook-voice-access-pin-security/reset-a-voice-mail-pin)) 。
    
- 郵件等待指示器 (如需詳細資訊，請參閱 [Exchange Online 中的 MWI](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/mwi-in-exchange-online))。 
    
- 呼叫應答規則 (請參閱 [允許語音信箱使用者轉接來電](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/allow-voice-mail-users-to-forward-calls) 以取得詳細資料) 。
    
- Exchange Online (中的「受保護的語音信箱」請參閱[保護 Exchange Online 中的語音信箱](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/protect-voice-mail)以取得詳細資料) 。
    
- 語音信箱預覽 (請參閱 [允許使用者查看語音信箱成績單](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/allow-users-to-see-a-voice-mail-transcript) ，以取得支援的語言) 清單。
    
- 對電子郵件、語音信箱、行事曆、個人連絡人及個人連絡群組進行語音存取。
    
- 透過 Outlook 語音存取或自動語音應答來搜尋目錄。
    
- 管理員可使用 Exchange 系統管理中心 (EAC) 設定和管理語音訊息服務的互通性。
    
如需語音信箱功能的相關資訊，請參閱[Exchange Online 中的語音信箱](/exchange/voice-mail-unified-messaging/voice-mail-unified-messaging)。
  
> [!IMPORTANT]
> Outlook 語音存取使用者或自動語音應答來電者使用語音命令進行功能表導覽或目錄搜尋時，無法使用自動語音辨識 (ASR) 功能。 
>
> 客戶必須使用 VoIP 閘道和 PBX、IP PBX，或商務用 Skype Server 2015，提供從公用交換電話網路 (PSTN) 的電話語音連線。 
>
> 客戶必須提供內部部署 SBC 硬體裝置，並確認 SBCs 已正確設定為連線到線上語音信箱服務。 這包括使用憑證和公開與私人 IP 介面，以及透過內部部署防火牆啟用正確 TCP 連接埠，設定適當的安全性等級。 
>
> 裝載的語音信箱僅適用于 Exchange Online 方案2和 Office 365 企業版 E3 訂閱者。 
  
## <a name="third-party-voice-mail-interoperability"></a>第三方語音信箱互通性

協力廠商的內部部署語音信箱解決方案只要能透過 SMTP 轉送語音訊息，或是支援 Microsoft Exchange Web 服務，即可與 Exchange Online 互通。如果語音信箱系統原本就不支援透過 SMTP 轉送語音訊息，則電子郵件伺服器可以保持為內部部署，以接收來自語音信箱系統的訊息，再使用 SMTP 將訊息轉寄到雲端。由於許多協力廠商語音郵件系統均使用 MAPI/CDO 與 Exchange Server 互通以便使用進階 UM 功能，因此，當使用 SMTP 以便與 Exchange Online 互通時，這些系統的完整功能可能無法提供。
  
> [!NOTE]
> 透過從運作 SBC 的客戶直接連線對第三方 PBX 系統提供的 Exchange Online UM 支援將於 2018 年 7 月終止。 如需詳細資訊，請參閱[終止支援 Exchange Online 整合通訊中的會話邊界控制器](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/Discontinuation-of-support-for-Session-Border-Controllers-in/ba-p/607117)。 
  
## <a name="skype-for-business-integration"></a>商務用 Skype 整合

組織可以購買商務用 Skype Online 做為獨立服務或做為 Microsoft Office 365 的一部分。 也支援商務用 Skype 2015 內部部署。 若要深入瞭解商務用 Skype 線上，請參閱[商務用 Skype 線上服務描述](../skype-for-business-online-service-description/skype-for-business-online-service-description.md)。
  
## <a name="feature-availability"></a>功能可用性

若要查看不同方案、獨立選項和內部部署方案中的功能可用性，請參閱[Exchange Online 服務描述](exchange-online-service-description.md)。
