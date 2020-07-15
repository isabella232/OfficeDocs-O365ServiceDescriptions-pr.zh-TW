---
title: 規劃及部署
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-planning-and-deployment
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: e44e5e61-1f5d-4e68-981d-77a42f0ea0d4
ms.openlocfilehash: e722bec332e67e93647b10bbbf4916e7e059c1b7
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132657"
---
# <a name="planning-and-deployment"></a>規劃及部署

## <a name="planning-for-service-changes-and-growth"></a>規劃服務的變化和增長

組織選擇遷移選項時，應基於來源電子郵件系統、希望的結束狀態（完全託管或部分託管）、遷移的使用者人數，以及結束狀態必須多快完成。
  
## <a name="deployment-options"></a>部署選項

- **Cloud-only deployment** Your organization has all user mailboxes hosted in Exchange Online. 
    
- **Exchange 混合部署** 你的組織將部分使用者信箱託管於內部佈署 Exchange 組織，部分使用者信箱託管於 Exchange Online。 
    
### <a name="cloud-only"></a>僅雲端

A cloud-only deployment is one where your organization in the Exchange Online service isn't connected with an on-premises Exchange organization. All users and mailboxes are hosted and managed in Exchange Online and Office 365.
  
### <a name="hybrid"></a>混合式

Available for Microsoft Exchange 2003, Exchange 2007, Exchange 2010 and Exchange 2013 on-premises organizations, a hybrid deployment offers either a long-term coexistence configuration with some mailboxes hosted on-premises and some mailboxes hosted in Exchange Online or a migration path to hosting all user mailboxes in Exchange Online. A hybrid deployment offers organizations the ability to extend the feature-rich experience and administrative control they have with their existing on-premises Microsoft Exchange organization to the cloud. Hybrid deployment features include secure mail transport, shared calendar free/busy information, and message tracking between the on-premises and Exchange Online organizations.
  
