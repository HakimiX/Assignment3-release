# Assignment 3

### 1. Read the entire dataset of Danish housing sales data, see Assignment 2, into a Pandas DataFrame. Use the read_csv function from the pandas module.

To combine all of the csv files into one file we used the following bash command 

`cat 1050-1549.csv; tail -n +2 -q *csv > datall.cs`

We had problems with the dataframe and was not able to read the whole dataset of danish housing sales data. We were able to read 2210225 lines and the application crashed. The scatter plot of the data is also incomplete because of the lack of data from our dataframe. 

### 2. Geocode the entire dataset of danish housing data

We were able to geocode 2210225 lines 


### 3. Scatter plot

![Text](https://github.com/HakimiX/Assignment3-release/blob/master/scatterplot.png)