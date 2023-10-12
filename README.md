# Exploratory Data Analysis (EDA) for Udemy and Weather Analysis
This is a project which helps to works on real Data using Python.
##Projects
 - [Udemy Exploration](https://github.com/Thilagavijayan/Data_Analysis_Projects/blob/main/udemy_py.ipynb)
 - [Weather Exploration](https://github.com/Thilagavijayan/Data_Analysis_Projects/blob/main/Weather.ipynb)
## UDEMY EXPLORATION
Udemy Courses Dataset is analyzed in a very Easy To Understand (ETU) language.
### Udemy Dataset
[Click Here to Download](https://drive.google.com/file/d/1zglnQkX756nfySz9RT8V3p1R6-69RHmS/view)
### Commands
* import pandas as pd -- To import Pandas library.
* pd.read_csv - To import the CSV file in Jupyter notebook.
* head() - It shows the first N rows in the data (by default, N=5).
* unique( ) - It shows the all unique values of the column.
* value_counts - In a column, it shows all the unique values with their count. It can be applied to a single column only.
* df[df.Col_1 = = ‘Element1’] - Filtering – We are accessing all records with Element1 only of Col_1.
* df.sort_values(‘Col_name' ,  ascending=False ) - To sort the dataframe wrt any column values in descending order.
* df[ (df.Col1 = = ‘Element1’) & (df.Col2 == ‘Element2’) ] - Multilevel filtering - And Filter – Filtering the data with two & more items.
* str.contains('Value_to_match’) - To find the records that contains a particular string.
* dtypes - To show datatypes of each column.
* pd.to_datetime(df.Date_Time_Col) - To convert the data-type of Date-Time Column into datetime[ns] datatype.
* dt.year - Creating a new column with only year values.
* df.groupby(‘Col_1’)['Col_2'].max() - Using groupby with two different columns.
## WEATHER EXPLORATION
Weather data is analysed in same method did in udemy exploration but using different Commands.
### Weather Dataset
[Click Here to Download](https://drive.google.com/file/d/1JvD4Ss2yS3d9X36YkWqmqZXLamNWLSFJ/view)
### Commands
* head() - It shows the first N rows in the data (by default, N=5).
* shape - It shows the total no. of rows and no. of columns of the dataframe
* index - This attribute provides the index of the dataframe
* columns - It shows the name of each column
* dtypes - It shows the data-type of each column
* unique() - In a column, it shows all the unique values. It can be applied on a single column only, not on the whole dataframe.
* nunique() - It shows the total no. of unique values in each column. It can be applied on a single column as well as on the whole dataframe.
* count - It shows the total no. of non-null values in each column. It can be applied on a single column as well as on the whole dataframe.
* value_counts - In a column, it shows all the unique values with their count. It can be applied on a single column only.
* info() - Provides basic information about the dataframe.
