---
title: 報告功能和疑難排解工具
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-reporting-features-and-troubleshooting-tools
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7a89aaf4-747a-434a-a20b-ebc1ee10c742
description: Microsoft Exchange Online 提供各種報告功能在 Exchange 系統管理中心 (EAC)。
ms.openlocfilehash: 48e3618e6fe5d0271bc10a356f81266f74e188f6
ms.sourcegitcommit: 19591e97b35c1b2a99e04a496d83af27dc6530d6
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 10/18/2019
ms.locfileid: "37581989"
---
# <a name="reporting-features-and-troubleshooting-tools"></a><span data-ttu-id="789d6-103">報告功能和疑難排解工具</span><span class="sxs-lookup"><span data-stu-id="789d6-103">Reporting features and troubleshooting tools</span></span>

<span data-ttu-id="789d6-104">Microsoft Exchange Online 提供各種報告功能在 Exchange 系統管理中心 (EAC)。</span><span class="sxs-lookup"><span data-stu-id="789d6-104">Microsoft Exchange Online offers a variety of reporting features both in and out of the Exchange admin center (EAC).</span></span>
  
## <a name="reporting-features"></a><span data-ttu-id="789d6-105">報告功能</span><span class="sxs-lookup"><span data-stu-id="789d6-105">Reporting features</span></span>

<span data-ttu-id="789d6-106">Exchange Online 客戶可以存取 Microsoft 365 系統管理中心內的報告，透過下載 Excel 報告活頁簿，或使用 web 服務。</span><span class="sxs-lookup"><span data-stu-id="789d6-106">Exchange Online customers can access reports in the Microsoft 365 admin center, by downloading an Excel reporting workbook, or by using web services.</span></span>
  
### <a name="reporting-in-the-microsoft-365-admin-center"></a><span data-ttu-id="789d6-107">在 Microsoft 365 系統管理中心報告</span><span class="sxs-lookup"><span data-stu-id="789d6-107">Reporting in the Microsoft 365 admin center</span></span>

<span data-ttu-id="789d6-108">有 Microsoft 365 系統管理中心 [報告] 頁面上的報告，提供有關信箱和群組的摘要資訊。</span><span class="sxs-lookup"><span data-stu-id="789d6-108">There are reports on the Reports page in the Microsoft 365 admin center that provide summary information about mailboxes and groups.</span></span> <span data-ttu-id="789d6-109">例如，一份報告列出了依日、週或年所建立和刪除的群組數目。</span><span class="sxs-lookup"><span data-stu-id="789d6-109">For example, one report lists the number of groups created and deleted by day, week, month, or year.</span></span> <span data-ttu-id="789d6-110">也有新增和刪除信箱的摘要報告，以及使用中和非使用中信箱的摘要報告。</span><span class="sxs-lookup"><span data-stu-id="789d6-110">There are also summary reports for new and deleted mailboxes, and active and inactive mailboxes.</span></span> 
  
