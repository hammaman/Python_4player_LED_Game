Python_4player_LED_Game
=======================

My first Python 4 player game written for Python on the Raspberry Pi

Main idea:
Raspberry Pi running Python with GPIO functionality

Hardware:
Using I2C to interact with an Adafruit mini 8x8 LED display
Four controllers made from stripboard - each controller has a big switch and two LEDs.
First LED is red (TBC) and lights when the button is pressed and the forcefield is active.
The other LED is yellow (TBC) and is lit while the forcefield is recharging. 
Design of these controllers to be trialled using a breadboard.

Game idea:
Ball moves around 8x8 grid - speed gets faster and faster as game goes on
Ball tries to escape out of the 8x8 grid and can only be restrained by activating the forcefield on each side by pressing the button.
Forcefield is active for a short time (to be determined)
Forcefield has a recharge time (this may be set constant or change as the ball gets faster).

How does the game proceed?
Start with a countdown?
Are players eliminated, so need a third LED to indicate game over?
