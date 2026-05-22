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

### 2026-05-22 Pre-Market

**Account snapshot (Alpaca, GET /v2/account + /v2/positions)**:
- Equity: $100,000.00 | Last equity: $100,000.00
- Cash: $100,000.00 | Buying power: $200,000.00
- Long market value: $0.00 | Open positions: none
- Status ACTIVE (PA39FINFSDLL); no trading/transfer blocks; PDT false; day-trade count 0.
- Fourth consecutive session opening 100% in cash.

**Watchlist closing prints (Alpaca snapshot, 2026-05-21 close)**:
| Symbol | 5/21 Close | 5/20 Close | 1-day Δ | Note |
|---|---|---|---|---|
| SPY  | 742.71 | 741.31 | +0.19% | Drift higher, light vol |
| QQQ  | 714.41 | 713.07 | +0.19% | Same |
| QTUM | 149.38 | 145.23 | **+2.86%** | Quantum-grant sector lift |
| NVDA | 219.47 | 223.48 | **−1.79%** | Sell-the-news after the beat |
| AMD  | 449.44 | 447.55 | +0.42% | Holding gains; multi-day strength |
| IONQ |  58.87 |  52.49 | **+12.15%** | Sympathy rip; not a grant recipient |

**Market Conditions**:
- Risk-on tone into Friday. Stock futures higher overnight; oil softer
  on easing US–Iran tensions; geopolitical risk premium compressing.
- Macro calendar today: Michigan Consumer Sentiment **Final** at 10:00
  ET, NY Fed Staff Nowcast at 12:45 ET. **No CPI / PPI / NFP / FOMC**.
  No 30-minute pre-print blackout triggered by the strategy rules.
- Fed leadership transition: Powell's term as Fed Chair ends May 2026
  — successor speculation ongoing, watch for headline risk.

**Key News**:
- **NVDA Q1 FY27 print (Wed 2026-05-20 AMC)**: Revenue **$81.62B**
  (+85% y/y) vs Street ~$78.8B / whisper ~$80B → **beat both bars**.
  Q2 FY27 guide **$91.0B ± 2%** vs Street $86.84B → **raised**.
  Dividend and buyback bumped. Reaction Thursday: stock −1.79% to
  $219.47 — classic "buy-the-rumor / sell-the-news" digestion, not a
  thesis break. Beat-and-raise unlocks the NVDA/AMD pre-print
  embargo per strategy.md.
- **Quantum sector — Trump admin $2B CHIPS Act package (announced
  Thu 2026-05-21)**: Commerce Dept awards $2B in grants to nine
  quantum-computing companies, with the federal government taking
  minority equity stakes. Recipients: **IBM $1B, GlobalFoundries
  $375M, D-Wave (QBTS) ~$100M, Rigetti (RGTI) ~$100M, Infleqtion
  (INFQ) ~$100M, PsiQuantum $100M, Diraq $38M**, plus two others.
  **IonQ is NOT a recipient.** Despite that, IONQ closed **+12.15%
  ($58.87)** as the sector got a structural-tailwind re-rating.
  Direct grantees QBTS / RGTI / INFQ ripped +7% to +21% intraday.
  QTUM (equal-weight basket) captured the sector lift cleanly at
  **+2.86%**.
- **AMD**: Up modestly into NVDA print and held the gain post-print
  — $449.44 close. Sell-side: Baird $625 PT (~+39% upside), BofA
  keeps AMD + NVDA as "top AI chip picks", hyperscalers actively
  cultivating AMD as second source. No fresh binary risk before Aug
  earnings.
- **Macro**: Iran de-escalation narrative dominant; oil retreating;
  futures green. No tier-1 data print today.

**Watchlist Updates**:
- Tier 1 (deploy first — no single-name binary risk): **QTUM, SPY,
  QQQ**. Plan unchanged from 5/19 draft, but now four sessions stale.
- Tier 2 (post-NVDA print): **NVDA, AMD** — both cleared to enter.
  NVDA print was beat-and-raise; AMD tape confirms.
- Tier 3 (chase risk): **IONQ** — gapped +12% on a competitor catalyst
  rather than its own. Strategy says wait for 10–15% pullback before
  starter; today violates that condition harder than it did last week.
- **RGTI** carried forward for research; today's grant recipient list
  makes it materially more relevant.

**Thesis Notes**:
- The "anything with earnings in the next 48h" guardrail is now
  cleared for NVDA. Print landed Wed AMC; we are >48h post-print on
  Friday open. AMD next earnings Aug 4 — no near-term binary.
