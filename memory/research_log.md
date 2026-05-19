# Research Log

Running log of market research, news, and analysis done each session.

## Format
```
### [DATE] [Session Type]
**Market Conditions**: [brief macro summary]
**Key News**: [any major catalysts found]
**Watchlist Updates**: [any changes to what we're watching]
**Thesis Notes**: [anything that strengthens or weakens current positions]
```

---

## Research History

### 2026-05-19 End of Day

**Account snapshot (Alpaca EOD)**:
- Equity: $100,000.00 (last equity $100,000.00)
- Cash: $100,000.00 | Buying power: $200,000.00
- Open positions: none
- Filled orders today: none (zero trades executed this session)

**Performance**:
- Portfolio today: 0.00% (flat, undeployed)
- SPY today: ~-0.79% (close ~$732.84 vs prior close $738.65; intraday range $731.56-$737.62)
- Relative: +79 bps vs SPY by virtue of being entirely in cash

**Market Conditions**: SPX/NDX closed broadly red into Wednesday's NVDA
print. Risk-off / de-risking ahead of the AI-tape catalyst rather than a
macro shock — no CPI/PPI/NFP/FOMC today. New Residential Construction and
NAR Pending Home Sales prints were not tape-moving.

**Observations**:
- First session with live Alpaca credentials confirmed at EOD. Account
  ACTIVE (PA39FINFSDLL); $100K cash; zero positions; zero filled orders.
- The pre-market run drafted three starter ideas (QTUM/SPY/QQQ at ~3%
  each) but the playbook was hold-only for this session, so the cash
  stayed parked. That happened to outperform a -0.79% SPY tape.
- No catalyst occurred today that would alter the pre-market thesis. The
  trade plan into NVDA AMC tomorrow stands: stay out of NVDA/AMD until
  after the print; deploy SPY/QQQ/QTUM baseline tomorrow if conditions
  permit.

**Next session (2026-05-20 pre-market)**:
- Execute the QTUM/SPY/QQQ starter entries (3% each, ~$3,000 each).
- Re-check Alpaca clock + macro calendar before trading.
- Hold NVDA/AMD untouched until Thursday pre-market (after Wed AMC print).
- Confirm IONQ pullback status; still wait for 10–15% retrace.

**ClickUp notification**: EOD ping sent per protocol.

---

### 2026-05-19 Pre-Market

**Account snapshot (Alpaca)**: Equity $100,000 / Cash $100,000 / BP $200,000.
Zero positions. ACTIVE, no blocks. Day-trade count 0.

**Time anomaly**: Alpaca `/v2/clock` returned `is_open: true` at
`2026-05-19T12:28 ET` — i.e. regular session is already open even though
session was framed as pre-market. Honored the user's "pre-market" framing
(drafts only, no trades placed). Next session should re-check timing
before assuming pre-market rules apply.

**Market Conditions**: Pre-market index futures soft into NVDA earnings —
SPY −0.49%, NDX −0.78%, DJI −0.31%, RUT −0.62%. Chip / AI complex broadly
red as the tape de-risks. Today's data: New Residential Construction
(08:30 ET) and NAR Pending Home Sales (10:00 ET) — neither tape-moving.
No CPI/PPI/NFP/FOMC today. Fed: 2026 dot plot implies ~1 more cut (median
3.4%); Powell continues "wait-and-see". Speculative micro-cap squeezes
(AMST +199%, INM +144%, MTVA +52%) — noise, not actionable for this
strategy.

**Key News**:
- **NVDA earnings Wed 2026-05-20 AMC (Q1 FY27)** is the dominant catalyst
  of the week. Street: EPS $1.78, revenue $79.2B (+79.5% y/y). Whisper EPS
  $1.85. Buy-side revenue bar ≈ $80B+; Q2 guide bar ≈ $90B vs $86.6B
  consensus. Wedbush bullish; "priced for perfection" risk widely noted.
  CEO Jensen Huang signaling hope for renewed China AI-chip access; US
  H200 export licenses exist, China side has not authorized.
- **IONQ Q1 (May 6)**: revenue $64.7M (+755% y/y, +30% above mid-guide);
  FY26 guide raised to $260–270M; RPO $470M (+554% y/y); 60% of revenue
  now commercial. Stock +98% since Mar 30.
- **AMD**: Q1 revenue $10.25B (+38% y/y); Q2 guide $11.2B midpoint (+45%
  y/y) above $10.5B consensus. Targets raised: Melius $540, Citi $460,
  Evercore $579. Next earnings Aug 4 — no near-term binary risk.
- **QTUM**: ~86 holdings, equal-weight (~2% cap each), 0.40% ER. +84% TTM
  vs SPY; beating Tech category by ~29pp.
- **QQQ**: ~$708, +11% over 30d; avg 12-mo target ~$727. AI capex
  narrative ($5–8T cumulative through 2030) intact.

**Watchlist Updates**:
- Confirmed core 6 (QTUM, IONQ, NVDA, AMD, SPY, QQQ).
- Added **RGTI** to watchlist tracker (mentioned in strategy.md but not
  researched this session — pick up next pre-market).
- Tier 1 (deploy first, no single-name binary risk): QTUM, SPY, QQQ.
- Tier 2 (wait for post-NVDA print): NVDA, AMD.
- Tier 3 (chase risk; wait for pullback): IONQ.

**Thesis Notes**:
- Strategy.md explicitly says "Anything with earnings in the next 48 hours
  (earnings are a coin flip)" → avoid. **NVDA is within 48h** → no
  pre-print entry. AMD trades as NVDA-tape proxy → also defer.
- Index + basket ETFs (SPY, QQQ, QTUM) are not earnings-exposed in the
  single-stock sense → cleared for starter entries next session.
- Cash floor: 20% per strategy; with $100k cash we have ample dry powder.
  Plan deploys ~9–15% in three 3–5% starters → still ~85–91% cash. Well
  inside floor.
- IONQ thesis is fundamentally strong but the entry is extended; chasing
  on day-1 of deployment violates the "patience is a position" guardrail.

**Trade Ideas Drafted (NOT placed in this pre-market run)**:
1. QTUM — BUY starter 3% (~$3,000), market on open next session.
   Stop −8%, trail 10% per strategy. Confidence 3/5.
2. SPY  — BUY starter 3% (~$3,000), market on open next session.
   Stop −8%, trail 10%. Confidence 4/5.
3. QQQ  — BUY starter 3% (~$3,000), market on open next session.
   Stop −8%, trail 10%. Confidence 4/5.
4. NVDA — HOLD OFF. Re-evaluate Thu pre-market after Wed AMC print.
   Buy a clean beat-and-raise; pass on guide-down; do not chase a gap.
5. AMD  — HOLD OFF until post-NVDA tape. Consider 3% starter on Thu if
   NVDA confirms.
6. IONQ — HOLD OFF; wait for 10–15% pullback before initiating 2–3%
   starter.

**ClickUp notification**: NOT sent. No held-name shock, no halt, no >5%
gap on watchlist, no macro tape-bomb today. NVDA earnings tomorrow are
material but we hold no position, so per strategy this does not meet the
urgent-catalyst bar.

---

### 2026-05-19 Pre-Market (BLOCKED — earlier run)

Earlier in the session, Alpaca / ClickUp credentials were absent. That
prior log entry has been superseded by the unblocked run above. Kept
historical note: the bootstrap run produced no fabricated research and
placed no trades.

---
