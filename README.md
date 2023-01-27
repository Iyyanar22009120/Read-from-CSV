# Read-from-CSV

## AIM:

## ALGORITHM:
### Step 1:
Import pandas as pd.


### Step 2:
Read the CSV file using read_csv method.
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns
### Step 5:
Print the output.


## PROGRAM:
```
reference number:22009120
name:s.iyyanar
import pandas as pd
f=pd.read_csv("nba.csv")
print(f.head(10))
print(f.tail())
print("Row",len(f.axes[0]))
print("Col",len(f.axes[1]))
```

## OUTPUT:
![OUTPUT](./output%20read%20from%20csv.png)

## RESULT:
Thus a python program is written to read the contents of a CSV file.