[English](README.md) · [简体中文](README.zh-CN.md) · **繁體中文** · [日本語](README.ja.md) · [한국어](README.ko.md) · [Deutsch](README.de.md) · [Español](README.es.md) · [Français](README.fr.md) · [Italiano](README.it.md) · [Polski](README.pl.md) · [Русский](README.ru.md) · [Português (Brasil)](README.pt-BR.md) · [हिन्दी](README.hi.md)

# Starry — 你的AI設計夥伴

<p align="center"><img src="assets/cover-editor.jpg" alt="Starry canvas — AI repairing a lost image node in a Y2K portfolio design" width="100%"></p>

> 為 AI 協作而生的設計工具。本地優先，基於 ACP 與 MCP 協定，將自然語言、精確 UI 規範與生產程式碼無縫打通。

[![Website](assets/badges/website.svg)](https://starry.design)
[![Try free in browser](assets/badges/trial.svg)](https://trial.starry.design)
[![Global](assets/badges/global.svg)](https://global.starry.design)
[![MCP](assets/badges/mcp.svg)](https://starry.design)
[![Export](assets/badges/export.svg)](https://starry.design/design-to-code.html)
[![Languages](assets/badges/langs.svg)](https://starry.design)
[![License](assets/badges/license.svg)](LICENSE)

---

## 下載 Starry

- [下載 macOS 版](https://starry.design/download.html) — macOS
- [在瀏覽器中試用](https://trial.starry.design)
- 官網: [starry.design](https://starry.design) · 全球站: [global.starry.design](https://global.starry.design)

## 重新定義你的 AI 設計工作流

Starry 讓畫布變得智能、可校驗，並與程式碼庫無縫連接，重新定義設計工作流。

| 能力 | 說明 |
|---|---|
| **AI 驅動畫布** | 基於 Agent Client Protocol（ACP），直接與畫布對話。AI 原生讀寫畫布，從自然語言產生自動佈局設計系統。 |
| **MCP 伺服器** | 透過 Model Context Protocol 無縫接入 Cursor、Claude 等 AI 編程工具，無需離開編輯器即可產生精確的 UI 程式碼。 |
| **CLI 接入 CI/CD** | 設計檔案即程式碼。使用 CLI 批次匯出資源、偵測排版違規，並在程式碼評審中自動對比設計變更。 |
| **與 Figma 完全資料互通** | Starry 與 Figma 始終保持同步。從一個畫布複製，貼上到另一個——畫板、文字、元件與樣式完整保留，沒有綁定，也沒有黑箱。 |

## Starry 用一句話生成介面

不用寫程式碼，也不從空白畫布開始——描述你想要的介面，Starry 的 AI 直接把它生成出來。

| 場景 | 為什麼適合 |
|---|---|
| SaaS / Web App 產品介面（設定頁、CRUD、表單） | 所有軟體團隊都要做，auto-layout + 直出 React (JSX) ，閉環最短。 |
| 行銷落地頁 / 官網 | 每個產品和新創公司的剛需，一句話生成，直接匯出 HTML/React。 |
| 資料看板 / 管理後台 | B2B 與內部工具的最大品類，表格、卡片、圖表都是 auto-layout 強項。 |
| 行動端 App 介面（登入、電商、Onboarding） | 需求量極大，定位「設計 + 原型」，匯出 HTML 直接交付。 |
| 設計系統 / 元件庫 | 「用自然語言生成設計系統」，差異化最強的一張牌。 |
| 快速原型 / MVP 驗證 | 提示詞→介面→程式碼，獨立開發者與 PM 驗證想法的最快路徑。 |

## Starry 生成的設計

從一句話到可上線的介面。每一次輸出都與你的程式碼庫保持像素級一致。

| ![](assets/editor-landing.jpg) | ![](assets/editor-mobile.jpg) |
|---|---|
| *行銷落地頁* | *行動端介面* |

## Starry 對比一覽

| | Starry | Figma | Stitch | Sketch |
|---|---|---|---|---|
| AI 生成 | 1 句話 → 介面 | 手動 + Figma AI | 文字生成 | 手動 + Sketch AI |
| 交付 | 0 返工 · React (JSX) 和 HTML | 僅標註，無元件 | 程式碼片段 | Sketch / PDF 匯出 |
| 遷移 | 原生 .fig 匯入 | —（它就是 Figma） | 無原生匯入 | 可匯入 Figma 檔案 |
| 上手門檻 | 0 學習成本 | 需學畫布 | 0（文字） | 需學 Sketch |
| AI 整合 | MCP 連編輯器 · ACP 託管智能體 | 無 | 無 | 無 |
| 協作 | 即時（WebRTC） | 即時 | 即時 | 即時 |
| 價格 | 免費 | $12+/人/月 | 免費 | $10/人/月 |

> 準確性核對於 2026 年 8 月。功能可能變動，請以各官網為準。

## 常見問題解答

**Starry 能直接用 AI 生成介面嗎？**

能。用白話描述需求，Starry 的 AI 生成介面——佈局、元件、自動佈局一步到位，並直接匯出生產級程式碼（React (JSX) 和 HTML）。它是真實、可編輯、可執行的介面，不是靜態稿。

**匯出的程式碼能直接用到我的專案裡嗎？**

能。Starry 匯出乾淨的生產級程式碼（React (JSX) 和 HTML），畫布與程式碼佈局一致。程式碼完全歸你，直接放進專案即可，不被鎖定。

**我已有的 Figma 設計能匯進來嗎？**

能。Starry 可直接匯入 .fig 檔案，向量、文字與樣式都能完整保留，你也能在兩個工具間繼續微調。

**我能在自己的編輯器裡用 Starry 嗎？**

能。Starry 內建 MCP 服務，讓 Cursor、Claude Code、Codex 等 AI 編碼工具直接讀寫你的畫布——不用切換工具，就能在編輯器裡生成介面程式碼。

**我的設計資料安全嗎？**

安全。Starry 預設本地優先：檔案存在你本機，可用 Git 管理版本；雲端協作是選用的，且端對端加密。

**在哪裡取得？**

在 starry.design 下載 macOS 應用，或打開 trial.starry.design 直接在瀏覽器試用 —— 無需安裝、無需註冊。

## 倉庫內容

可直接用於 Starry 的提示詞、設計系統規範與範例。不含應用源碼 —— 應用本身不開源。

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

## 如何使用

1. 打開 Starry —— 桌面應用或瀏覽器試用版。
2. 把 `design-systems/` 裡的設計系統規範貼上，再貼上 `prompts/` 裡的提示詞。
3. Starry 會產生可編輯的自動佈局圖層 —— 匯出 React (JSX) 或 HTML。

## 連結

- [starry.design](https://starry.design)
- [global.starry.design](https://global.starry.design)
- [Download](https://starry.design/download.html)
- [Browser trial](https://trial.starry.design)

## 授權與開發者

- MIT — see [LICENSE](LICENSE).
- 由 SmartAly (Aly) 以獨立開發者身分開發與維護。

---

*Starry — AI 原生設計，從畫布到程式碼。*
