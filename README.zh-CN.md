[English](README.md) · **简体中文** · [繁體中文](README.zh-TW.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Deutsch](README.de.md) · [Español](README.es.md) · [Français](README.fr.md) · [Italiano](README.it.md) · [Polski](README.pl.md) · [Русский](README.ru.md) · [Português (Brasil)](README.pt-BR.md) · [हिन्दी](README.hi.md)

# Starry — 你的AI设计伙伴

<p align="center"><img src="assets/cover-editor.jpg" alt="Starry canvas — AI repairing a lost image node in a Y2K portfolio design" width="100%"></p>

> AI原生设计产品研发工具。本地优先，基于 ACP 与 MCP 协议，将自然语言、精确 UI 规范与生产代码无缝打通。

[![Website](assets/badges/website.svg)](https://starry.design)
[![Try free in browser](assets/badges/trial.svg)](https://trial.starry.design)
[![Global](assets/badges/global.svg)](https://global.starry.design)
[![MCP](assets/badges/mcp.svg)](https://starry.design)
[![Export](assets/badges/export.svg)](https://starry.design/design-to-code.html)
[![Languages](assets/badges/langs.svg)](https://starry.design)
[![License](assets/badges/license.svg)](LICENSE)

---

## 下载 Starry

- [下载 macOS 版](https://starry.design/download.html) — macOS
- [在浏览器中试用](https://trial.starry.design)
- 官网: [starry.design](https://starry.design) · 全球站: [global.starry.design](https://global.starry.design)

## 重新定义你的AI设计工作流

Starry 让画布变得智能、可校验，并与代码库无缝连接，重新定义设计工作流。

| 能力 | 说明 |
|---|---|
| **AI 驱动画布** | 基于 Agent Client Protocol（ACP），直接与画布对话。AI 原生读写画布，从自然语言生成自动布局设计系统。 |
| **MCP 服务器** | 通过 Model Context Protocol 无缝接入 Cursor、Claude 等 AI 编程工具，无需离开编辑器即可生成精确的 UI 代码。 |
| **CLI 接入 CI/CD** | 设计文件即代码。使用 CLI 批量导出资源、检测排版违规，并在代码评审中自动对比设计变更。 |
| **与 Figma 完全数据互通** | Starry 与 Figma 始终保持同步。从一个画布复制，粘贴到另一个——画板、文字、组件与样式完整保留，没有锁定，也没有黑盒。 |

## Starry 用一句话生成界面

不用写代码，也不用从空白画布开始——描述你想要的界面，Starry 的 AI 直接把它生成出来。

| 场景 | 为什么适合 |
|---|---|
| SaaS / Web App 产品界面（设置页、CRUD、表单） | 所有软件团队都要做，auto-layout + 直出 React (JSX) ，闭环最短。 |
| 营销落地页 / 官网 | 每个产品和创业公司的刚需，一句话生成，直接导出 HTML/React。 |
| 数据看板 / 管理后台 | B2B 与内部工具的最大品类，表格、卡片、图表都是 auto-layout 强项。 |
| 移动端 App 界面（登录、电商、Onboarding） | 需求量极大，定位「设计 + 原型」，导出 HTML 直接交付。 |
| 设计系统 / 组件库 | 「用自然语言生成设计系统」，差异化最强的一张牌。 |
| 快速原型 / MVP 验证 | 提示词→界面→代码，独立开发者与 PM 验证想法的最快路径。 |

## Starry 生成的设计

从一句话到可上线的界面。每一次输出都与你的代码库保持像素级一致。

| ![](assets/editor-landing.jpg) | ![](assets/editor-mobile.jpg) |
|---|---|
| *营销落地页* | *移动端界面* |

## Starry 对比一览

| | Starry | Figma | Stitch | Sketch |
|---|---|---|---|---|
| AI 生成 | 1 句话 → 界面 | 手动 + Figma AI | 文字生成 | 手动绘制 |
| 交付 | 0 返工 · React (JSX) 和 HTML | 仅标注，无组件 | 代码片段 | Sketch / PDF 导出 |
| 迁移 | 原生 .fig 导入 | —（它就是 Figma） | 无原生导入 | 可导入 Figma 文件 |
| 上手门槛 | 0 学习成本 | 需学画布 | 0（文字） | 需学 Sketch |
| AI 集成 | MCP 连编辑器 · ACP 托管智能体 | 无 | 无 | 无 |
| 协作 | 实时（WebRTC） | 实时 | 实时 | 实时 |
| 价格 | 免费 | $12+/人/月 | 免费 | $10/人/月 |

> 准确性核对于 2026 年 8 月。功能可能变动，请以各官网为准。

## 常见问题解答

**Starry能用AI直接生成界面吗？**

能。用大白话描述需求，Starry 的 AI 生成界面——布局、组件、自动布局一步到位，并直接导出生产级代码（React (JSX) 和 HTML）。它是真实、可编辑、可运行的 UI，不是静态稿。

**导出的代码能直接用到我的项目里吗？**

能。Starry 导出干净的生产级代码（React (JSX) 和 HTML），画布与代码布局一致。代码完全归你，直接放进项目即可，不被锁定。

**我已有的 Figma 设计能导进来吗？**

能。Starry 可直接导入 .fig 文件，矢量、文字与样式都能完整保留，你也能在两个工具间继续微调。

**我能在 Codex、Claude、Cursor 中用 Starry 吗？**

能。Starry 内置 MCP 服务，让 Cursor、Claude Code、Codex 等 AI 编码工具直接读写你的画布——不用切换工具，就能在编辑器里生成界面代码。

**我的设计数据安全吗？**

安全。Starry 默认本地优先：文件存在你本机，可用 Git 管理版本；云端协作是可选的，且端到端加密。

**在哪里获取？**

在 starry.design 下载 macOS 应用，或打开 trial.starry.design 直接在浏览器试用 —— 无需安装、无需注册。

## 仓库内容

可直接用于 Starry 的提示词、设计系统规范与示例。不含应用源码 —— 应用本身不开源。

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
    └── design-to-code.md     # export pipeline & guarantees
```

## 如何使用

1. 打开 Starry —— 桌面应用或浏览器试用版。
2. 把 `design-systems/` 里的设计系统规范粘贴进去，再粘贴 `prompts/` 里的提示词。
3. Starry 会生成可编辑的自动布局图层 —— 导出 React (JSX) 或 HTML。

## 链接

- [starry.design](https://starry.design)
- [global.starry.design](https://global.starry.design)
- [Download](https://starry.design/download.html)
- [Browser trial](https://trial.starry.design)

## 许可与开发者

- MIT — see [LICENSE](LICENSE).
- 由 SmartAly (Aly) 以独立开发者身份开发与维护。

---

*Starry — AI 原生设计，从画布到代码。*
