# Research Log

Newest entries first.

---

## 2026-06-23 — End of Day

**Session:** Post-market close summary.

**Account (Alpaca paper, PA39FINFSDLL):**
- Equity: $100,000.00
- Cash: $100,000.00 (100% cash)
- Buying power: $400,000.00
- Open positions: none
- Filled orders today: none

**Performance:**
- Portfolio: 0.00% (flat — no exposure)
- SPY: -0.31% (close 744.39 from prior 746.74)
- Relative: +0.31 pts vs SPY

**Observations:**
- Account is still in its initial 100% cash state — no trades have ever
  been executed in this paper account. Strategy workflow has not yet
  initiated any entries off the watchlist (QTUM, IONQ, NVDA, AMD, SPY,
  QQQ).
- Sitting in cash on a mildly red SPY day delivered passive
  outperformance, but this is not a strategy — it's the absence of one.
- Action item for next pre-market: per strategy.md, draft initial 2%
  starter positions from the watchlist (no entries in post-market run).

**Notifications sent:**
- ClickUp end-of-day ping per daily SOP.

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
