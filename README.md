**English** · [简体中文](README.zh-CN.md) · [繁體中文](README.zh-TW.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Deutsch](README.de.md) · [Español](README.es.md) · [Français](README.fr.md) · [Italiano](README.it.md) · [Polski](README.pl.md) · [Русский](README.ru.md) · [Português (Brasil)](README.pt-BR.md) · [हिन्दी](README.hi.md)

# Starry — Your AI design partner.

<p align="center"><img src="assets/cover-editor.jpg" alt="Starry canvas — AI repairing a lost image node in a Y2K portfolio design" width="100%"></p>

> The design tool built for AI collaboration. Local-first, powered by ACP & MCP — turning natural language into precise UI specs and production code.

[![Website](assets/badges/website.svg)](https://starry.design)
[![Try free in browser](assets/badges/trial.svg)](https://trial.starry.design)
[![Global](assets/badges/global.svg)](https://global.starry.design)
[![MCP](assets/badges/mcp.svg)](https://starry.design)
[![Export](assets/badges/export.svg)](https://starry.design/design-to-code.html)
[![Languages](assets/badges/langs.svg)](https://starry.design)
[![License](assets/badges/license.svg)](LICENSE)

---

## Download Starry

- [Download for macOS](https://starry.design/download.html) — macOS
- [Try it in your browser](https://trial.starry.design)
- Website: [starry.design](https://starry.design) · Global site: [global.starry.design](https://global.starry.design)

## Redefine your AI design workflow

Starry redefines the workflow by making the canvas intelligent, verifiable, and seamlessly connected to your codebase.

| Feature | Description |
|---|---|
| **AI-Driven Canvas** | Powered by the Agent Client Protocol (ACP). Chat directly with the canvas. AI natively reads, writes, and generates auto-layout design systems from natural language. |
| **MCP Server** | Connects seamlessly to AI coding tools like Cursor and Claude via the Model Context Protocol. Generate accurate UI code instantly without leaving your editor. |
| **CLI for CI/CD** | Design files are code. Use the CLI to batch-export assets, detect typography violations, and diff design changes automatically during code review. |
| **Full data parity with Figma** | Starry stays in perfect sync with Figma. Copy from one canvas, paste into the other — frames, text, components, and styles land with full fidelity. No lock-in, no black box. |

## Starry turns a sentence into an interface

No code, no blank canvas — describe the interface you want, and Starry's AI generates it for you.

| Scenario | Why it fits |
|---|---|
| SaaS / Web App UI (settings, CRUD, forms) | Every software team builds these — auto-layout plus direct React (JSX) export keeps the loop shortest. |
| Marketing landing page / website | A must-have for every product and startup — one sentence in, HTML/React out. |
| Data dashboard / admin panel | The largest category in B2B — tables, cards and charts are all auto-layout strengths. |
| Mobile app UI (login, e-commerce, onboarding) | Huge demand — positioned as design + prototype, with HTML export for handoff. |
| Design system / component library | 'Generate a design system from natural language' — the most differentiated play. |
| Rapid prototype / MVP validation | Prompt → interface → code: the fastest path for indie devs and PMs to validate ideas. |

## Designs Starry generates

From a single prompt to production-ready screens. Every output keeps pixel-perfect parity with your codebase.

| ![](assets/editor-landing.jpg) | ![](assets/editor-mobile.jpg) |
|---|---|
| *Marketing landing* | *Mobile screen* |

## How Starry compares

| | Starry | Figma | Stitch | Sketch |
|---|---|---|---|---|
| AI generation | 1 sentence → UI | Manual + Figma AI | Text to UI | Manual + Sketch AI |
| Handoff | 0 rework · React (JSX) and HTML | Specs only, no components | Code snippets | Sketch / PDF |
| Migration | Native .fig import | — (it is Figma) | No native import | Imports Figma |
| Ease of use | 0 learning curve | Learn the canvas | 0 (text) | Learn Sketch |
| AI integration | MCP → editor · ACP → agents | None | None | None |
| Collaboration | Real-time (WebRTC) | Real-time | Real-time | Real-time |
| Pricing | Free | $12+/editor | Free | $10/editor |

> Accuracy checked Aug 2026. Feature availability may change — verify on each vendor's site.

## Frequently asked questions

**Can Starry use AI to generate an interface?**

Yes. Describe what you want in plain language and Starry's AI generates the interface - layout, components, and auto-layout - then exports production-ready code (React (JSX) and HTML). It's a real, editable, runnable UI, not a static mockup.

**Can I drop the exported code straight into my project?**

Yes. Starry exports clean, production-ready code (React (JSX) and HTML) with layout parity to the canvas. The code is yours - drop it into your project, no lock-in.

**Can I bring in my existing Figma designs?**

Yes. Starry imports native .fig files - vectors, text, and styles transfer faithfully, and you can keep refining in either tool.

**Can I use Starry from my own editor?**

Yes. Starry runs an MCP server so AI coding tools like Cursor, Claude Code, and Codex can read and write your canvas - generate UI code from your editor without switching context.

**Is my design data safe?**

Yes. Starry is local-first: files stay on your machine by default and work with Git. Cloud collaboration is optional and end-to-end encrypted.

**Where do I get it?**

Download the macOS app from starry.design, or open the browser trial at trial.starry.design — no install and no signup.

## What's in this repo

Starter prompts, design-system specs and examples you can drop into Starry. No application source code — the app itself stays private.

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

## How to use

1. Open Starry — the desktop app or the browser trial.
2. Paste a design-system spec from `design-systems/`, then a prompt from `prompts/`.
3. Starry builds editable auto-layout layers — export React (JSX) or HTML.

## Links

- [starry.design](https://starry.design)
- [global.starry.design](https://global.starry.design)
- [Download](https://starry.design/download.html)
- [Browser trial](https://trial.starry.design)

## License & developer

- MIT — see [LICENSE](LICENSE).
- Built and maintained by SmartAly (Aly) as an independent developer project.

---

*Starry — AI-native design, from canvas to code.*
