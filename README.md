# Doom Bridge

## Dependencies

- ZDoom
- Doom II: Hell on Earth

## Setup

- Find the file gzdoom-<USER>.ini and rename the file, replacing <USER> with the username of the account you are currently logged into on your computer.
- All commands should be run directly from the gunbridge directory.


## Singleplayer Instructions

To run the game on a Mac, run the command "./gzdoom doom2.wad -file shots.wad".  To run the game on windows, run the command "gzdoom.exe doom2.wad -file shots.wad".


## Multiplayer Instructions

To play multiplayer, one player must host a game so that others can join.  To do this, see the "Host a Game" section.  Other players may join the game by following the instructions in the "Join a Game" section.


### Host a Game

To host a game on a Mac, run the command: "./gzdoom doom2.wad -file shots.wad -host 4 -deathmatch -extratic".  On Windows run the command "gzdoom.exe doom2.wad -file shots.wad -host 4 -deathmatch -extratic".  Note that in order for players to join the server wirelessly, one must either forward port 5029 or use a service such as LogMeIn Hamachi.  The game will begin once all four players have joined.  It is also possible to host a server with less than four players by changing the 4 in the previous commands to a 2 or 3.  Hosting a game with more than 4 players will result in undefined behavior.


### Join a Game

To join a game on a Mac, run the command "./gzdoom doom2.wad -file shots.wad -join <IP_ADDRESS>".  To join a game on Windows, run the command "gzdoom.exe doom2.wad -file shots.wad -join <IP_ADDRESS>".
