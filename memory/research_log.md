# Research Log

Newest entries first.

---

## 2026-06-29 — Pre-market

**Session:** Pre-market. Account live on Alpaca paper (`PA39FINFSDLL`).

### Account snapshot
- Equity: $100,000 — cash 100%, no positions.
- Buying power: $400,000 (4x margin available, will not use per strategy).
- Last equity = current equity (no overnight delta).

### Macro setup — week of Jun 29–Jul 3, 2026
- **Geopolitics:** US-Iran ceasefire holding after weekend strikes; MoU signed
  for ≥60-day truce; Strait of Hormuz reopening, Gulf exports back to ~75%
  of prewar. Risk-on bias into the open.
- **Futures (pre-market):** NQ +1.0%, ES +0.7%, YM +0.4%.
- **Oil:** WTI ~ $69, down ~4% Friday and ~20% off 2026 highs. Tail risk
  fading — bullish for risk assets.
- **Holiday-shortened week:** Markets closed Fri Jul 4.
- **Calendar:**
  - Thu Jul 2 — June Non-Farm Payrolls (NFP) 08:30 ET. Strategy rule:
    no new entries 30 min around the print.
  - Core PCE for May likely already out late June; June Core PCE is
    Jul 30, not this week.
  - Fed June SEP revised 2026 core inflation up to 3.3% (hawkish drift).

### Holdings news
- None — account is flat.

### Watchlist updates

**NVDA** — Friday close $192.53 (-1.64%), 5th consecutive down day. Pre-market
$195.15 (+1.36%). 52-wk range $151.49–$236.54. Consensus Strong Buy, avg
analyst target ~$300. Short/long MAs still bearish; oversold-bounce setup
into a risk-on open.

**AMD** — ~$521–$532 area. UBS lifted target to $670 from $455 on data-center
acceleration (Q1 DC revenue +57% YoY to $5.8B). Next earnings Aug 4. Strong
Buy consensus. Already extended near analyst average — not a chase here.

**IONQ** — FY2026 revenue guide raised to $260–$270M; backlog $470M; Q1 rev
$64.7M (+755% YoY) but still pre-profit. Achieved photonic interconnect of
two trapped-ion systems and shipped 256-qubit chip-based system to U. of
Cambridge. Highly speculative; no fresh urgent catalyst overnight.

**QTUM (Defiance Quantum ETF)** — +54% YTD vs SPY +11%. AUM $6B. Equal-weight
70–80 names, 0.40% ER. Strong momentum but chasing the highs; equal-weight
structure mitigates single-name blow-up risk.

**SPY / QQQ** — Both red last week; QQQ ~$710 area, recovering pre-market on
ceasefire news. AI-capex narrative intact (hyperscaler '26 capex
projected >$650B). MACD on QQQ turned negative June 4, momentum mixed.

### Trade ideas drafted (no execution this run)

```
Ticker: SPY
Direction: long (starter)
Thesis: Ceasefire-driven risk-on reversal; flat account needs core
  exposure before NFP risk Thursday.
Catalyst: US-Iran MoU + oil collapse to $69; futures gap up.
Entry zone: scale-in on open, $605–$612 estimated area.
Stop: -8% from VWAP entry (per strategy hard stop).
Target: prior recent highs; trim into strength.
Size: 2% equity = $2,000 notional (≈ 3 shares).
Confidence: 3/5.
```

```
Ticker: QQQ
Direction: long (starter)
Thesis: AI/semis-led bounce; geopolitical de-risk pulls high-beta back.
Catalyst: NQ futures +1.0% pre-market; risk-on tape.
Entry zone: scale-in, ~$705–$715.
Stop: -8% from entry.
Target: reclaim of pre-pullback range.
Size: 2% equity = $2,000 notional.
Confidence: 3/5.
```

```
Ticker: NVDA
Direction: long (starter)
Thesis: 5-day losing streak into a risk-on open; consensus Strong Buy,
  avg target ~$300 vs spot ~$195; AI capex thesis unbroken.
Catalyst: Iran de-escalation lifts high-beta; oversold bounce.
Entry zone: $192–$196.
Stop: $179 (≈ -8%).
Target: $210–$220 retracement; trail per strategy after +10%.
Size: 2% equity = $2,000 notional (≈ 10 shares).
Confidence: 3/5.
```

```
Ticker: AMD
Direction: watch (defer)
Thesis: UBS $670 target is constructive but spot is already extended
  near street avg ($500). Wait for pullback to ~$480 or earnings setup.
Catalyst: Aug 4 earnings.
Entry zone: not chasing here.
Confidence: 2/5.
```

```
Ticker: IONQ
Direction: watch (defer)
Thesis: Strong tech milestones + raised guide, but speculative; no
  urgent overnight catalyst, and position would be at high vol vs.
  fresh account.
Confidence: 2/5.
```

```
Ticker: QTUM
Direction: watch (small starter candidate)
Thesis: +54% YTD + equal-weight structure = clean quantum/AI theme
  exposure; but chasing strength. Prefer dip-buy.
Entry zone: dip toward $150–$155 if it comes.
Size: 1–2% equity if entry triggers.
Confidence: 2/5.
```

### Urgent catalyst check (per strategy §7)
- No held name halted, no earnings beat/miss on a held name, no >5% gap
  on watchlist (NVDA +1.4%, AMD flat, etc.), no FOMC/CPI/NFP/PPI today.
- **No ClickUp ping sent.**

### Next step
- Intraday session: evaluate open print and consider scaling into SPY +
  QQQ starters, plus NVDA on confirmation. Avoid new entries within 30
  min of Thu Jul 2 NFP.

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
