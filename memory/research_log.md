# Research Log

Newest entries first.

---

## 2026-06-02 — Midday risk-management pass

**Session:** Midday checklist (Dexter).

**Alpaca sync:**
- `GET /v2/account` → equity $100,000.00, cash $100,000.00, buying power
  $200,000.00, status ACTIVE, PDT false. Paper account `PA39FINFSDLL`.
- `GET /v2/positions` → `[]` (no open positions).

**Risk-management actions:**
- Hard stop (≤ -8%): nothing to cut — no positions.
- Trim 50% on winners ≥ +30%: nothing to trim — no positions.
- Tighten trail to 7% on winners ≥ +15%: nothing to tighten — no positions.
- No new positions added; midday rule requires a major catalyst and there
  are no held names to react to. Watchlist (QTUM, IONQ, NVDA, AMD, SPY,
  QQQ) not researched this run — midday pass is risk-management only.

**Web search:** Skipped — no positions to monitor for significant moves.

**ClickUp:** No notification sent. Trigger conditions (stop fired or
position trimmed) did not occur.

**Next session:** Pre-market run should consider deploying capital
against the core watchlist; account has been 100% cash since inception.

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
