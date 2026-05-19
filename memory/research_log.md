# Research Log

Newest entries first.

---

## 2026-05-19 — Pre-market (PARTIAL — credentials still missing)

**Session:** Pre-market, ~pre-09:30 ET. Updated by Bull.

### Blocker status

`secrets.md` is **not present** in this repo (user prompt referenced it,
but no such file exists at the repo root or anywhere else). No Alpaca,
ClickUp, or Perplexity credentials are set as environment variables in
this remote session either. Therefore:

- **No call** was made to Alpaca `/v2/account` or `/v2/positions`.
  Portfolio remains unknown to this session. `portfolio.md` left as
  "unknown" — I will not fabricate balances or positions.
- **No ClickUp ping** was sent. There is a notable catalyst (NVDA
  earnings tomorrow) but it does not meet strategy.md's "urgent" bar
  (gap >5%, halt, macro shock, beat/miss on held name). Without a
  confirmed Alpaca position list I also cannot tell whether NVDA is
  actually held.
- **Perplexity sonar-pro** unavailable. Research below was gathered via
  built-in WebSearch instead, which is acceptable for narrative news
  but does not produce live quote snapshots.

### Macro / tape

- Pre-market futures soft: SPX -0.49%, NDX -0.78%, DJI -0.31%,
  RUT -0.62%. AI-led selloff sentiment carrying over from Monday's
  mixed close. ([CNN premarket](https://www.cnn.com/markets/premarkets))
- **Fed leadership transition:** Kevin Warsh was confirmed by the
  Senate on May 13 (54-45) and took over from Powell on May 15. Powell
  remains on the board — unusual. Warsh is generally read as more
  hawkish than Powell; rates path commentary from him is the new macro
  swing factor. ([CNBC](https://www.cnbc.com/2026/05/13/kevin-warsh-wins-senate-confirmation-as-the-next-federal-reserve-chair.html))
- Last FOMC (Apr 28-29) held funds at 3.50-3.75% on an 8-4 vote — most
  dissents since Oct 1992. March CPI ran hot at 3.3% YoY (vs 2.4% Feb),
  driven by a 21.2% MoM gasoline surge. Disinflation narrative is on
  hold.
- No major US data release flagged for today on the calendars I
  checked; Fed-speaker calendar for May has Waller, Barr, Bowman on the
  tape this month but I did not confirm a 5/19 slot.

### Watchlist notes

- **NVDA** — Earnings **tomorrow (Wed May 20) after close**. Consensus
  ~$79.17B rev / $1.78 EPS for Q1 FY27. Stock $236, +~20% MTD, cap
  $5.71T. Stock has fallen in 3 of last 4 reports despite beats —
  positioning is rich. China DC revenue assumed at zero in guide; any
  H200 / re-entry framework on the call is the real swing factor.
  ([Motley Fool](https://www.fool.com/investing/2026/05/18/nvidias-next-earnings-report-on-may-20-could-send/),
  [24/7 Wall St.](https://247wallst.com/investing/2026/05/14/nvidia-is-up-20-in-a-month-could-the-may-20-earnings-report-knock-it-right-back-down/))
- **AMD** — Already reported Q1 2026 (blowout): rev $10.3B (+38% YoY),
  Data Center $5.8B (+57%), EPS $1.37 (beat $0.08). Q2 guide ~$11.2B.
  Stock +66% YTD. Citi PT $460. Joint AMD/Intel "ACE" x86 AI compute
  announcement is a structural tailwind. "Advancing AI 2026" event
  July 23 in SF is next major scheduled catalyst.
  ([AMD IR](https://ir.amd.com/news-events/press-releases/detail/1284/amd-reports-first-quarter-2026-financial-results),
  [Motley Fool](https://www.fool.com/investing/2026/05/14/after-amds-blowout-earnings-report-is-this-ai-stoc/))
- **IONQ** — Reported May 6: record Q1 rev $64.7M (+755% YoY), FY guide
  raised to $260-270M, RPO $470M (+554% YoY), 60% of revenue now
  commercial. $3.1B cash. Stock +~80% past month — extended. Some
  sell-side cautioning on overheating into quantum-hype move. Defense
  wins (SDA HALO $39M, DARPA HARQ) confirm bookings strength.
  ([Motley Fool](https://www.fool.com/investing/2026/05/09/ionq-the-top-quantum-computing-stock-for-a-once-in/),
  [24/7 Wall St.](https://247wallst.com/investing/2026/05/12/prediction-ionq-faces-headwinds-that-could-push-it-lower-despite-quantum-hype/))
- **QTUM** — 5/18 range $142.00 – $146.19. Dropped 3.25% on 5/15
  ($147.88 → $143.08). 86 holdings, modified equal-weight, 0.40% ER.
  5y CAGR 26.32%. Seeking Alpha rated Buy on 5/12.
  ([Yahoo](https://finance.yahoo.com/quote/QTUM/),
  [Seeking Alpha](https://seekingalpha.com/article/4902986-qtum-the-infrastructure-of-tomorrow))
- **SPY / QQQ** — Yesterday SPY -0.15%, QQQ -0.50%. Heading into NVDA
  print with NDX heavily NVDA-weighted (~7-8% of QQQ). Asymmetric event
  risk through Wed close.

### Draft trade ideas (conditional — DO NOT PLACE)

Per strategy.md the pre-market session does not place trades. Also,
without a portfolio sync I do not know what is already held, so all
ideas below are conditional. Confidence is suppressed across the board
because of the NVDA event one session away.

```
Ticker: NVDA
Direction: TRIM if held >5% weight
Thesis: Stock +20% MTD into earnings; last 3 of 4 prints sold the news
  despite beats; rich positioning + Warsh-Fed overhang. De-risk into
  print, not after.
Catalyst: Earnings Wed 5/20 AMC.
Entry zone: n/a (trim, not add)
Stop: n/a
Target: take 25-33% of position off
Size (% equity): reduce, do not add
Confidence: 4/5 (process trade, not a directional call)
```

```
Ticker: NVDA
Direction: NO NEW LONG
Thesis: Strategy rule — no new entries within 30 min of earnings on
  held names. Even if not held, gap risk into print is too large for a
  pre-market entry today.
Catalyst: n/a
Confidence: 5/5 (rule-based)
```

```
Ticker: AMD
Direction: HOLD / add on pullback
Thesis: Already-printed blowout Q1 + raised Q2 guide remove near-term
  earnings risk through July. Likely to trade in sympathy with NVDA
  Wed; weakness into Thu could be a setup.
Catalyst: NVDA print sympathy move; July 23 "Advancing AI 2026" event.
Entry zone: pullback to prior breakout level — wait for Thu open.
Stop: -8% from entry per strategy.
Target: +20%, then trail.
Size: up to 2% on add.
Confidence: 3/5
```

```
Ticker: IONQ
Direction: TRIM if held; no new long
Thesis: +80% in a month, extended. Q1 already printed. Quantum-hype
  cohort is the most vulnerable name in a tech-led tape correction
  scenario. Take profits, do not chase.
Catalyst: Sentiment / NVDA spillover.
Confidence: 3/5
```

```
Ticker: QTUM
Direction: HOLD
Thesis: Broad equal-weight quantum exposure with single-name cap ~2%
  is the cleaner expression than IONQ alone. No catalyst today;
  monitor for break of 5/15 low ($143.08).
Confidence: 3/5
```

```
Ticker: SPY / QQQ
Direction: NO NEW LONG until NVDA prints
Thesis: Asymmetric event risk through Wed AMC. Warsh's first full week
  as Chair adds rates-path uncertainty on top.
Confidence: 4/5
```

### Actions for next session

1. **Unblock credentials.** Either commit a `secrets.md` to the repo
   (gitignored locally is fine but it must exist in the working
   directory for this prompt to function) or set ALPACA_API_KEY,
   ALPACA_SECRET_KEY, ALPACA_BASE_URL, CLICKUP_API_TOKEN,
   CLICKUP_LIST_ID in the environment's Variables/Secrets.
2. Once unblocked: sync `/v2/account` and `/v2/positions`, fill
   `portfolio.md`, re-validate the draft trade ideas above against
   actual holdings.
3. Re-evaluate NVDA trim sizing once a real weight is known.

---

## 2026-05-19 — Pre-market (BLOCKED) [superseded above]

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
