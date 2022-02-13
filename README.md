# Multiplying-two-matrix

## AIM:
To multiply two arrays using numpy.

## ALGORITHM:

### Step 1:
Import numpy.
### Step 2:
Get the input as array.
### Step 3:
Append it to a empty list.
### Step 4:
Multiply the two arrays.
### Step 5:
Print it.

## PROGRAM: 
```
Name:J.Archana priya
reg.no:21500533

import numpy as np
l1,l2=[],[]
n= int(input())
for i in range(n):
    l1.append(int(input()))
for i in range(n):
    l2.append(int(input()))
value1=np.array(l1)
value2=np.array(l2)
result=value1*value2
print("Product of two arrays is:",result)

```
## OUTPUT:
![array](./array.png)
## RESULT:
Multiplying of two arrays using numpy has been successfully done.

