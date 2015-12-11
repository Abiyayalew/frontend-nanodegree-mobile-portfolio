# Web Optimization

## Project Objective:

 Optimize a provided website with a number of optimization- and performance-related issues so that it achieves a target PageSpeed score and runs at 60 frames per second.

## Running Instruction: 
 
 1.	Go to Google PageSpeed Insights, input below link, then you will get the analysis of the page.
 2.	Scroll down to the protfolio page, click on the 'Yonglin's Pizzeria', you will be nagvigated to the pizza page, open the dev too to the console, you will get the rendering speed.

 link :  http://abiyayalew.github.io/mobile-portfolio/

## Approaches to Optimization Web Performance:

### Critical Rendering Path for index.html

It was optimised using with following methods:

1. Inline the style.css 
2. Use media print for print.css
3. Use async for analytics.js
3. Removed Google Analytics
4. Optimised the images using  http://optimizilla.com/
5. Minified the HTML

### Framerate for pizza.html 

It was optimised with the following methods on main.js:

1. The function updatePositions() was optimised by: 
      * Read layout outside of the for loop.

2. The function document.addEventListener () was optimised by: 
      * Read layout outside of the for loop.
      * Removed querySelectorAll .
      * Reduced the number of background pizzas rendered to 100.
      * Dynamically calculated the number of moving pizzas required.
      * 
3. The function changePizzaSizes() was optimised by: 

      * Changed the slider value to a percent width.
      * Read layout outside of the for loop.






