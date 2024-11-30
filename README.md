# Yahtzee.c
Implementing a Two-Player Yahtzee Game in C programming

_____**How to Play the Game**_____

**Clone the Repository** 

Download or clone the repository and extract the ZIP file to your desired location.

**Run the Game**

Compile and run the .c file using your preferred C development environment.

**System Requirements**

The game can run on any operating system with a functional C compiler.

**What is Yahtzee?**

Yahtzee is a classic dice game where players aim to score points by rolling five dice to achieve specific combinations. The game consists of 13 rounds, with players rolling the dice up to three times per round. After each roll, players decide which dice to keep and which to re-roll.

**Scoring Categories**

Ones, Twos, Threes, Fours, Fives, Sixes: Sum of dice showing the chosen number.
Three of a Kind: Sum of all dice if at least three are the same.
Four of a Kind: Sum of all dice if at least four are the same.
Full House: 25 points for three of one number and two of another.
Small Straight: 30 points for four consecutive numbers.
Large Straight: 40 points for five consecutive numbers.
Yahtzee: 50 points for five dice showing the same number.
Chance: Sum of all dice, regardless of combination.
Game Setup

The game is played over 13 rounds.
Both the human player and computer opponent take turns rolling five dice.
Players can roll the dice up to three times per turn, choosing which dice to keep or re-roll.
Game Flow

At the start of each round, both players roll their dice.
The human player chooses which dice to re-roll.
The computer uses an optimal strategy to decide which dice to re-roll.
After the third roll (or when players decide to stop re-rolling), the scores are calculated based on the selected category.
Winning the Game
After 13 rounds, the player with the highest total score wins.

**Enjoy the game, and may the best player win!**

