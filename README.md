# 3ds.hacks.guide Setup Script
A GodMode9 script for automating some of the Move EmuNand steps on 3ds.hacks.guide.

## Instructions
Copy the file "3ds.hacks.guide_Move_EmuNand_Script.gm9" to "\gm9\scripts\" on the SD card. Then open GodMode9, press the HOME button, choose "Scripts...", and choose "3ds.hacks.guide_Move_EmuNand_Script". The script will let you know what to do from there.

## Features
The script performs the following actions:
* Creates Nand Backups of Both the SysNand and EmuNand
	* To allow the SysNand to be restored in the event the EmuNand Backup has issues.
* Backup/Restore DSiWare Saves Automatically
	* Copies the SysNand DSiWare Saves to \gm9\out\ then restores them after the EmuNand Restore has completed.
* Automates the Move EmuNand process on 3ds.hacks.guide

The script features the following:
* Noob-proof
	* Does a lot of the work for the user, so there's less room for mistakes.
* Future-proof
	* The script is set up so that it should run without issues in the future, in case it isn't updated for newer exploits, apps, etc. (which it will be anyway!).
* User-interface
	* The script will show its current progress on the top screen, so you'll know what the script is currently working on.
