---
title: 語音訊息服務
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-voice-message-services
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a02af6e2-75c2-4e83-843e-77241072068e
ms.openlocfilehash: 7f01e3e013ea714735af300a8ecf36dd26984757
ms.sourcegitcommit: 96dc758c790ddaf05f5c2b836451b417729cf119
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/18/2019
ms.locfileid: "35776924"
---
# <a name="voice-message-services"></a>語音訊息服務

## <a name="voice-mail"></a>語音信箱

Microsoft Exchange Online 提供託管語音信箱服務，可提供：
  
- 自動答錄服務 (語音信箱)
    
- Exchange 的撥入使用者介面 (Outlook 語音存取)
    
- 來電者的撥入介面 (自動語音應答)
    
託管語音訊息服務可讓公司將其內部部署電話系統連線至 Exchange Online 提供的語音信箱服務。 語音信箱訊息會錄製並儲存在 Exchange Online 的基礎結構，可讓使用者從 Outlook、 Outlook web 應用程式或行動電話存取其語音訊息。 電話與 Exchange Online 之間的所有連線都需要 Voice-over-IP (VoIP) 通訊協定。 系統管理員可使用 VoIP 媒體閘道和工作階段邊界控制器 (SBC)，將內部部署 IP PBX 或 PBX 電話系統連線至 Exchange Online。 如果客戶已部署 IP PBX 或者 PBX 直接支援 VoIP，且可與 Exchange 語音訊息服務互通，則不需要 VoIP 媒體閘道。 SBC 會部署在客戶網路的周圍，以連接內部部署電話網路並協助保護通訊 (和客戶網路)，防止遭到竊聽和入侵。 此外，也支援與 Microsoft Lync Server 2010 和 2013 語音功能的互通性。
  
語音訊息服務功能 Exchange Online 中提供類似提供內部部署 Exchange Server 2016 中。 這些包括：
  
- 在電話上播放從 Outlook 和 outlook 網頁版。
    
- 未接來電通知。
    
- 來電顯示 (使用全域通訊清單、使用者個人連絡人、自訂 [連絡人] 資料夾及來自外部社交網路之連絡人中的資訊)。
    
- 語音信箱 pin 碼以從 Outlook （請參閱[重設語音信箱 pin 碼](https://go.microsoft.com/fwlink/p/?LinkId=286328)） 的網站和 Outlook 重設。
    
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
> Exchange Online UM 支援透過直接連線從客戶運作 Sbc 協力廠商 PBX 系統將在 2018 年 7 月結束。 請如需詳細資訊，參閱[主題的 Exchange Online 整合通訊中的工作階段邊界控制器的支援](https://blogs.technet.microsoft.com/exchange/2017/07/18/discontinuation-of-support-for-session-border-controllers-in-exchange-online-unified-messaging/)。 
  
## <a name="skype-for-business-integration"></a>商務用 Skype 整合

組織可以購買商務用 Skype Online 做為獨立服務或做為 Microsoft Office 365 的一部分。 也支援商務 2015年內部部署商務用 Skype。 若要深入了解商務用 Skype Online，請參閱[商務用 Skype Online 服務說明](../skype-for-business-online-service-description/skype-for-business-online-service-description.md)。
  
## <a name="feature-availability"></a>功能可用性

若要檢視 Office 365 計劃、獨立選項和內部部署解決方案中的功能可用性，請參閱 [Exchange Online 服務說明](exchange-online-service-description.md)。
  

