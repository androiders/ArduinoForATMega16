# ArduinoForATMega16
###Adaptation of the Arduino core software to work on a standalone AVR ATMega16 micro controller

Background:
Arduino has a lot of nice libraries that make development easy and fast but the IDE is not good. Enabling the use of other IDEs like Eclipse is good. This is documented
on many other places on the interwebz but here is a convenience repository for code adaptation. 

Compilation: 
Compilation needs to be done specifically for target device and for certain operating frequency. Set these at compile time.

It is specifically targeted at ATMega16 device but could be made to work on other devices as well. Documentation will be updated continuosely.

What works:
* Digital pin operations work. 
* Serial library works. (small change that was the same as for atmega8, probably mega8 and mega16 are very similar)
* ADC works at least a little. By wiring AREF (pin 32) to VCC the vref of the ADC is set. This works at least with a tft touch screen with the adafruit touchscreen library.

What does not work:
*Nothing more than the above has been tested.
