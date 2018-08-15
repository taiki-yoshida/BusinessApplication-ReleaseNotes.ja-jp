---
title: "強化され、より統合されたコネクターと開発者エコシステム"
description: "強化され、より統合されたコネクターと開発者エコシステム"
author: shellyhaverkamp
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: 64dd4753-dced-47af-8087-0a75f48a4a2d
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: tpalmer
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 62ff356275ffd55047573b9224fb7c94df8dd602
ms.openlocfilehash: 1a28b60ca0960084042d198483f7b2789415593d
ms.contentlocale: ja-jp
ms.lasthandoff: 08/15/2018

---
#  <a name="richer-and-more-unified-connector-and-developer-ecosystem"></a><span data-ttu-id="50e6e-103">強化され、より統合されたコネクターと開発者エコシステム</span><span class="sxs-lookup"><span data-stu-id="50e6e-103">Richer and more unified connector and developer ecosystem</span></span>

[!include[data-integration-platform banner](../includes/data-integration-platform.md)]




<span data-ttu-id="50e6e-104">データ統合とそれがサポートする製品スイートの重要な要素の一つに、外部データ ソースに対する接続性があります。</span><span class="sxs-lookup"><span data-stu-id="50e6e-104">A critical part of Data Integration and the suite of products it supports is connectivity to external data sources.</span></span> <span data-ttu-id="50e6e-105">Microsoft では、エンタープライズ レベルのデータ ソースのセットに引き続き投資していますが、多くのユーザーがそのセット以外にも依存するようになっているデータベースやサービスが増えています。</span><span class="sxs-lookup"><span data-stu-id="50e6e-105">While we continue to invest in a set of enterprise grade data sources, there are a growing number of databases and services many users come to depend on outside of that set.</span></span> <span data-ttu-id="50e6e-106">必要なデータにユーザーが接続できるよう、プラットフォーム全体の拡張性ポイントに引き続き投資しています。</span><span class="sxs-lookup"><span data-stu-id="50e6e-106">To ensure our users can connect to the data they need, we continue to invest in our extensibility points throughout the platform.</span></span>

## <a name="improved-development-for-connectors-across-the-platform"></a><span data-ttu-id="50e6e-107">プラットフォーム全体のコネクタに対する開発の向上</span><span class="sxs-lookup"><span data-stu-id="50e6e-107">Improved development for connectors across the platform</span></span>

<span data-ttu-id="50e6e-108">プラットフォーム用にコネクタを作成する開発者や ISV は、PowerApps、Microsoft Flow、および Logic Apps のアクションとトリガーでコネクタを作成するか、Power BI 用のリッチ データ コネクタを作成することができます。</span><span class="sxs-lookup"><span data-stu-id="50e6e-108">Developers and ISVs looking to build connectors for our platform can choose to build connectors with actions and triggers for PowerApps, Microsoft Flow, and Logic Apps, or build rich data connectors for Power BI.</span></span> <span data-ttu-id="50e6e-109">また、開発者および ISV はデータ統合を介してアプリケーション向け Common Data Service および Power BI データフローのコネクタを作成できます。</span><span class="sxs-lookup"><span data-stu-id="50e6e-109">Developers and ISVs can additionally build connectors for the Common Data Service for Applications and Power BI dataflows through Data Integration.</span></span> <span data-ttu-id="50e6e-110">フル プラットフォームのサポートに関心がある ISV は今それを行えます。</span><span class="sxs-lookup"><span data-stu-id="50e6e-110">ISVs interested in supporting our full platform can do so now.</span></span>

