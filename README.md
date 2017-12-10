# PIC-project

I'm trying to code a simple shooting gallery-style project where the 18f4685 microcontroller controls when the start button is pressed (and difficulty setting is chosen) to start a 30 second countdown while initiating an external 555 timer for a countdown clock, lighting all LED targets, which turn off when a hit is registered, and sending a high to the scoreboard. If all the LEDS are off while time is not up, to light them again. When the time is up, I want the program to stop registering scores and hits, but keeping the scoreboard value. The game's "hard mode" I wanted to do a random pattern of LEDs to light and scored when hit, but have given up on that idea, and will settle for a pattern of targets to light as targets. This is simply not working; can anyone help see what I'm doing wrong?
