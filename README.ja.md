[English](README.md) · [简体中文](README.zh-CN.md) · [繁體中文](README.zh-TW.md) · **日本語** · [한국어](README.ko.md) · [Deutsch](README.de.md) · [Español](README.es.md) · [Français](README.fr.md) · [Italiano](README.it.md) · [Polski](README.pl.md) · [Русский](README.ru.md) · [Português (Brasil)](README.pt-BR.md) · [हिन्दी](README.hi.md)

# Starry — あなたのAIデザインパートナー

<p align="center"><img src="assets/cover-editor.jpg" alt="Starry canvas — AI repairing a lost image node in a Y2K portfolio design" width="100%"></p>

> AIコラボレーションのために生まれたデザインツール。ローカルファースト、ACPとMCPにより、自然言語を正確なUI仕様とプロダクションコードへ変換します。

[![Website](assets/badges/website.svg)](https://starry.design)
[![Try free in browser](assets/badges/trial.svg)](https://trial.starry.design)
[![Global](assets/badges/global.svg)](https://global.starry.design)
[![MCP](assets/badges/mcp.svg)](https://starry.design)
[![Export](assets/badges/export.svg)](https://starry.design/design-to-code.html)
[![Languages](assets/badges/langs.svg)](https://starry.design)
[![License](assets/badges/license.svg)](LICENSE)

---

## Starry をダウンロード

- [macOS 版をダウンロード](https://starry.design/download.html) — macOS
- [ブラウザで試す](https://trial.starry.design)
- 公式サイト: [starry.design](https://starry.design) · グローバルサイト: [global.starry.design](https://global.starry.design)

## AI デザインのワークフローを再定義

Starry はキャンバスを知的で検証可能なものにし、コードベースとシームレスに接続することでワークフローを再定義します。

| 機能 | 説明 |
|---|---|
| **AI 駆動のキャンバス** | Agent Client Protocol（ACP）を採用。キャンバスと直接対話できます。AI は自然言語から自動レイアウトのデザインシステムをネイティブに読み書き・生成します。 |
| **MCP サーバー** | Model Context Protocol を通じて Cursor や Claude などの AI コーディングツールとシームレスに接続。エディタを離れることなく正確な UI コードを即座に生成します。 |
| **CI/CD 向け CLI** | デザインファイルはコードです。CLI を使ってアセットを一括エクスポートし、タイポグラフィの違反を検出し、コードレビュー時にデザインの変更を自動で差分比較できます。 |
| **Figma との完全なデータ互換** | Starry は Figma と常に同期しています。一方のキャンバスからコピーし、もう一方にペースト——フレーム、テキスト、コンポーネント、スタイルがそのまま維持されます。ロックインもブラックボックスもありません。 |

## Starry はひとことでインターフェースを生成する

コードを書く必要も、白紙のキャンバスから始める必要もありません——求めるインターフェースを説明するだけで、Starry の AI がそれを生成してくれます。

| シナリオ | 理由 |
|---|---|
| SaaS / Web アプリの UI（設定画面、CRUD、フォーム） | すべてのソフトウェアチームが作るもの——オートレイアウトと React (JSX) への直接書き出しで最短のループを実現。 |
| マーケティング用ランディングページ / ウェブサイト | あらゆるプロダクトやスタートアップに必須——一文入力するだけで HTML/React が出力されます。 |
| データダッシュボード / 管理画面 | B2B で最大のカテゴリ——表、カード、グラフはすべてオートレイアウトの得意分野です。 |
| モバイルアプリの UI（ログイン、EC、オンボーディング） | 需要が非常に大きい——「デザイン + プロトタイプ」として位置づけ、HTML 書き出しでそのまま引き継ぎ。 |
| デザインシステム / コンポーネントライブラリ | 「自然言語からデザインシステムを生成」——最も差別化できる機能です。 |
| 高速プロトタイプ / MVP 検証 | プロンプト→画面→コード：個人開発者や PM がアイデアを検証する最速の道筋です。 |

## Starry が生成するデザイン

1 つのプロンプトから本番公開可能な画面へ。すべての出力はコードベースとピクセル単位で一致します。

| ![](assets/editor-landing.jpg) | ![](assets/editor-mobile.jpg) |
|---|---|
| *マーケティングランディング* | *モバイル画面* |

## Starry と他社の比較

| | Starry | Figma | Stitch | Sketch |
|---|---|---|---|---|
| AI 生成 | 1 sentence → UI | 手動 + Figma AI | Text to UI | 手動 + Sketch AI |
| ハンドオフ | 0 rework · React (JSX) と HTML | 仕様のみ（コンポーネントなし） | コードスニペット | Sketch / PDF |
| 移行 | Native .fig import | —（Figma 自体） | ネイティブ导入なし | Figma を导入 |
| 使いやすさ | 0 learning curve | キャンバスを学ぶ | 0 (text) | Sketch を学ぶ |
| AI 連携 | MCP → editor · ACP → agents | なし | なし | なし |
| コラボレーション | Real-time (WebRTC) | リアルタイム | リアルタイム | リアルタイム |
| 料金 | Free | $12+/editor | Free | $10/editor |

> 精度は 2026年8月に確認。機能は変更される場合があります。各ベンダーのサイトでご確認ください。

## よくある質問

**Starry は AI を使ってインターフェースを生成できますか？**

はい。思い描いた内容を普通の言葉で説明するだけで、Starry の AI がインターフェースを生成します——レイアウト、コンポーネント、自動レイアウトまで。そして本番用のコード（React (JSX) と HTML）を直接出力します。編集・実行可能な本物の UI です。

**書き出したコードはそのまま自分のプロジェクトに使えますか？**

はい。Starry は clean で本番向けのコード（React (JSX) と HTML）を書き出し、キャンバスとレイアウトが一致します。コードはあなたのもの——そのままプロジェクトへ組み込め、ロックインされません。

**既存の Figma デザインを取り込めますか？**

はい。Starry はネイティブな .fig ファイルを直接インポートでき、ベクタ・テキスト・スタイルがそのまま保持され、どちらのツールでも調整を続けられます。

**自分のエディタから Starry を使えますか？**

はい。Starry は MCP サーバーを内蔵しており、Cursor、Claude Code、Codex などの AI コーディングツールがあなたのキャンバスを直接読み書きできます——ツールを切り替えずに、エディタから UI コードを生成できます。

**私のデザインデータは安全ですか？**

安全です。Starry はローカル優先です——ファイルは既定でお使いのマシンに保存され、Git でバージョン管理できます。クラウド協業は任意で、エンドツーエンド暗号化されています。

**入手方法は？**

macOS アプリは starry.design からダウンロード。trial.starry.design を開けばインストール・登録なしでブラウザで試せます。

## リポジトリの内容

Starry にそのまま使えるプロンプト、デザインシステム仕様、サンプル集。アプリのソースコードは含みません（アプリは非公開）。

```
starry-templates/
├── README.md                 # this file (+ 12 localized versions)
├── assets/                   # hero image & real editor screenshots
├── design-systems/
│   └── base-ui.md            # sample Markdown design-system spec
├── prompts/
│   ├── landing-page.md       # marketing landing page
│   ├── saas-settings.md      # settings console with members table
│   ├── analytics-dashboard.md
│   └── mobile-login.md       # login + OTP + onboarding screens
└── docs/
    ├── comparison.md         # Starry vs Figma / Stitch / Sketch
    ├── design-to-code.md     # export pipeline & guarantees
    ├── ai-ui-generator.md    # prompt-to-UI explained
    └── figma-to-react.md     # Figma → React (JSX) workflow
```

## 使い方

1. Starry を開きます（デスクトップアプリまたはブラウザ版）。
2. `design-systems/` のデザインシステム仕様を貼り付け、次に `prompts/` のプロンプトを貼り付けます。
3. Starry が編集可能なオートレイアウトを生成します — React (JSX) または HTML に書き出せます。

## リンク

- [starry.design](https://starry.design)
- [global.starry.design](https://global.starry.design)
- [Download](https://starry.design/download.html)
- [Browser trial](https://trial.starry.design)

## ライセンスと開発者

- MIT — see [LICENSE](LICENSE).
- SmartAly (Aly) が個人開発者として開発・運用しています。

---

*Starry — AI ネイティブなデザイン、キャンバスからコードへ。*
