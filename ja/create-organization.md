# 組織とプロジェクトの作成
**Quickstarts > 2.組織とプロジェクトの作成**

今回の学習モジュールでは、NHN Cloudコンソールの主な機能を理解し、活用するために必要な基本概念と設定方法をご案内します。NHN Cloudコンソールは、多様なクラウドリソースを効率的に管理・設定できる統合管理ツールです。ユーザーフレンドリーなインターフェースを通じてサービスの作成、モニタリング、設定変更などの作業を簡単に行うことができ、リアルタイムのリソースの状態とコスト管理機能も提供します。 
コンソールのプロジェクトダッシュボードを通じて使用中のクラウドサービスとリソース情報を一目で確認することができ、詳細設定や管理オプションは直感的なメニューを通じて簡単にアクセスすることができます。

![module_info](https://kr1-api-object-storage.nhncloudservice.com/v1/AUTH_2acdfabf4efe4efc8a04c00b348110c9/cdn_origin/prod_cloud_quickstarts/module_info/%EC%A1%B0%EC%A7%81%EA%B3%BC%20%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%20%EC%83%9D%EC%84%B1.png)
## 学習目標

今回の学習モジュールで学ぶ内容は以下の通りです。

* **NHN Cloudコンソール接続**
    * クラウド管理のためのコンソール接続
* **組織、プロジェクト、リージョンの設定**
    * クラウドリソース管理のための基本設定構成

<br></br>

![mod2_diagram](https://kr1-api-object-storage.nhncloudservice.com/v1/AUTH_2acdfabf4efe4efc8a04c00b348110c9/cdn_origin/prod_cloud_quickstarts/%EB%AA%A8%EB%93%88%202.%20%EC%A1%B0%EC%A7%81%EA%B3%BC%20%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%20%EC%83%9D%EC%84%B1.png)

<p style="text-align: center; color: black;">最終構成図</p>

> リージョン、組織、プロジェクト、可用性領域は以降の学習モジュールで同じように使用されるため、以降の学習モジュールの最終構成図では省略されます。

## 始める前に

今回の学習モジュールを始める前に必要なものは以下の通りです。

* **標準のインターネットブラウザ**
    * Google Chrome、Microsoft Edge、Firefox、Safariなどの最新バージョンのブラウザがインストールされている必要があります。
    * ブラウザの設定でJavaScriptとCookieが有効になっている必要があります。
* **インターネット接続環境**
    * 安定したインターネット接続が必要で、推奨帯域幅は最低5Mbps以上です。
    * HTTPSによる安全な通信が可能であること。
* **会員アカウント**
    * 決済手段を登録したNHN Cloudアカウントが必要です。
    * NHN Cloudのホームページにログインする必要があります。

    **本ガイドは、[1.アカウント作成とログイン](https://docs.nhncloud.com/ja/quickstarts/ja/create-account/)以降の手順から始めます。**

## NHN Cloudコンソールを使用するための準備

### ステップ1.NHN Cloudコンソールにアクセスする

1. NHN Cloudホームページ[(https://www.nhncloud.com)](https://www.nhncloud.com/)にログインします。
2. トップメニューの**CONSOLEを**クリックします。
3. 新しいブラウザウィンドウまたはタブで**NHN Cloudコンソールページを**確認します。

### ステップ2.組織を作成する

1. NHN Cloudコンソール上部にある**組織を作成してください。**横の**+**をクリックします。
2. 組織作成ウィンドウで以下の情報を入力し、[**OK**]をクリックします。
    * 組織名:`MyORG`
3. 通知ウィンドウで[**OK**]をクリックします。
4. 作成した組織のダッシュボードとコンソール画面を確認します。

!!! tip "知っておこう"
    * 既に作成された組織がある場合
        * 既に作成した組織がある場合は、その組織リストの下部にある**+組織作成を**クリックすると、以下の作業を進めることができます。

### ステップ3.プロジェクトを作成する

1. NHN Cloudコンソール上部にある**組織タブで** `MyORGを`クリックします。組織が1つの場合、自動的に選択されています。
2. 選択した組織タブの右側にある**新規プロジェクト作成の**横にある\*\*+**をクリックします。
3. **プロジェクト作成**ウィンドウで以下の情報を入力し、[**OK**]をクリックします。
    * プロジェクト名:`MyPRJ`
4. 通知ウィンドウで[**OK**]をクリックします。
5. 作成したプロジェクトのダッシュボードとコンソール画面を確認します。

### ステップ4.リージョンを選択する

1. NHN Cloudコンソールの右上にある**韓国(板橋)リージョンに**マウスカーソルを移動します。
2. リージョンリストから`韓国(平村)リージョンを`クリックします。

## 参考サイト

* [コンソールポリシーガイド](https://docs.nhncloud.com/ja/nhncloud/ja/console-guide/)
* [リソース提供ポリシー](https://docs.nhncloud.com/ja/nhncloud/ja/resource-policy/)

## 前の段階

* [1. アカウント作成とログイン](https://docs.nhncloud.com/ja/quickstarts/ja/create-account/)

## 次のステップ

* [3. IAMアカウントとガバナンス設定](https://docs.nhncloud.com/ja/quickstarts/ja/iam-accounts/)
