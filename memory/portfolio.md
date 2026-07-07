# Portfolio State

Last Updated: 2026-07-07 Tue pre-market ~02:37 ET — **4 market buy orders QUEUED for 09:30 ET open** (IONQ 64 sh, QTUM 32 sh, NVDA 25 sh, SPY 6 sh = $17,238 / 17.24% deploy expected at Mon 7/6 close bids); Mon 7/6 pre-market/EOD both UNLOGGED (5th and 6th log-gap sessions — Mon arm plan NEVER ARMED); re-priced Sun 7/5 draft zones vs Mon 7/6 close bids (feed=iex) — all 4 above their kill-triggers (IONQ $46.64 > $46, QTUM $151.87 > $146, NVDA $195.39 > $182, SPY $751.48 > $720), so per the stated re-price rule ALL 4 armed; **SPY $751 is +0.47% above zone top $748** but under the +1.45% chase-kill precedent from 7/2, so armed rather than killed; **AMD KILL still stands** (no re-arm); 10% trailing stops attempted with `position_intent: sell_to_close` and correctly REJECTED (HTTP 422 — no position to close, safe — no accidental short); trailing stops to be armed by first post-open session that sees filled positions; **ClickUp ping sent** (4 trades placed queued for open).

## Account Summary
- Starting Capital: ~$100,000 (Alpaca paper, opened 2026-05-12)
- Current Cash: $100,000.00 (pre-fill; expected ~$82,761 post-open fills at Mon close bids)
- Total Portfolio Value: $100,000.00 (pre-fill)
- Buying Power: $400,000.00 (intraday 4x); Reg-T $200,000.00 (not used per strategy)
- Long Market Value: $0.00 pre-fill | Short Market Value: $0.00
- Last Equity (prior close, Mon 7/6): $100,000.00
- **Day P/L: 0.00%** (pre-open pull — no fills yet)
- **Session-log gap grew:** Thu 7/2 EOD + Mon 7/6 pre + Mon 7/6 EOD all still missing (6-session gap now: Tue 6/30 pre, Wed 7/1 pre, Wed 7/1 EOD, Thu 7/2 EOD, Mon 7/6 pre, Mon 7/6 EOD). **Weekly review Mon 7/6 EOD MISSED — rolls to Tue 7/7 EOD.**
- **Market status TODAY (Tue 7/7 ~02:37 ET pre-market):** CLOSED — pre-market. `GET /v2/clock` this session: `is_open: false`, `next_open 2026-07-07T09:30:00-04:00`, timestamp `2026-07-07T02:34:25-04:00`. **User task-template said "market just opened"; per Alpaca clock, market opens in ~7 hours.** Market orders were still accepted (Alpaca queues day market orders received while closed and executes at next open).
- Account Status: ACTIVE — no trading/transfer blocks
- Account Number: PA39FINFSDLL
- Pattern Day Trader: false (day-trade count 0); options level 3 (unused per strategy); shorting_enabled: true (reason `position_intent: sell_to_close` was used on the trailing-stop attempt — see note above)
- Filled orders today: **none yet** (4 queued) | Filled orders since inception: **none** (0 fills across 36 trading sessions since 2026-05-12; Mon 7/6 counts as 36th cash open — plan never armed)
- `GET /v2/positions` → **`[]`** at 02:37 ET pre-open pull.
- `GET /v2/orders?status=all&limit=20` → **`[]`** at 02:37 ET pre-open pull, confirming Mon 7/6 arm never happened.
- balance_asof: 2026-07-02 (still unchanged since Thu 7/2 — Fri closed + weekend + Mon 7/6 no fills)

## Current Positions (pre-fill; queued orders below)

| Symbol | Shares | Avg Entry | Current Price | P&L % | Stop Loss | Thesis |
|--------|--------|-----------|---------------|--------|-----------|--------|
| —      | —      | —         | —             | —      | —         | —      |

## Queued Orders (submitted 2026-07-07 02:37 ET, execute at 09:30 ET open)

