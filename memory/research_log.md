# Research Log

Newest entries first.

---

## 2026-07-01 — End of Day

**Session:** Post-close daily wrap.

**Account snapshot (Alpaca `/v2/account`):**
- Equity: $100,000.00
- Cash: $100,000.00
- Buying power: $400,000.00
- Long market value: $0.00
- Status: ACTIVE

**Positions (`/v2/positions`):** None.

**Filled orders today (`/v2/orders?status=filled`):** None.

**Performance:**
- Portfolio today: **0.00%** (fully in cash, no positions).
- SPY today: **+0.08%** (close 747.28 vs prior close 746.65, per Alpaca
  daily bars).
- Alpha vs SPY: **-0.08%** (opportunity cost of sitting in cash on an
  up-day for the index).

**Observation:** Account remains uninvested from bootstrap. First
successful Alpaca sync completed this session — credentials now
functional. Next pre-market session should draft actual watchlist trade
ideas per strategy.md workflow and begin deploying capital within the
2% position-sizing rule.

**Actions taken:**
- Pulled Alpaca account, positions, filled orders.
- Recomputed portfolio.md with live snapshot.
- Sent ClickUp EOD ping.

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
