[English](README.md) · [简体中文](README.zh-CN.md) · [繁體中文](README.zh-TW.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Deutsch](README.de.md) · [Español](README.es.md) · [Français](README.fr.md) · [Italiano](README.it.md) · [Polski](README.pl.md) · **Русский** · [Português (Brasil)](README.pt-BR.md) · [हिन्दी](README.hi.md)

# Starry — Твой ИИ-партнёр по дизайну

<p align="center"><img src="assets/cover-editor.jpg" alt="Starry canvas — an AI-generated bold personal landing page" width="100%"></p>

> Инструмент для дизайна, созданный для работы с ИИ. Локально в первую очередь, на базе ACP и MCP — превращает естественный язык в точные UI-спецификации и production-код.

[![Website](assets/badges/website.svg)](https://starry.design)
[![Try free in browser](assets/badges/trial.svg)](https://trial.starry.design)
[![Global](assets/badges/global.svg)](https://global.starry.design)
[![MCP](assets/badges/mcp.svg)](https://starry.design)
[![Export](assets/badges/export.svg)](https://starry.design/design-to-code.html)
[![Languages](assets/badges/langs.svg)](https://starry.design)
[![License](assets/badges/license.svg)](LICENSE)

---

## Скачать Starry

- [Скачать для macOS](https://starry.design/download.html) — macOS
- [Попробовать в браузере](https://trial.starry.design)
- Сайт: [starry.design](https://starry.design) · Глобальный сайт: [global.starry.design](https://global.starry.design)

## Переосмыслите свой рабочий процесс ИИ-дизайна

Starry переосмысляет рабочий процесс, делая холст умным, проверяемым и незаметно связанным с вашей кодовой базой.

| Функция | Описание |
|---|---|
| **Холст с ИИ** | На базе Agent Client Protocol (ACP). Общайтесь с холстом напрямую. ИИ нативно читает, пишет и генерирует дизайн-системы с авто-раскладкой из естественного языка. |
| **Сервер MCP** | Бесшовно подключается к ИИ-инструментам для кода, таким как Cursor и Claude, через Model Context Protocol. Мгновенно генерирует точный UI-код, не покидая редактор. |
| **CLI для CI/CD** | Файлы дизайна — это код. Используйте CLI для пакетного экспорта ассетов, обнаружения нарушений типографики и сравнения изменений дизайна автоматически при ревью кода. |
| **Полная совместимость данных с Figma** | Starry всегда синхронизирован с Figma. Скопируйте с одного холста и вставьте в другой — фреймы, текст, компоненты и стили переносятся с полной точностью. Без привязки, без чёрного ящика. |

## Starry превращает одну фразу в интерфейс

Никакого кода, никакого пустого холста — опишите интерфейс, который вам нужен, и ИИ Starry сгенерирует его для вас.

| Сценарий | Почему |
|---|---|
| UI SaaS / веб-приложения (настройки, CRUD, формы) | Их строит каждая софтверная команда — авто-лейаут и прямой экспорт в React (JSX) держат цикл максимально коротким. |
| Маркетинговый лендинг / сайт | Маст-хэв для любого продукта и стартапа — одно предложение на входе, HTML/React на выходе. |
| Дашборд данных / админ-панель | Крупнейшая категория в B2B — таблицы, карточки и графики — всё это сильные стороны авто-лейаута. |
| UI мобильного приложения (вход, e-commerce, онбординг) | Огромный спрос — позиционируется как дизайн + прототип с экспортом в HTML для передачи. |
| Дизайн-система / библиотека компонентов | 'Сгенерируй дизайн-систему на естественном языке' — самый дифференцирующий козырь. |
| Быстрый прототип / валидация MVP | Промпт → интерфейс → код: самый быстрый путь для инди-разработчиков и PM проверить идеи. |

## Дизайны, которые генерирует Starry

От одного промпта до экранов, готовых к релизу. Каждый результат сохраняет пиксельное соответствие с вашей кодовой базой.

| ![](assets/editor-landing.jpg) | ![](assets/editor-mobile.jpg) |
|---|---|
| *Маркетинговый лендинг* | *Мобильный экран* |

## Чем Starry отличается

| | Starry | Figma | Stitch | Sketch |
|---|---|---|---|---|
| Генерация ИИ | 1 sentence → UI | Вручную + Figma AI | Text to UI | Вручную + Sketch AI |
| Передача | 0 rework · React (JSX) и HTML | Только спецификации, без компонентов | Фрагменты кода | Sketch / PDF |
| Миграция | Native .fig import | —（это Figma） | Нет нативного импорта | Импортирует Figma |
| Простота использования | 0 learning curve | Изучить холст | 0 (text) | Изучить Sketch |
| Интеграция ИИ | MCP → editor · ACP → agents | Нет | Нет | Нет |
| Совместная работа | Real-time (WebRTC) | В реальном времени | В реальном времени | В реальном времени |
| Цены | Free | $12+/editor | Free | $10/editor |

> Точность проверена авг 2026. Функции могут меняться — уточняйте на сайте каждого поставщика.

## Часто задаваемые вопросы

**Может ли Starry сгенерировать интерфейс с помощью ИИ?**

Да. Опишите своими словами, что хотите получить, и ИИ Starry сгенерирует интерфейс - макет, компоненты и авто-раскладку - и экспортирует готовый к производству код (React (JSX) и HTML). Это настоящий, редактируемый и запускаемый UI, а не статичный макет.

**Могу ли я импортировать свои существующие файлы Figma?**

Да. Starry напрямую импортирует нативные файлы .fig — векторы, текст и стили сохраняются полностью, и вы можете продолжать правки в любом инструменте.

**В какие фреймворки можно экспортировать?**

React (JSX) и чистый HTML — все с соответствием вёрстки между холстом и сгенерированным кодом. Результат принадлежит вашей кодовой базе.

**Как работает интеграция MCP?**

Starry запускает MCP-сервер, который даёт ИИ-инструментам для кода, таким как Cursor, Claude Code и Codex, доступ на чтение и запись к холсту. Генерируйте UI-код из редактора, не переключая контекст.

**Мои данные дизайна приватны?**

Starry отдаёт приоритет локальности. По умолчанию ваши файлы остаются на вашем компьютере и могут версионироваться через Git. Облачная совместная работа опциональна и шифруется сквозным шифрованием.

**Где скачать?**

Скачайте приложение для macOS на starry.design или откройте браузерную версию на trial.starry.design — без установки и регистрации.

## Содержимое репозитория

Стартовые промпты, спецификации дизайн-системы и примеры для Starry. Исходного кода приложения здесь нет — приложение остаётся закрытым.

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

## Как использовать

1. Откройте Starry — десктопное приложение или браузерную версию.
2. Вставьте спецификацию дизайн-системы из `design-systems/`, затем промпт из `prompts/`.
3. Starry создаст редактируемые слои auto-layout — экспортируйте в React (JSX) или HTML.

## Ссылки

- [starry.design](https://starry.design)
- [global.starry.design](https://global.starry.design)
- [Download](https://starry.design/download.html)
- [Browser trial](https://trial.starry.design)

## Лицензия и разработчик

- MIT — see [LICENSE](LICENSE).
- Разрабатывается и поддерживается SmartAly (Aly) как независимый проект.

---

*Starry — ИИ-нативный дизайн: от холста до кода.*
