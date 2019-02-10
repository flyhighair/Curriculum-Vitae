# 職務経歴書

## 基本情報

|key|value|
|---|-----|
|Name|白秋(hakshu)|
|Twitter|[@fly_highup_air](https://twitter.com/fly_highup_air)|
|Qiita|[hakshu](https://qiita.com/hakshu)|

---

## スキル

### 言語

- **JavaScript**
- **TypeScript**
- **Node.js**
- **Kotlin**
- **Java 8**
- C++
- C#
- Ruby

※太字のものは3ヶ月以上の業務経験があります。

### フレームワーク

- [Express](https://expressjs.com/)

  Node.jsフレームワーク。AndroidアプリのAPIサーバー実装やWebアプリケーションに使用。

- [Meteor](https://www.meteor.com/)

  Node.jsフレームワーク。[Rocket.Chat](https://rocket.chat/)というSlackライクのチャットシステムOSSをカスタマイズ利用した受託開発で使用。

- [Bot Builder](https://github.com/Microsoft/BotBuilder)

  Bot開発用フレームワーク。言語はJavaScriptを使用。

- [Vaadin](https://vaadin.com/)

  Webアプリケーション向けJavaフレームワーク。医療データ管理画面開発で使用。

- [React Native](https://facebook.github.io/react-native/)

  JavaScriptハイブリッドアプリケーション向けフレームワーク。チャットシステムのクライアント組み込み用アプリケーションに使用。

- Jest
- Mocha

### 自動化ツール

- CircleCI

### DB

- MySQL
- MongoDB
- Microsoft SQL Server
- SQLite

### パブリッククラウド

- Microsoft Azure
  - Azure Functions
  - Azure SQL Database
  - App Service
  - Storage

- AWS
  - Amazon Elastic Container Service
  - ECR
  - Amazon EC2
  - Amazon RDS(Aurora)
  - AWS Lambda
  - Amazon CloudWatch
  - Amazon S3
  - Amazon Simple Notification Service
  - Amazon Simple Email Service
  - Elastic Load Balancing

## 資格

- 認定スクラムマスター
  - 資格取得後、自分含めエンジニア2名・デザイナー2名のチャットボット開発チームでの3ヶ月間のスクラムマスター経験があります。
- 応用情報技術者
- HTML5 プロフェッショナル認定試験レベル1・2
- Oracle Certified Java Programmer, Silver SE 8
- 小学校教諭1種免許

## 受賞歴

- Pepper App Challenge2017 東日本予選 Motionboard賞

### その他

- 社内発表経験
  - 社外での登壇歴はありませんが、社内での発表経験が複数回あります。
- スクラム開発経験
  - 1年のスクラム開発経験があります。
- 社内SE経験
- PowerAppsアプリケーション開発経験
- Sketch・Prottでのスマートフォンアプリケーションの画面デザイン・設計経験あり
- HoloLens向けデモアプリケーション開発経験あり
- Amazon Echoアプリケーション開発経験あり

## 強み

- クラウド環境の設計からフロントエンド・サーバーサイドまで一通りの開発経験があります。
- 10数個の不具合を出したプロジェクトの炎上時にお客様からのクレームを一手に引き受けた経験や、一人での複数プロジェクト開発経験から、お客様との渉外力はついていると思います。
- 複数プロジェクトを1人で並行開発した経験や、プロジェクト開発と社内SEの兼任など並行タスクの処理能力があります。
- 興味を持った技術は躊躇せず、実際に触るようにしています。

## やったことはないが興味があるもの

- B to Cのサービス開発
- EdTech

## 職務経歴

### 2017/04 - 現在: ヘルスケア・医療向けアプリケーション受託開発の中小企業

職務: フルスタックエンジニア(Webメイン)・社内SE

---
#### 社内デモ向けVUIチャットボットアプリケーション

##### 概要

- お客様が社内で音声チャットボットの開発研究を進めるためのデモ向けアプリケーションとして、プロトタイプ実装を行いました。
- 要件定義、インフラ設計から行い、当日のデモサポートまで一通り担当しました。

##### 担当業務

- スクラムマスター・開発チームリーダー
- インフラ設計
- 技術調査・選定
- 要件定義・基本設計・詳細設計
- 実装・テスト
- デモサポート

##### 採用技術

- 開発言語はサーバーサイドでNode.js、フレームワークはExpress.js・Microsoft Bot Framework、DBにAzure SQL Database、画像ストレージにAzure Storage、アプリ基盤として、Azure FunctionsとAzure WebAppsを使用。 チャットボットの自然言語処理にMicrosoft Cognitive ServiceのLUISを利用。LUISの解析結果分析のため、PowerBIを使用。
後述にはなりますが、開発途中でクライアントのハードをAndroidに切り替えたため、言語にKotlin、音声認識にAndroid Speech Recognizer、音声発話にAzure Cognitive ServicesのText to Speechを使用。

##### 開発について

- 3ヶ月*2回のスクラム開発を行い、前半はAmazon Echoのアプリケーションとして開発、後半はAndroidアプリケーションとして開発しました。
- 前半と後半でクライアントのハードを変更していますが、スクラム開発の性質上、ボットのロジックをサーバーサイドに集約するよう設計・実装していたため、手戻りなく開発を進行しました。
- スクラム開発は社内でも3事例目であり、自身もスクラムマスターとして開発に参加するのは、初めてだったため、開発2ヶ月目ごろでScrum Inc.の認定スクラムマスター研修に参加し、認定を取得しました。
- プロトタイプ完成の1ヶ月後にお客様社内で発表を行った。特にトラブルもなく、今後の事業化へとつながりました。

---
#### 医療従事者向け患者情報管理画面システム開発

##### 概要

- スマートフォンアプリケーションで記録された日々の計測結果(血圧、体重等)の管理画面及び管理画面を閲覧する医療従事者が情報共有・記録するためのチャットシステムをWebアプリケーションとして構築しました。

##### 担当業務

- 基本設計・詳細設計
- 実装・テスト・リリース
- 運用保守

##### 採用技術

- 管理画面は開発言語にJava8、フレームワークはVaadin、DBにAWS Aurora、アプリケーションサーバーにJavaEEのWildflyを使用した。チャットシステムは開発言語にNode.js、フレームワークにMeteor、チャット基盤にOSSの、Rocket.Chat、DBにMongoDBを使用。インフラとして、AWSを使用し、アプリケーションはAWS ECSを使用したDockerコンテナでAWS EC2上に構築した。
CI環境として、CircleCIを使用し、AWS ECRへDockerイメージの自動デプロイを行った。
