---
title: 報告功能和疑難排解工具
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-reporting-features-and-troubleshooting-tools
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7a89aaf4-747a-434a-a20b-ebc1ee10c742
description: Microsoft Exchange Online 提供 Exchange 系統管理中心（EAC）內和以外的各種報告功能。
ms.openlocfilehash: f2cc51c9923be8d399fa2837e5b5fabe3117d5ba
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132597"
---
# <a name="reporting-features-and-troubleshooting-tools"></a><span data-ttu-id="888a6-103">報告功能和疑難排解工具</span><span class="sxs-lookup"><span data-stu-id="888a6-103">Reporting features and troubleshooting tools</span></span>

<span data-ttu-id="888a6-104">Microsoft Exchange Online 提供 Exchange 系統管理中心（EAC）內和以外的各種報告功能。</span><span class="sxs-lookup"><span data-stu-id="888a6-104">Microsoft Exchange Online offers a variety of reporting features both in and out of the Exchange admin center (EAC).</span></span>
  
## <a name="reporting-features"></a><span data-ttu-id="888a6-105">報告功能</span><span class="sxs-lookup"><span data-stu-id="888a6-105">Reporting features</span></span>

<span data-ttu-id="888a6-106">Exchange Online 客戶可以透過下載 Excel 報告活頁簿或使用 web 服務，存取 Microsoft 365 系統管理中心中的報告。</span><span class="sxs-lookup"><span data-stu-id="888a6-106">Exchange Online customers can access reports in the Microsoft 365 admin center, by downloading an Excel reporting workbook, or by using web services.</span></span>
  
### <a name="reporting-in-the-microsoft-365-admin-center"></a><span data-ttu-id="888a6-107">Microsoft 365 系統管理中心的報告</span><span class="sxs-lookup"><span data-stu-id="888a6-107">Reporting in the Microsoft 365 admin center</span></span>

<span data-ttu-id="888a6-108">Microsoft 365 系統管理中心的 [報告] 頁面上有報告，提供信箱和群組的摘要資訊。</span><span class="sxs-lookup"><span data-stu-id="888a6-108">There are reports on the Reports page in the Microsoft 365 admin center that provide summary information about mailboxes and groups.</span></span> <span data-ttu-id="888a6-109">例如，一份報告列出了依日、週或年所建立和刪除的群組數目。</span><span class="sxs-lookup"><span data-stu-id="888a6-109">For example, one report lists the number of groups created and deleted by day, week, month, or year.</span></span> <span data-ttu-id="888a6-110">也有新增和刪除信箱的摘要報告，以及使用中和非使用中信箱的摘要報告。</span><span class="sxs-lookup"><span data-stu-id="888a6-110">There are also summary reports for new and deleted mailboxes, and active and inactive mailboxes.</span></span> 
  
<span data-ttu-id="888a6-111">此外，Microsoft 365 系統管理中心的 [報告] 頁面包含郵件資料包告，其可提供郵件流量、垃圾郵件和惡意程式碼偵測的相關資訊，以及受 Exchange Transport Rules 或資料遺失防護（DLP）原則影響的郵件。</span><span class="sxs-lookup"><span data-stu-id="888a6-111">Additionally, the Reports page in the Microsoft 365 admin center contains messaging data reports, which provide information about message traffic, spam and malware detections, and messages affected by Exchange Transport Rules or Data Loss Prevention (DLP) policies.</span></span> <span data-ttu-id="888a6-112">保護、規則和 DLP 的增強型報告可讓 Exchange Online 系統管理員享有互動報告體驗。</span><span class="sxs-lookup"><span data-stu-id="888a6-112">The enhanced reports for protection, rules, and DLP offer an interactive reporting experience for Exchange Online admins.</span></span> <span data-ttu-id="888a6-113">這些報告提供摘要資料，而且可供人向下切入至個別郵件的詳細資料。</span><span class="sxs-lookup"><span data-stu-id="888a6-113">These reports provide summary data and the ability to drill down into details about individual messages.</span></span>
  
