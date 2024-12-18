# World of Warcraft - Addons - Vanilla (1.12.1 compatible or lower)

## [Browse Addons by Category](https://github.com/fondlez/wow-addons-vanilla/wiki#browse-by-category)

## [Browse Addons by Name](https://github.com/fondlez/wow-addons-vanilla/wiki#browse-by-name) 
## [a](https://github.com/fondlez/wow-addons-vanilla/wiki#A) | [b](https://github.com/fondlez/wow-addons-vanilla/wiki#B) | [c](https://github.com/fondlez/wow-addons-vanilla/wiki#C) | [d](https://github.com/fondlez/wow-addons-vanilla/wiki#D) | [e](https://github.com/fondlez/wow-addons-vanilla/wiki#E) | [f](https://github.com/fondlez/wow-addons-vanilla/wiki#F) | [g](https://github.com/fondlez/wow-addons-vanilla/wiki#G) | [h](https://github.com/fondlez/wow-addons-vanilla/wiki#H) | [i](https://github.com/fondlez/wow-addons-vanilla/wiki#I) | [j](https://github.com/fondlez/wow-addons-vanilla/wiki#J) | [k](https://github.com/fondlez/wow-addons-vanilla/wiki#K) | [l](https://github.com/fondlez/wow-addons-vanilla/wiki#L) | [m](https://github.com/fondlez/wow-addons-vanilla/wiki#M) | [n](https://github.com/fondlez/wow-addons-vanilla/wiki#N) | [o](https://github.com/fondlez/wow-addons-vanilla/wiki#O) | [p](https://github.com/fondlez/wow-addons-vanilla/wiki#P) | [q](https://github.com/fondlez/wow-addons-vanilla/wiki#Q) | [r](https://github.com/fondlez/wow-addons-vanilla/wiki#R) | [s](https://github.com/fondlez/wow-addons-vanilla/wiki#S) | [t](https://github.com/fondlez/wow-addons-vanilla/wiki#T) | [u](https://github.com/fondlez/wow-addons-vanilla/wiki#U) | [v](https://github.com/fondlez/wow-addons-vanilla/wiki#V) | [w](https://github.com/fondlez/wow-addons-vanilla/wiki#W) | [x](https://github.com/fondlez/wow-addons-vanilla/wiki#X) | [y](https://github.com/fondlez/wow-addons-vanilla/wiki#Y) | [z](https://github.com/fondlez/wow-addons-vanilla/wiki#Z)

### Other repositories:
* pfQuest addon and many other great addons from Shagu - https://shagu.org/

### Other addon lists:
* [Frostshock's Vanilla WoW Addons By Category (WABC)](https://frostshock.github.io/wabc/) - an older list, but still useful to this day
* [Turtle WoW Addons Wiki](https://turtle-wow.fandom.com/wiki/Addons) - this large, frequently updated community list supports a custom vanilla server, but many addons could still work on normal vanilla servers. Turtle WoW also uniquely has a significant third-party mod scene.

### Other resources:
* [Crazypoultry WoW 1.12.1 Addons Collection](https://github.com/crazypoultry/Wow1.12.1_Addons_Collection) - one of the largest and oldest addon collections, dating back to the days of the Nostalrius server
* [Meridaw Vanilla Macros collection](https://github.com/Meridaw/Vanilla-Macros) - special mention for Meridaw's great selection of many pure vanilla macros. In vanilla, macros and addons can have significant crossover because macro commands are so few and much of the WoW API is still accessible via the same Lua language to both addons and macros

## How to install a WoW addon ##

1. If you never launched WoW, double click WoW.exe or otherwise launch WoW.
2. Log in with one of your characters.
3. After login, exit the game completely. In future, to add new addons you will still need to exit the game to see them.
4. Download the addon that you want.
5. Extract it into the WoW `Interface\AddOns` folder, e.g. C:\GAMES\World of Warcraft\Interface\AddOns
6. Double click WoW.exe or otherwise launch WoW.
7. At the Character Select screen, look in the lower left corner for the "AddOns" button.
8. If button is there, click it and make sure all the addons you installed are listed and make sure "Load out of date AddOns" is checked.
9. If the button is NOT there, this means you did not install any addons properly.

Common issue: if you downloaded your addon from a Github site, then you may need to rename the extracted folder and remove "-master" from it.

## Have you installed an addon and it is not showing up in WoW? ##

**Rule 1:** Make sure that in each folder immediately below `Interface\AddOns`, there is a `.toc` file in it. This is the addon folder.  
**Rule 2:** Make sure that this addon folder matches the name of the `.toc` file.

<ins>Example</ins>
* GOOD :white_check_mark: : `Interface\AddOns\LunaUnitFrames\LunaUnitFrames.toc`
* BAD :x: : `Interface\AddOns\LunaUnitFrames-master\LunaUnitFrames\LunaUnitFrames.toc`
