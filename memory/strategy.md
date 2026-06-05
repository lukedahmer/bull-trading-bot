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
1. Read memory files: strategy, portfolio, trade_log, research_log.
2. Pull Alpaca account + positions.
3. Research via Perplexity (sonar-pro):
   - Pre-market movers
   - Overnight news on current holdings
   - Macro events today (Fed speakers, data prints, geopolitics)
   - Watchlist updates: QTUM, IONQ, NVDA, AMD, SPY, QQQ
4. Draft trade ideas — do **not** place trades in the pre-market run.
5. Update research_log.md and portfolio.md.
6. Commit + push.
7. ClickUp ping ONLY if an urgent catalyst (earnings beat/miss on a held
   name, halted stock we own, macro shock, gap >5% on watchlist).

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

## Logging cadence (added 2026-06-05 after Week 1 review)
- Pre-market run **must** append at least one entry to research_log.md
  every trading day, even when no trade is taken. A "no-trade, here's
  why" note is valid and lets us back-test idea quality vs. realized
  moves.
- Weekly review (Friday post-close) **must** append to
  weekly_review.md and refresh the watchlist table in portfolio.md
  with explicit entry zones, stops, and targets — name-only
  watchlists are not actionable on Monday.
- If the account is 100% cash for two consecutive weeks, the Friday
  review must call this out as a deployment gap, not a status
  update.
