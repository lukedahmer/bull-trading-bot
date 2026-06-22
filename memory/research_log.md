# Research Log

Newest entries first.

---

## 2026-06-22 — Market-open session (no-op)

**Session:** Intraday open routine (Monday).

**Account snapshot (Alpaca paper `PA39FINFSDLL`):**
- Equity: $100,000.00
- Cash: $100,000.00 (100% cash floor not at risk)
- Open positions: none

**Market clock check:** Alpaca `/v2/clock` reports `is_open: false`,
`next_open: 2026-06-22T09:30:00-04:00`. Local timestamp at run start was
02:31 ET — market has not yet opened despite the routine's prompt. Any
`time_in_force: day` order would queue until open, but see below.

**Trade ideas reviewed:** None. `research_log.md` contains no drafted
ideas since the 2026-05-19 bootstrap. No candidate passes the checklist
because no candidate exists.

**Stop-loss sweep:** No positions held → nothing to evaluate against the
-8% hard stop.

**Actions taken:**
- Synced Alpaca account + positions; updated `portfolio.md`.
- Did **not** place any orders (no ideas + no positions).
- Did **not** send a ClickUp ping (no trade placed, no stop triggered).

**Next session unblocker:** Pre-market run needs to draft trade ideas
into this log (using the strategy template) before the open session can
act on them.

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
