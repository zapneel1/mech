# Wiper Mechanism (Simulation) 

Simulator for a **4-bar wiper mechanism** with motion analysis and UI for user to change parameters.<br>

### Team Members: 
1. 22ME10087 - Swapneel Layek
2. 22ME10067 - Prodyumno Paik
3. 22ME10013 - Asjit Sinha

### Features: 
1. Smooth real-time simulation using JavaScript.
2. Real-time parameter adjustments possible.
3. Graphs for speed vs time and mod acceleration vs time.
4. Toogle buttons for velocity and acceleration vectors.
5. Data for area wiped, velocity, acceleration and its components. 

### Libraries Used: 📚
A simple JavaScript library called [``PrairieDraw.js``](https://prairielearn.readthedocs.io/en/latest/PrairieDraw/) is used for drawing technical diagrams and animations on an HTML5 canvas. <br>
``PrairieDraw.js`` uses the Sylvester.Vector class of [``Sylvester.js``](http://sylvester.jcoglan.com/docs.html) library to specify positions and directions for the drawing.
<br>

- PrairieDraw Repo :- [martin70/PrairieDraw.js](https://github.com/martin70/PrairieDraw.js)

See the [userManual.html] in the User Manual folder, or use the JsDoc toolkit to generate the documentation with the included Makefile.

## Instructions: 
- Adjust the parameters to the values you want and then click "Start Animation" button.
- You can also adjust the parameters during the simulation to see real-time changes.
- Toogle butttons to reveal or hide items.
- "i" buttons are added for extra information.
- Press "Reset" button to get to the default setttings.
