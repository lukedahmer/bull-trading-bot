# Research Log

Newest entries first.

---

## 2026-06-30 — Midday check-in

**Session:** Midday risk pass.

**Alpaca sync:** Account `PA39FINFSDLL` ACTIVE. Equity $100,000, cash
$100,000, long market value $0. **Zero open positions.**

**Risk checks (per midday checklist):**
- Hard stop at -8%: N/A — no positions.
- Trim 50% on winners ≥ +30%: N/A — no positions.
- Tighten trailing stop to 7% on winners ≥ +15%: N/A — no positions.

**Web search:** Skipped. No held names to research; no position is
"moving significantly" because there are none.

**New entries:** None. Strategy forbids midday adds without a major
catalyst, and the watchlist hasn't been screened in this run.

**ClickUp ping:** Suppressed. No stop triggered, no trim executed.

**Next session:** Pre-market run should screen QTUM, IONQ, NVDA, AMD,
SPY, QQQ and draft initial 2%-equity entries to start deploying the
cash floor toward the portfolio targets.

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
