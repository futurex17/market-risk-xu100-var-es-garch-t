\# Market Risk Modeling of XU100 using VaR, ES and GARCH (Student-t)



This project models market risk for XU100 (BIST 100) using:

\- Historical VaR / ES (99%)

\- Distribution diagnostics (Skewness, Kurtosis, Jarque-Bera)

\- VaR backtesting (Kupiec unconditional coverage, Christoffersen independence)

\- GARCH(1,1) with Student-t innovations (ARCH package)



\## Key Results (example)

\- Historical 99% VaR: ~4.60%

\- Historical 99% ES: ~6.55%

\- Kupiec test p-value: ~0.84 (passes unconditional coverage)

\- Christoffersen independence p-value: ~0.27 (no clustering evidence)

\- Strong fat tails and negative skewness (JB rejects normality)



\## Files

\- `Market Risk Modeling of XU100 Using VaR, ES and GARCH with Student-t Innovations.ipynb` : main notebook



\## How to Run

```bash

pip install -r requirements.txt

jupyter notebook

