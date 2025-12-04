# アプリケーション名

SampleApp - シンプルTODOアプリ

# 概要

日々のタスクを管理するためのシンプルなTODOアプリケーションです。タスクの追加、完了、削除などの基本的な機能を提供します。

## 主な機能

- タスクの追加・編集・削除
- タスクの完了/未完了の切り替え
- タスクの期限設定
- カテゴリ別のタスク管理
- タスクの検索・フィルタリング

# 技術スタック

- フロントエンド: React
- バックエンド: Node.js / Express
- データベース: SQLite
- スタイリング: CSS Modules

# セットアップ

```bash
# リポジトリのクローン
git clone git@github.com:test-org-n/SampleApp.git

# 依存関係のインストール
npm install

# 開発サーバーの起動
npm run dev
```

# ディレクトリ構成

```
SampleApp/
├── src/
│   ├── components/    # Reactコンポーネント
│   ├── pages/         # ページコンポーネント
│   ├── hooks/         # カスタムフック
│   ├── api/           # APIクライアント
│   └── utils/         # ユーティリティ関数
├── server/
│   ├── routes/        # APIルート
│   ├── models/        # データモデル
│   └── db/            # データベース設定
└── public/            # 静的ファイル
```

# ライセンス

MIT
