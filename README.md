# Retail_DataAnalysis
KAJAL BURAD KU2407U538
KHUSHI JAIN KU2407535
JINAL VISHAL KU2407U536
VANSH KABRA 

Aim : The purpose of this program is to analyze sales, discount, and profit trends from a dataset of a superstore's sales records. The program processes the data, cleans it, and performs an analysis by grouping the data by months and years. It then visualizes trends for sales, discount, and profit over time using various plots.
Tools and Libraries Used :
Pandas: For data manipulation, cleaning, and analysis.
Matplotlib: For creating visualizations such as line plots to show trends in sales, discount, and profit over time.
Python: Programming language used for data analysis.

DATA SOURCE : KAGGLE


Execution Steps
1 Data Loading: The dataset is loaded from a CSV file (Sample - Superstore.csv.zip) using pandas.read_csv() with the proper encoding ('latin1').
2 Data Cleaning:
Unnecessary columns such as Row ID, Order ID, Customer ID, etc., are dropped.
Any duplicates in the dataset are removed.
Negative profit values are converted to positive using abs().
3 Data Transformation:
The Order Date column is converted to datetime format.
The data is grouped by month and year to compute the total sales, discount, and profit.
4 Trend Analysis:
Monthly and yearly trends are computed by summing the sales, discount, and profit within each period.
Average values for monthly trends are calculated for comparison.
5 Visualization:
Line plots are created to visualize trends for sales, discounts, and profits.
The average values are displayed as dashed lines for reference.


Summary of Results :
The analysis generates line plots that visualize the trends in sales, discount, and profit on both monthly and yearly bases.
The average values of sales, discount, and profit are included for each trend, providing a benchmark for comparison.
The dataset showed varying trends, with periods of high sales and profit, as well as notable fluctuations in discount usage.

Challenges Faced:
Data Cleaning: Handling negative profit values and ensuring that the dataset is free from duplicates required attention.
Date Format Issues: Converting the Order Date from string to datetime format without errors was essential for correct grouping by time periods.
Handling Missing or Corrupt Data: Ensuring the dataset had no missing values or corrupted entries that would affect the analysis.







