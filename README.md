# Laravel From Scratch (2026 Edition) - ゼロから始める Laravel (2026年版)

[LARACASTS](https://laracasts.com/) で公開されている Laravel 入門コース [Laravel From Scratch (2026 Edition)](https://laracasts.com/series/laravel-from-scratch-2026) を日本語で要約したものです。（公開当初は AI による要約テキストが公開されており、それを日本語に翻訳。）

Laravel の基本的な仕組みの説明から、ポートフォリオの作成で役立つ実践的なテクニック（テスト、認可、通知、キュー、UI のコツ、ちょっとした JavaScript など）までいろいろ詰まっているので、Laravel の基本を学んだ後に目を通してみると勉強になるでしょう。

本編動画では音声を日本語（AI翻訳によるもの）に切り替えることが可能（動画右下の"Audio"から"Japanese"を選択）なので、実際の手順は本編をご覧ください。


## 基本 (13)

- ### [ようこそ](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/1.%20%E3%82%88%E3%81%86%E3%81%93%E3%81%9D%20-%20Welcome%20Aboard.md)

- ### [開発環境の構築](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/2.%20%E9%96%8B%E7%99%BA%E7%92%B0%E5%A2%83%E3%81%AE%E6%A7%8B%E7%AF%89%20-%20Set%20Up%20Your%20Development.md)

- ### [ルーティング入門](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/3.%20%E3%83%AB%E3%83%BC%E3%83%86%E3%82%A3%E3%83%B3%E3%82%B0%E5%85%A5%E9%96%80%20-%20Routing%20101.md)

- ### [レイアウトファイル](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/4.%20%E3%83%AC%E3%82%A4%E3%82%A2%E3%82%A6%E3%83%88%E3%83%95%E3%82%A1%E3%82%A4%E3%83%AB%20-%20Layout%20Files.md)

- ### [データをビューに渡す](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/5.%20%E3%83%87%E3%83%BC%E3%82%BF%E3%82%92%E3%83%93%E3%83%A5%E3%83%BC%E3%81%AB%E6%B8%A1%E3%81%99%20-%20Pass%20Data%20to%20Views.md)

- ### [Blade ディレクティブ](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/6.%20Blade%20%E3%83%87%E3%82%A3%E3%83%AC%E3%82%AF%E3%83%86%E3%82%A3%E3%83%96%20-%20Blade%20Directives.md)

- ### [フォーム](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/7.%20%E3%83%95%E3%82%A9%E3%83%BC%E3%83%A0%20-%20Forms.md)

- ### [データベース, マイグレーション, Eloquent](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/8.%20%E3%83%87%E3%83%BC%E3%82%BF%E3%83%99%E3%83%BC%E3%82%B9%2C%20%E3%83%9E%E3%82%A4%E3%82%B0%E3%83%AC%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B3%2C%20Eloquent%20-%20Databases%2C%20Migration%2C%20and%20Eloquent.md)

- ### [HTTP リクエストと REST](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/9.%20HTTP%20%E3%83%AA%E3%82%AF%E3%82%A8%E3%82%B9%E3%83%88%E3%81%A8%20REST%20-%20HTTP%20Requests%20and%20REST.md)

- ### [コントローラ](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/10.%20%E3%82%B3%E3%83%B3%E3%83%88%E3%83%AD%E3%83%BC%E3%83%A9%20-%20Controllers.md)

- ### [リクエストの検証](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/11.%20%E3%83%AA%E3%82%AF%E3%82%A8%E3%82%B9%E3%83%88%E3%81%AE%E6%A4%9C%E8%A8%BC%20-%20Request%20Validation.md)

- ### [Form Request クラス](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/12.%20Form%20Request%20%E3%82%AF%E3%83%A9%E3%82%B9%20-%20Form%20Request%20Classes.md)

- ### [DaisyUI についてちょっと寄り道](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/13.%20DaisyUI%20%E3%81%AB%E3%81%A4%E3%81%84%E3%81%A6%E3%81%A1%E3%82%87%E3%81%A3%E3%81%A8%E5%AF%84%E3%82%8A%E9%81%93%20-%20A%20Brief%20DaisyUI%20Detour.md)

## 認証と認可 (5)

- ### [認証の解説](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/14.%20%E8%AA%8D%E8%A8%BC%E3%81%AE%E8%A7%A3%E8%AA%AC%20-%20Authentication%20Explained.md)

- ### [ミドルウェアによる認証を必須化する](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/15.%20%E3%83%9F%E3%83%89%E3%83%AB%E3%82%A6%E3%82%A7%E3%82%A2%E3%81%AB%E3%82%88%E3%82%8B%E8%AA%8D%E8%A8%BC%E3%82%92%E5%BF%85%E9%A0%88%E5%8C%96%E3%81%99%E3%82%8B%20-%20Require%20Authentication%20With%20Middleware.md)

- ### [Eloquent リレーション](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/16.%20Eloquent%20%E3%83%AA%E3%83%AC%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B3%20-%20Eloquent%20Relationships.md)

- ### [ゲートによる認可](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/17.%20%E3%82%B2%E3%83%BC%E3%83%88%E3%81%AB%E3%82%88%E3%82%8B%E8%AA%8D%E5%8F%AF%20-%20Authorization%20Using%20Gates.md)

- ### [ポリシーによる認可](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/18.%20%E3%83%9D%E3%83%AA%E3%82%B7%E3%83%BC%E3%81%AB%E3%82%88%E3%82%8B%E8%AA%8D%E5%8F%AF%20-%20Authorization%20Using%20Policies.md)

## もっと深く掘り下げる (4)

- ### [Vite によるフロントエンドアセットバンドリング](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/19.%20Vite%20%E3%81%AB%E3%82%88%E3%82%8B%E3%83%95%E3%83%AD%E3%83%B3%E3%83%88%E3%82%A8%E3%83%B3%E3%83%89%E3%82%A2%E3%82%BB%E3%83%83%E3%83%88%E3%83%90%E3%83%B3%E3%83%89%E3%83%AA%E3%83%B3%E3%82%B0%20-%20Frontend%20Asset%20Bunding%20with%20Vite.md)

- ### [通知](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/20.%20%E9%80%9A%E7%9F%A5%20-%20Notifications.md)

- ### [キューはいつ使うのか](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/21.%20%E3%82%AD%E3%83%A5%E3%83%BC%E3%81%AF%E3%81%84%E3%81%A4%E4%BD%BF%E3%81%86%E3%81%AE%E3%81%8B%20-%20When%20to%20Queue%20it%20Up.md)

- ### [コードのテストの始め方](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/22.%20%E3%82%B3%E3%83%BC%E3%83%89%E3%81%AE%E3%83%86%E3%82%B9%E3%83%88%E3%81%AE%E5%A7%8B%E3%82%81%E6%96%B9%20-%20How%20to%20Get%20Started%20Testing%20Your%20Code.md)

## 最終プロジェクト：アプリの構築とデプロイ (21)

- ### [最終プロジェクトのセットアップ](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/23.%20%E6%9C%80%E7%B5%82%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%81%AE%E3%82%BB%E3%83%83%E3%83%88%E3%82%A2%E3%83%83%E3%83%97%20-%20Final%20Project%20Setup.md)

- ### [モデルの設計](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/24.%20%E3%83%A2%E3%83%87%E3%83%AB%E3%81%AE%E8%A8%AD%E8%A8%88%20-%20Design%20Your%20Model%20Layer.md)

- ### [Tailwind のテーマのセットアップと最初の UI](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/25.%20Tailwind%20%E3%81%AE%E3%83%86%E3%83%BC%E3%83%9E%E3%81%AE%E3%82%BB%E3%83%83%E3%83%88%E3%82%A2%E3%83%83%E3%83%97%E3%81%A8%E6%9C%80%E5%88%9D%E3%81%AE%20UI%20-%20Tailwind%20Theme%20Setup%20And%20Initial%20UI.md)

- ### [Pest で登録フォームのブラウザテストを行う](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/26.%20Pest%20%E3%81%A7%E7%99%BB%E9%8C%B2%E3%83%95%E3%82%A9%E3%83%BC%E3%83%A0%E3%81%AE%E3%83%96%E3%83%A9%E3%82%A6%E3%82%B6%E3%83%86%E3%82%B9%E3%83%88%E3%82%92%E8%A1%8C%E3%81%86%20-%20Browser%20Testing%20Registration%20Forms%20With%20Pest.md)

- ### [フラッシュメッセージと AlipineJS によるインタラクティビティ](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/27.%20%E3%83%95%E3%83%A9%E3%83%83%E3%82%B7%E3%83%A5%E3%83%A1%E3%83%83%E3%82%BB%E3%83%BC%E3%82%B8%E3%81%A8%20AlipineJS%20%E3%81%AB%E3%82%88%E3%82%8B%E3%82%A4%E3%83%B3%E3%82%BF%E3%83%A9%E3%82%AF%E3%83%86%E3%82%A3%E3%83%93%E3%83%86%E3%82%A3%20-%20Flash%20Messaging%20and%20Interactivity%20with%20AlipineJS.md)

- ### [アイデアカード](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/28.%20%E3%82%A2%E3%82%A4%E3%83%87%E3%82%A2%E3%82%AB%E3%83%BC%E3%83%89%20-%20Idea%20Cards.md)

- ### [アイデアのフィルタリング](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/29.%20%E3%82%A2%E3%82%A4%E3%83%87%E3%82%A2%E3%81%AE%E3%83%95%E3%82%A3%E3%83%AB%E3%82%BF%E3%83%AA%E3%83%B3%E3%82%B0%20-%20Idea%20Filtering.md)

- ### [アイデアの個別表示](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/30.%20%E3%82%A2%E3%82%A4%E3%83%87%E3%82%A2%E3%81%AE%E5%80%8B%E5%88%A5%E8%A1%A8%E7%A4%BA%20-%20Show%20A%20Single%20Idea.md)

- ### [AlpineJS で機能的なモーダルを作成する](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/31.%20AlpineJS%20%E3%81%A7%E6%A9%9F%E8%83%BD%E7%9A%84%E3%81%AA%E3%83%A2%E3%83%BC%E3%83%80%E3%83%AB%E3%82%92%E4%BD%9C%E6%88%90%E3%81%99%E3%82%8B%20-%20Create%20A%20Functional%20Modal%20With%20AlpineJS.md)

- ### [アイデアフォームの構築](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/32.%20%E3%82%A2%E3%82%A4%E3%83%87%E3%82%A2%E3%83%95%E3%82%A9%E3%83%BC%E3%83%A0%E3%81%AE%E6%A7%8B%E7%AF%89%20-%20Construct%20The%20Idea%20Form.md)

- ### [アイデア登録フォームのテスト](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/33.%20%E3%82%A2%E3%82%A4%E3%83%87%E3%82%A2%E7%99%BB%E9%8C%B2%E3%83%95%E3%82%A9%E3%83%BC%E3%83%A0%E3%81%AE%E3%83%86%E3%82%B9%E3%83%88%20-%20Test%20The%20Create%20Idea%20Form.md)

- ### [１つ以上のリンクを登録できるようにする](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/34.%20%EF%BC%91%E3%81%A4%E4%BB%A5%E4%B8%8A%E3%81%AE%E3%83%AA%E3%83%B3%E3%82%AF%E3%82%92%E7%99%BB%E9%8C%B2%E3%81%A7%E3%81%8D%E3%82%8B%E3%82%88%E3%81%86%E3%81%AB%E3%81%99%E3%82%8B%20-%20Allow%20For%20One%20or%20Many%20Links.md)

- ### [具体的手順](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/35.%20%E5%85%B7%E4%BD%93%E7%9A%84%E6%89%8B%E9%A0%86%20-%20Actionable%20Steps.md)

- ### [アイキャッチ画像をストレージにアップロードする](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/36.%20%E3%82%A2%E3%82%A4%E3%82%AD%E3%83%A3%E3%83%83%E3%83%81%E7%94%BB%E5%83%8F%E3%82%92%E3%82%B9%E3%83%88%E3%83%AC%E3%83%BC%E3%82%B8%E3%81%AB%E3%82%A2%E3%83%83%E3%83%97%E3%83%AD%E3%83%BC%E3%83%89%E3%81%99%E3%82%8B%20-%20Upload%20Featured%20Images%20To%20Storage.md)

- ### [アクションクラス](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/37.%20%E3%82%A2%E3%82%AF%E3%82%B7%E3%83%A7%E3%83%B3%E3%82%AF%E3%83%A9%E3%82%B9%20-%20Action%20Classes.md)

- ### [認可は必須要件](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/38.%20%E8%AA%8D%E5%8F%AF%E3%81%AF%E5%BF%85%E9%A0%88%E8%A6%81%E4%BB%B6%20-%20Authorization%20Is%20A%20Requirement.md)

- ### [アイデア編集モーダル](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/39.%20%E3%82%A2%E3%82%A4%E3%83%87%E3%82%A2%E7%B7%A8%E9%9B%86%E3%83%A2%E3%83%BC%E3%83%80%E3%83%AB%20-%20The%20Edit%20Idea%20Modal.md)

- ### [アイデアの更新](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/40.%20%E3%82%A2%E3%82%A4%E3%83%87%E3%82%A2%E3%81%AE%E6%9B%B4%E6%96%B0%20-%20Update%20Idea%20Action.md)

- ### [プロフィールの編集](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/41.%20%E3%83%97%E3%83%AD%E3%83%95%E3%82%A3%E3%83%BC%E3%83%AB%E3%81%AE%E7%B7%A8%E9%9B%86%20-%20Edit%20Your%20Profile.md)

- ### [デプロイと新機能の実装](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/42.%20%E3%83%87%E3%83%97%E3%83%AD%E3%82%A4%E3%81%A8%E6%96%B0%E6%A9%9F%E8%83%BD%E3%81%AE%E5%AE%9F%E8%A3%85%20-%20Deploy%20And%20Then%20Implement%20A%20Feature%20Request.md)

- ### [ここから次のステップ](https://github.com/shibamirai/laravel-from-scratch-2026/blob/main/docs/43.%20%E3%81%93%E3%81%93%E3%81%8B%E3%82%89%E6%AC%A1%E3%81%AE%E3%82%B9%E3%83%86%E3%83%83%E3%83%97%20-%20Where%20To%20Go%20From%20Here.md)