<span data-ttu-id="789d6-111">此外，在 Microsoft 365 系統管理中心 [報告] 頁面包含郵件的資料報告，提供有關郵件流量、 垃圾郵件和惡意程式碼偵測和郵件受到 Exchange 傳輸規則] 或 [資料外洩防護 (DLP) 的資訊原則。</span><span class="sxs-lookup"><span data-stu-id="789d6-111">Additionally, the Reports page in the Microsoft 365 admin center contains messaging data reports, which provide information about message traffic, spam and malware detections, and messages affected by Exchange Transport Rules or Data Loss Prevention (DLP) policies.</span></span> <span data-ttu-id="789d6-112">保護、規則和 DLP 的增強型報告可讓 Exchange Online 系統管理員享有互動報告體驗。</span><span class="sxs-lookup"><span data-stu-id="789d6-112">The enhanced reports for protection, rules, and DLP offer an interactive reporting experience for Exchange Online admins.</span></span> <span data-ttu-id="789d6-113">這些報告提供摘要資料，而且可供人向下切入至個別郵件的詳細資料。</span><span class="sxs-lookup"><span data-stu-id="789d6-113">These reports provide summary data and the ability to drill down into details about individual messages.</span></span>
  
<span data-ttu-id="789d6-114">如需每個 Office 365 訂閱可用報告的詳細資訊，請參閱[報告](../office-365-platform-service-description/reports.md)。</span><span class="sxs-lookup"><span data-stu-id="789d6-114">For more information about which reports are available with each Office 365 subscription, see [Reports](../office-365-platform-service-description/reports.md).</span></span> <span data-ttu-id="789d6-115">如 Microsoft 365 系統管理中心中，[報告] 頁面的詳細的資訊，請參閱[檢視並下載有關 Office 365 中服務使用情況報告](https://go.microsoft.com/fwlink/p/?LinkId=401187)和[使用的郵件保護報告在 Office 365 中以檢視有關惡意程式碼、 垃圾郵件和規則偵測的資訊](https://go.microsoft.com/fwlink/p/?LinkID=401102).</span><span class="sxs-lookup"><span data-stu-id="789d6-115">For more detailed information about the Reports page in the Microsoft 365 admin center, see [View and download reports about service usage in Office 365](https://go.microsoft.com/fwlink/p/?LinkId=401187) and [Use mail protection reports in Office 365 to view data about malware, spam, and rule detections](https://go.microsoft.com/fwlink/p/?LinkID=401102).</span></span>
  
### <a name="reporting-using-the-excel-reporting-workbook"></a><span data-ttu-id="789d6-116">使用 Excel 報告活頁簿執行報告</span><span class="sxs-lookup"><span data-stu-id="789d6-116">Reporting using the Excel reporting workbook</span></span>

<span data-ttu-id="789d6-117">您也可以使用 Excel 2013 報告活頁簿，來檢視具有深入探查功能的摘要報告。</span><span class="sxs-lookup"><span data-stu-id="789d6-117">You can also use the Excel 2013 reporting workbook to view summary reports with drill-down capabilities.</span></span> <span data-ttu-id="789d6-118">不過，我們建議您改為使用增強的 Microsoft 365 系統管理中心報告。</span><span class="sxs-lookup"><span data-stu-id="789d6-118">However, we recommend using the enhanced Microsoft 365 admin center reports instead.</span></span> <span data-ttu-id="789d6-119">Excel 2013 報告活頁簿預計將在未來被取代。</span><span class="sxs-lookup"><span data-stu-id="789d6-119">The Excel 2013 reporting workbook is planned to be deprecated in the future.</span></span> <span data-ttu-id="789d6-120">如需更多概觀資訊，以及下載和安裝活頁簿的連結，請參閱下列[下載頁面](https://go.microsoft.com/fwlink/p/?LinkId=271776)。</span><span class="sxs-lookup"><span data-stu-id="789d6-120">For more overview information and links to download and install the workbook, see the following [download page](https://go.microsoft.com/fwlink/p/?LinkId=271776).</span></span> <span data-ttu-id="789d6-121">如需有關如何使用活頁簿的資訊，請參閱[使用 Excel 報告活頁簿的郵件保護報告](https://go.microsoft.com/fwlink/p/?LinkId=285211)。</span><span class="sxs-lookup"><span data-stu-id="789d6-121">For information about how to use the workbook, see [Mail Protection Reports Using the Excel Reporting Workbook](https://go.microsoft.com/fwlink/p/?LinkId=285211).</span></span> 
  
### <a name="reporting-using-web-services"></a><span data-ttu-id="789d6-122">Reporting using web services</span><span class="sxs-lookup"><span data-stu-id="789d6-122">Reporting using web services</span></span>

<span data-ttu-id="789d6-123">存取信箱、 群組及郵件資料的相關的摘要和詳細報告，請使用 REST/OData 租用戶報告 web 服務，也就是可讓您建立自訂報告的程式設計介面。</span><span class="sxs-lookup"><span data-stu-id="789d6-123">Access to both summary and detailed reports about mailboxes, groups, and messaging data is available by using the REST/OData Tenant Reporting web service, which is a programmatic interface that lets you create custom reports.</span></span> <span data-ttu-id="789d6-124">如需詳細資訊，請參閱[Office 365 報告 web 服務](https://go.microsoft.com/fwlink/p/?LinkId=287041)。</span><span class="sxs-lookup"><span data-stu-id="789d6-124">For more information, see [Office 365 Reporting web services](https://go.microsoft.com/fwlink/p/?LinkId=287041).</span></span>
  
## <a name="reporting-features-and-troubleshooting-tools-in-the-eac"></a><span data-ttu-id="789d6-125">EAC 中的報告功能和疑難排解工具</span><span class="sxs-lookup"><span data-stu-id="789d6-125">Reporting features and troubleshooting tools in the EAC</span></span>

<span data-ttu-id="789d6-126">您可在 Exchange 系統管理中心中使用下列報告功能和疑難排解工具。</span><span class="sxs-lookup"><span data-stu-id="789d6-126">The following reporting features and troubleshooting tools are available in the Exchange admin center.</span></span>
  
### <a name="trace-an-email-message"></a><span data-ttu-id="789d6-127">追蹤電子郵件訊息</span><span class="sxs-lookup"><span data-stu-id="789d6-127">Trace an email message</span></span>

<span data-ttu-id="789d6-128">郵件追蹤功能可讓您，身為系統管理員，請遵循電子郵件，通過您 Exchange Online 服務。</span><span class="sxs-lookup"><span data-stu-id="789d6-128">The message trace feature lets you, as an administrator, follow email messages as they pass through your Exchange Online service.</span></span> <span data-ttu-id="789d6-129">它可以協助您判斷服務是否已接收、拒絕、延遲或傳遞目標電子郵件訊息。</span><span class="sxs-lookup"><span data-stu-id="789d6-129">It helps you determine whether a targeted email message was received, rejected, deferred, or delivered by the service.</span></span> <span data-ttu-id="789d6-130">此舉可讓您有效回答使用者的問題和疑難排解郵件流程問題，減少了需要連絡技術支援尋求協助的需求。</span><span class="sxs-lookup"><span data-stu-id="789d6-130">This lets you efficiently answer your users' questions and troubleshoot mail flow issues, and alleviates the need to contact technical support for assistance.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="789d6-p107">若要疑難排解一般問題和趨勢，請使用報告工具以取得此類資料。對於需要訊息詳細資料的單點細節，請使用郵件追蹤工具。</span><span class="sxs-lookup"><span data-stu-id="789d6-p107">For troubleshooting general issues and trends, use the reporting tools to obtain such data. For single point specifics where details are needed about a message, use the message trace tool.</span></span> 
  
<span data-ttu-id="789d6-133">如需有關郵件追蹤功能的詳細資訊，請參閱[追蹤電子郵件訊息](https://go.microsoft.com/fwlink/p/?LinkId=271777)。</span><span class="sxs-lookup"><span data-stu-id="789d6-133">For more information about the message trace feature, see [Trace an Email Message](https://go.microsoft.com/fwlink/p/?LinkId=271777).</span></span>
  
### <a name="auditing-reports"></a><span data-ttu-id="789d6-134">稽核報告</span><span class="sxs-lookup"><span data-stu-id="789d6-134">Auditing reports</span></span>

<span data-ttu-id="789d6-p108">您可以使用稽核記錄來追蹤系統管理員所做的特定變更，藉以疑難排解組態問題，以及協助您符合法規、規範和訴訟需求。Exchange Online 提供了兩種稽核記錄：</span><span class="sxs-lookup"><span data-stu-id="789d6-p108">You can use audit logging to troubleshoot configuration issues by tracking specific changes made by administrators and to help you meet regulatory, compliance, and litigation requirements. Exchange Online provides two types of audit logging:</span></span>
  
- <span data-ttu-id="789d6-p109">系統管理員稽核記錄記錄記錄由系統管理員執行的任何動作。這種記錄可以協助您疑難排解組態問題，或識別安全性相關或規範符合性相關問題的原因。</span><span class="sxs-lookup"><span data-stu-id="789d6-p109">Administrator audit logging records any action performed by an administrator. This can help you troubleshoot configuration issues or identify the cause of security-related or compliance-related problems.</span></span> 
    
- <span data-ttu-id="789d6-p110">「信箱稽核記錄」會記錄信箱擁有者以外人員存取信箱的行為。這種記錄可以協助您判斷存取信箱的人員以及他們進行的動作。</span><span class="sxs-lookup"><span data-stu-id="789d6-p110">Mailbox audit logging records whenever a mailbox is accessed by someone other than the person who owns the mailbox. This can help you determine who has accessed a mailbox and what they've done.</span></span> 
    
<span data-ttu-id="789d6-141">如需有關稽核記錄的詳細資訊，請參閱[稽核報告](https://go.microsoft.com/fwlink/p/?LinkId=271779)。</span><span class="sxs-lookup"><span data-stu-id="789d6-141">For more information about audit logging, see [Auditing Reports](https://go.microsoft.com/fwlink/p/?LinkId=271779).</span></span>
  
### <a name="unified-messaging-reports"></a><span data-ttu-id="789d6-142">整合通訊報告</span><span class="sxs-lookup"><span data-stu-id="789d6-142">Unified Messaging reports</span></span>

<span data-ttu-id="789d6-p111">您可以在 Exchange Online 組織中使用這些報告來監控和疑難排解整合通訊 (UM)。如需詳細資訊，請參閱[執行語音信箱通話報告](https://go.microsoft.com/fwlink/p/?LinkId=287042)。</span><span class="sxs-lookup"><span data-stu-id="789d6-p111">You can use these reports to monitor and troubleshoot Unified Messaging (UM) in your Exchange Online organization. For more information, see [Run Reports for Voice Mail Calls](https://go.microsoft.com/fwlink/p/?LinkId=287042).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="789d6-145">功能可用性</span><span class="sxs-lookup"><span data-stu-id="789d6-145">Feature availability</span></span>

<span data-ttu-id="789d6-146">若要檢視跨 Office 365 計劃、 獨立選項和內部部署解決方案的功能可用性，請參閱[Exchange Online 服務說明](exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="789d6-146">To view feature availability across Office 365 plans, standalone options, and on-premises solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

