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

Print the predicted output.

## PROGRAM:
```
'''
developed by : Tejusve Kabeer.F
reference.no : 22002543
'''
import pandas as pd
df = pd.read_csv('rd.csv/nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))

```

## OUTPUT:
![readcsv](https://user-images.githubusercontent.com/118364993/214817019-9ec65ba6-d1fc-4c9f-ac47-18ab649f86a0.png)


## RESULT:
Thus a python program is written to read the contents of a CSV file.
