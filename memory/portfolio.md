# Portfolio State

Last Updated: 2026-06-14 Pre-Market Sun (Alpaca /v2/account + /v2/positions @ Sun AM; markets closed — pre-Monday open prep)

## Account Summary
- Starting Capital: ~$100,000 (Alpaca paper, opened 2026-05-12)
- Current Cash: $100,000.00
- Total Portfolio Value: $100,000.00
- Buying Power: $400,000.00 (intraday 4x); Reg-T $200,000.00 (not used per strategy)
- Long Market Value: $0.00 | Short Market Value: $0.00
- Last Equity (Fri 6/12 close): $100,000.00
- **Weekend P/L: 0.00%** (market closed; **20 consecutive all-cash closes**)
- Account Status: ACTIVE — no trading/transfer blocks
- Account Number: PA39FINFSDLL
- Pattern Day Trader: false (day-trade count 0); options level 3
- Filled orders this weekend: **none** | Filled orders since inception: **none**
- /v2/positions → **`[]`** (empty array) at Sun 6/14 pre-market pull.
- Benchmark (SPY) last close: ~$738.66 area (S&P 500 cash index 7,435.47,
  +0.56% Fri) on US/Iran peace-deal hopes around the Strait of Hormuz.
  Dow +0.5%, Nasdaq 100 −0.5% (hyperscalers MSFT/AMZN/AAPL/ORCL each
  ~−2% on AI-infra wobble post-SpaceX-IPO rotation).
- **Sun 6/14 weekend overlay:** US-Iran draft peace deal text finalized
  Fri 6/12 with Pakistani mediation; possible signing in Switzerland
  as soon as Sunday. Crude −2% Fri to ~$85/bbl (still well above
  pre-war ~$70). If signing lands Sun PM, Mon 6/15 futures should gap
  green; if it slips, partial unwind of Friday's risk-on tape.
- **Path (A) RECONFIRMED for Mon 6/15:** SPY 3% + QTUM 2% pre-FOMC
  starter, staged in the 09:30–10:30 ET window. See research_log.md
  2026-06-13 + 2026-06-14 for full rationale and trade-idea cards.
  Wed 6/17 FOMC presser remains the binding gate for the rest of the
  basket (NVDA/AMD/QQQ DEFER). No weekend headline changes the
  Path (A) sizing.
- Cash drag note: **20 consecutive all-cash sessions closed.** Mon
  6/15 10:30 ET execution window must end or extend the streak. If
  passively deferred again, EOD 6/15 flips to Path (B) (strategy.md
  rewrite permitting catalyst-independent entries).

## Current Positions
[Agent populates this from Alpaca API each session]

| Symbol | Shares | Avg Entry | Current Price | P&L % | Stop Loss | Thesis |
|--------|--------|-----------|---------------|--------|-----------|--------|
| —      | —      | —         | —             | —      | —         | —      |

## Sector exposure
- Cash: 100%
- Equities: 0%
- Semis (NVDA + AMD): 0%
- Thematic quantum (QTUM + IONQ + RGTI): 0%
- Index (SPY + QQQ): 0%

## Watchlist (refreshed pre-market 6/10 from Alpaca snapshots)

| Symbol | 6/9 close | 6/8 close | Δ% Tue | Prior entry zone | Status |
|--------|-----------|-----------|--------|------------------|--------|
| SPY    | 737.07    | 739.235   | −0.29% | $737–740         | At low end of zone — actionable post-CPI |
| QQQ    | 707.86    | 716.05    | −1.14% | $710–716         | Below zone — entry quality improved |
| NVDA   | 208.20    | 208.66    | −0.22% | $205–210         | Mid-zone — Senate hearing 6/11 gate still binding |
| AMD    | 475.50    | 490.01    | −2.96% | $470–475         | At zone — CPI gate clears today |
| QTUM   | 153.79    | 157.855   | −2.58% | $156–159 → $152–156 (ratcheted down) | Below prior zone — best risk-adjusted theme entry |
| IONQ   | 56.66     | 62.78     | −9.75% | $56–58           | At zone — speculative starter possible post-CPI |
| RGTI   | 19.69     | 21.77     | −9.55% | $19–21           | At low end of zone — research only (small cap discipline) |
| PLTR   | 132.05    | 136.47    | −3.24% | $134–140         | Slipped below zone; ratchet to $128–134 |
| NBIS   | 220.17    | 218.03    | +0.98% | $215–225         | In zone but illiquid; research-only |

