# Inverse-of-matrix

## AIM:
To write a program to perform Inverse-of-matrix using python programming.

## ALGORITHM:
### Step 1:
Import Numpy module as np.

### Step 2:
Create empty lists.

### Step 3:
Get input from the user for number of rows and columns.

### Step 4:
Use nested lists to append list.

### Step 5:
Print the inverse of the array using np.linalg.inv .

## PROGRAM:
```
import numpy as np
rows=int(input())
columns=int(input())
l1=[]
for i in range(rows):
    temp=[]
    for j in range(columns):
        t=int(input())
        temp+=[t]
    l1+=[temp]
print(l1)
print(np.linalg.inv(l1))
```

## OUTPUT:
![image](https://user-images.githubusercontent.com/94505585/154478544-72c33e59-173d-4be9-89c4-7c62edc7f546.png)


## RESULT:
Thus the program is written to perform Inverse-of-matrix using python programming.
