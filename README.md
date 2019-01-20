# arcadeGame

The goal of the game is to make the player to go to the water area without touching the enemies. And do an activity after the player reached the water area successfully.   

## For completing my Arcade Game project,
# I did the following steps.

1. Read all the information and coding engine provided by **Udacity**. Observed all the modules, images in the project. And also downloaded project skeleton from GitHub.

2. After I run the project, It shows an empty page in browser. I found few errors from google developer console. For resolving those error I implemented an array named *allEnemies[]*, *Player* class and also created an object from *Player* class.

3. Implemented the below functions for Player.
  + *render()
  + *update()* and
  + *handleInput().

4. render() is for placing a player sprite on the canvas. and update() is for updating the player position. This function already implemented by using a dt parameter.

5. handleInput() is to handle the inputs which was given by user. The input indications were already given. I just implemented the functionality by using the indications. I used calculations to implement the functionality. And also divided the canvas into number of pieces. Based on the that I implemented handleInput function.
    The inputs are :
    - left arrow  : move towards the left side on x-axis. This key is not working when the player reaches left-most direction.
    - right arrow : Move towards the right side on x-axis. This key is not working when the player reaches right-most direction.
    - up arrow    : Move towards the upward direction on y-axis
    - down arrow  : Move towards the downward direction on y-axis. This key is not working when the player reaches down-most direction.

6. If the user reaches the water area, the he completes his game successfully. Again the player reborn at the starting position. If he touches the water area, the score is increased by 1. Similarly calculated high score based on the score.

7. Similarly implemented Enemy activity. Developed 2 functions for enemy.
  + render() and
  + update().

8. render() is already given. I used an array for placing 3 enemies on the game board based on the calculations. And update() updates the enemy position based on the speed which was generated by JavaScript random function.

9. Added few styles for the created score section ( both score and high score ).

10. Added meta tag for representing this in various resolutions.

11. Added little bit styles after the score become 5.
