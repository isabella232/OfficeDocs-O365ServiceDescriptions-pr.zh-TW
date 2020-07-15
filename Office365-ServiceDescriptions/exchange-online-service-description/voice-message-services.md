---
title: 語音訊息服務
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-voice-message-services
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a02af6e2-75c2-4e83-843e-77241072068e
ms.openlocfilehash: a6245acdeaeda173f1a675d1ce34d9086e3f077a
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132547"
---
# <a name="voice-message-services"></a><span data-ttu-id="b0ec2-102">語音訊息服務</span><span class="sxs-lookup"><span data-stu-id="b0ec2-102">Voice message services</span></span>

## <a name="voice-mail"></a><span data-ttu-id="b0ec2-103">語音信箱</span><span class="sxs-lookup"><span data-stu-id="b0ec2-103">Voice mail</span></span>

<span data-ttu-id="b0ec2-104">Microsoft Exchange Online 提供託管語音信箱服務，可提供：</span><span class="sxs-lookup"><span data-stu-id="b0ec2-104">Microsoft Exchange Online offers hosted voice mail services, which provide:</span></span>
  
- <span data-ttu-id="b0ec2-105">自動答錄服務 (語音信箱)</span><span class="sxs-lookup"><span data-stu-id="b0ec2-105">Call answering (voice mail)</span></span>
    
- <span data-ttu-id="b0ec2-106">Exchange 的撥入使用者介面 (Outlook 語音存取)</span><span class="sxs-lookup"><span data-stu-id="b0ec2-106">Dial-in user interface to Exchange (Outlook Voice Access)</span></span>
    
- <span data-ttu-id="b0ec2-107">來電者的撥入介面 (自動語音應答)</span><span class="sxs-lookup"><span data-stu-id="b0ec2-107">Dial-in interface for callers (auto attendant)</span></span>
    
<span data-ttu-id="b0ec2-108">託管語音訊息服務可讓公司將其內部部署電話系統連線至 Exchange Online 提供的語音信箱服務。</span><span class="sxs-lookup"><span data-stu-id="b0ec2-108">Hosted voice messaging services allow a company to connect its on-premises phone system to voice mail services provided by Exchange Online.</span></span> <span data-ttu-id="b0ec2-109">語音信箱訊息會記錄並儲存在 Exchange Online 基礎結構中，讓使用者可以從 Outlook、Outlook 網頁或行動電話存取其語音訊息。</span><span class="sxs-lookup"><span data-stu-id="b0ec2-109">Voice mail messages are recorded and stored in the Exchange Online infrastructure, allowing users to access their voice messages from Outlook, Outlook on the web, or mobile phones.</span></span> <span data-ttu-id="b0ec2-110">電話與 Exchange Online 之間的所有連線都需要 Voice-over-IP (VoIP) 通訊協定。</span><span class="sxs-lookup"><span data-stu-id="b0ec2-110">All telephony connections to Exchange Online require voice-over-IP (VoIP) protocols.</span></span> <span data-ttu-id="b0ec2-111">系統管理員可使用 VoIP 媒體閘道和工作階段邊界控制器 (SBC)，將內部部署 IP PBX 或 PBX 電話系統連線至 Exchange Online。</span><span class="sxs-lookup"><span data-stu-id="b0ec2-111">Administrators can connect on-premises IP PBXs or PBX phone systems using VoIP media gateways and session border controllers (SBCs) to Exchange Online.</span></span> <span data-ttu-id="b0ec2-112">如果客戶已部署 IP PBX 或者 PBX 直接支援 VoIP，且可與 Exchange 語音訊息服務互通，則不需要 VoIP 媒體閘道。</span><span class="sxs-lookup"><span data-stu-id="b0ec2-112">A VoIP media gateway is not required if the customer has deployed an IP PBX or if a PBX supports VoIP directly and is interoperable with Exchange voice messaging services.</span></span> <span data-ttu-id="b0ec2-113">SBC 會部署在客戶網路的周圍，以連接內部部署電話網路並協助保護通訊 (和客戶網路)，防止遭到竊聽和入侵。</span><span class="sxs-lookup"><span data-stu-id="b0ec2-113">SBCs are deployed in the perimeter of the customer network to connect an on-premises telephony network and help secure the communications (and the customer network) against eavesdropping and intrusion.</span></span> <span data-ttu-id="b0ec2-114">此外，也支援與 Microsoft Lync Server 2010 和 2013 語音功能的互通性。</span><span class="sxs-lookup"><span data-stu-id="b0ec2-114">Interoperability with the voice capabilities of Microsoft Lync Server 2010 and 2013 is also supported.</span></span>
  
