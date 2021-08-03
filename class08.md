# Layouts

Elements of HTML are displayed as block elements (taking the whole width of the page), and inline element (taking only the width of its content). Each element is treated like it is surrounded with a box that has borders,margins, and padding that control the size and appearance of the box.

## Positioning Of Elements
The position scheme assigned to thw element will determine its position on screen and relative to other elements in the page, here is abrief description of CSS positioning themes:

1. Normal Flow: the default scheme in which elements appear on top of each other, each box will start on a new line after the previous box.

2. Relative Position: the position of the box is set relative to its normal flow position, it will not affect the position of other elements.

3. Absolute Positioning: this will take of the element from its normal position affecting the appearance of other elements.

4. Fixed Positioning: close to absolute positioning but the element will stay on the same position when scrolling down page.

Position properties (left, right, top, and bottom) are used to set the location of the element, when elements overlap, the element with higher z-index will appear on top.

Floating of elements is used to change the location of the element's box

![float options](https://i2.wp.com/css-tricks.com/wp-content/uploads/2021/03/web-layout.png?resize=540%2C240&ssl=1)

Layout can respond to screen size (responsive layout) or stay the same regardless the screen size (none responsive layout).
