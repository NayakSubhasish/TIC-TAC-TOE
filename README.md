# TIC-TAC-TOE
Summary

This Java program implements a simple Tic Tac Toe game with the following features:

    Initialization:
        A 3x3 board is initialized with '-' representing empty spaces.
        The first player is set to 'X'.

    Game Loop:
        The game continues until the board is full or a player wins.
        Players take turns to enter their move. The program ensures the move is valid (within bounds and to an empty spot).
        After each move, the program checks if the current player has won.

    Win Conditions:
        The game checks for a win in rows, columns, and both diagonals.

    Changing Players:
        The current player alternates between 'X' and 'O'.

    Game End:
        If a player wins, the game announces the winner.
        If the board is full without any player winning, the game ends in a draw.

This code provides a straightforward implementation of the classic Tic Tac Toe game, playable in a console environment.
