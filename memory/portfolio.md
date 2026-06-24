# Portfolio State

Last Updated: 2026-06-24 EOD Wed (Alpaca /v2/account + /v2/positions + /v2/orders?status=filled post-close pull)

## Account Summary
- Starting Capital: ~$100,000 (Alpaca paper, opened 2026-05-12)
- Current Cash: $100,000.00
- Total Portfolio Value: $100,000.00
- Buying Power: $400,000.00 (intraday 4x); Reg-T $200,000.00 (not used per strategy)
- Long Market Value: $0.00 | Short Market Value: $0.00
- Last Equity (prior close, Tue 6/23): $100,000.00
- **Day P/L: 0.00%** (cash book, no positions — 27th consecutive cash close)
- Account Status: ACTIVE — no trading/transfer blocks
- Account Number: PA39FINFSDLL
- Pattern Day Trader: false (day-trade count 0); options level 3
- Filled orders today: **none** | Filled orders since inception: **none**
- /v2/positions → **`[]`** at Wed 6/24 post-close pull.
- /v2/orders?status=filled → **`[]`** (zero fills since inception 2026-05-12; 43 calendar days, 28 trading sessions).
- balance_asof: 2026-06-23

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

## Performance vs Benchmark (Wed 6/24)
- Bull EOD value: $100,000.00 → **Day P/L 0.00%** (cash book).
- SPY (Alpaca IEX daily bar): Tue 6/23 close $733.62 → Wed 6/24 close $731.625 → **SPY −0.27%**.
- **Relative perf: +27 bps vs SPY** — meaningless on an empty book; this is the 27th session of "winning by not playing."
- Cumulative since inception: Bull flat; SPY net positive over inception window — the cash drift continues to underperform on a beta-adjusted basis.

## Watchlist (Tue 6/23 closes carried; refresh next pre-market)

| Symbol | Tue 6/23 close (Alpaca IEX) | Entry zone (carried) | Status |
|--------|----------------------------:|----------------------|--------|
| SPY    | 733.62 (Wed 731.625) | $740–$748 | **gaps still BELOW zone** — 2nd straight day below |
| QQQ    | (refresh) | $725–$735 | likely below zone — confirm pre-mkt |
| NVDA   | (refresh) | $208–$215 | refresh — RS leader Tue |
| AMD    | (refresh) | $520–$535 ratcheted | refresh — was in zone Tue gap |
| QTUM   | (refresh) | $162–$168, skip >$170 | refresh |
| IONQ   | (refresh) | $56–$58 spec | refresh |

## Cash Allocation Plan (carried — aggressive mode per strategy.md)
- Cash floor: 5–10% (was 20%); stay heavily invested.
- Starter 5–10%; high conviction 15–25%; single-name cap 25%.
- Tue 6/23 deployable budget rolled forward UNTAPPED ($12,500 across NVDA / AMD / SPY / QQQ / QTUM / IONQ legs).
- **Tape continues to offer entry conditions; the failure mode is now process drift, not zone discipline.**

## Notes from Last Session
- **EOD 2026-06-24 (this run, Wed):** Post-close pull. `GET /v2/account`
  → equity $100,000.00 | cash $100,000.00 | last_equity $100,000.00 |
  long_market_value $0.00 | ACTIVE (PA39FINFSDLL). `GET /v2/positions`
  → `[]`. `GET /v2/orders?status=filled` → `[]`. Day P/L 0.00% on the
  cash book vs SPY −0.27% (Alpaca IEX daily bar $731.625 vs prior $733.62).
  Relative perf +27 bps — meaningless alpha; this is the **27th consecutive
  day** collecting cash carry while the tape grinds. **No trades placed all
  day** — Tue 6/23 pre-market draft package (NVDA / AMD / SPY / QQQ / QTUM
  / IONQ legs, $12,500 deployable) went unexecuted again. NVDA stockholder
  meeting today (Wed 6/24) digested without incident on the empty book.
  PCE Thu 6/25 is now 1 session out — binding test of the post-FOMC
  hawkish-dot regime arrives at 08:30 ET tomorrow. **Path-decision now
  10 sessions overdue.** EOD ClickUp ping sent per standing rule.
- **Pre-market 2026-06-23 (prior, Tue):** Credentials live this
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
  on; macro threshold not met.
- **EOD 2026-06-22 (prior, Mon):** Post-close pull. `GET /v2/account`
  → equity $100,000.00 | cash $100,000.00 | last_equity $100,000.00 |
  long_market_value $0.00 | ACTIVE (PA39FINFSDLL). `GET /v2/positions`
  → `[]`. `GET /v2/orders?status=filled` → `[]`. Day P/L 0.00% on the
  cash book vs SPY −0.16%. 25th consecutive cash close. EOD ClickUp
  ping sent per standing rule.

## Action items for next session (Thu 6/25 pre-market / PCE day)
1. **PCE 08:30 ET is the binding gate** — no new entries 08:00–09:00 ET
   per strategy §23. Pre-market checklist runs ~06:00 ET (before blackout).
2. **Re-pull /v2/snapshots** for SPY/QQQ/NVDA/AMD/QTUM/IONQ — refresh
   against Wed 6/24 official closes; stale Tue data is unusable for
   sizing post-PCE.
3. **Path-decision is now 10 sessions overdue.** Thu 6/25 EOD (post-PCE)
   is the natural commit point: (a) commit Path (B) edits to strategy.md,
   (b) execute starter on the post-PCE tape inside the 09:30–10:30 ET
   window, or (c) document an explicit defer reason in ClickUp.
4. **PCE consensus reminder:** headline +0.5% MoM / +4.1% YoY; core
   +0.3% MoM / +3.4% YoY (Wells Fargo). Hot core extends hawkish dot;
   cool core is the dovish unwind catalyst.
5. **Carry the Tue 6/23 drafts** — NVDA RS leg, AMD in-zone leg, SPY/QQQ
   index legs, QTUM conditional, IONQ spec — repriced against Wed close.
6. **Cash floor 5–10%** untouchable; total deployable ~12.5% across all
   six legs.
7. **ClickUp policy unchanged:** standing EOD ping; intra-session pings
   only on triggered stop, trim, or urgent catalyst on a held name.
