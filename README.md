ServoTimer2
===========

ServoTimer2 is a simple servo library for Arduino 1.x that does not use Timer1 in case of a conflict.

Original (c) 2008 Michael Margolis, updated for Arduino 1.x and example added by Nick Bontrager 2013.

------------

This fork changes MAX_PULSE_WIDTH from 2250 to 2600 and changes MIN_PULSE_WIDTH from 750 to 350. Nothing else is changed. I changed these values to get the full 0 to 180 degrees of rotation I needed in my project using an Arduino Mega 2560 r3 and a micro servo 9g SG90. Not guaranteed to work for you. No guarantees or support offered.
