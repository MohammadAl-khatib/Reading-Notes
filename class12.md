# Chart.js, Canvas
Charts are pretty way to convey data, it is easier to read but harder to create. Using chart.js plugin will allow you to create bar charts, line charts, pie charts and more.

![charts image](https://www.qlik.com/blog/assets/uploads/images/posts/patrik-lundblad/pl-minichartspost-082820.png)

Every chart is drawn by creating a `<canvas>` element like `<canvas id="buyers" width="600" height="400"></canvas>` then writing a script (JavaScript Code) which defines the shape of drawing (2D, 3D) in `<getcontext()>` and the type of chart and the source of data to be represented.

## `<canvas>`
canvas element can be used to draw different kinds of shapes like rectangles,circles,lines,arcs,texts,etc.... These shapes can also be styled for color, transparency, line width, repeat, gradient.

*important: this article does not focus on syntax, you can explore for how to write full code in: [MDN, applying styles and colors](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors) and [MDN, drawing shapeswith canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes).