# PRODIGY_SD_02
Welcome to the Guessing Game! This is a simple, interactive game where the player attempts to guess a randomly generated number within a specified range. Here's how it works:

Game Setup: The game begins by selecting a random number between a minimum and maximum value (e.g., 1 and 100).
Player Input: The player is prompted to guess the number.
Feedback: After each guess, the game provides feedback:
"Too high!" if the guess is greater than the number.
"Too low!" if the guess is less than the number.
"Congratulations!" if the guess is correct.
Repeat: The game continues until the player guesses the correct number.
End Game: Once the correct number is guessed, the game announces the number of attempts taken and offers the player an option to play again.
This game is a fun way to practice basic programming concepts such as loops, conditionals, and user input in Python.

#Guessing game in python
import random

number=random.randint(1,100)
guess=0

while guess!=number:

    guess=int(input("Enter the guesss:"))

    if(guess<number):
        print("guess higher!")
    elif(guess>number):
        print("guess lower!")
    else:
        print("Congratulations you won!")

