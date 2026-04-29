# Web Tic Tac Toe

A simple two-player Tic Tac Toe game that runs in the browser — no dependencies, no build step.

## Demo

Open `index.html` in any modern browser to play.

## How to Play

1. Player **X** always goes first.
2. Click any empty cell to place your mark.
3. The first player to get three in a row (horizontally, vertically, or diagonally) wins.
4. If all nine cells are filled with no winner, the game ends in a draw.
5. Click **Restart** to start a new round. Scores persist across rounds until the page is refreshed.

## Features

- Two-player local multiplayer (X vs O)
- Win detection for all rows, columns, and diagonals
- Draw detection
- Score tracking (X wins / Draws / O wins)
- Win highlight animation
- Clean dark UI — no frameworks or dependencies

## Project Structure

```
web-ttt-test/
└── index.html   # Entire game: HTML, CSS, and JavaScript in one file
```

## Running Locally

No server required — just open the file directly:

```bash
open index.html
```

Or serve it with any static file server:

```bash
npx serve .
# or
python3 -m http.server
```
