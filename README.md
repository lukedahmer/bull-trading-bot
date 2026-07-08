# Bull — AI Trading Agent

A 24/7 autonomous trading agent built with Claude Code routines and the Alpaca API. Goal: beat the S&P 500. (Formerly nicknamed "Dexter" — the agent is "Bull" everywhere now.)

## Stack
- **AI**: Claude (via Claude Code remote routines)
- **Broker**: Alpaca (paper trading)
- **Research**: Claude built-in web search
- **Notifications**: ClickUp
- **Scheduler**: Claude Code remote routines (cron, UTC)

## Schedule
Times shown in Central Time during daylight saving (crons are UTC, so local times shift 1h later when US DST ends in November).

| Routine | Cron (UTC) | Local (CT) | Days | Purpose |
|---------|------------|------------|------|---------|
| Pre-Market | `0 11 * * 1-5` | 6:00 AM | Mon-Fri | Research & draft trade ideas |
| Market Open | `35 13 * * 1-5` | 8:35 AM | Mon-Fri | Execute trades (5 min after the bell) |
| Midday | `0 17 * * 1-5` | 12:00 PM | Mon-Fri | Portfolio health check |
| Market Close | `10 20 * * 1-5` | 3:10 PM | Mon-Fri | End-of-day summary |
| Weekly Review | `0 21 * * 5` | 4:00 PM | Friday | Week recap + next week prep |

## Memory model
The agent's state lives in `memory/*.md` on the `main` branch. Every scheduled session clones `main`, reads memory, acts, and **must push memory updates back to `main`** — work left on auto-generated `claude/*` session branches is invisible to the next session.

## Setup
API keys should live as Variables/Secrets in the Claude Code cloud environment (`ALPACA_API_KEY`, `ALPACA_SECRET_KEY`, `ALPACA_BASE_URL`, `CLICKUP_API_TOKEN`, `CLICKUP_LIST_ID`). `secrets.md` in the repo root is a temporary fallback — once all five variables are set in the environment, rotate the keys and delete that file.
