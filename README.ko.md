[English](README.md) · [简体中文](README.zh-CN.md) · [繁體中文](README.zh-TW.md) · [日本語](README.ja.md) · **한국어** · [Deutsch](README.de.md) · [Español](README.es.md) · [Français](README.fr.md) · [Italiano](README.it.md) · [Polski](README.pl.md) · [Русский](README.ru.md) · [Português (Brasil)](README.pt-BR.md) · [हिन्दी](README.hi.md)

# Starry — 당신의AI 디자인 파트너

<p align="center"><img src="assets/cover-editor.jpg" alt="Starry canvas — AI repairing a lost image node in a Y2K portfolio design" width="100%"></p>

> AI 협업을 위해 태어난 디자인 도구. 로컬 우선, ACP 및 MCP를 통해 자연어를 정밀한 UI 사양과 프로덕션 코드로 전환합니다.

[![Website](assets/badges/website.svg)](https://starry.design)
[![Try free in browser](assets/badges/trial.svg)](https://trial.starry.design)
[![Global](assets/badges/global.svg)](https://global.starry.design)
[![MCP](assets/badges/mcp.svg)](https://starry.design)
[![Export](assets/badges/export.svg)](https://starry.design/design-to-code.html)
[![Languages](assets/badges/langs.svg)](https://starry.design)
[![License](assets/badges/license.svg)](LICENSE)

---

## Starry 다운로드

- [macOS용 다운로드](https://starry.design/download.html) — macOS
- [브라우저에서 사용해 보기](https://trial.starry.design)
- 공식 사이트: [starry.design](https://starry.design) · 글로벌 사이트: [global.starry.design](https://global.starry.design)

## AI 디자인 워크플로를 재정의

Starry는 캔버스를 지능적이고 검증 가능하게 만들고 코드베이스와 원활하게 연결함으로써 워크플로를 재정의합니다.

| 기능 | 설명 |
|---|---|
| **AI 구동 캔버스** | Agent Client Protocol(ACP) 기반. 캔버스와 직접 대화하세요. AI가 자연어에서 자동 레이아웃 디자인 시스템을 네이티브하게 읽고, 쓰고, 생성합니다. |
| **MCP 서버** | Model Context Protocol을 통해 Cursor, Claude 같은 AI 코딩 도구와 원활하게 연결됩니다. 편집기를 떠나지 않고도 정확한 UI 코드를 즉시 생성합니다. |
| **CI/CD용 CLI** | 디자인 파일은 코드입니다. CLI를 사용하여 애셋을 일괄 내보내고, 타이포그래피 위반을 감지하고, 코드 리뷰 중 디자인 변경 사항을 자동으로 비교하세요. |
| **Figma와 완전한 데이터 호환** | Starry는 Figma와 항상 동기화됩니다. 한 캔버스에서 복사해 다른 쪽에 붙여넣으면——프레임, 텍스트, 컴포넌트, 스타일이 그대로 유지됩니다. 종속성도 블랙박스도 없습니다. |

## Starry는 한 문장으로 인터페이스를 만들어냅니다

코드를 작성할 필요도, 빈 캔버스에서 시작할 필요도 없습니다——원하는 인터페이스를 설명하기만 하면 Starry의 AI가 그것을 생성합니다.

| 시나리오 | 이유 |
|---|---|
| SaaS / 웹 앱 UI(설정, CRUD, 폼) | 모든 소프트웨어 팀이 만드는 것——오토레이아웃과 React (JSX) 직접 내보내기로 가장 짧은 루프를 유지합니다. |
| 마케팅 랜딩 페이지 / 웹사이트 | 모든 제품과 스타트업에 필수——한 문장 입력하면 HTML/React가 출력됩니다. |
| 데이터 대시보드 / 관리자 패널 | B2B에서 가장 큰 범주——표, 카드, 차트는 모두 오토레이아웃의 강점입니다. |
| 모바일 앱 UI(로그인, 이커머스, 온보딩) | 수요가 매우 큰——'디자인 + 프로토타입'으로 포지셔닝, HTML 내보내기로 인수인계. |
| 디자인 시스템 / 컴포넌트 라이브러리 | '자연어로 디자인 시스템 생성'——가장 차별화되는 카드입니다. |
| 빠른 프로토타입 / MVP 검증 | 프롬프트 → 화면 → 코드: 개인 개발자와 PM이 아이디어를 검증하는 가장 빠른 경로. |

## Starry가 생성하는 디자인

단 한 줄의 프롬프트에서 배포 가능한 화면까지. 모든 출력은 코드베이스와 픽셀 단위로 일치합니다.

| ![](assets/editor-landing.jpg) | ![](assets/editor-mobile.jpg) |
|---|---|
| *마케팅 랜딩* | *모바일 화면* |

## Starry 비교

| | Starry | Figma | Stitch | Sketch |
|---|---|---|---|---|
| AI 생성 | 1 sentence → UI | 수동 + Figma AI | Text to UI | 수동 + Sketch AI |
| 핸드오프 | 0 rework · React (JSX) 및 HTML | 사양만 제공, 컴포넌트 없음 | 코드 스니펫 | Sketch / PDF |
| 마이그레이션 | Native .fig import | —（Figma 자체） | 네이티브 가져오기 없음 | Figma 가져오기 |
| 사용 편의성 | 0 learning curve | 캔버스 학습 필요 | 0 (text) | Sketch 학습 필요 |
| AI 연동 | MCP → editor · ACP → agents | 없음 | 없음 | 없음 |
| 협업 | Real-time (WebRTC) | 실시간 | 실시간 | 실시간 |
| 가격 | Free | $12+/editor | Free | $10/editor |

> 정확성은 2026년 8월 기준 확인. 기능은 변경될 수 있으니 각 공급업체 사이트에서 확인하세요.

## 자주 묻는 질문

**Starry가 AI로 인터페이스를 생성할 수 있나요?**

네. 원하는 것을 일상적인 말로 설명하면 Starry의 AI가 인터페이스를 생성합니다 — 레이아웃, 컴포넌트, 자동 레이아웃까지. 그리고 바로 사용 가능한 코드(React (JSX) 및 HTML)를 출력합니다. 편집·실행 가능한 진짜 UI입니다.

**내보낸 코드를 바로 내 프로젝트에 쓸 수 있나요?**

네. Starry는 깔끔한 프로덕션용 코드(React (JSX) 및 HTML)를 내보내며 캔버스와 레이아웃이 일치합니다. 코드는 당신의 것이라 그대로 프로젝트에 넣으면 되고, 종속성에 묶이지 않습니다.

**기존 Figma 디자인을 가져올 수 있나요?**

네. Starry는 네이티브 .fig 파일을 바로 가져오며 벡터, 텍스트, 스타일이 그대로 유지되어 어느 도구에서든 조정을 이어갈 수 있습니다.

**내 에디터에서 Starry를 쓸 수 있나요?**

네. Starry는 MCP 서버를 내장해 Cursor, Claude Code, Codex 같은 AI 코딩 도구가 캔버스를 직접 읽고 쓸 수 있습니다—도구를 전환하지 않고 에디터에서 UI 코드를 생성하세요.

**내 디자인 데이터는 안전한가요?**

안전합니다. Starry는 로컬 우선입니다—파일은 기본적으로 내 컴퓨터에 저장되고 Git으로 버전 관리할 수 있습니다. 클라우드 협업은 선택이며 엔드투엔드 암호화됩니다.

**어디서 받을 수 있나요?**

starry.design에서 macOS 앱을 내려받거나, trial.starry.design에서 설치·가입 없이 브라우저로 바로 써볼 수 있습니다.

## 저장소 구성

Starry에 바로 쓸 수 있는 프롬프트, 디자인 시스템 스펙, 예시 모음. 앱 소스 코드는 포함하지 않습니다(앱은 비공개).

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

## 사용법

1. Starry를 엽니다(데스크톱 앱 또는 브라우저 체험판).
2. `design-systems/` 의 디자인 시스템 스펙을 붙여넣고, `prompts/` 의 프롬프트를 입력합니다.
3. Starry가 편집 가능한 오토 레이아웃을 만듭니다 — React (JSX) 또는 HTML로 내보내세요.

## 링크

- [starry.design](https://starry.design)
- [global.starry.design](https://global.starry.design)
- [Download](https://starry.design/download.html)
- [Browser trial](https://trial.starry.design)

## 라이선스와 개발자

- MIT — see [LICENSE](LICENSE).
- SmartAly (Aly)가 개인 개발자 프로젝트로 개발·운영합니다.

---

*Starry — AI 네이티브 디자인, 캔버스에서 코드까지.*
