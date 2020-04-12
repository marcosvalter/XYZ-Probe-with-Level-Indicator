# XYZ-Probe-with-Level-Indicator

This Macro uses a Level Dial Indicator, assembled in a holder, to center a product and set the Z value of a surface in a milling machine.
It uses the old school way of center and uses a permanent reference for Z mesure, such as a table or vise.

You need:
  - One Dial Indicator with variable stylus angle;
  - One holder for the Dial Indicator;
  - This Macro to make the calculations for you and set the desired values.
  
How to use:
  - The X/Y center is made in the old school whay. You will be asked to touch the necessary points, one by one, and the calculations are made.
  - The Z position is made by calibrating the stylus position with the reference plane. For example, with the stylus almost horizontal, touch the reference surface till zero. Then you touch the surface to be mesured, and the Macro will calculate for you.
  
You must adjust the line #305 for your current set.

Example 1:

G65 P8813 X0 Y0 Z0 S54

- Sets X, Y and Z to zero on G54


Example 2:

G65 P8813 X10 Y-10 Z0 S1

- Sets the upper left corner as X/Y zero point and Z to zero on G54 P1


Example 3:

G65 P8813 Z10 S54

- Sets Z to 10 on G54



Example 4:

G65 P8813 H1

- Display help messages.
