# lasvegas
simple board game 'las vegas'  in Perl

## text decoration design

Each player is demonstrated by a couple of foreground and background colors.
Especially banker ocuppies purple+black, and retail ocuppies white+black.

Available colors are black, red, green, yellow, blue, purple, cyan and white.

Large dice is underlined comparing to normal dice.

## parameters

### --normal, --large, --banker and --retail

Set the number of dice for each player.
Default 8 normal dice, 1 large dice, 1 banker dice and 2 retail dice.

### --round

Set the number of round.
Default 4 rounds.

### --n-player or --name@, --player%

Set the number of players.
Default 3 anonymous players.

Or give each player's name.

Moreover setup demonstration for each player, otherwise randomly pick up one couple.

### --config-...

Config the game.

#### --config-dice-point

Set the maximum dice point.
Default 6.

#### --config-banknote-max

Set the maximum banknote.
Default 10.

#### --config-banknote-thres

Set the threshold of banknote the casino held.
Default 5.

#### --config-player-name-length

Set the maximum length for player's name to display.
Default 6.
