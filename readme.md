Spirograph Design using Turtle Graphics

Description:
This Python script generates a spirograph-like design using the Turtle module. The spirograph pattern is created by drawing lines with alternating colors as the Turtle moves in a circular motion.

How to Use:

Ensure you have Python installed on your system.
Run the script in a Python environment.
Watch as the spirograph pattern is drawn on the screen.
Code Explanation:

The script sets the background color of the drawing area to black.
It creates a Turtle object named 't'.
A list named 'colors' is defined containing two colors: white and red.
A loop runs 400 times, each time the Turtle moves forward by a distance equal to the current loop iteration number plus one.
After moving forward, the Turtle turns right by 89 degrees.
The pen color alternates between white and red using the modulus operator to determine the index from the 'colors' list.
Finally, the 'turtle.done' function is called to keep the window open and display the completed drawing.
Note:

You can modify the number of iterations in the loop to change the complexity of the spirograph design.
Experiment with different colors and angles to create unique patterns.
