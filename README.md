# Portfolio Optimization using Modern Portfolio Theory (MPT)

## Overview
This project applies **Modern Portfolio Theory (MPT)** to construct and evaluate investment portfolios with the aim of optimizing returns while managing risk. By leveraging **Monte Carlo Simulation**, different portfolio combinations are generated and analyzed to determine the **Efficient Frontier**.

## Portfolio Construction
Three different portfolio compositions have been built and evaluated:
1. **Domestic Portfolio** - Consisting entirely of Indian securities.
2. **Domestic + International Portfolio** - Adding the **Dow Jones Index (DJI)** to include international diversification.
3. **Domestic + International + Cryptocurrency Portfolio** - Further adding **Monero (XMR)** as a low-correlation asset.

## Methodology
- **Monte Carlo Simulation** was used to generate random portfolio allocations and estimate their respective returns and risks.
- The **Efficient Frontier** was plotted to visualize the optimal risk-return trade-offs.
- The **Sharpe Ratio** was used to evaluate risk-adjusted performance.

## Results

### 1. Domestic Portfolio
- **Return:** 68.02%
- **Volatility:** 28.92%
- **Sharpe Ratio:** 2.12
- **Observation:** High returns but high correlation among assets, limiting diversification benefits.

### 2. Domestic + International Portfolio
- **Return:** 35.45%
- **Volatility:** 11.37%
- **Sharpe Ratio:** 2.53
- **Observation:** Addition of **Dow Jones Index (DJI)** improved diversification, reduced volatility, and increased risk-adjusted returns.

### 3. Domestic + International + Cryptocurrency Portfolio
- **Return:** 25.22%
- **Volatility:** 9.55%
- **Sharpe Ratio:** 1.94
- **Observation:** Including **Monero (XMR)** further reduced risk but slightly lowered returns, demonstrating the benefit of uncorrelated assets in portfolio risk reduction.

## Comparison with Nifty 50
- **Nifty 50 Index** had an **expected return of 29.86%** and **volatility of 13.49%**.
- **Domestic + International and Domestic + International + Cryptocurrency portfolios outperformed Nifty 50** in risk-adjusted performance with **higher Sharpe ratios**.

## Key Takeaways
- **Diversification is crucial**: Adding international and cryptocurrency assets reduced portfolio risk while maintaining competitive returns.
- **Risk-Return Trade-Off**: Higher returns often come with increased volatility; proper asset allocation helps balance this.
- **Efficient Frontier Analysis**: Helps in constructing optimal portfolios based on an investor's risk tolerance.

## Technologies Used
- Python
- NumPy & Pandas
- Matplotlib & Seaborn
- Monte Carlo Simulation

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/your-repo.git
