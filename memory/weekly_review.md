# Weekly Review

Newest entries first. Written every Friday post-close by Dexter.

---

## 2026-06-29 → 2026-07-03 — Week 27 (Holiday-shortened)

### 1. Account snapshot (via Alpaca `/v2/account`, `/v2/positions`, `/v2/orders`)
| Field | Value |
|---|---|
| Equity | $100,000.00 |
| Last equity (prior close) | $100,000.00 |
| Cash | $100,000.00 |
| Buying power | $400,000.00 |
| Portfolio value | $100,000.00 |
| Long market value | $0.00 |
| Short market value | $0.00 |
| Pattern day trader | false |
| Account status | ACTIVE |
| Trading blocked | false |
| Balance as of | 2026-07-02 |

**Portfolio history (1W, 1D bars, base 2026-06-25 = $100,000):**
`$100k → $100k → $100k → $100k → $100k` — flat line. 0.00% W/W, 0.00% since inception.

### 2. Positions
None. Zero open positions. Zero short exposure. Full cash.

### 3. Trades executed this week
None. Alpaca `/v2/orders?status=filled` returned an empty array; `?status=all` also empty. **No orders have ever been placed on this account.**

### 4. Attribution
N/A — no positions, no trades, no realized or unrealized P/L. All performance is from sitting in cash. At the current 3.50–3.75% fed funds range, idle cash in a paper account contributes nothing; a real deployment would have earned roughly $67 in T-bill equivalent this week.

### 5. What happened in markets this week (context, not held)
- **Holiday-shortened week.** NYSE closed Fri Jul 3 for Independence Day observed (Jul 4 is Saturday). Only 4 trading sessions.
- **Watchlist close (Thu Jul 2, IEX last bar):**
  - QTUM $155.13
  - IONQ $49.68
  - NVDA $194.51
  - AMD $518.25
  - SPY $744.07 (near ATH; S&P 500 printed 7,420 on Jun 17)
  - QQQ $712.53
- **AI chip sector saw a mid-week reversal:** valuation concerns hit — Micron -13%, Intel -9%, AMD -7% on one session. Catalysts: SK Hynix reportedly slowing HBM expansion, growing skepticism on AI capex ROI, and a more hawkish Fed tone.
- **Fed backdrop:** Goldman on Jun 7 pulled its 2026 rate-cut call. June dot plot shifted from cuts to a projected +25bp hike. Fed funds target 3.50–3.75%. 10Y at 4.48%.

### 6. Lessons / process notes
1. **Account is still cold.** Six weeks after bootstrap (memory scaffold laid down 2026-05-19) not a single order has been sent. The strategy doc has rules for entries but no ramp plan. That is the gap.
2. **Watchlist prices have moved meaningfully** during dormancy. AMD is at $518 vs. the semiconductor rally's summer highs; QTUM has ridden the 2025/2026 quantum breakout (ETF +50.5% in 2024, +36.7% in 2025). Late entry risk on the thematic sleeve is real.
3. **Research pipeline works.** Alpaca account/positions/orders endpoints all responded 200. Latest-bar data endpoint responded 200. ClickUp + git flow verified in this run.

### 7. Look-ahead — Week of 2026-07-06
Light macro, front-loaded earnings calendar. Key items:
| Date | Event | Why it matters for us |
|---|---|---|
| Mon 07-06 | Return from holiday, thin volume | Chase risk elevated on gaps |
| Wed 07-08 | **FOMC June meeting minutes** | First minutes under Chair Warsh; markets want tone on the "no cuts / possibly hike" pivot. **No new entries in the 30 min around release.** |
| Thu 07-09 | **PepsiCo Q2 earnings** — unofficial Q2 season kickoff | Consumer read-through |
| Fri 07-10 | Delta Air Lines Q2 earnings | Travel/consumer discretionary read |
| Mon 07-13 → | Big banks report (JPM, BAC, C, WFC on 07-14; GS/MS on 07-14; JPM 07-15) | Bank tape sets tone for QQQ/SPY next Mon–Thu |

**No held names report next week** (mega-cap tech and semis are Week 3, ~Jul 27–31). NVDA/AMD/IONQ earnings are outside next week's window.

### 8. Sector outlook
**Quantum computing (QTUM, IONQ)**
- Structural bull setup intact: $2B CHIPS Act funding announced May, IONQ Q1'26 backlog $470M (+550% Y/Y), Strong Buy consensus with ~41% analyst upside to $69.31 average target.
- **Risk:** IONQ trades ~95x sales. Any risk-off week (like the mid-week AI chip drawdown) will hit thematic names 1.5–2x SPY.
- **Stance:** watchlist stays. First entry should be a starter (~1% eq, half our normal 2%) into IONQ on a >5% intraday drawdown day; QTUM ETF is the safer sleeve to lead with.

**AI / semiconductors (NVDA, AMD)**
- Global chip TAM tracking $975B → $1.3T; PHLX +47% YTD; NVDA Q1 rev $81.6B (+85% Y/Y), AMD $10.3B (+38%).
- **Divergence:** AMD +150% YTD vs. NVDA +13% — the trade has broadened past NVDA. AMD carries higher beta risk into any pullback.
- **Risk:** Fed hawkishness + capex-return skepticism = periodic 5–10% air pockets.
- **Stance:** NVDA is the first semi to add on the next -3% day (starter 2%). AMD only after a >7% drawdown given how extended it is.

**Index proxies (SPY, QQQ)**
- SPY near all-time highs; QQQ +11% in 30 days. Tech is >50% of QQQ.
- Fed pivot to "no cuts / hike risk" is the tape's biggest single risk. Bank earnings 07-14 will set the pulse for the following two weeks.
- **Stance:** SPY is the vehicle for our first "starter deployment" — 2% starter next week to break dormancy without picking a single-name entry wrong.

### 9. Decisions for next week
1. **Break dormancy.** Place first live paper order Mon 07-06 or Tue 07-07: **SPY 2% starter** (~$2,000 notional, ~2–3 shares) on any red open. Use a limit at the prior day's VWAP or better. Purpose is to activate the workflow, not to time the tape.
2. **Do not enter around 14:00 ET Wed 07-08** (FOMC minutes) — 30-min blackout per rulebook.
3. **Watch IONQ** for a >5% down day for a starter half-size entry.
4. **No new rules yet on AMD/NVDA** until we've seen the bank-earnings tape 07-14/15.
5. **Add "speculative bucket cap"** to strategy: QTUM + IONQ combined ≤ 15% of equity (below the 40% sector cap) to reflect ~95x sales valuation risk.
6. **Add "no-cold-account" note:** if the account remains 100% cash for another 5 sessions, mechanically deploy a 2% SPY starter to end the drift.

### 10. Blockers / infra
None. All credentials functioning:
- Alpaca account, positions, orders, latest-bar data — 200 OK.
- ClickUp API — used in this run to file notification.
- GitHub push to designated dev branch — completed.

---
