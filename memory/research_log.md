# Research Log

Newest entries first.

---

## 2026-05-31 — Pre-market (Sunday session, prepping for Mon 06-01 open)

**Session:** Pre-market research run. Market is closed (Sunday). Next open
Monday 2026-06-01 09:30 ET per Alpaca `/v2/clock`.

**Account snapshot (Alpaca paper PA39FINFSDLL):**
- Equity: $100,000 — Cash: $100,000 — Buying power: $200,000
- Positions: **none**. Clean slate.

### Macro / calendar this week
- **Fri 2026-06-05 08:30 ET — May NFP jobs report.** Primary catalyst. April
  printed +115K (vs 62K est) with March revised up to +185K. Consensus
  framing: "low-hire, low-fire" labor market. A hot print would lift yields
  and squeeze multiples; a soft print revives rate-cut hopes.
- Other June dates (out of session): CPI 6/10, PPI 6/11, FOMC 6/16–17.
- Backdrop: SPX & NDX both RSI ~73 (overbought but momentum-driven).
  10Y yields fell ~11bp last week, oil down ~10% on US-Iran peace-deal
  optimism — risk-on tape, but stretched.

### Watchlist updates

**NVDA**
- Reported Q1 FY27 on **2026-05-20**: revenue $81.6B (+85% YoY), beat $78.8B
  est; adj EPS $1.87 vs $1.76 est. Data center $39.1B (+69% YoY).
- Q2 guide: **$91B**, well above Street.
- New disclosure: Vera CPU launches NVDA into server CPU market — CFO
  framed a $200B incremental TAM with ~$20B CPU revenue visibility this
  year. Direct competitive threat to AMD/Intel.
- Stock sold off post-print ("buy rumor, sell news"); 30x forward, the bar
  was extreme. Earnings risk for held names is now **behind us**.

**AMD**
- Q1 data center $5.8B (+57% YoY) — healthy but dwarfed by NVDA $39B run
  rate. NVDA's CPU entry is an overhang. Wait for sector rotation or AMD
  AI MI400-series datapoints before committing.

**IONQ**
- Q1 revenue **$64.7M (+755% YoY)**. Stock +11.5% on 5/21 on print + raised
  guide. Wedbush target $75 Outperform; Jefferies $85 Buy.
- SkyWater acquisition cleared shareholder vote.
- Government tailwind: Missile Defense Agency contract; new 100-qubit
  Tempo system for South Korea National Quantum Computing Center.
- **Caveat:** P/S ~109 — any AI/quantum bubble cooldown could halve it.

**QTUM (Defiance Quantum ETF)**
- **AUM crossed $5B on 2026-05-26.** Same day, Trump administration
  unveiled ~$2B federal quantum funding push (Commerce awarded grants to
  9 firms incl IBM 2026-05-21).
- Trading ~$144.91 (May 8 snapshot), +84% TTM, outperformed SPX by ~57pp.
- Cleaner thematic vehicle than IONQ — diversified across quantum names
  with lower single-name blowup risk.

**SPY / QQQ**
- Both extended (RSI 73). Constructive but no rush to add at index level
  ahead of Friday NFP. Use any NFP-driven dip into 50dma as the entry.

### No urgent catalyst on held names
We hold nothing — no halts, no gap-risk events on the book, no earnings
landmines. **No ClickUp ping warranted.**

### Trade ideas drafted (NOT executed — pre-market session)

1. **QTUM — long starter (highest conviction this week)**
   - Direction: long
   - Thesis: Diversified quantum exposure with federal tailwind ($2B
     program 5/21) and crossing-the-Rubicon AUM milestone driving
     reflexive inflows. Lower idiosyncratic risk than IONQ.
   - Catalyst: Federal funding flow + quantum-sector momentum.
   - Entry zone: Monday open or first pullback after NFP.
   - Stop: -8% from entry per strategy.
   - Target: +15–20% (trail per strategy after +10%).
   - Size: 2% = $2,000. Can scale to 4% if NFP-driven dip materializes.
   - Confidence: **4/5**

2. **IONQ — long starter (speculative)**
   - Direction: long
   - Thesis: Q1 +755% YoY, raised guide, defense contracts, sell-side
     targets $75–85. Pure-play on US quantum funding push.
   - Catalyst: Quantum funding flow + SkyWater close + Korea Tempo
     deployment.
   - Entry zone: Monday — accept some chase risk; cap size due to P/S 109.
   - Stop: -8% (tight given vol; may need wider if implied vol > 80).
   - Target: First trim at +15%, full trail after +20%.
   - Size: 2% = $2,000. Do **not** scale up — single-name vol is extreme.
   - Confidence: **3/5**

3. **NVDA — long starter (post-earnings reset)**
   - Direction: long
   - Thesis: Earnings now behind us; $91B Q2 guide + Vera CPU $200B TAM
     story = multi-quarter narrative. The "sell the news" dip is buyable
     if it holds the 50dma.
   - Catalyst: Vera CPU narrative + AI capex durability into H2 2026.
   - Entry zone: Wait for confirmation candle off post-earnings low.
   - Stop: -8%.
   - Target: Trail per strategy.
   - Size: 2% = $2,000 starter; willing to add to 5% on weekly close above
     pre-earnings high.
   - Confidence: **4/5**

4. **AMD — watchlist only, no entry**
   - NVDA's CPU push is an active overhang. Need to see AMD response
     (MI400 traction, Epyc share defense) before sizing. **Skip Mon.**

5. **SPY / QQQ — watchlist only**
   - RSI 73 + NFP Friday = no urgency. Will revisit Friday afternoon if
     NFP forces a flush into 50dma.

### Plan for Monday open
- Do not chase the open. Watch first 15 minutes for direction.
- If tape is firm: deploy 2% QTUM + 2% IONQ + 2% NVDA = 6% / $6,000.
- If tape gaps up >1% on SPY: wait — do not chase ahead of NFP.
- Re-evaluate Friday post-NFP for any 4th add and/or sizing up to 5%.
- Cash target after Monday deployment: $94,000 (94%), well above 10% floor.

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
