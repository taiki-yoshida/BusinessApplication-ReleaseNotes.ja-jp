---
title: "キャンバス アプリによるエラーの捕捉、処理、レポートとデータベースへの Null 値の書き込み"
description: "アプリ開発者は発生したエラーをコントロールし、補足的なメリットとして Null 値を書き込めます。"
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
ms.sourcegitcommit: 62ff356275ffd55047573b9224fb7c94df8dd602
ms.openlocfilehash: 6b7018a8f71dfbdc937430575e6c561b0d1a4e05
ms.contentlocale: ja-jp
ms.lasthandoff: 08/15/2018

---
# <a name="catch-handle-and-report-errors-and-write-null-values-to-databases-with-canvas-apps"></a><span data-ttu-id="5c720-103">キャンバス アプリによるエラーの捕捉、処理、レポートとデータベースへの Null 値の書き込み</span><span class="sxs-lookup"><span data-stu-id="5c720-103">Catch, handle, and report errors, and write Null values to databases with canvas apps</span></span>

[!include[powerapps banner](../includes/powerapps.md)]




<span data-ttu-id="5c720-104">エラーは発生します。</span><span class="sxs-lookup"><span data-stu-id="5c720-104">Errors happen.</span></span>  <span data-ttu-id="5c720-105">キャンバス アプリはエラーが発生したときの既定の動作を提供しますが、これは希望するものとは異なる場合があります。</span><span class="sxs-lookup"><span data-stu-id="5c720-105">Canvas apps provide a default behavior when they do, but this may not always match what you want.</span></span>  <span data-ttu-id="5c720-106">この機能を使用すると、エラーの補足、問い合わせ、スロー、抑制、ログ記録、ユーザーに対するメッセージの送信を行えます。</span><span class="sxs-lookup"><span data-stu-id="5c720-106">With this feature, you can catch, interrogate, throw, suppress, log, and message errors to your users.</span></span>

<span data-ttu-id="5c720-107">以前は、エラーと Null 値を判別できず、データベースに Null 値をプッシュするのは問題でした。</span><span class="sxs-lookup"><span data-stu-id="5c720-107">Errors and Null values were previously indistinguishable, so pushing Null values to databases was a problem.</span></span>  <span data-ttu-id="5c720-108">Null は多くのデータベース システムでは正当な値です。</span><span class="sxs-lookup"><span data-stu-id="5c720-108">Null is a legitimate value in many database systems.</span></span>  <span data-ttu-id="5c720-109">キャンバス アプリではエラーが適切に分離されるため、すべてのデータベースに Null 値を書き込めます。</span><span class="sxs-lookup"><span data-stu-id="5c720-109">With errors properly separated out in canvas apps, you can write Null values to all databases.</span></span>

