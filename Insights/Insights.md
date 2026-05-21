Project goal:

This project explores COVID-19 case, death, and vaccination data across countries using Python, pandas, SQL, and visualization. The goal is not only to practice a complete data analysis workflow, including data cleaning, exploratory analysis, SQL querying, and interpretation.

Key insights:

### Insight 1: SQL and pandas support different stages of the workflow

SQL was most useful for answering focused, structured questions, such as generating grouped summaries and filtering specific subsets of data. Pandas was more useful for trend exploration, feature engineering, and preparing data for visualization. In this project, SQL helped me ask precise questions, while pandas helped me preclean and preprocess the dataset(feature engineering) and explore evolvement patterns on finer scale.

### Insight 2: Trend analysis provides more context than isolated summary statistics

SQL summary tables were useful for identifying maximum values, averages, and country-level rankings. However, these summary numbers alone do not explain when changes happened or how patterns evolved over time. The rolling-average trend plots provided more context by showing waves, turning points, and long-term changes. This suggests that summary statistics and time-series visualization should be used together rather than separately.

### Insight 3: Data reliability should be evaluated as part of the analysis

This project shows that public health data should not be interpreted mechanically. Sudden jumps, missing values, or unusually smooth trends may reflect reporting practices rather than real-world changes. For example, vaccination data may be affected by delayed reporting or batch updates. Therefore, data cleaning is not only about removing missing values; it is also about understanding how the data was generated and what kinds of bias may exist.
