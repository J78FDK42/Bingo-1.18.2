# Changelog
===============

All notable changes to this project will be documented in this file.


## [Unreleased] - TBD

### Added 
+ Official release file for Minecraft version 1.18.2 

## [0.2.0] - 2026-06-15 : Beta v2 Update!

### Added
+ Game Mode Tab to Bingo Game Screen
+ Unlocks Tab to Bingo Game Screen
+ Bingo language translations

##### Core Game Files 
+ Bingo client/server save files

##### Collectibles Datapacks
+ Custom collectibles easy peaceful datapack
+ Custom collectibles easy survival datapack
+ Custom collectibles medium peaceful datapack
+ Custom collectibles medium survival datapack
+ Custom collectibles hard survival datapack

Download Peaceful Easy Datapack: [collectibles_peaceful_easy_datapack.zip](https://github.com/J78FDK42/Bingo/blob/Bingo-0.2.0/collectibles_peaceful_easy_datapack.zip)
Download Survival Easy Datapack: [collectibles_survival_easy_datapack.zip](https://github.com/J78FDK42/Bingo/blob/Bingo-0.2.0/collectibles_survival_easy_datapack.zip)
Download Peaceful Medium Datapack: [collectibles_peaceful_medium_datapack.zip](https://github.com/J78FDK42/Bingo/blob/Bingo-0.2.0/collectibles_peaceful_medium_datapack.zip)
Download Survival Medium Datapack: [collectibles_survival_medium_datapack.zip](https://github.com/J78FDK42/Bingo/blob/Bingo-0.2.0/collectibles_survival_medium_datapack.zip)
Download Survival Hard Datapack: [collectibles_survival_hard_datapack.zip](https://github.com/J78FDK42/Bingo/blob/Bingo-0.2.0/collectibles_survival_hard_datapack.zip)

##### Game Loot Tables
+ Loot table files:
	* data/bingo/loot_tables/square.json
	* data/bingo/loot_tables/winner.json

Download Loot Tables: [BingoLoot.zip](https://github.com/J78FDK42/Bingo/blob/Bingo-0.2.0/BingoLoot.zip)

##### Language Translation Specification
+ Bingo English version language file
+ Bingo French version language file

Download Language Specification: [en_us.json](https://github.com/J78FDK42/Bingo/blob/Bingo-0.2.0/en_us.json)
 
#### Game Mode Tab
+ Bingo button (standard bingo)
+ Blackout button (all squares)
+ Twenty button (20 squares or best, no bingo)

#### Unlocks Tab

+ Advancements
+ Recipes

#### Advancements Tab
+ Vanilla checkbox - include/exclude vanilla advancements (all advancements with id of "minecraft")
+ Modded checkbox - include/exclude modded advancements (all advancements without id of "minecraft")
+ Custom checkbox - include/exclude custom advancements (all advancements with id provided by user)

#### Recipes Tab
+ Vanilla checkbox - include/exclude vanilla recipes (all recipes with id of "minecraft")
+ Modded checkbox - include/exclude modded recipes (all recipes without id of "minecraft")
+ Custom checkbox - include/exclude custom recipes (all recipes with id provided by user)

### Changed

#### Join Tab 
+ Changed to optional Teams Tab
+ All players in the session are in the game by default

#### Cards Tab 
+ Personal toggle button
+ Team toggle button
+ Global toggle button

#### Progress Tab 
+ Personal toggle button
+ Team toggle button
+ Global toggle button

#### Files
+ Bingo game files
+ Bingo networking files
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


[0.2.0]: https://github.com/J78FDK42/Bingo-1.18.2/blob/Version-0.2.0/bingo-0.2.0-forge-1.18.2.jar
[1.18.2-1.0.0b]: https://www.curseforge.com/minecraft/mc-mods/advancement-bingo-game/files/5375516/changelog
