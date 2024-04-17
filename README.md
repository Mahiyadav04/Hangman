# Hangman Game


Introduction:
The Hangman Game is a classic word guessing game where players attempt to guess a word by suggesting letters within a limited number of guesses. Each incorrect guess results in a part of a hangman being drawn. The objective is to guess the word correctly before the hangman is fully drawn.

Project Overview:
In this Python project, we'll create a text-based Hangman game. The game will randomly select a word from a predefined list, and the player will have to guess letters to uncover the word. For each incorrect guess, a part of the hangman will be drawn, and the player will lose a life. The game ends when the player correctly guesses the word or runs out of lives.

Features:

Random word selection: The game selects a word randomly from a list of words.
Display: The game displays the current progress of the guessed word, showing blanks for unguessed letters.
Input validation: The game validates user inputs to ensure they are single letters.
Lives system: The player starts with a certain number of lives, typically six. Incorrect guesses result in the loss of a life.
End of game detection: The game detects when the player wins by correctly guessing the word or loses by running out of lives.
Visual representation: The game visually represents the hangman's progress, updating with each incorrect guess.
Error handling: The game handles errors gracefully, providing feedback to the player for invalid inputs.
Project Structure:

hangman.py: Main Python script containing the Hangman game logic.
hangman_words.py: Python file containing a list of words for the game to choose from.
hangman_art.py: Python file containing ASCII art for the hangman stages.
Instructions for Playing:

Run the hangman.py script in a Python environment.
The game will display the Hangman logo and prompt you to guess a letter.
Enter a letter and press Enter.
Continue guessing letters until you either guess the word correctly or run out of lives.
The game will provide feedback for each guess and update the hangman visual accordingly.
If you win, the game will congratulate you. If you lose, it will reveal the correct word.
Conclusion:
The Hangman game project provides an entertaining way to practice Python programming skills while implementing fundamental concepts such as randomization, string manipulation, loops, conditionals, and input validation. Players can enjoy the challenge of guessing words while experiencing the classic Hangman gameplay.
