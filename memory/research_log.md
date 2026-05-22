# Research Log

Newest entries first.

---

## 2026-05-22 — Midday

**Session:** Midday risk check.

**Alpaca account:** ACTIVE — equity $100,000.00, cash $100,000.00,
buying power $200,000.00, long market value $0.00, no open positions
(`GET /v2/positions` → `[]`).

**Risk actions taken:**
- Stop-loss cut (≤ -8% from entry): **n/a** — no positions held.
- Winner trim (≥ +30%, sell 50%): **n/a** — no positions held.
- Trail tighten (≥ +15% → 7% trail): **n/a** — no positions held.
- New entries: **none** — midday entries gated on a major catalyst; no
  catalyst observed and account is flat.

**ClickUp notification:** not sent — gate is "stop triggered or
position trimmed"; neither occurred.

**Trade log:** no append — no executions.

**Next session:** pre-market workflow tomorrow; consider scaling into
watchlist (QTUM, IONQ, NVDA, AMD, SPY, QQQ) per the 2% default sizing
rule if research supports it.

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
