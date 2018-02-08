## Website Performance Optimization portfolio project

### Instructions
To view the portfolio website download all the files and open index.html in your browser.


## Optimizations to Pizza Site
1. Modified the code to calculate the number of pizzas needed to fill the webpage based on browser inner dimensions.

2. running updatePositions when the scrolling event fires. This optimizes animations to run in a single paint cycle.

3. Reduced number of pizzas at DOM load to 32 as that also filled the screen completely. Also moved fetching of movingPizzas1 DOM element outside the loop.

4.  Cached the needed DOM elements so that the brower isn't querying the DOM every time the for loops are iterated in the updatePositions and changePizzaSizes funcitons
