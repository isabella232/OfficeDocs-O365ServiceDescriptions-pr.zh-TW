---
title: 搜尋
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- sharepoint-online-search-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: cb36484c-0e8f-480e-be88-5daa8bf2d47d
description: SharePoint Online 是 web 式工具和技術，可協助您的組織儲存、 共用及管理數位資訊的集合。 建置於 Microsoft SharePoint Server 2013 的主控服務，在執行專案、將資料與文件儲存於中心位置，以及和他人分享資訊等方面，都相當理想。 下列的搜尋功能協助人們找到他們工作所需的資訊。 搜尋包含相關性、精簡搜尋和人員搜尋等功能。
ms.openlocfilehash: 5e91de48b374109f570168a2c85ae3c1a606ea5f
ms.sourcegitcommit: 2b9f68f7731dfd6f9d3f33e31e6303e81985ebb2
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 11/26/2019
ms.locfileid: "39263317"
---
# <a name="search"></a><span data-ttu-id="b26e5-106">搜尋</span><span class="sxs-lookup"><span data-stu-id="b26e5-106">Search</span></span>

<span data-ttu-id="b26e5-107">SharePoint Online 是 web 式工具和技術，可協助您的組織儲存、 共用及管理數位資訊的集合。</span><span class="sxs-lookup"><span data-stu-id="b26e5-107">SharePoint Online is a collection of web-based tools and technologies that help your organization store, share, and manage digital information.</span></span> <span data-ttu-id="b26e5-108">建置於 Microsoft SharePoint Server 2013 的主控服務，在執行專案、將資料與文件儲存於中心位置，以及和他人分享資訊等方面，都相當理想。</span><span class="sxs-lookup"><span data-stu-id="b26e5-108">Built on Microsoft SharePoint Server 2013, this hosted service is ideal for working on projects, storing data and documents in a central location, and sharing information with others.</span></span> <span data-ttu-id="b26e5-109">下列的搜尋功能協助人們找到他們工作所需的資訊。</span><span class="sxs-lookup"><span data-stu-id="b26e5-109">The following Search features help people find the information that they need to do their jobs.</span></span> <span data-ttu-id="b26e5-110">搜尋包含相關性、精簡搜尋和人員搜尋等功能。</span><span class="sxs-lookup"><span data-stu-id="b26e5-110">Search is a combination of relevance, refinement, and people.</span></span>
  
## <a name="continuous-crawls"></a><span data-ttu-id="b26e5-111">連續編目</span><span class="sxs-lookup"><span data-stu-id="b26e5-111">Continuous crawls</span></span>

