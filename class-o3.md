#### This is a summery for **List** , **Boxes** and **switch statements** 

_____________________________________


### **LIST**
There are three types of list :
1. *Ordered lists* are lists where each item in the list is numbered. 
2. *Unordered lists* are lists that begin with a bullet point (rather than characters that indicate order).
3. Definition lists are made up of a set of terms along with the definitions for each of those terms.


The **tags** we use it in list: `<li>` `<ol>` for ordered list . `<ul>` `<li>` for unordered list.
Lists can be nested inside one another. 

-----------------------------------

### **Box**
The most popular ways to specify the size of a box are to use pixels, percentages, or ems.
These are very helpful properties to ensure that the content of pages are legible ,like : max-width , min-width , min-height and max-height

*Overflowing Content* The overflow property tells the browser what to do if the content contained within a box is larger than the box itself. It can have one of two values: 
1. **hidden** This property simply hides any extra content that does not fit in the box.
2. **scroll** This property adds a scrollbar to the box so that users can scroll to see the missing content.

Every box has three available properties that can be adjusted to control its appearance:
* Border  : property allows you to specify the width, style and color of a border in one property.
* Margine : property controls the gap between boxes. Its value is commonly given in pixels, although you may also use percentages or ems.
* Padding : property allows you to specify how much space should appear between the content of an element and its border.

You can control the individual size of borders using four separate properties:
border-top-width / border-right-width / border-bottom-width / border-left-width
OR just border-width

You can control the style of a border using the **border-style** property. This property can take the following values: solid , dotted , dashed , double , inset ,etc.
The **display** property allows you to turn an inline element into a block-level element or vice
versa, and can also be used to hide an element from the page.The values this property can take are: inline / block / inline-block 
The visibility property allows you to hide boxes from users but It leaves a space where the element would have been.This property can take two values: hidden / visible 

and we have a lot of properties like : border-image, box-shadow, border-radius, border-radius.

-------------------------------------

### **SWITCH STATEMENTS**
A switch statement starts with a variable called the switch value. Each case indicates a possible value for this variable and the code that should run if the variable matches that value.

switch (level) {
case 'O ne ':
title= 'Level 1 ' ;
break;
case 'Two':
tit 1 e = ' Level 2 ' ;
break;
case ' Three' :
title = 'Level 3' ;
break ;
default :
title= 'Test';
break;

default;

**Loops** check a condition if it returns *true* , a code block will run then the condition will be checked again and if it still returns true the code block will run again. it repeats until the condition returns *false*

There are three types of loop: for, while, and do ... while. Each repeats a set of statements.
