# Research Log

Newest entries first.

---

## 2026-06-28 — Pre-market (for Mon 2026-06-29)

**Session:** Sunday pre-market prep. Markets closed. Account synced; no positions held.

### Alpaca snapshot
- Equity $100,000 / Cash $100,000 / BP $400,000. ACTIVE, no PDT flag, 0 positions.

### Macro setup for the week
- **FOMC June 16–17 outcome:** Held 3.50–3.75% unanimous. Updated dots show **no cuts in 2026**; SEP core PCE 3.3%, GDP 2.2%. Market is pricing **~30% chance of a HIKE in July**, full 25bp priced by October. Hawkish backdrop.
- **NFP early release Thu Jul 2** (moved up for the July 4 holiday). Consensus +172k. Last print: May +172k, U/E 4.3%.
- **May CPI (released Jun 10):** +4.2% YoY — re-acceleration from April's 3.8%. Inflation sticky.
- **Monday Jun 29:** No major US data on the day. China PMI overnight + RBA in focus globally.

### Tape character
- Mag 7 weakness leading; SPY/QQQ closed the prior week soft on the hawkish Fed + AI-trade cool-off. Russell 2000 / Dow relatively firm — rotation, not full risk-off.
- Strategists leaning "be patient, expect summer volatility / buying opportunities." Preference: large/mid-cap US, financials & industrials over pure tech.

### Watchlist read

**NVDA** — last close ~$192.53 (Jun 26). **-17% from ATH** despite record earnings. YTD only +12% (vs SOXX-like +85%). Pressures: B200 rental rate collapsed from $6.11 → $4.22/unit (-31% in 3 weeks); China data-center revenue effectively zero on US export curbs; Qualcomm AI-architecture competitive noise. Stock is the funding source of the AI-rotation trade. Not a chase here.

**AMD** — **+130% YTD**, dominant 2026 winner. Meta deal (up to 6 GW of Instinct GPUs incl. first 1-GW MI450 custom build) anchors multi-year thesis. Crowded long; extended; risk is mean-reversion if AI capex narrative wobbles further.

**IONQ** — Q1 rev $64.7M (+755% YoY). FY26 guide raised to $260–270M. RPO $470M (+554% YoY) — anchors: $39M SDA contract, MDA SHIELD IDIQ selection. **Trump quantum/cryptographic-defense EOs signed Jun 22** rallied the sector. Demonstrated first photonic interconnect of two trapped-ion systems. Offsets: FY EBITDA loss $310–330M; insiders in quantum names dumped ~$857M over trailing 2 yrs. High-beta, headline-driven.

**QTUM (Defiance Quantum ETF)** — **+54% YTD**, ~$6B AUM, 0.40% ER, ~70–80 names equal-weighted. Defiance just expanded suite (QTUP early-stage, QPUX leveraged). Cleanest way to express quantum theme without single-name blow-up risk.

**SPY / QQQ** — Index proxies. QQQ tech-heavy (>50%) — same Mag 7 drag. Both bracketed by Thu NFP + the July rate-hike pricing. No edge in adding here pre-data.

### Trade ideas (DRAFT — do not place pre-market)

```
Ticker: QTUM
Direction: long (starter)
Thesis: Equal-weighted quantum/AI-adjacent basket riding sector tailwind from Jun 22 EOs without single-name idiosyncratic risk. Up 54% YTD with broad participation.
Catalyst: Quantum policy momentum + continued AI capex spend.
Entry zone: scale at/near Friday close, add on a 1–2% pullback to 20-EMA
Stop: -8% from blended entry (per strategy)
Target: trail per rules — tighten to BE at +10%, 5% trail above HWM after +20%
Size (% equity): 2% starter ($2,000), room to 4% on confirmation
Confidence: 3/5
```

```
Ticker: IONQ
Direction: long (small starter)
Thesis: Best fundamentals in pure-play quantum (RPO +554%, gov't contracts). Sector benefiting from Trump EOs. High volatility — earn the position.
Catalyst: Quantum EOs, follow-through; any incremental gov't contract news.
Entry zone: only on a constructive consolidation, NOT chasing a gap >3%
Stop: -8% hard, per strategy
Target: trail per rules
Size (% equity): 1% starter ($1,000) — half-size given vol + insider-selling overhang
Confidence: 2/5
```

```
Ticker: NVDA
Direction: watch (no entry yet)
Thesis: -17% from ATH but knife is still falling — B200 pricing crack + China zeroed. Want to see stabilization (3 daily closes inside a tight range) before nibbling.
Catalyst: GTC/keynote chatter or pricing data improving.
Entry zone: TBD on stabilization
Stop: -8%
Target: TBD
Size (% equity): 0% now, plan 2% starter on signal
Confidence: 2/5
```

```
Ticker: SPY / QQQ
Direction: watch
Thesis: Hold dry powder into Thu Jul 2 NFP. Hot print → hike-pricing repricing & index pressure; cool print → relief rally. Better risk/reward to wait for the data.
Catalyst: NFP Thu Jul 2.
Entry zone: post-NFP, depending on reaction
Stop: -8%
Target: n/a
Size: 0% pre-data
Confidence: n/a
```

### Decisions
- **No trades placed.** Per pre-market protocol.
- **No ClickUp ping.** No urgent catalyst: no positions to defend, no held-name earnings, no halts, no >5% watchlist gap, no overnight shock — just normal hawkish-Fed digestion + a known NFP later in the week.
- **Next session (Mon 6/29 cash open):** Reassess QTUM and IONQ for starter entries if tape is constructive; otherwise stay flat into Thu NFP.

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
