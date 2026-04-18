# practical10


Aim
To learn and implement core pandas functionalities, including creating Series and DataFrames, accessing data using loc and iloc, modifying datasets, and performing basic statistical filtering.

Theory
1. Pandas Series
A Series is a one-dimensional labeled array capable of holding any data type. It is the fundamental building block of pandas.

2. Pandas DataFrame
A DataFrame is a two-dimensional, size-mutable, tabular data structure with labeled axes (rows and columns). It is essentially a collection of Series sharing the same index.

3. Key Concepts & Commands
Object Creation: pd.Series() creates a Series; pd.DataFrame() converts dictionaries into structured tables.

Metadata Access:

.shape: Returns tuple of dimensions (rows, columns).

.ndim: Returns number of dimensions.

.size: Returns total number of elements.

.columns: Lists column names.

.dtypes: Displays data types of each column.

Data Access:

df["column_name"]: Accesses a specific column.

.loc[row, col]: Accesses data by label/index.

.iloc[index]: Accesses data by integer position.

Data Manipulation:

Column Addition: df["New"] = [...] adds a new feature.

Update: Using .loc or .iloc to modify specific cell values.

Drop: .drop(..., axis=1) removes a column.

Statistical Analysis:

.max(), .min(): Compute extremes.

Boolean Indexing: df[df["Marks"] > 90] filters rows based on a condition.

Conclusion
Through this practical, we successfully executed several data manipulation tasks:

Exploration: We analyzed DataFrame structure using shape, ndim, and dtypes.

Modification: We performed CRUD (Create, Read, Update, Delete) operations, including adding columns, updating specific cell values, and dropping unnecessary data.

Analysis: We applied statistical functions and conditional filtering to extract meaningful insights (e.g., finding top-performing students).

These operations are the prerequisite for effective data cleaning and exploratory data analysis (EDA).
