# Research Log

Newest entries first.

---

## 2026-06-12 — Pre-market (Friday)

**Session:** Pre-market. Credentials now wired in via session prompt.

### Account snapshot (Alpaca paper `PA39FINFSDLL`)
- Equity: $100,000 — Cash: $100,000 — BP: $400,000.
- Positions: none. Account is 100% cash. Status ACTIVE, not PDT-flagged.

### Tape / futures
- Dow futures +0.08%, S&P 500 futures +0.24%, Nasdaq-100 futures +0.45%
  (8:47 PM ET print, 6/11).
- QQQ traded $694–$719 range yesterday; last $716.92.
- Retail sentiment: bearish SPY, neutral QQQ.

### Today's primary catalyst — SpaceX IPO
- SpaceX debuts on Nasdaq today at ~$1.75T valuation, raising >$75B —
  largest IPO in history. Likely index-fund rebalance flows into SPY/QQQ
  over coming sessions and elevated open-bell volatility.

### Macro
- No high-impact US data print scheduled for today on the calendars I
  hit (no CPI/PPI/NFP/FOMC). Last CPI (6/10) printed 4.2% — sticky.
- Geopolitical: Trump signaled US-Iran peace framework is "in sight";
  drove semis +6%-type moves Thursday. Risk-on bias for AI/semi tape.

### Watchlist updates
- **NVDA** — $206.15 pre-mkt (+0.62% vs $204.87 close). South Korea AI
  cloud partnership; KKR/NVDA/Vistra/Kuwait IA $10B+ Helix Digital
  Infrastructure JV; Abridge medical-AI deal. BofA top semi pick,
  raised server-CPU TAM to $170B by 2030. 12-mo consensus PT $298
  (~+49%). Rating Strong Buy.
- **AMD** — ~$488. Surged ~+6% Thursday on the Iran de-escalation
  headlines. BofA PT raised to $560 (Buy). Earnings 8/4/26 (out of
  scope for this week's risk). Up ~114% YTD — chase risk if entering
  here.
- **IONQ** — ~$64; spiked +13.6% on 6/8 on a clutch of catalysts:
  $3.3B funding base, DARPA HAQ contract, pending SkyWater foundry
  deal, 100-qubit Tempo system to S. Korea KISTI. Q1 rev $64.7M
  (+755% YoY), FY guide $260–270M. $3.1B cash. Vol is brutal — size
  small.
- **QTUM** — $168.76 (6/2 close cited), +54% YTD, ~$6B AUM. Equal-
  weighted quantum+ML index. Cleanest diversified expression of the
  theme. New sister fund QTUP launched for pure-play exposure.
- **SPY / QQQ** — no idiosyncratic news; today's tape will be driven
  by the SpaceX print and any incremental Iran/Mid-East headlines.

### Trade ideas — DRAFT ONLY (no orders placed)

```
Ticker: QTUM
Direction: long (initiate core)
Thesis: Diversified quantum/ML thematic exposure. Anchors the theme
  without single-name blowup risk; trend is intact.
Catalyst: Continued quantum capex headlines; Willow/Tempo milestones.
Entry zone: $166–170
Stop: $155 (-~8%)
Target: $195 (12-mo)
Size: 2% ($2,000, ~12 sh)
Confidence: 4/5
```

```
Ticker: NVDA
Direction: long (initiate)
Thesis: Top semi pick into AI capex cycle; KKR/Helix + S. Korea +
  Abridge widen the moat. Pulled back $260B in mkt cap recently —
  acceptable re-entry zone with BofA + sell-side support.
Catalyst: Helix DC funding flow; H2 AI capex prints.
Entry zone: $200–207
Stop: $189 (-~8%)
Target: $260 first leg, $298 sell-side consensus
Size: 2% ($2,000, ~10 sh)
Confidence: 4/5
```

```
Ticker: IONQ
Direction: long (initiate, starter)
Thesis: Best-funded pure-play quantum name; DARPA + SkyWater + KISTI
  contracts validate commercial traction.
Catalyst: 256-qubit demo this year; foundry deal close.
Entry zone: $60–66
Stop: $58 (-~8%)
Target: $80 swing, $100 12-mo
Size: 1% ($1,000, ~16 sh) — half size for vol.
Confidence: 3/5
```

```
Ticker: AMD
Direction: WATCH (do not chase)
Thesis: Stock is up ~114% YTD and gapped on Iran headlines; entering
  $488 violates discipline. Wait for pullback to 20DMA or consolidation.
Catalyst: Aug 4 earnings — too far away to underwrite today.
Entry zone: $440–460 on pullback
Stop: $415
Target: $560 (BofA PT)
Size: 2% if/when trigger hits
Confidence: 2/5 (today)
```

```
Ticker: SPY / QQQ
Direction: HOLD off today
Thesis: SpaceX IPO will create unusual flow; better to read the tape
  through Friday's close than chase the gap. Will evaluate index
  starters Monday once IPO mechanics settle.
```

### Net plan for the day
- Pre-market: research only — no orders (per strategy step 4).
- Intraday: monitor SpaceX open print and watchlist gap-and-go behavior;
  evaluate intraday entries on QTUM/NVDA/IONQ if entry zones print.
- Risk budget today: max 5% of equity deployed across the three
  starter ideas ($5,000).

### Urgent-catalyst gate
- No held names → no earnings/halts on holdings.
- No macro shock today (no scheduled prints).
- No watchlist gap >5% pre-market (NVDA +0.62%, others quiet pre-bell).
- **ClickUp ping: SKIP.** SpaceX IPO is newsworthy but doesn't meet
  the strategy's "held-name halt / earnings / macro shock / >5% gap on
  watchlist" bar.

### Sources
- Pre-market futures + SpaceX framing — Stocktwits / Yahoo Finance
- NVDA — Robinhood / Yahoo Finance / CNN Markets
- AMD — GuruFocus / Yahoo Finance / Investing.com
- IONQ — StocksToTrade / Motley Fool / Yahoo
- QTUM — 24/7 Wall St / Yahoo / Defiance ETFs

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
