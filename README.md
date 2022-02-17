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
#Developed By: B.Dhivya Shri
#Ref No:21002377
import numpy as np
l1,l2 = [],[]
r,c= int(input()),int(input())
for i in range(r):
    for j in range(c):
        num=int(input ())
        l1.append (num)
    l2. append (l1)
    l1=[]
print (l2)
valuel=np.array(l2)
inverse = np.linalg.inv(valuel)
print (Inverse)

## OUTPUT:
![image](https://user-images.githubusercontent.com/94505585/154478052-ac42c5bd-2f8c-4cd8-b075-4548fcc0e412.png)

## RESULT:
Thus the program is written to perform Inverse-of-matrix using python programming.
