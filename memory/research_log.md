# Research Log

Newest entries first.

---

## 2026-07-01 — Pre-market

**Session:** Pre-market. Credentials provided; workflow unblocked.

### Portfolio snapshot (Alpaca)
- Account PA39FINFSDLL, ACTIVE, no trading blocks.
- Equity $100,000 / Cash $100,000 / Buying power $400,000 (4x margin).
- Zero open positions. Daytrade count 0. PDT flag false.

### Macro / calendar (all times ET)
- **07:15 — ADP Nonfarm Employment Change**. Forecast +118K, prev +122K.
- **08:00 — Fed Chair Kevin Warsh speaks.** Traders watching for rate-path
  guidance; markets priced cautiously ahead of Friday NFP.
- **09:00 — ISM Manufacturing PMI (June).** Forecast 53.8, prev 54.0.
- Also on the tape: construction spending, EIA petroleum, Fed Gov. Warsh
  remarks.
- H1 2026 finished as one of the strongest first halves in years; futures
  were mixed / softer pre-open Wed. Retail sentiment SPY bearish, QQQ
  bullish. Bank of America 2026 S&P target 7,100; Citigroup 7,700.
- **No FOMC, CPI, PPI, or NFP today** — the 30-min pre-event blackout in
  strategy.md §Risk Rules is NOT triggered by ADP/ISM.

### Watchlist news
- **NVDA** — Closed 6/30 at $200.09 (+2.63%), after-hours +$5.12. Still
  ~23% below May ATH after the June sector shakeout. Fiscal 2026 revenue
  $215.9B (+65% YoY). New Palantir partnership on gov't AI infra. No
  fresh negative catalyst pre-open.
- **AMD** — Cantor Fitzgerald raised PT to $700 from $500 on 6/29. Q2
  revenue guide ~$11.2B (+46% YoY), 56% GM. Lisa Su called MI450 pipeline
  "strengthening." Bullish setup into next earnings.
- **QTUM (Defiance Quantum ETF)** — Up 20.5% YTD, up 77% TTM, hit fresh
  highs recently. Broad quantum theme still in favor.
- **IONQ** — Consensus Buy across 17 analysts, PT range $30–$100 (very
  wide → high-uncertainty name). Recently announced $1.8B SkyWater
  acquisition for vertically-integrated quantum-chip production.
  Ecosystem also expanded via Capella/Skyloom/Qubitekk. Merger-related
  chop possible.
- **SPY** — Retail bearish; comes in off strong H1 with jobs-week data
  gauntlet ahead. Broad-market posture: cautious into 07:15 print.
- **QQQ** — Retail bullish; AI capex thesis intact — hyperscaler AI infra
  spend projected >$650B in 2026, tech-sector earnings growth ~46% into
  YE. Semis sub-index (SOXQ) +99% YTD despite the 6/5 Broadcom-guide
  flush.

### Held-name overnight news
- None held. No overnight-gap risk to any current position.

### Urgent catalyst?
- **No.** No held name is halted, no earnings on any held or watchlist
  name today, no macro shock, no >5% gap on watchlist. **ClickUp
  notification withheld** per strategy.md §7.

### Draft trade ideas (NOT executed — pre-market run)

```
Ticker: QQQ
Direction: long (starter)
Thesis: Fresh $100k account needs core index exposure; AI/tech earnings
  growth thesis into H2 remains intact; hyperscaler capex >$650B.
Catalyst: Post-open confirmation after ISM 09:00 print.
Entry zone: Wait for ISM at 09:00; enter on constructive tape into
  09:45 window.
Stop: -8% from entry (per strategy).
Target: Trail per strategy trailing rules.
Size: 4% equity (~$4,000, ~7-8 shares depending on print).
Confidence: 3/5
```

```
Ticker: SPY
Direction: long (starter)
Thesis: Diversify index exposure alongside QQQ; broker consensus PTs
  7,100–7,700 for YE.
Catalyst: Same jobs-data window (ADP 07:15, ISM 09:00).
Entry zone: Post-ISM confirmation, 09:45–10:15.
Stop: -8% from entry.
Target: Trail.
Size: 3% equity (~$3,000).
Confidence: 3/5
```

