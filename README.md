# AlgorithmicTrading

## Dataset
We use ETF data for portfolio composition.
- Sheet1: Stock price of ETF
- Sheet2: Market cap of ETF
- Sheet3: Stop traiding (It is not used.)

## ETF selelction criteria
Two ETFs were selected based on the following criteria:
1. As of the date of back testing, only ETFs listed over 5 years were considered (84 items remaining).
2. Excluding the top 25% volatility (63 items remaining).
3. Select the asset with the highest sharpe ratio.
4. Select the asset with the lowest correlation coefficient from the asset selected in 3.

## Portfolio Composition Ratio
Risky assets: Risk-free asset = 0.85 : 0.15

## Back Test
- Date: 2017.04.16 ~ 2019.04.16
- Window size: 3 / 4 (months)
- Start value: 10,000
- Allow shortsale: Y/N