<span data-ttu-id="888a6-114">如需每個訂閱可用報告的詳細資訊，請參閱[報告](../office-365-platform-service-description/reports.md)。</span><span class="sxs-lookup"><span data-stu-id="888a6-114">For more information about which reports are available with each subscription, see [Reports](../office-365-platform-service-description/reports.md).</span></span> <span data-ttu-id="888a6-115">如需 Microsoft 365 系統管理中心內 [報告] 頁面的詳細資訊，請參閱[view and 下載中心 For Office 365 中的服務使用狀況](https://go.microsoft.com/fwlink/p/?LinkId=401187)和[使用郵件保護報告來查看有關惡意程式碼、垃圾郵件和規則](https://go.microsoft.com/fwlink/p/?LinkID=401102)偵測的資料。</span><span class="sxs-lookup"><span data-stu-id="888a6-115">For more detailed information about the Reports page in the Microsoft 365 admin center, see [View and download reports about service usage in Office 365](https://go.microsoft.com/fwlink/p/?LinkId=401187) and [Use mail protection reports to view data about malware, spam, and rule detections](https://go.microsoft.com/fwlink/p/?LinkID=401102).</span></span>
  
### <a name="reporting-using-the-excel-reporting-workbook"></a><span data-ttu-id="888a6-116">使用 Excel 報告活頁簿執行報告</span><span class="sxs-lookup"><span data-stu-id="888a6-116">Reporting using the Excel reporting workbook</span></span>

<span data-ttu-id="888a6-117">您也可以使用 Excel 2013 報告活頁簿，來檢視具有深入探查功能的摘要報告。</span><span class="sxs-lookup"><span data-stu-id="888a6-117">You can also use the Excel 2013 reporting workbook to view summary reports with drill-down capabilities.</span></span> <span data-ttu-id="888a6-118">不過，我們建議您改為使用增強型 Microsoft 365 系統管理中心報告。</span><span class="sxs-lookup"><span data-stu-id="888a6-118">However, we recommend using the enhanced Microsoft 365 admin center reports instead.</span></span> <span data-ttu-id="888a6-119">Excel 2013 報告活頁簿預計將在未來被取代。</span><span class="sxs-lookup"><span data-stu-id="888a6-119">The Excel 2013 reporting workbook is planned to be deprecated in the future.</span></span> <span data-ttu-id="888a6-120">如需更多概觀資訊，以及下載和安裝活頁簿的連結，請參閱下列[下載頁面](https://go.microsoft.com/fwlink/p/?LinkId=271776)。</span><span class="sxs-lookup"><span data-stu-id="888a6-120">For more overview information and links to download and install the workbook, see the following [download page](https://go.microsoft.com/fwlink/p/?LinkId=271776).</span></span> <span data-ttu-id="888a6-121">如需有關如何使用活頁簿的資訊，請參閱[使用 Excel 報告活頁簿的郵件保護報告](https://go.microsoft.com/fwlink/p/?LinkId=285211)。</span><span class="sxs-lookup"><span data-stu-id="888a6-121">For information about how to use the workbook, see [Mail Protection Reports Using the Excel Reporting Workbook](https://go.microsoft.com/fwlink/p/?LinkId=285211).</span></span> 
  
### <a name="reporting-using-web-services"></a><span data-ttu-id="888a6-122">Reporting using web services</span><span class="sxs-lookup"><span data-stu-id="888a6-122">Reporting using web services</span></span>

<span data-ttu-id="888a6-123">您可以使用 REST/OData 租使用者報告 web 服務（這是一種程式設計介面，可讓您建立自訂報告），存取信箱、群組和郵件資料的摘要和詳細報告。</span><span class="sxs-lookup"><span data-stu-id="888a6-123">Access to both summary and detailed reports about mailboxes, groups, and messaging data is available by using the REST/OData Tenant Reporting web service, which is a programmatic interface that lets you create custom reports.</span></span> <span data-ttu-id="888a6-124">如需詳細資訊，請參閱[Office 365 報告 web 服務](https://go.microsoft.com/fwlink/p/?LinkId=287041)。</span><span class="sxs-lookup"><span data-stu-id="888a6-124">For more information, see [Office 365 Reporting web services](https://go.microsoft.com/fwlink/p/?LinkId=287041).</span></span>
  
## <a name="reporting-features-and-troubleshooting-tools-in-the-eac"></a><span data-ttu-id="888a6-125">EAC 中的報告功能和疑難排解工具</span><span class="sxs-lookup"><span data-stu-id="888a6-125">Reporting features and troubleshooting tools in the EAC</span></span>

<span data-ttu-id="888a6-126">您可在 Exchange 系統管理中心中使用下列報告功能和疑難排解工具。</span><span class="sxs-lookup"><span data-stu-id="888a6-126">The following reporting features and troubleshooting tools are available in the Exchange admin center.</span></span>
  
### <a name="trace-an-email-message"></a><span data-ttu-id="888a6-127">追蹤電子郵件訊息</span><span class="sxs-lookup"><span data-stu-id="888a6-127">Trace an email message</span></span>

<span data-ttu-id="888a6-128">郵件追蹤功能可讓您以系統管理員的身分，在電子郵件訊息通過 Exchange Online 服務時，追蹤電子郵件。</span><span class="sxs-lookup"><span data-stu-id="888a6-128">The message trace feature lets you, as an administrator, follow email messages as they pass through your Exchange Online service.</span></span> <span data-ttu-id="888a6-129">它可以協助您判斷服務是否已接收、拒絕、延遲或傳遞目標電子郵件訊息。</span><span class="sxs-lookup"><span data-stu-id="888a6-129">It helps you determine whether a targeted email message was received, rejected, deferred, or delivered by the service.</span></span> <span data-ttu-id="888a6-130">此舉可讓您有效回答使用者的問題和疑難排解郵件流程問題，減少了需要連絡技術支援尋求協助的需求。</span><span class="sxs-lookup"><span data-stu-id="888a6-130">This lets you efficiently answer your users' questions and troubleshoot mail flow issues, and alleviates the need to contact technical support for assistance.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="888a6-131">For troubleshooting general issues and trends, use the reporting tools to obtain such data.</span><span class="sxs-lookup"><span data-stu-id="888a6-131">For troubleshooting general issues and trends, use the reporting tools to obtain such data.</span></span> <span data-ttu-id="888a6-132">For single point specifics where details are needed about a message, use the message trace tool.</span><span class="sxs-lookup"><span data-stu-id="888a6-132">For single point specifics where details are needed about a message, use the message trace tool.</span></span> 
  
<span data-ttu-id="888a6-133">如需有關郵件追蹤功能的詳細資訊，請參閱[追蹤電子郵件訊息](https://go.microsoft.com/fwlink/p/?LinkId=271777)。</span><span class="sxs-lookup"><span data-stu-id="888a6-133">For more information about the message trace feature, see [Trace an Email Message](https://go.microsoft.com/fwlink/p/?LinkId=271777).</span></span>
  
### <a name="auditing-reports"></a><span data-ttu-id="888a6-134">稽核報告</span><span class="sxs-lookup"><span data-stu-id="888a6-134">Auditing reports</span></span>

<span data-ttu-id="888a6-135">You can use audit logging to troubleshoot configuration issues by tracking specific changes made by administrators and to help you meet regulatory, compliance, and litigation requirements.</span><span class="sxs-lookup"><span data-stu-id="888a6-135">You can use audit logging to troubleshoot configuration issues by tracking specific changes made by administrators and to help you meet regulatory, compliance, and litigation requirements.</span></span> <span data-ttu-id="888a6-136">Exchange Online provides two types of audit logging:</span><span class="sxs-lookup"><span data-stu-id="888a6-136">Exchange Online provides two types of audit logging:</span></span>
  
- <span data-ttu-id="888a6-137">Administrator audit logging records any action performed by an administrator.</span><span class="sxs-lookup"><span data-stu-id="888a6-137">Administrator audit logging records any action performed by an administrator.</span></span> <span data-ttu-id="888a6-138">This can help you troubleshoot configuration issues or identify the cause of security-related or compliance-related problems.</span><span class="sxs-lookup"><span data-stu-id="888a6-138">This can help you troubleshoot configuration issues or identify the cause of security-related or compliance-related problems.</span></span> 
    
- <span data-ttu-id="888a6-139">Mailbox audit logging records whenever a mailbox is accessed by someone other than the person who owns the mailbox.</span><span class="sxs-lookup"><span data-stu-id="888a6-139">Mailbox audit logging records whenever a mailbox is accessed by someone other than the person who owns the mailbox.</span></span> <span data-ttu-id="888a6-140">This can help you determine who has accessed a mailbox and what they've done.</span><span class="sxs-lookup"><span data-stu-id="888a6-140">This can help you determine who has accessed a mailbox and what they've done.</span></span> 
    
<span data-ttu-id="888a6-141">如需有關稽核記錄的詳細資訊，請參閱[稽核報告](https://go.microsoft.com/fwlink/p/?LinkId=271779)。</span><span class="sxs-lookup"><span data-stu-id="888a6-141">For more information about audit logging, see [Auditing Reports](https://go.microsoft.com/fwlink/p/?LinkId=271779).</span></span>
  
### <a name="unified-messaging-reports"></a><span data-ttu-id="888a6-142">整合通訊報告</span><span class="sxs-lookup"><span data-stu-id="888a6-142">Unified Messaging reports</span></span>

<span data-ttu-id="888a6-143">You can use these reports to monitor and troubleshoot Unified Messaging (UM) in your Exchange Online organization.</span><span class="sxs-lookup"><span data-stu-id="888a6-143">You can use these reports to monitor and troubleshoot Unified Messaging (UM) in your Exchange Online organization.</span></span> <span data-ttu-id="888a6-144">For more information, see [Run Reports for Voice Mail Calls](https://go.microsoft.com/fwlink/p/?LinkId=287042).</span><span class="sxs-lookup"><span data-stu-id="888a6-144">For more information, see [Run Reports for Voice Mail Calls](https://go.microsoft.com/fwlink/p/?LinkId=287042).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="888a6-145">功能可用性</span><span class="sxs-lookup"><span data-stu-id="888a6-145">Feature availability</span></span>

<span data-ttu-id="888a6-146">若要查看不同方案、獨立選項和內部部署方案中的功能可用性，請參閱[Exchange Online 服務說明](exchange-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="888a6-146">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online service description](exchange-online-service-description.md).</span></span>
  