<span data-ttu-id="b26e5-p103">連續編目會頻繁地編目 SharePoint 網站中的內容，協助保持最新的搜尋結果。SharePoint Online 中已啟用連續編目，編目頻率由 Microsoft 管理。在 SharePoint Server 2013 中，系統管理員可以啟用連續編目，並且管理連續編目頻率。深入了解 [SharePoint Server 2013 的預設編目檔案副檔名及剖析檔案類型](https://docs.microsoft.com/sharepoint/technical-reference/default-crawled-file-name-extensions-and-parsed-file-types)。深入了解[管理連續編目](https://docs.microsoft.com/SharePoint/search/manage-continuous-crawls)。</span><span class="sxs-lookup"><span data-stu-id="b26e5-p103">Continuous crawls help keep search results fresh by frequently crawling content in SharePoint sites. Continuous crawls are enabled in SharePoint Online, with crawl frequencies managed by Microsoft. In SharePoint Server 2013, administrators can enable continuous crawls and manage continuous crawl frequencies. Learn more about [default crawled file name extensions and parsed file types in SharePoint](https://docs.microsoft.com/sharepoint/technical-reference/default-crawled-file-name-extensions-and-parsed-file-types). Learn more about [managing continuous crawls](https://docs.microsoft.com/SharePoint/search/manage-continuous-crawls).</span></span>
  
## <a name="deep-links"></a><span data-ttu-id="b26e5-117">Deep links</span><span class="sxs-lookup"><span data-stu-id="b26e5-117">Deep links</span></span>

<span data-ttu-id="b26e5-p104">搜尋系統會自動建立連結，以直接連至常被造訪之主要網頁上的子區段。這些連結被稱為「深層連結」。進一步了解 [SharePoint 搜尋系統](https://docs.microsoft.com/sharepoint/dev/general-development/search-in-sharepoint)。</span><span class="sxs-lookup"><span data-stu-id="b26e5-p104">The search system automatically creates links directly to sub-sections of a main page that is frequently visited. These links are called "deep links". Learn more about the [SharePoint search system](https://docs.microsoft.com/sharepoint/dev/general-development/search-in-sharepoint).</span></span>
  
## <a name="event-based-relevancy"></a><span data-ttu-id="b26e5-121">Event-based relevancy</span><span class="sxs-lookup"><span data-stu-id="b26e5-121">Event-based relevancy</span></span>

<span data-ttu-id="b26e5-122">搜尋系統會由內容連接方式、 項目會出現在搜尋結果的頻率和哪些搜尋結果人選取部分決定搜尋結果的相關性。</span><span class="sxs-lookup"><span data-stu-id="b26e5-122">The search system determines the relevance of search results in part by how content is connected, how often an item appears in search results, and which search results people select.</span></span> <span data-ttu-id="b26e5-123">分析元件追蹤並分析此資訊，並用此資訊持續改善其關聯性。</span><span class="sxs-lookup"><span data-stu-id="b26e5-123">The analytics component tracks and analyzes this information and uses it to continuously improve relevance.</span></span> <span data-ttu-id="b26e5-124">深入了解[分析過程](https://docs.microsoft.com/SharePoint/search/overview-of-analytics-processing)。</span><span class="sxs-lookup"><span data-stu-id="b26e5-124">Learn more about [analytics processing](https://docs.microsoft.com/SharePoint/search/overview-of-analytics-processing).</span></span>
  
## <a name="expertise-search"></a><span data-ttu-id="b26e5-125">專業知識搜尋</span><span class="sxs-lookup"><span data-stu-id="b26e5-125">Expertise search</span></span>

<span data-ttu-id="b26e5-p106">在 SharePoint 中利用垂直式 [人員搜尋]，可以更容易尋找到擁有特定技能或專業知識的人才。搜尋結果是依據中繼資料使用者在自己的網站中所輸入與其相關的資訊，和他們自己建立的資訊內容而決定的。進一步了解[變更搜尋類別設定](https://docs.microsoft.com/sharepoint/search/configure-properties-of-the-search-navigation-web-part)。</span><span class="sxs-lookup"><span data-stu-id="b26e5-p106">In SharePoint, it is easier to find people with specific skills or expertise in the People Search vertical. The search results are based on information such as the metadata users have entered about themselves on their personal sites, and information from the content that they have created. Learn more about [changing search vertical settings](https://docs.microsoft.com/sharepoint/search/configure-properties-of-the-search-navigation-web-part).</span></span>
  
## <a name="graphical-refiners"></a><span data-ttu-id="b26e5-129">Graphical refiners</span><span class="sxs-lookup"><span data-stu-id="b26e5-129">Graphical refiners</span></span>

<span data-ttu-id="b26e5-130">新的圖形精簡器可提供一種更具視覺效果的方式來篩選搜尋結果。</span><span class="sxs-lookup"><span data-stu-id="b26e5-130">The new graphical refiners provide a more visual way of filtering search results.</span></span> <span data-ttu-id="b26e5-131">深入了解[設定精簡搜尋網頁組件](https://support.office.com/article/About-configuring-the-Refinement-Web-Part-7cef67e8-b992-4659-b21a-ba534eea102e)。</span><span class="sxs-lookup"><span data-stu-id="b26e5-131">Learn more about [configuring the Refinement Web Part](https://support.office.com/article/About-configuring-the-Refinement-Web-Part-7cef67e8-b992-4659-b21a-ba534eea102e).</span></span>
  
## <a name="hybrid-search"></a><span data-ttu-id="b26e5-132">混合式搜尋</span><span class="sxs-lookup"><span data-stu-id="b26e5-132">Hybrid search</span></span>

<span data-ttu-id="b26e5-p108">在 SharePoint 的混合部署中，搜尋結果內容可來自內部部署網站中的 SharePoint Online 和 SharePoint Server 2013。若要進一步了解混合 SharePoint 環境，請參閱 [SharePoint Server 2013 混合模式](https://docs.microsoft.com/SharePoint/hybrid/hybrid)。</span><span class="sxs-lookup"><span data-stu-id="b26e5-p108">In a hybrid deployment of SharePoint, search result content can come from both SharePoint Online and SharePoint Server 2013 on-premises sites. To learn more about a hybrid SharePoint environment, see [Hybrid for SharePoint Server 2013](https://docs.microsoft.com/SharePoint/hybrid/hybrid).</span></span>
  
## <a name="manage-search-schema"></a><span data-ttu-id="b26e5-135">管理搜尋結構描述</span><span class="sxs-lookup"><span data-stu-id="b26e5-135">Manage search schema</span></span>

<span data-ttu-id="b26e5-p109">當使用者在您的 SharePoint 網站上搜尋內容時，您搜尋索引中的項目會決定他們能夠找到的結果。搜尋索引包含網站上所有文件和頁面的資訊，該索引是藉由編目 SharePoint 網站上的內容而建立的。搜尋結構描述可協助編目程式決定要揀選哪些內容和中繼資料，以及如何編製索引。您可以藉由變更搜尋結構描述，為使用者建立自訂的搜尋體驗。深入了解[在 SharePoint Online 中管理搜尋結構描述](https://docs.microsoft.com/sharepoint/manage-search-schema)。</span><span class="sxs-lookup"><span data-stu-id="b26e5-p109">When people search for content on your SharePoint sites, it's what's in your search index that determines what they'll find. The search index contains information from all documents and pages on your site and is built by crawling the content on your SharePoint site. The search schema helps the crawler decide what content and metadata to pick up and how to index it. By changing the search schema, you can create a customized search experience for your users. Learn more about [managing search schema in SharePoint Online](https://docs.microsoft.com/sharepoint/manage-search-schema).</span></span>
  
## <a name="on-hover-preview"></a><span data-ttu-id="b26e5-141">游標暫留預覽</span><span class="sxs-lookup"><span data-stu-id="b26e5-141">On-hover preview</span></span>

<span data-ttu-id="b26e5-p110">使用者可以將指標停留在搜尋結果上，並預覽搜尋結果右側暫留面板上的文件或網站內容，並與其互動。預覽顯示出豐富形中繼資料，並且有連至文件或網站主要區塊的深層連結。進一步了解[搜尋祕訣](https://support.office.com/article/Not-getting-the-search-results-you-re-looking-for-in-SharePoint-D80687F7-1010-4E6D-ADD9-584B423289D9)。</span><span class="sxs-lookup"><span data-stu-id="b26e5-p110">Users can rest the pointer over a search result to preview and interact with the document or site content in the hover panel to the right of the result. The preview shows rich metadata and has deep links to the main sections of the document or site. Learn more [tips for searching](https://support.office.com/article/Not-getting-the-search-results-you-re-looking-for-in-SharePoint-D80687F7-1010-4E6D-ADD9-584B423289D9).</span></span>
  
## <a name="phonetic-name-matching"></a><span data-ttu-id="b26e5-145">Phonetic name matching</span><span class="sxs-lookup"><span data-stu-id="b26e5-145">Phonetic name matching</span></span>

<span data-ttu-id="b26e5-146">改良的姓名發音匹配功能找到搜尋結果的類似發音名稱 （為它 John 或 Jon？）。</span><span class="sxs-lookup"><span data-stu-id="b26e5-146">Improved phonetic name matching finds search results for similar sounding names (is it John or Jon?).</span></span> <span data-ttu-id="b26e5-147">進一步了解[管理結果來源](https://docs.microsoft.com/sharepoint/manage-result-sources)。</span><span class="sxs-lookup"><span data-stu-id="b26e5-147">Learn more about [managing result sources](https://docs.microsoft.com/sharepoint/manage-result-sources).</span></span>
  
## <a name="query-rulesadd-promoted-results"></a><span data-ttu-id="b26e5-148">查詢規則增加升級的查詢結果</span><span class="sxs-lookup"><span data-stu-id="b26e5-148">Query rules—add promoted results</span></span>

<span data-ttu-id="b26e5-p112">在查詢規則中指定條件與相關的指令。當查詢符合查詢規則中的條件時，搜尋系統就會執行規則中所指定的動作。「新增升級的查詢結果」動作讓您可以升級個別查詢結果，並將其擺放在搜尋結果的前端。進一步了解[管理查詢規則](https://docs.microsoft.com/SharePoint/search/manage-query-rules)。</span><span class="sxs-lookup"><span data-stu-id="b26e5-p112">In a query rule, specify conditions and correlated actions. When a query meets the conditions in a query rule, the search system performs the actions specified in the rule. The "Add promoted results" action lets you promote individual results so that they appear at the top of search results. Learn more about [managing query rules](https://docs.microsoft.com/SharePoint/search/manage-query-rules).</span></span>
  
## <a name="query-rulesadvanced-actions"></a><span data-ttu-id="b26e5-153">Query rules—advanced actions</span><span class="sxs-lookup"><span data-stu-id="b26e5-153">Query rules—advanced actions</span></span>

<span data-ttu-id="b26e5-p113">在查詢規則中，您可以指定條件和相關動作。[新增結果區塊] 動作可讓您以群組形式顯示搜尋結果子集。[變更查詢來變更排名結果] 動作可讓您變更所傳回搜尋結果的排名。進一步了解[管理查詢規則](https://docs.microsoft.com/SharePoint/search/manage-query-rules)。</span><span class="sxs-lookup"><span data-stu-id="b26e5-p113">In a query rule, you can specify conditions and correlated actions. The "Add result blocks" action lets you display a subset of the search results as a group. The "Change ranked results by changing the query" action lets you change the ranking of the returned search results. Learn more about [managing query rules](https://docs.microsoft.com/SharePoint/search/manage-query-rules).</span></span>
  
## <a name="query-spelling-correction"></a><span data-ttu-id="b26e5-158">Query spelling correction</span><span class="sxs-lookup"><span data-stu-id="b26e5-158">Query spelling correction</span></span>

<span data-ttu-id="b26e5-p114">編輯排除與包含清單，以決定哪些查詢是搜尋結果網頁應該顯示其替代的查詢拼字建議。這個功能通常都稱為「您的意思是不是？」。深入了解[查詢拼字校正](https://docs.microsoft.com/sharepoint/search/manage-query-spelling-correction)。</span><span class="sxs-lookup"><span data-stu-id="b26e5-p114">Edit exclusions and inclusions lists to decide which queries the search results page should display alternative query spellings for. This feature is often called "Did you mean?". Learn more about [query spelling correction](https://docs.microsoft.com/sharepoint/search/manage-query-spelling-correction).</span></span>
  
## <a name="query-suggestions"></a><span data-ttu-id="b26e5-162">查詢建議</span><span class="sxs-lookup"><span data-stu-id="b26e5-162">Query suggestions</span></span>

<span data-ttu-id="b26e5-p115">查詢建議是使用者的已經搜尋的建議片語。這些建議會在使用者輸入查詢時，於搜尋方塊下方的清單中出現。查詢建議是由系統自動產生的，也可以將片語當成「務必」建議或「絕不」建議的片語而新增至系統中。進一步了解[管理查詢建議](https://docs.microsoft.com/sharepoint/search/manage-query-suggestions)。</span><span class="sxs-lookup"><span data-stu-id="b26e5-p115">Query suggestions are suggested phrases that users have already searched for. The suggestions appear in a list below the Search Box as a user types a query. Query suggestions are generated automatically, and phrases can be added to the system as "always" or "never" suggest. Learn more about [managing query suggestions](https://docs.microsoft.com/sharepoint/search/manage-query-suggestions).</span></span>
  
## <a name="ranking-models"></a><span data-ttu-id="b26e5-167">排名模型</span><span class="sxs-lookup"><span data-stu-id="b26e5-167">Ranking models</span></span>

<span data-ttu-id="b26e5-p116">SharePoint 使用排名模型，指派值給搜尋結果，讓最相關的項目可以優先顯示。排名模型是排名因素的集合，這些因素會計算特定項目的排名分數。SharePoint Online 和 SharePoint Server 2013 都包含數個排名模型，提供有效的排名，不需要進一步自訂。但是，如果您需要為使用者提供更相關的搜尋結果，可以自訂排名模型。排名模型調整應用程式可以讓 SharePoint Online 客戶建立自訂排名模型。該應用程式提供使用者介面，可以複製現有的排名模型、評判查詢集的結果，以及新增或移除排名功能與調整這些功能的加權，進行「調整」。深入了解[搜尋結果排名](https://docs.microsoft.com/sharepoint/search/overview-of-search-result-ranking)。</span><span class="sxs-lookup"><span data-stu-id="b26e5-p116">SharePoint uses ranking models to assign a value to search results so that the most relevant items appear first. A ranking model is a set of ranking factors that calculate the rank score of a particular item. Both SharePoint Online and SharePoint Server 2013 include several ranking models that provide effective rankings without any further customization. However, you can customize your ranking models if you need to make search results even more relevant to your end users. The Ranking Model Tuning App allows SharePoint Online customers to create a custom ranking model. The app provides a user interface to copy an existing ranking model, judge the results for a set of queries, and "tune" it by adding or removing rank features and adjusting the weight of those features. Learn more about [search result ranking](https://docs.microsoft.com/sharepoint/search/overview-of-search-result-ranking).</span></span>
  
## <a name="refiners"></a><span data-ttu-id="b26e5-175">精簡器</span><span class="sxs-lookup"><span data-stu-id="b26e5-175">Refiners</span></span>

<span data-ttu-id="b26e5-p117">精簡器將 SharePoint Server 搜尋結果中前幾份文件分類成幾個小組，讓使用者可以過濾搜尋結果。深入了解[設定精簡搜尋網頁組件](https://support.office.com/article/About-configuring-the-Refinement-Web-Part-7cef67e8-b992-4659-b21a-ba534eea102e)。</span><span class="sxs-lookup"><span data-stu-id="b26e5-p117">Refiners categorize the top documents in SharePoint Server search results into groups that let users filter the search results. Learn more about [configuring the Refinement Web Part](https://support.office.com/article/About-configuring-the-Refinement-Web-Part-7cef67e8-b992-4659-b21a-ba534eea102e).</span></span>
  
## <a name="restful-query-apiquery-om"></a><span data-ttu-id="b26e5-178">RESTful Query API/Query OM</span><span class="sxs-lookup"><span data-stu-id="b26e5-178">RESTful Query API/Query OM</span></span>

<span data-ttu-id="b26e5-179">開發人員可以撰寫 .NET 程式碼，用以存取公用搜尋物件模式。</span><span class="sxs-lookup"><span data-stu-id="b26e5-179">Developers can create .NET code to access the public search object model.</span></span> <span data-ttu-id="b26e5-180">這包括搜尋除了提交搜尋查詢的管理作業。</span><span class="sxs-lookup"><span data-stu-id="b26e5-180">This includes searching administration operations in addition to submitting search queries.</span></span> <span data-ttu-id="b26e5-181">為了與服務端的物件模式互動，.NET 程式碼必須於伺服器陣列中的網頁伺服器中執行。</span><span class="sxs-lookup"><span data-stu-id="b26e5-181">To interact with the service side object model, the .NET code must run on a web server in the farm.</span></span> <span data-ttu-id="b26e5-182">可以使用用戶端端物件模型 (CSOM)，從遠端電腦存取物件模型的子集合。</span><span class="sxs-lookup"><span data-stu-id="b26e5-182">A sub-set of the object model can be accessed from a remote computer by using the Client Side Object Model (CSOM).</span></span> <span data-ttu-id="b26e5-183">可以使用 rest web 服務或 oData 存取功能的用戶端端物件模型 (CSOM)。</span><span class="sxs-lookup"><span data-stu-id="b26e5-183">Features of the Client Side Object Model (CSOM) can be accessed by using a REST-based web service or oData.</span></span> <span data-ttu-id="b26e5-184">這可讓開發人員利用常用的網站開發工具將查詢提交至 SharePoint Server 2013 伺服器陣列的查詢。</span><span class="sxs-lookup"><span data-stu-id="b26e5-184">This allows developers to submit queries to the SharePoint Server 2013 farm using popular web development tools.</span></span>

## <a name="search-results-sorting"></a><span data-ttu-id="b26e5-185">Search results sorting</span><span class="sxs-lookup"><span data-stu-id="b26e5-185">Search results sorting</span></span>

<span data-ttu-id="b26e5-186">使用者可以選擇不同的準則來排序搜尋結果&mdash;，例如相關性、 新鮮度，並且關係距離 （人名）。</span><span class="sxs-lookup"><span data-stu-id="b26e5-186">Users can choose to sort search results by different criteria&mdash;for example, relevance, freshness, and social distance (people names).</span></span> <span data-ttu-id="b26e5-187">進一步了解[搜尋結果排序](https://support.office.com/article/change-settings-for-the-search-results-web-part-40ff85b3-bc5e-4230-b1dd-f088188e487e)。</span><span class="sxs-lookup"><span data-stu-id="b26e5-187">Learn more about [search results sorting](https://support.office.com/article/change-settings-for-the-search-results-web-part-40ff85b3-bc5e-4230-b1dd-f088188e487e).</span></span>
  
## <a name="this-list-searches"></a><span data-ttu-id="b26e5-188">「 此清單 」 搜尋</span><span class="sxs-lookup"><span data-stu-id="b26e5-188">"This list" searches</span></span>

<span data-ttu-id="b26e5-p120">在 SharePoint Online 和 SharePoint Server 2013 中，搜尋可以限制為執行搜尋所在的清單或文件庫。在 SharePoint Foundation 2013 中，搜尋會從執行搜尋所在網站或其下的清單或文件庫傳回結果。</span><span class="sxs-lookup"><span data-stu-id="b26e5-p120">In SharePoint Online and SharePoint Server 2013, a search can be limited to the list or library where the search is performed. In SharePoint Foundation 2013, a search will return results from all lists and libraries that exist at or below the site where the search is performed.</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="b26e5-191">功能可用性</span><span class="sxs-lookup"><span data-stu-id="b26e5-191">Feature availability</span></span>

<span data-ttu-id="b26e5-192">若要檢視跨 Office 365 計劃、 獨立選項和內部部署解決方案的功能可用性，請參閱[SharePoint Online 服務說明](sharepoint-online-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="b26e5-192">To view feature availability across Office 365 plans, standalone options, and on-premises solutions, see [SharePoint Online service description](sharepoint-online-service-description.md).</span></span>
  

