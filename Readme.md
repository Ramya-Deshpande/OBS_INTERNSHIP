This folder contains feature engineering steps applied on a csv file.

Steps:
1.Read the csv file.
2.Find number of null values in each column.
3.Assign a threshold and drop columns having percentage of null values greater than threshold.
4.Identify columns with numerical values, replace NaN values by median. Identify categorical null values and replace it by Unknown.
5.Convert categorical values which can actually be numerical but are categorical due to some symbols into numeric by using replace method and regex.
6.Convert height in feet into cm. Use split method to get values before and after "'" used in feet representation. Multiply value before "'" by 30.48 and after "'" with 2.54 and add these values.
7.Convert weight in lbs into kg, use replace method to replace lbs with empty space. The float value must be multiplied by 0.453592 to get weight in kg.
8.Drop some redundant columns like photo, club logo which actually are not useful in analysis.
9.Make sure all columns are consistent and have standard names. Here find unique Best Position and Nationality value to check if there is consistency. Use title method to have all Nationality names in a standard way.
10.Find outliers using IQR.
11.Drop columns with outliers.
12.Check for duplicates and missing values in final dataframe. If none the final data for analysis is ready else follow same feature engineering steps.

Requirements:
1.Pandas
2.Numpy
3.Matplotlib

