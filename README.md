Props are used to pass data from a parent component to a child component. In the Tic-Tac-Toe app:

The App component passes the current state of the board and a function to handle square clicks as props to the Board component.

The Board component passes the value of each square (X, O, or null) and a function to handle clicks as props to each Square component.

An array representing the current state of the grid.

This state is managed in the App component and passed down to the Board and Square components as props.

Current Player:

A boolean or string indicating whose turn it is (X or O).

This state is toggled after each move.

Winner:

A string or boolean indicating if there’s a winner (X, O, or null for no winner yet).

This state is updated after each move by checking the board for a winning combination.
