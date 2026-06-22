# Portfolio State

Last Updated: 2026-06-22 Midday Mon (Alpaca /v2/account + /v2/positions; midday risk sweep)

## Account Summary
- Starting Capital: ~$100,000 (Alpaca paper, opened 2026-05-12)
- Current Cash: $100,000.00
- Total Portfolio Value: $100,000.00
- Buying Power: $400,000.00 (intraday 4x); Reg-T $200,000.00 (not used per strategy)
- Long Market Value: $0.00 | Short Market Value: $0.00
- Last Equity (prior close, Thu 6/18 — Fri 6/19 was Juneteenth, market closed): $100,000.00
- **Day P/L: 0.00%** (cash book — no positions to move)
- **25th consecutive all-cash session in progress** (24 closes carried in)
- Account Status: ACTIVE — no trading/transfer blocks
- Account Number: PA39FINFSDLL
- Pattern Day Trader: false (day-trade count 0); options level 3
- Filled orders today: **none** | Filled orders since inception: **none**
- /v2/positions → **`[]`** (empty array) at Mon 6/22 midday pull.
- **Session gap:** Mon 6/22 pre-market did NOT run. Sun 6/21 prep was the
  last logged session before this midday sweep. Path-decision action item
  from yesterday's prep (commit Path B / execute starter / document defer)
  is overdue and rolls to today's EOD or Tue 6/23 pre-market.

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

## Watchlist (refreshed pre-market Sun 6/21 from Alpaca /v2/stocks/snapshots; latest dailyBar is Thu 6/18 close)

| Symbol | Thu 6/18 close | Wed 6/17 close | Δ% Thu (FOMC-recovery day) | Prior entry zone | Status |
|--------|---------------:|---------------:|---------------------------:|------------------|--------|
| SPY    | 746.75 | 741.02 | +0.77% | $735–$740 | **Above zone**; FOMC dump bottomed $739.26 Wed, recovered Thu. Ratchet entry to $740–$748 or wait for $735 retest. |
| QQQ    | 739.82 | 722.48 | +2.40% | $700–$710 (stale 6/16) | **Way above stale zone**; ratchet to $725–$735 (post-FOMC base). |
| NVDA   | 210.38 | 204.70 | +2.77% | $208–$215 (6/16 ratchet) | **Mid-zone**; cleanest single-name entry on the board. Stockholder mtg Wed 6/24. |
| AMD    | 537.13 | 512.19 | +4.87% | $470–$478 (stale 6/13) | **Far above stale zone** (+$60 since); MEXT close + Citi/BofA bull tape drove a re-rate. New zone $520–$535. |
| QTUM   | 167.89 | 162.36 | +3.41% | $152–$156 (stale) | **Way above stale zone** (+$15); quantum theme +54% YTD per Defiance. New zone $162–$168 (no chase >$170). |
| IONQ   | 56.54 | 54.725 | +3.32% | $56–$58 (alert-only) | **Back inside zone** post-FOMC pullback; still spec-only sizing per P/S 109. |

_FOMC Wed 6/17 was hawkish surprise — dot plot flipped from cut to hike (9 of 18 see ≥1 hike by year-end), worst Fed-day for a new chair since 1994. Thursday recovered cleanly; Friday was Juneteenth (closed). Net week +0.9% on SPY despite the Wed dump._

## Cash Allocation Plan (aggressive mode — per strategy.md)
- Cash floor: 5–10% (was 20%); stay heavily invested.
- Starter 5–10%; high conviction 15–25%; single-name cap 25%.
- Size small-caps 3–7% even in aggressive mode due to volatility.
- Deploy in tranches; respect −8% hard stop and 10% trail.
- **Mon 6/22 deployable budget (DRAFT — drafts only this run per user pre-market directive):**
  - Diversified-index leg: SPY 3% or QQQ 3% (single ticket) — choose at open based on which is closer to ratcheted zone.
  - Theme leg: QTUM 2% (single ticket) only if it backs off to $162–$165; skip if it gaps >$170.
  - Single-name semi leg: NVDA 2% starter — only name in zone after Thu's tape.
  - AMD DEFER — chase risk after +4.87% Thu rip; wait for $525 retest.
  - IONQ optional spec 1% inside $56–$58; skip if >$58 on Mon open.
  - Total deployable: ~7–8% ($7–8k), keeps cash ~92%.

## Notes from Last Session
- **Midday 2026-06-22 (this run, Mon):** Midday risk sweep per user
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

## Action items for next session (Pre-market Mon 6/22, ~06:00 ET)
1. **Re-pull /v2/account + /v2/positions + /v2/snapshots** for SPY,
   QQQ, NVDA, AMD, QTUM, IONQ — refresh entry zones against Thursday
   close (the last regular session) and any Mon pre-market gap.
2. **Watch pre-market for Monday gap risk** — first session after
   Juneteenth long weekend; expect catch-up flow. >1.5% SPY gap either
   direction = re-evaluate before deploying.
3. **Path-decision is overdue.** Strategy.md is unchanged from 5/19;
   Path (B) draft from 6/15 EOD has been parked for six days. Pre-market
   Mon 6/22 needs to either:
   (a) Commit Path (B) edits to strategy.md (catalyst-independent starter,
       cash-drag escalator, execution-or-document rule, binding-gate
       rename ban), OR
   (b) Execute a catalyst-independent starter inside the first hour
       on Mon (SPY 3% or QQQ 3% + NVDA 2% + QTUM 2% — total 7%),
       OR
   (c) Document an explicit reason for further defer in a ClickUp ping
       under the proposed execution-or-document rule.
4. **NVDA is the cleanest single-name entry** — only watchlist name
   sitting inside its ratcheted zone after Thursday's tape. Stockholder
   mtg Wed 6/24 is a non-blackout event but watch for headline drift.
5. **AMD and QTUM are now CHASE risk** — both broke above their prior
   zones on Thu's recovery. Wait for pullback or ratchet zones higher
   with explicit acknowledgment.
6. **IONQ** back inside $56–$58 — spec-only, optional 1% entry.
7. **PCE Thu 6/25 is the next macro gate.** Hot print resumes the
   Wed 6/17 hawkish-dot story; cool print disinflation back on the table.
8. **Cash floor 5–10% (aggressive mode)** untouchable.
9. **ClickUp ping policy unchanged:** standing EOD ping always;
   intra-session pings only on triggered stop, trim, or urgent
   catalyst on a held name.
