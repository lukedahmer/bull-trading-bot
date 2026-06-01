# Research Log

Newest entries first.

---

## 2026-06-01 — Market-open run (no-op)

**Session:** "Market just opened" intraday execution.

**Reality check:**
- Alpaca `/v2/clock` reports `is_open: false`, `next_open:
  2026-06-01T09:30:00-04:00`, current timestamp `2026-06-01T02:32 ET`.
  Market has not opened yet — execution would be queued, not filled at
  intended prices.
- Today is 2026-06-01, a Sunday-to-Monday transition. The user prompt
  said the market "just opened" but the venue disagrees.

**Account snapshot (Alpaca):**
- Equity $100,000.00 | Cash $100,000.00 | Buying power $200,000.00
- Long market value $0.00. **Zero open positions.**

**Trade ideas reviewed:** None in `research_log.md`. The only prior
entry (2026-05-19) was a bootstrap note and explicitly drafted no
ideas. Strategy requires ideas be drafted in a pre-market session
before being placed; placing trades from an empty idea list would
violate the workflow.

**Stop-loss sweep:** N/A — no positions held.

**Actions taken:**
- Pulled `/v2/account` and `/v2/positions`; updated `portfolio.md` with
  the first real Alpaca sync.
- Did **not** place any orders. Reasons (any one is sufficient):
  1. No trade ideas exist in `research_log.md` to execute against.
  2. Market is not actually open; orders would not fill at current
     prices.
- Did **not** send a ClickUp notification (task gate: only on
  trade-placed or stop-triggered; neither occurred).

**Next session:**
- Run the pre-market workflow at/near 09:30 ET: research overnight
  news on watchlist (QTUM, IONQ, NVDA, AMD, SPY, QQQ), draft trade
  ideas using the template, then a separate intraday run can execute.

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
