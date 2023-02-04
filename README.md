# iTheon-Auto-Looter - v0.1.2
Mod for Stalker Anomaly that adds the fully configurable (MCM config) auto-looting feature. Also allows you for remote looting (without opening a container).
For now it has two hard requirements:
1. https://github.com/lTheon/iTheon-Pick-Best-Disassembly-Tool
2. https://www.moddb.com/mods/stalker-anomaly/addons/weapon-parts-overhaul

It was tested only in Stalker GAMMA environment, so I don't give you any guarantee that it will work in vanilla Anomaly

Things you can configure - disassembling items (different options per item type), stripping weapon parts and attachments, looting stuff, remote looting range.

Given a large amount of possible combinations, I'm pretty sure it's almost impossible for me to test everything myself, though a big chunk of time was spent on that anyway. That's why the initial version is set to **v0.1**, as there might be some minor bugs to fix that I did not catch.

Contributors: 

Russian translation: https://github.com/IIJTypmaH

Changelog:

v0.1.1
- Changed defaults - disassembling is now turned off by default for weapons, armors and ammo; remote looting disabled by default.
- Added more descriptions to MCM menu. Explained why remote looting can cause problems.
- Added 3 more misc item disassemble options: Guitar (true), Compression bag (true), Sleeping bag (false)

v0.1.2
- Disable looter on player inventory screen (unexpected bug)
- Make collector function iterate over actor inventory instead of ruck
- Add failsafe for collect parts function (should be unnecessary after the fix above, but just in case)
