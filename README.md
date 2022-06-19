# Nukem-Rico
Files for Nukem modification for Starship Troopers: Terran Command

[MOD] Nuke em Rico! 
One thing that I constantly found my self asking throughout my campaign playthrough was “Where the hell are the nukes?!”
Now that ive completed my playthrough on brutal, I decided to dive into looking at the game files on how to make modifications after tinkering with the demo version.

Before installing, make a backup of your original files!!
Step 1.  Navigate to the folder “C:\Program Files (x86)\Steam\steamapps\common\Starship Troopers - Terran Command\Starship Troopers_Data\StreamingAssets\Data”
Note: your installation path might be slightly different depending on where you set steam to install games.
Step 2. Make a backup of Abilities.csv, copy paste that somewhere safe!
Step 3. From the download, move the modified Abilities.csv into “StreamingAssets\Data” & overwrite the existing file.
Step 4. Nuke em Rico!

OPTIONAL
If you look at the video showcasing the nuke in action, you might notice that there’s a description of the tactical nuke and a quote from the movie.  This isn’t there by default and is something I added in myself.  If you would like this description added to your game,
Step 1. Navigate to the folder “C:\Program Files (x86)\Steam\steamapps\common\Starship Troopers - Terran Command\Starship Troopers_Data\StreamingAssets\Language”
Step 2. Make a backup of English_0.csv, copy paste that somewhere safe!
Step 3. From the download, move the modified English_0.csv into “StreamingAssets\ Language” & overwrite the existing file.
Note:  This is only for the English version of the game, but the same concept applies if you would like to add it to your language specific version by following the steps below.


How to do it manually  (Again make backups of everything, don’t blame me for breaking your game)
For the Nuke
Navigate to the folder “C:\Program Files (x86)\Steam\steamapps\common\Starship Troopers - Terran Command\Starship Troopers_Data\StreamingAssets\Data”
Open Abilities.csv
Go to Line 71 or wherever “Klendathu_Nuke” is located
Change "Editor Only" to "unlockable"
Change  cooldown  "/" to "60 seconds"   <--or modify to your hearts desire
Added 10 to the "Elite" Cell to give a unit icon if player selects the ability
Nuke icon appears to be missing..unable to find it in the assets right now..using canister icon

Save the file.

For the description & quote 
Navigate to the folder “C:\Program Files (x86)\Steam\steamapps\common\Starship Troopers - Terran Command\Starship Troopers_Data\StreamingAssets\Language”
If your language is French for example, open French_0.csv
Scroll down to the bottom of the excel and add 2 new entries
ability_klendathu_nuke_title	Tactical Nuke
ability_klendathu_nuke_descr	Shoot a nuke down a bug hole, you got a lot of dead bugs. -Private Ace Levy
Save the file.

NOTE:  The game WILL NOT load if ANY the .csv files are currently open by the system, be sure to close them before launching.
