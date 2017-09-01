# FinalProject
FinalProject120B
POWER
The device can be powered either via USB or by the provided wall plug.
Menu
Upon powering the device, the unit will automatically show the main menu screen.
You can make your selection via the four buttons on the bottom of the bread board. They are ordered one to four from left to right.
At any time you wish to return to the menu, you can press the reset button which is located to the right of the ATMEGA-1284 processor.
Game Mode
Upon pressing one from the main menu, you will automatically be sent to the level selected in the menu option “choose level.” Default level is set to 1 if not set.
The LED matrix will light up its corners in correlation of the 4 large buttons.
*The buttons are slightly arranged by height:*
Button 1 = Top Left of Matrix
Button 2 = Top Right of Matrix
Button 3 = Bottom Left of Matrix
Button 4 = Bottom Right of Matrix
Choose Level
Upon entering the “choose level” mode via button 2, you will notice a numerical value on the LCD display.
From there you can change levels from one to five
Button 1 = Increase Level By One
Button 2 = Decrease Level By One
You can return to the main menu by pressing Button 3.
Chosen level will be saved upon returning to the main menu.
High Score
Upon entering the “High Score” mode via button 3, you will be shown with the highest score recorded.
The high score is determined by the highest number of blinks the user has gotten correct.
Single Blinks Pressed Correct = +1
Dual Blinks Pressed Correct = +2
OFF
To power down the unit, simply unplug the USB or power plug.
The high score will be saved to EEPROM and can be viewed at a later time upon 




disclaimer: i couldn't fully test this C code, and i wasn't able to test it on my breadboard because I broke a couple components.  This is all I can submit.  
