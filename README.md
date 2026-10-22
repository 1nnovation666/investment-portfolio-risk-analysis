# Investment Portfolio & Risk Analysis

I built this Excel model to compare three ETF portfolios and understand how different stock and bond allocations affected returns and risk over 2016–2025.

[Excel workbook](Portfolio_Risk_Analysis.xlsx) · [Full report](Investment_Portfolio_Risk_Analysis_Report.pdf)

## Portfolio Setup

Each portfolio starts with $10,000 and rebalances monthly.

| ETF | Conservative | Balanced | Growth |
|---|---:|---:|---:|
| IVV — U.S. large-cap stocks | 30% | 45% | 60% |
| IXUS — International stocks | 10% | 15% | 20% |
| IEF — U.S. Treasury bonds | 60% | 40% | 20% |

## Results

| Metric | Conservative | Balanced | Growth |
|---|---:|---:|---:|
| Ending Value | $18,225 | $22,783 | $28,216 |
| Annualized Return (CAGR) | 6.19% | 8.58% | 10.93% |
| Annualized Volatility | 7.57% | 9.53% | 11.93% |
| Maximum Drawdown | -19.21% | -21.03% | -22.86% |
| Sharpe Ratio | 0.56 | 0.70 | 0.76 |

The Growth portfolio had the highest return and Sharpe ratio over this period, but also the largest drawdown. The Conservative portfolio was less volatile, although its worst month-end decline was still about 19%.

One takeaway from the comparison is that a larger bond allocation reduced volatility but did not prevent substantial losses.

## Data and Calculations

I used monthly adjusted prices from Yahoo Finance and monthly risk-free returns from the Kenneth French Data Library. The workbook calculates returns, portfolio values, drawdowns, correlations, and risk metrics using Excel formulas.

Open the Dashboard sheet for the summary and charts. The other sheets contain the inputs and calculations.

The analysis excludes trading costs and taxes. Drawdowns use month-end values, so they may miss larger declines within a month. Results reflect this historical sample, not a forecast.
