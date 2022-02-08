# Display-Digital-Watch
##This project is an implementation of a digitalwatch on an Atmega16 microcontroller, written in embedded C

#How it works
##start timer0 to generate compare interrupt every 250 MiliSeconds,for each 4 times of interrupt occurance led to increament seconds count by one,
##and for each 60 seconds, minutes counter increamented by one minute,
##and for each 60 minutes, hours counter increamented by one hour,
## activate external interrupt INT0 ,using a push button to control resetting all counters then the watch.

#Hardware parts
##atmega16
##push button
##multipled 7segments
