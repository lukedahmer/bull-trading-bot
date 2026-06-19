# Research Log

Newest entries first.

---

## 2026-06-19 — End of Day (Juneteenth, market closed)

**Session:** End-of-day routine.

**Market status:** US equity markets closed all day for Juneteenth National
Independence Day. Alpaca `/v2/clock` confirmed `is_open: false`,
next open Monday 2026-06-22 09:30 ET. Bond markets and Fed banking
services also closed.

**Account snapshot (Alpaca):**
- Equity: $100,000.00 (unchanged from prior close $100,000.00)
- Cash: $100,000.00 — 100% cash
- Buying power: $400,000.00
- Open positions: none
- Filled orders today: none

**Performance:**
- Portfolio today: +0.00%
- SPY today: N/A (market closed; last close 2026-06-18 = $746.75)

**Observations:**
- Account remains in fully-funded, untraded state since bootstrap on
  2026-05-19. No trades have been placed in this paper account yet.
- Watchlist (QTUM, IONQ, NVDA, AMD, SPY, QQQ) — no data movement to
  log; quotes from Alpaca still showing 2026-06-18 close.
- Next decision point: Monday 2026-06-22 pre-market session. Strategy
  still calls for staged entries with 2% sizing and 8% hard stops.

**Actions taken:**
- Synced Alpaca account/positions/orders.
- Updated portfolio.md with final EOD state.
- Sent ClickUp EOD notification.
- Committed + pushed memory updates.

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
