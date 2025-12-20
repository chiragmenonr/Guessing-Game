# Number Guessing Game (Python)

## Description

This is a simple Python number guessing game. The program randomly selects a number between **0 and 100**, and the player must guess the number. After each guess, the program tells the player whether their guess is **too high** or **too low** until the correct number is guessed. The game also tracks how many attempts the user makes.

## How It Works

1. A random number between 0 and 100 is generated.
2. The user enters a guess.
3. The program compares the guess to the target number:

   * If the guess is too high, the user is notified.
   * If the guess is too low, the user is notified.
4. The user keeps guessing until the correct number is entered.
5. The program displays the total number of tries.

## Program Flowchart

The following diagram visually represents the decision-making process used in the program:

![Number Guessing Game Flowchart](NumberGuessingGameFlowchart.png)

## Requirements

* Python 3.x
* Uses Python’s built-in `random` module

## How to Run

1. Ensure Python is installed.
2. Save the code as `guessing_game.py`.
3. Open a terminal or command prompt.
4. Run:

   ```bash
   python guessing_game.py
   ```
5. Follow the prompts to play.

## Example Output

```
I'm thinking of a number between 0 and 100
Enter your guess of my number here: 45
Sorry, 45 is less than my number.
Enter your guess of my number here: 72
Sorry, 72 is greater than my number.
Enter your guess of my number here: 60
You guessed my number! It only took you 3 tries.
```

## Concepts Used

* Variables
* While loops
* Conditional statements (`if`, `elif`)
* User input
* Random number generation
* Flowchart-based algorithm visualization
