# DealLens

**Underwrite any rental deal in 10 minutes, like a pro.**

Consumer rental-deal analyzer for first-time investors. UI mockups generated with [Stitch](https://stitch.withgoogle.com) (project: "DealLens") — exported 2026-10-07.

## Screens

| Screen | Folder |
|---|---|
| Landing — Stop Guessing on Rentals | `screens/landing_stop_guessing_on_rentals/` |
| Key Setup — BYOK Local Vault | `screens/key_setup_byok_local_vault/` |
| New Analysis — Property Basics & Strategy | `screens/new_analysis_property_basics_strategy/` |
| Assumptions — Underwriting Grid | `screens/assumptions_underwriting_grid/` |
| Results Dashboard — Verdict & Deal Score | `screens/results_dashboard_verdict_deal_score/` |
| RentCast Deep-Dive & Comps | `screens/rentcast_deep_dive_comps/` |
| Deal Watch — Saved Alerts & Feeds | `screens/deal_watch_saved_alerts_feeds/` |
| Compare — 4-Deal Side-by-Side | `screens/compare_4_deal_side_by_side/` |
| History — Past Underwritings | `screens/history_past_underwritings/` |
| Settings — BYOK Vault & Portability | `screens/settings_byok_vault_portability/` |

Each screen folder has `index.html` (self-contained mockup) and `preview.png` (screenshot).

Design tokens: `design-system/DESIGN.md` (dark financial dashboard: bg `#020617`, cards `#0E1223`, primary green `#22C55E`, IBM Plex Sans).

## Concept

- **BYOK**: user pastes their own OpenAI / xAI / Anthropic API key, stored in the browser only.
- **Strategies**: Buy & Hold, Rehab Flip, New Build — 6 loan types.
- **Deterministic math** in-app (NOI, cap rate, cash flow, DSCR, 1%/50% rules); AI narrates and judges, never does arithmetic alone.
- Deal score 0–100, risk flags, suggested offer + walk-away price, printable report, Deal Watch alerts, 4-deal compare.

## Status

UI mockups only — no backend. Numbers on screens are demo data (1234 Demo St, Fort Pierce FL) and have known cross-screen inconsistencies being polished.
