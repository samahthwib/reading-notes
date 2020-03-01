## **Charts**

*Charts* are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.

I learnt from the article how to draw the charts of all kindes 
some of chart types : 
1. bar chart 
2. line chart
3. pie chart 

<canvas> it's an element used to draw graphics via javascript, it's just a container and must have an id, it has two attribute width , height .

The <canvas> element has a method called <getContext()>, used to obtain the rendering context and its drawing functions.
I learned how to draw rectangles, triangles, lines, arcs and curves
<canvas> only supports two primitive shapes: rectangles and paths (lists of points connected by lines)

There are three functions that draw rectangles on the canvas:

* fillRect(x, y, width, height)
  Draws a filled rectangle.
* strokeRect(x, y, width, height)
  Draws a rectangular outline.
* clearRect(x, y, width, height)
  Clears the specified rectangular area, making it fully transparent.

For drawing straight lines, use the <lineTo()> method.
To draw arcs or circles, we use the <arc()> or <arcTo()> methods

I learned about some canvas options we have at our disposal to make our drawings a little more attractive. I learned how to add different colors, line styles, gradients, patterns and shadows to your drawings.

The canvas rendering context provides two methods to render text:

1. fillText(text, x, y [, maxWidth])
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
2. strokeText(text, x, y [, maxWidth])
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.