```
Ticker: NVDA
Direction: long (starter)
Thesis: 23% pullback from May ATH into a strong fiscal 2026 print
  ($215.9B rev, +65% YoY). AH strength on 6/30. AI infra thesis
  reinforced by Palantir gov't deal.
Catalyst: Sector momentum; no negative overnight news.
Entry zone: $198–$202 on constructive tape. Avoid chasing above $205
  pre-open.
Stop: -8% (~$183 if entered $199).
Target: Trail to break-even at +10%, 5% trail after +20%.
Size: 3% equity (~$3,000 = ~15 shares).
Confidence: 3/5
```

```
Ticker: AMD
Direction: long (starter)
Thesis: Cantor +$200 PT raise on 6/29 to $700; strong Q2 guide and MI450
  ramp. Confirmation-of-strength setup.
Catalyst: Analyst upgrade tailwind, semis sector +99% YTD.
Entry zone: Wait for open; enter on relative-strength confirmation vs
  SOXQ.
Stop: -8%.
Target: Trail.
Size: 2% equity (~$2,000).
Confidence: 3/5
```

```
Ticker: QTUM
Direction: long (thematic starter)
Thesis: Quantum-theme ETF at fresh highs, diversified vs single-name
  IONQ risk. +20.5% YTD, +77% TTM.
Catalyst: Continued theme momentum.
Entry zone: Any constructive open, size small at fresh highs.
Stop: -8%.
Target: Trail.
Size: 2% equity (~$2,000).
Confidence: 2/5 (chasing highs, so smaller size)
```

```
Ticker: IONQ
Direction: PASS today
Thesis: PT dispersion $30–$100 (wide), merger-integration overhang from
  SkyWater deal. Prefer QTUM for quantum exposure until IONQ tape is
  cleaner.
Catalyst: N/A.
Entry zone: N/A.
Stop: N/A.
Target: N/A.
Size: 0%
Confidence: N/A
```

### Intended cash deployment (if all ideas trigger)
- QQQ 4% + SPY 3% + NVDA 3% + AMD 2% + QTUM 2% = **14% deployed**,
  86% cash remaining. Well above 10% cash floor. Semi cluster
  (NVDA+AMD+QTUM) at ~7% — well below 40% sector cap.

### Next action
- Monitor 07:15 ADP + 08:00 Warsh + 09:00 ISM. If any print is a shock
  or a watchlist name gaps >5%, re-evaluate and consider a mid-morning
  ClickUp ping. Otherwise proceed with above ideas at intraday session.

**Sources consulted:**
- Alpaca REST `/v2/account`, `/v2/positions` (paper).
- Kiplinger — [Economic Calendar week of June 29–July 3](https://www.kiplinger.com/investing/economy/this-weeks-economic-calendar)
- Investing.com — [ADP / PMI / oil Wed calendar](https://www.investing.com/news/stock-market-news/adp-employment-manufacturing-pmi-and-oil-inventories-due-wednesday-93CH-4768512)
- CNBC — [NVDA quote & news](https://www.cnbc.com/quotes/NVDA)
- CNN — [AMD forecast](https://www.cnn.com/markets/stocks/AMD)
- TipRanks — [QTUM ETF quantum breakout 2025–2026](https://www.tipranks.com/news/qtum-etf-and-the-quantum-computing-breakout-what-the-2025-2026-milestone-wave-means-for-tech-investors)
- Benzinga — [IONQ price prediction / analyst targets](https://www.benzinga.com/money/ionq-stock-price-prediction)
- Stocktwits — [Nasdaq/SPX/Dow futures ahead of payrolls](https://stocktwits.com/news-articles/markets/equity/stock-market-today-dow-nasdaq-sp500-futures-jobs-report-nke-tsla-nio-mu-lunr-cvkd/cZm3eh3R7KL)
- Kavout — [June semi sell-off recap](https://www.kavout.com/market-lens/what-triggered-the-recent-semiconductor-sell-off)
- Intellectia — [Chip sector June 2026 strategy](https://intellectia.ai/blog/chip-stocks-rebound-investment-strategy-june-2026)

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
