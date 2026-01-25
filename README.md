Rock-Paper-Scissors Game

A console-based Rock-Paper-Scissors game written in C++ where you can challenge the computer in multiple rounds.  
This project is a fun way to practice C++ programming, including enums, structs, functions, loops, and random number generation.

---

## Features

- Choose the number of rounds (1–10).
- Select your move each round:
  - Rock
  - Paper
  - Scissors

- Computer chooses randomly each round.
- Real-time results for each round (who won).
- Keeps track of:
  - Player wins
  - Computer wins
  - Draws

- Final game results with the overall winner.
- Colored console output for feedback:
  - Green for player win
  - Red for computer win
  - Yellow for draw

- Option to play again after each game.

---

## How It Works

1. The game asks how many rounds you want to play.
2. For each round:
   - You choose Rock, Paper, or Scissors.
   - The computer randomly selects its move.
   - The winner is determined and shown immediately.
3. At the end of all rounds:
   - Total scores are displayed.
   - The final winner is announced.
   - Option to play again.

---

## Input Validation

- The game validates all user inputs to prevent invalid entries.
- If the user enters a non-numeric value, the game clears the input buffer and asks again.
- If the user enters a number outside the allowed range, the game asks again.
- Validation is applied for:
  - Number of rounds (must be between 1 and 10)
  - Player choice (must be 1, 2, or 3)
  - Play again choice (must be Y or N)

---
