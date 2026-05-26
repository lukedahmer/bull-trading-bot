# Research Log

Newest entries first.

---

## 2026-05-26 — Midday risk check

**Session:** Midday risk-management sweep.

**Alpaca sync:** Successful.
- Account `PA39FINFSDLL` — status ACTIVE, equity $100,000.00, cash $100,000.00, buying power $200,000.00.
- `GET /v2/positions` returned `[]` — no open positions.

**Risk-rule evaluation:**
- Hard stop (-8%): no positions, no action.
- Trim 50% on winners (+30%): no positions, no action.
- Tighten trailing stop to 7% on winners (+15%): no positions, no action.
- New positions midday: skipped per rule (no major catalyst observed and no existing book to defend).

**Web search:** Not triggered — no positions moving significantly because there are no positions.

**ClickUp:** No notification sent — no stop triggered, no trim executed.

**Trade log:** No entries added — no trades executed.

**Next session:** Pre-market workflow should generate trade ideas to deploy the 100% cash position per strategy sizing rules.

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
