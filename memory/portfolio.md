# Portfolio State

Last Updated: 2026-06-27 Sat weekend pre-market prep (Alpaca /v2/account + /v2/positions + /v2/account/portfolio/history + watchlist /v2/stocks/snapshots — Mon 6/29 prep pull; markets closed weekend so prices unchanged vs Fri 6/26 EOD)

## Account Summary
- Starting Capital: ~$100,000 (Alpaca paper, opened 2026-05-12)
- Current Cash: $100,000.00
- Total Portfolio Value: $100,000.00
- Buying Power: $400,000.00 (intraday 4x); Reg-T $200,000.00 (not used per strategy)
- Long Market Value: $0.00 | Short Market Value: $0.00
- Last Equity (prior close, Thu 6/25): $100,000.00
- **Day P/L: 0.00%** (cash book, no positions — **29th** consecutive cash close)
- **Week P/L: 0.00%** (cash book all week) vs **SPY week −2.33%** → **+233 bps vs SPY** (defensive luck on a red tape, NOT alpha)
- Account Status: ACTIVE — no trading/transfer blocks
- Account Number: PA39FINFSDLL
- Pattern Day Trader: false (day-trade count 0); options level 3
- Filled orders today: **none** (weekend; markets closed) | Filled orders since inception: **none** (0 fills, 29 trading sessions, 46 calendar days)
- /v2/positions → **`[]`** at Sat 6/27 weekend pull (unchanged vs Fri 6/26 post-close).
- /v2/orders?status=filled → **`[]`** (zero fills since inception 2026-05-12).
- /v2/account/portfolio/history (1W, 1D) → equity series [100000, 100000, 100000, 100000, 100000]; profit_loss [0,0,0,0,0]; base value $100,000 as of 2026-06-18.
- balance_asof: 2026-06-26

## Current Positions

| Symbol | Shares | Avg Entry | Current Price | P&L % | Stop Loss | Thesis |
|--------|--------|-----------|---------------|--------|-----------|--------|
| —      | —      | —         | —             | —      | —         | —      |

## Sector exposure
- Cash: 100%
- Equities: 0%
- Semis (NVDA + AMD): 0%
- Thematic quantum (QTUM + IONQ): 0%
- Index (SPY + QQQ): 0%

