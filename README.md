<!-- omit from toc -->
# Styyx Tooling for Dev (STD)

![image](https://github.com/Styyx1/ADT/blob/main/Resources/NewTitle.webp?raw=true)

Wabbajack Modlist Installer by Althro and Styyx

<table stlyle="border: none;">
<tr>
<td><img src="https://raw.githubusercontent.com/Althro/ADT/main/Resources/WJIcon.png" width="64px" /></td>
<td><a href="https://github.com/wabbajack-tools/wabbajack/releases">Download on Wabbajack</a></td>	
<td><img src="https://raw.githubusercontent.com/Althro/ADT/main/Resources/AMLogo.webp" width="72px" /></td>
<td><a href="https://discord.gg/aetherius-modding"><img alt="Discord" src="https://img.shields.io/discord/1132691434420576337?style=for-the-badge&label=Aetherius%20Modding"></a></td>
</tr>
</table>

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

<!-- omit from toc -->
## Contents 
- [Preamble](#preamble)
- [System Requirements](#system-requirements)
  - [Disclaimer](#disclaimer)
- [Installation](#installation)
  - [Pre-Installation](#pre-installation)
  - [Wabbajack Installation](#wabbajack-installation)
    - [Installing Wabbajack](#installing-wabbajack)
    - [Downloading and Installing STD](#downloading-and-installing-std)
      - [Problems with installation](#problems-with-installation)
- [Post-Installation](#post-installation)
  - [BethINI Pie](#bethini-pie)
- [Playing the List](#playing-the-list)
  - [Starting up the list](#starting-up-the-list)
- [Adding mods to STD](#adding-mods-to-std)
  - [Anniversary Edition](#anniversary-edition)
- [Updating the modlist](#updating-the-modlist)
- [FAQ](#faq)
  - [Some downloaded files have a red triangle, is that normal?](#some-downloaded-files-have-a-red-triangle-is-that-normal)
  - [What's the difference between STD and Skyrim Modding Essentials (SME)?](#whats-the-difference-between-std-and-skyrim-modding-essentials-sme)
  - [Can I use STD as a base for my modlist?](#can-i-use-std-as-a-base-for-my-modlist)
  - [The game starts zoomed in](#the-game-starts-zoomed-in)
  - [No valid Game Data with mods in STD:](#no-valid-game-data-with-mods-in-std)
  - [How can I improve performance of the list?](#how-can-i-improve-performance-of-the-list)
  - [Why is the SkyUI SDK not included?](#why-is-the-skyui-sdk-not-included)
  - [What tools does STD come with?](#what-tools-does-std-come-with)
  - [Toggle UI hotkey?](#toggle-ui-hotkey)
- [Removing the Modlist](#removing-the-modlist)
- [Credits and Thanks](#credits-and-thanks)
- [Support](#support)

## Preamble
Designed to be the mod author's tool kit, Styyx Tooling for Dev comes with everything you need to create and test your mods. Featuring mandatory engine fixes, DLL libaries to build plugins with, a fully patched creation kit and modding libraries, it's the ideal playground to both work and build on. If you are led to the list thinking it's an ideal base to build your own modlist with, you've been misled, while it can be used for that, it's probably not what you want.

And to prevent any confusion, STD does use the version 1.6.1170 of Skyrim.

Full list of mods used can be found [here](https://loadorderlibrary.com/lists/adt)

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

## System Requirements

### Disclaimer

**GOG and other Languages aside from English are not supported due to how Wabbajack works.**.

Only, Windows 10 and 11 are fully supported with Wabbajack. LTSC, special variants, lightened editions or any other modified variant, this includes any variant of linux, **MAY OR MAY NOT WORK** and I definitely don't bother supporting any of that.

***

If you can run the vanilla game, you can run STD.

**NOTE**: You need to have **.NET V7 & V8** and **Java Runtime Environment** installed to make the full use of this list, chances are that **.NET V9** will work as well, but I don't know.

Space required: Approx 19GB (downloads included).

## Installation

Installing STD is relatively easy and, if you have Nexus Premium, will be a simple waiting game. If you are updating the modlist, you can safely skip to the [updating section](#updating).

### Pre-Installation

Prior to installing STD, please complete the following steps.

1. Install [Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe) & [.Net 9 Desktop runtime](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-9.0.11-windows-x64-installer).
2. Make sure your skyrim install is cleaned and its files are not modded. Otherwise fully uninstall it and reinstall it.
3. Change the language of the game to English, other languages are simply not supported.
4. Start the game once and let it do the graphics check. Do not worry about the settings as it will be replaced during installation.
5. Launch the game to the main menu and allow it to download the paid addon files.
6. Install the [Special Edition Creation Kit on Steam](https://store.steampowered.com/app/1946180/Skyrim_Special_Edition_Creation_Kit/).
7.  Run it once and select `No` when it asks about unpacking scripts (You can select ``Yes`` or ``No`` actually, but unpacking it takes forever).
8.   Close the creation kit and continue with the installation steps.
9.   Remove/Disable any 3rd party antivirus such as MalwareBytes or Webroot. These **will most likely** mess with the installation and, in the case of the latter, causes more problems than it solves.

### Wabbajack Installation

#### Installing Wabbajack

Once you have completed pre-installation, download the [latest version of Wabbajack]((https://github.com/wabbajack-tools/wabbajack/releases)) and place it in a folder such as `C:\Games\Wabbajack`. Do not place it in program files, on your desktop or in your downloads folder. I recommend placing it on an SSD as it will work quicker on there.

#### Downloading and Installing STD

Downloading and installing STD can take a while depending on your internet connection and computer. To install STD, complete the following steps.

1. Open Wabbajack and click on browse modlists.
2. Press the download button on STD and wait for it to download.
3. Set the installation folder to be somewhere like `C:\Games\STD`. **Do not install it to your desktop or downloads folder.**
4. The download location does not need to be on a SSD but it makes installing a bit faster.
5. Press the play button to begin.
6. Go and read through this readme again.
7. If the installation is successful, move onto [post installation](#post-installation). If the installation is unsuccessful, follow what is below.

##### Problems with installation
It is possible that you may encounter an error with Wabbajack when installing. Some common issues are listed below.

- Could not download x:
	- Big files can fail to download due to connection issues. You can either run wabbajack again or download the file manually. If you decide to manually download it, make sure to place it in the same place as the other downloads.
	- **Make sure you have downloaded the Creation Kit for Special Edition and not the ancient Creation Kit for Legendary Edition!**
 	- **Make sure your version of Rare Curios is from within the Game and not from verifying with steam** if you think this is dumb for a list without AE DLC support, i do so as well, please join the wabbajack discord server an tell them cause I'm forced to require it. Same goes if you don't know how to install it, I do not support issues the app administration created.

- x is not a whitelisted download:

	 - This will happen when I update the modlist. Please check if there is a new update or wait until you see a release ping.

- Wabbajack could not find my game folder:

	- Either buy the game on steam or go back to the [Pre-Installation](#pre-installation) step.

- Antivirus reports a virus:
	- You did not follow the steps in [Pre-Installation](#pre-installation). Go back and follow it.
	- If you have followed it then you can fix this by [adding an exclusion for Mod Organizer in windows defender](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

## Post-Installation

### BethINI Pie

This replaces the old BethINI and can be started from within mod organizer. Just select it in the executable dropdown.

## Playing the List

### Starting up the list
Open the installation folder and double click on the program called `ModOrganizer.exe`. 

Make sure the dropdown box on the right is set to `SKSE` and press the `Run` button.
	
## Adding mods to STD

All the tools you require to add mods to this list are included in the download. If you want some general tips on how to safely mod, visit our [Modding Tutorials](https://github.com/The-Animonculory/Modding-Resources) repository. Adding mods is your own responsibility and I will not provide any type of support for that whatsoever.

### Anniversary Edition

STD supports the latest verison of Skyrim, but **does not require** the paid update and also does not include it. If you still want to use it, see [Adding mods to STD](##Adding-mods-to-STD).

## Updating the modlist

Before updating, please check the changelog and back up your saves. You may need to start a new game after certain updates.

Updating is like installing the list. Simply make sure your paths are the same and tick the `overwrite existing modlist` button. **Note**: Any mods you have added will be deleted when updating.

## FAQ

### Some downloaded files have a red triangle, is that normal?

Yes, this basically just means that the mod was not downloaded from nexus so MO2 doesn't fully know where the mod came from.

### What's the difference between STD and Skyrim Modding Essentials (SME)?

SME is aimed at users wanting to create their own list and comes with a lot more content inlcuding mesh fixes and minor tweaks. STD is for mod-authors who want a blank canvas to build/test their creations on. Whilst there is some overlap, they are aimed at different audiences.

### Can I use STD as a base for my modlist?

Yes you can, but I would recommend using Skyrim Modding Essentials (SME) for that as it is made for that very purpose.

### The game starts zoomed in

Adjust your resolution with either BethINI Pie or SSE Display Tweaks

### No valid Game Data with mods in STD:

This just means MO2 does not know the location of the files is still valid even if they're not in the data folder or the mod is meant as a resource so it doesn't actually need to be loaded anyway. That's not an issue no matter what and you can safely ignore it.

### How can I improve performance of the list?

Literally by getting a better PC. This list comes with only vanilla visuals and that means you'd struggle running the vanilla game already

### Why is the SkyUI SDK not included?

Due to errors with downloading the file from google drive, it's not included. If you want to make MCM stuff, you can get it from [this link](https://drive.google.com/file/d/0B4iEH8ar3jtxbFlkVzZSVHN0alk/view?usp=sharing&resourcekey=0-bTFKQxbSl6Y_4-dZDHE0AQ) and install it, but this is not a supported action, just some information in case you need the SkyUI SDK.

### What tools does STD come with?

The following tools are present in STD:
- Bethesda Asset Extractor
- Bodyslide & Outfit Studio
- Cathedral Assets Optimizer
- Champolion
- Creation Kit
- Fallrim Tools
- NifSkope
- Octagon
- Pandora Behaviour Engine
- SSE Nif Optimizer
- Synthesis
- xEdit

STD also comes with various dev libraries like:
- CLibrary
- MCM Helper SDK
- Dylbills Papyrus Functions

### Toggle UI hotkey?
Num-


## Removing the Modlist
Simply delete the folder the modlist is in and you have uninstalled it.

## Credits and Thanks

- Althro for allowing me to continue to work on it.
- _YOU_ for reading this.
- The Aetherius Modding Team.
- Halgari and everyone the WJ Team.

## Support 

I only support the latest version of the modlist. No exceptions. \
If you encounter bugs with the list as is open a new issue on the list's github page, but check if it's not already mentioned cause duplicate bug reports do not mean it will be magically fixed faster. \
Support for the list is only for the base list as is, I do not provide support for adding stuff, removing stuff or anything in between. I also do not provide support for working with the tools, you have internet, use it!
