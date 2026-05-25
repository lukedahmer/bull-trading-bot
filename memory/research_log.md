# Research Log

Newest entries first.

---

## 2026-05-25 — Midday risk check

**Session:** Midday.

**Status:** Alpaca credentials now present in environment. Successfully
called `/v2/account` and `/v2/positions`.

- Account equity: $100,000.00 (paper account `PA39FINFSDLL`, ACTIVE).
- Cash: $100,000.00. Long market value: $0.
- Open positions: **none**.

**Risk actions evaluated (none triggered):**
- -8% hard-stop cut: N/A (no positions).
- +30% trim 50%: N/A.
- +15% tighten trailing stop to 7%: N/A.

**New entries:** None. Midday entries require a major catalyst per
strategy, and no held names exist to react to. Watchlist (QTUM, IONQ,
NVDA, AMD, SPY, QQQ) not researched this session — the run was scoped
to risk management on existing positions.

**ClickUp:** Not sent (no stop triggered, no trim executed).

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
