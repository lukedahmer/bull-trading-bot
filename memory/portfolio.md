# Portfolio State

Last Updated: 2026-06-04 pre-market (Alpaca /v2/account + /v2/positions + /v2/orders + /v2/stocks/bars/latest)

## Account Summary
- Starting Capital: ~$100,000 (Alpaca paper, opened 2026-05-12)
- Current Cash: $100,000.00
- Total Portfolio Value: $100,000.00
- Buying Power: $400,000.00 (intraday 4x); Reg-T $200,000.00 (not used per strategy)
- Long Market Value: $0.00 | Short Market Value: $0.00
- Last Equity (prior close, 6/3): $100,000.00
- Today's P/L: **0.00%** (flat, all cash, market not yet open)
- Account Status: ACTIVE — no trading/transfer blocks
- Account Number: PA39FINFSDLL
- Pattern Day Trader: false (day-trade count 0)
- Filled orders today: **none** | Recent orders (last 10): **none**
- Benchmark (SPY) inception window (carry-forward from 6/3 EOD):
  738.19 (5/12) → ~755.66 (6/3 close) = **+2.37%**. Dexter same
  window: 0.00%. **Cumulative vs SPY: −2.37%** (gap narrowed ~49 bps
  Wed as cash beat a down tape; will refresh after 6/4 close).
- Cash drag note: 100% cash entering the **14th consecutive session**.
  The 6/3 pre-market starter basket (SPY 5–8% / QQQ 6–7% / NVDA 5–6%
  / QTUM 2.5–5% / RGTI 3%) was **not executed**; the 6/4 pre-market
  reframes the basket (entry zones improved for NVDA / RGTI; PLTR
  promoted from HOLD OFF). See research_log.md 2026-06-04.

## Current Positions
[Agent populates this from Alpaca API each session]

| Symbol | Shares | Avg Entry | Current Price | P&L % | Stop Loss | Thesis |
|--------|--------|-----------|---------------|--------|-----------|--------|
| —      | —      | —         | —             | —      | —         | —      |

## Sector exposure
- Cash: 100%
- Equities: 0%

## Watchlist
Marks from Alpaca IEX 1-min latest bars pulled this session (6/3
post-close timestamps; consolidated open will refresh at the bell).
Pre-market color via web research is in research_log.md 2026-06-04.

| Symbol | 6/3 IEX print | Δ vs 6/2 close | Why Watching | Target Entry (6/4) | Notes |
|--------|------|---------|--------------|--------------|-------|
| SPY    | 753.45 | −0.77% | Baseline beta; account is 100% cash | ~$753–760 (in range) | Held in 5/30 starter zone through the 6/3 down day. Conviction starter. No FOMC/CPI/PPI/NFP-grade blackout today; respect 08:30 ±1 min around jobless claims. |
| QQQ    | 740.97 | −0.54% | Tech/AI tilt | ~$740–746 (in range) | VIX 3-mo low; Aroon bull 6/1. Tech leadership intact. |
| NVDA   | 214.98 | **−3.62%** | AI silicon leader; Vera/Rubin ramp | **$215–225 — at lower bound** | Ex-div $0.250 today (immaterial). COMPUTEX concludes today — sell-the-news watch. Best entry in two weeks. |
| AMD    | 534.11 | **+3.70%** | NVDA-tape proxy + hyperscaler 2nd-source | **HOLD OFF** — more extended | Barclays PT $665 (6/1); SB upgrade 6/3 on AI inference. RSI overbought, insider sales flagged. Wait $470–480. |
| QTUM   | 167.745 | −0.20% | Quantum-theme equal-weight basket; ETF AUM >$5B | **HALF tranche $166–168** or wait $160 | Entry zone $158–160 blown out. Quantinuum IPO halo this week. |
| IONQ   | 68.41 | **−2.73%** | Quantum leader | **HOLD OFF** — vs $50–52 trigger | P/S ~109; excluded from $2B LOI; SkyWater merger approved. Quantinuum IPO rotation risk. |
| RGTI   | 23.71 | **−8.84%** | Direct ~$100M CHIPS LOI + 108-qubit Cepheus GA across clouds | **In/below zone $23–25** — fresh starter | 6/3 washout improved entry quality. Small-cap 3% cap. |
| PLTR   | 141.52 | **−7.09%** | AI/data analytics + USG primary | **In trigger $140–145** — promoted from HOLD OFF | First time in the retrace zone since the 5/29 Dell pop. |
| NBIS   | 249.42 | **−4.91%** | AI infra / neocloud high-growth | **HOLD OFF** — wait $210–215 | Citi PT $287; still ~17% above settle target. |
| KTOS   |  — | — | Defense tech, drones | Research-only | Iran/Israel overhang could be a tailwind; deep-dive owed. |
| SOFI   |  — | — | Fintech disruptor | Research-only | No fresh catalyst. |

