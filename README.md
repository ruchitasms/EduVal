### 🎯 The Mission
EduVal is an interactive learning platform designed to translate complex financial data into intuitive insights. Most retail investors look at price; data professionals look at the "engine" behind the price. This project is a work-in-progress journey to bridge the gap between Financial Literacy and Data Science, helping users see the "truth" behind the tickers.

https://ruchitasms.github.io/EduVal/

### 📊 Core Framework (Current Features)
- Phase 01: The Valuation: Automatically categorizes stocks into Value Plays, Fair Value, or Premium Growth based on live EV/EBITDA multiples.Sector-Specific Intelligence: The UI dynamically adjusts its logic (e.g., Energy vs. Software) to reflect different market expectations.Momentum Tracking: Real-time 7-day price visualization using Chart.js to compare market sentiment against fundamental value.
- Phase 02: Financial Statement Deep DiveThe "Report Card" View: A dedicated dashboard for the Balance Sheet, Income Statement, and Cash Flow. Automated Logic Badges Liquidity: Checks if Current Assets can cover immediate liabilities.Efficiency: Identifies companies with "Moats" through high Net Margins.Quality: Validates if reported profits are backed by actual Free Cash Flow.
- Phase 03: Resilience & Survival (The Z-Score)Company Health Indicator: Implements the Altman Z-Score to predict bankruptcy risk.Safe (> 2.99): Low risk of insolvency (e.g., XOM at 4.56).Grey (1.81 - 2.99): Cautionary zone.Risk (< 1.81): High distress probability.Component Breakdown: A visual bar chart displaying the drivers of resilience: Working Capital (WC), Retained Earnings (RE), EBIT, Equity (EQ), and Sales.Trend Monitoring: Multi-year line charts tracking whether a company's financial "shield" is strengthening or weakening over time.
- Phase 04: Strategic Positioning & AlphaRisk-Reward Variance: A specialized plot of Beta vs. Actual Return. By mapping real-world performance against the theoretical benchmark, users can see the "Variance"—the gap between market expectations and reality.Capital Structure Visualization: A dynamic breakdown of the company’s funding mix (Debt vs. Equity) to calculate the WACC (6.2% in example).Performance Metrics: * Hurdle Rate: The minimum return required by investors.Actual ROIC: The company's actual efficiency in generating profit.Alpha Calculation: A red/green indicator showing the precise percentage of value creation or destruction (e.g., -0.1% Alpha).

### ⛏️ Built WithAPI: 
Financial Modeling Prep (FMP) Stable API.Frontend: HTML5, CSS (Pico.css Framework), JavaScript (Vanilla).Visualization: Chart.js for real-time market momentum and financial trends.Logic: Custom-built financial screening algorithms, Z-Score modeling, and WACC calculations.

### 🏢 Constraints
This project currently focuses on a curated list of 10 high-impact companies across diverse sectors (Tech, Energy, Fintech, etc.) to ensure data accuracy and speed within free API tier limits.

### ⏭️ Next-up: Phase 5
Roundup!
