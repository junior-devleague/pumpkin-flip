# pumpkin-flip

Flip over pumpkins to find the candy.

![Example](https://github.com/junior-devleague/pumpkin-flip/blob/master/imgs/example.gif)

## Objective

Use **JavaScript Logic**, **Flexbox**, **Events** and more to simulate a pumpkin flipping game.

## Prerequisites

To complete this project, students should have the following:
* Intermediate understanding of HTML elements (divs, images, attributes...etc.)
* Intermediate understanding of JavaScript and DOM (variables, setTimeout, for loops, appending elements, functions)

## Your Challenge

### Part I

To complete Part I, fulfill the following requirements:

1. Clone this repository.
2. Set up your file structure through the command line:
  * index.html
  * styles.css
  * app.js
3. Link your CSS and JS file to index.html

### Part II HTML

To complete Part II, fulfill the following requirements:
1. Create a ```div``` with an ```id``` of "container".

### Part III CSS

To complete Part III, fulfill the following requirements:
1. Target the element with an ```id``` of "container".
  * Set its width to ```calc(100vw)```.
  * Set its height to ```calc(100vh)```
  * Activate flexbox!
  * Use flexbox to give space around each element horizontally and vertically
2. Target the elements with a ```class``` of "pumpkin".
  * Set its width to 50px.
  * Set its height to 50px.
  * Set its background-image to the pumpkin.png image in the imgs folder.
  * Activate flexbox!
  * Use flexbox to center items horizontally and vertically.
3. Target the elements with a ```class``` of "row".
  * Activate flexbox!
  * Use flexbox to give horizontal space around the elements.
  * Use flexbox to center items vertically.
4. Target the elements with a ```class``` of "candy".
  * Set its width to 50px
  * Set its height to 50px
  * Set its position to relative
  * Set its z-index to -1

### Part IV JS

To complete Part IV, fulfill the following requirements:

1. Create a variable to store your container div.
2. Create a function called **start**. In this function, call another function called **generateScene(5)**. The generateScene will do the following in comments:
``` javascript
function start(){
  generateScene(5);
}
function generateScene(numRow) {
  //Create a numRow x numRow grid of divs with the class of "pumpkin".

  //Store all the elements with the class name of pumpkin in a variable.

  //Create an image with the src of the candy.jpg image. Give it a class name of "candy". Pick a random pumpkin to append this candy to.

  //Add an Event Listener to all of the pumpkins that will react when a user mouses over the pumpkin. Onmouseover, the pumpkin's background image should be changed to "none". If the candy is found (how do we know if we have hovered over a pumpkin with a candy in it?), give an alert that you found the candy, then "reset" the scene. Call generateScene again with a random numRow value between 3 and 6.
}
```
3. Don't forget to call your start function at the bottom of your code! 
