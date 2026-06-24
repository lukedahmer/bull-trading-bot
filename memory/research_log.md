# Research Log

Newest entries first.

---

## 2026-06-24 — Midday risk sweep

**Session:** Intraday risk check.

**Alpaca state:** Account ACTIVE, equity $100,000.00, cash $100,000.00,
buying power $400,000.00, long market value $0, zero open positions.

**Risk actions executed:** None — nothing to act on.
- Hard-stop sweep (-8%): n/a, no positions.
- Trim sweep (+30%): n/a, no positions.
- Trail-tighten sweep (+15% → 7% trail): n/a, no positions.

**New positions:** None added. Midday rule prohibits new entries without
a major catalyst; none observed and no holdings to defend.

**ClickUp:** No notification sent (rule: only on triggered stop or trim).

**Next session:** Resume pre-market workflow; consider re-entering core
watchlist (QTUM, IONQ, NVDA, AMD, SPY, QQQ) per strategy sizing rules
when next pre-market run executes.

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
