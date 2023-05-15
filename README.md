The Scripted Amiga Emulator for Itch.IO hosted Amiga Games/Tools.

WORK-IN-PROGRESS!

An Amiga Emulator in pure Javascript and HTML5 tailored to be used for Itch.IO hosted games/tools.

The orginal version of the emulator uses absolute paths which made it unfit to be used for Itch.io play-in-browser scenarios.
This fork has been modified to use relative paths instead which will work just fine in Itch.io.

Usage: Just add your .adf to the /adf folder and reference it in the index.js (work-in-progress).

// Change this to your ADF file name.
const ITCH_ADF = "SysInfo4_4.adf"   // <-- change this to your .adf file name.

The current configuration will be an A1200 with 2MB Chip and 4MB Fastram and two HD floppies to give you some more headroom.

Zip all files and subdirectories in the folder that contains the index.html and upload it to Itch.io.

Note: I do not plan to make any changes / bug fixes to the emulator itself, this is just a modification so you can use this awesome emulator for your Itch.io builds.

Visit https://scriptedamigaemulator.net or https://github.com/naTmeg/ScriptedAmigaEmulator for the original work of naTmeg.
