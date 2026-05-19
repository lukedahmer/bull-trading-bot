# Research Log

Newest entries first.

---

## 2026-05-19 — Pre-market

**Session:** Pre-market research run.

**Portfolio sync:** Still **blocked**. Alpaca credentials were provided
in the session prompt, but `paper-api.alpaca.markets` is not in this
remote environment's outbound network allowlist (`curl` returns "Host
not in allowlist"). No account or positions snapshot available. Treating
the account as empty / unknown for idea-generation purposes — no
sizing, exit, or trim decisions can be made until the sync works.

**Macro tape (pre-market):**
- Index futures soft: S&P 500 ~-0.49%, Nasdaq 100 ~-0.78%, Dow
  ~-0.31%, Russell 2000 ~-0.62%.
- Risk-off tone driven by repricing of Fed rate-cut timing — BofA note
  floating that cuts may slip into 2H 2027 on sticky inflation.
- Today's data/events: Business Inventories 10:00 ET; multiple
  Treasury auctions; Fed speakers Hammack, Barr, Williams.
- No CPI/PPI/NFP/FOMC today, so the strategy's 30-min blackout rule
  does not activate.

**Watchlist updates:**

- **NVDA** — Earnings **tomorrow (May 20, 2026)**. Last print $221.12;
  intraday range $217.91–$223.33. Consensus "Strong Buy", avg PT
  ~$275. Cross-currents: reports that China AI market access is
  re-tightening after a brief reopen; ex-OpenAI-researcher hedge fund
  disclosed bearish bets on NVDA + AI-chip peers. **This is the
  dominant catalyst across the watchlist this week.** Per strategy
  rules, no new entries within 30 min of earnings on held names — we
  have none, but pre-earnings initiation on NVDA is high-variance and
  not a fit for this book.
- **AMD** — Closed May 18 at $423.41 (+0.57%); pre-market ~$421.
  Melius raised PT to $540 (from $500). CEO Lisa Su met with a
  Chinese official — incremental positive for China revenue optics.
  Strong AI/data-center momentum continues; OpenAI 6 GW partnership
  still the structural tailwind.
- **IONQ** — Q1 2026 (reported May 6): revenue $64.7M (+755% YoY),
  FY guide raised to $260–270M, RPO $470M (+554% YoY), ~60% commercial
  mix. Stock +98% from late March to early May; ~24% below 52-wk high
  $84.64. Hot but extended; mixed sell-side (11 of 14 Buy/Strong Buy,
  consensus PT ~$63.91).
- **QTUM** — May 18 close ~$143.08; -3.25% on May 15 from $147.88.
  +20.5% YTD, +77% over 1y. Top weights include INTC, MU, MRVL.
  Quantum sector still backed by ~$2.9B in announced government
  funding (DOE, NSF, intl).
- **SPY / QQQ** — Following the macro tape above; no idiosyncratic
  catalysts. Watch reaction to Fed-speaker tone for risk-on/off.

**Pre-market movers (non-watchlist, FYI only):**
- AMST +199% (NurseMagic AI deployment news)
- INM +144% (fresh 8-K)
- MTVA +51%
- RMCO -23%, GOVX -17%, SBFM -18% (capital raises / dilution).
- All are speculative micro-caps; outside Bull's strategy.

**Trade ideas drafted (NOT executed):**

```
Ticker: NVDA
Direction: long (post-earnings, only if reaction is constructive)
Thesis: AI-chip leader into print; consensus Strong Buy, PT ~$275 vs spot ~$221.
        Want the print out of the way before sizing risk.
Catalyst: Earnings 2026-05-20 (after the close, per usual cadence).
Entry zone: Defer — set after earnings reaction. Indicative: $215–225 if
            results in-line/beat with stable guide; pass on guide-down.
Stop: -8% from entry (strategy hard stop).
Target: $260 first take, $275 (street avg) second.
Size (% equity): 2% starter, room to add to 5% on follow-through.
Confidence: 3 — high-variance event, defer entry until tomorrow.
```

```
Ticker: AMD
Direction: long (starter)
Thesis: Data-center / AI accel demand, OpenAI 6 GW deal, Melius PT $540,
        China optics improving on Lisa Su meeting.
Catalyst: Continued AI infra spend; sympathy bid if NVDA prints well 5/20.
Entry zone: $415–422 pre-market dip; avoid chasing >$430.
Stop: -8% from entry.
Target: $460 (street avg), $540 stretch.
Size (% equity): 2% starter.
Confidence: 3 — wait for NVDA print before initiating; correlated risk.
```

```
Ticker: IONQ
Direction: watch / no entry yet
Thesis: Strong Q1 print and raised guide, but +98% in ~5 weeks. Want
        a pullback before initiating; size small if at all (single-name
        quantum is high-vol).
Catalyst: Sector momentum + government funding headlines.
Entry zone: $50–55 area on a sector pullback (current levels feel
            extended — confirm with live quote once Alpaca sync works).
Stop: -8% from entry.
Target: Prior 52-wk high ~$84 over multi-month horizon.
Size (% equity): 1% starter (sub-default given volatility).
Confidence: 2 — wait.
```

```
Ticker: QTUM
Direction: watch
Thesis: Diversified quantum/AI-infra exposure via ETF; reduces single-
        name risk vs IONQ. Off recent highs.
Catalyst: Same as IONQ but ETF-smoothed.
Entry zone: $140–143 if tape stabilizes post-NVDA print.
Stop: -8% from entry.
Target: Recent high ~$148 reclaim, then trail.
Size (% equity): 2%.
Confidence: 3 — sensible thematic starter once Alpaca sync is live.
```

**Plan for today:**
1. **No trades.** Strategy says pre-market run is research-only; also
   we still can't sync the account.
2. Get Alpaca host allowlisted so positions/equity can be read.
3. Defer all watchlist initiations until after NVDA earnings tomorrow.

**ClickUp notification:** Not sent. NVDA earnings is a planned, known
event (not a surprise catalyst), no held names are halted, no gap >5%
on watchlist, no macro shock. Strategy threshold not met.

---

## 2026-05-19 — Pre-market (BLOCKED) [earlier entry, preserved for history]

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
