# 🚀Day 7/100: Hangman Game 🎮

Today, I tackled a fundamental project that combines logic, user interaction, and fun: The Hangman Game! 
Here’s a behind-the-scenes look at how it was built and the skills I applied along the way.

🎗️How It Works

♦️A random word is selected from a predefined word list using Python’s random module.

♦️Players guess the word one letter at a time, with incorrect guesses costing them one of their six lives.

♦️The game tracks correctly guessed letters, previously guessed letters, and updates the display dynamically.

♦️The game ends when the player either guesses the entire word or loses all their lives.

📚Key Concepts and Techniques Used

1. String Manipulation  
Strings are central to the game:
A placeholder (e.g., "____") represents the unguessed letters.
Each correct guess replaces underscores with the corresponding letter(s).
I used loops to check each letter in the chosen word and update the display.
3. Loops and Conditionals
The game runs in a loop until the player wins or loses.
Conditional checks (if, elif, else) determine the game flow:
Is the guessed letter correct?
Has the player guessed the letter before?
Is the game over due to lives running out or all letters being guessed?
4. Managing State
Keeping track of the game state was essential:
A correct_letters list stored the letters already guessed correctly.
A lives counter reduced with each incorrect guess.
A game_over boolean controlled the loop termination.
5. Modularity and Imports
To make the code more modular and reusable:
The word list was imported from hangman_words.py.
ASCII art for the game was imported from hangman_art.py for visual flair.

