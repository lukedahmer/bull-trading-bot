# Research Log

Newest entries first.

---

## 2026-06-26 — Pre-market

**Session:** Pre-market research, no trades executed.

### Account snapshot (Alpaca)
- Equity: $100,000 / Cash: $100,000 / Buying power: $400,000
- Account `PA39FINFSDLL`, status ACTIVE, no positions, day-trade count 0.
- Starting from a clean slate. Cash floor (10% = $10k) gives ~$90k deployable.

### Macro / tape
- **Core PCE (May)** released yesterday (Jun 25) hotter: **3.4% YoY vs 3.3%
  prior**, headline PCE **4.1% vs 3.8%**. Reinforces "higher-for-longer"
  rates and is the proximate driver of weak pre-market tape today.
- Pre-market futures: **SPY -0.44%, NDX -0.89%, Dow +0.21%, RUT -0.14%**.
  Tech under pressure; rotation into defensives/cyclicals.
- No FOMC, CPI, or NFP today. Five second-tier economic events on the US
  calendar. No held-name earnings.

### Watchlist tape
- **NVDA** ~$195.74 (intraday range $192.13–$200.80). Avg analyst PT
  $298.93; Strong Buy (59 buys / 1 sell). Mkt cap ~$4.72T. Next
  earnings Aug 26. Goldman favors NVDA/AMD/AVGO basket; AI-chip
  complex rose into Jun 25 close (NVDA/AMD/INTC).
- **AMD** ~$523, UBS raised PT (agentic-AI CPU demand), Gartner
  named "company to beat for enterprise AI server CPUs". Closed
  the **MEXT acquisition** (memory bottlenecks for data center).
  Q1 2026 data-center rev $5.8B (+57% YoY).
- **IONQ** very volatile. Q1 rev $64.7M (+755% YoY). Northland raised
  PT to $70 on Jun 22. Trump signed **two quantum executive orders
  Jun 22** (QC-ADDS initiative, post-quantum crypto mandate) — sector
  tailwind. Down 7.35% on a recent session — high beta.
- **QTUM** $156.81–$165 zone, +54% YTD (vs SPY +11%). Defiance also
  launched **QTUP** (early-stage quantum sister fund) Jun 9 — does not
  affect QTUM holdings but signals strong inflows into the theme.
- **SPY / QQQ**: tape soft on PCE; no idiosyncratic catalyst today.

### Read of the tape
Hot PCE puts pressure on long-duration tech. Quantum theme has a fresh
policy tailwind (Trump EOs) that the market has only partially priced.
AI-semi complex still structurally strong but extended; AMD breakout
above $500 is the cleaner setup than NVDA at the moment. No urgent
catalyst on any name we'd hold — no need to ping ClickUp.

### Draft trade ideas (NOT executed — paper account is empty)

```
Ticker: QTUM
Direction: long (starter)
Thesis: Establish thematic anchor. Equal-weighted quantum + AI exposure,
  +54% YTD with fresh White House EO tailwind. Lower idiosyncratic risk
  than single-name quantum.
Catalyst: Trump quantum EOs (Jun 22) + ongoing inflows; theme leadership.
Entry zone: $156–$160 (let pre-market weakness flush)
Stop: -8% from fill (~ $144)
Target: $185 (+15–18%) over 4–8 weeks
Size: 2% equity (~$2,000, ~12–13 sh)
Confidence: 3/5
```

```
Ticker: AMD
Direction: long (starter)
Thesis: Cleanest AI-semi breakout. UBS PT raise, Gartner top-pick,
  MEXT memory acquisition closed, Q1 DC +57% YoY. Hot PCE may give a
  better entry on a red open.
Catalyst: Enterprise AI server CPU adoption; MEXT integration narrative.
Entry zone: $505–$515 on weakness (don't chase $523)
Stop: -8% (~ $470)
Target: $600 (+15–18%) into Q2 print
Size: 2% equity (~$2,000, ~4 sh)
Confidence: 3/5
```

```
Ticker: IONQ
Direction: watch (no entry today)
Thesis: Pure-play quantum on Trump-EO tailwind, but vol is brutal
  (-7%+ days are routine). Want to see it base before committing.
Catalyst: Quantum EOs, federal contract flow, Q2 print (TBA).
Entry zone: only on a tested base (>3 sessions of $40–$45 hold);
  otherwise express via QTUM.
Stop: -8% from fill
Target: $70 (Northland PT)
Size: 1% equity max (high beta), only if base confirms
Confidence: 2/5
```

```
Ticker: NVDA
Direction: long (small starter on weakness)
Thesis: Mega-cap AI flywheel intact; consensus PT $299 vs $196 spot.
  But tape is heavy; want a pullback, not a chase.
Catalyst: Aug 26 earnings; ongoing hyperscaler capex headlines.
Entry zone: $188–$192 (test of yesterday's low)
Stop: -8% (~ $173)
Target: $230 (+20%)
Size: 2% equity (~$2,000, ~10 sh)
Confidence: 3/5
```

```
Ticker: SPY / QQQ
Direction: hold off
Thesis: No edge today. Hot PCE → broad pressure, but no defined level
  to lean against. Revisit if SPY tags 50DMA or after a clear reversal.
```

### Plan for the cash session
- Open: do not chase the open. Watch first 30 min for direction
  off PCE digestion.
- If SPY holds green by 10:30 ET and QTUM is constructive, take the
  QTUM starter first, then AMD on any retest of $510.
- Defer NVDA and IONQ to a confirmation session.
- Combined max deployment today: ~6% equity (~$6k notional), keeping
  ~$94k cash. Well clear of the 10% cash floor.

### Notifications
- **No ClickUp ping sent.** No held names → no earnings/halt/macro-shock
  trigger that matches strategy.md's ClickUp criteria.

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
