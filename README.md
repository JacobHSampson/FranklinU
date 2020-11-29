# FranklinU
Data Mining 612

Added assignment 1 from colab.
Loaded the stock market data from frankData612.
Show the .head() and .tail(), printed the column names, print the type of the data and the columns, 
  showed the shape to check number of rows and columns, used groupby to find mean of beta (grouped by date).

10/18/2020 
Added assignment 2 from colab.
Using stock data from frankData612.
Convert data column to a datetime format, subtract the max date from each date to get number of days from max date.
Convert the number of days to number of months, and add the number of months column to the data set. Finally, save the data set as csv.

10/25/2020
Added Assignment 4 from colab.
Imported two baseball data sets from frankData612, people and salaries.
Merged those sets on playerID.
Dropped columns that are irrelevant with missing data ('birthState', 'birthCity', 'deathState','deathCity').
Filled in other columns with missing values with a defaut value.


10/31/2020  
Addd Assignment 5 from colab.
Using stock data from frankData612.
Changed price changes to category type.
Changed beta (3Y Monthly) to string type.

11/15/2020
Added Assignment 6 from colab.
Using stock data from frankData612.
Used regex to separate percent changed and price change columns.
Created a function to return the mean, sum, mode, median, and range.
Note: I could not get this function to work with .apply() method.

11/29/2020
Added Assignment 7 from colab.
Using stock data from frankData612.
Modified the given function to find the difference between the weekly average price_at_close and 1Y target est.
Dropped the require for df.category.isin and used the mean instead of the sum.
