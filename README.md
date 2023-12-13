# Minesweeper

Welcome to Minesweeper, a classic game built in Python using Pygame.

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Getting Started](#getting-started)
- [How to Play](#how-to-play)

## Description

Minesweeper is a popular single-player puzzle game where the objective is to clear a rectangular board containing hidden "mines" or bombs without detonating any of them. The player must reveal the locations of safe cells by flagging or opening them. The game is won when all safe cells are uncovered, and it is lost if a mine is revealed.

## Features

- **Dynamic Board Creation:** The game dynamically generates a Minesweeper board with customizable dimensions and a specified mine probability.
- **Pygame Graphics:** Utilizes Pygame for a graphical user interface, providing an interactive and visually appealing gaming experience.
- **User Interaction:** Players can click on cells to reveal them and flag potential mine locations.
- **Game State Management:** Keeps track of the game state, including the number of mines, revealed cells, and flagged cells.
- **Win/Lose Conditions:** Implements win and lose conditions, ending the game when all safe cells are revealed or a mine is detonated.

## Getting Started

Follow these instructions to get the Minesweeper game up and running on your local machine.

### Prerequisites

- Python installed on your machine
- Pygame library installed (you can install it using `pip install pygame`)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/minesweeper.git

2. Navigate to the project directory:
   ```bash
   cd minesweeper

3. Run the game:
   ```bash
   python main.py

### How to Play

- Left-click to reveal a cell.
- Right-click to flag a potential mine.
- The numbers on revealed cells indicate the number of adjacent mines.
- Reveal all safe cells without detonating any mines to win the game.
