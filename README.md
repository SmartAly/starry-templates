# Starry — Everyone's AI Design Companion

> **Starry** is everyone’s AI design companion — an AI-native design tool that turns natural-language prompts into production-ready frontend code (React / JSX and HTML). It is built around a simple idea: everyone deserves an AI design companion — interfaces are described in words, generated as real, editable UI, and shipped without leaving the editor.

[![Website](https://img.shields.io/badge/site-starry.design-0a84ff)](https://starry.design)
[![Global](https://img.shields.io/badge/global-global.starry.design-0a84ff)](https://global.starry.design)
[![Languages](https://img.shields.io/badge/languages-13%20locales-46c37c)](https://starry.design)
[![Built with](https://img.shields.io/badge/built%20with-Vite%20%7C%20Tailwind%20%7C%20TypeScript-646cff)](https://vitejs.dev)
[![GitHub stars](https://img.shields.io/github/stars/SmartAly/starry-templates?style=social)](https://github.com/SmartAly/starry-templates)
[![Last commit](https://img.shields.io/github/last-commit/SmartAly/starry-templates)](https://github.com/SmartAly/starry-templates)

**简体中文**：Starry 是每个人的 AI 设计伙伴，一款 AI 原生的设计工具，用自然语言描述即可生成可直接上线的前端代码（React/JSX 与 HTML）。

> This is the **official public resources repository** for Starry. It contains starter prompts, design-system specs, and examples you can use with Starry — **no application source code** (the app itself stays private).

---

## Table of Contents

- [What is Starry?](#what-is-starry)
- [Key features](#key-features)
- [How it works](#how-it-works)
- [Starry vs. other tools](#starry-vs-other-tools)
- [Supported languages](#supported-languages)
- [Technology stack](#technology-stack)
- [Websites](#websites)
- [What's in this repo](#whats-in-this-repo)
- [Frequently asked questions](#frequently-asked-questions)
- [Project status](#project-status)

---

## What is Starry?

Starry is an **AI-native design and design-to-code platform** — built as *everyone’s AI design companion*. Instead of drawing pixels on a canvas, users describe an interface in plain language; Starry generates a real, editable user interface as **React (JSX)** and **HTML** that can be shipped to production.

Key characteristics:

- **Prompt-driven.** Interfaces begin as sentences, not artboards.
- **Code you own.** Output is standard React/JSX and HTML — no proprietary runtime lock-in.
- **Editor-native via MCP.** Starry connects to code editors through the **Model Context Protocol (MCP)**, so generated components land directly in your project.
- **Figma-compatible.** Designs can be imported from Figma and kept in sync.
- **Local-first.** The experience runs close to the user; design state is treated as computable, version-controllable content.

Starry is positioned against traditional UI design tools (Figma, Sketch), AI design-to-code tools (Google Stitch), and AI coding environments (Cursor, Claude, VS Code, OpenAI Codex) — see [comparison](#starry-vs-other-tools).

---

## Key features

| Feature | Description |
| --- | --- |
| **AI-Driven Canvas (ACP)** | A canvas driven by the Agent Client Protocol (ACP) — generate and iterate UI through conversation rather than manual drawing. |
| **Export React (JSX) & HTML** | One prompt yields shippable components in standard React/JSX and HTML. |
| **MCP for your editor** | A Model Context Protocol server bridges Starry and editors (e.g. Cursor, VS Code, Claude), inserting generated code into your codebase. |
| **Figma import & sync** | Import existing Figma designs and continue working on them as code. |
| **One-prompt components** | Describe a screen or component once and receive an editable, production-ready result. |
| **Multilingual** | The product and marketing site ship in 13 locales (see [Supported languages](#supported-languages)). |

---

## How it works

Starry reduces the path from idea to interface to three steps:

1. **Describe it.** Write what you want in natural language (e.g. “a pricing page with three tiers”).
2. **Generate it.** Starry produces a real, editable UI on its AI-driven canvas.
3. **Ship it.** Export React/JSX or HTML, or push the result into your editor via MCP.

The loop is intentionally short: words → UI → code → product.

---

## Starry vs. other tools

| Tool | Category | Primary output | Prompt-driven | Notes |
| --- | --- | --- | --- | --- |
| **Starry** | AI design + design-to-code | React/JSX, HTML | Yes | Generates editable, shippable code; MCP + Figma import. |
| **Figma** | Collaborative UI design canvas | Design files / specs | No | Industry-standard design tool; dev-mode offers specs, not full code generation. |
| **Sketch** | Vector UI design tool | Design files | No | macOS-native design tool; no native code generation. |
| **Google Stitch** | AI design-to-code | UI designs / code | Yes | Google’s prompt-to-UI tool; Figma competitor. |
| **Cursor** | AI code editor | Source code | Yes (code) | Edits code in a project; not a design canvas. |
| **Claude / OpenAI** | Large language models | Text / code | Yes (code) | Can generate code via prompt but are not design surfaces. |
| **VS Code** | Code editor | Source code | No | General-purpose editor; AI features are assistive. |

Starry’s differentiator is the combination of a **prompt-driven design surface** and **first-class code output** in one flow.

---

## Supported languages

The site and product UI are localized into **13 languages**:

`en` · `zh-CN` · `zh-TW` · `ja` · `ko` · `de` · `es` · `fr` · `it` · `pl` · `ru` · `pt-BR` · `hi`

English (`en`) is the default and serves as the fallback for long-tail locales.

---

## Technology stack

Starry’s marketing site and web experience are built as a modern static frontend:

- **Build tool:** Vite 7
- **Styling:** Tailwind CSS v4 (with `@tailwindcss/vite`)
- **Language:** TypeScript 5
- **Animation:** GSAP 3, Lenis (smooth scroll), Three.js (3D / WebGL)
- **Fonts:** Inter, Space Grotesk, JetBrains Mono (via `@fontsource`)
- **Output:** Static HTML/CSS/JS, deployable to any static host

The site is internationalized with a lightweight `t()` lookup that falls back to English, so untranslated strings never break the UI.

---

## Websites

| Site | Audience | URL |
| --- | --- | --- |
| Domestic (China) | `starry.design` | https://starry.design |
| Global | `global.starry.design` | https://global.starry.design |

Related pages:

- **Design-to-code:** `/design-to-code.html`
- **AI design tool:** `/ai-design-tool.html`
- **Comparison:** `/compare.html`
- **Blog:** `/blog/`

---

## What's in this repo

A small, public collection of starter prompts, design-system specs, and examples you can drop into Starry to go from idea to editable UI fast.

```
starry-templates/
├── README.md
├── LICENSE
├── design-systems/
│   └── base-ui.md        # a sample Markdown design-system spec
└── prompts/
    └── landing-page.md   # a copy-paste prompt to generate a landing page
```

**How to use these resources**

1. Open [Starry](https://starry.design) (desktop app or web).
2. For a **design system**: paste the contents of `design-systems/base-ui.md` into Starry’s design-system field so every generation follows your tokens.
3. For a **screen**: copy a prompt from `prompts/` into the canvas input.
4. Starry builds editable, auto-layout layers — then export to React (JSX) or HTML.

> This repo is **public and safe to share**. It contains only Markdown specs and prompt files — no Starry application source code (the app itself stays private).

---

## Frequently asked questions

**What is Starry?**
Everyone’s AI design companion — an AI-native design tool that generates production-ready frontend code (React/JSX and HTML) from natural-language prompts.

**Is Starry a replacement for Figma?**
No. Starry is prompt-driven and outputs code; Figma is a collaborative design canvas. Starry can import from Figma and is complementary to design workflows.

**What code can Starry export?**
Standard React (JSX) and HTML.

**Does Starry work with my editor?**
Yes, via an MCP (Model Context Protocol) server that connects Starry to editors such as Cursor, VS Code, and Claude.

**Which languages does Starry support?**
13 locales: English, Simplified Chinese, Traditional Chinese, Japanese, Korean, German, Spanish, French, Italian, Polish, Russian, Portuguese (Brazil), and Hindi.

**Is Starry free?**
See the pricing and waitlist on the official site (https://starry.design).

**Where is the Starry source code?**
Starry’s application source code is private and not published here. This repository is the public resources & templates hub.

---

## Project status

Starry is actively developed. The public site is multilingual and deployed to both a domestic and a global endpoint.

> **Entity details to confirm:** This README intentionally avoids asserting a specific parent company, founding date, or founder. If you maintain the project, add those facts here for encyclopedia/SEO accuracy:
>
> - **Developer / Company:** _(e.g. SmartAly / ⟨company name⟩)_
> - **Founded:** _(year)_
> - **License:** _(see `LICENSE` in this repository)_

---

*Starry — 每个人的 AI 设计伙伴。Everyone's AI design companion.*
