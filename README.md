
# PortfolioRiskDashboard

## 📊 Demo Preview
![Dashboard Preview](screenshots/dashboard.png)

---

## 📌 Project Overview
This project is a Python-powered analytical tool that processes historical price data for a portfolio of assets and generates an Excel report rich with investment risk metrics. It is designed to simulate the kind of quantitative risk dashboards used by investment analysts and risk managers in banks and asset management firms.

The Excel file produced gives a breakdown of risk-adjusted performance per asset over time, helping decision-makers identify volatility patterns, underperformers, and efficient assets.

---

## 📊 Dataset Contents
Each row in the final Excel output corresponds to a specific **Ticker** on a given **Date**, enriched with calculated risk metrics:

| Column | Description |
|--------|-------------|
| Date | Trading date |
| Ticker | Asset symbol |
| Daily Return | % change in price from previous trading day |
| Cumulative Return | Compound return since start date |
| Benchmark Cumulative Return | Market or index return for comparison |
| Risk-Free Rate | Daily risk-free return (e.g. from T-Bills) |
| Rolling Volatility (21D) | Std. dev. of daily returns over last 21 days |
| Rolling Sharpe Ratio (21D) | Risk-adjusted return over last 21 days |

---

## 🧠 Financial Concepts Involved

- **Daily Return**: Measures short-term price movement.
- **Cumulative Return**: Shows long-term growth.
- **Risk-Free Rate**: Baseline return to compare risky assets.
- **Rolling Volatility**: Highlights fluctuations and risk over time.
- **Sharpe Ratio**: Core risk-adjusted performance metric (higher = better).

These are the foundational metrics used in real-world portfolio risk monitoring, such as in private banks, hedge funds, and institutional asset management.

---

## ⚙️ Tech Stack
- **Python**: For data wrangling and metric computation.
- **pandas**: Time series and groupby analytics.
- **openpyxl**: Styling the Excel report (column widths, bold headers).
- **Excel**: Final deliverable for readability and business user use.

---

## 🎯 Why This Project Matters
- Demonstrates hands-on understanding of core **risk concepts** used in finance.
- Shows ability to translate financial theory into **code and visuals**.
- Perfect conversation starter for interviews around risk, asset management, and dashboarding.


---

## 📆 Setup Instructions

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/PortfolioRiskDashboard.git
   cd PortfolioRiskDashboard
    ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Add your historical price dataset (e.g. from Yahoo Finance or other APIs) to the `data/` folder.

4. Run the script:

   ```bash
   python risk_dashboard.py
   ```

5. Open the generated Excel file in the `output/` folder.

---

## 📸 Screenshots

| Rolling Metrics | Excel Styling |
| --------------- | ------------- |
|                |               |

---
