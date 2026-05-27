# Research Log

Newest entries first.

---

## 2026-05-27 — Intraday open (no action)

**Session:** Intraday, market just opened. Credentials provided this run.

**Alpaca sync:**
- Equity $100,000.00, cash $100,000.00, buying power $200,000.00
- Positions: none
- Account ACTIVE, not flagged PDT

**Stop-loss sweep:** No positions held — nothing to stop out.

**Trade ideas reviewed:** None in the log. The only prior entry
(2026-05-19) was a blocked pre-market run that drafted no ideas.

**Decision:** Stand down. Placing trades without research or a drafted
idea on the checklist would violate the strategy's decision workflow.
No orders sent, no trailing stops set, no ClickUp ping.

**Next session unblocker:** Run a pre-market research pass (Perplexity
sonar-pro on watchlist QTUM, IONQ, NVDA, AMD, SPY, QQQ + macro
calendar) and draft trade ideas using the template in strategy.md
before the next intraday session.

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
