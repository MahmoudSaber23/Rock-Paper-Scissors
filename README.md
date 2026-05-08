# Rock-Paper-Scissors Game

A console-based Rock-Paper-Scissors game written in C++ where you can challenge the computer in multiple rounds.  
This project is a practical way to strengthen core C++ concepts such as enums, structs, functions, loops, input validation, and random number generation.

---

## Features

- Choose the number of rounds (1–100).
- Select your move each round:
  - Rock
  - Paper
  - Scissors

- Computer chooses randomly each round.
- Real-time round results showing:
  - Player choice
  - Computer choice
  - Round winner

- Automatic tracking of:
  - Player wins
  - Computer wins
  - Draws

- Final game summary including:
  - Total rounds played
  - Total wins for player and computer
  - Number of draws
  - Overall game winner

- Colored console feedback for better user experience:
  - Green for player win
  - Red for computer win
  - Yellow for draw
  - Default screen reset before each new game

- Sound alert when the computer wins.

- Option to replay the game after each session.

---

## How It Works

1. The game asks how many rounds you want to play (from 1 to 100).
2. For each round:
   - You choose Rock, Paper, or Scissors.
   - The computer randomly selects its move.
   - The winner of the round is determined immediately.
   - Round details are displayed on the screen.
3. After all rounds are completed:
   - Final game statistics are displayed.
   - The overall winner is announced.
   - You can choose to play again or exit.

---

## Input Validation

The game validates all user inputs to prevent invalid entries and unexpected behavior.

### Validation includes:

- Number of rounds:
  - Must be a numeric value
  - Must be between 1 and 100

- Player choice:
  - Must be a numeric value
  - Must be 1, 2, or 3

- Play again option:
  - Must be either `Y` or `N`

### Validation behavior:

- If the user enters invalid input (such as letters instead of numbers),
  the program clears the input buffer using:

```cpp
cin.clear();
cin.ignore(numeric_limits<streamsize>::max(), '\n');
