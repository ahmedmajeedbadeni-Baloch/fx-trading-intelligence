FX Trading Intelligence

A professional platform for analyzing USD exchange rates and generating automated trading signals. Built for people who want sharp, reliable insights—without the noise.

Project Overview

I designed this for the Sapphire Capital Partners KTP Associate recruitment. It crunches official US Treasury data and analyzes how the US dollar stacks up against the euro, pound, and Canadian dollar. The main goal? Deliver trading intelligence that actually helps.

Key Features

- Trend Analysis: Five years of historical trends, complete with regression lines and key event notes.
- Volatility Assessment: Rolling volatility checks, with clear risk zones—HIGH, MEDIUM, or LOW.
- Trading Signals: Automated BUY, HOLD, or WATCH calls. No guesswork.
- Correlation Analysis: See how currencies move together, spot concentration risks, and get portfolio insights.
- AI Summaries: LLM-powered executive summaries for fast, clear decision-making.

Visualizations

1. USD Exchange Rate Trends (2020-2025)
   - Quarterly data, trend lines, and big event markers (think COVID-19, Ukraine war, rate hikes).
   - Tracks where we are now and how far we’ve strayed from the trend.
   - Risk bands flagging overbought or oversold zones.

2. Year-on-Year Comparison
   - Annual averages, with Q1 seasonal patterns and standard deviation bands.

3. Volatility Analysis
   - Rolling 1-year window, risk zones (LOW <5%, MEDIUM 5-10%, HIGH >10%).
   - Box plots show return distributions.

4. Correlation Matrix
   - Analyze diversification, spot concentration risk, and highlight independent moves.

Tech Stack

Core tools:
- Python 3.9+
- Pandas, NumPy for data crunching
- Matplotlib, Seaborn for charts
- US Treasury Fiscal Data API

Analysis methods:
- Linear regression for trends
- Rolling window volatility (annualized)
- Pearson correlation matrices
- Deviation bands for outliers

Quick Start

Clone the repo, install the dependencies, and run the analyzer. That’s it.

git clone https://github.com/ahmedmajeedbadeni-Baloch/fx-trading-intelligence.git
cd fx-trading-intelligence
pip install -r requirements.txt
python src/currency_analyzer.py

Requirements

pandas>=2.0.0
numpy>=1.24.0
matplotlib>=3.7.0
seaborn>=0.12.0
requests>=2.31.0

Sample Output

Trading Signals:
- EUR: 7.8% OVERSOLD — BUY opportunity
- GBP: 4.2% below trend — WATCH
- CAD: Fair value — HOLD

Risk Status:
- EUR/GBP: HIGH volatility (>10%) — Needs hedging
- CAD: MODERATE (9.2%) — Just monitor

Portfolio Insights:
- EUR-GBP correlation: 0.79 (watch for concentration risk)
- CAD correlation: 0.45 (good for diversification)

Project Structure

fx-trading-intelligence/
├── data/                  # Processed datasets
├── visualizations/        # Generated charts
├── src/                   # Source code
├── docs/                  # Documentation
└── README.md

Context

Built as part of the Digital Platform Developer - KTP Associate application at Sapphire Capital Partners.

Objectives:
- Show real-world, production-ready code
- Prove financial analytics know-how
- Deliver business intelligence you can act on
- Make complex stuff simple—even for non-technical folks

Key Findings

Current Market Position (as of Nov 2025):
1. EUR is a buy right now—7.8% under value
2. EUR/GBP volatility is high, so active hedging is a must
3. CAD helps balance the portfolio—low correlation, steady
4. EUR-GBP correlation is too tight; time to rebalance

Immediate Actions:
- Hedge EUR/GBP volatility
- Start EUR long positions
- Review correlation exposure
- Monitor daily

Future Enhancements

- Real-time API streaming
- Machine learning for predictions
- Automated alerts
- Interactive dashboards (Plotly/Dash)
- Backtesting
- Multi-timeframe analysis

Author

Ahmed Baloch
- MSc Artificial Intelligence (First Class Honours), Ulster University Belfast
- LinkedIn: linkedin.com/in/ahmedbaloch19a
- Email: ahmedmajeedbadeni@gmail.com

License

This project is part of a recruitment assessment. 