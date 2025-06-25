# 📈 Momentum vs. Buy-and-Hold: Data-Driven Investment Strategy with Python & MPT

### 👨‍💼 Author: Luis Pazmiño  
*Finance & Data Strategy Consultant | Python for Risk & Investment Modeling | Based in New York, USA*

---

## 🧠 Project Overview

This project showcases a comparative study of two investment strategies using real S&P 500 data:  
- **Momentum Trading Strategy (8/21-day moving average crossover)**  
- **Buy-and-Hold Strategy optimized via Modern Portfolio Theory (MPT)**

My goal was to simulate real-world portfolio decisions using Python, evaluate outcomes, and communicate insights visually and analytically—skills highly transferable to data-driven financial roles.

---

## 🎯 Key Objectives

- Apply the 8/21-day **momentum trading** strategy to 30 real stocks across 3 sectors:  
  `Technology`, `Real Estate`, and `Utilities`
- Use **Modern Portfolio Theory (MPT)** to optimize a portfolio based on return-risk trade-offs
- Build and test **allocation strategies across 100+ risk levels** and visualize the **efficient frontier**
- Compare outcomes of three strategies using 2022 data:
  - Buy-and-Hold on MPT portfolio
  - Momentum trading on the S&P 500 (^GSPC)
  - Buy-and-Hold on the S&P 500 (^GSPC)

---

## ⚙️ Technologies Used

- **Python** (pandas, numpy, matplotlib, seaborn)
- **Google Colab**
- **cvxpy** (for convex optimization under MPT)
- **yfinance** (data retrieval from Yahoo Finance API)

---

## 📈 Highlights

- Retrieved and cleaned **5 years of daily stock data** programmatically.
- Built **modular, reusable Python functions** for trading simulation and optimization.
- Applied the **8/21 momentum crossover strategy** to all stocks.
- Selected the **top 3 performers per sector** based on strategy gains.
- Constructed an MPT-based optimizer exploring **over 100 risk levels**, plotted and analyzed.
- Simulated strategies in 2022 with an investment of **$100,000**, including fractional shares.
- **Compared and visualized all strategy outcomes** in a single plot for clarity.

---

## 💻 Notebook Files

- [`MomentumTrading.ipynb`](./MomentumTrading.ipynb): Core analysis notebook  
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Luis-Pazmino-Alvarez/momentum-trading-strategy/blob/main/MomentumTrading.ipynb)

- `requirements.txt` (to be added): Python package dependencies

---

## 📊 Visual Outputs

- Momentum strategy plots per sector
- Efficient frontier plot
- Allocation variation vs. risk level
- Portfolio performance comparison across strategies (2022)

> (> 📊 Visual outputs (momentum indicators, stock performance plots, optimization results) are rendered directly within the Colab notebook. An `images/` folder may be added in future for static exports.)

---

## 🧑‍💼 Skills Demonstrated

- Financial modeling with real market data
- Convex optimization for investment strategy
- Time-series analysis & trading logic automation
- Effective communication of insights via markdown and plots
- Clean and professional code with reproducibility focus

---

## 📚 Sources & References

- [Modern Portfolio Theory - Wikipedia](https://en.wikipedia.org/wiki/Modern_portfolio_theory)  
- [Momentum Trading Strategy - Investopedia](https://www.investopedia.com/terms/m/momentum_trading.asp)  
- [Yahoo Finance API Guide](https://algotrading101.com/learn/yahoo-finance-api-guide/)

---

## 📩 Connect With Me

If you're hiring for financial analytics, data science, or quant roles—  
📧 **Luis Pazmiño** | [LinkedIn](https://www.linkedin.com/in/luis-pazmino-702838248/) | Based in NYC  
🚀 I’m open to challenging opportunities in finance, risk modeling, and business strategy powered by data.

