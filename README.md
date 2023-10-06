import random

x = random.randint(1,10)
guess_left = 3
guess_count = 0
while guess_count <=guess_left:
    guess_count +=1
    guesses = int(input("Guest the secret number: "))
    if x == guesses:
        print("Yehey you got it right", x)
    elif x > guesses:
        print("Lower your almost there")
    elif x < guesses:
        print("Higher Your almost there")
