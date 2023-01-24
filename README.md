# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7

## ALGORITHM: 

Step 1:
Import pandas as pd.

Step 2:
Read the CSV file using read_csv method.

Step 3:
Use head and tail method to get the required contents from the file.

Step 4:
Use len() method to get the number of rows and columns

Step 5:
Print the output.

## PROGRAM:
```
#To write a python program for reading content from a CSV file.
#eveloped by: P.Hemasonica
#Register Number: 22003246

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("rows",len(df.axes[0]))
print("columns",len(df.axes[1]))

````

### OUTPUT:

![Screenshot (65)](https://user-images.githubusercontent.com/118361409/214373627-0e8961e7-c825-41d7-b1ff-2464324bfd91.png)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
