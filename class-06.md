### **Objects**
group together a set of variables and functions to create a model
of a something you would recognize from the real world.

IN AN OBJECT: VARIABLES BECOME KNOWN AS *PROPERTIES*
IN AN OBJECT: FUNCTIONS BECOME KNOWN AS *METHODS*

An object cannot have two keys with the same name.The value of a property can be a string, number, Boolean, array, or even another object.

Creating an object , for example :

var hotel ={
name: 'Quay',
rooms: 40,
booked: 25,
}

checkAvailability: function(){
    return this.room ;
};

Accessing an object,for example :
var hotelName = hotel.name;

-----------------------------------------------------------------

### **Document Object Model**

specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.
the DOM Tree is a model of a web page.
Accessing and updating the DOM tree involves two steps:
1. Locate the node that represents the element you want to work with.
2. Use its text content, child elements, and attributes.

You can select element nodes by their id or class attributes, by tag name, or using CSS selector syntax. An element node can contain multiple text nodes and child elements that are siblings of each other. 
You can select element nodes by their id or class attributes, by tag name, or using CSS selector syntax. An element node can contain multiple text nodes and child elements that are siblings of each other. 
