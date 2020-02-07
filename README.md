For use with the following repository: https://github.com/watagi/AutoWatt

WARNING: THIS PROGRAM REQUIRES THAT SOMEONE JOINS. IF IT SENDS IN AN EMPTY LOBBY, DESYNC WILL OCCUR AND YOU WILL NEED TO REDO THE PROCESS AGAIN.

&nbsp;

**HOW TO USE THE FILES**

These files are meant to replace the "Joystick.c" file and the "makefile" in the above repository. 

&nbsp;

**IMPORTANT PROGRAM INFORMATION**

I used an Ardino UNO R3 for this program with an atmega16u2 MCU. This program will work on docked switches.

&nbsp;

This program hosts dens automatically online using the link code 8075 (BOTS). It uses Airplane mode to back out of raids 
instead of closing the game. To make the program go public instead, make the following changes:

&nbsp;

1. Type `/*` in the beginning of Line 92.
2. Type `*/` at the end of Line 122.

&nbsp;

The program sends the lobby in once the lobby timer reaches 2:00. Everyone has to be ready by then in order for the lobby
to enter successfully. Otherwise, the program will close the game and the lobby will be lost. 

&nbsp;

**INSTRUCTIONS**
1. Collect any Watts from the den if you have not done so. Return to the overworld and face the den.
2. Activate your bike to ensure that the "A" input instantly takes you to the raid screen.
3. Go offline if you are not already.

&nbsp;

**THINGS TO ADJUST**

Everyone's internet speed is different. This program was optimized for my own connection. There are certain timers that 
depend on your internet speed. I have listed them below.

&nbsp;

__Internet Based__

1. Line 67 (The time it takes for you to connect to the internet after pressing the "+" sign and before closing the "connected" prompt
2. Line 76 (The time it takes for you to see your first stamp on the left side of your screen)
3. Line 90 (The time it takes for the "Communicating" prompt to complete)
4. Line 127 (The time it takes for the "Communicating" prompt to complete)

__Other Important Timers__

5. Line 160 (If people are getting disconnected after the lobby is sent properly, increase this value)









