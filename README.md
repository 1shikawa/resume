# 職務経歴書

## 基本情報

| 項目     | 内容 |
| -------- | ------------- |
| 氏名     | 石川 透（Ishikawa Toru）|
| 居住地   | 東京都杉並区 |
| 最終学歴 | 東京理科大学理工学部 |
| GitHub   | <a href="https://github.com/1shikawa/my-resume" target="_blank"><img alt="Github" src="https://img.shields.io/badge/1shikawa-%2312100E.svg?&style=flat-square&logo=Github&logoColor=white" /></a> |

## 概要

- クラウドアーキテクチャ設計、クラウドインフラ構築管理、CI/CDを含むDevOps推進が現在の専門です
(元々はオンプレミスインフラやWindows系のエンジニアでしたが、現在はLinuxプラットフォームでの開発運用がメインです)
- 小規模〜中規模サービスの新規開発フェーズやサービスのリプレイスフェーズにおいて価値提供できると考えています
ユーザーへより良いプロダクトを提供するために、アジリティ高くフィードバックサイクルを回していける仕組み作りに取り組んできました
そのためにクラウドのマネージドサービスや周辺エコシステムを活用することで、開発プロセスの自動化や省力化を推進し、サービス開発や運用効率化に貢献できると思います

## 保有スキル

実務経験のある技術やツールなどを記載しています。

| カテゴリ           | 技術スタック                                                 | 主な役割/担当業務                                                             |
| ------------------ | ------------------------------------------------------------- | ----------------------------------------------------------------------- |
| インフラ           | AWS <br>(VPC \| S3 \| CloudFront \| Lambda \| ELB \| EC2 \| EFS \| ECR \| ECS \| Fargate \| EKS(Kubernetes) \| App Runner \| Route53 \| ACM \| IAM \| RDS(MySQL\|PostgreSQL) \| Aurora \| Aurora Serverless V2 \| DynamoDB \| Kinesis firehose \| SQS \| SNS \| SES \| Chatbot \| CloudFormation \| CloudWatch \| SSM \| EventBridge \| Backup \| CloudTrail \| Config \| GuardDuty \| Security Hub \| KMS \| Secrets Manager \| Parameter Store \| Athena(Glue) \| VPC Peering \| VPC Lattice)<br>Google Cloud <br>(VPC \| GCS \| Cloud Functions \| GCE \| GKE(Kubernetes) \| Cloud Run \| GCLB \| IAP \| IAM \| Cloud SQL \| Cloud Pub/Sub \| Cloud NAT \| Cloud Armor \| Dataflow(Apache Beam) \| Cloud Build \| Cloud Deploy \| Artifact Registory \| Logging \| Monitoring) <br>OpenStack \| VMware               | クラウドアーキテクチャ設計<br>クラウドインフラ構築・運用管理<br>新規サービスの調査検証と選定導入 |
| IaC、構成管理 | Terraform \| AWS CloudFormation \| AWS CDK \| Helm \| Helmfile \| Kustomize \| Ansible \| Chef | dev/stg/prod環境の構築と切り分け管理<br>インフラリソースの構成管理と標準化 |
| CI/CD | GitHub Actions \| GitLab CI/CD \| Cloud Build \| Cloud Deploy \| ArgoCD \| Screwdriver \| Ansible AWX | Self Hosted RunnerによるCI/CD基盤の構築<br>CI/CDパイプラインの設計・構築・運用<br>CIOpsやGitOpsの展開|
| モニタリング、オブザーバビリティ | Prometheus \| Grafana \| New Relic \| Amazon CloudWatch \| Cloud Operations \| ELK (Elasticsearch,Logstash,Kibana) \| Fluentd \| Fluent Bit \| Zabbix \| Trivy \| Yamory \| Redash | 監視環境の設計・構築<br>ログ収集と分析基盤の構築<br>インシデント対応とアラート運用 |
| 開発言語、フレームワーク等 | Python(Flask,Django) \| Go(Gin) \| TypeScript(CDK) \| Bash Script \| SQL | 自動化スクリプト作成・運用<br>バッチアプリやWebAPI作成 |
| DB | MySQL \| PostgreSQL \| Oracle \| SQL Server \| SAS \| MongoDB Atlas | データベース設計構築<br>バックアップ運用管理<br>EOL(バージョンアップ)対応 |
| 開発ツール | GitHub \| GitLab \| Docker \| Kubernetes(k9s,krew) \| LocalStack \| Artifactory | Dockerfile作成によるコンテナ化<br>Manifest作成と管理<br>コンテナ基盤の運用管理 |
| コミュニケーション | Jira \| Confluence \| Notion \| Miro \| Slack \| Mattermost \| Chatwork \| Zoom \| Gather | 課題/プロジェクト管理、ドキュメント共有、ディスカッションなど |

