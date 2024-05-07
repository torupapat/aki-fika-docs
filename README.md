# aki-fika-docs

## Useful links
[Patcher](https://pixeldrain.com/u/gr6nXU1N)

1. Download and install latest build of Official Tarkov
2. After install and/or patching successfully play one offline game (at least you get to spawn in game then you can disconnect of the game and close it)
3. Download SPT-AKI Installer from [official site](https://ligma.waffle-lord.net/SPTInstaller.exe)
    - SPT-AKI Installer required some dependency such as .NET etc. you can install that beforehand or open up the program and click through "X" mark to install
4. Create new folder called "SPT-AKI" and put SPT-AKI Installer into that folder
    - Make sure that you have enough space for new copy of the game (at least 60GB)
5. Now Installer will automatically find EFT location, copy, downgrade and install patcher on its own.
6. After finished, copy and paste latest "user" and "BeplnEx" in Modpack and Bundles files into X:/SPT-AKI 
7. run Aki-server.exe once to make sure that Fika and mods generate necessary files. When its said "Happy Playing!!", close aki-server.exe
8. run Aki-launcher.exe and click setting
9. in URL put in http://ip-address:6969 in the box
10. go back to the first page and you should be able to register an account
11. put in your username and click "Login/Register" and select any starting pack (if you want to play Zero to Hero then select that!)
12. Now you can click "Start" to play the game!


# Change-Logs

## V0.2.2
Date 24/05/07
### Server Side (user/mods or sometime BeplnEx)
- Rearrange server mods load order
- Adjusted Hephaestus's preset selling price to be more realistic ("discount":55)
- Added MoreCheckmark 1.5.13 backend
- Added AmmoStats 3.1.1
- Added new trader Painter 1.0.3
- Added Blackcore 1.0.8 (Painter's dependency)
- Added Mag Tape 1.0.4 (Painter's dependency)
- Added Compatibility for SPT-Realism
- Added AnyStand 2.0.0 (for show anything on stands)
- Added Tactical Gear Component 1.0.6
- Added Sandcore 1.0.3
- Added Greencore 1.0.7
- Added Redcore 1.0.3
- Added Whitecore 1.0.5


### Client Side (BeplnEx/plugins)
- Added Color Converter API dependency for other mods
- Added MoreCheckmark 1.5.13

### Bundle Files
- Repackage bundles to include new mods bundles

## V0.2.1
Date 24/05/04
### Server Side (user/mods or sometime BeplnEx)
- Added ChooChoo Trader Modding 1.6.2

### Client Side (BeplnEx/plugins)
- Added ChooChoo Trader Modding 1.6.2's plugins
- Added Wara Modding Stats Helper 1.0.3 plugins

## V0.2.0
Date 2024/05/04
### Server Side (user/mods or sometime BeplnEx)
- Updated SPT Realism to 1.1.2
- Added Geff's Scope Overhaul SPT-380
- Added SamSWAT EOTech Vudu Overhaul SPT-380
- Added Fontaine FOV-Fix 1.11.0-SPT-3.8.0
- Added WTT-Pack n' Strap
- Added WTT-Head Voice Selector
- Added WTT-The Long Lost Heads of Yojenkz
- Added MoxoPixel-WarHeads-1.0.2
- Added BRNVG 1.5.3 (Mods for realistic thermal goggles)
- Added BBRTP 1.0.2 (Mods for thermal sight improvement)

### Client Side (BeplnEx/plugins)
- Updated SPT Realism plugins to 1.1.2
- Added No hurry Async Bundle 1.1.0 (helped with client to load bundle packed from server)
- Added Fontaine FOV-Fix 1.11.0-SPT-3.8.0 (Fix FOV for scope)
- Added SamSWAT FOV Increase (Incase you want moar FOV)
- Added AmandsGraphics 1.6.0 (MAKE GAME BEAUTIFUL)
- Added DrakiaXYZ-Quick Move To Container 1.0.2 (Make so that you can Ctrl+Click compatible items into opened container)
- Added Tyfon-UI Fixes 1.3.3 (Various UI fixes for the game, improve QoL)
- Added ThatsLit (make bots have the same vision as players)
- Added Use Items Anywhere (so players can assign hotkey anywhere)
- Added Ram Cleaner Fix (make so the game not eating ram and trash everywhere)
- Added WTT-Pack n' Strap's plugins
- Added WTT-Head Voice Selector's plugins
- Added WTT-The Long Lost Heads of Yojenkz's plugins
- Added BRNVG 1.5.3 plugins

### Bundle Files
- Replace broken files and .bundle files to stop showing unhandle in server logs


## V0.1.2
Date 2024/05/04
### Server Side (user/mods or sometime BeplnEx)
- Added Hephaestus 1.1.5 (preset trader)
- Added No hurry Async Bundle 1.1.0 (helped with client to load bundle packed from server)

## V0.1.1
Date 2024/05/03
### Server Side (user/mods or sometime BeplnEx)
- Added SVM 1.8.1
- Modified SVM config to suit PvE server play style (basically I don't remembered what is change in there lol)
- Added Remove Timegate from Quest 1.0.1

## V0.1.0
Date 2024/05/01
### Server Side (user/mods or sometime BeplnEx)
- Added Fika(MPT) Release 0.9.8875.33465
- Added SPT Realism 1.1.2-SPT-3.8.0-RC2 and modified its configuration
- Added SWAG Donut 3.3.5-SPT380
- Added Looting Bots 1.3.1_2
- Added Questing Bots
- Added SAIN 2.2.1-Hotfix
- Added VCQL 2.0.1 (Quest loader for custom trader quest)
- Added ArtemTrader 1.5.1
- Added Lotus 3.8.0

### Client Side (BeplnEx/plugins)
- Added DrakiaXYZ's BigBrain 0.4.0_3.8.0, TaskListFixes 1.4.0, Waypoints 1.4.3
- Added Bright Laser
- Added Kaeno-TraderScolling
