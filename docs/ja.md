# GeniusBotsLab — エージェント型システムと信頼性の高い AI 自動化

**制御可能で測定可能な業務プロセスのための AI 自動化エンジニア。**

私は、専門エージェントが明確な引き継ぎ、権限、予算、ログ、そして重要な操作に対する人間の承認を通じて、調査、計画、実行、レビュー、検証、報告を行う AI システムを設計します。

[English](en.md) · [Русский](ru.md) · [Română](ro.md) · [简体中文](zh-CN.md) · [עברית](he.md) · [Français](fr.md) · [Deutsch](de.md) · [Español](es.md) · [Português (Brasil)](pt-BR.md) · [日本語](ja.md) · [العربية](ar.md) · [Українська](uk.md)

---

## 提供できること

- **マルチエージェント・オーケストレーション** — 調査、分析、計画、実行、レビュー、検証、レポーティングの役割を、明確な責任範囲とともに設計します。
- **長時間稼働ワークフロー** — 状態管理、キュー、スケジュール、チェックポイント、再試行、タイムアウト、アラート、監査ログ、承認ゲートを扱います。
- **AI 支援ソフトウェアデリバリー** — Claude、Claude Code、ChatGPT を調査、実装、レビュー、テスト設計、文書化に活用します。アーキテクチャ、セキュリティ、検証、リリース、意思決定の責任は人間が負います。
- **認可済みのソーシャル／メディア・ワークフロー** — 承認済みの公開、コメントのモデレーションと返信、コンテンツ計画、画像・動画・音声パイプライン、レポート、内部業務を対象にします。

## エンジニアリングの実践

```text
プロセス監査 → パイロット指標 → 役割とアクセス権 → 構築 → テストと QA → 制御された公開 → コスト・品質・エラーの監視 → 改善
```

該当する場合、単体テスト、統合テスト、エンドツーエンドテストを必須とし、CI で合意済みの自動チェックを実行します。構造化された入力と出力を検証し、曖昧または影響の大きい結果は人間がレビューします。

### モデル、RAG、信頼性

- タスクの複雑さ、必要な品質、コストに応じてモデルを振り分けます。
- コンテキストを制御し、再利用可能な結果をキャッシュし、トークンと操作の予算を設定します。
- 根拠となる情報検索が適切な場合に RAG と状態を持つワークフローを使用します。
- 可観測性、権限、配信ステータス、再試行／フォールバック経路、文書化された障害処理により運用します。

## 技術スタック

**AI とエージェント：** Claude · Claude Code · ChatGPT · OpenAI 互換 API · ロールベースのエージェント · ツール呼び出し · RAG

**エンジニアリング：** Python · TypeScript / JavaScript · SQL · REST API · Webhook · Docker · Git/GitHub · CI · 自動テスト · データベース · キュー · 監視

**自動化とメディア：** 許可されたブラウザ/API 連携 · Telegram Bot API · ElevenLabs · テキスト、画像、動画、音声向け AI パイプライン

## 主な公開プロジェクト

- [**Social Media Crossposter**](https://github.com/GeniusBotsLab/social-crossposter-comment-module) — 許可された連携を通じ、認可済みアカウントとチャンネルへテキスト、画像、動画を公開するワークスペース。
- [**Swarm Agent Coordinator**](https://github.com/GeniusBotsLab/swarm-agent-coordinator) — エージェントチーム、タスク、役割、作業ルームのためのセルフホスト型コーディネーション。
- [**TextFix**](https://github.com/GeniusBotsLab/textfix) — OpenAI 互換 API による AI 支援テキスト修正の Windows ユーティリティ。
- [**NeuroMedia Marketplace**](https://github.com/GeniusBotsLab/neuromedia-marketplace) — 公開多言語 AI Marketplace のショーケースと安全なカタログ同期。
- [**Self-Correcting Link Parser**](https://github.com/GeniusBotsLab/self-correcting-link-parser) — 準拠した調査ワークフローのための公開リンク収集、正規化、品質管理。

## 責任ある自動化

所有者の同意を得て、プラットフォーム規則に準拠した、認可済みのアカウント、データ、連携のみを扱います。スパム、偽の身元、人工的なエンゲージメント、プラットフォーム規則の回避、CAPTCHA または不正防止機構の回避、無許可アクセスを構築・運用することは**ありません**。大量アカウント登録についての主張も行いません。

## 連絡先

- **メール：** [BotsLab@proton.me](mailto:BotsLab@proton.me)
- **Telegram：** [@TheBotsLab](https://t.me/TheBotsLab)

---

<sub>公開プロフェッショナルポートフォリオのみです。認証情報、顧客データ、私有インフラ、未公開資料は含みません。定量的な主張および本番環境に関する主張は、許可された公開成果物または匿名化された証拠で裏付けられる場合にのみ公開します。</sub>
