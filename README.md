# Emperador Inc. Year-to-Date Stock Technical Analysis & Volatility Model

Predictive Analytics for Investments | Course Requirement

## Overview

This project provides a quantitative technical analysis and volatility model for **Emperador Inc. (PSE: EMI)** using Microsoft Excel. By evaluating historical daily price movements, return distributions, volatility metrics, and technical indicators (such as Moving Averages and Bollinger Bands), the model simulates dynamic portfolio performance, models projected cash flows, and measures compounding returns over time.

Developed as a course requirement for *Predictive Analytics for Investments*, the model bridges core financial theory with hands-on quantitative modeling to evaluate portfolio risk, equity growth, and potential returns under stochastic market conditions.

## Objectives

The project aims to:
- **Analyze Historical Trends:** Track and evaluate year-to-date (YTD) price actions and return metrics for Emperador Inc.
- **Quantify Risk & Volatility:** Compute historical and annualized volatility metrics to evaluate downside exposure.
- **Implement Technical Indicators:** Model Moving Averages, Standard Deviation channels, and Bollinger Bands to identify potential buy/sell signals and mean-reversion trends.
- **Simulate Portfolio Outcomes:** Build dynamic cash flow and return schedules to project ending portfolio values under modeled investment scenarios.
- **Evaluate Risk-Adjusted Performance:** Assess overall risk-return trade-offs to aid investment decision-making.

## Business & Investment Context

Investors and portfolio managers require objective, quantitative frameworks to navigate stock market volatility and timing. Analyzing raw equity prices alone often misses structural volatility shifts and key technical signals.

This model serves as a decision-support system to:
- Monitor daily asset price fluctuations and historical return behaviors.
- Apply statistical technical boundaries (Bollinger Bands) to gauge overbought or oversold conditions.
- Test systematic investment strategies using cash flow projections and compounded return calculations.

## Key Model Outputs & Findings

- **Ending Portfolio Balance:** Projected to reach **₱1,203,697.94** under the modeled investment scenario.
- **Total Net Profit:** Generated **₱203,697.94** (+20.37% yield) over the simulation period.
- **Annualized Profit:** Achieved a **+29.62% annualized return** across the evaluated timeframe.
- **Trade Execution:** Identified and simulated 4 closed trade opportunities based on Bollinger Band buy and sell triggers.
- **Volatility Analysis:** Calculated dynamic standard deviation bands ($k = 1.4$) to establish precise upper and lower volatility envelopes.

## Model Framework & Features

The Excel model is structured across several specialized analytical components:

1. **Price & Return Engine:**
   - Daily price series tracking (Date, Closing Price in PHP).
   - Rolling 20-Day Moving Averages (MA) and 20-Day Moving Standard Deviation (MSD).
2. **Technical Indicator & Trigger Module:**
   - Upper Bollinger Band (UBB) and Lower Bollinger Band (LBB) calculations.
   - Dynamic Buy Triggers (`Close <= LBB`) and Sell Triggers (`Close >= UBB`).
3. **Simulated Trading & Cash Flow Engine:**
   - Share position tracking and liquid capital movement across closed trades.
   - Dynamic balance updates reflecting trade entries, price targets, and trade exits.
4. **Performance & Return Metrics:**
   - Total yield, net profit, and annualization scaling formulas adjusting for trading days ($365 / 251$).

## Tools & Technologies

- **Microsoft Excel** — Quantitative financial modeling, technical indicator formulas (`AVERAGE`, `STDEV.P`, `IF`), dynamic tables, and financial tracking.
- **Financial Analytics & Quantitative Formulas** — Moving Averages, Bollinger Bands, standard deviation scaling, compound returns, and annualized yield modeling.

## Repository Structure

```text
emperador-stock-analysis/
│
├── data/
│   └── CS176-Bollinger_Bands-Garcia.xlsx
│
└── README.md
```

## Limitations

- **Historical Bias:** The model relies on historical price movements and volatility trends, which may not fully predict future market shifts or sudden market anomalies.
- **Exogenous Factors:** Macroeconomic factors, industry regulations, corporate earnings reports, and broader market sentiment for Emperador Inc. are not explicitly integrated into the quantitative technical rules.
- **Execution Assumptions:** Trade simulations assume frictionless execution without incorporating brokerage commissions, slippage, bid-ask spreads, liquidity constraints, or capital gains taxes.

## Author

**Jerick L. Garcia**  
Bachelor of Science in Mathematics  
University of the Philippines Diliman  

*Predictive Analytics for Investments*
