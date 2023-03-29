# Tic-Tac-Toe-with-Minimax-Algorithm

This is a Python implementation of the classic game Tic Tac Toe with an AI player using the Minimax algorithm.

The program starts by initializing the game board, which is a 3x3 matrix, with empty cells represented by the constant EMPTY. Players are represented by the constants X and O. The game board is implemented as a Board class that keeps track of the current player, winner, available moves, and game over state.

The Minimax algorithm is implemented as two functions max_value and min_value, which recursively evaluate the game state to determine the best move for the current player. The result function is used to simulate a move on a copy of the current game state, and the get_utility function is used to evaluate the utility of the game state for the current player.

The play_game function runs the game loop, where players take turns making moves until the game is over. At each turn, the current player is asked to enter their move. If the player is X, the program uses the get_best_move function to determine the best move based on the Minimax algorithm. If the player is O, the program uses a random move. After each turn, the game board is printed to the console. Once the game is over, the winner is announced, or a tie is declared.

In the updated version, the game now includes a score system and allows the user to choose whether to continue playing or exit the game after each round. The play_game function has been modified to keep track of the score and prompt the user to continue playing or exit after the game is over.

To run the program, simply run the main function. The program requires Python 3 to run.

Enjoy playing Tic Tac Toe with an AI player using the Minimax algorithm!
