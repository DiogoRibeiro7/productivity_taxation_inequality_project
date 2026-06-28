# Productivity, Taxation, Inequality, and Poverty Rebuttal Notebook

This project contains a single Jupyter notebook that tests the claim:

> Productivity growth, not taxation, has been the most proven way to fix inequality and poverty.

The notebook does not deny that growth matters. It shows that the claim is too strong.

## Main tests

1. GDP per capita vs extreme poverty.
2. GDP per capita vs inequality.
3. OECD tax-and-transfer redistribution effect on Gini inequality.
4. U.S. productivity growth vs real median weekly earnings.

## Data sources

- Our World in Data Grapher datasets.
- World Bank Poverty and Inequality Platform data via OWID.
- OECD Income Distribution Database via OWID.
- FRED / U.S. Bureau of Labor Statistics.

## How to run

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter lab
```

Then open:

```text
productivity_taxation_inequality_rebuttal.ipynb
```

The notebook downloads data at runtime and caches CSV files under `data/`.
Charts and small CSV summaries are written under `outputs/`.

## Notes

The notebook separates poverty from inequality. This is the central analytical point:
GDP per capita is an average, while inequality is a distributional property.