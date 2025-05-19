# Demand Forecasting for a Retail Store

## Overview

This project demonstrates demand forecasting for retail products using the "Historical Product Demand" dataset. The workflow covers data cleaning, aggregation, visualization, ARIMA modeling, and forecast evaluation.

## Dataset

- **Source:** [Kaggle - Product Demand Forecasting](https://www.kaggle.com/datasets/felixzhao/productdemandforecasting)
- **File:** `Historical Product Demand.csv`
- **Fields:**
  - `Product_Code`
  - `Warehouse`
  - `Product_Category`
  - `Date`
  - `Order_Demand`

## How to Run

1. Clone or download this repository.
2. Open `demand_forecasting.ipynb` in Jupyter Notebook or VS Code.
3. Run all cells in order.  
   Required libraries: `pandas`, `numpy`, `matplotlib`, `statsmodels`.

To install dependencies: `pip install pandas numpy matplotlib statsmodels`


## Project Steps

1. **Data Loading:** Read and preview the dataset.
2. **Data Cleaning:** Handle missing values and convert data types.
3. **Aggregation:** Aggregate demand by date and resample to weekly totals.
4. **Visualization:** Plot trends in daily and weekly demand.
5. **Forecasting:** Fit an ARIMA model to the training data.
6. **Evaluation:** Forecast and compare to actual demand for the test period.

## Results

- The ARIMA model provides a baseline forecast for weekly demand.
- The model captures overall trends but may miss sudden spikes or drops.
- Further improvements could include using advanced models or more granular features.

## Author

- Nitin Nandan
- Internship Project for CodeClause
