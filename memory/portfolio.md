# Portfolio State

Last Updated: 2026-06-25 EOD Thu (Alpaca /v2/account + /v2/positions + /v2/orders?status=filled post-close pull)

## Account Summary
- Starting Capital: ~$100,000 (Alpaca paper, opened 2026-05-12)
- Current Cash: $100,000.00
- Total Portfolio Value: $100,000.00
- Buying Power: $400,000.00 (intraday 4x); Reg-T $200,000.00 (not used per strategy)
- Long Market Value: $0.00 | Short Market Value: $0.00
- Last Equity (prior close, Wed 6/24): $100,000.00
- **Day P/L: 0.00%** (cash book, no positions — **28th** consecutive cash close)
- Account Status: ACTIVE — no trading/transfer blocks
- Account Number: PA39FINFSDLL
- Pattern Day Trader: false (day-trade count 0); options level 3
- Filled orders today: **none** | Filled orders since inception: **none**
- /v2/positions → **`[]`** at Thu 6/25 post-close pull.
- /v2/orders?status=filled → **`[]`** (zero fills since inception 2026-05-12; 44 calendar days, 29 trading sessions).
- balance_asof: 2026-06-24

## Current Positions

| Symbol | Shares | Avg Entry | Current Price | P&L % | Stop Loss | Thesis |
|--------|--------|-----------|---------------|--------|-----------|--------|
| —      | —      | —         | —             | —      | —         | —      |

## Sector exposure
- Cash: 100%
- Equities: 0%
- Semis (NVDA + AMD): 0%
- Thematic quantum (QTUM + IONQ): 0%
- Index (SPY + QQQ): 0%

## Performance vs Benchmark (Thu 6/25 — PCE day)
- Bull EOD value: $100,000.00 → **Day P/L 0.00%** (cash book).
- SPY: **+0.52%** (S&P 500 close per TheStreet wrap; PCE in-line + Micron blowout).
- **Relative perf: −52 bps vs SPY** — 28th session of cash drag on a green tape. PCE was the binding gate; the post-print rally was the deploy window and we sat it out.
- Cumulative since inception: Bull flat; SPY net positive over inception window — cash drift continues to compound underperformance on a beta-adjusted basis.

## Watchlist (Wed 6/24 closes; refresh next pre-market for Fri 6/26)

| Symbol | Wed 6/24 close (Alpaca IEX) | Entry zone (carried) | Status |
|--------|---------------------------:|----------------------|--------|
| SPY    | 733.32 (Thu ~+0.52%) | $740–$748 | post-PCE rally; refresh against Thu close for Fri |
| QQQ    | (refresh) | $725–$735 | refresh — Nasdaq +0.24% post-PCE |
| NVDA   | (refresh) | $208–$215 | refresh — semis bid on Micron beat read-through |
| AMD    | (refresh) | $520–$535 ratcheted | refresh — Micron tailwind |
| QTUM   | (refresh) | $162–$168, skip >$170 | refresh |
| IONQ   | (refresh) | $56–$58 spec | refresh |

## Cash Allocation Plan (carried — aggressive mode per strategy.md)
- Cash floor: 5–10%; stay heavily invested.
- Starter 5–10%; high conviction 15–25%; single-name cap 25%.
- Tue 6/23 deployable package ($12,500 across NVDA / AMD / SPY / QQQ / QTUM / IONQ legs) rolled forward UNEXECUTED through PCE day.
- **PCE has cleared. The "wait for PCE" rationale is now spent. Path-decision is 11 sessions overdue.**

## Notes from Last Session
- **EOD 2026-06-25 (this run, Thu — PCE day):** Post-close pull.
  `GET /v2/account` → equity $100,000.00 | cash $100,000.00 |
  last_equity $100,000.00 | long_market_value $0.00 | ACTIVE
  (PA39FINFSDLL). `GET /v2/positions` → `[]`. `GET /v2/orders?status=filled`
  → `[]`. Day P/L 0.00% on the cash book vs SPY +0.52% (S&P 500
  post-PCE tape per TheStreet wrap). Relative perf **−52 bps** —
  this is the 28th consecutive cash session and the deploy window
  was today's 09:30–10:30 ET post-PCE bid that the carried package
  was explicitly designed to take. **PCE printed in-line: headline
  +4.1% YoY / +0.4% MoM (cool by 0.1pp), core +3.4% YoY / +0.3% MoM
  (in-line).** Micron blowout earnings led semis. **No trades placed.**
  Path-decision is now 11 sessions overdue; the named binding gate
  (PCE) has cleared without execution. EOD ClickUp ping sent.
- **EOD 2026-06-24 (Wed):** Post-close pull. equity $100,000.00,
  cash $100,000.00, LMV $0. `/v2/positions` `[]`; `/v2/orders` `[]`.
  Day P/L 0.00% vs SPY −0.27% (IEX bar $731.625 vs prior $733.62).
  27th cash close. NVDA stockholder meeting digested without incident.
  PCE T-minus 1.
- **Pre-market 2026-06-23 (Tue):** Tape gap-down (ES −1.33%, NQ −2.42%)
  on SpaceX selloff + AI capex concerns + pre-PCE rates. **Watchlist
  forced into zones:** NVDA RS leader (−0.28% premkt vs peers −5–9%);
  AMD's −5% gap back INTO ratcheted $520–$535 zone; SPY/QQQ gap BELOW
  their entry zones. Full trade-idea package drafted (NVDA / AMD /
  SPY / QQQ / QTUM / IONQ, $12,500 deployable). **No trades placed**
  (drafts-only). **No ClickUp ping** (no held position).
- **EOD 2026-06-22 (Mon):** equity $100k, cash $100k. `/v2/positions`
  `[]`; `/v2/orders` `[]`. Day P/L 0.00% vs SPY −0.16%. 25th cash
  close. EOD ClickUp ping sent.

## Action items for next session (Fri 6/26 pre-market)
1. **Path-decision is now 11 sessions overdue and the named binding
   gate has cleared.** PCE printed in-line; the cool 0.1pp on headline
   MoM is a marginal dovish tilt, not a regime shock. Fri 6/26
   pre-market is no longer "waiting for X" — the X arrived. Either
   commit Path (B) edits to strategy.md or execute a starter at
   09:30–10:30 ET, or document an explicit named-blocker defer in a
   ClickUp ping.
2. **Re-pull /v2/snapshots** for SPY/QQQ/NVDA/AMD/QTUM/IONQ — refresh
   against Thu 6/25 official closes; Wed close is now stale post-PCE.
3. **Carry the Tue 6/23 drafts** — NVDA RS leg, AMD in-zone leg,
   SPY/QQQ index legs, QTUM conditional, IONQ spec — repriced against
   Thu close on the post-PCE tape.
4. **Micron earnings beat** is fresh semi tailwind for the Fri
   pre-market read on NVDA/AMD/QTUM.
5. **Fri 6/26 macro:** quiet day — Univ of Michigan final sentiment +
   5y inflation expectations only. No tier-1 prints; no Fed-speaker
   blackout. Clean window for execution.
6. **Cash floor 5–10%** untouchable; total deployable ~12.5% across
   all six legs.
7. **ClickUp policy unchanged:** standing EOD ping; intra-session
   pings only on triggered stop, trim, or urgent catalyst on a held
   name.
