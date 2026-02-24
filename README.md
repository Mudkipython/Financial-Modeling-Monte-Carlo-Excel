# Quantitative Business Analysis: Stochastic Simulation & Optimization

This repository showcases advanced Excel-based quantitative models used to solve complex business decision problems under uncertainty. The project focuses on stochastic simulation, risk management, and revenue optimization across diverse industries.

## 🚀 Project Overview

The project is divided into three core analytical modules, each addressing a unique business challenge using Monte Carlo simulations and statistical inference:

### 1. Agricultural Risk Management (Freemark Abbey Winery)
- **Problem**: Optimal harvesting strategy for Riesling grapes under the threat of a storm and potential botrytis (noble rot) infection.
- **Approach**: Built a decision-making model using random variables to simulate weather outcomes and their impact on grape quality and market pricing.
- **Key Skill**: Decision analysis under uncertainty and risk-reward trade-off modeling.

### 2. Revenue Management & Booking Optimization
- **Problem**: Determining the optimal "Booking Limit" for discount airline seats to maximize total revenue while balancing the risk of empty seats versus lost full-fare opportunities.
- **Methodology**: 
  - Simulated demand distributions for both discount and full-fare segments.
  - Conducted sensitivity analysis to identify the booking limit that yields the highest Mean Revenue.
- **Result**: Identified a robust recommendation for seat allocation based on 1000+ simulation iterations.

### 3. Financial Engineering: Put-Call Parity Simulation
- **Problem**: Testing the theoretical validity of the Put-Call Parity relationship in derivative pricing through simulation.
- **Modeling Techniques**:
  - **Monte Carlo Simulation**: Generated 10,000+ stock price paths using geometric Brownian motion principles.
  - **Statistical Analysis**: Calculated 95% Confidence Intervals (CI) for call and put option prices to evaluate the convergence towards theoretical values.
  - **Sample Size Optimization**: Analyzed the impact of sample size on model precision and error margins.

## 🛠️ Technical Stack
- **Tools**: Microsoft Excel (Advanced Modeling)
- **Methodologies**: 
  - Monte Carlo Simulation
  - Stochastic Modeling
  - Statistical Inference & Hypothesis Testing
  - Revenue Optimization (Littlewood’s Rule logic)

## 📊 Key Deliverables
- `Quantitative_Analysis_Models.xlsx`: The core engine containing simulation sheets, data tables, and automated calculations.
- `Executive_Analysis_Report.pdf`: A comprehensive business report summarizing findings, statistical interpretations, and strategic recommendations.

## 💡 How to Use
1. Open the `.xlsx` file and navigate to the respective tabs for each case study.
2. (Optional) Press `F9` to re-run the simulations and observe the dynamic changes in results and confidence intervals.