_Tuesday's intraday saw a massive reversal: opens were green (S&P futures
+0.46% pre-open), then sold off into CPI. Lows were materially deeper
than the closes — IONQ printed $53.30, AMD $437.71, QTUM $147.53, QQQ
$686.43, SPY $722.605. The wicks suggest stop runs / panic selling
ahead of the print rather than persistent distribution._

## Cash Allocation Plan (aggressive mode — per strategy.md)
- Cash floor: 5–10% (was 20%); stay heavily invested.
- Starter 5–10%; high conviction 15–25%; single-name cap 25%.
- Size small-caps 3–7% even in aggressive mode due to volatility.
- Deploy in tranches; respect −8% hard stop and 10% trail.
- **Today's deployable budget (per pre-market 6/10 plan, all post-CPI):**
  - In-line/cool CPI branch (≤4.2% YoY, core ≤2.9%): SPY 5% + QQQ 4% +
    QTUM 4% + AMD 3% basket (~$16k, 16% deployed, 84% cash).
  - Hot CPI branch (>4.3% YoY or core >3.0%): SPY 3% + QTUM 2% defensive
    starter only (~$5k, 5% deployed, 95% cash). Single-name semis defer
    again.
  - Either branch: NVDA waits for Senate hearing tomorrow (6/11);
    IONQ/RGTI spec-only on confirmed bounce.

## Notes from Last Session
- **Pre-Market 2026-06-14 (this run, Sun):** Sunday pre-market workflow
  ahead of Mon 6/15 open. `GET /v2/account` → equity $100,000.00, cash
  $100,000.00, BP $400,000.00, ACTIVE (PA39FINFSDLL), PDT false.
  `GET /v2/positions` → `[]`. Book unchanged since 6/13 weekend prep —
  no fills, no orders. Weekend headline scan turned up two material
  items: (1) **US-Iran draft peace deal text finalized Fri 6/12** with
  Pakistani mediation, possible signing in Switzerland today (Sun) —
  risk-positive if it lands; (2) **week-ahead calendar is heavy** —
  BoJ rate decision Tue 6/16, FOMC statement Wed 6/17 14:00 ET,
  Warsh's first presser, May retail sales + pending home sales Wed.
  No new catalysts on QTUM, IONQ, NVDA, AMD, SPY, QQQ beyond what
  the 6/13 prep already captured. **Path (A) RECONFIRMED** — SPY 3%
  + QTUM 2% pre-FOMC starter for Mon 09:30–10:30 ET. NVDA / AMD / QQQ
  remain DEFERRED to post-Warsh-presser Wed PM. No ClickUp ping
  (no held positions, peace-deal-signing is risk-positive not a
  shock, FOMC still 2 sessions out, no watchlist >5% gap).
- **Weekend Prep 2026-06-13 (prior):** Saturday weekend-prep workflow.
  `GET /v2/account` → equity $100,000.00, cash $100,000.00, BP $400,000.00,
  ACTIVE (PA39FINFSDLL), PDT false. `GET /v2/positions` → `[]`. No
  fresh tick data (weekend); using Friday EOD marks from web research.
  Watchlist news scan delivered fresh catalysts: AMD BofA "Top CPU Pick"
  PT lift + Citi Buy upgrade ("GPU upside not fully priced"); NVDA Vera
  CPU China-client pitch (export-control overhang persists) + Abridge
  AI healthcare partnership (additive); IONQ 256-qubit deployment to
  Horizon Quantum Holdings in Dublin + Rosenblatt Buy reiteration + QEC
  milestone (9 codes, 3.95s logical memory lifetime). **Decision:
  Path (A) committed — SPY 3% + QTUM 2% pre-FOMC starter for Mon 6/15
  09:30–10:30 ET window.** NVDA/AMD/QQQ defer to post-presser Wed 6/17 PM.
  No ClickUp ping (no urgent catalyst; weekend prep ping not a
  standing requirement). 20 cash-session streak unchanged at weekend
  prep — Monday's execution ends or extends the streak.
- **EOD 2026-06-12 (prior):** Post-close summary. `GET /v2/account`,
  `/v2/positions` → `[]`, `/v2/orders?status=filled` → `[]`. Equity flat
  at $100,000.00; cash $100,000.00; BP $400,000.00. **20th consecutive
  all-cash session close.** SPY +0.56% on the day (S&P 7,435.47 close)
  on US/Iran Strait-of-Hormuz peace-deal hopes; Dexter 0.00% → today's
  relative −56 bps vs SPY. Seventh passive defer through the
  CPI/Senate-hearing window; FOMC 6/16–17 is now the binding gate.
  Standing EOD ClickUp ping sent.
