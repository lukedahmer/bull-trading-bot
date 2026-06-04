# Research Log

Newest entries first.

---

## 2026-06-04 — End of Day

**Session:** Market close summary.

**Account snapshot (Alpaca):**
- Equity: $100,000.00
- Cash: $100,000.00
- Buying power: $400,000.00
- Open positions: none
- Filled orders today: none

**Performance:**
- Portfolio: 0.00% (fully in cash)
- SPY: +0.12% (close ~$755.18 vs prior close $754.24)
- Relative to SPY: -0.12%

**Observations:**
- Account is in initial state with credentials now configured. No trade
  ideas were placed today; the bot remained 100% cash through the
  session.
- SPY closed marginally green on a quiet tape. No urgent catalysts
  affecting the watchlist (QTUM, IONQ, NVDA, AMD, SPY, QQQ) crossed the
  pre-market threshold worthy of a ClickUp ping during the day.

**Next session:**
- Resume normal pre-market workflow: pull account + positions, run
  research, draft trade ideas with proper sizing per strategy.md.
- First deployments should respect the 2% default size, 10% cash
  floor, and 40% semis sector cap.

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
