# TicTacToe_Game
Tic Tac Toe game created to the STM32Nucleo-64. The Lcd screen and the buttons were simulated in the Client App.

It's only playable in a player vs player mode. The map size is 3x3. 
The software uses a 3x3 Matrix to track the moves of the player. 
As i said before, the screen is simulated, but the states of the screen pixels are coded in the MicroController side.(Drawing.c: U can see detaled information there)
I used UART communication to establish the connection between the microcontroller and the client App.

My final goal with the Project is to make the map size costumable. (nxn)
