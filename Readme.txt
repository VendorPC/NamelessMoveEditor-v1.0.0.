=============================
Nameless Move Editor v1.0.0.
=============================
This is a Generation 4 Move Editor by Vendor.

This tool was originally made in concept on the Pokecommunity thread sometime ago.
Unfortuantely I have no real clue who made and created the source code for the tool.
I just recently came across the code when browsing the threads and I took it upon myself to begin working on it and editing it's functionality.
This tool works with DPPt and HGSS.

Here is how it works:
To edit the Move Files you need to extract the Waza_tbl NARC out of the game that you wish to edit.
In HGSS the file is located at a/0/1/1; You can rename the file to whatever you like just make sure it have has ".narc" as it's file extension.
In Platinum the file is located at poketool/waza/pl_waza_tbl.narc you can keep the name as is as the ".narc extension is already there.
In Diamond and Pearl the file is located at poketool/waza/waza_tbl.narc you can keep the name as is as the ".narc extension is already there.
(Personally I like to use NitroExplorer2b)

Then you wanna run the .exe included in this folder, that should boot up the menu.
Go to File\Open Rom and then select the Waza_tbl NARC you just extracted.
After this go to Module/LoadModule then go to the "Interals" Folder of this download and the file name should be "Attack Data Module" open that one.
Your all set!

To Save Changes Press the "Enter" Key or go to File\Save Changes
To write changes to the ROM go to File\Save Rom
To reinsert back into your ROM just use your Rom Explorer and go to where you found the original file and reinsert.

Additional Helpful Information:
"Automatic" Move Targeting will cause a move to always fail if the moves effect is not related to who or what it targets.
(Metal Burst is a example of how Automatic targeting works if you want to look it up on Bulbapedia.)
Priority Settings can go in a range of -7 to 5.
Base Power can only go up to 255 and Accuracy can only go up to 100%.
For moves that always want their move effect active (For Example: Brick Break) set the effect chance % to "0" it will always trigger this way.

For Moves like Zap Cannon that always paralyze set the effect chance % to 100%.

