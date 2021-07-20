# Slots Framework

General framework for a slot game.

**Possible Features**
* Increased bets allow for more "match" options/directions
* Version where multiple copies of the same `GamePiece` explode to reveal even more `GamePieces`

## Game Board
We could have a fair and an unfair mode. Fair mode would generate the "wheels" of options and then spin each wheel
to mimic an old fashion slot machine. The unfair mode could randomly generate gameboard each time.

## Architecture

Entities
  GamePiece
  Board

GameMaster
  Coordinates everything and stores the players session
  Requires payment from the player before starting
  Gets a new board if it doesn't exist


BoardGenerator
  Accepts possible game pieces and generates the board
  Board has a number of rows and columns

PieceMatcher
  Takes the board and finds matches

## Questions
* ???
