# Investigating the relationship between ESG scores and stock returns
A simple notebook investigating the relationship between ESG scores and returns of S&P 500 companies by constructing decile portfolios based on total ESG scores and comparing the performance of top and bottom portfolios.

To run locally:
- Clone the repo by running ```git clone https://github.com/deniz-o/esg-scores-and-returns.git``` in the terminal or download the zip
- Install dependencies by running ```pip install -r requirements.txt```

## Result Summary
| Portfolio	| Average Return | Standard Deviation | CAPM Alpha | Information Ratio |	5-Factor Alpha | Sharpe Ratio |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| TOP	| 0.0155 | 0.0741	| 0.0049 | 0.2442 | 0.0049 | 0.2442 |
| BOT	| 0.0116 | 0.0646	| 0.0017 | 0.2099	| 0.0017 | 0.2099 |
| DIF	| 0.0039 | 0.0316	| 0.0032	| 0.0343 | 0.0032 | 0.0343 |


| Difference in | Average Return | CAPM Alpha | 5-Factor Alpha |
| ----------- | ----------- | ----------- | ----------- |
| t-statistic | 2.4920 | 0.9104 | 0.3915 |
