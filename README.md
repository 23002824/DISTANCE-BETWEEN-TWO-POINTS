# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1:
Start 
### Step 2:
Define the coordinates of the two points (x1, y1) and (x2, y2).
### Step 3: 
Substitute the values of the coordinates into the distance formula: 
[formula](/formula.JPG)
### Step 4:
Calculate the square of the differences of x-coordinates and y-coordinates.
### Step 5:
Sum the squared differences and take the square root to find the distance.
### Step 6:
Round the result to the desired precision, if necessary
### Step 7:
Output the calculated distance.
### Step 8:
End
### PROGRAM:

```
import math
x1=10
x2=4
y1=6
y2=2
d=math.sqrt((x2 - x1)**2 + (y2 - y1)**2)
e=round(d,2)
print(e)
```
### OUTPUT:
![alt text](<Screenshot 2024-03-09 214202.png>)
### RESULT:
Thus DISTANCE-BETWEEN-TWO-POINTS are successfully executed
