# Weekly Watchlist Refresh Prompt
# Copy everything below this line and paste into Claude every week

---

**Weekly refresh — update the India Equity Masterlist**

Today's date: [FILL IN DATE e.g. 26 May 2026]

Please do the following:

**1. Price & delta update**
Pull live prices for all active stocks via Yahoo Finance / web search:
HAL, BSE, BEL, NATCOPHARM, AJANTPHARM, SOLARINDS, POWERGRID, TITAN, AUROPHARMA, CDSL, GVT&D, COFORGE, ETERNAL, ATHERENERG, KEC, LUPIN, STLTECH, HFCL, TDPOWERSYS

**2. Screener run**
Run a momentum screener on NSE with these criteria:
- Price > SMA(21)
- SMA(200) < SMA(21) [Golden Cross]
- ATR(14) > 5% [High momentum]
- Revenue growth YoY > 15%

Search for: "India NSE momentum breakout stocks [CURRENT WEEK] [MONTH YEAR]"
Cross-reference any new names against recent earnings, analyst upgrades, and sector news.

**3. News scan**
Search for the following and flag anything material:
- "[Each stock name] news [current month year]"
- "India NSE sector rotation [current month year]"
- "India defence stocks news [current month year]"
- "India pharma USFDA approval [current month year]"
- "India power transmission news [current month year]"

**4. Conviction re-score**
For each stock, based on new prices and news:
- Upgrade / downgrade conviction pips
- Adjust entry zones to reflect new CMP
- Flag any stops that are now live (price near or below stop)
- Flag any upcoming results (board meetings, earnings dates)
- Move any watchlist stocks to active if they've triggered

**5. Universe expansion**
Based on screener results and news, suggest up to 3 new additions:
- 1 from momentum screener
- 1 from recent earnings beats
- 1 from sector rotation / news

**6. Output**
Generate the updated `index.html` file — same v3 format with:
- White background
- Live TradingView charts on "Live Chart" tab
- Yahoo Finance live prices on card header
- FIRE gates + plain English on "Why Conviction?" tab
- All entry/target/stop levels updated to reflect new prices

Attach the file so I can upload it to GitHub.

---

**My portfolio (already held — mark as Hold/Add not Fresh Buy):**
HAL, BSE [ADD ANY OTHERS YOU NOW HOLD]

**Stocks to remove this week (if any):**
[LIST ANY YOU'VE SOLD OR WANT OFF THE LIST]

**Specific questions this week:**
[ANY SPECIFIC STOCK YOU WANT DEEPER ANALYSIS ON]