| Symbol | Side | Qty | Type | TIF | Order ID | Client Order ID | Est. Fill ($) | Est. Weight | Trailing Stop |
|--------|------|----:|------|-----|----------|-----------------|--------------:|------------:|---------------|
| IONQ   | buy  | 64  | market | day | d7a4c185-f8c1-4ded-bf40-26f5a24c4dae | dexter-20260707-ionq-open | ~$2,985 (@ $46.64) | ~2.99% | 10% GTC — arm post-fill |
| QTUM   | buy  | 32  | market | day | d6fc898a-fff0-4281-acfa-60cac43f6d11 | dexter-20260707-qtum-open | ~$4,860 (@ $151.87) | ~4.86% | 10% GTC — arm post-fill |
| NVDA   | buy  | 25  | market | day | 7272c566-91d3-448e-aa66-017f56e78bb9 | dexter-20260707-nvda-open | ~$4,885 (@ $195.39) | ~4.88% | 10% GTC — arm post-fill |
| SPY    | buy  |  6  | market | day | a0467eb0-2d64-4528-9af5-cf1de01f166c | dexter-20260707-spy-open  | ~$4,509 (@ $751.48) | ~4.51% | 10% GTC — arm post-fill |
| **Total** | — | — | — | — | — | — | **~$17,239** | **~17.24%** | — |

- Guardrail check: max single position 4.88% ≤ 10% task cap ✓ | expected cash post-fill 82.76% ≥ 20% task floor ✓ | no leverage / no options / no shorts / no crypto.
- Sector split (post-fill): quantum-theme (QTUM+IONQ) ~7.85%, semis (NVDA) ~4.88%, broad index (SPY) ~4.51% — well under the 40% sector cap from strategy §Position sizing.

## Sector exposure (pre-fill / post-fill projection)
- Cash: 100% pre-fill → ~82.76% post-fill
- Equities: 0% pre-fill → ~17.24% post-fill
- Semis (NVDA + AMD): 0% pre-fill → ~4.88% post-fill (NVDA only; AMD still KILLED)
- Thematic quantum (QTUM + IONQ): 0% pre-fill → ~7.85% post-fill
- Index (SPY + QQQ): 0% pre-fill → ~4.51% post-fill (SPY only)

## Watchlist (Thu 7/2 close — actual Alpaca 1Day bars, feed=iex)

| Symbol | Thu 7/2 close | Wed 7/1 close | Δ 7/1→7/2 | 7/2 intraday low | Post-7/2 draft zone | Status |
|--------|---------------:|---------------:|-----------:|------------------:|---------------------|--------|
| NVDA   | 194.51        | 197.54        | −1.53%     | 192.35            | $192–$198           | **HOLD-LIVE for Mon 7/6** (inside zone) |
| AMD    | 518.25        | 540.89        | −4.19%     | **506.33**        | $520–$540 (killed)  | **KILLED** — $510 invalidation broken intraday |
| SPY    | 744.86        | 745.665       | −0.11%     | 740.04            | $740–$748           | **HOLD-LIVE for Mon 7/6** (inside zone) |
| QQQ    | 712.53        | 725.32        | −1.76%     | 707.61            | (no draft)          | tracking; SPY preferred index expression |
| QTUM   | 155.13        | 160.28        | −3.21%     | 153.62            | $148–$156 (re-drawn)| **HOLD-LIVE for Mon 7/6** (re-priced from $156–$162) |
| IONQ   | 49.165        | 51.44         | −4.42%     | 48.19             | $48–$52             | **HOLD-LIVE for Mon 7/6** (inside zone, lower end) |

## Cash Allocation Plan (arm on Mon 7/6 pre-market, contingent on gap check + weekend headlines)
- **Four candidate drafts survive** the 7/2-close re-price and are HOLD-LIVE for Mon 7/6 pre-market arming as limit orders in the 09:30–10:30 ET Cash-Drag Escalator window:
  - **IONQ 3%** (~$3,000, ~61 sh at $49). Stop $45.24. Target $65–$70. Zacks #4 Sell is the offset.
  - **QTUM 5%** (~$5,000, ~32 sh at $155). Stop $142.72. Target $180–$200. Cleanest quantum-theme wrapper.
  - **NVDA 5%** (~$5,000, ~26 sh at $194). Stop $178.95. Target $240 initial / $301 consensus PT. Room to add to 15% on confirmation.
  - **SPY 5%** (~$5,000, ~7 sh at $744). Stop $684.87. Benchmark leg.
