# The-Snake-Game by Shivam Kumar Gupta
<h1>Code Explation</h1>
<div>Code Explanation:

The code starts by creating a window screen.
The title of the window is “Snake Game”.
The background color of the window is blue.
Next, the code creates two turtle objects: head and food.
Head is used to control the snake, while food will be used as the game’s object.
The code first sets up head so that it looks like a square with white color and starts at (0, 0).
Next, it sets up food so that it looks like a square with blue color and places it at (10, 10).
Finally, head moves towards food using direction=”Stop”.
The code creates a window screen with the title “Snake Game” and sets the background color to blue.
Next, a square head object is created and set to have the color white.
The pen up() method is called on the head object, which causes it to rise up from the bottom of the screen.
Finally, the goTo() method is used to move the head object towards (0, 0) in the x-direction.
Next, two turtle objects are created – one for food and one for head.
The food object has a shape of “square” and will be placed at (0, 0) on the screen.
The head object has no shape specified and will be placed at (0, 0) in the y-direction
The code starts by creating a few variables to store information about the game.
The first is food, which stores information about the shapes and colors of the food that will be displayed on the screen.
Next, the code creates a function called speed() that will control how quickly the food moves across the screen.
Finally, the shape() and color() functions are used to create different types of food (square, triangle, and circle) with corresponding colors and speeds.
The next section of code sets up an event handler for when the user clicks on one of the buttons in the toolbar.
This handler calls a function called goto() that takes two arguments: position (in pixels) and direction (which can be “up”, “down”, “left”, or “right”).
goTo() then uses these values to move the pen object to a specific location onscreen and set its properties accordingly.
The last section of code displays some text onscreen and starts timing it using time().
Then it prints out a score value for each round played as well as high scores for both players at once.
The code will create a turtle that will move at 0 speed and have a square shape.
The turtle will be white in color and will start at the top left corner of the screen.
Once the code has executed, it will output “Score : 0 High Score : 0” in center alignment.
The code starts by creating three variables: head, wn, and godown.
The head variable stores information about the player’s current position on the screen (xcor and ycor), while wn is a listening object that will be used to track keyboard input.
Godown stores information about where the player should go next (if they are moving left or right), and goleft and goright store key directions for moving up, down, or left/right respectively.
The code then starts to loop through each of these variables in turn.
If any of them change (head.direction, wn.listen(), godown.direction), the code updates itself accordingly and sets various properties on head such as its xcor and ycor coordinates, its heading direction (up, down, left/right), as well as colors and shapes for each segment in the game world according to what was just inputted by the user via keyboard presses.
Finally, there is a delay timer set to 0.1 seconds which allows time for one frame of animation before starting over again with another round of gameplay; this is important because it ensures that everything looks smooth even when there are lots of objects moving around on-screen at once!
The code assigns key directions to the turtle, listens for user input, updates the screen and calculates the player’s score.
It also creates a new square segment if needed and moves it according to the key presses.
If the player is moving their turtle up or down, then head.direction will be set to “up” or “down”, respectively.
If they are moving left or right, head.direction will be set to “left” or “right”.
The code also checks whether the player’s current position falls within a food zone and if not, then the appropriate x and y coordinates are randomly generated and stored in food and moved accordingly by calling Turtle().goto() with those values.
</div?
<img ![Screenshot (4)](https://user-images.githubusercontent.com/89629088/227526191-984cf9bb-dc6c-40c9-961d-d2913fad6d4d.png)>
 
