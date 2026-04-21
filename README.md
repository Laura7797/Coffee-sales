# Coffee Sales Analysis

This repository presents a mini data analytics project based on coffee shop transaction records. The project explores customer demand patterns, product popularity, and pricing behaviour, then discusses how these insights could support small business decision-making.

The analysis was developed as coursework for `ACC102` and follows a practical workflow: define a business problem, select an appropriate dataset, clean and analyse the data in Python, visualise the findings, and reflect on limitations and possible improvements.

## Project Aim

The project investigates how transaction data can be used to answer business-oriented questions such as:

- When is the shop busiest?
- Are weekdays and weekends different in sales volume?
- Which drinks are the most popular?
- What price range dominates customer purchases?
- How can behavioural economics ideas be used to interpret the results?

## Dataset

- File: `Coffe_sales.csv`
- Source used in the notebook/report: Kaggle daily coffee transactions dataset
- Number of records analysed: `3547`
- Main fields: transaction hour, payment type, amount, coffee name, weekday, month, date, and time

## Tools and Methods

- `Python`
- `pandas` for cleaning and aggregation
- `matplotlib` and `seaborn` for visualisation
- `Jupyter Notebook` for analysis workflow

The main analysis notebook is:

- `Mini Assessment.ipynb`

## Key Findings

The current dataset supports the following descriptive findings:

1. The busiest hour is `10:00`, with `328` transactions.
2. Weekdays are much busier than weekends: `2658` vs `889` transactions.
3. The peak month in this dataset is `March`, with `494` transactions.
4. The two most popular drinks are `Americano with Milk` and `Latte`.
5. The dominant transaction price band is `30-50`, which contains `2345` purchases.
6. Average spending is broadly similar on weekdays and weekends, so this result should be interpreted cautiously.

## Example Visual

The repository includes a histogram showing the distribution of transaction amounts:

![Distribution of Transaction Values](figures%20(amounts).png)

## Repository Structure

- `Mini Assessment.ipynb` - main notebook containing data cleaning, exploratory analysis, charts, and summary insights
- `Coffe_sales.csv` - dataset used for the analysis
- `figures (amounts).png` - exported visual used in the report/README
- `Reflection report.docx` - reflective commentary on the project process, limitations, and learning
- `workflow materials.docx` - supporting workflow notes from earlier development

## How To Run

1. Open `Mini Assessment.ipynb` in Jupyter Notebook or VS Code.
2. Make sure `Coffe_sales.csv` is in the same folder as the notebook.
3. Run the notebook cells from top to bottom.
4. Review the charts and summary outputs.

## Business Relevance

This project is designed for a coffee shop manager or a small business owner who wants to make more evidence-based decisions. The results could help with:

- staff scheduling during peak demand periods
- product focus and menu planning
- pricing strategy discussions
- promotional timing and targeting

## Limitations

- The dataset appears to represent a single business context, so the findings are not universally generalisable.
- The project is descriptive rather than predictive.
- Some behavioural economics interpretations are exploratory and should not be treated as causal claims.
- The dataset has limited external variables, such as weather, promotions, or store location.

## Coursework Notes

This repository is intended to support the `track2` direction of the coursework, where the emphasis is on a documented Python-based analysis project with supporting evidence, visuals, and reflection.

## AI Use Disclosure

AI tools were used during the coursework process to help with:

- debugging Python and workflow logic
- checking the wording of economic interpretations
- improving clarity of written explanations

All outputs were reviewed and adapted to fit the actual dataset and project requirements.
