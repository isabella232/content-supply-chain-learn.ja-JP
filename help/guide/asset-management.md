---
title: アセット管理チュートリアル
description: コンテンツの作成と完了を計画するプロセスを通じて、コンテンツ要件の接続と追跡に苦労する企業向けです。 プロジェクト間での効果的なプロセス、計画、承認、データの一貫性が欠如しているため、この企業の生産性と効率性の両方のコンテンツ・サプライ・チェーンが奪われています。
solution: Experience Cloud, Experience Manager Assets
feature-set: Experience Manager, Experience Manager Assets
feature: Asset Management, Asset Processing
topic: Content Management, Collaboration, Artificial Intelligence
role: Admin, User, Leader, Developer
level: Beginner
last-substantial-update: 2024-03-06T00:00:00Z
jira: KT-15076
source-git-commit: f3082975a674a13152aa92c06302e67e9f4715b6
workflow-type: tm+mt
source-wordcount: '1075'
ht-degree: 17%

---


# アセット管理チュートリアル

ブランドの一貫性を確保しながら、1 つのクラウドベースのソリューションから数百万のアセットに容易にアクセスし、再利用できます。  これらのチュートリアルでは、Adobe Experience Manager Assetsの使用に焦点を当てています。


>[!TIP]
>
>アドビのAdobe製品エキスパートチームは、主なコンテンツサプライチェーンの使用例に関する統合チュートリアルのコレクションを組み立てました。 複数のソリューションを使用している場合は、統合する最適な方法を学んでください。  以下を確認します。 [コンテンツサプライチェーン統合チュートリアル](https://experienceleague.adobe.com/docs/integrations-learn/experience-cloud/solution-categories/content-supply-chain.html?lang=en).

## 推奨コース
<div class="columns is-multiline">
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[AEM Assets - Assets View] Bulk Import - Feature Video" tabIndex="0">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/bulk-import.html?lang=ja" title="[AEM Assets - Assets の表示 ] 一括読み込み — 機能のビデオ" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/3426857?format=jpeg" alt="[AEM Assets - Assets の表示 ] 一括読み込み — 機能のビデオ">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/bulk-import.html?lang=ja" title="[AEM Assets - Assets の表示 ] 一括読み込み — 機能のビデオ">[AEM Assets - Assets の表示 ] 一括読み込み — 機能のビデオ</a>
          </p>
          <p class="is-size-6">一括読み込み機能を使用して多数のファイルをAEM Assetsに読み込む方法を説明します。Dropboxは、サンプルのクラウドストレージプロバイダーとして機能し、わかりやすく簡単に統合できます。</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/bulk-import.html?lang=ja" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">続きを読む</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Asset Essentials][Workfront] Assets Essentials and Workfront integration - Catalog" tabIndex="1">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/overview.html" title="[Asset Essentials][Workfront]Assets EssentialsとWorkfrontの統合 — カタログ" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/3422184?format=jpeg" alt="[Asset Essentials][Workfront]Assets EssentialsとWorkfrontの統合 — カタログ">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/overview.html" title="[Asset Essentials][Workfront]Assets EssentialsとWorkfrontの統合 — カタログ">[Asset Essentials][Workfront]Assets EssentialsとWorkfrontの統合 — カタログ</a>
          </p>
          <p class="is-size-6">WorkfrontとAssets Essentialsの統合方法</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/overview.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">続きを読む</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[AEM Assets] Adobe Express integration - Feature Video" tabIndex="2">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/creative-workflows/adobe-express-aem-assets-add-on.html" title="[AEM Assets]Adobe Expressの統合 — 機能のビデオ" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/3425193?format=jpeg" alt="[AEM Assets]Adobe Expressの統合 — 機能のビデオ">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/creative-workflows/adobe-express-aem-assets-add-on.html" title="[AEM Assets]Adobe Expressの統合 — 機能のビデオ">[AEM Assets]Adobe Expressの統合 — 機能のビデオ</a>
          </p>
          <p class="is-size-6">AEM Assets と Adobe Express を使用してコンテンツのサプライチェーンを最適化し、すべてのチームメンバーの生産性とアクセシビリティを向上させる方法について説明します。</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/creative-workflows/adobe-express-aem-assets-add-on.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">続きを読む</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Adobe Express] Empower marketing teams to create multi-channel content - Feature video" tabIndex="3">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/expressoverview/expressusecase/multi-channel-marketing-content.html" title="[Adobe Express] マーケティングチームがマルチチャネルコンテンツを作成できるようにする — ビデオを特集" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/3424446?format=jpeg" alt="[Adobe Express] マーケティングチームがマルチチャネルコンテンツを作成できるようにする — ビデオを特集">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/expressoverview/expressusecase/multi-channel-marketing-content.html" title="[Adobe Express] マーケティングチームがマルチチャネルコンテンツを作成できるようにする — ビデオを特集">[Adobe Express] マーケティングチームがマルチチャネルコンテンツを作成できるようにする — ビデオを特集</a>
          </p>
          <p class="is-size-6">イベントマーケティングチームが、オンラインイベントの視聴者を惹きつける独自のコンテンツを作成する方法を説明します。 このワークフローでは、B2B マーケターがブランドキットとライブラリのテンプレートを使用して、Adobe Expressで新しいプロジェクトを開始します。 B2B マーケターは、様々なソーシャルチャネルと Web チャネルのバリエーションを作成し、ソーシャルメディアおよびビデオホスティングプラットフォームでコンテンツを共有します。</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/expressoverview/expressusecase/multi-channel-marketing-content.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">続きを読む</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[AEM Assets] Workfront Enhanced Integration Basics - Feature Video" tabIndex="4">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/basics.html?lang=ja" title="[AEM Assets] Workfront Enhanced Integration Basics — 機能のビデオ" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/337575?format=jpeg" alt="[AEM Assets] Workfront Enhanced Integration Basics — 機能のビデオ">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/basics.html?lang=ja" title="[AEM Assets] Workfront Enhanced Integration Basics — 機能のビデオ">[AEM Assets] Workfront Enhanced Integration Basics — 機能のビデオ</a>
          </p>
          <p class="is-size-6">アセットとフォルダーのリンク、メタデータマッピングの定義、AEMへのアセットの送信、バージョンアセットの自動公開の方法など、Adobe WorkfrontとExperience Manager Assetsの統合の基本について説明します。</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/basics.html?lang=ja" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">続きを読む</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[AEM Assets] AEM and Adobe Asset Link Creative Workflow - Value Video" tabIndex="5">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/creative-workflows/adobe-asset-link.html" title="[AEM Assets] AEMとAdobeアセットリンクのクリエイティブワークフロー — Value Video" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/335927?format=jpeg" alt="[AEM Assets] AEMとAdobeアセットリンクのクリエイティブワークフロー — Value Video">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/creative-workflows/adobe-asset-link.html" title="[AEM Assets] AEMとAdobeアセットリンクのクリエイティブワークフロー — Value Video">[AEM Assets] AEMとAdobeアセットリンクのクリエイティブワークフロー — Value Video</a>
          </p>
          <p class="is-size-6">AAL およびAAMを使用するユーザーのクリエイティブワークフローを示すビデオ</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/creative-workflows/adobe-asset-link.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">続きを読む</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[AJO] Create content with the Email Designer - Feature Video" tabIndex="6">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/email-channel/create-content-with-the-email-designer.html" title="[AJO] E メールデザイナーでコンテンツを作成する — 機能ビデオ" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/334150?format=jpeg" alt="[AJO] E メールデザイナーでコンテンツを作成する — 機能ビデオ">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/email-channel/create-content-with-the-email-designer.html" title="[AJO] E メールデザイナーでコンテンツを作成する — 機能ビデオ">[AJO] E メールデザイナーでコンテンツを作成する — 機能ビデオ</a>
          </p>
          <p class="is-size-6">メールを一から作成する方法を学習します。AEM Assets Essentials ライブラリのアセットの使用方法、レスポンシブメールデザインの編集方法、テンプレートからのメールの作成方法について説明します。</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/email-channel/create-content-with-the-email-designer.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">続きを読む</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Asset Essentials] Getting started with Assets Essentials - Feature Video" tabIndex="7">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/getting-started.html?lang=ja" title="[Asset Essentials]Assets Essentialsの概要 — 機能のビデオ" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/336005?format=jpeg" alt="[Asset Essentials]Assets Essentialsの概要 — 機能のビデオ">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/getting-started.html?lang=ja" title="[Asset Essentials]Assets Essentialsの概要 — 機能のビデオ">[Asset Essentials]Assets Essentialsの概要 — 機能のビデオ</a>
          </p>
          <p class="is-size-6">Assets Essentialsが直感的で使いやすいユーザーインターフェイスを提供し、アセットや関連情報を見つけ、覚えやすくする方法について説明します。</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/getting-started.html?lang=ja" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">続きを読む</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[AEM Assets] Content Automation - Value video" tabIndex="8">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/content-automation/overview.html" title="[AEM Assets] コンテンツの自動化 — バリュービデオ" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/333197?format=jpeg" alt="[AEM Assets] コンテンツの自動化 — バリュービデオ">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/content-automation/overview.html" title="[AEM Assets] コンテンツの自動化 — バリュービデオ">[AEM Assets] コンテンツの自動化 — バリュービデオ</a>
          </p>
          <p class="is-size-6">概要は、Adobe Experience Manager Assets コンテンツ自動処理機能で Photoshop と Lightroom の機能を適用する場合のものです。</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/content-automation/overview.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">続きを読む</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Assets] Metadata profiles - Feature Video" tabIndex="9">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/configuring/metadata-profiles" title="[Assets] メタデータプロファイル — 機能のビデオ" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/33974?format=jpeg" alt="[Assets] メタデータプロファイル — 機能のビデオ">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/configuring/metadata-profiles" title="[Assets] メタデータプロファイル — 機能のビデオ">[Assets] メタデータプロファイル — 機能のビデオ</a>
          </p>
          <p class="is-size-6">メタデータプロファイルを使用すると、デフォルトのメタデータをアセットフォルダー内のアセットに自動的に適用でき、AEM ユーザーに対するメタデータ管理の負担を軽減し、メタデータの一貫性を向上できます。</p>
        </div>
        <a href="https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/configuring/metadata-profiles" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">続きを読む</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Assets] Navigation - Feature Video" tabIndex="10">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/authoring/navigation.html" title="[Assets] ナビゲーション — 機能に関するビデオ" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/32046?format=jpeg" alt="[Assets] ナビゲーション — 機能に関するビデオ">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/authoring/navigation.html" title="[Assets] ナビゲーション — 機能に関するビデオ">[Assets] ナビゲーション — 機能に関するビデオ</a>
          </p>
          <p class="is-size-6">AEM Assetsナビゲーションの基本を学ぶ。</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/authoring/navigation.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">続きを読む</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Assets] Comments and Annotations - Feature Video" tabIndex="11">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/collaboration/comments-and-annotations.html" title="[Assets] コメントと注釈 — 機能のビデオ" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/32049?format=jpeg" alt="[Assets] コメントと注釈 — 機能のビデオ">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/collaboration/comments-and-annotations.html" title="[Assets] コメントと注釈 — 機能のビデオ">[Assets] コメントと注釈 — 機能のビデオ</a>
          </p>
          <p class="is-size-6">AEM でコメントと注釈を使用して、アセットに関するコミュニケーションと共同作業を行う方法について説明します。</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/collaboration/comments-and-annotations.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">続きを読む</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Assets] Search - Feature Video" tabIndex="12">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://docs.adobe.com/content/help/en/experience-manager-learn/assets/search-and-discovery/search.html" title="[Assets] 検索 — 機能のビデオ" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/32054?format=jpeg" alt="[Assets] 検索 — 機能のビデオ">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://docs.adobe.com/content/help/en/experience-manager-learn/assets/search-and-discovery/search.html" title="[Assets] 検索 — 機能のビデオ">[Assets] 検索 — 機能のビデオ</a>
          </p>
          <p class="is-size-6">AEM のオムニサーチを使用してアセットをすばやく検出する方法を説明します。</p>
        </div>
        <a href="https://docs.adobe.com/content/help/en/experience-manager-learn/assets/search-and-discovery/search.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">続きを読む</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Assets] Download - Feature Video" tabIndex="13">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/sharing/download.html" title="[Assets] ダウンロード — 機能に関するビデオ" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/35090?format=jpeg" alt="[Assets] ダウンロード — 機能に関するビデオ">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/sharing/download.html" title="[Assets] ダウンロード — 機能に関するビデオ">[Assets] ダウンロード — 機能に関するビデオ</a>
          </p>
          <p class="is-size-6">アセットとそのレンディションをローカルマシンにダウンロードして、使用および共有する方法を説明します。</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/sharing/download.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">続きを読む</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Assets] AEM Desktop App 2.0 - Feature Video" tabIndex="14">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/creative-workflows/aem-desktop-app.html?lang=ja" title="[Assets] AEM Desktop App 2.0 — 機能に関するビデオ" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/28868?format=jpeg" alt="[Assets] AEM Desktop App 2.0 — 機能に関するビデオ">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/creative-workflows/aem-desktop-app.html?lang=ja" title="[Assets] AEM Desktop App 2.0 — 機能に関するビデオ">[Assets] AEM Desktop App 2.0 — 機能に関するビデオ</a>
          </p>
          <p class="is-size-6">AEM Desktop App を使用すると、デスクトップ上で管理されるあらゆるアセットに対し、あらゆるアプリケーションおよびファイル形式で簡単にアクセスできます。</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/creative-workflows/aem-desktop-app.html?lang=ja" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">続きを読む</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Assets] DM Smart Image Crop - Feature Video " tabIndex="15">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/dynamic-media/images/smart-crop-feature-video-use.html?lang=ja" title="[Assets] DM スマート画像切り抜き — 機能ビデオ " tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/21519?format=jpeg" alt="[Assets] DM スマート画像切り抜き — 機能ビデオ ">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/dynamic-media/images/smart-crop-feature-video-use.html?lang=ja" title="[Assets] DM スマート画像切り抜き — 機能ビデオ ">[Assets] DM スマート画像切り抜き — 機能ビデオ </a>
          </p>
          <p class="is-size-6">スマート切り抜きでは Adobe Sensei を使用して、レスポンシブデザインでのコンテンツの切り抜きにおける時間とコストのかかるタスクを排除します。</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/dynamic-media/images/smart-crop-feature-video-use.html?lang=ja" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">続きを読む</span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Assets] Asset Source File Translation - Feature Video" tabIndex="16">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/translation/source-file-translation-feature-video-use" title="[Assets] アセットソースファイルの翻訳 — 機能のビデオ" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/18331?format=jpeg" alt="[Assets] アセットソースファイルの翻訳 — 機能のビデオ">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/translation/source-file-translation-feature-video-use" title="[Assets] アセットソースファイルの翻訳 — 機能のビデオ">[Assets] アセットソースファイルの翻訳 — 機能のビデオ</a>
          </p>
          <p class="is-size-6">Adobe Experience Manager(AEM)Assets では、共通の属性を共有するアセットを識別し、新しい関連アセット機能を使用して、それらのアセットを関連アセットとしてマークすることができます。</p>
        </div>
        <a href="https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/translation/source-file-translation-feature-video-use" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold">続きを読む</span>
        </a>
      </div>
    </div>
  </div>
</div>

## その他のリソース

* [Experience Leagueイベント](https://experienceleague.adobe.com/events/)
* [コンテンツサプライチェーンに関するAdobe](https://business.adobe.com/resources/webinars/adobe-on-the-content-supply-chain.html)
