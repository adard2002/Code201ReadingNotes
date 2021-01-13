[Home](README.md)

# Class 08
## Chapter 15: "Layout"
### Positioning elements
CSS treats each HTML elements as if everything is inside its own box. This box will either be a block-level element, or an inline element.
- block-level element: Starts on a new line
- inline elements: Flow in between surrounding text
### Different positions of the elements
1. Normal Flow: This shows every block-level element on it's own line. 
2. Relative Positioning: This shifts an element from the position it would be in the normal flow to the top, right, bottom, left or anywhere it wouldn't have been placed before.
3. Absolute Positioning: This positions the element depending on what the relation to it's containing element
4. Fixed Positioning: This positioning depends on the browser window. Elements with fixed positioning do not affect the surrouding elements
5. Floating Elements: This allows the element to be on the left or the right. The floating element becomes a block-level element where the surrounding contents can flow around the floating element. Not being disturbed.
### Different Elements to use in CSS
- position:static- This is displayed by the elements lining up and being displayed as being on top of eachother
- position: relative- This moves it back to where it would originally be in a normal flow
- position: absolute- This makes it so the element is not affected by the position of the browser, or anything around it
- position: fixed- This can be used as a navigation bar, as some like to apply this rule to navigation bar sometimes. This makes it so that no matter where you scroll it will always be sticking to the top or bottom of your window no matter how much you scroll.

- z-index: Because elements are seen as boxes this makes it so the boxes that are on towards the bottom of the page are on stuck on the top layer
- float: This can be used for floating an image or a paragraph, or anything. This makes it to where it floats to the right or left, or anywhere as well. This makes it so everything flows around the floating element not disturbing it.
### Fixed width layout
This will make it so boxes on a page will be nicely lined up and the same width and height for some.
### liquid layout
These boxes are freely movable throughout the page.
