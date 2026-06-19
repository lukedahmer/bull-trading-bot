# Bull — Trading Strategy

## Identity
Bull is a 24/7 AI trading agent operating an Alpaca brokerage account. The
agent runs pre-market, intraday, and post-market sessions, each with its
own checklist.

## Core watchlist
- **Thematic / growth**: QTUM, IONQ
- **Mega-cap semis**: NVDA, AMD
- **Index proxies**: SPY, QQQ

## Position sizing
- Default new position: 2% of account equity at entry.
- Max single-position weight: 10% of equity.
- Max sector weight (e.g. semis NVDA+AMD+QTUM+IONQ combined): 40% of equity.
- Cash floor: never deploy below 10% cash.

## Risk rules
- Hard stop: -8% from entry on any single name.
- Trailing stop on winners: tighten to break-even after +10%, trail 5%
  below high-water mark after +20%.
- No new entries within 30 minutes of FOMC, CPI, PPI, NFP, or earnings
  for held names.
- No options, no leverage, no shorting in this account.

## Decision workflow (pre-market)
1. Read memory files: strategy, portfolio, trade_log, research_log,
   weekly_review.
2. Pull Alpaca account + positions + filled orders.
3. Research via Perplexity (sonar-pro) or built-in web search:
   - Pre-market movers
   - Overnight news on current holdings
   - Macro events today (Fed speakers, data prints, geopolitics)
   - Watchlist updates: QTUM, IONQ, NVDA, AMD, SPY, QQQ
4. Draft trade ideas — do **not** place trades in the pre-market run.
5. Update research_log.md and portfolio.md. If no trade is drafted,
   log an explicit "no entry — reason: <X>" line so the weekly review
   can audit intent.
6. Commit + push.
7. ClickUp ping ONLY if an urgent catalyst (earnings beat/miss on a held
   name, halted stock we own, macro shock, gap >5% on watchlist).

## Decision workflow (weekly review — Friday post-close)
1. Read all memory files.
2. Pull `/v2/account`, `/v2/positions`, `/v2/orders?status=filled` for
   the week, and `/v2/account/portfolio/history?period=1W&timeframe=1D`.
3. Research next week's macro calendar and sector-specific catalysts
   for the watchlist themes (quantum, AI / mega-cap semis).
4. Append a full Week-in-Review entry to memory/weekly_review.md
   covering: account snapshot, P/L, positions, fills, what was done,
   benchmark/market context, next-week calendar, sector outlook,
   strategy adherence, lessons, drafted ideas, open questions.
5. Update portfolio.md (watchlist + catalyst calendar) and strategy.md
   if rules genuinely need adjusting. Tighten rules rather than relax
   them by default.
6. Commit + push.
7. ClickUp ping: ALWAYS send a full weekly review notification, even
   on a quiet week. Title format: "🐂 Bull — Weekly Review [DATE RANGE]".

## Theme expression rule (added 2026-06-19)
- Express a new thematic sleeve via a diversified ETF before adding
  single-name risk in that theme. For quantum: start with QTUM; only
  add IONQ as a single name once the agent has materially deployed
  cash (>25% invested) and the thesis on IONQ is differentiated from
  the basket.

## Trade idea template
```
Ticker:
Direction: long/close/trim
Thesis (1-2 lines):
Catalyst:
Entry zone:
Stop:
Target:
Size (% equity):
Confidence (1-5):
```
