# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```
import math
class cse:
    def mech(self, radius):
        area = math.pi * radius ** 2
        return area
radius = float(input("Enter the radius of the circle: "))
circle = cse()
circle_area = circle.mech(radius)
print(f"The area of the circle with radius {radius} is: {circle_area:.2f}")
```
## Output
<img width="1136" height="314" alt="Screenshot 2025-12-26 190342" src="https://github.com/user-attachments/assets/a2a12842-afbd-4aa7-bb54-e67422607504" />

## Result
The code is executed successfully.

