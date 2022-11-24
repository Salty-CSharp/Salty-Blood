# Salty Blood

Salty Blood is a community suggested rebalance mod for MBAACC that increases the overall power level of the game.

If you have any ideas or suggestions, join the discord server, and put it in the suggestions channel.
https://discord.gg/83HmUsXkc6

## Installation

**It is recommended to have a seperate duplicate version of your Melty Blood folder.**

Download the .zip file from the green Code button on the github page and extract using a program like 7-zip.  
Move the data folder into the MBAACC installation such that the data folder is in the same folder as MBAA.exe.  
Rename or (strongly discouraged!) remove 0002.p and 0003.p so that the game reads the modded content instead.

## Uninstallation

Rename 0002.p back  
**OPTIONAL:** Delete data/ if you want to free up the space. This is not necessary, as renaming 0002.p back will cause the game to ignore it.

## FAQ

- If you need help with anything that isn't answered here, contact Skeleton#6953 on discord.

### For Users:



### For Developers:

- It might be helpful to create a hard link from the data folder to the MBAACC folder so changes can be tested, pushed, and pulled all without having to copy anything over anywhere.
To do this, open a cmd process as administrator (can be done by searching cmd or command prompt on your computer and choosing run as administrator from the right-click context menu).
Once inside, locate the git and game directories (can be done by navigating to them in windows explorer and clicking on the blank space to the right of the path).
Once done, type the following command in the command prompt and hit enter:

        mklink /J X:/path/to/game/directory/MBAACC/data X:/path/to/git/directory/Salty-Blood/data

Make sure the drive letters and paths are correct for each. Feel free to look up "mklink" and the error message (if applicable) for any information.