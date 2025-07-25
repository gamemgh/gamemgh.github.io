+++
title = "Multi Games Hoard Changes"
+++
# Multi Games Hoard Changes
## New in version 0.1.0 (build 2025.07.05)
- Warning. After updating, you might lose your data because of a change in data directory retrieving system. This is system dependent. If your data is somehow unavailable, review the path in the settings so you can make necessary corrections, for example moving the files when needed. This is the last adjustment to the data directory. Android devices can now save the game data!
- Language translation system has been changed. You can now click an icon in the main menu called "Language Manager". Due to this, all languages have been cleared and we apoligize for it. This system is good because it makes updating keys easier than before and you can test your translations without leaving the game. After translating you can send to me as before, but this time, 1 file only.
- Fixed language downloader detecting languages incorrectly. Thanks "Rafael Brito" for the report.
- Added an icon in the main menu to check your current language updates.
- You can now set sound input and output devices in the settings (Android exclusive).
- Improved Settings and other UI dialogs (Android exclusive).
- You can now select menu music or make it random in the settings (Android inclusive). By default, it is set to random.
- In Endless Battle, enemies can now wear shields, therefore it is now more difficult to hit them. Also, some of your large enough weapons – like Rifle, Sniper, Grenade – can be randomized whether they will hit the shield or the body of the enemy directly. Since you already have magical abilities, you currently do not have the ability to wear shields.
- Readable time days, hours, minutes, seconds, and milliseconds can now be translated.
- Added download system in the game. Unfortunately Android has not been tested.

## New in version 0.0.9 (build 2025.04.02)
- Changed the name to Multi Games Hoard to resolve copyright name and DMCA issues. This change does not affect players much though, because the website and general short form of the game's name is left untouched. Note: to get your data back, go to appdata folder, then rename the previous game's name folder to MGH, then put it in a folder called HarryMK. You will need to create that folder, or you can also open the game so it will automatically create for you then you can copy the folder and rename it.
- Added Statistics Menu to display your statistics. Thanks "Lamar" for the suggestion. The number of available Statistics is currently small but will be expanded in the future.
- Added 2 questions when the English language does not exist in the folder. This means that the English folder is not required now, but these questions will be constantly asked every time you run the game. This is a temporary issue to resolve a Mac OS directory checking issue, so it might be taken away in the future, because English should be there to replace the keys that are not translated in your language, either it is outdated or the keys do not exist. There is also an option in the settings to disable this warning, but this option is never translated.
	1. Firstly, before asking questions, it will display an alert box warning you about the cause.
	2. Next, it will ask whether or not to open the download page to download the English language.
	3. Finally, it will ask whether or not to continue anyway.
- Fixed the bug where you do not get more than 4 times your total points worth of currency in Archery mini game, now you will get up to the maximum of 10 times your total points worth of currency  as documented.
- Added a new magic spell called "Trophy Energy" which increases your magic energy faster for seconds. This spell will be able to use in other future magic games as well. How many times faster it will increase your energy as well as how many seconds it will last will be determined by the mini game you play. In Endless Battle, for example, it will increase your magic energy 2 times faster for 20 seconds.
- Language Downloader now includes information of each language's name and its author name if available.
- Changes for Endless Battle mini game; These are changes that have been applied to Endless Battle mini game and thus it is best to group them into 1 for readability:
	- Enemy voices will now randomize depending on how much voices the enemy has. Thanks "Blue Ken Sunshine" for the suggestion!
	- Enemies now possess the capacity for mutual combat; they will attack and eliminate each other if within attack range, but do not actively move towards each other to initiate such engagements. You can exploit this by strategically positioning enemies. For example, by moving around a combat area - to the right, then left, then back again - you can manipulate enemy proximity, causing them to attack each other, thus reducing the overall threat. When you think their health is low enough, for instance, you can shoot them once, avoiding 2 bullets.

## New in version 0.0.8 (build 2025.03.15)
- The game will no longer run if the fallback language (en) cannot be found in the folder.
- Translation languages now require config.toml file be present in the root folder of the language. Copy the config.toml from English language (en) and replace with your own configuration values. See the translations documentation first for more information if you are unsure about it.
- You can no longer set the same language when choosing in the language selection menu.
- Added a menu to download the languages you want! Due to this, only English is added in official game release to prevent increasing size, and go download other languages (if available) if you want to use them. Regardless of what languages you download, you must never delete the English folder or the game will not run as indicated by above change.

