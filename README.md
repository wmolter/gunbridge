# Doom Bridge

The central premise of DOOMbridge is to provide a quick, round-based experience with the strategy of a trick-taking card-game, but within a first person shooter. Players maintain a set of weapons which are analogous to a “hand” of cards in a trick-taking game. This mechanic provides for new forms of resource management, information hiding strategies, and variance in the round-to-round gameplay of a standard free-for-all deathmatch found in an arena shooter. It also provides a source of asymmetric capability and “underdog” moments within a round or a game.

The game takes place with four individual players managing a hand of 6 cards. The full deck of weapons in the game contains 24 cards, 6 cards of 4 different “suits”. Each suit has two weapons of a similar behavior and power level, with a weak, normal, and strong variation of each of weapon. At the beginning of each game, each player chooses 2 cards in their hand to pass to another player. At the beginning of a round, the winning player of the previous round chooses one of their remaining cards. The three other players must then pick a card in their hand of this “leading” suit, or any card in their hand if they have no card of the leading suit. Once all four players have selected a card, the shooting begins. Each player is teleported into a 4-way symmetric arena, where the final surviving player wins that round, and scores a point. At the end of the six rounds when all cards have been played, the player with the most points is crowned the victor.

## Dependencies

- GZDoom (https://zdoom.org/downloads)
- Doom II: Hell on Earth (need the file doom2.wad)

## Setup

- Find the file gzdoom-<USER>.ini and rename the file, replacing <USER> with the username of the account you are currently logged into on your computer.
- All commands should be run directly from the gunbridge directory.


## Singleplayer Instructions

To run the game on a Mac, run the command "./gzdoom doom2.wad -file shots.wad".  To run the game on windows, run the command "gzdoom.exe doom2.wad -file shots.wad -deathmatch -warp 01".


## Multiplayer Instructions

To play multiplayer, one player must host a game so that others can join.  To do this, see the "Host a Game" section.  Other players may join the game by following the instructions in the "Join a Game" section.


### Host a Game

To host a game on a Mac, run the command: "./gzdoom doom2.wad -file shots.wad -host 4 -deathmatch -extratic -warp 01".  On Windows run the command "gzdoom.exe doom2.wad -file shots.wad -host 4 -deathmatch -extratic -warp 01".  Note that in order for players to join the server wirelessly, one must either forward port 5029 or use a service such as LogMeIn Hamachi.  The game will begin once all four players have joined.  It is also possible to host a server with less than four players by changing the 4 in the previous commands to a 2 or 3.  Hosting a game with more than 4 players will result in undefined behavior.


### Join a Game

To join a game on a Mac, run the command "./gzdoom doom2.wad -file shots.wad -join <IP_ADDRESS>".  To join a game on Windows, run the command "gzdoom.exe doom2.wad -file shots.wad -join <IP_ADDRESS>".
