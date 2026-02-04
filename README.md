# AI-Value-Chain-Portfolio-Optimisation
Strategic Portfolio Optimisation Across the Foundational Layer of the AI Value Chain

---
**Project Description**
---
Investment professionals have overvalued AI’s impact compared to its current capabilities, leading to extremely high company valuations which provide good returns that ignore the possibility of the progress seen being empty promises. This project will strategically optimise a portfolio of stocks involved in the infrastructure and supply chain supporting the growth of AI. Maintaining a low risk appetite and prioritising growth is the project's objective, which will be completed by developing a Markowitz portfolio, researching and implementing portfolio optimisation techniques, and evaluating and comparing the results to the S&P500 benchmark and previous versions of the portfolio.

---
**Tools Used**
---
- Google Colab - Project Python code and notes
- YFinance Library - Market Data collected from Yahoo Finance
- Pandas Library - Data pre-processed and organised into Pandas dataframes
- MatPlotLib Library - Visualising important results
- PyPortfolioOpt - Portfolio Creation and Optimisation
- NumPy Library - Mathematical Equations (e.g Fractional Kelly Criterion, Volatility)
- Arch_Model Library - Volatility Forecasting
- GitHub - Portfolio Version Control and Project Documentation

---
**Challenges and Limitations**
---
- Company Ticker Changes - Manual replacement with the new stock sticker
- Foreign Currency Stocks - Currency Conversion of all assets into portfolio majority (USD)
- Negative Stock Prices - Auto Adjustment of stock Close prices manipulated stocks to display negative prices
- Fractional Kelly Criterion - Full Kelly Criterion estimates better growth, but 1/2 Kelly is needed to be conservative and eliminate extreme drawdowns
- Portfolio Stock Weights - Portfolio v1 shows many selected stocks with no allocation whatsoever, so better data collection and understanding is required
- Python Library Installation - Installing Arch and PyPortfolioOpt is essential to run the Jupyter Notebook
- Out-of-Sample Testing - Portfolio v1 must be tested on Out-of-Sample data for optimisation technique comparison

---
**Credits**
---
- Fantastic project support from Dr Fang He (University of Westminster), as she saved me countless hours of manual research by recommending to use popular, already analysed, ETF Top 25 Holdings
- "GARCH Models in Python" - DataCamp Course created by Chelsea Yang
- "Introduction to Portfolio Analysis in Python" - DataCamp Course created by Charlotte Werger
- "Quantitative Risk Management in Python" - DataCamp Course created by Jamsheed Shorish 
