# Website Performance Optimization portfolio project

### To run the project :

http://abiyayalew.github.io/frontend-nanodegree-mobile-portfolio/

###  Critical Rendering Path for index.html

It was optimised using with following methods:

1. Inline the style.css 
2. Use media print for print.css
3. use async for analytics.js
3. Removed Google Analytics
4. Optimised the images using  http://optimizilla.com/
5. Minified the HTML

### Framerate for pizza.html 
It was optimised with the following methods on main.js:

1. The function updatePositions() was optimised by 
      * Read layout outside of the for loop.
2. The function changePizzaSizes() was optimised by 
      * Read layout outside of the for loop.
      * Removed querySelectorAll .
      * Reduced the number of background pizzas rendered to 100.
      * Dynamically calculated the number of moving pizzas required.
3. The function changePizzaSizes() was optimised by 
      * Changed the slider value to a percent width.
      * read layout outside of the for loop.






