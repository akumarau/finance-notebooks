# 📊 Finance Notebooks

A small collection of Python/Jupyter notebooks exploring personal finance and equity valuation —
part personal project, part coursework alongside my **Master of Applied Finance (UNSW)**.

Each notebook is built from first principles with clearly labelled assumptions, worked formulas,
and charts, so the models are easy to follow and easy to re-run with your own numbers.

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](LICENSE)

---

## Notebooks

### 1. [Personal Finance Calculator](personal_finance_calculator.ipynb)

A personal toolkit for everyday money questions, in AUD and using the Australian superannuation
system. Five small models:

- **Budget split** — the 50/30/20 rule
- **Savings growth** — future value of regular contributions and the power of compounding
- **Loan / mortgage** — repayments, full amortisation schedule, and lifetime interest
- **Superannuation** — a projection to retirement with contributions, wage growth, and returns
- **Financial independence (FIRE)** — the 4% rule and years-to-FI

### 2. [Equity Valuation — A Worked Example](stock_price_valuation.ipynb)

The standard valuation toolkit applied to one illustrative company, comparing what each method
implies for intrinsic value:

- **Cost of capital** — CAPM and WACC
- **Dividend Discount Model** — Gordon Growth and a two-stage variant
- **Discounted Cash Flow** — FCFF forecast, terminal value, enterprise → equity value
- **Relative valuation** — peer P/E and EV/EBITDA multiples
- **Sensitivity analysis** — a WACC × terminal-growth heatmap
- **Summary** — a "football field" of valuation ranges vs the market price

> ⚠️ The valuation notebook is an **educational exercise** using illustrative assumptions.
> It is **not investment advice** and not a recommendation on any security.

---

## Running the notebooks

```bash
pip install -r requirements.txt
jupyter notebook
```

Then open either file in the `notebooks/` folder. Every assumption sits at the top of its cell —
change the numbers and the outputs and charts update. The notebooks run fully offline; the
valuation one includes an optional `yfinance` cell (commented out) to pull live market data.

## Tech

Python · Jupyter · NumPy · pandas · Matplotlib

## License

[MIT](LICENSE)
