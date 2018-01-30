# Particles Generator using OpenGL and glut

A very simple particle system using euler's approximation with OpenGL and glut.

Particles are affected by forces like gravity and wind. They also "collide" with terrain at zero height, making an elastic collision (just a check that particle reached zero height, no real collision checks).

## Instructions ##
- Right-click to show the available menu with the given choices:
  - Toggle Generator, to stop or start particles generator.
  - Toggle Wind, to  switch on or off the wind (force applied at certain height).
