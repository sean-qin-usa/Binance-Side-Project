Project from September 2024 - April 2025

Data used was 1s samples from 2025 on BTC and ETH from the Binance website. 

https://data.binance.vision/?prefix=data/spot/daily/klines/ETHUSDT/1s/ 

While the model itself doesn't seem to generate positive returns (even pre-fees and live implementation), this was still a valuable learning experience in data processing, data analysis, modelling (specifically financial models), machine learning (OLS), as well as learning to debug efficiently and format code cleanly to an industry standard. 

I look forward to future projects which may build on the skills cultivated here as well as new ventures into the coding and financial industry.


Details:

- Researched a pair trading strategy in the crypto market using Binance data; added rolling OLS hedge ratios (time-varying β), cointegration residuals, and z-score entry/exit logic with hysteresis, stop-loss, and max-hold.

- Wrote Python program to download market data; processed and analyzed the data visually and statistically; calculated beta and spread between different pairs; implemented one-bar execution delay, per-leg transaction/spread costs, turnover accounting, volatility targeting on residual risk, and visualizations of residuals, thresholds, and cumulative PnL.

- Used scikit-learn to fit linear predictive models for trading signals; added a walk-forward grid search to tune beta window, entry/exit bands, and volatility targets; reported Sharpe, hit rate, and turnover.
