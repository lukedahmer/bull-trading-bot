# Research Log

Newest entries first.

---

## 2026-06-20 — Pre-market (Sat, US markets closed)

**Session:** Pre-market routine. NOTE: today is Saturday and Friday
2026-06-19 was Juneteenth (US equity markets closed). Next regular
session is Monday 2026-06-22. Research below reflects last-close data
(Thu 2026-06-18) and weekend news flow.

### Account snapshot (Alpaca paper, PA39FINFSDLL)
- Equity: **$100,000** | Cash: **$100,000** | BP: **$400,000** (4x)
- No open positions. Full dry powder. PDT: false. Day trades: 0.

### Macro / calendar
- **Fed:** Market pricing ~2x 25bp cuts across 2026; policy band
  3.50–3.75%. No FOMC this week, but watch Fed speakers for
  rate-path color.
- **Inflation backdrop:** CPI prints have been running 2.9–3.2%
  — sticky but not accelerating.
- **Geopolitics:** Middle East tensions and supply-chain risk
  still flagged as headwinds; some easing has supported the chip
  rally narrative.
- **Technicals (QQQ):** +11% past 30d on AI-chip leadership, but
  MACD histogram flipped negative 2026-06-04 → near-term caution
  flag despite parabolic April–June run.

### Watchlist notes
- **NVDA** — Last close ~ $210.69 (prev $204.65); range $206.50–$211.39.
  Market cap ~$5.17T, P/E ~32.3. Consensus Strong Buy (59 buy, 1 sell).
  **Risk:** AMZN selling its custom AI chips externally + GOOG $3.2B
  AI data-center build = competitive overhang on the merchant-AI-silicon
  monopoly thesis. Still the cleanest AI infra long.
- **AMD** — Up ~118% YTD 2026; quadrupled over last year. Q1 rev
  $10.25B (+38% YoY), Data Center +57% to $5.8B. Catalysts: Rackspace
  multi-year 30MW AI-compute deal through 2028; $10B Taiwan
  packaging/assembly investment announced 2026-05-21. Same AMZN custom-
  chip threat. Strong momentum but extended.
- **IONQ** — Rallied ~13.6% on commercialization optimism. FY25 rev
  ~$130M (first pure-play quantum >$100M). 256-qubit system sold to
  Cambridge in Q1; UK NQCC PoC. Median analyst PT $65. Cash burn and
  P/S multiples still extreme — sentiment-driven name, size small.
- **QTUM** — +47.39% YTD vs QQQ +17.42%; +82.93% TTM vs QQQ +35.17%.
  AUM > $5.6B, 86 holdings. Top weights: NVDA 8.14%, AAPL 7.10%,
  MSFT 4.74%. Strong vehicle to express the quantum + semi-AI theme
  without single-name blowup risk. Watch competing QTUP launch.
- **SPY** — Index proxy; broad-tape bullrun intact since April but
  approaching resistance.
- **QQQ** — See macro/technicals above. MACD warning + extension =
  prefer dips, not breakouts, for initiating.

### Trade ideas (DRAFT — no orders placed)

```
Ticker: QTUM
Direction: long (starter)
Thesis: Diversified expression of AI-semi + quantum themes;
  outperforming QQQ by ~30pp YTD with broader holding base
  than IONQ. Vehicle to put capital to work without single-
  name binary risk on Monday open.
Catalyst: Continued AI capex (hyperscalers ~$650B/yr 2026)
  + quantum milestone wave; no single-stock event risk.
Entry zone: Monday 06-22 open or first 5–10 min VWAP pullback.
Stop: -8% from entry (strategy hard stop).
Target: +20% (then trail per strategy rule).
Size: 2% equity = ~$2,000.
Confidence: 3/5
```

```
Ticker: NVDA
Direction: long (starter)
Thesis: AI infra leader, Strong Buy consensus, 32x P/E not
  unreasonable for current growth. Use weakness from AMZN/GOOG
  chip-competition headlines as entry.
Catalyst: Hyperscaler capex; next earnings is the binary risk
  to clear before sizing up.
Entry zone: $204–208 (recent support / prev close pivot).
Stop: -8% (~$190 from $207).
Target: $230+ (gradual trail).
Size: 2% equity = ~$2,000 starter.
Confidence: 3/5
```

```
Ticker: IONQ
Direction: long (small speculative)
Thesis: Pure-play quantum leader, only one with >$100M rev;
  strong contract pipeline. Pair with NVDA/QTUM for theme
  exposure.
Catalyst: 256-qubit demo this year; further sovereign /
  university deals.
Entry zone: monitor Monday open — if gaps up >5%, skip.
Stop: -8% hard.
Target: leave to trail.
Size: 1% equity = ~$1,000 (smaller due to volatility / cash burn).
Confidence: 2/5
```

### Decision for Monday 2026-06-22
- Do **not** front-run the open on Saturday. Re-validate at
  Monday pre-market session with fresh quotes and overnight tape.
- If QQQ gaps down >1% on Monday open, prioritize QTUM starter
  over single-name NVDA. If gaps up >1%, wait for first
  pullback before deploying any capital.
- No new positions inside 30 min of any scheduled macro print
  this week (none currently flagged for Mon-Tue, will reverify).

### ClickUp notification
- **None sent.** No urgent catalyst: no positions held, no
  earnings on watchlist, no halts, no macro shock, US markets
  closed for the session anyway.

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
