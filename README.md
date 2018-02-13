# Snake
## Using p5 JS

Snake is a recreation of the vintage snake game, developed to work on cross browser platforms for various devices.

I took on this project to learn to make light browser games and canvases and to get acquainted with the p5 JS library. This game is further meant to be assigned to the freshers as a begineer's project, so they can build a project (using other languages and libraries like PyGame) on their own having this game as a reference.

![screenshot of the game](snake_screnshot.png)

### The game has a very minimilistic object rendering with two categories of objects made from the same class
#### 1. foodBlock
#### 2. playerBlocks (array of player blocks)

### The collision detection is quite simple, and is done in two different ways
#### 1. foodBlock to playerBlock head collision :
The collision is said to be true if the absolute difference of the x coordinates and y coordinates of the head of the player block and the foodblock are of a certain magnitude.

#### 2. playerBlock to playerBlock collision (to detect overlapping):
Here, simply it is checked whether the x and y coordinates of two playerBlocks is same or not. This method of collision detection somethimes does not work for bigger snakes, but the prior collision detection method would not work for the playerBlock-playerBlock collision.

### Following are some of the features to be added to the project :
1. Add a UI and link it with the game, wherein attributes like the color, game speed, etc. can be tweaked with a switch of a button or a slider.
2. Change the control configurations to support touchscreen devices.
3. Improve the collision detection, especially for the playerBlock-playerBlock collisions.
