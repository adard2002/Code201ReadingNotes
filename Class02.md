[Home](README.md)

# Class 02

## Chapter 2: "Text"

### What are DOCTYPES?
Since there are several versions of HTML each webpage code should start with &lt;!DOCTYPE&gt; at the very top of the code. This tells the browser which version of HTML you are running so the page is properly rendered. 

### How do you use comments and why are they used?
Comments are only shown when you are looking at the code itself. No comments are shown on the actual webpage. HTML, CSS, and other computer languages have their own unique comments. 
- HTML: &lt;!-- This is a comment --&gt;
- CSS: /* This is a comment */
- JS: // This is a single line comment.
- JS: /* This is a multiple line comment */

### ID and Class attributes.
- ID Attribute: This can be used on any HTML element. It is used to identify that specific element from the other elements on the page. 
- Class Attribute: This can also be used to any HTML element but instead of identifying just one element it identifies all of the elements. Example can be identifying all of the &lt;p&gt; elements on a page.

### Block Elements and Inline Elements.
- Block Elements: These elements force the text to show on a new line. Some examples of Block elements are; &lt;h1&gt;, &lt;p&gt;, &lt;ul&gt;, and &lt;li&gt;.
- Inline Elements: These elements can be used in the same line of a sentence and still work. Some exaamples of Inline elements are; &lt;a&gt;, &lt;b&gt;, &lt;img&gt;, &lt;em&gt;.

### Grouping text and elements: block vs. inline
- Block (div): You might use this to create your navigation bar and to make separate lines so your links are in different lines either horizontal or vertical.
- Inline (span): This is used to contain a number of inline elements or contains a section of text to help identify that specific text in a crowded text.

### Iframes
An Iframe's use is mostly for google maps. It takes a location and puts it onto the page. Some attributes to get it to work are: src, height, and width. 
- src: specifies where you got the page
- height: specifies the height in pixels.
- width: specifies the width in pixels

### What is the &lt;meta&gt; tag?
This is an element that lives inside of the head element and tells us information about the web page. 

## Chapter 10: "Introducing CSS"

### What is CSS?
- CSS stands for cascading style sheets. This adds in color to your web page and design. When using CSS it is useful to think of everything as a box. 

### Parts of CSS rules
There are 2 parts to CSS elements: the Selector and the Declaration. 
- Selector: Tells us which element the rule is going to apply to. And if you want the rule to apply to multiple elements they can be separated with a comma.
- Declaration: Tell us what is going to happen to the elements that are selected. This can result in many things: Font, color, etc.
There are 2 parts to the CSS Declarations: the Property and the Value.
- Property: This tells what aspects of the elemtn you want to change, this can be the color, font, size, or anything. 
- Value: This tells us what you are going to change the result to. For color this can be blue, purple, green, etc. 

### CSS Selectors 

| Selector | Meaning | Example |
|:---------|:-------:|--------:|
| Universal Selector | Applies to all elements in a webpage | * {} 
| Type Selector | Applies to the specific elements | h1, h2, h3 {}
| Class Selector | Matches an element whose class attribute has a value that matches the one specified after the period (or full stop) symbol | .note {} or p.note {}
| ID Selector | Applies to all elements with the ID attribute | #introduction {} |
| Child Selector | Applies to the elements that have a direct child of another | li>a {} |
| Descendant Selector | Matches an element that is a descendent of another specified element | p a {} |
| Adjacent Sibling Selector | Applies to the element that is the next sibling after another | h1+p {} |
| General Sibling Selector | Matches an element that is a sibling of another, although it does not have to be the directly preceding element | h1~p {} | 

## Chapter 2: "Basic JavaScript Instructions"

### Statements
var today = new Date();
var hourNow = today.getHours();
var greeting;

if (hourNow > 18) {
  greeting = 'Good evening';
} else if (hourNow > 12) {
  greeting = 'Good afternoon';
} else if (hourNow > 0) {
  greeting = 'Good morning';
} else {
  greeting = 'Welcome';
}
document.write(greeting);

