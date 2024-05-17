# Read-from-CSV

## AIM:

To write a python program for reading the csv file content

## ALGORITHM:
### Step 1:
Load the CSV into a DataFrame.
### Step 2:
Print the number of contents to be displayed using df.head().
### Step 3:
The number of rows returned is defined in Pandas option settings.
### Step 4:
Check your system's maximum column with the pd.options.display.max_column statement.
### Step 5:
Increase the maximum number of rows to display the entire DataFrame.
## PROGRAM:
```
Developed By: GOKUL C
Registration No: 212223240040

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```

## OUTPUT:

![331071167-af51a201-2adc-4d1e-b21f-a7c17ed34a39](https://github.com/Gokul1410/Read-from-CSV/assets/153058321/60e4dea0-a646-4bf4-9ed6-1e879628c4f4)


## RESULT:
