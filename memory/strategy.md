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

## FOMC-week sizing (added 2026-06-12)
- In any week that contains an FOMC rate decision, cap new initiations
  at 1% equity per name until after the Powell presser.
- Post-decision: normal 2% default applies, but stage entries over at
  least two sessions rather than a single-day fill.

## First-deployment guidance (added 2026-06-12)
- When the book is 100% cash, do not deploy more than 25% of equity in
  any single session. Build core exposure (SPY/QQQ) before thematic
  (QTUM) before single-name speculation (NVDA, AMD, IONQ).
- Target equilibrium: ~60% deployed, ~40% cash by end of the first
  two operating weeks — well inside the 10% cash floor and the 40%
  sector cap.

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
