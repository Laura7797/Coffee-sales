# Coffee Sales Analysis for Small Business Decision-Making

## Executive Summary

This project analyses coffee shop transaction data to support more evidence-based decision-making for small business managers. Using the Kaggle `Daily Coffee Transactions` dataset, the notebook applies Python-based cleaning, descriptive analysis, visualisation, and revenue analysis to identify demand and sales patterns. The results show a clear weekday sales advantage, a 10:00 peak transaction hour, strong demand in the `30-50` price band, and March as the strongest month by transaction volume and revenue. These findings support practical actions in staffing, pricing, promotions, and product prioritisation.

## 1. Problem & User

This project analyses coffee shop transaction data to support more evidence-based business decisions. The main target user is a coffee shop manager or small business owner who wants practical insights on peak demand, customer spending, product popularity, and revenue trends.

## 2. Data

- Dataset: `Daily Coffee Transactions` from Kaggle
- Access date used in the coursework: `08 April 2026`
- Local data file in this repo: `data/coffee_sales.csv`
- Number of records analysed: `3547`
- Key fields:
  - `hour_of_day`
  - `money`
  - `coffee_name`
  - `Weekday`
  - `Month_name`
  - `Time_of_Day`
  - `Date`

## 3. Methods

The analysis was completed in Python using a Jupyter Notebook workflow.

Main steps:

1. Import `pandas`, `matplotlib`, `seaborn`, and `numpy`
2. Load the transaction dataset using a relative path
3. Check missing values and basic data structure
4. Clean and rename columns for analysis
5. Perform descriptive analysis on transactions, products, and price levels
6. Analyse hourly, weekday/weekend, and monthly transaction patterns
7. Visualise the main outputs using exported charts
8. Add a revenue analysis section covering monthly revenue and average order value
9. Summarise findings and interpret them in a business context

## 4. Key Findings

- The busiest trading hour is `10:00`, with `328` transactions.
- Weekday sales volume is much higher than weekend sales volume: `2658` versus `889`.
- `March` is the peak month in this dataset, with `494` transactions.
- The two most popular drinks are `Americano with Milk` and `Latte`.
- The strongest transaction price band is `30-50`, with `2345` purchases.
- The average order value is `$31.65`, and the highest monthly revenue occurs in `March`.

## Business Recommendations

- Increase staffing coverage around the `10:00` peak period to reduce waiting time and support service quality.
- Keep the `30-50` price band as the core pricing zone because it captures the strongest share of demand.
- Use weekend promotions to stimulate volume, since weekday transactions clearly exceed weekend transactions while average spending remains similar.
- Prioritise best-selling drinks such as `Americano with Milk` and `Latte` in menu visibility, stock planning, and campaign design.

## 5. How to Run

1. Open `notebooks/notebook.ipynb` in Jupyter Notebook, JupyterLab, or VS Code.
2. Keep the repository structure unchanged, especially `data/coffee_sales.csv` and the `figures/` folder.
3. Run all cells from top to bottom.
4. The notebook will save the chart outputs into the `figures/` folder.
5. Review the printed outputs and exported figures.

Packages used in the notebook are listed in `requirements.txt`.

## 6. Product Link / Demo

- GitHub repository: [Laura7797/Coffee-sales](https://github.com/Laura7797/Coffee-sales)
- Main notebook demo: `notebooks/notebook.ipynb`
- Example output figure:

<img src="./figures/transaction_values_distribution.png" alt="Distribution of Transaction Values" width="700">

If the image does not render in a local preview, open it directly from:
`figures/transaction_values_distribution.png`

## 7. Limitations & Next Steps

Limitations:

- The dataset reflects one business context, so the findings are not fully generalisable.
- The analysis is descriptive rather than predictive.
- Some behavioural economics discussion is interpretive and should not be treated as causal proof.
- External factors such as weather, promotions, store location, and customer demographics are not included.

Next steps:

- Extend the analysis with forecasting or segmentation methods
- Compare multiple stores or multiple periods for stronger conclusions
- Build a cleaner interactive demo if the coursework later requires a product layer

## Repo Structure

- `README.md`
- `requirements.txt`
- `data/coffee_sales.csv`
- `notebooks/notebook.ipynb`
- `figures/transaction_values_distribution.png`
- `figures/hourly_transactions.png`
- `figures/monthly_transaction_trend.png`
- `figures/average_spending_by_hour.png`
- `figures/price_range_demand.png`
- `figures/drink_price_vs_popularity.png`
- `figures/monthly_revenue_trend.png`

## Coursework Note

This repository is prepared for the `track2` direction, focusing on a documented Python analysis project with a clearer structure, stronger reproducibility, and a more professional GitHub presentation.
