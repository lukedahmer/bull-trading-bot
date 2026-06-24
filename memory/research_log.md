# Research Log

Newest entries first.

---

## 2026-06-24 — Overnight / pre-market sync

**Session:** Scheduled routine fired at 02:32 ET. Task description claimed
"the market just opened" but Alpaca `/v2/clock` reports `is_open=false`,
next open 09:30 ET. Treated as a pre-market sync, not an intraday run.

**Account snapshot (Alpaca `PA39FINFSDLL`):**
- Equity $100,000.00 — Cash $100,000.00 — Long mkt value $0.00
- Buying power $400,000.00, status ACTIVE, PDT false
- Open positions: **none**

**Stop-loss sweep:** N/A — no positions held.

**Trade ideas reviewed:** None. `research_log.md` contained no drafted
ideas going into this session (prior entry was the 2026-05-19 BLOCKED
bootstrap), and the strategy workflow forbids placing trades in the
pre-market run. No orders submitted.

**ClickUp notification:** Suppressed. No trade placed, no stop triggered,
no urgent catalyst surfaced.

**Next session:** Run the real pre-market research workflow once a
research source is wired up — pull movers, overnight news on the
watchlist (QTUM, IONQ, NVDA, AMD, SPY, QQQ), and macro events for
2026-06-24, then draft ideas here for the next intraday run to act on.

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
