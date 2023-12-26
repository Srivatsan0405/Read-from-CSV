# Read-from-CSV

## AIM:
To write a python program to read contents from a CSV file.

## ALGORITHM:
### Step 1:
Import pandas module as pd.
### Step 2:
Using pd.read_csv() method read the CSV file.
### Step 3:
Using df.head() print the first 10 rows of the CSV file.
### Step 4:
Using df.tail() print the last 5 of the CSV file.
### Step 5:
Using len(df.axes[]) print the toal no.of rows and columns with argument 0 for row and argument 1 for column.
    
## PROGRAM:
```
#Program to read contents from a CSV file
#Developed by: SRIVATSAN V
#RegisterNumber: 23000970
import pandas as pd
f=pd.read_csv('nba.csv')
print(f.head(10))
print(f.tail())
print('Number of Rows:',len(f.axes[0]))
print('Number of column:',len(f.axex[1]))
```
## OUTPUT:
![292386086-4e385378-c24a-418d-bbeb-b5016c116f9e](https://github.com/Srivatsan0405/Read-from-CSV/assets/139841630/58f0a4f2-cadb-40b3-881a-2da202a67d07)
  ![292386170-1e42a64d-fe88-4747-9929-369a22ab8c55](https://github.com/Srivatsan0405/Read-from-CSV/assets/139841630/257ec6a2-a2a9-498c-a7aa-3915c5d7436a)



## RESULT:
Hence the program is executed successfully!
