## **EJS**

### EJS stands for Embedded JavaScript templating we use it to include repeatable parts of our site (partials) and pass data to our views.

Steps:
1. npm init -y
2. npm install ejs and other libraries
3. on the server.js we will create an instance of the server
4. we will configure our server to run everything 
5. set the view folder to handle our all views that we are creating as demonstrated
6. create view engine that we set it to ejs
7. create get route for the route directory

we have to know some tage like :
 `<%` `<%_` `<%=` `<%-` `<%#` `<%%` `-%>` `_%>` 

And some options like :
`cache` `filename` `context` `compileDebug` `client` `delimiter` `debug` `_with`