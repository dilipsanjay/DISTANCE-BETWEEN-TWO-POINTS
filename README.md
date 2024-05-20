# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
## Step 1:
Import the math module to use the built-in functions for calculation.

## Step 2:
Get the 2 points from the user.

## Step 3:
Substitute the values in the distance formula
formula  ![formula](/formula.JPG)

## Step 4:
Print the distance.

## Step 5:
End the program

### PROGRAM:
```
#Program to find the distance of the bridge from one point to another point
#Developed by: Dilip sanjay M
#Register no:212223240032
import math
def calculate_distance(point1, point2):
    x1, y1 = point1
    x2, y2 = point2
    distance = math.sqrt((x2 - x1) ** 2 + (y2 - y1) ** 2)
    return distance
point1 = [4, 2]
point2 = [10, 6]
distance = calculate_distance(point1, point2)
print(f"{distance:.2f}")
```
### OUTPUT:
![image](https://github.com/dilipsanjay/DISTANCE-BETWEEN-TWO-POINTS/assets/155506948/2d6dfeca-bd24-45e2-b167-19fa3762c6aa)


### RESULT:
Thus the program to find the distance between two points is written and verified using python programming.
