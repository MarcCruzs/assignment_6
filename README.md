# CS 2520 Assignment 6
### Group Members: Marc Cruz, Prerna Joshi, Johnathan Mitri, and Zack Wawi

The purpose of this assignment is to refactor the file /Intro to Pygame Graphics/major league soccer animation/graphics_v4.py

To run the project, make sure pygame is installed, and run graphics_v4.py with python. 

#### Controls:
D - Toggles between Day and Night

L - Toggles the stadium lights on and off

### List of all refactorings:
- **Clouds** - Clouds can now be different colors and sizes depending on the parameters passed to the draw_cloud function. The cloud creation loop now generates a random size for each cloud.
- **Stars** - A drawStar function was added which draws a star based on the location, color, and scale passed to it. The star creation loop now generates a random color for each star. 
- **Flags** - drawLeftFlag and drawRightFlag functions were added, which draw the flag based on the position, pole color, and flag color passed to it. Using these functions, the flags were programmed to jump up and down to demonstrate the functions' ease of use. 
- **Goal** - The goal can now be drawn by calling the drawGoalPost function, supplying it the color and thickness of lines intended. 
- **Field** - The field's grass is now drawn by the drawGrass function. The grass is drawn with two alternating colors, which are passed as the two parameters of the drawGrass function.
- **Field Lines** - The white lines painted on the field have been refactored into one function that takes the intended color as a parameter.
- **Stadium Lights** - Capable of changing the colors of the lights and the pole of the stadium light as well. Also allowed the user to be able to change the location of the stadium lights.
- **Fence** - able to change the color of the fence 

### Link to graphics_v4.py:
https://github.com/MarcCruzs/assignment_6/blob/master/Intro%20to%20Pygame%20Graphics/major%20league%20soccer%20animation/graphics_v4.py
