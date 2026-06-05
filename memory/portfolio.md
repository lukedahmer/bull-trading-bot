# Portfolio

_Last synced from Alpaca: **2026-06-05 (Fri close)**, live via /v2/account
and /v2/positions._

## Account
| Field | Value |
|---|---|
| Account # | PA39FINFSDLL |
| Status | ACTIVE |
| Equity | $100,000.00 |
| Cash | $100,000.00 |
| Buying power | $400,000.00 |
| Non-marginable BP | $100,000.00 |
| Long market value | $0.00 |
| Short market value | $0.00 |
| Pattern day trader | false |
| Day-trade count | 0 |
| Multiplier | 4 |

## Open positions
GET /v2/positions returned `[]`. No open positions.

| Symbol | Qty | Avg entry | Mkt value | Unrealized P/L | Weight |
|---|---|---|---|---|---|
| _(none)_ | | | | | |

## Sector exposure
| Bucket | Weight | Cap |
|---|---|---|
| Cash | 100.0% | floor 10% |
| Semis (NVDA+AMD+QTUM+IONQ) | 0.0% | 40% |
| Index (SPY+QQQ) | 0.0% | — |

## Watchlist (refreshed 2026-06-05)
Levels are working ranges, not orders. Re-evaluate Monday pre-market.

| Symbol | Bias | Entry zone | Stop | Target | Starter size | Notes |
|---|---|---|---|---|---|---|
| IONQ | long | $58–62 | $54 | $75 | 2% ($2k) | Pure-play quantum leader; $470M RPO, $3.1B cash. Extended — prefer pullback. |
| QTUM | long | pullback to 20D MA | -8% | trend trail | 2% ($2k) | Diversified quantum exposure; +54% YTD. |
| NVDA | long | dips into prior week's VWAP | -8% | trend trail | 2% ($2k), scale to 8% | Rubin in production H2'26; no near-term earnings. |
| AMD | long | dips into prior week's VWAP | -8% | trend trail | 2% ($2k) | DC +39% YoY; secondary to NVDA. |
| SPY | hedge | n/a | n/a | n/a | only if concentration >30% single name | Index proxy. |
| QQQ | hedge | n/a | n/a | n/a | only if concentration >30% single name | Off ATH $746.16 set 2026-06-02. |

## Open orders
GET /v2/orders?status=open returned `[]`. No working orders.
