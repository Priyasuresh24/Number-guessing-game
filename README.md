Number Guessing Game
Overview
This is a simple Python-based number guessing game where the computer randomly selects a number between 1 and 100, and the player attempts to guess it. The game provides feedback on whether the guess is too high, too low, or correct. The number of attempts is tracked, and the game ends when the player correctly guesses the number.

How It Works
Generate a Random Number:

The program selects a random number between 1 and 100 using random.randint(1, 100).

Player Makes Guesses:

The player enters a guess through the console.

The program checks if the input is a valid number; otherwise, it asks the player to try again.

Game Logic:

If the guess is too low, the program prints "Too low!".

If the guess is too high, it prints "Too high!".

If the guess is correct, the program congratulates the player and displays the number of attempts taken.

Loop Until Correct Guess:

The game runs in a loop (while True), ensuring the player keeps guessing until they find the correct number.

Key Concepts Demonstrated
✅ Random Number Generation – Uses Python’s random module to generate unpredictable numbers.
✅ User Input Handling – Reads user input with input() and ensures valid number entry with try-except for error handling.
✅ Conditional Statements – Uses if-elif-else to provide hints based on the guess.
✅ Loops – A while loop ensures continuous gameplay until the correct guess is made.

Why This is a Great Beginner Project
Simple yet engaging – Encourages logical thinking and interaction.

Covers Python fundamentals – Control structures, error handling, loops, and functions.

Easy to expand – Can be modified to add difficulty levels, scoring, or a graphical user interface.
