# Research Log

Newest entries first.

---

## 2026-05-19 — Pre-market (partial: web research only)

**Session:** Pre-market.

**Credentials status:** `secrets.md` is not present in the repo and the
relevant env vars are still unset (`ALPACA_API_KEY`, `ALPACA_SECRET_KEY`,
`ALPACA_BASE_URL`, `PERPLEXITY_API_KEY`, `CLICKUP_API_TOKEN`,
`CLICKUP_LIST_ID`). Alpaca account/positions sync and ClickUp ping
remain blocked. Web research below was done with the built-in
WebSearch tool and uses only sourced facts — no fabricated portfolio
data.

### Pre-market tape (cash indices)
- SPY -0.49%, Nasdaq 100 -0.78%, Dow -0.31%, Russell 2000 -0.62%.
- Risk-off lean into NVDA earnings tomorrow; mega-cap semis softer on
  high volume; speculative micro-caps bid.

### Macro events today / this week
- **Today (Tue 5/19):** no top-tier US data print confirmed. Fed
  speakers possible but no scheduled FOMC decision.
- **Wed 5/20:** FOMC minutes (Powell's final meeting as Chair) — and
  NVDA earnings post-close. Both are dominant catalysts for our book.
- Market is pricing ~2 quarter-point Fed cuts later in 2026; NFP and
  CPI later in the cycle are the main swing factors.

### Watchlist news

**NVDA — earnings Wed 5/20 post-close.**
- Closed $221.12 (-1.3%) Mon 5/18 ahead of the print. YTD +19.2%.
- Sell-side expects another beat-and-raise on AI infra demand and Q1
  data points; consensus framing is "priced for perfection."
- Overhang: China market access — Beijing reportedly tightening again
  after a brief reopening.
- Per strategy: no new entries within 30 min of earnings for held
  names. NVDA action today should be defensive only (size/stop
  review) until the print clears.

**AMD — no near-term earnings catalyst.**
- Q1 already reported 5/5: revenue $10.253B (+37.85% YoY), non-GAAP
  EPS $1.37 beat, Data Center +57% YoY to $5.775B. Stock +16% on the
  print to new highs.
- 52-wk high $469.22; YTD +96.58%, 1-mo +51.22%.
- Meta named lead customer for 6th-gen Epyc and up to 6 GW of MI
  Instinct GPU deployment — durable bullish tailwind.
- Risk: extended; momentum trade, not a fresh-entry zone.

**IONQ — Q1 reported 5/6, strong.**
- Q1 revenue $64.7M (+755% YoY); FY guide raised to $260–270M.
  RPO +554% YoY to $470M; ~60% revenue now commercial.
- 256-qubit system in system-level testing.
- Stock +98% since 3/30 (alongside D-Wave +84%). Analyst consensus
  target $63.91, 11/14 Buy/Strong Buy — but several pieces flag
  extension risk.

**QTUM — Defiance Quantum ETF.**
- ~$140–141 range; -3.25% Fri 5/15 to $143.08, drifted lower.
- 86 holdings, modified equal-weight (~2% cap), 0.40% ER. Captures
  quantum + AI chip + ML basket — overlaps NVDA/AMD exposure.
- 5-yr total return ~202%; no single-name idiosyncratic news today.

**SPY / QQQ.**
- QQQ +11% trailing 30 days on AI-chip rally; Street targets for
  S&P 500 year-end 2026 range BofA 7,100 to Citi 7,700.
- Tomorrow's combo of FOMC minutes + NVDA print is the single biggest
  intraday vol setup of the week.

### Urgent catalyst check (would trigger ClickUp)
- Earnings beat/miss on a held name: **No** (NVDA prints tomorrow,
  not today).
- Halt on a held name: **No** known halt.
- Macro shock: **No** scheduled top-tier print today.
- Watchlist gap >5%: **No** — index futures ~0.3–0.8% down, none of
  NVDA/AMD/IONQ/QTUM/SPY/QQQ gapping >5% on what we can see.
- Decision: **no ClickUp ping** (and no creds available anyway).

### Trade ideas drafted (NO ORDERS)

All sizes are placeholders pending an Alpaca portfolio snapshot.

```
Ticker: NVDA
Direction: hold / no new add
Thesis: Earnings 5/20 post-close. Strategy bans new entries within
        30 min of earnings on held names; respect that. If we own
        NVDA, review stop placement vs implied move; do not
        chase pre-print.
Catalyst: Q1 FY27 print + guide, China commentary, data-center growth.
Entry zone: n/a (no entry today)
Stop: existing -8% from entry; tighten only if break-even rules apply.
Target: n/a
Size: 0% new
Confidence: 3/5
```

```
Ticker: AMD
Direction: hold; no add at extension
Thesis: Blowout Q1 already in the tape, name is +51% in a month.
        Wait for a pullback to the post-earnings gap rather than
        chase ATHs into NVDA print risk-off.
Catalyst: Sympathy move on NVDA print; Meta MI GPU deployment news flow.
Entry zone: defer; reassess if AMD pulls back 8–12% from ATH.
Stop: -8% from any new entry (none planned today).
Target: n/a
Size: 0% new
Confidence: 3/5
```

```
Ticker: IONQ
Direction: hold; trim candidate
Thesis: +98% in ~7 weeks; commercial mix improving but valuation
        stretched. If we hold a meaningful position, consider
        trimming back toward 2% target weight before NVDA print
        adds sector vol.
Catalyst: 256-qubit milestone, but no scheduled catalyst this week.
Entry zone: no new entry.
Stop: trailing — strategy says trail 5% below high-water mark after +20%.
Target: n/a
Size: trim to default 2% if currently overweight.
Confidence: 3/5
```

```
Ticker: QTUM
Direction: watch
Thesis: Diversified quantum/AI basket overlapping our single-name
        semi exposure; not a high-conviction add while we already
        hold (or are watching) NVDA/AMD/IONQ.
Catalyst: None idiosyncratic today.
Entry zone: defer.
Size: 0% new
Confidence: 2/5
```

```
Ticker: SPY / QQQ
Direction: watch
Thesis: Pre-market soft into NVDA print + FOMC minutes Wed. No
        macro print today. Wait for tomorrow's vol event before
        adjusting index exposure.
Catalyst: 5/20 FOMC minutes + NVDA after-the-close.
Entry zone: defer.
Size: 0% new
Confidence: 2/5
```

### Still-open blockers
- No `secrets.md`, no Alpaca creds → cannot reconcile actual
  positions vs. these ideas (sizing, sector weight, NVDA hold y/n).
- Provision the six env vars or commit a real `secrets.md` (and add
  it to `.gitignore`) to unblock the next session.

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
