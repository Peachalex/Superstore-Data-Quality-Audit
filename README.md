# Trust but Verify: A Superstore data quality audit project

## Description
The data quality assessment of the Superstore sales data is to determine whether it is suitable for the business reporting (e.g, financial and operational reporting)

## Business question
Can the exesctives trust the Superstore dashboard to make decisions about the regional sales. discount strategy, and profitability?

The executives rely on the allocated and cleaned data, visualized through the composite dashboard, to develop strategy and make high-stakes decisions. If the underlying data cannot be trusted, neither can the decisions built upon it. This project audits the data across six dimensions to answer the trust question with evidence.

## Structure
```
.
├── [composite_scorecard.png](composite_scorecard.png)
├── data
│   ├── Superstore_Orders_q1.csv
│   └── Superstore_Orders_q2.csv
├── notebooks
│   ├── [01_completeness.ipynb](notebooks/01_completeness.ipynb)
│   ├── [02_validity.ipynb](notebooks/02_validity.ipynb)
│   ├── [03_uniqueness.ipynb](notebooks/03_uniqueness.ipynb)
│   ├── [04_timeliness.ipynb](notebooks/04_timeliness.ipynb)
│   ├── [05_consistency.ipynb](notebooks/05_consistency.ipynb)
│   ├── [06_accuracy.ipynb](notebooks/06_accuracy.ipynb)
│   └── [07_composite_scorecard.ipynb](notebooks/07_composite_scorecard.ipynb)
└── README.md
```

## Composite Data Quality Scoreboard
![Composite Scoreboard](composite_scorecard.png)
