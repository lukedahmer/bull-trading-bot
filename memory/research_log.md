# Research Log

Newest entries first.

---

## 2026-05-19 — Midday (BLOCKED, network)

**Session:** Midday risk-management sweep.

**Status:** Unable to execute the midday checklist. Credentials for
Alpaca and ClickUp were provided inline in the session prompt, but the
remote execution environment's network policy does not allow outbound
traffic to either host:

- `https://paper-api.alpaca.markets/...` → HTTP 403 ("Host not in allowlist")
- `https://api.clickup.com/...` → HTTP 403 ("Host not in allowlist")

Because of the network block I could not:

- `GET /v2/positions` — current holdings are unknown this session.
- `GET /v2/account` — equity/cash/buying-power unknown.
- Evaluate the -8% hard-stop rule on any name (no P/L data).
- Evaluate the +30% trim rule on any name.
- Tighten trailing stops on +15% winners.
- Place any orders.
- Send a ClickUp ping (and per the rule none would be sent anyway —
  no stop was triggered and no position was trimmed).

**Web search on movers:** Not run. Without a position list there is no
held name to investigate, and per the standing rule of this log I will
not fabricate research.

**Memory hygiene:** `portfolio.md` and `trade_log.md` are intentionally
NOT updated — there is no verified new state to write. The portfolio
file still carries its "never synced" banner from the pre-market
session, which remains accurate.

**Secrets handling:** The Alpaca and ClickUp credentials supplied in
the prompt were used only for the in-session HTTP calls above. They
are NOT being written to the repo. The environment's
Variables/Secrets panel is the correct place for them so future
sessions can read them from env vars without exposing them in chat or
git history.

**Next session unblocker:**
Add `paper-api.alpaca.markets` and `api.clickup.com` to the
environment's outbound network allowlist (and move the credentials
into the environment's Variables/Secrets settings). See
https://code.claude.com/docs/en/claude-code-on-the-web for how
environment network policy and secrets are configured.

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
