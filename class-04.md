#### This is a summery for **Links** , **Layout**  

### **LINKS**
Links are the defining feature of the web because they allow you to move from one web page to another . links are created using the `<a>` element. Users can click on anything between the opening `<a>` tag and the closing `</a>` tag.
for example: 
`<a href="http://www.google.com">Google</a>`
`<a href="index.html">Home</a>` This is a link for to other pages
on the same site.
`<a href="mailto:jon@example.org">Email Jon</a>` This is an E-mail link

For opening Links in a New Window we should use : `target` tag
You can use the id attribute to target elements within a page that can be linked to.

### **LAYOUT**
It's how to control where each element sits on a page and how to create attractive page layouts.
*CSS* treats each *HTML* element as if it is in its own box. This box will either be a block-level box or an inline box.
1. block-level box : start on a new line Examples include: `<h1>` `<p>` `<ul>` `<li>`
2. Inline elements : flow in between surrounding text Examples include: `<img>` `<b>` `<i>`

If one block-level element sits inside another block-level element then the outer box is known as the **containing** or **parent element**
CSS has the following positioning schemes that allow you to control the layout of a page: 
* normal flow : `position:static`
* relative positioning : `position:relative`
* absolute positioning : `position:absolute`

The `float` property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible.
The `clear` property allows you to say that no element (within the same containing element) should touch the left or righthand sides of a box.
Different visitors to your site will have different sized screens that show
different amounts of information, so your design needs to be able to
work on a range of different sized screens.
**Fixed width layout** designs do not change size as the user increases or decreases the size of their browser window.Measurements tend to be given in pixels.
The **liquid layout** uses percentages to specify the width of each box so that the design will stretch to fit the size of the screen.

**CSS frameworks** aim to make your life easier by providing the code for
common tasks, such as creating layout grids, styling forms, creating
printer-friendly versions of pages and so on.

Some web page authors split up their CSS style rules into separate style sheets. For example, they might use one style sheet to control the layout and another to control fonts,colors and so on.Your HTML page can link to one style sheet and that stylesheet can use the @import rule to import other style sheets.

**FUNCTIONS** 
1. Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function
Example:
var msg = 'Sign up to receive our newsletter for 10% off!';
function updateMessage() {
var el = document.getElementByld('message'};
el .textContent = msg;
}
updateMessage(};


The location where you declare a variable will affect where it can be used
within your code. If you declare it within a function, it can only be used
within that function. This is known as the variable's scope
* LOCAL VARIABLES
* GLOBAL VARIABLE

These are software engineering practices that have proven to dramatically improve the quality of code developers produce :
1. Iterative loops. 
2. Code reviews. 
3. Fast feedback. 
4. Error checking and linting.

pair programming commonly involves two roles: the Driver and the Navigator.
skills that help anyone learn a new language: Listening: hearing and interpreting the vocabulary Speaking

Six Reasons for Pair Programming :
1. Greater efficiency
2. Engaged collaboration
3. Learning from fellow students
4. Social skills
5. Job interview readiness
6. Work environment readiness