## EJS Partials

### Partials we need it to reuse the same HTML across multiple views.they are like functions, they make large websites easier to maintain as you don’t have to go and change a piece of text in every page it appears in. Instead, you define that reusable bundle of code in a file andinclude it wherever you need it.

#### Imagine we have two pages and these two pages have the same footer and navigation bar so we will use the partials EJS by creating a directory for each one then write what we need inside it then we can include each one of them by using the **include** like this:
`<%- include('partials/footer') %>`