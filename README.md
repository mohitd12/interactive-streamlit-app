# Interactive Sales Dashboard (Streamlit)

A simple Streamlit app to upload sales data and visualize **Sales** or **Profit** by region using interactive charts.

## Features
- Upload CSV/Excel sales data
- Preview dataset
- View total sales/profit
- Region-wise aggregation
- Bar, Line, and Pie charts
- Download processed results as CSV

## Required Columns
Your data file must include:
- `region`
- `sales`
- `profit`

## Run Locally
```bash
pip install streamlit pandas matplotlib
streamlit run app.py
