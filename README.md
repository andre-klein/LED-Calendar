# LED-Calendar


In this code, LEDPins is an array that holds the pin numbers for each LED, and numOfLEDs is the number of LEDs, which is set to 31.

The setup function sets all the LED pins as outputs.

In the loop function, we use the getCurrentDay function to get the current day of the month, and then turn on the LED for the current day using a for loop. The rest of the LEDs are turned off using another for loop. The delay(1000) at the end of the loop function is to slow down the refresh rate so that the changes to the LED state are more visible.

The getCurrentDay function uses the time library to get the current date and time, and then returns the current day of the month using the tm_mday field of the tm struct.

This code will sync the LED array to the current date and turn on one LED at a time, cumulatively, to simulate a calendar. You can modify the code as needed to fit your specific requirements.
