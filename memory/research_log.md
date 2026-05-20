# Research Log

Newest entries first.

---

## 2026-05-20 — Pre-market sync

**Session:** Pre-market, ~08:39 ET. Credentials now provided in-session
(Alpaca paper, ClickUp). Perplexity key still not provided, so no
external research was performed.

**Alpaca account snapshot** (`/v2/account`, `/v2/positions`):
- Account `PA39FINFSDLL`, status ACTIVE, not blocked.
- Equity $100,000.00 / Cash $100,000.00 / Buying power $200,000.00.
- Open positions: **none**.
- Market clock: `is_open=false`, next open 2026-05-20 09:30 ET. We are
  in pre-market, not "just opened" as the prompt asserted — verified
  against `/v2/clock`.

**Stop-loss sweep:** N/A — zero positions to evaluate.

**Trade ideas in queue:** None. The prior session (2026-05-19) was
blocked before any ideas were drafted, and no Perplexity research was
run today, so the idea queue is empty.

**Actions taken this session:**
- Pulled live Alpaca account + positions, refreshed `portfolio.md`.
- Did **not** place any orders — pre-market session per strategy
  (`strategy.md` decision workflow step 4: "do not place trades in the
  pre-market run"), and no qualified ideas exist regardless.
- Did **not** trigger any stop-losses — no positions held.
- Did **not** send a ClickUp ping — no trade, no stop-loss, no urgent
  catalyst observed (no research performed).

**Next session:** At/after 09:30 ET regular open, with research feed
available, draft watchlist ideas (QTUM, IONQ, NVDA, AMD, SPY, QQQ),
size at 2% default and enter only those that pass the checklist.

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
