# SRB2Vita-Builds

SRB2-Vita.vpk is the initial beta release of the project. It uses Software Rendering with a resolution matching the PSP (480x272).

Feb. 11 - 06:57 - This is a build updated with fixed controls.

Feb. 11 - 13:52 - This is the first build using VitaGL as a renderer in place of the game's standard OpenGL implementation.

Feb. 12 - 09:23 - Another OpenGL build. Runs at Vita's native resolution (960x544). The game crashes when the camera moves behind a liquid source (water, lava, goop, etc).

Feb. 12 - 09:42 - Most recent build (as of Feb. 18th), runs at PSP resolution. The crash has been fixed, but garbage is drawn on the screen.

# Usage
Install srb2-vita.vpk using VitaShell, then replace the eboot.bin located at "ux0:/app/SNCRBBLST" with one of the bin files from this repo.

Download [SRB2-Data.zip](https://downloads.devkitpro.org/srb2_data.zip) and place the files at "ux0:/data/srb2vita"

Create a folder named "srb2" at "ux0:/data/srb2vita" for storing configurations and save files.


# Notes 
This is a beta where you cannot complete all levels. [Here](https://cdn.discordapp.com/attachments/400692448902512650/547142675216990211/gamedata.dat) is a fully complete save file that will allow you to use level select and other cheats. Place gamedata.dat at "ux0:/data/srb2vita/srb2"

SRB2 Vita is based on SRB2 2.1.20, which serves as the base of the [3DS](https://github.com/derrekr/srb2_3ds/) and the initial [Switch](https://github.com/carstene1ns/SRB2/tree/switch-port) ports. As this is an older version, many improvements to OpenGL aren't available, which results in rendering issues on levels as well as the introduction.
