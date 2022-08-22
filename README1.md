# Number-guessing-game
Number guessing game based on python language
n=19
number_of_guesses=1
print("Number of guesses is limited to only 10 times:")
while (number_of_guesses<=10):
    guess_number=int(input("Guess the number:\n"))
    if guess_number<19:
        print("You guess too low!")
    elif guess_number>19:
        print("You guess too high!")
    else:
        print("You win\n")
        print(number_of_guesses,"no of guesses took to finish the game")
        break
    print(10-number_of_guesses,"no. of guesses left")
    number_of_guesses= number_of_guesses+1

if(number_of_guesses>9):
    print("Game over")
