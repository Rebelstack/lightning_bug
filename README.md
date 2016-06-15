# lightning_bug
EAGLE hardware design and production files for Lightning Bug
# Product Description
Lightning Bug is an acceleration-activated PWM current supply.  Inspired by flying trapeze, 
it is designed to be worn on the body and and connected to a strip of LEDs.  The LEDs are lit
with an intensity that varies with acceleration.  Powered with a standard 9V battery,
Lightning Bug provides a maximum of close to 1A which will be divided among the number of
parallel connected LEDs.
# Release Notes
-It is somewhat difficult to insert and remove battery with the battery clip specified.
-R1 and C7 form a low pass recommended by the accelerometer, but may not be necessary 
for this application.  Replace R1 with a 0 Ohm short to remove.
-Standard 4-40 screws/nuts can be used to affix the battery clip to the PCB, but two
of the four mounting holes have components close which may interfere.
# Licensing
This work is licensed under a Creative Commons Attribution-ShareAlike 4.0 International License
