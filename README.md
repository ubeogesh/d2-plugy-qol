## What's Included

- Storm.DLL fix. Allows you to downgrade your official 1.14 battle.net install.
- [PlugY](http://plugy.free.fr/en/index.html) - adds unlimited stash, shared stash, Diablo Clone, Ubers, Ladder-only runewords, etc.
- [BaseMod](https://d2mods.info/forum/viewtopic.php?t=65492) - auto gold pickup, extra actions with shift-clic
- [5 is not 6](https://www.snakebytestudios.com/projects/mods/diablo-2-mods/#fixedfont) - makes 5s look like 5s instead of 6s.
- [No Intro](https://www.snakebytestudios.com/projects/mods/diablo-2-mods/#nointro) - skip the Blizzard intro videos when you start the game in full screen
- [LootFilter](https://github.com/Synial/SynFilter/tree/cd4ab9d8b51320973c7b3df9c90b74b3d1ea8f91/xfiles) - adds the loot filter from [Path of Diablo](https://pathofdiablo.com/).
- [MultiRes](https://drive.google.com/drive/folders/1hLbrYs_U7eVcK-bWOom_Lr2_Y839AVba) - adds widescreen resolutions to the game.

## How To Install

### Preparation:
1. If you don't already have latest Diablo 2 version, purchase and install Diablo 2 and Diablo 2 LoD from [Battle.net shop](https://us.shop.battle.net/en-us/family/diablo-ii)
2. Open your Diablo 2 installation folder, and delete all the files that don't end with .mpq.
If you don't see file extensions (endings), enable their display under "View" menu in the file explorer.
The only remaining files should be:
- d2video.mpq
- d2char.mpq
- d2data.mpq
- d2exp.mpq
- Patch_D2.mpq (this one can be deleted too)
- d2xvideo.mpq
- d2xtalk.mpq
- d2music.mpq
- d2xmusic.mpq
- d2speech.mpq
- d2sfx.mpq
3. Download [1.13d patch archive](http://plugy.free.fr/Patch/LODPatch_113d.zip) and unpack it to your Diablo 2 folder
4. Install [PlugY](http://plugy.free.fr/PlugY_The_Survival_Kit_v11.02.exe). This link is to Installer verison. ZIP file version won't do.
5. Download [Glide Wrapper](http://www.svenswrapper.de/gl32ogl14e.zip) and unpack it into your Diablo 2 folder.5
After unpacking, run the glide-init program, go to settings and check "desktopresolution" box. 
This installation is needed for proper Full Screen gaming, as well as for the Widescreen Resolution.

### Full Install
Install full pack from here: https://github.com/ubeogesh/diablo2-addons/releases/download/1.0-Full-Pack/Full.Pack.zip. Just unpack to Diablo 2 folder and it's done.

### Modular install
1. Download the modular release: https://github.com/ubeogesh/diablo2-addons/releases/download/1.0/Modular.zip
2. Apply Storm.DLL fix: copy the Storm.DLL file into your Diablo 2 folder, and overwrite (detailed instructions inside 1 StormDLL)
3. Install any desired addons: BaseMod, Widescreen, Skip Intro, 5 Not 6, POD Loot filter. See detailed instructions inside each folder.

### Starting and optional configuration
1. Use PlugY.exe to start the game (it's inside Mod PlugY folder). By Default PlugY installer also creates a shortcut on the desktop.
2. If you want to play in windowed mode, edit the PlugY.ini file.
Make sure that it doesn't have "-3dfx" in the Params= line. 
Scroll a bit down to [WINDOWED], and activate it (0 means inactive, 1 - active). 
ActiveWindowed makes game windowed
RemoveBorder removes window border (frame)
You can configure window position offset by X and Y (from top left corner), and also Width and Height (these values are in pixels).
For Fake Full Screen Full HD experience you can use following values: X=0 Y=0 Width=1920 Height=1080
Don't be afraid to experiment with these. Then save the file and test your changes. If you afraid to mess up, just back up the PlugY.ini file before.

### How To Uninstall

1. Delete all files from Diablo 2 folder except MPQs.
2. Download 1.14d patch ZIP from PlugY website (very bottom of the page) and extract it into Diablo 2 folder.

### Known issues

When working with POD loot filter, PlugY option to relocate save files doesn't work and  causes an error:
BYTE 56 wanted but E8 found to change memory at 6FF6E16A.
Make sure to deactivate it:

    [SAVEPATH]
    ActiveSavePathChange=0

If you want to change save path, do it through Mod PlugY\config\config.cfg file. Note that you have to type double backslashes in the path there like so:
\Save Path\="C:\\Users\\ubeogesh\\OneDrive\\Games\\D2Saves"


## Credits

- Inspired by whipowill's mod compilation: https://github.com/whipowill/d2-plugy-qol, but I didn't like that it's "all or nothing" and the instructions
- [PlugY](http://plugy.free.fr/en/index.html) provided by [Yohann Nicolas](http://plugy.free.fr/en/index.html) (v11.02).
- [BaseMod](https://www.dropbox.com/s/fj3f5smvxdld3kx/BaseMod106.zip) provided by [devurandom](https://d2mods.info/forum/viewtopic.php?t=65492) (v1.06).
- [FontFix](https://www.snakebytestudios.com/projects/mods/diablo-2-mods/#fixedfont) provided by [SnakeByteStudios](https://www.snakebytestudios.com/projects/mods/diablo-2-mods/).
- [NoIntro](https://www.snakebytestudios.com/projects/mods/diablo-2-mods/#nointro) provided by [SnakeByteStudios](https://www.snakebytestudios.com/projects/mods/diablo-2-mods/).
- [DropMod](https://www.snakebytestudios.com/projects/mods/diablo-2-mods/#betterdrops) provided by [SnakeByteStudios](https://www.snakebytestudios.com/projects/mods/diablo-2-mods/).
- [KeepEquip](https://www.snakebytestudios.com/projects/mods/diablo-2-mods/#equipmentdeath) provided by [SnakeByteStudios](https://www.snakebytestudios.com/projects/mods/diablo-2-mods/).
- [LootFilter](https://github.com/Synial/SynFilter/tree/cd4ab9d8b51320973c7b3df9c90b74b3d1ea8f91/xfiles) provided by [Path of Diablo](https://pathofdiablo.com/).
- [MultiRes](https://drive.google.com/drive/folders/1hLbrYs_U7eVcK-bWOom_Lr2_Y839AVba) provided by [SlashDiablo](https://www.reddit.com/r/slashdiablo/comments/7z5uy1/hd_mod_and_maphack_new_release/).
