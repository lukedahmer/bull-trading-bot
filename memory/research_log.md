# Research Log

Newest entries first.

---

## 2026-06-04 — Midday risk check

**Session:** Midday risk-management sweep.

**Account snapshot (Alpaca paper `PA39FINFSDLL`):**
- Equity: $100,000.00
- Cash: $100,000.00
- Buying power: $400,000.00
- Long market value: $0.00
- Status: ACTIVE

**Positions:** `GET /v2/positions` → `[]`. Account is flat.

**Risk-rule evaluation:**
- Hard stop at -8%: N/A — no positions.
- Trim 50% on winners ≥ +30%: N/A — no positions.
- Tighten trailing stop to 7% on winners ≥ +15%: N/A — no positions.
- New entries midday: skipped per rule (no major catalyst, no thesis in
  hand at this run).

**Web search:** Not performed — no held names to monitor for material
moves.

**ClickUp:** No ping sent. Notification criterion (stop triggered or
trim executed) not met.

**Next session:** Pre-market workflow — gather overnight news on the
core watchlist (QTUM, IONQ, NVDA, AMD, SPY, QQQ) and draft entry ideas
to deploy cash on the next pre-market run.

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
