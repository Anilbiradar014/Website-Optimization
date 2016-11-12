#Website Optimization
 
######Project Overview
 
The task was to optimize a provided website with a number of optimization and performance-related issues so that it achieves a target PageSpeed score and runs at 60 frames per second.
 
Link to Optimised page : [Website-Optimization](https://anilbiradar014.github.io/Website-Optimization/)
  
 
###Index Page
 
The index page originally had a Google PageSpeed score of 35/100 for mobile and 47/100 for desktop. After optimizing the score increased to 96/100 for mobile and 97/100 for desktop. .
 
##The following changes were made:
 
* Inlined CSS added to index.html
 
* Media print was added for destination/css/print.css
 
* async added to <script> in index.html.
 
* optimized images in “img” folder by compressing them using tinypng.com.
 
* Using Grunt views/images/pizzeria.jpg was optimised.
 
* Optimization made in views/js/main.js file.
 
-  document.querySelector() is replaced with document.getElementById() on line 427.
 
-  used document.getElementsByClassName() Web API on line 452.

-  moved variables newwidth and dx outside the loop to line 453 and 454.
 
-  declared pizzasDiv variable outside the loop on line 472.
 
-  document.querySelectorAll is replaced with document.getElementsByClassName() Web API on line 505
 
-  document.body.scrollTop / 1250 was assigned to a variable scrollTop and declared outside loop on line 506.
