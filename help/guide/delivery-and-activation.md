---
title: 配信とアクティベーションのチュートリアル
description: コンテンツとキャンペーンのパフォーマンスとエクスペリエンスを強化します。  アセットの迅速なアクティベーションとコンテンツのパフォーマンスの向上
solution: Experience Cloud, Experience Manager, Campaign, Journey Optimizer, Marketo, Target
feature-set: Experience Cloud, Experience Manager, Campaign, Journey Optimizer, Marketo Engage, Target
topic: Content Management, Collaboration, Personalization, Artificial Intelligence
role: Admin, User, Leader, Data Architect, Data Engineer
level: Beginner
last-substantial-update: 2024-03-06T00:00:00Z
jira: KT-14157
source-git-commit: fecc107042220664ce5b76584f834a025844ef4b
workflow-type: tm+mt
source-wordcount: '610'
ht-degree: 48%

---


# 配信とアクティベーションのチュートリアル

コンテンツとキャンペーンのパフォーマンスとエクスペリエンスを強化します。  アセットの迅速なアクティベーションとコンテンツのパフォーマンスの向上

コンテンツのアクティベーションと分析に使用されるAdobeソリューションは次のとおりです。

<table>
    <tr style="border: 0;">
      <td style="vertical-align: middle">
        <p style="margin: 0"><img alt="Experience Manager Sites" src="/help/assets/aem-logo.png" style="verticle-align: middle;width: 42px;height: 42px;"></p>
        <strong>Experience Manager Sites</strong>
      </td>
      <td style="vertical-align: middle">
        <p style="margin: 0"><img alt="Adobe Campaign" src="/help/assets/ac-logo.png" style="verticle-align: middle;width: 42px;height: 42px;"></p>
        <strong>Adobe Campaign</strong>
      </td>
      <td style="vertical-align: middle">
        <p style="margin: 0"><img alt="Journey Optimizer" src="/help/assets/ajo-logo.png" style="verticle-align: middle;width: 42px;height: 42px;"></p>
        <strong>Journey Optimizer</strong>
      </td>
      <td style="vertical-align: middle">
        <p style="margin: 0"><img alt="Marketo" src="/help/assets/marketo-logo.png" style="verticle-align: middle;width: 42px;height: 42px;"></p>
        <strong>Marketo</strong>
      </td>
      <td style="vertical-align: middle">
        <p style="margin: 0"><img alt="ターゲット" src="/help/assets/target-logo.png" style="verticle-align: middle;width: 42px;height: 42px;"></p>
        <strong>Target</strong>
      </td>
    </tr>
</table>

