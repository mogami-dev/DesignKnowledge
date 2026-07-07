# Design Workflow

## 目的

実装前に、人間とChatGPTで要件・画面・デザインを固め、Codexが迷わず実装できる状態にする。

## 全体フロー

```text
Idea
↓
要件定義（人間 + ChatGPT）
↓
画面・機能設計（人間 + ChatGPT）
↓
デザイン設計（人間 + ChatGPT）
↓
実装仕様確定（人間 + ChatGPT）
↓
Codexへ渡す
↓
実装
↓
レビュー
↓
リリース
```

## Phase 1: 要件定義

決めること:

- 誰のためのアプリか
- 何を解決するか
- MVPで何を作るか
- Phase2以降に回すものは何か

主な成果物:

- product_contract.md
- mvp_contract.md
- non_goals.md

## Phase 2: 画面・機能設計

UIの見た目ではなく、ユーザーが何をどう操作するかを決める。

画面ごとに決めること:

- 表示項目
- 操作
- 遷移
- 空状態
- ローディング
- エラー
- 編集・削除・保存
- 検索・ソート・フィルタ

## Phase 3: デザイン設計

画面の方向性を複数案で検討し、最終案を決める。

進め方:

1. Inspiration収集
2. UI案を最低5案作成
3. メリット・デメリット比較
4. ChatGPTでレビュー
5. 人間が最終決定
6. Design Decision Recordへ保存

## Phase 4: Design Freeze

ここでデザイン変更を止める。

以降は、Codexに「考えさせる」のではなく「再現させる」。

Design Freeze時点の成果物:

- 画面仕様
- デザイン方針
- デザインシステム
- コンポーネント一覧
- 状態別仕様
- デザイン決定記録
- Codex向け実装依頼
