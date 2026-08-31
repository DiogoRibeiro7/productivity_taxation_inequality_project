# Productivity, Taxation, Inequality, and Poverty

This repository contains a Jupyter notebook that tests the claim:

> Productivity growth, not taxation, has been the most proven way to fix inequality and poverty.

The notebook does not argue that growth is irrelevant. It argues that the slogan is too broad and mixes together distinct questions about poverty, inequality, and redistribution.

## What the notebook does

The analysis is organized around four separate tests:

1. Whether countries with higher GDP per capita tend to have lower extreme poverty.
2. Whether GDP per capita alone explains cross-country inequality.
3. Whether taxes and transfers measurably reduce inequality in the data.
4. Whether U.S. productivity growth automatically shows up in typical worker pay.

## Repository contents

- `productivity_taxation_inequality_rebuttal.ipynb`: the main notebook, already executed with saved outputs for GitHub rendering.
- `data/`: cached source CSV files used by the notebook.
- `outputs/`: generated charts and summary CSV files written by the notebook.
- `requirements.txt`: Python dependencies for local execution.

## Data sources

- Our World in Data Grapher datasets.
- World Bank Poverty and Inequality Platform data via OWID.
- OECD Income Distribution Database via OWID.
- FRED / U.S. Bureau of Labor Statistics.

## Results at a glance

The notebook supports a narrower claim than the social-media post:

- Higher GDP per capita is strongly associated with lower extreme poverty across countries.
- GDP per capita does not mechanically determine inequality.
- Taxes and transfers measurably reduce income inequality.
- U.S. productivity gains do not automatically translate into comparable growth in typical worker earnings.

## Running locally

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter lab
```

Then open `productivity_taxation_inequality_rebuttal.ipynb`.

The notebook uses local cached CSV files under `data/` and writes figures and summary tables under `outputs/`.

## Note on interpretation

The central analytical distinction is simple: poverty and inequality are not the same thing. GDP per capita is an average, while inequality is a distributional property. A poverty-versus-income chart cannot, by itself, establish claims about taxation or the distribution of gains.

## Licence

Code is [MIT](LICENSE). Data, derived tables and manuscript text are
[CC BY 4.0](LICENSE-DATA.md). Third-party source data keeps its provider's terms — see
[`LICENSE-DATA.md`](LICENSE-DATA.md).
