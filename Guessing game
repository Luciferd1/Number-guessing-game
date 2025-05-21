
import random

low = 1
high = 100
ans = random.randint(low, high)
guesses = 0
is_active = True

print("---------------------------------------------")
print("   Welcome To The Number Guessing Game!!!    ")
print("---------------------------------------------")

print(f"Select a number between {low} and {high}")

while is_active:
    guess = input("Enter your guess: ")

    if guess.isdigit():
        guess = int(guess)
        guesses += 1

        if guess < low or guess > high:
            print("That Number Is Out Of Range")
            print(f"Please Select a number between {low} and {high}")

        elif guess < ans:
            print("Too low!, Try again")
        elif guess > ans:
            print("Too High!, Try again")

        else:
            print(f"Correct the answer was {ans}")
            print(f"Number of guesses: {guesses}")
            is_active = False
    else:
        print("Invalid Guess")
        print(f"Please Select a number between {low} and {high}")
