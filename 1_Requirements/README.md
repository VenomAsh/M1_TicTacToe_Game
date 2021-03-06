# Description
Tic-tac-toe is fun,tactic game played on a three-by-three grid by two players, who alternately place the marks X and O in one of the nine spaces in the grid. The objective of Tic Tac Toe is to get three in a row. You play on a three by three game board. The first player is known as X and the second is O. Players alternate placing Xs and Os on the game board until either opponent has three in a row or all nine squares are filled. X always goes first, and in the event that no one has three in a row, the stalemate is called a cat game. We can choose any symbol, as there is not restriction in that & any player can go first.

# Requirements
## High Level Requirements</br>

|ID|Description|
|:---|:---|
|HR01|Player1 shall be able to choose 'X' to play.|
|HR02|Player2 shall be able to choose 'O' to play.|
|HR03|Player shall be able to Exit the game.|
|HR04|Player1 shall win/lose.|
|HR05|Player2 shall win/lose.|
|HR06|Game shall end up in a Draw.|

## Low Level Requirements
|ID|Description|HLR ID|
|:---|:---|:---|
|LR01|If the user presses '1', he'll be play with 'X'.|HR01|
|LR02|If the user is playing with 'X', he'll get the first turn.|HR01|
|LR03|If the user presses '2', he'll be play with 'O'.|HR02|
|LR04|If the user is playing with 'O', he'll get the second turn.|HR02|
|LR05|If the user presses '3', it'll exit the game.|HR03|
|LR06|If the player1 gets 3 Xs or 3 Os in vertical,horizontal or diagonal row, User will lose.|HR04|
|LR07|If the player2 gets 3 Xs or 3 Os(as per his choice), in vertical,horizontal or diagonal row, he'll win.|HR05|
|LR08|If the total number of moves, i.e., 9 moves have been completed and player1 nor player2 has won, it'll end up in a draw.|HR06|

# SWOT Analysis:

<img width="563" alt="SWOT" src="https://user-images.githubusercontent.com/98833151/153712194-4c443cc9-2a43-4ec2-8b0d-8e2815cbc976.png">


## 4W's & 1H
### Who
:point_right: Anyone who wants to play the game.

### What
:point_right: This game is for fun purpose.

### When
:point_right: Anytime when user wants to play.

### Where
:point_right: Can be played anywhere.

### How
:point_right: By implementing the code using C-program.
