# Prompt: SaaS settings & CRUD

Copy the block below into Starry's canvas input.

---

Build a responsive settings console with:

1. A left nav with section groups: **Account** (Profile, Security, Billing) and
   **Workspace** (Members, Integrations, API keys).
2. A content area for "Members": a header row with title, a search field, an
   "Invite member" green button, and a segmented filter (All / Admins / Pending).
3. A members table: avatar + name + email, role chip, status chip (Active /
   Pending), last-active timestamp, and a row action menu.
4. An empty state for zero results: icon, "No members found", one-line helper
   text, and a secondary button "Clear filters".
5. A right-side drawer (320px) for "Invite member": email input, role select,
   a "Send invite" primary button and a "Cancel" ghost button.

Use the Base UI design system: dark theme (#15151A background), green (#00A737)
primary, cyan→violet gradient for AI accents, 12px card radius, auto-layout,
mobile-first, max-width 1200px container. Table rows must be auto-layout so the
layout reflows on mobile.
