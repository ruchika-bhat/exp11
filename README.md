# AIM: CREATE DATASET AND LOAD DATASET IN PANDAS LIBRARY

# THEORY:
In this experiment, the Pandas library is used to create and load datasets for data analysis.

# Dataset Creation:
A dataset is created using a dictionary in Python. The dictionary contains the following fields:
Roll_No.
Gender
Department
CGPA
Each key represents a column and the values represent the data entries.
This dictionary is converted into a DataFrame using:

pd.DataFrame(data)
Thus, a structured dataset is created in tabular form.

# Loading Dataset:
An external dataset is loaded using:
pd.read_csv()
In this experiment, the file Cars93.csv is loaded into a DataFrame (df1) for further analysis.

# Dataset Analysis Functions:
The following Pandas functions are used:

shape → Gives number of rows and columns
describe() → Performs statistical analysis of numerical data
info() → Provides complete information about dataset (data types, non-null values)
size → Returns total number of elements

# Data Display Functions:
head() → Displays first 5 rows
tail() → Displays last 5 rows
sample() → Displays random rows

# Data Checking Functions:
isnull().sum() → Gives sum of all null values
duplicated().sum() → Checks for duplicate rows
nunique() → Gives number of unique values in each column


# CONCLUSION:
In this experiment, we created a dataset using a dictionary and converted it into a DataFrame using Pandas. We also loaded an external dataset using read_csv().
Various functions such as shape, describe(), and info() were used to analyze the dataset.
Functions like head(), tail(), and sample() helped in displaying the data, while isnull(), duplicated(), and nunique() were used to check data quality.
Hence, Pandas helps in efficient creation, loading, and analysis of datasets.






