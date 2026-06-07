# Research Log

Newest entries first.

---

## 2026-06-07 — Pre-market (Sunday, prepping for Mon 6/8 open)

**Session:** Pre-market bootstrap with live credentials. Account synced
from Alpaca for the first time.

### Account snapshot
- Equity: $100,000 — 100% cash, 0 positions.
- Buying power: $400,000 (4x intraday margin available, unused).
- Status: ACTIVE, not flagged as PDT.

### Tape context — Friday 6/5 close
- **S&P 500:** -2.64% to 7,383.74.
- **Nasdaq Composite:** -4.0%.
- **Dow:** -1.35% (-695 pts) to 50,866.78.
- **Trigger:** violent chip selloff after Broadcom guidance disappointed
  and a strong jobs report pushed yields up. AMD -10.86% on the day.
- Friday was a risk-off day going into the weekend; gap risk on Mon open.

### Macro / catalysts this week
- **Wed 6/10:** **May CPI / core CPI release** — primary macro event.
  Strategy rule: no new entries within 30 min of CPI. Plan light sizing
  Mon/Tue; reassess after the print.
- Fed cut path: market pricing ≥2 quarter-point cuts later in 2026;
  Gov. Miran on the dovish wire warning against staying tight.
- Earnings on the tape this week: ORCL, CHWY (not in watchlist).

### Watchlist notes
- **NVDA** ~$218.66 last print. +13% YTD, +54% 1Y. Q1 revenue beat; mgmt
  guided Q2 ~$91B (sequential accel, zero China). Next earnings ~Aug 25.
  Analyst consensus target $298 (~28% upside). Friday selloff likely
  guilt-by-association via Broadcom — fundamentals intact.
- **AMD** trading $466 (prev close $523, -10.86%). CFO Jean Hu (6/3)
  flagged "significant" agentic-AI CPU demand. Jun-Q rev guide $11.2B
  (+45% YoY) above $10.5B consensus. Cowen pounded the table 6/2 after
  meeting Lisa Su. Insider sales noted. Bigger Friday drawdown = more
  oversold; primary tactical candidate.
- **QTUM** (Defiance Quantum ETF) ~$169, +54% YTD through 6/2. CHIPS
  Act $2B in letters of intent across 9 quantum firms announced 5/21
  (D-Wave, Rigetti, Quantinuum, PsiQuantum, Atom Computing, Infleqtion
  $100M each). Equal-weight ~85 holdings, single-name risk diluted.
- **IONQ** Q1 rev $64.7M (+754% YoY); FY guide raised to $260–270M.
  $3.1B cash. Sold 256-qubit system to U. Cambridge. RPO $470M (+554%
  YoY) — SDA $39M contract, MDA SHIELD IDIQ selection. Headwind:
  Quantinuum IPO pulled IONQ/RGTI/QBTS -10%+ recently.
- **SPY / QQQ** Sell-side targets split: BofA 7,100, Citi 7,700 for SPX.
  QQQ +11% trailing 30d before Friday's flush.

### Pre-market movers
- Sunday — no live pre-market tape. Will recheck movers Mon ~07:00 ET.

### Draft trade ideas (NOT executing in pre-market run)

```
Ticker: AMD
Direction: long (starter)
Thesis: -10.86% Friday on Broadcom-driven sector flush — not company
        news. Jun-Q guide $11.2B (+45% YoY) above consensus; Cowen
        bullish post Lisa Su meeting; agentic-AI CPU demand cited by CFO.
Catalyst: Sector mean-reversion bounce; CPI Wed 6/10 (asymmetric risk).
Entry zone: $455–470 (Mon open zone; scale don't slam)
Stop: -8% from entry (~$430 if entered $467) — strategy rule.
Target: $520 reclaim (prior close) then $560.
Size (% equity): 2% starter ($2,000 ≈ 4 shares). Add post-CPI if hold.
Confidence: 3/5 — high-quality name, but CPI Wed = headline risk.
```

```
Ticker: NVDA
Direction: long (starter)
Thesis: Caught in Friday's chip flush; fundamentals (85% growth, $91B
        Q2 guide) intact. Earnings not until Aug 25 — no immediate
        binary. Analyst target $298 vs $218 spot.
Catalyst: Chip-sector relief rally; AI capex narrative still constructive.
Entry zone: $215–222.
Stop: -8% (~$201 from $218).
Target: $245 short term; $260+ if SPX stabilizes post-CPI.
Size (% equity): 2% starter ($2,000 ≈ 9 shares).
Confidence: 3/5.
```

```
Ticker: QTUM
Direction: long (core sleeve)
Thesis: Diversified quantum exposure; CHIPS Act tailwind; equal-weight
        avoids single-name binary. 54% YTD with broad sector momentum.
Catalyst: Continued government funding announcements; quantum
        commercialization headlines.
Entry zone: $165–170.
Stop: -8% (~$156 from $170).
Target: $185, then $200.
Size (% equity): 2% ($2,000 ≈ 12 shares).
Confidence: 3/5 — thematic conviction, but expects sector beta.
```

```
Ticker: IONQ
Direction: watch only
Thesis: Best balance sheet in quantum ($3.1B cash) and strongest
        contract pipeline, but Quantinuum-IPO overhang + dilution
        concerns. Prefer QTUM as the thematic expression here.
Catalyst: None imminent; next print is Q2 earnings (Aug).
Entry zone: TBD — want a clean base before sizing.
Size: 0 in pre-market plan.
Confidence: 2/5.
```

```
Ticker: SPY / QQQ
Direction: hold powder
Thesis: Index hedge / beta dry powder. Will not deploy until after CPI
        print Wed 6/10 to avoid macro whipsaw.
Size: 0 pre-CPI.
```

### Risk plan for the day
- CPI is **Wednesday 6/10** — strategy bans new entries within 30 min
  of release. Acceptable to enter Mon/Tue but keep aggregate semi
  exposure ≤ ~6% pre-print so a tape-bomb doesn't blow the 8% stop
  on everything simultaneously.
- Cash floor 10% — easily satisfied even after the three starters
  above (combined ≈ 6% deployed, 94% cash).
- No earnings on held names this week.

### ClickUp notification decision
**No urgent catalyst** identified:
- No held names → no overnight gap risk to existing positions.
- Friday's chip selloff is yesterday's news, not a fresh halt or
  earnings shock.
- No watchlist name gapped >5% in pre-market (market is closed).
- CPI is a scheduled event 3 days out, not an urgent surprise.

→ No ClickUp ping sent.

### Next session
Intraday Mon 6/8: revisit pre-market movers ~07:00 ET, confirm AMD/NVDA
quotes haven't gapped beyond entry zone, then execute starters per the
ideas above if levels hold.

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
