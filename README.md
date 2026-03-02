# 📊 Monte Carlo Financial Simulation

## 📌 Business Context
Financial decisions are made under uncertainty. This project applies 
Monte Carlo simulation — a powerful quantitative finance technique — to 
model portfolio risk, revenue scenarios and investment decisions across 
10,000 simulated outcomes, enabling data driven risk aware decision making.

---

## 🎯 Project Objectives
- Simulate stock portfolio performance under uncertainty
- Calculate Value at Risk (VaR) at 95% and 99% confidence levels
- Model 3 year revenue scenarios with probability distributions
- Compare risk vs return across investment strategies
- Quantify probability of financial outcomes

---

## 📊 Simulation Parameters

| Parameter | Value |
|-----------|-------|
| Simulations Run | 10,000 iterations |
| Portfolio Stocks | 3 assets |
| Trading Days | 252 (1 year) |
| Initial Investment | $100,000 |
| Base Revenue | $5,000,000 |
| Forecast Horizon | 3 years |

---

## 📈 Simulation Results

### 💼 Portfolio Simulation
| Metric | Value |
|--------|-------|
| Average Portfolio Value | $112,375.52 |
| Median Portfolio Value | $111,539.76 |
| Standard Deviation | $13,389.81 |
| Best Case Outcome | +$87,714.10 |
| Worst Case Outcome | -$26,803.41 |

### ⚠️ Value at Risk (VaR)
| Confidence Level | Maximum Loss |
|-----------------|-------------|
| VaR 95% | -$7,874.24 |
| VaR 99% | -$14,429.20 |

### 📊 3 Year Revenue Scenarios
| Scenario | Revenue |
|----------|---------|
| Base Revenue | $5,000,000 |
| Average Forecast | $6,655,143 |
| Optimistic (95th) | $8,090,967 |
| Pessimistic (5th) | $5,323,249 |
| Probability of Growth | 98.3% |

---

## 🔬 Methodology

### 1️⃣ Portfolio Simulation
- Modeled 3 stocks with different risk/return profiles
- Simulated 252 daily returns using normal distribution
- Applied geometric Brownian motion for price paths
- Aggregated 10,000 portfolio outcomes

### 2️⃣ Value at Risk (VaR)
- Calculated VaR at 95% and 99% confidence levels
- VaR represents maximum expected loss under normal conditions
- Used historical simulation approach with Monte Carlo

### 3️⃣ Revenue Scenario Analysis
- Simulated 3 year revenue growth under uncertainty
- Applied random normal distribution to annual growth rates
- Identified optimistic, pessimistic and base case scenarios

### 4️⃣ Investment Decision Analysis
- Compared Growth vs Conservative investment strategies
- Quantified risk adjusted returns for each option
- Calculated probability of positive returns

---

## 🔍 Key Insights

### 💰 Portfolio Performance
- Average portfolio grows from **$100,000 to $112,375** (+12.4%)
- **95% confidence** maximum loss limited to **$7,874**
- **99% confidence** maximum loss limited to **$14,429**
- Strong positive skew indicates more upside than downside

### 📊 Revenue Outlook
- **98.3% probability** of revenue growth over 3 years
- Average 3 year revenue of **$6.66M** vs base of **$5M** (+33%)
- Optimistic scenario reaches **$8.09M** (+62% growth)
- Even pessimistic scenario shows modest growth to **$5.32M**

### ⚖️ Risk vs Return
- Portfolio standard deviation of **$13,390** shows manageable risk
- Growth investment offers higher return with proportionally higher risk
- Conservative investment provides more predictable outcomes
- Diversification across 3 assets reduces overall portfolio volatility

---

## 💡 Business Recommendations
- **Proceed with growth strategy** — 98.3% probability of revenue increase
- **Set risk limits** using VaR — maximum acceptable loss at 99% = $14,429
- **Plan for pessimistic scenario** — budget should account for $5.32M floor
- **Diversify portfolio** — 3 asset mix reduces concentration risk
- **Review assumptions quarterly** — update volatility inputs with market data

---

## 🛠️ Tools & Technologies

| Tool | Usage |
|------|-------|
| Python | Simulation engine and analysis |
| NumPy | Random number generation and statistics |
| pandas | Results aggregation and export |
| matplotlib | Distribution and scenario visualizations |

---

## 📂 Repository Structure
```
monte-carlo-financial-simulation/
│
├── data/
│   └── simulation_results.csv    # Key simulation outputs
├── python/
│   └── monte_carlo_simulation.ipynb  # Full simulation notebook
├── reports/
│   ├── portfolio_distribution.png    # Portfolio outcome distribution
│   ├── revenue_scenarios.png         # Revenue scenario chart
│   └── investment_comparison.png     # Investment comparison chart
└── README.md
```

---

## 🚀 Outcome
This project demonstrates **quantitative finance expertise** combined with 
**statistical simulation skills**, delivering risk insights suitable for 
**Quantitative Analyst, Risk Analyst, FP&A and Data Science roles**.

---
*All simulations use synthetic financial parameters for demonstration purposes.*
```

---

