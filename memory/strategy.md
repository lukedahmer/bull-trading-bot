# Dexter Trading Strategy

## Primary Goal
Beat the S&P 500 (SPY) over the long term using a mix of thematic ETFs and high-conviction growth stocks.

## Core Themes to Watch
1. **Quantum Computing** — QTUM is the primary ETF. Also watch IonQ (IONQ), Rigetti (RGTI), D-Wave (QBTS)
2. **AI Infrastructure** — NVDA, AMD, SMCI, and AI-focused ETFs
3. **Semiconductors** — SOXX ETF, ASML, TSM
4. **Clean Energy** — ICLN, FSLR, ENPH
5. **Broad Market Hedge** — SPY/QQQ positions when thesis is unclear

## Entry Signals (BUY)
- Strong earnings beat + raised guidance
- Analyst upgrades from major firms
- Positive sector tailwind (gov funding, new regulation, macro shift)
- Technical: price above 50-day MA, RSI between 40-60 (not overbought)
- News catalyst with long-term structural impact (not hype)
- ETF shows consistent inflows over 2+ weeks

## Exit Signals (SELL)
- Position down -8% from entry → hard stop loss, exit immediately
- Thesis broken (bad earnings, leadership change, regulatory risk)
- Better opportunity found and portfolio is at max positions
- Trailing stop of 10% triggered on a winner
- Position up 30%+ → trim 50%, let the rest run

## Position Sizing (AGGRESSIVE MODE — paper trading)
- This is a paper account; goal is to find out fast whether the strategy works.
- Deploy the majority of the $100,000. Sitting on cash defeats the purpose.
- Starter position: 5-10% of portfolio
- High conviction: 15-25% of portfolio is allowed
- Single-name cap raised to 25% (was 10%) for highest-conviction ideas
- Cash floor relaxed to 5-10% (was 20%) — keep a little dry powder for dislocations, but stay heavily invested
- Still respect the -8% hard stop and 10% trailing stop — aggressive sizing requires disciplined exits

## Cash-Drag Escalator (added 2026-06-26 weekly review)
- **Trigger**: cash ≥ 90% of equity for ≥ 4 consecutive trading weeks (≥ 20 sessions).
- **Default action**: the next pre-market session must place a 5% starter on the highest-conviction name on the watchlist within the 09:30–10:30 ET window UNLESS an explicit, time-stamped, written named-blocker is documented in research_log.md (and ClickUp pinged) the same session.
- **Named-blocker eligibility**: only a tier-1 macro print due THAT SESSION (CPI / PCE / NFP / FOMC) or a halted/blocked status on the target name. "Digesting prior print" / "waiting for next print" do NOT qualify.
- **Watchdog**: every weekly review must restate the current cash-drag session count and whether the escalator was tripped.
- Rationale: 29 cash sessions through 2026-06-26 with the named binding gate (PCE) cleared without execution demonstrated that the named-blocker framework on its own can produce indefinite drift; the escalator forces an action-or-document choice.

## Drafts → Armed Order Rule (added 2026-06-26 weekly review)
- A "trade idea" drafted in research_log.md does NOT become an executable order automatically.
- Any draft carried > 1 trading session must be re-priced against the most recent close at the next pre-market run, AND either:
  (a) submitted as a live Alpaca order (limit or market) within that session's execution window, or
  (b) explicitly killed in the same pre-market run with the kill reason logged.
- Carrying drafts forward as "still valid" indefinitely is the failure mode the Tue 6/23 → Thu 6/25 → Fri 6/26 sequence exposed. No more silent rolls.

## Small-Cap / High-Growth Research Mandate
- Actively research smaller, less-covered names with large growth potential
- Risk is acceptable if the thesis is sound and the upside is asymmetric
- Look for: emerging tech, disruptive business models, early-stage thematic plays, post-IPO names with strong fundamentals
- Document the downside case explicitly before sizing in — small caps can go to zero
- Size small-caps more conservatively (3-7%) even in aggressive mode due to volatility
- Use the research log to flag promising names early so they can be tracked before becoming consensus

## Research Checklist (Before Any Buy)
- [ ] What is the thesis in one sentence?
- [ ] What would break the thesis?
- [ ] What is the catalyst in the next 30-90 days?
- [ ] What is the downside if wrong?
- [ ] Is the sector seeing institutional inflows?

## What to Avoid
- Meme stocks, Reddit hype, social media momentum without fundamentals
- Companies with no revenue and no clear path to profitability
- Anything with earnings in the next 48 hours (earnings are a coin flip)
- Penny stocks under $5
- Options, crypto, leveraged ETFs

## Benchmark Tracking
- Compare portfolio return vs SPY weekly
- If underperforming SPY by more than 5% over 30 days, reassess strategy
