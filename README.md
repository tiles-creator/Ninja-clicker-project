# Ninja-clicker-project
Ninja Clicker Game - Group Project
  
Authors:  Teresa Iles, William Owuama, Albert Rosas, Mark Wilson
Due Date:  11/21/19
Course:  COSC 1137 Fundamentals of Programming II
Instructor:  Greg Yera

This program is a game that allows the player to click on moving objects that pass across the screen.  The player earns points each time
they successfully click on an object.  Clicking these objects makes them go away, and updates your score in real time by incrementing it by
their respected value.  Circles = 1 point, Triangles = 2 points, and Squares = 5 points.  The game lasts 20 seconds, and a countdown timer
in the upper right corner displays the time remaining as you play the game.  Score is displayed in the lower left corner of the window.

To play this game, download the five classes included in the zip folder:\n
NinjaClickerGame.java\n
MovingObject.java\n
SquareObject.java\n
TriangleObject.java\n
CircleObject.java\n
\n
Then, run the program by running the NinjaClickerGame.java file.\n

Description of classes:\n
NinjaClickerGame.java - Main class that launches the application, controls user interface, timer, keeps track of score, and creates GUI\n
MovingObject.java - Extends Pane.  Parent class for each moving object.  \n
SquareObject.java - Extends MovingObject class.  Creates a square object and its movement across the screen, using the path transition animation feature\n
TriangleObject.java - Extends MovingObject class.  Creates a triangle object and its movement across the screen, using the path transition animation feature\n
CircleObject.java - Extends MovingObject class.  Creates a circle object and its movement across the screen, using the path transition animation feature\n
