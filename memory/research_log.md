# Research Log

Newest entries first.

---

## 2026-05-28 — Midday (live sync OK)

**Session:** Midday risk-management check.

**Status:** Alpaca credentials present this session. First successful live
sync of account + positions.

**Account snapshot (`/v2/account`):**
- Equity: $100,000.00 | Cash: $100,000.00 | Buying power: $200,000.00
- Status: ACTIVE | Account #: PA39FINFSDLL

**Positions (`/v2/positions`):** Empty `[]` — no open positions.

**Risk actions evaluated:**
- Cut at ≤ -8% from entry: N/A (no positions).
- Trim 50% on winners ≥ +30%: N/A (no positions).
- Tighten trailing stop to 7% on positions ≥ +15%: N/A (no positions).
- New positions: held off — midday entries only on a major catalyst, none
  identified. No web search needed (no position moving).

**Files updated:** portfolio.md (first live snapshot), trade_log.md (midday
no-trade note), this log.

**ClickUp:** Not sent — no stop triggered and no position trimmed.

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
