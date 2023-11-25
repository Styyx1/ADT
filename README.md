# Althro's Dev Tools (ADT)

![image](https://raw.githubusercontent.com/The-Animonculory/ADT/main/.github/ADTBanner.webp)

Wabbajack Modlist Installer by Althro

<table stlyle="border: none;">
<tr>
<td><img src="https://raw.githubusercontent.com/The-Animonculory/AVO/main/.github/WJIcon.png" width="64px" /></td>
<td><a href="https://github.com/wabbajack-tools/wabbajack/releases">Download on Wabbajack</a></td>	
<td><img src="https://raw.githubusercontent.com/The-Animonculory/ADT/main/.github/AMLogo.webp" width="72px" /></td>
<td><a href="https://discord.gg/aetherius-modding"><img alt="Discord" src="https://img.shields.io/discord/1132691434420576337?style=for-the-badge&label=Aetherius%20Modding"></a></td>
</tr>
</table>

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

## Contents
  - [Preamble](#preamble)
  - [System Requirements](#system-requirements)
  - [Installation](#installation)
    - [Pre-Installation](#pre-installation)
    - [Wabbajack Installation](#wabbajack-installation)
      - [Installing Wabbajack](#installing-wabbajack)
      - [Downloading and Installing ADT](#downloading-and-installing-adt)
      - [Problems with installation](#problems-with-installation)
  - [Post-Installation](#post-installation)
    - [Post Processing](#post-processing)
  - [Playing the List](#playing-the-list)
    - [Starting up the list](#starting-up-the-list)
    - [In Game MCM Options](#in-game-mcm-options)
  - [Updating ADT](#updating-the-modlist)
  - [FAQ](#faq)
   - [Removing the modlist](#removing-the-modlist)
  - [Credits and Thanks](#credits-and-thanks)
  - [Contact](#contact)

## Preamble
Designed to be the mod author's tool kit, Althro's Dev tools comes with everything you need to create and test your mods. Featuring mandatory engine fixes, DLL libaries to build plugins with, a fully patched creation kit and post processing libraries, it's the ideal playground to both work and build on.

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

## System Requirements

### Disclaimer

Owing to the need to clean master files and certain errors with Wabbajack, AVO only supports **English Steam** versions of Skyrim AE. **GOG and other Languages are not supported**.

Only, Windows 10 and 11 work with Wabbajack fully. LTSC, special variants, lightened editions or any other modified variant **WILL NOT WORK**.

***

If you can run the vanilla game, you can run ADT.

**NOTE**: You need to have **.NET V8** and **Java Runtime Environment** installed to make the full use of this list.

Space required: Approx 18GB (downloads included).

## Installation

Installing ADT is relatively easy and, if you have Nexus Premium, will be a simple waiting game. If you are updating the modlist, you can safely skip to the [updating section](#updating).

### Pre-Installation

Prior to installing ADT, please complete the following steps.

1. Install [Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe) & [.Net Runtime v5 desktop x64](https://dotnet.microsoft.com/download/dotnet/5.0/runtime).
2. Change Skyrim so it does not [automatically update](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
3. Fully uninstall Skyrim by deleting the folder and the Skyrim Special edition folder inside \Documents\My Games\.
4. Fully disable OneDrive and any other programs which hook into user file areas.
5. Reinstall Skyrim into a location that is not Program files. Somewhere like `C:\Games` is a good location. If you only have one drive, look into LostDragonist's [SteamLibrary tool](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide).
6. Start the game once and let it do the graphics check. Do not worry about the settings as it will be replaced during installation.
7. Install the [Creation Kit on steam](https://store.steampowered.com/app/1946180/Skyrim_Special_Edition_Creation_Kit/).
8. Run it once and select `NO` when it asks about unpacking scripts. They are handled by ADT already.
9. Close the creation kit and continue with the installation steps.
10. Remove/Disable any 3rd party antivirus such as MalwareBytes or Webroot. These **will** mess with the installation and, in the case of the latter, causes more problems than it solves.

### Wabbajack Installation

#### Installing Wabbajack

Once you have completed pre-installation, download the [latest version of Wabbajack]((https://github.com/wabbajack-tools/wabbajack/releases)) and place it in a folder such as `C:\Games\Wabbajack`. Do not place it in program files, on your desktop or in your downloads folder. I recommend placing it on an SSD as it will work quicker on there.

#### Downloading and Installing ADT

Downloading and installing ADT can take a while depending on your internet connection and computer. To install ADT, complete the following steps.

1. Open Wabbajack and click on browse modlists.
2. Press the download button on ADT and wait for it to download.
3. Set the installation folder to be somewhere like `C:\Games\ADT`. **Do not install it to your desktop or downloads folder.**
4. The download location does not need to be on a SSD but it makes installing a bit faster.
5. Press the play button to begin.
6. Go and pet your nearest fluffy animal whilst Wabbajack does its thing. Alternatively read through this readme again.
7. If the installation is successful, jump for joy and move onto [post installation](#post-installation). If the installation is unsuccessful, follow what is below.

##### Problems with installation
It is possible that you may encounter an error with Wabbajack when installing. Some common issues are listed below.

- Could not download x:
	- Big files can fail to download due to connection issues. You can either run wabbajack again or download the file manually. If you decide to manually download it, make sure to place it in the same place as the other downloads.
	- **Make sure you have downloaded the Creation Kit!**

- x is not a whitelisted download:

	 - This will happen when I update the modlist. Please check if there is a new update or wait until you see a release ping.

- Wabbajack could not find my game folder:

	- Either buy the game or go back to the [Pre-Installation](#pre-installation) step.

- Antivirus reports a virus:
	- You did not follow the steps in [Pre-Installation](#pre-installation). Go back and follow it.
	- If you have followed it then you can fix this by [adding an exclusion for Mod Organizer in windows defender](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

## Post-Installation

### BethINI

You will need to use BethINI to set your monitors screen resolution. If you don’t, you’ll be running the game at 1440p which is a lot more performance intensive. To set this, complete the following steps.

1. Go to where you have installed the list and open the tools folder.
2. Open the BethINI folder and run the program.
3. Set your resolution, in my case this is 1440p.
4. Choose whether you want borderless/windowed or Fullscreen.
5. Press save and exit.

### Post Processing

ADT included both Community Shaders and ENB for you to utilise. The list uses Root Builder and Stock Game so please bear that in mind.

## Playing the List

### Starting up the list
Open the installation folder and double click on the program called `ModOrganizer.exe`. 

Make sure the dropdown box on the right is set to `SKSE` and press the `Run` button.

### In-Game MCM options
`ADT has no MCM options required.`

- This serves as a placeholder in case you want to use the Readme as some sort of template.
	
## Adding mods to ADT

All the tools you require to add mods to this list are included in the download. If you want some general tips on how to safely mod, visit our [Modding Tutorials](https://github.com/The-Animonculory/Modding-Resources) repository.

### Anniversary Edition

ADT supports the latest verison of Skyrim, but **does not require** the paid update. If you wish to use the paid creation club content, simply add it to the list and then resolve any conflicts that may appear.

## Updating the modlist

Before updating, please check the changelog and back up your saves. You may need to start a new game after certain updates.

Updating is like installing the list. Simply make sure your paths are the same and tick the `overwrite existing modlist` button. **Note**: Any mods you have added will be deleted when updating.

## FAQ

### What's the difference between ADT and Skyrim Modding Essentials (SME)?

SME is aimed at users wanting to create their own list and comes with a lot more content inlcuding mesh fixes and minor tweaks. ADT is for mod-authors who want a blank canvas to build/test their creations on in a 1.6.xx environment. Whilst there is some overlap, they are aimed at different audiences. Plus, Phoenix is a friend and we don't compete :)

### Why is the SkyUI SDK not included?

Due to errors with downloading the file from google drive, it's not included. If you want to make MCM stuff, you can get it from [this link](https://drive.google.com/file/d/0B4iEH8ar3jtxbFlkVzZSVHN0alk/view?usp=sharing&resourcekey=0-bTFKQxbSl6Y_4-dZDHE0AQ) and install it as shown in the picture below.

![SkyUI SDK Placement](https://raw.githubusercontent.com/The-Animonculory/ADT/main/.github/SkyUI%20SDK.webp)

### What tools does ADT come with?

The following tools are presnt in ADT:
- Bethesda Asset Extractor
- Bodyslide & Outfit Studio
- Cathedral Assets Optimizer
- CLibrary
- Champolion
- Creation Kit
- Creature Behaviour Generator
- Dylbills Papyrus Functions
- ENB Manager
- Fallrim Tools
- MCM Helper SDK
- NifSkope
- Octagon
- SNIFF
- SSE Nif Optimizer
- Synthesis
- xEdit

## Removing the Modlist
Simply delete the folder, and you have uninstalled it.

## Credits and Thanks

- _YOU_ for reading this.
- The Aetherius Modding Team.
- Sr Kaio for testing
- Halgari and everyone the WJ Team - Wabbajack is awesome and so are you.

## Contact

Whilst I am available primarily on [my server](https://discord.gg/xRrHRsb5e9), please check the [issues](https://github.com/The-Animonculory/ADT/issues) tab on github first if you have any issues. DO NOT DM ME ON DISCORD.
