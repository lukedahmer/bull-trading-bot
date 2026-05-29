# Research Log

Newest entries first.

---

## 2026-05-29 — Midday risk check

**Session:** Intraday / midday risk management.

**Status:** Completed. Alpaca credentials now present in the environment,
so the pre-market blocker (see 2026-05-19) is resolved.

**Account snapshot (`/v2/account`):**
- Equity: $100,000.00
- Cash: $100,000.00
- Buying power: $200,000.00
- Long market value: $0.00
- Status: ACTIVE, not flagged PDT.

**Positions (`/v2/positions`):** Empty array — no open positions.

**Risk actions evaluated:**
- Hard stop (≤ -8% from entry): N/A — no positions.
- Trim 50% on winners (≥ +30%): N/A — no positions.
- Tighten trailing stop to 7% on names ≥ +15%: N/A — no positions.
- New midday entries: none. Restricted absent a major catalyst, and the
  account is in a clean all-cash state.

**Web research:** None performed — no position is moving, nothing to
monitor.

**ClickUp:** No notification sent (criteria are a triggered stop or a
trim; neither occurred).

**Notes:** Account is freshly capitalized at $100k and fully in cash.
Next deployment of capital should follow the pre-market workflow and
position-sizing rules in strategy.md (2% default, 10% cash floor).

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
