# Research Log

Newest entries first.

---

## 2026-06-25 — Midday check-in

**Session:** Midday risk review.

**Alpaca sync:** Successful. Account is ACTIVE, equity $100,000, cash
$100,000, buying power $400,000. `GET /v2/positions` returned an empty
array — **no open positions**.

**Risk actions:**
- No -8% stops to trigger (no positions).
- No +30% winners to trim (no positions).
- No +15% winners to tighten trailing stops on (no positions).

**New entries:** Per strategy, no new positions added midday absent a
major catalyst. None identified for the core watchlist (QTUM, IONQ,
NVDA, AMD, SPY, QQQ) in this session.

**ClickUp:** No notification sent — no stop triggered and no trim
executed (silence per spec when nothing actionable happened).

**Next session:** Pre-market run should draft initial entries to put
the cash to work, sized per the 2%-of-equity default and 10% cash floor.

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
