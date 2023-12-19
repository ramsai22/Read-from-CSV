# Read-from-CSV:

## AIM:
To write a python program for reading content from a CSV file.
## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
Read the CSV file using read_csv method.
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns.
### Step 5:
Display the result.
## PROGRAM:
```
Developed by:paida ram sai
Register No: 212223110034

To write a python program for reading content from a CSV file.
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
![image](https://github.com/saiganesh2006/Read-from-CSV/assets/145742342/9ae89c3e-0fe5-4ec9-af69-1251aa4d901a)

## RESULT:
Thus python program for reading content from a CSV file is successful.
