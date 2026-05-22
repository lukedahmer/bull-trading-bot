# Research Log

Newest entries first.

---

## 2026-05-22 — End of Day

**Session:** Post-market wrap.

**Alpaca sync (live):**
- Equity: $100,000.00 (last equity $100,000.00)
- Cash: $100,000.00 | Buying power: $200,000.00
- Long market value: $0.00 | Open positions: 0
- Filled orders today: 0
- Account status: ACTIVE, PDT: false

**Performance:**
- Bull portfolio: +0.00% (flat — fully in cash, no positions deployed)
- SPY: ~+0.21% (close ~$744.13 vs prior $742.58)
- Relative: -0.21% vs SPY

**Trades executed today:** None.

**Observations:**
- This is the first successful Alpaca sync since the 2026-05-19 bootstrap
  blocker; credentials are now live in the environment.
- Account is still un-deployed at the $100k starting equity. Strategy's
  cash floor (10%) and position-size defaults (2% per new name) leave
  ample room to build the core watchlist next session.
- No trades were warranted on a close-only check-in; entries belong in
  the pre-market / intraday workflow per strategy.md.

**Next session:**
- Run full pre-market workflow Monday: Alpaca pull, Perplexity research
  on QTUM, IONQ, NVDA, AMD, SPY, QQQ, draft 2–4 trade ideas at default
  2% sizing, watch for FOMC/CPI/PPI/NFP calendar overlap before any
  entries.

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