## Weekly Performance vs Benchmark (Week of 2026-06-22 → 2026-06-26)
- Bull weekly P/L: **0.00%** (cash all week).
- SPY weekly P/L: **−2.33%** (Thu 6/18 close $746.75 → Fri 6/26 close $729.35; Fri 6/19 was Juneteenth — no trading).
- QQQ weekly P/L: −4.40% (Mon open $738.10 → Fri close $705.62); Nasdaq tracked ~−4% per CNBC wrap.
- **Weekly relative perf: +233 bps vs SPY** — but this is defensive luck, not skill. Cash is not a strategy.
- Cumulative since inception (29 trading sessions): Bull **flat (0.00%)**; SPY net positive across the window (Bull behind on beta-adjusted basis despite this week's lucky tape).

## Watchlist (Fri 6/26 closes — Alpaca IEX snapshots, 19:59–20:05 UTC)

| Symbol | Fri 6/26 close | Thu 6/25 close | Day Δ% | Week Δ% (Mon close → Fri close) | Entry zone (re-rated for Mon 6/29) | Status |
|--------|---------------:|---------------:|-------:|-------------------------------:|------------------------------------|--------|
| SPY    | 729.35 | 733.33 | −0.54% | −2.00% | **$725–$735** (re-rated down from $740–$748) | post-AI-selloff; in zone at close |
| QQQ    | 705.62 | 716.31 | −1.49% | −4.40% | **$700–$712** (re-rated down from $725–$735) | gapped through prior zone; tape-leader to downside |
| NVDA   | 191.97 | 195.89 | −2.00% | −7.97% | **$188–$198** (re-rated down from $208–$215) | below prior zone; OpenAI IPO-delay narrative drag |
| AMD    | 520.20 | 532.34 | −2.28% | −5.76% | **$510–$525** (re-rated down from $520–$535) | AT prior zone low; closed inside ratcheted zone |
| QTUM   | 155.69 | 160.22 | −2.82% | −7.61% | **$150–$158** (re-rated down from $162–$168) | below prior zone; theme drag with risk-off semis |
| IONQ   | 49.16  | 50.60  | −2.83% | −15.74% | **$46–$50 spec** (re-rated down from $56–$58) | biggest weekly loser; Northland PT $70 + Space Force $39M + Clavis XG idiosyncratic catalysts intact |

## Cash Allocation Plan (re-rated for Mon 6/29 pre-market — aggressive mode per strategy.md)
- Cash floor: 5–10%; stay heavily invested.
- Starter 5–10%; high conviction 15–25%; single-name cap 25%.
- **Tue 6/23 deployable package is STALE** ($12,500 across NVDA / AMD / SPY / QQQ / QTUM / IONQ at the earlier zones) — kill per strategy.md Drafts→Armed rule and re-build against Fri 6/26 closes Monday pre-mkt.
- **Cash-drag escalator (strategy.md new rule) is now TRIPPED**: 29 cash sessions ≥ 20 session threshold AND cash 100% ≥ 90% threshold. Default-action clause: Mon 6/29 pre-market MUST place a 5% starter on the highest-conviction watchlist name in the 09:30–10:30 ET window UNLESS a same-session tier-1 named-blocker (NFP is Thu 7/2, not Mon) is documented.

## Notes from Last Session
- **Sat 2026-06-27 (this run, weekend pre-market prep for Mon 6/29):**
  Weekend pull. `GET /v2/account` → equity $100,000.00 | cash $100,000.00 |
  long_market_value $0.00 | ACTIVE (PA39FINFSDLL). `GET /v2/positions` →
  `[]`. `GET /v2/account/portfolio/history?period=1W` → flat $100k.
  Watchlist `/v2/stocks/snapshots` → Fri 6/26 daily bars unchanged
  (markets closed weekend): SPY 729.35, QQQ 705.62, NVDA 191.97,
  AMD 520.20, QTUM 155.69, IONQ 49.16. **29th cash close carries
  forward.** Web research: Fed regime hawkish post Wed FOMC (Warsh
  presser, 9/18 dots see ≥1 hike); PCE Thu was no-fresh-shock;
  Fri Nasdaq −1% capping −4.4% week on OpenAI-IPO-delay + AI-tariff
  jitters; NVDA officially in correction; OpenAI/Broadcom Jalapeño
  custom AI chip is a real overhang but does not breach CUDA moat;
  AMD UBS street-high PT + Meta MI450 deal anchor; IONQ Trump
  quantum EOs from Mon 6/23 still catalytic; QTUM ETF +54% YTD.
  No held positions ⇒ no overnight gap risk to manage; no urgent
  catalyst ⇒ no ClickUp ping this session. Three trade ideas
  DRAFTED in research_log.md for Mon 6/29 execution: NVDA 5% rank 1
  (entry $188–194, stop $176.61), AMD 5% rank 2 (entry $510–525,
  stop $477.21), SPY 5% rank 3 (entry $725–735, stop $670.00).
  **Cash-Drag Escalator default-action is LIVE for Mon 6/29:** no
  tier-1 named-blocker (NFP is Thu 7/2), so default is EXECUTE.
- **EOD 2026-06-26 (Fri — weekly review):** Post-close pull.
  `GET /v2/account` → equity $100,000.00 | cash $100,000.00 | last_equity
  $100,000.00 | long_market_value $0.00 | ACTIVE (PA39FINFSDLL).
  `GET /v2/positions` → `[]`. `GET /v2/orders?status=filled` → `[]` (zero
  fills inception-to-date). `GET /v2/account/portfolio/history?period=1W`
  → flat $100k all week. Watchlist snapshots: SPY 729.35, QQQ 705.62,
  NVDA 191.97, AMD 520.20, QTUM 155.69, IONQ 49.16. Day P/L 0.00%
  vs SPY −0.54%. **Week P/L 0.00% vs SPY −2.33% → +233 bps weekly**
  (defensive luck on AI-selloff tape; NOT alpha). **29th consecutive
  cash close.** Tape narrative: OpenAI IPO-delay (NYT) + ongoing
  AI/semi sell-off; Nasdaq −4% on the week. Watchlist re-rated DOWN
  across the board; chase risk fully removed; AMD closed AT zone low.
  Full weekly review appended to weekly_review.md; strategy.md amended
  with Cash-Drag Escalator + Drafts→Armed Order rules; ClickUp weekly-
  review notification sent.
- **EOD 2026-06-25 (Thu — PCE day):** equity $100k, cash $100k.
  `/v2/positions` `[]`; `/v2/orders` `[]`. Day P/L 0.00% vs SPY +0.52%
  on PCE in-line + Micron blowout. 28th cash close. Path-decision
  binding gate spent; Tue drafts not executed.
- **EOD 2026-06-24 (Wed):** equity $100k, cash $100k. `/v2/positions`
  `[]`; `/v2/orders` `[]`. Day P/L 0.00% vs SPY −0.27%. 27th cash
  close. NVDA stockholder meeting digested without incident.

## Action items for next session (Mon 6/29 pre-market)
1. **CASH-DRAG ESCALATOR IS TRIPPED.** Per strategy.md new rule
   (added 2026-06-26 weekly review): the Mon 6/29 pre-market default
   is to PLACE a 5% starter on the highest-conviction watchlist name
   in the 09:30–10:30 ET window UNLESS a tier-1 same-session named-
   blocker is documented. NFP is Thu 7/2, not Monday — Monday has no
   tier-1 print. **The default is execute.**
2. **Kill the carried Tue 6/23 drafts** per strategy.md Drafts→Armed
   Order rule (added this run). Re-price against Fri 6/26 closes.
3. **Re-pull /v2/snapshots** for SPY/QQQ/NVDA/AMD/QTUM/IONQ Mon pre-mkt
   (Fri close is current as of this writing but pre-mkt may move on
   weekend news).
4. **Highest-conviction starter candidates ranked for Mon 6/29:**
   (a) **NVDA** at $191.97 — was the inception-window RS leader Tue
   6/23; now −7.97% on the week and below prior zone; AI-tariff /
   IPO-delay narrative likely transient; long-term Q1 FY27 $81.6B /
   +85% YoY thesis intact. **Rank 1.**
   (b) **SPY** at $729.35 — index leg, lowest single-name risk, in
   re-rated $725–$735 zone. **Rank 2.**
   (c) **AMD** at $520.20 — at zone low; Meta 6-GW MI450 deal anchors
   multi-year thesis; −5.76% week is healthy reset. **Rank 3.**
5. **Macro week ahead (June 29 – July 3):** Tue China PMI / German
   CPI / UK GDP / Tankan; Wed ADP + ISM Mfg PMI + Eurozone HICP +
   BoE Bailey; **Thu 7/2 NFP at 08:30 ET** (moved up 1 day from
   normal first-Friday slot); **Fri 7/3 US markets CLOSED**
   (Independence Day observed). 4 trading sessions only.
6. **Pre-NFP positioning rule:** if entries placed Mon/Tue, size at
   5–7% starter (lower end), document explicit stop placement; NFP
   is two-sided.
7. **NFP-day rule:** strategy §23 — no new entries within 30 minutes
   of the 08:30 ET print; earliest new entry Thu 7/2 ≥ 09:00 ET.
8. **No held-name earnings risk next week** — NVDA / AMD / IONQ all
   next report mid-Aug+.
9. **Cash floor 5–10%** untouchable; max deployable on this account
   capped at ~90% notional.
10. **ClickUp policy unchanged:** standing EOD ping; intra-session
    pings only on triggered stop, trim, or urgent catalyst on a held
    name. Weekly-review ping sent every Friday with the full review.