<span data-ttu-id="50e6e-111">このリリースには、プラットフォーム全体でコネクタの作成、テスト、リリースを行えるよう、ISV および開発者向けに多くの機能強化が含まれています。</span><span class="sxs-lookup"><span data-stu-id="50e6e-111">This release includes a number of improvements for ISVs and developers to build, test, and release their connectors across our entire platform.</span></span>  <span data-ttu-id="50e6e-112">Power Query SDK の一般提供に伴い、開発者は、Power BI、アプリケーション向け Common Data Service、および Power BI データフローのリッチ コネクタを作成するために、成熟したプラットフォームにアクセスできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="50e6e-112">With the general availability of the Power Query SDK, developers now have access to a mature platform for building rich connectors for Power BI, Common Data Service for Applications, and Power BI dataflows.</span></span>  <span data-ttu-id="50e6e-113">開発者にはガイドとなる豊富なドキュメントおよびサンプルが準備されており、SDK の新しい機能を使用してカスタム コネクタの署名、バージョン管理、検証を行うことができます。</span><span class="sxs-lookup"><span data-stu-id="50e6e-113">With a rich set of documentation and samples to guide developers, new features in the SDK allow for signing, versioning, and validation of custom connectors.</span></span>  <span data-ttu-id="50e6e-114">[ここから Power Query SDK](https://aka.ms/dataconnectors) にアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="50e6e-114">Access the [Power Query SDK here](https://aka.ms/dataconnectors).</span></span>

<span data-ttu-id="50e6e-115">プレビュー機能の一つとして、フル プラットフォームで機能するシングル コネクタがあります。最初から開発することも、既存の OpenAPI 定義から作成することもできます。</span><span class="sxs-lookup"><span data-stu-id="50e6e-115">One of the features in preview is a single connector that works across the full platform, and can be developed from scratch or created from an existing OpenAPI definition.</span></span>  <span data-ttu-id="50e6e-116">そのようなコネクタの作成に関心のある開発者は、Microsoft PowerApps、Microsoft Flow、または Logic Apps にあるカスタム コネクタ ポータルで開始するか、利用可能になった Power Query Data Connector SDK で開始することができます。</span><span class="sxs-lookup"><span data-stu-id="50e6e-116">Developers interested in building such a connector can get started with the custom connector portal in Microsoft PowerApps, Microsoft Flow or Logic Apps, or with the Power Query Data Connector SDK that is now available.</span></span> <span data-ttu-id="50e6e-117">開発者は、フル プラットフォームで正しいコンポーネントを生成することができます。</span><span class="sxs-lookup"><span data-stu-id="50e6e-117">It allows developers to generate the correct artifacts for the full platform.</span></span>
<span data-ttu-id="50e6e-118">Microsoft Flow と PowerApps での現在のインライン テスト エクスペリエンスに加えて、Power BI Desktop またはオンプレミス データ ゲートウェイで使用するためにコネクタをダウンロードして、それらの製品で完全なエンド ツー エンドのテストを行うこともできます。</span><span class="sxs-lookup"><span data-stu-id="50e6e-118">In addition to the current inline testing experiences in Microsoft Flow and PowerApps, the connector can be downloaded to use with the Power BI Desktop or On-premises Data Gateway for a full end-to-end testing in those products.</span></span>

<span data-ttu-id="50e6e-119">![](media/3-richer-more-unified-connector-developer-ecosystem-2.png "ナビゲーターの ListContacts")
<!-- picture --></span><span class="sxs-lookup"><span data-stu-id="50e6e-119">![](media/3-richer-more-unified-connector-developer-ecosystem-2.png "ListContacts in Navigator")
<!-- picture --></span></span>

## <a name="improved-consumption-for-connectors"></a><span data-ttu-id="50e6e-120">コネクタの消費の向上</span><span class="sxs-lookup"><span data-stu-id="50e6e-120">Improved consumption for connectors</span></span>
<span data-ttu-id="50e6e-121">このリリースでは、Power BI Desktop のコネクタおよびオンプレミス データ ゲートウェイを介して消費エクスペリエンスを向上させるために、統合エクスペリエンスが提供されるようになっています。</span><span class="sxs-lookup"><span data-stu-id="50e6e-121">With this release, we now provide an integrated experience to offer improved consumption experiences for connectors in Power BI Desktop and via the On-premises Data Gateway.</span></span>  <span data-ttu-id="50e6e-122">パートナーや ISV が作成した認定コネクタを簡単に見つけて Power BI Desktop で使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="50e6e-122">Certified connectors built by partners and ISVs can now be easily discovered and used in Power BI Desktop.</span></span>
<span data-ttu-id="50e6e-123">この統合により、コネクタが多くの統合に追加されることになり、エコシステムの開発者と消費者にとってエクスペリエンスが改善されます。</span><span class="sxs-lookup"><span data-stu-id="50e6e-123">This  integration will add connectors to the large number of integrations and improve experiences for our developers and consumers in the ecosystem.</span></span>  <span data-ttu-id="50e6e-124">オンプレミス データ ゲートウェイの個人およびエンタープライズ バージョンの両方で、認定コネクタおよびカスタム コネクタの検出とデータ更新がサポートされるようになっています。</span><span class="sxs-lookup"><span data-stu-id="50e6e-124">Both the personal and enterprise versions of the On-premises Data Gateway now support discovery and data refreshes for certified and custom connectors.</span></span>

-  [<span data-ttu-id="50e6e-125">Power BI Desktop での認定コネクタのサポート</span><span class="sxs-lookup"><span data-stu-id="50e6e-125">Support for certified connectors in Power BI Desktop</span></span>](1-power-query.md#certified-custom-connectors-in-power-bi-desktop)
-  [<span data-ttu-id="50e6e-126">個人およびエンタープライズ ゲートウェイのカスタム コネクタのサポート</span><span class="sxs-lookup"><span data-stu-id="50e6e-126">Support for custom connectors in the personal and enterprise gateway</span></span>](5-data-gateway.md#certified-custom-connectors-in-power-bi-desktop)


## <a name="unified-connector-certification-program"></a><span data-ttu-id="50e6e-127">統一コネクタ認定プログラム</span><span class="sxs-lookup"><span data-stu-id="50e6e-127">Unified connector certification program</span></span>
<span data-ttu-id="50e6e-128">コネクタを作成する開発者や ISV は、認定用にコネクタを Microsoft に提出することができます。</span><span class="sxs-lookup"><span data-stu-id="50e6e-128">Developers and ISVs building connectors may submit their connectors for certification to Microsoft.</span></span>
<span data-ttu-id="50e6e-129">認定されたコネクタは公開され、エンドユーザーに統合エクスペリエンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="50e6e-129">Certified connectors are released publicly and provide an integrated experience for end users.</span></span>
<span data-ttu-id="50e6e-130">また、サービスのリーチ、見つけやすさ、使用率を向上することになります。</span><span class="sxs-lookup"><span data-stu-id="50e6e-130">It increases the reach, discoverability, and usage of the service.</span></span>

<span data-ttu-id="50e6e-131">コネクタ認定プログラムでは、次の基本要件を満たすパートナー作成コネクタであればどれでも提出できます。</span><span class="sxs-lookup"><span data-stu-id="50e6e-131">The connector certification program is open to submissions for any partner-built connectors that meet the basic requirements:</span></span>

- <span data-ttu-id="50e6e-132">提出者は、コネクタが対象としているサービスの関係者である。</span><span class="sxs-lookup"><span data-stu-id="50e6e-132">The submitter is affiliated with the service the connector is built against.</span></span>
- <span data-ttu-id="50e6e-133">コネクタは、対象プラットフォームのビジネス ユーザー シナリオをサポートしている。</span><span class="sxs-lookup"><span data-stu-id="50e6e-133">The connector supports business user scenarios for the targeted platform.</span></span>

<span data-ttu-id="50e6e-134">詳細については、[コネクタ認定プログラム](https://aka.ms/connector-certification)をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="50e6e-134">Read more about the [connector certification program](https://aka.ms/connector-certification).</span></span>


