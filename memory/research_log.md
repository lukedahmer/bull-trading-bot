# Research Log

Newest entries first.

---

## 2026-06-24 — Pre-market

**Session:** Pre-market research, no trades placed (per strategy step 4).

### Account snapshot
- Equity $100,000 / Cash $100,000 / no open positions.
- Account `PA39FINFSDLL`, ACTIVE, PDT=false, paper environment.

### Macro / tape
- Tuesday (6/23) closed risk-off: SPY -1.43%, QQQ -3.32%. AI-chip
  sell-off led the tape; Communications + Consumer Disc + Tech worst,
  Real Estate / Health Care / Energy outperformed.
- Pre-market Wed: futures mixed — Dow softer, Nasdaq-100 / S&P 500
  green. Polymarket leans bounce despite chip weakness.
- USD index broke 101 (2026 high); JPY near 2-yr lows vs USD.
- Fed: CME FedWatch 67.9% no-hike in July. Citadel Securities flagged
  "second-round effects" forcing a hiking bias at the July FOMC and a
  September hike, with risk of consecutive hikes through Mar 2027.
- Geopolitics: Trump issued a 60-day waiver on Iran sanctions.

### Today's calendar
- May new home sales.
- Fed bank stress test results.
- **Earnings AMC: Micron (MU)** — fiscal Q3, consensus ~$34.7B rev /
  $19.95 EPS. Highly read-through to NVDA/AMD/QTUM (HBM tightness,
  AI-memory cycle). Mgmt has said 2026 HBM is sold out.
- Earnings AMC: PAYX, JEF.

### Watchlist headlines
- **NVDA $200.07 (-3.7% to -4% on the day):** Caught in the AI sell-off.
  Q1 reported $81.6B rev (+85% YoY), data center $75.2B. Street avg PT
  ~$309 (≈47% upside from spot). No company-specific overnight news.
- **AMD $519.57 (-5.9%):** Hit hardest in the chip group. Recent
  positive: 6-GW Instinct GPU deployment agreement with Meta (incl.
  1-GW MI450). Street avg PT $491 — *below* spot, so consensus is
  cautious here.
- **IONQ $57.81 (-0.9%):** Quantum group volatile after Quantinuum IPO
  pressure. Fundamentals strong: Q1 rev $64.7M (+755% YoY), FY guide
  raised to $260-270M, backlog $470M, $3.1B cash on hand. SDA $39M
  award + MDA SHIELD IDIQ selection.
- **QTUM $163.24 (-3.1%):** Tracks quantum basket. Honeywell quantum
  spin-out + Quantinuum IPO are sector overhangs into June.
- **SPY $733.62 / QQQ $713.58:** Both broke down from prior-day highs;
  QQQ leading lower on chip weight.

### Trade ideas (drafted, NOT executed)
Cash floor is 100% — no positions yet. Bias: patient. MU earnings
tonight is a known catalyst that resolves the HBM / AI-capex question
both ways; do **not** add chip risk into the print.

```
Ticker: QQQ
Direction: long (starter)
Thesis: NDX -3.3% in a single session into a known catalyst (MU AMC)
  often mean-reverts; index limits single-name blow-up risk.
Catalyst: MU print, July FOMC tone.
Entry zone: $710-715 (near 6/23 close, look for early-session flush).
Stop: $688 (-3.5% from 712 mid).
Target: $740 then $755.
Size: 2% equity (≈$2,000 ≈ 3 shares) — starter only, no add until
  after MU prints.
Confidence: 2/5 (Fed-hike tail risk + AI sentiment unresolved).
```

```
Ticker: NVDA
Direction: long (starter, post-MU)
Thesis: -4% on macro/sentiment, no company-specific bad news; Q1 data
  center $75B sets the floor. Wait for MU read-through.
Catalyst: MU HBM commentary, NVDA's GTC/earnings cadence.
Entry zone: $195-200 only AFTER MU reports (no pre-print entry per
  strategy §risk rule on earnings).
Stop: $184 (-8% hard stop from $200).
Target: $230, then trailing.
Size: 2% equity (≈10 shares at $200).
Confidence: 3/5 if MU confirms HBM tightness; 1/5 if MU guides soft.
```

```
Ticker: IONQ
Direction: long (small starter)
Thesis: Hyper-growth name with $3.1B cash war chest; quantum sector
  pullback offers a cheaper entry; high beta to thematic flows.
Catalyst: Govt contract flow (SDA / SHIELD IDIQ), Quantinuum IPO
  comparable read.
Entry zone: $55-58.
Stop: $53 (-8% hard stop from $57.50).
Target: $70 (prior local highs).
Size: 1% equity (≈17 shares) — half-size due to vol.
Confidence: 2/5.
```

- **AMD:** Skip until tape stabilizes — consensus PT below spot, was
  the weakest semi yesterday. Watch for $500 reaction.
- **QTUM:** No edge over QQQ + IONQ direct exposure; skip ETF.
- **SPY:** Pass — QQQ gives better beta to the thesis if we want index
  long.

### ClickUp notification decision
**No ping.** We hold no positions, so no earnings/halt/macro shock on
held names triggers the urgent-catalyst rule. MU print is on the
calendar but is not a held-name event. Will revisit intraday.

### Risk notes for intraday session
- Do not enter NVDA / AMD / QTUM in the 30 min before MU close —
  strategy §risk rule extends "earnings for held names" but the
  read-through to chips is direct enough to apply here as well.
- Watch DXY > 101 — further USD strength can cap multi-day NDX bounce.
- If SPY breaches $725 with broad-tape risk-off, defer all new entries.

---

## 2026-05-19 — Pre-market (BLOCKED)

**Session:** Pre-market bootstrap.

**Status:** Unable to complete research workflow. Required environment
variables are not set in this remote execution environment:

- `ALPACA_API_KEY` — missing
- `ALPACA_SECRET_KEY` — missing
- `ALPACA_BASE_URL` — missing
- `PERPLEXITY_API_KEY` — missing
- `CLICKUP_API_TOKEN` — missing
- `CLICKUP_LIST_ID` — missing

**Actions taken:**
- Bootstrapped repository scaffolding (`memory/strategy.md`,
  `memory/portfolio.md`, `memory/trade_log.md`, this file).
- Did **not** call Alpaca `/v2/account` or `/v2/positions` — no creds.
- Did **not** call Perplexity `sonar-pro` — no key. No fabricated
  research has been written here; only verified facts belong in this
  log.
- Did **not** send a ClickUp notification (no creds, and no urgent
  catalyst is known to exist).

**Trade ideas drafted:** None. Cannot draft ideas without a current
portfolio snapshot and live market research.

**Next session unblocker:**
Configure the six environment variables above in the environment's
Variables/Secrets settings (see
https://code.claude.com/docs/en/claude-code-on-the-web for how the
environment is configured), then re-run the pre-market workflow.

---
