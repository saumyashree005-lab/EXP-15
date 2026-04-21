# NAME: SAUMYA SHREE
# PRN: 25070123161
# Part A: Data Normalization and Data Type Conversion
# Theory:
* Data normalization is the process of scaling numerical values into a common range while preserving differences between values.
a) Creating Dataset: Imports required libraries:
pandas → data handling numpy → numerical operations.
b) Min-Max Normalization: Rescales the data to a fixed range, usually 0 to 1, by subtracting the minimum and dividing by the range.



# Part B: Turning categorical variables into quantitative variables in Python
Data encoding is the process of converting categorical data into numerical form so that machine learning models can process.

It Label encoding assigns a unique integer to each category (e.g., Male = 1, Female = 0) but may introduce unwanted ordering.

One-hot encoding creates separate binary (0/1) columns for each category and avoids any ordinal relationship.

Dummy encoding is similar to one-hot encoding but drops one column to avoid redundancy and multicollinearity.

Required libraries include Pandas for data handling, NumPy for numerical operations, and Scikit-learn for encoding techniques.

# Important functions used are:

* pd.DataFrame() → create structured dataset from lists/dictionaries/arrays for analysis

* pd.read_csv() → load dataset from CSV file into DataFrame

* head(), tail() → preview first/last few rows of dataset

* info() → display dataset structure, column types, and non-null values

* describe() → generate statistical summary (mean, std, min, max, percentiles)

* min(), max() → find minimum and maximum values for range calculation

* mean(), std() → compute average and standard deviation for data distribution

* median() → find middle value of dataset

* value_counts() → count frequency of unique values in a column

* isnull(), notnull() → detect missing values in dataset

* dropna() → remove missing/null values

* fillna() → replace missing values with mean/median/constant

* get_dummies() → perform one-hot encoding by creating binary columns for categories

* LabelEncoder() → convert categorical labels into numerical form

* fit_transform() → fit encoder and transform data in one step

* astype() → change data type of a column

* rename() → rename column labels

* drop() → remove columns or rows from dataset

* apply() → apply function across rows or columns

* map() → map values using dictionary or function

* sort_values() → sort dataset based on column values

* groupby() → group data for aggregation and analysis

Overall, normalization ensures all numerical features are on the same scale, and encoding ensures categorical data becomes usable, making both essential steps in data preprocessing.

# Conclusion :
The experiment successfully demonstrates how raw data can be transformed into a structured and machine-friendly format using normalization and encoding techniques.