For more information about hybrid deployments, see [Exchange Server 2013 Hybrid Deployments](https://go.microsoft.com/fwlink/p/?LinkId=287035). If you are using Office 365 operated by 21Vianet, see [Configuring Exchange hybrid deployment features with Office 365 operated by 21Vianet](https://go.microsoft.com/fwlink/?LinkID=733373&amp;clcid=0x409).
  
> [!IMPORTANT]
> On-premises Exchange 2003 organizations must install at least one Exchange 2010 Client Access/Mailbox server to configure a hybrid deployment with Exchange Online. On-premises Exchange 2007 organizations must install at least one Exchange 2010 or Exchange 2013 Client Access and Mailbox server to configure a hybrid deployment with Exchange Online. On-premises Exchange 2010 and Exchange 2013 organizations natively support hybrid deployments with Exchange Online. For more information about Exchange server compatibility in hybrid deployments, see [Hybrid Deployment Prerequisites](https://go.microsoft.com/fwlink/p/?LinkId=243541)> On-premises Exchange organizations must configure their organization for a hybrid deployment. We strongly recommend that administrators use the Exchange Server Deployment Assistant and the Hybrid Configuration Wizard to configure the hybrid deployment. Learn more at [Exchange Server Deployment Assistant](https://go.microsoft.com/fwlink/p/?LinkId=287036)
  
## <a name="migration-options"></a>遷移選項

Organizations should choose migration options based on their source email systems, the desired end state (fully hosted or partially hosted), the number of users to migrate, and how quickly the end state needs to be reached. Possible migration options are:
  
- **IMAP 遷移** 將信箱資料從 IMAP 架構之電子郵件系統遷移至 Exchange Online。 
    
- **Cutover Exchange migration** Migrate mailboxes from Exchange Server 2003, Exchange Server 2007, Exchange Server 2010, Exchange 2013 and Hosted Exchange systems to Exchange Online in a single cutover migration. 
    
- **Staged Exchange migration** Perform a staged migration to migrate mailboxes from Exchange Server 2003 or Exchange Server 2007 with web-based migration tools and minimal changes to on-premises infrastructure. 
    
- **Remote move migration** Migrate on-premises Exchange mailboxes to Exchange Online in an Exchange hybrid deployment. You must have an Exchange hybrid deployment to use a remote move migration. 
    
如需將電子郵件和信箱遷移至 Exchange Online 的詳細資訊，請參閱[將電子郵件移轉到 Exchange Online ](https://support.office.com/en-us/article/-a3e3bddb-582e-4133-8670-e61b9f58627e)。
  
### <a name="imap-migration"></a>網際網路訊息存取通訊協定 (IMAP) 移轉

Exchange Online offers a web-based tool for migrating mailbox data from email systems that support IMAP. It guides administrators through the following migration steps: 
  
1. 在雲端為組織的使用者建立空信箱（通常是透過上傳 .csv 檔案，或使用遠端 Windows PowerShell 而完成）。
    
2. 輸入遠端伺服器連接設置。
    
3. Use使用 CSV 檔案來指定信箱，信箱內的資料將由 Exchange Online 信箱遷移過來。
    
4. 輸入資料之後，Exchange Online 開始透過 IMAP 遷移信箱內容（行事曆項目、聯絡人、工作，以及其他非郵件項目將不會遷移）。
    
如需 IMAP 遷移的詳細資訊，請參閱[將 IMAP 信箱移轉到 Office 365](https://support.office.com/en-ie/article/Migrate-your-IMAP-mailboxes-to-Office-365-3fe19996-29bc-4879-aab9-5a622b2f1481) 和 [將其他類型的 IMAP 信箱移轉到 Office 365](https://support.office.com/en-ie/article/Migrate-other-types-of-IMAP-mailboxes-to-Office-365-58890ccd-ce5e-4d94-be75-560a3b70a706)。
  
> [!IMPORTANT]
> 為避免在遷移過程中過度使用遠端伺服器的來源和頻寬，Exchange Online 建立低於十個連線到 IMAP 伺服器。 
  
### <a name="cutover-exchange-migration"></a>Exchange 完全移轉

Exchange Online offers a web-based tool for migrating data from on-premises Exchange Server 2003, Exchange Server 2007, or Exchange Server 2010 environments. It guides an administrator through the following migration steps:
  
1. 對於內部部署管理員帳戶使用電子郵件地址及認證，Exchange Online 使用 自動探索 服務，連線到內部部署電子郵件組織。
    
2. Exchange Online 使用 RPC/HTTP 連線以讀取遠端伺服器的目錄資訊，並且在 Exchange Online 建立信箱。
    
3. Exchange Online synchronizes the mailbox content to the cloud mailboxes. Users remain connected to their original mailboxes while their data is being migrated to Exchange Online.
    
4. 初始移轉完成後，系統每 24 小時會進行一次同步作業，將所有變更同步至雲端，直到管理員停止或刪除批次移轉。
    
若要將使用者切換至其雲端信箱，系統管理員會設定其 MX 記錄，使其指向 Microsoft，並在 Outlook 中重新設定使用者的設定檔。 使用者切換到雲端信箱時，他們的本機離線資料夾（.ost 檔案）會將重新同步化，結果會將遷移郵件下載到用戶端工作站。 遷移之後，使用者可以回覆郵箱中的舊訊息。
  
如需轉換 Exchange 遷移的詳細資訊，請參閱[將電子郵件完全移轉到 Office 365 所需注意的事項](https://support.office.com/en-us/article/What-you-need-to-know-about-a-cutover-email-migration-to-Office-365-961978ef-f434-472d-a811-1801733869da)。
  
> [!IMPORTANT]
> An organization can migrate a maximum of 2,000 Exchange 2003, Exchange 2007, Exchange 2010, or Exchange 2013 mailboxes to the cloud using a cutover Exchange migration. > Exchange Online must connect to an on-premises Exchange Server, so the on-premises server must have a certificate issued by a trusted certificate authority and a public IP address. 
  
### <a name="staged-exchange-migration"></a>Exchange 分段移轉

With a staged migration, users can be migrated to the cloud using the web-based Exchange migration tool and the Directory Synchronization tool. Instead of migrating all users at once, like a cutover Exchange migration, administrators migrate users in batches. This is accomplished by uploading a .csv file to specify a partial list of users to migrate. In a staged migration, all of the users in an organization can share the same email domain name.
  
Staged Exchange migration requires administrators to use the Online Services Directory Synchronization tool. This provides users with a unified Global Address List (GAL) where the online environment is continuously synchronized with the on-premises environment.
  
如需分段 Exchange 遷移的詳細資訊，請參閱[將電子郵件分段移轉到 Office 365 所需注意的事項](https://support.office.com/en-ie/article/What-you-need-to-know-about-a-staged-email-migration-to-Office-365-7e2c82be-5f3d-4e36-bc6b-e5b4d411e207)。
  
> [!IMPORTANT]
> Organizations can't use a staged Exchange migration to migrate Exchange 2010 and Exchange 2013 mailboxes. If you have fewer than 2,000 Exchange 2010 or Exchange 2013 mailboxes in your organization, you can use a cutover Exchange migration. If you have more than 2,000 Exchange 2010 or Exchange 2013 mailboxes, you can implement a hybrid deployment. > During migration, administrators must use the Online Services Directory Synchronization tool to provide users with a unified Global Address List where the online environment is continuously synchronized with the on-premises environment. 
  
## <a name="migration-tools"></a>遷移工具

Microsoft provides several tools to help migrate an existing email environment to Exchange Online. Which ones are appropriate depends on the organization's current environment and deployment goals:
  
- **Migration dashboard** Administrators can use the Migration dashboard in the Exchange admin center to manage mailbox migration to Exchange Online in a cutover or staged Exchange migration. Administrators can also use the dashboard to migrate the contents of users' mailboxes from an on-premises IMAP server to existing Exchange Online mailboxes. The dashboard gives administrators the following capabilities: 
    
  - **Create and start multiple migration batches** Administrators can create and queue up to 100 migration batches. Only one migration batch runs at a time, but administrators can queue up multiple batches, so when a migration batch is finished running the next batch in the queue starts. 
    
  - **Restart a migration batch with failures** After the initial synchronization for a migration batch, where items are copied from on-premises mailboxes to the cloud mailboxes for each user in the migration batch, some mailboxes may fail synchronization. Administrators can restart that migration batch to try to synchronize the failed mailboxes. 
    
  - **取得略過項目之詳細資料** 針對 IMAP 移轉、完全移轉和分段移轉，[移轉] 儀表板會顯示略過之特定項目資訊，其中包括：原因以及該項目位於使用者信箱的哪個位置。 
    
  - **Open migration reports** Administrators can open migration statistics or the migration error report for a migration batch right from the dashboard. 
    
  - **Edit a migration batch** If a migration batch for a staged Exchange migration or an IMAP migration is in the migration queue but not currently running, administrators can edit the migration batch. 
    
- **Azure Active Directory Sync tool** The Azure Active Directory Sync tool plays an important role in migration to hybrid email scenarios that utilize both Exchange Online and an on-premises Exchange Server. The tool performs a one-way synchronization from on-premises Active Directory to Exchange Online. After migration is complete, administrators only need to use Exchange Online to manage Active Directory users and groups. The tool also provides users with a unified Global Address List where the online environment is continuously synchronized with the on-premises environment. 
    
    如需 Azure Active Directory 同步處理工具的詳細資訊，請參閱[目錄同步處理：藍圖](https://go.microsoft.com/fwlink/p/?LinkId=287034)。
    
- **Hybrid Configuration Wizard** The Hybrid Configuration Wizard streamlines the hybrid deployment process by simplifying the on-premises and Exchange Online configuration of features and services. Introduced as part of Exchange Server 2010 Service Pack 2, the Hybrid Configuration Wizard is run only in on-premises organizations and has the following components: 
    
  - [Exchange 系統管理中心 (EAC)] 精靈會引導管理員透過完整的程序，進行混合部署的設定。
    
  - 一組 Exchange Management Shell（EMS）指令，安排設定過程。
    
    如需有關混合設定精靈的詳細資訊，請參閱[混合設定精靈](https://go.microsoft.com/fwlink/p/?LinkId=271734)。
    
- **Remote Windows PowerShell** As part of the Exchange Online December 2011 Service Update, remote Windows PowerShell can be used to help troubleshoot migration errors. For instance, administrators can display diagnostic information for migration batches, as well as migration statistics and diagnostic information for users based on their primary SMTP addresses. 
    
## <a name="feature-availability"></a>功能可用性

若要查看各個方案、獨立選項和內部部署方案中的功能可用性，請參閱[Exchange Online 服務說明](exchange-online-service-description.md)。
  