>[!TIP]
>
>アドビのAdobe製品エキスパートチームは、主なコンテンツサプライチェーンの使用例に関する統合チュートリアルのコレクションを組み立てました。 複数のソリューションを使用している場合は、統合する最適な方法を学んでください。  以下を確認します。 [コンテンツサプライチェーン統合チュートリアル](https://experienceleague.adobe.com/docs/integrations-learn/experience-cloud/solution-categories/content-supply-chain.html?lang=en).

## チュートリアル

<div class="columns is-multiline"><div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="Video Smart Tags" tabIndex="0">
  <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
    <div class="card-image">
      <figure class="image x-is-16by9">
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/metadata/video-smart-tags.html?lang=ja" title="ビデオスマートタグ" tabindex="-1">
          <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/327005?format=jpeg" alt="ビデオスマートタグ">
        </a>
      </figure>
    </div>
    <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
      <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
              <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/metadata/video-smart-tags.html?lang=ja" title="ビデオスマートタグ">ビデオスマートタグ</a>
          </p>
          <p class="is-size-6"><em>Experience Manager Assets は Adobe Sensei を利用して、ビデオの主要な要素を説明するキーワードでインテリジェントにビデオアセットにタグを付け、AEM ユーザーによるキーワード検索で簡単に見つけられるようにします。</em></p>
      </div>
      <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/metadata/video-smart-tags.html?lang=ja" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
        <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">ビデオを見る</span>
      </a>
    </div>
  </div>
</div><div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="Quick Site Creation" tabIndex="1">
  <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
    <div class="card-image">
      <figure class="image x-is-16by9">
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-wknd-tutorial-develop/site-template/overview.html?lang=ja" title="クイックサイト作成" tabindex="-1">
          <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/333477?format=jpeg" alt="クイックサイト作成">
        </a>
      </figure>
    </div>
    <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
      <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
              <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-wknd-tutorial-develop/site-template/overview.html?lang=ja" title="クイックサイト作成">クイックサイト作成</a>
          </p>
          <p class="is-size-6"><em>ローコードのアプローチを使用して、クイックサイト作成と事前定義済みのサイトテンプレートを使用してAdobe Experience Managerで最初のサイトを作成する方法を説明します。</em></p>
      </div>
      <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-wknd-tutorial-develop/site-template/overview.html?lang=ja" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
        <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">ビデオを見る</span>
      </a>
    </div>
  </div>
</div><div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="Mapping Metadata" tabIndex="3">
  <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
    <div class="card-image">
      <figure class="image x-is-16by9">
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/map-metadata.html?lang=ja" title="メタデータのマッピング" tabindex="-1">
          <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/336458?format=jpeg" alt="メタデータのマッピング">
        </a>
      </figure>
    </div>
    <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
      <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
              <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/map-metadata.html?lang=ja" title="メタデータのマッピング">メタデータのマッピング</a>
          </p>
          <p class="is-size-6"><em>Workfront フィールドと Assets Essentials プロパティの間でメタデータマッピングを設定する方法と、マッピングされた値を表示するように Assets Essentials を設定する方法について説明します。</em></p>
      </div>
      <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/map-metadata.html?lang=ja" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
        <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">ビデオを見る</span>
      </a>
    </div>
  </div>
</div><div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="Getting started with AEM Headless CMS" tabIndex="4">
  <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
    <div class="card-image">
      <figure class="image x-is-16by9">
        <a href="https://experienceleague.adobe.com/landing/experience-manager/headless/developer.html?lang=ja" title="AEMヘッドレス CMS の概要" tabindex="-1">
          <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/339031?format=jpeg" alt="AEMヘッドレス CMS の概要">
        </a>
      </figure>
    </div>
    <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
      <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
              <a href="https://experienceleague.adobe.com/landing/experience-manager/headless/developer.html?lang=ja" title="AEMヘッドレス CMS の概要">AEMヘッドレス CMS の概要</a>
          </p>
          <p class="is-size-6"><em>AEMヘッドレス CMS について学ぶ必要のあるすべてが、より優れたアプリケーションを構築して出荷し、より迅速なエクスペリエンスを実現します。</em></p>
      </div>
      <a href="https://experienceleague.adobe.com/landing/experience-manager/headless/developer.html?lang=ja" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
        <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">ビデオを見る</span>
      </a>
    </div>
  </div>
</div><div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="Create templates" tabIndex="5">
  <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
    <div class="card-image">
      <figure class="image x-is-16by9">
        <a href="https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/expressoverview/expresshowto/create-templates.html" title="テンプレートの作成" tabindex="-1">
          <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/3420208?format=jpeg" alt="テンプレートの作成">
        </a>
      </figure>
    </div>
    <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
      <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
              <a href="https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/expressoverview/expresshowto/create-templates.html" title="テンプレートの作成">テンプレートの作成</a>
          </p>
          <p class="is-size-6"><em>同じプロジェクトレイアウトを再度使用する方法を説明します。</em></p>
      </div>
      <a href="https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/expressoverview/expresshowto/create-templates.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
        <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">ビデオを見る</span>
      </a>
    </div>
  </div>
</div><div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="AEM Assets Sidekick plugin and Edge Delivery Services" tabIndex="6">
  <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
    <div class="card-image">
      <figure class="image x-is-16by9">
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/edge-delivery-services/sidekick-plugin.html?lang=ja" title="AEM Assets Sidekick プラグインと Edge 配信サービス" tabindex="-1">
          <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/3424615?format=jpeg" alt="AEM Assets Sidekick プラグインと Edge 配信サービス">
        </a>
      </figure>
    </div>
    <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
      <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
              <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/edge-delivery-services/sidekick-plugin.html?lang=ja" title="AEM Assets Sidekick プラグインと Edge 配信サービス">AEM AssetsSidekickのプラグインとEdge Delivery Services</a>
          </p>
          <p class="is-size-6"><em>AEM Assets Sidekick プラグインを利用して、Edge 配信サービスを通じて提供される影響力の高いエクスペリエンスに管理対象アセットを組み込む方法について説明します。</em></p>
      </div>
      <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/edge-delivery-services/sidekick-plugin.html?lang=ja" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
        <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">ビデオを見る</span>
      </a>
    </div>
  </div>
</div><div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="Content Fragments Console videos" tabIndex="7">
  <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
    <div class="card-image">
      <figure class="image x-is-16by9">
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/content-fragments-console/overview.html?lang=ja" title="コンテンツフラグメントコンソールのビデオ" tabindex="-1">
          <img class="is-bordered-r-small" src="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/main.png?lang=en" alt="コンテンツフラグメントコンソールのビデオ">
        </a>
      </figure>
    </div>
    <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
      <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
              <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/content-fragments-console/overview.html?lang=ja" title="コンテンツフラグメントコンソールのビデオ">コンテンツフラグメントコンソールのビデオ</a>
          </p>
          <p class="is-size-6"><em>Adobe Experience Manager のコンテンツフラグメントコンソールを使用すると、コンテンツフラグメントの管理とオーサリングが簡単になります。これらのビデオでコンテンツフラグメントコンソールを最大限に活用する方法を説明します。</em></p>
      </div>
      <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/content-fragments-console/overview.html?lang=ja" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
        <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">詳細情報</span>
      </a>
    </div>
  </div>
</div><div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="Assets Essentials Overview" tabIndex="8">
  <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
    <div class="card-image">
      <figure class="image x-is-16by9">
        <a href="https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/assets-essentials-overview.html" title="Assets Essentialsの概要" tabindex="-1">
          <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/342098?format=jpeg" alt="Assets Essentialsの概要">
        </a>
      </figure>
    </div>
    <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
      <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
              <a href="https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/assets-essentials-overview.html" title="Assets Essentialsの概要">Assets Essentialsの概要</a>
          </p>
          <p class="is-size-6"><em>Assets Essentialsの機能と、Adobe Journey Optimizerでの使用方法の概要を説明します。</em></p>
      </div>
      <a href="https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/assets-essentials-overview.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
        <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">ビデオを見る</span>
      </a>
    </div>
  </div>
</div><div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="Personalization of full web page Experience" tabIndex="9">
  <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
    <div class="card-image">
      <figure class="image x-is-16by9">
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/sites/integrations/target/personalization-web-page.html" title="完全な web ページエクスペリエンスのパーソナライゼーション" tabindex="-1">
          <img class="is-bordered-r-small" src="https://cdn.experienceleague.adobe.com/thumb/6353-personalization-web-page.jpg" alt="完全な web ページエクスペリエンスのパーソナライゼーション">
        </a>
      </figure>
    </div>
    <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
      <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
              <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/sites/integrations/target/personalization-web-page.html" title="完全な web ページエクスペリエンスのパーソナライゼーション">完全な Web ページエクスペリエンスのパーソナライズ</a>
          </p>
          <p class="is-size-6"><em>Adobe Target を使用して、AEMでホストされているサイトのページを新しいページにリダイレクトするアクティビティの作成方法を説明します。</em></p>
      </div>
      <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/sites/integrations/target/personalization-web-page.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
        <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">詳細情報</span>
      </a>
    </div>
  </div>
</div><div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="Personalization using Visual Experience Composer" tabIndex="10">
  <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
    <div class="card-image">
      <figure class="image x-is-16by9">
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/sites/integrations/target/personalization-using-vec.html" title="Visual Experience Composer を使用したパーソナライズ機能" tabindex="-1">
          <img class="is-bordered-r-small" src="https://cdn.experienceleague.adobe.com/thumb/6352-personalization-using-vec.jpg" alt="Visual Experience Composer を使用したパーソナライズ機能">
        </a>
      </figure>
    </div>
    <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
      <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
              <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/sites/integrations/target/personalization-using-vec.html" title="Visual Experience Composer を使用したパーソナライズ機能">Visual Experience Composer を使用したパーソナライゼーション</a>
          </p>
          <p class="is-size-6"><em>Visual Experience Composer（VEC）を使用して Target アクティビティの A/B テスト を作成する方法を説明します。</em></p>
      </div>
      <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/sites/integrations/target/personalization-using-vec.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
        <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">詳細情報</span>
      </a>
    </div>
  </div>
</div><div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="Create Adobe Target Activity using Experience Fragment Offers" tabIndex="11">
  <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
    <div class="card-image">
      <figure class="image x-is-16by9">
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/sites/integrations/target/create-target-activity.html" title="エクスペリエンスフラグメントオファーを使用して Adobe Target Activity を作成する" tabindex="-1">
          <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/41246?format=jpeg" alt="エクスペリエンスフラグメントオファーを使用して Adobe Target Activity を作成する">
        </a>
      </figure>
    </div>
    <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
      <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
              <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/sites/integrations/target/create-target-activity.html" title="エクスペリエンスフラグメントオファーを使用して Adobe Target Activity を作成する">エクスペリエンスフラグメントオファーを使用してAdobe Targetアクティビティを作成する</a>
          </p>
          <p class="is-size-6"><em>AEM エクスペリエンスフラグメントオファーを使用して、 Adobe Target Activity を作成およびテストする方法について説明します。</em></p>
      </div>
      <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/sites/integrations/target/create-target-activity.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
        <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">ビデオを見る</span>
      </a>
    </div>
  </div>
</div></div>

<!--
<table class="tablelayout-is-fixed">
<tr>
  <td>
    <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/metadata/video-smart-tags.html">
      <img alt="Video Smart Tags" src="https://video.tv.adobe.com/v/327005?format=jpeg">
    </a>
    <div>
      <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/metadata/video-smart-tags.html">
    <strong>Video Smart Tags</strong>
    </a>
    </div>
    <p>
    <em>Experience Manager Assets leverages Adobe Sensei to intelligently tag video assets with keywords that describe key elements of the video, allowing them to be easily discovered using keyword search by AEM users.</em>
    </p><p>
  </p></td>
  <td>
    <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-wknd-tutorial-develop/site-template/overview.html">
      <img alt="Quick Site Creation" src="https://video.tv.adobe.com/v/333477?format=jpeg">
    </a>
    <div>
      <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-wknd-tutorial-develop/site-template/overview.html">
    <strong>Quick Site Creation</strong>
    </a>
    </div>
    <p>
    <em>Learn how to use a low-code approach to create your first site in Adobe Experience Manager with Quick Site Creation and a pre-defined Site Template.</em>
    </p><p>
  </p></td>
  <td>
    <a href="https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/email-channel/create-content-with-the-email-designer.html">
      <img alt="Create content with the Email Designer" src="https://video.tv.adobe.com/v/334150?format=jpeg">
    </a>
    <div>
      <a href="https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/email-channel/create-content-with-the-email-designer.html">
    <strong>Create content with the Email Designer</strong>
    </a>
    </div>
    <p>
    <em>Learn how to create emails from scratch. Understand how to use assets from the Adobe Experience Manager Assets Essentials library, edit the responsive email design, and create emails from templates.</em>
    </p><p>
  </p></td>
  <td>
    <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/map-metadata.html">
      <img alt="Mapping Metadata" src="https://video.tv.adobe.com/v/336458?format=jpeg">
    </a>
    <div>
      <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/map-metadata.html">
    <strong>Mapping Metadata</strong>
    </a>
    </div>
    <p>
    <em>Learn how to configure metadata mapping between Workfront fields and Assets Essentials properties, as well as configuring Assets Essentials to display the mapped values.</em>
    </p><p>
  </p></td>
  </tr>
  <tr>
  <td>
    <a href="https://experienceleague.adobe.com/landing/experience-manager/headless/developer.html">
      <img alt="Getting started with AEM Headless CMS" src="https://video.tv.adobe.com/v/339031?format=jpeg">
    </a>
    <div>
      <a href="https://experienceleague.adobe.com/landing/experience-manager/headless/developer.html">
    <strong>Getting started with AEM Headless CMS</strong>
    </a>
    </div>
    <p>
    <em>Everything you need to learn about AEM headless CMS to build and ship better applications and faster experiences.</em>
    </p><p>
  </p></td>
  <td>
    <a href="https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/expressoverview/expresshowto/create-templates.html">
      <img alt="Create templates" src="https://video.tv.adobe.com/v/3420208?format=jpeg">
    </a>
    <div>
      <a href="https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/expressoverview/expresshowto/create-templates.html">
    <strong>Create templates</strong>
    </a>
    </div>
    <p>
    <em>Learn how to use the same project layout again.</em>
    </p><p>
  </p></td>
   <td>
    <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/edge-delivery-services/sidekick-plugin.html">
      <img alt="AEM Assets Sidekick plugin and Edge Delivery Services" src="https://video.tv.adobe.com/v/3424615?format=jpeg">
    </a>
    <div>
      <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/edge-delivery-services/sidekick-plugin.html">
    <strong>AEM Assets Sidekick plugin and Edge Delivery Services</strong>
    </a>
    </div>
    <p>
    <em>Learn how the AEM Assets Sidekick plugin can be utilized to incorporate managed assets into high-impact experiences delivered through Edge Delivery Services.</em>
    </p><p>
  </p></td>
  <td>
    <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/content-fragments-console/overview.html">
      <img alt="Content Fragments Console videos" src="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/main.png">
    </a>
    <div>
      <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/content-fragments-console/overview.html">
    <strong>Content Fragments Console videos</strong>
    </a>
    </div>
    <p>
    <em>Adobe Experience Manager's Content Fragments Console makes managing and authoring Content Fragments easy! Learn how to make the most of the Content Fragments Console with these videos.</em>
    </p><p>
  </p></td>
  </tr>
  <tr>
  <td>
    <a href="https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/assets-essentials-overview.html">
      <img alt="Assets Essentials Overview" src="https://video.tv.adobe.com/v/342098?format=jpeg">
    </a>
    <div>
      <a href="https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/assets-essentials-overview.html">
    <strong>Assets Essentials Overview</strong>
    </a>
    </div>
    <p>
    <em>Get an overview over the Assets Essentials features and how it can be used in Adobe Journey Optimizer.</em>
    </p><p>
  </p></td>
   <td>
    <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/sites/integrations/target/personalization-web-page.html">
      <img alt="Personalization of full web page Experience" src="https://cdn.experienceleague.adobe.com/thumb/6353-personalization-web-page.jpg">
    </a>
    <div>
      <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/sites/integrations/target/personalization-web-page.html">
    <strong>Personalization of full web page Experience</strong>
    </a>
    </div>
    <p>
    <em>Learn how to create an activity to redirect your site pages that are hosted on AEM to a new page using Adobe Target.</em>
    </p><p>
  </p></td>
   <td>
    <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/sites/integrations/target/personalization-using-vec.html">
      <img alt="Personalization using Visual Experience Composer" src="https://cdn.experienceleague.adobe.com/thumb/6352-personalization-using-vec.jpg">
    </a>
    <div>
      <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/sites/integrations/target/personalization-using-vec.html">
    <strong>Personalization using Visual Experience Composer</strong>
    </a>
    </div>
    <p>
    <em>Learn how to create an A/B Test Target Activity using Visual Experience Composer (VEC).</em>
    </p><p>
  </p></td>
   <td>
    <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/sites/integrations/target/create-target-activity.html">
      <img alt="Create Adobe Target Activity using Experience Fragment Offers" src="https://video.tv.adobe.com/v/41246?format=jpeg">
    </a>
    <div>
      <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/sites/integrations/target/create-target-activity.html">
    <strong>Create Adobe Target Activity using Experience Fragment Offers</strong>
    </a>
    </div>
    <p>
    <em>Learn how to create and test an Adobe Target Activity using AEM Experience Fragment Offers.</em>
    </p><p>
  </p></td>
</tr>
</table>
-->

## その他のリソース

* [Experience Leagueイベント](https://experienceleague.adobe.com/events/)
* [コンテンツサプライチェーンに関するAdobe](https://business.adobe.com/resources/webinars/adobe-on-the-content-supply-chain.html)