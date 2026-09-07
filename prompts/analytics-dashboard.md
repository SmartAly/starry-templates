# Prompt: analytics dashboard

Copy the block below into Starry's canvas input.

---

Build a responsive analytics dashboard with:

1. A left sidebar (240px): workspace switcher at the top, then nav items
   (Overview, Traffic, Conversions, Reports, Settings) with icons.
2. A top bar: page title "Overview", a date-range chip "Last 30 days", a search
   field, and an avatar on the right.
3. A KPI row of four cards: "Visitors" 24.8k (+12.4%), "Signups" 3,142 (+8.1%),
   "Conversion" 4.6% (-0.3%), "Revenue" ¥182,540 (+15.2%) — each with a label,
   big number, and delta chip.
4. A main chart card: line chart "Visitors over time", 30 daily points, two
   series (this period vs. previous period), legend on the top right.
5. A secondary row: a 5-bar horizontal chart "Top channels" and a list card
   "Recent activity" with three rows (avatar, name, action, relative time).

Use the Base UI design system: dark theme (#15151A background), green (#00A737)
primary, cyan→violet gradient for AI accents, 12px card radius, auto-layout,
mobile-first, max-width 1440px container. Every block must be auto-layout so it
survives responsive export.
