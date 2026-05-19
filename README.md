# CodeAlpha_HangmanGame
A simple text-based Hangman Game developed using Python for the CodeAlpha Internship. The player guesses a hidden word letter by letter with only 6 attempts. This project demonstrates Python basics like loops, conditions, lists, strings, random module, and user input handling in a fun interactive way.


## Sample Run
```bash
===================================
     WELCOME TO HANGMAN GAME
===================================

Current Word :  _ _ _ _ _ _
Guessed Letters : []
Remaining Attempts : 6

Enter a letter : p
Correct Guess!

Current Word :  p _ _ _ _ _
Guessed Letters : ['p']
Remaining Attempts : 6

Enter a letter : y
Correct Guess!

Current Word :  p y _ _ _ _
Guessed Letters : ['p', 'y']
Remaining Attempts : 6

Enter a letter : z
Wrong Guess!

Current Word :  p y _ _ _ _
Guessed Letters : ['p', 'y', 'z']
Remaining Attempts : 5

Enter a letter : t
Correct Guess!

Current Word :  p y t _ _ _
Guessed Letters : ['p', 'y', 'z', 't']
Remaining Attempts : 5

Enter a letter : h
Correct Guess!

Enter a letter : o
Correct Guess!

Enter a letter : n
Correct Guess!

===================================
Congratulations! You Won!
The word was : python
===================================
