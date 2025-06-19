# GitHubStar_Nomination
## 連絡先情報
- X: @YoutanDml (https://x.com/YoutanDml)
- LinkedIn: https://www.linkedin.com/in/yutaka-osada0922/
- Zenn（技術ブログ）: https://zenn.dev/yutakaosada
- GitHub: https://github.com/yutaka-art

## SpeakerDeck（スライドアーカイブ）
https://speakerdeck.com/yutakaosada

## なぜGitHub Starになりたいのか？
私のプロフェッショナルな使命は、複雑なDevOps理論を、どのチームでも採用できる実践的かつ再現可能なワークフローへと変換することです。そのため、GitHub Starになりたいと考えています。
私は日本のDevOpsエンジニア・コミュニティスピーカーとして、Infrastructure as Code、マルチステージCI/CDパイプライン、GitHubとAzure上でのセキュアな開発者プラットフォームを専門としています。過去1年間で以下の活動を行いました。

- 主要カンファレンス（DevOps Days Tokyo 2025、GitHub Dockyard、Microsoft Build振り返り等）で登壇し、GitHub Copilot、Advanced Security、GitHub Actionsランナーパターン（Azure上）のライブデモを実施
- 技術書籍（AZ-400 IaC章）やZenn記事（セルフホストランナー、Copilotメトリクス等）など、深掘り技術コンテンツを執筆
- レガシーパイプラインのGitHub移行や、IaCによるガバナンスポリシー・脅威モデリングのハンズオンワークショップでエンジニアを指導
- Workload Identity & OIDCの普及を推進し、長期シークレットを排除した安全な認証を企業に数分で導入

GitHub Starになることで、これらの取り組みをさらに拡大し、GitHubプロダクトチームや世界中のStarとの直接的なフィードバックループを得られます。IaCやパイプライン自動化のベストプラクティス普及を加速し、規制業界の開発者体験を向上させ、日本およびグローバルなOSS貢献者の新しい波を生み出したいと考えています。

## 過去12ヶ月の主な実績

### 登壇実績
1. DevOps Days Tokyo 2025登壇 – 「GitHub監査ログ×Azure分析基盤によるエンタープライズセキュリティ強化」

- 日時: 2025年4月15日
- リンク: https://confengine.com/conferences/devopsdays-tokyo-2025/proposal/21874/github
- 概要
  - 日本最大級のDevOpsカンファレンスで、競争率の高いCFPを通過し、20分間のアドバンストセッション（Hall A）を担当
  - ConfEngineで18件の「Interested」を獲得し、Administration & Securityトラックの上位25%にランクイン
  - GitHub Enterprise監査ログをAzure Event Hubs・Cosmos DBへストリーミングし、リアルタイム異常検知・コンプライアンスレポートを実現。Copilotテレメトリ分析も紹介
  - IaC（Bicep）サンプル、Dapr/KEDAパターン、GitHub APIレート制御戦略など、生成AI時代の実践的DevSecOpsガバナンスを解説
- スライド: https://speakerdeck.com/yutakaosada/202504xx-githubjian-cha-roguwohuo-yong-sitaentapuraizuxiang-kesekiyuriteiqiang-hua-todetafen-xi-ji-pan-nogou-zhu
- YouTube: https://www.youtube.com/watch?v=TpEmCG57fQQ

2. GitHub Dockyard登壇 – 「GitHub監査ログ×クラウド分析で実現するエンタープライズセキュリティ」

- 日時: 2025年2月25日  
- リンク: https://github-dockyard.connpass.com/event/345814/
- 概要  
  - 日本のGitHub活用コミュニティイベント「GitHub Dockyard」で30分の技術セッションを担当（CFP通過、当日のセキュリティ目玉セッション）
  - GitHub Enterprise監査ログをAzure Event Hubsにストリーミングし、Azure Functionsで処理、Cosmos DB・Log Analyticsに格納して脅威検知・コンプライアンスを実現するリファレンスアーキテクチャを紹介
  - IaC（Bicep）テンプレート、Functionアプリコード、GitHub REST-APIスクリプトを公開し、参加者が自環境で再現可能に
  - トークン管理（GitHub Appsインストールトークン vs PAT）、レート制御、Copilotテレメトリ連携によるセキュリティインサイトのベストプラクティスを解説
- スライド: https://speakerdeck.com/yutakaosada/20250225-githubjian-cha-roguxkuraudofen-xi-deshi-xian-suruentapuraizusekiyuriteiqiang-hua
- YouTube: https://www.youtube.com/live/V020w8w8MwI?si=taSLNhnHIGNPh1hp

### ブログ寄稿
1. 「GitHub Copilotの新しいPremiumモデルとリクエスト上限を徹底解説」

- 日時: 2025年6月19日
- リンク: https://zenn.dev/yutakaosada/articles/5f607ed5b03205
- 概要
  - 2種類のモデル（Base/Premium）と、Premiumリクエスト割当（Business: 300回、Enterprise: 1,000回/月）の消費ルール、モデルごとの倍率（例: GPT-4.5=×50）を解説
  - 超過料金（$0.04/リクエスト）、Budgets & Alertsによる上限設定、GitHub UIからのPremiumリクエスト利用レポート出力手順を紹介
  - 独自の比較表、YAMLフロントマター、スクリーンショット、VS Code活用Tipsを掲載し、管理者・開発者双方がリアルタイムで消費状況を監視できるよう支援
  - Zenn・SNSで拡散され、企業のCopilotコスト予測やAI開発導入時の予期せぬ課金回避に貢献

2. 「GitHub組織監査ログをAzure Blob Storageへ自動エクスポートする方法」

- 日時: 2025年1月15日
- リンク: https://zenn.dev/yutakaosada/articles/84b66b2ba6d282
- 概要
  - GitHub監査ログのデフォルト保持期間（90日）と、長期外部保存の必要性（セキュリティ・コンプライアンス要件）を解説
  - `GET /orgs/{org}/audit-log`（PAT利用）で監査ログを取得し、SAML SSOトークン認証を含めたC#（.NET 8）サンプルと、Azure.Storage.Blobs SDKでのBlobアップロード例を紹介
  - 必要なPATスコープ（`audit_log`, `admin:org`）、User-Agentヘッダー設定、大量ログのページング・レート制御戦略を詳細解説
  - コード例、JSONサンプル、スクリーンショット、手順を掲載し、DevOpsチームが数分で継続的な監査ログオフロードとクラウド分析を実現できるよう支援

3. 「GitHub ActionsセルフホストランナーをAzure Container Apps上に構築（GitHub App認証編）」

- 日時: 2024年12月20日
- リンク: https://zenn.dev/yutakaosada/articles/6ce1577a84db2d
- 概要
  - PATではなくGitHub App認証を用いた、Azure Container Apps上のセルフホストランナークラスタ構築手順を解説
  - ACR、ACA、Key Vault、Managed Identity、KEDAスケーラーのセットアップをAzure CLIスクリプトで段階的に紹介。環境変数テンプレートやARM/CLIワンライナーも掲載
  - Microsoft公式ランナーイメージのフォーク、`entrypoint.sh`のJWT生成・インストールアクセストークン交換・動的ランナー登録のBashコードを公開
  - Key Vault連携、Managed Identity、GitHub App短期トークンによるセキュリティベストプラクティスと、キュー長に応じた自動スケールによるコスト最適化を解説

4. 「GitHub ActionsセルフホストランナーをAzure Container Apps上に構築（PAT認証編）」

- 日時: 2024年12月17日
- リンク: https://zenn.dev/yutakaosada/articles/f150d9d403656a
- 概要
  - Microsoft公式サンプルを、PAT認証による本番運用可能なセルフホストランナー構成へと発展させる手順を解説
  - ACR、ACA、Log Analytics、KEDA GitHub-runnerスケーラーのプロビジョニングから、PATで自動登録するコンテナイメージのデプロイまで、CLIスニペットを掲載
  - PATの最小スコープ・定期ローテーション・シークレット参照注入など、セキュリティベストプラクティスを解説
  - ワークフローYAML（`runs-on: self-hosted`）編集や、`az containerapp job execution list`によるスケール検証方法も紹介し、コスト効率と拡張性を両立したCI/CDテンプレートを提供

5. 「GitHub Actions & BicepでAzureリソースをIaCデプロイ」

- 日時: 2024年11月8日
- リンク: https://zenn.dev/yutakaosada/articles/a5d77da31ce26d
- 概要
  - GitHub ActionsからBicepファイルをAzureへデプロイする方法を、従来のService Principal認証と最新のOIDC/Workload Identity認証で比較
  - Entra IDアプリ作成、フェデレーション資格情報設定、`AZURE_CLIENT_ID`等のリポジトリシークレット登録までを解説
  - `azure/login@v1`でOIDCログインし、`azure/arm-deploy@v1`で`main.bicep`をデプロイするサンプルワークフローを掲載（`workflow_dispatch`入力・権限スコープ付き）
  - Azure DevOps Service Connectionとの違い（GitHub Actionsには「接続テスト」機能がない）を解説し、トークン検証用のミニワークフローも提案
  - ACR、ACA等のCLIプロビジョニング例や、公開リポジトリ<https://github.com/yutaka-art/bicep_deployment>の全ソースも案内

6. 「GitHub Copilot Metrics ViewerをAzure Static Web Appsへデプロイ」

- 日時: 2024年9月3日
- リンク: https://zenn.dev/yutakaosada/articles/018772bd0ce461
- 概要
  - Copilot Metrics Viewerプロジェクトのフォーク・ローカルテスト・Azure Static Web AppsへのGitHub Actionsパイプラインデプロイ手順を解説
  - 必要なPATスコープ（`copilot`, `manage_billing:*`, `read:enterprise`, `read:org`）の取得、`VUE_APP_GITHUB_TOKEN`へのマッピング、`VUE_APP_SCOPE`等のSecrets/Variables設定方法を紹介
  - Static Web Appsウィザード（Standardプランで基本認証）、自動生成ワークフロー、Secretsをビルドステップへ渡す`env:`ブロック追加方法を解説
  - 各種ダッシュボード（Acceptance Rate、Total Suggestions/Acceptances、Language Breakdown、Copilot Chat、Seat Analytics）のスクリーンショットと、採用率・ROI（目標30%）の可視化方法を紹介
  - セキュアなトークン管理、開発時のモックデータ利用（`VUE_APP_MOCKED_DATA=true`）、Azureサービス連携拡張のベストプラクティスも掲載

### OSSプロジェクト貢献
1. Zenn記事向けAzure Durable Functions Workerサンプル
- 日時: 2025年1月22日
- リンク: https://github.com/yutaka-art/DurableFunction_Worker
- 概要
Zenn技術記事に合わせて作成したAzure Durable FunctionsのC#サンプルプロジェクトです。Azure上で信頼性・スケーラビリティの高いワークフローを実装するための実践例を提供し、サーバーレスアーキテクチャにおけるステートフルオーケストレーションパターンの理解を支援します。Durable Functionsの入門・応用に役立つリソースです。

2. Application Insights Workerユーティリティ
- 日時: 2024年9月30日
- リンク: https://github.com/yutaka-art/ApplicationInsights_Worker
- 概要
Azure Application Insightsと連携するC#ユーティリティプロジェクトを作成しました。このワーカーはテレメトリデータの収集・処理・分析を自動化し、開発・運用チームがアプリケーションのパフォーマンスを効率的に監視できるよう支援します。これにより、クラウドアプリの信頼性・効率性向上に貢献します。

3. Swagger YAMLファイルマージツール
- 日時: 2024年9月16日
- リンク: https://github.com/yutaka-art/swagger-detect-merger
- 概要
複数の`swagger.yaml`ファイルを統合するツールを開発しました。APIドキュメントを複数ソースで管理する際の統合作業を効率化し、手作業やミスを減らします。大規模プロジェクトや複数マイクロサービスを運用する組織に特に有用で、統一された最新APIドキュメントの維持に役立ちます。
