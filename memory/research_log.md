# Research Log

Newest entries first.

---

## 2026-05-20 — Midday risk check

**Session:** Midday intraday risk review.

**Alpaca sync:** Successful. Credentials now present in session env.
- Equity: $100,000.00
- Cash: $100,000.00
- Buying power: $200,000.00
- Long market value: $0.00
- Status: ACTIVE, no PDT flag, no trading block.

**Positions:** `GET /v2/positions` → `[]`. Zero open positions.

**Risk actions evaluated:**
- Hard stop ≤ -8%: N/A — no positions.
- Trim 50% on winners ≥ +30%: N/A — no positions.
- Tighten trailing stop to 7% on winners ≥ +15%: N/A — no positions.

**New positions:** Per instruction, no new midday entries absent a major
catalyst. No catalyst identified that overrides this rule. Held off web
search since there are no held names moving "significantly" to track.

**ClickUp ping:** Skipped — no stop triggered and no trim executed
(notification rule scoped to those two events).

**Next session:** Resume normal pre-market workflow on 2026-05-21 —
research watchlist (QTUM, IONQ, NVDA, AMD, SPY, QQQ) and macro calendar,
then draft initial entries to put cash to work.

---

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
