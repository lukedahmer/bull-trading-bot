# Dexter — AI Trading Agent

A 24/7 autonomous trading agent built with Claude Code routines and the Alpaca API. Goal: beat the S&P 500.

## Stack
- **AI**: Claude Opus (via Claude Code routines)
- **Broker**: Alpaca (paper trading)
- **Research**: Perplexity API
- **Notifications**: ClickUp
- **Scheduler**: Claude Code remote routines

## Schedule
| Routine | Time | Days | Purpose |
|---------|------|------|---------|
| Pre-Market | 6:00 AM | Mon-Fri | Research & draft trade ideas |
| Market Open | 8:30 AM | Mon-Fri | Execute trades |
| Midday | 12:00 PM | Mon-Fri | Portfolio health check |
| Market Close | 3:00 PM | Mon-Fri | End-of-day summary |
| Weekly Review | 4:00 PM | Friday | Week recap + next week prep |

## Setup
API keys are stored as environment variables in the Claude Code cloud environment. Never commit keys to this repo.
