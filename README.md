# rotate-rectangle


A class that rotates a four sided polygon a desired number of radians.
Based on the graphics.py package by John Zelle.

params : (width(as float), height(as float), rotation(as float, radians), centre point(as point))

Calculates corner points by modelling the corners as if they were on a circle:
 Calculates the radius of circle.
 Calculates angle between vertical line passing through the centre point and the line connecting the 
  centrepoint and the top right edge before rotation.
 Creates a list with new angles. 
 Creates a list of new points by using the parametrization <(radius)*cos(angle), -(radius)*sin(angle)>.
 Draws lines connecting all the points.
