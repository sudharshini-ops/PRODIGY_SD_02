# PRODIGY_SD_02
Creating a Guessing Game

#Guessing game in python
import random

number=random.randint(1,10)
guess=0

while guess!=number:

    guess=int(input("Enter the guesss:"))

    if(guess<number):
        print("guess higher!")
    elif(guess>number):
        print("guess lower!")
    else:
        print("you won!")

