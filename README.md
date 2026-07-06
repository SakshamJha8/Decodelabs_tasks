### &#x20;             ***Project 1: Advanced EDA and Feature Engineering***



\# Objective:



Perform Exploratory Data Analysis (EDA) on the dataset.

Clean and preprocess the data.

Handle missing values and duplicate records.

Analyze data distribution and detect outliers.

Create new features to improve the dataset for future machine learning or analytics tasks.





\# Steps Performed:



1\.Imported required Python libraries (Pandas, NumPy, Matplotlib, Seaborn).



2\.Loaded the dataset and explored its structure using info(), describe(), head(), and shape.



3\.Checked data types and converted the Date column into datetime format.



4\.Analyzed categorical columns using frequency counts and unique values.



5\.Identified missing values and filled missing CouponCode entries with "No coupon".



6\.Removed duplicate records.



7\.Extracted Year, Month, and Day from the Date column.



8\.Examined the distribution of UnitPrice and TotalPrice using histograms.



9\.Calculated descriptive statistics, skewness, and kurtosis.



10\.Filled missing values in TotalPrice using the median.



11\.Removed invalid records with zero or negative TotalPrice.



12\.Detected outliers in TotalPrice using the IQR (Interquartile Range) method.



13\.Performed Feature Engineering by creating:

PricePerItem

CartUtilization

IsReferred



14\.Exported the cleaned and transformed dataset as cleaned\_data.csv.

Output:

Cleaned and preprocessed dataset with improved data quality.

Missing values and duplicates handled successfully.

Outliers identified for further analysis.

New features generated to enhance predictive analysis.

Final processed dataset saved as cleaned\_data.csv.



\# Tools Used:

Python

Pandas

NumPy

Matplotlib

Seaborn