- The top 3 rows and all of the rows with greeting in them are statements. Statements should start on a new line and the semicolon tells the JavaScript to continue on to the next step. 
- JavaScript IS case sensitive.
- The curly braces are the start and end of a codeblock.
- the else if and hourNow's determines which code will run.

## Variables
While writing JavaScript you have to be very specific on the steps you want it to take to complete the task you are wanting it to complete. This data is stored in variables. 

Example: 
var quantity;

- In this example var is the Variable Keyword and quantity is the Variable Name. var is an example of what programmers call a keyword. The JavaScript interpreter knows that this keyword is used to create a variable. 
- In order to use the variable, you must give it a name. (This is sometimes called an identifier.) In this case, the variable is called quantity. 

Example:
quantity = 3;

- In this example quantity is the variable name. The equals sign is the assignment operator. And the 3 is the variable value.
- Where possible, a variable's name should describe the kind of data the variable holds.
- The equal sign says that you are going to assign a value to the variable. It is also used to upadte the value given to a variable. 

[comment]: <> (Yes, I know I just copied what was in the book for JavaScript but I'm struggling to understand JavaScript. With HTML and CSS it's pretty straight forward. You have specific elements that go inside other elements and such whereas JavaScript I don't know where to start. I do understand the expressions page (pg. 74) and the operators a bit (pg. 75) and Arithmetic Operators. and I understand the firstName and lastName stuff on the page 78. I understand how we got the console results in the demo. I think it's just getting started and how to make it work from scratch is hard for me. I'm not exactly sure. I hear people say it's kinda easy but I don't know lol)

### Data Types

- Numeric Date Type: This is used when counting or calculating sums. Example: 0.75
- String Data Type: Everything within single quotes is called a String. Example: 'Hi, Ivy!'
- Boolean Data Type: These result in either true or false


## Chapter 4: "Decisions and Loops"

## Comparison Operators
- == is equal too
'Hello' == 'Goodbye' return false due to not being the same string
'Hello' == 'Hello' return true due to being the same string
- === strict equal too
'3' === 3 returns false because not the same value or type
'3' === '3' returns true because they are the same 
- != is not equal too
'Hello' != 'Goodbye' returns true. they are not the same string
'Hello' != 'Hello' returns falce. they are the same string
- !== strict not equal too
'3' !== 3 returns true because they are not the same data type or value.
'3' !== '3' returns false because they are the same
- &gt; greater than
4 > 3 returns true
3 > 4 returns false
- &lt; less than
4 < 3 returns false
4 < 3 returns true
- &gt;= greater than or equal to
4 >= 3 returns true
3 >= 4 returns false
4 >= 4 returns true
- <= less than or equal to
4 <= 3 returns false
3 <= 4 returns true
3 <= 3 returns true

### Logical Operators
- &&: Logical And. Tests more than 1 condition
Example: ((2 < 5) && (3 >= 2)) returns true
true && true returns true
true && false returns false
false && true returns false
false && false returns false
- || Logical Or. Tests at least one condition
Example: ((2 < 5) || (2 < 1)) returns true
true || true returns true
true || false returns true
false || true returns true
false || false returns false
- ! Logical Not. Takes a single Boolean value and inverts it.
Example: ~(2 < 1) returns true
!true returns false 
!false returns true

### Loops
- For: Is used to run code a specific number of times.
Round 1: 24
Round 2: 32 
Round 3: 17

- While: Used when the number of times a code should run is unknown.
1 x 5 = 5
2 x 5 = 10
3 x 5 = 15
4 x 5 = 20
5 x 5 = 25
6 x 5 = 30
7 x 5 = 35
8 x 5 = 40
9 x 5 =45

- Do While: It will run the code at least once even if the condition returns false.
1 x 5 = 5

