# Assignment5
data archive activity
# Loading necessary libraries
import pandas as pd
import matplotlib.pyplot as plt
%matplotlib inline
These are the libraries using import function.
# df = pd.read_csv("/C:/Users/Guest 1/Documents/Data analytics Adarsh/1200 sub/PythonData1200/HousingNew.csv.csv")
here we read and load the data set of housingNEw.csv file from harddrive.
# df.head()
Using head function in python we can retrive first five rows from the data.
# df.tail()
Using tail function in python we retrive last five rows froms the dataset.
# df
this function is called Dataframe function which is used for retrive the row,coloum and index.
# df.shape
This shape function we used for to get shape of data.
# df.size
By using Size function we can retrive the size of the dataset.
# df.info()
The info() functiomn is used to print a concise summary of a dataframe.
# df1 = df.drop('ID', axis=1)
Here the the drop() function we used to drop ID lebel from row & coloum.
# df1.describe()
Using the desrice function,we can get key insights from the dataset.as in this data set by doiscribe function we get mean,median,mode,standard deviation,first inter-quartile,third interquartile and difference of inter-quartile.
# df1.describe().T
This function we used for transpose the dataset.
