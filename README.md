# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
Import math package
### Step 2: 
Input number l1,l2
### Step 3: 
Substitute the values in the distance formula

![formula](/formula.JPG)
### Step 4:
Distance = math.sqrt((l2[0]-l1[0])**2+(l2[1]-l1[1])**2)
### Step 5: 
Print the distance in two decimal
### PROGRAM:
````
#Program to find the distance between two points.
#Developed by: Balachandran S
#RegisterNumber: 22006708
import math as m
l1=[4,2]
l2=[10,6]
d=m.sqrt((l2[0]-l1[0])**2+(l2[1]-l1[1])**2)
print("{:.2f}".format(d))
````

### OUTPUT:
!['output'](/Screenshot%20from%202022-12-25%2018-55-54.png)

### RESULT:
By this program we able to find the distance two points
