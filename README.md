# Sqaure-Tracer-Parallax-BASIC-STAMP-2
Initial Open loop test of the three wheeled robot.

TWO METHODS OF CODING ARE USED FOR THE ROBOT TO TRACE THE SQUARE.
Reason:
  The PBASIC STAMP EDITOR is incapable of  floating point arithmetic. Therefore, certain calculation errors are inevitable due 
  approximation. Two methods were used to compare which of them has minimal error for application purposes.

--
First Method:

This method uses a Lookup table for the pre-calculated number of loops("countLoop" = decides the amount of time the bot runs) 
for various input distances.Disadvantage: Limited number of values in the lookup table.

-
Second Method:

This method uses the STAMP Editor's Multiply Middle Operator(*/) that provides a reasonable approximation for values that
involve floating point arithmetic.

-
Result:

The Second Method had lesser error compared to Method 1, since it involves direct calculation, over pre-fixed values in the look-up 
table.



