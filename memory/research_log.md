# Research Log

Newest entries first.

---

## 2026-06-11 — Pre-market

**Session:** Pre-market research run. Credentials provided in prompt.

### Alpaca sync
- Account `PA39FINFSDLL` ACTIVE, equity $100,000, cash $100,000, BP $400,000.
- Zero open positions. Day-trade count 0, not flagged PDT.
- Paper-trading endpoint (`paper-api.alpaca.markets`).

### Macro snapshot
- **May CPI (released 2026-06-10):** headline +0.5% m/m, **+4.2% y/y — 3-year high**, in line with consensus. Core +0.2% m/m, +2.9% y/y. Energy +3.9% m/m drove ~60% of the print.
- **US–Iran conflict escalating.** CENTCOM launched fresh self-defense strikes; Iran retaliated against Gulf targets. WTI Jul ~$90.82 (+0.88%), Brent Aug ~$93.70 (+0.66%). Below $100 buffer holds but tail risk is live. Tape consensus: "long grind."
- **Rates / Fed:** hotter CPI keeps Fed on hold expectations intact; growth-tech sensitive to back-end yields.
- **Indices yesterday (06-10):** SPX -0.53%, NDX -0.85%, DJI -0.50%, RUT -0.11%. Risk-off into CPI + Iran headlines.

### Watchlist news

**NVDA** — Close $199.18, mkt cap ~$4.93T. Q1 FY27 (qtr end Apr 26): revenue $81.6B (+85% y/y), net income $58.3B (+211% y/y), Data Center $75.2B (+92% y/y). Jensen Huang declined Senate Banking AI/China hearing invite — modest political-overhang headline, not a fundamentals event. Street consensus Strong Buy, avg PT $303.71 (~+47% upside). Barchart flagged June 11 as a date to watch for NVDA holders — likely refers to product/keynote cadence, not earnings.

**AMD** — Last $452.40 (-3.13% on 06-10, intraday -4.9% off prior close). Selloff was AI-chip-wide on hot CPI + Iran headlines, not company-specific. 34-analyst Buy consensus, avg PT $465.10. Money Morning flagged the selloff as overdone.

**IONQ** — Rallied +13.63% on 06-08 to mid-$60s. Tailwinds: 256-qubit system sold to Univ. of Cambridge in Q1, 100-qubit Tempo to South Korea's KISTI, DARPA HAQ contract, pending SkyWater foundry deal. Cash $3.1B as of 03-31-26. Q1 revenue $64.67M (+755% y/y); FY26 guide raised to $260–270M. Avg PT ~$69.95 (~+10% from last close).

**QTUM (Defiance Quantum ETF)** — AUM ~$6B, +54% YTD, +99% trailing year. Defiance just launched QTUP (early-stage) and QPUX (2x leveraged) — broader product suite signals continued retail flows into the theme. Extended, but uptrend intact.

**SPY / QQQ** — QQQ +11% trailing 30 days but RSI(14) 77.97 (overbought) and MACD histogram flipped negative on 06-04. BofA 2026 SPX target 7,100; Citi 7,700. Setup: bullish backdrop, near-term overbought into hot CPI + Iran tape.

### Catalysts on deck
- Iran/Israel/US headline risk — fluid, can gap markets either way.
- PPI release (usually day after CPI) — verify on econ calendar.
- No held-name earnings today.
- No FOMC today (next meeting per schedule, not within 30-min window).

### Draft trade ideas (NOT executed — pre-market is research-only)

```
Ticker:    NVDA
Direction: long (starter)
Thesis:    Fundamentals dominant (Data Center +92% y/y, Strong Buy PT
           ~$304 vs ~$199). Selloff is macro/geopolitical, not company.
Catalyst:  Jun 11 product/keynote watch; ongoing AI capex from hyperscalers.
Entry zone: $196–$200 (current area). Better fill on Iran-headline dip.
Stop:      $183 (-8% from $199 entry, per strategy hard stop).
Target:    $245 (analyst midpoint trim); trail per strategy after +10/20%.
Size:      2% equity (~$2,000 = ~10 sh at $199).
Confidence: 4/5
```

```
Ticker:    AMD
Direction: long (starter)
Thesis:    -3% on macro headlines, not company news. Buy consensus,
           PT $465 vs $452. AI-chip beta to any Iran de-escalation.
Catalyst:  Macro relief, AI capex narrative.
Entry zone: $445–$455. Prefer a tag of $445 support.
Stop:      $416 (-8% from $452).
Target:    $500 (10%+); trail per strategy.
Size:      2% equity (~$2,000 = ~4 sh at $452).
Confidence: 3/5
```

```
Ticker:    IONQ
Direction: long (starter)
Thesis:    Pure-play quantum leader, $3.1B cash war chest, revenue
           +755% y/y, raised guide. Thematic + fundamental.
Catalyst:  Quantum theme momentum, SkyWater foundry close, KISTI/Cambridge
           deployment milestones.
Entry zone: $58–$62 (post-rally pullback). Avoid chasing mid-$60s green.
Stop:      $56 (-8% from $61 entry).
Target:    $72 (analyst PT + breakout extension).
Size:      2% equity (~$2,000 = ~33 sh at $61).
Confidence: 3/5
```

```
Ticker:    QTUM
Direction: long (thematic starter)
Thesis:    Diversified quantum/AI compute basket. Up 54% YTD; new sister
           products (QTUP, QPUX) signal retail flows persist.
Catalyst:  Continued sector rotation into quantum theme.
Entry zone: Pullback only — wait for 5% off recent high; do not chase.
Stop:      Trail -8% from fill.
Target:    Hold as core thematic; trim 1/3 at +20%.
Size:      2% equity (~$2,000).
Confidence: 3/5
```

```
Ticker:    SPY / QQQ
Direction: stand-down (no new entries)
Thesis:    QQQ RSI 77.97 + MACD flip + hot CPI + live geopolitical
           shock = poor risk/reward to chase indices here.
Action:    Wait for either a 3–5% pullback or a clear Iran de-escalation
           catalyst before initiating index exposure.
```

### Risk flags
- Combined draft sizing (NVDA + AMD + IONQ + QTUM) = ~8% equity, well
  under the 40% semis/thematic cap and the 10% per-name cap. Fine.
- Iran headline tail risk argues for scaling in, not full size on day 1.
- No urgent catalyst (no earnings on held names — there are no holdings,
  no halts, no >5% gap on watchlist outside the IONQ move 3 sessions
  ago). **No ClickUp ping sent.**

### Next session
- Intraday: re-check Iran headlines and AMD/NVDA pre-market tape near
  the open; if NVDA fills $196–$200 with no fresh negative headline,
  consider executing the starter.

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
