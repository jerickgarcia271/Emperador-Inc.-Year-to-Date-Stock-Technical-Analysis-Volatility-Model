# Emperador Inc. Year-to-Date Stock Technical Analysis & Volatility Model

Predictive Analytics for Investments | Course Requirement

## Overview

This project provides a quantitative technical analysis and volatility model for **Emperador Inc. (EMP.MN)** using Microsoft Excel. By evaluating historical daily price movements, return distributions, volatility metrics, and technical indicators (such as Moving Averages and Bollinger Bands), the model simulates dynamic portfolio performance, models projected cash flows, and measures compounding returns over time.

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

- **Ending Portfolio Balance:** Projected to reach **₱1,200,000.00** under the modeled investment scenario.
- **Annualized Return:** Achieved a **+29.6% annualized profit** across the evaluated timeframe.
- **Volatility Analysis:** Calculated annualized volatility metrics that establish clear price boundaries and dynamic standard deviation bands.
- **Technical Signals:** Bollinger Bands and Moving Averages effectively highlighted periods of heightened volatility compression and price expansion.

## Model Framework & Features

The Excel model is structured across several specialized analytical components:

1. **Price & Return Engine:**
   - Daily price series tracking (Open, High, Low, Close, Volume).
   - Logarithmic and simple daily return calculations.
2. **Technical Analysis Module:**
   - Simple Moving Averages (SMA) for baseline trend identification.
   - Dynamic Standard Deviation calculations.
   - Upper and Lower Bollinger Bands to visualize volatility envelopes.
3. **Volatility & Risk Metrics:**
   - Historical volatility scaling (daily to annualized calculations).
   - Downside risk and variance metrics.
4. **Portfolio Simulation & Cash Flow Model:**
   - Dynamic compounding calculation schedules.
   - Cash inflow/outflow tracking with modeled cumulative growth outputs.

## Tools & Technologies

- **Microsoft Excel** — Quantitative financial modeling, technical indicator formulas, dynamic tables, statistical calculations, and financial charting.
- **Financial Analytics Functions** — Log/Simple return modeling, standard deviation, moving averages, compound growth, and return annualization logic.

## Repository Structure

```text
emperador-stock-analysis/
│
├── data/
│   └── CS176-Garcia-Assignment3 (Excel).xlsx
│
├── docs/
│   └── Executive_Summary_and_Technical_Report.pdf
│
└── README.md
```

## Limitations

- **Historical Bias:** The model relies on historical price and volatility trends, which may not fully predict future market shifts or black-swan events.
- **Exogenous Variables:** Macroeconomic changes, market sentiment, company earnings reports, and regulatory updates for Emperador Inc. are not explicitly integrated into the technical quantitative calculations.
- **Execution Assumptions:** Portfolio performance outputs assume frictionless trading (zero slippage, fixed transaction costs, and instant trade execution).

## Author

**Jerick L. Garcia**  
Bachelor of Science in Mathematics  
University of the Philippines Diliman  

*Predictive Analytics for Investments*