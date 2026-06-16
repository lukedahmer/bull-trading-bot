# Research Log

Newest entries first.

---

## 2026-06-16 — Market open

**Session:** Market-open sync.

**Account:** Equity $100,000.00, cash $100,000.00, buying power $400,000.00,
status ACTIVE. Zero open positions.

**Trade ideas evaluated:** None. `research_log.md` contained no drafted
ideas from a prior pre-market session, so the strategy checklist had no
candidates to score. Strategy prohibits placing trades without a vetted
thesis.

**Stop-loss sweep:** N/A — no positions held.

**Actions taken:**
- Pulled `/v2/account` and `/v2/positions` from Alpaca (paper).
- Refreshed `portfolio.md` with the live snapshot.
- Did **not** place any orders (no qualifying ideas).
- Did **not** ping ClickUp (no trade placed, no stop triggered).

**Next session:** Run the pre-market research workflow to generate vetted
trade ideas (per `strategy.md` §"Decision workflow (pre-market)") before
the next market-open run.

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
