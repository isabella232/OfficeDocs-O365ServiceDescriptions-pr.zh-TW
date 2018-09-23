---
title: 規劃及部署
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-planning-and-deployment
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: e44e5e61-1f5d-4e68-981d-77a42f0ea0d4
ms.openlocfilehash: b8e805452bde7553640c4b02f39792c0dd1c6b78
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035344"
---
# <a name="planning-and-deployment"></a>規劃及部署

## <a name="planning-for-service-changes-and-growth"></a>規劃服務的變化和增長

組織選擇遷移選項時，應基於來源電子郵件系統、希望的結束狀態（完全託管或部分託管）、遷移的使用者人數，以及結束狀態必須多快完成。
  
## <a name="deployment-options"></a>部署選項

- **僅限雲端部署**您的組織具有所有使用者信箱託管於 Exchange Online。 
    
- **Exchange 混合部署** 你的組織將部分使用者信箱託管於內部佈署 Exchange 組織，部分使用者信箱託管於 Exchange Online。 
    
### <a name="cloud-only"></a>僅雲端

僅雲端部署是指 你的組織在 Exchange Online 服務中未與內部部署 Exchange 組織連線。所有使用者與信箱均由 Exchange Online 及 Office 365 託管及管理。
  
### <a name="hybrid"></a>混合

Microsoft Exchange 2003、Exchange 2007、Exchange 2010，以及 Exchange 2013 均適用的內部組織，混合部署提供了部分使用者信箱裝載於內部佈署 Exchange 組織，部分使用者信箱託管於 Exchange Online 的長期共存設置，或者將所有使用者信箱託管於 Exchange Online 的遷移路徑。混合部署可讓組織將功能豐富的體驗，以及現有內部部署 Microsoft Exchange 組織所具有的管理控制延伸至雲端。混合部署之特色包括安全郵件傳輸、共用行事曆空閑／忙碌資訊，以及內部佈署和 Exchange Online 組織之間的郵件追蹤。
  
