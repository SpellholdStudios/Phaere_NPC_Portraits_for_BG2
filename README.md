
![Latest Release](https://img.shields.io/github/v/release/SpellholdStudios/Phaere_NPC_Portraits_for_BG2?include_prereleases&color=darkred)<a name="top" id="top"> </a>
![Platform](https://img.shields.io/static/v1?label=platform&message=windows%20%7C%20Mac%20%7C%20linux&color=informational)
![Language](https://img.shields.io/static/v1?label=language&message=English&color=limegreen)

<div align="center"><h1>Phaere NPC Portraits for BG2 (WIP)</h1>

<h3>A mod hosted by Spellhold Studios for Baldur's Gate II: SoA and ToB (classical and EE games),<br>
Baldur's Gate Trilogy and EET<h3>

</div><br />


**Authors:** Phaere and Rastor  
**Mod Website:** <a href="http://www.shsforums.net/forum/234-miscellaneous-released-mods/">Spellhold Studios</a>  
**Mod Forum:** <a href="http://www.shsforums.net/topic/60737-super-firkraag-updated-to-v16-ee-compatible/">Super Firkraag</a>  


[Read the mod's readme](http://spellholdstudios.github.io/readmes/phaere_ports-readme-english.html)

[Download the mod at Spellhold Studios](http://www.shsforums.net/files/file/1257-super-firkraag/)<br>

&nbsp;

**Note:** This mod was first released at <a href="http://web.archive.org/web/20120414212350/http://www.rpgdungeon.net/content/view/30/44/">RPGDungeon.net</a>. As this site is no more available since many years, it was time to save it from disappearance. It is now hosted at Spellhold Studios with Rastor authorization.


&nbsp;

<div align="center">
<a href="#intro">Overview</a> &#8226; <a href="#compat">Compatibility</a> &#8226; <a href="#installation">Installation</a> &#8226; <a href="#credits">Credits and Acknowledgements</a> &#8226; <a href="#versions">Version History</a></br>
</div>

<hr>


## <a name="intro" id="intro"></a>Overview

This mod .

<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="compat" id="compat"></a>Compatibility

This mod is designed to work on the following Infinity Engine games: the original Baldur's Gate II (BG2 or just SoA) with or without the Throne of Bhaal (ToB) expansion, Baldur's Gate II: Enhanced Edition (BG2:EE), the conversion projects <a href="http://www.shsforums.net/forum/261-bgt-weidu/">Baldur's Gate Trilogy (BGT)</a> and <a href="https://github.com/K4thos/EET/releases">Enhanced Edition Trilogy (EET)</a>.

Phaere NPC Portraits for BG2 is a WeiDU mod, and therefore should be compatible with all WeiDU mods. However, we cannot test every single one. If you encounter any bugs, please <a href="http://www.shsforums.net/topic/60737-super-firkraag-updated-to-v16-ee-compatible/">report them on the forum</a>!

The mod is not compatible with other mods that change NPC portraits. Phaere’s NPC Portraits will function properly with those mods but any new NPC portraits that were added by any other mods will not be seen in-game.

>Although it is not required for the Phaere NPC Portraits for BG2 to function properly, classical game players are strongly recommended to download and install the latest version of the <a href="http://www.gibberlings3.net/bg2fixpack/">BG2 Fixpack</a> before proceeding with the installation of this mod.<br>
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="installation" id="installation"></a>Installation

#### Notes

*If you've previously installed the mod, remove it before extracting the new version. To do this, run **`setup-phaere_ports.exe`**, un-install all previously installed components and delete the :file_folder: **phaere_ports** folder.*

*When installing or un-installing, **do not close the DOS window** by clicking on the **X** button! Instead, press the **Enter** key whenever instructed to do so.*

*__Disable any antivirus__ or other memory-resident software before installing this or any other mod. Some (particularly avast and Norton!) have a tendency to report false positives with mod activity, resulting in failed installs.*

## 

#### Enhanced Editions Note

The Enhanced Editions are actively supported games. Please note that every patch update will wipe your current mod setup! If in the middle of a modded game you might want to delay the patch update (if possible) as even after reinstalling the mods, you might not be able to continue with your old savegames. Alternatively, copy the whole game's folder into a new one that can be modded and will stay untouched by game patches. It is important that you install the mod to the language version you are playing the game in. Otherwise, the dialogues of the mod will not show but give error messages.

## 

#### Windows

Phaere NPC Portraits for BG2 for Windows is distributed as an extractable compressed archive and includes a WeiDU installer.

Extract the contents of the mod archive into the folder of the game you wish to modify (*the folder which contains the "CHITIN.KEY" file*), using <a href="http://www.7-zip.org/download.html">7zip</a>, <a href="http://www.rarlab.com/download.htm">WinRAR</a>, or another file compression utility that handles .zip files. On successful extraction, there should be a :file_folder: phaere_ports folder and a setup-phaere_ports.exe file in your game folder. To install, simply double-click **`setup-phaere_ports.exe`** and follow the instructions on screen.

Run **`setup-phaere_ports.exe`** in your game folder to reinstall, un-install or otherwise change the components settings.

## 

#### Mac OS X

Phaere NPC Portraits for BG2 for Mac OS X is distributed is distributed in the same compressed archive and includes a WeiDU installer.

First, extract the files from the archive into your game directory. On successful extraction, there should be a :file_folder: phaere_ports folder, setup-phaere_ports and setup-phaere_ports.command files in your game folder. To install, simply double-click **`setup-phaere_ports.command`** and follow the instructions on screen.

Run **`setup-phaere_ports.command`** in your game folder to reinstall, un-install or otherwise change the components settings.

## 

#### Linux

Phaere NPC Portraits for BG2 for Linux is distributed as a compressed tarball and does not include a WeiDU installer.

Extract the contents of the mod to the folder of the game you wish to modify.

Download the latest version of WeiDU for Linux from <a href="https://github.com/WeiDUorg/weidu/releases">WeiDU.org</a> and copy WeiDU and WeInstall to /usr/bin. Following that, open a terminal, **cd** to your game installation directory, run tolower and answer 'Y' to both queries. You can avoid running the second option (linux.ini) if you've already ran it once in the same directory. To save time, the archive is already tolowered, so there's no need to run the first option (lowercasing file names) either if you've extracted only this mod since the last time you lowercased file names. If you're unsure, running tolower and choosing both options is the safe bet.

To install, run **`WeInstall setup-phaere_ports`** in your game folder. Then run **`wine BGMain.exe`** and start playing.

## 

#### Note for Complete Un-installation

In addition to the methods above for removing individual components, you can completely un-install the mod using **`setup-phaere_ports --uninstall`** at the command line to remove all components without wading through prompts.</br>
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="credits" id="credits"></a>Credits and Acknowledgements

**Authors:** Phaere and <a href="http://www.shsforums.net/user/1153-rastor/">Rastor</a>  

#### Programs/tools used in creation:

- <a href="https://github.com/WeiDUorg/weidu/releases"><acronym title="Weimer Dialogue Utility">WeiDU</acronym></a>, by Wes Weimer, the bigg and Wisp.
- <a href="https://github.com/Argent77/NearInfinity/releases">Near Infinity</a>, by Jon Olav Hauglid, FredSRichardson, and Argent77.
- <a href="http://www.shsforums.net/topic/31285-infinity-explorer-v085/">Infinity Explorer</a>, by Dmitry Jemerov / bigmoshi.
- <a href="https://gibberlings3.github.io/iesdp/"><acronym title="Infinity Engine Structures Description Project">IESDP</acronym></a>, maintained by igi and lynx.
- <a href="http://notepad-plus-plus.org/">Notepad++</a>, by the Notepad++ team, Don Ho, and the spellcheck plug-in.
- <a href="http://www.shsforums.net/files/file/1048-weidu-highlighter-for-notepad/">WeiDU Notepad++ Highlighters</a>, by Argent77.
- <a href="https://forums.beamdog.com/discussion/78364/infinity-auto-packager-automatically-generate-and-adds-mod-packages-to-release-when-you-publish-it">Infinity Auto Packager</a>, by AL|EN.

## 

#### Copyrights Information

###### Phaere NPC Portraits for BG2 is not developed, supported, or endorsed by BioWare&trade; or Interplay/BlackIsle, Overhaul, Beamdog or the Wizards of the Coast. It was developed by Phaere and Rastor, based on material from the game Baldur's Gate II and its expansion.
###### All mod content is &copy;Phaere and Rastor.
###### Baldur's Gate II: Shadows of Amn and Baldur's Gate II: Throne of Bhaal &copy; TSR, Inc. The BioWare Infinity Engine is &copy; BioWare Corp. All other trademarks and copyrights are property of their respective owners.

###### This mod was created to be freely enjoyed by all Baldur's Gate II players, and its content is free of rights. However, it should not be sold, published, compiled or redistributed in any form without the consent of the author.

###### The modding community for the Infinity Engine has been going strong for more than 10 years now, and is the culmination of thousands of unpaid modding hours by fellow fans of the game. Modders produce their best work and players get the best, well-supported mods when we all work together.
###### There are two big ways to upset this harmony. One is to claim someone else's work as your own. The second is to host and redistribute a mod without permission from the author(s).
###### Be kind to your fellow players and modders. Don't do either.</br></br>
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="versions" id="versions"></a>Version History

#### Version 5.0

- Replaced old-school `DECOMPILE_BCS_TO_BAF` plus `COMPILE_BAF_TO_BCS` process with more accurate `DECOMPILE_AND_PATCH` command.
- Fixed two bugs with .bcs files patching: *aerie* (was applying *r#aeport* spell instead of *r#pparie*), was patching *sarev25a* file instead of *sarev25*.
- Removed useless backup folder.
- Lower cased files.
- Updated WeiDU installer to v246.
- Uploaded mod to official Spellhold Studios GitHub mirror account.

## 

#### Version 4.0 (16 June 2005)

- Streamlined some TP2 code.
- Mac OS X now supported.
- Cleaned up BG2 folder.
- SoA-only installation now supported.
- The portrait changes are now retroactive.
- Installer is faster now.
- Updated WeiDU installer to v183.

## 

#### Version 3.0

- Added portraits to Bodhi and Mazzy.
- Another attempt at fixing the bugs with Aerie’s portrait.
- Updated WeiDU installer to v168.

## 

#### Version 2.0

- Added portraits for Sarevok and Jaheira.
- Aerie in ogre form no longer has a portrait.

## 

#### Version 1.0 (16 October 2004)

- Initial release.
<div align="right"><a href="#top">Back to top</a></div>
