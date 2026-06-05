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

### 2026-06-05 End-of-Day

**Session:** EOD summary (Fri 6/5; market closing at 16:00 ET, snapshot
taken ~15:09 ET, 51 min before the bell).

**Account snapshot (Alpaca, GET /v2/account + /v2/positions + /v2/orders?status=filled):**
- Equity: $100,000.00 | Last equity: $100,000.00 | **Day P/L: 0.00%**
- Cash: $100,000.00 | Buying power: $400,000.00 (intraday 4x)
- Long market value: $0.00 | Short market value: $0.00
- Open positions: **none** | Filled orders today: **none**
- Status ACTIVE (PA39FINFSDLL); PDT false; day-trade count 0
- **15th consecutive all-cash session close.** The pre-market plan's
  fourth-defer branch (hot NFP → no execution) is now the realized
  outcome.

**Tape (Alpaca daily 1-day bars / latest trades, 6/5 in-progress at snapshot):**
| Symbol | 6/5 close (so far) | Δ vs 6/4 | Notes |
|---|---|---|---|
| SPY  | 738.42 | **−2.45%** | Low $738.33; latest trade $738.02 @ 15:08 ET. Round-tripped back to 5/12 inception print ($738.19). |
| QQQ  | 708.75 | **−4.29%** | Tech/AI risk-off in size. |
| NVDA | 205.96 | **−5.45%** | Sliced through the $215–225 starter zone; well below pre-mkt $212. |
| AMD  | 470.12 | **−9.40%** | $470–480 reset zone printed at the lower bound. |
| QTUM | 153.88 | **−7.58%** | Theme basket lower with the cohort. |
| IONQ | 56.63  | **−12.01%** | Closing the $50–52 trigger gap. |
| RGTI | 20.34  | **−13.74%** | Now well below the $23–25 zone. |
| PLTR | 134.64 | **−4.97%** | Below the $140–145 trigger. |
| NBIS | 223.51 | **−13.92%** | Approaching $210–215 settle. |
_All marks from Alpaca data-API snapshot; intraday at 15:08 ET. Final
4 PM consolidated print likely within ±0.3%._

**Today's portfolio return vs SPY:**
- Dexter: **0.00%** (flat — fully in cash all session)
- SPY: **−2.45%** (Alpaca daily bar so far; web color reported a
  smaller intraday level earlier in the session, but live Alpaca tape
  is the authoritative read at close-of-day)
- **Relative: +2.45% vs SPY** on the day
- **Inception (5/12 → 6/5): Dexter 0.00% vs SPY +0.03% → cumulative
  −0.03%.** The −2.43% inception gap carried in pre-market was
  effectively erased — SPY round-tripped to the starting print on a
  brutal red close.

**Market Conditions (EOD read):**
- May NFP came in **hot** at roughly double the 80–85K consensus
  (web reports — "doubling the consensus estimate" + upward prior
  revisions ~+93K combined). Hot labor print → bear-steepening
  pressure on the curve → multiple compression on long-duration tech.
- Chip cohort cratered: AVGO carryover from Thu's −15% guide miss
  compounded by a fresh AI-capex-deceleration narrative. NVDA
  −5.45%, AMD −9.40% (HSBC analyst flagging chip-price slide +
  AI spend slowdown).
- Quantum names lower with the theme: IONQ −12%, RGTI −14%,
  QTUM (ETF) −7.6%. Quantinuum-IPO rotation continues.
- Defensive rotation: consumer staples reportedly +2% on the day
  as flows fled high-beta AI.

**Trade activity (Alpaca /v2/orders?status=filled):**
- **None.** No orders placed, staged, or filled today. The pre-market
  decision tree's "hot NFP → defer + document fourth pass" branch
  was the realized outcome. The 6/5 pre-market plan now closes as
  the documented fourth defer.

**Decision retrospective:**
- The cash thesis got paid today — +245 bps vs SPY in a single session,
  closing the inception gap from −2.43% to −0.03% in one tape.
- The pre-market log was explicit that a hot print routed to defer.
  The bot followed the rule. **However**, the broader pattern of 15
  consecutive cash sessions is now reframed: the 6/4 EOD log called
  this an "execute or document" inflection; today's deferral was
  process-correct but the underlying multi-session drift remains the
  real risk to manage on Monday.
- The new mark-down across the watchlist is the best entry quality
  observed since inception. Monday's pre-market needs fresh entry
  zones (the prior $215–225 NVDA / $754–760 SPY zones are now stale).

**Urgent catalyst check (per strategy §7):**
- Earnings beat/miss on a **held** name? — No holdings. N/A.
- Halted stock we **own**? — No holdings. N/A.
- Macro shock? — Hot NFP was scheduled; no shock. SPY −2.45% is
  inside normal one-σ for the realized vol regime, but is the worst
  day in the inception window.
- Gap >5% on **held** watchlist? — No holdings; multiple watchlist
  names dropped >5% intraday but none are held.
→ **ClickUp end-of-day ping sent** (per the standing EOD requirement).

**Next session (Pre-market Mon 6/8):**
1. **Refresh all entry zones** — Friday's reset rendered prior
   triggers stale across the basket.
2. **CPI Tue 6/10 08:30 ET** — pre-print blackout 08:00–09:00.
3. **FOMC 6/16–17** — Fed speaker blackout begins 00:00 ET Sat 6/6.
4. **Weekend headlines** — Iran/Israel, China chips response to the
   AI-capex narrative, any Fed shadow-speak.
5. **Execution discipline** — fifth session of cash drag enters
   risk-of-drift territory even though today validated the call.
   Pre-market 6/8 needs a clear go/no-go before the bell.

---

### 2026-06-05 Pre-Market

**Session:** Pre-market (sync at 06:05 ET; market closed; next open
2026-06-05 09:30 ET per Alpaca `/v2/clock`).

**Account snapshot (Alpaca, GET /v2/account + /v2/positions + /v2/orders):**
- Equity: $100,000.00 | Last equity: $100,000.00 | Cash: $100,000.00
- Buying power: $400,000.00 (intraday 4x) | Reg-T: $200,000.00
- Long market value: $0.00 | Short market value: $0.00
- Open positions: **none** | Recent orders (last 20, all statuses): **none**
- Status ACTIVE (PA39FINFSDLL); PDT false; day-trade count 0
- **15th consecutive all-cash session.** The 6/4 intraday execute-or-document
  call was answered with a third passive defer; the basket was not staged.

**Tape (Alpaca IEX latest 1-min bars, 6/4 close 16:00 ET):**
| Symbol | 6/4 IEX print | Δ vs 6/3 | Entry zone | Status |
|---|---|---|---|---|
| SPY  | 756.16 | +0.36% | $754–760 | **In zone** |
| QQQ  | 738.60 | −0.32% | $740–746 | At/just-below zone (improved) |
| NVDA | 217.83 | +1.33% | $215–225 | **In zone** (pre-mkt ~$212 / −1.25%) |
| AMD  | 518.89 | **−2.85%** | $470–480 | Pulled in; pre-mkt $498–520 (−4%) — still above zone |
| QTUM | 166.49 | −0.75% | $158–160 | Just above zone |
| IONQ |  64.36 | **−5.92%** | $50–52 | Big leg lower; still above trigger |
| RGTI |  23.58 | −0.55% | $25–27 | Below zone (fresh entry) |
| PLTR | 141.68 | +0.11% | $140–145 | **In zone** |
| NBIS | 259.66 | +4.10% | $210–215 | Above zone — HOLD OFF |
| AVGO | 417.58 | (post-earn) | — | Not on watchlist; sector tone setter |
_Pre-market 6/5: Alpaca IEX quote latencies wide pre-04:00 ET; web color used._

**Market Conditions:**
- US session 6/4 was a chip-led wobble. AVGO **−15%** post-print on
  AI-revenue guidance ($16B Q3 vs ~$17.2B consensus) — the headline
  miss was the *rate of acceleration*, not the absolute number
  (~+200% YoY). Spillover hit AMD (−2.85% cash, −4% pre-mkt), MU,
  and clipped NVDA's pre-market today (~−1.25%). CRWD −9% on
  in-line earnings + 4-for-1 split.
- IONQ −5.92% on the day stands out — the strategy's "watchlist gap
  >5%" line. The move was a single regular-hours session leg, not
  an overnight gap, and IONQ is not held. **Below the ping threshold**
  but worth noting: P/S ~109 + Quantinuum listing rotation are
  driving the unwind. The $50–52 trigger zone is finally within
  reach of a second leg.
- US-Iran ceasefire holding but fragile; futures weak into NFP.
- Risk tone: Dow record Thu, SPX +0.41%, Nasdaq −0.09% — bifurcated.

**Today's calendar (Fri 6/5):**
- **08:30 ET — May NFP** (Bloomberg consensus 85K, Dow Jones 80K,
  Goldman 60K; prior 115K; U/R est 4.3% unch). **ADP came in hot at
  122K** on Wed 6/3 (vs 110K est) — sets up an upside surprise risk
  vs the dovish BLS consensus.
