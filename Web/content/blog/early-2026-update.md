+++
date = "2026-01-01T07:00:00+06:30"
title = "Early 2026 Update"
+++
Welcome to the year 2026!
<!--more-->

## Introduction
Hello everyone! Happy new year! This post will cover changes that have been made into the game to mark the first and early release of version 0.1.4 of 2026, which will be the version with a lot of changes.

Changes were made to UI designs, system changes, and new features in both per-minigame and global game itself (the MGH) and a big list of changes have also been implemented to RFC, which is now the minigame that becomes popular among players.

Thank you everybody for suggestions and bug reports; Without each and everyone else's suggestions and bug reports it would have been impossible for the game to even exist in the first place. In addition, thank goes out to voice actors contributed into RFC minigame, you are part of the process that made the RFC popular.

## Changes for "Run for Your CHOCOLATES" (RFC)
### New Voices
RFC received 2 new voices, "Aleesya" and "James Nelson"; Thanks for the contributions. More voices mean more chocolate makers spawned on the map, so be prepared to avoid them, or in the worse case scenario, to fire them with your fireballs.

For a reminder, if you want to add a voice to the game, simply record, zip, send, and your voice is live in the next version. More information is also available in the [RFC's documentation]({{% relref "/docs/rfc/_index.md" %}}) section.

In addition, you can now disable the voices that you don't want to be used and/or listened. Simply use the "Game Specific Settings" icon in the main menu, and select RFC in the list. Unfortunately, on Android, a keyboard's intervention will be needed.

### Movement and Map
The game is also now a little faster to move around. Could this be a more easy way to avoid the chocolate makers and/or to smash them running with fireballs? Well, this is the player's choice after all.

The map's maximum size has also been increased to 100. This puts the space between 1 chocolate and another, and thus may require more steps to walk up, reach the target, and pick up. This change is also made so that more chocolate makers can spawn.

### Chocolates and Chocolate Makers
You will no longer get chocolates directly in your inventory when you kill a chocolate maker. Instead, it will be spawned at the location where the chocolate maker is killed. This means that another chocolate maker nearby (if within their range) sees it, it might pick the chocolates up into their inventory. In this case, use your fireballs, and you will get the chocolates they took from other chocolate makers or from the ground, and also the chocolates they initially have in their inventory when they are spawned.

Next, each and every one of the chocolates now has its own weight.
- The weight will be displayed in the format set in the global settings. Grams / Kilograms (Metric), and Pounds (Imperial).
- Metric unit is used by default just as the case of the global standard.

### Intelligent Chocolate Makers, Are They?
Yes, it's correct. Chocolate makers now move more dynamically, using engine's pathfinder abilities. Please report any bug related to pathfinding if you happened to come across.
- They will still actively target you, but in rare cases it can change, see below.
- If they see chocolates on the ground (within 10 meters, about 32 feet), they will shift their target and move to pick them up. At that time, they will no longer target you, until they have picked up the chocolates which will shift their target back to you.

### Automatic Mode, Really?
Yes, you've heard right! You can use automatic mode. Well, not everything is controlled of course, but it controls most. To use it, press `Alt+A` to bring up the actions menu. Each use of the automatic mode costs 1 million dollars. Oh, on Android, swipe down with 2 fingers.
- It controls your movement. Due to this, you will no longer be able to move yourself in this mode.
- It goes and pick up nearest chocolates. This uses the pathfinder again to determine the path.
- It tries to avoid chocolate makers from colliding. However, this is not always possible. At one point or another, the automatic computer may late noticing, and could eventually crash into one of them.
- It goes and pick up fireballs, if within the range of 30 meters, about 98 feet.
- Throwing fireballs will need to be done manually.

## Changes for Endless Battle
- Added a new map called "Lion Forest", and is available for players with greater or above resurrection 4.
- Similar to chocolate makers in RFC, enemies in Endless Battle now move using pathfinder.

## Global Changes
### UI Related
#### New Modern Menu and Form Systems
We now have new modern menu and form systems. Menu and form systems are made with the ability to easily maintain. The Games Menu now uses this new modern menu system. The menu system is combined with the new modern form system to maximize the abilities on Android on form based dialogs like `Ctrl+F` and `Ctrl+G`, even though keyboard's intervention will still be needed. This modern form system allows Android players using a keyboard to have the ability to type.

In this new form system, a possibility of keyboard typing sound implementation exists, and is thus added for auditory.

#### Force PC Settings on Android.
Android players who use a keyboard have now a new option in the main menu to open settings that allows you to force using form UI controls rather than menu so that you have maximum possible configuration options. Be warned that using that option without having a keyboard actually connected will set you in a position where you will not be able to exit the dialog. In this case, force closing the application may be needed.

#### Per-Game Settings
You can now configure settings for per-game specific. The spawn time and the item loop sound have also been moved to the new Endless Battle settings dialog. Simply use the "Game Specific Settings" icon in the main menu.

### General
#### Automatic Update Extraction Layer on Windows
Updates can now automatically extract the zip file. This means that the manual extraction will no longer be needed. This is only possible on Windows.

#### Statistics Menu
The statistics menu has been redesigned. It now supports viewing per-game statistics, as well as copying per-game and/or full statistics across all games.

The way of serializing the statistics has also been redesigned. Due to this change, all statistics have been automatically cleared.

#### The In-Game Downloader System
The in-game downloader system has been redesigned using new modern UI form system. Please note that support for Android version is still limited, and thus you will need to use a keyboard to browse through the downloader informational fields.
- Keys such as Spacebar, 1, 2, 3, etc, are no longer supported.
- Use the UI form keys to navigate through the informational fields, such as `Tab` and `Shift+Tab`.
- The progress bar now feels more realistic, as it is part of the UI form system.

#### Unit System
The display of distance has been redesigned. It now uses 2 main units, Metric and Imperial.
- Metric (global unit - default) is used.
- Imperial unit is also supported.
- You can configure it in the global settings dialog.

The difference in units is as follows:

| Metric | Imperial |
|---|---|
| Meter (m) | Feet (ft) |
| Kilometers (km) | Miles (mi) |
| Grams (g) | Pounds (lb) |
| Kilograms (kg) | Pounds (lb) |

## Conclusion
Well, that's it guys. Please note that you should check the [change log]({{% relref "/changelog.md" %}}) to view the full changes made.

Lastly, don't forget to read the [documentation]({{% relref "/docs/_index.md" %}}) for a list of shortcuts.

**Happy gaming!**
