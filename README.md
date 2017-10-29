# Arduino-Due-Drv-8825-Tiny-G2
A "shield" and the compiled binary for Due being used for a CNC with drv 8825 and tiny G2

The "shield" is completed as per the required electrical connections But... if you want a refined version you might have to do it yourself.. feel free to use these files as you see fit.

I have used a lot of jumpers to save me time while routing and to make it just simpler.. 

I am using 4 Drv 8825 Polulu drivers for 3 Nema 23 stepper motors and 1 Nema 17 stepper motor. 

2 Nema 23's go on the Y gantry opposite to each other hence Y and Y' where the 4 pin stepper connections are reversed and everything else is shared.

1 Nema 23 goes on the X axis

and 1 Nema 17 for the Z axis.

Here are my pinouts:



Pin   -            Function

8      -           Enable (Shared by all 4 steppers)

7      -           STEP - X - Axis

6      -           DIRECTION - X - Axis

5      -           STEP - Y & Y' - Axis

4      -           DIRECTION - Y & Y'- Axis

3      -           STEP - Z - Axis

2      -           DIRECTION - Z - Axis

37     -           M 1 MICRO STEPPING Z Axis DRV8825

39     -           M 2 MICRO STEPPING Z Axis DRV8825

41    -            M 3 MICRO STEPPING Z Axis DRV8825

42    -            M 3 MICRO STEPPING Y & Y' Axis DRV8825

44    -            M 2 MICRO STEPPING Y & Y' Axis DRV8825

46    -            M 1 MICRO STEPPING Y & Y' Axis DRV8825

48    -            M 3 MICRO STEPPING X Axis DRV8825

50    -            M 2 MICRO STEPPING X Axis DRV8825

52    -            M 1 MICRO STEPPING X Axis DRV8825

53    -            Limit Switch X + (max)

51    -            Limit Switch X - (min)

49    -            Limit Switch Y + (max)

47    -            Limit Switch Y - (min)

45    -            Limit Switch Z + (max)

43    -            Limit Switch Z - (min)

