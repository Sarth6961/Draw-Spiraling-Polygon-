# Draw-Spiraling-Polygon
Turtle is an inbuilt module of python. It enables us to draw any drawing by a turtle, methods defined in the turtle module and by using some logical loops. To draw something on the screen(cardboard) just move the turtle(pen). To move turtle(pen) there are some functions i.e forward(), backward(), etc.

Approach to draw a Spiraling Polygon of the given sides and of size n:  

Import turtle and create a turtle instance.
Set sides = 5, sides of the polygon.
Using for loop(i = 0 to i < n * sides) and repeat below step
turtle.forward(i  * 10).
turtle.right(360 / sides).
Close the turtle instance.
