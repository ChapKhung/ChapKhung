
def introduce_myself():
    name = "Your Name"
    age = 25
    profession = "Your Profession"
    
    introduction = f"Hello! My name is {name}. I am {age} years old and I work as a {profession}."
    return introduction

print(introduce_myself())

import random

def guess_the_number():
    number_to_guess = random.randint(1, 10)
    attempts = 0
    print("Guess the number between 1 and 10.")

    while True:
        try:
            guess = int(input("Enter your guess: "))
            attempts += 1
            if guess < number_to_guess:
                print("Too low! Try again.")
            elif guess > number_to_guess:
                print("Too high! Try again.")
            else:
                print(f"Congratulations! You've guessed the number in {attempts} attempts.")
                break
        except ValueError:
            print("Please enter a valid number.")

guess_the_number()
```
import random

def guess_the_number():
    number_to_guess = random.randint(1, 10)
    attempts = 0
    print("Guess the number between 1 and 10.")

    while True:
        try:
            guess = int(input("Enter your guess: "))
            attempts += 1
            if guess < number_to_guess:
                print("Too low! Try again.")
            elif guess > number_to_guess:
                print("Too high! Try again.")
            else:
                print(f"Congratulations! You've guessed the number in {attempts} attempts.")
                break
        except ValueError:
            print("Please enter a valid number.")

guess_the_number()
