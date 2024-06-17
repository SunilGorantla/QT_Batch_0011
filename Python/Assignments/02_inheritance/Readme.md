# Class Notes and Assignment

## Assignment: Shape Inheritance Hierarchy with Minimum Three-Sided Shapes

### Background
In this exercise, you will develop a shape inheritance hierarchy in Python that focuses on shapes with a minimum of three sides. You will define a base class called `Polygon` and derive specific shape classes from it, such as `Triangle` and `Rectangle`. This exercise aims to demonstrate the concepts of inheritance, method overriding, and polymorphism with an emphasis on multi-sided shapes.

### Requirements

1. **Create a base class `Polygon` with the following:**
   - A method `area` that returns `NotImplemented`.
   - A method `perimeter` that returns `NotImplemented`.
   - A `__str__` method that returns `"Polygon"`.

2. **Create a `Triangle` class that inherits from `Polygon`:**
   - It should have an `__init__` method that takes `base` and `height` for area calculation, and `side1`, `side2`, and `side3` for perimeter calculation.
   - Override the `area` method to calculate the area of the triangle.
   - Override the `perimeter` method to calculate the perimeter of the triangle.
   - Override the `__str__` method to return `"Triangle"`.

3. **Create a `Rectangle` class that inherits from `triangle`:**
   - It should have an `__init__` method that takes `length` and `width` as parameters.
   - Override the `area` method to calculate the area of the rectangle.
   - Override the `perimeter` method to calculate the perimeter of the rectangle.
   - Override the `__str__` method to return `"Rectangle"`.

4. **(Optional) Create additional classes for other polygons, such as `Pentagon`, `Hexagon`, etc.**

5. **Ensure that each polygon class correctly calculates its area and perimeter.**

### Instructions

- Write the classes as described above, making sure that each derived class correctly overrides the methods from the base class `Polygon`.
- Create instances of each polygon with the appropriate dimensions.
- For each instance, print the type of polygon, its area, and its perimeter.
- Demonstrate polymorphism by writing a function that takes a `Polygon` instance and prints its type, area, and perimeter, without needing to know the specific type of polygon.