- **Aggregate Mon 7/6 deploy target: 18% ($18,000)** → 82% cash remaining, well above aggressive-mode 5–10% floor.
- Sector split: semis 5% (NVDA), thematic quantum 8% (QTUM+IONQ), index 5% (SPY).
- **Single-name cap 25% respected** (max 5% starter on any name).
- **AMD KILLED** — the drafted $520–$540 zone included a "$510 breaks = invalidate" condition; Thu 7/2 intraday low $506.33 tripped it. Re-drafting requires a fresh base candle in $490–$510 and is queued for Mon 7/6 EOD or Tue 7/7 pre-market, NOT for the Mon 7/6 open.
- **Contingency to abort all Mon 7/6 arms** (Sun 7/5 status noted):
  - (a) SPY/QQQ gap-open > 2% down at Mon open → **CHECK AT MON PRE-MARKET**
  - (b) Fresh Meta / hyperscaler capex-cut headline → **CLEARED** (no weekend headlines; Meta capex RAISED $10B)
  - (c) EU tariff shock (Sat 7/4 add) → **CLEARED** — deal implemented on schedule; 15% EU→US, 0% US→EU regime in force
  - (d) Kospi / SK Hynix down 5%+ in Sun-night Asia session → **RESIDUAL** — Kospi Fri 7/3 closed +5.76%; mechanical hurdle now high but still watch ~19–20 ET Sun open
- **Cash-Drag Escalator** (strategy §25): TRIPPED (33-session count carried). Today's default-action is BLOCKED by market closure — documented per rule. Mon 7/6 pre-market is the next operative session; the 4-starter Monday plan above IS the escalator response for that session.

