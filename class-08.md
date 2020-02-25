### **Layout**

*Building Blocks* 
CSS treats each HTML element as if it is in its own box. This box will either be a **block-level box** or an **inline box**.

positioning schemes : 
1. Normal flow => position:static
2. Relative Positioning => position:relative
3. Absolute positioning => position:absolute

When you use relative, fixed, or absolute positioning, boxes can overlap. If boxes do overlap, the elements that appear later in the
HTML code sit on top of those that are earlier in the page. If you want to control which element sits on top, you can use the z-index property. I
The `clear` property allows you to say that no element (within the same containing element) should touch the left or righthand sides of a box.

 ------------------------------------------------------------

Many web pages use multiple columns in their design. This is achieved by using a `<div>` element to represent each column.
Different visitors to your site will have different sized screens that show different amounts of information, so your design needs to be able to work on a range of different sized screens.
Fixed width layout designs do not change size as the user increases or decreases the size of their browser window.Measurements tend to be given in pixels.
Liquid layout designs stretch and contract as the user increases or decreases the size of their browser
window. They tend to use percentages.
Grids help create professional and flexible designs.