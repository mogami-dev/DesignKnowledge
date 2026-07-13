# Design Resources

## 使い方

このファイルは、デザインに困った時の「素材・UI部品・配色・フォント探し辞典」として使う。

コードを実行するためのリポジトリではなく、デザイン検討時の参照先を整理する。

## 取り込み方針

個人の好みだけでなく、一般的に質の高いデザイン判断へ寄せるために、以下を優先する。

- プラットフォーム公式のガイドライン
- アクセシビリティ確認に使えるもの
- 実プロダクトや実例を観察できるもの
- デザインシステムとして原則・コンポーネント・状態が整理されているもの
- Codex実装時に再現しやすいもの

出典候補:

- [bradtraversy/design-resources-for-developers](https://github.com/bradtraversy/design-resources-for-developers)

## Inspiration

用途:

- 画面構成
- UXパターン
- ナビゲーション
- LP構成

候補:

- Design Vault
- Mobbin
- Screenlane
- Collect UI
- Landingfolio
- SaaS Landing Page
- Really Good Emails
- Awwwards
- Dribbble
- Behance

使い分け:

- アプリ画面: Mobbin / Screenlane / Design Vault
- LP: Landingfolio / SaaS Landing Page / Awwwards
- メール: Really Good Emails
- ビジュアル方向性: Behance / Dribbble

## Colors

用途:

- 配色
- アクセントカラー
- ダークモード
- ブランドカラー

候補:

- Color Brewer
- Coolors
- UI Colors
- Color Hunt
- Adobe Color
- whocanuse
- Colorable
- InclusiveColors

確認順:

1. まずコントラストを確認する
2. 次にブランドらしさを見る
3. 最後にトレンド感を見る

## Fonts

用途:

- 本文
- 見出し
- 英数字
- LP

候補:

- Google Fonts
- Fontshare
- Bunny Fonts
- Fontjoy
- FontPair
- Fonts for Apple Platforms

原則:

- iOSはまずシステムフォントを検討する
- Webは読み込み速度とライセンスを確認する
- フォント組み合わせは2系統までに抑える

## Icons

用途:

- アプリUI
- Web管理画面
- LP

候補:

- Lucide
- Heroicons
- Phosphor
- Material Icons
- Material Design Icons
- Feather Icons

原則:

- 同一画面でアイコンセットを混ぜない
- アイコンだけで重要操作を伝えない
- SVG利用時はサイズ、線幅、アクセシビリティ名を確認する

## Illustrations

用途:

- Empty画面
- Onboarding
- LP

候補:

- unDraw
- Storyset
- DrawKit
- Humaaans
- Blush
- Open Peeps

原則:

- Empty画面以外で装飾を増やしすぎない
- 画面の主目的よりイラストを目立たせない
- 商用利用とクレジット要否を確認する

## Photos

用途:

- LP
- モックアップ
- 背景

候補:

- Unsplash
- Pexels
- Pixabay

原則:

- 実プロダクトを説明する画面では、雰囲気写真より実物写真を優先する
- 写真のライセンス、人物権利、ブランド写り込みを確認する

## Mockups

用途:

- App Store画像
- SNS告知
- LP

候補:

- Shots
- Mockup World
- Graphic Burger
- Freebiesbug

原則:

- 実装仕様ではなく説明・共有用に使う
- App StoreやLPで使う場合はライセンスを確認する

## Design Systems & Style Guides

用途:

- 一般的な良いUI原則の確認
- プラットフォーム標準の確認
- コンポーネント設計の参考
- 状態、アクセシビリティ、ライティングの参考

候補:

- Apple Human Interface Guidelines
- Apple Design Resources
- Material Design
- Microsoft Fluent UI
- IBM Carbon Design System
- Shopify Polaris
- GitHub Primer
- Atlassian Design System
- Adobe Spectrum
- Laws of UX
- Checklist Design
- Humane by Design

使い分け:

- iOS / macOS: Apple Human Interface Guidelines / Apple Design Resources
- Android / Google系: Material Design
- 業務ツール: Carbon / Fluent UI / Atlassian
- コマース: Polaris
- 開発者向けUI: Primer
- UX原則確認: Laws of UX / Checklist Design / Humane by Design

## Components

用途:

- Web管理画面
- LP
- プロトタイプ

候補:

- Tailwind UI
- shadcn/ui
- DaisyUI
- Headless UI
- Flowbite

原則:

- 実装候補としてではなく、まず部品仕様の参考として見る
- 導入前に既存技術・アクセシビリティ・保守性を確認する

## React UI

用途:

- 管理画面
- ダッシュボード
- Webアプリ

候補:

- Mantine
- HeroUI
- Ant Design
- Framer Motion
- Recharts
- Tremor

## Image Optimization

用途:

- LPやアプリ紹介画像の軽量化
- Codexへ渡す画像素材の圧縮
- SVGの最適化

候補:

- Squoosh
- TinyPNG
- SVGOMG

原則:

- 元画像は残す
- 圧縮後の見た目を確認する
- EXIFなど不要なメタ情報を公開前に確認する

## ライセンス注意

リンク集自体のライセンスと、掲載されている各素材サイトのライセンスは別。

`bradtraversy/design-resources-for-developers` はMIT Licenseだが、掲載先サービスの素材・フォント・画像・UIキットの利用条件はそれぞれ確認する。

商用アプリで使う場合は必ず確認する。

確認項目:

- 商用利用可否
- クレジット表記要否
- 改変可否
- 再配布可否
