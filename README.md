# Coffee Shop Sales Analysis

## 1. Problem & User

Coffee shop owners need data‑driven insights to optimize staffing, pricing, and promotions. This project analyzes transaction data to identify peak hours, weekday/weekend differences, seasonal trends, popular drinks, and price elasticity.

## 2. Data

- **Source**: Kaggle – Daily Coffee Transactions
- **Access date**: 8 April 2026
- **Key fields**: hour_of_day, weekday, month, coffee_name, money, cash_type
- **Size**: ~6,000 transactions

## 3. Methods

- Data cleaning and feature extraction (hour, weekday, month) using pandas
- Aggregation analysis to find sales patterns by time, product, and price
- Price elasticity analysis by dividing transactions into price brackets
- Visualisation with matplotlib and seaborn (bar charts, line plots, histograms)

## 4. Key Findings

- **Peak hour**: 10:00 with 328 transactions
- **Weekday vs weekend**: Weekdays are 1.2× busier than weekends
- **Peak season**: March with 494 transactions
- **Most popular drink**: Americano with Milk
- **Best‑selling price range**: 20–30 yuan
- **Highest average spending**: 7:00 (9.5 yuan)

## 5. How to Run

1. Clone this repository
2. Install dependencies: `pip install pandas matplotlib seaborn`
3. Open `mini_assessment.ipynb` in Jupyter Notebook
4. Run all cells

## 6. Product Link / Demo

An interactive AI agent based on this analysis is available at:  
[https://www.coze.cn/store/agent/7626221777488298047](https://www.coze.cn/store/agent/7626221777488298047)

The agent answers natural language questions and provides marketing suggestions with economic explanations (e.g., peak‑load pricing, anchoring, bundling).

## 7. Limitations & Next Steps

- **Limitations**: Single‑store data, no weather or location variables, payment method mostly card
- **Next steps**: Add multi‑store data, integrate weather API, use LLM intent recognition for more flexible queries
