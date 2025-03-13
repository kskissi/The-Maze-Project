Maze project
Background Context

The goal of this project is to create a game in 3D using raycasting !

Tasks

0. Walls !

In this first part, you’ll have to:

Create a window with SDL2
Use raycasting to draw walls on your window !
You don’t need to be able to rotate the camera during the execution in this part, but you must provide a way to change the angle of the camera in your code to see if it works after recompiling it
The color of the walls must be different from the color of the ground/ceil
The map doesn’t need to be parsed from a file, but you must provide a way to modify it in your code to see if it works after recompiling it. (e.g. using an array of arrays of integers or characters).
Example:



In the following image, the camera is the red square, and the visible area is painted in green:



1. Orientation

In this part, you must draw a different color depending on the orientation of the walls.

You must at least draw walls facing NORTH and SOUTH in a different color from walls facing EAST and WEST.
Example:



2. Rotation

You must provide a way to rotate the camera during the execution.

For example, you can rotate the camera when the left,right arrows are pressed on the keyboard.
Or you can rotate the camera when the mouse moves, just like a FPS game !
Example:



3. Move

You must provide a way to move the camera during the execution.

For example, you can move the camera when the w,a,s,d keys are pressed on the keyboard.
Example:


