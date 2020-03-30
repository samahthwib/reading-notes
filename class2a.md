
**jQuery**

jQuery is a JavaScript Library, It makes things like HTML document traversal and manipulation, event handling, animation, and Ajax much simpler with an easy-to-use API that works across a multitude of browsers.

1. In order to use jQuery, the first thing you need to do is include
the jQuery script in your page.

2. Once jQuery has been added to the page, a second JavaScript file is included that uses jQuery selectors and methods to update the content of the HTML page.

jQuery doesn't do anything you cannot achieve with pure JavaScript.
It is just a JavaScript file but estimates show it has been used on over a quarter of the sites on the web, because it makes coding simpler.

With jQuery, when a selector returns multiple elements, you can update all of them using the one method. There is no need to use a loop.

**implicit iteration** The ability to update all of the elements in the jQuery selection
**chaining** The process of placing several methods in the same selector
methods act on the same selection of elements:
* **hide()** hides the elements
* **delay ()** creates a pause**
* **fade In ()** fades in the elements

When you create a selection with jQuery, it strores a reference to the corresoponding nodes in DOM tree. It doesn't creat a copy

The **.html()** and **•text ()** methods both retrieve and update the content of elements.

The **replaceWith()** and **remove ()** methods replace and remove the elements they match
(as well as their content and any child elements).

**.on()** method is used to handle all events. Behind the scenes, jQuery handles all of the cross-browser issues
jQuery allows you to recreate the functionality of a loop on a selection of elements, using the
**•each ()** method.
The **.animate()** method allows you to create some of your own effects and animations by changing CSS properties.