## Notes from Last Session
- **Tue 2026-07-07 pre-market ~02:37 ET (this run) — 4 QUEUED ORDERS.**
  Ran under the user's daily "market just opened" task-template, but
  Alpaca `GET /v2/clock` returned `is_open: false`, `next_open
  2026-07-07T09:30:00-04:00`, timestamp `2026-07-07T02:34:25-04:00` —
  the harness fired ~7 hours ahead of the intended intraday window.
  **Mon 7/6 pre-market + Mon 7/6 EOD were both UNLOGGED and the arm
  plan was NEVER ARMED** — `GET /v2/orders?status=all` returned `[]` at
  this session's pull, confirming the 4-starter Mon 7/6 arm plan
  documented in the Sun 7/5 pass silently rolled forward. This is the
  **fifth and sixth log-gap sessions** and a third independent process
  failure (structural, not behavioral). Weekly review Mon 7/6 EOD
  MISSED — rolls to Tue 7/7 EOD.

  Applied the Drafts→Armed Order Rule (strategy §26) to the 4 carried
  drafts, re-priced against Mon 7/6 close bids (feed=iex): **IONQ
  $46.64** (still > $46 kill trigger, below zone $48–$52 but below-zone
  = IMPROVED entry not chase); **QTUM $151.87** (inside zone $148–$156,
  below midpoint $152 — clean); **NVDA $195.39** (inside zone $192–$198,
  near midpoint $195 — clean); **SPY $751.48** (above zone top $748 by
  0.47%, kill trigger <$720 not tripped; under the 7/2 chase-kill
  precedent of +1.45% premium — armed rather than killed). Per the
  research-log-stated re-price rule as written ("if IONQ still >$46,
  QTUM still >$146, NVDA still >$182, SPY still >$720, arm all four"),
  all 4 armed. AMD KILL still stands — no re-draft (Advancing AI event
  Jul 22–23 remains queued).

  **Order class chosen: plain market TIF=day** (per user task
  instruction "type: market, time_in_force: day"). Alpaca queued all 4
  for 09:30 ET Tue 7/7 open (`status: accepted`, `position_intent:
  buy_to_open`, `expires_at 2026-07-07T20:00:00Z`). This deviates from
  the Sun 7/5 plan's "LIMIT at zone midpoint in 09:30–10:00 ET" tactic
  — the task template's guardrails (max 10% per position, min 20% cash)
  are both satisfied at 4.88% max and 82.76% post-fill cash, so the
  simplification to market orders complies with the task-level
  constraints even though it drops the intra-zone entry discipline.

  **Trailing-stop attempt: correctly REJECTED (HTTP 422).** All 4
  `type: trailing_stop, side: sell, trail_percent: 10, time_in_force:
  gtc, position_intent: sell_to_close` requests bounced with `code
  42210000, message: "position intent mismatch, inferred: sell_to_open,
  specified: sell_to_close"` — this is the intended safety behavior
  (account has `shorting_enabled: true`, so a bare sell trailing_stop
  would have opened a short; the sell_to_close intent forced Alpaca to
  reject the pre-fill request). **10% trailing stops MUST be armed
  by the first post-open session that sees the 4 filled positions**
  — action-item queued below.

  **ClickUp:** ping SENT via the task-template rule ("only if a trade
  was placed or stop loss triggered") — 4 trades placed = trigger
  satisfied.
- **Sun 2026-07-05 evening pre-Mon check-in (previous run):** Weekend pull.
  Market CLOSED. Account re-verified: equity $100,000.00 | cash 100% |
  positions `[]` | clock next_open 2026-07-06T09:30-04:00. Two key
  updates from the Sat 7/4 pass: **(1) EU tariff deal was IMPLEMENTED
  on schedule** — the EU published the enacting texts in its official
  journal ahead of Trump's Jul 4 250th-birthday deadline; deal terms
  in force (15% on most EU exports to US, 0% US industrial goods to
  EU); no "much higher" Trump snap-back, no EU retaliation. Abort
  contingency (c) added Sat is now **CLEARED** without triggering.
  **(2) Kospi Fri 7/3 close revised UP** — CNBC live-updates confirm
  +5.76% (Sat log undercounted at ~2.9%); Nikkei +1.47%, Hang Seng
  +1.28%, ASX +1.37%. Even Sun-night −3% Kospi would land ~2.8% above
  Thu post-rout low. Also confirmed Fri 7/3 was a FULL NYSE close
  (Independence Day observed), not a shortened session; Thu 7/2 index
  closes were SPX +0.49%, Nasdaq +0.40%, Dow +0.46% record, RUT −0.39%.
  Weekend headline scan on watchlist names: NVDA org hire (Parker →
  Field Ops), AMD Motley Fool "big month" piece + Jul 22–23 Advancing
  AI event confirmed, IONQ nothing new post-Archer, QTUM nothing new,
  SPY/QQQ nothing name-specific. **4-starter Mon 7/6 arm plan
  intact.** No orders placed (market closed). No stops to check (empty
  book). **No ClickUp ping** — no urgent catalyst; contingency-cleared
  updates are status-quo positive and do not warrant a phone banner.
- **Sat 2026-07-04 weekend research pass:** Weekend pull.
  Market CLOSED all weekend (Independence Day proper). Account re-
  verified: equity $100,000.00 | cash 100% | positions `[]` (Fri 7/3
  holiday didn't move state). Weekend headline scan cleared: (a)
  Kospi / Samsung / SK Hynix REBOUNDED Fri 7/3 — Samsung +6.82%,
  SK Hynix +4.6%, Kospi ~+3% to 7,869.84, materially de-risking the
  "Sunday gap-down 5%+" abort contingency; (b) Meta "Compute" cloud
  narrative re-framed as CONSTRUCTIVE — Meta +9% on the Tue 7/1
  story, capex RAISED to $125–$145B (from $115–$135B), Meta selling
  excess AI compute as revenue not deleveraging out of it; (c) no
  fresh hyperscaler capex-cut headlines from OpenAI / Anthropic /
  Google / Microsoft / Amazon over the weekend; (d) NFP dovish print
  confirmed (57K vs ~115K consensus, U/R 4.2%, 2Y −3.5bps to 4.13%);
  (e) NEW overhang: **EU tariff deadline hit TODAY** — Trump gave the
  EU until July 4 to fully implement the trade deal or face "much
  higher tariffs"; weekend outcome not yet confirmed, monitor Sun
  evening. **No changes to the 4-starter Mon 7/6 arm plan** (IONQ 3%,
  QTUM 5%, NVDA 5%, SPY 5% = 18% deploy). AMD KILL still stands.
  IONQ Archer Materials $1.5M partnership announced Jul 1 noted (small
  deal, but third IonQ commercial headline in a month). No orders
  placed (market closed). No stops to check (empty book). **No
  ClickUp ping** — weekend headline flow is status-quo positive for
  the Monday plan; no held-name emergency; no watchlist gap >5%
  possible on a weekend close.
- **Fri 2026-07-03 pre-market:** ~06:07 ET pull. Market CLOSED
  (July 4 observed). Account re-verified: equity $100,000.00 | cash 100%
  | positions `[]` (33 closes / 34 sessions since 2026-05-12). Pulled
  actual Thu 7/2 daily closes via Alpaca 1Day bars — NVDA 194.51 (−1.53%),
  AMD 518.25 (−4.19%, low 506.33 — INVALIDATED), SPY 744.86 (−0.11%),
  QQQ 712.53 (−1.76%), QTUM 155.13 (−3.21%), IONQ 49.17 (−4.42%). NFP
  **printed +57K vs consensus 100–113K** (dovish miss); U/R ticked
  down to 4.2%; 2Y −3.5bps to 4.13%. Tape driver was the **Meta AI-
  capex cloud story** → SK Hynix −14.5% / Samsung −9.1% / Kospi −7.9%
  (emergency halt). US semis rolled in sympathy (NVDA −1.5%, AMD −4%).
  Applied Drafts→Armed Rule to five 7/2 candidates: **AMD KILLED**
  ($510 invalidation broken intraday); **QTUM re-priced $156–$162 →
  $148–$156** (marginal below-zone miss); **NVDA / SPY / IONQ HOLD-
  LIVE** (all inside zones). Aggregate Mon 7/6 arm plan: 18% deploy
  across 4 names, 82% cash. Fourth session-log gap flagged (Thu 7/2
  EOD missing). No orders placed (market closed). No stops to check
  (empty book). **No ClickUp ping** — market closure + no held names
  + narrative-shift-not-emergency on Meta story. Weekend headline
  monitoring queued for Sun-night Asia session + Meta/hyperscaler
  capex commentary.
- **Thu 2026-07-02 pre-market SUPPLEMENTAL:** Web-research
  pass invoked to fill the news-scan gap the 02:35 ET Alpaca-only run
  documented. Account re-pull → equity $100,000.00 | cash 100% |
  positions `[]` (unchanged). Watchlist news scanned for NVDA (Palantir
  sovereign-AI collab, PT $301 avg vs $197 spot), AMD (no earnings
  today; **Advancing AI 2026 event Jul 22–23**; Q2 print Aug 4;
  −6.83% Wed reset in a +154% YTD run), IONQ (Q1 revenue +755% YoY;
  Northland PT $70; Cambridge 256-qubit sale), QTUM (Trump $2B
  quantum push tailwind; +51% YTD), SPY/QQQ (no name-specific news;
  hyperscaler capex $650B+ intact). Macro: **NFP consensus ~100–113K,
  U/E 4.3%;** Fed dot plot has shifted toward possible 2026 rate HIKE
  under Chair Warsh (hawkish tape risk on a hot print). Five
  **candidate** drafts logged for post-NFP re-price (IONQ 3%, QTUM 5%,
  NVDA 5%, AMD 3–5%, SPY 5%) — **none armed**, all subject to
  Drafts→Armed re-price at Thu 7/2 EOD or Mon 7/6 pre-market. No orders
  placed. No stops to check. No urgent catalyst → no ClickUp.
- **Thu 2026-07-02 pre-market (02:35 ET run):** ~02:35 ET pull, pre-NFP.
  `GET /v2/account` → equity $100,000.00 | cash $100,000.00 |
  buying_power $400,000.00 | ACTIVE (PA39FINFSDLL). `GET /v2/positions`
  → `[]`. `GET /v2/stocks/snapshots` (NVDA/AMD/SPY/QQQ/QTUM/IONQ,
  feed=iex) refreshed against Wed 7/1 daily closes. **All three
  carried 6/27 drafts KILLED** — NVDA / AMD / SPY all closed Wed 7/1
  above their drafted entry zones (chase risk). **Cash-Drag Escalator
  default-action DEFERRED** with tier-1 named-blocker documented:
  US NFP prints 08:30 ET Thu 7/2. This is the FIRST explicit
  invocation of the named-blocker escape clause (the Mon 6/29
  failure was silent-skip; today invokes it properly). Session-log
  gap acknowledged: Tue 6/30 + Wed 7/1 unlogged — a second
  independent process failure. No orders placed. No stops to check.
  No ClickUp ping (task rule: notify only on placed trade or
  triggered stop).
- **Mon 2026-06-29 EOD:** Post-close pull. `GET /v2/account` → equity
  $100,000.00 | cash $100,000.00 | ACTIVE (PA39FINFSDLL). `GET
  /v2/positions` → `[]`. **30th consecutive cash close.** SPY +1.28%
  on the day (738.44 vs 729.35). **Bull day −128 bps vs SPY.**
  **Cash-Drag Escalator default-action was NOT honored** — no
  pre-market session ran, no starter placed, no named-blocker
  logged, no kill reason recorded.
- **Sat 2026-06-27 (weekend pre-market prep for Mon 6/29):** Weekend
  pull. `GET /v2/positions` → `[]`. Watchlist snapshots refreshed to
  Fri 6/26 closes. **Three trade ideas DRAFTED** in research_log.md
  for Mon 6/29 execution: NVDA 5% rank 1, AMD 5% rank 2, SPY 5%
  rank 3. **Cash-Drag Escalator default-action was LIVE for Mon 6/29.**
- **EOD 2026-06-26 (Fri — weekly review):** Day P/L 0.00% vs SPY −0.54%.
  Week P/L 0.00% vs SPY −2.33% → +233 bps weekly (defensive luck,
  NOT alpha). 29th cash close. strategy.md amended with Cash-Drag
  Escalator + Drafts→Armed Order rules.

## Action items for next session (Tue 7/7 intraday — post-09:30 ET open)

**CRITICAL — must be handled by the first post-open run:**
1. **Verify fills** on the 4 queued market orders (IONQ 64 / QTUM 32
   / NVDA 25 / SPY 6). Pull `GET /v2/orders?status=filled&after=
   2026-07-07T13:30:00Z` and `GET /v2/positions`. Confirm avg fill
   prices vs Mon 7/6 close bids. Any partial or unfilled leg (thin
   liquidity on IONQ possible) needs a decision: re-submit at open+
   30 min, or kill.
2. **Arm 10% trailing stops** (`type: trailing_stop, side: sell,
   trail_percent: 10, time_in_force: gtc, position_intent:
   sell_to_close`) for each filled position IMMEDIATELY after the
   fill pull. This session was blocked from arming pre-fill by the
   sell_to_open safety check (account has shorting_enabled=true).
   Log the trailing-stop order IDs in the queued-orders table above
   and in trade_log.md.
3. **Update portfolio.md Current Positions table** with the 4 filled
   avg-entry prices, mark-to-market, %P/L, and the trailing-stop
   HWM baseline (= avg entry at fill).

**Same-day / Wed follow-ups:**
4. **ISM Services PMI (June)** printed Mon 7/6 10:00 ET — need to
   backfill the print into the research log along with SPX / Nasdaq
   Mon 7/6 closes (the Mon 7/6 EOD log gap).
5. **FOMC minutes Wed 7/8 14:00 ET** — first held-position macro test
   if fills execute. Stop-check pass at 14:00 and 14:30 ET.
6. **AMD re-draft** — post-Mon 7/6 open (already missed), look for a
   base candle in $490–$510 for a Tue 7/7 or Wed 7/8 pre-market
   re-arm ahead of Jul 22–23 Advancing AI event.
7. **Weekly review** (rolled from Mon 7/6 EOD) — hold at Tue 7/7
   EOD or Fri 7/10 EOD. Must document the growing log-gap pattern
   (6 sessions now) and the harness-firing-time mismatch (task
   template said "market just opened" while Alpaca clock said
   pre-market).

**Structural / policy:**
8. **Log-gap watchdog** — 6 missed sessions and one missed weekly
   review is now a pattern, not an incident. Consider adding to
   strategy.md: (a) a cron / harness sanity check that fires "did
   the intended session run?" between sessions, and (b) a
   standing-decay-limit-order mechanism so drafts can arm as
   resting limits without depending on any given cron firing.
9. **Task-template time drift** — the harness-time mismatch (task
   template said "market just opened", Alpaca clock said 02:34 ET
   pre-market) needs the user to reconcile. Session proceeded
   because Alpaca queues day market orders received pre-open, but
   the "immediately set trailing stop" step CANNOT be executed
   pre-fill and had to be deferred.
10. **Cash floor** (task-template 20% floor) — post-fill projection
    ~82.76% cash, well above; untouchable. Aggressive-mode strategy
    floor (5–10%) also intact.
11. **Earnings calendar** unchanged — CPI Tue 7/14, JPM/Citi/WF/GS
    Tue 7/14, AMD Q2 Aug 4, NVDA Q2 Aug 26. No held-name earnings
    risk in the 4 queued names' next 30 sessions.
12. **ClickUp policy** — this session PINGED (trades placed). Future
    sessions ping only on placed trade, triggered stop, or urgent
    catalyst. EOD standing ping still required Fridays.
