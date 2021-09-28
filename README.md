## PLEASE READ

This project is abandoned. A new version is in the works, and will be linked here upon completion. The latest version of Phasmophobia altered how the game handles save data, meaning all save editors will no longer work. 

# The Phasmophobia Save Editor

This is the first real Phasmophobia saveData editor.  This program descrambles the saveData and allows you to edit it in the application, then rescrambling it in a readable format for an *unmodded* version of Phasmophobia.

## FAQ
* Q: Will this get me banned?
* A: Definitely not.  This only changes saveData.  Just don't set your money to stupid amounts, and you'll be fine (over 250,000 triggers the 'anti cheat', which sets it back to 0)  
* Q: I have problem X and don't know what to do.  Help pls?
* A: Create an issue post. Do not add me on Discord for bug reports.
* Q: I have a suggestion and would rather DM it to you. Can I add you on Discord?
* A: Chroma#1000. 
* Q: Can this application corrupt your game save?
* A: During it's creation I didn't corrupt any of my testing saves, but, you should DEFINITELY keep multiple backups JUST in case anything happens.

## Getting Started

* Step 1: Navigate to where your saveData.txt file is.  You can do this by opening file explorer, and in the path bar, paste `%appdata%/../LocalLow/Kinetic Games\Phasmophobia`
* Step 2: Make a copy of your saveData.txt file.
* Step 3: Extract the zip you downloaded from Releases into a folder. (https://github.com/chromamods/phasmo-save-editor/releases)
* Step 4: Place the saveData.txt file in the SAME FOLDER as the PhasmoSaveEditor.exe file.
* Step 5: Launch PhasmoSaveEditor.exe and do what you want to the save.  Follow on screen prompts for editing stuff. 
* Step 6: When you're done, make sure to select the 'Exit and save' option.  Your now modded saveData.txt file will be in the generated "Modified" folder. The "Backups" folder holds the last edited file before you made changes and saved, so in your case (assuming you do not run the program multiple times), it'll be your unmodified save.
* Step 7: Overwrite the old saveData.txt in your `Kinetic Games/Phasmophobia` directory with the modified saveData.txt
* Step 8: Launch Phasmophobia and enjoy your now modded save.
 
**Note 1:** Relaunching the program multiple times does NOT edit the modified file.  If you want to mod the modded save file, you HAVE to move the `saveData.txt` from `Modified` to the root directory (by PhasmoSaveEditor.exe).

**Note 2:** Currently, i'm getting reports that sometimes the editor isn't properly saving data.  Keep an eye out for a new update for when I do fix it (Soon™)

### Known Bugs

* There is next to no error checking in user inputs, meaning if you try to input something that you shouldn't (negative numbers, characters where it's asking for an int, etc), you likely will get undesired side effects.  You can avoid this by just putting in the right stuff the first try and not try and break the program. (I'll add error checking in later, but not super worried about it).

* Sometimes, the Exp does not update to the value you input.

## Screenshots
![Screenshot 1](https://i.imgur.com/O2qsUfV.png)
![Screenshot 2](https://i.imgur.com/4Gtgq5T.png)
