[English](README.md) · [简体中文](README.zh-CN.md) · [繁體中文](README.zh-TW.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Deutsch](README.de.md) · [Español](README.es.md) · [Français](README.fr.md) · [Italiano](README.it.md) · [Polski](README.pl.md) · [Русский](README.ru.md) · **Português (Brasil)** · [हिन्दी](README.hi.md)

# Starry — Seu parceiro de design IA

<p align="center"><img src="assets/cover-editor.jpg" alt="Starry canvas — AI repairing a lost image node in a Y2K portfolio design" width="100%"></p>

> A ferramenta de design criada para colaboração com IA. Local primeiro, com ACP e MCP — transforma linguagem natural em especificações UI precisas e código de produção.

[![Website](assets/badges/website.svg)](https://starry.design)
[![Try free in browser](assets/badges/trial.svg)](https://trial.starry.design)
[![Global](assets/badges/global.svg)](https://global.starry.design)
[![MCP](assets/badges/mcp.svg)](https://starry.design)
[![Export](assets/badges/export.svg)](https://starry.design/design-to-code.html)
[![Languages](assets/badges/langs.svg)](https://starry.design)
[![License](assets/badges/license.svg)](LICENSE)

---

## Baixar Starry

- [Baixar para macOS](https://starry.design/download.html) — macOS
- [Testar no navegador](https://trial.starry.design)
- Site: [starry.design](https://starry.design) · Site global: [global.starry.design](https://global.starry.design)

## Redefina seu fluxo de trabalho de design com IA

Starry redefiniu o fluxo de trabalho tornando a tela inteligente, verificável e perfeitamente conectada ao seu codebase.

| Recurso | Descrição |
|---|---|
| **Tela dirigida por IA** | Baseada no Agent Client Protocol (ACP). Converse diretamente com a tela. A IA lê, escreve e gera nativamente sistemas de design com auto layout a partir de linguagem natural. |
| **Servidor MCP** | Conecta-se perfeitamente a ferramentas de coding com IA como Cursor e Claude via Model Context Protocol. Gere código UI preciso instantaneamente sem sair do editor. |
| **CLI para CI/CD** | Arquivos de design são código. Use a CLI para exportar assets em lote, detectar violações tipográficas e comparar mudanças de design automaticamente durante a revisão de código. |
| **Paridade total de dados com Figma** | O Starry permanece perfeitamente sincronizado com o Figma. Copie de uma tela, cole na outra — quadros, textos, componentes e estilos se conservam com total fidelidade. Sem lock-in, sem caixa preta. |

## Starry transforma uma frase em uma interface

Sem código, sem tela em branco — descreva a interface que você quer e a IA da Starry a gera para você.

| Cenário | Por quê |
|---|---|
| UI de SaaS / app web (configurações, CRUD, formulários) | Toda equipe de software constrói isso — o auto-layout e a exportação direta para React (JSX) mantêm o ciclo mais curto. |
| Landing page de marketing / site | Essencial para todo produto e startup — uma frase entra, HTML/React sai. |
| Dashboard de dados / painel administrativo | A maior categoria no B2B — tabelas, cartões e gráficos são pontos fortes do auto-layout. |
| UI de app mobile (login, e-commerce, onboarding) | Demanda enorme — posicionado como design + protótipo, com exportação HTML para entrega. |
| Sistema de design / biblioteca de componentes | 'Gere um design system a partir de linguagem natural' — o diferencial mais forte. |
| Protótipo rápido / validação de MVP | Prompt → interface → código: o caminho mais rápido para devs independentes e PMs validarem ideias. |

## Designs que o Starry gera

De um único prompt a telas prontas para produção. Cada saída mantém paridade pixel a pixel com sua base de código.

| ![](assets/editor-landing.jpg) | ![](assets/editor-mobile.jpg) |
|---|---|
| *Landing page de marketing* | *Tela mobile* |

## Como o Starry se compara

| | Starry | Figma | Stitch | Sketch |
|---|---|---|---|---|
| Geração por IA | 1 sentence → UI | Manual + Figma AI | Text to UI | Manual + Sketch AI |
| Entrega | 0 rework · React (JSX) e HTML | Apenas especificações, sem componentes | Trechos de código | Sketch / PDF |
| Migração | Native .fig import | —（é o Figma） | Sem importação nativa | Importa Figma |
| Facilidade de uso | 0 learning curve | Aprender a tela | 0 (text) | Aprender Sketch |
| Integração de IA | MCP → editor · ACP → agents | Nenhuma | Nenhuma | Nenhuma |
| Colaboração | Real-time (WebRTC) | Tempo real | Tempo real | Tempo real |
| Preços | Free | $12+/editor | Free | $10/editor |

> Precisão verificada ago 2026. A disponibilidade de recursos pode mudar — confira no site de cada fornecedor.

## Perguntas frequentes

**O Starry consegue gerar uma interface com IA?**

Sim. Descreva o que quer em linguagem natural e a IA do Starry gera a interface - layout, componentes e auto-layout - e exporta código pronto para produção (React (JSX) e HTML). É uma UI real, editável e executável, não um mockup estático.

**Posso importar meus arquivos Figma existentes?**

Sim. Starry importa arquivos nativos .fig - vetores, texto e estilos são preservados fielmente, e você pode continuar ajustando em qualquer uma das ferramentas.

**Para quais frameworks posso exportar?**

React (JSX) e HTML puro — todos com paridade de layout entre o canvas e o código gerado. Sua base de código é dona do resultado.

**Como funciona a integração MCP?**

O Starry executa um servidor MCP que dá a ferramentas de IA como Cursor, Claude Code e Codex acesso de leitura e escrita ao canvas. Gere código de UI no seu editor sem trocar de contexto.

**Meus dados de design são privados?**

O Starry é local-first. Seus arquivos ficam na sua máquina por padrão e podem ser versionados com Git. A colaboração na nuvem é opcional e criptografada de ponta a ponta.

**Onde baixar?**

Baixe o app para macOS em starry.design ou abra a versão de teste no navegador em trial.starry.design — sem instalação e sem cadastro.

## Conteúdo do repositório

Prompts iniciais, especificações de design system e exemplos prontos para o Starry. Sem código-fonte da aplicação — o app permanece privado.

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

## Como usar

1. Abra o Starry — app desktop ou a versão de teste no navegador.
2. Cole uma especificação de design system de `design-systems/` e depois um prompt de `prompts/`.
3. O Starry gera camadas editáveis com auto-layout — exporte para React (JSX) ou HTML.

## Links

- [starry.design](https://starry.design)
- [global.starry.design](https://global.starry.design)
- [Download](https://starry.design/download.html)
- [Browser trial](https://trial.starry.design)

## Licença e desenvolvedor

- MIT — see [LICENSE](LICENSE).
- Desenvolvido e mantido por SmartAly (Aly) como projeto de desenvolvedor independente.

---

*Starry — Design nativo de IA, do canvas ao código.*
