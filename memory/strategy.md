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
- Half-size starter (1%) for names trading >50x sales (currently IONQ).
- Max single-position weight: 10% of equity.
- Max sector weight (e.g. semis NVDA+AMD+QTUM+IONQ combined): 40% of equity.
- **Speculative bucket cap (added 2026-07-03):** QTUM + IONQ combined ≤ 15%
  of equity. Reflects ~95x-sales quantum valuations and 1.5–2x SPY beta on
  drawdown days.
- Cash floor: never deploy below 10% cash.
- **Anti-dormancy rule (added 2026-07-03):** if the account holds 100% cash
  for 5 consecutive trading sessions, mechanically place a 2% SPY starter
  on the next session's open to break drift. Rule is disabled once any
  position exists.

## Risk rules
- Hard stop: -8% from entry on any single name.
- Trailing stop on winners: tighten to break-even after +10%, trail 5%
  below high-water mark after +20%.
- No new entries within 30 minutes of FOMC, CPI, PPI, NFP, or earnings
  for held names.
- No options, no leverage, no shorting in this account.

## Decision workflow (pre-market)
1. Read memory files: strategy, portfolio, trade_log, research_log, weekly_review.
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
