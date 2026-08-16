# Starry Templates & Examples

> 📦 This is the **official public examples repository** for [Starry](https://starry.design) — an AI-native design tool.

A small, public collection of starter prompts, design-system specs, and example
projects you can drop into [Starry](https://starry.design) to go from idea to
editable UI fast.

> This repo is **public and safe to share**. It contains only Markdown specs and
> prompt files — no Starry application source code (the app itself stays private).

## What's inside

```
starry-templates/
├── README.md
├── design-systems/
│   └── base-ui.md        # a sample Markdown design-system spec
└── prompts/
    └── landing-page.md   # a copy-paste prompt to generate a landing page
```

## How to use

1. Open [Starry](https://starry.design) (desktop app or web).
2. For a **design system**: paste the contents of `design-systems/base-ui.md`
   into Starry's design-system field so every generation follows your tokens.
3. For a **screen**: copy a prompt from `prompts/` into the canvas input.
4. Starry builds editable, auto-layout layers — then export to React (JSX) or HTML.

## Why Markdown specs?

In Starry, design systems are Markdown specs injected into every generation.
That means a design system is just text you can version-control, review in PRs,
and reuse across projects — exactly like code.

## Contributing

PRs welcome: add a prompt, a component spec, or a small example. Keep files
Markdown-only so they stay portable and readable.

## License

MIT — use freely, attribute if you like.
