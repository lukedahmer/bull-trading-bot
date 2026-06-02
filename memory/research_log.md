# Research Log

Newest entries first.

---

## 2026-06-02 — Pre-market

**Session:** Pre-market. Credentials present. Alpaca sync OK.

### Account snapshot
- Equity $100,000, cash $100,000, no open positions. Paper account
  `PA39FINFSDLL`, status ACTIVE.

### Macro backdrop
- **Iran / US conflict:** Conflict that began Feb 28 2026 remains live.
  60-day ceasefire MoU reached late May but the US and Iran exchanged
  retaliatory strikes this week; oil jumped >3% on the fresh missiles.
  Strait of Hormuz disruption risk still in play (Brent has touched
  $100/bbl during the war; WTI ~$90.55 reported June 1). Risk-off tail
  is real — keep cash buffer above the 10% floor.
- **Fed:** Dot plot median implies just one cut in 2026 (to 3.4%);
  market is priced for ~2. Powell "wait and see." No FOMC today; next
  major data print is NFP later this week — avoid new entries within
  30 min of NFP per strategy.
- **Data:** May ISM Manufacturing PMI printed 54.0 yesterday (June 1),
  strongest since May 2022 — supportive for cyclicals/semis. No
  scheduled tier-1 US data today (June 2). ISM Services later this week.
- **Tape:** Indexes opened June higher; June 1 closed mixed (SPY
  -0.15%, QQQ -0.50%). Pre-market June 2 futures broadly flat-to-up on
  NVDA halo.

### Watchlist notes

**NVDA** — Announced a new AI-PC microprocessor in partnership with
Microsoft (Huang called it "largest PC reinvention in 40 years");
Anthropic and OpenAI cited as users. NVDA up ~2–2.5% pre-market.
$0.25 cash dividend, ex-date June 4. ARK was a net buyer (300k shares
bought June 1).

**AMD** — Down ~3.4% on the NVDA chip news after a monster run
(+141% YTD into the print). ARK trimmed (-110k shares). No
company-specific negative — competitive read-through only.

**IONQ** — +71% past month, +56% YTD into May 28; profit-taking ongoing
as IBM ($10B quantum investment, FT-ready by 2029) concentrated the
quantum trade. Q1 2026 revenue $64.7M (+755% YoY), full-year guide
raised to $260–270M. $3.1B cash on hand — longest runway in the group.
Pulled back on June 1 as IBM jumped 7%.

**QTUM** (Defiance Quantum ETF) — Returned 36.69% in 2025, 50.54% in
2024. Sector breadth softening as the trade concentrates into IBM.

**SPY / QQQ** — Analyst SPX 2026 targets: BofA 7,100 (cautious), Citi
7,700 (bullish). QQQ +11% trailing 30 days; consensus 12-mo PT ~$727.
AI infra spend remains the marginal earnings driver.

### Trade ideas drafted (NOT executed — pre-market is research only)

```
Ticker: NVDA
Direction: long (new)
Thesis: AI-PC microprocessor + MSFT partnership is a fresh
  multi-year growth vector on top of the data-center franchise.
  Pre-market +2–2.5%; ARK accumulating.
Catalyst: AI-PC reveal yesterday; ex-div Jun 4 ($0.25).
Entry zone: market open dip if first 15-min weakness; else VWAP
  reclaim.
Stop: -8% from entry (strategy hard stop).
Target: +15–20% trailing per strategy rules.
Size (% equity): 2% starter (~$2,000).
Confidence: 4/5.
```

```
Ticker: QTUM
Direction: long (new)
Thesis: Diversified basket play on the quantum theme while IONQ
  digests gains and IBM concentrates the single-name trade. Lower
  single-name risk than IONQ; sector tail-wind from IBM $10B
  commitment and continued government contracts.
Catalyst: Sector re-rate post-IBM announcement.
Entry zone: open-then-pullback; avoid chasing >+1% intraday.
Stop: -8%.
Target: trailing per strategy.
Size (% equity): 2% (~$2,000).
Confidence: 3/5.
```

```
Ticker: IONQ
Direction: watch (no entry today)
Thesis: Fundamentals strong (Q1 +755% YoY, $3.1B cash, gov't
  contracts) but +71% in a month — wait for a base / VWAP test
  before sizing.
Catalyst: Profit-taking after IBM news.
Entry zone: TBD — looking for a higher-low / consolidation.
Stop: -8% from entry.
Size: 1–2% on confirmation.
Confidence: 3/5.
```

```
Ticker: AMD
Direction: watch (no entry today)
Thesis: Competitive read-through from NVDA AI-PC reveal pressures
  the stock after a +141% YTD run. Not a thesis break, but no need
  to catch the falling knife on day one.
Entry zone: wait for stabilization; revisit if it holds prior
  breakout shelf.
Confidence: 2/5.
```

```
Ticker: SPY / QQQ
Direction: watch
Thesis: No actionable edge intraday; consider as a tactical add
  only on a clean macro-driven flush (Iran headline gap >1.5%).
Confidence: 2/5.
```

### Risk flags
- Geopolitical (Iran/Hormuz) headline risk through the session — size
  starter positions small and keep cash >10%.
- Quantum names are crowded and reflexive; honour the -8% hard stop
  without negotiation.

### Decision
- No trades this run (pre-market is draft-only per strategy).
- No ClickUp ping: no halted holdings (we hold nothing), no >5% gap on
  watchlist, no earnings on a held name, no macro shock vs. prior
  close. NVDA's +2.5% is supportive but does not meet the urgent
  catalyst bar.

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