- The dominant operational issue remains the **non-execution streak**.
  Four consecutive sessions of carrying QTUM/SPY/QQQ baseline starters
  without firing. Cumulative drag vs SPY is small (~−21 bps thru
  5/21) but compounding while we sit. The plan is decided; the
  execution is the gap.
- The quantum-grant story is a structural positive for QTUM (basket
  captures D-Wave/Rigetti/Infleqtion automatically) but adds entry-
  timing risk on the basket — entering at +2.9% on a one-off catalyst
  is worse than entering pre-catalyst. Mitigation: split the QTUM
  starter into two tranches (half today, half on the next 2–3% dip)
  rather than chase the full size at the open gap.

**Trade Ideas Drafted (NOT placed in this pre-market run)**:

```
1. Ticker: SPY
   Direction: long (starter)
   Thesis: Establish baseline beta. Account is 100% cash; we cannot
     beat SPY from cash. Risk-on tape, futures up, no macro shock today.
   Catalyst: Carry-forward baseline trade; Iran de-escalation tailwind.
   Entry zone: MOO ~ $742–745
   Stop: −8% from fill (~$683)
   Target: open-ended (index hold); trim plan per strategy 30%+ rule.
   Size: 3% (~$3,000 = ~4 shares)
   Confidence: 4/5
```
```
2. Ticker: QQQ
   Direction: long (starter)
   Thesis: AI/tech tilt to complement SPY; captures NVDA/MSFT capex
     story; index, not single-name.
   Catalyst: Same baseline; NVDA beat-and-raise validates capex thesis.
   Entry zone: MOO ~ $714–717
   Stop: −8% from fill (~$657)
   Target: open-ended.
   Size: 3% (~$3,000 = ~4 shares)
   Confidence: 4/5
```
```
3. Ticker: QTUM
   Direction: long (starter, scale-in)
   Thesis: Quantum-theme basket; equal-weight basket caps single-name
     blow-up; sector just received $2B CHIPS Act structural support.
   Catalyst: Trump admin quantum grants (5/21) — re-rating tailwind.
   Entry zone: split — half MOO ~ $149, half on a 2–3% retrace.
   Stop: −8% from blended fill
   Target: open-ended; equal-weight basket hold.
   Size: 3% total (~$3,000 = ~20 shares), split 1.5%/1.5%
   Confidence: 4/5
```
```
4. Ticker: NVDA
   Direction: long (starter)
   Thesis: Beat-and-raise on Q1 FY27 ($81.6B vs $78.8B; guide $91B vs
     $86.8B). "Sell-the-news" dip to $219 = constructive entry.
   Catalyst: Post-print digestion; AI capex narrative intact.
   Entry zone: $217–222
   Stop: −8% (~$202)
   Target: trail per strategy; trim 50% at +30%
   Size: 3% (~$3,000 = ~14 shares)
   Confidence: 3/5 (post-print chop is real)
```
```
5. Ticker: AMD
   Direction: long (starter)
   Thesis: NVDA-tape proxy, Q1 beat, $11.2B Q2 guide raised; hyperscaler
     second-source bid; Baird $625 PT.
   Catalyst: NVDA confirmed; AMD held strength into and out of the print.
   Entry zone: $445–452
   Stop: −8% (~$413)
   Target: $540+ (Melius)
   Size: 3% (~$3,000 = ~7 shares)
   Confidence: 3/5
```
```
6. Ticker: IONQ
   Direction: HOLD OFF (no entry)
   Thesis: Gapped +12% on a competitor's catalyst, not its own; entry
     would chase a sympathy move. Strategy demands 10–15% pullback
     first.
   Catalyst (negative for entry): IonQ excluded from $2B CHIPS Act
     grant package. Bullish for sector, neutral-to-bearish for IONQ
     relative valuation vs grantees.
   Re-eval trigger: pullback to $50–52 zone or fresh IONQ-specific
     positive catalyst.
```

**Combined Tier-1+Tier-2 deployment**: ~15% of equity (~$15,000)
across 5 starters keeps cash at ~85% — well above 20% floor.

**ClickUp notification**: **NOT sent**. No held-name shock (we hold
none), no halt, no fresh >5% gap on watchlist this morning, no macro
tape-bomb. IONQ's +12% and the quantum-grant news are yesterday's
events, already in the tape. NVDA earnings already digested. None
of this clears the urgent-catalyst bar.

**Open execution risk**: Plan is solid and unchanged in shape from
5/19. Execution gap is now four sessions. Whether the pre-market
run can be allowed to place orders today is governed by session
framing — this run is per the user prompt drafts-only.

---

### 2026-05-21 End of Day

