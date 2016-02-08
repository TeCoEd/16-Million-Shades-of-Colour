# 16-Million-Shades-of-Colour
Simple program to cycle through all RGB colour combinations on the Raspberry Pi SenseHat

The SenseHat’s LED Matrix boasts 64 LEDs which can show over 16 million colours, but how?  Each LED is made up of three smaller Red, Green and Blue elements which can be coded to display up to 255 different shades. That is 255 shades of Red, a zero value gives you no red! 255 shades of Green and Blue too.   So, how do you get over 16 million colours?  Well, the maths is simple, 255 x 255 x255 which is 16581375 combinations.  What better way to show this than to use the SenseHat and some Python to calculate each colour and display it on the LEDs.  But, how long do you think it takes to cycle through and to display all the colours? 
