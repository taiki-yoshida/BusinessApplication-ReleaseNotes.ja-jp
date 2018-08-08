---
title: "メジャーをクリック可能な URL として表示する"
description: "メジャーを使用して、レポートから他の Web アドレスに移動するためのハイパーリンクを定義できます。"
author: MI77
manager: kimani
ms.date: 6/22/18
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: willthom
audience: end user, developer, citizen developer, customizer, business analyst, IT pro
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 0ae8e309078c1aea0a4b24abe8eb4b253db34b29
ms.contentlocale: ja-jp
ms.lasthandoff: 07/18/2018

---

# <a name="show-measures-as-clickable-urls"></a><span data-ttu-id="0d322-103">メジャーをクリック可能な URL として表示する</span><span class="sxs-lookup"><span data-stu-id="0d322-103">Show measures as clickable URLS</span></span>

[!include[banner](../../../includes/banner.md)]

<span data-ttu-id="0d322-104">エンド ユーザーは、レポート間を移動したり、レポートから他のアプリケーションに移動しながらも、参照しているデータのコンテキストを維持できる、簡単な方法を求めています。</span><span class="sxs-lookup"><span data-stu-id="0d322-104">End users need an easy way to navigate between reports, or from reports to other applications, while still retaining the context of the data they were looking at.</span></span> <span data-ttu-id="0d322-105">メジャーを使用すれば、移動のための URL を生成したり、レポートやアプリケーション間を簡単に移動するためのハイパーリンクを表示することができます。</span><span class="sxs-lookup"><span data-stu-id="0d322-105">Measures can generate URLs to allow navigation, and can be shown as hyperlinks that make it easy to move between reports or applications.</span></span>

<span data-ttu-id="0d322-106">DAX メジャーを使用すれば、レポート内でのデータ選択に対応するフィルター付きで URL を返すことができます。</span><span class="sxs-lookup"><span data-stu-id="0d322-106">A DAX measure can return a URL, appended with filters corresponding to the data selections made in the report.</span></span> <span data-ttu-id="0d322-107">これは、テーブルやマトリックス ビジュアル内でハイパーリンクとして表示できるため、ユーザーの選択に基づいて動的に調整できます。</span><span class="sxs-lookup"><span data-stu-id="0d322-107">This can be shown in table and matrix visuals as a hyperlink, dynamically adjusted based on the selections that are made.</span></span> <span data-ttu-id="0d322-108">エンド ユーザーは、このリンクをクリックすることで、目的のレポートを新しいタブで開くことができます。</span><span class="sxs-lookup"><span data-stu-id="0d322-108">End users can click this link to open a new tab with the target report shown.</span></span>

<span data-ttu-id="0d322-109">次に示すのは DAX メジャーの例です。</span><span class="sxs-lookup"><span data-stu-id="0d322-109">The DAX measure might look something like this:</span></span>

`Link = “http://app.powerbi.com/Report/GUID/&filter=Table1/Category eq “ & SELECTEDVALUE(Products[Category])`

<!--
### Who uses this feature
This feature is intended for end users, developers, citizen developers, customizers, business analysts, and IT pros. No additional setup is required.
## Status
### Development status
In development
#### Target timeframe
October ‘18
-->

