# Research Log

Newest entries first.

---

## 2026-05-21 — Pre-market

**Session:** Pre-market, ~04:54 ET. Market closed; next open 09:30 ET.

### Account snapshot (Alpaca paper)
- Equity $100,000 / cash $100,000 / BP $200,000.
- Zero open positions. Account active, no blocks. PDT count 0.

### Macro / data calendar today (ET)
- 08:30 — Initial Jobless Claims (cons. 210K, prior 211K).
- 08:30 — Continuing Claims (cons. 1,790K, prior 1,782K).
- 08:30 — Philly Fed Manufacturing (cons. 17.6, prior 26.7 — sharp
  deceleration expected; downside surprise would risk-off tech).
- 09:45 — S&P Global Flash PMIs: Mfg 53.8 cons., Svcs 51.1 cons.
- FOMC minutes were released yesterday (May 20). No Powell speech
  scheduled today per available calendars.

### Overnight / pre-market movers (from May 20 close → May 21 pre-mkt)
- **NVDA** — reported FY27 Q1 after close May 20: rev $81.62B vs
  $79.2B cons; EPS $1.87 vs $1.78; Data Center $75.2B. Guided Q2 to
  ~$91B vs $85–87B cons. Authorized $80B buyback. Raised quarterly
  dividend from $0.01 to $0.25. Initial AH reaction muted (~−0.7%),
  but the beat-and-raise across every line is bullish; muted reaction
  reflects rich expectations, not a weak print. Mkt cap ~$5.5T;
  recent range $216–$227.
- **Semis broadly** — MU and INTC up ~5% in May 20 pre-market on
  heavy dollar volume; sector tone constructive into NVDA.
- **AMD** — announced >$10B in Taiwan AI ecosystem investments
  (announcement dated May 21). Stock recently ~$447; YTD +66%,
  trailing 52-wk +tripled. Strong Buy with avg target $472.
- **IONQ** — Q1 2026: revenue +755% YoY, RPOs $470M (+554%),
  pending SKYT foundry acquisition, expanded $60M QuantumBasel
  contract, photonic interconnect milestone. High-beta but
  fundamentals improving rapidly.
- **QTUM** — last close $140.63 (May 19); up ~84% YoY. AUM $3.6B.
  Top holdings include INTC, MU, MRVL — overlapping semi tailwind.
- **SPY / QQQ** — soft last several sessions (QQQ −0.50%, SPY −0.15%
  most recent close); 3 down days for QQQ. Yields elevated. No
  index-level catalyst overnight; the day's tone hinges on claims +
  Philly Fed at 08:30 and PMIs at 09:45, plus how NVDA opens.

### No urgent catalysts on held names
- We hold no positions, so no halts, no held-name earnings shocks,
  no >5% watchlist gaps requiring an immediate ClickUp ping. No
  notification sent.

### Trade ideas drafted (NOT placed — pre-market run)

Available cash to deploy under strategy caps: up to $90,000.

```
Ticker: NVDA
Direction: long (initiate)
Thesis: Clean beat-and-raise: $81.6B rev / $1.87 EPS, Q2 guide $91B
  well above consensus, $80B buyback, dividend raise. Muted AH
  reaction = entry opportunity, not a tell of weakness.
Catalyst: FY27 Q1 print + Q2 guide (May 20).
Entry zone: $216–$220 (recent low end of post-print range).
Stop: -8% from entry (≈ $199 if filled at $216).
Target: $245 (initial), trail per strategy after +10%.
Size: 8% equity (≈ $8,000) — sized below 10% cap to leave room.
Confidence: 4/5
```

```
Ticker: AMD
Direction: long (initiate)
Thesis: $10B Taiwan AI ecosystem build-out announced today reinforces
  the data-center AI narrative on top of Q1 blowout (Rev $10.3B,
  +38% YoY; DC +57%). YTD +66%, but momentum + catalyst stack
  supports adding.
Catalyst: Taiwan AI investment headline (May 21).
Entry zone: $430–$445 on any open dip; chase only on confirmed
  strength above $450 with tight stop.
Stop: -8% from entry.
Target: 52-wk high $469 first, then $480+.
Size: 6% equity (≈ $6,000). Combined with NVDA keeps mega-cap semi
  at 14% — well under 40% sector cap.
Confidence: 4/5
```

```
Ticker: QTUM
Direction: long (initiate)
Thesis: Thematic quantum + AI semi basket riding both AI semi
  tailwind (INTC, MU, MRVL exposure) and quantum narrative (IONQ +
  peers). Lower single-name risk than IONQ outright.
Catalyst: Quantum sector momentum + AI semis. No name-specific.
Entry zone: $138–$142.
Stop: -8% from entry.
Target: re-test recent high near $145, then trail.
Size: 5% equity (≈ $5,000).
Confidence: 3/5
```

```
Ticker: IONQ
Direction: long (small starter)
Thesis: Q1 +755% YoY revenue, RPO $470M, SKYT foundry deal pending,
  photonic interconnect milestone. Speculative — keep size disciplined.
Catalyst: Continued quantum momentum; pending SKYT close.
Entry zone: stagger fills on weakness; high volatility.
Stop: -8% (firm; this name is the biggest drawdown risk).
Target: scale-out plan, no fixed target — trail.
Size: 2% equity (≈ $2,000) starter only.
Confidence: 2/5
```

```
Ticker: SPY / QQQ
Direction: WAIT
Thesis: Index has been red 3 days, yields elevated, two macro prints
  hit at 08:30 (claims + Philly Fed) before any entry decision.
  Better to react after the data than guess.
Plan: No pre-market entry. Re-evaluate after 09:45 PMIs.
```

### Open questions for the intraday session
- How does NVDA actually open vs the muted AH print? A green
  opening on a confirmed beat-and-raise validates the long thesis;
  a red open on rich expectations is a yellow flag.
- Philly Fed: a print near 0 or negative would risk-off tech and
  delay entries.
- Watch yields — further multi-month highs would pressure QQQ
  regardless of NVDA.

### ClickUp notification
**Not sent.** No urgent catalyst meeting strategy thresholds
(earnings beat/miss on a held name, halted held stock, macro shock,
or >5% gap on a watchlist name). NVDA's beat is bullish but stock
is roughly flat AH; not an emergency ping.

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
