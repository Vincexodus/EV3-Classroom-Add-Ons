# EV3-Classroom-Add-Ons
Attempt to Replicate blocks from EV3 Lab Software that are unavailable in EV3 Classroom.

## Unavailable/Unsupported blocks 
<img src="/images/sensor(yellow).png" height="400">&nbsp;&nbsp;&nbsp;&nbsp;<img src="/images/advanced(blue).png" height="400">


## Replicated blocks (results not completely identical)
<img src="/images/classroom_draw.png" width="400">
Write block is used to draw shapes on screen, symbols like `.`, `a` produces weird/inconsistent results.
Unicode characters mostly results in small `...` dots on screen.
Current viable characters that works: `+`, `0`.

### Display Shape: Line
<img src="/images/shape_line.png" align="top" width="250">&nbsp;&nbsp;&nbsp;&nbsp;<img src="/images/touch_classroom.png" width="500">


### Display Shape: Rectangle
<img src="/images/shape_rectangle.png" align="top" width="250">&nbsp;&nbsp;&nbsp;&nbsp;<img src="/images/rectangle_classroom.png" height="500">
<br>To fll drawn rectangle, set `fill` to 1.

### Display Shape: Circle 
<img src="/images/shape_circle.png" align="top" width="250">&nbsp;&nbsp;&nbsp;&nbsp;<img src="/images/circle_classroom.png" height="500">
<br>To empty fill of drawn circle, simply add condition of radius between two ranges instead of one as diagram shown above.

<!-- ### Display Shape: Point  -->

### Touch Sensor: Bumped
<img src="/images/touchSensor_bump.png" height="200">&nbsp;&nbsp;&nbsp;&nbsp;<img src="/images/touch_classroom.png" align="top" width="400">
<br>Works both in if statement or two wait until statement. 

I also repair EV3 Large & Medium Motors [here](https://github.com/Vincexodus/EV3-Repair-Guide).

