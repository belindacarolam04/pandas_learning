# Pandas Learning

Hands-on practice repo for learning Pandas — built while preparing for a data science career. Each notebook focuses on one core topic, applied on real datasets (Breast Cancer Wisconsin dataset, Pima Diabetes dataset) rather than toy examples.

## Notebooks

**Data_Selection.ipynb**
- `loc` and `iloc` basics
- Single row, multiple rows, row range selection
- Selecting a single value
- Selecting entire rows/columns
- Conditional selection

**Filtering.ipynb**
- Multi-condition filtering using `&` and `|`
- `isin()`
- `between()`
- `query()`
- `filter()`

**Sorting.ipynb**
- `sort_values()` — single column
- `sort_values()` — multiple columns with mixed ascending/descending order
- `sort_index()`
- `nlargest()` and `nsmallest()`

**Missing_Value_Prediction.ipynb**
- Detecting missing values with `isnull()` / `notnull()`
- Counting nulls per column and total
- Percentage of missing values per column
- Filtering rows/columns containing nulls

**Handling_Missing_Values.ipynb**
- Dropping missing values — `dropna()` with `how`, `thresh`, `subset`
- Dropping a column based on missing percentage
- Filling missing values — constant, mean, median
- Forward fill and backward fill
- Duplicate value detection

**Value_Counts.ipynb**
- `value_counts()`
- Unique value analysis

**Groupby.ipynb**
- Grouping data by category
- Aggregations on grouped data

**PIVOT_TABLE.ipynb**
- Reshaping data using `pivot_table()`

**MERGE.ipynb**
- Inner join, outer join
- Merging on different column names
- Merging on multiple columns
- Handling duplicate column suffixes
- Merging on index

## Approach

- Every topic is practiced on a real dataset

## Datasets Used

- [Breast Cancer Wisconsin (Diagnostic) Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- Pima Indians Diabetes Dataset (missing values)

## Related Repos

- [numpy_learning](https://github.com/belindacarolam04/numpy_learning) — NumPy probability distributions
