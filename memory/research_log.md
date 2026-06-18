# Research Log

Newest entries first.

---

## 2026-06-18 — Pre-market

**Session:** Pre-market research run. Credentials supplied; Alpaca sync successful.

### Portfolio snapshot
- Equity $100k, Cash $100k, BP $400k, **no open positions**. Clean slate.

### Macro / tape
- **Yesterday (6/17) FOMC**: Warsh's first meeting. Fed held, but dot-plot
  shifted hawkish — median 2026 fed funds raised to 3.75% (from 3.375%),
  implying at least one more 25 bp hike this year. 9 of 18 see ≥1 hike,
  6 see ≥2. Core PCE 2026 revised up to 3.3% (from 2.7%); GDP cut to 2.2%.
- **Reaction**: SPY -1.21%, QQQ -0.99% Wednesday close. Dow off an ATH.
- **Pre-market 6/18**: ES +0.58%, NQ +0.85% — modest bounce, not a
  capitulation reversal. Tape remains data-sensitive.

### Watchlist news
- **NVDA** ~$204.65 (-1.33% Wed). Filing $20B bond issuance to fund AI
  capex. Vultr/HPE-NVDA hyperscaler buildout announced. Consensus PT
  ~$298. Fundamentals strong (FY26 rev $215.9B, +65%), but tape risk from
  rates.
- **AMD** ~$507, +149% YTD, ATH $558 on 6/15. Lisa Su flagged MI450/Helios
  customer forecasts running **ahead** of AMD's own projections.
  Rackspace 30MW deployment pact. Extended/parabolic — chase risk high.
- **IONQ** ripping on government/defense pipeline: DARPA HAQ contract,
  $39M SDA contract, Missile Defense SHIELD IDIQ selection, ~$3.3B
  funding base, SkyWater foundry deal pending. RPO +554% YoY to ~$470M.
  Q1 rev +755% YoY. Sentiment hot.
- **QTUM** ETF +47.4% YTD vs QQQ +17.4%. Defiance AUM >$6B. Trump admin
  $2B CHIPS Act grants to 9 quantum names (IBM, GFS, RGTI, QBTS, INFL).
  Sub-sector positioning intact.
- **SPY / QQQ**: Use weakness; do not chase post-FOMC bounce. No CPI/PPI
  print today; watch initial jobless claims & Fed-speak.

### Today's known catalysts
- No earnings on watchlist names today.
- Initial jobless claims 8:30 ET, Philly Fed manufacturing 8:30 ET.
- Multiple Fed speakers post-FOMC (Warsh-era guidance — high vol risk).

### Trade ideas (DRAFT — not placed)

```
Ticker: SPY
Direction: long (starter)
Thesis: Use post-FOMC flush to start a core index sleeve. Dot-plot
  hawkishness is now priced in; bounce in futures shows dip buyers
  present. Build slowly into weakness, not into the gap-up.
Catalyst: Mean reversion after -1.2% FOMC drop; jobless claims may soften.
Entry zone: only if SPY gives back the pre-market gap (limit ≤ Wed close)
Stop: -3% from entry (tight on index)
Target: prior ATH retest
Size (% equity): 2% starter
Confidence: 3/5
```

```
Ticker: NVDA
Direction: long (starter)
Thesis: Best-in-class AI infra, FY26 rev +65%, $20B bond = aggressive
  reinvestment. Wed sell-off was rates-driven, not company-specific.
Catalyst: Vultr/HPE hyperscaler pact; PT $298 vs ~$205 spot.
Entry zone: $200-205 (do not chase >$210)
Stop: -8% (strategy max) = ~$188
Target: $240 first, $295 stretch
Size (% equity): 2% starter
Confidence: 4/5
```

```
Ticker: IONQ
Direction: long (small / speculative)
Thesis: Pure-play quantum with real government/defense revenue
  ramp; sentiment + flows tailwind from CHIPS quantum grants.
Catalyst: 256-qubit demo expected this year; SkyWater close.
Entry zone: stagger; volatile name — pyramid in thirds
Stop: -8% from blended entry
Target: trail; momentum trade
Size (% equity): 1% starter (half of default — risk weight)
Confidence: 3/5
```

```
Ticker: AMD
Direction: WATCH only — do NOT initiate
Thesis: +149% YTD, parabolic into ATH. Excellent fundamentals (MI450
  demand > guidance) but tape is stretched. Wait for first 10%+ pullback.
Catalyst: Any market-wide risk-off should give entry into the $440-460
  zone.
Entry zone: $440-460 (limit only)
Stop: -8% = ~$410
Target: prior ATH retest
Size: 0% today; 2% on pullback
Confidence: 4/5 (on pullback), 1/5 (today)
```

```
Ticker: QTUM
Direction: long (starter, thematic sleeve)
Thesis: Diversified quantum exposure without single-name blow-up risk;
  CHIPS Act tailwind continues; ETF held near highs without parabolic
  blow-off.
Catalyst: Continued government quantum spend; equal-weight basket caps
  single-name drawdown.
Entry zone: any pre-market dip
Stop: -8%
Target: trail
Size (% equity): 1.5% starter
Confidence: 3/5
```

### Risk notes
- Fresh account, zero positions — do **not** front-load. Build sleeves in
  thirds across multiple sessions.
- Honor 10% cash floor and 40% semi-sector cap from strategy.
- No new entries within 30 min of jobless claims/Philly Fed (8:30 ET).

### ClickUp
- No urgent catalyst today (no held-name earnings, no halts, no >5% gap
  on watchlist). **No ping sent.**

### Next session
- Intraday: execute SPY + NVDA starters if entry zones hold; pass on AMD;
  initiate QTUM on weakness; small IONQ tranche only if not gapping up.

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
