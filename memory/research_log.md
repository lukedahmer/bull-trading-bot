# Research Log

Newest entries first.

---

## 2026-05-27 — Midday risk check

**Session:** Midday risk-management sweep.

**Account snapshot (Alpaca PA39FINFSDLL, paper):**
- Equity: $100,000.00
- Cash: $100,000.00
- Long market value: $0.00
- Status: ACTIVE

**Positions:** `GET /v2/positions` returned `[]`. No open positions.

**Risk-rule pass:**
- Hard stop -8%: n/a (no positions).
- Trim 50% on +30% winners: n/a.
- Tighten trail to 7% on +15% winners: n/a.

**Actions taken:**
- No orders placed (midday rule: no new positions without major catalyst).
- No ClickUp ping (no stop triggered, no trim executed).
- Updated `portfolio.md` with fresh sync.

**Notes:** Account is fully in cash. Next pre-market session should
draft entries against the core watchlist (QTUM, IONQ, NVDA, AMD, SPY,
QQQ) consistent with the 2% default sizing rule.

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
