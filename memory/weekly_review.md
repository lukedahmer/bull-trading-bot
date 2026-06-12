# Weekly Review

Newest entries first.

---

## 2026-06-08 → 2026-06-12 — Week 1 (First successful sync)

### Account snapshot (EOD Friday)
| Field | Value |
|---|---|
| Equity | $100,000.00 |
| Cash | $100,000.00 |
| Buying power | $400,000.00 |
| Long market value | $0.00 |
| Account status | ACTIVE |
| Pattern day trader | false |
| Day trades used (5d) | 0 |

### Activity this week
- **Filled orders (GET /v2/orders?status=filled, after 2026-06-08):** `[]` — none.
- **Open positions (GET /v2/positions):** `[]` — none.
- **Realized P/L:** $0.
- **Unrealized P/L:** $0.
- **Equity Δ vs last_equity:** $0 (last_equity=$100,000, balance_asof=2026-06-11).

### What happened
First week in which Alpaca credentials were available end-to-end. The
2026-05-19 bootstrap session was blocked on missing env vars; that is
now resolved. No trades have been placed yet because the operating
rule for pre-market runs is "draft ideas, do not execute," and no
session this week ran the (currently undefined) execution leg.
Net: 100% cash, zero risk taken, zero risk lost.

### What the market did
- **SPY / QQQ:** Tape closed a positive week on reports of progress
  toward an Iran peace deal lifting oil sanctions; QQQ near 715,
  SPY trailing 12-month return ~+21.6%, QQQ ~+33.0%.
- **Semis:** AI-chip basket sold off mid-week (Jun 5–10) after
  Broadcom's cautious AI outlook and a memory-chip warning. NVDA
  around $214.75 with Street avg target ~$328 (still uniformly
  bullish); AMD and MU each down ~3–4% on the week.
- **Quantum:** Sector remains a momentum trade. IBM committed >$10B
  to US quantum + mainframe manufacturing; Commerce announced ~$2B
  in CHIPS-Act quantum LOIs. IONQ Q1 revenue $64.7M (+755% YoY),
  cash $3.1B, and a $1.8B SkyWater acquisition for vertical
  integration. QTUM ETF +20.5% YTD, +77% TTM. Valuations stretched
  — pure-play P/S ratios (IONQ 109x, RGTI 836x, QBTS 791x) leave
  no margin for execution misses.

### What's on deck next week (Jun 15–19)
- **Mon 6/15:** May Industrial Production.
- **Tue 6/16:** FOMC Day 1; May Housing Starts & Building Permits.
- **Wed 6/17:** **FOMC rate decision + Powell presser**; May Retail
  Sales; Pending Home Sales; CarMax (KMX) earnings.
- **Thu 6/18:** Accenture (ACN) and Kroger (KR) earnings; weekly
  jobless claims.
- **Fri 6/19:** **US markets CLOSED — Juneteenth.**

Held-name earnings risk: none (no positions).

### Lessons / observations
1. **Infra is now unblocked.** Alpaca account pulls cleanly, $400k
   buying power, options L3 enabled and shorting enabled — both
   intentionally disallowed by `strategy.md` and will remain so.
2. **Sitting in 100% cash through an FOMC week is fine.** The rule
   says "no new entries within 30 min of FOMC"; the corollary for a
   blank book is "wait for the decision before sizing in."
3. **Quantum sub-theme is in a momentum regime, not a value regime.**
   QTUM (ETF) is the policy-aligned way to keep exposure; IONQ
   single-name should stay at the small end of the 2% default.
4. **Semi sell-off is a buy-the-dip setup, not a thesis break** —
   AI capex narrative intact; the trigger was Broadcom's guide and
   a memory cycle wobble, not NVDA-specific.

### Plan for next week
- **Pre-FOMC (Mon–Tue AM):** Do not initiate new core positions
  larger than 1% equity. Watchlist deep-dive on NVDA, AMD, QTUM,
  IONQ for entry zones.
- **Post-FOMC (Wed late / Thu):** If reaction is benign, stage into
  core exposure: SPY/QQQ as index ballast (target 5–8% each), QTUM
  for thematic (target ~3%), NVDA starter (~2%). Stay well below
  the 40% sector cap and the 90% deployed cap.
- **Earnings discipline:** No initiations in KMX/ACN/KR before
  their prints; not on the watchlist anyway.
- **Juneteenth:** No US session Fri 6/19 — no run needed beyond
  weekly review on Thu close.

### Strategy adjustments
See `strategy.md` — added an explicit "first deployment" guidance
block plus an FOMC-week sizing carve-out. No structural changes to
risk rules.

---
