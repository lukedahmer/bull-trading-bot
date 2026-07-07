# Research Log

Newest entries first.

---

## 2026-07-07 — Midday risk check

**Session:** Midday.

**Alpaca account:** Equity $99,850.19; cash $82,728.63 (82.85%);
long market value $17,121.56 (17.15%). Account ACTIVE.

**Positions:**
- IONQ 64 @ $47.86 → $45.30 (-5.36%; -7.3% today)
- NVDA 25 @ $192.21 → $195.18 (+1.55%)
- QTUM 32 @ $153.20 → $151.81 (-0.91%)
- SPY 6 @ $750.06 → $747.35 (-0.36%)

**Risk actions:** None taken.
- No position ≤ -8% (hard stop).
- No position ≥ +30% (trim).
- No position ≥ +15% (trail-tighten).

**IONQ move check (web search):** IONQ ~-7% intraday appears tied to a
broader quantum / growth pullback (context: IONQ -26.1% in June;
sector-wide profit-taking after strong Q1 results). No company-specific
adverse catalyst identified. Position remains above hard stop; hold.

**New entries:** None. Rules bar midday adds without a major catalyst.

**ClickUp ping:** None (no stop triggered, no trim executed).

---

## 2026-05-19 — Pre-market (BLOCKED)

## 2026-05-19 — Pre-market (BLOCKED)

**Session:** Pre-market bootstrap.

**Status:** Unable to complete research workflow. Required environment
variables are not set in this remote execution environment:

- `ALPACA_API_KEY` — missing
- `ALPACA_SECRET_KEY` — missing
- `ALPACA_BASE_URL` — missing
- `PERPLEXITY_API_KEY` — missing
- `CLICKUP_API_TOKEN` — missing
- `CLICKUP_LIST_ID` — missing

**Actions taken:**
- Bootstrapped repository scaffolding (`memory/strategy.md`,
  `memory/portfolio.md`, `memory/trade_log.md`, this file).
- Did **not** call Alpaca `/v2/account` or `/v2/positions` — no creds.
- Did **not** call Perplexity `sonar-pro` — no key. No fabricated
  research has been written here; only verified facts belong in this
  log.
- Did **not** send a ClickUp notification (no creds, and no urgent
  catalyst is known to exist).

**Trade ideas drafted:** None. Cannot draft ideas without a current
portfolio snapshot and live market research.

**Next session unblocker:**
Configure the six environment variables above in the environment's
Variables/Secrets settings (see
https://code.claude.com/docs/en/claude-code-on-the-web for how the
environment is configured), then re-run the pre-market workflow.

---