- **Midday 2026-06-12 (prior in-day):** Midday risk sweep on the standing
  cash book. `GET /v2/positions` → `[]`. Account equity unchanged at
  $100,000.00, cash $100,000.00, buying power $400,000.00. No fills
  since inception; `/v2/orders` history still empty for the working
  window. **Risk-rule pass: −8% hard stop, +30% trim, +15%→7% trail
  tighten are all N/A — zero open positions.** No new midday entries
  per strategy (the CPI print is two sessions stale, the Senate hearing
  on NVDA cleared Wed 6/11 without producing a fresh actionable line,
  and FOMC 6/16–17 is the next live binding gate — none of these is a
  "major catalyst" worth midday entry on a Friday). 20th cash session
  in progress. ClickUp ping suppressed (no stop, no trim).
- **Midday 2026-06-10 (prior midday):** Midday risk sweep. `GET /v2/positions`
  → `[]`. Account equity unchanged at $100,000.00, cash $100,000.00,
  buying power $400,000.00. No orders filled since the pre-market
  snapshot; pre-market plan was not staged before midday. **Risk-rule
  pass: −8% cut, +30% trim, +15%→7% trail tightening are all N/A —
  zero open positions.** No new midday entries per strategy (no major
  catalyst beyond the already-priced CPI print, and intraday rule
  forbids adding without one). 18th cash session in progress; if the
  post-CPI execution window also closes flat by EOD, today is the
  **seventh passive defer** and the binding-gate rename required by
  action item #9 (pre-market plan) is triggered for the EOD log. No
  ClickUp ping (no stop, no trim).
- **Pre-Market 2026-06-10 (prior in-day):** 18th consecutive cash session
  entering. CPI today 8:30 ET. The 6/9 starter plan was not executed —
  no orders ever staged (sixth passive defer in inception window) — but
  the defer was REWARDED for the second time in three sessions: Tuesday's
  intraday reversal (-1.14% QQQ, -2.58% QTUM, -2.96% AMD, -9.75% IONQ)
  closed the inception cumulative-vs-SPY gap from −0.59% → +0.15%.
  Process gap remains: cash is "winning" on volatility, not strategy.
  Today's post-CPI execution is the explicit terminus — see 6/9 plan's
  "execute-or-document inflection moves to Wednesday." Strategy now
  forces a written decision either way.
- **Pre-Market 2026-06-09 (prior):** Plan called for SPY 3% + QQQ 2% +
  QTUM 2% starter in 09:30–10:30 ET window. Plan NOT staged.
- **EOD 2026-06-08:** 16th consecutive cash close. SPY +0.68% — cash
  drag day; cumulative gap −0.59% vs SPY.
- **EOD 2026-06-05:** NFP washout (SPY −2.45%, NVDA −5.45%, AMD −9.40%);
  cash beat SPY by +245 bps and erased prior underperformance.

## Action items for next session (Pre-market Mon 6/15, ~06:00 ET)
1. **Re-pull /v2/account + /v2/positions + /v2/snapshots + /v2/bars**
   for SPY, QQQ, NVDA, AMD, QTUM, IONQ, RGTI, PLTR, NBIS — refresh
   exact entry zones against Friday's official closes.
2. **Compute exact Dexter-vs-SPY inception P/L** (5/12 → 6/12) using
   /v2/bars daily, replacing the Friday ~−50 bps estimate band.
3. **EXECUTE — Path (A) committed:** SPY 3% ($3,000) + QTUM 2%
   ($2,000) pre-FOMC starter, 09:30–10:30 ET window. SPY split into
   two limit tickets ($730–737); QTUM single ticket ($152–156). Cards
   in research_log.md 2026-06-13.
4. **Skip the starter ONLY if:** SPY gaps red >1.5% on a fresh weekend
   macro shock, OR QTUM gaps above $158 on no-news (chase risk).
5. **NVDA / AMD / QQQ DEFER** to post-presser Wed 6/17 PM. NVDA gated
   on China export-control headline clearance; AMD on FOMC tape;
   QQQ on Nasdaq-100 concentration drag resolution.
6. **IONQ** alert-only. Pass on chase >$60; P/S 109 keeps spec-only.
7. **Cash floor 5–10% (aggressive mode)** untouchable.
8. **Process kill-switch:** If 10:30 ET Mon passes without execution,
   EOD 6/15 log MUST flip to Path (B) — strategy.md rewrite proposal
   for catalyst-independent entries. No more recycled gate renames.
9. **ClickUp ping policy unchanged:** standing EOD ping always;
   intra-session pings only on triggered stop, trim, or urgent
   catalyst on a held name.
