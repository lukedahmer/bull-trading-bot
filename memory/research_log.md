# Research Log

Newest entries first.

---

## 2026-07-02 — Midday risk check

**Session:** Midday (Dexter).

**Alpaca sync:** Successful. Account ACTIVE, equity $100,000.00, cash
$100,000.00, buying power $400,000.00. `GET /v2/positions` returned an
empty array — no open positions.

**Risk actions evaluated:**
- Hard stop (-8% from entry): N/A, no positions.
- Trim winners at +30%: N/A, no positions.
- Tighten trailing stop to 7% on +15% winners: N/A, no positions.
- No new positions midday (strategy rule) — no major catalyst warrants
  overriding the rule; nothing added.

**ClickUp:** Not pinged — no stop triggered, no position trimmed.

**Web search:** Not run — no held names to check for significant moves.

**Next:** Wait for pre-market session to draft any new entries per
strategy. Watchlist unchanged: QTUM, IONQ, NVDA, AMD, SPY, QQQ.

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
