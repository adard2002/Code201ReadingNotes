[Home](README.md)

# Class 07
## Domain Modeling
### What is domain modeling?
Domain modeling is when you create a model in code designed for a specific problem. This tells you all of the attributes and behaviors, and tells what you may need to do to reach the problem domain
### How would you calculate daily likes
Popularity is measured by Likes. You will need to generate a random number between 10 and 30 and times it by the good ratings of the video.
> 1. When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
> 2. Model its attributes with a constructor function that defines and initializes properties.
> 3. Model its behaviors with small methods that focus on doing one job well.
> 4. Create instances using the *new* keyword followed by a call to a constructor function.
> 5. Store the newly created object in a variable so you can access its properties and methods from *outside*
> 6. Use the *this* variable within methods so you can access the object's properties and methods from *inside*.

## Chapter 6: "Tables"
### What are tables?
Tables are where you would store information in several boxes. Like if you want to type in the definition of a word along with the word. You would have 2 boxes on top with the titles of "Word" and "Definition" and there would be 2 columns going down those two with several different words and definitions.
### How would you make a table?
There are 4 different elements you are going to need to learn to make a table:
1. &lt;table&gt;: This is going to contain everything inside of your table, including the table headers, content within the rows, etc.
2. &lt;tr&gt;: This stands for Table Row, this is going to be followed by:
3. &lt;td&gt;: This is following the Table Row tags. This stands for Table Data. There will multiple of these inside of one row usually.
4. &lt;th&gt;: This is like the td element but stands for Table Header,
### How would you make a long table?
There are 3 elements you are going to need:
1. &lt;thead&gt;: This is where all of your table headers will be contained
2. &lt;tbody&gt;: This will go after where all of your table headers are and will close right before the closing table tag.
3. &lt;tfoot&gt;: This is the footer of your table. Where sometimes you may want to have a final row that will add up all of the numbers in one row. This is where you would put that final number perhaps.
### Other things to know
- You can also have width and height in tables.
- You can also have borders and background colors here too.

## Chapter 3: "Functions, Methods, and Objects"
We've already looked at functions I think a few times before in this chapter. So
### What's an object?
Objects group together a set of variables and function to create a model. Variables and functions in objects can have names.
### Creating an object: Literal Notation
This is the most easy and most popular way to create an object. There are many possible ways of creating an object.
There are 3 parts to creating an object:
1. object: This is the name after the var variable. 
2. key: This is what element or trait you will want to call. Example: eyeColor:
3. value: This is the description or value of what the key is. Since the example for key is eyeColor, for the value you may have blue,
### What does the this keyword do?
We used this a few times in class today
> The keyword this is commonly used inside function and objects. Where the function is declared alters what *this* means. It always refers to one object, usually the object in which the function operates.
### Arrays are objects
Objects are arrays, they are just typed out differently. These are typed out in a vertical list whereas an array are inside brackets. They both use commas to separate the array list items.