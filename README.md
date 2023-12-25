# Read-from-CSV

## AIM:

## ALGORITHM:
### step 1:
Import pandas as pd.

### Step 2:
Read the CSV file using read_csv

### Step 3:
use head and tail method to get the required contents from the file

### Step 4:
Use len() method to get the number of rows and columns.

### Step 5:
print the output

### PROGRAM:

Developed by: naresh.r
Register Number:23005559
import pandas as pd
df = pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0))
print("NUmber of columns:",len(df.axes[1]))

### OUTPUT:

![Screenshot 2023-12-25 141630](https://github.com/feryjfgkuyfgewjfgew/Read-from-CSV/assets/150319377/3f8e030d-78aa-4519-bd83-cf32d026ddf2)



## RESULT:

thus the output got sucessfully
