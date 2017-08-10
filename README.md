# Hangman-Game 
Hangman game in JavaScript


This is the classic Hangman game where the player is given
a word and has 12 chances to guess the word one letter at a 
time.

### Game Interface

Blank spaces are displayed on the screen equal to the length of the word chosen randomly from a list. Player can guess a letter by pressing a keyboard key. If the letter is
present in the word, the blank spaces are replaced with the letter at the right position. If the letter occurs more than once in the word, each occurence of the letter is replaced for a correct guess.

A letter can be guessed only once and for each wrong guess, the chances are decreased by 1 and hangman image is drawn on the canvas part by part till all the twelve chances are used up.

A new word is chosen after a successful game or after 12 guesses are up. Also, the player can choose a new word using the Next Word button.