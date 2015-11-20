Index.html is optimized to above 90 for both mobile and web

I made the following improvements:

* Loaded print CSS style sheet only during print requests
* Resized and Compressed photos (several times)
* Tried updating font with a web font loader and ultimately decided to remove it
* Minified and Inlined the CSS style sheet
* Inlined perfmatters javascript and made sure all other javascript was loaded async

Main.js in the pizza view is mostly to 60fps I think - I'm not sure where to go next so I'm submitting it now.

I made the following improvements

* Reduced the number of pizzas created from 200 to 40 and the number of columns to 6
* In the UpdatePositions function I changed the select all to get elements by class name and took a major calculation out of the interior function scope.
* I created an outside variable to ease calculations in the change pizza size and the change pizza slider functions.
