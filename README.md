Download Link: https://assignmentchef.com/product/solved-python3
<br>
Consider a water tank as a right circular cylinder. You can google the volume of a right circular cylinder (and other properties as well). You can also google the number of gallons in a cubic foot and the weight of that water.

Code Example 1 – defining a class

<pre># Defining a classclass class_name:    [statement 1]    [statement 2]    [statement 3]    [etc.]</pre>

Code Example 2 – Example of a Class

<pre>#An example of a classclass Shape:    def __init__(self, x, y):        self.x = x        self.y = y        self.description = "This shape has not been described yet"        self.author = "Nobody has claimed to make this shape yet"    def area(self):        return self.x * self.y    def perimeter(self):        return 2 * self.x + 2 * self.y    def describe(self, text):        self.description = text    def authorName(self, text):        self.author = text    def scaleSize(self, scale):        self.x = self.x * scale        self.y = self.y * scale</pre>

Code Example 3 – Creating a class

<pre>rectangle = Shape(100, 45)</pre>

Code Example 4 – accessing attributes from outside an instance

<pre>#finding the area of your rectangle:print(rectangle.area())#finding the perimeter of your rectangle:print(rectangle.perimeter())#describing the rectanglerectangle.describe("A wide rectangle, more than twice as wide as it is tall")#making the rectangle 50% smallerrectangle.scaleSize(0.5)#re-printing the new area of the rectangleprint(rectangle.area())</pre>

For this assignment you only need to look at Code Example 1 thru 4 from the link above.

Assignment: Create a “tank” class and use it in a program that accepts height and radius from the user and prints total volume in cubic feet, total volume in gallons, and total weight of the water in pounds. Also print the surface area of the top of the tank, the surface area of the outside of the tank, and the total of these two areas (in square feet). So, the only inputs the class would need is the height and radius of the tank in feet.