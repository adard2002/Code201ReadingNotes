[Home](README.md)

# Class 14
## What Google Learned From Its Quest to Build the Perfect Team




## Aricle on CSS Transforms https://learn.shayhowe.com/advanced-html-css/css-transforms/ 
### 2D and 3D Transforms and their axis
Two-dimensional transforms work with the x and y axis whereas the three-dimensionals work with x, y AND z axis. The z axis is like the dept, or layers on a page.
### How do you do the transformation?
In the HTML you are going to want to put it in a &lt;figure&gt; tag. Along with the class="box-1" or whatever you want to call it. And what goes between the opening and closing figure tags are what you want to be in the boxes. In the CSS you are going to want the .box-1 to have "transform: rotate(20deg);" this will rotate it that many degrees and change the angle it is facing. You can also use negative degrees which will rotate the other way too.
### How to do the 2D scale
This allows you make for example, a card different size. The way the scale is used in HTML is the same way, it's the CSS is the thing that changes the most. How you would do the CSS is "transform: scale(.75);" the default value is 1. Anything above 1 will appear larger while anything below 1 will appear smaller in size. 
### Multiple scaling 
This enlarges the width and height by being given a certain x and y value. The x value is width, and the y value is height. 
### CSS translate
This moves the card to the right and left however much is being given. this is done by "transform: translateY(-35%);" this moves it only up and down. And "transform: translateX(-10);" shifts it to the right or left. You can make the card go towards the bottom left corner if you want. Just put both x and y amounts in the parenthesis.
### CSS Skew
This stretches the card diagonally. This looks like "transform: skewX(-20deg);" and if you want the y axis to be effected instead just change it from X to Y.
### Combining transforms
You can combine these by just placing them in the same line after transform:. Example: transform: skew(10def, 20deg) translateX(20px);.
### transform origin
If you want to make a card flip from one side of a box to another this is what you will use. transform: scale(.5); and transform-origin: 100% 100%.


## Article on CSS Transitions & Animations
### How to make a box change color when you hover over it, and when you don't hover over it it will slowly fade to it's original color. 
* .box { 
*  background: #2db34a; // background color
*  transition-property: background; 
*  transition-duration: 1s; // how long it takes to transition to the other color
*  trasition-timing-function: linear;
* }
* .box:hover {
*  background: #ff7b29 // what you want the color to change to
* }
* 
### How to make a box that transforms into a box and changing color
* .box {
*    background: #2db34a;
*    border-radius: 6px // changes the sharpness of the corners
*    transition-property: background, border-radius; // changes so as its transitioning it changes color
*    transition-duration: 1s; 
*    transition-timing-function: linear; 
*  }
*  .box:hover {
*    background: #ff7b29; // what the color is changing to
*    border-radius: 50%; // makes it into a circle, changing the corners of the box into a circle.
*  }
### Animations https://learn.shayhowe.com/advanced-html-css/transitions-animations/ 
How to make a ball that slides and moves to a direction (alot like pong)
* @keyframes slide {
*  0% { 
*    left: 0;
*    top: 0;
*  }
*  50% {
*    left: 244px;
*    top: 100px;
*  }
*  100% {
*    left: 488px;
*    top: 0;
*  }
* }
* .stage:hover .ball {
*  animation-name: slide;
* }

## 8 simple CSS3 transitions that will wow your users http://www.webdesignerdepot.com/2014/05/8-simple-css3-transitions-that-will-wow-your-users/ 
Fading in. When being hovered it changing to a deeper version of that color
* .fade
* {
*        opacity:0.5;
* }
* .fade:hover
* {
*        opacity:1;
* }
Changing the color when being hovered
Use the same code as above but instead of fade:hover use:
* .color:hover
* {
*        background:#53a7ea;
* }


## Pure CSS Bounce Animation https://codepen.io/dp_lewis/pen/gCfBv 