**Account snapshot (Alpaca EOD)**:
- Equity: $100,000.00 (last equity $100,000.00)
- Cash: $100,000.00 | Buying power: $200,000.00
- Long market value: $0.00 | Open positions: none
- Filled orders today: none (zero trades executed)

**Performance**:
- Portfolio today: 0.00% (flat — still 100% cash)
- SPY today: +0.08% (close $741.88 vs prior close $741.31; intraday range
  $737.20–$744.84; source: Alpaca daily bars)
- Relative: −8 bps vs SPY today
- Three-session running tally: SPY −0.79% → +0.92% → +0.08%
  (≈ +0.21% cumulative); Dexter 0.00% across all three → roughly −21 bps
  cumulative drag vs SPY. The opportunity cost is small in absolute
  terms but the pattern of non-execution is now the story.

**Market Conditions**: SPY drifted modestly higher into the close
($741.88) on light volume after NVDA's Wed AMC print. The market
absorbed the print without a directional explosion in either direction
— suggesting the result and guide landed at or near the buy-side bar
rather than wildly above/below it. No CPI/PPI/NFP/FOMC today.

**Observations**:
- Third consecutive session with no execution. The QTUM/SPY/QQQ baseline
  starters drafted on 2026-05-19 have now been carried forward three
  sessions without action. This is the dominant operational issue —
  not the tape.
- The −21 bps cumulative drag is small, but the strategy explicitly
  benchmarks against SPY and the goal is to beat it. We cannot beat
  SPY from 100% cash; the math is decisive.
- NVDA post-print tape was constructive (broader market green +0.08%
  on the day, but the intraday high reached $744.84). Without the
  exact print numbers in this session's research budget, defer
  NVDA-specific sizing to the next pre-market with primary-source
  data.

**Next session (2026-05-22 pre-market)**:
- Execute the carried-forward QTUM + SPY + QQQ baseline starters (3%
  each, ~$3,000) at the open unless a macro tape-bomb creates a reason
  to delay. The non-execution streak is the active risk.
- Pull NVDA's actual Q1 FY27 print + guide. Re-grade NVDA/AMD sizing
  on the actual numbers (beat-and-raise = 3% NVDA starter; in-line =
  hold; guide-down = pass and reassess AMD).
- Re-check IONQ for the 10–15% pullback condition.
- Confirm Alpaca `/v2/clock` is_open before placing orders.

**ClickUp notification**: EOD ping sent per protocol.

---

### 2026-05-20 End of Day

**Account snapshot (Alpaca EOD)**:
- Equity: $100,000.00 (last equity $100,000.00)
- Cash: $100,000.00 | Buying power: $200,000.00
- Long market value: $0.00 | Open positions: none
- Filled orders today: none (zero trades executed)

**Performance**:
- Portfolio today: 0.00% (flat — still 100% cash)
- SPY today: +0.92% (intraday range $731.53–$737.65, open $734.78)
- Relative: −92 bps vs SPY today (opportunity cost of being un-deployed
  on a green tape)
- Two-session running tally: SPY −0.79% then +0.92% (≈+0.13% cumulative);
  Dexter 0.00% both days → roughly flat-of-flat vs the tape on the week
  but contributing zero to the strategy goal of beating SPY long-term.

**Market Conditions**: Broad market closed higher into NVDA's AMC print —
SPY +0.92%. Risk-on rebound off Tuesday's de-risking; no macro tape-bombs
(no CPI/PPI/NFP/FOMC today). All eyes on NVDA Q1 FY27 release after the
bell.

**Observations**:
- The drafted starter trades (QTUM/SPY/QQQ at 3% each) were NOT executed
  today. The account remains 100% cash. This is the second consecutive
  session where the pre-market plan was not actioned — flag for the next
  pre-market run.
- Being in cash on a +0.92% SPY day is a clean miss; the cumulative drag
  vs SPY since funding is now small (~13 bps) but the opportunity cost
  compounds the longer we stay un-deployed.
- NVDA reports AMC tonight. The 48-hour earnings guardrail still rules
  out an NVDA/AMD entry before the print. AMC tape reaction will set the
  tone for Thursday's open.

**Next session (2026-05-21 pre-market)**:
- Re-grade NVDA print: beat-and-raise = consider 3% NVDA starter; in-line
  = wait; guide-down = pass and reassess AMD.
- Execute the carried-forward QTUM + SPY + QQQ baseline starters (3%
  each, ~$3,000) unless the NVDA tape reaction creates a reason to
  delay.
- Re-check IONQ for the 10–15% pullback condition.
- Confirm Alpaca `/v2/clock` is_open behavior matches expected session
  framing before placing orders.

**ClickUp notification**: EOD ping sent per protocol.

---

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
