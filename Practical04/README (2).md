# Practical 04
* This folder contains practical 04.
* The program calculates the approximate area under the curve using the trapezoidal rule of the tangent function between 0 and 60 degrees.

## To compile: 
* gcc -o trap02 .trap02.c -lm

# To execute:
* ./trap02 .
  
# Output:
TanArr[0] = 0.000000<br>
TanArr[1] = 0.087489<br>
TanArr[2] = 0.176327<br>
TanArr[3] = 0.267949<br>
TanArr[4] = 0.363970<br>
TanArr[5] = 0.466308<br>
TanArr[6] = 0.577350<br>
TanArr[7] = 0.700208<br>
TanArr[8] = 0.839100<br>
TanArr[9] = 1.000000<br>
TanArr[10] = 1.191754<br>
TanArr[11] = 1.428148<br>

Initial area (sum at x(0) and x(12)) = 0.000000<br>
Value of the sum after the loop is: 14.197204<br>

Trapezoidal result is : 0.619470<br>
Real result is : 0.693147  <br>

The program calculates and prints the tangent values for each interval, then computes the intermediate areas using the trapezoidal rule. Finally, it displays the total result from the trapezoidal method and compares it with the actual value of log(2).
