# Research Log

Newest entries first.

---

## 2026-06-15 — Pre-market

**Session:** Pre-market. Cash open, account fully funded ($100k equity,
$100k cash, no positions). Credentials are live this session.

### Alpaca snapshot
- Account `PA39FINFSDLL`, ACTIVE, options L3 enabled (unused per
  strategy: no options, no leverage, no shorting).
- Equity $100,000 / Cash $100,000 / Long MV $0.
- BP $400k intraday, $200k Reg-T. Daytrade count 0, PDT=false.

### Macro tape
- **US–Iran framework deal (Sun 6/14)** — Trump announced an agreement
  ending hostilities and reopening the Strait of Hormuz toll-free; US
  naval blockade lifted. Strait had been largely closed since the
  Feb 28 US/Israel strikes. Brent –4% to ~$83, WTI –4.5% to ~$80.
  Risk-on across US futures Monday AM. Source: CNN, Al Jazeera, NBC.
- **FOMC June 16–17** — First meeting under new Chair Kevin Warsh
  (regarded as more hawkish than Powell). 89% prob hold per
  prediction markets, CME FedWatch shows ~0.6% prob of a hike at this
  meeting but ~70% prob of at least one hike by year-end (up from ~0%
  at start of year). Fed funds target 3.50–3.75%. Inflation 4.2%.
  Expected bias shift from easing → neutral/tightening; SEP dots are
  the swing factor.
- VIX at a 3-month low into the meeting.
- Strategy reminder: **no new entries within 30 min of FOMC**
  (Wed 2:00pm ET decision + presser).

### Pre-market movers / watchlist
- **NVDA** +~2% pm. Riding the AI-infra-spend narrative and the
  risk-on bid from the Iran deal. No company-specific overnight news.
- **AMD** +~4% pm. Largest gainer in the AI-chip cohort on the peace
  deal. No fresh company catalyst.
- **TSM** +~4% pm (reference for the cohort, not in watchlist).
- **SPY / QQQ** — Futures green; Nasdaq 100, S&P 500, Dow all higher
  premarket on the Iran deal + lower oil.
- **IONQ** — No fresh news today, but: P/S ~109 as of late May
  (historically rich for early-stage), Q1 sold a 256-qubit trapped-ion
  system to U. Cambridge, placed a second 256-qubit system with
  Horizon Quantum (Ireland), demonstrated error-correction on 40-ion
  barium. Q1 prints across the quantum cohort beat. Heat in the name,
  but valuation risk + FOMC tomorrow = no chase here.
- **QTUM (Defiance Quantum ETF)** — Broad quantum exposure, way less
  single-name risk than IONQ. Riding the same milestone wave.

### Trade ideas drafted (NOT placed)

```
Ticker: SPY
Direction: long (starter)
Thesis: Risk-on tape on Iran peace deal + lower oil; VIX at 3-mo low.
        Want index exposure ahead of FOMC, sized small so the Wed
        decision can't blow up the book.
Catalyst: US–Iran framework deal; FOMC Wed (binary).
Entry zone: market open or first pullback to Friday's close ± 0.3%.
Stop: −3% from entry (index, not single-name; tighter than the 8% rule).
Target: +5% trail / FOMC reassessment.
Size (% equity): 2% (starter; can add to 4% if Fed not surprise-hawkish).
Confidence: 3/5
```

```
Ticker: QQQ
Direction: long (starter)
Thesis: Same risk-on driver as SPY but heavier tech/semi exposure
        captures the chip-cohort rally without single-name binary risk.
Catalyst: Iran deal; FOMC Wed.
Entry zone: open ± 0.3%.
Stop: −3% from entry.
Target: +5% / FOMC reassessment.
Size (% equity): 2% (starter).
Confidence: 3/5
```

```
Ticker: NVDA
Direction: long (starter)
Thesis: Best-in-class AI infra demand; cohort moving on macro tailwind.
        Already +2% pm so don't chase — want pullback or fade into open.
Catalyst: AI capex narrative + Iran deal + post-FOMC clarity.
Entry zone: only on pullback to flat-to-down 0.5% from Friday close.
Stop: −8% from entry (per strategy).
Target: trail per strategy (BE at +10%, 5% trail after +20%).
Size (% equity): 1.5% starter, add to 3% post-FOMC if dot plot benign.
Confidence: 3/5
```

```
Ticker: AMD
Direction: long (starter)
Thesis: Up most in the cohort (+4% pm) on risk-on; thesis is same AI
        capex tailwind but with the laggard-catch-up angle.
Catalyst: Iran deal; FOMC Wed.
Entry zone: ONLY on pullback — do not chase +4% gap.
Stop: −8% from entry.
Target: trail per strategy.
Size (% equity): 1.5% starter, add to 3% post-FOMC.
Confidence: 2/5 (chasing risk).
```

```
Ticker: IONQ
Direction: pass today
Thesis: Tech wins are real but P/S ~109 leaves no margin for a hawkish
        Fed surprise. Wait for either (a) post-FOMC reset or (b) a
        company-specific catalyst (contract, error-correction print).
Size: 0% — revisit after Wed.
Confidence: n/a
```

```
Ticker: QTUM
Direction: long (small thematic starter)
Thesis: Diversified quantum exposure without IONQ single-name
        valuation risk. Same milestone-wave thesis.
Catalyst: Sector momentum; FOMC Wed.
Entry zone: open ± 0.3%.
Stop: −5% from entry.
Target: hold thematic, no fixed target.
Size (% equity): 1% starter.
Confidence: 2/5
```

### Total proposed deployment if all starters filled
- 2 + 2 + 1.5 + 1.5 + 1 = **8% of equity** (~$8k), leaving 92% cash.
- Comfortably under the 40% semi-sector cap (NVDA+AMD+QTUM = ~4%) and
  well above the 10% cash floor.

### ClickUp ping?
No. No held positions to be threatened by a catalyst, no halts, no
earnings on watchlist names today, no gap >5% on a held name. Iran
deal is positive macro but not urgent for our (currently empty) book.

### Next session
- Intraday: monitor pre-FOMC positioning. Do NOT initiate new entries
  in the 30-min window before Wed 2:00pm ET.
- Post-FOMC Wed: re-evaluate dot plot + Warsh presser tone, then size
  up the starters that are still working.

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