## Cash Allocation Plan (aggressive mode — per strategy.md)
- Cash floor relaxed to 5–10% (was 20%); stay heavily invested.
- Starter 5–10%; high conviction 15–25%; single-name cap 25%.
- Size small-caps 3–7% even in aggressive mode due to volatility.
- Deploy in tranches, not all at once; respect −8% hard stop and 10% trail.

## Notes from Last Session
- **Pre-market 2026-06-04 (this run):** 14th consecutive all-cash
  open. Alpaca confirms equity $100,000.00, cash $100,000.00, zero
  positions, no recent orders (PA39FINFSDLL, ACTIVE, PDT false, dtc 0).
  Re-marked watchlist on Alpaca IEX prints. The 6/3 session was
  broadly red: SPY −0.52% consolidated (−0.77% IEX), QQQ −0.54%,
  NVDA −3.62%, RGTI −8.84%, PLTR −7.09%, NBIS −4.91%; AMD bucked
  +3.70%. Entry zones are now **better** for NVDA (at lower bound)
  and RGTI (below zone); **PLTR promoted from HOLD OFF to a fresh
  3–5% starter**. Today's calendar: 08:30 ET Initial Jobless Claims
  (est 211K) + Q1 Nonfarm Productivity (final, est 0.8%) — neither
  is on the strategy's mandatory blackout list, but stuff orders
  outside the 60-second window around the print. **Friday 6/5 NFP
  triggers an 08:00–09:00 ET blackout tomorrow.** No urgent
  catalyst — no ClickUp ping sent.
- **EOD 2026-06-03:** Alpaca confirmed 100% cash through the close
  (equity $100,000.00, no positions, no fills today). SPY ~−0.52%
  to ~$755.66; cash beat the tape by ~52 bps → inception gap
  narrowed to **−2.37%** (from −2.86% Tue). 13th consecutive cash
  close. ISM Services PMI was the tier-1 print; blackout honored.
- **Pre-market 2026-06-03:** drafted basket SPY 5–8% / QQQ 6–7% /
  NVDA 5–6% / QTUM 2.5–5% / RGTI 3%. Not executed intraday.
- Action items for next session (intraday 6/4):
  1. **Execute or document one more hard defer reason.** The 6/3 EOD
     log already said "no new structural reason to defer further" at
     $755.66; today's pre-market further improves entry quality on
     NVDA and RGTI. A 3rd straight passive defer needs to be
     consciously chosen, not drifted into.
  2. **No new entries 08:00–09:00 ET Fri 6/5** (NFP pre-print blackout).
  3. **CPI Tue 6/10 08:30 ET** — pre-print blackout 08:00–09:00 ET.
  4. **FOMC 6/16–17** (Warsh's first presser) — Fed speaker blackout
     begins midnight Sat 6/6.
  5. Watch Iran/Israel headlines — no fresh overnight tape-bomb in
     scans run this session; still an overhang. Trigger for a
     ClickUp ping remains oil >$100, SPY −2%+, or a halt.