## New in version 0.0.7 (build 2025.03.13)
- Added translation system! This is still in its early development, and all strings might not be available to translate. Translations live in the lang folder, with a subfolder with the language code prefix. To translate the program, copy the main fallback translation folder (en) with your own language prefix. After translations you may send to me.
- You can now copy menu items with Control+C, or triple tap with three fingers on Android.
- Introducing a new mini game (Archery)! This is a game where you will shoot a flying plane that is moving from side to side. This game fully supports Android gestures. Read more about the game in the documentation section on the website.
- Removed auto updating because it may cause some devices with slow internet so that they cannot start the game. Updates are now require manual checks.
- Changes for Endless Battle mini game; These are changes that have been applied to Endless Battle mini game and thus it is best to group them into 1 for readability as many changes were made:
	- Removed coordinate checking. You do not need it.
	- Fixed enemy detection to spawn.
	- XP for Bear is slightly increased, and all enemies have increased their health.
	- Introducing a new weapon (Axe)! This weapon is better than Sword as a melee weapon and is available for resurrection 2. This causes the Sword to shorten its range as the Axe takes place on it.
	- Introducing magic attacks! Press the M key, or double tap with one finger on the top right of the screen on Android, to bring up the magic spells which can be casted if you have enough magic energy. The magic energy can be gained as the enemies are killed, and will not reach over 100. Note that availability of magic spells is based on your resurrection, and in some case, level is also included.
	- Some weapons damage has been reduced.
	- Fixed the S key to turn a full 180 degrees.
	- You can now get coin as an item when you kill an enemy.
	- Hitting your target with weapon is now harder as you now need to exactly face in the direction. Better listen, use headphones.

## New in version 0.0.6 (build 2025.01.01)
First of all, **Happy new year!**
- Dice Match can now generate below 1 number, in which case you will lose dollar. This is completely randomized anyway. As such, you can now press faster.
	- Dice Match now has buffer support. Note this is only for non Android users.
- The game will now auto check for updates at startup. You can turn it off in the settings if you want to, but it is recommended to keep it on, as that option can be removed in the future if needed.
- Added a checkbox in the settings to control whether item loop sounds are played. Thanks "Way Yan Soe" for his suggestion!
- Changes for Endless Battle mini game; These are changes that have been applied to Endless Battle mini game and thus it is best to group them into 1 for readability as many changes were made:
	- Enemies can now spawn base on your map and the number of your resurrection. This means that bigger and bigger enemies will you likely to find as your resurrection goes higher. This acts just like a starting point for an expansive map system that will be available in the near future.
	- Introducing a new enemy or animal (Lion)! Watch out! This animal is big, and take a lot of damage than previous enemies, with the approximate estimation that you will be killed is two hits. Don ot worry newbies, you will only find them at resurrection 4 or above. Suggestion? Well, stay away from them, and shoot from a greater distance. They also have a slight higher range than Bears, which is another thing to care of.
	- The game now speaks who kills you as soon as you die.
	- Fixed bullet shoot range.

## New in version 0.0.5 (build 2024.12.08)
- Fixed the download URL for update.
- Changes for Endless Battle mini game; These are changes that have been applied to Endless Battle mini game and thus it is best to group them into 1 for readability as many changes were made:
	- Items in the map will now play a loop sound which will indicate where they are.
	- Added a new weapon (Knife)! This is small and lightweight, doing only a small amount of damage though it is faster than the Sword. You should get this weapon when your resurrection is 1 or above. Now, the Sword range is increased while the Knife has a shorter range.
	- Added a new enemy (Bear!) Be careful, it does a little higher amount of damage than Wolf.
	- Require experience point will now randomize.
	- You can now customize the spawn time of enemy and it is set to 10 seconds by default.
