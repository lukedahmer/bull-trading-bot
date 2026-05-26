# Research Log

Newest entries first.

---

## 2026-05-26 — Pre-market

**Session:** Pre-market, first trading day after Memorial Day (May 25 closed).

**Status:** Workflow unblocked — Alpaca creds available in session. Used built-in web search in lieu of Perplexity (PERPLEXITY_API_KEY still not configured); findings are sourced and clearly noted.

### Account snapshot (Alpaca /v2/account)
- Equity $100,000 · Cash $100,000 · BP $200,000 · long mkt value $0.
- Status ACTIVE, no positions (verified via /v2/positions → `[]`).
- This is essentially a clean-slate paper account.

### Macro / tape
- US equity futures bid overnight on US–Iran progress narrative: ES ~+0.6%, NQ ~+1.0%, YM ~+0.5%.
- S&P 500 entered Tuesday's open on an 8-week winning streak; Nasdaq 7 of 8.
- Driver: reports of advancing US–Iran talks that could reopen the Strait of Hormuz. Brent -5% / WTI -8% on the week. Sticking points remain: Iranian enriched-uranium stockpile and tolls on the Strait. Headline-risk both ways.
- Fed: market pricing ~2x 25bp cuts across the remainder of 2026. No FOMC, CPI, PPI, NFP today.
- QQQ technicals mixed: MACD turned negative 5/19; Aroon flipped bullish 5/22.

### Watchlist updates

**NVDA**
- Reported FY27 Q1 on 5/20: EPS $1.87 vs $1.76 est (+6.25%), revenue $81.61B vs est (+3.16%, +85% YoY). Data Center $75.25B (+92% YoY).
- Pre-mkt reference (5/22 close-area): ~$221. Recent tape -1.9%; post-earnings digestion / profit-taking.
- BofA reiterated NVDA + AMD as top AI chip picks.

**AMD**
- Q1 2026: revenue $10.3B (+38% YoY), Data Center record $5.8B (+57% YoY) — now >50% of total revenue.
- Lisa Su flagged ~35% CPU growth/yr for next 5 years (5/22).
- Trades near $421; 52-wk $107.67–$469.22. Trend strong.

**IONQ**
- Q1 2026 revenue $64.7M (+755% YoY); sold first 256-qubit system; FY guide raised to $260–270M.
- Opened 22,000 sq ft Boulder R&D lab.
- US Commerce awarded $2B across 9 quantum names with NIST taking non-controlling minority equity stakes; IONQ +12% on the news cycle. Sector rotation tailwind into quantum.

**QTUM** (Defiance Quantum ETF)
- 2025 return 36.69%; 2024 50.54%; outpaced NDX. Diversified quantum exposure, lower idiosyncratic risk than IONQ.

**SPY / QQQ**
- SPY consensus year-end ~7,600 (≈+11% from current). QQQ +11% trailing 30d on AI chip strength.
- Mixed valuation: QQQ P/E ~41 — sensitive to any hawkish surprise.

### Pre-market movers / urgent catalysts
- No held names to flag (we own nothing). No watchlist name halted or gapping >5% in either direction.
- AZO reports today (5/26) — not on watchlist; ignore.
- No FOMC, CPI, PPI, NFP today → no blackout window from strategy §"Risk rules".

### Trade ideas (DRAFT — do NOT place this session)

```
Ticker: SPY
Direction: long (starter)
Thesis: Re-enter market via index after Memorial Day with futures bid; 8-wk SPX streak intact; Iran/oil de-risking.
Catalyst: Strait of Hormuz progress; Fed cut path; no event risk today.
Entry zone: open or first pullback to VWAP
Stop: -8% hard (per strategy); near-term tactical stop ~-3% under entry
Target: SPY ~7,600-equivalent into year-end
Size: 2% equity ($2,000) starter; scaleable to 5%
Confidence: 3/5
```

```
Ticker: QQQ
Direction: long (starter)
Thesis: AI-chip leadership + Nasdaq 7/8 wk green; pair with SPY to balance high-P/E exposure.
Catalyst: Macro relief + NVDA/AMD strength bleeding through.
Entry zone: open or pullback toward 20-day MA
Stop: -8% hard; tactical -3% under entry
Target: 1.5–2x SPY beta into Q3
Size: 2% equity ($2,000) starter
Confidence: 3/5
```

