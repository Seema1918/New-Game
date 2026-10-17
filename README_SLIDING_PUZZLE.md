# Slide Shift

A standalone sliding tile puzzle built with HTML, CSS, and JavaScript. Open `sliding-puzzle.html` directly in a modern web browser to play. No installation, server, or external dependencies are required.

## How to Play

Arrange the numbered tiles in ascending order, leaving the empty space at the bottom-right. Only a tile next to the empty space can move.

- Click or tap a neighboring tile to slide it.
- Focus the board and use the arrow keys to move tiles.
- Choose a 3 x 3, 4 x 4, or 5 x 5 board.
- Use **Undo** to reverse the last move, **Restart** to reset the current shuffle, or **New puzzle** for a fresh board.

## Features

- Every shuffled board is generated through legal moves, so it is solvable.
- Move counter and timer.
- Best move count saved separately for each board size.
- Dark and light themes, with the selected theme saved in the browser.
- Responsive layout and keyboard-accessible controls.
- Game data is stored locally in the browser; no account or network connection is needed.

## Run Locally

Open `sliding-puzzle.html` in your browser. Alternatively, from the project directory, start a local server:

```bash
python -m http.server 8000
```

Then visit <http://localhost:8000/sliding-puzzle.html>.