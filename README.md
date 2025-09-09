Features:
Custom Range: Player chooses the starting and ending numbers for the game.
Interactive Input: Prompts the player for their name and guesses.
Limited Attempts: The player has a maximum of 10 guesses to find the secret number.
Exit Option: The player can type 0 at any time to exit the game.
Winner Announcement: If the player guesses the number correctly, the game displays a congratulatory message along with the number of attempts taken.
Game Over Messages: If the player exceeds 10 attempts or exits early, an appropriate game-over message is displayed.

How it Works:
The game uses Python’s random.randint() to generate the secret number.
A while loop runs until the player guesses correctly or exits.
Each guess increments a counter to track the number of attempts.
Conditional checks determine if the player has exited, exceeded attempts, or guessed correctly, and displays messages accordingly.

This simple game is a great exercise for beginners to practice loops, conditionals, input handling, and random number generation in Python.
