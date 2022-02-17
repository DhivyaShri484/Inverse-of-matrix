# Inverse-of-matrix

## AIM:
To write a python program to find the inverse of nested array using numpy module.

## ALGORITHM:
### Step 1:
Import numpy module
### Step 2:
Declare a variables l1 and l2 as an empty list.
### Step 3:
Get the input of the variables n and m.
### Step 4:
Loop a variable i in the range of n and nest loop a variable j in range m
### Step 5:
Get the value of num variable
### Step 6:
During the loop append the num values to l1 and l1 valuse to list l2
### Step7:
Declare a variable value1 to l2 by coverting to an array
### Step 8:
Declare a variable inverse, using numpy module's linalg and inv functions find the inverse of l2
### Step9:
Print the value of the inverse

## PROGRAM:
import numpy as np
l1,l2=[],[]
n1,n2=int(input()),int(input())
for i in range(n1):
    for j in range(n2):
        values=int(input())
        l1.append(values)
    l2.append(l1)
    l1=[]
print(l2)
a=np.linalg.inv(l2)
print(a)

## OUTPUT:
![image](https://user-images.githubusercontent.com/94505585/154476700-093a1f61-3680-4274-85b4-ae8b257b1f86.png)

## RESULT:
Therefore the program is successfully executed to find the inverse of nested arrays using numpy module.
