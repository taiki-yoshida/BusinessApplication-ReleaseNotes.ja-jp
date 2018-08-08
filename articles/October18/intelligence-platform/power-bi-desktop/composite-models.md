---
title: "複合モデル"
description: "Power BI Desktop での DirectQuery とインポート データ ソースのマッシュアップのサポート"
author: MI77
manager: kimani
ms.date: 7/22/18
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: willthom
audience: developer, citizen developer, business analyst, IT pro
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 3256b373787e8c32a7ef80faad85e2ebd5f3634e
ms.contentlocale: ja-jp
ms.lasthandoff: 07/18/2018

---

# <a name="composite-models-public-preview"></a><span data-ttu-id="d6d82-103">複合モデル (パブリック プレビュー)</span><span class="sxs-lookup"><span data-stu-id="d6d82-103">Composite models (Public Preview)</span></span>

[!include[banner](../../../includes/banner.md)]

<span data-ttu-id="d6d82-104">複合モデルを使用すると、インポート ソースと表形式の直接クエリ ソースを混在させることができ、複数の表形式 DirectQuery ソースを使用できます。</span><span class="sxs-lookup"><span data-stu-id="d6d82-104">Composite models allow you to mix import and tabular direct query sources as well as have multiple tabular DirectQuery sources.</span></span> <span data-ttu-id="d6d82-105">これにより、インポートされたテーブルでエンタープライズ データ モデルを拡大できます。</span><span class="sxs-lookup"><span data-stu-id="d6d82-105">This lets you augment your enterprise data models with imported tables.</span></span> 

<span data-ttu-id="d6d82-106">モデラーは、DirectQuery データ ソースを基にして Power BI Desktop ファイルを作成した後、別のデータ ソースからインポートされたテーブルを追加することもできます。</span><span class="sxs-lookup"><span data-stu-id="d6d82-106">Modelers can create a Power BI Desktop file over a DirectQuery datasource, and then also add tables that are imported from another data source.</span></span> <span data-ttu-id="d6d82-107">この新しいモデル構造をサポートするため、デュアル モードの多対多リレーションシップとテーブルが導入されています。これは、ビジュアルに追加される他のテーブルに応じて、インポートまたは DirectQuery として動作できることを意味します。</span><span class="sxs-lookup"><span data-stu-id="d6d82-107">To support this new model structure, we also are introducing many-to-many relationships and tables that are in dual mode, which means they can act as import or DirectQuery, depending on what other tables you add to the visuals.</span></span> <span data-ttu-id="d6d82-108">Power BI は、インポートされたデータから、または基盤となるデータ ソースにクエリをプッシュすることにより、ユーザーの分析に対する回答をインテリジェントに提供します。</span><span class="sxs-lookup"><span data-stu-id="d6d82-108">Power BI will then intelligently serve answers to your analyses from either the imported data or by pushing a query to the underlying datasource.</span></span>

<!--
### Who uses this feature
This feature is intended for model developers. 
## Status
### Development status
In development
#### Target timeframe
October ‘18
-->

