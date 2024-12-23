# README for Rock-Paper-Scissors Showdown

**Rock-Paper-Scissors Showdown** is a simple Python program that brings the classic game of Rock, Paper, Scissors to your computer. Play against the computer, test your strategy, and see if you can win!

---

## Features
- Allows users to select their move: Rock, Paper, or Scissors.
- The computer randomly selects its move.
- Displays the computer’s choice and determines the result (Win, Lose, or Draw).
- A fun and interactive way to play Rock, Paper, Scissors!

---

## How to Play

1. **Run the Program**:
   Execute the script in your Python environment.

2. **Choose Your Move**:
   - Enter `0` for Rock.
   - Enter `1` for Paper.
   - Enter `2` for Scissors.

3. **Computer's Turn**:
   The computer will randomly select one of the three options.

4. **View the Result**:
   The program will compare your choice with the computer's and display:
   - "You Win!" if you beat the computer.
   - "You Lose!" if the computer beats you.
   - "It's a Draw!" if both make the same choice.

---

## Example Run

- **User Input**: `0` (Rock)  
- **Computer Output**: `2` (Scissors)  
- **Result**: "You Win!"

---

## Prerequisites
- Python 3 installed on your system.
- The `random` module is used, which is part of Python's standard library.

---

## Code Logic
- **Input Validation**: Accepts user input (0, 1, or 2).
- **Random Choice**: Uses `random.randint(0, 2)` to simulate the computer's move.
- **Game Rules**:
  - Rock (0) beats Scissors (2).
  - Paper (1) beats Rock (0).
  - Scissors (2) beats Paper (1).
- Compares the user’s choice with the computer’s choice to decide the winner.

---

## Notes
- Enter a valid number (0, 1, or 2). Invalid inputs may cause the program to crash or behave unexpectedly.
- Feel free to enhance the game by adding more features like replay options or a scoring system.

---

Enjoy playing **Rock-Paper-Scissors Showdown** and see how often you can beat the computer!
