[Home](README.md)

# Class 10
## JavaScript Book, Chapter 10: "Error Handling & Debugging"
### Order of execution
To find the source of an error, it's exremely helpful to know how a script code is being run. Some tasks can't be processed until the previous ones have run and gone through. 
### Execution Contexts
1. Execution context: Every statement in a script lives in one of three execution contexts:
- Global Context: This is when code is in a script but not in a function. There is only one global context in any page.
- Function Context: Code being run in a function. Every function has it's own function context.
- Eval Context (not shown): Text is executed like code in an internal function called eval(). eval() evaluates or executes an argument. eval() evaluates expression if the argument is an expression. eval() executes the statements if there is one or more statement.
2. Variable Scope: The first two execution contexts correspond with the notion of scope.
- Global Scope: How a variable can be used anyway is if it is called outside of the function and this makes it a global scope. 
- Function-level Scope: This is the opposite of the global scope. This scope is only used within the function because the variable is only called in the function itself. Not outside the function. 
### Error Objects
There are 7 types of error object in javascript. These can be visible in the JavaScript console which is located in your browser when you right click the browser you should see an "inspect" tool choice when you right click. Click this button and it should bring up a little window on the right side of your browser. Look towarsd the top of the window and you should see a "Console" tab. Click that and that is where you errors will register and the console will tell you which line is causing the error.
1. Error: Generic Error - The other errors are based on this error
2. SyntaxError: This is an error in writing the language, sometimes can be caused by a simple missing comma or quotation mark. or a misspelled word. 
3. ReferenceError: Represents a non-existant variable that is used. This could be a mistype
4. TypeError: An unexpected datatype
5. RangeError: Numbers not in an expected range. Possibly when you have a function that only ranges from 1 to 10 and you enter an 11 or higher?
6. URIError: encodeURI(), decodeURI(), and similar methods used incorrectly.
7. EvalError: eval() function used incorrectly
### How to deal with errors
1. Debug the script to fix errors: You will find that the inspect tool in your browser is extremely helpful. And this is when you go into your code and try to find the error. Look closely at your code because it could be a simple mistype or you typing a string with the beginning being a single quote while the end of your string is a double quote. This can throw off your whole code.
2. Handle errors gracefully: This is when you have code that is causing errors beyond your control. This is good for error-handling code. Such as; try, catch, throw, and finally statements. An example of this is when you might request data from a third party, and their stops responding. 
### Handling expressions
1. Try: This tries to execude the preceding code
2. catch (exeption): If there is an exception this code will be run
3. finally: This will always be executed
