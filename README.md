[English](README.en.md) | 日本語

職務経歴書
======

**[GitHub Pages](https://daichimorihara.github.io/resume/)からもご覧いただけます。**

基本情報
-------
|項目|内容|
|---|-----|
|氏名|森原 大地(もりはら だいち)|
|生年月日|1998年8月|
|居住地|大阪|
|最終学歴|大阪大学工学部 応用理工学科|
|資格|AWS認定ソリューションアーキテクト-アソシエイト、TOEIC L&R: 935|

<br>

職務経歴
-------
### 株式会社ニーリー
【期間】2024/03 - 現在
【事業内容】月極駐車場SaaS  

#### 所属・役職
- 2024/09 - 現在: プロダクト開発本部 プラットフォームグループ SRE
- 2024/03 - 2024/08: プロダクト開発本部 プラットフォームグループ SRE（インターン）


#### 主なプロジェクト

|プロジェクト|使用技術|概要|
|----|----|--------|
|Amazon ConnectのGUI開発とIaCの両立|Github Actions, AWS(Amazon Connect, EventBridge, Step Functions, S3), Terraform|Amazon ConnectのGUI開発の利便性とIaCによる安定したリソース管理・リリースの両方の恩恵を享受するためのシステムを構築した。|
|Datadogのログコスト削減|Datadog|環境ごとに最適な保持期間のインデックスログの設定と一部ログをインデックス対象外にすることで70％のコスト削減に成功した。|
|一部フロントエンドをEC2からS3への移行|Github Actions, AWS(Code Pipeline, S3, CloudFront)|複数のアプリが同一EC2にホストされており、リリースに制約があった。これを改善するためにSPAをS3＋CloudFrontに移行させた。また移行に伴うCICDの整備も実施。|
|バッチの監視改善|AWS(Step Functions, ECS, EventBridge, Lambda)、Datadog|バッチ失敗時の自動再実行の設定、バッチのインフラ監視改善と、APM導入の導入を行なった。|
|バックエンドのリアーキテクチャ|Github Actions, Django, Nginx, Docker, Gunicorn, AWS(ECS, ALB, VPC), Datadog, Terraform|バックエンドのホスト先をElastic Beanstalk→ECSへの移行をメインとしつつ、AWS Networkの整備、Nignx＋Gunicornの導入、アプリのログ整備、リソースのIaC化、CICDの整備、メンテナンスモードの導入などを行った。|
|バックエンドCDの速度改善|Github Actions, Docker|CD内でのDocker Imageのビルド方法とキャッシュ保存方法を改善し、CDの実行時間を10分(50%)短縮させた。|
|RPA用のWindowsサーバー構築|AWS(EC2, Patch Manager, CloudWatch Logs, Athena, EventBridge), Datadog|RPAを実行するための仮想環境を構築した。監査向上のためにWindowsログの集積とPatch Managerによる自動定期パッチを導入した。|
|主要データのマルチアカウントバックアップ|Github Actions, AWS(CodeCommit, RDS, S3, AWS Backup)|強固なセキュリティをかけたバックアップ用AWSアカウントを作成し、そこにGithubのソースコード・RDS・S3のバックアップを保管。既存データの一括送信の実施および新規データの同期を行う仕組みを構築した。|
|feature環境構築の自動化・整備|Github Actions, AWS(RDS, Step Functions, SNS, S3, Amplify, CloudFront, ALB, Amazon Q, Route53), Nginx|feature環境のfrontend・DBを自動で作成できる仕組みを構築した。GithubのPRに付与するラベルでfeature環境を制御することで開発者体験を高めつつ、コストを抑える仕組みを構築した。|


<br>


執筆記事
-------
|日付|記事|
|---|---|
|2025/08|[Amazon ConnectのGUI開発体験を維持しつつ、Terraformで安全にリリースするハイブリッドIaC戦略](https://nealle-dev.hatenablog.com/entry/2025/08/28/102131)|
|2025/08|[Datadogのコスト最適化〜ログのコストを70%削減した話〜](https://nealle-dev.hatenablog.com/entry/2025/08/18/131030)|
|2025/06|[バッチ監視改善 ~手動再実行のトイル削減とNAT gatewayコスト急増の失敗談付き〜](https://nealle-dev.hatenablog.com/entry/2025/06/27/104521)|
|2025/06|[Amazon Auroraのエンドポイントを変えずにKMSキーを交換する方法](https://nealle-dev.hatenablog.com/entry/2025/06/24/154358)|
|2025/04|[S3 + CloudFront構成のSPAでWAFによるブロックが効かないときの解決策](https://nealle-dev.hatenablog.com/entry/2025/04/22/114803)|
|2024/12|[インフラから、社会にプラスの影響を与えるプロダクトを支えたい　～エンジニアインターンでの直感を信じて入社～](https://note.nealle.com/n/nb3c46aa0f7a2)|
|2024/12|[コストと開発体験を両立させるfeature環境の運用方法](https://nealle-dev.hatenablog.com/entry/2024/12/20/01)|
|2024/11|[KPI集計のために秒単位の正確性でAuroraのスナップショットを作成する仕組みを構築した話](https://nealle-dev.hatenablog.com/entry/2024/11/05/100031)|

