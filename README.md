# Read-from-CSV

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
Print the output.
## PROGRAM:
```
#Developed by: JAYAMANI R
#Reference No: 22008124
import pandas as pd 
f=pd.read_csv('nba.csv')
print(f.head(10))
print(f.tail())
print('Row:',len(f.axes[0]))
print('Col:',len(f.axes[1]))
```

## OUTPUT:
![Screenshot from 2023-01-26 16-05-40](https://user-images.githubusercontent.com/85949888/214815244-aa20d1a2-d798-461d-ad1d-69e56307a0f4.png)


## RESULT:
Thus a python program is written to read the contents of a CSV file.
