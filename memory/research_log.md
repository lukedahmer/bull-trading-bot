# Research Log

Newest entries first.

---

## 2026-07-06 — Pre-market

**Session:** Pre-market. Credentials now provided in-session.

**Account snapshot (Alpaca `/v2/account`):**
- Equity: $100,000 | Cash: $100,000 | BP: $400,000 (4x)
- Status: ACTIVE, no positions, no orders.

**Macro / calendar this week:**
- **Wed Jul 8** — FOMC minutes from the June meeting (Kevin Warsh's
  first meeting as Fed Chair). Warsh has already declined to
  participate in the dot plot, so the minutes are the primary read on
  the new regime's rate path. Fed funds range currently 3.50–3.75%.
- Light macro calendar otherwise. Theme: persistent inflation,
  Section 122 tariff overhang, structural changes under new Fed
  leadership.

**Index setup (SPY / QQQ):**
- SPY still above 100- and 200-day SMAs — trend intact.
- QQQ in corrective consolidation off recent highs; momentum tilted
  mildly bearish but long-term uptrend intact.
- Semis have been the weak spot recently (memory names like MU took
  heat on Friday's jobs print + profit-taking).

**Watchlist news:**
- **NVDA** — Pre-market ~$197. Raised div to $0.25/qtr, authorized
  $80B buyback, closed $25B bond deal to fund Blackwell ramp. Poached
  a Microsoft exec (Jul 2) to run Field Operations. ~+13% YTD.
  Narrative still "AI infra leader" despite bubble chatter.
- **AMD** — Ran to record highs >$558 in mid-June, market cap
  cracked $900B for the first time. Approx +150% YTD. Extended and
  arguably frothy; needs a pullback for a clean entry.
- **IONQ** — Strong Buy consensus, avg 12-mo PT ~$69 (~+41%). Q1
  FY26 revenue +755% YoY to $64.7M. Announced $1.5M Archer Materials
  deal (Jul 1) for Australian sovereign-quantum access. ID Quantique
  Clavis XG Multiplex QKD product launched June.
- **QTUM** (Defiance Quantum ETF) — Rides IONQ + broader quantum
  basket. No specific ETF news; tracks the theme.
- **SPY / QQQ** — See index setup above; no idiosyncratic news.

**No urgent catalyst on held names** (we hold none), so no ClickUp
ping is warranted. No earnings for watchlist tickers today. No FOMC
event within 30-minute blackout window.

**Trade ideas drafted (NOT executed — pre-market run):**

```
Ticker: SPY
Direction: long (initial core)
Thesis: Regime filter is on — SPY above 100/200 SMA, trend intact.
        Use as the first building block ahead of a light-calendar
        week and FOMC minutes Wednesday.
Catalyst: FOMC minutes Wed; otherwise price action / rotation.
Entry zone: market open, VWAP-follow first 30 min after open.
Stop: -8% hard stop per strategy (soft: below prior swing low).
Target: no fixed target — trail per strategy (BE after +10%, 5%
        below HWM after +20%).
Size: 4% of equity (~$4,000, ~7 shares near current levels).
Confidence: 3/5 — vanilla trend-following starter.
```

```
Ticker: QQQ
Direction: long (initial core)
Thesis: Broad tech beta while individual names (NVDA extended,
        AMD frothy) are hard to time. QQQ consolidation lets us
        add exposure without picking a single semi.
Catalyst: FOMC minutes Wed; semis stabilization.
Entry zone: intraday pullback to recent consolidation low.
Stop: -8% hard stop.
Target: trail per strategy.
Size: 3% of equity (~$3,000).
Confidence: 3/5.
```

```
Ticker: NVDA
Direction: long (starter)
Thesis: $80B buyback + dividend raise + Blackwell ramp = capital-
        return + growth story intact. Pre-market ~$197 not
        extended vs. AMD's parabolic run.
Catalyst: Buyback flow, Blackwell shipments, AI capex prints.
Entry zone: $195–$198 zone; scale in.
Stop: -8% hard stop (~$182). Soft: close below $190.
Target: trail; look for $215+ into next earnings.
Size: 2% of equity (~$2,000, ~10 shares) as starter, room to add.
Confidence: 3/5.
```

```
Ticker: IONQ
Direction: long (small, thematic)
Thesis: Revenue inflection (+755% YoY), Strong Buy consensus,
        active enterprise/sovereign deals. Highest-quality name
        in the quantum basket.
Catalyst: New enterprise contracts, Tempo roadmap updates.
Entry zone: pullback preferred; don't chase a gap.
Stop: -8% hard stop — this name is volatile, size accordingly.
Target: trail; analyst avg PT ~$69.
Size: 1% of equity (~$1,000) — thematic starter only.
Confidence: 2/5 — high volatility, catalyst-dependent.
```

**Passed on today:**
- **AMD** — Up ~150% YTD, market cap >$900B, up against recent
  ATHs. Wait for a pullback or consolidation break; do not chase.
- **QTUM** — Redundant vs. IONQ starter; can add later for
  diversification if IONQ works.

**Next session:** Intraday (post-open). Reassess index setup on
first 30-min bar, then decide whether to execute SPY/QQQ starters.

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
