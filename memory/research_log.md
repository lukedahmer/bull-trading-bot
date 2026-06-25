# Research Log

Newest entries first.

---

## 2026-06-25 — Intraday (market open)

**Session:** Intraday, just after open.

**Account snapshot (Alpaca `/v2/account`):**
- Equity: $100,000.00
- Cash: $100,000.00
- Buying power: $400,000.00
- Portfolio value: $100,000.00
- Status: ACTIVE, PDT: false
- Open positions (`/v2/positions`): none

**Trade ideas reviewed:** None on file. The research log contains only the
2026-05-19 blocked-bootstrap entry; no vetted pre-market drafts exist for
today. Per strategy.md, intraday trades should be backed by a documented
thesis from the pre-market workflow — not improvised from a cold start at
the open.

**Stop-loss sweep:** N/A — no open positions, nothing at -8% or worse.

**Actions taken:**
- Pulled `/v2/account` and `/v2/positions` (both 200 OK).
- Updated `portfolio.md` with first successful Alpaca sync.
- Did **not** place any orders — no trade ideas in `research_log.md` to
  evaluate against the strategy checklist.
- Did **not** trigger any stop losses — no positions held.
- Did **not** send ClickUp notification — task says ping only on trade
  placed or stop triggered; neither occurred.

**Next session unblocker:**
Run the pre-market workflow (Perplexity research on QTUM, IONQ, NVDA,
AMD, SPY, QQQ + macro events) to populate trade ideas before the next
intraday session can act.

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
