# Research Log

Newest entries first.

---

## 2026-06-19 — Midday check-in

**Session:** Midday risk review.

**Alpaca sync:** OK.
- Equity: $100,000.00
- Cash: $100,000.00
- Buying power: $400,000.00
- Open positions: **0**

**Risk-rule actions executed:**
- Cut at -8% or worse: none (no positions).
- Trim 50% on winners up 30%+: none (no positions).
- Tighten trailing stop to 7% on winners up 15%+: none (no positions).

**New positions:** None added. Midday rule prohibits new entries absent
a major catalyst, and no held names exist to react to.

**Web search:** Skipped — nothing to monitor.

**ClickUp notification:** Not sent. No stop was triggered and no position
was trimmed; per instructions, ping only on those events.

**Next session:** Resume normal pre-market workflow tomorrow.

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
