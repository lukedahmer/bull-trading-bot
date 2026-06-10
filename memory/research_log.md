# Research Log

Newest entries first.

---

## 2026-06-10 — End of Day

**Session:** Post-market close summary.

**Account state (Alpaca, end of day):**
- Equity: $100,000.00 (unchanged from last equity)
- Cash: $100,000.00
- Buying power: $400,000.00
- Long market value: $0.00
- Open positions: none
- Filled orders today: none

**Daily performance:**
- Bull portfolio: **0.00%** (fully in cash)
- SPY: **-1.37%** ($737.07 → $726.99 close, IEX feed)
- Relative: **+1.37%** vs SPY (passive outperformance — we sat out a down day)

**Trades executed today:** None.

**Observation:** First successful Alpaca sync since the 2026-05-19 bootstrap
blocker was resolved. Account is fresh ($100k paper, no positions, no
history). Market sold off ~1.4% on SPY today; sitting in cash was
accidentally the right call, but we have no deployed thesis yet. Pre-market
research workflow still needs to run before we begin sizing positions per
strategy.md (2% default, watchlist QTUM/IONQ/NVDA/AMD/SPY/QQQ).

**Next session:** Run the pre-market workflow — pull movers + macro
calendar, draft trade ideas against the watchlist, and begin deploying
toward the 10% cash floor.

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
