# Research Log

Newest entries first.

---

## 2026-06-23 — Market open session

**Status:** First successful Alpaca sync. Credentials provided in
session. Account is fresh ($100k equity, 100% cash, no positions, no
open orders).

**Stop-loss checks:** N/A — no positions.

**Trade ideas considered:** None. The research_log had no drafted trade
ideas from a prior pre-market session. Per strategy.md, trades require a
prior pre-market research pass (Perplexity sonar-pro on movers / macro /
watchlist) — no such pass has been run yet in a session with creds. Will
not place trades on an unresearched watchlist.

**Actions taken:**
- Pulled `/v2/account` and `/v2/positions` from Alpaca paper API. Both
  succeeded.
- Updated `portfolio.md` with the synced snapshot.
- No orders placed. No trailing stops set. No ClickUp ping (per user
  instruction: notify only on trade placed or stop triggered).

**Next session:** Run the pre-market research workflow (movers,
overnight news on watchlist, macro calendar) to draft the first set of
trade ideas. Only then graduate to intraday execution.

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
