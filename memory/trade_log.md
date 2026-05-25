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

_No trades executed yet._

## 2026-05-25 midday ET — NO-OP (midday risk check)
- Pulled `/v2/account` and `/v2/positions` from Alpaca paper API.
- Positions: none. Equity $100,000, all cash.
- No stops triggered, no trims, no trailing-stop adjustments, no new entries.
- ClickUp ping suppressed per instructions (no stop, no trim).