<span data-ttu-id="b0ec2-115">Exchange Online 中的語音訊息服務功能與內部部署 Exchange Server 2016 中提供的功能類似。</span><span class="sxs-lookup"><span data-stu-id="b0ec2-115">The voice messaging services features available in Exchange Online are similar to those offered in on-premises Exchange Server 2016.</span></span> <span data-ttu-id="b0ec2-116">包括：</span><span class="sxs-lookup"><span data-stu-id="b0ec2-116">These include:</span></span>
  
- <span data-ttu-id="b0ec2-117">從 Outlook 和網頁型 Outlook 上的電話播放。</span><span class="sxs-lookup"><span data-stu-id="b0ec2-117">Play on phone from Outlook and Outlook on the web.</span></span>
    
- <span data-ttu-id="b0ec2-118">未接來電通知。</span><span class="sxs-lookup"><span data-stu-id="b0ec2-118">Missed call notifications.</span></span>
    
- <span data-ttu-id="b0ec2-119">來電顯示 (使用全域通訊清單、使用者個人連絡人、自訂 [連絡人] 資料夾及來自外部社交網路之連絡人中的資訊)。</span><span class="sxs-lookup"><span data-stu-id="b0ec2-119">Caller ID (using information in the Global Address List, users' personal contacts, custom Contacts folder, and contacts from external social networks).</span></span>
    
- <span data-ttu-id="b0ec2-120">從網頁上的 Outlook 和 Outlook 重設語音信箱 PIN 碼（請參閱[重設語音信箱 PIN 碼](https://go.microsoft.com/fwlink/p/?LinkId=286328)）。</span><span class="sxs-lookup"><span data-stu-id="b0ec2-120">Voice mail PIN reset from Outlook on the web and Outlook (see [Reset a Voice Mail PIN](https://go.microsoft.com/fwlink/p/?LinkId=286328)).</span></span>
    
- <span data-ttu-id="b0ec2-121">郵件等待指示器 (如需詳細資訊，請參閱 [Exchange Online 中的 MWI](https://go.microsoft.com/fwlink/p/?LinkId=271794))。</span><span class="sxs-lookup"><span data-stu-id="b0ec2-121">Message Waiting Indicator (see [MWI in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271794) for details).</span></span> 
    
- <span data-ttu-id="b0ec2-122">呼叫應答規則（如需詳細資訊，請參閱[允許語音信箱使用者轉接通話](https://go.microsoft.com/fwlink/p/?LinkId=271795)）。</span><span class="sxs-lookup"><span data-stu-id="b0ec2-122">Call answering rules (see [Allow voice mail users to forward calls](https://go.microsoft.com/fwlink/p/?LinkId=271795) for details).</span></span>
    
- <span data-ttu-id="b0ec2-123">Exchange Online 中的「受保護的語音信箱」（請參閱[在 Exchange online 中保護語音信箱](https://go.microsoft.com/fwlink/p/?LinkId=271796)以取得詳細資訊）。</span><span class="sxs-lookup"><span data-stu-id="b0ec2-123">Protected voice mail in Exchange Online (see [Protect voice mail in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271796) for details).</span></span>
    
- <span data-ttu-id="b0ec2-124">語音信箱預覽（請參閱[允許使用者查看語音信箱成績單](https://go.microsoft.com/fwlink/p/?LinkId=271797)以取得支援的語言清單）。</span><span class="sxs-lookup"><span data-stu-id="b0ec2-124">Voice mail preview (see [Allow users to see a voice mail transcript](https://go.microsoft.com/fwlink/p/?LinkId=271797) for a list of supported languages).</span></span>
    
- <span data-ttu-id="b0ec2-125">對電子郵件、語音信箱、行事曆、個人連絡人及個人連絡群組進行語音存取。</span><span class="sxs-lookup"><span data-stu-id="b0ec2-125">Speech access to email, voice mail, calendar, personal contacts, and personal contact groups.</span></span>
    
- <span data-ttu-id="b0ec2-126">透過 Outlook 語音存取或自動語音應答來搜尋目錄。</span><span class="sxs-lookup"><span data-stu-id="b0ec2-126">Directory search through Outlook Voice Access or an auto attendant.</span></span>
    
- <span data-ttu-id="b0ec2-127">管理員可使用 Exchange 系統管理中心 (EAC) 設定和管理語音訊息服務的互通性。</span><span class="sxs-lookup"><span data-stu-id="b0ec2-127">Administrators configure and manage voice messaging services interoperability by using the Exchange admin center (EAC).</span></span>
    
<span data-ttu-id="b0ec2-128">如需語音信箱功能的相關資訊，請參閱[voice mail In Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271798)。</span><span class="sxs-lookup"><span data-stu-id="b0ec2-128">For more information about voice mail features, see [Voice mail in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271798).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="b0ec2-129">Outlook 語音存取使用者或自動語音應答來電者使用語音命令進行功能表導覽或目錄搜尋時，無法使用自動語音辨識 (ASR) 功能。</span><span class="sxs-lookup"><span data-stu-id="b0ec2-129">The Automatic Speech Recognition (ASR) feature isn't available in menu navigation or directory search for Outlook Voice Access users or auto attendant callers using voice commands.</span></span> 
>
> <span data-ttu-id="b0ec2-130">客戶必須使用 VoIP 閘道和 PBX、IP PBX 或商務用 Skype Server 2015，從公用交換電話網路（PSTN）提供電話連線。</span><span class="sxs-lookup"><span data-stu-id="b0ec2-130">The customer must provide a telephony connection from the public switched telephone network (PSTN) using a VoIP gateway and PBX, IP PBX, or Skype for Business Server 2015.</span></span> 
>
> <span data-ttu-id="b0ec2-131">客戶必須提供內部部署 SBC 硬體裝置，並確認 SBCs 已正確設定為連線到線上語音信箱服務。</span><span class="sxs-lookup"><span data-stu-id="b0ec2-131">The customer must provide the on-premises SBC hardware devices and ensure that the SBCs are correctly configured to connect to the online voice mail services.</span></span> <span data-ttu-id="b0ec2-132">這包括使用憑證和公開與私人 IP 介面，以及透過內部部署防火牆啟用正確 TCP 連接埠，設定適當的安全性等級。</span><span class="sxs-lookup"><span data-stu-id="b0ec2-132">This includes configuring the appropriate level of security by using certificates and public and private IP interfaces and by enabling the correct TCP ports through their on-premises firewalls.</span></span> 
>
> <span data-ttu-id="b0ec2-133">主控的語音信箱僅適用于 Exchange Online Plan 2 和 Office 365 Enterprise E3 訂閱者。</span><span class="sxs-lookup"><span data-stu-id="b0ec2-133">Hosted voice mail is available only to Exchange Online Plan 2 and Office 365 Enterprise E3 subscribers.</span></span> 
  
## <a name="third-party-voice-mail-interoperability"></a><span data-ttu-id="b0ec2-134">第三方語音信箱互通性</span><span class="sxs-lookup"><span data-stu-id="b0ec2-134">Third-party voice mail interoperability</span></span>

<span data-ttu-id="b0ec2-135">On-premises voice mail solutions from third-party providers can interoperate with Exchange Online if they can forward voice messages through SMTP or if they support Microsoft Exchange Web Services.</span><span class="sxs-lookup"><span data-stu-id="b0ec2-135">On-premises voice mail solutions from third-party providers can interoperate with Exchange Online if they can forward voice messages through SMTP or if they support Microsoft Exchange Web Services.</span></span> <span data-ttu-id="b0ec2-136">If the voice mail system does not natively support forwarding voice messages through SMTP, an email server can be kept on-premises to receive messages from the voice mail system and then forward them to the cloud using SMTP.</span><span class="sxs-lookup"><span data-stu-id="b0ec2-136">If the voice mail system does not natively support forwarding voice messages through SMTP, an email server can be kept on-premises to receive messages from the voice mail system and then forward them to the cloud using SMTP.</span></span> <span data-ttu-id="b0ec2-137">Because many third-party voice mail systems use MAPI/CDO to interoperate with Exchange Server for advanced UM features, the full capabilities of these systems may not be available when SMTP is used for interoperability with Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="b0ec2-137">Because many third-party voice mail systems use MAPI/CDO to interoperate with Exchange Server for advanced UM features, the full capabilities of these systems may not be available when SMTP is used for interoperability with Exchange Online.</span></span>
  
> [!NOTE]
> <span data-ttu-id="b0ec2-138">透過從運作 SBC 的客戶直接連線對第三方 PBX 系統提供的 Exchange Online UM 支援將於 2018 年 7 月終止。</span><span class="sxs-lookup"><span data-stu-id="b0ec2-138">Exchange Online UM support for third-party PBX systems via direct connections from customer operated SBCs will end in July 2018.</span></span> <span data-ttu-id="b0ec2-139">如需詳細資訊，請參閱[終止支援 Exchange Online 整合通訊中的會話邊界控制器](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/Discontinuation-of-support-for-Session-Border-Controllers-in/ba-p/607117)。</span><span class="sxs-lookup"><span data-stu-id="b0ec2-139">Please see [Discontinuation of support for Session Border Controllers in Exchange Online Unified Messaging](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/Discontinuation-of-support-for-Session-Border-Controllers-in/ba-p/607117) for more information.</span></span> 
  
## <a name="skype-for-business-integration"></a><span data-ttu-id="b0ec2-140">商務用 Skype 整合</span><span class="sxs-lookup"><span data-stu-id="b0ec2-140">Skype for Business integration</span></span>

<span data-ttu-id="b0ec2-141">組織可以購買商務用 Skype Online 做為獨立服務或做為 Microsoft Office 365 的一部分。</span><span class="sxs-lookup"><span data-stu-id="b0ec2-141">Organizations can purchase Skype for Business Online as a standalone service or as part of Microsoft Office 365.</span></span> <span data-ttu-id="b0ec2-142">也支援商務用 Skype 2015 內部部署。</span><span class="sxs-lookup"><span data-stu-id="b0ec2-142">Skype for Business 2015 on-premises is also supported.</span></span> <span data-ttu-id="b0ec2-143">若要深入瞭解商務用 Skype Online，請參閱[商務用 Skype online 服務說明](../skype-for-business-online-service-description/skype-for-business-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="b0ec2-143">To learn more about Skype for Business Online, see [Skype for Business Online service description](../skype-for-business-online-service-description/skype-for-business-online-service-description.md).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="b0ec2-144">功能可用性</span><span class="sxs-lookup"><span data-stu-id="b0ec2-144">Feature availability</span></span>

<span data-ttu-id="b0ec2-145">若要查看不同方案、獨立選項和內部部署方案中的功能可用性，請參閱[Exchange Online 服務說明](exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="b0ec2-145">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online service description](exchange-online-service-description.md).</span></span>
  

