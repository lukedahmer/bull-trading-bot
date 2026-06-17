# Research Log

Newest entries first.

---

## 2026-06-17 — Midday risk check

**Session:** Midday risk-management sweep.

**Alpaca sync:** Credentials now configured. `/v2/account` and
`/v2/positions` both responded 200.

- Equity: $100,000.00 (all cash)
- Buying power: $400,000.00
- Open positions: **none**

**Risk actions evaluated:**
- Hard stop (-8% from entry): N/A — no positions.
- Winner trim (+30%, sell 50%): N/A — no positions.
- Tighten trailing stop to 7% on +15% winners: N/A — no positions.

**New entries:** Per the strategy, no new positions added midday absent
a major catalyst. None identified this session.

**ClickUp:** No notification sent — no stop triggered, no position
trimmed.

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
