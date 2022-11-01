# Hangman
## Description
This program is written in ruby.

Hangman is a guessing game for one player. Program thinks of a word and the player tries to guess it by suggesting letters within a certain number of guesses.
## Launching
To run the program, enter this command into your console.
```
ruby hangman.rb
```
## Game Rules
Each time the program is run, the algorithm selects a random word from the list.

After starting the program, you will see an interface where at the top, after the greeting, there are `__` signs indicating the number of letters in the hidden word.
During the game `__` signs will be filled with guessed letters.
Below you will see an image showing the current progress of the game.
At the bottom are displayed the letters that were entered and are not part of the hidden word (mistakes), as well as the number of remaining errors.
As soon as the number of allowed errors reaches zero, the game will be over.

The player sequentially enters the letters that he considers part of the hidden word.
If they are, then the letters are displayed in their places within the word. If not, they are written to errors.
## Adding hidden words
To add a word, find the **data** folder and there the **words.txt** file.

Enter your word on a new line in the **words.txt** file. Each word requires a separate line. Save the file.

Your word has been added and will be used in the program on an equal basis with other words.
