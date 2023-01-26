# Read-from-CSV

## AIM:
To write a program for reading a csv file.
## ALGORITHM:
### Step 1:
Import pandas library using import statement.
### Step 2:
Read the contents of the given csv file using read_csv() method and pass the name of the file with '.csv' extension as the argument. Make sure that the data file and the python program are saved in the same location, otherwise mention the file's full path.
### Step 3:
Display the first few indices of the file using head() method and pass required number of indices as the argument. The default number of indices displayed is 5.
### Step 4:
Display the number of rows and columns of the file using len() and axes() method and pass argument as 0 to display row and 1 to display column.

## PROGRAM:
```
'''
#Program for reading a csv file.
#Developed by: mallu jagadeeswar reddy
#RegisterNumber: 22001910
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("column",len(df.axes[0]))
print("rows",len(df.axes[1]))
```
## OUTPUT:
![214321315-4c5b02de-2e89-4049-b647-e4427c654638](https://user-images.githubusercontent.com/120623104/214892461-baaee318-ce7d-424b-b70f-1470cf065fcf.jpg)

## RESULT:
Thus the python program to read contents from a csv file is successfully executed.
