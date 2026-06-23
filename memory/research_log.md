# Research Log

Newest entries first.

---

## 2026-06-23 — Midday risk check

**Session:** Midday risk-management sweep.

**Alpaca sync:** Successful. Paper account `PA39FINFSDLL`, status ACTIVE.
- Equity: $100,000.00
- Cash: $100,000.00
- Long market value: $0.00
- Open positions: **0** (GET /v2/positions returned `[]`)

**Risk actions evaluated:**
- Hard stop at -8%: N/A — no positions.
- Trim 50% on winners up >=30%: N/A — no positions.
- Tighten trailing stop to 7% on winners up >=15%: N/A — no positions.

**Trades placed:** None. Per strategy, no new positions added midday absent a
major catalyst, and no catalyst is in play for this run.

**ClickUp notification:** Not sent. Trigger condition (stop hit or position
trimmed) did not occur.

**Notes:** This is the first successful Alpaca sync since the 2026-05-19
bootstrap blocker. Portfolio.md now reflects live broker state. No trade log
entries since none have been executed.

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
