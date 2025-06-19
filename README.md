## 基本情報

### プロフィール

|項目|値|
|---|---|
|氏名|石川 透（Ishikawa Toru）|
|居住地|東京都杉並区|
|最終学歴|東京理科大学理工学部|

### アカウント

- [GitHub](https://github.com/1shikawa)

## 業務スキル

### 概要

```txt
クラウドアーキテクチャ設計、クラウドインフラ構築管理、CI/CDを含むDevOps推進が現在の専門です。
元々はオンプレミスインフラやWindows系のエンジニアでしたが、現在はLinuxプラットフォームでの開発運用がメインです。
小規模〜中規模サービスの新規開発フェーズやサービスのリプレイスフェーズにおいて価値提供できると考えています。
ユーザーへより良いプロダクトを提供するために、アジリティ高くフィードバックサイクルを回していける仕組み作りに取り組んできました。
そのためにクラウドのマネージドサービスや周辺エコシステムを活用することで、開発プロセスの自動化や省力化を推進し、サービス開発や運用効率化に貢献できると思います。
```

## 技術スキル

実業務で使用した技術のみ列挙します。

### インフラ

`AWS` `VPC` `S3` `CloudFront` `Lambda` `ELB` `EC2` `EFS` `ECR` `ECS` `Fargate` `EKS(Kubernetes)` `App Runner` `Route53` `ACM` `IAM` `RDS(MySQL|PostgreSQL)` `Aurora` `Aurora Serverless V2` `DynamoDB` `Kinesis firehose` `SQS` `SNS` `SES` `Chatbot` `CloudFormation` `CloudWatch` `SSM` `EventBridge` `Backup` `CloudTrail` `Config` `GuardDuty` `Security Hub` `KMS` `Secrets Manager` `Parameter Store` `Athena(Glue)` `VPC Peering` `VPC Lattice` `Google Cloud` `VPC` `GCS` `Cloud Functions` `GCE` `GKE(Kubernetes)` `Cloud Run` `GCLB` `IAP` `IAM` `Cloud SQL` `Cloud Pub/Sub` `Cloud NAT` `Cloud Armor` `Dataflow(Apache Beam)` `Cloud Build` `Cloud Deploy` `Artifact Registry` `Logging` `Monitoring` `OpenStack` `VMware`

### IaC、構成管理

`Terraform` `AWS CloudFormation` `AWS CDK` `Helm` `Helmfile` `Kustomize` `Ansible` `Chef`

### CI/CD

`GitHub Actions` `GitLab CI/CD` `Cloud Build` `Cloud Deploy` `ArgoCD` `Screwdriver` `Ansible AWX`

### モニタリング、オブザーバビリティ

`Prometheus` `Grafana` `New Relic` `Amazon CloudWatch` `Cloud Operations` `ELK (Elasticsearch,Logstash,Kibana)` `Fluentd` `Fluent Bit` `Zabbix` `Trivy` `Yamory` `Redash`

### 開発言語、フレームワーク等

`Python(Flask,Django)` `Go(Gin)` `TypeScript(CDK)` `Bash Script` `SQL`

### DB

`MySQL` `PostgreSQL` `Oracle` `SQL Server` `SAS` `MongoDB Atlas`

### 開発ツール

`GitHub` `GitLab` `Docker` `Kubernetes(k9s,krew)` `LocalStack` `Artifactory`

### コミュニケーション

`Jira` `Confluence` `Notion` `Miro` `Slack` `Mattermost` `Chatwork` `Zoom` `Gather`

## 補足資料

[アーキテクチャ概要](https://github.com/1shikawa/my-resume/blob/master/docs/Architecture.md)

## 経歴

### フリーランス（2022/03〜現在）

```txt
フリーランスエンジニアとして、複数のプロジェクトでインフラエンジニア/DevOps/SREの役割を担当。
クラウドネイティブアーキテクチャの設計構築、CI/CDパイプラインの構築、IaCによる運用改善などを推進。
```

以下では参画したプロジェクトの内、主要なもののみを記載します。

#### 物流業向けDXプラットフォームの開発、運用（2024/10〜現在）

**概要**

SREとして、クラウドネイティブベースの既存プラットフォーム開発運用業務に従事。

**担当**

1. AWS CDKによるインフラ環境のコード化と運用改善
2. EKSおよびカスタムコントローラーのバージョンアップ対応
3. ALB・EKSにおけるブルー・グリーン環境構築

**業務内容**

1. SREチームでの1メンバーとして参画
2. 週2副(兼)業での参画

**使用技術**

- インフラ：`AWS`

#### 建設業向けDXプラットフォームの開発、運用（2024/05〜現在）

**概要**

インフラエンジニア(DevOps/SRE)として、クラウドネイティブベースの既存プラットフォーム開発運用業務に従事。

**担当**

1. インフラをメインとした要件定義、機能検討・調査、設計、実装、テスト、レビュー
2. Terraformによる全インフラ環境のコード化と運用改善
3. CI/CDパイプラインの改善
4. MongoDB AtlasのEOL対応

**業務内容**

1. Cloud Run Jobs、driftctlによる構成ドリフト検出と定期通知の導入
2. plan、applyの並行実行化による処理時間短縮
3. tfcmtによるplan結果のPRコメント自動追加とレビュアーの負荷軽減
4. tfnotifyによるapply結果のSlack通知
5. 全インフラ環境への自動デプロイフロー構築
6. MongoDB AtlasのEOL(メジャーバージョンアップ)対応
7. テスト環境構築(Cloud Run、Dataflow)とE2Eテスト対応
8. GitHub ActionsとWorkload Identity連携環境構築
9. OpenAPIドキュメントの自動更新による運用効率化

**使用技術**

- インフラ：`Google Cloud`
- チーム規模：8人チームでのアジャイル(スクラム)開発（PO、SM、バックエンドDev、フロントエンドDev、インフラ/SRE、QA）

#### 会計系全社統合マスター管理サービスの新規開発（2023/01〜2024/04）

**概要**

インフラエンジニア(DevOps/SRE)として、クラウドネイティブベースの新規プロダクト開発業務に従事。

**担当**

1. インフラをメインとした要件定義、機能検討・調査、設計、実装、テスト、レビュー
2. Terraformによる全インフラ環境のコード化と運用定着化
3. CI/CD基盤構築と運用管理
4. イベント駆動アーキテクチャの導入
5. オブザーバビリティ環境構築

**業務内容**

1. AWS EKSとGitHub Actions Runner Controllerを利用したCI/CD基盤構築と運用管理
2. ブランチ戦略に基づいたGitHub ActionsによるCI/CDパイプラインの設計構築と各種運用自動化
3. アプリのビルド・テスト、コンテナイメージ作成、DBマイグレーション、ECSタスクローリングアップデート、ドキュメント更新等
4. dev/stg/prod環境へ適宜手動・自動デプロイしリリース可能な仕組みを確立
5. SQS、Lambda、S3、DynamoDB、SNSを利用したPub/Subファンアウト構成
6. AWS(ECS/CloudWatch)とNew Relicのインテグレーションとオブザーバビリティ環境構築
7. アプリコンテナへのAPMエージェント組込み、各種メトリクスやログの転送と集約
8. NRQLによる閾値アラートルールとSlackチャンネルへの通知設定
9. 稼働状況モニタリングのためのダッシュボード作成
10. New Relic APMを活用したボトルネック探索とレイテンシー改善のための取組み
11. ECSスタンドアロンタスクを活用した踏み台、ポートフォワーディング、バッチコンテナ環境構築
12. Fargate SPOTや夜間の自動スケールイン機能のスケジュール実行によるコスト最適化
13. SLI/SLO達成のための負荷試験によるFargateタスクの必要スペックと常時起動数の算出とスケーリング設定
14. セキュリティやレイテンシーを考慮したクロスアカウントアクセスの導入
15. VPCピアリング、WAF、内部ALB/NLB、VPCエンドポイント(PrivateLink)、最小権限のAssumeロール
16. DRを想定したデータソースのリージョン間定期バックアップとレプリケーション設定
17. Golang(Gin)による他サービスを模したモックAPI作成とコンテナ化、App Runnerへの自動デプロイとテストスクリプト作成実行

**使用技術**

- インフラ：`AWS`
- Kubernetes：`GitHub Actions Runner Controller` `New Relic Kubernetes integration`
- チーム規模：6人チームでのアジャイル(スクラム)開発（PO/SM、TL、バックエンドDev、インフラDev、QA）
- その他：インフラ(SRE)領域のリーディングとペア・モブプロによるDevメンバーへの展開、アジャイル(スクラム)開発未経験メンバーへのマインドセットや知見共有

**発揮したバリュー**

ローカル開発環境の整備やインフラのコード化、CI/CDパイプラインの構築など、作業フローの効率化と各種自動化作業等に大きく貢献。予定していた本番商用リリースもほぼトラブル無く完遂。モダンな技術スタックの選定による開発者体験(DX)の向上施策を推進。

#### クラウドインフラをベースとしたCI/CD環境構築とDevOps推進支援（2022/03〜2022/12）

**概要**

DevOpsエンジニアとしてクラウドネイティブベースの開発、本番環境の構築運用業務に従事。

**担当**

1. インフラをメインとした要件定義、機能検討・調査、設計、実装、テスト、レビュー
2. Terraformによるインフラのコード化
3. CI/CD基盤構築と運用
4. モニタリング・ロギング基盤構築

**業務内容**

1. Terraformによるインフラのコード化とCI(tfint,tfsec)実装
2. GitLab CI、ArgoCDによるCI/CD基盤構築と運用
3. Prometheus、Alertmanager、Grafanaによるモニタリング基盤構築
4. Promtail、Loki、Grafana、FruentBit、CloudWatchによるロギング基盤構築
5. Kubernetes(EKS)クラスター構築と開発スクラムチームへの展開
6. アプリケーション構成に基づいたManifest作成と管理、CI(Kubeconform,Polaris)実装
7. DevSecOps（シフトレフト）を意識したGitOpsスタイルのCI/CDパイプライン構築
8. Golang(Gin)による技術検証およびデモ用Webapp、API作成とコンテナ化

**使用技術**

- インフラ：`AWS`
- Kubernetes：`ALB Controller` `External DNS` `External Secrets` `GitLab Runner` `ArgoCD` `Kube-prometheus-stack` `Loki-stack` `Redash` `Velero`
- チーム規模：平均3〜5人チームでのアジャイル(スクラム)開発（PO/SM、インフラDev）
- その他：DevOps推進活動のリード（課題抽出整理、スケジューリング、タスク実行）、チーム内外に対するCI/CD勉強会の主催、ハンズオン及びQA対応

**発揮したバリュー**

GitLab CIやArgoCDについては未経験であったが、機能を速習することで短期間でキャッチアップ。CI/CD環境整備とチーム内外に対するDevSecOps導入推進を主導し、自動化による開発プロセスの改善や開発生産性向上に貢献。また開発プロセス中に脆弱性チェックなどを組み込むことで継続的なセキュリティ対応にも貢献。

### ヤフー株式会社（2021/04〜2022/03）

```txt
DevOpsエンジニアとして、プライベートクラウド基盤ベースの全社成果物管理プラットフォームの開発・運用保守業務に従事。
```

以下では参画したプロジェクトの内、主要なもののみを記載します。

#### 全社成果物管理プラットフォームの開発、運用管理（2021/04〜2022/03）

**概要**

プライベートクラウド基盤ベースの全社成果物管理プラットフォームの開発・運用保守業務。

**担当**

1. 機能検討・調査、設計、実装、テスト、レビュー
2. Terraformによるインフラのコード化
3. DC移転対応

**業務内容**

1. Terraformによる成果物プラットフォームインフラのコード化
2. AnsibleによるVMインスタンスの構成管理
3. DC移転に伴う成果物プラットフォーム移行対応
4. 他部署からのQA対応

**使用技術**

- インフラ：`OpenStack` `Artifactory` `Terraform` `Docker-compose` `MySQL` `PostgreSQL` `Ansible` `Chef` `Screwdriver(CI)` `AWS S3`
- チーム規模：平均4〜6人チームでのスクラム開発（PO、SM、バックエンドDev、インフラDev）

**発揮したバリュー**

DC移転に伴う新環境構築と移行対応により事業継続性とコスト削減に貢献。

### GMOグローバルサイン・ホールディングス株式会社（2016/05〜2021/03）

```txt
コーポレートエンジニアとして、オンプレミスベースの基幹系業務システムや周辺システムの開発、運用保守業務に従事。
```

以下では参画したプロジェクトの内、主要なもののみを記載します。

#### 基幹系業務システム及び周辺システムの開発、運用管理（2016/05〜2021/03）

**概要**

オンプレミスベースの基幹系業務システムや周辺システムの開発、運用保守業務。

**担当**

1. 要件定義、機能検討・調査、設計、実装、テスト、レビュー、ベンダー管理等
2. 業務効率化のためのWebアプリ開発
3. CI/CD環境構築と自動化

**業務内容**

1. 経理関連業務効率化を図るPython、DjangoによるWebアプリ開発
2. 基幹業務システムと電子契約サービスとの連携機能開発（Asteria、Oracle、MySQL）
3. Ansible/AWXによるCI/CD環境構築と定期メンテナンス作業やデプロイの自動化
4. ElasticStack(ElasticSearch、Kibana、Filebeat)によるログ統合管理基盤構築
5. 在庫管理システムリニューアルに伴う運用保守設計とバックアップ、監視基盤の構築
6. 基幹業務システムのバージョンアップに伴う影響調査分析と実行計画、ベンダー管理
7. 基幹業務システムや周辺システムの運用保守とヘルプデスク対応

**使用技術**

- インフラ：`Windows Server` `Linux` `VMWare` `Python` `Django` `Bash Script` `Java` `Tomcat` `Weblogic` `Docker` `MySQL` `PostgreSQL` `Oracle` `SQL Server` `Ansible` `ElasticSearch` `Zabbix` `Asteria` `Kintone`
- チーム規模：平均3〜15人チームでのウォーターフォール開発
- その他：TCO削減につながる施策の提案と実行、既存業務の自動化推進を主導

**発揮したバリュー**

電子契約サービスの利用顧客増加による売上拡大に貢献。既存業務の自動化による属人化解消とオペミス削減、省力化に貢献。管理対象システム情報を自動同期するシステムを構築し、運用保守業務効率化に貢献。

### 富士ゼロックス株式会社（2005/04〜2015/11）

```txt
顧客対応システムエンジニアとして、様々な業界業種のお客様向けにオンプレミスベースのシステム提案・開発運用業務に従事。
```

以下では参画したプロジェクトの内、主要なもののみを記載します。

#### 自社他社ソフトウェア、ハードウェアをベースとした顧客向けシステム提案、開発（2005/04〜2015/11）

**概要**

様々な業界業種のお客様向けにオンプレミスベースのシステム提案・開発運用業務。

**担当**

1. 要件定義、機能検討・調査、設計、実装、テスト、レビュー、ベンダー管理等
2. 各種システムの開発と運用

**業務内容**

1. 病院向け診療記録管理システムの開発、運用
2. 中央省庁向け統計調査システムの開発、運用
3. 中央省庁向け調査研究に伴うWebシステム開発、運用
4. 総合電機メーカー向け設計業務管理システムの開発、運用
5. 銀行向け融資情報管理システムの開発、運用
6. 製造業・流通業向け図書管理システムの開発、運用

**使用技術**

- インフラ：`Windows Server` `VMWare` `Java` `Tomcat` `Seasar` `VBA` `Oracle` `MySQL` `PostgreSQL` `SAS` `自社ソフト`
- チーム規模：平均3〜20人チームでのウォーターフォール開発
- その他：体系的知識を向上させるため積極的に資格を取得（Oracle、MCP、IPA関連）

**発揮したバリュー**

ステークホルダー間調整や情報共有を心がけ、手戻りによるスケジュール遅延を防ぎ納期を遵守。顧客にシステム導入効果や満足度を実感頂き、次案件の継続受注に貢献。

## 意欲・興味

- バックエンド・クラウドインフラの新しい技術への興味関心が高く、今後も専門性を深めたいと考えています
- 比較的規模の大きいサービスメッシュ構成などのマイクロサービス基盤構築と運用に興味があります
- 用途に応じて複数のパブリッククラウドを組み合わせるマルチクラウドに興味があります
- Golangによるバックエンドや基盤コード開発力を向上させたいと思っています
