# Weekly Review

Newest entries first. Each entry is the Friday end-of-week sweep.

---

## 2026-05-18 → 2026-05-22 — Week 1 (account live, capital not yet deployed)

### Account snapshot (close Fri 2026-05-21 balance-as-of)
| Field | Value |
|---|---|
| Equity | $100,000.00 |
| Last equity (prior close) | $100,000.00 |
| Cash | $100,000.00 |
| Buying power | $200,000 (2x reg-T, unused) |
| Long market value | $0 |
| Portfolio value | $100,000 |
| Account # | PA39FINFSDLL |
| Status | ACTIVE, not flagged PDT |
| Account age | 10 days (opened 2026-05-12) |

### P/L for the week
- Realized: **$0** (no closes)
- Unrealized: **$0** (no opens)
- Net week change: **$0.00 / 0.00%**
- Net YTD (since 2026-05-12 open): **$0.00 / 0.00%**

### Trades this week
GET `/v2/orders?status=filled&after=2026-05-18` returned `[]`.
Zero fills. No trades executed.

### What happened
- 2026-05-19 pre-market session: blocked. The runtime had no
  Alpaca / Perplexity / ClickUp credentials, so no research, no
  trade ideas, no fills. Logged in `research_log.md`.
- 2026-05-20 → 2026-05-22: no sessions ran. Account sat flat in
  cash through NVIDIA earnings (Tue 2026-05-20 AMC) and the rest
  of the week.
- Net result: 100% cash on a week where NVDA printed a record
  $81.6B quarter and guided Q2 to $91B. Opportunity cost, not
  capital loss.

### What worked
- Risk discipline by default: no creds → no trades → no losses.
  The "do not fabricate" rule in `research_log.md` held.
- Repo scaffolding from 2026-05-19 is the foundation this review
  is being written on. Memory files are in place.

### What didn't work
- Operational readiness. Credentials existed (the user has them)
  but were not wired into the environment until this Friday
  session. We were dark through an NVDA earnings print that is
  directly relevant to two of six watchlist tickers (NVDA, AMD).
- Zero deployment 10 days into account life. The strategy says
  "default new position: 2% of equity" but provides no cadence
  for ramping a flat account. Addressed in strategy.md update
  below.

### Macro / catalyst recap (the week we just had)
- **NVDA Q1 FY27, Tue 2026-05-20 AMC:** revenue $81.6B (+85% YoY,
  beat), Data Center $75.2B (+92% YoY), non-GAAP EPS $1.87 vs
  $1.76 consensus. Q2 guide $91B ±2%. Board added $80B buyback,
  raised dividend $0.01 → $0.25. NVDA underperformed YTD heading
  into the print (~+15%, roughly in line with Nasdaq) as the AI
  trade rotated toward AMD / Intel / Micron.
- **QQQ:** all-time closing high $719.79 on 2026-05-14; closed
  Wed 2026-05-20 at $713.15 (+1.66% on the day); ranged
  $706.77–$717.52 into Fri 2026-05-22.
- **Sector rotation:** AMD / Intel / Micron leading semis YTD;
  Micron crossed $800B mkt cap. BTIG flagged a possible
  25–30% correction in the SOX after a ~66% YTD run.
- **Quantum:** QTUM at new ETF highs, +20.5% YTD, +77% trailing
  12mo, ~$3.5B AUM. IONQ Q1 2026 revenue +755% YoY, first
  256-qubit unit sale, announced $1.8B acquisition of SkyWater
  Technology (quantum foundry). US gov't ~$2B CHIPS-Act grants
  earmarked for quantum + advanced semis; IBM building first
  purpose-built quantum foundry.

### Next week — events & catalysts (2026-05-25 → 2026-05-29)
- **Mon 2026-05-25 — Memorial Day.** US equity + bond markets
  closed. No session. Crypto open (irrelevant to us, equities-only).
- **Tue 2026-05-26:** Consumer Confidence (May), new home sales,
  Treasury 2y/5y auctions. Reopen gap risk after 3-day weekend.
- **Wed 2026-05-27:** Fed speakers (watch for late-cycle rate
  guidance), 7y auction.
- **Thu 2026-05-28:** GDP 2nd estimate Q1, initial claims,
  pending home sales.
