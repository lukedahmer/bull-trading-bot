# Research Log

Newest entries first.

---

## 2026-06-26 — End of Day

**Session:** Post-market close.

**Account snapshot (Alpaca):**
- Equity: $100,000.00 (unchanged from last equity)
- Cash: $100,000.00
- Buying power: $400,000.00
- Open positions: none
- Filled orders today: none

**Today's performance:**
- Portfolio return: 0.00% (entirely in cash)
- SPY return: -0.50% (S&P 500 dropped on tech selloff)
- Relative to SPY: +0.50%

**Market context (2026-06-26):**
- Global tech sell-off on AI capex concerns. Nasdaq 100 -0.7%, S&P 500 -0.5%, Dow flat.
- Hyperscalers held losses from prior session; Nvidia, Tesla, Oracle down >1%.
- Chip producers gave back Micron-rally gains: MU -4%, SNDK / LRCX / WDC down up to 10%.
- OpenAI reportedly delaying IPO to next year (NYT).
- Asian tech rout: Kospi -5.8% (8% intraday drop triggered circuit breaker).

**Observation:** Account has been idle in cash since inception (no Bull
trades have been executed yet — trade_log remains empty). Today's flat
return beats SPY by virtue of zero exposure during a risk-off session,
but this is not a strategy outcome — it's an unworked account. Next
pre-market session needs to draft the first real entries on the
watchlist (QTUM, IONQ, NVDA, AMD, SPY, QQQ) per strategy.md.

**Actions taken:**
- Pulled Alpaca `/v2/account`, `/v2/positions`, `/v2/orders?status=filled`.
- Updated portfolio.md with end-of-day snapshot.
- Sent end-of-day ClickUp notification.

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
