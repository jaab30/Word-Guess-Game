# Word-Guess-Game


This is a game of Hangman. The user will try to guess the names of a few rock bands from all times.

This is just a beginner's assignment that is useful when starting to learn Javascript.

The computer picks a random word from an array of ten bands. In this project, I decided not to pick them at random so that the bands don't repeat since there are only 10 bands. But the code for the random choice is still in the code as a comment. Then, a for loop generate the dashes for the letter. The user then starts entering letters using the keyboard.
The game calculates the "Wins" (when the word is guessed correctly), "Guesses remaining" (the user has 12 guesses available before losing the game) and "Letters Guessed" (show the letters already typed by the user).

I made a for loop to be able to check for the answers by checking for the position of the character method charAt().

When the user guesses the correct band, a picture of the band comes up and a song from the band start to play. Also, text with the band name and the name of the song is inserted below the band picture.

When user missed 12 times, user gets an alert to re-start the game or quit.

When user guess all 10 bands correctly, user gets an alert to re-start the game or quit.

Enjoy...!


