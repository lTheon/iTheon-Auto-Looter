# iTheon-Auto-Looter - v0.1.14

![Auto looter by Blackgrowl](https://user-images.githubusercontent.com/35302307/216791072-fa553c9d-d205-4480-a506-b833aee55ed1.jpg)

Mod for Stalker Anomaly that adds the fully configurable (MCM config) auto-looting feature. Also allows you for remote looting (without opening a container).
It has a semi-hard requirement - https://github.com/lTheon/iTheon-Pick-Best-Disassembly-Tool . Technicaly you can play without this dependency, but you might experience some CTDs on disassembling large amount of items at once (just XRay stuff). This mod can be replaced with any other mod that prevents the full depletion of disassembly tools

Tested in both GAMMA and vanilla Anomaly. To get all you can out of it, you'll need two other mods: <br>
https://github.com/ahuyn/anomaly-wpo <br>
https://www.moddb.com/mods/stalker-anomaly/addons/crafting-info-in-tooltips <br>
Or simply play GAMMA :)

Disassemble animations should be turned off to not cause CTDs/busy hands <br>
Things you can configure - disassembling items (different options per item type), stripping weapon parts and attachments, looting stuff, remote looting range, deleting items (get rid of piles of dead bodies).

Given a large amount of possible combinations, I'm pretty sure it's almost impossible for me to test everything myself, though a big chunk of time was spent on that anyway. That's why the initial version is set to **v0.1**, as there might be some minor bugs to fix that I did not catch.

Contributors: 

Russian translation: https://github.com/IIJTypmaH <br>
Cool image you can see above and the MCM banner: Blackgrowl

Changelog:

v0.1.14
- Add config for mags looting

v0.1.13
- Fix recipe material detection for armors

v0.1.12
- Delay item deletion so looting processes properly

v0.1.11
- Fix mag ejection for mags users

v0.1.10
- Add delete feature

v0.1.9a
- Bring back no disassembly tool message configuration (lost during reverting some stuff)

v0.1.9
- Fix looter stutters/infinite loop on empty dead bodies

v0.1.8
- Added stalker-dropped PDAs to disassembling config list - defaults set to false
- Normalized misc items list rendering - now it's sorted by item's section (internal identifier)

v0.1.7
- Add failsafe for stripping all parts.

v0.1.6
- Experimental: Add proximity looting

v0.1.5
- Added a cool MCM banner by Blackgrowl

v0.1.4
- Removed some of hard dependencies

v0.1.3
- Add context menu option for disabling/enabling auto-disassembling for misc items
- Make message on no valid tool configurable

v0.1.2
- Disable looter on player inventory screen (unexpected bug)
- Make collector function iterate over actor inventory instead of ruck
- Add failsafe for collect parts function (should be unnecessary after the fix above, but just in case)

v0.1.1
- Changed defaults - disassembling is now turned off by default for weapons, armors and ammo; remote looting disabled by default.
- Added more descriptions to MCM menu. Explained why remote looting can cause problems.
- Added 3 more misc item disassemble options: Guitar (true), Compression bag (true), Sleeping bag (false)
