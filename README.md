# Hooverboard

This is a simple interactive webpage called "Hoverboard" that generates a grid of squares and changes their colors when hovered over.

# How to Use
To use the Hoverboard, follow these steps:

1. Open the index.html file in a web browser.

2. The webpage will display a grid of squares on a dark background.

3. Move your mouse over the squares to see them change color.

4. Move your mouse out of a square to restore its original color.

# Files
The following files are included in this project:

- index.html: This file contains the HTML structure of the webpage. It includes references to the CSS and JavaScript files and provides a container element for the squares.

- style.css: This file contains the CSS styles that define the appearance of the webpage, including the background color, square dimensions, and transitions.

- script.js: This file contains the JavaScript code responsible for generating the squares, handling the hover events, and changing the colors dynamically.

# Functionality
The functionality of this webpage is as follows:

1. The JavaScript code selects the container element with the id container from the HTML document and assigns it to the container variable.

2. An array of colors (colors) is defined. Each color in the array is represented by a hexadecimal value.

3. A constant SQUARES is defined with a value of 500, indicating the number of squares to be generated.

4. A loop is used to create the specified number of squares. Inside the loop:

a. A new div element is created and assigned to the square variable.

b. The class square is added to the square element using classList.add('square').

c. Event listeners are attached to the square element. When the mouse is hovered over a square, the setColor function is called, and when the mouse is moved out of a square, the removeColor function is called.

d. The square element is appended to the container element.

5. The setColor function is defined, which takes an element parameter representing a square. Inside the function:

a. A random color is obtained from the colors array using the getRandomColor function.

b. The background color of the element is set to the random color.

c. The box shadow of the element is set to create a glow effect using the same random color.

6. The removeColor function is defined, which takes an element parameter representing a square. Inside the function:

a. The background color of the element is set to a default dark color.

b. The box shadow of the element is set to a default color to remove the glow effect.

7. The getRandomColor function is defined, which returns a random color from the colors array. It generates a random index between 0 and the length of the colors array and returns the color at that index.

In summary, this webpage generates a grid of 500 squares and dynamically changes their colors and box shadows when they are hovered over. The colors are randomly chosen from the colors array defined in the JavaScript code.

# Acknowledgements
The Hoverboard webpage was created by [ Brian ] for [ showcasing front end skills ].

If you have any questions or feedback, please contact [ cepteinhawks@gmail.com ].

Enjoy your interactive Hoverboard experience!