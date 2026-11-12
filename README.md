# Yield-Curve Modelling with Cubic Spline Interpolation

An applied fixed-income project exploring yield-curve interpolation using **cubic splines**, supported by a Python notebook and an Excel workbook.

A yield curve maps interest rates to maturities. Since observable market instruments do not trade at every possible maturity, interpolation estimates rates between available market observations.

## Repository Contents

- `Cubic_Spline_Interpolation.ipynb` — Python implementation and analysis of cubic spline interpolation.
- `Modeling-Yield-Curves.xlsx` — spreadsheet-based yield-curve modelling workbook.

## Methodology

The project explores observed yield/maturity points, interpolation between discrete maturities, cubic spline methods for producing a smooth curve, and interpolated values across the maturity spectrum. Consult the notebook and workbook for the exact input curve, spline boundary conditions, and numerical implementation.

## Technology

Python · NumPy · pandas · SciPy · Matplotlib · Jupyter Notebook · Microsoft Excel

## Run the Python Notebook

```bash
pip install numpy pandas scipy matplotlib jupyter
jupyter notebook
```

Open `Cubic_Spline_Interpolation.ipynb` and execute the cells. The Excel workbook can be opened separately in Microsoft Excel or a compatible spreadsheet application.

## Fixed-Income Considerations

Interpolation is not the same as bootstrapping. A smooth interpolated yield curve does not automatically represent a no-arbitrage discount curve. Instrument selection, compounding and day-count conventions, curve methodology, and boundary conditions can materially affect the result.

## Disclaimer

Educational numerical-finance project. Not a production curve-construction system or investment advice.
