# automated_curtain
A microcontroller project with a motor, clock, and light sensor that opens and closes curtains to control light levels throughout the day.

# Desired Functionality

* Open and close curtains without user intervention
* Consistenly simulate sunrise at desired wake-up time by reacting to a light sensor, and sunset at night

# Hardware

* Microcontroller. Probably RaspberriPi Zero
* Warning LED(s) for low battery power, and inability to reach desired light targets
* Power. A battery that can be easily removed and charged with USB
* Motor. Something powerful enough, won't catch on fire, and not too noisy
* Limit sensors. In case the motor doesn't know where the curtain is
* RTC and battery for having a timer that remember the time even when the main battery is charging
* Light sensor. Determine how much to open or close the curtains based on desired light levels, allowing it to react to changing outside conditions
* Mounting hardware. Preferably something like 3M Command products that are easily removable and do not require making holes in the wall
* Optional: Cheap display to show current light levels, and maybe target light levels, like a thermostat does

# Software

* Preferably Python
