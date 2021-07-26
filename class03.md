# HTML Lists, Control Flow with JS, and the CSS Box Model
## Lists
There are 3 types of lists in HTML:
1. Ordered list
2. unordered list
3. Definition list

### Ordered Lists
As the name implies, the components of this list will be numbered, the list is declared between `<ol>` and `</ol>`, each component must be wrapped with `<li>` and `</li>`.

### Unordered Lists
the components of this list will have bullets or symbols instead of numbers, the list is declared between `<ul>` and `</ul>`, each component must be wrapped with `<li>` and `</li>`.

## Definition Lists
This list is used to preview terms and their definitions, the list is declared between `<dl>` and `</dl>`, each term must be wrapped with `<dt>` and `</dt>`, followed by `<dd>` and `</dd>` to enter the definition.

*All of these lists can be nested i.e. a list declared inside a list.*

## Boxes
Each element in HTML has its allocated area in the page, this area is called a box, and by using CSS, you can edit the properties of this box like dimensions, borders, location, color, margins, padding....etc.

Basic properties to control size of boxes.
property | description
------------ | -------------
width, height | set dimensions measured in px,%, or em
max width, max height | to limit max dim size
min width, min height | to limit min dim size
overflow | what to do when the content is larger than box

Basic properties to control borders of boxes.
property | description
------------ | -------------
border-width | set width of borders or one side of them
border-style | like solid, dotted, dashed,..etc
border-color | set the color for borders
border | set width style colr respectively
*border width is measured in px only*

Basic properties to control padding and margins
property | description
------------ | -------------
padding | set padding size, all or seprate directions are valid
margin | set margin size, all or seprate directions are valid
*margins and padding are measured in px, %, or em*

Basic properties to control display and visibility
property | description
------------ | -------------
display: inline | the element will act like inline elements
display: block | the element will act like block elements
display: inline-block | act like block but flows like inline
visibility: hidden | replaces element with blank space

for more information, pease visit [CSS Box Model](https://www.w3schools.com/css/css_boxmodel.asp)

## Arrays
A variable that stores a list of values that can be recalled and updated by their index number.

## Switch and If statments

the general form for if statement is
![if statement example](https://cdn.programiz.com/sites/tutorial2program/files/js-if-else-statement.png)

the general form for switch statement is
![switch statement example](https://images.slideplayer.com/19/5803798/slides/slide_2.jpg)