# Research Log

Newest entries first.

---

## 2026-05-28 — Session (credentials now present; account synced)

**Session:** Trading run. Wall-clock at run time was 06:34 UTC ≈ 02:34 ET,
i.e. overnight / pre-market — the US cash session was **not** actually open
despite the prompt framing.

**Status:** Alpaca credentials were supplied this session. Account synced
successfully.

**Account snapshot (GET /v2/account, GET /v2/positions):**
- Equity / cash / portfolio value: $100,000 (100% cash).
- Buying power: $200,000. Status ACTIVE, not flagged PDT.
- Open positions: **none** (`[]`).

**Stop-loss check:** No open positions, so no -8% hard-stop evaluations and
no liquidations were possible or needed.

**Trade ideas reviewed:** research_log.md contained **no drafted trade
ideas** (the only prior entry, 2026-05-19, was a BLOCKED bootstrap that
explicitly recorded "Trade ideas drafted: None"). Per the strategy, trades
are placed only against researched, pre-drafted ideas that clear the
checklist — and "only verified facts belong in this log." With zero
qualifying ideas on file, **no orders were placed and no trailing stops
were set.** No theses were fabricated to justify deploying capital.

**ClickUp:** No notification sent — no trade was placed and no stop loss
triggered (matches the notify-only-on-action rule).

**Next session:** Run the pre-market research workflow (Perplexity
`sonar-pro` movers/news/macro on the watchlist: QTUM, IONQ, NVDA, AMD, SPY,
QQQ), draft trade ideas into this log, and only then execute on a
subsequent run during live market hours. Note: `PERPLEXITY_API_KEY` was not
provided this session, so live research could not be performed.

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
