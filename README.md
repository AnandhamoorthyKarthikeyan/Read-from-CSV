# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file
## ALGORITHM:
## Step 1:
Import pandas as pd.

## Step 2:
Read the CSV file using read_csv method.

## Step 3:
Use head and tail method to get the required contents from the file.

## Step 4:
Use len() method to get the number of rows and columns

## Step 5:
Print the output
## PROGRAM:
```
Developed by: ANANDHAMOORTHY.K
Register number: 212222100004
import pandas as pd
f = pd.read_csv('nba.csv')
print(f.head(10))
print(f.tail())
print("Number of rows:",len(f.axes[0]))
print("Number of columns:",len(f.axes[1]))
```

## OUTPUT:
![Screenshot 2023-06-08 105107](https://github.com/AnandhamoorthyKarthikeyan/Read-from-CSV/assets/119475998/b6e5434e-6f69-471f-b2cc-598aa1733a9d)


## RESULT:
Thus a python program is written to read the contents of a CSV file.
