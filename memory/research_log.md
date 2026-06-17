# Research Log

Newest entries first.

---

## 2026-06-17 — Pre-market

**Session:** Pre-market. Credentials now provided in-session.

**Account snapshot (Alpaca paper PA39FINFSDLL):**
- Equity $100,000 / Cash $100,000 / Long MV $0
- Buying power $400,000 (4x), zero positions, zero day trades used.
- Status ACTIVE, no trading blocks. Clean slate.

### Macro — today's dominant catalyst
- **FOMC decision today 2:00 PM ET; Chair Warsh press conf 2:30 PM ET.** First
  meeting under newly confirmed Chair Kevin Warsh.
- Consensus: **hawkish hold** at 3.50–3.75%. Fed funds futures pricing ~97%
  prob of hold.
- May CPI printed 4.2% (three-year high), reducing rate-cut case. The single
  2026 rate cut still penciled in the March dot plot is widely expected to
  vanish; Warsh may even scrap the dot-plot framework entirely.
- Risk-off skew: hawkish surprise could pressure Nasdaq 100, gold, EUR/USD;
  support USD. Oil tumbled below $80 into the print.
- **Strategy implication:** no new entries within 30 min of FOMC (per rules).
  Wait for the post-2:30 PM tape before deploying capital.

### Pre-market movers (general tape)
- Index futures broadly flat into FOMC.
- Speculative micro-cap volume hot (SUGP +179%, CRVO +31% on insider buy).
- Consumer discretionary weak: PLAY -19% on Q1 miss; VSME -33%.
- Nothing on our watchlist gapped >5% pre-market.

### Watchlist news

**NVDA**
- ~26% below 52-week high; consensus PT $298.
- No idiosyncratic overnight catalyst; trades primarily on AI-chip risk
  appetite into FOMC. China-related sentiment recently constructive.

**AMD**
- Closed -4.62% on June 16 on heavy distribution.
- Cathie Wood's ARK liquidated 141,408 shares (~$72.3M) across ARKK/ARKQ/ARKX
  on June 15. Adds to CEO Lisa Su's 125,000-share / $57.6M insider sale.
- New positive: **Rackspace partnership** announced June 16 — phased 30 MW
  AMD-based compute deployment across Rackspace facilities.
- One valuation model flags AMD as ~21.6% overvalued at current quote (fair
  value ~$450 implied). Mixed picture: bullish product news vs. ugly
  ownership tape.

**IONQ**
- Strong Q1 2026: **$64.7M revenue**, 4th consecutive record quarter, ahead
  of guidance.
- June 6: nine-family quantum error-correcting code demo on 40-barium-ion
  processor; logical error rate 4–9x better than prior superconducting work;
  3.95-sec logical memory lifetime.
- June 11: Horizon Quantum (Dublin) deployed a 256-qubit IonQ trapped-ion
  system, backed by Ireland's National Semiconductor Strategy.
- Momentum + clear commercial story; high beta into a hawkish print.

**QTUM (Defiance Quantum ETF)**
- Quantum theme broadly outperforming. Diversified play preferable to single
  names if we want exposure without IONQ idiosyncratic risk.

**SPY / QQQ**
- QQQ ~$729.78 on June 16, just off the $748.65 52-week high. Sits on
  psychological $730 level into FOMC.
- SPY tape flat into print; oil < $80 trims energy/inflation pulse.

### Trade ideas — DRAFTED, NOT PLACED (pre-market run, FOMC blackout)

```
Ticker: QQQ
Direction: long (initial starter)
Thesis: Establish core index exposure post-FOMC if Warsh delivers as
  expected (hawkish hold) and tape holds $730. Avoids single-name risk.
Catalyst: FOMC + press conf reaction.
Entry zone: $725–732 after 2:45 PM ET, only if tape constructive.
Stop: -8% hard ($668 area) per strategy.
Target: trail per rules; +10% break-even tighten, +20% trail 5%.
Size: 2% of equity (~$2,000, ~3 sh).
Confidence: 3/5.
```

```
Ticker: IONQ
Direction: long (starter, thematic)
Thesis: Strong Q1 print, error-correction breakthrough, Dublin deployment.
  Commercial story leading the quantum cohort.
Catalyst: Continued enterprise deployments; quantum-theme rotation.
Entry zone: wait for post-FOMC pullback; do not chase pre-print.
Stop: -8% from entry.
Target: trail per rules.
Size: 2% of equity (~$2,000).
Confidence: 3/5.
```

```
Ticker: NVDA
Direction: long (starter, mega-cap semis)
Thesis: 26% below 52-week high, clean technical setup vs AMD's distribution
  tape. Preferred semi exposure here.
Catalyst: AI capex durability; post-FOMC risk-on.
Entry zone: post-FOMC, only on confirmed bid.
Stop: -8% from entry.
Target: consensus PT $298; trail per rules.
Size: 2% of equity (~$2,000).
Confidence: 3/5.
```

```
Ticker: AMD
Direction: PASS for now
Thesis: Heavy insider selling (Su) + ARK liquidation + overvaluation flag
  outweighs the Rackspace 30 MW positive. Revisit only after the
  distribution tape clears.
Catalyst: n/a.
Confidence: avoid.
```

```
Ticker: QTUM
Direction: long (optional thematic, mutually exclusive with sizing IONQ
  bigger)
Thesis: Diversified quantum exposure if IONQ idiosyncratic risk feels
  heavy post-FOMC.
Size: up to 2% of equity if used in lieu of doubling IONQ.
Confidence: 2/5.
```

**Aggregate deployment plan (if conditions are right post-2:45 PM ET):**
~$8,000 across QQQ + NVDA + IONQ + (QTUM optional) = ~8% gross deployed,
leaves ~92% cash. Well inside sector cap and cash floor.

### Risk gates today
- 30-min FOMC blackout: 1:30–3:00 PM ET no new entries.
- If hawkish surprise → QQQ < $720, hold off; do not catch a knife.
- If dovish surprise (low prob) → may scale entries faster but still cap 2%.

### ClickUp notification decision
- No held positions to defend; no halt; no >5% gap on watchlist; FOMC is a
  scheduled known event, not a shock. **No ping sent.** Will re-evaluate
  intraday around 2 PM ET.

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
