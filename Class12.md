[Home](README.md)

# Chart.JS API
## <canvas>
The opening canvas tag will only need a width and height. If there is no given height or width then the canvas will be the default of 300px wide and 150px in height. The canvas tag does look similar to the img tag but the img tag has the alt and src attributes whereas this canvas one doesn't and is not a self closing tag. 
## Drawing shapes with canvas
### How to draw rectanglees with canvas
There are 3 functions needed to draw rectangles:
1. fillRect(x, y, width, height): This draws a filled rectangle
2. strokeRect(x, y, width, height): This draws an outline in shape of a rectangle
3. clearRect(x, y, width, height): Clears the specified rectangular area, making it fully transparent
### Drawing a triangle with canvas
function draw() {
  var canvas = document.getElementById('canvas');
  if (canvas.getContext) {
    var ctx = canvas.getContext('2d');

    ctx.beginPath();
    ctx.moveTo(75, 50);
    ctx.lineTo(100, 75);
    ctx.lineTo(100, 25);
    ctx.fill();
  }
}
- This creates a triangle pointing to the left
- The moveTo(x, y) moves the pen that many pixels away using the x(horizontal) and the y(vertical) axis.
- beginPath() is used to start a new shape path. 
### Drawing circles using arc() or arcTo()
- arc(x, y, radius, startAngle, endAngle, anticlockwise)
- arcTo(x1, y1, x2, y2, radius)

## Colors https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors 
- fillstyle = color" Sets the style used for filling shapes
- strokeStyle = color: Sets the style for shape outlines
- globalAlpha = transparencyValue: transparency 

## Line styles
- lineWidth = value:  Sets width of lines drawn in the future
- lineCap = type: Sets appearance of the end of the lines
- lineJoin = type: Sets appearance of the corners where the lines meet
- miterLimit = value: Controls how thick the junction is when the two lines join at a sharp angle
- getLineDash(): Returns the current line dash pattern array containing an even number of non-negative numbers.
- setLineDash(segments): Sets current line dash pattern
- lineDashOffset = value: Specifies where to start a dash array of a line.

## Drawing Text
- fillText(text, x, y [, maxWidth])
Fills text at the (x,y) position that is given. 
- strokeText(text, x, y [, maxWidth])
Strokes text at the (x,y) position. Pretty much the outline of the letters
### Styling Text
- font = value: Text style used when drawing the text. Default is 10px sans-serif
- textAlign = value: Possible values: start, end, left, right, or center. Default is start
- textBaseline = value: Possible values: top, hanging, middle, alphabetic, ideographic, bottom. Default is alphabetic.
- direction = value: Possible values: ltr, rtl, inherit. Default is inherit