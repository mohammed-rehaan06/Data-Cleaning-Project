Data Cleaning Project

1. Introduction

This project is about cleaning a sales dataset using Python and Pandas. The main aim is to find and correct errors in the dataset and make it ready for analysis.

2. Objective

* Identify missing values.
* Find and remove duplicate rows.
* Handle missing numerical values.
* Save the cleaned dataset separately.

3. Tools Used

* Python
* Google Colab
* Pandas
* NumPy

4. Dataset Description

The dataset contains sales information with the following columns:

* Order_ID
* Product
* Category
* Quantity
* Sales
* Profit
* Order_Date

5. Data Cleaning Steps

Step 1: Load the Dataset

Loaded the original CSV file using Pandas.

Step 2: Check Missing Values

Checked the dataset for missing values using isnull().sum().

Step 3: Check Duplicate Rows

Used duplicated().sum() to find duplicate rows.

Step 4: Remove Duplicates

Removed duplicate rows using drop_duplicates().

Step 5: Handle Missing Values

Filled missing numerical values using the mean of each numerical column.

Step 6: Save Cleaned Dataset

Saved the cleaned data as cleaned_data.csv.

6. Before and After Cleaning

* Original dataset: 12 rows.
* Duplicate rows found: 1.
* Cleaned dataset: 11 rows.
* Missing numerical values: Filled using column means.

7. Conclusion

In this project, I used Python and Pandas to clean a sales dataset. I removed duplicate rows, handled missing numerical values, and saved the cleaned dataset separately. The cleaned data is now more suitable for further analysis.
