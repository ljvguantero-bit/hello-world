# hello-world
This repository is for practicing the GitHub Flow.

hi=str(input("What is your name:) " ))

print("Hello,", hi,"Welcome to my number guessing game!")

print("I am thinking of a number from 1-67, can you guess it?")

while True:
    guess=input("Enter your guess:").strip()
    
     if not user_input.isdigit():
            print("Please enter a valid whole number.")
            continue
