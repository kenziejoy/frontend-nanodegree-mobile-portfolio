Made by MacKenzie Rawcliffe
November 2015
For Udacity Project 4 of the Front End Developer nanodegree

Visit http://kenziejoy.github.io/frontend-nanodegree-mobile-portfolio/views/pizza.html to see a live version of the site.

You can test the site speed of index.html using the link above.

Index.html is optimized to above 90 for both mobile and web

I made the following improvements:

* Loaded print CSS style sheet only during print requests
* Resized and Compressed photos (several times)
* Tried updating font with a web font loader and ultimately decided to remove it
* Minified and Inlined the CSS style sheet
* Inlined perfmatters javascript and made sure all other javascript was loaded async

Main.js in the pizza view is mostly to 60fps I think - I'm not sure where to go next so I'm submitting it now.

I made the following improvements

* Calcualted the number of pizzas needed using screen.height
* In the UpdatePositions function I changed the select all to get elements by class name and took a major calculation out of the interior function scope. I also moved several variables out of the loop
* Moved the pizzasDiv variable our of the for loop
* I created an outside variable to ease calculations in the change pizza size function. I also moved some variables out of the loop
* Declared and moved the elem, movingPizzas and numberOfPizzas variables outside the for loop