```
Ticker: NVDA
Direction: long (starter)
Thesis: Earnings beat 5/20 + Data Center +92% YoY; recent -1.9% tape = post-print digestion, not thesis break.
Catalyst: Sell-side reiterations (BofA top pick), guidance cadence.
Entry zone: $215–$222 (below post-print pivot)
Stop: -8% hard from entry
Target: 52-wk high retest
Size: 2% equity ($2,000) starter; can pyramid to 5%
Confidence: 4/5
```

```
Ticker: AMD
Direction: long (starter)
Thesis: Q1 +38% rev, DC record, Lisa Su 35%/yr CPU CAGR call; BofA top pick alongside NVDA.
Catalyst: Server CPU share gains; AI accelerator roadmap.
Entry zone: $410–$425
Stop: -8% hard
Target: 52-wk high $469 retest
Size: 2% equity ($2,000) starter
Confidence: 4/5
```

```
Ticker: IONQ
Direction: long (small/starter)
Thesis: $2B US quantum grants + NIST equity stakes + 755% YoY rev = inflection. High-vol; size accordingly.
Catalyst: Continued gov't funding headlines; 256-qubit deliveries.
Entry zone: any pullback in first hour
Stop: -8% hard (tighter -10% trail given vol)
Target: re-rate higher on grant news; trail aggressively
Size: 1% equity ($1,000) — half-size due to vol
Confidence: 3/5
```

```
Ticker: QTUM
Direction: long (starter)
Thesis: Diversified quantum exposure — capture the theme without single-name blowup risk.
Catalyst: Same as IONQ but spread across ~70 holdings.
Entry zone: at open or first dip
Stop: -8% hard
Target: continuation of 2024/2025 +50%/+37% trend
Size: 2% equity ($2,000) starter
Confidence: 3/5
```

**Aggregate if all six ideas fire at starter sizes:** ~$11,000 deployed (~11% of equity); semis sector (NVDA+AMD+IONQ+QTUM) ≈ $7,000 (≈7%), well below 40% cap; cash ~89%, well above 10% floor. Plenty of room to pyramid on confirmation.

### ClickUp notification decision
- Criteria (strategy.md §7): earnings beat/miss on held name, halted stock we own, macro shock, gap >5% on watchlist.
- We hold nothing; no halts; no >5% gap on any watchlist name; no macro shock (Iran narrative is risk-on, not shock).
- **No ClickUp ping sent.**

### Sources
- Alpaca paper API `/v2/account`, `/v2/positions` (live response captured this session).
- [CNBC: Oil prices post weekly loss as U.S. and Iran signal progress toward a deal](https://www.cnbc.com/2026/05/22/oil-prices-today-trump-iran-strait-of-hormuz-uranium-.html)
- [Benzinga: Memorial Day 2026 — Is Stock Market Open Today?](https://www.benzinga.com/markets/equities/26/05/52765375/memorial-day-2026-is-stock-market-open-today)
- [CNBC: Nvidia (NVDA) Q1 2027 earnings report](https://www.cnbc.com/2026/05/20/nvidia-nvda-earnings-report-q1-2027.html)
- [HeyGoTrade: AMD Stock Analysis 2026](https://www.heygotrade.com/en/blog/amd-stock-analysis-2026-how-amd-quietly-outperformed-nvidia-with-114-gain/)
- [The Quantum Insider: IonQ Reports $64.7M Q1 2026 Revenue](https://thequantuminsider.com/2026/05/06/ionq-reports-64-7-million-q1-2026-revenue-fueled-by-quantum-contracts-and-system-sales/)
- [CNBC: Quantum stocks soar as U.S. plans $2 billion funding incentives](https://www.cnbc.com/2026/05/21/quantum-stocks--us-taking-equity-stakes.html)
- [TipRanks: QTUM ETF and the Quantum Computing Breakout](https://www.tipranks.com/news/qtum-etf-and-the-quantum-computing-breakout-what-the-2025-2026-milestone-wave-means-for-tech-investors)
- [Tickeron: QQQ outlook 2026](https://tickeron.com/blogs/qqq-outlook-2026-an-ai-informed-view-of-the-nasdaq-100-etf-s-future-11624/)

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
