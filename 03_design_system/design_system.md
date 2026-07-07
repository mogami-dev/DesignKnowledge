# Design System

## Purpose

プロジェクト全体で利用するデザインルールを定義する。

実装前にこのファイルを更新し、Codexにはこの内容を前提として実装させる。

## Design Principles

- シンプル
- 余白を活かす
- 情報量を最小限にする
- ユーザーが迷わない
- プラットフォーム標準を優先する
- 見た目だけでなく操作しやすさを重視する

## Color System

### Primary

用途:

- 主要CTA
- 選択状態
- 強調

### Secondary

用途:

- 補助ボタン
- 補助情報

### Accent

用途:

- 注意喚起
- 特別な状態

### Semantic Colors

- Success
- Warning
- Danger
- Info

### Base Colors

- Background
- Surface
- Divider
- Text Primary
- Text Secondary
- Disabled

## Typography

定義するもの:

- Title Large
- Title Medium
- Headline
- Body
- Caption
- Button

各項目で決めること:

- Font Family
- Size
- Weight
- Line Height
- 用途

## Spacing

基本は8pt Gridを採用する。

利用値:

- 4
- 8
- 12
- 16
- 20
- 24
- 32
- 48

## Radius

- Small
- Medium
- Large
- Round

用途例:

- Button
- Card
- Sheet
- Dialog
- Image

## Shadow

- Level 0: 影なし
- Level 1: 軽い浮き
- Level 2: カード・シート
- Level 3: Dialogなど強い前面表示

## Icons

推奨:

- Lucide
- SF Symbols（iOS）
- Material Icons（Android/Web）

サイズ:

- 16
- 20
- 24
- 32

ルール:

- アイコンだけで意味を伝えない
- 重要操作にはテキストを添える
- 同一画面でアイコンスタイルを混ぜない

## Buttons

種類:

- Primary
- Secondary
- Text
- Danger
- Disabled
- Loading

確認項目:

- タップ領域44pt以上
- CTAの優先順位が明確
- Disabled理由が分かる

## Form

対象:

- TextField
- TextArea
- Search
- Picker
- Toggle
- Checkbox
- Radio

## Navigation

対象:

- Bottom Tab
- Navigation Stack
- Sheet
- Dialog
- Full Screen

## Animation

Duration:

- 100ms
- 200ms
- 300ms
- 500ms

原則:

- アニメーションは目的を持って使う
- 操作結果を理解しやすくするために使う
- 過剰演出にしない
- Reduced Motionを考慮する

## Empty State

最低限含めるもの:

- アイコンまたは画像
- 状態説明
- 次の行動
- CTA

## Error

最低限含めるもの:

- 何が起きたか
- なぜ起きたか
- どうすればよいか
- 再試行ボタン

## Loading

原則:

- Skeleton優先
- Spinnerは短時間処理のみ
- 長時間処理は進捗または説明を出す

## Accessibility

確認項目:

- Dynamic Type
- VoiceOver
- タップ領域44pt以上
- Color Contrast
- Reduced Motion
