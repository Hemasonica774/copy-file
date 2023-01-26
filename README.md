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
with open("file.txt") as fp:
    with open("fire2.txt","w") as fp1:
        line= fp.read()
        fp1.write(line)
        


````

### OUTPUT:

![good morning](https://user-images.githubusercontent.com/118361409/214816500-be9f0910-ae65-4a84-968d-8a57bbaefac4.png)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
