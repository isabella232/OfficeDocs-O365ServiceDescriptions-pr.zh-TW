---
title: 語音訊息服務
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-voice-message-services
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a02af6e2-75c2-4e83-843e-77241072068e
ms.openlocfilehash: 98591e47ece7c59581824c6df375c41c66b7d2d1
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035375"
---
# <a name="voice-message-services"></a>語音訊息服務

## <a name="voice-mail"></a>語音信箱

Microsoft Exchange Online 提供託管語音信箱服務，可提供：
  
- 自動答錄服務 (語音信箱)
    
- Exchange 的撥入使用者介面 (Outlook 語音存取)
    
- 來電者的撥入介面 (自動語音應答)
    
主控的語音訊息服務允許其內部的電話系統連線至 Exchange Online 提供語音信箱服務的公司。語音信箱訊息所記錄且儲存在 Exchange Online 的基礎結構，讓使用者能夠從 Outlook、 Outlook web 或行動電話上的存取其語音訊息。所有電話語音連線至 Exchange Online 需要聲音傳送 IP (VoIP) 通訊協定。系統管理員可以連線內部 IP Pbx 或 PBX 電話系統使用 VoIP 媒體閘道和 Exchange online 的工作階段邊界控制器 (Sbc)。如果客戶已部署 IP PBX 或 PBX 直接支援 VoIP，並可互通與 Exchange 語音訊息服務不需要 VoIP 媒體閘道。Sbc 連線至內部部署電話語音網路的客戶網路周邊網路中部署及說明對竊聽和入侵安全通訊 （和客戶網路）。也支援與 Microsoft Lync Server 2010 與 2013年的語音功能的互通性。
  
語音訊息 Exchange Online 中可用的服務功能類似提供的內部部署 Exchange Server 2016 中。這些包括：
  
- 在電話上播放從 Outlook 和 Outlook web 上。
    
- 未接來電通知。
    
- 來電顯示 (使用全域通訊清單、使用者個人連絡人、自訂 [連絡人] 資料夾及來自外部社交網路之連絡人中的資訊)。
    
- 語音信箱 pin 碼從 Outlook 上 （請參閱[重設語音信箱 pin 碼](https://go.microsoft.com/fwlink/p/?LinkId=286328)） 的網頁和 Outlook 重設。
    
- 郵件等待指示器 (如需詳細資訊，請參閱 [Exchange Online 中的 MWI](https://go.microsoft.com/fwlink/p/?LinkId=271794))。 
    
- 自動答錄規則 (如需詳細資訊，請參閱[允許語音信箱使用者轉接通話](https://go.microsoft.com/fwlink/p/?LinkId=271795))。 
    
- Exchange Online 中受保護的語音信箱 (如需詳細資訊，請參閱 [Exchange Online 中受保護的語音信箱](https://go.microsoft.com/fwlink/p/?LinkId=271796))。 
    
- 語音郵件預覽 (如需支援的語言清單，請參閱[允許使用者查看語音郵件文字記錄](https://go.microsoft.com/fwlink/p/?LinkId=271797))。 
    
- 對電子郵件、語音信箱、行事曆、個人連絡人及個人連絡群組進行語音存取。
    
- 透過 Outlook 語音存取或自動語音應答來搜尋目錄。
    
- 管理員可使用 Exchange 系統管理中心 (EAC) 設定和管理語音訊息服務的互通性。
    
如需有關語音信箱功能的詳細資訊，請參閱 [Exchange Online 中的語音信箱](https://go.microsoft.com/fwlink/p/?LinkId=271798)。
  
> [!IMPORTANT]
> Outlook 語音存取使用者或自動語音應答來電者使用語音命令進行功能表導覽或目錄搜尋時，無法使用自動語音辨識 (ASR) 功能。 > 客戶必須使用 VoIP 閘道和 PBX、IP PBX, 或 商務用 Skype Server 2015，從公用交換電話網路 (PSTN) 提供電話連線。 > 客戶必須提供內部部署 SBC 硬體裝置，並確認 SBC 已正確設定為連線至線上語音信箱服務。這包括使用憑證和公開與私人 IP 介面，以及透過內部部署防火牆啟用正確 TCP 連接埠，設定適當的安全性等級。 > 裝載的語音信箱僅適用於 Exchange Online 方案 2 和 Office 365 Enterprise E3訂閱者。 
  
## <a name="third-party-voice-mail-interoperability"></a>協力廠商語音信箱互通性

協力廠商的內部部署語音信箱解決方案只要能透過 SMTP 轉送語音訊息，或是支援 Microsoft Exchange Web 服務，即可與 Exchange Online 互通。如果語音信箱系統原本就不支援透過 SMTP 轉送語音訊息，則電子郵件伺服器可以保持為內部部署，以接收來自語音信箱系統的訊息，再使用 SMTP 將訊息轉寄到雲端。由於許多協力廠商語音郵件系統均使用 MAPI/CDO 與 Exchange Server 互通以便使用進階 UM 功能，因此，當使用 SMTP 以便與 Exchange Online 互通時，這些系統的完整功能可能無法提供。
  
> [!NOTE]
> Exchange Online UM 支援透過直接從客戶 21vianet Sbc 連線協力廠商 PBX 系統將會結束年 7 月 2018年中。請參閱[主題的 Exchange Online 整合通訊中的工作階段邊界控制器支援](https://blogs.technet.microsoft.com/exchange/2017/07/18/discontinuation-of-support-for-session-border-controllers-in-exchange-online-unified-messaging/)如需詳細資訊。 
  
## <a name="skype-for-business-integration"></a>商務用 Skype 整合

組織可購買 Skype 商務 Online 做為獨立服務或 Microsoft Office 365 的一部分。針對 Business 2015 內部 Skype 也支援。若要深入了解 Skype 商務 online，請參閱[Skype for Business Online 服務說明](../skype-for-business-online-service-description/skype-for-business-online-service-description.md)。
  
## <a name="feature-availability"></a>功能可用性

若要檢視 Office 365 計劃、獨立選項和內部部署解決方案中的功能可用性，請參閱 [Exchange Online 服務說明](exchange-online-service-description.md)。
  

