# Hangman Project

Purpose of this project is to make a Hangman Game. The game will be CLI (command line interface) based.
The game will require that the file "dictionary.txt" be accessed to randomly select a word when a new game is started.
Below are some requirements that the project must satisfy (not in order).

* Access, read, and write to "dictionary.txt" file
* On program run, populate from "dictionary.txt" a data structure that can be randomly accessed.
* Accept and filter user input (no numbers, capital and lowercase letters are different but generally don't play a role in a hangman game)
* Keep track of wrong letters and if the user tries to use it again, inform that that letter has been played already
* Properly handle words that use the same letter more than once.
* Give the user the opportunity to guess the word without modifying the flow of the game
  * For example, the user must be able to enter "a", "x", and "y" as letters to play and the words that are guessed the same way.
* Give the user a visual representation of the status of the game. Representing the 
  * \________
  * \_l_____t
  * el\______
* Upon winning a game, produce an animation of the word using its letters.
  * C
  * CA
  * CAT
  * CA
  * C
* The game must have a menu.
  * 1 for new game
  * 2 for changing the "dictionary.txt" file
    * The user fed "dictionary.txt" must be appendable but not the default file.
    * Handle wrong filetypes gracefully - if the user feeds an .mp3, the program must inform that file type is not acceptable and ask again
    or if left blank, revert to the built-in file.
  * 3 Quit Program

## Clone Project

From the Intellij project manager splash page, clone project from VCS (version control system). 
This may require that you enter your credentials.