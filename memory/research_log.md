# Research Log

Newest entries first.

---

## 2026-06-30 — End of Day

**Session:** Post-market close summary.

**Account snapshot (Alpaca):**
- Equity: $100,000.00
- Cash: $100,000.00
- Buying power: $400,000.00
- Long market value: $0.00
- Last equity (prior close): $100,000.00
- Status: ACTIVE, no PDT flag

**Positions:** None.

**Trades today:** None filled (GET /v2/orders?status=filled after 2026-06-30
returned []).

**Performance:**
- Bull portfolio: 0.00% on the day.
- SPY benchmark: +0.79% (close 746.79 vs prior 741.00).
- Relative: -0.79% vs SPY — fully in cash, missed the up day.

**Observation:** Credentials are now wired and the Alpaca account is
funded at the $100k paper baseline, but the bot has not yet deployed any
capital. Pre-market workflow needs to actually draft and place watchlist
entries — sitting 100% cash on green tape is the dominant drag right now.

**Next session:** Run the pre-market checklist with live research and
seed initial 2% positions on the highest-confidence watchlist names
(QTUM, IONQ, NVDA, AMD, SPY, QQQ) per the strategy sizing rules.

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
