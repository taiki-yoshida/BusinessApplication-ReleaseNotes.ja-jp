---
title: "集約"
description: "DirectQuery によってユーザーによる詳細レベルへのドリルダウンを可能にしながら、集約されたクエリのキャッシュをサポート"
author: MI77
manager: kimani
ms.date: 7/22/18
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: willthom
audience: developer, IT pro
ms.translationtype: HT
ms.sourcegitcommit: 7d6f339c1e92c937c47306db6da360eb8fdd5d77
ms.openlocfilehash: ec6fc313ef498181725c0e131d0e2ec1a91a90ce
ms.contentlocale: ja-jp
ms.lasthandoff: 08/16/2018

---

# <a name="aggregations-public-preview"></a><span data-ttu-id="0183f-103">集約 (パブリック プレビュー)</span><span class="sxs-lookup"><span data-stu-id="0183f-103">Aggregations (Public Preview)</span></span>

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]

<span data-ttu-id="0183f-104">大量のデータには、フィルターによる対話型分析と詳細レベル レポートのニーズのバランスを取る新しい情報格納方法が必要です。</span><span class="sxs-lookup"><span data-stu-id="0183f-104">Massive volumes of data require new ways of storing information to balance the needs of slice-and-dice interactive analysis with deep, detail-level reporting.</span></span> <span data-ttu-id="0183f-105">集約機能により、モデル開発者は対話型分析のために高レベルでキャッシュされた値を表示でき、ユーザーは基になるデータからクエリされた詳細データにドリルダウンすることができます。</span><span class="sxs-lookup"><span data-stu-id="0183f-105">Aggregations allow model developers to surface cached values at a high level for interactive analysis, but still let users drill down to detailed data that is queried from the underlying data.</span></span>

<span data-ttu-id="0183f-106">Spark クラスターや大規模データ ウェアハウスなど、大量のデータ ソースに対する DirectQuery モデルを作成できます。</span><span class="sxs-lookup"><span data-stu-id="0183f-106">You can create DirectQuery models over massive-scale data sources such as Spark clusters, or massive data warehouses.</span></span> <span data-ttu-id="0183f-107">対話型分析の場合、これらのデータセットに対してクエリを直接実行するのは実際的でありません。</span><span class="sxs-lookup"><span data-stu-id="0183f-107">For interactive analysis, running queries directly against these datasets is impractical.</span></span> <span data-ttu-id="0183f-108">しかし、数百テラバイトもの大きさになる可能性があるデータセットでは、すべてのデータをメモリ内にキャッシュすることはできません。</span><span class="sxs-lookup"><span data-stu-id="0183f-108">But for datasets that could be as large as hundreds of terabytes, the data cannot all be cached in memory.</span></span> <span data-ttu-id="0183f-109">集約を使うと、集約データだけをメモリにキャッシュしてすばやくアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="0183f-109">Aggregations lets you cache just aggregate data into memory for fast access.</span></span> <span data-ttu-id="0183f-110">集約テーブルとしてデータ モデル内にテーブルを定義し、詳細レベルでテーブルにリンクします。</span><span class="sxs-lookup"><span data-stu-id="0183f-110">You define tables in your data model as an aggregate table, linked to tables at the detail level.</span></span> 

<span data-ttu-id="0183f-111">詳細テーブルは DirectQuery モードのままですが、集約はデュアル モードとして定義されるので、データは集約レベルでメモリにもキャッシュされます。</span><span class="sxs-lookup"><span data-stu-id="0183f-111">The detail tables stay in DirectQuery mode but the aggregates are defined as being in dual mode so the data is also cached in memory at the aggregate level.</span></span> <span data-ttu-id="0183f-112">ユーザーがメモリ内キャッシュから応答できるクエリを実行したりビジュアルを作成したりした場合、結果はメモリから取得されます。</span><span class="sxs-lookup"><span data-stu-id="0183f-112">If users run queries or create visuals that can be answered from the in-memory cache, the results are retrieved from there.</span></span> <span data-ttu-id="0183f-113">一方、クエリで詳細データが必要な場合は、基になる DirectQuery ソースに動的に渡されます。</span><span class="sxs-lookup"><span data-stu-id="0183f-113">But if the query requires the detail data, it’s pushed down to the underlying DirectQuery source dynamically.</span></span> <span data-ttu-id="0183f-114">エンド ユーザーが Power BI レポートのエクスペリエンスで違いに気付くことはありません。</span><span class="sxs-lookup"><span data-stu-id="0183f-114">The end user doesn’t see any difference in experience in their Power BI report.</span></span>

<!--
### Who uses this feature
This feature is intended for advanced modelers. It enables them to create data models with aggregate tables linked together to make sure that their end-user reports are designed to encourage filtering of data before queries are served from the DirectQuery source. 
## Status
### Development status
In development
#### Target timeframe
October ‘18
-->

