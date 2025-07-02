import random 

num = random.randrange(0, 101) # Assigning a variable for a ramdom number from 0 to 100
tries = 0 # Assigning a variable for the number of tries someone takes
print("I'm thinking of a number between 0 and 100")
guess = int(input("Enter your guess of my number here: "))


while guess != num: # Making a while loop that runs when the guess is not equal to the actual number

    if guess > num: # If the guess is greater than the actual number,
        tries += 1 # then add 1 to the number of tries taken,
        print("Sorry, " + str(guess) + " is greater than my number.") # tell that the guess was greater than the goal,
        guess = int(input("Enter your guess of my number here: ")) # and allow the user to have another chance

    elif guess < num: # Otherwise, if the guess is less than the actual number,
        tries += 1 # then add 1 to the number of tries taken,
        print("Sorry, " + str(guess) + " is less than my number.") # tell that the guess was less than the goal,
        guess = int(input("Enter your guess of my number here: ")) # and allow the user to have another chance

if guess == num: # If the guess is correct,
    tries += 1 # then add 1 to the number of tries taken
    print("You guessed my number! It only took you " + str(tries) + " tries.") # and congradulate the user, ending the game
