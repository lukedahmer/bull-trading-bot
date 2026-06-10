# Research Log

Newest entries first.

---

## 2026-06-10 — Market open

**Session:** Market-open run. Credentials provided inline this session.

**Alpaca account snapshot:**
- Equity: $100,000.00
- Cash: $100,000.00 (100% cash)
- Buying power: $400,000.00
- Status: ACTIVE, no PDT flag
- Open positions: none
- Open orders: none

**Stop-loss sweep:** N/A — no positions to evaluate against the -8%
hard stop.

**Trade ideas evaluated:** None. `research_log.md` contains no prior
drafted trade ideas (only the 2026-05-19 BLOCKED bootstrap entry). The
strategy workflow requires research-backed ideas before entries; with
no Perplexity research run this session and no pre-drafted ideas in the
log, **no orders were placed**. Guardrails (10% max position, 20% cash
floor) were therefore not engaged.

**Actions taken:**
- Synced `portfolio.md` with live Alpaca account + positions.
- Logged this session here.
- No trades placed, no stops triggered → no ClickUp notification sent
  (per session brief: notify only on trade placed or stop triggered).

**Next session unblocker:**
Run a pre-market research pass (movers, holdings news, macro, watchlist
QTUM / IONQ / NVDA / AMD / SPY / QQQ) and draft trade ideas under the
`Trade idea template` before the next market-open run so the entry
workflow has candidates to evaluate.

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
