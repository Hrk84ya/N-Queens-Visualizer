# N-Queens Solver with GUI

##### NOTE: tkinter is a must for running this code

## Introduction
This project implements an N-Queens problem solver with a graphical user interface (GUI) using Python's tkinter library. The N-Queens problem involves placing N queens on an N×N chessboard such that no two queens threaten each other. The GUI allows visualization of solutions and navigation through them.

## Concept Used
The N-Queens problem is solved using a backtracking algorithm. The program generates all possible solutions and allows users to navigate through them using buttons or by clicking on the board.

## Technologies Used
- Python: Programming language used for implementation.
- tkinter: Python's standard GUI toolkit used for creating the graphical interface.
- Canvas: tkinter's Canvas widget is utilized for drawing the chessboard and queens.
- Buttons and Events: tkinter widgets used for navigation between solutions and resizing the board.

## Screenshots used
### Empty board
<img src="/images/Empty-Board.png" width="600">

### Solution-1
<img src="/images/Solution-1.png" width="600">

### Solution-2
<img src="/images/solution-2.png" width="600">

### Resizing the board
<img src="/images/resize.png" width="600">



## Analysis
The program generates solutions to the N-Queens problem using a recursive backtracking approach. It efficiently checks for safe positions for queens and stores all valid configurations. Users can visualize each solution on the GUI and navigate forward or backwards through them. Additionally, the board can be resized dynamically to change the number of queens.

## Contributing
Contributions to this repository are welcome! If you have a code sample or topic you'd like to contribute, please follow these steps:

- Fork the repository
- Create a new branch (git checkout -b feature/new-topic)
- Make your changes
- Commit your changes (git commit -am 'Add new topic')
- Push to the branch (git push origin feature/new-topic)
- Create a new Pull Request

Please ensure your code adheres to the repository's coding standards and includes appropriate documentation/comments.
