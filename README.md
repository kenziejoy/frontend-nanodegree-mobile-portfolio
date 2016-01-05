Intro section

This was a project of the Udacity Front End Development Nanodegree. The purpose was to optimize a mobile portfolio. Index.html is optimized to above 90 for both mobile and web and pizza.html is below 60fps.

Made by MacKenzie Rawcliffe
November 2015

## Table of Contents

1. [Implementation](#implementation)
1. [License](#license)


## Implementation

There is a website so you can proceed to the [demo](#demo) to implement.

### Dependencies

1. Udacity resources

### Optimizations

I made the following improvements:

* Loaded print CSS style sheet only during print requests
* Resized and Compressed photos (several times)
* Tried updating font with a web font loader and ultimately decided to remove it
* Minified and Inlined the CSS style sheet
* Inlined perfmatters javascript and made sure all other javascript was loaded async

Main.js in the pizza view is mostly to 60fps I think - I'm not sure where to go next so I'm submitting it now.

I made the following improvements

* Calculated the number of pizzas needed using screen.height
* In the UpdatePositions function I changed the select all to get elements by class name and took a major calculation out of the interior function scope. I also moved several variables out of the loop
* Moved the pizzasDiv variable our of the for loop
* I created an outside variable to ease calculations in the change pizza size function. I also moved some variables out of the loop
* Declared and moved the elem, movingPizzas and numberOfPizzas variables outside the for loop


**[Back to top](#table-of-contents)**

## Demo

You can view the [demo site here](http://kenziejoy.github.io/frontend-nanodegree-mobile-portfolio).

The animation speed can [be tested here](http://kenziejoy.github.io/frontend-nanodegree-mobile-portfolio/views/pizza.html)

**[Back to top](#table-of-contents)**


## License

#### (The MIT License)

Copyright (c) 2014 Bill Gooch

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
		distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

		The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

		THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
		EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
		IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
		TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

**[Back to top](#table-of-contents)**
