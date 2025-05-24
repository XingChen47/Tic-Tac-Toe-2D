# Tic Tac Toe (2D)

A C++ console implementation of the classic Tic Tac Toe game using a 3x3 grid (2D array). Play as "X" against the computer ("O") right in your terminal. The game displays the board after each move and will announce wins, ties, and end the game accordingly. Works on Linux, Windows, and macOS.

## Features

- Play as "X" against a computer opponent "O"
- Board displayed in an easy-to-read 3x3 grid format
- Input coordinates for your moves (row and column)
- Detects wins and ties automatically
- Simple command line interface
- Cross-platform: works on Linux, Windows, and macOS

## Installation

### 1. Clone the repository
```sh
git clone https://github.com/XingChen47/Tic-Tac-Toe-2D.git
cd Tic-Tac-Toe-2D
```

### 2. Compile the program

#### **Linux/macOS**
```sh
g++ -o tictactoe2d "Tic Tac Toe (2D) .cpp"
```

#### **Windows (using MinGW)**
```sh
g++ -o tictactoe2d.exe "Tic Tac Toe (2D) .cpp"
```
*Make sure `g++` is available in your PATH.*

## Usage

Run the compiled program from your terminal:

**Linux/macOS:**
```sh
./tictactoe2d
```

**Windows:**
```sh
tictactoe2d.exe
```

You will be prompted to enter a row and column (1-3) for your move. The computer will make a random move after yours. The board is displayed after every move. The game ends when someone wins or the board is full (tie).

**Example Output:**
```
WELCOME TO TIC-TAC-TOE!
-------------
|   |   |   | 
-------------
|   |   |   | 
-------------
|   |   |   | 
-------------
Enter a coordinate where you wish to place your marker
Row(1-3): 
2
Column(1-3): 
2
-------------
|   |   |   | 
-------------
|   | X |   | 
-------------
|   |   |   | 
-------------
...
YOU WIN!
THANKS FOR PLAYING!
```

## Customization

You can modify or extend the logic, board size, or victory messages by editing the source code.
