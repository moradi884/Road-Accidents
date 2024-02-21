This Jupyter Notebook file, Cleaned_Data.ipynb, is used for cleaning road traffic accident statistics data.

File Contents
The Cleaned_Data.ipynb file contains the following:

Reading the CSV File: First, the CSV file is read using the read_csv() function from the pandas library. This function allows for reading CSV files with the appropriate format.

Removing Invalid Rows: Using the dropna() function from the pandas library, rows with invalid or missing values are removed.

Changing Data Types: Using functions such as astype() from the pandas library, different data types, such as strings, can be converted to integers.

Cleaning Duplicate Data: Using the drop_duplicates() function from the pandas library, duplicate data in specified columns is removed.

Cleaning Inappropriate Data: Using functions like str.contains() from the pandas library, data that does not follow specific patterns or violates certain rules can be identified and potentially removed.

Cleaning Outliers: Using statistical methods such as outliers detection, data points that are considered outliers or unusual are identified and examined for potential removal.

Displaying Data: Using display functions such as head() and tail() from the pandas library, a portion of the cleaned data is displayed.

Important Notes
This Cleaned_Data.ipynb file is used for cleaning road traffic accident statistics data.

The relevant CSV file has the name "dft-road-casualty-statistics-casualty-provisional-mid-year-unvalidated-2022.csv".

The pandas and matplotlib.pyplot libraries are used in this file for data cleaning operations and visualization purposes.

Please ensure that the required CSV file is in the correct path and that the necessary libraries are installed before executing the Cleaned_Data.ipynb file.