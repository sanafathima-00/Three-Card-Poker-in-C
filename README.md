# Three-Card-Poker-in-C
<br>
The "Create Card" function dynamically creates a new `Card` structure, initializes its members with the provided rank and suit, and returns a pointer to the newly created `Card`.
<br>
The "Create Player" function dynamically creates a new `Player` structure, initializes its members with the provided player name and default values for other attributes, and returns a pointer to the newly created `Player`.
<br>
The "Display Card" function iterates through the cards in a player's hand, printing each card's rank and suit, and the function is responsible for displaying the player's hand.
<br>
The "Decide Winner" function iterates through a linked list of players, comparing the ranks of the cards in their hands to determine the winner, and returns a pointer to the winning player.
<br>
The "Play Game" function sets up and runs a card game for a specified number of players. It creates players, generates random cards for each player, displays each player's hand, determines the winner, and then frees the memory allocated for players and cards.
<br>
The "Main" function prompts the user to input the number of players for a game, validates the input, initializes the random number generator, and then starts the game by calling the `playGame` function with the number of players provided. Finally, it returns 0 to indicate successful execution of the program.
