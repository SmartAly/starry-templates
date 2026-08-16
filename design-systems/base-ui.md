# Base UI — design system spec

Apply this spec to every Starry generation so output stays consistent.

## Tokens
- Background: `#15151A` (page), `#1C1C22` (surface), `#23232B` (surface-2)
- Text: `#E8E8EA` (primary), `#A0A0A8` (muted)
- Brand / accent: `#00A737` (green)
- AI accent gradient: `#22D3EE` → `#A855F7` (cyan to violet)
- Border: `#2C2C34`
- Radius: 12px cards, 8px controls, 16px hero
- Font: system UI stack; headings 600 weight

## Rules
- Use auto-layout (flex / CSS grid via Yoga). No absolutely-positioned hacks.
- Spacing scale: 4 / 8 / 12 / 16 / 24 / 32 / 48 px.
- Components: buttons, inputs, cards, nav bar, footer.
- Buttons: green primary; AI actions use the cyan→violet gradient.
- Always produce responsive layout (mobile-first, max-width 1200px container).
- Prefer semantic HTML; export target React (JSX) + HTML.
