# FreestyleJam
-y3tii Freestyle Jam V1.02-
For training Yvona Renown. Equip a silent score scroll that lasts 1 minute.
Yvona training caps at 2000 exp daily, 40 exp per 1 minute play, and another 40 exp for completing 5 combos.
This means that Yvona takes 50 minutes a day to cap, or 25 minutes with perfect combos.

Place the Freestyle Jam skill onto your hotkey bar in F1 position.
Extract the files to a folder and run freestyleV1.02.exe

Hardest part is setting up the region you want scanned.
If you want the smallest region possible, for maximum speed, read below. However you can also guesstimate the
region you want scanned, keeping in mind your screens resoltion. For reference, this bots defaults have been
configured for a screen resolution of 1366 x 768.

For smallest region, you need a printscreen of your screen, when you have a combo of 5.
	This is because once you've reached a 5 combo, the number of arrows do not increase.
	The smaller the search area, the faster the program can scan,
	scanning the whole screen can mean the bot is too slow to play the long combos.
To achieve this, play freestyle jam up to 5th combo (complete 4 combos).
	During the countdown timer for 5th combo, take a printscreen.
	Run Mabinogi in windowed mode, you will need to click outside of Mabinogi (onto your desktop),
	and take the printscreen from there. Otherwise printscreen will just save an image of the Mabinogi window,
	inside your Screenshots folder for Mabinogi, without the surrounding pixels of your desktop area etc.
	You will then need to open up this printscreen in a paint editing program, and use tools to find the
	dimensions in pixels, listed below.

The left input box:
	Number of pixels width (starting from the left of your screen), that will be ignored by the scan.

The right input box:
	Number of pixels width (starting from the left input box digit), that will be scanned.

The top input box:
	Number of pixels height (starting from the top of your screen), that will be ignored by the scan.

The bottom input box:
	Number of pixels height (starting from the top input box digit), that will be scanned.


You need a delay between key presses, because the icon from the previous keypress needs to update. Default 100.
An extended pause has been added between combos, to reduce the chance of missing the first keypress. Default 500.

-Troubleshooting-

Q. The program isn't doing anything.
A. Make sure your active window is Mabinogi, and that your F1 key is hotkeyed to Freestyle Jam.

Q. It keeps failing on the first keypress of a combo.
A. Increase the delay between combos, default value is 500.

Q. It keeps failing on a keypress mid-combo.
A. Increase the delay between keypresses, default value is 100.

Q. It keeps failing to complete longer combos, such as 4th or 5th.
A. Reduce the area that will be scanned, if you did not use the printscreen method mentioned above.
   If that doesn't help, decrease the delay between combos, default value is 500.
   Finally, if that doesn't help you can decrease the delay between keypresses, default value is 100.

Q. It doesn't enter any of the keys, when Freestyle Jam starts. No failed combo message.
A. Make sure you're scanning the right region for arrows, in your current resolution and window position.
   A fast way to check this, set the top and left input boxes to 0, and the bottom and right input boxes
   to your screens resolution, for example 768 and 1366.

Q. I'm not getting any training for Yvona.
A. Make sure you're using a song scroll that lasts for at least 1 minute.


Created by y3tii.
2016
