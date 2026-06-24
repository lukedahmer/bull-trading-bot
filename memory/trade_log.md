# Trade Log

Append-only ledger of executed trades. Newest first.

Format:
```
## YYYY-MM-DD HH:MM ET — SIDE TICKER QTY @ PRICE
- Order ID:
- Thesis:
- Catalyst:
- Stop:
- Target:
- Outcome (filled at):
```

---

## 2026-06-24 midday ET — SYNC (no trades)
- Pulled `/v2/account` and `/v2/positions` from Alpaca paper API.
- Equity $100,000.00, cash $100,000.00, 0 open positions.
- Midday risk sweep: no -8% stops, no 30%+ trims, no 15%+ trail tightening — nothing to act on.
- No new positions added (intraday rule; no major catalyst).

_No trades executed yet._
