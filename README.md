# lab6_js
# lab-06-readjs
# Web developers usually talk about three languages that are used to create web pages: HTML, CSS, and JavaScript
Where possible, aim to keep the three languages in separate files, with the HTML page linking to CSS and JavaScript files.
Each language forms a separate layer with a different purpose. Each layer, from left to right. builds on the previous one
## CONTENT LAYER##
. html files ->
This is where the content of the page lives. The HTML gives the page structure and adds semantics. 
![html](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcQEc9A_S6BPxCDRp5WjMFEfXrpCu1ya2OO-Lw&usqp=CAU)


## PRESENTATION LAYER ##
. css files->
The CSS enhances the HTML page with rules that state how the HTML content is presented (backgrounds, borders, box dimensions, colors, fonts, etc.)
![css logo](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcTpXaDo9xQfNOh-0nAtgdMzekEMdTbESQoFhQ&usqp=CAU)

## BEHAVIOR LAYER##
.js files->
This is where we can change how the page behaves, adding interactivity. We will aim to keep as much of our JavaScript as possible in separate files. 
![js logo](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcQ1v2eqAIG-m60VWzx2cLJlfFGJRvQR4HPLbg&usqp=CAU)

### HTML ONLY###
Starting with the HTML layer allows you to focus on the most important thing about your site: its content. Being plain HTML, this layer should work on all kinds of devices,  accessible to all users, and load quite quickly on slow connections.

### HTML+CSS ###
Adding the CSS rules in a separate file keeps rules regarding how the page looks away from the content itself. You can use the same style sheet with all of your site, making your sites faster to load and easier to maintain. Or you can use different style sheets with the same content to create different views of the same data. 
### HTML+CSS+JAVASCRIPT ###
The JavaScript is added last and enhances the usability of the page or the experience of interacting with the site. Keeping it separate means
that the page still works if the user cannot load or run the JavaScript. You can also reuse the code on several pages (making the site faster to load
and easier to maintain). 
