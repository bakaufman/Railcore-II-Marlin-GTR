For Railcore II kit using BTT GTR 1.0 board. 
Novel board settings in pins file:
1) Moved fans down one position, top position for fan(s) on electronics. Activated with motion. Z holds if you cancel print, but will release if you complete a print with the right exit gcode with a delay.
2) Steppers are X, Y, Z, E, Z2, Z3.  You must make that order. E wiring is reverse.
3) Tried to model settings after Raicore Duet as a starting point. Current version is the product of many mistakes, some expensive. 
4) Uses bltouch for bilinear. UBL wasn't working out reliably
