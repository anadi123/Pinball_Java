# Pinball_Java
Pinball is a classic arcade game that has been around since the 1930s. It involves the player using flippers to hit a ball around a table aiming to score points by hitting various targets and obstacles.

Code Explanation
Pinball class extends the JFrame class and implements the ActionListener interface which allows it to handle events.
The timer object is created to update the game every 10 milliseconds.
The ballX, ballY, and ballSize variables are used to keep track of the ball’s position and size.
The ballXdir and ballYdir variables are used to control the ball’s direction and speed.
The paddleX, paddleY, paddleWidth, and paddleHeight variables are used to keep track of the paddle’s position and size.
The Pinball constructor sets the size of the window sets the title of the game starts the timer
 adds a key listener to handle input, and sets the window to be visible.
The paint method is called whenever the window needs to be redrawn. It draws the ball and paddle on the screen.
