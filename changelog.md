Changelog
===============

All notable changes to this project will be documented in this file.


## [Unreleased] - TBD

### Added 

+ Official release file for Minecraft version 1.18.2


[1.18.2-1.0.0b] - 2024-05-20*

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

- Key Bindings
+ View Bingo card key `'o'`
+ View Start and Config key `'b'`

#### Minecraft item

`bingo:bingo_card`
+ right click / view card

### Minecraft Commands

+ `bingo start` starts the game
+ `bingo reset` cancels any game in progress
+ `bingo restart` restarts the game
+ `bingo add -player-` adds the player to the list of active players
+ `bingo start` starts the game for all active players
+ `bingo reset` renamed to `bingo stop` to cancel a game in progress
+ `bingo add all` adds all players in the session to the list of active players
+ `bingo start all` starts the game for all players in the session
+ `bingo players` lists all active players in the session
+ `bingo add -player- red|blue` adds the player to the list of active team players
+ `bingo join` adds the player to the list of active players
+ `bingo join red|blue` adds the player to the list of active team players
+ `bingo quit` cancels the player's game in progress


[1.18.2-1.0.0b]: https://github.com/J78FDK42/Bingo/raw/1.18.2-1.0b/bingo-1.18.2-1.0.0b.jar