- **Fri 2026-05-29:** **Core PCE (Apr) — Fed's preferred inflation
  gauge.** Highest-impact print of the week. Personal income &
  spending alongside.
- **Earnings on watchlist:** none of QTUM holdings / NVDA / AMD /
  IONQ report next week (NVDA + AMD already reported in May).
  Watchlist is clean of earnings risk Mon–Fri.

### Sector outlook going into next week
- **AI semis (NVDA, AMD):** Setup is constructive but crowded.
  NVDA print was a beat-and-raise; reaction tape into Fri
  2026-05-22 will signal whether the rotation away from NVDA
  has bottomed. AMD already guided Q2 ~$11.2B (above
  consensus). Risk: BTIG's SOX correction call, plus PCE
  surprise tightening multiples.
- **Quantum (QTUM, IONQ):** Highest-momentum theme on the
  watchlist. Government tailwind (CHIPS quantum grants, IBM
  foundry) is durable. IONQ's SkyWater deal makes it a more
  hybrid quantum+semi name; raises execution risk but also
  TAM. QTUM at new highs = no margin of safety on entry.

### Trade ideas for Tuesday 2026-05-26 reopen
_(Drafts only — pre-market session Tuesday will reconfirm.)_

```
Ticker: QQQ
Direction: long (starter)
Thesis: Deploy first 2% of cash on index proxy to end the
  100% cash drag while keeping single-name risk off until
  PCE clears Friday.
Catalyst: Tuesday reopen, PCE de-risking trade Wed–Thu.
Entry zone: $710–$717
Stop: -8% from entry per strategy (~$655)
Target: re-test $720+ (ATH) post-PCE
Size: 2% equity (≈$2,000 → ~3 shares)
Confidence: 3/5
```

```
Ticker: NVDA
Direction: long (starter)
Thesis: Post-earnings beat-and-raise into Q2 guide $91B.
  Stock entered print de-rated vs peers; reaction over
  Wed–Fri 2026-05-21/22 will dictate sizing.
Catalyst: Confirmed Q1 FY27 beat, $80B buyback added,
  dividend hiked 25x.
Entry zone: TBD after reading Fri 2026-05-22 close on
  Tuesday pre-market.
Stop: -8% from entry.
Target: open.
Size: 2% equity starter, scale to 5% on confirmation.
Confidence: 3/5
```

```
Ticker: QTUM
Direction: watch / no entry
Thesis: Strongest momentum on watchlist but at ATH with
  no pullback. Wait for either a 5–8% pullback or a PCE
  shakeout dip.
Catalyst: IBM quantum foundry rollout, ongoing CHIPS
  quantum grant headlines.
Entry zone: pullback to ~$120–$125 zone.
Stop: -8% from entry.
Size: 2% equity on first entry.
Confidence: 3/5
```

```
Ticker: IONQ
Direction: watch
Thesis: Revenue +755% YoY is real, but the SkyWater
  acquisition changes the business model; let the next
  earnings report frame the new combined entity. High
  single-name volatility — keep size below 2% on first
  entry if taken.
Confidence: 2/5
```

### Process / rule changes
- Add **PCE** to the no-new-entries-30-min-before list.
- Add a **holidays** rule (no new entries in the final 30 min
  before a 3-day weekend; reopen day = staged entries only,
  no full-size).
- Add a **bootstrap deployment cadence** for a flat account:
  no more than 1 starter position per session, max 3 starters
  per week, until the book is ≥30% deployed.
- Applied to `strategy.md` in this commit.

### Risk posture going into next week
- **Net exposure target by Fri close:** 6–10% of equity (i.e.
  one or two starter positions, max). Do not chase.
- **Hard ceiling:** 20% deployed by end of week 2 of trading.
- **Cash floor:** 10% (per strategy) — not at risk this week.

### Open questions / to revisit
- Should the watchlist include a defensive sleeve (e.g. XLP,
  GLD) given SOX correction risk? Flag for week 2 review.
- Should IONQ be re-classified after SkyWater deal closes?
- ClickUp + Alpaca creds: ensure they are persisted as
  environment Variables/Secrets for the web runtime so the
  next session is not blocked.

---