### 補足資料

[アーキテクチャ概要](https://github.com/1shikawa/my-resume/blob/master/docs/Architecture.md)

## 職務経歴詳細

### フリーランス（2022/03〜現在）

#### 物流業向けDXプラットフォームの開発、運用（2024/10〜現在）

SREとして、クラウドネイティブベースの既存プラットフォーム開発運用業務に従事。

- **プロジェクト規模**
  - SREチームでの1メンバーとして参画
- **役割**
  - SRE
- **担当業務**
  - AWS CDKによるインフラ環境のコード化と運用改善
    - EKSおよびカスタムコントローラーのバージョンアップ対応
    - ALB・EKSにおけるブルー・グリーン環境構築
- **環境・技術**
  - AWS
- **その他**
  - 週2副(兼)業
- **発揮したバリュー**
  - TBA

#### 建設業向けDXプラットフォームの開発、運用（2024/05〜現在）

インフラエンジニア(DevOps/SRE)として、クラウドネイティブベースの既存プラットフォーム開発運用業務に従事。

- **プロジェクト規模**
  - 8人チームでのアジャイル(スクラム)開発
    - PO、SM、バックエンドDev、フロントエンドDev、インフラ/SRE、QA
- **役割**
  - インフラをメインとした要件定義、機能検討・調査、設計、実装、テスト、レビュー
- **担当業務**
  - Terraformによる全インフラ環境のコード化と運用改善
    - Cloud Run Jobs,driftctlによる構成ドリフト検出と定期通知の導入
  - CI/CDパイプラインの改善
    - plan,applyの並行実行化による処理時間短縮
    - tfcmtによるplan結果のPRコメント自動追加とレビュアーの負荷軽減
    - tfnotifyによるapply結果のSlack通知
    - 全インフラ環境への自動デプロイフロー構築
  - MongoDB AtlasのEOL(メジャーバージョンアップ)対応
    - テスト環境構築(Cloud Run,Dataflow)とE2Eテスト対応
  - GitHub ActionsとWorkload Identity連携環境構築
    - OpenAPIドキュメントの自動更新による運用効率化
- **環境・技術**
  - Google Cloud
- **その他**
  - 週5フルタイム
- **発揮したバリュー**
  - TBA

#### 会計系全社統合マスター管理サービスの新規開発（2023/01〜2024/04）

インフラエンジニア(DevOps/SRE)として、クラウドネイティブベースの新規プロダクト開発業務に従事。

- **プロジェクト規模**
  - 6人チームでのアジャイル(スクラム)開発
    - PO/SM、TL、バックエンドDev、インフラDev、QA
- **役割**
  - インフラをメインとした要件定義、機能検討・調査、設計、実装、テスト、レビュー
- **担当業務**
  - Terraformによる全インフラ環境のコード化と運用定着化
  - AWS EKSとGitHub Actions Runner Controllerを利用したCI/CD基盤構築と運用管理
  - ブランチ戦略に基づいたGitHub ActionsによるCI/CDパイプラインの設計構築と各種運用自動化
    - アプリのビルド・テスト、コンテナイメージ作成、DBマイグレーション、ECSタスクローリングアップデート、ドキュメント更新等
    - dev/stg/prod環境へ適宜手動・自動デプロイしリリース可能な仕組みを確立
  - イベント駆動(サーバレス)アーキテクチャの導入
    - SQS、Lambda、S3、DynamoDB、SNSを利用したPub/Subファンアウト構成
  - AWS(ECS/CloudWatch)とNew Relicのインテグレーションとオブザーバビリティ環境構築
    - アプリコンテナへのAPMエージェント組込み、各種メトリクスやログの転送と集約
    - NRQLによる閾値アラートルールとSlackチャンネルへの通知設定
    - 稼働状況モニタリングのためのダッシュボード作成
  - New Relic APMを活用したボトルネック探索とレイテンシー改善のための取組み
  - ECSスタンドアロンタスクを活用した踏み台、ポートフォワーディング、バッチコンテナ環境構築
  - Fargate SPOTや夜間の自動スケールイン機能のスケジュール実行によるコスト最適化
  - SLI/SLO達成のための負荷試験によるFargateタスクの必要スペックと常時起動数の算出とスケーリング設定
  - セキュリティやレイテンシーを考慮したクロスアカウントアクセスの導入
    - VPCピアリング、WAF、内部ALB/NLB、VPCエンドポイント(PrivateLink)、最小権限のAssumeロール
  - DRを想定したデータソースのリージョン間定期バックアップとレプリケーション設定
  - Golang(Gin)による他サービスを模したモックAPI作成とコンテナ化、App Runnerへの自動デプロイとテストスクリプト作成実行
- **環境・技術**
  - AWS
  - Kubernetes(カスタムオペレーター)
    - GitHub Actions Runner Controller/New Relic Kubernetes integration
- **その他**
  - インフラ(SRE)領域のリーディングとペア・モブプロによるDevメンバーへの展開
  - アジャイル(スクラム)開発未経験メンバーへのマインドセットや知見共有
- **発揮したバリュー**
  - ローカル開発環境の整備やインフラのコード化、CI/CDパイプラインの構築など、作業フローの効率化と各種自動化作業等に大きく貢献。予定していた本番商用リリースもほぼトラブル無く完遂。モダンな技術スタックの選定による開発者体験(DX)の向上施策を推進。

#### クラウドインフラをベースとしたCI/CD環境構築とDevOps推進支援（2022/03〜2022/12）

DevOpsエンジニアとしてクラウドネイティブベースの開発、本番環境の構築運用業務に従事。

- **プロジェクト規模**
  - 平均3〜5人チームでのアジャイル(スクラム)開発
    - PO/SM、インフラDev
- **役割**
  - インフラをメインとした要件定義、機能検討・調査、設計、実装、テスト、レビュー
- **担当業務**
  - Terraformによるインフラのコード化とCI(tfint,tfsec)実装
  - GitLab CI、ArgoCDによるCI/CD基盤構築と運用
  - Prometheus,Alertmanager,Grafanaによるモニタリング基盤構築
  - Promtail,Loki,Grafana、FruentBit,ClouwWatchによるロギング基盤構築
  - Kubernetes(EKS)クラスター構築と開発スクラムチームへの展開
  - アプリケーション構成に基づいたManifest作成と管理、CI(Kubeconform,Polaris)実装
  - DevSecOps（シフトレフト）を意識したGitOpsスタイルのCI/CDパイプライン構築
  - Golang(Gin)による技術検証およびデモ用Webapp,API作成とコンテナ化
- **環境・技術**
  - AWS
  - Kubernetes(カスタムオペレーター)
    - ALB Controller/External DNS/External Secrets/GitLab Runner/ArgoCD/Kube-prometheus-stack/Loki-stack/Redash/Velero
- **その他**
  - DevOps推進活動のリード（課題抽出整理、スケジューリング、タスク実行）
  - チーム内外に対するCI/CD勉強会の主催、ハンズオン及びQA対応
- **発揮したバリュー**
  - GitLab CIやArgoCDについては未経験であったが、機能を速習することで短期間でキャッチアップ。CI/CD環境整備とチーム内外に対するDevSecOps導入推進を主導し、自動化による開発プロセスの改善や開発生産性向上に貢献。また開発プロセス中に脆弱性チェックなどを組み込むことで継続的なセキュリティ対応にも貢献。

### ヤフー株式会社（2021/04〜2022/03）

#### 全社成果物管理プラットフォームの開発、運用管理

DevOpsエンジニアとして、プライベートクラウド基盤ベースの全社成果物管理プラットフォームの開発・運用保守業務に従事。

- **プロジェクト規模**
  - 平均4〜6人チームでのスクラム開発
    - PO、SM、バックエンドDev、インフラDev
- **役割**
  - 機能検討・調査、設計、実装、テスト、レビュー
- **担当業務**
  - Terraformによる成果物プラットフォームインフラのコード化
  - AnsibleによるVMインスタンスの構成管理
  - DC移転に伴う成果物プラットフォーム移行対応
  - 他部署からのQA対応
- **環境・技術**
  - OpenStack,Artifactory,Terraform,Docker-compose,MySQL,PostgreSQL,Ansible,Chef,Screwdriver(CI),AWS S3
- **その他**
- **発揮したバリュー**
  - DC移転に伴う新環境構築と移行対応により事業継続性とコスト削減に貢献

### GMOグローバルサイン・ホールディングス株式会社（2016/05〜2021/03）

#### 基幹系業務システム及び周辺システムの開発、運用管理

コーポレートエンジニアとして、オンプレミスベースの基幹系業務システムや周辺システムの開発、運用保守業務に従事。

- **プロジェクト規模**
  - 平均3〜15人チームでのウォーターフォール開発
- **役割**
  - 要件定義、機能検討・調査、設計、実装、テスト、レビュー、ベンダー管理等
- **担当業務**
  - 経理関連業務効率化を図るPython,DjangoによるWebアプリ開発
  - 基幹業務システムと電子契約サービスとの連携機能開発（Asteria,Oracle,MySQL）
  - Ansible/AWXによるCI/CD環境構築と定期メンテナンス作業やデプロイの自動化
  - ElasticStack(ElasticSearch,Kibana,Filebeat)によるログ統合管理基盤構築
  - 在庫管理システムリニューアルに伴う運用保守設計とバックアップ、監視基盤の構築
  - 基幹業務システムのバージョンアップに伴う影響調査分析と実行計画、ベンダー管理
  - 基幹業務システムや周辺システムの運用保守とヘルプデスク対応
- **環境・技術**
  - Windows Server/Linux/VMWare/Python/Django/Bash Script/Java/Tomcat/Weblogic/Docker/MySQL/PostgreSQL/Oracle/SQL Server/Ansible/ElasticSearch/Zabbix/Asteria/Kintone
- **その他**
  - TCO削減につながる施策の提案と実行
  - 既存業務の自動化推進を主導
- **発揮したバリュー**
  - 電子契約サービスの利用顧客増加による売上拡大に貢献
  - 既存業務の自動化による属人化解消とオペミス削減、省力化に貢献
  - 管理対象システム情報を自動同期するシステムを構築し、運用保守業務効率化に貢献

### 富士ゼロックス株式会社（2005/04〜2015/11）

#### 自社他社ソフトウェア、ハードウェアをベースとした顧客向けシステム提案、開発

顧客対応システムエンジニアとして、様々な業界業種のお客様向けにオンプレミスベースのシステム提案・開発運用業務に従事。

- **プロジェクト規模**
  - 平均3〜20人チームでのウォーターフォール開発
- **役割**
  - 要件定義、機能検討・調査、設計、実装、テスト、レビュー、ベンダー管理等
- **担当業務**
  - 病院向け診療記録管理システムの開発、運用
  - 中央省庁向け統計調査システムの開発、運用
  - 中央省庁向け調査研究に伴うWebシステム開発、運用
  - 総合電機メーカー向け設計業務管理システムの開発、運用
  - 銀行向け融資情報管理システムの開発、運用
  - 製造業・流通業向け図書管理システムの開発、運用
- **環境・技術**
  - Windows Server/VMWare/Java/Tomcat/Seasar/VBA/Oracle/MySQL/PostgreSQL/SAS/自社ソフト
- **その他**
  - 体系的知識を向上させるため積極的に資格を取得（Oracle,MCP,IPA関連）
- **発揮したバリュー**
  - ステークホルダー間調整や情報共有を心がけ、手戻りによるスケジュール遅延を防ぎ納期を遵守
  - 顧客にシステム導入効果や満足度を実感頂き、次案件の継続受注に貢献

## 意欲・興味

- バックエンド・クラウドインフラの新しい技術への興味関心が高く、今後も専門性を深めたいと考えています
- 比較的規模の大きいサービスメッシュ構成などのマイクロサービス基盤構築と運用に興味があります
- 用途に応じて複数のパブリッククラウドを組み合わせるマルチクラウドに興味があります
- Golangによるバックエンドや基盤コード開発力を向上させたいと思っています

<div style="text-align: right;">
以上
</div>