如需有關混合部署的詳細資訊，請參閱 [Exchange Server 2013 混合部署](https://go.microsoft.com/fwlink/p/?LinkId=287035)。如果您使用 21Vianet 操作的 Office 365，請參閱 [使用 21Vianet 操作的 Office 365 設定 Exchange 混合部署](http://go.microsoft.com/fwlink/?LinkID=733373&amp;clcid=0x409)。
  
> [!IMPORTANT]
> 內部部署 Exchange 2003 組織必須至少安裝一個 Exchange 2010 用戶端存取／郵件伺服器，以便設定和 Exchange Online 之混合部署。內部部署 Exchange 2007 組織必須至少安裝一個 Exchange 2010 或 Exchange 2013 用戶端存取及郵件伺服器，以便設定和 Exchange Online 之混合部署。內部部署 Exchange 2010 和及 Exchange 2013 組織原生支援和 Exchange Online 之混合部署。如需有關混合部署中 Exchange Server 相容性的詳細資訊，請參閱[混合部署必要條件](https://go.microsoft.com/fwlink/p/?LinkId=243541)。 > 內部佈署 Exchange 組織必須將其組織設定為混合部署。我們強烈建議管理者使用 Exchange Server 部署助理及混合設定精靈來設定混合部署。進一步了解 [Exchange Server 部署助理](https://go.microsoft.com/fwlink/p/?LinkId=287036)
  
## <a name="migration-options"></a>遷移選項

組織選擇遷移選項時，應基於來源電子郵件系統、希望的結束狀態（完全託管或部分託管）、遷移的使用者人數，以及結束狀態必須多快完成。可能遷移選項：
  
- **IMAP 遷移** 將信箱資料從 IMAP 架構之電子郵件系統遷移至 Exchange Online。 
    
- **轉換 Exchange 移轉**以單一轉換方式遷移至 Exchange Online 將信箱從 Exchange Server 2003、 Exchange Server 2007、 Exchange Server 2010、 Exchange 2013 及 Hosted Exchange 系統遷移。 
    
- **分段 Exchange 遷移**執行分段的移轉將信箱從 Exchange Server 2003 或 Exchange Server 2007 的資料具有網路架構遷移工具及最少改變移轉至內部部署基礎結構。 
    
- **遠端移動移轉** 將內部部署 Exchange 信箱移轉至 Exchange 混合部署的 Exchange Online。您必須具有 Exchange 混合部署，才能使用遠端移動移轉。 
    
如需將電子郵件和信箱遷移至 Exchange Online 的詳細資訊，請參閱[將電子郵件移轉到 Exchange Online ](https://support.office.com/en-us/article/-a3e3bddb-582e-4133-8670-e61b9f58627e)。
  
### <a name="imap-migration"></a>IMAP 移轉

Exchange Online 提供網路架構工具，以便遷移支援 IMAP 的電子郵件系統中的信箱資料。它將透過以下遷移步驟來引導管理員： 
  
1. 在雲端為組織的使用者建立空信箱（通常是透過上傳 .csv 檔案，或使用遠端 Windows PowerShell 而完成）。
    
2. 輸入遠端伺服器連接設置。
    
3. Use使用 CSV 檔案來指定信箱，信箱內的資料將由 Exchange Online 信箱遷移過來。
    
4. 輸入資料之後，Exchange Online 開始透過 IMAP 遷移信箱內容（行事曆項目、聯絡人、工作，以及其他非郵件項目將不會遷移）。
    
如需 IMAP 遷移的詳細資訊，請參閱[將 IMAP 信箱移轉到 Office 365](https://support.office.com/en-ie/article/Migrate-your-IMAP-mailboxes-to-Office-365-3fe19996-29bc-4879-aab9-5a622b2f1481) 和 [將其他類型的 IMAP 信箱移轉到 Office 365](https://support.office.com/en-ie/article/Migrate-other-types-of-IMAP-mailboxes-to-Office-365-58890ccd-ce5e-4d94-be75-560a3b70a706)。
  
> [!IMPORTANT]
> 為避免在遷移過程中過度使用遠端伺服器的來源和頻寬，Exchange Online 建立低於十個連線到 IMAP 伺服器。 
  
### <a name="cutover-exchange-migration"></a>轉換 Exchange 遷移

Exchange Online 提供網路架構工具，以便從內部部署 Exchange Server 2003、Exchange Server 2007，或 Exchange Server 2010 的環境遷移資料。它將透過以下遷移步驟來引導管理員：
  
1. 對於內部部署管理員帳戶使用電子郵件地址及認證，Exchange Online 使用 自動探索 服務，連線到內部部署電子郵件組織。
    
2. Exchange Online 使用 RPC/HTTP 連線以讀取遠端伺服器的目錄資訊，並且在 Exchange Online 建立信箱。
    
3. Exchange Online 將信箱內容同步化到雲端信箱。Users使用者將資料遷移到 Exchange Online，同時保持連線到原有的信箱。
    
4. 初始移轉完成後，系統每 24 小時會進行一次同步作業，將所有變更同步至雲端，直到管理員停止或刪除批次移轉。
    
要切換使用者到雲端信箱，管理員會設定他們的 MX 紀錄指向 Office 365，並且在 Outlook 設定使用者檔案。使用者切換到雲端信箱時，他們的本機離線資料夾（.ost 檔案）會將重新同步化，結果會將遷移郵件下載到用戶端工作站。遷移之後，使用者可以回覆郵箱中的舊訊息。
  
如需轉換 Exchange 遷移的詳細資訊，請參閱[將電子郵件完全移轉到 Office 365 所需注意的事項](https://support.office.com/en-us/article/What-you-need-to-know-about-a-cutover-email-migration-to-Office-365-961978ef-f434-472d-a811-1801733869da)。
  
> [!IMPORTANT]
> 組織可以使用 Exchange 完全移轉，將最多 2,000 個信箱從 Exchange 2003、Exchange 2007、Exchange 2010 或 Exchange 2013 信箱移轉至雲端。 > Exchange Online 必須連線到一個內部部署 Exchange 伺服器，所以內部部署伺服器必須具備由可信賴之憑證授權單位所發出的憑證，以及一個公開的 IP 位址。 
  
### <a name="staged-exchange-migration"></a>Exchange 分段移轉

分段遷移的方法讓使用者能使用網路架構的 Exchange 工具，以及目錄同步處理工具來遷移至雲端。管理員不會一次遷移所有使用者，例如轉換 Exchange 遷移，而是分批遷移使用者。完成方式為上傳一個 .csv 檔案以指定遷移的使用者部份名單。在分段遷移中，組織內的所有使用者都能分享相同的電子郵件網域名稱。
  
分段 Exchange 遷移要求管理員使用線上服務目錄同步處理工具。這將提供使用者一個統一的全球通訊清單（GAL），線上環境會持續和內部部署環境進行同步化。
  
如需分段 Exchange 遷移的詳細資訊，請參閱[將電子郵件分段移轉到 Office 365 所需注意的事項](https://support.office.com/en-ie/article/What-you-need-to-know-about-a-staged-email-migration-to-Office-365-7e2c82be-5f3d-4e36-bc6b-e5b4d411e207)。
  
> [!IMPORTANT]
> 組織不能使用 Exchange 分段移轉來移轉 Exchange 2010 和 Exchange 2013 信箱。如果組織中的 Exchange 2010 或 Exchange 2013 信箱少於 2,000 個，您可以使用 Exchange 完全移轉。如果您有超過 2,000 個 Exchange 2010 或 Exchange 2013 信箱，可以實作混合部署。 > 在遷移期間，管理員必須使用線上服務目錄同步處理工具，以提供使用者統一的全球通訊清單，線上環境將持續與內部部署環境進行同步化。 
  
## <a name="migration-tools"></a>遷移工具

Microsoft 提供數種工具以協助將現存電子郵件環境遷移至 Exchange Online。至於合適者為哪些，將視組織目前環境與內部部署目的而定：
  
- **移轉儀表板** 管理員可使用 Exchange 系統管理中心的 [移轉] 儀表板，將信箱以 Exchange 完全或分段移轉的方式移轉至 Exchange Online。管理員也可以使用儀表板，將使用者信箱內容從內部部署 IMAP 伺服器移轉至現有的 Exchange Online 信箱。儀表板為管理員提供了以下功能： 
    
  - **建立和啟動多個移轉批次** 管理員可以建立並在佇列中存放最多 100 個移轉批次。一次只執行一個遷移批次，不過管理員能將多重批次排入佇列，因此當一個遷移批次執行完畢，下一個佇列批次便能開始。 
    
  - **重新啟動失敗的遷移批次**初始同步處理移轉批次，其中項目從內部部署信箱複製至雲端信箱遷移批次中每個使用者之後, 一些信箱可能會失敗同步處理。系統管理員可以重新啟動該遷移批次，以嘗試進行同步處理失敗的信箱。 
    
  - **取得略過項目之詳細資料** 針對 IMAP 移轉、完全移轉和分段移轉，[移轉] 儀表板會顯示略過之特定項目資訊，其中包括：原因以及該項目位於使用者信箱的哪個位置。 
    
  - **開啟遷移報告**系統管理員可以開啟遷移統計或遷移錯誤報告的遷移批次右儀表板。 
    
  - **編輯移轉批次**如果分段的 Exchange 遷移或 IMAP 遷移的遷移批次，但目前未執行移轉佇列中系統管理員可以編輯遷移批次。 
    
- **Azure Active Directory 同步處理工具**Azure Active Directory 同步處理工具在移轉中扮演重要的角色，混合使用 Exchange Online 與內部部署 Exchange Server 的電子郵件案例。工具的作用為進行從內部部署 Active Directory 到 Exchange Online 的單向同步化。遷移完成之後，管理員僅需使用 Exchange Online 來管理 Active Directory 使用者和群組。此工具也可讓使用者維持一致的全域通訊清單 (GAL)，線上環境會持續和內部部署環境進行同步作業。 
    
    如需 Azure Active Directory 同步處理工具的詳細資訊，請參閱[目錄同步處理：藍圖](https://go.microsoft.com/fwlink/p/?LinkId=287034)。
    
- **混合組態精靈**混合組態精靈簡化混合式部署程序來簡化的內部部署和 Exchange Online 的功能與服務的設定。採用 Exchange Server 2010 Service Pack 2 的一部分，混合組態精靈只在內部部署組織中執行，並具有下列元件： 
    
  - [Exchange 系統管理中心 (EAC)] 精靈會引導管理員透過完整的程序，進行混合部署的設定。
    
  - 一組 Exchange Management Shell（EMS）指令，安排設定過程。
    
    如需有關混合設定精靈的詳細資訊，請參閱[混合設定精靈](https://go.microsoft.com/fwlink/p/?LinkId=271734)。
    
- **遠端 Windows PowerShell**Exchange Online 2011 年 12 月的一部分服務更新、 遠端 Windows PowerShell 可用來協助疑難排解移轉錯誤。例如，系統管理員可以顯示遷移批次為遷移統計資料的診斷資訊以及為其主要的 SMTP 地址為基礎的使用者的診斷資訊。 
    
## <a name="feature-availability"></a>功能可用性

若要檢視 Office 365 計劃、獨立選項和內部部署解決方案中的功能可用性，請參閱 [Exchange Online 服務說明](exchange-online-service-description.md)。
  

