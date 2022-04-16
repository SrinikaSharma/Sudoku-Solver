Project Name : SUDOKU

Solve any Suduko puzzle using this solver GUI built using Python and Tkinter.
The code uses a backtracking algorithm to solve the puzzle.

Description:

- Sudoku, also known as Su Doku, popular form of number game.
- Sudoku consists of a 9 × 9 grid with numbers appearing in some of the squares. 
- The object of the puzzle is to fill the remaining squares, using all the numbers 1–9 exactly once in each row, column, and the nine 3 × 3 subgrids.

Rules:

1. Every square has to contain a single number.
2. The numbers from 1 to 9 can be used.
3. Each 3x3 box ,column,row can only contain a number from 1 to 9-No duplications allowed.

Approach:

- We used lists to take input from the user. Incase if the user enters the number which is out of range then it prompts to enter the valid number between the range.
- Next task is to solve the puzzle.We just defined a function in which we just perform the checking operations based on the rules of Sudoku puzzle i.e,row checking and column checking,3x3 grid checking-No Duplicates.
- Number will be assigned to the cell if all the above conditions are satisfied.

Running the Program:

- Begin by importing gui.py into your IDE of choice. 
- Then run the program and a window will appear.
- Input your chosen Sudoku puzzle into the cells of the window. 
- Leave any empty cells blank. 
- Then simply click "solve" to complete the puzzle or "clear" to clear the puzzle.
