[English](README.md) · [简体中文](README.zh-CN.md) · [繁體中文](README.zh-TW.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Deutsch](README.de.md) · [Español](README.es.md) · [Français](README.fr.md) · [Italiano](README.it.md) · **Polski** · [Русский](README.ru.md) · [Português (Brasil)](README.pt-BR.md) · [हिन्दी](README.hi.md)

# Starry — Twój partner projektowy AI

<p align="center"><img src="assets/cover-editor.jpg" alt="Starry canvas — an AI-generated bold personal landing page" width="100%"></p>

> Narzędzie do projektowania stworzone do współpracy z AI. Lokalnie przede wszystkim, oparte na ACP i MCP — zamienia język naturalny w precyzyjne specyfikacje UI i kod produkcyjny.

[![Website](assets/badges/website.svg)](https://starry.design)
[![Try free in browser](assets/badges/trial.svg)](https://trial.starry.design)
[![Global](assets/badges/global.svg)](https://global.starry.design)
[![MCP](assets/badges/mcp.svg)](https://starry.design)
[![Export](assets/badges/export.svg)](https://starry.design/design-to-code.html)
[![Languages](assets/badges/langs.svg)](https://starry.design)
[![License](assets/badges/license.svg)](LICENSE)

---

## Pobierz Starry

- [Pobierz dla macOS](https://starry.design/download.html) — macOS
- [Wypróbuj w przeglądarce](https://trial.starry.design)
- Strona: [starry.design](https://starry.design) · Strona globalna: [global.starry.design](https://global.starry.design)

## Przedefiniuj swój workflow projektowania AI

Starry redefiniuje przepływ pracy, czyniąc płótno inteligentnym, weryfikowalnym i płynnie połączonym z Twoją bazą kodu.

| Funkcja | Opis |
|---|---|
| **Płótno sterowane przez AI** | Oparte na Agent Client Protocol (ACP). Rozmawiaj bezpośrednio z płótnem. AI natywnie czyta, zapisuje i generuje systemy projektowe z autoukładem z języka naturalnego. |
| **Serwer MCP** | Łączy się płynnie z narzędziami kodującymi AI, takimi jak Cursor i Claude, przez Model Context Protocol. Generuje dokładny kod UI natychmiast, bez opuszczania edytora. |
| **CLI dla CI/CD** | Pliki projektowe to kod. Użyj CLI, aby eksportować zasoby wsadowo, wykrywać naruszenia typografii i porównywać zmiany projektu automatycznie podczas przeglądu kodu. |
| **Pełna zgodność danych z Figma** | Starry pozostaje w pełnej synchronizacji z Figmą. Skopiuj z jednego płótna, wklej do drugiego — ramki, tekst, komponenty i style przenoszą się z pełną wiernością. Bez lock-in, bez czarnej skrzynki. |

## Starry zamienia jedno zdanie w interfejs

Bez kodu, bez pustego płótna — opisz interfejs, który chcesz, a AI Starry wygeneruje go za ciebie.

| Scenariusz | Dlaczego |
|---|---|
| UI SaaS / aplikacji web (ustawienia, CRUD, formularze) | Każdy zespół programistów to buduje — auto-layout i bezpośredni eksport do React (JSX) utrzymują najkrótszą pętlę. |
| Strona docelowa / strona marketingowa | Must-have dla każdego produktu i startupu — jedno zdanie wchodzi, HTML/React wychodzi. |
| Dashboard danych / panel administracyjny | Największa kategoria w B2B — tabele, karty i wykresy to mocne strony auto-layoutu. |
| UI aplikacji mobilnej (logowanie, e-commerce, onboarding) | Ogromny popyt — pozycjonowane jako design + prototyp, z eksportem HTML do przekazania. |
| System projektowy / biblioteka komponentów | 'Wygeneruj system projektowy z języka naturalnego' — najbardziej zróżnicowany atut. |
| Szybki prototyp / walidacja MVP | Prompt → interfejs → kod: najszybsza ścieżka dla niezależnych devów i PM-ów do walidacji pomysłów. |

## Projekty generowane przez Starry

Od pojedynczego promptu do ekranów gotowych do produkcji. Każdy wynik zachowuje pikselową zgodność z Twoją bazą kodu.

| ![](assets/editor-landing.jpg) | ![](assets/editor-mobile.jpg) |
|---|---|
| *Landing marketingowy* | *Ekran mobilny* |

## Jak wypada Starry

| | Starry | Figma | Stitch | Sketch |
|---|---|---|---|---|
| Generowanie przez AI | 1 sentence → UI | Ręcznie + Figma AI | Text to UI | Ręcznie + Sketch AI |
| Przekazanie | 0 rework · React (JSX) i HTML | Tylko specyfikacje, brak komponentów | Fragmenty kodu | Sketch / PDF |
| Migracja | Native .fig import | —（to Figma） | Brak natywnego importu | Importuje Figma |
| Łatwość obsługi | 0 learning curve | Nauka płótna | 0 (text) | Nauka Sketch |
| Integracja AI | MCP → editor · ACP → agents | Brak | Brak | Brak |
| Współpraca | Real-time (WebRTC) | Czas rzeczywisty | Czas rzeczywisty | Czas rzeczywisty |
| Cennik | Free | $12+/editor | Free | $10/editor |

> Dokładność sprawdzona sie 2026. Dostępność funkcji może się zmienić — sprawdź na stronie każdego dostawcy.

## Często zadawane pytania

**Czy Starry może wygenerować interfejs za pomocą AI?**

Tak. Opisz własnymi słowami, czego potrzebujesz, a AI Starry wygeneruje interfejs - układ, komponenty i auto-layout - i wyeksportuje gotowy do produkcji kod (React (JSX) i HTML). To prawdziwy, edytowalny i uruchamialny interfejs, a nie statyczny mockup.

**Czy mogę zaimportować moje istniejące pliki Figma?**

Tak. Starry importuje natywne pliki .fig - wektory, tekst i style zachowują się wiernie, a Ty możesz dalej dopieszczać w dowolnym narzędziu.

**Do jakich frameworków mogę eksportować?**

React (JSX) i czysty HTML — wszystkie z zgodnością układu między płótnem a wygenerowanym kodem. Wynik należy do Twojej bazy kodu.

**Jak działa integracja MCP?**

Starry uruchamia serwer MCP, który daje narzędziom AI do kodowania, takim jak Cursor, Claude Code i Codex, dostęp do odczytu i zapisu płótna. Generuj kod UI z edytora bez przełączania kontekstu.

**Czy moje dane projektowe są prywatne?**

Starry jest local-first. Twoje pliki domyślnie pozostają na Twoim komputerze i można je wersjonować przez Git. Współpraca w chmurze jest opcjonalna i szyfrowana end-to-end.

**Gdzie to pobrać?**

Pobierz aplikację macOS ze starry.design albo otwórz wersję przeglądarkową na trial.starry.design — bez instalacji i rejestracji.

## Zawartość repozytorium

Prompty startowe, specyfikacje design systemu i przykłady gotowe do użycia w Starry. Bez kodu źródłowego aplikacji — aplikacja pozostaje zamknięta.

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

## Jak używać

1. Otwórz Starry — aplikację desktopową albo wersję w przeglądarce.
2. Wklej specyfikację design systemu z `design-systems/`, potem prompt z `prompts/`.
3. Starry tworzy edytowalne warstwy auto-layout — wyeksportuj jako React (JSX) lub HTML.

## Linki

- [starry.design](https://starry.design)
- [global.starry.design](https://global.starry.design)
- [Download](https://starry.design/download.html)
- [Browser trial](https://trial.starry.design)

## Licencja i twórca

- MIT — see [LICENSE](LICENSE).
- Rozwijane i utrzymywane przez SmartAly (Aly) jako niezależny projekt deweloperski.

---

*Starry — Projektowanie natywne dla AI, od płótna do kodu.*
