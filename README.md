P5.js
Description:

This project is a simulation of vehicle behavior in a 2D environment. The vehicles, represented as triangles, exhibit pursuit, avoidance, and flocking behaviors. The environment includes a target that follows the mouse cursor, obstacles, and dynamic vehicles.

Table of Contents:

Setup
Usage
Controls
Code Structure

Setup
Open the project in a web browser or an integrated development environment (IDE) that supports p5.js.
Ensure you have the p5.js library linked in your project.

Usage
The simulation starts with two pursuer vehicles and a target that follows the mouse cursor.
Additional vehicles can be added by pressing the 'v' key.
Obstacles can be added by clicking on the canvas.
Press 'd' to toggle debug mode, which shows additional visualizations.
Press 'f' to launch a group of missiles.

Controls
Mouse: Move the cursor to guide the target.
Key 'v': Add a new vehicle to the simulation.
Key 'd': Toggle debug mode to display additional visualizations.
Key 'f': Launch a group of missiles.

Code Structure
The project consists of two main classes: Vehicle and Obstacle.
The Vehicle class defines the behavior and properties of the vehicles.
The Obstacle class represents static obstacles in the environment.
The setup function initializes the canvas and sets up the initial state of the simulation.
The draw function is responsible for updating and rendering the vehicles, target, and obstacles.
Various helper functions and methods are implemented for vehicle behaviors such as seeking, avoidance, pursuit, and flocking.
