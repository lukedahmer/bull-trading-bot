# Research Log

Newest entries first.

---

## 2026-05-26 — End of Day

**Session:** Post-market wrap.

**Account snapshot (Alpaca):**
- Equity: $100,000.00
- Cash: $100,000.00
- Buying power: $200,000.00
- Last equity (prior close): $100,000.00
- Positions: none
- Filled orders today: none

**Performance:**
- Portfolio return today: +0.00%
- SPY today: +0.74% (close 751.19 vs prior close 745.64)
- Relative to SPY: -0.74% (sat in cash on an up day)

**Observations:**
- Account remains 100% cash. No trades have been executed since the
  initial bootstrap; the pre-market research/idea-generation step has
  not yet been run with the now-configured credentials.
- Credentials (Alpaca, ClickUp) are now active in the environment and
  the Alpaca API responded successfully to `/v2/account`,
  `/v2/positions`, and `/v2/orders` calls.
- Risk exposure is nil. Cash floor (10%) and max position rules are
  not binding while flat.

**Next session:**
- Run pre-market workflow: pull Alpaca state, research watchlist
  (QTUM, IONQ, NVDA, AMD, SPY, QQQ), draft trade ideas per strategy
  template, and decide on first deployments toward target equity
  weights.

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
