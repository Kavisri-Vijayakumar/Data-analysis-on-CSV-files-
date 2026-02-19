# Data-analysis-on-CSV-files-
## Objective
Analyze sales data using Pandas to generate basic data insights.

## Tools Used
- Python
- Pandas
- Jupyter Notebook / Google Colab

## Key Concepts
- Pandas
- DataFrame
- Visualization

## Outcome
Basic data insights using Python.

## Hints / Mini Guide
1. Load CSV using Pandas  
2. Use `groupby()`, `sum()`, `plot()`  

## Task Description
In this task, sales data from a CSV file is analyzed using Pandas.  
The dataset is loaded into a DataFrame, explored, filtered, grouped, and visualized using a bar chart.

## Steps Performed
1. Loaded the CSV file using `pd.read_csv()`.
2. Displayed the first 5 rows using `.head()`.
3. Checked the shape of the DataFrame using `.shape`.
4. Verified missing values using `.isna()`.
5. Filtered rows using conditions.
6. Applied `groupby()` and `sum()` to calculate total sales.
7. Generated a bar chart using `.plot(kind="bar")`.
