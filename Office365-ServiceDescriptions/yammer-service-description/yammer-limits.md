---
title: Yammer 中的限制
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- yammer-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: ''
description: 深入瞭解 Microsoft 365 中 Yammer 的服務限制。
ms.openlocfilehash: 390bb642e45e2ac4868069698530d7c43a171762
ms.sourcegitcommit: c061620e1ccabec8ee97d49f25d575cde54fbc9b
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 07/30/2021
ms.locfileid: "53661643"
---
# <a name="limits-in-yammer"></a>Yammer 中的限制

深入瞭解 Microsoft 365 中 Yammer 的服務限制。

## <a name="network-limits"></a>網路限制

| 功能 | 詳細資料 |
|---------|---------|
| 原生模式 | 建議使用[原生模式](/yammer/configure-your-yammer-network/overview-native-mode)，以獲得長期的最佳支援。 Microsoft 365 Native 模式中 Yammer 網路與舊版 Yammer 網路具有不同的功能。 |
| 網路系統管理員的大量更新 | 非原生模式網路的2000使用者或更少的使用者可以大量更新至使用者。 |
| 家用網路 | 無法刪除及重新建立家用網路。 |

## <a name="file-limits"></a>檔限制

| 功能 | 詳細資料 |
|---------|---------|
| 檔案大小上限及儲存體 | 建議您先遷移至 Microsoft 365 Yammer 的原生模式，以確保所有檔案都儲存在 SharePoint 線上中。 <br/>針對 SharePoint 中儲存的 Yammer 檔案： <ul><li>單一檔案附件的大小上限為 15 gb (GB) 。</li><li>圖像沒有任何尺寸限制，但組織中的 SharePoint 大小上限設定。</li><li>任何檔案類型都可以新增，但預覽及編輯會限制在某些檔案類型。</li> </ul><br/>[SharePoint 限制](/office365/servicedescriptions/sharepoint-online-service-description/sharepoint-online-limits)適用于 Yammer 中 Microsoft 365[連接的團體](/yammer/manage-yammer-groups/yammer-and-office-365-groups)。 <br/>儲存在 Yammer 檔案存放區中的檔案： <br/><ul><li>單一檔案附件的大小上限為 5 gb (GB) Yammer Enterprise 網路和 100 mb () 基本網路。</li><li>最大尺寸為7680圖元寬和4320圖元高，而圖像大小上限為 10 mb (MB) 。</li></ul> <br/>如需影像使用的詳細資訊，包括封面相片的範本和維度，請參閱[Yammer 採用資源](https://adoption.microsoft.com/yammer/)。 |
| 每個文章的檔附件數目 | 每個貼上最多可以有100個檔案。 |
| 支援的影片格式 | 下列影片類型支援內聯播放： .wmv、.avi、.mpeg、3gp、flv、mov、.mp4、.mpg、ogm、mkv、ogv 及 ogg。 <br/>Yammer 會使用 Azure 媒體服務來顯示上傳 Yammer 中的影片。 |
| 內置影片播放 | Microsoft Stream、SharePoint Online、YouTube 及 Vimeo 都支援內聯播放。 |
| 來賓存取 | Microsoft 365完全來賓支援需要 Yammer 的原生模式。 <br/>舊版網路層級來賓可能會遇到檔存取問題。 |
| Graph 物件的連結預覽 (開啟)  | 無法公開解析的內部系統連結，或需要驗證，因為無法解壓縮中繼資料，所以不會顯示有效的預覽。 |

## <a name="yammer-live-event-limits"></a>Yammer 即時事件限制

| 功能 | 詳細資料 |
|---------|---------|
| 即時事件檢視器的數目 | 目前的限制為10000參與者。 如需較高大小的事件，請使用 [即時事件協助程式](https://resources.techcommunity.microsoft.com/live-events/assistance/)。 |
| 即時事件建立許可權 | 需要在資料流程中建立即時事件的許可權。 <br/>Yammer 中的 Community 管理員可以建立或排程即時事件。 |
| 來賓存取 | 您的規範網路成員可以在 Yammer 中建立或參加 live 事件。 |
| 隱藏字幕 | 隱藏字幕不適用於 Yammer 中的 live 事件。 未來的更新將新增對封閉式字幕的支援。 |
| 事件期間 | 4 小時 |
| 在 Microsoft 365 或 Office 365 組織中執行的並行即時事件 | 每個租使用者的50事件 |
| 簡報者的限制？ | 100簡報者 |

如需 Microsoft Teams 即時事件和會議的相關限制，請參閱[Teams live events](/microsoftteams/limits-specifications-teams#teams-live-events)。

## <a name="yammer-community-limits"></a>Yammer 社區限制

| 功能 | 詳細資料 |
|---------|---------|
| 群組中的成員數目 | 會根據群組是[連線至 Microsoft 365 群組](/yammer/manage-yammer-groups/yammer-and-office-365-groups)、[動態群組](/yammer/manage-yammer-groups/create-a-dynamic-group)，還是[全公司](/yammer/manage-yammer-groups/yammer-all-company-yammer-community)團體而有所不同。 <br/>動態群組成員資格限制：有500000位 |
| 您可以是成員的社區數目 | 7000 |
| 透過通訊錄匯入同時新增多個使用者的更新數目 | 200每個批次上傳的群組成員。 |
| 動態社區的限制 | 無限制 |
| 每個群組的系統管理員人數 | 在原生模式中，系統管理員可以設定最小值。 非原生模式網路每個群組的系統管理員數目限制為100。 |
| 網路系統管理員數目 | 根據原生模式設定而有所不同。 沒有網路系統管理員的限制。 |
| 連接的社區和 Azure AD 同步 | 使用超過100K 的群組成員資格時，可能會發生同步處理延遲。 |
| 所有公司中的成員 | 包含租使用者中的所有使用者。 |
| 官方社區數目 | 無限制 |
| 我的常用連絡人社區數目 | 10  |
| Community 名稱字元限制 | 取決於網路的命名慣例。 <br/>最多255個字元（包括任何前置詞）。 |
| Community 描述字元限制 | 150個字元 |
| Community 資訊長度 |  (最多 1 GB 的字元數上限)  |
| 固定資源的限制 | 無限制 |
| 相關社區的限制 | 一般的社區沒有限制，但最佳作法是3-5 相關社區。 <br/>所有公司都無法使用相關的社區。 |
| 私人團體的未決成員限制 | 無限制。 |
| 在原生模式中群組管理的限制 | 連接的群組應該使用專門用來更新 Microsoft 365 群組的工具進行管理，包括 Microsoft 365 系統管理入口網站、azure ad 入口網站和 azure ad PowerShell 模組。 |
| 電子郵件張貼 | 無限制 |

## <a name="yammer-messaging-limitations"></a>Yammer 郵件限制

| 功能 | 詳細資料 |
|---------|---------|
| 每封郵件的字元限制 | 10K 字元限制 |
| 刪除交談 | 刪除整個執行緒時，需要刪除所有的郵件。 刪除交談後，就會將第一個回復提升為執行緒 starter。 <br/>如果啟用 [私人內容模式](/yammer/manage-security-and-compliance/monitor-private-content) ，網路系統管理員可以從任何交談執行緒刪除郵件。 <br/>Community 系統管理員可以刪除其所管理之社區中的郵件。 <br/>原始作者只能刪除其自身的文章。 |
| 每個交談執行緒的郵件限制 | 交談最多可以有10000篇文章。 |
| 連結預覽 (開啟 Graph 中繼資料)  |<ul><li>僅能針對公開內容和某些支援的 Microsoft 365 資源產生連結內容預覽。</li><li>預覽版的產生取決於張貼時成功的中繼資料解壓縮是否會因所連結之網站的可用性而異。</li><li>不支援組織防火牆內部或要求驗證的系統連結。 </li><li>連結預覽中繼資料可能無法在網路中第一次使用連結之後更新。</li></ul> |
| 私人內容模式 | 已驗證系統管理員無法依預設存取私人內容。 必須啟用私人內容模式，才能存取私人郵件和私人團體。 |
| 嵌套的回復和舊版執行緒 | 舊版執行緒將允許建立新的嵌套回復。 舊的「回復到」郵件會維持在最上層的批註。 |

## <a name="external-network-limits"></a>外部網路限制

| 功能 | 詳細資料 |
|---------|---------|
| External Networks | 限制系統管理員可以建立的5個外部網路如果這5個外部網路只有一個成員 (，則其中一個成員是網路的建立者) 。 <br/> 如果外部網路中至少有一個其他使用者，則不會計入該限制。 |
| 檔案 | 檔案儲存在 Yammer 儲存區中，無法透過 SharePoint 存取。 |
| 社區 | 社區未連接至 Microsoft 365 群組。 |
| 原生模式 | [原生模式功能及限制](/yammer/configure-your-yammer-network/overview-native-mode) 不適用於外部網路。 |