- **08:30 ET — Hourly Earnings, Unemployment Rate** (same release).
- **Strategy-mandated entry blackout: 08:00–09:00 ET.** No orders staged.
- **Fed speaker blackout begins 00:00 ET Sat 6/6** (FOMC 6/16–17,
  Warsh's first presser).
- Tue 6/10 08:30 ET — May CPI; pre-print blackout 08:00–09:00.

**Key News (watchlist, refreshed via web research this session):**

- **NVDA — $217.83 cash close (+1.33% on 6/4); ~$212 pre-mkt (−1.25%).**
  Carry-through from the AVGO sector reprice. Quarterly **$0.250 ex-div
  was 6/4** (immaterial). Other items: RTX Spark laptop chip launch
  (edge-AI offload); **Senate Banking hearing 6/11** (Warren invitation
  to Jensen re: China sales) — political headline risk into next week.
  Kumo AI ($400M pAI startup) bolt-on closed. Consensus Buy, avg PT
  ~$298 (+~37%). Tape **back in the $215–225 zone** at cash close;
  pre-market wobble keeps the entry quality.

- **AMD — $518.89 cash (−2.85%); pre-mkt $498–520 (−4%).** Sector
  collateral damage from AVGO; nothing company-specific. Strong Buy
  consensus (41 buys / 0 sells). Q1 print still the dominant
  fundamentals story. Pre-market lower bound is closer to but still
  ~4–5% above the $470–480 reset zone — **HOLD OFF** until either
  $470s prints or thesis catalyst.

- **IONQ — $64.36 (−5.92%).** Quantum-basket rotation; Quantinuum IPO
  (Honeywell majority, priced 6/3) continues to siphon. P/S still ~109.
  Q1 fundamentals unchanged (rev +755% YoY, FY26 guide $260–270M,
  RPO +554% to $470M, SkyWater merger approved). Excluded from $2B
  CHIPS Act LOI list. **HOLD OFF** vs $50–52 trigger — but the gap
  to the trigger has closed materially.

- **QTUM ETF — $166.49 (−0.75%).** Theme +53% YTD (Yahoo) / +69% YTD
  per prior week's basket-index report. Top weights still rotated
  (MU 3.35%, MediaTek 2.61%, ARM 2.47%). Just above $158–160 zone
  again. **Half-tranche $166–168** or wait for full retrace.

- **RGTI — $23.58 (−0.55%).** Sits below the $25–27 zone. Direct
  $100M CHIPS LOI + 108-qubit Cepheus-1-108Q now GA on QCS + Braket
  + Azure + qBraid; story unchanged from 6/4. **Fresh small-starter
  candidate** (3% cap, high vol).

- **PLTR — $141.68 (+0.11%).** Held the $140–145 retrace zone
  through a chop session — still **in trigger**. AI/data analytics
  + USG thesis intact.

- **SPY/QQQ — $756.16 / $738.60.** SPY held in zone; QQQ leaked back
  to the lower bound. Sell-side YE 2026 SPX targets 7,100–7,700.
  Pre-NFP futures weak.

- **NBIS — $259.66 (+4.10%).** Bounced; further above $210–215 settle
  zone. **HOLD OFF.**

- **AVGO (sector tone setter, not on watchlist):** −15% post Q2 FY26.
  Q3 AI-chip guide $16B vs ~$17.2B consensus. Q3 total rev guide
  $29.4B vs $28.53B. The *deceleration of the deceleration* is the
  read — not a thesis break for AI capex, but a multiple compressor
  for high-beta AI names through next week.

**Urgent catalyst check (per strategy §7):**
- Earnings beat/miss on a **held** name? — No holdings. N/A.
- Halted stock we **own**? — No holdings. N/A.
- Macro shock? — None overnight. NFP at 08:30 ET is *scheduled* and
  the strategy already gates it; consensus-vs-print is the risk we'll
  see at 08:30, not a pre-print shock.
- Gap >5% on watchlist? — IONQ −5.92% on 6/4 (regular session, not
  fresh overnight gap; not held). **Sub-ping under a strict reading
  of "fresh overnight gap on watchlist."**
→ **No ClickUp ping this session.**

**Trade ideas drafted for the 6/5 intraday session** (aggressive
mode per strategy.md: starter 5–10%, high conviction 15–25%,
single-name cap 25%, cash floor 5–10%, small-caps 3–7%; −8% hard
stop / 10% trailing on all). **No entries 08:00–09:00 ET (NFP
blackout).** Earliest action window: 09:30 open (post-print
digestion), preferably 09:45+ after MOO settles.

```
1) SPY — long starter (highest-conviction beta sleeve)
   Thesis: 15 sessions of cash drag is the dominant risk now. SPY is
           inside $754–760 and the NFP gate clears at 09:30. A
           5% half-starter at 09:45 + 3% add at 10:30 if green is
           the cleanest way to end the cash streak.
   Catalyst (today): NFP @ 08:30. In-line/dovish (60–85K, U/R 4.3%)
                     = bullish for SPY → execute. Hot print
                     (>110K) = yields up, defer or trim sizing.
   Entry: $754–760 (post-NFP) | Stop: −8% (~$695) | Target: trend-follow, 10% trail
   Size: 5–8% (~$5,000–8,000) | Confidence: 4/5

2) QQQ — long starter (tech/AI tilt sleeve)
   Thesis: AVGO sector compression has improved QQQ entry quality
           (~$738 vs $740–746 zone). Captures NVDA/AMD/MSFT capex
           tape without single-name reprice risk.
   Entry: $738–744 (post-NFP) | Stop: −8% (~$681) | Target: trend-follow, 10% trail
   Size: 6–7% (~$6,000–7,000) | Confidence: 4/5

3) NVDA — long starter (single-name AI core)
   Thesis: Pre-market $212 area is at/just-below the lower bound of
           the $215–225 zone after the AVGO-driven chip wobble. The
           AVGO read is a multiple compressor, not a thesis break.
   Caveats: 6/11 Senate Banking hearing (China-sales overhang);
            sector-wide AI-capex deceleration narrative is the new
            tape risk through next CPI / FOMC.
   Entry: $212–222 (scale in on the post-print) | Stop: −8% (~$195)
   Target: $240, then trail | Size: 5–6% (~$5,000–6,000) | Confidence: 4/5

4) QTUM — long, HALF starter
   Thesis: Theme intact; basket equal-weight caps single-name risk
           (vs IONQ's −5.92% reprice). Half-tranche at $166–168,
           reserve the second half for a $160 retrace.
   Entry: half ~$166–168 | Stop: −8% from blended | Target: open-ended
   Size: 2.5–5% (~$2,500–5,000) | Confidence: 3/5

5) RGTI — long small starter (small-cap quantum complement)
   Thesis: $100M CHIPS LOI + Cepheus-1-108Q GA across major clouds;
           tape below $25–27 zone improves entry. Highest single-name
           leverage on the quantum funding wave.
   Downside (explicit): pre-/early-revenue, dilution, 30–50% drawdown
                        risk; small size + tight stop.
   Entry: $23–25 | Stop: −8% (~$21.7) | Target: asymmetric, trim spikes
   Size: 3% (~$3,000 ≈ 125 sh) | Confidence: 2/5

6) PLTR — long small starter (still in trigger zone)
   Thesis: Holds $140–145 retrace zone through a chop session.
           Thesis (AI data analytics + USG primary) unchanged.
   Downside: high multiple; another 5–10% leg lower if NFP hot.
   Entry: $140–145 | Stop: −8% (~$130) | Target: $160 then trail
   Size: 3–4% (~$3,000–4,000) | Confidence: 3/5

7) AMD — HOLD OFF (still ~4–5% above $470–480 reset)
   Watch pre-market $498 print; deepen only if cash session prints
   $470s, otherwise wait. No company-specific thesis break.

8) IONQ — HOLD OFF (vs $50–52 trigger; closing the gap)
   Quantinuum rotation could push another leg lower — but P/S 109
   needs the trigger before sizing in. Patient.

9) NBIS — HOLD OFF (still ~21% above $210–215 zone after +4% bounce).
```

**Deployment math if all active ideas fire at midpoints**
(SPY 6.5% + QQQ 6.5% + NVDA 5.5% + QTUM 3.75% + RGTI 3% + PLTR 3.5%):
**~28.75% deployed / ~71% cash** — inside the 5–10% cash floor with
plenty of room to scale on confirmation.

Sector check: AI single-name (NVDA 5.5%) + quantum bucket (QTUM
3.75% + RGTI 3%) + AI/USG (PLTR 3.5%) ≈ 15.75% thematic;
SPY+QQQ ≈ 13% index beta. All under 25% single-name and ~40% sector caps.

**Decision pressure:** 15th consecutive cash session. The 6/4
log mandated either execute or document a hard reason for a
third defer. The bot did neither. Today's NFP gate is a *legitimate*
reason to wait until 09:30 — but post-print, the basket either
executes (in-line/dovish print) or earns a fourth-defer paper trail
(hot print + AVGO compression). The pattern of drift has to break.

**ClickUp notification:** **Not sent.** No held-name earnings, no
halts on holdings (no holdings), no overnight macro shock, no
fresh overnight gap >5% on the watchlist. IONQ's −5.92% intraday
on 6/4 is noted but does not meet the strict overnight-gap reading.

**Next session unblocker:**
- 08:30 ET — read NFP print + market reaction (yields, SPX futures,
  dollar). Decision tree above keyed off the 80–85K consensus.
- 09:30–09:45 ET — confirm 09:30 consolidated opens; stage SPY/QQQ
  half-starters at 09:45 if tape is digesting cleanly.
- Bias the day toward execution unless the print is a hot tail
  (>110K) or futures break −1%+ pre-bell.

---

### 2026-06-04 Pre-Market

**Session:** Pre-market (sync at 06:05 ET; market closed; next open
2026-06-04 09:30 ET per Alpaca `/v2/clock`).

**Account snapshot (Alpaca, GET /v2/account + /v2/positions + /v2/orders):**
- Equity: $100,000.00 | Last equity: $100,000.00 | Cash: $100,000.00
- Buying power: $400,000.00 (intraday 4x) | Reg-T: $200,000.00
- Long market value: $0.00 | Short market value: $0.00
- Open positions: **none** | Recent orders: **none**
- Status ACTIVE (PA39FINFSDLL); PDT false; day-trade count 0
- **14th consecutive all-cash session** (no orders Wed 6/3).
- Inception window (5/12 → 6/3): Dexter 0.00% vs SPY +2.37%
  ⇒ **−2.37% cumulative** (carried from 6/3 EOD; refresh after today's close).

**Tape (Alpaca IEX latest 1-min bars, ~16:00 ET print 6/3):**
| Symbol | 6/3 IEX print | Δ vs 6/2 close | Entry zone | Status |
|---|---|---|---|---|
| SPY  | 753.45 | −0.77% | $754–760 | At/just-below zone (in range) |
| QQQ  | 740.97 | −0.54% | $740–746 | In range |
| NVDA | 214.98 | −3.62% | $215–225 | At lower bound of zone |
| AMD  | 534.11 | +3.70% | $470–480 | **HOLD OFF — more extended** |
| QTUM | 167.75 | −0.20% | $158–160 | Above zone (half-tranche only) |
| IONQ |  68.41 | −2.73% | $50–52 | Above zone — HOLD OFF |
| RGTI |  23.71 | **−8.84%** | $25–27 | **Below zone — fresh entry** |
| PLTR | 141.52 | **−7.09%** | $140–145 | **In trigger zone — fresh entry** |
| NBIS | 249.42 | −4.91% | $210–215 | Above zone — HOLD OFF |
_IEX tape is a thin proxy for 4 PM consolidated print; treat to ±0.3%._

**Market Conditions:**
- US session 6/3 closed broadly red: SPY ~−0.52% (consolidated, per
  6/3 EOD log) / −0.77% on the IEX print used here, QQQ −0.54%, NVDA
  −3.62%, RGTI −8.84% (quantum pullback continued), PLTR −7.09%.
  AMD bucked the tape +3.70% extending the post-earnings rally.
- The narrowing of the inception SPY gap from −2.86% → −2.37% earlier
  this week was a *relative* win on a down tape, not an absolute one.
  Cash drag remains the structural problem after 14 sessions.

**Today's calendar (Thu 6/4):**
- **08:30 ET — Initial Jobless Claims** (consensus ~211K vs prior 215K).
- **08:30 ET — Q1 Nonfarm Productivity (final)** (consensus +0.8% vs +0.8%).
- Neither is FOMC/CPI/PPI/NFP grade — **no strategy-mandated entry
  blackout** around 08:30. Still, common sense: avoid stuffing orders in
  the 60 seconds around the 08:30 print.
- **Fri 6/5 08:30 ET — May NFP** ⇒ **pre-print blackout 08:00–09:00 ET**.
- Tue 6/10 CPI (pre-print blackout); 6/16–17 FOMC (Warsh's first
  presser); Fed speaker blackout begins midnight Sat 6/6.

**Key News (watchlist, refreshed via web research this session):**

- **NVDA — $214.98 (Alpaca IEX 6/3).** -3.11% press quote on 6/3.
  Today is the **ex-dividend date** for the $0.250 quarterly (small,
  not a sizing factor). **COMPUTEX 2026 concludes today** (US clock;
  Jensen keynote arc winding down — sell-the-news risk into the close).
  37-analyst consensus Buy; avg PT ~$298 (+39%). No near-term earnings
  binary (8/26 next). Tape now sitting **at the lower bound** of the
  $215–225 starter zone — the best entry in two weeks.

- **AMD — $534.11.** Continues to defy the tape; Q1 2026 print (May 6)
  remains the dominant narrative ($10.25B rev / $1.37 adj EPS / data
  center $5.8B +57% YoY and first-time >50% of mix). Sell-side action
  this week: **Barclays raised PT to $665 (6/1, street high)**, and a
  separate analyst upgraded to **Strong Buy 6/3** citing AI inference
  demand. Still extended vs the $470–480 reset zone — **HOLD OFF**.
  Next earnings ~Aug 4; no near-term print risk if entry trigger fires.

- **IONQ — $68.41.** Story unchanged: Q1 +755% YoY rev ($64.7M); FY26
  guide $260–270M; RPO $470M (+554%); SkyWater $1.8B merger approved
  by shareholders; 256-qubit chip-based system presold with demo
  targeted year-end. P/S ~109 — historically rich. Still excluded
  from the 5/21 $2B CHIPS Act LOI list (relative negative vs RGTI).
  **Quantinuum IPO** (Honeywell-majority) priced **6/3**, listing
  Nasdaq this week — likely rotation pressure on IONQ in the near term.
  **HOLD OFF** vs $50–52 trigger.

- **QTUM ETF — $167.75.** Theme momentum stayed intact (basket index
  +69% YTD pre this week's pullback per 24/7 Wall St.). Quantinuum
  listing is a basket-level halo; CHIPS Act LOIs auto-captured.
  Entry zone $158–160 still blown out, but the basket pulled back
  modestly from the +3.26% spike day. **Half-tranche today, or wait
  for full retrace.**

- **RGTI — $23.71 (−8.84% on 6/3).** Direct $100M CHIPS Act LOI
  recipient; 108-qubit Cepheus-1-108Q now GA on Rigetti QCS + Amazon
  Braket + Azure Quantum + qBraid. Stock now **below the prior $25–27
  starter zone**, in part on quantum-basket profit-taking (QBTS also
  hit). Fundamentals unchanged → entry quality has *improved*. Small
  starter still framed at 3% (high-vol cap).

- **SPY/QQQ — $753.45 / $740.97.** Both inside the prior 5/30 starter
  zones ($754–760 / $740–746); SPY a touch below the lower bound on
  IEX (consolidated probably in-range). VIX recently hit a 3-mo low;
  QQQ Aroon flashed bullish 6/1. Sell-side YE 2026 SPX targets bracket
  7,100 (BofA) – 7,700 (Citi).

- **PLTR — $141.52 (−7.09% on 6/3).** **In the $140–145 retrace
  trigger zone for the first time.** Lost 5-day momentum after the
  5/29 Dell-driven spike; 6/3 tape washed out the impatient longs.
  No fresh negative thesis line — **promotes from HOLD OFF to a fresh
  3–5% starter candidate**.

- **NBIS — $249.42.** Pulled back ~5% but still ~17% above the
  $210–215 settle zone. **HOLD OFF.**

- **Geopolitics:** Iran/Israel headlines remain an overhang; no
  fresh overnight escalation flagged in scans run this session. WTI
  still sensitive — if oil >$100 tape-bomb, revisit defensives /
  trim AI beta.

**Urgent catalyst check (per strategy §7):**
- Earnings beat/miss on a **held** name? — No holdings. N/A.
- Halted stock we **own**? — No holdings. N/A.
- Macro shock? — None pre-bell; jobless/productivity are
  routine prints, not shock-grade.
- Gap >5% on watchlist? — RGTI −8.84%, PLTR −7.09%, NBIS −4.91%
  on the **6/3 session** (yesterday). These are post-close prints
  already in the public log, not fresh overnight gaps. **No ping-grade
  shock.**
→ **No ClickUp ping this session.**

**Trade ideas drafted for the 6/4 intraday session** (aggressive mode
per strategy.md: starter 5–10%, high conviction 15–25%, single-name
cap 25%, cash floor 5–10%, small-caps 3–7%; −8% hard stop / 10%
trailing stop on all). **No entries 08:00–09:00 ET tomorrow (NFP
pre-print blackout); 8:30 ET today is *not* on the blackout list but
avoid stuffing orders within ±1 min of the print.**

```
1) SPY — long starter (highest-conviction beta sleeve)
   Thesis: End the 14-session cash drag with the lowest-binary trade
           on the desk. SPY held in the 754–760 starter zone
           through the 6/3 down day; IEX print 753.45 is at/just-below
           zone (≈consolidated ~$755.66 per 6/3 EOD log).
   Catalyst: Tomorrow's NFP is the next macro pivot; entering today
             ahead of NFP is the risk we accept for ending cash drag.
   Entry: ~$753–760 | Stop: −8% (~$695) | Target: trend-follow, 10% trail
   Sizing: conservative MOO 5% half-starter; full 8% if tape green at 10:00.
   Size: 5–8% (~$5,000–8,000) | Confidence: 4/5

2) QQQ — long starter (tech/AI tilt sleeve)
   Thesis: Captures NVDA/AMD/MSFT capex tape without single-name risk.
   Entry: ~$740–746 | Stop: −8% (~$681) | Target: trend-follow, 10% trail
   Size: 6–7% (~$6,000–7,000) | Confidence: 4/5

3) NVDA — long starter (single-name AI core)
   Thesis: -3.6% 6/3 pullback put $215 at the lower bound of the
           $215–225 entry zone — the best entry since the COMPUTEX
           gap-and-fade. Ex-div $0.25 today is immaterial. Vera/Rubin
           ramp + 8/26 print is the next narrative leg.
   Caveat: COMPUTEX concludes today — be alert for sell-the-news.
   Entry: $215–225 | Stop: −8% (~$197) | Target: $240, then trail
   Size: 5–6% (~$5,000–6,000) | Confidence: 4/5

4) QTUM — long, HALF starter (entry zone still blown out)
   Thesis: Theme intact; $167.75 is ~5% above the $158–160 zone.
           Take a 2.5% half-tranche; reserve the other half for a
           pullback to ~$160. Equal-weight basket caps single-name risk.
   Entry: half ~$166–168 | Stop: −8% from blended | Target: open-ended
   Size: 2.5–5% (~$2,500–5,000) | Confidence: 3/5

5) RGTI — long small starter (small-cap quantum complement)
   Thesis: $100M CHIPS Act LOI + Cepheus-1-108Q GA across major
           clouds + 6/3 −8.84% washout has improved entry quality —
           now BELOW the $25–27 zone. Highest single-name leverage on
           the quantum funding wave; complements QTUM basket.
   Downside (explicit): pre-/early-revenue, dilution, 30–50% drawdown
           risk; hence small size and aggressive stop discipline.
   Entry: ~$23–25 | Stop: −8% (~$21.8) | Target: asymmetric, trim spikes
   Size: 3% (~$3,000 ≈ 125 shares at $24) | Confidence: 2/5

6) PLTR — long small starter (NEW — promoted from HOLD OFF)
   Thesis: 6/3 −7.09% washout dropped PLTR into the $140–145 retrace
           trigger zone for the first time. Thesis (AI data analytics
           + USG primary use case) unchanged; momentum reset is the
           setup, not a thesis break.
   Downside (explicit): high-multiple name; another 5–10% leg lower
           is on the table if NFP disappoints.
   Entry: ~$140–145 | Stop: −8% (~$130) | Target: $160 then trail
   Size: 3–4% (~$3,000–4,000) | Confidence: 3/5

7) AMD — HOLD OFF (more extended at $534)
   Reason: +3.7% on 6/3 took the price further from the $470–480
           reset zone; insider sales / overbought flags still in the
           narrative. Re-engage only on pullback or fresh catalyst.

8) IONQ — HOLD OFF
   Reason: $68 vs $50–52 trigger; P/S ~109; left off $2B LOI;
           Quantinuum listing rotation risk this week.

9) NBIS — HOLD OFF
   Reason: $249 vs $210–215; still ~17% above settle target.
```

**Deployment math if all active ideas fire at midpoints**
(SPY 6.5% + QQQ 6.5% + NVDA 5.5% + QTUM 2.5–5% + RGTI 3% + PLTR 3.5%):
**~27.5–30% deployed / ~70–72.5% cash** — well inside the 5–10% cash
floor with room to scale.

Sector check: semis bucket (NVDA 5.5%) + quantum bucket (QTUM 2.5–5%
+ RGTI 3%) ≈ 11–13.5%; +PLTR 3.5% = ~14.5–17% in "AI / thematic"
single-name + small-cap; SPY+QQQ ≈ 13% in index beta. All under the
25% single-name and ~40% sector caps with comfort.

**Decision pressure:** This is the 14th cash session. The 6/3 EOD log
flagged "no new structural reason to defer further" at $755.66; the
6/4 pre-print holds the same setup with the addition of NVDA at the
zone bottom and PLTR finally triggering. Intraday session should
either execute the basket or document a hard reason for one more
defer — not a passive third one.

**ClickUp notification:** **Not sent.** No held-name earnings, no
halts on holdings (no holdings), no macro shock, no fresh overnight
gap >5% on the watchlist. Routine pre-market.

**Next session unblocker:**
- Intraday 6/4 09:30–16:00 ET: confirm consolidated open prints,
  re-check the entry zones at 09:45 (post-MOO settle), and either
  stage the basket above or commit to a documented defer.
- Tomorrow's NFP is the next mandated blackout.

---

### 2026-06-03 End-of-Day

**Session:** Post-close summary (sync after 16:00 ET close).

**Account snapshot (Alpaca, GET /v2/account + /v2/positions + /v2/orders?status=filled)**:
- Equity: $100,000.00 | Last equity: $100,000.00 | Cash: $100,000.00
- Buying power: $200,000.00 | Long market value: $0.00
- Open positions: **none** | Filled orders today: **none**
- Status ACTIVE (PA39FINFSDLL); PDT false; day-trade count 0.

**Performance:**
- Dexter today: **0.00%** (flat, all cash, 13th consecutive cash close)
- SPY today: **−0.52%** (~$759.57 prior close → ~$755.66 today close, per web)
- Today vs SPY: **+0.52 pp** (cash beat the down tape)
- Since 5/12 inception: Dexter 0.00% vs SPY **+2.37%** (738.19 → 755.66)
  ⇒ **−2.37% cumulative** (gap narrowed ~49 bps from −2.86% Tuesday).

**Market Conditions:**
- SPY closed modestly red (−0.52%) — first material down day for the
  index since the recent ATH run; trading range ~$755.41–$760.29 per
  web data. No tape-bomb, no halts; a textbook digestion day after
  the 6/2 ATH close.
- Today's tier-1 print (ISM Services PMI for May, 10:00 ET) was the
  scheduled catalyst; intraday weakness suggests the market read it
  on the softer side or de-risked into the print. We did not capture
  the print value directly in this sync.
- Geopolitics: Iran/Israel headlines remained an overhang into the
  session per the pre-market log; gold/silver had a safe-haven bid
  overnight (gold +1.27%, silver +1.84%).
- Forward calendar unchanged: Fri 6/5 NFP, Tue 6/10 CPI, 6/16–17 FOMC.

**Trades today:** **None.** The pre-market drafted starter basket
(SPY 5–8% / QQQ 6–7% / NVDA 5–6% / QTUM 2.5–5% / RGTI 3%) was **not
staged** during the intraday session — no orders placed, no fills.
13th consecutive cash close.

**Key observations:**
- **Cash drag arithmetic flipped today.** A down SPY (−0.52%) means
  staying flat *gained* ~52 bps of relative performance vs the
  benchmark on the day. Inception gap narrowed from −2.86% to −2.37%
  — the first time the gap has compressed materially in two weeks.
- This is a one-day reprieve, not a vindication: the strategy is
  long-only growth/index, so a multi-day SPY drawdown would help our
  *relative* P&L while still missing the absolute-return mandate.
- The pre-market entry zones (SPY $754–760, QQQ $740–746) **remain
  valid** at the EOD print — SPY $755.66 is still in-zone, slightly
  better than this morning. No new structural reason to defer further.
- AMD / IONQ / PLTR / NBIS HOLD-OFF prices unchanged (no new catalysts
  observed this sync; intraday tape not pulled for individual names).

**Watchlist updates:** No fresh price marks this sync (intraday Alpaca
1Day bars not pulled). Tape will be re-marked at 6/4 pre-market.

**ClickUp notification:** **Sent.** Standard EOD ping per protocol
(daily summary line, not an urgent-catalyst alert).

**Next session unblocker:**
- Thu 6/4 pre-market: re-mark watchlist on consolidated 1Day bars,
  confirm whether SPY/QQQ entry zones are still intact, and frame the
  execute/defer decision again. 14 cash sessions is the new
  baseline if Thursday closes flat without orders.

---

### 2026-06-03 Pre-Market

**Session:** Pre-market (sync at 06:02 ET; market closed; next open 09:30 ET).

**Account snapshot (Alpaca, GET /v2/account + /v2/positions + /v2/clock)**:
- Equity: $100,000.00 | Last equity: $100,000.00 | Cash: $100,000.00
- Buying power: $200,000.00 | Long market value: $0.00
- Open positions: **none** | Working orders: not pulled this run
- Status ACTIVE (PA39FINFSDLL); PDT false; day-trade count 0
- Clock: `is_open: false`; next open **2026-06-03 09:30 ET**, next close 16:00 ET
- **13th consecutive all-cash session.** Since 5/12 inception:
  Dexter 0.00% vs SPY +2.86% ⇒ **−2.86% cumulative**.

**Tape (carried forward from 6/2 Alpaca IEX 1Day bars; pre-market quotes
not pulled — web research used for sentiment color only):**
| Symbol | 6/2 Close | 1-day Δ | Notes |
|---|---|---|---|
| SPY  | 759.28 | +0.11% | ATH close; futures marginally lower overnight on Iran headlines |
| QQQ  | 745.02 | +0.33% | ATH close |
| NVDA | 223.06 | −0.61% | Gapped ATH $232 then faded |
| AMD  | 515.04 | +0.98% | +130% YTD; RSI overbought |
| QTUM | 168.09 | **+3.26%** | Quantum theme leader; entry zone blown out |
| IONQ |  70.33 | +1.51% | Continues grinding higher; P/S ~109 |
| RGTI |  26.02 | +1.50% | Reclaimed 5/28 spike high |
| PLTR | 152.32 | **−5.18%** | Gave back Fri Dell pop |
| NBIS | 262.30 | −0.83% | Still extending |

**Market Conditions:**
- **Today's tier-1 print: ISM Services PMI (May) at 10:00 ET.** April
  was 53.6 (modest pullback from 54.0); new orders weakened; prices
  index 70.7 (multi-year high — stagflation watch); employment in
  contraction 2nd month. Polymarket-style implied distribution is
  diffuse (~47% across mid-40s to mid-50s) → real two-sided risk.
  Strategy blackout: **no new entries 9:30–10:30 ET**.
- **Overnight geopolitical re-escalation:**
  - Senior Iranian military officer said return to hostilities with
    the US "appears inevitable"; Iran still considering the latest US
    draft, no response yet.
  - Israel/Hezbollah clashed overnight despite Trump reportedly
    securing a halt after a phone call with Netanyahu.
  - Safe-haven bid: gold futures +1.27% to $4,563.70/oz, silver +1.84%
    to $76.64/oz.
- **Futures:** index futures marginally lower per overnight reports;
  no tape-bomb-level gap.
- **Forward calendar:**
  - **Wed 6/3 10:00 ET:** ISM Services PMI (May) — blackout 9:30–10:30
  - **Fri 6/5 08:30 ET:** May NFP — pre-print blackout
  - **Tue 6/10 08:30 ET:** May CPI — pre-print blackout
  - **Tue/Wed 6/16–17:** FOMC (Warsh's first presser per prior memo).
    Fed speaker blackout begins midnight Sat 6/6.

**Key News (watchlist, refreshed via web research):**
- **NVDA — ~$222 area, market cap $5.48T.** 61 analyst average PT
  $296.81 (Strong Buy; +33% from current). COMPUTEX tailwind
  continues; Vera Rubin custom CPU for agentic AI; commitment to
  return >50% of FCF to shareholders. FY26 revenue $215.94B (+65% y/y).
  Entry embargo cleared (next earnings 8/26). $215–225 entry in range.
- **AMD — ~$510 area, +130% YTD.** Barclays raised PT to $665 on 6/1
  (street high; ~30% upside from $510). Q1 2026: $10.25B (+38% y/y);
  data center $5.8B (+57%); CEO Su raised TAM forecast to >$120B
  growing 35%+/yr by 2030. **Caveats flagged in news flow: RSI
  overbought, insider sales.** **HOLD OFF — extended** vs $470–480 zone.
- **IONQ — ~$70 area.** Q1 rev $64.7M (+755% y/y); FY26 guide $260–270M;
  RPO $470M (+554% y/y); $39M Space Development Agency contract;
  Missile Defense Agency SHIELD IDIQ vehicle selected; **SkyWater
  $1.8B merger shareholder-approved**. Cash $3.1B — longest runway in
  the quantum cohort. **But P/S ratio ~109** flagged as "historically
  expensive at early commercialization." Still excluded from $2B LOI
  list — relative negative vs RGTI/QBTS. **HOLD OFF** vs $50–52 trigger.
- **QTUM ETF — $168.09 (6/2).** Recent holdings as of 6/2 include
  D-Wave, Quantum Computing, Rigetti, IonQ. 6-mo net flows $1.08B;
  1-yr $2.34B. Theme still hot; **entry zone $158–160 blown out.**
  Wait for retrace to ~$160 or open a half-tranche if conviction high.
- **SPY/QQQ — fresh ATH closes 6/2; mild risk-off pre-market on Iran
  headlines but no tape-bomb.** SPY ~$759, QQQ ~$745 both still inside
  the 5/30 starter zones ($754–760 / $740–746). Retail SPY sentiment
  'bullish', QQQ 'neutral'.
- **PLTR — $152.32 (−5.18% on 6/2).** Lost 5-day momentum; trigger at
  $140–145 retrace zone unchanged.
- **NBIS — $262.30.** Still extending; wait for $210–215 settle.
- **RGTI — $26.02.** Direct ~$100M grantee; quantum-theme bid intact.
  3% starter still in $25–27 range.

**Pre-market movers (broad-tape color, not actionable for our names):**
- ABVX −29% (Phase 3 cancer-cases safety overhang).
- JZ −43% (despite AI-partnership announcement).
- DXST +113% (chairman 90.5% voting-stake disclosure).
- SBFM +37% (unusual volume).
None on our watchlist; flagged only as broad-tape biotech/micro-cap
volatility signal.

**Trades:** None — pre-market run is draft-only by protocol.

**Trade ideas drafted for the 6/3 session** (aggressive mode per
strategy.md: starter 5–10%, high-conviction 15–25%, single-name cap
25%, cash floor 5–10%, small-caps 3–7%; −8% hard stop / 10% trailing
stop on all). **All entries must respect the 9:30–10:30 ET ISM
Services blackout — stage MOO or wait until ≥10:30.**

```
1) SPY — long starter (lowest binary risk, highest conviction)
   Thesis: Stop the 13-session cash drag. SPY closed at ATH 6/2; only
           mild pre-market dip on Iran headlines. AI/macro tape
           constructive; ISM Services is two-sided risk but not a
           known hot/cold tilt. Index = no single-name binary.
   Catalyst: AI broad rally intact; entry levels still in 5/30 zone.
   Entry: ~$754–760 | Stop: −8% (~$697) | Target: trend-follow, 10% trail
   Sizing options:
     - Conservative: MOO 5% half-starter; add 5% post-ISM if tape green
     - Aggressive:  MOO 8% full starter
   Size: 5–8% (~$5,000–8,000) | Confidence: 4/5

2) QQQ — long starter (tech/AI tilt)
   Thesis: Captures NVDA/AMD/MSFT capex without single-name risk.
           Same ISM Services blackout applies.
   Entry: ~$740–746 | Stop: −8% (~$680) | Target: trend-follow, 10% trail
   Size: 6–7% (~$6,000–7,000) | Confidence: 4/5

3) NVDA — long starter (high-quality AI core)
   Thesis: Vera CPU + ~$200B CPU TAM + 61-analyst PT $296.81. 6/2's
           gap-and-fade gave a wider $215–225 entry zone vs the $208–214
           we had on 5/29. No near-term earnings binary (8/26 next).
   Catalyst: COMPUTEX/Vera ramp; AI capex cycle.
   Entry: $215–225 (in range at $223 close) | Stop: −8% (~$205)
   Target: $240, then trail | Size: 5–6% (~$5,000–6,000)
   Confidence: 4/5

4) QTUM — long, HALF starter only (entry zone blown out)
   Thesis: Theme still hot but $168.09 close is ~5% above the prior
           $158–160 zone; do not chase the full 5%. Open 2.5%
           half-tranche; reserve the other half for a 3–5% pullback
           toward ~$160. Equal-weight basket caps single-name risk.
   Entry: half ~$166–168 OR wait full size on retrace to ~$160
   Stop: −8% from blended | Target: open-ended basket hold, trim 50% at +30%
   Size: 2.5–5% (~$2,500–5,000) | Confidence: 3/5

5) RGTI — long small starter (small-cap quantum complement)
   Thesis: Direct ~$100M grantee + federal equity stake; complements
           QTUM basket; 5/30 entry zone $24.50–26 still intact at $26.02
           close. Highest single-name leverage on the $2B funding wave.
   Downside (explicit): pre-/early-revenue, dilution, 30–50% draw-down
           potential; hence small size.
   Entry: ~$25–27 | Stop: −8% (~$23.4) | Target: asymmetric, trim spikes
   Size: 3% (~$3,000 ≈ 115 shares) | Confidence: 2/5

6) AMD — HOLD OFF (do not chase)
   Reason: +130% YTD; RSI overbought; insider sales flagged; ~58x fwd
           rich. Wait for $470–480 pullback (or a fresh AMD-specific
           catalyst).

7) IONQ — HOLD OFF
   Reason: $70 vs $50–52 trigger; P/S ~109 historically rich; left off
           $2B LOI list. SkyWater merger approval is incremental, not
           a fresh trigger. Wait for pullback or LOI add-on.

8) PLTR — HOLD OFF
   Reason: $152.32 vs $140–145 retrace trigger. Lost momentum after
           5/29 spike; let it base.

9) NBIS — HOLD OFF
   Reason: Still ~$262 vs $210–215 settle target; volatile.
```

**If all five active ideas fire at midpoints** (SPY 6.5% / QQQ 6.5% /
NVDA 5.5% / QTUM 2.5–5% / RGTI 3%): **~24–27% deployed / ~73–76% cash**
— well inside the 5–10% cash floor with room to scale. Semis (NVDA 5.5%)
+ quantum (QTUM 2.5–5% + RGTI 3%) = ~11–13.5%, far under the 25%
single-name and ~40% sector caps.

**ClickUp notification: NOT sent.** Bar-by-bar check vs strategy.md
urgent-catalyst criteria:
- *Earnings beat/miss on a held name*: we hold none.
- *Halted stock we own*: we own none.
- *Macro shock*: ISM Services is a *scheduled* tier-2 print, not a
  shock. Iran/Israel headlines are concerning but Tuesday's tape was
  only −0.14% to −0.25% — not a tape-bomb. Gold +1.27% notable but
  short of "shock."
- *Gap >5% on watchlist*: no watchlist name has a fresh overnight gap
  >5%. The 6/2 closes are already in tape.
None clears the bar.

**Key thesis notes / lesson**:
- 13 sessions in cash. The opportunity cost is now the dominant P&L
  item on the book (−2.86 pp vs SPY since 5/12). The 5/30 drafts had
  already passed — and QTUM specifically blew out the entry zone
  (5/30 plan: $158–160 → 6/2 close $168 = ~5% missed).
- SPY/QQQ index zones are **still** intact at 6/3 pre-market prices.
  That means today is the cheapest opportunity to convert the lowest-
  binary-risk drafts into actual orders before the cumulative drag
  grows further.
- The right execution path today is: stage SPY/QQQ MOO (or wait
  post-10:00 ET ISM print if cautious), then add NVDA and the
  small-cap quantum complements once the print clears. AMD/IONQ
  remain HOLD OFF on price.

**Next session unblocker:**
- Convert at least SPY/QQQ starters into live orders during the
  intraday session, respecting the 10:00 ET ISM blackout. Re-mark
  watchlist on Alpaca consolidated 1Day bars at EOD and write the
  EOD log.

---

### 2026-06-02 End-of-Day

**Session:** Post-close summary (sync at 15:07 ET, ~53 min before 16:00 ET close).

**Account snapshot (Alpaca, GET /v2/account + /v2/positions + /v2/orders)**:
- Equity: $100,000.00 | Last equity: $100,000.00 | Cash: $100,000.00
- Buying power: $200,000.00 | Long market value: $0.00
- Open positions: **none** | Filled orders today: **none**
- Status ACTIVE (PA39FINFSDLL); PDT false; day-trade count 0.

**Performance:**
- Dexter today: **+0.00%** (flat, all cash)
- SPY today (near-close): **+0.11%** (758.44 → 759.28)
- Today vs SPY: **−0.11 pp**
- Since 5/12 inception: Dexter 0.00% vs SPY **+2.86%** (738.19 → 759.28)
  ⇒ **−2.86% cumulative** (gap widened ~40 bps over 6/1–6/2 sessions).

**Tape (Alpaca IEX 1Day bars; 6/2 near close vs 6/1)**:
| Symbol | 6/2 Last | 1-day Δ | Intraday range | Note |
|---|---|---|---|---|
| SPY  | 759.28 | +0.11% | 756.75–760.40 | Fresh ATH close |
| QQQ  | 745.02 | +0.33% | 739.25–746.21 | Fresh ATH close |
| QTUM | 168.09 | **+3.26%** | 165.32–168.59 | Quantum-theme leader; AUM trajectory + RGTI strength |
| NVDA | 223.06 | −0.61% | 221.91–232.28 | Gapped to ATH $232 then faded; wider range than usual |
| AMD  | 515.04 | +0.98% | 501.46–519.90 | Held the $515 level |
| IONQ |  70.33 | +1.51% | 69.11–72.63 | Continues to grind higher |
| RGTI |  26.02 | +1.50% | 25.48–27.22 | Reclaimed Wed 5/27 spike high |
| PLTR | 152.32 | **−5.18%** | 149.80–159.43 | Gave back most of Fri 5/29 Dell-driven pop |
| NBIS | 262.30 | −0.83% | 260.66–278.79 | Still extending range; ~$18 peak-to-trough |

**Market Conditions:**
- Quiet drift higher into the close on light volume. SPY 6/2 volume
  ~784k shares vs ~1.45M on 6/1 — typical post-Monday-ISM digestion.
- Quantum theme had the cleanest tape: QTUM +3.26%, RGTI +1.50%, IONQ
  +1.51%. The 5/21 $2B Commerce LOI tailwind continues to bid the basket.
- AI single-name dispersion: NVDA gapped to a fresh ATH $232 on
  continued Vera CPU enthusiasm then faded to $223; PLTR gave back
  the Dell-driven pop, closing back below $156. Suggests rotation
  out of last week's leaders rather than broad de-risking.
- No tier-1 macro print today; ISM Mfg landed yesterday in line.
  Wed 6/3 ISM Services next; Fri 6/5 May NFP.

**Trades today:** **None.** Account remains 100% cash for the 12th
consecutive session. Drafted 5/30 starter ideas (SPY 8% / QQQ 7% /
QTUM 5% / NVDA 6% / RGTI 3%) were **not executed** at the 6/1 open
as planned. No EOD trades placed.

**Key observations:**
- The cost of cash drag has now reached **−2.86 pp** vs SPY since
  5/12 inception. The decision to defer execution at 6/1 was
  unfortunate for QTUM specifically (entry zone $158–160 → $168
  in two sessions = ~5% missed).
- SPY/QQQ index entry zone has **not** materially moved (SPY $759.28
  is still within the $754–760 starter range), so the index portion
  of the drafted plan is still actionable at fresh prices.
- NVDA's gap-and-fade today widened the entry zone — $215–223 is now
  available (vs the $208–214 zone last week). Confidence on a clean
  entry has improved.
- PLTR's −5.18% confirms last Friday's spike was not the start of a
  trend; the $140–145 retrace target remains the right trigger.

**Next session unblocker:**
- Wed 6/3 pre-market: re-pull movers, recalibrate the drafted starter
  basket at fresh prices, and place a decision in front of the user
  (execute / hold / modify). Continued cash drag without a documented
  reason is now the largest single P&L item on the book.

---

### 2026-05-30 Pre-Market (weekend prep for Mon 2026-06-01 open)

**Account snapshot (Alpaca, GET /v2/account + /v2/positions + /v2/orders + /v2/clock)**:
- Equity: $100,000.00 | Last equity: $100,000.00 | Cash: $100,000.00
- Buying power: $200,000.00 | Long market value: $0.00
- Open positions: none | Open orders: none
- Status ACTIVE (PA39FINFSDLL); PDT false; day-trade count 0.
- Clock: `is_open: false` (Sat 5/30 06:03 ET) → next open **Mon 2026-06-01 09:30 ET**.
- **10th consecutive all-cash session.** Since inception (5/12): Dexter 0.00%
  vs SPY **+2.46%** (738.19 → 756.34) ⇒ **−2.46% cumulative**.

**Tape (Alpaca IEX 1Day bars; 5/29 Fri close vs 5/28)**:
| Symbol | 5/29 Close | 1-day Δ | Intraday range | Note |
|---|---|---|---|---|
| SPY  | 756.34 | +0.22% | 754.72–758.06 | Fresh ATH close |
| QQQ  | 738.21 | +0.35% | 735.29–741.54 | Fresh ATH close |
| QTUM | 159.81 | +0.47% | 157.79–160.69 | Held gains |
| NVDA | 211.155 | **−1.45%** | 211.14–217.80 | Mild post-print digestion → better entry |
| AMD  | 516.265 | −0.35% | 503.52–521.69 | Still in chase zone |
| IONQ |  72.07 | **+2.75%** | 66.84–72.17 | Continues extended |
| RGTI |  25.535 | **−5.51%** | 24.44–26.53 | Gave back Wed spike |
| PLTR | 156.58 | **+9.22%** | 145.85–157.75 | Biggest 1-day gain since Apr-25 |
| NBIS | 231.10 | +2.10% | **210.59–233.40** | Whippy ~$22 range |

**Market Conditions**:
- **Today is Sat 5/30** — markets closed. This is weekend prep for the
  **Mon 6/1 cash open**.
- **5/29 close was a fresh all-time-high** in SPY/QQQ on an AI-led broad
  rally, with reports of progress toward a US–Iran framework adding to the
  risk-on tone. No tier-1 macro Friday (NY Fed second-tier prints only).
- **Forward calendar (next 3 weeks):**
  - Mon 6/1: ISM Manufacturing PMI (May)
  - Wed 6/3: ISM Services PMI (May)
  - **Fri 6/5: May NFP (08:30 ET)** — pre-print blackout per strategy
  - **Tue 6/10: May CPI** — pre-print blackout
  - PPI: typically Wed/Thu of CPI week
  - **Tue–Wed 6/16–17: FOMC** (Chair Warsh's first meeting/presser) —
    blackout 30 min before each statement/presser
- Pre-Memorial-Day-+1 week macro tone: April PCE landed benign 5/28;
  core PCE +3.3% y/y; Fed Gov Miran has flagged that being too tight risks
  the labor market — dovish-leaning at the margin.

**Key News (watchlist)**:
- **PLTR — +9.22% on 5/29 to $156.58**, biggest 1-day move since Apr-25.
  Trigger: **Dell** fiscal Q1-27 print (rev $43.84B +88% y/y; AI-optimized
  server rev **$16.13B, +757% y/y**) combined with **Snowflake** beat and
  reports the Trump admin is weighing direct funding for US drone makers
  (Pentagon/Office of Strategic Capital). PLTR has an on-prem AI-OS
  partnership with Dell aimed at healthcare/defense — fundamentals reinforced
  but the entry zone is now blown out. Re-rate trigger to $140–145.
- **NBIS — $208 → $231 over 5/28–5/29** on Situational Awareness LP
  disclosure of a **5.6% stake** (~12M Class A shares). Q1 fundamentals
  remain strong (rev $399M +685% y/y, Cloud AI +841%); Citi PT $287
  maintained. Very volatile (Fri intraday range $210.59–$233.40 ≈ ~10% peak-
  to-trough). Let it settle.
- **NVDA — $211.16 on 5/29** (−1.45%). Q1 FY27 print (5/20) was a clean
  beat-and-raise (rev $81.6B +85% y/y, EPS $1.87 vs $1.76; data center
  $39.1B +69%; Blackwell "off the charts"). Vera CPU launch adds a ~$200B
  data-center CPU TAM and ~$20B CPU rev guided this FY. Next earnings
  **8/26** — no near-term binary; entry embargo cleared. Friday's small
  pullback brings the entry zone $208–214 squarely in range.
- **AMD — $516 on 5/29.** Q1 rev $10.25B (+38% y/y), data-center
  $5.8B (+57%); MI400/MI455X + OpenAI 6GW + Meta deals; **$10B Taiwan
  packaging investment announced 5/21**. Ran +45.6% during May, ATH 5/22.
  ~58x fwd is rich; entry still in chase territory vs the $470–480 zone.
- **IONQ — $72.07 on 5/29** (+2.75%). Q1 rev $64.7M +755% y/y; FY26
  guide $260–270M; first 256-qubit sale; SkyWater deal cleared shareholder
  vote. **Still excluded from Commerce's $2B LOI list** — relative negative
  vs RGTI/QBTS. Trigger $50–52 not met.
- **QTUM — $159.81 on 5/29** (+0.47%). ETF AUM crossed **$5B** on 5/26
  alongside the **$2.013B Trump-admin federal quantum push** (Commerce LOIs
  to IBM $1B, GlobalFoundries $375M, RGTI ~$100M, QBTS ~$100M, INFQ ~$100M,
  PsiQuantum $100M, Diraq $38M, +2). Basket auto-captures the grantees;
  cleanest sector expression. YTD +84% per third-party data, +57pp vs SPX.
- **RGTI — $25.535 on 5/29** (−5.51%). Gave back ~half of Wed's $24.6 → $27
  spike. Direct ~$100M grantee + federal minority equity stake. Higher-beta
  single-name quantum expression vs QTUM basket.
- **Indices: SPY $756.34 / QQQ $738.21 — fresh ATH closes** on AI rally +
  US–Iran de-escalation optimism. 2026 SPX targets BofA 7,100 / Citi 7,700.

**Trades**: None — markets closed (Sat) and draft-only by instruction.

**Trade ideas drafted for Mon 6/1 open** (aggressive mode: starter 5–10%,
high-conviction 15–25%, single-name cap 25%, cash floor 5–10%, small-caps
3–7%; −8% hard stop / 10% trailing stop on all):

```
1) SPY  — long starter (lowest binary risk, biggest conviction)
   Thesis: stop the 10-session cash drag; ATH close on benign macro +
           AI tape; ISM Mfg lands Mon 10:00 ET so stage entry pre-print
           or wait until after if the print is hot.
   Catalyst: AI broad rally + Iran-deal optimism + benign PCE behind us.
   Entry: ~$754–757 | Stop: −8% (~$696) | Target: trend-follow, 10% trail
   Size: 8% (~$8,000 ≈ 10 shares) | Confidence: 4/5

2) QQQ  — long starter (tech/AI tilt)
   Thesis: AI/tech leadership at ATH; captures NVDA/MSFT/AMD capex
           without single-name binary risk; Dell+Snowflake prints
           reinforce the AI-infra demand picture.
   Entry: ~$735–740 | Stop: −8% (~$679) | Target: trend-follow, 10% trail
   Size: 7% (~$7,000 ≈ 9 shares) | Confidence: 4/5

3) QTUM — long, two tranches (cleanest quantum expression)
   Thesis: basket on the $2B federal funding wave; $5B AUM milestone =
           strong inflows. Diversification dampens single-name risk vs
           IONQ/RGTI.
   Entry: half ~$158–160 (MOO Mon), half on 2–3% retrace (~$155)
   Stop: −8% from blended (~$147) | Target: +20–30%, trim 50% at +30%
   Size: 5% (~$5,000 ≈ 31 shares total) | Confidence: 3/5

4) NVDA — long starter (high-quality AI core)
   Thesis: beat+raise digested; Vera CPU adds ~$200B TAM / ~$20B CPU rev
           this FY; ~25x fwd reasonable; 8/26 earnings far away.
           Friday's −1.45% gives a cleaner $211 entry.
   Entry: $208–214 | Stop: −8% (~$194) | Target: $240, 10% trail
   Size: 6% (~$6,000 ≈ 28 shares) | Confidence: 4/5

5) RGTI — long small starter (small-cap quantum complement)
   Thesis: direct ~$100M grantee + federal equity stake — highest-leverage
           single name on the funding catalyst; Fri pullback to $25.5
           after Wed spike = OK entry; complements QTUM basket.
   Downside (explicit): pre-/early-revenue, high burn, dilution risk,
           extreme volatility — can draw down 30–50%; hence small size.
   Entry: ~$24.50–26 | Stop: −8% hard (~$23.4) | Target: asymmetric,
   trim into spikes | Size: 3% (~$3,000 ≈ 117 shares) | Confidence: 2/5
```

If all five fire at midpoints: ~29% deployed / ~71% cash (well inside the
5–10% floor with room to scale); semis (NVDA 6%) + quantum (QTUM 5% +
RGTI 3%) = 14%, under the 25% single-name and 40% sector ceilings.

**HOLD-OFF / watch (not ideas this run)**:
- **AMD** — do NOT chase $516 (~58x fwd); wait $470–480 pullback.
- **IONQ** — HOLD OFF; $72 vs $50–52 trigger; left off $2B LOI list.
- **PLTR** — entry blown out by Fri's +9.22% rip; **RAISE trigger to
  $140–145** pullback (was $130–135). Strong fundamentals + Dell/SNOW
  tailwind, but don't chase $157.
- **NBIS** — let the +5.6%-stake spike settle; revisit ~$210–215.
- **KTOS / SOFI** — research-only; dedicated deep dive still owed
  (KTOS got a small drone-funding tailwind 5/29 worth tracking).

**Thesis Notes / Lesson**:
- 10th straight all-cash session; SPY drift to a new ATH on Friday widened
  the since-inception gap to **−2.46%**. Two of the prior watch names that
  were "ready" pre-Friday (PLTR, NBIS) ran away from the entry zone on
  Friday's AI rip — concrete cost of execution lag. The lowest-binary-risk
  ideas (SPY/QQQ/QTUM/NVDA) are still in range and should be the first to
  convert on the Mon 6/1 open if execution is authorized.
- Mon's ISM Mfg PMI ~10:00 ET is a tier-2 print but can move the tape;
  stage SPY/QQQ either at open (MOO) or wait through 10:00 if cautious.
  NFP 6/5 and CPI 6/10 are the bigger gating events for sizing decisions
  later in the week.

**ClickUp notification**: **NOT sent.** No urgent catalyst clears the bar:
markets are closed (Sat); we hold no positions (no held-name halt/shock);
no fresh overnight macro tape-bomb; PLTR's +9.22% is a >5% watchlist move
but it (a) printed during regular hours on a known AI rally and (b) is on
a name we don't hold, so it's a re-plan input, not an urgent ping. The
$2B quantum funding and Dell AI-server print are already in the tape.

**Next session**:
- Mon 6/1 pre-market: re-pull /v2/clock + /v2/account; refresh watchlist
  marks; lead with SPY/QQQ index starters, then QTUM scale-in and NVDA;
  pre-print blackout for ISM Mfg (~10:00 ET) — stage entries either MOO
  or post-10:00. Keep cash-floor headroom for NFP-week opportunities.

---

### 2026-05-29 Pre-Market

**Account snapshot (Alpaca, GET /v2/account + /v2/positions)**:
- Equity: $100,000.00 | Last equity: $100,000.00 | Cash: $100,000.00
- Buying power: $200,000.00 | Long market value: $0.00
- Open positions: none | Working orders: none
- Status ACTIVE (PA39FINFSDLL); PDT false; day-trade count 0.
- **9th consecutive all-cash session.** Since inception (5/12): Dexter 0.00%
  vs SPY +2.23% (738.19 → 754.68) ⇒ **−2.23% cumulative**.

**Tape (Alpaca IEX; 5/28 daily-bar close, Δ vs 5/27 close, 5/29 pre-mkt last)**:
| Symbol | 5/28 Close | Δ vs 5/27 | 5/29 pre-mkt last |
|---|---|---|---|
| SPY  | 754.68 | +0.54% | ~755.4 |
| QQQ  | 735.64 | +0.84% | ~736.0 |
| QTUM | 159.06 | +1.63% | ~159.1 |
| NVDA | 214.27 | +0.80% | ~214.1 |
| AMD  | 518.07 | +4.54% | ~519.4 |
| IONQ |  70.14 | +7.25% | ~70.1 |

**Market Conditions**:
- **Macro:** April PCE (Fed's preferred gauge) + Q1 GDP 2nd reading landed
  5/28 with no hawkish surprise; S&P 500 / Nasdaq closed at fresh records.
  **Today (5/29, Fri) is light** — only second-tier NY Fed releases
  (Multivariate Core Trend Inflation 10:00 ET, Staff Nowcast 12:45,
  R-star 14:00); no tier-1 print. Forward calendar: **May NFP June 5,
  May CPI June 10, FOMC June 16–17 (Chair Warsh's first presser).**
- **Pre-market tone (5/29):** mildly risk-off in small caps amid a wave of
  dilutive secondaries (e.g. SIDU −17.6% on a $100M raise; PLAB −25% on
  earnings); index futures roughly flat. No broad shock.

**Key News (watchlist)**:
- **Quantum theme — HOT.** Trump administration unveiled an ~$2B federal
  quantum funding push (announced 5/26); Commerce issued letters of intent
  with nine quantum companies totaling $2.013B. **QTUM ETF crossed $5B AUM**
  the same day (strong-inflows = a strategy BUY signal). **RGTI** is a direct
  ~$100M grant recipient + gov't equity stake.
- **IONQ:** Q1 rev $64.7M (+755% y/y, +30% above guide), raised FY26 guide to
  $260–270M, booked first **256-qubit** system sale, SkyWater acquisition
  passed shareholder vote (regulatory close Q2/Q3). **BUT excluded from
  Commerce's $2B LOI list** — relative negative vs RGTI/peers. Ran $43 (4/27)
  → $58 (5/21) → $70 (5/28), **+7.25% on 5/28 alone**. Extremely extended.
- **NVDA:** Q1 FY27 beat+raise digested; **NEW** — Vera CPU launch puts NVDA
  into the data-center CPU market; CFO cites a ~$200B TAM and ~$20B of CPU
  revenue this fiscal year. Trades ~25x fwd (reasonable). $214.
- **AMD:** Q1 beat (rev $10.25B; data-center record $5.8B, +57% y/y);
  MI400/MI455X roadmap; OpenAI 6GW + Meta deals. **Ran +4.5% on 5/28 to $518;
  ~58x fwd (rich)** — now well above the $470–480 entry zone.
- **Indices:** SPY/QQQ at/near records; 2026 SPX targets BofA 7,100 /
  Citi 7,700.

**Trades**: None — draft-only by instruction.

**Trade ideas drafted** (aggressive mode: starter 5–10%, high-conviction
15–25%, single-name cap 25%, cash floor 5–10%, small-caps 3–7%; −8% hard
stop / 10% trailing stop on all):

```
1) SPY  — long starter (lowest binary risk)
   Thesis: deploy beta to stop the 9-session cash drag; tape at records
           after a benign PCE, no tier-1 data today.
   Catalyst: PCE cleared; constructive trend into June.
   Entry: ~$752–755 | Stop: −8% (~$695) | Target: trend-follow, 10% trail
   Size: 8% (~$8,000) | Confidence: 4/5

2) QQQ  — long starter (tech/AI tilt)
   Thesis: AI/tech leadership, captures NVDA/MSFT capex w/o single-name risk.
   Entry: ~$732–736 | Stop: −8% (~$677) | Target: trend-follow, 10% trail
   Size: 7% (~$7,000) | Confidence: 4/5

3) QTUM — long, two tranches (cleanest quantum expression)
   Thesis: diversified quantum basket on the $2B federal funding wave; $5B
           AUM milestone = strong inflows (BUY signal). Basket dampens
           single-name risk vs IONQ/RGTI.
   Entry: half ~$157–159 now, half on 2–3% retrace (~$154)
   Stop: −8% from blended (~$146) | Target: +20–30%, trim 50% at +30%
   Size: 5% (~$5,000) | Confidence: 3/5 (theme hot but extended)

4) NVDA — long starter (high-quality AI core)
   Thesis: beat+raise plus NEW Vera CPU opening a ~$200B CPU TAM (~$20B CPU
           rev this FY); ~25x fwd is reasonable for the franchise.
   Catalyst: Vera CPU ramp; AI capex cycle.
   Entry: $210–215 (in range) | Stop: −8% (~$197) | Target: $240, 10% trail
   Size: 6% (~$6,000) | Confidence: 4/5

5) RGTI — long small starter (small-cap quantum complement)
   Thesis: direct ~$100M grant recipient + gov't equity stake — highest-
           leverage single name on the funding catalyst; complements QTUM.
   Downside (explicit): pre-/early-revenue, high burn, dilution, extreme
           volatility — can draw down 30–50%; hence small size.
   Entry: ~$24–25 (5/27 mark — CONFIRM live quote before any order)
   Stop: −8% hard (expect wide swings) | Target: asymmetric, trim into spikes
   Size: 3% (~$3,000) | Confidence: 2/5
```

If all five executed: ~29% deployed / ~71% cash (within the 5–10% cash
floor with room to scale); semis (NVDA 6%) + quantum (QTUM 5% + RGTI 3%) =
14%, far under the 25% single-name and ~40% sector ceilings.

**HOLD-OFF / watch (not ideas this run)**:
- **AMD** — do NOT chase $519 (+4.5% on 5/28, ~58x fwd); wait ~$470–480.
- **IONQ** — HOLD OFF; spiked to $70 (+7.25%) and was left off the $2B LOI
  list. Need a real pullback or fresh IONQ-specific catalyst; do not chase.
- **PLTR / NBIS** — still valid growth starters (3–5% / 3%) but not re-quoted
  today; confirm live marks before sizing.
- **KTOS / SOFI** — research-only; need a deeper fundamental dive.

**Thesis Notes / Lesson**:
- 9th straight all-cash session; execution remains the binding constraint
  (−2.23% vs SPY since inception). This run is draft-only by explicit
  instruction, so the gap persists another session — but the
  lowest-binary-risk ideas (SPY/QQQ index starters) are staged and ready to
  convert into orders immediately on approval.

**ClickUp**: No notification sent. IONQ printed +7.25% (a >5% watchlist
move), but it is (a) continuation of a known multi-week run, not a fresh
overnight shock; (b) on a name we do not hold; and (c) driven by already-
public catalysts (5/26 funding, earlier earnings). No held-name earnings,
no halts, no macro shock — the bar for an urgent ping is not met.

### 2026-05-28 End-of-Day

**Account snapshot (Alpaca, GET /v2/account + /v2/positions + /v2/orders?status=filled)**:
- Equity: $100,000.00 | Last equity: $100,000.00 | Cash: $100,000.00
- Buying power: $200,000.00 | Long market value: $0.00
- Open positions: none | Filled orders today: none
- Status ACTIVE (PA39FINFSDLL); PDT false; day-trade count 0.

**Daily performance**:
- Dexter today: **0.00%** ($0.00 P/L) — flat, 100% cash, no trades.
- SPY today: **+0.52%** (IEX daily bar 750.59 → 754.48).
- vs Benchmark: **−0.52%** today.
- Since inception (5/12): Dexter **0.00%** vs SPY **+2.21%** (738.19 → 754.48) ⇒ **−2.21%** cumulative.
- Top winner / top loser: n/a (no positions held).

**Market Conditions**:
- April PCE (Fed's preferred inflation gauge) + Q1 GDP 2nd reading landed
  this morning without a hawkish surprise; the tape took it well. S&P 500
  / Nasdaq pushed to fresh records intraday (SPY ~$754.5, +0.52%) before
  gains moderated into the close. Sentiment helped by reports of a
  US–Iran ceasefire extension (~60 days) and nuclear talks. No held-name
  catalysts to manage (book is empty).

**Trades**: None.

**Thesis Notes / Lesson**:
- Eighth consecutive all-cash session. The analysis is sound and the
  watchlist is well-staged (SPY/QQQ index starters, QTUM + RGTI quantum,
  NVDA at a cheaper post-print entry, PLTR/NBIS growth starters), but the
  book has never been deployed — so the strategy keeps booking the full
  opportunity cost of a rising market (now −2.21% vs SPY since 5/12).
  Execution risk has overtaken selection risk as the dominant problem.
  Tomorrow's pre-market must convert at least the lowest-binary-risk
  ideas (SPY/QQQ 5% index starters) into actual orders rather than
  re-drafting them.

### 2026-05-28 Pre-Market

**Account snapshot (Alpaca, GET /v2/account + /v2/positions)**:
- Equity: $100,000.00 | Last equity: $100,000.00 | Cash: $100,000.00
- Buying power: $200,000.00 | Long market value: $0.00
- Open positions: none | Status ACTIVE (PA39FINFSDLL); PDT false; day-trade count 0.
- Still 100% cash entering a 7th+ session. Non-execution streak persists.

**Watchlist marks (Alpaca IEX, 2026-05-27 daily-bar close)**:
| Symbol | 5/27 Close | Δ vs prior | vs 5/21 ref | Note |
|---|---|---|---|---|
| SPY  | 750.59 | +0.02% | +1.06% | Near record, grinding sideways |
| QQQ  | 729.48 | −0.09% | +2.11% | 4-day win streak into 5/26 |
| QTUM | 156.51 | −1.26% | +4.77% | Quantum basket, YTD +36% |
| NVDA | 212.42 | −1.03% | −3.21% | Post-print digestion deepened → cheaper entry |
| AMD  | 494.88 | −1.66% | +10.1% | Ran hard; now above prior entry zone |
| IONQ |  64.77 | +2.86% | +10.0% | Still extended; no pullback |
| PLTR | 133.03 | −3.00% | n/a | New coverage |
| NBIS | 208.32 | +0.14% | n/a | New coverage; very volatile |
| RGTI |  24.52 | −1.82% | n/a | Direct CHIPS grantee |
| KTOS |  57.31 | +0.77% | n/a | Defense; research-only |
| SOFI |  16.17 | +1.25% | n/a | Fintech; research-only |

**Market Conditions**:
- **Tier-1 macro today (2026-05-28, Thu): April PCE price index — the
  Fed's preferred inflation gauge — plus the Q1 GDP second reading,
  both out this morning.** March PCE ran hot at 3.5% headline / 3.2%
  core (above the 2% target). Street looks for April core PCE around
  +0.3% m/m (~3.3% y/y, per BofA). A hot print is a rate-cut headwind
  and a risk-off catalyst; a cool print is the opposite. **Stage any
  entries AFTER the print** to respect the pre-data blackout discipline.
- Broad tape: S&P 500 near records (SPY ~$750.6); QQQ on a multi-day
  win streak and technically constructive (~$729.5). BofA 2026 SPX
  target 7,100 / Citi 7,700.
- Macro-narrative caveat: one third-party source flagged "oil >$100,
  10y yields ~4.6%, Strait of Hormuz closed." This **conflicts** with
  the more recent internal session notes (Iran de-escalation, oil
  sub-$90) and could not be corroborated this session — treating it as
  low-confidence / possibly stale. Verify next session.

**Key News (watchlist)**:
- **NVDA** — Q1 FY27 (reported 5/20 AMC) was a clean beat-and-raise:
  record rev $81.6B (+85% y/y) vs Street $78.8B; EPS $1.87 vs $1.76;
  Q2 guide $91B vs $86.8B; $80B buyback authorized. Stock muted/lower
  post-print on prior run-up; drifted from $219→$212. Consensus Strong
  Buy. Earnings >48h past — entry embargo cleared.
- **AMD** — Q1 2026 (5/5): rev $10.3B (+38% y/y), EPS $1.37 beat; data
  center $5.8B (+57%). MI400 series (MI455X 40 PFLOPS FP4, Helios racks
  Q3'26); OpenAI 6GW + Meta up to 6GW (~$60B) multi-year deals. Stock
  +267% TTM and ran +10% since our 5/21 ref to ~$495 — now above the
  prior $445–452 entry zone (chase risk).
- **IONQ** — Q1: rev $64.7M (+755% y/y), first 256-qubit system sale,
  raised FY guidance; SkyWater acquisition cleared shareholder vote
  (close Q2/Q3 pending regulators). Wedbush PT $75 Outperform. Stock
  ~$65, +37% YTD — still no pullback to the $50–52 entry trigger.
- **QTUM** — $156.51 (5/27); YTD +36%, 1yr +74%; $3.78B AUM. Equal-
  weight quantum/AI-chip basket; still riding the $2B CHIPS-grant
  re-rating.
- **PLTR** (new) — Q1 (5/4): EPS $0.33 vs $0.27, rev $1.63B (+85%);
  raised FY26 rev to ~$7.66B, US commercial guide +120%, FCF $4.2–4.4B.
  Strong fundamentals; valuation rich → size small. Pulled back to ~$133.
- **NBIS** (new) — Q1 (5/13): rev $399M (+685% y/y from $50.9M), Cloud
  AI +841%, EBITDA swung positive ($129.5M); NVDA $2B investment, Meta
  & Microsoft multi-year compute contracts, 1.2GW PA AI factory, raised
  FY guide $3–3.4B on $20–25B capex. High-growth AI-infra neocloud;
  very volatile (5/26 range $206–221) and capex-heavy → small-cap size.
- **RGTI** (new coverage) — direct ~$100M CHIPS-grant recipient with a
  federal minority equity stake; higher-beta single-name expression of
  the quantum theme vs the QTUM basket. ~$24.5.
- **KTOS / SOFI** — carried as research-only; no fresh fundamental
  catalyst confirmed this session. KTOS ~$57 (defense/drones tailwind),
  SOFI ~$16 (fintech). Need a dedicated deep dive before sizing.

**Watchlist Updates**:
- Added PLTR and NBIS to active coverage with fundamentals + entry zones.
- RGTI promoted from research-only to a sized small-cap idea.
- AMD entry zone RAISED / flagged as chase risk after the +10% move.
- NVDA entry zone LOWERED to $208–214 (better than 5/21).
- IONQ remains hold-off; trigger unchanged at $50–52.

**Thesis Notes**:
- The dominant operational issue remains the **non-execution streak**
  (7th+ session in 100% cash). Aggressive-mode strategy says deploy the
  majority of capital; sitting in cash defeats the paper-trading goal.
  Plan is decided — execution is the gap. This run is drafts-only per
  pre-market protocol.
- Today's PCE is the gating event: stage entries after the print to
  avoid buying into a potential hot-inflation air pocket.

**Trade Ideas Drafted (NOT placed in this pre-market run)**:

```
1. Ticker: SPY
   Direction: long (starter)
   Thesis: Establish baseline beta; cannot beat SPY from 100% cash.
   Catalyst: Carry-forward baseline; tape near records.
   Entry zone: after PCE print, ~$748–752
   Stop: −8% from fill
   Target: open-ended (index hold)
   Size: 5% (~$5,000 ≈ 6–7 shares)
   Confidence: 4/5
```
```
2. Ticker: QQQ
   Direction: long (starter)
   Thesis: AI/tech tilt to complement SPY; captures NVDA/MSFT capex.
   Catalyst: NVDA beat-and-raise validates capex; constructive technicals.
   Entry zone: after PCE print, ~$726–731
   Stop: −8% from fill
   Target: open-ended
   Size: 5% (~$5,000 ≈ 6–7 shares)
   Confidence: 4/5
```
```
3. Ticker: QTUM
   Direction: long (starter, scale-in)
   Thesis: Equal-weight quantum basket; caps single-name blow-up; $2B
     CHIPS structural tailwind.
   Catalyst: Sector re-rating; basket auto-captures grantees.
   Entry zone: ~2.5% near $156, ~2.5% on a 2–3% dip (~$152)
   Stop: −8% from blended fill
   Target: open-ended basket hold
   Size: 5% total (~$5,000), split
   Confidence: 4/5
```
```
4. Ticker: NVDA
   Direction: long (starter)
   Thesis: Beat-and-raise; post-print drift from $219→$212 = better entry.
   Catalyst: AI capex intact; $80B buyback; Strong Buy consensus.
   Entry zone: $208–214
   Stop: −8% (~$195)
   Target: trail per strategy; trim 50% at +30%
   Size: 5% (~$5,000 ≈ 23 shares)
   Confidence: 4/5
```
```
5. Ticker: AMD
   Direction: long (starter — REVISED, reduced)
   Thesis: Strong Q1 + MI400/hyperscaler deals, but ran +10% to ~$495.
   Catalyst: data-center momentum intact; no near-term earnings binary.
   Entry zone: prefer pullback to ~$470–480; else half-size only at mkt
   Stop: −8% from fill
   Target: trail per strategy
   Size: 2.5% (half starter) if chasing; full 5% only on pullback
   Confidence: 3/5 (entry timing, not thesis)
```
```
6. Ticker: PLTR
   Direction: long (small starter — NEW)
   Thesis: AI/data-analytics compounder; Q1 beat, raised FY guide, US
     commercial +120%. Valuation rich → keep size small.
   Catalyst: post-beat momentum; gov + commercial pipeline.
   Entry zone: $130–135
   Stop: −8% (~$122)
   Target: trail per strategy
   Size: 3–5% (~$3,000–5,000)
   Confidence: 3/5
```
```
7. Ticker: NBIS
   Direction: long (small-cap starter — NEW)
   Thesis: AI-infra neocloud; rev +685% y/y, EBITDA positive, NVDA $2B
     backing + Meta/MSFT contracts. Downside: $20–25B capex, high vol,
     execution risk — small-cap can de-rate hard.
   Catalyst: hyperscaler compute demand; capacity build-out.
   Entry zone: $200–210
   Stop: −8% (~$192) — honor strictly given volatility
   Target: trail per strategy
   Size: 3% (~$3,000)
   Confidence: 3/5
```
```
8. Ticker: RGTI
   Direction: long (small-cap starter — NEW)
   Thesis: Direct ~$100M CHIPS grantee w/ federal equity stake; high-beta
     single-name quantum expression vs QTUM basket.
   Catalyst: $2B quantum-grant package; sector re-rating.
   Entry zone: ~$23–25
   Stop: −8% (~$22.5)
   Target: trail per strategy
   Size: 3% (~$3,000)
   Confidence: 3/5
```
```
9. Ticker: IONQ
   Direction: HOLD OFF (no entry)
   Thesis: Strong fundamentals but extended; ~$65 vs $50–52 trigger.
   Re-eval trigger: pullback to $50–52 or fresh IONQ-specific catalyst.
```
```
10. Tickers: KTOS, SOFI
    Direction: RESEARCH-ONLY (no entry)
    Note: tailwinds plausible but no fresh fundamental catalyst confirmed
    this session; deep-dive required before sizing.
```

**Combined draft deployment** (if all non-hold-off ideas fired at
midpoints): ~5+5+5+5+2.5+4+3+3 ≈ **32.5% of equity (~$32,500)**, leaving
~67% cash — well above the relaxed 5–10% floor, with room to add.

**ClickUp notification**: **NOT sent.** We hold no positions (no held-
name shock or halt), no watchlist name gapped >5% on the latest close,
and today's PCE is a *scheduled* tier-1 print, not an unscheduled macro
shock. None clears the urgent-catalyst bar per strategy. (If the PCE
print lands materially hot/cold and the open gaps hard, the market-open
session should reassess the ping.)

**Next session**:
- Re-check Alpaca /v2/clock is_open before any orders.
- After the PCE print, lead with SPY/QQQ index starters, then QTUM
  scale-in and NVDA; treat AMD as pullback-or-half-size; layer PLTR/
  NBIS/RGTI as conviction allows; keep IONQ on hold.

---

### 2026-05-27 End-of-Day

**Account snapshot (Alpaca, GET /v2/account + /v2/positions + /v2/orders?status=filled)**:
- Equity: $100,000.00 | Last equity: $100,000.00 | Cash: $100,000.00
- Buying power: $200,000.00 | Long market value: $0.00
- Open positions: none | Filled orders today: none
- Status ACTIVE (PA39FINFSDLL); PDT false; day-trade count 0.

**Performance**:
- Portfolio return today: **+0.00%** (flat — no exposure)
- SPY return today: **+0.06%** (close 750.46 → 750.90, Alpaca IEX bars)
- Relative to SPY: **−0.06%**

**Market Conditions**:
- SPY/S&P 500 drifted slightly higher into the close on a choppy session.
  Tech and financials briefly turned red mid-session on headlines that
  the White House contradicted a leaked Iran deal draft; Nasdaq
  recovered led by select chip names.
- Prior session (5/26) closed at fresh records (S&P 500 7,519.12, +0.61%);
  today digested those gains rather than extending them.

**Key News**:
- Iran deal headline cross-currents whipsawed risk assets intraday — net
  flat for SPY, modest gains for Nasdaq.
- Oil softened (sub-$90); no tier-1 macro print today.

**Watchlist Updates**:
- No change to composition. SPY mark refreshed to $750.90 (+0.06%).
  Other watchlist prints carried forward from 5/21 close pending the
  next pre-market refresh.

**Thesis Notes**:
- Non-execution streak continues — Alpaca confirms zero fills since
  bootstrap. The drafted 5/22 starter slate (SPY, QQQ, QTUM split,
  NVDA, AMD) is still on the books but unpriced at current tape.
- SPY has drifted +1.10% from the 5/21 reference ($742.71 → $750.90)
  while we sat in cash; the cost of waiting compounds.

**Actions taken**:
- Pulled `/v2/account`, `/v2/positions`, `/v2/orders?status=filled` — all
  consistent (100% cash, no positions, no fills).
- Updated `portfolio.md` with EOD snapshot and refreshed SPY mark.
- Sent end-of-day ClickUp notification per protocol.
- No trades executed in EOD window.

**Next session**:
- Pre-market on next trading day: refresh full watchlist quotes against
  current tape, re-validate the 5/22 idea slate at today's prices, and
  fire the index starters (SPY/QQQ) first to establish baseline beta.


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
