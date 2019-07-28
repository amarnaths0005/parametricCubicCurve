# parametricCubicCurve
App to display a Parametric Cubic Curve in 3D, and modify its parameters.

HTML Program to draw and manipulate a Parametric Cubic Curve in its Four Point Form and Hermite Form.

Requirements:
   1. Should enable the user to modify the x, y, z coordinates of four points, corresponding to u values of 0, 1/3, 2/3 and 1,
      in the Four Point Form of a Parametric Cubic Curve.
   2. Should enable the user to modify the x, y, z coordinates of the two end points u = 0 and 1, 
      and also the x, y, z components of the derivatives at these two end points
      in case of the Hermite Form of the Parametric Cubic Curve.
   3. The range for the coordinates should be in [-1, 1], and the range
      for the derivatives should be [-10, 10].
   4. Should display the Parametric Cubic Curve in 3D, and this curve should 
      change dynamically as the user modifies any of the values using sliders.
   5. Should display the bounding box of dimension 2 units, centred at the origin.
   6. Should enable the user to modify the camera angle, from which viewing is done.
   7. Should enable the user to modify the u value, and should display a moving point
      on the curve as the user modifies this value.

Tested on Chrome and Firefox, on Windows.
Uses the three.js library. 

Open the file <i>index.html</i> in your browser.

Please send feedback to amarnaths.codeproject@gmail.com

Screenshot

![Screenshot of ParametricCubicCurve](https://github.com/amarnaths0005/parametricCubicCurve/blob/master/pcCurve.png)

