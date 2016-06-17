# Smile_Match
## Matching game built in JavaScript

### The Rules
+ Go to the match.html file and run it in the browser
+ You'll notice a set of smiley faces on each side of the game board
... Click on the extra smiley face on the left side of the game board that is missing on the right side
+ If you click the right smiley face, you progress to the next level
... On each level, more smiley faces are added, making it more difficult to find the extra smiley face
+ If you click on the wrong face, game over


### How I Build It
+ I used HTML and a simple CSS border to create the game board
+ The smiley face is a png file borrowed, you can find it [here](http://home.cse.ust.hk/~rossiter/mooc/matching_game/smile.png) 
![alt tag](http://home.cse.ust.hk/~rossiter/mooc/matching_game/smile.png)
+ I created a four loop and used the .createElement() JavaScript method to generate the number of images based on a random number between 0 and 400.
+ Using style methods, I added the random number as pixels to the number of images generated, which set the locations of the smiley faces on the game board
+ I used the .appendChild() method to set the images to the left side of the game board and the .cloneNode() method to match the right side
+ Outside of that for loop, another function was created for the click handler, in which for every correct smiley face the user matched, another 5 faces are generated, thus creating the instance for the next level
+ Finally, I created a game over function for when the user clicked on the wrong face.

![alt tag](http://home.cse.ust.hk/~rossiter/mooc/matching_game/smile.png)


