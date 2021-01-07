[Home](README.md)

# Class 05
## Chapter 5: "Images"
### Where would you put your images?
It's best if you keep your files and images organized in folders, as your site folder may become really cluttered. So they will most likely be found in an "Images" folder.

### How do you add Images?
- &lt;img src="images/imagefile.jpg" alt="A description of the image here" title="This is where you would put text and when a user hovers over them this text is visible." /&gt;
### Adding Height and Width
How adding height and width is done by attributes which are inside of the img tag. You would put height at the very end of the code before the closing tag, and the width would be right after that.
- width="123px"
- height="123px"
### Aligning images
- align="left" aligns the image to the left
- align="right" aligns the image to the right
When aligning images vetically it is best to use the attributes:
- align="top"
- align="middle"
- align="bottom"

## Chapter 11: "Color"
### 3 ways of using color
1. RGB values: This tells the amount of Red, Green, and Blue that is in the chosen color. rgb(100,100,90)
2. Hex Codes: This is done by 6 digit codes with a hash tag or a pound sign before the 6 digits #123456
3. Color Names: These are the default colors that are used in coding, teal, red, blue, aqua, etc. Teal
4. hsl: This stands of Hue, Saturation, and lightness. 
5. hsla: Hue, Saturation, Lightness, and Alpha

background-color is used in css and is seen as a box on the page. These boxes can contain paragraphs, images, the header, etc.

- contrast: This is better when there is a darker color behind a lighter color or vice versa. Good contrast is the text being white and the background being black, bad contrast would be a very dark gray text on a black background.
- opacity: This tells how see through an image is. How transparent a color or image is.

## Chapter 12: "Text"
### How to choose a font for your website
- It has to be fitting to the subject, like if it was for a bank the font should not be bubble letters
### CSS things you can do with text
- font-family: This will give you a selection of different fonts, it will give you a group of fonts because it wants to be certain the browser can run at least one of them.
- font-size: This contains the size of the font or text within the page.
- @font-face: allows you to use a font even if the font isn't downloaded on the device
- font-weight: This can be either bold or normal
- font-style: This can be either italic, normal, or oblique.
- text-transform: This can change the header or any text uppercase or lowercase or even capitalize for you
- <b>text-decoration:</b> This can be either none, underline, overline, line-through, or blink. -----(which animates the text to flash on and off)---- (I just definitely wanna keep that in mind lol)
- line-height: This separates the line from the typeface
- letter-spacing and word-spacing: These can make the letters or words appear as far from eachother as you choose.
- text-align: This can be either left, right, center, or justify.
- vertical-align: this can align images
- <b>text-indent:</b> allows you to indent the first line of text within an element the amount you want the line indented by can be specified in a number of ways but is usually given in pixels or ems. (page 287)
- text-shadow: this puts shadow behind your text and can be adjusted in any way. 
- :first-letter: This makes the first letter of every paragraph really big.
- :first-line: This makes the first line of every paragraph big. or bolded.
- :link: This is applied to every link within the page and the links can be decorated in any way here.
- :visited: This decorates the links you have already been to. 