This Script is a Sudoku Solver that solves almost any Sudoku Puzzle by visualizing through the Backtracking Algorithm which is made using the PyGame Library in Python. Ever tried but stucked on Sudoku Puzzles given in newspapers, magazines and online. You can use this script to get its solution instantly and move further.

## Working:

-	Every time this Script is executed, a Random Solvable board is created.
-	Now, the user can first try to attempt solving it by clicking on the cells and entering values manually. Check the Input Section for the same.
-	Once the the user finalizes that the inputted number is the correct entry, pressing the enter key will attempt to input the number onto the board. 
-	Correct answers will be permanently displayed while incorrect answers will be removed. 
-	Likewise, values can be removed by pressing on the backspace or delete keys.

## Input:

| Keys              | Actions                                                         |
|-------------------|-----------------------------------------------------------------|
| `Left Click`      | Selects the Box to enter a value into that cell.                |
| `Enter`           | Confirms the Value written on the board.     |
| `Backspace/Delete`| Deletes the value in that cell.                                 |
| `Space`           | Solves the Board using the Algorithm.                           |
| `h`               | Gives a Hint. Displays a random correct value on the board.     |

## Requirements:
In order to run the Script, the require **Python & PyGame** and you can install the requirements using:
```
pip install -r requirements.txt
```

## Execution:
-	Clone this repository using
```
git clone https://github.com/dhhruv/Sudoku-Solver.git
```
**OR**
Zip Download the Repository and Extract it's contents.
-	Now run the [SudokuGUI](https://github.com/dhhruv/Sudoku-Solver/blob/master/SudokuGUI.py) file directly in your Terminal using
```
python SudokuGUI.py
```
**OR**
```
python3 SudokuGUI.py
```

