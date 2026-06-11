# Changelog
===============

All notable changes to this project will be documented in this file.


## [Unreleased] - TBD

### Added 

+ Official release file for Minecraft version 1.18.2 

## [0.2.0] - 2026-06-15 : Beta v2 Update!

### Added

+ Game Mode Tab to Bingo Game Screen
+ Bingo command translations

#### Files

+ Bingo client/server save files
+ Bingo French version language file

+ Fabric version 1.18.2

Download Language Specification: [en_us.json](https://github.com/J78FDK42/Bingo-1.18.2/blob/Version-0.2.0/en_us.json)
 
#### Game Mode Tab

+ Game mode Bingo (standard bingo)
+ Game mode Blackout (all squares)
+ Game mode Twenty (20 squares, no bingo)

#### Unlocks Tab

+ Advancements
+ Recipes

#### Advancements Tab

+ Vanilla
+ Modded
+ Custom

#### Recipes Tab

+ Vanilla
+ Modded
+ Custom

### Changed

+ Forward compatible version name/number with Gradle

#### Join Tab

+ Changed to Teams Tab

#### Cards Tab 

+ Toggle button Personal
+ Toggle button Team
+ Toggle button Global

#### Progress Tab 

+ Toggle button Personal
+ Toggle button Team
+ Toggle button Global

#### Files

+ Bingo game files
+ Bingo networking files
+ Bingo key binding files
+ Bingo save files

### Removed

+ Bingo config files 
+ Bingo player capabilities save file

### Fixed

+ Player saved data lost on player death
+ Advancement progress saved after being cleared
+ Team progress updates correctly
+ Global progress updates correctly
+ Team cards issued correctly
+ Global cards issued correctly
+ Translatable text issues


## [1.18.2-1.0.0b] - 2024-05-27

### Added

#### Files

+ Bingo game files
+ Bingo networking files
+ Bingo config files
	* Include recipe advancements in the game
	* Include vanilla advancements in the game
	* Include custom advancements in the game
	* All players use the same bingo card in the game
	* Any player advancement is marked completed for all players in the game
	* Team players use the same bingo card in the game
	* Team player advancement is marked completed for all players on the team
	* Generate player loot on square completed and game winners
+ Custom collectibles easy datapack
+ Custom collectibles medium datapack
+ Custom collectibles hard datapack
+ Loot table files:
	* data/bingo/loot_tables/square.json
	* data/bingo/loot_tables/winner.json

#### Minecraft GUI

+ Bingo Card screen
+ Bingo Winners screen
+ Bingo Start screen

#### Key Bindings
+ View Bingo card key `'o'`
+ View Start and Config key `'b'`

#### Minecraft item

`bingo:bingo_card`
+ right click / view card

#### Minecraft Commands

+ `bingo start` starts the game
+ `bingo stop` cancels any game in progress
+ `bingo reset` same as `bingo stop` to cancel a game in progress
+ `bingo add -player-` adds the player to the list of active players
+ `bingo start` starts the game for all active players
+ `bingo add all` adds all players in the session to the list of active players
+ `bingo start all` starts the game for all players in the session
+ `bingo players` lists all active players in the session
+ `bingo add -player- red|blue` adds the player to the list of active team players
+ `bingo join` adds the player to the list of active players
+ `bingo join red|blue` adds the player to the list of active team players
+ `bingo quit` cancels the player's game in progress
+ `bingo kick -player-` removes a player from the game (requires op privileges)
+ `bingo loot` toggles game loot generation on or off


[0.2.0]: https://www.curseforge.com/minecraft/mc-mods/advancement-bingo-game/files/5375516/changelog
[1.18.2-1.0.0b]: https://www.curseforge.com/minecraft/mc-mods/advancement-bingo-game/files/5375516/changelog
