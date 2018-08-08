---
title: "Common Data Service または SharePoint を使用しているときにキャンバス アプリでわかりやすい表示名を使用する"
description: "暗号的な開発者名を使用する必要がなくなります。 アプリ開発者は、開発者ポータルやアプリの UI で表示名を使用できるようになりました。"
author: gregli
manager: AnnBe
ms.date: 7/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: gregli
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: f24043336465f7f6f344cad0b70d846f7e52f11a
ms.contentlocale: ja-jp
ms.lasthandoff: 07/18/2018

---
# <a name="work-with-friendly-display-names-in-canvas-apps-when-using-common-data-service-or-sharepoint"></a><span data-ttu-id="a55b2-104">Common Data Service または SharePoint を使用している場合にキャンバス アプリでわかりやすい表示名を使用する</span><span class="sxs-lookup"><span data-stu-id="a55b2-104">Work with friendly display names in canvas apps when using Common Data Service or SharePoint</span></span>


[!include[banner](../../includes/banner.md)]

<span data-ttu-id="a55b2-105">Common Data Service と SharePoint では、すべてのテーブルとフィールドに対して 2 つの名前が保持されます。</span><span class="sxs-lookup"><span data-stu-id="a55b2-105">Both the Common Data Service and SharePoint maintain two names for every table and field.</span></span>  <span data-ttu-id="a55b2-106">1 つは、開発者向けの名前です。これはやや暗号的な名前で、スペースを使用せず、大文字/小文字の使用も不規則です。アンダースコアを使用して、一意の名前にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="a55b2-106">First, there's a developer-friendly name, which is somewhat cryptic, with no spaces, odd capitalization, underscores, and a requirement to be unique.</span></span> <span data-ttu-id="a55b2-107">もう 1 つは、エンドユーザーに表示されるユーザー フレンドリ名です。スペースを使用でき、大文字/小文字も標準の方法で使用されます。この名前はアプリの UI に表示されます。</span><span class="sxs-lookup"><span data-stu-id="a55b2-107">Then there's a user-friendly name, meant for end users to see, with spaces and standard capitalization, displayed in the app's UI.</span></span>  

<span data-ttu-id="a55b2-108">これまで、PowerApps では開発者名しかサポートされていませんでした。</span><span class="sxs-lookup"><span data-stu-id="a55b2-108">To date, PowerApps has only supported the developer names.</span></span> <span data-ttu-id="a55b2-109">今回導入された機能により、表示名を開発者名の代わりに使用できるようになったので、式の読み書きがしやすくなり、わかりやすくなりました。</span><span class="sxs-lookup"><span data-stu-id="a55b2-109">With this feature, authors can now work with display names instead, making reading and writing of formulas easier and clearer.</span></span>