- Added buffer! This means that you can review informations that you have missed. For example, alerts and in-game important notifications. You can press left and right brackets to switch between buffers (holding down Shift will move to top or bottom), and you can press the Comma key or Period key to move through the current buffer (holding down Shift will move to top or bottom). Android gestures not supported.
- Introducing a new mini-game: Dice Match! The objective is to roll the dice, which contain two numbers, each ranging from 1 to 6. If the two numbers match, you will earn money equal to 0 to 20 times their total. There you go, Android gamers, because this mini game fully supports gestures and thus keyboard is not required!

## New in version 0.0.4 (build 2024.11.17)
Please note that the Android version still cannot save data.
- This update Fixes a serious bug that the store item health drink is being incorrect. It is now changed to health potion, which is making wrong item. All health drinks that you have purchased will be transfered to health potion automatically. Thanks "Jes Bel" for report!
- Computer sequence in Blackjack will now more randomize and does not nearly always win or lose.
- Changes for Endless Battle mini game; These are changes that have been applied to Endless Battle mini game and thus it is best to group them into 1 for readability as many changes were made:
	- You can now select the map you want to play on. Of course, there is currently 1 map, but it will be expanded in the future.
	- Added items! Now, when an enemy dies, a random item will be spawned at its location which will be picked up if you are close enough with it.
	- Fixed inventory item speech on Android which causes the item to stop speaking. The positional speak of the inventory item has now been removed.
	- You can now rotate a full 180 degrees by pressing the S key. Android gesture not available.
- Improved in-game shortcuts announcement. At the start of Blackjack it will tell the shortcuts related to it depending on the platform you are on.
- Added test speaker in the main menu to test your speaker's position in realtime.
- Added the message that will speak upon the click of the "Check for Updates" icon.

## New in version 0.0.3 (build 2024.10.29)
- Changed the name to Mini Games Hub, and added a new mini game! Of course, new mini game suggestions are always welcome!
	- In this new mini game, you play blackjack. You can move up and down arrows to navigate through the game's structure. When you gained dollars, you can use them to buy health items, ammos, etc for Endless Battle mini game.
- Changes for Android; These are changes that have been applied to Android operating system as well as game UI related to it:
	- Upon opening the game on Android, it will play a sound file which suggests to turn off your screen reader and using a keyboard if possible. To skip the sound you can double tap with 1 finger on the screen.
	- Android platform can now select gender as the play game option is pressed.
	- You can now change settings on Android! Since forms are not able to navigate on Android, a menu base system is added to it. Also note, to check or uncheck a checkbox in the menu, double tap with 2 fingers.
	- More Android gestures for Endless Battle: Swipe up with 3 fingers to check ammo, and swipe down with 3 fingers to check coordinates. Wo, near to 4 fingers!
	- Hopefully fixed screen reading problem on some Android devices by using an alternative screen reading method. Thanks several players for report!
	- Added Android number field. Uh, of course, this is simulation. Once the field is popped out you can click on the numbers you want to type, and click done button to finish. This is the only way that Android devices can type.
- Updates will now include about update build date. Eg build 2024.10.19.
- Added sounds for update available, started, and canceled.

## New in version 0.0.2 (build 2024.10.19)
- You can now press F1 on each store item to get its description.
- Fixed speech interrupting in menus, especially with Android having speech interrupt on. On Android if you want to force speech stop while you are in game play, triple tap with 1 finger.
- Fixed enemy death sound not playing in the correct listener.
- You can now click on "get system information" icon in the main menu to get information related to system, including its information and necessary debug logs. Only do this when it is necessary, for example if you asked a question related to device issue, so developer might need to ask you that information; only provide it when it is asked! The information you retrieved is encrypted, meaning only developers can extract its information, adding another possible security implementations to each information that you provide. This also means that even if the information is published publicly to the internet, no one will be able to access its original form.
- Decreased jump time a bit.
- Improved store related text strings.
- Information of the weapons have been removed from the weapon draw menu. Instead, you will have to press F1 to read the weapon's related information while you are at it.
- You can now rotate 90 degrees by pressing turn keys (Q and E) while holding down Shift. This 90 degrees rotation is not currently available by touch.
- In-game key shortcuts can now display base on the operating system!
- Added pluralization strings to items, for instance, store purchases.

## New in version 0.0.1 (build 2024.10.13)
- First release