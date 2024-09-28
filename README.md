# Tic-Tac-Toe-Challenge

This is a simple console-based Tic-Tac-Toe game implemented in Java. Two players take turns to mark a 3x3 grid with 'X' or 'O', and the first to get three in a row wins.

## Features
- Play as Player X or Player O.
- Input your move by specifying the row and column number.
- The game automatically checks for a win or a draw.

## How to Play
1. The game starts with Player X.
2. Players take turns entering their move. You will be prompted to enter the row and column where you'd like to place your mark (X or O).
3. A valid move consists of selecting an empty spot on the 3x3 grid.
4. The game checks for a winner after every move. If no one wins and the board is full, the game ends in a draw.

## Example Gameplay
```
Player X, enter your move (row [1-3] and column [1-3]): 1 1
X - -
- - -
- - -

Player O, enter your move (row [1-3] and column [1-3]): 2 2
X - -
- O -
- - -

... (and so on)

Player X wins!
```

## Requirements
- Java Development Kit (JDK) 8 or higher
- You must have Java installed on your system. You can download it from [here](https://www.oracle.com/java/technologies/javase-downloads.html).
- A terminal or IDE to run the Java program

## Running the Program
1. Save the code in a file named `TicTacToe.java`.
2. Open a terminal and navigate to the directory where the file is saved.
3. Compile the program using the following command:
   ```
   javac TicTacToe.java
   ```
4. Run the compiled program:
   ```
   java TicTacToe
   ```

## License
This project is licensed under the MIT License.
