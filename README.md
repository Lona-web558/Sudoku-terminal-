# Sudoku-terminal-

# sudoku:// terminal

A 9×9 constraint grid — no repeats, no shortcuts.

**Live:** https://lonalonakie.neocities.org/Sudoku

## Overview

`sudoku:// terminal` is a single-file, browser-based sudoku solver/player built with a terminal-inspired interface (`~/sudoku/board.grid`). It generates puzzles across four difficulty levels and tracks time, mistakes, and progress in real time.

## Features

- 🧩 **9×9 puzzle grid** with standard sudoku constraint rules
- 🎚 **Four difficulty levels** — Easy, Medium, Hard, Expert
- ⏱ **Live timer** tracking solve time
- ❌ **Mistake tracking** (0/3 limit)
- ✏️ **Notes mode** — pencil-mark candidate numbers per cell
- 💡 **Hint system** — reveal a cell when stuck
- ↩ **Undo** and **Erase** controls
- 🔄 **Generate new puzzle** on demand
- ✅ **Completion screen** — shows final time and mistake count on clear

## Tech Stack

- HTML5 / CSS3 / vanilla JavaScript
- Client-side puzzle generation and validation logic
- No backend, no database — fully self-contained

## Design

Terminal/command-line aesthetic (`board.grid`, `sudoku://solve` styling) with dark theme, monospace typography, and gold/cyan accents consistent with the rest of the portfolio.

## Status

Live and functional. Single-page, single-file architecture — no build step required.

## Author

Built by Lona Matshingana (Lona Smith), Johannesburg, South Africa — part of the Gold Fundamentals Lab portfolio.

---
© 2026
