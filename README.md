# Konane
Konane game in Python using Minimax algorithm.

### Requirements
- Python 3
- Terminal shell

### Usage
Run `run-konana.<bat OR sh>` and view the results of each game.
The simple player will always choose the first valid move it finds and the 
'Toast Player' will use a minimax algorithm.

### Modifications
If you want the games to be verbose change the last line from
`game.playNGames(10, MinimaxPlayer(8, 2), SimplePlayer(8), 0)`
to
`game.playNGames(10, MinimaxPlayer(8, 2), SimplePlayer(8), 1)`
