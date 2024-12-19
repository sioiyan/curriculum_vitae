# オープン職務履歴書

- [プロフィール](#プロフィール)
  - [自己紹介](#自己紹介)
- [技術スタック](#技術スタック)
- [関わった案件](#関わった開発案件)

## プロフィール
key|value  
--|--
Name|山下浩志
Birth|1995/02/22
Location|京都市 中京区
Education|国立大学卒
Job|[FLINTERS](https://www.flinters.co.jp/) の開発者
Mail|[sioiyan3456@gmail.com](mailto:sioiyan3456@gmail.com)
Github|[sioiyan](https://github.com/sioiyan)

### 自己紹介
新卒でFLINTERSに入社して、今現在も同社でWebアプリケーションの開発を約5年ほど行っています。

同社ではドメイン駆動設計とスクラムを開発に取り入れているため、仕様の決まりきった物をそのまま作る作業的な開発よりも、
プロダクトマネージャーと密にコミュニケーションを取りながらより価値の高いものを共に作り上げていけるような開発を得意としています。
（直近でアサインされたプロジェクトではウォーターフォール開発で進めたのでそういう開発ができないわけではないです。）

プロジェクトで利用してきた言語は主に、フロントエンドはTypescript (Next.js, Nuxt.js(Composition API))、バックエンドはScalaです。
kubernetesやterraform等のインフラ系も多少触れます。

## 技術スタック
言語|備考
--|--
Scala|5年／バックエンド開発では一番利用した。機能実装は問題なくできます。
Python|2年／学生時代に機械学習で利用し、趣味で競技プログラミングをやっていた頃に利用していた。業務ではAirflowの処理を記述するDAGファイルを実装するのに利用しました。
TypeScript|5年／過去にアサインされてきたプロジェクトすべてにおいて利用してきた。1からシステムを実装することができるレベルで習得しました。
C言語|4年／業務では使っていませんが学生時代に課題提出用に必要だったため利用しました。4年の時には4ヶ月ほどでMPPLで記述されたコードをCASLIIのコードに変換するコンパイラを実装しました。

フレームワーク|備考
--|--  
Next.js|4年／直近のプロジェクト以外で使用しました。フロントエンドの機能実装タスクを手広く担当した。
Nuxt.js|6ヶ月／直近のプロジェクトで使用しました。Nuxt 2以前はさわっておらず、Nuxt 3から触りました。フロントエンドの実装をメインで担当。
Relay|2.5年／フロントエンド開発に使用しました。GraphQLを採用しているバックエンドに対応する形で利用
Caliban(GraphQL)|2.5年／バックエンド開発に使用しました。GraphQLの性質を生かして必要なデータだけを返せるのでフロントエンドとのやりとりするデータ量を減らすのに貢献


インフラ周り|備考
--|--
RDB|5年／PostgreSQLを利用してきた。複雑なクエリの実装経験あります。DB設計も一応できます。パフォーマンスチューニング等まではやっていません。
NoSQL|数ヶ月／試験的にGoogle Cloud Datastoreを利用したが、複雑なWHERE句を書きたいモチベーションがあり、RDBに移行した。
AWS|数ヶ月／直近のプロジェクトで使用。構築は他のエンジニアがやったためあまり詳しくはない。
利用したサービス: CloudFront, S3, Lambda, Athena
GCP|5年／過去のプロジェクトで運用経験あり。一時期Professional Arcitect等の資格を取得していた。
よく使っていたサービス: Cloud Run, Cloud SQL, GKE, GCS, BigQuery, Cloud Armor, Logging, Cloud Composer, Secret Manager, GCE
Docker|5年／デプロイ用のイメージ作成や開発用のコンテナを利用した。
Terraform|5年／関わってきたプロジェクトすべてで利用してきた。1から構築はしていないが修正対応はできます。
kubernetes|1年／GKEのリソース配分の調整等のタスクを行った。1から構築はしていない。

その他の技術スタック|備考
--|--
設計手法|5年／DDD(ドメイン駆動設計)
digdag|2.5年／最初のプロジェクトでETL処理を行うのに使用していた。
Confluence|3年／プロジェクト用のドキュメントを管理するのに使用していた。
Jira|半年／プロジェクトのチケット管理に使用しました。
GitHub Boards|4.5年／プロジェクトのチケット管理に使用しました。
GitLab, GitHub|5年／バージョン管理に使用しました。
Slack|5年／チーム内の連絡に使用しました。
Miro|5年／MTG時のアイデア出しやドメインモデリング時に使用しました。
IntelliJ|4.5年／開発で使用しました。
VSCode|半年／開発で使用しました。DevContainerが非常に便利だった。

## 関わった案件
### 広告クリエイティブ特化のソリューションツールの開発
- 期間:2020年7月 ~ 2021年5月, 2021年7月 ~ 2022年5月
  - Scala, AkkaStreamを用いた各種広告データ取得アプリの修正
  - digdagを利用したETL処理の開発
  - PostgreSQLを用いて新規テーブル作成・既存テーブル修正と既存クエリの改変を行いレポートデータに新項目の追加
    - ドメインモデリングしてドメインの変更・テーブルの変更を行った。
  - KubernetesのPodのリソース振り分け修正
  - Next.jsによるUIコンポーネントの微修正
  - レポートデータの数値の乖離やETLの遅延の調査・修正対応
  - 各種広告API(LINE, Google, Yahoo, Twitter, Facebook)の変更点の調査・修正対応

### 新卒の教育
- 期間: 2021年5月~2021年6月
  - 開発しているアプリの研修ではなく各チームに配属される前の新卒の教育補佐を行った。
  - 補佐役としてレビュワーや新卒メンバーの質問対応を行った。
  - また一部研修の資料作成・説明も行った。

### AIを活用したマーケティングソリューションツールの開発
- 期間: 2022年5月 ~ 2024年7月
  - AirflowによるレポートデータやAIによる予測結果データの取り込み
  - Next.js, Relayによるレポートデータ・予測結果データを閲覧できる画面の作成
  - Scala, Caliban, PostgreSQLによる各種データをDBから取得するAPIアプリの作成
  - UIコンポーネントの共通化
  - React Hook Form や zod を利用した検索広告の予測分析画面の実装
  - ディスプレイ広告のレポート画面・予測画面の実装
    - 開発当初figmaによる画面イメージが存在しなかったためPMとこまめに話し合いながら必要な機能について確認し、なるべく手戻りが起きないように実装を行った。
  - 検収用のドキュメント作成
  - チームメンバーと話し合ってディスプレイ広告周りのドメインモデルの見直しを行った。これにより統廃合されたドメインがあり適宜修正した。

### アンケートデータの分析ツール
- 期間: 2024年8月 ~ 2024年12月
  - Nuxt.js を用いたSPA開発
  - 仕様が開発しながら決まっていくプロジェクトだったので、PMや他の開発者と密な連携をとりながらタスクの手戻りが起きないように進めた。
  - 当初、既存のアプリケーションのコンポーネントを流用する予定だったが「Typescriptで描かれているがany型が多用」
「使われ方の異なる複数の場面に対応するように共通化されたコンポーネント（オプショナルなProps多数）」
「ライブラリにあまり頼らないフルスクラッチな実装多数」となっており
流用が難しい箇所が多数存在したため、それらは上記で挙げた問題を解消した上で自分で1から作成した。