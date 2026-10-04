# 開発ガイド

このリポジトリは、以下の Git サブモジュールを参照する。

- `microduck/`: Microduck 本体
- `microduck_rl/`: Microduck 関連の強化学習コンポーネント

## サブモジュールのドキュメント

各サブモジュールに関する仕様、実装、設計、運用方法を確認するときは、WebFetch や外部 Web ページを使わない。必ずローカルの各サブモジュール内にあるドキュメントとソースコードを参照する。

- **Microduck**: まず `microduck/AGENTS.md` と `microduck/CONTRIBUTING.md` を読み、必要に応じて `microduck/docs/` を確認する。
- **Microduck RL**: まず `microduck_rl/AGENTS.md` と `microduck_rl/README.md` を読み、必要に応じて `microduck_rl/docs/` を確認する。

## 回答の規約

回答は日本語の常体で記述する。読者はソフトウェアエンジニアであることを前提とし、必要な技術的背景、前提条件、検証結果を簡潔かつ正確に示す。
