# Portfolio

_Last synced from Alpaca: **never** — Alpaca credentials still missing
as of 2026-05-19 pre-market. See research_log.md._

## Account
| Field | Value |
|---|---|
| Equity | _unknown_ |
| Cash | _unknown_ |
| Buying power | _unknown_ |
| Account status | _unknown_ |

## Open positions
_No data yet — `secrets.md` is not present in the repo and the Alpaca
env vars (`ALPACA_API_KEY`, `ALPACA_SECRET_KEY`, `ALPACA_BASE_URL`)
are unset in this session, so `/v2/account` and `/v2/positions` were
not called. No positions will be inferred or written here until a
real Alpaca sync succeeds._

| Symbol | Qty | Avg entry | Mkt value | Unrealized P/L | Weight |
|---|---|---|---|---|---|

## Sector exposure
_Will be computed on first successful sync._

## Pending review on next sync
- If NVDA is held: confirm size and stop before its 5/20 post-close
  earnings print; strategy bans new entries within 30 min of
  earnings on held names.
- If IONQ is held above the 2% default weight: trim candidate after
  +98% rally since 3/30 (see research_log.md 2026-05-19).
- Confirm semis sector weight (NVDA+AMD+QTUM+IONQ) is under the 40%
  cap before any tactical add.
