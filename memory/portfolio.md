# Portfolio State

Last Updated: 2026-06-23 Pre-market Tue (Alpaca /v2/account + /v2/positions + /v2/stocks/snapshots pre-market pull)

## Account Summary
- Starting Capital: ~$100,000 (Alpaca paper, opened 2026-05-12)
- Current Cash: $100,000.00
- Total Portfolio Value: $100,000.00
- Buying Power: $400,000.00 (intraday 4x); Reg-T $200,000.00 (not used per strategy)
- Long Market Value: $0.00 | Short Market Value: $0.00
- Last Equity (prior close, Mon 6/22): $100,000.00
- **Day P/L: 0.00%** (cash book, pre-market — no positions)
- **26th consecutive cash open** (25 closes carried in + today's open).
- Account Status: ACTIVE — no trading/transfer blocks
- Account Number: PA39FINFSDLL
- Pattern Day Trader: false (day-trade count 0); options level 3
- Filled orders today: **none** | Filled orders since inception: **none**
- /v2/positions → **`[]`** at Tue 6/23 pre-market pull.
- balance_asof: 2026-06-22

## Current Positions
[Agent populates this from Alpaca API each session]

| Symbol | Shares | Avg Entry | Current Price | P&L % | Stop Loss | Thesis |
|--------|--------|-----------|---------------|--------|-----------|--------|
| —      | —      | —         | —             | —      | —         | —      |

## Sector exposure
- Cash: 100%
- Equities: 0%
- Semis (NVDA + AMD): 0%
- Thematic quantum (QTUM + IONQ): 0%
- Index (SPY + QQQ): 0%

## Watchlist (Mon 6/22 closes from Alpaca /v2/stocks/snapshots; pre-market 6/23 deltas from web search)

| Symbol | Mon 6/22 close | Mon range L–H | Pre-mkt 6/23 | Entry zone (carried) | Status |
|--------|---------------:|---------------|--------------|----------------------|--------|
| SPY    | 744.27 | 743.13–750.14 | gap ~−1.3% → ~$734 | $740–$748 | **gaps below zone** — reassess at open |
| QQQ    | 738.10 | 734.41–745.32 | gap ~−2.4% → ~$720 | $725–$735 | **gaps below zone** — oversold open |
| NVDA   | 208.59 | 207.72–213.98 | $211.28 (−0.28%) | $208–$215 | **inside zone + RS leader** (peers down −5 to −9%) |
| AMD    | 552.00 | 536.50–562.30 | gap ~−5%+ → ~$524 | $520–$535 (ratcheted) | **gap BACK into zone** — chase risk removed by tape |
| QTUM   | 168.51 | 166.48–169.76 | (no specific) | $162–$168 (skip >$170) | sits top of zone; likely inside on a −1.5% gap |
| IONQ   | 58.34  | 55.56–61.97 | (idiosyncratic) | $56–$58 spec | wild Mon range; Northland PT $70 + Clavis XG remain idiosyncratic + |

_Pre-market tape (web): ES −1.33%, NQ −2.42%, YM −0.61% at 5:30 ET.
Trigger cluster: SpaceX (SPCX) −16.4% Mon 6/22 (4th straight down session
since 6/12 IPO) bleeding into AI infra; AI capex sustainability debate;
rates-higher-for-longer pre-PCE; Senate hearing on China chip sales
overhang on NVDA/AMD. Chip carnage pre-mkt: SNDK −9%, MU −7%, MRVL −7%,
STX −7%, INTC −6.7%, AMD −5%+, QCOM −5%. **NVDA only −0.28% — RS leader.**_

## Cash Allocation Plan (aggressive mode — per strategy.md)
- Cash floor: 5–10% (was 20%); stay heavily invested.
- Starter 5–10%; high conviction 15–25%; single-name cap 25%.
- Size small-caps 3–7% even in aggressive mode due to volatility.
- Deploy in tranches; respect −8% hard stop and 10% trail.
- **Tue 6/23 deployable budget (revised by today's gap-down tape):**
  - **NVDA 2% starter** ($2,000) — RS leader, inside ratcheted zone, cleanest read.
  - **AMD 2% starter** ($2,000) — gap into ratcheted $520–$535 zone removes chase risk.
  - **SPY 3% leg** ($3,000) — index ballast, gap below long-standing zone.
  - **QQQ 2–3% leg** ($2,000–$3,000) — oversold gap below zone, mean-reversion bet.
  - **QTUM 2%** ($2,000) — only if inside $162–$168 (skip if open >$170).
  - **IONQ 1% spec** ($1,000) — idiosyncratic catalysts insulate from chip-capex worry.
  - **Total deployable: ~12.5% ($12,500)**, keeps cash ~87.5% (well above 5–10% floor).
  - Semis sector weight if all fill: 7% (cap 40% — plenty of room).

## Notes from Last Session
- **Pre-market 2026-06-23 (this run, Tue):** Credentials live this
  session. `GET /v2/account` → equity $100k, cash $100k, BP $400k,
  LMV $0, ACTIVE. `GET /v2/positions` → `[]` (26th cash open). Watchlist
  refreshed from `/v2/stocks/snapshots` for Mon 6/22 closes. Pre-market
  tape gap-down (ES −1.33%, NQ −2.42%) driven by 4th-day SpaceX selloff
  (−16.4% Mon) + AI capex sustainability concerns + rates-higher pre-PCE.
  **Watchlist development:** NVDA showing RS (−0.28% premkt vs peers
  −5 to −9%); AMD's −5% premkt gap brings it BACK into the ratcheted
  $520–$535 zone (chase risk removed); SPY/QQQ gap BELOW their entry
  zones for the first time. Trade ideas drafted across NVDA / AMD /
  SPY / QQQ / QTUM (conditional) / IONQ (spec) — see research_log.md
  for sizing + stops + targets. **No trades placed** (drafts-only per
  strategy.md). **No ClickUp ping sent** — no held position to alert
  on; macro threshold not met (single-name-driven gap, not regime
  change). Path-decision branch (b) "execute starter" is now strongly
  indicated for the midday session or next pre-market commit, since
  the tape is offering exactly the entry conditions the watchlist
  zones were set up for.
- **EOD 2026-06-22 (prior, Mon):** Post-close pull. `GET /v2/account`
  → equity $100,000.00 | cash $100,000.00 | last_equity $100,000.00 |
  long_market_value $0.00 | ACTIVE (PA39FINFSDLL). `GET /v2/positions`
  → `[]`. `GET /v2/orders?status=filled` → `[]`. Day P/L 0.00% on the
  cash book vs SPY −0.16% (close $745.55 from stockanalysis.com,
  cross-checked against Alpaca IEX daily bar showing $743.75; consolidated
  $745.55 is the trustworthy print). Relative perf +16 bps — meaningless
  alpha; this is the 25th consecutive day collecting the cash carry while
  the index drifts. **Pre-market Mon 6/22 did not run; midday sweep did;
  EOD did.** Path-decision overdue for the 9th consecutive session. PCE
  Thu 6/25 is now 3 sessions out — the binding test of the post-FOMC
  hawkish-dot regime. NVDA stockholder mtg Wed 6/24 (non-blackout). EOD
  ClickUp ping sent per standing rule.
- **Midday 2026-06-22 (prior this Mon):** Midday risk sweep per user
  checklist. `GET /v2/account` → equity $100,000.00, cash $100,000.00,
  BP $400,000.00, long_market_value $0.00, ACTIVE (PA39FINFSDLL).
  `GET /v2/positions` → `[]`. All risk-rule branches N/A on an empty
  book: −8% stop (no positions), +30% trim-50% (no winners), +15%→7%
  trail tighten (no winners). No midday entries — strategy prohibits
  midday adds without a major catalyst, and none on the empty book.
  Web search not triggered (rule fires only on a held position moving).
  Mon 6/22 pre-market did NOT run; Path-decision action item from Sun
  6/21 prep rolls forward. ClickUp suppressed (no stop, no trim).
- **Pre-Market 2026-06-21 (prior, Sun — weekend prep for Mon 6/22):** First
  agent session since Tue 6/16 midday — multi-day log gap covering FOMC Wed
  6/17, Thu 6/18 recovery, Juneteenth-closed Fri 6/19, Sat 6/20. `GET /v2/account`
  → equity $100,000.00, cash $100,000.00, BP $400,000.00, long_market_value
  $0.00, ACTIVE (PA39FINFSDLL), PDT false. `GET /v2/positions` → `[]`.
  `GET /v2/orders?status=all&limit=20` → `[]` (still zero fills since
  inception 2026-05-12). **24 consecutive all-cash closes carried in.**
  Path (B) commit decision was NOT recorded during the gap — strategy.md
  remains unchanged. Watchlist re-ticked from /v2/stocks/snapshots: SPY
  $746.75, QQQ $739.82, NVDA $210.38, AMD $537.13, QTUM $167.89, IONQ $56.54
  (all Thu 6/18 closes). Macro this week: **May PCE / Core PCE Thu 6/25**
  is the binding inflation print after the hawkish Wed 6/17 dot-plot flip.
  NVDA stockholder meeting Wed 6/24. **No ClickUp ping this run:** no held
  positions, no halts, no watchlist gap >5% (market was closed Fri), FOMC
  is digested, PCE is four sessions out — no urgent catalyst threshold met.
  Trade ideas drafted (see research_log.md); no orders placed per user
  directive.
- **Midday 2026-06-16 (prior, Tue):** Midday risk sweep on the standing
  cash book between BoJ-overnight digestion and Wed FOMC. All risk-rule
  branches N/A (zero positions). No midday entries (BoJ in-line, FOMC
  not until Wed). 22nd cash session in progress; Path (B) commit was
  flagged non-optional at EOD if close was flat.
- **Pre-Market 2026-06-16 (prior, Tue):** Drafts-only run per user
  directive. BoJ +25bp landed in-line. 21 consecutive cash closes
  carried; today's flat close puts 22 in play. Path (B) commit deferred.
- **EOD 2026-06-15 (prior, Mon):** Kill-switch triggered — Path (A)
  SPY 3% + QTUM 2% pre-FOMC starter failed to execute inside 09:30–10:30
  ET window. None of the named skip conditions tripped — pure process
  failure (8th passive defer). EOD flipped to Path (B) draft.
- **Pre-Market 2026-06-14 (prior, Sun):** Reconfirmed Path (A) for Mon
  6/15 09:30–10:30 ET window. No execution followed.
- **Weekend Prep 2026-06-13 (prior, Sat):** Committed Path (A) — SPY 3%
  + QTUM 2% pre-FOMC starter for Mon 6/15. AMD upgraded by BofA Top CPU
  Pick + Citi Buy; IONQ shipped 256-qubit to Horizon Dublin.

## Action items for next session (Tue 6/23 09:30–10:30 ET window / midday)
1. **Re-pull /v2/snapshots at the open** — confirm pre-market quotes
   translated into the regular session; replace stale Mon close prices
   with live opens. Look for the first 10-minute capitulation print.
2. **NVDA RS check at 09:45 ET** — if NVDA holds green/unchanged while
   QQQ is red 1.5%+, execute the NVDA starter ($2,000 ≈ 9–10 shares).
   If NVDA cracks with the rest, the RS thesis is broken — wait.
3. **AMD entry inside $520–$535 only** — do not chase if it rebounds
   above $535 on a midday squeeze. Stop $483.
4. **SPY/QQQ index leg** — wait for the 09:45–10:15 ET retest of the
   open low; do NOT buy the gap and go. Stops: SPY $715, QQQ $695.
5. **QTUM gating:** only buy if open is inside $162–$168; skip if
   it gaps and goes >$170.
6. **IONQ spec only at $54–$57** — anchor near Mon low $55.56.
7. **Volume confirmation** — real capitulation lows print with volume
   spikes. If the first hour is light volume, that's not the low; wait.
8. **PCE Thu 6/25** still 2 sessions out — keep starter sizes
   disciplined; bigger adds should wait for the post-PCE tape.
9. **NVDA stockholder meeting Wed 6/24** — non-blackout but headline
   drift risk. If entering NVDA, prefer Tue over Wed.
10. **Cash floor 5–10%** untouchable; today's total deployable budget
    is capped at ~12.5% ($12,500) across all six legs.
11. **ClickUp policy unchanged:** standing EOD ping; intra-session
    pings only on triggered stop, trim, or urgent catalyst on a held
    name.
