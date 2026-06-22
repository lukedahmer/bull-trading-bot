# Research Log

Newest entries first.

---

## 2026-06-22 — Pre-market

**Session:** Pre-market (Monday). Unblocked: Alpaca creds now wired; using
built-in web search in place of Perplexity until `PERPLEXITY_API_KEY` is
provisioned.

### Account snapshot (Alpaca `/v2/account`)
- Equity $100,000.00 / Cash $100,000.00 / Buying power $400,000.00.
- Long market value $0. No positions. Status ACTIVE. PDT false.
- Account opened 2026-05-12; first real research session.

### Macro tape
- **US futures lower, mixed mood.** Iran tensions re-flared over the
  weekend: first round of US-Iran talks in Switzerland was reported as
  constructive, but Trump then threatened fresh strikes and warned
  Tehran against closing the Strait of Hormuz; Iranian media said
  Tehran suspended negotiations, sources say still ongoing. Oil bid.
- **Fed last week (Jun 16-17):** rates held, but dots turned hawkish —
  nearly half of FOMC members now pencil in at least one more hike
  before year-end. Risk-off tilt vs. last month.
- **This week's data:** PCE price index (Fed's preferred inflation
  gauge) is the headline print; no FOMC, no NFP, no CPI today.
- **Sector tape:** SOX +6.4% spike noted after Trump/Apple announcement
  of Apple–Intel US chip partnership (Intel +10.6% record). Semis
  leadership is narrow but intact; AI-infra rotation continues.

### Watchlist scan

**NVDA** — *Major catalyst today.* NVIDIA is being added to the S&P 500
on **June 22, 2026**. Expect passive index buying through the open and
into close-on-rebalance. Fiscal-2026 revenue $215.9B (+65% YoY); 62
analysts at "Strong Buy", avg 12-mo PT $298.93. Separate item: $25B
multi-tranche debt offering closed June 18. Tape-positive.

**AMD** — YTD +133%, mkt cap >$834B. Citi upgrade ("AI underappreciated").
But sector was bruised June 5 on Broadcom guide; AMD -10.86%
intraday that day. Volatile, no immediate single-name catalyst into
today's open.

**QTUM** — Defiance Quantum ETF. YTD +47.39% vs QQQ +17.42%; trailing
12-mo +82.93% vs QQQ +35.17%. AUM >$6B. New sister fund QTUP launched
(early-stage pure-plays). Core thematic vehicle, equal-weight ~2%/name
across 83-85 holdings.

**IONQ** — Duke + IonQ demonstrated 3-node distributed entanglement over
remote atomic qubits (modular QC milestone). Horizon Quantum ordered a
256-qubit trapped-ion system, sited Dublin under Ireland's National
Semiconductor Strategy. IonQ registered as federal lobbying client
2026-06-15 (defense/homeland-sec/aerospace). News is constructive but
no fresh price catalyst into today's session.

**SPY / QQQ** — QQQ traded $721.97–$744.37 recently, last seen $732.31
pre-market, ~858k pre-mkt shares. Intermediate trend still bullish but
leadership narrow (semis-heavy). Futures soft pre-open on geopolitics.

### Other pre-market movers noted
- **CDT** +152% on volume; **CAST** +130% on Starlink reseller deal —
  not on watchlist, no action.
- **ACN** -16% on revenue guide cut; **NVCR** -16% on Phase-3 failure
  — not on watchlist.

### Risk read
- Geopolitical tail = oil/energy higher, equities under modest pressure.
- Hawkish Fed dot-plot caps the "rate-cut bid" for QQQ duration.
- Semi rotation still intact; passive flow into NVDA today is a tailwind.

### Draft trade ideas (NOT placed — pre-market drafting only)

```
Ticker: NVDA
Direction: long (starter)
Thesis: S&P 500 inclusion today drives meaningful passive demand;
  fiscal-2026 fundamentals already strong (+65% YoY rev).
Catalyst: Index-inclusion rebalance, close-of-day passive prints.
Entry zone: after 9:30 open settles; avoid first 5-min wick.
Stop: -8% from fill (strategy hard stop).
Target: +10% (move to break-even stop per strategy rule).
Size: 2% equity = $2,000 starter.
Confidence: 4/5
```

```
Ticker: QTUM
Direction: long (core thematic)
Thesis: Equal-weight quantum ETF, AUM >$6B, 47% YTD vs QQQ 17%.
  Lower single-name risk than IONQ; survives a single-name blowup.
Catalyst: Continued quantum-news flow, fund growth, no-FOMC week.
Entry zone: scale-in on any -1% intraday dip.
Stop: -8% from VWAP entry.
Target: trail per strategy (BE stop after +10%, 5% trail after +20%).
Size: 2% starter ($2,000), willing to add to 4%.
Confidence: 4/5
```

```
Ticker: QQQ
Direction: long (index core)
Thesis: Trend bullish, but geo-tail and hawkish dots argue for staggered
  entry rather than full-size at open.
Catalyst: PCE later this week — wait for print before sizing up.
Entry zone: split: 1% on green-after-first-hour, 1% on dip to prior day's
  VWAP, hold remainder for post-PCE.
Stop: -8% from blended entry.
Target: trail per strategy.
Size: 2% starter, can scale to 5%.
Confidence: 3/5
```

```
Ticker: IONQ
Direction: watch (no entry yet)
Thesis: Real engineering progress (Duke 3-node entanglement, Horizon
  256-qubit deal), but no fresh price catalyst today and single-name
  volatility is high.
Catalyst: Next earnings or contract announcement.
Entry zone: wait for break above last week's high on volume, or hold
  exposure via QTUM.
Stop: n/a (no position).
Size: 1% if/when triggered (high-vol name).
Confidence: 2/5
```

```
Ticker: AMD
Direction: watch (no entry yet)
Thesis: +133% YTD, Citi upgrade constructive, but the June 5 -10.86%
  flush shows how violent the unwinds can be off bad sector guides.
Catalyst: Next data-center customer win or earnings.
Entry zone: prefer to come in via NVDA + QTUM today; revisit AMD if it
  reclaims a clean range high on volume.
Size: 2% when triggered.
Confidence: 2/5
```

### Decision
- **No trades placed this session** (per strategy: pre-market run drafts
  only).
- **No ClickUp ping**: no held-name earnings, no halts (we hold
  nothing), no >5% gaps on watchlist, no overnight macro *shock* (Iran
  is simmering, not erupting). NVDA S&P inclusion is a known,
  scheduled event, not an urgent surprise.

### Next session
- Intraday: confirm NVDA open behavior; if it gaps cleanly, start the
  $2k starter after first-hour settles. Pair with $2k QTUM scale-in.
- Watch oil and DXY for Iran headline risk.
- PCE later this week — no full-size adds before the print.

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
