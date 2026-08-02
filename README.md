# hello-world

##This repository is for practicing the GitHub Flow.

     import random

     #Generate  random number between 1 and 67
    
     _number = random.randint(1, 67)

     #Set number of attempts
     attempts = 0

     # Intro 
      print("Welcome to my number guessibg game!😳🤯😶🥺❤️🤩😛😎🤓😾🥶🤤😇") 
      print("I'm thinking of a number between 1 and 67. Try to guess it😻😻😻")

     #Main game mechanic

     while True:
    #Get  person's guess
    try:
        guess = int(input("Plz enter your guess: "))
    except ValueError:
        print("Nah bro, enter a valid number.")
        continue

    #increase  number of attempts
    attempts += 1

    # check if  guess is correct
    if guess == _number:
        print("Congratulations! You guessed the number {_number} in {attempts} attempts :o")
        break
    elif guess < _number:
        print("Try guessing higher")
    else:
        print("Try guessing lower")
